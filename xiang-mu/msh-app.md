启动工程注意事项：

1.下来源码后不要再react-native link，否则会有错误；

2.XCode要打开xcworkspace而不是原来的xcodeproj，因为工程使用了Pod；

3.XCode打开后，要删除MSH-Libraries-RNCamera-FaceDetector目录，否则运行会报错；

4.安卓可能需用android studio打开工程，根据提升自动修复一些错误。

