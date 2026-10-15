# Thiết kế cách theo dõi góp ý và cải tiến qua ba Sprint (RikkeiAssist)

Người đề xuất: Thu Hà, Scrum Master. Cùng thống nhất với Scrum Team: Product Owner Minh Anh, Thu Hà và 5 Developers.

## Tóm tắt vấn đề từ dữ liệu Sprint 11–13

| Chỉ số | Sprint 11 | Sprint 12 | Sprint 13 |
|---|---|---|---|
| Góp ý ghi nhận | 12 | 15 | 18 |
| Đã hỏi rõ | 5 (42%) | 7 (47%) | 10 (56%) |
| Đã đưa vào xem xét Product Backlog | 3 (25%) | 6 (40%) | 5 (28%) |
| Improvement mới | 3 | 2 | 2 |
| Improvement còn mở cuối Sprint | 2 | 3 | 4 |

Nhận xét: mỗi Sprint có 7–8 góp ý chưa được hỏi rõ; Improvement còn mở tăng đều từ 2 lên 4 vì nhóm thêm cái mới nhưng chưa kiểm tra hoặc kết thúc cái cũ. Cách theo dõi bên dưới nhằm xử lý đúng hai chỗ này, không thêm cuộc họp mới.

## Nguyên tắc nền

- **Hai vòng, hai bảng riêng.** Góp ý sản phẩm (từ Sprint Review) vào Product Backlog; Improvement (từ Sprint Retrospective) được kiểm tra ở Retrospective sau. Hai sự kiện giữ nguyên mục tiêu, người tham gia, thời lượng; không gộp thành một cuộc họp.
- **Góp ý không tự động thành cam kết.** Improvement không phải chỉ tiêu cá nhân; bảng chỉ ghi hành động và người theo dõi, không ghi ai gây ra vấn đề, và không dùng để đánh giá cá nhân. Điều này giúp mọi người vẫn dám nói thẳng.
- **Chỉ nối thêm, không sửa hay xóa lịch sử.** Mỗi lần cập nhật là một dòng mới có ngày và người cập nhật.
- **Nhẹ.** Mỗi người cập nhật phần của mình trong lúc làm việc; Thu Hà chỉ nhắc, không quyết thay.

---

## Phần 1 – Chu trình

### Vòng A: góp ý, từ Sprint Review tới Product Backlog

```
[Sprint Review]
   │
   ▼
(A1) Ghi nhận góp ý ──► (A2) Làm rõ ──► (A3) PO xem xét cho Product Backlog
                                              │
                          ┌───────────────────┼──────────────────────┐
                          ▼                   ▼                      ▼
                 Đã liên kết PBI      Chưa đủ thông tin     Chưa làm / không làm
                 (xác nhận mã)        (đánh dấu, quay      (ghi lý do)
                          │            lại A2)                       │
                          └───────────────────┬──────────────────────┘
                                              ▼
                              (A4) Báo lại người góp ý ở
                                   Sprint Review kế tiếp
```

| Bước | Việc làm | Ai cập nhật |
|---|---|---|
| A1 | Ghi góp ý ngay trong Sprint Review: nguồn, nội dung giữ nguyên văn người góp ý, Sprint ghi nhận. | Thu Hà ghi |
| A2 | Hỏi lại những chỗ chưa rõ (ngưỡng, mục tiêu, rủi ro). Hạn làm rõ: trước Ngày 3 của Sprint kế tiếp. Chưa rõ thì đánh dấu "Chưa rõ" và ghi còn thiếu gì. | Minh Anh phụ trách; Developer liên quan hỗ trợ |
| A3 | Xem xét cho Product Backlog và ghi quyết định cùng lý do: đã liên kết PBI / chưa đủ thông tin / chưa làm hoặc không làm. | Minh Anh |
| A4 | Báo lại tình trạng cho người góp ý ở Sprint Review kế tiếp. | Minh Anh trình bày; Thu Hà ghi |

### Vòng B: Improvement, từ Sprint Retrospective tới lần kiểm tra ở Sprint sau

```
[Sprint Retrospective Sprint N]
   │
   ▼
(B1) Chọn Improvement ──► (B2) Thực hiện và ghi bằng chứng trong Sprint N+1
   (≤ 2 cái mới; ghi hành động,
    người theo dõi, ngày kiểm tra,
    bằng chứng mong đợi)
                                   │
                                   ▼
        [Sprint Retrospective Sprint N+1, đầu buổi: kiểm tra từng cái còn mở]
                                   │
        ┌──────────────────────────┼─────────────────────────┐
        ▼                          ▼                         ▼
   Đạt: đóng,              Chưa đạt: giữ mở,         Không còn phù hợp: dừng
   ghi bằng chứng          chỉnh cách làm,           bằng quyết định minh bạch
                           hẹn kiểm tra lại          của Scrum Team, ghi lý do
```

