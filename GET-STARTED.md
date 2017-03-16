# Get started
Đầu tiên chúng ta cần biết sơ về Ionic 2.
* Ionic 2 là 1 framework javascript cho phép chúng ta làm việc tương tác trên mobile, nó xây dựng dựa trên cordova, từ đó chúng ta có thể xây dựng các ứng dụng Native App.
* Giúp chúng ta xây dựng các ứng dụng cross platform sử dụng HTMl, CSS và Javascript.

# Installation

# Cài đặt NodeJS

* Đầu tiên, cần đảm bảo chúng ta đã cài NodeJS, nếu chưa chúng ta phải cài vào, => tải và cài [NodeJS]

# Cài đặt Ionic 2

Chúng ta sử dụng Command Prompt của Windows, hoặc trong Windows 10 chúng ta có thể sử dụng Windows PowerShell hoặc Git Bash.
Đối với trên MAC/Linux chúng ta xài Terminal để xử thôi.

### Cài đặt Cordova

```sh
$ npm install -g cordova
```

Trên máy MAC/Linux/Unix, nếu bị lỗi access, bạn phải chạy dưới quyền root, sử dụng lệnh sau

```sh
$ sudo npm install -g cordova
```

### Cài đặt Ionic CLI
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

### Cài đặt TypeScript
Vì Ionic sử dụng AngularJS 2, Typescript thì làm việc rất tốt với AngularJS2, phần khác mình sẽ hướng dẫn các bạn về TypeScript để có thể code nhanh hơn.

```sh
$ npm install -g typescript
```

### Khởi tạo 1 Project
Ví dụ ta khởi tạo 1 project hello-world

```sh
$ ionic start hello-world --v2
```

Sau đó tao vào thư mục project và chạy ứng dụng

```sh
$ ionic serve
```

Mặc định ionic sẽ generate cho bạn 1 port chạy.
Ví dụ: localhost:8080

Ngoài ra trong IONIC-CLI chúng ta có thể debug cùng lúc trên nhiều thiết bị ảo, chúng ta chạy lệnh sau để chạy thử.

```sh
$ ionic serve -l
```

### Tổng kết:
Vậy là đã cài xong Ionic, chúng ta có thể khởi tạo ứng dụng và tung hoành trên này nhé, phần sau sẽ hướng dẫn các bạn về cấu trúc của Ionic 2.

[NodeJS]: <https://nodejs.org/en/>
