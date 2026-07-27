# Group Report — Day 02

## Thành viên nhóm

| STT | Họ và tên              | Mã học viên | Vai trò trong nhóm |
| --: | ------------------------- | -------------- | -------------------- |
|   1 | Điền Mạnh Hùng        | 2A202601888    | Thành viên         |
|   2 | Ngô Lưu Quốc Đạt     | 2A20262014     | Nhóm trưởng       |
|   3 | Nguyễn Phương Thùy    | 2A202601953    | Thành viên         |
|   4 | Lưu Xuân Dũng          | 2A202601774    | Thành viên         |
|   5 | Nguyễn Thị Huyền Trang | 2A202601960    | Thành viên         |
|   6 | Lê Thị Trúc Linh       | 2A202601322    | Thành viên         |
|   7 | Nguyễn Lâm Tùng Bách  | 2A202601830    | Thành viên         |
|   8 | Trần Phú Nghĩa         | 2A202601298    | Thành viên         |
|   9 | Trần Minh Quang          | 2A202601856    | Thành viên         |
|  10 | Cao Minh Quang            | 2A202601884    | Thành viên         |

---

# 02 — Group Problem Statement

## Group convergence

| Cluster                    | Candidate examples                                   | Pattern chung                                                          |
| -------------------------- | ---------------------------------------------------- | ---------------------------------------------------------------------- |
| Luyện tập / feedback     | Mock Interview theo vị trí, follow-up, rubric STAR | Thực hành nhiều vòng, nhận feedback và sửa lỗi                 |
| Hồ sơ ứng tuyển        | CV–JD Alignment, viết bullet CV từ project        | Chuyển evidence thật thành nội dung phù hợp với vị trí        |
| Tạo năng lực / evidence | Skill Gap → Project                                 | Tạo artifact mới khi sinh viên chưa có minh chứng                |
| Planning / progress        | Theo dõi application, lịch luyện và tiến bộ    | Nhiều việc rời rạc làm sinh viên mất tập trung và động lực |

## Shortlist và score

| Candidate                    | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
| ---------------------------- | --------: | -----------: | ----------------: | -----------------: | -------------: | ---------------------: | -----------------: | ----: |
| Mock Interview theo vị trí |         5 |            5 |                 3 |                  4 |              5 |                      5 |                  4 |    31 |
| CV–JD Alignment             |         5 |            5 |                 3 |                  4 |              5 |                      5 |                  3 |    30 |
| Skill Gap → Project         |         4 |            4 |                 2 |                  4 |              3 |                      4 |                  3 |    24 |

Nhóm chọn hiện tại: **Mock Interview theo vị trí**.

Vì sao chọn:

- Actor và workflow rõ.
- Pain xuất phát từ trải nghiệm trực tiếp của Hùng.
- Có thể thử nhỏ với một JD, một rubric và ba buổi mock interview.
- Có thể đo STAR, evidence coverage, confidence và chất lượng feedback.
- Có thể so sánh rõ Rule / Workflow / Agent.

Vì sao không chọn các bài khác:

- CV–JD Alignment: là workflow chuẩn bị hồ sơ riêng; gộp với mock interview làm scope quá rộng.
- Skill Gap → Project: impact dài hạn nhưng chu kỳ tạo artifact dài, khó validate trong buổi lab.

# Quick Validation & Research Giải pháp

## Problem đang kiểm chứng

**Actor:** Sinh viên đang chuẩn bị tìm việc, đặc biệt là người chưa từng hoặc ít tham gia phỏng vấn.

**Problem hypothesis:** Sinh viên thiếu môi trường luyện phỏng vấn đủ thực tế. Việc chỉ đọc danh sách câu hỏi hoặc chuẩn bị câu trả lời mẫu không giúp họ làm quen với câu hỏi tiếp nối, áp lực hội thoại và tình huống bất ngờ.

**Solution hypothesis ban đầu:** Mock Interview Agent nhận Job Description, mô phỏng phỏng vấn nhiều lượt, đặt câu hỏi tiếp nối và điều chỉnh mức độ khai thác dựa trên câu trả lời của người dùng.

> Lưu ý: Quick validation cần kiểm chứng **problem và hành vi hiện tại** trước khi kiểm chứng solution.

---

## Quick validation

Nhóm phỏng vấn nhanh sinh viên chuẩn bị tìm việc, người vừa trải qua phỏng vấn và mentor/recruiter nếu tiếp cận được.

