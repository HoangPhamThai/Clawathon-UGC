<div align="center">

# UGC

### *User-Generated Content Platform*

Nền tảng quản lý nội dung end-to-end — từ ý tưởng đến nghiệm thu, trên một hệ thống thống nhất.

<br/>

`Sáng tạo` &nbsp;·&nbsp; `Kiểm duyệt` &nbsp;·&nbsp; `Nghiệm thu` &nbsp;·&nbsp; `Thống kê`

</div>

---

## ✦ Tổng quan

**UGC** là giải pháp platform end-to-end giúp quản lý nội dung — kết nối mọi bên liên quan trong cùng một luồng công việc thông minh, minh bạch và có AI đồng hành.

---

## ✦ Ba vai trò — Một nền tảng

### ✍️ Nhà sáng tạo nội dung

Tập trung vào sáng tạo, không bị vướng thủ tục.

- Quản lý thông minh cho các bài viết
- Giảm thủ tục kiểm tra đối soát thủ công
- Theo dõi tiến trình kiểm duyệt và nghiệm thu theo thời gian thực

</td>
<td width="33%" valign="top">

### 🔍 Nhà kiểm duyệt nội dung

Kiểm duyệt nhanh hơn, chính xác hơn.

- Quản lý trạng thái và tiến trình kiểm duyệt tập trung
- Trao đổi trực tiếp với nhà sáng tạo nội dung
- AI hỗ trợ kiểm duyệt theo quy tắc tùy chỉnh

</td>
<td width="33%" valign="top">

### 📊 Quản trị viên

Toàn cảnh hệ thống trong tầm tay.

- Thống kê, tổng hợp và truy vấn thông tin bằng AI
- Số hóa quy trình tạo biên bản nghiệm thu
- Giảm thiểu nhập tay và kiểm tra dữ liệu thủ công

</td>
</tr>
</table>

---

## Cấu trúc dự án

Repo này là meta-repository, chứa các submodule sau:

| Thư mục | Repository | Mô tả |
|---------|------------|-------|
| `agents/` | [UGC-agent](https://github.com/HoangPhamThai/UGC-agent) | AI agents hỗ trợ kiểm duyệt và tự động hóa |
| `frontend/` | [UGC](https://github.com/HoangPhamThai/UGC) | Giao diện người dùng |
| `backend/` | [UGC-backend](https://github.com/HoangPhamThai/UGC-backend) | API và logic nghiệp vụ |

## Clone dự án

```bash
git clone --recurse-submodules https://github.com/HoangPhamThai/Clawathon-UGC.git
cd Clawathon-UGC
```

Nếu đã clone mà chưa kéo submodule:

```bash
git submodule update --init --recursive
```
