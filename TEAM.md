# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: Newbie
- Candidate problem nhóm chọn (1 câu): Sinh viên mất khoảng 2–3 giờ/môn để gom, đọc và tổng hợp tài liệu thành đề cương ôn tập nhưng vẫn chưa chắc đã đủ các chương.
- Quyết định cuối (Go / Not Yet / No-Go): Not Yet

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Nguyễn Trung Duy | 2A202603387 | nhóm trưởng, điều phối + hội tụ nhóm (CP3) | duy321111 |
| 2 | Trần Nguyên Anh Phong | 2A202603629 | thành viên, vẽ quy trình (CP5) | anhphongtrng |
| 3 | Võ Sỹ Thái Sơn | 2A202603623 | thành viên, mức can thiệp AI + quyết định (CP6) | SonVinUni |
| 4 | Phạm Quang Trường | 2A202603378 | thành viên, kiểm chứng + research (CP4) | truongpham090325 |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Duy | Trường, Phong, Sơn | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | Trường | Phong | Assumption map, snapshot hoặc survey |
| CP4 — Research | Trường | Duy | Bảng research có link |
| CP5 — Quy trình trước/sau | Phong | Duy | Quy trình + bảng before/after |
| CP5 — Problem Statement v0 | Phong | Sơn | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | Sơn | Trường | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định | Sơn | Duy | 4 rủi ro + Go/Not Yet/No-Go |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### Phạm Quang Trường - 2A202603378

**Phần việc phụ trách:**

- Thực hiện Problem Scan (CP1) với 8 vấn đề về học tập: gom tài liệu phân tán, tóm tắt nội dung, xác định phần chưa nắm vững...
- Xây dựng 3 Problem Card (CP2): Dựng đề cương ôn tập (T1), Gom tài liệu phân tán (T2), Xác định phần chưa nắm vững (T3).
- Pitch candidate T1 — Dựng đề cương ôn tập; đây là candidate được nhóm chọn làm bài toán chính (CP3).
- Phụ trách kiểm chứng và research (CP4): Assumption Map, thiết kế Quick Interview / Mini Poll / Time Log, tổng hợp 3 nghiên cứu và điều chỉnh Problem Statement sau kiểm chứng.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Hoàn thành bảng Problem Scan 8 vấn đề kèm Job Story, người chịu ảnh hưởng và dấu hiệu thực tế đo được.
- Xây dựng Problem Card T1 với quy trình 6 bước, xác định bottleneck là bước "tóm tắt từng chương" (khoảng 1,5–2 giờ/môn trong tổng 2–3 giờ/môn).
- Lập Assumption Map gồm 6 giả định và chọn 3 giả định ưu tiên kiểm chứng (#1, #2, #3).
- Thiết kế bộ câu hỏi Quick Interview (5 câu), Mini Poll (4 câu) và bảng Time Log so sánh tự tóm tắt với dùng AI.
- Tổng hợp 3 nghiên cứu khoa học (Study Behavior, AI Summarization, Factual Accuracy) và viết kết luận điều chỉnh Problem Statement.
- Đặt câu hỏi phản biện cho card của các bạn khác (D2, P2, S1, S2, S3).

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/individual/202603378_PhamQuangTruong.md` — mục 2 (CP1 Scan), mục 3 (CP2 Top 3 Problem Cards).
- `report/team/group_report.md` — mục 3 (CP4: Assumption Map, Kiểm chứng, Research).
- Commit `a907b4e` — "Feat: Fill CP4 (Assumption Map, Validation, Research) into group report".

**Điều mình học được từ phần nhóm:**

- Candidate T1 của mình được chọn nhờ quy trình rõ và có baseline đo được, không phải vì cảm giác "đau" — nên ngay từ đầu cần làm rõ quy trình và số liệu.
- Con số "2–3 giờ/môn" ban đầu chỉ là ước lượng; câu hỏi phản biện "đã đo thật chưa?" khiến nhóm đưa Time Log vào kiểm chứng thay vì tin vào ước lượng.
- Cây OST giúp phân biệt "solution đội lốt opportunity" (ví dụ "AI tóm tắt từng chương" là giải pháp, không phải nhu cầu), nhờ đó giữ Problem Statement ở đúng tầng nhu cầu.
