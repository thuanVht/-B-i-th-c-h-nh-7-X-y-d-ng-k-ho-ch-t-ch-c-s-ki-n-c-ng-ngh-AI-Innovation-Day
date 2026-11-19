# **BÀI TẬP THỰC HÀNH: XÂY DỰNG KẾ HOẠCH TỔ CHỨC SỰ KIỆN AI INNOVATION DAY BẰNG AI**

## **1. Xây dựng bộ Prompt kết hợp 3 kỹ thuật**

Sử dụng kết hợp Chain-of-Thought, Prompt Chaining và Context Management để xây dựng kế hoạch tổ chức sự kiện một cách khoa học, đảm bảo tính khả thi và không vượt ngân sách.

**Thông tin cố định của dự án:**

- Tên sự kiện: AI Innovation Day.
- Quy mô: 150 sinh viên.
- Thời gian: 1 ngày.
- Ngân sách tối đa: 15.000.000 đồng.
- Nhân sự: 10 người.
- Mục tiêu: Giúp sinh viên hiểu và trải nghiệm ứng dụng AI trong học tập và công việc.

### **1.1. Sơ đồ quy trình Prompt Chaining**

**Prompt 1: Phân tích tính khả thi**

Chain-of-Thought: Phân tích nguồn lực, ngân sách và rủi ro

**Prompt 2: Xây dựng lịch trình**

Sử dụng kết quả phân tích tính khả thi

**Prompt 3: Lập ngân sách và phân công**

Liên kết lịch trình, chi phí và 10 nhân sự

**Prompt 4: Xây dựng truyền thông**

Dựa trên nội dung và nguồn lực sự kiện

**Prompt 5: Kiểm tra và hiệu chỉnh**

Kiểm tra tính thống nhất và điều chỉnh sai sót

**Context Management**

Tóm tắt dự án để tiếp tục ở hội thoại mới

### **1.2. Bộ prompt hoàn chỉnh**

**Prompt 1: Phân tích tính khả thi (Chain-of-Thought)**

```
Bạn là chuyên gia tổ chức sự kiện công nghệ.

Hãy phân tích tính khả thi của sự kiện AI Innovation Day.

Thông tin:
- Quy mô: 150 sinh viên.
- Thời gian: 1 ngày.
- Ngân sách tối đa: 15.000.000 đồng.
- Nhân sự: 10 người.
- Mục tiêu: Giúp sinh viên hiểu và trải nghiệm
ứng dụng AI trong học tập và công việc.

Hãy phân tích lần lượt:
1. Nhu cầu cơ sở vật chất.
2. Khả năng đáp ứng nhân sự.
3. Khả năng tổ chức với ngân sách hiện có.
4. Những rủi ro có thể xảy ra.
5. Đề xuất giải pháp hạn chế rủi ro.

Kiểm tra các giả định và phép tính ngân sách.
Không thay đổi các thông tin ban đầu.

Trả về kết luận về tính khả thi và các điều kiện
cần đảm bảo cho sự kiện.
```

**Prompt 2: Xây dựng lịch trình sự kiện (Prompt Chaining)**

```
Bạn là chuyên gia lập kế hoạch sự kiện.

Dựa trên kết quả phân tích tính khả thi từ Prompt 1,
hãy xây dựng lịch trình sự kiện AI Innovation Day
trong một ngày.

Yêu cầu:
- Phù hợp với 150 sinh viên.
- Có hoạt động khai mạc, giới thiệu AI,
  trải nghiệm thực tế, giải lao và tổng kết.
- Ghi rõ thời gian bắt đầu và kết thúc.
- Phân bổ thời gian hợp lý.
- Phù hợp với nguồn lực và ngân sách đã phân tích.

Không thay đổi quy mô, thời gian và mục tiêu sự kiện.

Đầu ra sẽ được sử dụng cho Prompt 3.
```

**Prompt 3: Lập ngân sách và phân công nhân sự**

```
Bạn là chuyên gia quản lý dự án sự kiện.

Dựa trên kết quả Prompt 1 và Prompt 2,
hãy thực hiện:

1. Lập bảng dự toán ngân sách chi tiết.
2. Phân bổ kinh phí cho từng hạng mục.
3. Đảm bảo tổng ngân sách không vượt 15 triệu đồng.
4. Phân công nhiệm vụ cụ thể cho 10 nhân sự.
5. Đảm bảo mỗi hoạt động trong lịch trình
   đều có người phụ trách.

Kiểm tra tổng chi phí bằng phép tính cộng.
Dành một khoản dự phòng hợp lý.

Không thay đổi quy mô 150 sinh viên
và số lượng 10 nhân sự.

Đầu ra sẽ được sử dụng cho Prompt 4.
```