| Nguồn                                                          | Số người | Tín hiệu xác nhận                                                                                                                                                                                                                                | Tín hiệu phản bác                                                                                                                                                                                                                                                                                                                                                 | Nhóm sửa problem thế nào                                                                                                                                                                                                                                                                                                                 |
| --------------------------------------------------------------- | ----------: | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Quick interview — Sinh viên chưa từng hoặc ít phỏng vấn |           2 | Cả hai người đều muốn có cơ hội luyện trước để chuẩn bị tốt hơn và giảm sự bỡ ngỡ khi tham gia phỏng vấn thật. Người được hỏi quan tâm đến việc thực hành trả lời, thay vì chỉ đọc danh sách câu hỏi. | Người được hỏi nghi ngờ câu hỏi do AI tạo có bám sát thực tế tuyển dụng hay không. Một buổi luyện không có giới hạn thời gian hoặc áp lực phản hồi có thể chưa đủ giống phỏng vấn thật. Dữ liệu này mới thể hiện sự quan tâm đến solution, chưa chứng minh rõ tần suất và mức độ nghiêm trọng của pain. | Thu hẹp problem từ “thiếu công cụ luyện phỏng vấn” thành “thiếu môi trường luyện khả năng trả lời câu hỏi tiếp nối dưới áp lực thời gian”. Cá nhân hóa theo JD, vị trí, lĩnh vực hoặc công ty được xem là giả thuyết cần kiểm chứng thêm, chưa phải requirement đã được xác nhận. |

### Insight sau validation

- **Tín hiệu pain nổi bật nhất:** Hai người được phỏng vấn đều muốn được luyện trước trong một môi trường an toàn để giảm sự bỡ ngỡ và chuẩn bị tốt hơn cho buổi phỏng vấn thật. Tuy nhiên, do mẫu mới có hai người, đây chỉ là tín hiệu ban đầu chứ chưa phải xác nhận mạnh.
- **Pain yếu hoặc chưa được xác nhận:** Chưa có đủ bằng chứng cho thấy việc thiếu câu hỏi phỏng vấn là pain chính. Người dùng có thể tìm được danh sách câu hỏi trên Internet, nhưng chưa chắc tin rằng câu hỏi do công cụ tạo sẽ sát với thực tế tuyển dụng.
- **Cách người dùng đang tự giải quyết:** Người được hỏi hiện chủ yếu tự tìm câu hỏi phỏng vấn trên Internet, tự chuẩn bị câu trả lời hoặc hình dung trước các tình huống có thể xảy ra. Chưa ghi nhận việc họ luyện thường xuyên với mentor, bạn bè hoặc công cụ mock interview chuyên dụng.
- **Khoảnh khắc khó nhất trong workflow hiện tại:** Khó biết nên luyện câu hỏi nào cho đúng vị trí mục tiêu và khó tái tạo tình huống phải trả lời ngay khi interviewer hỏi sâu, yêu cầu làm rõ hoặc thay đổi hướng câu hỏi.
- **Problem statement sau khi chỉnh sửa:** Sinh viên đang chuẩn bị tìm việc nhưng chưa từng hoặc ít tham gia phỏng vấn gặp khó khăn khi luyện khả năng trả lời câu hỏi tiếp nối dưới áp lực thời gian. Cách chuẩn bị hiện tại chủ yếu là đọc danh sách câu hỏi và chuẩn bị câu trả lời tĩnh, nên họ ít có cơ hội thực hành phản ứng khi interviewer yêu cầu làm rõ, đưa bằng chứng hoặc xử lý tình huống ngoài kịch bản. Điều này có thể khiến họ bỡ ngỡ, trả lời lan man hoặc mất bình tĩnh trong buổi phỏng vấn thật.
- **Giả thuyết cần kiểm chứng tiếp:**

  1. Sinh viên gặp khó với câu hỏi tiếp nối hay chủ yếu thiếu kiến thức để trả lời câu hỏi ban đầu?
  2. Giới hạn thời gian giúp trải nghiệm thực tế hơn hay chỉ làm người mới căng thẳng và bỏ cuộc?
  3. Người dùng cần cá nhân hóa theo role, JD, vòng phỏng vấn, seniority, CV hay công ty cụ thể?
  4. Người dùng cần feedback về communication, nội dung hay cả hai?
  5. Người dùng có tin feedback và mức độ khó do AI tạo nếu không có rubric và evidence đi kèm?
  6. Người dùng hiện đang dùng cách nào để luyện và vì sao cách đó chưa đủ tốt?
  7. Người dùng có tiến bộ trên câu hỏi mới hay chỉ học thuộc các câu đã luyện?

