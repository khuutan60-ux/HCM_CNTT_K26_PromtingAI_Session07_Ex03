# XÂY DỰNG PROMPT ĐÁNH GIÁ BÀI VIẾT CỦA SINH VIÊN BẰNG AI

## 1. Mục tiêu

Xây dựng một Prompt giúp AI đóng vai trò giảng viên chấm bài viết của sinh viên đại học một cách khách quan, nhất quán và có căn cứ.

Chủ đề bài viết: **Vai trò của AI trong hoạt động học tập của sinh viên đại học.**

AI cần đánh giá bài viết theo Rubric 5 tiêu chí, chỉ rõ minh chứng cho từng điểm số, nhận xét ưu điểm, hạn chế và đề xuất cách cải thiện.

## 2. Prompt thiết lập vai trò người chấm

```text
ROLE:
Bạn là giảng viên đại học có kinh nghiệm trong việc đánh giá
kỹ năng viết và tư duy lập luận của sinh viên.

TASK:
Đọc và đánh giá bài viết khoảng 300 từ với chủ đề:
"Vai trò của AI trong hoạt động học tập của sinh viên đại học".

Yêu cầu đánh giá:

1. Chấm điểm theo đúng 5 tiêu chí trong Rubric.
2. Không tự ý thay đổi điểm tối đa hoặc trọng số.
3. Mỗi điểm số phải có minh chứng cụ thể từ bài viết.
4. Không đánh giá cao chỉ vì bài viết dài.
5. Không chấm điểm theo cảm tính.
6. Chỉ ra lỗi và đề xuất cách sửa cụ thể.
7. Tính tổng điểm chính xác trên thang 10.

RUBRIC:

- Đúng chủ đề: 2 điểm.
- Nội dung và lập luận: 3 điểm.
- Ví dụ minh họa: 2 điểm.
- Cấu trúc bài viết: 1.5 điểm.
- Ngữ pháp và diễn đạt: 1.5 điểm.

OUTPUT FORMAT:

Phần 1: Bảng chấm điểm chi tiết.
Phần 2: Minh chứng cụ thể cho từng tiêu chí.
Phần 3: Điểm mạnh của bài viết.
Phần 4: Điểm yếu và lỗi cần khắc phục.
Phần 5: Đề xuất cải thiện.
Phần 6: Tổng điểm trên thang 10.

QUY TẮC:
- Sử dụng tiếng Việt.
- Nhận xét khách quan, chuyên nghiệp.
- Không tự tạo minh chứng không xuất hiện trong bài.
- Nếu không có đủ thông tin để đánh giá, phải nêu rõ.
- Không thay đổi Rubric dưới bất kỳ hình thức nào.
```

## 3. Rubric đánh giá bài viết

| Tiêu chí | Điểm tối đa | Nội dung đánh giá |
|---|---:|---|
| Đúng chủ đề | 2 | Bám sát chủ đề AI trong học tập |
| Nội dung và lập luận | 3 | Có luận điểm, phân tích và lập luận hợp lý |
| Ví dụ minh họa | 2 | Có ví dụ cụ thể, phù hợp |
| Cấu trúc bài viết | 1.5 | Có mở bài, thân bài và kết luận |
| Ngữ pháp và diễn đạt | 1.5 | Câu văn rõ ràng, đúng ngữ pháp |
| **Tổng** | **10** | |

## 4. Bài viết mẫu khoảng 300 từ

### Chủ đề: Vai trò của AI trong hoạt động học tập của sinh viên đại học

Trong thời đại công nghệ phát triển mạnh mẽ, trí tuệ nhân tạo (AI) đang trở thành một công cụ hỗ trợ quan trọng trong nhiều lĩnh vực, đặc biệt là giáo dục đại học. AI giúp sinh viên tiếp cận kiến thức nhanh hơn, nâng cao hiệu quả học tập và phát triển khả năng tự nghiên cứu.

Trước hết, AI giúp sinh viên tiết kiệm thời gian tìm kiếm và tổng hợp thông tin. Thay vì phải đọc nhiều tài liệu trong thời gian dài, sinh viên có thể sử dụng AI để tóm tắt nội dung, giải thích những khái niệm khó hiểu và gợi ý tài liệu tham khảo. Chẳng hạn, khi học lập trình Python, sinh viên có thể nhờ AI giải thích lỗi trong đoạn code và đưa ra hướng khắc phục. Điều này giúp người học hiểu rõ hơn nguyên nhân gây lỗi thay vì chỉ tìm cách sao chép đáp án.

Bên cạnh những lợi ích, việc sử dụng AI cũng tồn tại một số hạn chế. Nếu quá phụ thuộc vào AI, sinh viên có thể giảm khả năng tư duy độc lập, sáng tạo và giải quyết vấn đề. Ngoài ra, AI đôi khi cung cấp thông tin chưa chính xác, vì vậy người học cần kiểm tra lại nội dung từ giáo trình và các nguồn đáng tin cậy.

