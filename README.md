# Muse UI

English | [简体中文](./README.zh-CN.md)

> UI elements for **Flutter**

The current repository is created out of personal interest and my experience in front-end development, as a Flutter-based UI library project.

The goal of this project is to build a **practical**, **convenient**, and **simple** Flutter UI component library.

This aims to facilitate daily complex business development by focusing on business functionality and custom component development.

- [MuseUI Github](https://github.com/musetools/muse_ui)
- [MuseUI Pub.dev](https://pub.dev/packages/muse_ui)

- [Demo Github](https://github.com/musetools/muse_ui_demo/)

### [UI Widgets Preview](https://musetools.github.io/muse_ui_demo/)

  ![](http://oss.musetools.uk/pic/button1.png)
  ![](http://oss.musetools.uk/pic/button2.png)

## Getting started

### Install muse_ui

```bash
$ flutter pub add muse_ui
```

### Import it

```dart
import 'package:muse_ui/button/muse_button.dart';
import 'package:muse_ui/button/types.dart';
```

### Use

```dart
MuseButton(
  text: "Square",
  type: ButtonType.primary,
  borderType: ButtonBorderType.square,
  click: () => {},
)
```

## License

MIT
