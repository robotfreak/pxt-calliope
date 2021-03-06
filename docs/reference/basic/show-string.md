# Show String

Show a number on the [LED screen](/device/screen). It will slide left if it is bigger than the screen.

```sig
basic.showString("Hello!")
```

### Parameters

* `text` is a [String](/reference/types/string). It can contain letters, numbers, and punctuation.
* `interval` is an optional [Number](/reference/types/number). It means the number of milliseconds before sliding the [String](/reference/types/string) left by one LED each time. Bigger intervals make the sliding slower.

### Examples:

To show the word **Hello**:

```blocks
basic.showString("Hello")
```

To show what is stored in a [String](/reference/types/string) variable:

```blocks
let s = "Hi"
basic.showString(s)
```

### Other show functions

* Use [show number](/reference/basic/show-number) to show a number on the [LED screen](/device/screen).
* Use [show animation](/reference/basic/show-animation) to show a group of pictures on the screen, one after another.

### See also

[String](/reference/types/string), [show number](/reference/basic/show-number), [show animation](/reference/basic/show-animation)

