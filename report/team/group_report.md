# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm:
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |
| 7 | | | | | |
| 8 | | | | | |
| 9 | | | | | |
| 10 | | | | | |
| 11 | | | | | |
| 12 | | | | | |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | | |
| B | | |
| C | | |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: 
├── Opportunity A: 
├── Opportunity B: 
└── Opportunity C: 
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

**Job Story:**

> Khi tới giai đoạn ôn thi cuối kỳ, tôi muốn tóm tắt được nội dung chính của môn học từ slide, giáo trình và ghi chú, để xây dựng đề cương ôn tập nhanh chóng mà không bỏ sót kiến thức quan trọng.

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | AI có thể tóm tắt nội dung từng chương từ slide, giáo trình và ghi chú mà vẫn giữ được các ý quan trọng, không bỏ sót chương. | Feasibility | 5 | 1 | Có |
| 2 | Sinh viên kiểm tra và chỉnh sửa bản tóm tắt do AI tạo ra nhanh hơn đáng kể so với tự tóm tắt, giúp tổng thời gian xây dựng đề cương giảm từ khoảng 2,5 giờ xuống dưới 1 giờ/môn. | Usability | 5 | 1 | Có |
| 3 | Các sinh viên khác cũng mất nhiều thời gian để xây dựng đề cương, khoảng 2–3 giờ/môn, trong đó đọc và tóm tắt là công đoạn tốn nhiều thời gian nhất. | Value | 5 | 2 | Có |
| 4 | Các phương pháp hiện tại như sử dụng template và chia sẻ đề cương giữa bạn bè chưa giải quyết đáng kể thời gian đọc và chọn lọc kiến thức. | Value | 4 | 2 | Có |
| 5 | Các tài liệu học tập thực tế như slide PDF, trang Notion và ghi chú có thể được đưa vào AI để xử lý mà không làm mất nội dung quan trọng. | Feasibility | 4 | 2 | Sau |
| 6 | Sinh viên sẵn sàng sử dụng đề cương có AI hỗ trợ và việc sử dụng AI không bị hạn chế bởi quy định của giảng viên hoặc nhà trường. | Viability | 3 | 2 | Không |

**Cơ sở chấm điểm:**

| Giả định | Lý do chấm điểm |
|---|---|
| #1 (5/1) | Nếu AI bỏ sót chương hoặc nội dung quan trọng thì sản phẩm không đáp ứng mục tiêu xây dựng đề cương đầy đủ. Nhóm chưa có kết quả thử nghiệm thực tế để chứng minh. |
| #2 (5/1) | Nếu thời gian kiểm tra và chỉnh sửa bản AI gần bằng thời gian tự tóm tắt thì sản phẩm không tạo ra lợi ích tiết kiệm thời gian đáng kể. Chưa có Time Log để xác nhận. |
| #3 (5/2) | Nhóm mới có thông tin ước lượng về thời gian thực hiện từ một số sinh viên, chưa có khảo sát đủ rộng hoặc dữ liệu bấm giờ để xác nhận mức độ phổ biến. |
| #4 (4/2) | Các phương pháp như template và chia sẻ đề cương có thể hỗ trợ trình bày và phân chia công việc, nhưng chưa có bằng chứng thực nghiệm cho thấy chúng không giảm được thời gian đọc và tóm tắt. |
| #5 (4/2) | Tài liệu dạng số có tiềm năng xử lý bằng AI, nhưng khả năng đọc nội dung, nhận diện bảng biểu và ghi chú vẫn cần được thử nghiệm. |
| #6 (3/2) | Mức độ sẵn sàng sử dụng AI và quy định của giảng viên chưa được khảo sát. Giả định này ít ảnh hưởng trực tiếp đến khả năng hoàn thành thử nghiệm ban đầu. |

Giả định nhóm kiểm chứng trong buổi này: **#1, #2, #3** (ba giả định có mức độ quan trọng cao nhất).

- **#1:** Kiểm tra khả năng AI tóm tắt một chương tài liệu thực tế, đối chiếu với tài liệu gốc để xác định nội dung quan trọng bị bỏ sót.
- **#2:** Sử dụng Time Log để so sánh thời gian tự tóm tắt và thời gian kiểm tra, chỉnh sửa bản AI trên cùng một bộ tài liệu.
- **#3:** Phỏng vấn nhanh 3–5 sinh viên về lần gần nhất họ xây dựng đề cương, thời gian thực hiện và công đoạn tốn nhiều thời gian nhất.

