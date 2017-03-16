#Get started
Đầu tiên chúng ta cần biết sơ về Ionic 2s.
* Ionic 2 là 1 framework javascript cho phép chúng ta làm việc tương tác trên mobile, nó xây dựng dựa trên cordova.
* Giúp chúng ta xây dựng các ứng dụng cross platform sử dụng HTMl, CSS và Javascript.

#Installation
* Đầu tiên, cần đảm bảo chúng ta đã cài NodeJS, nếu chưa chúng ta phải cài vào, => tải và cài [NodeJS]

* Cài đặt Ionic 2

Cài đặt Cordova
```sh
$ npm install -g cordova
```
Trên máy MAC/Linux/Unix, nếu bị lỗi access, bạn phải chạy dưới quyền root, sử dụng lệnh sau
```sh
$ sudo npm install -g cordova
```

Tiếp đến, cài đặt Ionic CLI - là 1 bộ code sử dụng command line phát triển riêng cho IONIC, thông qua lệnh ionic ta có thể thực thi các lệnh (khởi tạo, chạy project, tạo page)

```sh
$ npm install -g ionic
```
Một số trường hợp cài đặt bị lỗi, mà ko biết lý do tại sao, bạn có thể cần xóa bản cài đặt cũ của ionic-cli

```sh
$ npm uninstall -g ionic
```

Clear cache
```sh
$ npm cache clean
```

Sau đó cài lại
```sh
$ npm install -g ionic
```

Kiểm tra lại thông tin cài đặt ionic
```sh
$ ionic info
```



[NodeJS]: <https://nodejs.org/en/>
