# Audit & Report

Ứng dụng macOS giúp audit thiết kế/sản phẩm từ ảnh chụp màn hình, file Figma hoặc cấu trúc web — chấm điểm và tổng hợp thành báo cáo trong vài phút. Chạy trên máy của bạn bằng chính tài khoản Claude.ai Pro/Max đã đăng nhập.

## Tải về

[**⬇ Tải bản mới nhất cho macOS (Apple Silicon)**](https://github.com/kitbui1504/Report-hub-Release/releases/latest)

Phiên bản hiện tại: **v3-1-07-10**. Các bản cũ và ghi chú thay đổi xem ở trang [Releases](https://github.com/kitbui1504/Report-hub-Release/releases).

## Yêu cầu hệ thống

- macOS trên chip Apple Silicon (M1/M2/M3...). **Chưa hỗ trợ Mac Intel.**
- [Claude Code CLI](https://claude.com/claude-code) đã cài và đăng nhập bằng tài khoản Claude.ai Pro/Max. Chưa có cũng không sao: bấm **Kết nối AI** trong app để cài/đăng nhập.

## Cài đặt

1. Tải file `.dmg`, mở lên và kéo **Audit & Report** vào `Applications`.
2. App **chưa được Apple ký** nên lần mở đầu macOS sẽ chặn với thông báo "không thể mở vì không xác định được nhà phát triển". Chọn một trong hai cách:
   - Chuột phải (hoặc Control‑click) vào app trong `Applications` → **Open** → xác nhận **Open** lần nữa.
   - Hoặc mở Terminal và chạy:
     ```
     xattr -cr "/Applications/Audit & Report.app"
     ```
3. Mở app và bấm **Kết nối AI** nếu máy chưa đăng nhập Claude.

## Tính năng

8 loại hình audit: Quick UX audit, Figma heatmap audit, JTBD framework, User journey map, Heuristic evaluation, Accessibility audit, UX Writing audit, Competitive audit.

Audit có thể tạo từ đường link, ảnh chụp màn hình hoặc Figma MCP. Báo cáo lưu lại, chỉnh sửa được và xuất PDF.

## Dữ liệu & quyền riêng tư

Report mới mặc định lưu **cục bộ trên máy bạn**. Dữ liệu thiết kế không được gửi lên server để phân tích. Online Database là tuỳ chọn, cần license key do admin cấp (xem **Cài đặt** trong app).

## Hỗ trợ

Góp ý hoặc báo lỗi: dat.bui2@mservice.com.vn