---

## Research giải pháp

Nhóm tìm các hướng đã có sẵn, không giả định phải tự build toàn bộ từ đầu.

| Nguồn / tool / case                                     | Link                                                                                                        | Họ giải quyết phần nào?                                                                                                                                                                                                                     | Điểm mạnh                                                                                                                                                                 | Khoảng trống / rủi ro                                                                                                                                                                                                                                                                                               | Bài học cho nhóm                                                                                                                                                 |
| -------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Yoodli — AI Interview Coach                             | https://support.yoodli.ai/en/articles/9550465-practice-with-yoodli                                          | Cho người dùng luyện với AI interviewer bằng microphone/camera. Hệ thống sử dụng câu hỏi đặt trước và xen kẽ dynamic follow-up dựa trên câu trả lời của người dùng.                                                   | Có trải nghiệm hội thoại bằng giọng nói; có contextual follow-up; hỗ trợ luyện phản xạ thay vì chỉ đọc câu hỏi.                                          | Nguồn chính thức xác nhận dynamic follow-up nhưng chưa mô tả rõ cơ chế điều chỉnh độ khó theo rubric. Chưa thấy bằng chứng trong nguồn này rằng toàn bộ JD được chuyển thành competency map. Feedback về giao tiếp cũng không tự động bảo đảm độ chính xác chuyên môn. | Chỉ “có follow-up” chưa đủ khác biệt. Follow-up cần có mục tiêu rõ như kiểm tra evidence, contribution, rationale hoặc consistency.                |
| Huru — AI Mock Interview theo JD                        | https://huru.ai/ai-mock-interview-generator-custom-role-company/                                            | Tạo mock interview theo role, company và seniority; Huru cũng quảng bá khả năng biến job description thành các câu hỏi luyện tập phù hợp và đưa feedback sau phiên.                                                          | Cá nhân hóa theo công việc; onboarding đơn giản; phù hợp với người muốn luyện nhanh; đã giải quyết khá rõ bước job information → tailored questions. | Các claim chủ yếu đến từ trang sản phẩm của Huru. Nhóm chưa có đánh giá độc lập để xác minh câu hỏi sát interview loop thực tế đến mức nào. Chưa tìm thấy mô tả đủ rõ về answer-aware follow-up và adaptive difficulty trong từng phiên.                                     | Phân tích JD để sinh câu hỏi đã có trên thị trường, vì vậy không nên dùng làm điểm khác biệt chính.                                         |
| PolyInterview — LLM-based Mock Interview Platform       | https://arxiv.org/abs/2607.10310                                                                            | Dùng CV và JD để tạo câu hỏi; thực hiện phỏng vấn giọng nói nhiều lượt; đặt answer-aware follow-up; đánh giá nội dung, giọng nói và hành vi phi ngôn ngữ; liên kết feedback với evidence dựa trên KSA và STAR. | Bao phủ gần như toàn bộ solution hypothesis ban đầu; có multi-turn spoken interview, follow-up theo câu trả lời và feedback có cấu trúc.                      | Đây là công trình nghiên cứu mới công bố tháng 7/2026. Kết quả chủ yếu do nhóm tác giả báo cáo, nên chưa đủ để kết luận hiệu quả dài hạn trong phỏng vấn tuyển dụng thật. Scope của hệ thống cũng lớn đối với một project sinh viên.                                    | “CV/JD + multi-turn + follow-up + feedback” không còn là novelty đủ mạnh. Nhóm cần chọn một pain hẹp, actor cụ thể hoặc cơ chế probing tốt hơn. |
| interviewing.io — Mock interview với interviewer thật | https://interviewing.io/                                                                                    | Cung cấp mock technical interview với interviewer thật; có recording, feedback và thư viện interview replay. Nền tảng cũng có AI Interviewer cho coding và system design.                                                            | Là benchmark tốt về mức độ thực tế; interviewer thật có thể phản biện, đổi hướng hỏi và điều chỉnh độ sâu theo câu trả lời.                      | Không phải direct competitor hoàn toàn vì thiên về technical interview, đặc biệt coding và system design. Việc luyện với người thật cần đặt phiên nên có thể khó lặp lại tức thời như AI; nhận định này cần được kiểm chứng thêm với người dùng.                          | Agent cần mô phỏng được probing và câu hỏi ngoài kịch bản, không chỉ dùng giọng nói giống interviewer.                                            |
| Pattern — Structured interview + scoring rubric         | https://rework.withgoogle.com/intl/en/guides/a-guide-to-structured-interviewing-for-better-hiring-practices | Dùng câu hỏi chuẩn hóa, liên quan đến role và rubric rõ ràng để đánh giá ứng viên nhất quán hơn.                                                                                                                            | Giúp giảm đánh giá tùy ý; làm rõ vì sao một câu trả lời tốt hoặc yếu; là pattern phù hợp để thiết kế competency và feedback.                        | Rubric chung không thể phù hợp mọi role hoặc mọi vòng phỏng vấn; vẫn cần người có chuyên môn thiết kế tiêu chí và hiệu chỉnh mức điểm.                                                                                                                                                      | Feedback nên bám rubric và trích evidence từ transcript; tránh chỉ trả về điểm số như “7/10” mà không giải thích.                                |

