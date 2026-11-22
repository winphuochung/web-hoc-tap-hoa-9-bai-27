# Web/app học tập — Hóa học 9, Bài 27

**Bài 27: Acetic acid**
Môn Khoa học tự nhiên 9 (phân môn Hóa học) — Chương trình GDPT 2018, sách Kết nối tri thức với cuộc sống.

Giáo viên: Lê Văn Thắng — Trường TH và THCS Phước Hưng, xã Nhơn Hội, tỉnh An Giang.

## Nội dung

Web/app học tập 6 phần: Khởi động, Khám phá, Mô phỏng, Sơ đồ tư duy, Luyện tập (10 câu trắc nghiệm tự chấm), Vận dụng.

Mô phỏng gồm:
1. Tính chất hoá học của acetic acid (SGK trang 124) — 5 phép thử với dung dịch acetic acid 10%: quỳ tím hoá đỏ; Mg tan dần + bọt khí H₂; CuO đen tan dần + dung dịch xanh; dung dịch NaOH + phenolphthalein mất màu hồng; đá vôi tan dần + sủi bọt khí CO₂.
2. Phản ứng ester hoá (SGK trang 125) — 4 bước đúng thứ tự: trộn ethylic alcohol + acetic acid đặc, thêm H₂SO₄ đặc, đun trong cốc nước nóng 60–70 °C, đổ sang ống nghiệm nước muối bão hoà → lớp ethyl acetate phía trên, không màu, mùi thơm nhẹ.

Khóa đáp án trắc nghiệm: 1B 2C 3D 4A 5B 6C 7A 8D 9B 10A (BCDABCADBA).

## Trạng thái lưu điểm

**CHỜ /exec** — chưa gắn link Google Sheets. Google đang chặn tạo dự án Apps Script mới nên khóa `hoa9-bai27` chưa có webAppUrl trong `sheets_registry.json`. File giao KHÔNG chứa link `/exec` nào (không bịa URL). Khi deploy xong, parent sẽ patch link Web App vào `index.html` và `.md`; điểm hiện lưu cục bộ trên máy học sinh (localStorage).

## Cách dùng

- Mở file `index.html` bằng trình duyệt bất kì (không cần máy chủ).
- Học sinh đăng nhập bằng Họ tên + Lớp, học 6 phần, làm 10 câu trắc nghiệm rồi nộp bài.
- Sau khi patch link Sheets: điểm tự động lưu về Google Sheets của giáo viên (qua Apps Script Web App, chạy bằng tài khoản giáo viên).

## File trong repo

- `index.html` — web/app hoàn chỉnh, tự chứa (3 ảnh nền + logo nhúng base64).
- `Web_Hoc_Tap_Hoa9_Bai27.md` — bản sao toàn bộ mã nguồn kèm khóa đáp án (round-trip 100% với `index.html`).
- `Code.gs` — Apps Script Web App ghi điểm về tab `KetQua` (deploy sau).
- `assets-flow/` — 3 ảnh nền gốc (1376×768) + logo thầy Lê Văn Thắng (`logo-le-van-thang.png`, 500×500, nền trong suốt).
