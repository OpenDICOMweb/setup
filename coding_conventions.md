[**Open DICOMweb**](http://opendicomweb.org/home.html)
## Coding Conventions
---

The Open DICOMweb Project follows the recommendations in [Effective Dart]
including the guides for [Style], [Documentation], [Usage], and [Design].
It also follows the [Flutter] conventions.

### Constant Values

In the past we have followed the original Dart convention of making `const` names
all uppercase. Later we switch to a convention of prefixing `const` names with
`$`. Currently, we are following the convention of using the prefix "k" for
`const` names, which creates less ugly names. For example:

```
const int kVRLength = 2;
const int kStudyInstnaceUid = 0x002000D;
```

Any new code that is checked in should use this convention for constants.

#### Tag Values

All integer tag values should be written in hexadecimal.  For example,

```
const int kSpecificCharacterSet = 0x00080005;
```

```
TODO:
    1. Extend this list going forward.
```


[Effective Dart]: https://www.dartlang.org/effective-dart
[Style]: https://www.dartlang.org/effective-dart/style
[Documentation]: https://www.dartlang.org/effective-dart/documentation
[Usage]: https://www.dartlang.org/effective-dart/usage
[Design]: https://www.dartlang.org/effective-dart/design
[Flutter]: https://flutter.io/style-guide