### 3.2. Kiểm chứng

**Phương pháp kiểm chứng:**

| Phương pháp | Mục đích | Giả định kiểm chứng |
|---|---|---|
| Phỏng vấn nhanh (Quick Interview) | Tìm hiểu hành vi thực tế trong lần gần nhất sinh viên xây dựng đề cương, thời gian thực hiện và khó khăn gặp phải. | #3, #4 |
| Khảo sát nhanh (Mini Poll) | Xác định mức độ phổ biến của vấn đề và các phương pháp sinh viên đang sử dụng để xây dựng đề cương. | #3, #4 |
| Bấm giờ thực tế (Time Log) | So sánh thời gian tự tóm tắt với thời gian sử dụng AI, kiểm tra tính đầy đủ và số lượng nội dung cần chỉnh sửa. | #1, #2 |

**Dữ liệu tham khảo ban đầu từ sinh viên:**

| Trường | Sinh viên Phong | Sinh viên Trường | Sinh viên Duy |
|---|---|---|---|
| Người được đề cập | Sinh viên CNTT, đang học nhiều môn trong một kỳ. | Sinh viên CNTT, chuẩn bị thi cuối kỳ. | Sinh viên CNTT, đang học nhiều môn trong một kỳ. |
| Khó khăn được ghi nhận | Tổng hợp tài liệu và tóm tắt nội dung. | Tự đọc, chọn lọc và xây dựng đề cương. | Tìm kiếm nội dung quan trọng cần ôn tập. |
| Cách xử lý hiện tại | Sử dụng đề cương môn học làm khung, chia sẻ công việc với bạn bè. | Tự đọc tài liệu, chọn lọc ý chính và sắp xếp thành đề cương. | Tìm kiếm và lọc nội dung cần học từ tài liệu hiện có. |
| Thời gian ước lượng | Khoảng 36 phút/môn/tuần. | Khoảng 2–3 giờ/môn. | Khoảng 15–20 phút để tìm nội dung cần ôn. |
| Insight ban đầu | Cần giảm công sức tổng hợp nội dung từ nhiều nguồn. | Cần giảm thời gian đọc và chọn lọc kiến thức. | Cần xác định nhanh nội dung trọng tâm. |

> ⚠️ Đây là thông tin tham khảo được ghi nhận trong tài liệu nhóm, **chưa phải kết quả của ba cuộc phỏng vấn độc lập** đã được xác nhận. Không dùng bảng này thay thế dữ liệu Quick Interview thực tế.

**Câu hỏi Quick Interview (hỏi hành vi đã xảy ra):**

| STT | Câu hỏi phỏng vấn | Mục đích |
|---|---|---|
| 1 | Lần gần nhất bạn tự xây dựng đề cương ôn thi là khi nào? | Xác định hành vi thực tế. |
| 2 | Khi đó bạn đã sử dụng những tài liệu nào và thực hiện các bước ra sao? | Tìm hiểu quy trình hiện tại. |
| 3 | Bạn mất bao lâu để hoàn thành đề cương đó? | Xác định thời gian thực tế. |
| 4 | Công đoạn nào khiến bạn mất nhiều thời gian nhất? | Xác định bottleneck. |
| 5 | Bạn đã từng sử dụng đề cương có sẵn hoặc chia sẻ tài liệu với bạn bè chưa? Việc đó giúp giảm thời gian ở bước nào? | Tìm tín hiệu phản bác giả định #4. |

> ⚠️ Không hỏi những câu như *"Nếu có AI hỗ trợ thì bạn có muốn sử dụng không?"* vì đây là câu hỏi về ý định, không phải bằng chứng hành vi đã xảy ra.

**Nội dung Mini Poll:**