Theo tôi, AI nên được xem là công cụ hỗ trợ chứ không phải phương tiện thay thế hoàn toàn quá trình học tập. Sinh viên cần chủ động đặt câu hỏi, kiểm chứng thông tin và tự thực hiện bài tập để nâng cao kiến thức.

Tóm lại, AI mang lại nhiều cơ hội cải thiện chất lượng học tập ở đại học. Tuy nhiên, hiệu quả của công nghệ này phụ thuộc vào cách mỗi sinh viên sử dụng. Biết khai thác AI hợp lý sẽ giúp sinh viên học tập chủ động và hiệu quả hơn.

## 5. Kết quả AI chấm điểm bài viết mẫu

### 5.1. Bảng chấm điểm tổng hợp

| Tiêu chí | Điểm tối đa | Điểm đạt | Nhận xét |
|---|---:|---:|---|
| Đúng chủ đề | 2 | 2.0 | Bám sát chủ đề xuyên suốt |
| Nội dung và lập luận | 3 | 2.5 | Có phân tích lợi ích và hạn chế |
| Ví dụ minh họa | 2 | 1.5 | Có ví dụ Python cụ thể nhưng chưa đa dạng |
| Cấu trúc bài viết | 1.5 | 1.5 | Đầy đủ mở bài, thân bài, kết luận |
| Ngữ pháp và diễn đạt | 1.5 | 1.3 | Diễn đạt rõ ràng, một số ý còn khái quát |
| **Tổng điểm** | **10** | **8.8** | |

### 5.2. Bảng đối chiếu điểm số và minh chứng

| Tiêu chí | Minh chứng từ bài viết | Căn cứ chấm điểm |
|---|---|---|
| Đúng chủ đề | "AI giúp sinh viên tiếp cận kiến thức nhanh hơn" | Nội dung tập trung trực tiếp vào AI trong học tập |
| Nội dung và lập luận | "Nếu quá phụ thuộc vào AI, sinh viên có thể giảm khả năng tư duy độc lập" | Có phân tích cả lợi ích và hạn chế |
| Ví dụ minh họa | "Khi học lập trình Python, sinh viên có thể nhờ AI giải thích lỗi trong đoạn code" | Ví dụ phù hợp nhưng mới tập trung vào một tình huống |
| Cấu trúc bài viết | Các đoạn mở đầu, triển khai luận điểm và kết luận | Bố cục rõ ràng, trình tự hợp lý |
| Ngữ pháp và diễn đạt | "Biết khai thác AI hợp lý sẽ giúp sinh viên học tập chủ động và hiệu quả hơn" | Câu văn rõ nghĩa, dễ hiểu, chưa có lỗi nghiêm trọng |

### 5.3. Điểm mạnh

- Bài viết bám sát chủ đề được giao.
- Trình bày được cả mặt tích cực và hạn chế của AI.
- Có ví dụ liên quan đến việc học lập trình Python.
- Các đoạn văn được sắp xếp theo trình tự logic.
- Ngôn ngữ tương đối rõ ràng và phù hợp với môi trường học thuật.

### 5.4. Điểm yếu

- Ví dụ minh họa chưa đa dạng, chủ yếu tập trung vào lập trình.
- Một số nhận định còn khái quát, chưa có dẫn chứng hoặc số liệu cụ thể.
- Phần phân tích hạn chế của AI chưa đi sâu vào vấn đề kiểm chứng thông tin và trách nhiệm của người học.
- Một số câu văn có thể diễn đạt cụ thể hơn để tăng tính thuyết phục.

### 5.5. Đề xuất cải thiện

1. Bổ sung ví dụ về việc sử dụng AI trong học ngoại ngữ, nghiên cứu tài liệu hoặc chuẩn bị thuyết trình.
2. Phân tích sâu hơn tác động của việc phụ thuộc AI đến tư duy phản biện.
3. Bổ sung nguồn thông tin đáng tin cậy nếu đưa ra các nhận định cần chứng minh.
4. Tăng tính liên kết giữa các luận điểm bằng những câu chuyển ý phù hợp.
5. Thay thế các nhận định chung chung bằng phân tích và tình huống cụ thể.

## 6. Kết luận

Thông qua Prompt và Rubric được xây dựng, AI có thể hỗ trợ giảng viên đánh giá bài viết của sinh viên theo một hệ thống tiêu chí thống nhất.

Kết quả chấm điểm không chỉ thể hiện bằng điểm số mà còn đi kèm minh chứng cụ thể, nhận xét ưu điểm, hạn chế và đề xuất cải thiện.

**Kết quả bài viết mẫu: 8.8/10 điểm.**

Prompt này giúp hạn chế việc đánh giá cảm tính, tăng tính minh bạch và giúp sinh viên hiểu rõ mình cần cải thiện những kỹ năng nào trong quá trình viết bài.