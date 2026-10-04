# Checklist lộ trình Data Analyst — 12 tuần

> Dành cho: sinh viên năm 3 ngành Hệ thống thông tin quản lý (MIS)
> Mục tiêu: từ nền tảng → thực chiến → có 3 dự án cá nhân trong portfolio
> Ngày bắt đầu: ____ / ____ / ________  ·  Ngày kết thúc dự kiến: ____ / ____ / ________

## Cách dùng

- Đánh dấu `[x]` vào ô khi hoàn thành từng việc.
- Mỗi tuần có **Mốc kiểm tra** — chỉ tick khi đã tự làm được, không nhìn đáp án.
- Cuối mỗi giai đoạn tự đánh giá lại trước khi sang giai đoạn tiếp theo.
- Tick ô lớn ở phần **Bảng theo dõi tiến độ** khi xong cả tuần.

---

## Giai đoạn 1 — Nền tảng vững (Tuần 1–4)

### Tuần 1 — SQL
- [ ] Cài PostgreSQL hoặc MySQL trên máy
- [ ] Ôn SELECT, WHERE, ORDER BY, LIMIT
- [ ] Ôn JOIN (INNER, LEFT), GROUP BY, HAVING
- [ ] Học subquery
- [ ] Học window functions (ROW_NUMBER, RANK, LAG/LEAD)
- [ ] Làm 30–50 bài tập SQL (SQLZoo, HackerRank)
- [ ] Tự tạo 2–3 bảng mẫu và viết query trả lời 1 câu hỏi kinh doanh

**Mốc kiểm tra:** JOIN được 2–3 bảng để trả lời một câu hỏi kinh doanh mà không tra cứu liên tục. [ ]

### Tuần 2 — Thống kê cho Analyst
- [ ] Ôn thống kê mô tả (mean, median, độ lệch chuẩn)
- [ ] Hiểu phân phối dữ liệu
- [ ] Hiểu tương quan (correlation) và cảnh báo "tương quan ≠ nhân quả"
- [ ] Học A/B testing cơ bản (giả thuyết, p-value, ý nghĩa thống kê)
- [ ] Viết 1 notebook phân tích tập dữ liệu đơn giản

**Mốc kiểm tra:** giải thích được khi nào một kết quả A/B test là "có ý nghĩa". [ ]

### Tuần 3 — Excel / Google Sheets nâng cao
- [ ] Pivot Table
- [ ] VLOOKUP / XLOOKUP / INDEX-MATCH
- [ ] Hàm thống kê và điều kiện (SUMIF, COUNTIF, IF)
- [ ] Làm sạch dữ liệu cơ bản trên bảng tính
- [ ] Dựng 1 dashboard Excel từ dữ liệu thật

**Mốc kiểm tra:** có 1 dashboard Excel hoàn chỉnh, tự động cập nhật theo dữ liệu. [ ]

### Tuần 4 — Python cho dữ liệu
- [ ] Cài Python + Jupyter Notebook (hoặc Anaconda)
- [ ] Học cơ bản pandas (DataFrame, đọc/ghi file)
- [ ] Học numpy
- [ ] Làm sạch một dataset "bẩn" (dữ liệu thiếu/sai/trùng)
- [ ] Đưa notebook đầu tiên lên GitHub

**Mốc kiểm tra:** tự làm sạch một dataset bẩn và xuất ra file sạch. [ ]

---

## Giai đoạn 2 — Công cụ & trực quan hóa (Tuần 5–8)

### Tuần 5 — Công cụ BI
- [ ] Chọn 1 công cụ: Power BI (khuyến nghị) hoặc Tableau
- [ ] Cài đặt và làm quen giao diện
- [ ] Kết nối dữ liệu (Excel / CSV / database)
- [ ] Học data modeling cơ bản (quan hệ bảng)

**Mốc kiểm tra:** dựng được 1 biểu đồ đơn giản từ dữ liệu được nạp vào. [ ]

### Tuần 6 — Dashboard nâng cao
- [ ] Học DAX (Power BI) hoặc calculated field (Tableau)
- [ ] Thiết kế bố cục dashboard
- [ ] Thêm filter / slicer tương tác
- [ ] Dựng dashboard trả lời 1 câu hỏi kinh doanh cụ thể

**Mốc kiểm tra:** dashboard tương tác kể được 1 câu chuyện kinh doanh. [ ]

### Tuần 7 — Trực quan hóa bằng Python
- [ ] Học matplotlib
- [ ] Học seaborn
- [ ] Vẽ biểu đồ phân bố, xu hướng, so sánh nhóm
- [ ] Kết hợp biểu đồ vào notebook phân tích

**Mốc kiểm tra:** notebook có biểu đồ rõ ràng, chú thích đầy đủ. [ ]

### Tuần 8 — Storytelling với dữ liệu
- [ ] Học cấu trúc: bối cảnh → câu hỏi → phát hiện → khuyến nghị
- [ ] Viết phần kết luận có đề xuất hành động cho 1 dashboard
- [ ] Luyện trình bày dashboard trong 3–5 phút

