# WORLD_INDEX.md
# MỤC LỤC CÁC THẾ GIỚI NHIỆM VỤ

**Quy tắc đặt mã:** Mỗi thế giới có mã cố định `WORLD_XXX`. Số thứ tự là số thứ tự hồ sơ thế giới trong dự án, không mặc định là số nhiệm vụ của tất cả thành viên.

## 1. Quy tắc đánh số hành trình cá nhân

- Số nhiệm vụ của vợ, chồng và con được tính độc lập.
- Một thế giới có thể là nhiệm vụ thứ mấy khác nhau đối với từng thành viên.
- Không suy ra số nhiệm vụ của người này từ số nhiệm vụ của người khác.
- Thời điểm bắt đầu, kết thúc và thời lượng trải qua nhiệm vụ của từng người có thể khác nhau.
- SYSTEM_BIBLE quy định thời gian tại Tổng bộ và thế giới nhiệm vụ trôi qua đồng bộ 1:1. Quy tắc này không có nghĩa các thành viên phải bắt đầu nhiệm vụ cùng lúc hoặc có cùng tổng thời gian trải nghiệm.
- Không tự đặt thêm tỷ lệ quy đổi thời gian giữa các thành viên.

## 2. Danh mục thế giới

| Mã hồ sơ | Tên tạm | Vị trí trong hành trình | Trạng thái |
|---|---|---|---|
| WORLD_001 | Chưa đặt tên | Nhiệm vụ 1 của vợ; thông tin hành trình của chồng và con chưa xác định | Chờ xây dựng |
| WORLD_002 | Kinh Thành Dưới Màn Mưa | Nhiệm vụ 2 của vợ; nhiệm vụ 8 của chồng; con ở hành trình riêng, khoảng nhiệm vụ đầu | Hồ sơ nền đã tổng hợp; chi tiết tên riêng/bối cảnh đang là thiết kế làm việc |

## 3. Tài liệu riêng

- [WORLD_001.md](./WORLD_001.md) – Hồ sơ thế giới nhiệm vụ thứ nhất.
- [WORLD_002.md](./WORLD_002.md) – Kinh Thành Dưới Màn Mưa, thế giới đoàn tụ của vợ chồng.

## 4. Nguyên tắc quản lý

1. Không gộp nhiều thế giới vào cùng một hồ sơ.
2. Mỗi thế giới chỉ ghi những sự kiện, nhân vật, quy tắc và nhiệm vụ thuộc chính thế giới đó.
3. Quy tắc hệ thống dùng chung đặt tại `SYSTEM_BIBLE.md`; hồ sơ thế giới chỉ dẫn chiếu, không tự viết lại hoặc sửa luật hệ thống.
4. Thông tin đã xác nhận, đề xuất đang thử nghiệm và điểm chưa chốt phải được phân biệt rõ.
5. Khi thay đổi thứ tự hành trình, cập nhật bảng danh mục và hồ sơ liên quan; không đổi mã hồ sơ đã cấp.
