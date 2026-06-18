---
artifact: 02 - JTBD Project Analysis
bai-tap: Lab 2 - Dùng JTBD để soi lại dự án nhóm
ngày: 18/06/2026
người-làm: Đỗ Thị Thanh Bình
companion-reference: Strategyn_JTBD_Playbook.pdf
---

# Lab 2 — JTBD Project Analysis

**Tên dự án / sản phẩm:** VinUni International Student Assistant — trợ lý hỗ trợ sinh viên quốc tế

---

## 1. Project Slice

- **Dự án của nhóm tôi là:** VinUni International Student Assistant — trợ lý đa ngôn ngữ giúp sinh viên quốc tế tìm và hiểu thông tin chính thức của VinUniversity.
- **Lát cắt tôi chọn để phân tích:** Sinh viên quốc tế mới nhập học cần hoàn tất đúng hạn các thủ tục bắt buộc liên quan đến visa và hồ sơ nhập học trước khi bắt đầu học kỳ.
- **Vì sao tôi chọn lát cắt này:** Đây là một job có điểm bắt đầu, kết quả và hậu quả rõ ràng. Nếu tìm sai nguồn, hiểu sai yêu cầu hoặc bỏ lỡ deadline, sinh viên có thể chậm nhập học hay phải làm lại hồ sơ. Workflow cũng đủ cụ thể để map từ xác định thủ tục đến xác nhận đã hoàn tất.

**Checklist lát cắt:**

- [x] 1 nhóm người dùng chính
- [x] 1 hoàn cảnh / tình huống rõ
- [x] 1 job cốt lõi
- [x] 1 workflow đủ cụ thể để vẽ ra được

---

## 2. Project Snapshot

1. **Nhóm tôi đang nghĩ mình đang giải quyết vấn đề gì?**  
   > Sinh viên quốc tế mới nhập học khó ghép các thông tin rải rác thành một kế hoạch hành động đáng tin: cần làm thủ tục nào, chuẩn bị giấy tờ gì, theo deadline nào và hỏi ai khi trường hợp của mình không khớp hướng dẫn chung.

2. **Người dùng chính hiện nhóm đang nhắm tới là ai?**  
   > Sinh viên quốc tế đã nhận thư mời nhập học và đang chuẩn bị bắt đầu học kỳ tại VinUniversity.

3. **Hiện tại người dùng đó đang giải quyết vấn đề này bằng cách nào?**  
   > Họ dò website và email nhập học, tự lập checklist, hỏi senior, gửi email cho phòng ban phụ trách, hoặc dùng công cụ dịch/AI tổng quát để hiểu nội dung khó.

---

## 3. Market Context

1. **Ai đang gặp vấn đề này?**  
   > Sinh viên quốc tế đã được nhận vào VinUniversity nhưng chưa quen quy trình visa và hồ sơ nhập học tại Việt Nam.

2. **Vấn đề xuất hiện trong hoàn cảnh nào?**  
   > Trong giai đoạn từ khi nhận thư mời đến ngày bắt đầu học kỳ, khi họ phải phối hợp nhiều yêu cầu, giấy tờ, đầu mối và deadline.

3. **Hiện tại họ đang dùng giải pháp thay thế nào?**  
   > Website và email chính thức, checklist tự tạo, senior/bạn bè, công cụ dịch hoặc AI tổng quát, và email trực tiếp tới phòng ban.

4. **Vì sao đây là thời điểm đáng giải?**  
   > Đây là job có deadline và chi phí sai sót cao, trong khi khác biệt ngôn ngữ, múi giờ và bối cảnh hành chính làm tăng khả năng hiểu sai. Tuy nhiên, mức độ phổ biến và cường độ của pain vẫn cần được xác nhận bằng dữ liệu người dùng thật.

**Tóm tắt market context:**

> Trong giai đoạn trước nhập học, sinh viên quốc tế không chỉ cần “tìm thông tin”; họ cần biến nhiều nguồn hướng dẫn thành một chuỗi việc đúng với trường hợp của mình. Các kênh hiện tại có thể chứa câu trả lời đúng nhưng buộc sinh viên tự ghép nguồn, kiểm tra phiên bản và xác định đầu mối. Cơ hội sản phẩm nằm ở việc giảm sự bất định trước khi hành động, không phải thay thế quyết định chính thức của nhà trường.

