
trích toàn bộ văn bản cấm thêm bớt nội dung sử lý từ bảng -> text
-------------------------------------------------------------
I. QUY TẮC LÀM PHẦN METADATA
1. Khi nào tạo Metadata
Chỉ tạo # Metadata nếu văn bản có đủ thông tin như:
Số văn bản
Tiêu đề
Loại văn bản
Ngày ban hành
Người ký
Cơ quan ban hành
KHÔNG bịa nếu thiếu dữ liệu.
2. Cấu trúc Metadata bắt buộc
# Metadata

- **doc_id:** ...
- **Title:** ...
- **Category:** ...
- **Date:** ...
- **signed_by:** ...
- **organization:** ...

3. Quy tắc điền Metadata
doc_id → Số văn bản gốc
Title → Tên văn bản (giữ nguyên 100%)
Category → Loại văn bản (VD: Báo cáo, Thông báo, Quyết định...)

Date → Ngày trong văn bản (KHÔNG sửa format nếu không được yêu cầu)

signed_by → Người ký (giữ nguyên chức danh nếu có)

organization → Cơ quan ban hành

4. Nguyên tắc bất biến Metadata

❌ KHÔNG thêm trường mới

❌ KHÔNG xóa trường có sẵn

❌ KHÔNG sửa chữ, số, chính tả

✅ Chỉ thay đổi hình thức hiển thị

II. QUY TẮC PHÂN CẤP NỘI DUNG VĂN BẢN
1. Khung cấu trúc tổng thể
# Thông tin văn bản
## Kính gửi
## Nội dung
## 1.
## 2.
## 3.
## Nơi nhận
## Chữ ký
# Phụ lục (nếu có)

2. Phần Thông tin văn bản

Chứa:

Quốc hiệu

Cơ quan ban hành

Số văn bản

Ngày tháng

KHÔNG chỉnh sửa nội dung — chỉ xuống dòng cho dễ đọc

3. Phần Kính gửi

Tách riêng mục ## Kính gửi

Mỗi đơn vị nhận → 1 dòng

KHÔNG gộp câu

4. Phần Nội dung

Toàn bộ thân văn bản đưa vào ## Nội dung

5. Phân cấp mục đánh số
Văn bản gốc	Markdown
I., II., III.	## I.
1., 2., 3.	### 1.
1.1, 1.2	#### 1.1.
Điều	## Điều
Khoản	### Khoản
Điểm	Bullet -
6. Nếu có cấu trúc pháp lý
Cấp	Format
Chương	# Chương
Điều	## Điều
Khoản	### Khoản
Điểm	-
7. Phần Nơi nhận

Gom toàn bộ danh sách nơi nhận

Mỗi dòng = 1 đơn vị nhận

8. Phần Chữ ký

Ghi nguyên văn:

Chức danh

Ghi chú ký

Họ tên

9. Quy tắc TUYỆT ĐỐI KHÔNG VI PHẠM

❌ KHÔNG thêm nội dung

❌ KHÔNG bớt nội dung

❌ KHÔNG sửa chữ, số, lỗi chính tả

❌ KHÔNG diễn giải lại

❌ KHÔNG rút gọn

✅ CHỈ thay đổi HÌNH THỨC & PHÂN CẤP