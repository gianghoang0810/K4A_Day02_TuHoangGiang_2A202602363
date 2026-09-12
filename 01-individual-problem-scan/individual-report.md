# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Từ Hoàng Giang
- Mã học viên: 2A202602363
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...):
An, Media Buyer tại một Digital Marketing Agency khoảng 30 người. Mỗi tuần An phải tổng hợp số liệu từ Meta Ads, Google Ads và TikTok Ads để viết báo cáo tuần và đề xuất phân bổ ngân sách cho Brand Marketing Manager của 4 nhãn hàng.

- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
  + Sáng thứ Hai, đăng nhập vào 3 tài khoản quảng cáo (Meta Ads Manager, Google Ads, TikTok Ads Manager) để tải file CSV xuất số liệu hiệu suất tuần trước (Chi phí, CTR, CPC, CPA, ROAS) của 4 nhãn hàng.
  + Copy - paste và hợp nhất các bảng dữ liệu rời rạc vào một file Google Sheets tổng, sau đó tính toán tỷ lệ tăng/giảm so với tuần trước và đối soát với KPI mục tiêu của từng thương hiệu.
  + Phân tích các adset/chiến dịch biến động bất thường (CPA tăng cao, ngân sách cắn chậm) và tự gõ 3–5 gạch đầu dòng nhận xét định tính giải thích nguyên nhân cho từng nhãn hàng.
  + Dự toán ngân sách còn lại trong tháng và soạn bảng đề xuất phân bổ lại dòng tiền quảng cáo giữa các kênh cho tuần kế tiếp.
  + Ghép toàn bộ biểu đồ, số liệu và phần nhận xét vào mẫu Google Slides/PDF báo cáo của agency, rà soát lỗi chính tả rồi gửi email cho Brand Marketing Manager của 4 khách hàng trước 11:30 trưa.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại | Xuất CSV số liệu tuần từ Meta, Google, TikTok Ads ghép vào Sheet | An, Account Manager | Mất 60 phút mỗi sáng thứ Hai |
| 2 | Lặp lại | Copy bảng số liệu và biểu đồ từ Sheet vào slide báo cáo tuần | An | 4 slide template, lặp lại đều đặn mỗi tuần |
| 3 | Lặp lại | Gắn mã UTM tracking thủ công cho từng link bài quảng cáo trước khi bật chiến dịch | An, Data team | 20–30 link/tuần, mất 30 phút rà soát |
| 4 | Tốn thời gian | Viết 3–5 gạch đầu dòng nhận xét và giải thích nguyên nhân biến động CPA cho 4 nhãn hàng | An, Brand Manager | Mất 90–120 phút mỗi sáng thứ Hai |
| 5 | Tốn thời gian | Tính toán ngân sách còn lại trong tháng và soạn phương án tái phân bổ cho tuần tới | An, Media Lead | 30–45 phút/tuần |
| 6 | AI có thể tốt hơn | Dashboard Looker Studio chỉ hiện số liệu khô, không tự diễn giải insight/nguyên nhân adset giảm hiệu quả | An, Brand Manager | Client luôn hỏi thêm "tại sao số lại tụt?" sau khi xem biểu đồ |
| 7 | AI có thể tốt hơn | Đọc báo cáo Search Query trên Google Ads để tự động lọc danh sách từ khóa phủ định (Negative Keywords) | An | Đọc 200–300 search terms/tuần, dễ bỏ sót từ khóa rác |
| 8 | AI có thể tốt hơn | Nhận diện hiện tượng bão hòa tệp đối tượng (ad fatigue) trước khi chi phí CPA tăng vọt | An, Media Lead | Thường chỉ phát hiện sau khi chỉ số đã tệ 2–3 ngày |
| 9 | Pain từ người khác | Brand Marketing Manager nhắn tin giục vì 11:30 chưa nhận được báo cáo để kịp họp nội bộ đầu tuần | Brand Manager, An | Trễ hẹn gửi báo cáo 2 lần trong tháng qua |
| 10 | Pain từ người khác | Creative Designer phàn nàn vì không rõ mẫu video/banner nào chạy kém để làm mẫu mới thay thế | Designer, An | Hỏi đi hỏi lại 2–3 lần/tuần trên Slack |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Giúp tôi tìm các ví dụ tương tự như các bước của Minh kèm hình ảnh,
- Ý dùng được: Bảng 10 vấn đề đã chuẩn hóa số liệu và actor ở trên.
- Ý bỏ vì không phải pain thật:
  * **Bật/tắt thủ công campaign Flash Sale lúc 23:00:** Bị loại vì đây là bài toán scheduler/rule thuần túy (tính năng hẹn giờ có sẵn trên Ads Manager), không có độ phức tạp về tư duy hay ngôn ngữ để cần đến giải pháp sâu.
  * **Kiểm tra số dư tài khoản quảng cáo mỗi sáng (10 phút):** Thời gian quá ngắn (dưới 15 phút), mức độ ảnh hưởng thấp, giải quyết tốt bằng bot webhook thông báo số dư tự động thay vì coi là một problem lớn.
  * **Nhân bản (duplicate) nhóm quảng cáo thắng sang tài khoản dự phòng:** Thao tác chuột đơn giản chỉ mất vài click, tần suất không tạo thành điểm nghẽn nghiêm trọng cho năng suất cả tuần.
  * **Lập bảng dự toán ngân sách (forecast) khi pitch khách hàng mới:** Hoạt động diễn ra không đều đặn theo chu kỳ tuần (chỉ xuất hiện khi có khách mới), phụ thuộc nhiều vào đàm phán thương mại hơn là một workflow cố định lặp lại.
  * **Soát lỗi chính tả và link đích trước khi bật camp:** Thuộc về check-list kỷ luật cá nhân của Media Buyer; tần suất sai sót thực tế không đủ dày đặc để chứng minh là một điểm nghẽn hệ thống.
  * **Đối soát hóa đơn VAT và ủy nhiệm chi cuối tháng với Kế toán:** Chu kỳ theo tháng (Monthly), thuộc phạm vi nghiệp vụ hành chính - tài chính chứ không phải trọng tâm công việc chuyên môn hàng tuần của Media Buyer.

