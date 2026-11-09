# 📊 EduReport - Báo Cáo Chuyên Môn & Phân Tầng Học Sinh

Hệ thống web phân tích phổ điểm, so sánh đa chiều các lớp và phân loại học sinh 4 tầng sau kỳ thi, kèm đề xuất giải pháp sư phạm (Phụ đạo, VIP, Kèm 1-1, Tự học trực tuyến) và xuất file báo cáo Word/PDF/Excel nộp Ban Giám Hiệu.

---

## 🌟 Tính Năng Nổi Bật

1. **🔐 Phân quyền & Phân cấp bộ môn**:
   - **Tổ trưởng Tổ KHTN - Thầy Thạch Thanh Tâm (`tamtt48@fpt.edu.vn`)**: Toàn quyền quản trị, chuyển đổi linh hoạt giữa 5 môn (Toán, Tin học, Sinh học, Hóa học, Vật lý) và xuất báo cáo tổng hợp toàn tổ.
   - **Trưởng môn Toán - Cô Nguyễn Hồng Chi (`chinh10@fpt.edu.vn`)**: Quản lý và lập báo cáo môn Toán.
   - **Trưởng môn Tin học - Thầy Trần Thanh Hiếu (`hieutt85@fpt.edu.vn`)**: Quản lý và lập báo cáo môn Tin học.
   - **Trưởng môn Sinh học - Cô Trương Minh Phương (`phuongtm30@fpt.edu.vn`)**: Quản lý và lập báo cáo môn Sinh học.
   - **Trưởng môn Hóa học - Cô Nguyễn Tuyền Muội (`muoint@fpt.edu.vn`)**: Quản lý và lập báo cáo môn Hóa học.
   - **Trưởng môn Vật lý - Thầy Nguyễn Võ Anh Duy (`duynva3@fpt.edu.vn`)**: Quản lý và lập báo cáo môn Vật lý.

2. **📈 Thống kê & Phổ điểm trực quan (Chart.js)**:
   - Thống kê ĐTB, Trung vị, Min, Max, Độ lệch chuẩn (SD), Tỉ lệ đạt (≥ 5.0).
   - Biểu đồ histogram phổ điểm toàn khối và từng lớp.
   - Biểu đồ tỉ lệ phân loại 4 tầng (Giỏi, Khá, Trung bình, Yếu).
   - Biểu đồ so sánh chênh lệch giữa các lớp trong cùng khối.

3. **🏷️ Phân tầng 4 nhóm học sinh chuẩn**:
   - 🟢 **Giỏi** (Điểm ≥ 8.0)
   - 🔵 **Khá** (6.5 – 7.9)
   - 🟡 **Trung bình** (5.0 – 6.4)
   - 🔴 **Yếu** (< 5.0)
   - *Phát hiện nhóm cận tầng (thiếu ≤ 0.5 điểm) để giao mục tiêu bứt phá.*

4. **💡 Kế hoạch giải pháp sư phạm chuyên sâu**:
   - **Nhóm Yếu**:
     - ⭐ **Lớp VIP nâng hạng** (4.5 – 4.9 điểm): Ôn tập trọng tâm cấp tốc để đạt chuẩn.
     - 📚 **Phụ đạo tập trung** (3.0 – 4.4 điểm): Lớp học 2 buổi/tuần, vá lỗ hổng kiến thức.
     - 👨‍🏫 **Kèm cặp 1-1 / Đôi bạn cùng tiến** (< 3.0 điểm): Gia sư bạn học + giáo viên kèm riêng.
   - **Nhóm Giỏi**:
     - 🌐 **Tự học trên nền tảng Website**: Ngân hàng đề thi vận dụng cao, bài giảng chuyên sâu.
     - 🏆 **Bồi dưỡng Đội tuyển HSG & Dự án STEM**: Tham gia các kỳ thi học thuật lớn.
     - 🤝 **Mentor trợ giảng**: HS giỏi đồng hành kèm cặp các bạn yếu trong lớp.