**Prompt 4: Xây dựng kế hoạch truyền thông**

```
Bạn là chuyên gia truyền thông sự kiện.

Dựa trên kết quả Prompt 1, 2 và 3,
hãy xây dựng kế hoạch truyền thông trước sự kiện
AI Innovation Day.

Yêu cầu:
1. Xác định đối tượng truyền thông.
2. Xây dựng thông điệp chính.
3. Lập kế hoạch truyền thông trước sự kiện.
4. Xác định kênh truyền thông phù hợp.
5. Phân công nhân sự phụ trách.
6. Đề xuất nội dung bài đăng và hình ảnh.
7. Kêu gọi sinh viên đăng ký tham gia.

Truyền thông phải phù hợp với quy mô 150 sinh viên,
ngân sách 15 triệu đồng và nhân sự hiện có.

Đầu ra sẽ được sử dụng cho Prompt 5.
```

**Prompt 5: Kiểm tra và hiệu chỉnh kế hoạch**

```
Bạn là chuyên gia kiểm định kế hoạch tổ chức sự kiện.

Hãy kiểm tra toàn bộ kết quả từ Prompt 1 đến Prompt 4.

Các tiêu chí:
1. Tổng ngân sách có vượt 15 triệu không?
2. Quy mô có đúng 150 sinh viên không?
3. Nhân sự có đúng 10 người không?
4. Lịch trình có phù hợp trong một ngày không?
5. Các hạng mục có liên kết với nhau không?
6. Nhân sự có bị phân công trùng hoặc quá tải không?
7. Kế hoạch truyền thông có phù hợp với sự kiện không?
8. Có rủi ro nào chưa được xử lý không?

Nếu phát hiện vấn đề:
- Chỉ rõ vấn đề.
- Giải thích nguyên nhân.
- Đề xuất phương án sửa.
- Cập nhật lại kế hoạch.

Không tự ý thay đổi các ràng buộc ban đầu.

Xuất báo cáo kiểm tra và kế hoạch sau hiệu chỉnh.
```

## **2. Bản phân tích tính khả thi của sự kiện**

### **2.1. Đánh giá nguồn lực**

| Tiêu chí  | Nguồn lực                  | Đánh giá                      |
| --------- | -------------------------- | ----------------------------- |
| Quy mô    | 150 sinh viên              | Có thể tổ chức                |
| Thời gian | 1 ngày                     | Phù hợp                       |
| Ngân sách | 15 triệu đồng              | Cần kiểm soát chi phí         |
| Nhân sự   | 10 người                   | Có thể phân công theo nhóm    |
| Địa điểm  | Hội trường của trường      | Giả định được hỗ trợ miễn phí |
| Thiết bị  | Máy chiếu, âm thanh, Wi-Fi | Cần kiểm tra trước            |

### **2.2. Đánh giá rủi ro**

| Rủi ro                     | Mức độ     | Giải pháp                                           |
| -------------------------- | ---------- | --------------------------------------------------- |
| Vượt ngân sách             | Cao        | Theo dõi chi phí từng hạng mục                      |
| Sinh viên tham gia ít      | Trung bình | Tăng cường truyền thông                             |
| Mất kết nối Internet       | Cao        | Chuẩn bị video và tài liệu dự phòng                 |
| Thiếu thiết bị             | Trung bình | Kiểm tra trước sự kiện                              |
| Diễn giả đến muộn          | Trung bình | Có người thay thế hoặc điều chỉnh lịch              |
| Quá tải khi trải nghiệm AI | Trung bình | Chia 150 sinh viên thành 15 nhóm, mỗi nhóm 10 người |

### **2.3. Kết luận tính khả thi**

Sự kiện AI Innovation Day có tính khả thi nếu ban tổ chức tận dụng được hội trường và thiết bị sẵn có của trường, sử dụng diễn giả nội bộ hoặc khách mời hỗ trợ và kiểm soát chặt chẽ chi phí.

Với 10 nhân sự, ban tổ chức có thể chia thành các nhóm phụ trách nội dung, hậu cần, truyền thông và điều phối.

## **3. Lịch trình chương trình trong một ngày**

**Địa điểm dự kiến:** Hội trường trường học.

