# Track 1 — Day 17: Problem Interview

> README cá nhân sử dụng kết quả chung của nhóm `3 in 1` cho Chặng 1–2 và dữ liệu lượt phỏng vấn của Phạm Hương Giang cho Chặng 3–4. Đây là buổi luyện tập, không phải một vòng validation.

## 1. Thông tin cá nhân và nhóm

- MHV: `2A202602359`
- Họ và tên: `Phạm Hương Giang`
- Tên nhóm: `3 in 1`
- Thành viên nhóm:
  - Lê Thanh Tình — `2A202602449`
  - Phạm Hương Giang — `2A202602359`
  - Chu Thùy Dương — `2A202602660`
- Case đã chọn: **Case B — AI Notes: Personal Learning Notes**

## 2. Problem Hypothesis Brief

> Đây là giả thuyết của nhóm, chưa phải fact về user và chưa được validation.

### 2.1. Solution và capability trung tính

**Solution directive**

Trong khi học, học viên có thể highlight một đoạn nội dung, đánh dấu “Chưa hiểu”, hoặc viết một câu hỏi hay ghi chú ngắn. Khi bài học kết thúc, AI Notes kết hợp những dấu vết này với nội dung bài để tạo một bản ghi chú có cấu trúc. Học viên có thể chỉnh sửa và xác nhận trước khi lưu.

**Capability trung tính**

Giúp học viên chuyển các dấu vết rời rạc được tạo trong lúc học thành tài liệu cá nhân dễ hiểu, dễ tìm lại và có thể dùng cho bước học tiếp theo.

### 2.2. Chuỗi thay đổi kỳ vọng

**Solution →** các dấu vết học tập rời rạc được tập hợp và tổ chức **→** học viên xem lại, chỉnh sửa và lưu một tài liệu có ý nghĩa với mình **→** học viên tìm và sử dụng lại thông tin cần thiết khi ôn tập hoặc tiếp tục học **→ Outcome:** việc ôn lại/giải quyết chỗ chưa hiểu hiệu quả hơn.

Các thay đổi được kỳ vọng:

1. Học viên nhận ra những nội dung quan trọng và những điểm chưa hiểu sau một buổi học.
2. Học viên biến các dấu vết đã lưu thành tài liệu có thể dùng lại thay vì để chúng phân tán hoặc bị bỏ quên.
3. Khi có nhu cầu ôn tập hoặc tiếp tục nhiệm vụ học tập, học viên tìm lại và sử dụng tài liệu đó.

**Output nhóm có thể tạo:** một bản ghi chú được sắp xếp.  
**Outcome nhóm chỉ có thể ảnh hưởng:** học viên hiểu, nhớ, tìm lại hoặc áp dụng kiến thức hiệu quả hơn. Outcome này còn phụ thuộc vào việc học viên có kiểm tra và dùng lại ghi chú hay không.

### 2.3. Actor

| Actor | Họ đang làm gì? | Pain hoặc hậu quả có thể có | Họ hưởng lợi thế nào? |
|---|---|---|---|
| Học viên có ghi chú/highlight/lưu nội dung | Ghi lại nội dung đáng chú ý trong lúc học và dùng lại sau đó | Dấu vết phân tán, thiếu ngữ cảnh, khó tìm hoặc không được dùng lại | Có tài liệu cá nhân hữu ích cho việc học tiếp theo |
| Giảng viên/người thiết kế khóa học | Cung cấp nội dung và hỗ trợ quá trình học | Không biết học viên thường vướng ở đâu; phải giải thích lặp lại | Có thể hiểu hơn về điểm học viên gặp khó khăn nếu có cơ chế phù hợp và được phép |
| Người hỗ trợ/coach | Giúp học viên xử lý vướng mắc | Thiếu ngữ cảnh về điều học viên đã xem, đã hiểu hoặc chưa hiểu | Hỗ trợ đúng trọng tâm hơn |

**Actor nhóm chọn điều tra trước:** học viên đã ghi chú, highlight hoặc lưu nội dung học tập để xem lại trong 7 ngày gần đây.