**Self-check Phase 1:**
- [X] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [X] Dùng ít nhất 3/4 lăng kính
- [X] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Dashboard Looker Studio chỉ hiện số liệu khô, không tự diễn giải insight/nguyên nhân adset giảm hiệu quả | • Giải quyết đúng điểm nghẽn lớn nhất của dashboard: người xem chỉ thấy số chứ không hiểu bản chất.<br>• Phù hợp với thế mạnh của AI trong việc đọc bảng số liệu và chuyển ngữ thành insight định tính.<br>• Giảm hẳn các câu hỏi phát sinh lặp đi lặp lại từ client hỏi "tại sao số tụt". | AI có thể suy diễn sai nguyên nhân bên ngoài (như thị trường, đối thủ) nếu chỉ dựa vào dữ liệu nội bộ trên dashboard. |
| 2 | Viết 3–5 gạch đầu dòng nhận xét và giải thích nguyên nhân biến động CPA cho 4 nhãn hàng | • Workflow cố định mỗi sáng thứ Hai, bottleneck rõ rệt ở bước tổng hợp phân tích.<br>• Tốn nhiều thời gian nhất (90–120 phút), impact đo được trực tiếp qua thời gian tiết kiệm.<br>• Ranh giới phân tầng Rule / Workflow / Agent rất rõ ràng. | Chất lượng nhận xét của AI có đủ sâu và hợp văn phong agency để client chấp nhận không? |
| 3 | Xuất CSV số liệu tuần từ Meta, Google, TikTok Ads ghép vào Sheet | • Quy trình lặp lại tuyệt đối vào sáng thứ Hai.<br>• Tiết kiệm ngay 60 phút thao tác tay chân cố định.<br>• Đo lường hiệu quả trước/sau cực kỳ dễ dàng. | Bài toán này thuần về Rule/Automation script (ETL/Zapier), chưa phát huy mạnh thế mạnh suy luận của AI. |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Tự động diễn giải insight và nguyên nhân biến động hiệu quả trên Looker Studio Dashboard

