### Mẫu Bug Report Template (4 mảnh ghép bắt buộc)
Tạo Issue trên Jira ➔ Gắn tag `#BUG`➔ Điền đủ mẫu sau trước khi gửi link cho Trưởng nhóm:
```
### [ENV-BUG] <Tên lỗi ngắn gọn - VD: Lỗi Port 8080 trên Docker>

* **1. Context:** HĐH (Win/Mac/Ubuntu) + Phiên bản Docker/Tool + Lệnh vừa chạy.
* **2. Expected:** Kết quả mong muốn (VD: Container chạy ổn định ở port 8080).
* **3. Actual:** Hiện tượng thực tế (VD: Container tự tắt sau 3 giây, báo lỗi Exited 1).
* **4. Log:** Dán đoạn mã lỗi dạng text (kèm xác nhận đã tự tra cứu 3 bước bên dưới).
```

### Quy trình 3 bước tự xử lý bắt buộc (Quy tắc 15-30-15)
Bước|	Hành động	|Thời gian	|Cách thực hiện cốt lõi|
|---|---|---|---|
1.Googling	|Tìm chính xác mã lỗi	|15 phút|	Copy dòng lỗi chính (bỏ đường dẫn cá nhân), đặt trong ngoặc kép `"..."` + tên công cụ.|
2.Community|	Tra cứu nội bộ & cộng đồng|	30 phút|	Tìm trên Jira/Chat cũ của nhóm trước; sau đó tìm trên GitHub Issues và StackOverflow.|
3.AI Translation|	Nhờ AI dịch nghĩa & gỡ rối|	15 phút|	Dán Context + Log vào AI, yêu cầu giải thích nguyên nhân và gợi ý 3 lệnh kiểm tra.|

3. Quy tắc vận hành (5 điểm chạm)
- Không nhắn hỏi ngang vào nhóm chat chung.   

- Tự chạy phễu 3 bước tra cứu trong tối đa 60 phút.

- Vẫn lỗi ➔ Tạo Issue trên Jira, gắn tag `#BUG` và điền đủ 4 mảnh ghép.   

- Gửi link Issue vào kênh hỗ trợ riêng và thông báo cho Trưởng nhóm.   

- Xử lý xong ➔ Ghi lại cách sửa vào phần bình luận của Issue trước khi đóng.