**Lý do chọn:** đây là người trực tiếp thực hiện hành vi đầu vào, trải nghiệm quá trình dùng lại các dấu vết và chịu hậu quả nếu chúng không giúp hoàn thành mục tiêu học tập. Nhánh này cũng phù hợp với tiêu chí tuyển người của case.

### 2.4. Situation & Job

**Mô tả Situation & Job**

Khi học một nội dung và nhận ra thông tin quan trọng hoặc một điểm chưa hiểu, học viên đang cố giữ lại điều cần thiết để có thể tìm, hiểu và sử dụng nó trong bước học tiếp theo bằng cách ghi chú, highlight hoặc lưu nội dung bằng công cụ hiện có.

**JTBD Hypothesis**

Khi tôi gặp nội dung quan trọng hoặc chưa hiểu trong lúc học, tôi muốn lưu lại đúng ý cùng đủ ngữ cảnh để có thể nhanh chóng tiếp tục tìm hiểu, ôn tập hoặc áp dụng kiến thức khi cần.

### 2.5. Hai Pain Hypothesis cạnh tranh

**Pain Hypothesis A — tổ chức và tìm lại**

Khi cần dùng lại nội dung đã ghi dấu sau một buổi học, học viên gặp khó khăn trong việc tìm và hiểu lại điều mình đã lưu vì các highlight/ghi chú nằm rời rạc hoặc thiếu cấu trúc và ngữ cảnh, dẫn đến mất thời gian dựng lại mạch kiến thức hoặc bỏ qua việc xem lại.

**Pain Hypothesis B — biến dấu vết thành hiểu biết/hành động**

Khi gặp nội dung quan trọng hoặc chưa hiểu trong lúc học, học viên gặp khó khăn trong việc quyết định cần ghi gì và xử lý nó tiếp theo ra sao vì họ chưa hiểu đủ hoặc đang ưu tiên theo kịp bài, dẫn đến dấu vết được lưu nhưng không giúp họ giải quyết chỗ chưa hiểu hay hoàn thành mục tiêu học tập.

**Giả thuyết chọn điều tra trước:** A — `[NHÓM CẦN XÁC NHẬN HOẶC ĐỔI SANG B]`.

**Lý do chọn:** solution directive đặc biệt phụ thuộc vào giả định rằng vấn đề nằm ở việc chọn lọc, nhóm và tổ chức các dấu vết. Vì vậy, đây là giả định cần được kiểm tra sớm và có thể bị bác bỏ nếu người học vốn đã dễ dàng tìm, hiểu và dùng lại nội dung đã lưu.

### 2.6. Evidence Map

| Cần kiểm tra | Evidence làm nhóm tin hơn | Evidence làm nhóm nghi ngờ hoặc bác bỏ |
|---|---|---|
| Situation có thật | Interviewee kể được một lần gần đây, có trigger, bối cảnh và mục tiêu cụ thể | Không nhớ được trường hợp cụ thể; hành vi chỉ mang tính giả định hoặc đã xảy ra quá lâu |
| Pain có ý nghĩa | Việc tìm/hiểu lại bị gián đoạn, tốn công đáng kể hoặc cản một mục tiêu học thật | Tìm lại ngay, không thấy khó, hoặc khó khăn quá nhỏ để ảnh hưởng đến việc học |
| Workaround tồn tại | Đã tự phân loại, chép lại, chụp màn hình, tìm lại bài, hỏi người khác hoặc dùng nhiều công cụ | Không từng làm gì để xử lý vì không cần hoặc không đủ quan trọng |
| Consequence tồn tại | Mất thời gian, bỏ quên điểm chưa hiểu, ôn thiếu nội dung, phải học lại hoặc không hoàn thành việc cần làm | Không có hậu quả quan sát được; lưu hay không lưu không làm thay đổi bước tiếp theo |
| Pattern có lặp | Có các lần tương tự gần đây với cùng barrier/workaround | Chỉ là sự cố cá biệt hoặc phụ thuộc vào một nội dung bất thường |

### 2.7. Problem Hypothesis được mang sang Chặng 2

