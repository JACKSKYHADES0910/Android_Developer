# Android开发

![image](https://github.com/JACKSKYHADES0910/Android_Developer/assets/90612462/8f7ab360-bb77-4592-a496-57782f5e93cf)

## 1. Android开发前准备工作

### 1.1 Android Studio下载

1. [Android Studio中文开发网](https://developer.android.google.cn/studio?hl=zh-cn)

![image](https://github.com/JACKSKYHADES0910/Android_Developer/assets/90612462/408b7259-64ba-48f1-a9b6-0b8b744767fb)

### 1.2 安装步骤

1. 下载并安装Android Studio。
2. 配置必要的SDK和工具。

### 1.3 项目初始化

1. 打开Android Studio，选择"Start a new Android Studio project"。
2. 选择项目模板并填写项目名称及保存位置。
3. 配置项目的基本设置，如包名、语言（Java/Kotlin）等。

## 2. 项目结构

### 2.1 文件夹说明

- `app/`：包含项目的主要代码和资源文件。
- `gradle/`：包含Gradle构建脚本和配置文件。

### 2.2 主要文件说明

- `AndroidManifest.xml`：应用的清单文件，声明应用的组件、权限等。
- `build.gradle`：项目的构建配置文件。

## 3. 编码规范

### 3.1 命名规范

- 类名：采用大驼峰命名法（如 `MainActivity`）。
- 变量名：采用小驼峰命名法（如 `userName`）。

### 3.2 代码注释

- 使用Javadoc风格的注释。
- 代码逻辑复杂处添加必要的行内注释。

## 4. 运行与调试

### 4.1 运行应用

1. 连接设备或启动模拟器。
2. 点击运行按钮或使用快捷键 `Shift + F10`。

### 4.2 调试技巧

- 设置断点：在代码行号左侧点击。
- 查看变量值：在调试模式下，悬停查看或使用"Variables"窗口。

## 5. 常见问题

### 5.1 构建失败

- 检查`build.gradle`文件的依赖是否正确。
- 清理项目并重新构建：`Build > Clean Project`，然后`Build > Rebuild Project`。

### 5.2 模拟器启动失败

- 检查模拟器配置是否正确。
- 尝试重启Android Studio和计算机。

## 6. 参考资料

- [Android官方文档](https://developer.android.google.cn)
- [Stack Overflow](https://stackoverflow.com)