| STT | Câu hỏi | Các lựa chọn |
|---|---|---|
| 1 | Trong kỳ học gần nhất, bạn đã từng tự xây dựng đề cương ôn thi từ nhiều nguồn tài liệu chưa? | Có / Không |
| 2 | Trong lần gần nhất tự xây dựng đề cương, bạn mất bao lâu để hoàn thành một môn? | Dưới 1 giờ / 1–2 giờ / 2–3 giờ / Trên 3 giờ / Chưa từng thực hiện |
| 3 | Công đoạn nào khiến bạn mất nhiều thời gian nhất khi xây dựng đề cương? | Gom tài liệu / Đọc và tóm tắt / Xác định nội dung trọng tâm / Trình bày đề cương |
| 4 | Trong lần gần nhất chuẩn bị đề cương, bạn đã sử dụng phương pháp nào? | Tự làm hoàn toàn / Sử dụng template / Dùng đề cương của bạn bè / Sử dụng AI / Kết hợp nhiều phương pháp |

Tiêu chí đánh giá kết quả:

- Tỷ lệ sinh viên từng tự xây dựng đề cương từ nhiều nguồn tài liệu.
- Tỷ lệ sinh viên mất trên 2 giờ cho một môn.
- Công đoạn được lựa chọn nhiều nhất.
- Tỷ lệ sinh viên đang sử dụng các phương pháp thay thế AI.

