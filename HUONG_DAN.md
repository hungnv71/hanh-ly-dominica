# Hành lý Dominica – app checklist Android

Checklist đồ mang sang Dominica: 2 vali ký gửi × 23 kg, xách tay 7 kg. App chạy offline, dữ liệu lưu trong bộ nhớ app trên điện thoại.

## Chức năng
- **Đồ mang theo**: 75 món chia 9 nhóm. Chạm để tick đã xếp; lọc theo Vali 1 / Vali 2 / Xách tay / Người; nút "Ẩn đã xếp".
- **Cân hành lý**: tự cộng kg từng vali (tính cả vỏ vali) so với giới hạn, báo vàng khi còn dưới 1,5 kg, đỏ khi vượt.
- **Nút ⋯**: sửa số lượng, kg, vị trí, đánh dấu "Không mang". **+ Thêm món** để thêm đồ ngoài danh sách.
- **Trước bay 24h**: 12 việc, tick 2 lần (tối hôm trước và trước khi đi).
- Nút Back của Android: đóng cửa sổ sửa → về tab đầu → thoát app.

## Tạo APK
Mỗi lần đẩy code lên nhánh `main`, GitHub Actions tự build. Tải file `HanhLyDominica.apk` ở mục **Releases** của repo (hoặc tab Actions → lần chạy → Artifacts).

## Cài lên điện thoại
Mở file APK trên Android, cho phép "Cài ứng dụng không rõ nguồn gốc" nếu máy hỏi.

Lưu ý: gỡ app sẽ xoá dữ liệu tick. Cài bản mới đè lên bản cũ thì dữ liệu vẫn giữ.