Khi cần dùng lại nội dung đã đánh dấu sau một buổi học, học viên có ghi chú/highlight/lưu nội dung gần đây gặp khó khăn trong việc tìm và hiểu lại điều mình đã lưu vì các dấu vết nằm rời rạc hoặc thiếu cấu trúc và ngữ cảnh, dẫn đến mất thời gian dựng lại mạch kiến thức hoặc bỏ qua việc xem lại.

**Điều phải đúng để giả thuyết đứng vững:**

- Học viên thực sự có nhu cầu dùng lại nội dung đã lưu cho một mục tiêu học cụ thể.
- Việc tổ chức hoặc khôi phục ngữ cảnh là một barrier đáng kể, không chỉ là bất tiện nhỏ.
- Barrier tạo ra công sức, workaround hoặc hậu quả quan sát được và có tính lặp lại.

**Điều có thể khiến nhóm sửa hoặc bác bỏ giả thuyết:**

- Học viên không có ý định xem lại; hành vi lưu chỉ giúp duy trì chú ý ngay trong lúc học.
- Học viên tìm và hiểu lại nội dung dễ dàng bằng cách hiện tại.
- Pain chính là không hiểu kiến thức, thiếu thời gian/động lực hoặc không biết bước tiếp theo, chứ không phải tổ chức ghi chú.
- Hậu quả không đáng kể và học viên chưa từng bỏ công tìm cách xử lý.

### 2.8. Solution Parking Lot

> Các hướng dưới đây chỉ được “park”; problem interview không dùng để giới thiệu hoặc đánh giá chúng.

| Hướng giải quyết có thể có | AI / Không sử dụng AI |
|---|---|
| Tự động nhóm các dấu vết theo chủ đề và gắn lại ngữ cảnh bài học | AI |
| Gợi ý danh sách điểm cần xem lại hoặc câu hỏi còn mở | AI |
| Cho phép tìm kiếm bằng ngôn ngữ tự nhiên trong nội dung đã lưu | AI |
| Mẫu ghi chú thủ công theo cấu trúc: ý chính – chưa hiểu – bước tiếp theo | Không sử dụng AI |
| Trang tổng hợp highlight/ghi chú theo bài, chủ đề và thời gian | Không sử dụng AI |
| Nhắc người học xem lại những điểm chưa được xử lý | Không sử dụng AI |

## 3. Conversation Guide — phiên bản cuối

> Trước buổi luyện, sao chép phần này vào ghi chú riêng nếu cần. Sau buổi luyện, phải sửa trực tiếp guide theo điều đã quan sát và ghi thay đổi tại mục 3.7.

### 3.1. Big 3

| Điều cần học | Evidence cần tìm | Điều gì khiến nhóm xem lại giả thuyết? |
|---|---|---|
| 1. Trong một lần học gần đây, điều gì kích hoạt việc lưu và học viên đã định dùng nội dung đó để làm gì? | Một câu chuyện cụ thể: bối cảnh, mục tiêu, trigger và bước tiếp theo dự kiến | Việc lưu không gắn với nhu cầu dùng lại hoặc mục tiêu học cụ thể |
| 2. Học viên thực sự đã làm gì khi cần dùng lại nội dung đã lưu? | Trình tự hành vi, công cụ, cách tìm, cách khôi phục ngữ cảnh, thời gian/công sức và workaround | Họ tìm, hiểu và dùng lại dễ dàng; không có workaround hay chi phí đáng kể |
| 3. **Câu hỏi “đáng sợ”: Có lần nào học viên đã lưu nhưng không xem lại, và vì sao?** | Một sự kiện thật cho thấy nội dung bị bỏ quên cùng nguyên nhân và hậu quả, hoặc cho thấy việc không xem lại hoàn toàn không gây vấn đề | Không xem lại vì không cần; không có hậu quả; pain thực sự nằm ở hiểu bài, động lực hoặc ưu tiên chứ không nằm ở tổ chức dấu vết |

### 3.2. Tiêu chí tuyển người

Chúng tôi cần nói chuyện với người đã **ghi chú, highlight hoặc lưu lại nội dung học tập để xem sau** trong vòng **7 ngày gần đây**.

**Recruitment check**

