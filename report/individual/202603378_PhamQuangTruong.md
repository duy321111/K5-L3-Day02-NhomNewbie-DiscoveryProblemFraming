# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên:
- MSSV:
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm:
- Link repo nhóm:

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

|   # | Lăng kính                         | Job Story: Khi… tôi muốn… để…                                                                                       | Ai chịu ảnh hưởng?       | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
| --: | --------------------------------- | ------------------------------------------------------------------------------------------------------------------- | ------------------------ | --------------------------------------------------------- |
|   1 | Lặp lại                           | Khi tới sáng thứ Hai, tôi muốn có số liệu sprint và tình hình team ở một chỗ, để gửi báo cáo tuần cho CEO trước 10h | PM, EM, CEO              | Tự bấm giờ 2 tuần gần nhất: 85 và 95 phút                 |
|   2 | Lặp lại                           | Khi cập nhật slide cho buổi họp tháng, tôi muốn có sẵn velocity các sprint, để không phải copy tay từ Jira          | PM                       | Mỗi tháng 1 lần, khoảng 20 phút                           |
|   3 | Tốn thời gian                     | Khi nhận một PRD 10–15 trang cần review, tôi muốn nắm nhanh các quyết định chính, để comment đúng chỗ trước hạn     | PM reviewer, design lead | Khoảng 45 phút/bản, 2 bản/tuần                            |
|   4 | Tốn thời gian                     | Khi vừa xong một cuộc họp liên team, tôi muốn có danh sách việc cần làm và người phụ trách, để không ai bỏ sót      | PM, team                 | 30 phút/buổi viết lại ghi chú                             |
|   5 | Cần đọc, tổng hợp nhiều thông tin | Khi có quá nhiều task cùng hạn, tôi muốn biết nên làm việc nào trước, để không trễ việc quan trọng                  | PM, team                 | Tuần trước trễ 2 task vì ưu tiên sai                      |
|   6 | Cần đọc, tổng hợp nhiều thông tin | Khi cần biết vì sao team từng chọn phương án A, tôi muốn tìm lại được quyết định cũ, để không tranh luận lại từ đầu | Cả team                  | 10–15 phút mỗi lần tìm trong Slack, 3–4 lần/tuần          |
|   7 | Pain từ người khác                | Khi designer nhận spec từ tôi, họ muốn hiểu đúng yêu cầu ngay lần đầu, để không phải hỏi lại                        | Designer, PM             | Designer hỏi lại 2–3 lần/spec (đếm từ thread Slack)       |
|   8 | Pain từ người khác                | Khi CEO cần chuẩn bị họp leadership sáng thứ Hai, CEO muốn có báo cáo trước giờ họp, để nắm tình hình               | CEO, PM                  | 3/8 tuần gần nhất báo cáo gửi trễ                         |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- ***

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem                | Vì sao chọn                                      | Điều còn chưa chắc                              |
| ---: | ---------------------- | ------------------------------------------------ | ----------------------------------------------- |
|    1 | Báo cáo tuần (#1)      | Quy trình rõ, tốn thời gian, có baseline đo thật | Narrative "đủ tốt" đo thế nào?                  |
|    2 | Review PRD (#3)        | Pain thật, nhiều người gặp                       | Chất lượng review khó đo                        |
|    3 | Tìm quyết định cũ (#6) | Nhiều người đau, impact rộng                     | Quyền truy cập dữ liệu khó, phạm vi dễ quá rộng |

### Problem Card #1 — Báo cáo tuần

| Trường                                    | Nội dung                                                                                                                                                                                                                  |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi tới sáng thứ Hai, tôi muốn có số liệu sprint và tình hình team ở một chỗ, để gửi báo cáo tuần cho CEO trước 10h                                                                                                       |
| Actor                                     | Junior PM phụ trách báo cáo tuần cho EM và CEO                                                                                                                                                                            |
| Thời điểm / bối cảnh                      | Sáng thứ Hai, trước buổi họp leadership lúc 10h                                                                                                                                                                           |
| Quy trình hiện tại (3–7 bước)             | 1. Export dữ liệu sprint từ Jira · 2. Lấy số từ Google Sheets · 3. Đọc lại Slack cả tuần · 4. Tổng hợp vào Google Docs · 5. Viết narrative (điểm nổi bật, rủi ro, việc tiếp theo) · 6. Tự review và format · 7. Gửi email |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 5, viết narrative: khoảng 25 phút, hay bị "trang trắng"                                                                                                                                                              |
| Impact (nếu không giải thì sao)           | 90 phút/tuần cho 1 PM; công ty có 3 PM nên khoảng 270 phút/tuần; 3/8 tuần gần nhất gửi trễ                                                                                                                                |
| Success metric (baseline → target)        | Tổng thời gian từ 90 phút → dưới 30 phút; số câu hỏi lại từ CEO/EM không tăng                                                                                                                                             |
| Phương án không dùng AI                   | Template cố định + dashboard Jira + checklist: giảm thời gian format, chưa giảm thời gian viết narrative                                                                                                                  |
| Giả thuyết về AI (nếu có)                 | AI soạn nháp narrative từ dữ liệu đã gom; PM review và sửa trước khi gửi                                                                                                                                                  |
| Cảm nhận nhanh                            | Workflow                                                                                                                                                                                                                  |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 90 phút

[1 Export Jira: 10'] → [2 Lấy số Sheets: 10'] → [3 Đọc Slack: 15']
→ [4 Tổng hợp Docs: 15'] → [5 Viết narrative: 25'] ← BOTTLENECK
→ [6 Review + format: 10'] → [7 Gửi: 5']
```

### Problem Card #2 — Review PRD

| Trường                                    | Nội dung                                                                                                                                                                                        |
| ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi nhận một PRD 10–15 trang cần review, tôi muốn nắm nhanh các quyết định chính, để comment đúng chỗ trước hạn                                                                                 |
| Actor                                     | PM reviewer và design lead phụ trách review PRD                                                                                                                                                 |
| Thời điểm / bối cảnh                      | Khi nhận PRD cần review trước hạn, khoảng 2 bản/tuần                                                                                                                                            |
| Quy trình hiện tại (3–7 bước)             | 1. Nhận PRD và đọc lướt cấu trúc · 2. Đọc kỹ 10–15 trang để nắm ngữ cảnh và quyết định chính · 3. Đối chiếu với yêu cầu/ngữ cảnh cũ · 4. Ghi comment vào từng mục · 5. Trao đổi lại với tác giả |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2, đọc kỹ 10–15 trang để nắm ngữ cảnh: khoảng 30 phút trong tổng 45 phút/bản                                                                                                               |
| Impact (nếu không giải thì sao)           | 45 phút/bản × 2 bản/tuần ≈ 90 phút/tuần; comment trễ hoặc nông làm chậm design                                                                                                                  |
| Success metric (baseline → target)        | Thời gian từ 45 phút/bản → 20 phút/bản; số câu hỏi lại từ design lead không tăng                                                                                                                |
| Phương án không dùng AI                   | Template/checklist các mục cần review: giảm sót mục, chưa giảm thời gian đọc                                                                                                                    |
| Giả thuyết về AI (nếu có)                 | AI tóm tắt PRD thành các quyết định chính và đánh dấu mục cần chú ý; PM vẫn tự đọc và comment                                                                                                   |
| Cảm nhận nhanh                            | Workflow                                                                                                                                                                                        |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 45 phút/bản

[1 Nhận + đọc lướt cấu trúc: 3'] → [2 Đọc kỹ 10–15 trang: 30'] ← BOTTLENECK
→ [3 Đối chiếu ngữ cảnh cũ: 5'] → [4 Ghi comment: 5'] → [5 Trao đổi lại: 2']
```

### Problem Card #3 — Tìm quyết định cũ

| Trường                                    | Nội dung                                                                                                                                                       |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi cần biết vì sao team từng chọn phương án A, tôi muốn tìm lại được quyết định cũ, để không tranh luận lại từ đầu                                            |
| Actor                                     | Thành viên team (PM, dev, design) cần tìm lại quyết định cũ                                                                                                    |
| Thời điểm / bối cảnh                      | Khi có tranh luận hoặc cần hiểu vì sao chọn phương án A                                                                                                        |
| Quy trình hiện tại (3–7 bước)             | 1. Nhớ đại khái chủ đề · 2. Gõ keyword tìm trong Slack · 3. Đọc lại cả thread dài · 4. Nếu không tìm thấy thì hỏi người liên quan · 5. Tổng hợp lại quyết định |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3, đọc lại cả thread để tìm đúng quyết định: khoảng 8–10 phút trong tổng 10–15 phút/lần                                                                   |
| Impact (nếu không giải thì sao)           | 10–15 phút mỗi lần, 3–4 lần/tuần; quyết định bị chậm, tranh luận lặp lại                                                                                       |
| Success metric (baseline → target)        | Thời gian từ 15 phút/lần → dưới 2 phút/lần; giảm số lần hỏi lại người cũ                                                                                       |
| Phương án không dùng AI                   | Quy ước ghi quyết định vào một nơi cố định (wiki/ADR): xử lý quyết định mới, chưa xử lý kho cũ                                                                 |
| Giả thuyết về AI (nếu có)                 | AI tìm kiếm và tóm tắt quyết định cũ từ Slack/wiki; người vẫn tự kiểm nguồn trước khi dùng                                                                     |
| Cảm nhận nhanh                            | Workflow hoặc Agent                                                                                                                                            |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 10–15 phút/lần
[1 Nhớ chủ đề: 1'] → [2 Gõ keyword tìm trong Slack: 2']
→ [3 Đọc lại cả thread: 8–10'] ← BOTTLENECK
→ [4 Hỏi người liên quan (nếu miss): 3'] → [5 Tổng hợp quyết định: 1']
```

### Card muốn pitch nhất

- Card số: 1 — Báo cáo tuần
- Vì sao: Quy trình rõ, tốn thời gian, có baseline đo thật (bấm giờ 2 tuần: 85 và 95 phút)
- Câu hỏi muốn nhóm phản biện: Narrative "đủ tốt" đo thế nào — làm sao đo chất lượng báo cáo chứ không chỉ thời gian?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra                    | Đồng ý?         | Đã sửa gì                                       |
| ------------------------------------- | --------------- | ----------------------------------------------- |
| Baseline 90 phút chỉ dựa trên trí nhớ | Đồng ý          | Bấm giờ thật 2 tuần: 85 và 95 phút              |
| Chưa chắc CEO đọc phần narrative      | Đồng ý một phần | Đưa vào danh sách giả định cần kiểm chứng ở CP4 |
| Gợi ý làm agent tự gửi báo cáo        | Không đồng ý    | Giữ "PM review trước khi gửi" làm boundary      |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động                  | Tôi đã làm gì?         | Kết quả / ảnh hưởng tới bài nhóm |
| -------------------------- | ---------------------- | -------------------------------- |
| Pitch Problem Card         |                        |                                  |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt:    |                                  |
| Nhận phản biện             | Câu hỏi tôi nhận được: | Tôi đã sửa gì:                   |
| Gom cluster / cây OST      |                        |                                  |
| Chọn candidate problem     |                        |                                  |
| Kiểm chứng / research      |                        |                                  |
| Quy trình nhóm             |                        |                                  |
| Problem Statement          |                        |                                  |
| Mức can thiệp AI           |                        |                                  |
| Quyết định                 |                        |                                  |

---

## 5. Dùng AI

| Checkpoint                     | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
| ------------------------------ | ---------------------- | ----------------- | -------------------------- | ----------------------------------- |
| CP1 Scan                       |                        |                   |                            |                                     |
| CP2 Problem Card               |                        |                   |                            |                                     |
| CP4 Research                   |                        |                   |                            |                                     |
| CP5 Quy trình                  |                        |                   |                            |                                     |
| CP5–6 Problem Statement        |                        |                   |                            |                                     |
| CP6 Mức can thiệp / quyết định |                        |                   |                            |                                     |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi _problem → quy trình → metric → boundary → mức can thiệp AI → quyết định_ của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
