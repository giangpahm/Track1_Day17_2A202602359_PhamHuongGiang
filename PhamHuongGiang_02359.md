# Chặng 1 — Đặt giả thuyết (Bài làm cá nhân)

## Thông tin

- Họ và tên: **Phạm Hương Giang**
- MHV: **2A202602359**
- Case đã chọn: **Case B — AI Notes: Personal Learning Notes**

> Toàn bộ nội dung dưới đây là giả thuyết cá nhân trước khi phỏng vấn, chưa phải fact về người dùng và chưa được validation.

---

## 1. Solution — Gỡ solution khỏi hình thức cụ thể

### Solution directive

> “Trong khi học, học viên có thể highlight một đoạn nội dung, đánh dấu ‘Chưa hiểu’, hoặc viết một câu hỏi hay ghi chú ngắn. Khi bài học kết thúc, AI Notes kết hợp những dấu vết này với nội dung bài để tạo một bản ghi chú có cấu trúc. Học viên có thể chỉnh sửa và xác nhận trước khi lưu.”

### Các yếu tố thuộc giao diện, công nghệ và cách triển khai

- Tên feature/công nghệ: **AI Notes** và thao tác chọn lọc, nhóm, tổ chức thông tin bằng AI.
- Thao tác giao diện: highlight, gắn nhãn “Chưa hiểu”, nhập câu hỏi hoặc ghi chú ngắn.
- Thời điểm xử lý được quy định sẵn: sau khi bài học kết thúc.
- Dạng output được quy định sẵn: một bản ghi chú có cấu trúc.
- Cơ chế kiểm soát: học viên chỉnh sửa và xác nhận trước khi lưu.

### Capability trung tính

Khả năng ghi nhận các ý quan trọng và thắc mắc cá nhân nảy sinh trong lúc học, giữ chúng gắn với bối cảnh bài học và chuyển chúng thành tài liệu có thể hiểu và sử dụng lại cho bước học tiếp theo.

Capability này không mặc định phải dùng AI, không bắt buộc triển khai bằng các nút hoặc màn hình đã mô tả trong directive.

---

## 2. Change — Làm lộ chuỗi thay đổi được kỳ vọng

### Chuỗi thay đổi

**Solution →** học viên ghi lại nhanh các ý chính và điểm chưa hiểu ngay trong luồng học **→** các dấu vết giữ được liên hệ với nội dung gốc **→** học viên rà soát và biến chúng thành tài liệu có thể dùng lại **→** học viên sử dụng tài liệu để ôn tập hoặc xử lý chỗ chưa hiểu **→ Outcome:** giảm công sức tìm/xem lại toàn bộ bài và hạn chế bỏ sót lỗ hổng kiến thức.

### Các thay đổi được kỳ vọng

1. Học viên chuyển từ việc dừng bài để ghi chép dài hoặc lưu thông tin rời rạc sang ghi lại tín hiệu ngắn ngay khi chúng xuất hiện.
2. Sau bài học, học viên rà soát và hoàn thiện các dấu vết thay vì để chúng nằm ở dạng nháp hoặc ảnh chụp phân tán.
3. Khi cần ôn tập hoặc áp dụng kiến thức, học viên tìm, hiểu và sử dụng lại tài liệu đã lưu thay vì xem lại toàn bộ bài học.

### Baseline đang được giả định — cần kiểm chứng

- Học viên có thể đang dùng sổ tay, Notion, Google Docs hoặc ứng dụng ghi chú song song với video/slide.
- Học viên có thể phải dừng bài để ghi chép hoặc chụp màn hình rồi lưu vào tài liệu nháp.
- Một số điểm chưa hiểu có thể được ghi nhanh hoặc bỏ qua với ý định quay lại sau.

Các mô tả trên chưa phải hành vi đã được chứng minh; interview cần kiểm tra xem chúng có thực sự xảy ra hay không.

### Phân biệt output và outcome

- **Output team có thể tạo:** một tài liệu tập hợp và sắp xếp các dấu vết học tập.
- **Outcome team chỉ có thể ảnh hưởng:** học viên ôn tập nhanh hơn, xử lý được điểm chưa hiểu hoặc áp dụng kiến thức hiệu quả hơn.
- Nếu học viên không rà soát và dùng lại tài liệu, output vẫn tồn tại nhưng outcome có thể không xảy ra.

---

