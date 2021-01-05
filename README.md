###环境搭建
1. 下载[Flutter](https://storage.googleapis.com/flutter_infra/releases/stable/macos/flutter_macos_1.22.5-stable.zip)

2. 添加到环境变量
```bash
export PATH="$PATH:/flutter/bin"
```

3. 安装 Android Studio & Xcode
   
4. 执行`flutter doctor`
   无法下载dart先执行下如下命令
```bash
export PUB_HOSTED_URL=https://pub.flutter-io.cn
export FLUTTER_STORAGE_BASE_URL=https://storage.flutter-io.cn
```
按照命令行提示缺啥补啥

5. 通过`flutter create xxx`创建flutter项目
   如果卡在"flutter pub get"请先执行如下命令
```bash
export PUB_HOSTED_URL=https://pub.flutter-io.cn
export FLUTTER_STORAGE_BASE_URL=https://storage.flutter-io.cn
```
