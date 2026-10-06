# [Vận dụng cơ bản] PHÂN ĐỊNH LẠI 3 VAI TRÒ TRONG ĐỘI RIKKEIGO

> 👤 **Học viên:** Đỗ Hoàng Sơn | **Mã SV:** PTIT-HCM-055
> 🏫 **Môn học:** IT206-K25-Agile-va-Scrum

---

## Phần 1 - Phân tích

Sau khi rà soát 4 quy ước làm việc hiện tại của đội RikkeiGo, mình đã lập bảng phân tích chi tiết để chỉ ra quy ước nào đúng, quy ước nào sai, vai trò nào thực sự chịu trách nhiệm và mối liên hệ của chúng với các triệu chứng mà Đức và đội đang gặp phải.

- Triệu chứng 1: Đức (PO) bị quá tải vì nhiều việc phải chờ anh xử lý (do ôm đồm duyệt code, chọn thư viện bản đồ).
- Triệu chứng 2: Lập trình viên phàn nàn bị bắt làm theo cách kém hiệu quả (do SM can thiệp sâu vào việc phân công thẻ việc, và Developers tự ý đảo lộn Backlog).

| Quy ước | Đúng/Sai | Quyết định này thuộc về vai trò nào & vì sao | Triệu chứng nào ở Bối cảnh do quy ước này gây ra (nếu có) |
| --- | --- | --- | --- |
| QU1. Đức duyệt từng đoạn code và tự chọn thư viện bản đồ cho tính năng đặt xe. | Sai | Thuộc về Developers. Lý do: Đội ngũ phát triển có quyền tự tổ chức và tự quyết định cách triển khai kỹ thuật, lựa chọn công nghệ/thư viện. PO không làm kỹ thuật nên không thể sa đà vào việc duyệt code. | Gây ra triệu chứng Đức bị quá tải vì ôm đồm việc kỹ thuật, làm chậm tiến độ chung. |
| QU2. Để đội làm nhanh hơn, trong buổi Daily Scrum mỗi sáng, Lan giao cụ thể ai làm thẻ việc nào trong ngày. | Sai | Thuộc về Developers. Lý do: Scrum Master là người phục vụ, coach quy trình và gỡ rối, tuyệt đối không ra lệnh hay phân công công việc. Developers phải tự tổ chức và tự nhận việc. | Gây ra triệu chứng lập trình viên thấy bức xúc, phàn nàn vì bị áp đặt cách làm kém hiệu quả. |
| QU3. Đức sắp xếp thứ tự ưu tiên Product Backlog dựa trên giá trị mang lại cho người đặt xe. | Đúng | Thuộc về Product Owner (Đức). Lý do: PO sở hữu Product Backlog, chịu trách nhiệm tối đa hóa giá trị sản phẩm và là cầu nối business với đội phát triển. | Không gây triệu chứng tiêu cực; đây là quy ước chuẩn cần phát huy. |
| QU4. Developers tự đổi thứ tự hạng mục trong Product Backlog khi thấy một tính năng khác dễ làm hơn. | Sai | Thuộc về Product Owner (Đức). Lý do: Developers có quyền tự chủ trong Sprint Backlog (cách làm trong Sprint), nhưng Product Backlog hoàn toàn do PO quản lý và định đoạt thứ tự ưu tiên dựa trên giá trị kinh doanh. | Gây lệch hướng sản phẩm, làm sai lệch mục tiêu kinh doanh mà PO đã định hình. |

## Phần 2 - Vá lỗi

Dựa trên kết quả phân tích ở Phần 1, mình viết lại 4 quy ước làm việc sao cho chuẩn vai trò Agile/Scrum, giúp đội RikkeiGo gỡ bỏ hoàn toàn cả 2 triệu chứng quá tải và áp lực kỹ thuật:

- Quy ước 1 (Đã vá): Đức (PO) tập trung định nghĩa yêu cầu nghiệp vụ và giá trị tính năng đặt xe, còn việc chọn thư viện bản đồ và duyệt code do Developers tự quyết định dựa trên thống nhất kỹ thuật nội bộ.
- Quy ước 2 (Đã vá): Trong buổi Daily Scrum, Lan (SM) chỉ đóng vai trò điều phối giữ đúng thời lượng, không giao việc; các Developers tự trao đổi tiến độ và tự nhận các thẻ việc trong ngày.
- Quy ước 3 (Giữ nguyên): Đức (PO) tiếp tục làm chủ Product Backlog và sắp xếp thứ tự ưu tiên dựa trên giá trị mang lại cho người đặt xe.
- Quy ước 4 (Đã vá): Developers chỉ tập trung thực hiện các hạng mục đã cam kết trong Sprint Backlog; nếu muốn thay đổi thứ tự ưu tiên trong Product Backlog, Developers phải thảo luận và đề xuất với Đức (PO) để quyết định.

---

## 📁 Danh sách tệp tin nộp bài trong Repository
- 📝 `bt2.docx`: Báo cáo tài liệu phân tích nghiệp vụ hoàn chỉnh.