---

## 4. Job Executor

- **Job executor của dự án này là:** Sinh viên quốc tế đã nhận thư mời nhập học tại VinUniversity.
- **Vì sao đây là người trực tiếp “thuê” giải pháp để làm job:** Chính sinh viên phải hiểu yêu cầu, chuẩn bị và nộp hồ sơ, theo dõi deadline, rồi xử lý các thiếu sót. Nhà trường có thể là buyer hoặc đơn vị vận hành; staff và senior là influencer/supporter, nhưng không trực tiếp hoàn thành job thay sinh viên.

---

## 5. Core JTBD

**Core JTBD bản nháp:**  
> Tìm và hiểu thông tin cần thiết để xử lý thủ tục nhập học.

**Các từ solution cần tránh:** AI, chatbot, RAG, knowledge base, app.

**Core JTBD cuối cùng:**  
> Hoàn tất đúng hạn các thủ tục visa và hồ sơ nhập học bắt buộc để có thể bắt đầu học tại VinUniversity theo kế hoạch.

**Tự kiểm:**

- [x] Nếu bỏ tool hiện tại đi, job này vẫn còn tồn tại
- [x] Trong câu không có tên sản phẩm, AI, chatbot, app, màn hình
- [x] Câu mô tả điều user muốn hoàn thành, không phải thứ product đang làm

---

## 6. Job Stories

| # | Trigger / When | Motivation / I want to | Outcome / so I can | Điều story này cho thấy |
|---|---|---|---|---|
| JS1 | Khi tôi nhận thư mời nhập học nhưng chưa biết trường hợp visa của mình cần những bước nào | tôi muốn xác định đúng thủ tục, giấy tờ và deadline áp dụng cho mình | tôi có thể lập kế hoạch hoàn tất hồ sơ trước ngày nhập học | Pain bắt đầu từ việc phân loại đúng trường hợp, không chỉ từ việc thiếu thông tin |
| JS2 | Khi hướng dẫn nằm trong nhiều email hoặc trang web và dùng thuật ngữ tôi chưa quen | tôi muốn đối chiếu yêu cầu và chuyển chúng thành một checklist có nguồn | tôi có thể chuẩn bị đủ hồ sơ mà không phải đoán hoặc làm lại | User cần tổng hợp có khả năng truy vết, không phải một câu trả lời trôi nổi |
| JS3 | Khi hồ sơ của tôi có ngoại lệ hoặc tôi vẫn chưa chắc trước khi nộp | tôi muốn biết câu hỏi cần gửi, thông tin cần đính kèm và đúng đầu mối phụ trách | tôi có thể nhận xác nhận chính thức mà không mất nhiều vòng email | Product cần biết giới hạn và routing, không được giả vờ thay thế staff |

---

## 7. Current Alternatives

| Alternative hiện tại | User đang thuê nó để làm gì? | Nó làm tốt gì? | Nó fail ở đâu? | Switching cost hiện tại |
|---|---|---|---|---|
| Website và email chính thức của VinUni | Tra yêu cầu, biểu mẫu, deadline và đầu mối | Có thẩm quyền và có thể trích dẫn | Có thể phân tán theo kênh; sinh viên vẫn phải tự xác định nội dung nào áp dụng cho mình | Trung bình |
| Gửi email cho phòng ban phụ trách | Xin giải đáp hoặc xác nhận cho trường hợp cụ thể | Có thể đưa ra câu trả lời chính thức và xử lý ngoại lệ | Có thể cần nhiều vòng nếu câu hỏi ban đầu thiếu ngữ cảnh; thời gian phản hồi cần được đo thay vì giả định | Trung bình |
| Hỏi senior/bạn bè | Học kinh nghiệm thực tế và cách diễn giải dễ hiểu | Dễ tiếp cận, tạo cảm giác yên tâm | Thông tin có thể cũ hoặc không áp dụng cho quốc tịch/trường hợp khác | Thấp |
| Công cụ dịch hoặc AI tổng quát | Dịch, tóm tắt và giải thích thuật ngữ | Nhanh, hội thoại được, dùng bất cứ lúc nào | Không biết nguồn VinUni nào mới nhất và có thể tạo câu trả lời nghe hợp lý nhưng sai | Thấp |

