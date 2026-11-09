# Thiết kế kiến trúc#
## Xây dựng một mẫu **Bug Report Template** dựa trên 4 mảnh ghép (*Context, Expected, Actual, Log*) để các thành viên bắt buộc phải điền trước khi hỏi.
-Context :   
 + hệ điều hành : Windows 11
 + công cụ : node.js v18
 + thao tác thực hiện : chạy lệnh docker-compose up sau khi pull branch main mới nhất
- Expected :
 + khởi chạy thành công
- Actual :
 + terminal báo lỗi không thể ràng buộc cổng 8080 và process bị dừng đột ngột
- Log :
 + đọa log u/
   ```bag
  Error response from daemon: driver failed programming external connectivity on endpoint backend_app: Bind for 0.0.0.0:8080 failed: port is already allocated.
  ## Đề xuất một quy trình 3 bước tra cứu bắt buộc (*Googling ➔ Community Search ➔ AI Translation*) để thành viên tự xử lý 80% vấn đề trước khi nhờ hỗ trợ.
  - Bước 1 ( Googling ) :
    + thao tác : sử dụng chính xác với các thông tin báo lỗi cốt lõi
    + Toán tử
      * Ngoặc kép " " cho lỗi cụ thể
      * toán tử `-` để loại trừ trang rác
      * toán tư site: nếu tìm tài liệu chính thống
  - Bước 2 ( Community Search ) :
    + thao tác : tra cứu giải pháp trực tiếp từ các diễn đàn chuyên ngành hoặc kho mã nguồn của dự án
    + cú pháp : site:stackover.com "docker" "bind: addres already in use"
  - Bước 3 ( AI Translation ) :
    + dịch và giải thích ý nghĩa của thông báo lỗi
    + Nguyên nhân gốc rễ gây ra lỗi gì
    + cho tôi 3 bước kiểm tra sửa lỗi nhanh nhất trên hệ điều hành windows
    
    
