# Hướng dẫn SOP AI

Trang tra cứu SOP theo mã lỗi (66 mã, 6 dòng máy) mà AI dùng để chấm vé CCTS.

⚠️ **Nội bộ ChargeCore** — không sao chép hoặc phân phối ra ngoài khi chưa được phép. Repo để **public + GitHub Pages** theo quyết định của chủ repo ngày 27/11/2026 (để có link xem); ai có link đều đọc được.

`index.html` là file SINH RA, không sửa tay: sửa `src/ccts-doc/SOP_TatCa.md` trong ccts-app, chạy `node scripts/gen-sop-ai.mjs` rồi `node scripts/gen-sop-guide.mjs`.

Bản này dựng 27/11/2026 từ nhánh `feat/sop-c6100-v6-voms-desc` (PR Shymon2/ccts-app#31): S/N pin lỗi · C6100 theo lưu đồ v6 · khuôn mô tả VOMS của VF.