### Research takeaway

Không nên định vị sản phẩm chỉ là:

> “Chatbot tạo câu hỏi phỏng vấn từ JD.”

Cũng không nên xem các tính năng sau là điểm khác biệt đủ mạnh:

- Nhận JD hoặc CV.
- Sinh câu hỏi theo vị trí.
- Phỏng vấn nhiều lượt bằng giọng nói.
- Đặt câu hỏi tiếp nối.
- Đưa feedback sau phiên.

Các công cụ và case đã có đã giải quyết phần lớn những bước này.

Hướng hợp lý hơn là:

> **Mock Interview Agent cho sinh viên ít kinh nghiệm, tập trung luyện khả năng xử lý câu hỏi tiếp nối dưới áp lực thời gian. Agent xác định phần còn thiếu trong câu trả lời — như evidence, contribution, rationale hoặc trade-off — rồi chọn loại follow-up và mức hỗ trợ phù hợp theo một rubric có thể giải thích.**

Workflow đề xuất:

1. Người dùng nhập JD, vị trí và loại vòng muốn luyện.
2. Hệ thống tách JD thành một số competency cần kiểm tra và hiển thị để người dùng xác nhận.
3. Mỗi competency được gắn với câu hỏi ban đầu, mục tiêu đánh giá và rubric.
4. Agent phân tích câu trả lời để xác định phần còn thiếu.
5. Agent đặt follow-up để kiểm tra evidence, contribution, rationale, trade-off hoặc consistency.
6. Độ khó tăng bằng các cơ chế quan sát được như thêm constraint, giảm gợi ý, rút ngắn thời gian hoặc yêu cầu phản biện quyết định.
7. Feedback trích dẫn trực tiếp phần transcript còn thiếu hoặc chưa nhất quán.
8. Phiên sau sử dụng câu hỏi mới hoặc paraphrase để kiểm tra tiến bộ và hạn chế học thuộc.

### Khoảng trống đáng ưu tiên kiểm chứng

- Sinh viên có thật sự thiếu **môi trường hội thoại**, hay pain chính là thiếu kiến thức và cấu trúc câu trả lời?
- Câu hỏi tiếp nối có phải pain lớn hơn việc không biết câu hỏi ban đầu sẽ xuất hiện?
- Áp lực thời gian có tạo ra giá trị luyện tập hay chỉ khiến người mới căng thẳng và bỏ cuộc?
- “Điều chỉnh độ khó” nên được định nghĩa bằng kiến thức, thời gian, constraint, số lượt probing hay lượng gợi ý?
- Người dùng cần feedback về communication, nội dung hay cả hai?
- JD có đủ để cá nhân hóa hay cần thêm CV, loại vòng và seniority?
- Người dùng có tin feedback AI khi không có interviewer thật kiểm chứng không?
- Người dùng có sẵn sàng tải CV/JD và ghi âm câu trả lời không?
- Rubric của AI có đồng thuận với đánh giá của mentor hoặc interviewer thật không?
- Người dùng có cải thiện trên câu hỏi mới hay chỉ quen với bộ câu hỏi đã luyện?

---

## Workflow before/after

Nội dung workflow:

