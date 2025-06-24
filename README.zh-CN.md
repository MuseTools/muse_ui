# Muse UI

简体中文 | [English](./README.md)

> 基于**Flutter**的 UI 组件库

这个项目是出于个人喜好和对前端的开发经验，创建了这个基于 flutter 的 UI 库项目。
项目目的是构建一套**实用**、**便捷**、**简单**的 flutter UI 组件库。
便于在日常繁杂的业务开发中，专注于业务功能和个性组件的开发。

- [MuseUI Github](https://github.com/musetools/muse_ui)
- [MuseUI Pub.dev](https://pub.dev/packages/muse_ui)

- [Demo Github](https://github.com/musetools/muse_ui_demo/)

### [UI组件预览](https://musetools.github.io/muse_ui_demo/)

  ![](http://oss.musetools.uk/pic/button1.png)
  ![](http://oss.musetools.uk/pic/button2.png)

## 使用说明

### 安装 muse_ui

```bash
$ flutter pub add muse_ui
```

### 导入组件及依赖

```dart
import 'package:muse_ui/button/muse_button.dart';
import 'package:muse_ui/button/types.dart';
```

### 使用组件

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