**Nếu project biến mất hôm nay, user nhiều khả năng sẽ quay về:**

> Ghép thông tin từ website và email, hỏi senior, rồi gửi email cho phòng ban để xác nhận; nếu khó hiểu, họ sẽ dùng công cụ dịch hoặc AI tổng quát như một lớp hỗ trợ phụ.

---

## 8. JTBD Lite Map

| Step | Trong workflow này user đang cố làm gì? | Hôm nay họ đang dùng gì? | Friction / pain hiện tại | Mức đau |
|---|---|---|---|---|
| Define | Xác định những thủ tục nào áp dụng cho quốc tịch, tình trạng visa và kỳ nhập học của mình | Thư mời, email onboarding, website, hỏi senior | Khó phân biệt hướng dẫn chung với yêu cầu áp dụng cho trường hợp cá nhân | High |
| Locate | Tìm phiên bản hướng dẫn, biểu mẫu và đầu mối có thẩm quyền | Website VinUni, email, Google | Nguồn có thể nằm ở nhiều nơi; khó nhận biết nội dung mới nhất | High |
| Prepare | Lập checklist và chuẩn bị đủ giấy tờ/thông tin cần nộp | Checklist tự tạo, email cũ, mẫu từ senior | Một yêu cầu bị hiểu sai có thể kéo theo hồ sơ thiếu hoặc phải làm lại | High |
| Confirm | Kiểm tra checklist và các ngoại lệ trước khi nộp | Đọc lại nguồn, hỏi senior, email cho staff | Khó biết khi nào có thể tự tin làm tiếp và khi nào bắt buộc phải xin xác nhận | High |
| Execute | Điền form, gửi email hoặc nộp hồ sơ qua kênh quy định | Form, email, portal, phòng ban liên quan | Gửi sai kênh hoặc thiếu ngữ cảnh làm tăng số vòng xử lý | Med |
| Monitor | Theo dõi trạng thái, yêu cầu bổ sung và deadline | Inbox, calendar, ghi chú cá nhân | Trạng thái phân tán; dễ bỏ sót yêu cầu mới trong email | Med |
| Modify | Bổ sung hoặc sửa hồ sơ theo phản hồi | Email qua lại, chỉnh form/tài liệu | Có thể sửa phần biểu hiện nhưng vẫn chưa hiểu nguyên nhân bị trả lại | Med |
| Conclude | Xác nhận mọi thủ tục bắt buộc đã hoàn tất | Email xác nhận, portal, checklist cá nhân | Thiếu một “định nghĩa hoàn tất” thống nhất khiến sinh viên vẫn lo còn bước ẩn | Med |

**Bước đau nhất #1:** Define — xác định đúng bộ yêu cầu áp dụng cho trường hợp của mình

**Bước đau nhất #2:** Confirm — kiểm tra cách hiểu và ngoại lệ trước khi nộp

**Vì sao đây là nơi đáng chú ý:**

> Locate là vấn đề nhìn thấy được, nhưng Define và Confirm mới là nơi rủi ro quyết định tập trung. Tìm thấy một trang chưa có nghĩa sinh viên biết trang đó có áp dụng cho mình hay không. Nếu phân loại sai trường hợp hoặc tự tin sai trước khi nộp, mọi bước sau đều phát sinh rework.

---

## 9. AI Leverage Point

| Step | AI nên giúp bằng cách nào? | Vì sao AI hợp ở đây? | Rủi ro chính nếu dùng AI |
|---|---|---|---|
| Define | Hỏi các câu làm rõ tối thiểu, đối chiếu với nguồn chính thức và chỉ ra bộ yêu cầu có khả năng áp dụng | AI phù hợp với việc hiểu câu hỏi tự nhiên, hỗ trợ đa ngôn ngữ và điều hướng qua nhiều tài liệu | Phân loại sai có thể khiến sinh viên bỏ qua thủ tục; các trường hợp không chắc chắn phải được chuyển sang staff |
| Confirm | Chuyển các yêu cầu đã truy xuất thành checklist có citation, nêu điểm chưa chắc chắn và chuẩn bị nội dung để xin xác nhận chính thức | AI mạnh ở tóm tắt, so sánh và cấu trúc hóa thông tin thành bước hành động | Checklist tạo cảm giác chắc chắn giả nếu nguồn cũ, thiếu hoặc mâu thuẫn |