Trong 7 ngày vừa rồi, bạn có lần nào ghi chú, highlight hoặc lưu một nội dung đang học để có thể xem lại sau không? Bạn đã làm việc đó vào khoảng ngày nào?

> Câu trả lời chỉ dùng để xác nhận tuyển đúng người, không được tính là evidence chính.

### 3.3. Lời mở đầu và xin phép ghi âm

Cảm ơn bạn đã dành thời gian. Mình đang luyện cách tìm hiểu trải nghiệm học tập thực tế. Mình muốn nghe về những việc bạn đã làm trong một lần học gần đây; không có câu trả lời đúng hay sai và mình không kiểm tra kiến thức của bạn.

Mình muốn ghi âm cuộc trò chuyện để nghe lại, ghi chép chính xác và phục vụ bài học. Bản ghi không được chia sẻ công khai, chỉ được dùng để review bài với giảng viên/TA. Bạn có đồng ý cho mình ghi âm không?

> Chỉ bắt đầu ghi sau khi interviewee đồng ý rõ ràng. Nếu không đồng ý, không ghi âm và báo giảng viên để được hướng dẫn.

**Thực hiện trong lượt phỏng vấn của Phạm Hương Giang**

- Mã người tham gia: **P-02536**.
- Thời gian: **12:34, ngày 03/10/2026**.
- Hình thức/địa điểm: **phỏng vấn trực tiếp tại cầu thang tầng 2, tòa H, Trường Đại học VinUni**.
- Người phỏng vấn đã giải thích đây là cuộc phỏng vấn phục vụ project nhóm và nói rõ mục đích, phạm vi sử dụng bản ghi.
- Người tham gia đã đồng ý tham gia và cho ghi âm trước khi bắt đầu ghi.
- Bản ghi chỉ được dùng để nghe lại, bóc transcript và review bài với giảng viên/TA; không chia sẻ công khai.
- Nội dung và evidence của lượt phỏng vấn được ghi fact-first trong [`interview/notes.md`](interview/notes.md).

### 3.4. Story opener

Kể mình nghe về **lần gần nhất bạn ghi chú, highlight hoặc lưu một nội dung trong lúc học để xem lại sau**. Lúc đó bạn đang học gì và muốn hoàn thành việc gì?

### 3.5. Big 3 Questions

Các câu hỏi này là xương sống, không phải bảng hỏi bắt buộc đọc nguyên văn hoặc đúng thứ tự.

| Điều cần học | Câu hỏi sẽ dùng |
|---|---|
| 1. Trigger và job | Trong lần đó, điều gì khiến bạn quyết định lưu phần nội dung ấy? Sau đó bạn cần làm gì với nó? |
| 2. Hành vi dùng lại, barrier và workaround | Lần tiếp theo bạn cần nội dung đó, bạn đã làm gì từ lúc bắt đầu tìm cho đến khi tiếp tục được việc học? |
| 3. Trường hợp không xem lại và nguyên nhân thật | Kể mình nghe về lần gần nhất bạn đã lưu một nội dung học tập nhưng cuối cùng không dùng lại. Chuyện gì đã xảy ra? |

### 3.6. Probe bank

Chỉ dùng khi cần đào sâu điều interviewee vừa kể:

- “Lúc đó chuyện gì xảy ra tiếp theo?”
- “Bạn đã làm gì?”
- “Bạn có thể chỉ rõ từng bước bạn đã làm lúc đó không?”
- “Vì sao bạn chọn cách đó?”
- “Phần nào khó nhất?”
- “Bạn đã thử cách nào khác chưa?”
- “Việc đó mất khoảng bao lâu hoặc kéo theo hậu quả gì?”
- “Bạn đã dùng nội dung vừa tìm được như thế nào?”
- “Lần gần nhất trước đó là khi nào?”

Khi data lệch:

| User đưa ra | Phản xạ | Cách quay lại evidence |
|---|---|---|
| Lời khen | Deflect | “Cảm ơn bạn. Quay lại lần vừa kể, sau khi lưu thì bạn đã làm gì tiếp?” |
| Câu chung chung hoặc lời hứa tương lai | Anchor | “Lần gần nhất chuyện đó thực sự xảy ra là khi nào?” |
| Ý tưởng hoặc feature request | Dig | “Điều đó sẽ giúp bạn làm được việc gì? Lần gần nhất cần làm việc đó, bạn đã xử lý ra sao?” |

