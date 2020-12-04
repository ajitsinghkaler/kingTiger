# Mat Menu

This component has 2 input parameters

items = All the items that are supplied to the component. These should be of the form  `{
  image: string;
  value: string;
}`

value = This is the selected value of menu. It should be one of the item from the items array otherwise there will a error in console and the first item in the items aarray will be selected.

Output Properties

addNew = It is triggered on click of New Account

selectionChange = It is triggered when a selection is changed in the menu. It outputs the value of the selected Item.

A basic working setup is shown in the AppComponent

