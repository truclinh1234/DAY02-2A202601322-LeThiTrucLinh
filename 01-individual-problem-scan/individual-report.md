# 01 — Individual Problem Scan

## Scan rộng

Tôi scan 8 problems từ trải nghiệm thực tế tại LAB.

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Lặp lại | Mỗi cuối tuần phải tổng hợp tiến độ từ Zalo/Git để viết báo cáo LAB | Sinh viên, Trưởng LAB | Mất khoảng 45-60 phút rà soát |
| 2 | Tốn thời gian | Tìm kiếm paper từ nguồn uy tín để làm Literature Survey | Người làm Literature Review | Mất 2-3 tiếng lướt Scholar, tra cứu rank Q1/Q2 mất thêm 10p/bài |
| 3 | AI có thể tốt hơn | Đọc paper dài 10-15 trang, trích xuất ý chính hàn lâm ra Slide báo cáo | Sinh viên chuẩn bị Seminar | Đọc mệt, tóm tắt câu dài thành bullet points mất thêm 1.5 - 2 tiếng |
| 4 | Lặp lại | Rà soát lỗi format, chỉnh citation chuẩn APA/IEEE cho báo cáo/slide | Sinh viên viết bài / báo cáo | Tốn 30-45 phút trước giờ nộp, thỉnh thoảng vẫn sai lề, lỗi font |
| 5 | Lặp lại | Trả lời lặp lại cách cài môi trường, dùng server cho sinh viên mới vào LAB | Sinh viên năm cuối / Trưởng nhóm | Tốn 2-3 tiếng/tuần để lục link tài liệu hoặc gõ tin nhắn giải thích lỗi |
| 6 | Tốn thời gian | Setup môi trường chạy lại code (reproduce baseline) của paper cũ bị lỗi | Sinh viên chạy thực nghiệm | Lỗi thư viện liên tục, mất 1-2 ngày chỉ để cài môi trường |
| 7 | AI có thể tốt hơn | So sánh nhược điểm của 3-4 papers cùng chủ đề để viết "Related Work" | Sinh viên viết báo cáo khoa học | Mở 4 tab PDF kẻ bảng so sánh thủ công, mất nguyên 1 ngày mới xong 1 trang draft |
| 8 | Pain từ người khác | Gom slide của các thành viên khác thành 1 file báo cáo tổng | Trưởng nhóm / Người tổng hợp slide | Chữ to nhỏ, format lộn xộn. Mất 45-60 phút sát giờ họp cặm cụi sửa, gây ức chế |

---

## Top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Trích xuất ý Paper ra Slide | Workflow cực kỳ rõ (từ đọc → tóm tắt → dán slide), ai trong LAB cũng bị ám ảnh, metric dễ đo bằng thời gian. | AI trích xuất có giữ được đúng thuật ngữ chuyên ngành hàn lâm không, hay bị "bình dân hóa"? |
| 2 | Tổng hợp Báo cáo LAB | Pain lặp lại đều đặn mỗi cuối tuần, có thể vẽ Before/After rõ ràng. | Liệu chỉ cần đưa ra một Template chuẩn (Rule) đã đủ giải quyết 80% chưa, có thật sự cần dùng AI? |
| 3 | Lọc Paper uy tín (Q1/Q2) | Mất nhiều công tra cứu thủ công, impact rất lớn cho Literature Review. | Nguồn Data/API để kiểm tra Rank (Q1/Q2) có miễn phí và dễ truy cập tự động cho Agent không? |

---

## Problem Card #1 — Trích xuất ý Paper ra Slide

**Problem 1 câu:**  
Khó khăn và tốn thời gian trong việc tự đọc hiểu các văn bản học thuật dài, sau đó phải rút gọn thành ý chính (bullet points) để làm slide Seminar.

**Actor:**  
Sinh viên / Nghiên cứu viên chuẩn bị báo cáo Seminar hàng tuần.

**Thời điểm / bối cảnh:**  
Trước buổi Seminar/báo cáo định kỳ hàng tuần của LAB.

**Current workflow:**
```text
1. Tải Paper PDF về máy.
2. Đọc Abstract, Intro, Method và Highlight bằng tay.
3. Copy phần highlight sang file PowerPoint.
4. Tự viết rút gọn câu chữ thành dạng bullet points.
5. Chỉnh sửa format (font chữ, cỡ chữ, lề).
6. Chèn hình ảnh cắt từ paper vào slide.
7. Trình chiếu thử và nộp.
```

**Bottleneck:**  
Bước 2 (đọc hiểu) và Bước 4 (tóm tắt từ văn bản hàn lâm sang câu nói ngắn gọn) mất tổng cộng khoảng hơn 2 tiếng đồng hồ và gây mệt mỏi nhất.

**Impact:**  
Trung bình mất 3 tiếng cho mỗi buổi làm Slide báo cáo. Việc này chiếm dụng thời gian làm thí nghiệm/code chuyên môn, dẫn đến tình trạng sinh viên hay làm slide đối phó sát giờ.

**Success metric:**  
Thời gian chuẩn bị nội dung thô (draft content) cho slide giảm từ 135 phút xuống dưới 20 phút.

**Non-AI alternative:**  
Dùng Template PPTX có sẵn các placeholder (Intro, Method, Result) để định hình tư duy viết, nhưng không giải quyết được khâu "đọc hiểu" PDF.

**AI hypothesis:**  
AI hỗ trợ đọc, trích xuất cấu trúc và tóm tắt thành bullet points. Sinh viên chỉ cần review nội dung và copy vào Slide.

**Quick gut:**  
Workflow.

### Draft current workflow

```text
CURRENT STATE — 180 phút (3 tiếng)

[1 Tải Paper PDF: 5']
→ [2 Đọc hiểu và highlight: 90']  <-- bottleneck 1
→ [3 Copy text thô qua Slide: 15']
→ [4 Viết lại thành bullet points: 45'] <-- bottleneck 2
→ [5 Format và chèn hình: 25']
```

### Draft future workflow

```text
FUTURE STATE — 35 phút

[1 Upload PDF vào công cụ AI: 2']
→ [2 AI trích xuất Intro/Method/Result dạng bullet: 5']  -- Workflow step
→ [3 Sinh viên REVIEW đối chiếu nội dung: 10']           -- Human boundary
→ [4 Copy text vào Template Slide của LAB: 3']           -- Rule
→ [5 Chỉnh sửa format, chèn hình: 15']                   -- Human

Fallback: AI tóm tắt thiếu ý → Sinh viên tự đọc lướt lại đoạn đó trong PDF để bổ sung.
```

---

## Problem Cards #2 và #3 — tóm tắt

| Card | Actor | Bottleneck | Metric | Quick gut | Vì sao chưa chọn làm #1 |
|---|---|---|---|---|---|
| Báo cáo LAB hàng tuần | Sinh viên LAB | Tốn 45p ngồi nhớ lại việc để viết thành đoạn văn báo cáo | Giảm từ 60p → dưới 10p | Workflow / Rule | Có thể Rule/Template là đủ giải quyết, chưa đủ độ phức tạp để chứng minh vai trò của AI. |
| Lọc Paper uy tín (Q1/Q2) | Người làm Survey | Phải copy tên từng paper qua SCImago tra cứu tốn 10p/bài | 2 tiếng → 15 phút (được 5 bài Q1/Q2) | Agent | Việc truy cập Data check Rank phức tạp, dễ sa đà vào việc xây dựng một Agent rườm rà. |
