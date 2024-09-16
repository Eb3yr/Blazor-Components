# Blazor-Components
A repository of custom blazor components

## TriCheckbox
A checkbox that can hold an indeterminate value. Has several properties to get or set its state, including a nullable bool, int, enum or regular bool.

## GenericDropdown
A generic dropdown input with a generic SelectedOption param, IEnumerable Options to select from, and SelectedOptionChanged event callback. Can infer missing parameters with context, eg an enum type will set Options to Enum.Getvalues and SelectedOption to the first member of that enum. 
