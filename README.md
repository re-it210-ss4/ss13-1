Phần 1: Phân tích
Tại sao thiếu hibernate.dialect lại lỗi? Hibernate là một lớp trung gian. Mỗi loại cơ sở dữ liệu (MySQL, PostgreSQL, Oracle) có cú pháp SQL riêng biệt. Dialect giúp Hibernate biết cách dịch từ ngôn ngữ HQL sang đúng "tiếng địa phương" của database bạn đang dùng.

Thuộc tính tự động tạo bảng: Đó là hibernate.hbm2ddl.auto. Để tự động tạo bảng từ Java Class, ta thường dùng giá trị update hoặc create.