| Bước | Việc làm | Ai cập nhật |
|---|---|---|
| B1 | Scrum Team chọn tối đa 2 Improvement mới; ghi hành động, người/nhóm theo dõi (một đầu mối cụ thể), ngày kiểm tra, bằng chứng mong đợi. Nếu tổng Improvement còn mở đã đạt 3, phải kiểm tra, điều chỉnh hoặc dừng bớt trước khi mở thêm. | Scrum Team quyết định; Thu Hà ghi |
| B2 | Người theo dõi ghi bằng chứng vào bảng khi có (số liệu, ngày, kết quả). | Người/nhóm theo dõi |
| B3 | Kiểm tra từng Improvement mở trong 5 phút đầu Retrospective kế tiếp, so với bằng chứng đã hẹn. Kết quả là một trong ba trạng thái ở sơ đồ. | Scrum Team quyết định; Thu Hà điều phối và ghi |

### Chỗ hai vòng gặp nhau

Hai bảng chỉ liên hệ qua một lối: nếu Review phát hiện vấn đề cách làm, hoặc Retrospective phát hiện phản hồi sản phẩm, bản ghi được chuyển sang bảng tương ứng, không trộn trong cùng một bảng.

---

## Phần 2 – Bảng theo dõi

Hai bảng riêng. Mỗi dòng là một lần cập nhật (chỉ nối thêm). Dưới đây là mẫu điền cho F-11-04 và IM-11-02, chỉ dùng dữ liệu đề bài cung cấp; chỗ chưa có dữ liệu được ghi rõ để bổ sung, không bịa.

### Bảng 1: Góp ý (Feedback)

Cột: Mã | Nguồn | Sprint | Nội dung | Làm rõ | Còn thiếu | Quyết định của PO | Liên kết PBI | Đã báo lại nguồn | Người cập nhật

**Mẫu F-11-04**

| Sprint | Ghi nhận (nối thêm) | Làm rõ | Còn thiếu | Quyết định của PO | Liên kết PBI |
|---|---|---|---|---|---|
| 11 | Nguồn: Trưởng nhóm CSKH. Nội dung: "Chuyển người sớm hơn khi AI không chắc chắn". Ghi nhận ở Sprint Review. | Chưa rõ ngưỡng | Ngưỡng nào là "không chắc chắn"; trường hợp nào cần chuyển | Chưa có (chưa đủ thông tin) | Không có |
| 12 | Không có cập nhật nào được ghi, góp ý vẫn chưa xử lý. Áp dụng quy tắc mới: gắn cờ "quá hạn làm rõ" vì đã qua một Sprint; Minh Anh hẹn người góp ý làm rõ đầu Sprint 13. | Chưa rõ ngưỡng | Như trên | Chưa có | Không có |
| 13 | Xuất hiện F-13-05 (Nhân viên CSKH ca tối) có nội dung gần giống nhưng câu chữ khác. Ghi liên kết "có thể trùng với F-11-04", chưa gộp; hỏi hai người góp ý xác nhận. Đồng thời liên quan F-12-11 (xem Phần 3, tình huống 1). | Chưa rõ ngưỡng (2 nguồn, 2 Sprint) | Như trên, thêm: xác nhận trùng | Chưa có | Không có |

### Bảng 2: Improvement

Cột: Mã | Hành động | Người/nhóm theo dõi | Ngày kiểm tra | Bằng chứng mong đợi | Kết quả ghi nhận | Trạng thái | Quyết định của Scrum Team | Lần đầu xuất hiện (Sprint)

**Mẫu IM-11-02**

| Sprint | Kết quả ghi nhận (bằng chứng) | Trạng thái | Ghi chú / quyết định |
|---|---|---|---|
| 11 | Tạo ở Retrospective Sprint 11. Hành động: cấp đủ quyền môi trường thử nghiệm từ Ngày 1 và chạy Integration Test khi PBI đầu tiên sẵn sàng. Người theo dõi: Developers (đề xuất chỉ định một đầu mối). Bằng chứng mong đợi: ngày bắt đầu Integration Test đầu tiên. Mức nền: Ngày 8. | Mở | Hẹn kiểm tra ở Retrospective Sprint 12 |
| 12 | Integration Test đầu tiên: Ngày 7 (sớm hơn mức nền 1 ngày). Chưa có dữ liệu: ngày cấp quyền, ngày PBI đầu tiên sẵn sàng. | Mở | Ghi thêm hai chỉ số còn thiếu từ Sprint 14 |
| 13 | Integration Test đầu tiên: Ngày 8 (không cải thiện so với mức nền). | Mở (3 Sprint) | Đưa vào Retrospective Sprint 14 để xem lại (xem Phần 3, tình huống 3) |

---

## Phần 3 – Quy tắc xử lý

### Tình huống 1: Chủ cửa hàng muốn tăng tự động hóa; nhân viên CSKH muốn chuyển người sớm

