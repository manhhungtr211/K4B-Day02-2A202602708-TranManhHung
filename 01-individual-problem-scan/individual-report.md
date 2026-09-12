# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Trần Mạnh Hùng
- Mã học viên: 2A202602708
- Vai trò / bối cảnh: sinh viên vừa tốt nghiệp ngành Khoa học dữ liệu, đang tham gia khóa đào tạo AI thực chiến

- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
    - Học tiếng anh
    - Lên todo và sắp xếp công việc
    - Đặt tên, sắp xếp các tài liệu đã tải xuống
    - Tìm các tài liệu, thông tin cần thiết cho từng môn

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lấy từ mới, tra từ, đưa vào quizlet|Tốn thời gian , lặp lại |Người học tiếng anh | Tốn 3-5 phút mỗi từ tra|
| 2 | tìm món ăn, địa điểm ăn uống |Tốn thời gian, lặp lại |Tôi | Tốn 10-15 phút mỗi lần tra|
| 3 | nhắn tin trao đổi với nhóm để thống nhất lịch học tập| khó khăn khi thống nhất thời gian |Tôi và các bạn trong nhóm | Tốn cả tiếng mỗi lần trao đổi|
| 4 | tìm kiếm teammate cho các bài tập, cuộc thi|khó khăn khi tìm kiếm, không biết ai phù hợp |Tôi và các bạn sinh viên |tốn 3-5 ngày để tìm được team |
| 5 |liên tục phải truy cập vào các group để tìm phòng thuê|lặp lại, tốn thời gian |Tôi và các bạn sinh viên |tốn 15-20 ngày để tìm được phòng phù hợp |
| 6 |sắp xếp ,đặt tên cho các tài liệu tải về| lặp lại, tốn thời gian |Tôi | Tốn 10-15 phút mỗi lần tra|
| 7 | | | | |
| 8 | | | | |
| 9 | | | | |
| 10 | | | | |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi:
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**
- [ ] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [ ] Dùng ít nhất 3/4 lăng kính
- [ ] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Lấy từ mới, tra từ, đưa vào quizlet | Xảy ra hằng ngày, lặp lại nhiều lần, có thể tự động hóa dễ dàng | Độ chính xác của AI khi hiểu ngữ cảnh của từ |
| 2 | Tìm món ăn, địa điểm ăn uống | Tốn thời gian, lặp lại, thường xuyên gặp bế tắc khi ra quyết định | AI có thể recommend quán ăn không có trên bản đồ hay không |
| 3 | Tìm kiếm teammate cho các bài tập, cuộc thi | Pain lớn, khó khăn trong việc tìm người phù hợp, tốn kém thời gian chờ đợi | AI lấy dữ liệu profile của mọi người từ đâu để match |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Tốn thời gian lưu từ vựng

```text
Problem 1 câu: tốn thời gian lưu từ vựng

Actor:tôi và các bạn sinh viên

Thời điểm / bối cảnh: học tiếng anh 

Current workflow 3-7 bước:
1. Chọn từ vựng cần học (thường là khi đọc tài liệu)/ xem video nghe giảng/ xem phim
2. Tra từ vựng qua từ điển
3. Copy từng mục và thêm từ vựng vào quizlet

Bottleneck: lặp đi lặp lại

Impact: tốn thời gian, lặp lại

Success metric: thêm được từ vựng lưu vào các mục phù hợp

Non-AI alternative: Không dùng quizlet, học từ vựng bằng cách khác

AI hypothesis: Dùng AI Agent để tự động chọn ra các từ phù hợp level, tự động tra cứu và thêm từ vựng vào quizlet

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[x] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 10 phút / từ

[1 Chọn từ vựng: 2'] → [2 Tra từ điển: 3'] → [3 Copy/Paste vào Quizlet: 5']  <-- bottleneck

FUTURE STATE — 2 phút / từ

[1 AI tự động nhận diện và trích xuất từ khó: 1'] → [2 AI tự tra nghĩa và nạp Quizlet: 0'] → [3 Human review: 1']  <-- human boundary

Fallback: nếu AI sai thì học luôn cũng được, không sao, hoặc sửa lại bằng tay trên Quizlet.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Khó khăn khi tìm địa điểm ăn uống

```text
Problem 1 câu: khó khăn khi tìm món ăn, địa điểm ăn uống