## 3. Actor — Xác định các nhóm người liên quan

| Actor | Họ đang làm gì? | Pain hoặc hậu quả có thể có | Họ hưởng lợi thế nào? |
|---|---|---|---|
| Học viên học khóa online có nội dung lý thuyết/kỹ thuật phức tạp | Theo dõi bài, ghi lại ý chính và điểm chưa hiểu để ôn tập hoặc áp dụng | Bị ngắt mạch học; ghi chú thiếu ngữ cảnh; mất công tổng hợp; bỏ quên thắc mắc | Có tài liệu cá nhân dễ hiểu và dùng lại |
| Giảng viên/người thiết kế khóa học | Trình bày và tổ chức nội dung học | Không biết học viên vướng ở đâu; phải giải thích lại những điểm bị bỏ sót | Có thêm cơ sở để cải thiện nội dung hoặc hỗ trợ học viên nếu dữ liệu được chia sẻ phù hợp |
| Coach/người hỗ trợ học tập | Giải đáp và giúp học viên tiếp tục tiến trình | Thiếu ngữ cảnh về phần học viên đã học và chưa hiểu | Có thể hỗ trợ đúng điểm vướng hơn |

### Actor chọn điều tra trước

Học viên theo học khóa trực tuyến self-paced hoặc blended có nội dung lý thuyết/kỹ thuật phức tạp, đã ghi chú, highlight hoặc lưu nội dung học tập để xem lại trong 7 ngày gần đây.

### Lý do chọn

- Đây là người trực tiếp thực hiện hành vi được solution giả định.
- Họ trực tiếp trải nghiệm việc ghi, tìm, hiểu và dùng lại nội dung.
- Họ chịu hậu quả nếu điểm chưa hiểu bị bỏ quên hoặc ghi chú không thể sử dụng lại.
- Tiêu chí này cho phép interviewee nhớ đủ chi tiết về một sự kiện gần đây.

### Người không ưu tiên trong vòng điều tra này

- Người chỉ nghe bài thụ động trong lúc làm việc khác.
- Người xem nội dung giải trí hoặc video thực hành rất ngắn và không có nhu cầu ghi chép.

Việc không ưu tiên các nhóm này là quyết định lấy mẫu cho vòng phỏng vấn, không phải kết luận rằng họ không bao giờ có pain.

---

## 4. Situation & Job — User đang cố làm gì?

### Chuỗi Situation & Job

**Tình huống bắt đầu:** học viên đang theo dõi một bài giảng online dài, có nhiều nội dung mới, thuật ngữ mới hoặc cấu trúc phức tạp và bắt gặp một ý quan trọng hay điểm chưa hiểu.

**→ User muốn:** giữ lại ý đó cùng đủ ngữ cảnh để có thể ôn tập, tra cứu hoặc xử lý sau mà vẫn theo kịp mạch bài.

**→ Cách hiện tại được giả định:** dừng video để viết vào sổ/ứng dụng ghi chú, chụp màn hình, bookmark hoặc ghi một dòng nhắc ngắn.

**→ Điểm có thể bắt đầu vướng:** việc ghi chi tiết làm gián đoạn mạch học; ghi quá ngắn lại thiếu ngữ cảnh; sau bài học phải tốn công tìm và sắp xếp lại.

### Mô tả Situation & Job

Khi đang theo dõi một bài giảng trực tuyến có nhiều nội dung mới và phức tạp, học viên đang cố lưu lại các ý chính và điểm chưa hiểu cùng ngữ cảnh bằng sổ tay, ứng dụng ghi chú, ảnh chụp hoặc bookmark để có thể tiếp tục theo dõi bài và dùng lại thông tin sau đó.

### JTBD Hypothesis

Khi tôi đang tự học một bài giảng online có nhiều nội dung mới và phức tạp, tôi muốn ghi lại nhanh các điểm mấu chốt và khúc mắc cá nhân cùng ngữ cảnh, để có thể ôn tập hoặc xử lý phần chưa hiểu mà không phải mất nhiều thời gian xem lại toàn bộ bài học.

---

## 5. Pain — Các cách giải thích cạnh tranh

### Pain Hypothesis A — Synthesis Friction

