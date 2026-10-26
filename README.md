# CHECKXML PRO - Bản phát hành

Kho này dùng cho tính năng **tự cập nhật** của CHECKXML PRO.

- `version.json`: phiên bản mới nhất, link tải và mã SHA-256 của file cài đặt.
- File cài đặt `CHECKXML_PRO_Setup.exe` được đăng ở mục **[Releases](https://github.com/thnguyen1891-coder/CHECKXML-Releases/releases)**, không lưu trong git.

## Tải về

Vào mục **Releases**, chọn bản mới nhất và tải `CHECKXML_PRO_Setup.exe`.

## Quy trình phát hành bản mới

1. Build bằng `build_installer.bat` trong dự án CHECKXML.
2. Tạo Release mới với tag `v<phiên bản>` (vd `v20261026.2`), upload `CHECKXML_PRO_Setup.exe`.
3. Cập nhật `version.json` (version, url, sha256) rồi commit và push.