```text
Problem 1 câu:
Dashboard Looker Studio chỉ hiển thị biểu đồ và chỉ số hiệu suất thô mà không tự động diễn giải nguyên nhân biến động (CPA, CTR), khiến Brand Marketing Manager liên tục nhắn tin/gọi điện hỏi giải trình ngoài giờ và Media Buyer mất thời gian tra cứu lắt nhắt trong tuần.

Actor:
An (Media Buyer) và Brand Marketing Manager (khách hàng theo dõi dashboard).

Thời điểm / bối cảnh:
Sau 12:00 trưa thứ Hai hàng tuần (sau khi số liệu tuần mới được đồng bộ lên Looker Studio), kéo dài rải rác suốt cả tuần làm việc.

Current workflow 3-7 bước:
1. Cập nhật bảng số liệu tuần mới lên Looker Studio: 10'
2. Client truy cập dashboard, thấy biểu đồ biến động (ví dụ: CPA tăng đột biến) nhưng không hiểu nguyên nhân: 10'
3. Client nhắn tin trên Zalo/Slack hỏi An: "Tại sao adset tuần này CPA lại tăng vọt?": 5'
4. An tạm dừng công việc hiện tại, mở lại Ads Manager lục tìm adset/creative liên quan để tra soát lịch sử: 20'
5. An soạn đoạn giải trình chi tiết kèm ảnh chụp màn hình gửi lại cho client: 20'
6. Client đọc giải trình, trao đổi qua lại 2-3 tin nhắn để chốt phương án xử lý: 10'

Bottleneck:
Bước 4 & 5 — An bị ngắt quãng luồng làm việc tập trung (context switching) để mở lại Ads Manager, đối chiếu dữ liệu lịch sử và tự tay gõ đoạn văn giải trình cho từng câu hỏi phát sinh.

Impact:
- Cá nhân: Tiêu tốn 45–60 phút/tuần cho các tin nhắn giải trình không báo trước, làm gián đoạn các công việc tối ưu campaign chính.
- Khách hàng: Dashboard mất đi tính tự phục vụ (self-serve); client nhìn thấy số liệu tụt nhưng hoang mang vì không có lời giải thích ngay lập tức.

Success metric:
- Giảm 70% số lượng tin nhắn/cuộc gọi từ client hỏi về nguyên nhân biến động số liệu trên dashboard.
- Thời gian An dành để tra soát và trả lời giải trình phát sinh giảm từ 45 phút xuống dưới 10 phút/tuần.
- Duy trì điểm đánh giá mức độ rõ ràng của báo cáo (Report Clarity Score) từ client đạt tối thiểu 4.5/5.

Non-AI alternative:
Chèn thêm một khối text box/Google Sheet tĩnh bên dưới mỗi biểu đồ Looker Studio và yêu cầu Media Buyer tự gõ tay dòng ghi chú phân tích mỗi tuần. Cách này vẫn tốn công sức thao tác thủ công và dễ bị bỏ quên.

AI hypothesis:
Nếu kết nối dữ liệu biến động từ bảng tính với LLM thông qua API webhook, hệ thống có thể tự động sinh ra một đoạn tóm tắt ngắn (Executive Summary & Root Causes) và nhúng thẳng vào khung ghi chú đầu trang Looker Studio. Client mở dashboard là thấy ngay phân tích mà không cần hỏi thêm.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[X] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 75 phút

[1 Cập nhật số liệu Looker Studio: 10']
→ [2 Client xem dashboard nhưng không hiểu nguyên nhân tụt số: 10']
→ [3 Client nhắn hỏi An trên Zalo/Slack: 5']
→ [4 An mở Ads Manager lục tìm adset/creative tra soát lịch sử: 20']   <-- bottleneck
→ [5 An gõ đoạn giải trình định tính gửi lại client: 20']
→ [6 Client đọc và chốt phương án: 10']

FUTURE STATE — 20 phút

[1 Webhook trigger đẩy bảng chênh lệch chỉ số vào LLM: 1']
→ [2 LLM phân tích root-cause và draft sẵn Executive Summary vào Looker Studio: 2']
→ [3 An kiểm tra nhanh 3 gạch đầu dòng insight trên dashboard: 7']   <-- human boundary
→ [4 Client mở dashboard đọc trực tiếp phân tích, không cần hỏi thêm: 10']

Fallback: nếu AI sai thì ...
Nếu LLM suy diễn sai nguyên nhân bên ngoài (ví dụ: gán nhầm do bão hòa tệp trong khi thực tế do lỗi cổng thanh toán) hoặc dữ liệu thiếu logic, An bấm nút "Tắt hiển thị AI Note" trên dashboard, hệ thống trả về khung ghi chú trống và An tự gõ 2 dòng nhận xét thủ công trong 5 phút.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Viết 3–5 gạch đầu dòng nhận xét và giải thích nguyên nhân biến động CPA cho 4 nhãn hàng

```text
Problem 1 câu:
Media Buyer tại Agency mất 90–120 phút mỗi sáng thứ Hai để tự phân tích và viết narrative giải thích nguyên nhân biến động hiệu quả (CPA, CTR) cho 4 nhãn hàng, dễ bị "blank page" dẫn đến trễ hạn nộp báo cáo và nội dung nhận xét mang tính đối phó.

