# ☕ Coffee Shop Management System

![C#](https://img.shields.io/badge/Language-C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/Framework-.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/Database-SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

> Ứng dụng quản lý quán cà phê toàn diện, hỗ trợ quy trình từ gọi món, thanh toán đến quản lý kho và báo cáo doanh thu.

## 📖 Giới thiệu (Introduction)

Dự án này là một ứng dụng Windows Forms (WinForms) được xây dựng bằng C#, giúp các chủ quán cà phê tối ưu hóa quy trình vận hành. Hệ thống phân quyền rõ ràng giữa **Admin** (Quản trị viên) và **Nhân viên/Khách hàng**, tích hợp báo cáo thống kê chi tiết.

## 🚀 Tính năng chính (Key Features)

### 1. Phân hệ Admin (Quản trị viên)
- **Dashboard:** Xem tổng quan tình hình kinh doanh, biểu đồ doanh thu.
- **Quản lý Thực đơn (Menu):** Thêm, sửa, xóa đồ uống, cập nhật giá và hình ảnh.
- **Quản lý Nhân viên:** Tạo tài khoản, phân quyền truy cập hệ thống.
- **Quản lý Kho (Inventory):**
  - Nhập hàng từ nhà cung cấp.
  - Quản lý danh sách nhà cung cấp.
  - Lịch sử nhập hàng chi tiết.
- **Báo cáo & Thống kê:** Xuất báo cáo doanh thu, báo cáo nhập hàng (sử dụng *Microsoft Report Viewer*).

### 2. Phân hệ Bán hàng (Cashier/Staff)
- **Order món:** Giao diện trực quan chọn món nhanh chóng.
- **Thanh toán:** Tính tiền tự động, in hóa đơn (Bill).
- **Lịch sử bán hàng:** Xem lại các đơn hàng đã thực hiện trong ca làm việc.

## 🛠️ Công nghệ sử dụng (Tech Stack)

- **Ngôn ngữ:** C# (.NET Framework)
- **Giao diện:** Windows Forms (WinForms)
- **Cơ sở dữ liệu:** Microsoft SQL Server
- **Báo cáo:** Microsoft Report Viewer (.rdlc)
- **IDE:** Visual Studio 2022

## ⚙️ Cài đặt & Chạy dự án (Installation)

Để chạy được dự án này trên máy của bạn, hãy làm theo các bước sau:

1. **Clone repository này về máy:**
   ```bash
   git clone [https://github.com/tcwiuy/CoffeShop_CSharp.git](https://github.com/tcwiuy/CoffeShop_CSharp.git)
