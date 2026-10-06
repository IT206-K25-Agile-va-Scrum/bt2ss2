# [Vận dụng cơ bản] PHÂN ĐỊNH LẠI 3 VAI TRÒ TRONG ĐỘI RIKKEIGO

> 👤 **Học viên:** Đỗ Hoàng Sơn | **Mã SV:** PTIT-HCM-066
> 🏫 **Môn học:** IT206-K25-Agile-va-Scrum

---

## Phần 1 - Phân tích: Đánh giá 4 quy ước làm việc hiện tại

Trong bài tập này, mình tiến hành rà soát lại 4 quy ước làm việc đang gây ra các triệu chứng tắc nghẽn và ức chế trong đội RikkeiGo. Dưới đây là bảng phân tích chi tiết từng quy ước dựa trên chuẩn phân định vai trò Scrum (Product Owner, Scrum Master, Developers).

- Mục tiêu: Làm rõ ranh giới trách nhiệm để Đức (PO) thoát cảnh quá tải và giúp đội Developers lấy lại quyền tự chủ kỹ thuật.
- Nguyên tắc: Đánh giá đúng bản chất công việc theo chuẩn Scrum thay vì nghe theo các lý do ngụy biện 'để làm nhanh hơn'.

| Quy ước | Đúng/Sai | Quyết định này thuộc về vai trò nào & vì sao | Triệu chứng nào ở Bối cảnh do quy ước này gây ra (nếu có) |
| --- | --- | --- | --- |
| QU1. Đức duyệt từng đoạn code và tự chọn thư viện bản đồ cho tính năng đặt xe. | Sai | Thuộc về Developers. Lý do: PO chịu trách nhiệm về bài toán kinh doanh và giá trị sản phẩm, không phải chuyên gia kỹ thuật. Việc quyết định chọn thư viện hay duyệt code là quyền tự chủ kiến trúc và chuyên môn kỹ thuật của Developers. | Đức bị quá tải vì ôm đờm quá nhiều việc chi tiết kỹ thuật mà nhẽ ra đội dev phải tự lo. |
| QU2. Để đội làm nhanh hơn, trong buổi Daily Scrum mỗi sáng, Lan giao cụ thể ai làm thẻ việc nào trong ngày. | Sai | Thuộc về Developers. Lý do: Scrum Master là người hỗ trợ, huấn luyện và gỡ rào cản, tuyệt đối không ra lệnh hay phân công công việc. Developers là đội tự tổ chức (self-organizing), họ tự quyết định ai làm việc gì để hoàn thành mục tiêu Sprint. | Lập trình viên phàn nàn bị bắt làm theo cách kém hiệu quả vì SM can thiệp sâu vào cách vận hành công việc hàng ngày của họ. |
| QU3. Đức sắp xếp thứ tự ưu tiên Product Backlog dựa trên giá trị mang lại cho người đặt xe. | Đúng | Thuộc về Product Owner. Lý do: PO là người sở hữu Product Backlog, chịu trách nhiệm tối ưu hóa giá trị sản phẩm và đại diện cho phía business, khách hàng. | Không gây ra triệu chứng tiêu cực nào; đây là quy ước chuẩn cần được duy trì. |
| QU4. Developers tự đổi thứ tự hạng mục trong Product Backlog khi thấy một tính năng khác dễ làm hơn. | Sai | Thuộc về Product Owner. Lý do: Developers có quyền tự chủ trong Sprint Backlog (cách làm trong Sprint), nhưng Product Backlog là vùng đất của PO. Không ai được tự ý đổi độ ưu tiên Product Backlog ngoài PO để đảm bảo tính nhất quán về kinh doanh. | Gây lệch hướng mục tiêu kinh doanh sản phẩm vì dev làm việc theo sở thích dễ/khó thay vì theo giá trị thực tế cho khách hàng. |

## Phần 2 - Vá lỗi: Viết lại quy ước chuẩn cho đội RikkeiGo

Để giải quyết triệt để 2 triệu chứng đang kìm hãm đội RikkeiGo (Đức quá tải và dev thấy kém hiệu quả), mình tiến hành viết lại các quy ước sai thành các quy chuẩn đúng vai trò, có thể áp dụng ngay vào thực tế làm việc hàng ngày của team.

- Vá lỗi QU1: Chuyển quyền chọn thư viện và kiểm tra code về cho Developers thông qua quy trình Code Review nội bộ trong team. Đức (PO) chỉ nghiệm thu tính năng dựa trên Acceptance Criteria đã thống nhất.
- Vá lỗi QU2: Trong buổi Daily Scrum, Lan (Scrum Master) đóng vai trò điều phối, hỗ trợ team tự nhìn nhận tiến độ. Việc ai nhận thẻ nào do chính các Developers tự thảo luận và phân chia với nhau.
- Duy trì QU3: Giữ nguyên việc Đức làm chủ Product Backlog và sắp xếp thứ tự ưu tiên dựa trên giá trị business.
- Vá lỗi QU4: Chấm dứt việc dev tự ý đổi thứ tự Product Backlog. Nếu có đề xuất thay đổi, Developers phải bàn bạc và thuyết phục PO, quyền quyết định cuối cùng thuộc về Đức.

---

## 📁 Danh sách tệp tin nộp bài trong Repository
- 📝 `bt2.docx`: Báo cáo tài liệu phân tích nghiệp vụ hoàn chỉnh.
