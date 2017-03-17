# Cấu trúc của 1 dự án IONIC 2
Về cơ bản cấu trúc của 1 source IONIC 2 cũng tương tự như IONIC.
Vì thế nếu bạn nắm cấu trúc cơ bản của IONIC thì cũng nhanh chóng nắm bắt IONIC 2.

# Tree Source
Cấu trúc cơ bản của project IONIC 2
```sh
├── config.xml
├── hooks
├── ionic.config.json
├── node_modules
├── package.json
├── platforms
├── plugins
├── resources
├── src
├── tsconfig.json
├── tslint.json
```

Hầu hết thời gian, chúng ta sẽ làm việc trong thư mục src, chứa các source code html, css, js và asset để chúng ta viết app.
Mặc định nó sẽ load file src/index.html

### src/index.html
Chúng ta sẽ ít chỉnh sửa trên file này, lưu ý là trong source code của file này thì <ion-app></ion-app> chính là 1 entry point, code app của chúng ta sẽ render thông qua tag này.

Các phần include khác trong file này, chính là để load các thành phần liên quan build IONIC 2 (thường gọi là dependencies)

### config.xml
Chứa tất cả các thành phần để chúng ta cấu hình cho app, để build trên máy thật, bao gồm tất cả các thành phần như (Tên App, tên Package, đền các plugin của cordova,....)

### src
Chứa toàn bộ source code để code app

### node_moudles
Chứa các npm packages mà chúng ta đã khai báo trong file package.json

### platforms
* Folder này chứa các platform chúng ta build, khi sử dụng ionic-cli chúng ta add platform nó sẽ chạy ra đây.

* Chúng ta chạy lệnh sau nó sẽ tự tạo folder (android / ios ) tương ứng trong folder platform

```sh
ionic platform add android
```

hoặc
```sh
ionic platform add ios
```
### plugins
Chứa các plugins của cordova khi chúng ta cài đặt cho app của mình.
Khi chúng ta add plugin cho cordova với lệnh như bên dưới, nó sẽ thêm các plugins chúng ta cần cài đặt vào trong folder này.

Ví dụ lệnh bên dưới cho phép chúng ta cài plugin trong cordova làm việc với camera của thiết bị.
```sh
$ cordova plugin add cordova-plugin-camera
```
Bạn cũng có thể xem danh sách các plugin của Cordova tại đây - [Cordova Plugins] 


### Tổng kết:
Vậy là đã cài xong Ionic, chúng ta có thể khởi tạo ứng dụng và tung hoành trên này nhé, phần sau sẽ hướng dẫn các bạn về cấu trúc của Ionic 2.

[Cordova Plugins]: https://cordova.apache.org/plugins/

[NodeJS]: <https://nodejs.org/en/>
