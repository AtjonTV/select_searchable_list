# Dropdown Searchable List Choices
A very useful widget for searching through single or multiple options from a drop-down list.

# Platforms
This plugin has been successfully tested on iOS, Android & web.

# Examples
The following examples are extracted from the example project available in the repository. More examples are available in this project.

# Demo of Dropdown Searchable list with choices

![drop-down-list](https://github.com/AmirHome/select_searchable_list/blob/main/assets/demo_select_searchable_list.gif)

# How to Use
```
          // ####### Category Select List
          DropDownTextField(
            textEditingController: _categoryTextEditingController,
            title: 'Category',
            hint: 'Select Category',
            options: _listCategories,
            selectedOptions: _selectedCategory,
            onChanged: (selectedIds) {
              // setState(() => selectedIds);
            },
          ),

          // ####### Colors Select List
          DropDownTextField(
            textEditingController: _colorsTextEditingController,
            title: 'Colors',
            hint: 'Select Colors',
            options: _listColors,
            selectedOptions: _selectedColors,
            onChanged: (selectedIds) {
              // setState(() => selectedIds);
            },
            multiple: true,
          ),
```

### Required parameters

##### data:
This property takes List<SelectedListItem> as a parameter and it is useful to display items in drop down list.

### Optional parameters

##### listBuilder:
This property takes int value as a parameter. This is use to set the initial segment from [segmentNames].

##### enableMultipleSelection:
This property takes Color value as a parameter. You can change the background color of animated segment. default value is `Color(0xff8AADFB)`

##### bottomSheetTitle:
This gives the bottom sheet title.

##### submitButtonChild:
You can set your custom submit button when the multiple selection is enabled.

##### selectedItems:
This will give the call back to the selected items from list.

##### dropDownBackgroundColor:
This will set the background color to the Dropdown Searchable.

##### searchWidget:
This property takes TextFormField value as a parameter. [searchWidget] is use to show the text box for the searching. If you are passing your own widget then you must have to add [TextEditingController] for the [TextFormField].

##### isSearchVisible:
This property takes bool value as a parameter. [isSearchVisible] is use to manage the search widget visibility. by default it is [True] so widget will be visible.


# LICENSE!

Dropdown Searchable list is [MIT-licensed](https://github.com/AmirHome/select_searchable_list/LICENSE "MIT-licensed").

# Let us know!

I would be happy if you send us feedback on your projects where you use our component. Just email amir.email@gmail.com  and let me know if you have any questions or suggestions about my work.