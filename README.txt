MY FISH WORLD - BẢN HTML ĐÃ GẮN SPRITES

Chạy: mở thư mục bằng VS Code -> Live Server, hoặc: python -m http.server 8000
Truy cập http://localhost:8000/

assets/fish/: ảnh cá
assets/decor/: đồ trang trí

Các ID được ánh xạ trong SPRITE_FILES trong index.html. Đổi tên ảnh hoặc thay ID bằng cách sửa bảng đó.
Những loài/đồ trang trí không có ảnh sẽ tiếp tục sử dụng hàm Canvas gốc.

Bản HTML này vẽ UI và bể cá động bằng Canvas; sprite mới được dùng cả trong Canvas và danh sách HTML.
PNG được cắt từ ảnh mockup nên kích thước nhỏ; có thể thay bằng PNG lớn hơn cùng tên.

TEST UPDATE (30/10/2026):
- Chợ cá > Cá thường: luôn có Cá hề để mua (kể cả save cũ).
- Coin test: tối thiểu 99,999,999 xu; gem test: tối thiểu 99,999 kim cương.
- Giữ lại dữ liệu tiến trình localStorage; không xóa save.
- Các hiệu ứng 8 frame cá hề và 13 frame cần Hỏa Long vẫn giữ nguyên.
- Đây là bản TEST, không dùng cơ chế cộng tiền này cho bản production.
