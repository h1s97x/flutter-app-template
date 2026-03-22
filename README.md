# Flutter App Template

Flutter 应用模板 - 适用于快速创建移动端应用，包含完整项目结构、状态管理、路由配置。

## 📦 包含内容

- ✅ Flutter 3.x + Dart
- ✅ Riverpod 状态管理
- ✅ GoRouter 路由管理
- ✅ 响应式设计
- ✅ 主题配置
- ✅ CI/CD 工作流

## 🚀 快速开始

### 使用模板创建新项目

1. 点击 **"Use this template"** 按钮
2. 输入新项目名称
3. 开始开发！

### 本地开发

```bash
# 克隆项目
git clone https://github.com/h1s97x/flutter-app-template.git
cd flutter-app-template

# 获取依赖
flutter pub get

# 运行应用
flutter run
```

## 📁 项目结构

```
lib/
├── main.dart              # 应用入口
├── app.dart               # 应用配置
├── core/
│   ├── router/           # 路由配置
│   ├── theme/            # 主题配置
│   └── constants/         # 常量
├── features/
│   └── home/             # 功能模块
│       ├── presentation/
│       └── domain/
├── shared/
│   └── widgets/          # 共享组件
└── generated/            # 生成文件
```

## 🛠️ 开发命令

```bash
flutter pub get      # 获取依赖
flutter run          # 运行
flutter build apk    # 构建 APK
flutter build ios    # 构建 iOS
flutter analyze      # 代码分析
flutter test         # 运行测试
```

## 📱 支持平台

- Android
- iOS
- Web
- macOS
- Windows
- Linux

## 📝 License

MIT