**Kết thúc**

Cảm ơn bạn. Trước khi kết thúc, trong câu chuyện vừa rồi có bước hoặc khó khăn nào quan trọng mà mình chưa hỏi tới không?

### 3.7. Revision Log sau buổi luyện

| Nội dung | Trước khi sửa | Sau khi sửa | Evidence từ buổi luyện và lý do sửa |
|---|---|---|---|
| Câu hỏi về gián đoạn | “Việc vừa học vừa ghi chép như vậy có làm bạn bị ngắt mạch nghe giảng không?” | “Kể mình nghe bạn đã làm gì từ lúc nhận ra nội dung cần ghi cho đến khi tiếp tục xem bài.” Sau đó hỏi: “Việc đó ảnh hưởng thế nào đến quá trình theo dõi bài, nếu có?” | Câu cũ nêu pain trước và mời user xác nhận. |
| Hành động sau bài học | “Có sắp xếp lại không hay để nguyên?” | “Sau khi tắt bài học, bạn đã làm gì tiếp theo với phần vừa ghi?” | Câu cũ đưa sẵn hai lựa chọn và giới hạn câu chuyện. |
| Tìm lại ghi chú | “Đã khi nào bạn note rất kỹ nhưng lúc cần thì tìm không ra hoặc đọc không hiểu chưa?” | “Kể mình nghe về lần gần nhất bạn cần dùng lại một ghi chú đã lưu.” Sau đó đào từng bước tìm, kết quả và hậu quả. | Câu cũ chứa sẵn khó khăn và giả định consequence tồn tại. |
| Workaround bằng công cụ khác | Chưa có probe riêng | “Lần gần nhất bạn dùng Google hoặc ChatGPT thay vì mở ghi chú là khi nào? Vì sao bạn chọn cách đó và kết quả ra sao?” | Người tham gia nói dùng Google/ChatGPT vì nhanh hơn việc mò lại file nháp. |
| Nguyên nhân không tổng hợp | Chỉ hỏi có sắp xếp lại hay không | Thêm probe: “Điều gì khiến bạn không quay lại xử lý ghi chú sau bài học?” | Người tham gia nói đóng máy vì mệt; cần phân biệt friction của việc tổng hợp với thiếu năng lượng hoặc không còn nhu cầu. |

## 4. Practice Reflection

> Phần này phải do người phỏng vấn tự hoàn thành sau khi nghe lại bản ghi. Viết một tình huống cụ thể cho mỗi câu, không dùng nhận xét chung chung.

1. **Câu hỏi nào đã giúp user kể một tình huống cụ thể?**  
   Câu hỏi “Tắt bài học xong, bạn làm gì tiếp theo với phần ghi chép/ảnh chụp đó?” giúp người tham gia kể hành động cụ thể: sau khi học Bài 14 trên VLearn, bạn ấy mệt, đóng máy đi ngủ và để nguyên file Docs. Tuy nhiên, phần hỏi thêm “có sắp xếp lại không hay để nguyên?” vẫn đưa sẵn lựa chọn, nên phiên bản sau luyện đã bỏ phần này.

2. **Chỗ nào mình cần làm tốt hơn ở lần phỏng vấn thật?**  
   Tôi cần tránh đặt pain vào câu hỏi. Câu “Việc vừa học vừa ghi chép như vậy có làm bạn bị ngắt mạch nghe giảng không?” dẫn người tham gia xác nhận giả thuyết. Câu hỏi về việc từng note kỹ nhưng tìm không ra cũng gợi sẵn khó khăn và hậu quả. Lần sau tôi sẽ yêu cầu user kể từng bước trước, sau đó mới hỏi ảnh hưởng “nếu có”. Tôi cũng cần đào sâu các tín hiệu “mệt quá”, “cho nhanh” và “mò lại từ đầu” thay vì chuyển câu hỏi ngay.

