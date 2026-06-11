# Zoro

**Che dữ liệu định danh (PII) tiếng Việt — xử lý 100% trên máy, không gửi gì ra mạng.**

Dành cho kế toán / tư vấn tài chính / doanh nghiệp cần đưa dữ liệu cho AI (ChatGPT, Claude…)
hoặc chia sẻ ra ngoài mà không lộ thông tin khách hàng.

## Tải về

Tải bản mới nhất ở mục **[Releases](https://github.com/nguyendangminh/zoro-app/releases/latest)**.

| Nền tảng | File | Ghi chú |
|---|---|---|
| **macOS** (Intel + Apple Silicon) | `Zoro-macOS.dmg` | Đã ký Developer ID + notarize — mở chạy bình thường. |
| **Windows** (64-bit) | `zoro-amd64-installer.exe` | Chưa ký số → SmartScreen sẽ cảnh báo; bấm *More info → Run anyway*. |

Mỗi file kèm `.sha256` để kiểm tra toàn vẹn.

## Tính năng

- Che PII trong **văn bản dán**, **Excel (.xlsx)** và **Word (.docx)** — giữ nguyên công thức
  và con số tài chính (doanh thu, lương, số dư…).
- **Round-trip:** khôi phục giá trị thật từ câu trả lời của AI.
- Có sẵn **file ví dụ** trong app để thử ngay (nút "Dùng file ví dụ" / "Dùng văn bản ví dụ").
- Báo cáo audit sau mỗi lần che; trường mơ hồ được đánh dấu "nghi ngờ", không tự che.

## Quyền riêng tư

Mọi xử lý diễn ra ngay trên máy bạn. Zoro **không** gửi dữ liệu ra mạng dưới bất kỳ hình thức nào.

> ⚠️ Công cụ hỗ trợ phát hiện PII, **không đảm bảo phát hiện 100%**. Vui lòng kiểm tra lại trước khi gửi.