Khi kết thúc một bài học online phức tạp và cần chuẩn bị tài liệu để xem lại, học viên gặp khó khăn trong việc biến các ghi chú, highlight và ảnh chụp rời rạc thành một mạch nội dung dễ dùng vì phải tự lọc, bổ sung ngữ cảnh và sắp xếp lại, dẫn đến tốn thời gian, để ghi chú ở dạng nháp hoặc không dùng lại chúng.

### Pain Hypothesis B — Context Severance

Khi mở lại ghi chú hoặc ảnh chụp sau buổi học, học viên gặp khó khăn trong việc hiểu chính xác dấu vết đó liên quan tới phần nào của bài vì nó bị tách khỏi slide và mạch giải thích ban đầu, dẫn đến phải tìm/xem lại nội dung gốc hoặc bỏ qua ghi chú.

### Pain Hypothesis C — Forgotten Blockers

Khi gặp một điểm chưa hiểu nhưng vẫn muốn theo kịp bài giảng, học viên gặp khó khăn trong việc giữ và quay lại xử lý thắc mắc vì thông tin tiếp theo liên tục xuất hiện, dẫn đến điểm vướng bị quên và lỗ hổng kiến thức không được giải quyết.

### Giả thuyết chọn điều tra trước

**Pain Hypothesis A — Synthesis Friction.**

### Lý do chọn

- Đây là giả định liên hệ trực tiếp nhất với hành động “chọn lọc, nhóm và tổ chức thông tin” trong solution directive.
- Solution chỉ tạo giá trị đáng kể nếu việc tổng hợp hiện tại thực sự tốn công và khiến học viên bỏ cuộc hoặc không dùng lại ghi chú.
- Giả thuyết này dễ bị bác bỏ: nếu học viên vốn đã tổ chức và dùng lại ghi chú thuận lợi, hoặc không hề có nhu cầu tổng hợp, hướng giải quyết được đề xuất mất cơ sở.
- Pain B và C được giữ lại như các cách giải thích cạnh tranh, tránh mặc định rằng mọi hành vi lưu thông tin đều xuất phát từ khó khăn tổng hợp.

---

## 6. Evidence — Điều cần tìm trước khi viết câu hỏi

| Cần kiểm tra | Evidence làm tôi tin hơn | Evidence làm tôi nghi ngờ hoặc bác bỏ |
|---|---|---|
| Situation có thật | Interviewee kể được một lần trong 7 ngày gần đây: đang học nội dung gì, mục tiêu gì, khi nào quyết định ghi/lưu | Không nhớ được sự kiện cụ thể; chỉ nói về thói quen chung hoặc tình huống giả định |
| Pain có ý nghĩa | Việc tổng hợp/tìm lại làm gián đoạn mục tiêu học, mất công đáng kể hoặc khiến họ trì hoãn/bỏ cuộc | Họ sắp xếp và sử dụng lại dễ dàng; bất tiện nhỏ, không ảnh hưởng mục tiêu |
| Workaround tồn tại | Đã dùng sổ, Notion, Google Docs, ảnh chụp, bookmark, tự chép lại hoặc xem lại bài | Không từng tìm cách xử lý vì không có nhu cầu hoặc vấn đề không quan trọng |
| Consequence tồn tại | Mất thời gian xem lại; không ôn được; bỏ quên thắc mắc; học lại; không áp dụng được kiến thức | Không tổng hợp/xem lại nhưng cũng không có hậu quả quan sát được |
| Pattern có lặp | Có nhiều lần gần đây với cùng barrier, workaround hoặc hậu quả | Chỉ là một trường hợp cá biệt do bài học hoặc công cụ bất thường |

### Evidence hành vi cụ thể cần tìm

- Công cụ người học thực sự đã dùng trong lần gần nhất.
- Bản ghi chú, highlight, bookmark hoặc ảnh chụp thật nếu interviewee tự nguyện cho xem.
- Trình tự từ lúc nhận ra nội dung cần lưu đến lúc dùng lại hoặc từ bỏ.
- Việc họ thực sự làm với ghi chú sau khi kết thúc bài.
- Số lần mở lại và mục đích của mỗi lần, nếu người dùng nhớ được.
- Thời gian/công sức họ thực sự bỏ ra; không ép họ ước lượng nếu không nhớ.
- Ghi chú hoặc thắc mắc đã không được xử lý và hậu quả thực tế của việc đó.

### Evidence có thể làm giả thuyết được chọn sai

