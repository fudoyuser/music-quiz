# Đố Vui Giai Điệu

Thư viện quiz kiến thức âm nhạc, sắp xếp theo **ca sĩ → bài hát**. Mỗi câu hỏi thuộc một trong ba nhóm:

- **Nội dung**: lời bài hát, thông điệp, câu chuyện bài hát kể.
- **Giọng điệu**: thể loại, chất giọng, cảm xúc và không khí của bài.
- **Bối cảnh MV**: nơi quay, đạo diễn, diễn viên, chi tiết hình ảnh trong MV.

Ca sĩ hiện có: Sơn Tùng M-TP, Hoàng Thùy Linh, Taylor Swift, Adele (mỗi người 2 bài).

## Thêm ca sĩ hoặc bài hát

Mở `index.html`, sửa mảng `ARTISTS`. Mỗi ca sĩ có `id`, `name`, `meta`, `songs`; mỗi bài hát có `id`, `title`, `year`, `album`, `sources`, `questions`.
Mỗi câu hỏi: `t` (nhóm: `nd` nội dung, `gd` giọng điệu, `mv` bối cảnh MV), `q` (câu hỏi), `a` (đáp án đúng), `w` (3 đáp án sai), `e` (giải thích).
Nếu ca sĩ mới cần bảng màu riêng, thêm một khối CSS `[data-theme="<id>"]`.
