# Mẫu Báo cáo LaTeX - Đại học Tôn Đức Thắng (TDTU)

Đây là một mẫu (template) LaTeX được xây dựng để soạn thảo các bài báo cáo, đồ án, tiểu luận hoặc khóa luận tốt nghiệp theo định dạng chung của Trường Đại học Tôn Đức Thắng.

Mẫu template này được mình tạo ra nhằm giúp các bạn tiết kiệm thời gian định dạng và tập trung hơn vào nội dung học thuật.

## ✨ Tính năng mình đã triển khai

-   **Cấu trúc rõ ràng:** Phân chia tài liệu thành các thư mục `frontmatter`, `backmatter` giúp quản lý file dễ dàng.
-   **Định dạng chuẩn:** Đã thiết lập sẵn các thông số theo yêu cầu chung về báo cáo:
    -   Khổ giấy A4, căn lề (`top=3.5cm`, `bottom=3cm`, `left=3.5cm`, `right=2cm`).
    -   Font chữ Times New Roman, cỡ chữ 13.
    -   Giãn dòng 1.5 lines.
    -   Thụt đầu dòng 1.25cm cho mỗi đoạn văn.
-   **Tự động hóa:** Tự động tạo trang bìa, mục lục, danh mục hình ảnh, danh mục bảng biểu.
-   **Hỗ trợ tiếng Việt:** Cấu hình sẵn `vietnam` package để gõ tiếng Việt hoàn chỉnh.
-   **Dễ dàng tùy chỉnh:** Mọi thiết lập định dạng chung được tập trung tại file `preamble.tex`, giúp người dùng dễ dàng thay đổi theo yêu cầu của từng môn học hoặc giảng viên.

## 📁 Cấu trúc Thư mục

```
.
├── main.tex                # File chính để biên dịch toàn bộ tài liệu
├── preamble.tex            # "Bộ não" của template - Chứa mọi thiết lập định dạng
├── README.md               # File hướng dẫn này
├── media/                  # Thư mục chứa hình ảnh, logo...
│   └── logo.png
├── frontmatter/            # Chứa các trang đầu của báo cáo
│   ├── titlepage.tex       # Trang bìa
│   ├── declaration.tex     # Lời cam đoan
│   ├── acknowledgment.tex  # Lời cảm ơn
│   └── abstract.tex        # Trích yếu/Tóm tắt
└── backmatter/             # Chứa các trang cuối của báo cáo
    └── references.tex      # Tài liệu tham khảo
```

## 📝 Hướng dẫn Sử dụng trên Overleaf

1.  **Tải template:** Tải về thư mục `.zip` và tải lên trên dự án (Project) mới của bạn trên Overleaf.
2.  **Chỉnh sửa thông tin cơ bản:**
    -   Mở file `frontmatter/titlepage.tex` và điền thông tin của bạn (Tên đề tài, sinh viên thực hiện, giảng viên, năm...).
    -   Viết nội dung cho các file `declaration.tex`, `acknowledgment.tex`, `abstract.tex`.
3.  **Viết nội dung chính:**
    -   Nội dung báo cáo được viết trực tiếp trong file `main.tex` tại khu vực `\mainmatter`.
    -   Bạn có thể tạo các file `.tex` riêng cho từng chương (ví dụ `chuong1.tex`, `chuong2.tex`) và dùng lệnh `\input{chuong1.tex}` trong `main.tex` để tài liệu gọn gàng hơn.
4.  **Thêm tài liệu tham khảo:**
    -   Mở file `backmatter/references.tex` và thêm danh sách tài liệu tham khảo.
5.  **Biên dịch:**
    -   Mở file `main.tex`.
    -   Biên dịch dự án.
    -   **Lưu ý:** Bạn cần biên dịch ít nhất 2 lần để Mục lục và các tham chiếu được cập nhật chính xác.

## 🎨 Tùy chỉnh

Tất cả các định dạng về font chữ, lề, giãn dòng, tiêu đề, mục lục... đều được đặt trong file `preamble.tex`. Nếu bạn muốn thay đổi bất kỳ định dạng nào, chỉ cần mở file này và chỉnh sửa các giá trị tương ứng.

---

Chúc bạn có những bài báo cáo thật chuyên nghiệp!
Nếu bạn thấy dự án hữu ích, mình rất mong nhận được một ⭐️ hoặc fork để có thêm động lực hoàn thiện và phát triển hơn nữa.


