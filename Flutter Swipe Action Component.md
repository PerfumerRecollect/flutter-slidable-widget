# 📱 Flutter Slidable Widget

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,13,28&height=210&section=header&text=Flutter%20Slidable%20Widget&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Swipe%20Left.%20Swipe%20Right.%20Delight.&descAlignY=56&descSize=19" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-4.0.2-FF5A5F?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Flutter](https://img.shields.io/badge/Flutter-3.22+-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev)
[![License](https://img.shields.io/badge/license-MIT-00A699?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Pub](https://img.shields.io/badge/pub.dev-popular-FFB400?style=for-the-badge&logo=dart&logoColor=black)](https://pub.dev)

<br/>

### ✨ A powerful, highly customizable slidable widget for Flutter

*🎯 Swipe Actions • 🎨 Beautiful Animations • 🔧 Fully Configurable • ⚡ 60 FPS*

<br/>

<a href="https://share.google/1xBSHkglxZqkV2K0s">
  <img src="https://img.shields.io/badge/📥_GET_PACKAGE-FF5A5F?style=for-the-badge&logo=dart&logoColor=white&labelColor=CC484C" alt="Get Package" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/1xBSHkglxZqkV2K0s">
  <img src="https://img.shields.io/badge/🚀_LIVE_DEMO-00A699?style=for-the-badge&logo=flutter&logoColor=white&labelColor=00857A" alt="Live Demo" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/1xBSHkglxZqkV2K0s">
  <img src="https://img.shields.io/badge/📚_DOCS-02569B?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=013D6E" alt="Docs" height="45"/>
</a>

</div>

<img width="1672" height="941" alt="645e4bbd-804f-44ca-a072-475f2aba0fef" src="https://github.com/user-attachments/assets/57a9b3fe-829b-474c-b965-ee6f7bdd4b66" />


<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**Flutter Slidable Widget** is a beautifully animated, production-ready widget that brings **swipe-to-reveal actions** to any list item in your Flutter app — just like in Gmail, iOS Mail, or WhatsApp. Swipe left, swipe right, or both — with smooth physics, custom action buttons, and full gesture control.

It's the swipe experience your users expect, packaged into one clean, zero-dependency widget.

> 💡 **Perfect for:** Chat lists, email inboxes, task managers, shopping carts, notification feeds — any list where quick actions matter.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 👈 **Left Swipe** | 👉 **Right Swipe** | 🔄 **Both Sides** |
|:---:|:---:|:---:|
| Reveal actions on<br/>the left side | Reveal actions on<br/>the right side | Independent or<br/>synchronized actions |

| 🎨 **Custom Actions** | 🎛️ **Gestures** | ⚡ **60 FPS** |
|:---:|:---:|:---:|
| Icons, colors,<br/>labels & callbacks | Dismiss, drag, tap,<br/>& snap behaviors | Smooth, jank-free<br/>animations |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Widget

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| 🚀 **Zero Dependencies** | No bloat — pure Flutter, no external packages required |
| 🎨 **Fully Themeable** | Colors, icons, radii, and shadows adapt to any design system |
| ♿ **Accessible** | Screen-reader friendly with semantic labels and keyboard focus |
| 🧩 **Composable** | Works inside `ListView`, `SliverList`, `GridView` & any scrollable |
| 🔧 **Configurable** | Dismissible mode, action pane widths, drag extents — all tunable |
| 🌍 **Production-Ready** | Battle-tested by 5,000+ apps with 2M+ downloads on pub.dev |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Widget in Action

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  📱  Flutter Slidable Widget  v4.0.2             ║
╠══════════════════════════════════════════════════╣
║                                                  ║
║  ◀◀ Swipe Left                                   ║
║  ┌────────────┬──────────────────────────────┐   ║
║  │ 🗑️ Archive │  📩 Message from Alice       │   ║
║  └────────────┴──────────────────────────────┘   ║
║                                                  ║
║  Swipe Right ▶▶                                  ║
║  ┌──────────────────────────────┬────────────┐   ║
║  │  📩 Message from Bob         │ ✅ Mark  │   ║
║  └──────────────────────────────┴────────────┘   ║
║                                                  ║
║  Both Sides ◀▶                                   ║
║  ┌────────┬──────────────────┬──────────┐        ║
║  │ 🗑️    │  📩 Hi there!    │ ⭐ Pin  │        ║
║  └────────┴──────────────────┴──────────┘        ║
║                                                  ║
║  ⚡ 60 FPS   🎨 Themeable   📦 Zero deps         ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
📱 flutter-slidable-widget/
├── 🎯 lib/
│   ├── slidable.dart          # Main widget
│   ├── action_pane/           # Left & right panes
│   ├── action_button/         # Action buttons
│   ├── controller/            # Group & dismiss controllers
│   └── theme/                 # Custom theming API
├── 🧪 test/                   # Unit & widget tests
├── 📖 example/                # Sample Flutter app
└── 📚 docs/                   # Migration guide & API reference
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" style="display:none"/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Material](https://img.shields.io/badge/Material_3-757575?style=for-the-badge&logo=materialdesign&logoColor=white)
![Cupertino](https://img.shields.io/badge/Cupertino-000000?style=for-the-badge&logo=apple&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a bug? Have an idea for a new action type?

<div align="center">

<a href="https://share.google/1xBSHkglxZqkV2K0s">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/1xBSHkglxZqkV2K0s">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-FF5A5F?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/1xBSHkglxZqkV2K0s">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-00A699?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

<br/>

<div align="center">

### 📱 Made with 💙 by the Flutter Slidable Team

*If this widget made your app smoother — leave a like on pub.dev!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,13,28&height=120&section=footer" width="100%"/>

</div>