- Học viên ghi chú chủ yếu để tập trung hoặc ghi nhớ ngay trong lúc học, không có ý định tạo tài liệu để xem lại.
- Họ không hệ thống hóa vì nội dung đã hoàn thành vai trò và không còn cần thiết, chứ không phải vì quá tốn công.
- Họ có quy trình hiện tại đơn giản, nhanh và đủ tốt để tổ chức ghi chú.
- Pain chính là không hiểu kiến thức, thiếu thời gian/động lực hoặc không biết nên học gì tiếp theo.
- Không có consequence khi ghi chú bị bỏ lại.

---

## Chốt Problem Hypothesis và park solution

### Problem Hypothesis mang sang Chặng 2

Khi kết thúc một bài học online có nhiều nội dung mới hoặc phức tạp và cần chuẩn bị để ôn tập hay áp dụng kiến thức, học viên có thói quen ghi chú/highlight/lưu nội dung gặp khó khăn trong việc biến các dấu vết rời rạc thành một tài liệu dễ hiểu và dùng lại vì phải tự lọc, bổ sung ngữ cảnh và sắp xếp chúng, dẫn đến mất thời gian, để ghi chú ở dạng nháp hoặc bỏ qua việc xem lại.

### Điều phải đúng để giả thuyết đứng vững

1. Học viên thực sự có nhu cầu dùng lại thông tin đã lưu cho một mục tiêu học tập cụ thể.
2. Họ đang tạo ra nhiều dấu vết rời rạc hoặc thiếu ngữ cảnh.
3. Việc tổng hợp các dấu vết đòi hỏi công sức đáng kể.
4. Công sức này tạo ra workaround, trì hoãn, bỏ cuộc hoặc hậu quả quan sát được.
5. Tình huống có tính lặp lại, không chỉ là một sự cố cá biệt.

### Điều có thể khiến tôi sửa hoặc bác bỏ giả thuyết

1. Học viên không có nhu cầu dùng lại ghi chú sau buổi học.
2. Cách hiện tại đã giúp họ tổ chức và sử dụng lại nội dung dễ dàng.
3. Việc không tổng hợp không tạo hậu quả đáng kể.
4. Pain B hoặc Pain C giải thích hành vi tốt hơn Pain A.
5. Một barrier khác như thiếu động lực, thời gian hoặc kiến thức nền mới là nguyên nhân chính.

### Solution Parking Lot

| Hướng giải quyết có thể có | AI / Không sử dụng AI |
|---|---|
| Tự động nhóm các dấu vết theo chủ đề và tạo bản nháp ghi chú | AI |
| Khôi phục ngữ cảnh cho ghi chú bằng cách liên kết với đoạn video/slide nguồn | AI |
| Gợi ý danh sách các điểm chưa hiểu cần xử lý sau bài học | AI |
| Mẫu ghi chú thủ công gồm: ý chính – chưa hiểu – ngữ cảnh – bước tiếp theo | Không sử dụng AI |
| Trang tổng hợp highlight, bookmark và ghi chú theo bài/chủ đề | Không sử dụng AI |
| Nhắc lịch xem lại các điểm chưa được xử lý | Không sử dụng AI |

---

## CHECKPOINT 1 — Problem Hypothesis

- [x] Có chuỗi **Solution → Change → Actor → Situation & Job → Pain → Evidence**.
- [x] Capability được mô tả mà không phụ thuộc vào AI hoặc giao diện cụ thể.
- [x] Baseline và target behavior được trình bày như giả thuyết, không phải fact.
- [x] Actor và situation đủ cụ thể để tuyển người phù hợp.
- [x] Job vẫn tồn tại khi bỏ solution khỏi bối cảnh.
- [x] Có ba cách giải thích cạnh tranh về pain.
- [x] Đã chọn Pain Hypothesis A để điều tra trước và nêu lý do.
- [x] Đã nêu evidence làm giả thuyết mạnh hơn và yếu đi.
- [x] Đã nói rõ điều có thể khiến giả thuyết bị sửa hoặc bác bỏ.
- [x] Solution Parking Lot có ít nhất năm hướng và có hướng không sử dụng AI.

**Kết luận checkpoint:** Bài làm cá nhân đã hình thành một Problem Hypothesis cụ thể và có thể bị bác bỏ. Chưa có nội dung nào được coi là evidence hoặc kết luận validation trước khi thực hiện phỏng vấn.