**AI leverage point quan trọng nhất:**

> Giảm sự bất định tại hai “cổng quyết định”: xác định yêu cầu nào áp dụng và kiểm tra mức độ chắc chắn trước khi nộp. Hệ thống nên đưa ra checklist có nguồn, hiển thị ngày cập nhật và chuyển đúng đầu mối khi gặp ngoại lệ.

**Vì sao không phải ở bước khác:**  
> Execute liên quan đến giao dịch chính thức và trách nhiệm của nhà trường; Monitor cần tích hợp trạng thái với hệ thống nguồn. Trong phạm vi MVP, AI tạo giá trị khả thi hơn ở trước hành động, nơi nó có thể giảm thời gian đọc và số vòng hỏi lại mà không tự nhận quyền phê duyệt.

---

## 10. Product Hypothesis

> Nếu chúng ta giúp sinh viên quốc tế mới nhập học xác định đúng bộ yêu cầu visa/hồ sơ áp dụng cho mình và kiểm tra checklist trước khi nộp, bằng một trợ lý đa ngôn ngữ truy xuất từ nguồn VinUni có citation và cơ chế chuyển staff khi không chắc chắn, thì họ sẽ dùng trợ lý trước khi tự dò nhiều email hoặc gửi câu hỏi thiếu ngữ cảnh, vì họ có thể chuẩn bị nhanh hơn mà vẫn truy vết được căn cứ chính thức.

**Tín hiệu sớm nếu hypothesis đúng:**

1. Trong bài test theo nhiệm vụ, sinh viên hoàn thành checklist đúng và nhanh hơn cách dùng website/email hiện tại, không tăng số lỗi nghiêm trọng.
2. Các câu hỏi cần chuyển cho staff chứa đủ thông tin ngay từ vòng đầu; số lượt trao đổi trung vị để đi đến câu trả lời chính thức giảm.

---

## 11. Assumptions To Validate

| Assumption | Vì sao assumption này rủi ro? | Tôi đang có bằng chứng gì? | Cần validate bằng cách nào tiếp theo? |
|---|---|---|---|
| A1: Sinh viên là job executor phù hợp và sẵn sàng tự phục vụ trước khi hỏi staff | Nếu họ luôn muốn staff xử lý trực tiếp, một lớp self-service sẽ ít được dùng | Hiện mới có logic từ cấu trúc workflow, chưa có bằng chứng người dùng trực tiếp | Phỏng vấn 5–7 sinh viên quốc tế gần đây; dựng timeline cho một thủ tục thật và ghi lại điểm họ tìm trợ giúp |
| A2: Define/Confirm là hai pain lớn nhất | Pain thực tế có thể nằm ở việc xin giấy tờ bên ngoài VinUni hoặc thời gian cơ quan nhà nước xử lý — nơi sản phẩm không can thiệp được | Chưa có dữ liệu định lượng; đây là suy luận từ hậu quả của việc hiểu sai | Quan sát 5 task thực tế, mã hóa thời gian chờ, rework và số lần chuyển kênh theo từng bước job map |
| A3: Nguồn VinUni đủ đầy, nhất quán và có owner cập nhật | RAG không thể bù cho nguồn thiếu hoặc mâu thuẫn; thông tin sai về visa/deadline có hậu quả cao | Nhóm mới có hướng xây knowledge base, chưa có audit về coverage/freshness | Lập source inventory, owner và SLA cập nhật; tạo bộ câu hỏi vàng được staff duyệt để regression test |
| A4: Trợ lý tốt hơn workflow website/email hiện tại | Nếu người dùng đã tìm được câu trả lời đủ nhanh, chatbot chỉ thêm một lớp giao diện | Chưa có baseline về thời gian hoàn thành, tỷ lệ đúng hoặc số vòng email | A/B task test với 8–10 người: current workflow so với prototype; đo thời gian, độ chính xác và nhu cầu escalation |
| A5: Citation và escalation tạo đủ niềm tin để hành động | Người dùng có thể hoặc tin mù quáng, hoặc bỏ qua công cụ và vẫn hỏi staff mọi lần | Chưa có bằng chứng hành vi; mới là giả thuyết thiết kế | Test ba mức trình bày nguồn/độ chắc chắn; đo khả năng chọn đúng lúc tự làm và đúng lúc hỏi staff |

