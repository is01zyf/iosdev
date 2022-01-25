# iosdev


## 解决无法解析dependency问题
export http_proxy=http://127.0.0.1:1087;export https_proxy=http://127.0.0.1:1087;
xcodebuild -resolvePackageDependencies -scmProvider system -project Facebook/Facebook.xcodeproj
