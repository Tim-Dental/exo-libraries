# exo-libraries

Kho thư viện exocad DentalCAD dùng cho ứng dụng **Exo Library Hub** — giúp kỹ thuật viên
tra cứu và cài thư viện nhanh, không phải đi tìm trên từng trang của hãng.

Library repository for the **Exo Library Hub** app — lets dental technicians look up and
install exocad DentalCAD libraries quickly instead of searching each manufacturer's site.

| Release | Nội dung / Contents |
|---|---|
| `tooth-v1` | Thư viện răng / Tooth libraries |
| `implant-v1` | Thư viện implant + analog Model Creator / Implant + Model Creator analog libraries |

Danh mục mỗi release: `manifest.json`. Mỗi gói `.zip` giải nén thẳng vào thư mục `library` của exocad.

## Nguồn & bản quyền

- **Thư viện implant và analog (`implant-v1`)** là thư viện chính thức do **exocad GmbH** và
  các **hãng implant** phát hành miễn phí, công khai (bộ exocad Intraoral Scanbody và
  Model Creator Lab Analog). Repo này chỉ gom lại để tra cứu nhanh — **nguyên bản, không
  chỉnh sửa, không giải mã, giữ nguyên chữ ký số**. Hãng của từng thư viện ghi ở trường
  `Supplier` trong `config.xml` và trường `vendor` trong `manifest.json`.
- **Thư viện răng (`tooth-v1`)** thuộc tác giả / nhà phát hành tương ứng.
- Mọi quyền thuộc exocad GmbH, các hãng implant và tác giả thư viện. Repo không thu phí và
  không nhận quyền sở hữu với bất kỳ thư viện nào.
- Exo Library Hub **không đọc, không giải mã** file `.sdfa` hay bất kỳ định dạng mã hoá nào.
- Thư viện do người dùng tự tạo trong app (đánh dấu `-ELH-`) **không** được đưa lên repo này.

## Source & copyright

- **Implant and analog libraries (`implant-v1`)** are official libraries published free of
  charge by **exocad GmbH** and the respective **implant manufacturers** (exocad Intraoral
  Scanbody and Model Creator Lab Analog sets). This repo only aggregates them for quick
  lookup — **unmodified, not decrypted, digital signatures intact**. The manufacturer of each
  library is given by `Supplier` in `config.xml` and `vendor` in `manifest.json`.
- **Tooth libraries (`tooth-v1`)** belong to their respective authors / publishers.
- All rights remain with exocad GmbH, the implant manufacturers and the library authors.
  This repo charges nothing and claims no ownership of any library.
- Exo Library Hub **does not read or decrypt** `.sdfa` or any other encrypted format.
- User-created libraries (marked `-ELH-`) are **never** published here.

## Yêu cầu gỡ / Removal requests

Hãng, tác giả hoặc chủ sở hữu muốn gỡ thư viện của mình, xin liên hệ — chúng tôi gỡ ngay.

Manufacturers, authors or rights holders who want their libraries removed, please contact
us — we will remove them promptly.

📧 justim.hoangvu@gmail.com