**Assumption nguy hiểm nhất nếu tôi đang sai:**

> Nguồn VinUni có đủ đầy, nhất quán và có người chịu trách nhiệm cập nhật hay không. Nếu lớp dữ liệu nền không đáng tin, AI chỉ làm thông tin sai lan nhanh và thuyết phục hơn.

---

## 12. Share Trong Bàn Và Version Cuối

| Ý phản biện tôi nghe được | Nó chạm vào phần nào? | Tôi sẽ giữ / sửa gì? |
|---|---|---|
| Chatbot không nên tự quyết các trường hợp visa nhạy cảm | AI leverage point / risk | Thêm ngưỡng độ chắc chắn và escalation bắt buộc; AI không xác nhận thay staff |
| User không chỉ cần câu trả lời nhanh mà cần biết căn cứ nào đáng tin | Product hypothesis | Yêu cầu citation, ngày cập nhật và owner của nguồn ngay trong trải nghiệm |
| Nhu cầu tập trung mạnh ở một giai đoạn ngắn | Project slice / assumptions | Giữ lát cắt hẹp để kiểm chứng giá trị trước; chưa mở rộng sang học tập/đời sống khi chưa có bằng chứng |

**Sau phản biện, tôi thay đổi gì:**

- [x] Giữ nguyên job executor
- [x] Giữ nguyên core JTBD
- [x] Sửa AI leverage point
- [x] Sửa product hypothesis

**Vì sao tôi giữ / sửa:**

> Tôi giữ job executor và Core JTBD vì người trực tiếp chịu trách nhiệm hoàn tất thủ tục vẫn là sinh viên. Tôi sửa leverage point và hypothesis để bỏ hàm ý “chatbot biết mọi thứ”: AI chỉ cấu trúc hóa thông tin có nguồn, biểu đạt mức độ chắc chắn và chuyển trường hợp ngoại lệ cho staff.

### Version cuối cùng tôi nộp

**Job executor:**  
> Sinh viên quốc tế đã nhận thư mời nhập học và đang chuẩn bị bắt đầu học kỳ tại VinUniversity.

**Core JTBD:**  
> Hoàn tất đúng hạn các thủ tục visa và hồ sơ nhập học bắt buộc để có thể bắt đầu học tại VinUniversity theo kế hoạch.

**2 bước đau nhất trong workflow:**  
> Define — xác định đúng bộ yêu cầu áp dụng; Confirm — kiểm tra cách hiểu và ngoại lệ trước khi nộp.

**AI leverage point chính:**  
> Trợ lý đa ngôn ngữ tạo checklist có citation từ nguồn VinUni, nêu điểm chưa chắc chắn và chuyển đúng đầu mối khi trường hợp cần xác nhận chính thức.

**Product hypothesis:**  
> Nếu chúng ta giúp sinh viên quốc tế mới nhập học xác định đúng bộ yêu cầu visa/hồ sơ áp dụng cho mình và kiểm tra checklist trước khi nộp, bằng một trợ lý đa ngôn ngữ truy xuất nguồn VinUni có citation và escalation, thì họ sẽ dùng trợ lý trước khi tự dò nhiều email hoặc gửi câu hỏi thiếu ngữ cảnh, vì họ chuẩn bị nhanh hơn mà vẫn truy vết được căn cứ chính thức.

**Assumption cần validate đầu tiên:**  
> Nguồn VinUni có đủ đầy, nhất quán và có owner cập nhật để hệ thống tạo hướng dẫn an toàn hay không.

---

## Checklist Trước Khi Nộp

- [x] Tôi đã khoanh đúng 1 lát cắt cụ thể của dự án.
- [x] Tôi đã phân biệt được job executor với buyer / influencer.
- [x] Core JTBD của tôi không nhét solution vào câu.
- [x] Tôi đã viết đủ 3 job stories.
- [x] Tôi đã điền JTBD lite map và khoanh ra 2 bước đau nhất.
- [x] Tôi đã chỉ ra AI leverage point thay vì nhảy thẳng vào feature list.
- [x] Tôi đã ghi rõ assumptions to validate.
- [x] Tôi đã sửa version cuối sau khi share trong bàn.
