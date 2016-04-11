To save and restore data, when your `Activity` being recreated, you can use

`onSaveInstanceState()/onRestoreInstanceState()`

or config the android:configChanges to avoid recreate the `Activity`.

***Attention:***

The `TextView` overrides `onSaveInstanceState()/onRestoreInstanceState()`

so that `EditText` can save and restore data without overrides the methods,

but it must have an id.