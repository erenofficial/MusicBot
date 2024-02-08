<h1 align="center"><img src="./assets/logo.gif" width="30px"> Discord Music Bot <img src="./assets/logo.gif" width="30px"></h1>

## ✨Cập nhật mới nhất

v5.1 Đang được phát triển! Hãy xem thử [TẠI ĐÂY!](https://github.com/erenofficial/MusicBot/)

Bạn đạt được gì từ nó? Hãy để chúng tôi giải thích:
  - Môi trường docker hoàn toàn theo mô-đun để phát triển và triển khai dễ dàng hơn
  - MỘT BẢNG ĐIỀU KHIỂN LÀM VIỆC!!!
  - Tích hợp DB để bạn lưu các bài hát yêu thích vào
  - Tích hợp Lavalink tự lưu trữ
  - Kênh truy vấn chuyên dụng
  - Nhiều lệnh và chức năng hơn
  - Và còn nhiều hơn thế nữa!
## 🚧 | Điều kiện tiên quyết

- [Node.js 16+](https://nodejs.org/en/download/)
- [Máy chủ Lavalink](https://code.darrennathanael.com/how-to-lavalink)
- Bạn sẽ cần chạy `npm run triển khai` hoặc `yarn triển khai`. để khởi tạo các lệnh gạch chéo. _Bạn có thể làm điều này trên máy tính của mình
   tại địa phương_

> LƯU Ý: Lavalink cần thiết cho chức năng nghe nhạc. Bạn cần có một máy chủ Lavalink đang hoạt động để bot hoạt động.

## 📝 | Lưu ý quan trọng nếu bạn đang chuyển từ v4 sang v5

1. Tải xuống và định cấu hình v5 trong một thư mục riêng.
2. Đưa bot ra khỏi máy chủ của bạn.
3. Mời lại Bot bằng quyền
    phạm vi. [Ví dụ về URL mời (Thay đổi CLIENT_ID)](https://discord.com/oauth2/authorize?client_id=CLIENT_ID&permissions=277083450689&scope=bot%20applications.commands)
4. Chạy `npm run triển khai` hoặc `yarn triển khai` để khởi tạo các lệnh gạch chéo. _Bạn có thể thực hiện việc này trên máy tính cục bộ_

## 📝 | Hướng dẫn

### 🐳 Docker
> Tệp `config.js` phải được định cấu hình với máy chủ `"lavalink"` và bạn nên sử dụng cùng một `mật khẩu` như trong `docker/application.yml`.

Xây dựng và khởi động bot và Lavalink
```sh
docker-compose up -d --build
```
### 💪🏻 Không phải Docker
> Tệp `config.js` phải được định cấu hình trước. Đừng quên thêm máy chủ Lavalink

Cài đặt tất cả các phụ thuộc và triển khai Lệnh Slash
```sh
cài đặt npm
npm chạy triển khai
```
Khởi động bot
```sh
nút index.js
```

## 📝 | [Máy chủ hỗ trợ](https://ec330e24-8403-4b83-8a25-f15174b4ecc4-00-yijkw46trfpu.riker.replit.dev/)

Nếu bạn gặp vấn đề lớn về mã hóa với bot này, vui lòng tham gia và yêu cầu trợ giúp.

## 📸 | Ảnh chụp màn hình

Sớm


## ✨ | Người đóng góp

Những đóng góp luôn được hoan nghênh :D Hãy nhớ theo dõi [Contributing.md](/CONTRIBUTING.md)

<a href="[https://github.com/SudhanPlayz/Discord-MusicBot/graphs/contributors](https://github.com/erenofficial/MusicBot/)">
   <img src="https://github.com/erenofficial/MusicBot/" />
</a>

## 🌟 | Làm với

- [Discord.js](https://discord.js.org/)
- [Lavalink](https://github.com/freyacodes/Lavalink) với erela.js
- [Express](https://expressjs.com/)
- [JS tiếp theo](https://nextjs.org/)
- [Giao diện người dùng tiếp theo](https://nextui.org)
- [Biểu tượng giao diện người dùng Material](https://mui.com/material-ui/material-icons/)