5. **📥 Xuất báo cáo đa định dạng**:
   - 📄 **Word (.doc)**: Mẫu văn bản hành chính chuẩn Bộ GD&ĐT / FPT Education với tiêu ngữ, bảng biểu và chữ ký Tổ trưởng/Trưởng môn.
   - 📑 **PDF**: Tối ưu sẵn cho in ấn khổ A4 nộp Ban Giám Hiệu.
   - 📊 **Excel (.xlsx)**: Đầy đủ 4 sheet (Tổng quan, So sánh lớp, Danh sách học sinh, Kế hoạch phân bổ giải pháp).

---

## 🚀 Hướng Dẫn Đẩy Lên GitHub & Triển Khai GitHub Pages

Website được thiết kế **Single-File (HTML/CSS/JS thuần)**, không cần cài đặt Node.js hay build server phức tạp. Bạn có thể triển khai lên **GitHub Pages** hoàn toàn miễn phí.

### Bước 1: Khởi tạo Git trong thư mục dự án

Mở **Terminal** hoặc **PowerShell** tại thư mục `d:\baocaomonhoc`:

```bash
git init
git add .
git commit -m "feat: Khoi tao website EduReport phan tich diem va phan tang hoc sinh"
git branch -M main
```

### Bước 2: Tạo Repository mới trên GitHub

1. Truy cập [github.com](https://github.com) và đăng nhập.
2. Bấm nút **New repository** (hoặc dấu `+` góc phải trên).
3. Đặt tên kho lưu trữ (Ví dụ: `baocaomonhoc` hoặc `edureport-khtn`).
4. Để chế độ **Public** rồi bấm **Create repository**.

### Bước 3: Đẩy mã nguồn lên GitHub

Chạy lệnh liên kết và đẩy code lên (thay `YOUR_USERNAME` và `YOUR_REPO` bằng tên tài khoản và tên repo của bạn):

```bash
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

### Bước 4: Bật GitHub Pages để chạy Website Online

1. Vào Repository vừa tạo trên GitHub, chọn thẻ **Settings** (Cài đặt).
2. Ở thanh menu bên trái, chọn mục **Pages**.
3. Tại phần **Build and deployment** -> **Branch**:
   - Chọn nhánh: `main`
   - Chọn thư mục: `/(root)`
   - Bấm **Save**.
4. Chờ khoảng 1-2 phút, GitHub sẽ cấp cho bạn đường link website trực tuyến:
   `https://YOUR_USERNAME.github.io/YOUR_REPO/`

---

## 👥 Danh Sách Tài Khoản Phân Quyền Theo Bộ Môn

| Vai trò | Họ và tên | Email | Phạm vi phụ trách & Quyền hạn |
|---|---|---|---|
| 👑 **Tổ trưởng Tổ KHTN** | **Thầy Thạch Thanh Tâm** | `tamtt48@fpt.edu.vn` | **Toàn quyền cả 5 môn** (Toán, Tin học, Sinh học, Hóa học, Vật lý) & Xuất báo cáo tổng hợp |
| 📐 **Trưởng môn Toán** | **Cô Nguyễn Hồng Chi** | `chinh10@fpt.edu.vn` | Quản lý & Lập báo cáo bộ môn Toán |
| 💻 **Trưởng môn Tin học** | **Thầy Trần Thanh Hiếu** | `hieutt85@fpt.edu.vn` | Quản lý & Lập báo cáo bộ môn Tin học |
| 🧬 **Trưởng môn Sinh học** | **Cô Trương Minh Phương** | `phuongtm30@fpt.edu.vn` | Quản lý & Lập báo cáo bộ môn Sinh học |
| ⚗️ **Trưởng môn Hóa học** | **Cô Nguyễn Tuyền Muội** | `muoint@fpt.edu.vn` | Quản lý & Lập báo cáo bộ môn Hóa học |
| ⚡ **Trưởng môn Vật lý** | **Thầy Nguyễn Võ Anh Duy** | `duynva3@fpt.edu.vn` | Quản lý & Lập báo cáo bộ môn Vật lý |

---

*Phát triển cho Tổ Khoa Học Tự Nhiên · Trường THPT FPT*
