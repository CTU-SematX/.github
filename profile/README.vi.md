<div align="center">

# 🏙️ CTU-SematX

### Xây Dựng Tương Lai Thành Phố Thông Minh

[![NGSI-LD](https://img.shields.io/badge/NGSI--LD-Tương%20thích-blue?style=for-the-badge)](https://www.etsi.org/deliver/etsi_gs/CIM/001_099/009/01.04.01_60/gs_cim009v010401p.pdf)
[![Mã Nguồn Mở](https://img.shields.io/badge/Mã%20Nguồn%20Mở-❤️-red?style=for-the-badge)](https://github.com/CTU-SematX)
[![Giấy Phép](https://img.shields.io/badge/Giấy%20Phép-MIT-green?style=for-the-badge)](LICENSE)

**Tiếng Việt** | [English](README.md)

</div>

---

## 👋 Giới Thiệu

**CTU-SematX** là một tổ chức nghiên cứu và phát triển tập trung vào xây dựng các giải pháp thành phố thông minh sử dụng công nghệ ngữ nghĩa và tiêu chuẩn NGSI-LD. Chúng tôi phát triển các công cụ và framework mã nguồn mở giúp các thành phố quản lý tài sản, cơ sở hạ tầng và dịch vụ một cách hiệu quả.

> 🎯 **Sứ Mệnh**: Tạo ra các giải pháp thành phố thông minh đổi mới, có khả năng tương tác và mở rộng, tận dụng sức mạnh của công nghệ web ngữ nghĩa và dữ liệu liên kết.

---

## 📦 Các Dự Án

<table>
<tr>
<td width="50%">

### 🏗️ [LegoCity](https://github.com/CTU-SematX/LegoCity)

**Template & Điều Phối Thành Phố Thông Minh**

[![Phiên bản](https://img.shields.io/github/v/release/CTU-SematX/LegoCity?label=phiên%20bản)](https://github.com/CTU-SematX/LegoCity/releases)
![Giấy phép](https://img.shields.io/badge/giấy%20phép-MIT-green)
![Stars](https://img.shields.io/github/stars/CTU-SematX/LegoCity?style=social)

Template Smart City nhẹ cho thử nghiệm nhanh và giảng dạy. Stack hoàn chỉnh với server mẫu, dữ liệu mở (giao thông, cảm biến lũ, trạm thời tiết, chất lượng không khí), và tích hợp Mapbox.

`TypeScript` `Bun` `Elysia` `Docker`

</td>
<td width="50%">

### 🎨 [Lego-Dashboard](https://github.com/CTU-SematX/Lego-Dashboard)

**Nền Tảng Dashboard Low-Code**

[![Phiên bản](https://img.shields.io/github/v/release/CTU-SematX/Lego-Dashboard?label=phiên%20bản)](https://github.com/CTU-SematX/Lego-Dashboard/releases)
![Giấy phép](https://img.shields.io/badge/giấy%20phép-MIT-green)
![Stars](https://img.shields.io/github/stars/CTU-SematX/Lego-Dashboard?style=social)

Dashboard hiện đại, low-code cho ứng dụng NGSI-LD thành phố thông minh. Thay thế WireCloud (FIWARE) với tạo nội dung AI, multi-tenancy, và import Smart Data Models.

`Next.js` `React 19` `PayloadCMS` `MongoDB`

</td>
</tr>
<tr>
<td width="50%">

### 🔒 [Orion-Nginx](https://github.com/CTU-SematX/Orion-Nginx)

**Cổng API Bảo Mật**

[![Phiên bản](https://img.shields.io/github/v/release/CTU-SematX/Orion-Nginx?label=version)](https://github.com/CTU-SematX/Orion-Nginx/releases)
![Giấy phép](https://img.shields.io/badge/giấy%20phép-MIT-green)
![Stars](https://img.shields.io/github/stars/CTU-SematX/Orion-Nginx?style=social)

Cổng API bảo mật để bảo vệ FIWARE Orion-LD context broker với xác thực JWT (HS256) và kiểm soát truy cập dựa trên IP. Mô hình bảo mật hai lớp.

`OpenResty` `Lua` `Docker` `MongoDB`

</td>
<td width="50%">

### 📚 [Lego-Doc](https://github.com/CTU-SematX/Lego-Doc)

**Trung Tâm Tài Liệu**

[![Phiên bản](https://img.shields.io/github/v/release/CTU-SematX/Lego-Doc?label=phiên%20bản)](https://github.com/CTU-SematX/Lego-Doc/releases)
![Giấy phép](https://img.shields.io/badge/giấy%20phép-MIT-green)
![Stars](https://img.shields.io/github/stars/CTU-SematX/Lego-Doc?style=social)

Tài liệu chính thức cho hệ sinh thái LegoCity. Hướng dẫn toàn diện về cài đặt, cấu hình, phát triển, tích hợp AI, và triển khai. Song ngữ (EN/VI).

`VitePress` `Markdown` `GitHub Pages`

</td>
</tr>
</table>

---

## 🔧 Công Nghệ Sử Dụng

<div align="center">

|       Danh mục       | Công nghệ                                       |
| :------------------: | :---------------------------------------------- |
|  **🌐 Tiêu chuẩn**   | NGSI-LD • FIWARE • Smart Data Models            |
|    **⚡ Runtime**    | Bun • Node.js 20+ • Docker                      |
|   **🎨 Frontend**    | Next.js 16 • React 19 • Tailwind CSS • Radix UI |
|    **📦 Backend**    | Elysia • PayloadCMS • Orion-LD Context Broker   |
|    **🔒 Bảo mật**    | OpenResty • JWT (HS256) • IP Whitelisting       |
| **🗄️ Cơ sở dữ liệu** | MongoDB (Replica Set) • PostgreSQL              |
|   **📝 Ngôn ngữ**    | TypeScript • Lua • Python                       |
|   **📚 Tài liệu**    | VitePress • Markdown                            |

</div>

---

## 🚀 Bắt Đầu Nhanh

```bash
# Clone template chính
git clone https://github.com/CTU-SematX/LegoCity.git
cd LegoCity

# Khởi động toàn bộ stack với Docker
docker compose up -d

# Truy cập các dịch vụ
# Dashboard: http://localhost:3000
# API Docs:  http://localhost:8004/swagger
```

📖 **Tài liệu đầy đủ**: [ctu-sematx.github.io/Lego-Doc](https://ctu-sematx.github.io/Lego-Doc/)

---

## 🤝 Tham Gia Cùng Chúng Tôi

Chúng tôi hoan nghênh đóng góp từ cộng đồng! Đây là cách bạn có thể giúp đỡ:

<div align="center">

|    ⭐ Star    |  🐛 Issues  |  🔀 PRs  |       📖 Docs       |
| :-----------: | :---------: | :------: | :-----------------: |
| Star các repo | Báo cáo lỗi | Gửi code | Cải thiện hướng dẫn |

</div>

---

## 📫 Liên Hệ

<div align="center">

[![Email](https://img.shields.io/badge/Email-ctusematx%40gmail.com-red?style=for-the-badge&logo=gmail)](mailto:ctusematx@gmail.com)
[![Discord](https://img.shields.io/badge/Discord-Tham%20Gia-5865F2?style=for-the-badge&logo=discord)](https://discord.gg/gREP69pH)
[![Tài liệu](https://img.shields.io/badge/Tài%20Liệu-Đọc%20Ngay-blue?style=for-the-badge&logo=gitbook)](https://ctu-sematx.github.io/Lego-Doc/)

</div>

---

<div align="center">

**Xây dựng với ❤️ bởi Đội ngũ CTU-SematX**

<sub>© 2025 CTU-SematX • Đại học Cần Thơ</sub>

</div>
