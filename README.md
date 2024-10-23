# yClipboardText

A LiveCode Builder library for working with the clipboard on Android.

## Description

This LiveCode Builder library provides a set of functions for interacting with
the clipboard on Android devices. You can easily get, set, and clear clipboard
text using the following functions:

| name | type | parameters | value | description |
| :--- | :---: | :--- | :--- | :--- |
| **hasClipboardText** | function | - | `boolean` | Checks if there is any text currently on the clipboard. |
| **clearPrimaryClip** | command | - | - | Clears all data from the clipboard. |
| **getClipboardText** | function | - | `string` | Retrieves the text currently stored on the clipboard. |
| **setClipboardText** | command |  `string` | - | Stores the specified text on the clipboard. |

## LICENSE

This library is licensed under the `GPL-3.0 license`.
For more information read the [LICENSE](LICENSE) file
