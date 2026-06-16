<div align="center">

# NodeZ Hub

### *UGC Quality control & Payment Automation*

Nền tảng quản lý nội dung end-to-end — từ ý tưởng đến nghiệm thu, trên một hệ thống thống nhất.

</div>

---

## ✦ Tổng quan

**NodeZ Hub** trên GreenNode Agent Base giúp chuẩn hóa quy trình UGC từ duyệt content đến xây dựng database để tự động hóa nghiệm thu và thanh toán nhờ 4 tính năng

- AI tự động trích xuất metrics từ link bài đăng: Hệ thống tự trích xuất view, like, comment, ngày đăng trực tiếp từ link bài đăng.Không nhập tay, không sai lệch.
- Tự động tạo BBNT: Một click, BBNT hoàn chỉnh được tạo ra, đúng mã sản phẩm, đúng đơn giá theo rate card, đúng cấu trúc. Gửi thẳng đến creator.
- AI Chatbot: Admin và creator hỏi trực tiếp về trạng thái duyệt, số liệu, lịch sử thanh toán, không cần mở file, không cần hỏi qua lại.
- Email báo cáo tự động: Kết thúc mỗi kỳ, creator nhận email về trạng thái BBNT, rõ ràng, có thể truy vết.


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

## Account test

- Account cho nhà kiểm duyệt: qc@example.com, password: qcqc1234
- Account cho nhà quản trị: admin@example.com, password: admin123
- Account cho nhà sáng tạo nội dung: đăng ký trên app.