Actor:
An (Media Buyer) và Brand Marketing Manager của 4 nhãn hàng (stakeholders nhận báo cáo).

Thời điểm / bối cảnh:
09:30 – 11:30 sáng thứ Hai hàng tuần, ngay sau khi hoàn thành bước đồng bộ số liệu thô từ các nền tảng quảng cáo (Meta, Google, TikTok Ads).

Current workflow 3-7 bước:
1. Mở file Google Sheets tổng hợp số liệu tuần: 5'
2. Đối chiếu số liệu từng nhãn hàng với KPI cam kết và tuần trước: 15'
3. Soi từng adset/creative để tìm nguyên nhân CPA biến động: 25'
4. Viết narrative (3–5 gạch đầu dòng nhận xét + đề xuất tối ưu): 60'
5. Copy nhận xét và biểu đồ vào slide/email báo cáo: 15'
6. Rà soát lỗi chính tả và format theo văn phong agency: 20'
7. Bấm gửi báo cáo cho 4 nhãn hàng: 5'

Bottleneck:
Bước 4 — Viết narrative từ dữ liệu số mất khoảng 60 phút (15 phút/nhãn hàng) và thường xuyên bị "blank page syndrome" khi phải chuyển đổi các chỉ số kỹ thuật khô khan (CTR, CPC, CPA) thành insight kinh doanh có giá trị hành động cho khách hàng.

Impact:
- Cá nhân: Mất 145 phút vào khung giờ áp lực nhất đầu tuần; 2 lần trong tháng qua bị trễ deadline 11:30 do tắc ở khâu viết.
- Khách hàng: Khi báo cáo gửi trễ hoặc nhận xét sơ sài, Brand Manager thiếu bối cảnh để giải trình trong cuộc họp nội bộ đầu tuần của họ, dẫn đến việc họ liên tục nhắn tin/gọi điện hỏi lại ngoài giờ.

Success metric:
- Rút ngắn tổng thời gian hoàn thiện báo cáo từ 145 phút xuống dưới 45 phút.
- 100% báo cáo tuần được gửi đúng hạn trước 11:30 sáng thứ Hai.
- Giảm trên 70% số câu hỏi phát sinh từ Brand Manager yêu cầu giải thích "tại sao số liệu tuần này tụt".

Non-AI alternative:
Xây dựng khung template báo cáo cố định + danh sách mẫu câu (canned responses) dạng IF-ELSE theo ngưỡng số liệu: giảm được thời gian format ở bước 5 và 6, nhưng nhận xét rất máy móc, không liên kết được nhiều chỉ số cùng lúc (ví dụ: CPA tăng do CTR giảm hay do CPM thị trường tăng).

AI hypothesis:
Nếu cấp dữ liệu biến động tuần (chi tiêu, CTR, CPA theo adset) vào prompt có sẵn quy tắc nghiệp vụ và văn phong agency, LLM có thể draft sẵn 80% phần narrative (Highlight, Nguyên nhân cốt lõi, Đề xuất phân bổ ngân sách). An chỉ cần review/edit trong 3–5 phút cho mỗi nhãn hàng.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[X] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 145 phút