Actor:tôi và các bạn

Thời điểm / bối cảnh: buổi trưa/ tối khi đi học

Current workflow 3-7 bước:
1. Mở google maps tìm quán 
2. Đọc review quán trên mạng
3. Mở thread/fb tìm quán
4. Tra vị trí trên google map
5. Đi đến quán

Bottleneck: tốn thời gian khi tìm kiếm, lặp đi lặp lại, mất nhiều thời gian để tìm được quán ưng ý

Impact: tốn thời gian, lặp lại

Success metric: tìm được quán đúng ý trong thời gian 2-5p

Non-AI alternative: chọn bừa 1 quán gần đó để ăn

AI hypothesis: Dùng AI Agent để tự động tìm kiếm, tổng hợp thông tin và đưa ra các lựa chọn phù hợp theo yêu cầu

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[x] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 20 phút

[1 Mở google maps tìm quán: 3'] → [2 Đọc review/bài đăng FB: 5'] <-- bottleneck → [3 Chốt quán và tìm đường: 12']

FUTURE STATE — 5 phút

[1 Nhập yêu cầu món ăn/giá/vị trí: 1'] → [2 AI tổng hợp top 3 quán + tóm tắt review: 1'] → [3 Human review và chọn: 3']  <-- human boundary

Fallback: Chọn bừa 1 quán gần nhất nếu AI không tìm được hoặc recommend sai.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Tìm kiếm teammate cho bài tập, cuộc thi

```text
Problem 1 câu: tìm kiếm teammate cho bài tập, cuộc thi

Actor: tôi và các bạn sinh viên

Thời điểm / bối cảnh: bắt đầu làm bài tập/ tham gia cuộc thi

Current workflow 3-7 bước:
1. đăng lên group tìm teammate
1a. lướt các group để tìm nhóm tuyển người, comment
2. chờ đợi trả lời, nếu không đủ người/phù hợp sẽ đăng lại
3. nhắn tin riêng cho từng người để trao đổi, chốt nhóm

Bottleneck: tốn thời gian, khó tìm được nhóm phù hợp

Impact: mất nhiều thời gian để tìm được nhóm phù hợp, lặp lại

Success metric: tìm được nhóm phù hợp trong thời gian 1-2 ngày

Non-AI alternative: chọn bừa 

AI hypothesis: Dùng AI để đề xuất những bạn phù hợp với profile, định hướng để join team

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[x] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 2-3 ngày

[1 Đăng bài tìm nhóm: 15'] → [2 Chờ đợi và lướt tìm nhóm: 1-2 ngày] <-- bottleneck → [3 Nhắn tin trao đổi với từng người: 2-3 giờ]

FUTURE STATE — 2-3 giờ

[1 Nhập profile và yêu cầu tìm team: 10'] → [2 AI tự động match với các profile phù hợp: 5'] → [3 Human review và nhắn tin chốt: 2-3 giờ]  <-- human boundary

Fallback: Quay lại cách cũ, tự đăng bài và tìm kiếm thủ công trên các group.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Tốn thời gian lưu từ vựng
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Quy trình hiện tại gồm các bước chọn từ phù hợp trình độ, tra từ điển, sau đó copy và paste vào Quizlet gây tốn rất nhiều thời gian (khoảng 10 phút/từ nếu làm kĩ). Nếu tự động hóa, người học có thể tiết kiệm hàng giờ mỗi tuần, giảm sự nhàm chán và tăng cường hiệu quả học tập. 
Impact trực tiếp đến tất cả những người đang học tiếng Anh.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
Làm sao để AI hiểu chính xác ngữ nghĩa của từ trong bối cảnh bài đọc đó (vì một từ tiếng Anh có nhiều nghĩa)?
Việc tự động hóa hoàn toàn bước "lưu từ" có khiến người học mất đi cơ hội tiếp xúc với từ để "nhớ từ" do không phải tự tay gõ lại không?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Quá trình tự gõ từ vào Quizlet thực chất là một bước ghi nhớ. Tự động hóa hoàn toàn có thể làm giảm khả năng nhớ từ.
- Tôi sửa gì: Thêm bước Human Review (Tự đánh giá) từ vựng trước khi học, yêu cầu AI không chỉ nạp từ vựng mà còn tạo các câu ví dụ từ ngữ cảnh để tăng hiệu quả ghi nhớ.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