- Ghi thành các góp ý riêng (F-12-11 và F-11-04/F-13-05), không chọn bên nào chỉ vì người góp ý.
- Mỗi góp ý ghi rõ mục tiêu và rủi ro/cái giá. F-12-11 hiện chưa ghi rủi ro, phải làm rõ "90%" của chỉ số nào và nếu tăng thì rủi ro là gì; F-11-04/F-13-05 phải làm rõ ngưỡng "không chắc chắn".
- Ghi liên kết "đánh đổi nhau" giữa các góp ý này. Minh Anh xem xét cùng lúc, Developers cho ý kiến khả thi, và quyết định kèm lý do được báo lại ở Sprint Review kế tiếp.
- Không góp ý nào tự thành cam kết cho đến khi PO quyết định đưa vào Product Backlog.

### Tình huống 2: Góp ý lặp với câu chữ khác; góp ý có PBI kèm dấu hỏi

- **Góp ý lặp (F-11-04 và F-13-05):** không gộp ngầm. Giữ nguyên cả hai bản ghi, thêm liên kết "có thể trùng", hỏi hai người góp ý xác nhận. Sau khi xác nhận mới chọn một mã chính, mã còn lại trỏ về và vẫn giữ lịch sử. Số nguồn và số Sprint xuất hiện được ghi lại để PO cân nhắc.
- **Liên kết có dấu hỏi (F-12-07, "PBI-52?"):** ghi là "Chưa xác nhận" và không tính vào số "đã đưa vào xem xét Product Backlog". Trong buổi Refinement kế tiếp, Minh Anh cùng một Developer mở PBI-52 đối chiếu nội dung với góp ý. Đúng thì xác nhận; sai thì bỏ liên kết (ghi lý do) hoặc tạo PBI mới.

### Tình huống 3: Báo "đã tiếp nhận" khi chưa làm rõ; đóng Improvement quá một Sprint

- **Báo cáo góp ý:** "Đã tiếp nhận" chỉ nghĩa là đã ghi. Báo cáo theo trạng thái thật: Mới ghi / Đang làm rõ / Đã làm rõ / Đã xem xét (có quyết định và lý do) / Đã liên kết PBI / Không làm (có lý do). Số "đã hỏi rõ" luôn được báo riêng.
- **Đóng Improvement:** không đóng chỉ vì tuổi hay để bảng gọn. Chỉ đóng khi (1) có bằng chứng đạt mục tiêu, hoặc (2) Scrum Team quyết định dừng minh bạch ở Retrospective vì không còn phù hợp, kèm lý do, hoặc (3) được thay bằng Improvement khác, có ghi liên kết. Lịch sử luôn được giữ.

**Áp dụng cho từng Improvement:**

| Mã | Tình trạng | Quyết định đề xuất cho Retrospective Sprint 14 |
|---|---|---|
| IM-11-02 | Mở 3 Sprint; Integration Test đầu tiên Ngày 8, 7, 8, chưa cải thiện. | **Giữ mở nhưng chỉnh lại, không đóng vì tuổi.** Vấn đề vẫn còn nên chưa thể đóng; nhưng vì ba Sprint không đổi, cách làm cũng cần đổi: chỉ định một đầu mối cụ thể thay vì "Developers", bổ sung hai chỉ số (ngày cấp quyền, ngày PBI đầu tiên sẵn sàng), hỏi "vì sao" ở Retrospective, và đặt mục tiêu bằng ngày cụ thể. |
| IM-12-04 | Bằng chứng: kênh không còn dùng. | **Dừng vì không còn phù hợp.** Gia Huy xác nhận kênh đã ngừng thí điểm; Scrum Team quyết định dừng công khai, ghi lý do và bằng chứng. Không xóa dòng. |
| IM-13-03 | Đã kiểm tra một lần: hai phiên Pairing, thời gian tái hiện giảm. | **Giữ mở đến lần kiểm tra thứ hai.** Bằng chứng hiện chỉ nói "giảm"; ghi số cụ thể (thời gian tái hiện mỗi phiên so với trước). Nếu mức giảm giữ được ở lần hai thì đóng vì đạt. |

### Tiêu chí đo được sau 3 Sprint tới (Sprint 14–16)

**Đến hết Sprint 16, có ít nhất 2 Improvement được đóng vì đạt mục tiêu, mỗi cái có bằng chứng số đo so với mức nền Sprint 11–13.** Ví dụ: Integration Test đầu tiên bắt đầu không muộn hơn Ngày 5 ở 2 Sprint liên tiếp, so với Ngày 7–8 hiện nay. Ngưỡng Ngày 5 chỉ là đề xuất để nhóm xác nhận ở Retrospective Sprint 14, vì hiện chưa có dữ liệu ngày PBI đầu tiên sẵn sàng.

Tiêu chí này chỉ đạt khi công việc thật thay đổi, không đạt chỉ vì các buổi họp diễn ra đúng lịch hay vì bảng gọn hơn do đóng bớt.