| Thời gian   | Hoạt động    | Nội dung                                |
| ----------- | ------------ | --------------------------------------- |
| 07:30–08:00 | Đón tiếp     | Check-in sinh viên                      |
| 08:00–08:15 | Khai mạc     | Giới thiệu sự kiện                      |
| 08:15–09:00 | Chuyên đề 1  | Tổng quan về trí tuệ nhân tạo           |
| 09:00–09:45 | Chuyên đề 2  | Ứng dụng AI trong học tập               |
| 09:45–10:00 | Giải lao     | Nghỉ ngơi                               |
| 10:00–11:30 | Workshop 1   | Thực hành sử dụng AI                    |
| 11:30–13:00 | Nghỉ trưa    | Nghỉ ngơi                               |
| 13:00–14:00 | Chuyên đề 3  | Ứng dụng AI trong công việc             |
| 14:00–15:15 | Workshop 2   | Thực hành giải quyết tình huống bằng AI |
| 15:15–15:30 | Giải lao     | Nghỉ ngơi                               |
| 15:30–16:30 | Thử thách AI | Sinh viên thực hiện thử thách theo nhóm |
| 16:30–17:00 | Tổng kết     | Chia sẻ kết quả, trao quà và bế mạc     |

**Kết quả mong đợi:**

- 150 sinh viên được tham gia sự kiện.
- Sinh viên hiểu những ứng dụng cơ bản của AI.
- Sinh viên trực tiếp trải nghiệm các công cụ AI.
- Sinh viên biết cách ứng dụng AI vào học tập và công việc.

## **4. Bảng dự toán ngân sách**

Nguyên tắc: Ưu tiên sử dụng cơ sở vật chất của trường, hạn chế chi phí không cần thiết và dành một khoản dự phòng.

| STT | Hạng mục                     | Chi phí dự kiến |
| --- | ---------------------------- | --------------- |
| 1   | Trang trí, backdrop sân khấu | 1.200.000đ      |
| 2   | Nước uống và đồ ăn nhẹ       | 5.250.000đ      |
| 3   | Hỗ trợ diễn giả              | 1.500.000đ      |
| 4   | Quà tặng và giải thưởng      | 1.000.000đ      |
| 5   | In ấn tài liệu, thẻ tên      | 450.000đ        |
| 6   | Truyền thông, quảng cáo      | 700.000đ        |
| 7   | Vật tư workshop              | 600.000đ        |
| 8   | Hậu cần và vận chuyển        | 800.000đ        |
| 9   | Dự phòng phát sinh           | 1.300.000đ      |
|     | **TỔNG CỘNG**                | **12.800.000đ** |

**Kiểm tra ngân sách**

Ngân sách tối đa

**15.000.000đ**

Ngân sách dự kiến

**12.800.000đ**

**Ngân sách còn lại**

# **2.200.000đ**

Sử dụng khoảng 85,33% ngân sách tối đa.

Đạt yêu cầu ngân sách

*Lưu ý: Đây là dự toán giả định để lập kế hoạch, cần xác nhận báo giá thực tế. Chi phí địa điểm và thiết bị được giả định do nhà trường hỗ trợ miễn phí. Khoản 2.200.000đ còn lại là phần ngân sách chưa phân bổ, không phải khoản chi bắt buộc.*

## **5. Bảng phân công nhiệm vụ cho 10 nhân sự**

| STT | Nhân sự    | Nhiệm vụ chính                           |
| --- | ---------- | ---------------------------------------- |
| 1   | Nhân sự 1  | Trưởng ban tổ chức, giám sát chung       |
| 2   | Nhân sự 2  | Phụ trách nội dung chương trình          |
| 3   | Nhân sự 3  | Liên hệ và hỗ trợ diễn giả               |
| 4   | Nhân sự 4  | Phụ trách truyền thông Facebook          |
| 5   | Nhân sự 5  | Phụ trách truyền thông TikTok            |
| 6   | Nhân sự 6  | Thiết kế poster, backdrop                |
| 7   | Nhân sự 7  | Quản lý đăng ký và check-in              |
| 8   | Nhân sự 8  | Phụ trách thiết bị, âm thanh, máy chiếu  |
| 9   | Nhân sự 9  | Phụ trách hậu cần, nước uống và vật tư   |
| 10  | Nhân sự 10 | Điều phối workshop, trò chơi và tổng kết |

**Nguyên tắc phối hợp:**

- Trưởng ban theo dõi tiến độ của tất cả bộ phận.
- Mỗi nhân sự có nhiệm vụ chính và người phối hợp rõ ràng.
- Các bộ phận trao đổi trước sự kiện để tránh trùng lặp công việc.
- Trong ngày diễn ra sự kiện, nhân sự 7 phụ trách check-in và sau đó có thể hỗ trợ điều phối; nhân sự 10 điều phối hoạt động trải nghiệm.

