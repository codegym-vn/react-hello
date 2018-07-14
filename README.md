# HelloReactNative
Ứng dụng HelloWorld trong React Native

# Mục tiêu bài tập
- Cài đặt thành công Nodejs
- Cài đặt thành công Android Studio (Windows)
- Build được ứng dụng react native đầu tiên : HelloWorld

# Start

Trong bài hướng dẫn đầu tiên này, mình sẽ hướng dẫn các bạn từng bước để tạo một 
ứng dụng HelloReactNative.

Để bắt tay vào cài đặt được ứng dụng đầu tiên này. Trước tiên, chúng ta cần phải có môi trường trước
Bạn sẽ cần phải cài Nodejs, Android Studio.
- Link tải Nodejs: https://nodejs.org/en/download/
- Link tải Android Studio : https://developer.android.com/studio/

Sau khi cài xong, chúng ta sẽ bắt tay vào từng bước như bên dưới

####  Bước 1: 
Chạy câu lệnh sau = Command Prompt hoặc Git Bash nhé ! Cài Nodejs sẽ giúp chúng ta 
chạy câu lệnh dưới mà không bị lỗi, npm chính là viết tắt của Node Package Manager

```npm install -g react-native-cli```

#### Bước 2:
Chạy tiếp câu lệnh:

```react-native init HelloReactNative --version 0.55.4```

Trong đó : HelloReactNative chính là tên Project của bạn

Trong thời điểm viết bài này, version React Native 0.56 của facebook
đang bị lỗi, vì thế mình muốn mọi người cài version 0.55.4. Đây
cũng chính là version mà mình đang sử dụng cho các dự án khác.

#### Bước 3:
Tại thư mục chứa code Project, bạn chạy lệnh

```npm install```
Mục đích của lệnh này để cài đặt tất cả các thư viện đang được khai báo ở file `package.json`

#### Bước 4: 
Sau khi cài đặt xong, bạn chạy lệnh

```react-native run-android```
hoặc
Mở project bằng Android Studio, chỉ chọn mở thư mục Android thôi nhé !!!

Sau đó chạy lệnh : 
```react-native start```
nếu chạy lệnh start thì bạn phải tự build App bằng Android Studio

#### Bước 5: 
Đón nhận kết quả từ màn hình mobile hoặc emulator

![alt](https://github.com/anhtbok92/HelloReactNative/blob/master/img/react_native_hello_world.PNG)
