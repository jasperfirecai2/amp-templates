# Useful regexes

## paramfieldnames

Grab all fieldsnames in configs that don't have a paramfieldname right after it

```js
/^(?<front>.+)"(?<key>FieldName)":."(?<value>\$?\w+)",(?!\n.+"ParamFieldName")$/gm
```

Add a paramfieldname below it as the lowercase of the fieldname with this replace regex

```js
$&\n$1"Param$2": "\L$3",
```