```text
CURRENT STATE — baseline thời gian chưa đo

[1 Chọn vị trí/JD]
→ [2 Tìm câu hỏi phổ biến]
→ [3 Tự chọn câu, chưa mapping competency]
→ [4 Luyện một mình]  <-- bottleneck bắt đầu
→ [5 Không có follow-up]
→ [6 Feedback ad-hoc, không cùng rubric]
→ [7 Không biết lỗi lặp/mức tiến bộ]
→ [8 Đi phỏng vấn thật]

FUTURE STATE — Workflow có human review

[1 Sinh viên chọn JD + consent dữ liệu]
→ [2 Rule/AI tách 3–5 competency]
→ [3 Rule chọn câu hỏi gốc từ question bank]
→ [4 Sinh viên trả lời]
→ [5 AI hỏi tối đa 1–2 follow-up]
→ [6 Tạo transcript + đánh dấu evidence]
→ [7 Draft feedback theo rubric STAR]
→ [8 Sinh viên xác nhận transcript/evidence]  <-- human boundary
→ [9 Cố vấn review case quan trọng]
→ [10 Sinh viên luyện lại và so sánh trước/sau]

Fallback:
- AI hỏi sai → quay về question bank cố định.
- Transcript/feedback sai → bỏ điểm AI, sinh viên sửa và cố vấn chấm.
- Privacy/bias không kiểm soát được → dùng text-only + peer review.

Bottleneck mới:
Sinh viên/cố vấn review transcript và feedback. Đây là bottleneck chấp nhận được
vì nó là điểm kiểm soát chất lượng và công bằng.
```

Before/after impact:

| Metric                         |              Trước |                                 Sau kỳ vọng | Ghi chú                           |
| ------------------------------ | -------------------: | --------------------------------------------: | ---------------------------------- |
| Câu hỏi gắn với competency |   Không nhất quán |                    100% câu gốc có mapping | Mapping question → competency     |
| Follow-up theo câu trả lời  | Ít hoặc không có |                  Tối đa 1–2 follow-up/câu | Giới hạn để tránh lệch scope |
| Rubric                         |  Không thống nhất |                Cùng rubric STAR qua ba buổi | Version hóa rubric                |
| Điểm STAR                    |            Chưa đo |                           Tăng ít nhất 20% | Baseline buổi 1, so với buổi 3  |
| Câu behavioral có evidence   |            Chưa đo |                                 Ít nhất 80% | Cố vấn audit mẫu                |
| Mức tự tin                   |            Chưa đo |                           Tăng ít nhất 1/5 | Chỉ số phụ                      |
| Risk mới                      |      Feedback ad-hoc | Bias, transcript sai, privacy, overconfidence | Human review + fallback            |

## Problem Statement v0

| Field                    | Nội dung                                                                                                                                                                              |
| ------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Actor**          | Sinh viên năm cuối / mới tốt nghiệp đã chọn vị trí mục tiêu và chuẩn bị cho một trong những cuộc phỏng vấn đầu tiên.                                           |
| **Workflow**       | Chọn JD → tìm câu hỏi → tự luyện → ít follow-up → feedback ad-hoc nếu có → đi phỏng vấn thật.                                                                        |
| **Bottleneck**     | Thiếu vòng luyện tập tương tác có follow-up và feedback có evidence, được chấm bằng cùng một rubric qua nhiều lần; mentor thật không luôn sẵn sàng.            |
| **Impact**         | Câu trả lời dễ chung chung/thiếu evidence; không biết lỗi lặp; khó thấy tiến bộ; thiếu tự tin.                                                                          |
| **Success Metric** | Sau ba buổi cùng competency/rubric: STAR tăng ít nhất 20%; ít nhất 80% câu behavioral có evidence; confidence tăng ít nhất 1/5; CSAT feedback từ 4/5. Baseline chưa đo. |
| **Boundary**       | Không dự đoán đậu/rớt; không chấm yếu tố nhạy cảm; feedback phải dựa trên transcript; sinh viên có quyền xem/sửa/xóa; cố vấn review case quan trọng.           |

## Rule / Workflow / Agent

| Mức               | Phương án                                                                                       | Khi nào đủ                                                            | Rủi ro                                               | Chọn?                              |
| ------------------ | -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ | ----------------------------------------------------- | ----------------------------------- |
| **Rule**     | Question bank theo role + checklist STAR + form feedback cố định                                | Đủ nếu không cần follow-up theo ngữ cảnh                          | Cứng nhắc; không phản hồi theo câu trả lời    | Dùng cho câu hỏi gốc và rubric |
| **Workflow** | JD → competency → question bank → AI follow-up → transcript/evidence → rubric → human review | Hợp vì luồng tuyến tính, AI chỉ hỗ trợ vài bước               | Feedback sai/bias, transcript sai, privacy            | **Chọn cho pilot**           |
| **Agent**    | Tự chọn chiến lược hỏi, gọi nhiều tool và tự quyết bài luyện tiếp                    | Chỉ cần nếu nhiều nhánh/tool và tự lập kế hoạch tạo giá trị | Scope rộng, khó dự đoán, chi phí/permission cao | Chưa chọn                         |

