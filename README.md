# BÁO CÁO THỰC HÀNH LẬP TRÌNH C# WINFORMS (BÀI 6.6, 6.7, 6.8 - 3-TIER ARCHITECTURE)

## MỤC 1: THÔNG TIN SINH VIÊN
* **Họ và tên sinh viên:** Phạm Gia Bảo
* **Mã sinh viên:** 24810320309
* **Lớp / Khóa:** D19QTANM1 (Lập trình .NET / C# WinForms)
* **Link Repository:** https://github.com/404-syntax/TH13-11-2026-Bai_tap_6.6-6.7-6.8

---

## MỤC 2: HÌNH ẢNH KẾT QUẢ CÁC MÀN HÌNH CHỨC NĂNG

### 1. Bài 6.6: Hệ thống Quản lý Thư viện
* **Màn hình chính:**
  ![Main 6.6](docs/bai66_main.png)
* **Quản lý / Thêm sách mới:**
  ![Add Book](docs/bai66_add_book.png)
* **Danh sách phiếu mượn:**
  ![Loan List](docs/bai66_loan_list.png)
* **Xử lý trả sách:**
  ![Return Book](docs/bai66_return.png)
* **Cảnh báo quá hạn & Thẻ hết hạn:**
  ![Overdue](docs/bai66_overdue.png)
  ![Card Expired](docs/bai66_card_expired.png)
* **Báo cáo - Thống kê:**
  ![Statistics 6.6](docs/bai66_statistics.png)

---

### 2. Bài 6.7: Hệ thống Quản lý Phòng khám / Bệnh nhân
* **Màn hình chính:**
  ![Main 6.7](docs/bai67_main.png)
* **Tiếp nhận bệnh nhân mới & Tìm kiếm:**
  ![New Patient](docs/bai67_new_patient.png)
  ![Find Patient](docs/bai67_find_patient.png)
* **Quản lý danh mục thuốc & Kê đơn:**
  ![Medicine](docs/bai67_medicine.png)
  ![Prescription](docs/bai67_prescription.png)
* **Thanh toán & Xử lý giao dịch (Rollback):**
  ![Payment 6.7](docs/bai67_payment.png)
  ![Rollback 6.7](docs/bai67_rollback.png)

---

### 3. Bài 6.8: Hệ thống Quản lý Nhà hàng / Quán ăn
* **Màn hình chính:**
  ![Main 6.8](docs/bai68_main.png)
* **Mở bàn & Gọi món (Order):**
  ![Open Table](docs/bai68_open_table.png)
  ![Order](docs/bai68_order.png)
* **Tính tiền & Thanh toán hoàn tất:**
  ![Payment Calc](docs/bai68_payment_calc.png)
  ![Paid](docs/bai68_paid.png)

---

## HƯỚNG DẪN CÀI ĐẶT & CHẠY DỰ ÁN
1. Mở SQL Server Management Studio (SSMS), thực thi file `Database/ScriptDB.sql` trong từng thư mục bài tập để khởi tạo CSDL và dữ liệu mẫu.
2. Mở file `.sln` bằng Visual Studio 2022.
3. Sửa lại chuỗi kết nối `ConnectionString` trong `App.config` hoặc lớp DAL cho phù hợp với máy cá nhân.
4. Bấm **F5** để biên dịch và chạy chương trình.