3. **Sau khi luyện, nhóm đã sửa Conversation Guide ở đâu và vì sao?**  
   Guide được sửa theo hướng thay câu hỏi yes/no và câu hỏi chứa sẵn pain bằng lời mời kể lại một sự kiện cùng trình tự hành vi; tách hành vi khỏi consequence; thêm probe cho Google/ChatGPT như một workaround cạnh tranh; và thêm probe để phân biệt không tổng hợp vì công việc tốn công với không tổng hợp vì mệt hoặc không còn nhu cầu. Các thay đổi giúp evidence ít bị dẫn dắt hơn và cho phép giả thuyết yếu đi.

## 5. AI Support Log

### AI đã hỗ trợ

- Sau phần suy luận cá nhân theo yêu cầu của bài, AI hỗ trợ tạo khung repo và sắp xếp nội dung theo bốn chặng.
- AI gợi ý bản nháp cho capability trung tính, chuỗi thay đổi, actor, JTBD, hai Pain Hypothesis cạnh tranh, Evidence Map và Solution Parking Lot của Case B.
- AI hỗ trợ diễn đạt Conversation Guide theo nguyên tắc The Mom Test, rà soát câu hỏi để tập trung vào hành vi quá khứ và tránh làm lộ solution.
- AI hỗ trợ cấu trúc Interview Record từ nội dung phỏng vấn do Phạm Hương Giang cung cấp, giữ nguyên exact quotes và tách facts khỏi diễn giải.
- AI chỉ ra các câu hỏi có tính dẫn dắt và gợi ý Revision Log. Phạm Hương Giang cần tự đối chiếu Practice Reflection với bản ghi trước khi nộp.

### Điểm cần tự kiểm tra và chỉnh sửa

- Bản nháp của AI có thể đang ưu tiên Pain Hypothesis A do suy luận từ solution directive, không phải do evidence từ user. Nhóm phải so sánh với nhánh suy luận ban đầu và tự chọn giả thuyết.
- Các câu hỏi có thể cần rút gọn hoặc đổi từ ngữ để phù hợp với cách nói tự nhiên của interviewer.
- AI không tham gia cuộc phỏng vấn, không tạo dữ liệu, không bịa quote và không kết luận hypothesis đã được validation.

### Người học đã tự sửa

- Giữ Problem Hypothesis về rào cản tổng hợp–tái sử dụng nhưng bổ sung các cách giải thích cạnh tranh: mất ngữ cảnh, bỏ quên điểm chưa hiểu, thiếu năng lượng và ưu tiên tìm Google/ChatGPT.
- Sửa các câu hỏi dẫn dắt thành câu hỏi kể chuyện và trình tự hành vi dựa trên chính lượt phỏng vấn của Phạm Hương Giang.
- Giữ nguyên exact quotes của người tham gia trong `interview/notes.md`; phần suy luận được tách riêng và dùng ngôn ngữ “tôi suy đoán”.
- Không coi một lượt luyện là validation cho giả thuyết.

## Checklist trước khi nộp

- [ ] Repo có tên `Track1_Day17_2A202602359_PhamHuongGiang`.
- [x] Đã điền tên nhóm và đủ ba thành viên.
- [ ] Nhóm đã xác nhận/chỉnh Problem Hypothesis Brief thay vì giữ nguyên bản AI một cách máy móc.
- [x] Interviewee là người ngoài nhóm và đáp ứng tiêu chí 7 ngày.
- [x] Interviewee đã đồng ý trước khi bắt đầu ghi âm.
- [x] `interview/notes.md` chỉ chứa notes từ lượt Phạm Hương Giang làm interviewer.
- [x] Đã thêm bản ghi thật `interview/recording.m4a`; file mở được dưới dạng M4A, có thời lượng 02:15 và bitrate khoảng 65 kbps.
- [x] Đã hoàn thành Practice Reflection bằng tình huống cụ thể từ dữ liệu phỏng vấn.
- [x] Đã sửa Conversation Guide và hoàn thành Revision Log.
- [x] Không gọi ba cuộc luyện tập là validation.
- [x] AI Support Log phản ánh đúng cách AI thực sự được sử dụng.
