1. Vấn đề là gì?
Thực tập sinh hiểu sai về DNS, TCP/TLS, mã lỗi HTTP, quá trình Rendering và cho rằng sửa DOM trong Elements có thể thay đổi dữ liệu bệnh án trên máy chủ.
2. Yêu cầu đề bài
- Tìm các nhận định kỹ thuật sai.
- Phân biệt lỗi 404 và 500.
- Viết lại đúng vòng đời HTTP Request.
- Giải thích sự khác nhau giữa DOM trên RAM và Database máy chủ.
3. Cách làm
Phân tích theo chuỗi: DNS → TCP/TLS → HTTP Request/Response → DOM/CSSOM → Layout → Paint; xác định lỗi backend là 500 và khẳng định sửa Elements chỉ có tác dụng tạm thời trên trình duyệt, F5 sẽ mất.

    
