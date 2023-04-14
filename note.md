# Chuẩn bị công cụ

Các Extensions cần cài đặt trong Visual Studio Code

- Live Server => Hỗ trợ tạo ra 1 server ảo trên máy tính cá nhân
- Prettier - Code formatter => Tự động format code

Cấu hình:

- Thiết lập tự động format code khi lưu

# Request - Response

## Request

- URL Request
- Http Method: GET, POST,...
- Request Header: Cookie, Content-Type,...
- Body (Data, Payload): Dữ liệu được gửi lên Server

## Response

- Response Header: Connection, Data, Content-Length, Content-Type,...
- Response Status:

* Code
* Text

=> Tham khảo: https://developer.mozilla.org/en-US/docs/Web/HTTP/Status

- Response: Dữ liệu được trả về từ Server (html, text, json, image, attachment,...)

Lưu ý: Request và Response giao tiếp với nhau thông qua HTTP

Đặc điểm của HTTP: Không liên tục

# Cấu tạo của trang web

- HTML => Bộ khung xương của trang web
- CSS => Tạo ra bố cục của trang
- Javascript => Sự kiện, hành động từ phía người dùng tương tác lên trang web
- Ảnh, Icon, Font chữ

# Ngôn ngữ HTML

<tenthe>Content</tenthe>

<tenthe />

Thẻ head:

- Các thẻ meta
- Thẻ tiêu đề
- Thẻ liên kết css, js

Thẻ body:

- Chứa nội dung của trang web

## Thẻ Inline

- Width bằng nội dung
- Nhiều thẻ inline đứng cạnh nhau => Cùng nằm trên 1 dòng

## Thẻ block

- Width mặc định bằng 100% (Tỷ lệ theo thành phần cha gần nhất)
- Mỗi thẻ block sẽ nằm trên 1 dòng

## Đặc điểm chung của các thẻ html

- Bất kì thẻ html nào cũng có 2 thuộc tính mặc định: class và id
- 2 thuộc tính này không có tác dụng thay đổi về mặt hiển thị nhưng sẽ hỗ trợ định danh cho CSS
- class: có thể thêm nhiều class trong 1 element (1 thẻ html) => Mỗi class cách nhau bởi dấu cách (space)
- id: chỉ thêm 1 id trong 1 element

## Viết comment trong html

- Ghi chú, diễn giải cho đoạn code mong muốn
- Trình duyệt sẽ không biên dịch nội dung trong comment
- Ngoài ra, comment có thể dùng để ẩn 1 đoạn code nào đó (Không có thực thi)
- Nên viết comment để diễn giải về đoạn code cũng như dễ phát triển, nâng cấp sau này

<!--
Nội dung comment
-->

Phím tắt: Ctrl + /