## **6. Kế hoạch truyền thông trước sự kiện**

**Thông điệp chính:**

"AI Innovation Day – Khám phá AI, trải nghiệm công nghệ, sáng tạo tương lai!"

**Đối tượng:** Sinh viên trong trường, đặc biệt là sinh viên quan tâm đến công nghệ và trí tuệ nhân tạo.

**Kênh truyền thông:** Facebook, TikTok, nhóm sinh viên và bảng tin của trường.

| Thời gian     | Nội dung                                 | Kênh                     | Người phụ trách |
| ------------- | ---------------------------------------- | ------------------------ | --------------- |
| Trước 14 ngày | Đăng poster giới thiệu sự kiện           | Facebook                 | Nhân sự 4, 6    |
| Trước 12 ngày | Video giới thiệu AI Innovation Day       | TikTok                   | Nhân sự 5       |
| Trước 10 ngày | Mở form đăng ký tham gia                 | Facebook                 | Nhân sự 4, 7    |
| Trước 7 ngày  | Giới thiệu nội dung workshop             | Facebook, TikTok         | Nhân sự 2, 5    |
| Trước 5 ngày  | Đăng thông tin diễn giả                  | Facebook                 | Nhân sự 3, 4    |
| Trước 3 ngày  | Video nhắc lịch và kêu gọi đăng ký       | TikTok                   | Nhân sự 5       |
| Trước 1 ngày  | Xác nhận đăng ký, gửi hướng dẫn tham gia | Facebook, nhóm sinh viên | Nhân sự 7       |

### **Nội dung quảng bá mẫu**

# AI INNOVATION DAY – KHÁM PHÁ THẾ GIỚI TRÍ TUỆ NHÂN TẠO!

Bạn đã bao giờ tò mò AI có thể giúp ích gì trong học tập và công việc chưa?

Hãy tham gia **AI Innovation Day** để:

- Tìm hiểu những kiến thức cơ bản về trí tuệ nhân tạo.
- Khám phá các ứng dụng AI trong học tập.
- Trực tiếp trải nghiệm các công cụ AI.
- Tham gia thử thách sáng tạo cùng bạn bè.

**Thông tin sự kiện:**

- Quy mô: 150 sinh viên.
- Thời gian: 1 ngày.
- Đối tượng: Sinh viên trong trường.

Số lượng tham gia có giới hạn. Hãy đăng ký ngay để cùng khám phá thế giới AI!

**AI Innovation Day – Học hỏi, trải nghiệm và sáng tạo!**

**Chỉ tiêu truyền thông:**

- Tiếp cận sinh viên qua các kênh truyền thông của trường.
- Thu hút tối thiểu 150 lượt đăng ký hợp lệ.
- Xác nhận người tham dự trước ngày tổ chức.
- Phấn đấu có đủ 150 sinh viên tham gia thực tế.

## **7. Context Management – Bản tóm tắt ngữ cảnh dự án**

Context Management giúp AI duy trì thông tin quan trọng khi cuộc hội thoại kéo dài hoặc chuyển sang một cuộc hội thoại mới.

### **7.1. Prompt tạo bản tóm tắt ngữ cảnh**

```
Bạn là trợ lý quản lý dự án sự kiện.

Hãy tổng hợp toàn bộ thông tin đã xây dựng
về sự kiện AI Innovation Day thành một bản
tóm tắt ngữ cảnh để tiếp tục làm việc
trong một cuộc hội thoại mới.

Bản tóm tắt phải bao gồm:

1. Tên và mục tiêu sự kiện.
2. Quy mô, thời gian, ngân sách và nhân sự.
3. Kết quả phân tích tính khả thi.
4. Lịch trình sự kiện.
5. Bảng dự toán ngân sách.
6. Phân công nhiệm vụ.
7. Kế hoạch truyền thông.
8. Những rủi ro cần chú ý.
9. Các vấn đề cần tiếp tục hoàn thiện.

Giữ nguyên các thông tin và ràng buộc ban đầu.
Trình bày ngắn gọn, dễ sử dụng lại.
```

### **7.2. Bản tóm tắt ngữ cảnh dự án**

# CONTEXT SUMMARY – AI INNOVATION DAY

## 1. Thông tin dự án

