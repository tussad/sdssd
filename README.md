# IMPASTO HORIZON — 3D Painterly Black Hole Exploration Game

Một dự án web game khám phá thế giới mở 3D chạy trực tiếp trên trình duyệt (WebGL / Three.js + Custom GLSL Shaders + Web Audio API), kết hợp tinh hoa nghệ thuật sơn dầu 3D của **Impasto Cape** và bầu không khí điện ảnh vũ trụ của **The Horizons (Aurum & Viola)**.

## Điểm nổi bật

- **Hố đen Gargantua (Custom GLSL Shader)**: Mô phỏng chân trời sự kiện, đĩa bồi tụ phát sáng xoáy động, hiệu ứng thấu kính hấp dẫn (gravitational lensing) và dải sao xoay chậm.
- **14.400 nét cọ sơn dầu 3D Impasto (Instanced Rendering)**: 12.000 nét cỏ/lúa mì/hoa tím uốn lượn theo gió (tự động rẽ ra khi nhân vật đi qua) + 2.400 nét cọ bầu trời xoáy kiểu Van Gogh.
- **4 Thế giới chuyển cảnh điện ảnh mượt mà (`1`–`4`)**:
  1. **Aurum Horizon**: Cánh đồng lúa mì vàng, ngôi nhà gỗ sáng đèn và xe bán tải trước hố đen hổ phách.
  2. **Viola Cosmos**: Cánh đồng hoa tím bạt ngàn dưới vòng cung sáng chói.
  3. **Starry Cobalt**: Đêm xanh cobalt kiểu Van Gogh, ngọn hải đăng và sóng biển phản chiếu.
  4. **Crimson Tempest**: Bão đỏ rực quét qua cối xay gió với gió mạnh.
- **Thanh trượt so sánh X-Ray Wireframe (`X`)**: Kéo trực tiếp giữa màn hình để so sánh hình học 3D nguyên thủy (Wireframe Cyan) và tranh sơn dầu Impasto thời gian thực.
- **Ống kính điện ảnh (24mm – 85mm) & HUD khoa học viễn tưởng**: Điều chỉnh tiêu cự mượt mà, hiển thị độ cao (`ALT`), khoảng cách chân trời (`Rs`), thời gian, FPS và số nét cọ.
- **Gameplay & Nhạc nền tự sinh**: Điều khiển phi hành gia áo choàng phát sáng thu thập 12 Mảnh Ánh Sáng (*Lumen Shards*) để mở khóa sự kiện *Singularity Bloom* và chế độ nhảy không trọng lực, đi kèm nhạc nền tổng hợp Piano + Sáo Ambient (Web Audio API, không cần file âm thanh ngoài).

## Điều khiển

| Phím / Thao tác | Chức năng |
| --- | --- |
| `W A S D` / Phím mũi tên | Di chuyển (hỗ trợ D-pad cảm ứng trên di động) |
| `Shift` | Chạy nhanh / lướt |
| `Space` | Nhảy trọng lực thấp |
| `Kéo chuột` / Chạm kéo | Xoay camera 360° |
| `Cuộn chuột` / Thanh Lens | Zoom tiêu cự 24mm – 85mm |
| `1` – `4` | Chuyển nhanh giữa 4 thế giới |
| `X` | Bật/tắt chế độ kéo so sánh X-Ray Wireframe |
| `C` | Bật/tắt chế độ quay camera điện ảnh (Orbit) |
| `M` | Bật/tắt âm thanh |

## Cách đưa lên GitHub Pages (Miễn phí, 1 phút)

1. Tạo một repository mới trên [GitHub](https://github.com/new) (ví dụ: `impasto-horizon`).
2. Giải nén toàn bộ thư mục này và tải lên repository (gồm `index.html`, `README.md`, `LICENSE`, `.nojekyll`).
3. Vào **Settings → Pages → Build and deployment → Source: Deploy from a branch**, chọn nhánh `main` và thư mục `/ (root)` rồi nhấn **Save**.
4. Chờ khoảng 1 phút và truy cập đường dẫn `https://<username>.github.io/impasto-horizon/`.

## Giấy phép

Phát hành theo giấy phép MIT — tự do tùy biến, mở rộng và chia sẻ.