**Mốc kiểm tra:** trình bày được dashboard của mình như một câu chuyện. [ ]

---

## Giai đoạn 3 — Thực chiến với dự án cá nhân (Tuần 9–12)

### Project 1 — Phân tích bán hàng (SQL + Dashboard)
- [ ] Tải dataset (Superstore / E-commerce trên Kaggle)
- [ ] Nạp dữ liệu vào PostgreSQL
- [ ] Viết 10–15 query trả lời câu hỏi doanh thu theo vùng/thời gian/sản phẩm
- [ ] Dựng dashboard Power BI từ kết quả
- [ ] Viết README: bối cảnh, câu hỏi, cách làm, insight, khuyến nghị
- [ ] Đẩy lên GitHub (file .sql + ảnh dashboard)

**Mốc kiểm tra:** repo Project 1 hoàn chỉnh trên GitHub. [ ]

### Project 2 — Hành vi khách hàng (Python + Cohort/RFM)
- [ ] Tải dataset online retail hoặc app events
- [ ] Làm sạch bằng pandas
- [ ] Phân tích cohort retention
- [ ] Phân nhóm khách hàng bằng RFM
- [ ] Trực quan hóa kết quả
- [ ] Viết kết luận + đề xuất marketing
- [ ] Đẩy notebook lên GitHub

**Mốc kiểm tra:** repo Project 2 có notebook + biểu đồ + kết luận. [ ]

### Project 3 — A/B Testing (hoặc dự đoán đơn giản)
- [ ] Chọn dataset A/B test (hoặc mô phỏng)
- [ ] Đặt giả thuyết và tiêu chí đo lường
- [ ] Kiểm định giả thuyết
- [ ] Kết luận: có nên đổi tính năng không, vì sao
- [ ] (Tùy chọn) Thêm model dự đoán: logistic regression / dự báo doanh thu
- [ ] Đẩy lên GitHub

**Mốc kiểm tra:** repo Project 3 trả lời rõ "có/không nên làm gì" dựa trên dữ liệu. [ ]

### Đóng gói portfolio
- [ ] Tạo GitHub profile README giới thiệu bản thân
- [ ] Pin 3 repo dự án
- [ ] Mỗi repo có README chuẩn: bối cảnh — câu hỏi — cách làm — insight — khuyến nghị
- [ ] Viết 1 bài ngắn chia sẻ 1 project (LinkedIn / blog)

**Mốc kiểm tra:** portfolio GitHub có 3 repo hoàn chỉnh. [ ]

---

## Giai đoạn 4 — Đưa ra thị trường

- [ ] Viết CV theo hướng "impact" (nêu số liệu cụ thể, không chỉ liệt kê công cụ)
- [ ] Chuẩn bị LinkedIn (tiêu đề rõ ràng: Data Analyst / Business Analyst Intern)
- [ ] Ứng tuyển thực tập Data Analyst / Business Analyst
- [ ] Luyện phỏng vấn SQL
- [ ] Luyện case study kinh doanh ("doanh thu giảm, bạn phân tích thế nào?")
- [ ] Luyện giải thích dashboard của mình
- [ ] Tham gia cộng đồng: Kaggle, group Data Analyst VN

**Mốc kiểm tra:** gửi ít nhất 5 đơn ứng tuyển thực tập. [ ]

---

## 📊 Bảng theo dõi tiến độ

| Tuần | Nội dung | Hoàn thành |
|---|---|---|
| 1 | SQL | [ ] |
| 2 | Thống kê cho Analyst | [ ] |
| 3 | Excel nâng cao | [ ] |
| 4 | Python cho dữ liệu | [ ] |
| 5 | Công cụ BI | [ ] |
| 6 | Dashboard nâng cao | [ ] |
| 7 | Trực quan hóa Python | [ ] |
| 8 | Storytelling | [ ] |
| 9 | Project 1 — Phân tích bán hàng | [ ] |
| 10 | Project 2 — Hành vi khách hàng | [ ] |
| 11 | Project 3 — A/B Testing | [ ] |
| 12 | Đóng gói portfolio | [ ] |

---

## 🎓 Tài nguyên gợi ý

- **SQL:** SQLZoo, HackerRank SQL, Mode Analytics SQL Tutorial
- **Thống kê:** Khan Academy Statistics, StatQuest
- **Python:** pandas documentation, Kaggle Learn
- **BI:** Microsoft Learn (Power BI), Tableau Free Training
- **Dữ liệu thực hành:** Kaggle Datasets, UCI Machine Learning Repository

## 💡 Lời khuyên riêng cho dân MIS

- Tận dụng hiểu biết về **quy trình nghiệp vụ, ERP/CRM** — chọn dự án gắn một ngành cụ thể (bán lẻ, ngân hàng, logistics) để khác biệt.
- Chưa chắc chọn Analyst hay Scientist? Cứ bắt đầu bằng **Analyst + SQL + BI**, mở rộng sang Python/model sau.
- Đừng chờ học hết mới làm — học 2 tuần là đủ để bắt tay project đầu tiên.
