# Hệ thống Smartfarm
*Hướng dẫn chạy script*
```powershell
Get-Content smartfarm-system 
```
- [x] Kiểm tra cảm biến
- [x] Kiểm tra camera
- [ ] Kiểm tra chỉ số
## Bảng thông số phần cứng
|Tên thiết bị|đơn giá|loại storage|
| --- | --- | ---|
|Intel NUC i3|6,200,000|SSD|
|Orange Pi 5|2,300,000|SSD|
|Dell Optiplex Micro|5,400,000|HDD|
## Phân tích hệ thống
Input: là dữ liệu log có trên file log-hethong.log được nhập vào
Process: là quá trình xử lí lọc dữ liệu
Output: báo cáo được lọc xuất ra màn hình
Data: 2026-10-12 08:15:01 [ERROR] sensor-03 Connection TIMEOUT after 30s
Information: Hôm nay hệ  thống  ghi  nhận 8 sự  cố, trong  đó 4 sự  cố  đến  từ  trạm sensor-03.
Knowledge:Quyết  định  thay modem trạm sensor-03 trước  thứ  Sáu
Wisdom:Trạm sensor-03 hay mất  kết  nối  vào  buổi  chiều do sóng  yếu, nên  cần  lắp  thêm  anten