**Time Log — Bấm giờ thực tế** (bổ sung bắt buộc theo Assumption Map, kiểm chứng #1 và #2):

| Tiêu chí | Phương pháp tự tóm tắt | Phương pháp sử dụng AI |
|---|---|---|
| Bộ tài liệu | Cùng một chương học | Cùng một chương học |
| Thời gian thực hiện | Ghi nhận thời gian đọc và tóm tắt. | Ghi nhận thời gian tải tài liệu, tạo bản tóm tắt và kiểm tra. |
| Nội dung bị bỏ sót | Đối chiếu với tài liệu gốc. | Đối chiếu với tài liệu gốc. |
| Số lỗi cần chỉnh sửa | Ghi nhận số lỗi trong bản tóm tắt. | Ghi nhận số lỗi trong bản AI. |
| Kết quả | Đề cương do sinh viên tự xây dựng. | Đề cương do AI hỗ trợ, có sinh viên kiểm tra. |

Cách đánh giá:

- **#1** được ủng hộ nếu AI giữ được các chương và ý chính quan trọng theo tiêu chí đối chiếu đã xác định.
- **#2** được ủng hộ nếu tổng thời gian tạo và kiểm tra bản AI thấp hơn đáng kể so với phương pháp tự làm.

> Dùng cùng một tài liệu, cùng một tiêu chí đánh giá và ghi nhận thời gian thực tế. Một lần thử chỉ là tín hiệu ban đầu, chưa đủ để khẳng định hiệu quả cho mọi môn học.

**Tổng hợp kết quả kiểm chứng:**

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác / Giới hạn |
|---|---|---|---|
| Dữ liệu nhóm ban đầu | 3 trường hợp được ghi nhận | Có các khó khăn liên quan đến tìm kiếm, đọc và tổng hợp nội dung. | Thời gian chỉ là ước lượng, chưa xác nhận bằng phỏng vấn độc lập hoặc bấm giờ. |
| Quick Interview | Chờ phỏng vấn 3–5 người | Chờ ghi nhận hành vi, thời gian và bottleneck thực tế. | Có thể có sinh viên sử dụng đề cương có sẵn và không cần tự xây dựng. |
| Mini Poll | Chờ khảo sát | Chờ xác định tỷ lệ sinh viên gặp vấn đề và phương pháp đang sử dụng. | Có thể vấn đề không phổ biến ở toàn bộ sinh viên. |
| Time Log | Chờ thử nghiệm | Chờ so sánh thời gian và độ đầy đủ của hai phương pháp. | AI có thể cần nhiều thời gian chỉnh sửa hoặc bỏ sót nội dung quan trọng. |

> Khi hoàn thành các hoạt động kiểm chứng, thay nội dung chờ kết quả bằng số liệu và quan sát thực tế.

**Nhóm đã sửa problem thế nào sau kiểm chứng:** xem mục 3.4 — Kết luận và điều chỉnh Problem.

### 3.3. Research

**Mục tiêu nghiên cứu:** tìm kiếm và phân tích các nghiên cứu khoa học, bài báo và tài liệu đã được công bố nhằm kiểm chứng cơ sở của các giả định trong Assumption Map, tập trung vào ba vấn đề: **Study Behavior**, **AI Summarization**, **Factual Accuracy**.

| Tiêu chí | Research 01 – Study Behavior | Research 02 – AI Summarization | Research 03 – Factual Accuracy |
|---|---|---|---|
| Tên nghiên cứu | To What Extent Do Study Habits Relate to Performance? | Automatically Generated Summaries of Video Lectures May Enhance Students' Learning Experience | Understanding Factual Errors in Summarization: Errors, Summarizers, Datasets, Error Detectors |
| Tác giả / Nguồn | Elise M. Walck-Shannon và cộng sự – CBE—Life Sciences Education (2021). | Hannah Gonzalez và cộng sự – ACL Anthology, BEA 2023. | Liyan Tang và cộng sự – ACL Anthology, ACL 2023. |
| Đối tượng / Phạm vi | Nghiên cứu thói quen học tập và mối liên hệ với kết quả thi của sinh viên đại học. | Nghiên cứu sử dụng mô hình ngôn ngữ lớn để tạo bản tóm tắt video bài giảng và đánh giá trải nghiệm học tập. | Nghiên cứu lỗi thông tin sai sự thật trong các bản tóm tắt được tạo tự động. |
| Kết quả nghiên cứu | - Sinh viên sử dụng trung bình khoảng 4 phương pháp học tập chủ động.<br>- Khoảng một nửa thời gian học được dành cho các phương pháp này.<br>- Việc sử dụng nhiều phương pháp học tập chủ động có mối liên hệ tích cực với kết quả thi.<br>- Sinh viên bắt đầu ôn tập trung bình khoảng 6 ngày trước kỳ thi. | - Nghiên cứu sử dụng GPT-3 và các mô hình ngôn ngữ lớn để tạo bản tóm tắt video bài giảng.<br>- Nhóm được xem video kèm bản tóm tắt có kết quả quiz tốt hơn nhóm chỉ có video hoặc chỉ có bản tóm tắt.<br>- Sinh viên đánh giá bản tóm tắt hữu ích khi học trong điều kiện hạn chế thời gian. | - Các mô hình tóm tắt tự động có thể tạo ra lỗi sai về thông tin so với nội dung nguồn.<br>- Khả năng phát hiện lỗi khác nhau tùy mô hình và loại lỗi.<br>- Không có một phương pháp đánh giá độ chính xác nào tốt nhất trong mọi trường hợp. |
| Liên hệ với Problem | Sinh viên cần chọn lọc, xử lý và hệ thống hóa kiến thức để phục vụ quá trình ôn tập thay vì chỉ đọc lại tài liệu. | AI có tiềm năng hỗ trợ sinh viên tiếp cận và tổng hợp kiến thức nhanh hơn thông qua bản tóm tắt bài giảng. | Bản tóm tắt do AI tạo ra vẫn có nguy cơ chứa thông tin sai lệch hoặc không nhất quán với tài liệu gốc. |
| Hạn chế / Tín hiệu phản bác | Nghiên cứu không trực tiếp chứng minh sinh viên mất nhiều thời gian để gom slide, giáo trình và ghi chú. | Nghiên cứu tập trung vào video bài giảng, chưa chứng minh khả năng tổng hợp nhiều định dạng tài liệu thành đề cương đầy đủ. | Nghiên cứu tập trung vào lỗi factuality của các hệ thống tóm tắt, không trực tiếp đo mức độ bỏ sót chương trong đề cương ôn thi. |
| Insight / Opportunity | Công cụ hỗ trợ cần giúp sinh viên hệ thống hóa kiến thức thành cấu trúc rõ ràng để phục vụ học tập chủ động. | AI có thể hỗ trợ dựng đề cương nhưng cần cho phép sinh viên kiểm tra và chỉnh sửa nội dung. | Sản phẩm cần hỗ trợ đối chiếu nội dung AI với tài liệu gốc để sinh viên kiểm tra những thông tin chưa chính xác. |
| Giả định liên quan | #3, #4 | #1, #2 | #1, #2 |
| Link nghiên cứu | [Xem nghiên cứu 01](https://www.lifescied.org/doi/10.1187/cbe.20-12-0277) | [Xem nghiên cứu 02](https://aclanthology.org/2023.bea-1.47/) | [Xem nghiên cứu 03](https://aclanthology.org/2023.acl-long.690/) |

**Tổng hợp kết quả Research:**

| Vấn đề nghiên cứu | Bằng chứng ủng hộ | Hạn chế / Bằng chứng phản bác | Kết luận |
|---|---|---|---|
| Sinh viên cần hệ thống hóa kiến thức để ôn thi. | Research 01 cho thấy các phương pháp học tập chủ động có mối liên hệ tích cực với kết quả thi. | Chưa chứng minh trực tiếp sinh viên mất 2–3 giờ để xây dựng đề cương. | Có cơ sở về nhu cầu hệ thống hóa kiến thức, cần khảo sát thêm hành vi thực tế. |
| AI có thể hỗ trợ tóm tắt tài liệu học tập. | Research 02 cho thấy bản tóm tắt AI có thể hỗ trợ trải nghiệm học tập khi kết hợp với video bài giảng. | Chưa chứng minh khả năng tổng hợp nhiều loại tài liệu thành đề cương hoàn chỉnh. | Có cơ sở để thử nghiệm AI trong việc hỗ trợ tổng hợp kiến thức. |
| Nội dung AI tạo ra có đảm bảo chính xác không? | AI có khả năng tạo bản tóm tắt tự động từ tài liệu nguồn. | Research 03 chỉ ra nguy cơ xuất hiện lỗi thông tin và khó khăn trong việc phát hiện lỗi. | Cần có cơ chế đối chiếu và kiểm tra nội dung AI trước khi sử dụng. |

### 3.4. Kết luận và điều chỉnh Problem sau kiểm chứng

**Những phát hiện chính:**

- **Về hành vi học tập:** Sinh viên cần chọn lọc và hệ thống hóa kiến thức để phục vụ ôn tập. Mức độ mất thời gian khi xây dựng đề cương vẫn cần xác nhận bằng phỏng vấn và khảo sát thực tế.
- **Về khả năng ứng dụng AI:** AI có tiềm năng hỗ trợ tóm tắt bài giảng và giảm công sức tiếp cận kiến thức, nhưng chưa có đủ bằng chứng để khẳng định khả năng tổng hợp nhiều định dạng tài liệu.
- **Về độ chính xác:** Nội dung AI tạo ra có thể chứa lỗi hoặc thiếu thông tin, vì vậy sinh viên vẫn cần kiểm tra và đối chiếu với tài liệu gốc.

**Problem ban đầu và Problem sau điều chỉnh:**

| Tiêu chí | Problem ban đầu | Problem sau điều chỉnh |
|---|---|---|
| Nội dung | Sinh viên mất nhiều thời gian để tổng hợp slide, giáo trình và ghi chú thành đề cương ôn tập trước kỳ thi. | Sinh viên gặp khó khăn trong việc chọn lọc, hệ thống hóa và tổng hợp kiến thức từ nhiều nguồn tài liệu thành đề cương ôn thi có cấu trúc. |
| Trọng tâm vấn đề | Tập trung chủ yếu vào thời gian xây dựng đề cương. | Bổ sung vấn đề về tính đầy đủ, chính xác và khả năng kiểm tra nội dung sau khi tổng hợp. |
| Nhu cầu | Giảm thời gian tự đọc và tóm tắt tài liệu. | Giảm công sức tổng hợp kiến thức nhưng vẫn đảm bảo nội dung quan trọng được giữ lại và có thể đối chiếu với tài liệu gốc. |
| Vai trò AI | Công cụ hỗ trợ tạo đề cương nhanh hơn. | Công cụ hỗ trợ tổng hợp và hệ thống hóa kiến thức, không thay thế hoàn toàn việc kiểm tra của sinh viên. |

**Problem Statement sau điều chỉnh:**

> Sinh viên gặp khó khăn trong việc chọn lọc, hệ thống hóa và tổng hợp kiến thức từ nhiều nguồn tài liệu như slide, giáo trình và ghi chú thành một đề cương ôn thi có cấu trúc. Quá trình này đòi hỏi thời gian đọc, chọn lọc và xử lý thông tin. AI có tiềm năng hỗ trợ giảm công sức tổng hợp, nhưng vẫn tồn tại rủi ro về độ chính xác và khả năng bỏ sót nội dung quan trọng. Vì vậy, sinh viên cần một giải pháp hỗ trợ xây dựng đề cương nhanh hơn, đồng thời cho phép kiểm tra và đối chiếu nội dung với tài liệu gốc.

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