[1 Mở Google Sheets tổng hợp số liệu tuần: 5']
→ [2 Đối chiếu số liệu với KPI cam kết và tuần trước: 15']
→ [3 Soi từng adset/creative để tìm nguyên nhân CPA biến động: 25']
→ [4 Viết narrative (3–5 gạch đầu dòng nhận xét + đề xuất tối ưu): 60']   <-- bottleneck
→ [5 Copy nhận xét và biểu đồ vào slide/email báo cáo: 15']
→ [6 Rà soát lỗi chính tả và format theo văn phong agency: 20']
→ [7 Bấm gửi email báo cáo cho 4 nhãn hàng: 5']

FUTURE STATE — 30 phút

[1 Trigger đẩy bảng chênh lệch metrics từ Google Sheets sang LLM: 1']
→ [2 LLM phân tích adset và draft sẵn 3-5 gạch narrative theo template agency: 2']
→ [3 Tự động điền bản nháp vào slide/email báo cáo của từng nhãn hàng: 2']
→ [4 An review, tinh chỉnh câu chữ và chốt đề xuất ngân sách: 20']   <-- human boundary
→ [5 An bấm phê duyệt gửi báo cáo hàng loạt cho 4 nhãn hàng: 5']

Fallback: nếu AI sai thì ...
Nếu LLM tạo narrative sáo rỗng, đưa số liệu sai lệch hoặc đề xuất phân bổ ngân sách vô lý, An chuyển chế độ sang "Template Mode", hệ thống khôi phục mẫu câu điền chỗ trống mặc định (canned responses) và An tự tay gõ lại 3 ý chính trong 15 phút.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Xuất CSV số liệu tuần từ Meta, Google, TikTok Ads ghép vào Sheet

```text
Problem 1 câu:
Media Buyer mất 60 phút mỗi sáng thứ Hai để thực hiện các thao tác tay chân lặp lại gồm đăng nhập 3 tài khoản quảng cáo, xuất file CSV và copy-paste vào một Google Sheets tổng, dễ gây nhầm lẫn số liệu và chậm trễ tiến độ làm báo cáo.

Actor:
An (Media Buyer) và Account Manager (người cần số liệu tổng hợp để kiểm tra tiến độ chiến dịch).

Thời điểm / bối cảnh:
08:30 – 09:30 sáng thứ Hai hàng tuần, là công đoạn mở đầu bắt buộc trước khi có thể bắt tay vào viết báo cáo tuần.

Current workflow 3-7 bước:
1. Đăng nhập Meta Ads Manager, chọn dải ngày tuần trước, kiểm tra múi giờ và tải file CSV: 15'
2. Đăng nhập Google Ads, lọc danh sách chiến dịch đang chạy và xuất file báo cáo: 10'
3. Đăng nhập TikTok Ads Manager, xuất số liệu chuyển đổi tuần: 10'
4. Mở Google Sheets master, copy-paste dữ liệu từng nền tảng vào đúng cột/tab quy định: 15'
5. Kéo công thức tính chênh lệch tuần, kiểm tra thủ công xem có bị lệch hàng/cột không: 10'

Bottleneck:
Bước 4 — Copy-paste dữ liệu thủ công từ nhiều file định dạng khác nhau (tên cột Meta, Google, TikTok không đồng nhất) vào một bảng chung rất nhàm chán, tốn thời gian và rủi ro lệch dòng rất cao.

Impact:
- Cá nhân: Tiêu tốn 60 phút đầu tuần vào các thao tác chuột lặp đi lặp lại có giá trị gia tăng thấp.
- Dây chuyền: Nếu copy nhầm cột (như nhầm chi phí trước VAT và sau VAT), toàn bộ báo cáo phân tích và tính toán ROAS phía sau sẽ bị sai lệch hoàn toàn, buộc phải rà soát lại từ đầu.

Success metric:
- Giảm thời gian tổng hợp số liệu từ 60 phút xuống 0 phút (dữ liệu được tự động đồng bộ sẵn trước 08:30 sáng thứ Hai).
- Tỷ lệ lỗi lệch số, lệch dòng dữ liệu do thao tác con người giảm về 0%.

Non-AI alternative:
Sử dụng các công cụ kết nối dữ liệu (ETL connector) chuyên dụng như Supermetrics, Coupler.io hoặc viết script Google Apps Script / Python chạy định kỳ để tự động kéo API từ 3 nền tảng quảng cáo về Google Sheets.

AI hypothesis:
Có thể dùng mô hình AI đa phương thức đọc ảnh chụp màn hình dashboard hoặc prompt LLM để chuẩn hóa mapping tên cột. Tuy nhiên, cách này cồng kềnh, chi phí cao và độ ổn định kém hơn nhiều so với việc dùng mã lập trình hay công cụ tích hợp tự động hóa thuần túy.

Quick gut:
[ ] No AI / process fix
[X] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 60 phút

[1 Đăng nhập Meta Ads Manager, lọc ngày và xuất CSV: 15']
→ [2 Đăng nhập Google Ads và xuất file báo cáo chiến dịch: 10']
→ [3 Đăng nhập TikTok Ads Manager và xuất dữ liệu hiệu suất: 10']
→ [4 Copy-paste thủ công dữ liệu từng kênh vào đúng cột Google Sheets: 15']   <-- bottleneck
→ [5 Kéo công thức tính chênh lệch tuần và check lệch dòng: 10']

FUTURE STATE — 5 phút

[1 Cron-job/ETL connector tự kéo dữ liệu API 3 nền tảng về Google Sheets lúc 07:00: 0']
→ [2 Rule-based script chuẩn hóa tên cột và tự động tính toán chênh lệch tuần: 0']
→ [3 An mở Google Sheets kiểm tra chéo tổng chi phí và dòng dữ liệu cuối: 5']   <-- human boundary

Fallback: nếu AI sai thì ...
(Vì đây là Rule/ETL script thuần túy) Nếu API bị lỗi token/hết hạn hoặc nền tảng đổi format cột khiến script gãy, hệ thống bắn cảnh báo qua Telegram kèm link báo cáo lỗi; An quay về phương án tải CSV thủ công trong 30 phút cho ca sáng thứ Hai đó.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Card #1 — Tự động diễn giải insight và nguyên nhân biến động hiệu quả trên Looker Studio Dashboard

```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Bài toán này can thiệp trực tiếp vào workflow hậu báo cáo, nơi Media Buyer phải liên tục ngắt quãng công việc trong tuần để tra soát Ads Manager và trả lời tin nhắn giải trình lặt vặt của client. 
Về số đo, giải pháp giúp giảm trực tiếp thời gian giải trình từ 45-60 phút xuống dưới 10 phút/tuần và cắt giảm 70% số lượng tin nhắn hỏi "tại sao số tụt". 
Impact lớn nhất là biến Looker Studio từ một bảng số liệu thô thành công cụ tự phục vụ (self-serve) có giá trị hành động, vừa giải phóng thời gian cho Media Buyer vừa tăng mức độ hài lòng và tính chủ động cho Brand Manager.

```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Khi chỉ dựa vào dữ liệu chỉ số nội bộ (CPA, CTR, CPM) trên bảng tính, làm sao AI biết được nguyên nhân thực sự đến từ yếu tố bên ngoài (như thị trường đổi mùa, đối thủ phá giá, lỗi cổng thanh toán web) để không tạo ra các nhận định suy diễn ngô nghê trước mặt client?
2. Việc nhúng thẳng nhận xét tự động của AI lên dashboard khách hàng có tạo ra rủi ro vạ miệng (hallucination) hay làm lộ các lỗi kỹ thuật vận hành nội bộ của agency không?

```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: AI dễ bị "ảo giác" (hallucination) hoặc suy diễn phiến diện khi cố giải thích nguyên nhân gốc rễ (root cause) chỉ bằng các con số thô. Nếu dashboard tự động hiển thị nhận định sai cho Brand Manager xem trước khi có người duyệt, uy tín chuyên môn của Agency sẽ bị ảnh hưởng nghiêm trọng.
- Tôi sửa gì: Đưa bước Human-in-the-loop vào làm chốt chặn bắt buộc trước khi insight xuất hiện công khai: LLM chỉ draft bản phân tích vào một bảng kiểm duyệt nội bộ; Media Buyer có 5–7 phút sáng thứ Hai để tick chọn "Phê duyệt" hoặc sửa nhanh 1–2 ý thì đoạn text mới được đồng bộ hiển thị lên Looker Studio của khách hàng.

### Self-check nộp phần 01
- [X] Có 5+ problems + top 3 Cards đủ field
- [X] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [X] Đã chọn 1 card pitch + câu hỏi challenge