Mức chọn:

```text
Workflow có AI hỗ trợ.
```

Vì sao:

- Rule đủ cho question bank, giới hạn follow-up và rubric.
- AI hữu ích ở follow-up, transcript/evidence và draft feedback.
- Sinh viên/cố vấn vẫn review trước khi dùng feedback.
- Chưa cần Agent vì workflow chưa cần tự lập kế hoạch động.

## Problem Statement v1

| Field                                       | Nội dung                                                                                                                                                                                         |
| ------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Actor**                             | Sinh viên năm cuối / mới tốt nghiệp đã chọn một vị trí mục tiêu và thiếu cơ hội luyện phỏng vấn thực tế.                                                                   |
| **Workflow**                          | Chọn JD → tìm câu hỏi → tự luyện → ít follow-up → feedback ad-hoc → không có progress log → phỏng vấn thật.                                                                     |
| **Bottleneck**                        | Không có vòng practice nhất quán gồm câu hỏi theo competency, follow-up, feedback dựa trên transcript/evidence và cùng một rubric qua nhiều lần.                                   |
| **Impact**                            | Câu trả lời dễ chung chung/thiếu evidence; lỗi lặp lại không được nhìn thấy; sinh viên khó biết mình tiến bộ và thiếu tự tin.                                              |
| **Success Metric**                    | Với cùng competency/rubric qua ba buổi: STAR tăng ít nhất 20%; ít nhất 80% câu behavioral có evidence; confidence tăng ít nhất 1/5; CSAT từ 4/5; cố vấn thấy feedback hữu ích. |
| **Boundary**                          | Không dự đoán tuyển dụng; không chấm yếu tố nhạy cảm; không suy đoán ngoài transcript; sinh viên có quyền xem/sửa/xóa và phản hồi; cố vấn review case quan trọng.      |
| **AI intervention point**             | Sau khi role/competency được xác nhận: hỗ trợ follow-up, transcript/evidence và draft feedback; trước bước sinh viên/cố vấn review.                                                |
| **Mức chọn**                        | Workflow: Rule cho question bank/rubric; AI cho follow-up và feedback draft; human review.                                                                                                       |
| **Rủi ro & người thật kiểm tra** | Transcript sai, feedback thiếu căn cứ, bias, overconfidence và privacy. Sinh viên xác nhận transcript/evidence; cố vấn hiệu chỉnh rubric và review case bất thường.                |

## Final decision

Decision:

```text
Not Yet cho việc build Agent hoặc triển khai rộng.
Go cho pilot validation bán thủ công.
```

Pilot nhỏ nhất:

- Một sinh viên: Hùng.
- Một JD/vị trí mục tiêu và 3–5 competency.
- Ba buổi mock interview dùng cùng question scope và rubric STAR.
- Cố vấn/peer có kinh nghiệm review ít nhất một transcript + feedback.
- So sánh với benchmark: question bank + checklist STAR + peer review.

Điều kiện chuyển sang Go cho Workflow pilot lớn hơn:

- STAR tăng ít nhất 20%.
- Ít nhất 80% câu behavioral có evidence.
- CSAT feedback từ 4/5 và cố vấn thấy feedback hữu ích.
- Không có lỗi bias/privacy nghiêm trọng.

Exit / rollback:

- Nếu Rule + peer review giải phần lớn pain với effort tương đương, giữ phương án non-AI/Rule.
- Nếu điểm AI thiếu nhất quán, bỏ scoring tự động và chỉ giữ transcript/insight.
- Nếu feedback bịa evidence, hỏi yếu tố nhạy cảm hoặc gây hại, dừng feedback tự động.

Decision rationale:

- Problem và workflow đủ rõ để thiết kế pilot.
- Có metric và boundary nhưng baseline/peer validation chưa hoàn tất.
- AI nằm ở các bước cụ thể, không ôm toàn bộ workflow.
- Human review và fallback đã rõ.
