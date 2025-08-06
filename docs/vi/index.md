![Banner](../assets/banner.png)

# Phân Tích Mối Đe Dọa Của Việc Sideloading

## Những Thông Tin Chính

- Quyền riêng tư và bảo mật mạnh mẽ của iPhone là cực kỳ quan trọng vì tính chất nhạy cảm của dữ liệu cá nhân được lưu trữ trên thiết bị.
- Sideloading (cài đặt ứng dụng bên ngoài App Store) gây ra những mối đe dọa nghiêm trọng đối với mô hình bảo mật này.
- Phần mềm độc hại xuất hiện phổ biến hơn nhiều trên các nền tảng hỗ trợ sideloading (ví dụ: Android có số lượng lây nhiễm cao hơn iOS từ 15–47 lần).
- Các quy trình đánh giá của App Store và cơ chế bảo vệ hệ thống giúp giảm đáng kể nguy cơ phần mềm độc hại.

## Rủi Ro Của Việc Sideloading

- **Gia Tăng Phần Mềm Độc Hại**: Sideloading bỏ qua các kiểm tra của App Store, cho phép cài đặt adware, spyware, trojan, v.v.
- **Lừa Đảo Xã Hội**: Người dùng có thể bị lừa cài đặt các ứng dụng giả mạo giống như ứng dụng thật.
- **Giảm Kiểm Soát Của Người Dùng**: Ứng dụng cài đặt qua sideloading có thể bỏ qua kiểm soát của phụ huynh, tính minh bạch trong theo dõi ứng dụng hoặc các yêu cầu quyền truy cập.
- **Làm Suy Yếu Bảo Mật Nền Tảng**: Có thể yêu cầu công khai API độc quyền hoặc phần nội bộ của hệ điều hành, đe dọa đến kiến trúc bảo mật cốt lõi của iOS.
- **Tác Động Tiêu Cực Bên Ngoài**: Ngay cả người dùng không sideload cũng có thể gặp rủi ro — ví dụ như do sự ép buộc từ doanh nghiệp, ứng dụng giả mạo App Store hoặc yêu cầu công việc.

## Ví Dụ Về Phần Mềm Độc Hại

- **Adware** (HiddenAds, CopyCat): Gây ngập quảng cáo gây khó chịu hoặc lừa đảo cho người dùng.
- **Ransomware** (CryCryptor, MalLocker.B): Mã hóa dữ liệu thiết bị và yêu cầu tiền chuộc.
- **Spyware** (SpyNote, HelloSpy): Theo dõi hoạt động, thu thập dữ liệu riêng tư, được sử dụng trong việc giám sát giữa các cặp đôi.
- **Trojan Ngân Hàng** (BlackRock, Anubis): Đánh cắp thông tin đăng nhập bằng tấn công lớp phủ, thậm chí vượt qua cả xác thực hai yếu tố (2FA).

## Lời Khuyên Từ Chuyên Gia Bảo Mật

> "Chỉ nên cài đặt ứng dụng từ các kho ứng dụng chính thức." — Europol
> "Tránh sideloading trên thiết bị BYOD." — Bộ An ninh Nội địa Hoa Kỳ
> "Ứng dụng bên thứ ba là mối đe dọa bảo mật nghiêm trọng." — Interpol / Kaspersky

## Quan Điểm Của Apple

- Apple hiện đã cho phép sideloading trong doanh nghiệp một cách hạn chế với các kiểm soát nghiêm ngặt.
- Các trường hợp lạm dụng trước đây (ví dụ: ứng dụng Facebook Research, phần mềm gián điệp Goontact) cho thấy các cơ chế này dễ bị lạm dụng như thế nào.
- Việc sideloading phổ biến sẽ làm gia tăng nguy cơ này một cách nghiêm trọng.

## Kết Luận

Sideloading tạo ra rủi ro trên diện rộng đối với người dùng, nhà phát triển và tổ chức. Apple khẳng định rằng điều này sẽ làm suy giảm lòng tin vào nền tảng, mở rộng bề mặt tấn công và làm giảm khả năng bảo vệ quyền riêng tư cho tất cả người dùng — không chỉ những người thực hiện sideloading.

---

## Tài Liệu Gốc

- *Xây Dựng Hệ Sinh Thái Tin Cậy Cho Hàng Triệu Ứng Dụng* (tháng 6 năm 2021)
  -  [apple.com (chính thức)](https://www.apple.com/privacy/docs/Building_a_Trusted_Ecosystem_for_Millions_of_Apps.pdf)
  -  [github.com/lucasditomase (bản sao lưu)](https://github.com/lucasditomase/app-restrictions/blob/main/summary.pdf)

- *Phân Tích Mối Đe Dọa Của Sideloading* (tháng 10 năm 2021)
  -  [apple.com (chính thức)](https://www.apple.com/privacy/docs/Building_a_Trusted_Ecosystem_for_Millions_of_Apps_A_Threat_Analysis_of_Sideloading.pdf)
  -  [github.com/lucasditomase (bản sao lưu)](https://github.com/lucasditomase/app-restrictions/blob/main/threat-analysis.pdf)
