# PNHL Auto (com.pnhl.auto)

Bộ công cụ tự động hóa: Tới / Lùi / Trái / Phải / Nhảy (bật-tắt độc lập từng nút).

## Build APK
**Cách 1 – Android Studio:** File > Open thư mục này > Build > Build APK(s).
APK nằm ở `app/build/outputs/apk/debug/app-debug.apk`.

**Cách 2 – GitHub Actions:** push lên GitHub, vào tab Actions > Build APK > tải artifact.

**Cách 3 – dòng lệnh:** có Gradle 8.7 + JDK 17 + Android SDK 34: `gradle assembleDebug`

## Sử dụng
1. Cài APK, mở app > "Bật dịch vụ Trợ năng" > bật PNHL Auto.
2. Bảng điều khiển nổi sẽ hiện ra (kéo bằng ✥).
3. Mở game, bấm 🎯 Joystick rồi chạm vào tâm cần điều hướng; bấm 🎯 Nút nhảy rồi chạm vào nút nhảy.
4. Chọn các nút muốn bật (xanh = bật), bấm ▶ CHẠY.