- Tên: AI Innovation Day.
- Đối tượng: Sinh viên trong trường.
- Quy mô: 150 sinh viên.
- Thời gian: 1 ngày.
- Ngân sách tối đa: 15.000.000 đồng.
- Nhân sự: 10 người.

## 2. Mục tiêu

Giúp sinh viên hiểu và trải nghiệm ứng dụng AI trong học tập và công việc.

## 3. Kết quả phân tích

Sự kiện có tính khả thi nếu sử dụng hội trường và thiết bị có sẵn của trường, đồng thời kiểm soát tốt chi phí.

## 4. Lịch trình

- 07:30–08:00: Đón tiếp.
- 08:00–09:45: Khai mạc và chuyên đề AI.
- 09:45–11:30: Giải lao và workshop.
- 11:30–13:00: Nghỉ trưa.
- 13:00–15:15: Chuyên đề và workshop.
- 15:15–17:00: Thử thách AI và tổng kết.

## 5. Ngân sách

- Tổng dự toán: 12.800.000 đồng.
- Ngân sách tối đa: 15.000.000 đồng.
- Ngân sách chưa phân bổ: 2.200.000 đồng.

## 6. Nhân sự

Có 10 người phụ trách: quản lý, nội dung, diễn giả, truyền thông, thiết kế, đăng ký, thiết bị, hậu cần và điều phối.

## 7. Truyền thông

Sử dụng Facebook, TikTok, nhóm sinh viên và bảng tin trường học.

Thông điệp: "AI Innovation Day – Khám phá AI, trải nghiệm công nghệ, sáng tạo tương lai!"

## 8. Rủi ro

- Vượt ngân sách.
- Thiếu thiết bị.
- Mất kết nối Internet.
- Diễn giả đến muộn.
- Số lượng sinh viên tham gia không đủ.

## 9. Ràng buộc bắt buộc

- Không vượt 15.000.000 đồng.
- Không thay đổi quy mô 150 sinh viên.
- Không thay đổi số lượng 10 nhân sự.
- Thời gian tổ chức 1 ngày.
- Các hạng mục phải thống nhất với nhau.

## 10. Công việc tiếp theo

Kiểm tra báo giá thực tế, xác nhận hội trường, thiết bị, diễn giả và hoàn thiện kế hoạch tổ chức.

## **8. Báo cáo kiểm tra và hiệu chỉnh kế hoạch**

### **8.1. Kết quả kiểm tra**

| Tiêu chí                  | Kết quả             | Đánh giá     |
| ------------------------- | ------------------- | ------------ |
| Ngân sách tối đa 15 triệu | Dự toán 12,8 triệu  | Đạt          |
| Quy mô 150 sinh viên      | Giữ nguyên 150      | Đạt          |
| Nhân sự 10 người          | Có đủ 10 người      | Đạt          |
| Thời gian 1 ngày          | 07:30–17:00         | Đạt          |
| Lịch trình                | Có đủ các hoạt động | Đạt          |
| Truyền thông              | Có kế hoạch 7 mốc   | Đạt          |
| Phân công nhiệm vụ        | Có người phụ trách  | Đạt          |
| Quản lý rủi ro            | Đã xác định rủi ro  | Đạt một phần |

### **8.2. Các vấn đề phát hiện và phương án hiệu chỉnh**

| Vấn đề                         | Phương án hiệu chỉnh                     |
| ------------------------------ | ---------------------------------------- |
| Chưa có địa điểm xác nhận      | Liên hệ nhà trường đặt hội trường        |
| Chưa xác nhận diễn giả         | Chuẩn bị diễn giả dự phòng               |
| Có nguy cơ mất Internet        | Chuẩn bị video và tài liệu offline       |
| Có thể thiếu người điều phối   | Phân công người hỗ trợ giữa các bộ phận  |
| Chưa chắc đủ 150 người tham dự | Gửi xác nhận và nhắc lịch trước sự kiện  |
| Chưa có báo giá chính thức     | Kiểm tra giá trước khi phê duyệt chi phí |

### **8.3. Kế hoạch sau hiệu chỉnh**

- Giữ nguyên quy mô 150 sinh viên.
- Giữ nguyên 10 nhân sự.
- Giữ nguyên thời gian tổ chức một ngày.
- Giữ nguyên ngân sách tối đa 15 triệu đồng.
- Duy trì dự toán 12,8 triệu đồng và chỉ sử dụng khoản ngân sách còn lại khi cần thiết.
- Bổ sung phương án dự phòng cho thiết bị, Internet và diễn giả.
- Theo dõi số lượng đăng ký và xác nhận người tham dự.
