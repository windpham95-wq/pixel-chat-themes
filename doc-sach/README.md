# Mọt Sách

Ứng dụng đọc sách tiếng Việt chạy ngay trong trình duyệt, có chú tiểu Mọt làm bạn đọc. Chỉ một tệp `index.html`, không cần cài đặt, không cần tài khoản. Sách và ghi chú được cất trong trình duyệt của bạn và không gửi đi đâu.

## Mở app

- **Trên máy tính:** mở `doc-sach/index.html` bằng Chrome, Edge, Firefox hoặc Safari. Nếu repo bật GitHub Pages, địa chỉ là `https://<tên-tài-khoản>.github.io/pixel-chat-themes/doc-sach/`.
- **Trên điện thoại:** mở địa chỉ GitHub Pages ở trên, rồi chọn *Thêm vào Màn hình chính* (Safari) hoặc *Cài đặt ứng dụng* (Chrome). App mở được cả khi không có mạng.

## Thêm sách

Bấm **Thêm sách** hoặc kéo thả tệp vào cửa sổ.

| Định dạng | Ghi chú |
|---|---|
| `.epub` | Giữ mục lục nhiều cấp, ảnh bìa, chữ nghiêng/đậm, chú thích bật lên (`[1]`, `[1.1]`, `<aside epub:type="footnote">`) |
| `.docx` | Tách chương theo kiểu tiêu đề Heading 1, Heading 2 |
| `.txt`, `.md` | Tự nhận mã UTF-8, UTF-16 và Windows-1258; tự tách chương khi gặp “Chương 1”, “Hồi thứ hai”, “Phẩm thứ ba”, “Quyển IV”, “Lời nói đầu”, tiêu đề `#` |
| `.html` | Trang web đã lưu về máy |

Có thể bấm **Dán văn bản** (hoặc nhấn Ctrl + V ở tủ sách) để biến một đoạn kinh, bài viết vừa chép thành sách mới. Tệp PDF chưa đọc được, hãy chuyển sang EPUB bằng Calibre.

## Đọc êm mắt

- Chữ mặc định Literata cỡ 20px, nền giấy ngà ấm, chữ màu nâu mực (không dùng trắng tinh, đen tuyền).
- Tám nền trang: tự động, giấy ngà, giấy dó, lá sen, hồng đào, ánh nến, đêm trăng, mực đen (OLED).
- **Độ sáng trang** và **Lọc ánh sáng xanh** chỉnh bằng thanh kéo; nút **Đọc đêm** bật cả ba cùng lúc.
- Tám phông chữ hỗ trợ đầy đủ dấu tiếng Việt, tuỳ chọn chữ đậm hơn, giãn dòng, độ rộng trang, căn đều hoặc căn trái, cách dòng hoặc thụt đầu dòng.
- Đọc cuộn dọc hoặc lật trang (chạm mép, vuốt, phím mũi tên).
- Thơ lục bát tự thụt câu sáu chữ; chữ Hán hiển thị bằng Noto Serif TC.
- Đọc to bằng giọng tiếng Việt có sẵn trên máy.

## Học và nghiên cứu

- Bôi đen để tô bốn màu, ghi chú, chép kèm tên sách và chương, tra Wiktionary.
- Đánh dấu trang, tìm trong sách không cần gõ dấu (“tam kinh” ra “Tâm Kinh”).
- Xuất toàn bộ ghi chú ra Markdown để dán vào Word, Notion, Obsidian.
- Đếm thời gian đọc thật, mục tiêu mỗi ngày, chuỗi ngày đọc, biểu đồ bảy ngày.
- Sao lưu và khôi phục toàn bộ sách, ghi chú ra một tệp `.json`.

## Phím tắt

| Phím | Việc |
|---|---|
| `←` `→` | Lật trang, hoặc chuyển chương khi đọc cuộn |
| `T` | Mục lục |
| `F` hoặc `/` | Tìm trong sách |
| `N` | Ghi chú |
| `B` | Đánh dấu trang |
| `A` | Chữ và ánh sáng |
| `Esc` | Đóng bảng, bỏ chọn |

## Sách mẫu đi kèm

Sổ tay hướng dẫn, *Bát Nhã Ba La Mật Đa Tâm Kinh* (Hán văn, phiên âm, dịch nghĩa), sáu bài thơ Thiền Lý – Trần (nguyên văn, phiên âm, dịch nghĩa), 56 câu đầu *Truyện Kiều* và một số ca dao. Các văn bản gốc thuộc phạm vi công cộng; phần dịch nghĩa do Mọt Sách soạn để tham khảo, khi trích dẫn trong nghiên cứu nên đối chiếu với các bản dịch đã xuất bản.

## Ghi nguồn

- [JSZip](https://stuk.github.io/jszip/) 3.10.1 (giấy phép MIT) để mở EPUB và DOCX, kèm trong `vendor/`.
- Phông chữ Baloo 2, Be Vietnam Pro, Mali, Literata, Merriweather, Lora, Noto Serif, Nunito, Noto Serif TC từ Google Fonts (giấy phép SIL Open Font License).
