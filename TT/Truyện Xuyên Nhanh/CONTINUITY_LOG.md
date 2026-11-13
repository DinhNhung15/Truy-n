## 2026-11-13 – Chốt lại quyền chuyển nhượng Vé Về Nhà (SYS-010)

**Tài liệu cập nhật:**
- `TT/Truyện Xuyên Nhanh/SYSTEM_BIBLE.md` – v1.20 → v1.21
- `TT/Truyện Xuyên Nhanh/SYS/SYS-010.md`

### Quyết định canon
- Vé mua cho bản thân có giá 1 tỷ điểm, là vé cá nhân gắn cố định với người mua ban đầu. Chỉ người mua ban đầu được kích hoạt; vé không thể cho, tặng, bán, trao đổi, chuyển giao hoặc chuyển quyền sử dụng. Nếu bị cướp/chiếm đoạt, người chiếm giữ không có quyền kích hoạt.
- Vé mua để trao cho người khác có giá 10 tỷ điểm, là vé chuyển nhượng. Người mua không cần chỉ định trước người nhận.
- Vé chuyển nhượng được cho, tặng, bán, trao đổi hoặc chuyển giao không giới hạn số lần; việc bị cướp/chiếm đoạt cũng không làm mất quyền kích hoạt của người đang nắm giữ.
- Người nhận, được cho, tặng, mua lại hoặc cướp/chiếm đoạt vé chuyển nhượng không phải trả thêm phí khi sử dụng. Giá 10 tỷ là toàn bộ chi phí; không có khoản chênh lệch 9 tỷ, phí chuyển nhượng hay phí kích hoạt.
- Không thể mua vé cá nhân 1 tỷ rồi trả thêm để đổi thành vé chuyển nhượng 10 tỷ. Loại vé được xác định tại thời điểm mua.
- Quy tắc cũ cho phép trả thêm 9 tỷ để đổi vé cá nhân thành vé vô danh đã bị thay thế hoàn toàn.

### Trạng thái
- SYS-010 và SYSTEM_BIBLE Mục 7.3 đã được đồng bộ theo quyết định mới.
- SYSTEM_BIBLE nâng lên v1.21.
- Đây là quy tắc canon thay thế toàn bộ cơ chế vé cá nhân/ vé vô danh và khoản chênh lệch 9 tỷ của v1.20.

---

## 2026-11-13 – Chốt toàn bộ vấn đề còn mở của SYS-007, SYS-010 và thất bại cuối cùng

**Tài liệu cập nhật:**
- `TT/Truyện Xuyên Nhanh/SYSTEM_BIBLE.md` – v1.19 → v1.20
- `TT/Truyện Xuyên Nhanh/SYS/SYS-007.md`
- `TT/Truyện Xuyên Nhanh/SYS/SYS-010.md`

### SYS-007 – Tính phí khi nhiều hệ số thay đổi
- Chốt cách tính lại toàn bộ chi phí khi một hoặc nhiều hệ số E₀, Kp, Kt, Ks thay đổi đồng thời: E_mới = E₀_mới × Kp_mới × Kt_mới × Ks_mới.
- Chi phí tăng thêm bằng max(0, E_mới − E_đã_tính); chỉ thu phần vượt mức cao nhất đã tính cho cùng hiệu ứng/giai đoạn. Không cộng cơ học các chênh lệch riêng lẻ, không hoàn năng lượng khi chi phí giảm.
- Mỗi hiệu ứng độc lập hoặc giai đoạn hiệu ứng có sổ chi phí riêng.

### SYS-007 – Hiệu ứng thay đổi bản chất theo thời gian
- Khi bản chất tác động thay đổi, chia hiệu ứng thành các giai đoạn liên tiếp và tính riêng từng giai đoạn.
- Các đặc tính đồng thời của cùng hiệu ứng trong một giai đoạn vẫn áp dụng Ks cao nhất; thay đổi phạm vi/thời lượng nhưng không đổi bản chất không tự tạo giai đoạn mới.
- Kt căn cứ thời lượng cam kết duy trì giai đoạn; kéo dài làm tăng bậc Kt thì chỉ thu phần chênh vượt mức đã tính; kết thúc sớm không hoàn năng lượng.

### SYS-007 – Ranh giới Kp
- Nhóm nhỏ 2–10 người có liên hệ thực tế/chức năng: Kp 2.
- Nhóm thống nhất trên 10 người, chỉ bị tác động trực tiếp với tư cách thành viên nhóm: Kp 5, không phụ thuộc phân bố một hay nhiều thành phố.
- Kp 5 địa lý áp dụng cho một vùng địa phương nhỏ hơn thành phố; Kp 10 áp dụng khi hiệu ứng vận hành ở quy mô thành phố hoặc trải trên từ hai thành phố trở lên.
- Không gom các mục tiêu độc lập thành nhóm chỉ vì cùng xuất hiện trong một danh sách/lần kích hoạt; không chia cơ học một nhóm thống nhất để hạ Kp.

### Nhiệm vụ thất bại cuối cùng
- Bổ sung Mục 6.6 để phân biệt lượt ký chủ thất bại với nhiệm vụ kết thúc thất bại.
- Chốt các căn cứ: hết thời hạn bắt buộc trong khế ước; mục tiêu bất khả thi khách quan; thế giới nhiệm vụ không còn khả năng tiếp cận; hoặc điều kiện thất bại riêng đã ghi rõ trong khế ước xảy ra.
- Cục Điều Phối có thẩm quyền quyết định cuối cùng. Trong thời gian xác minh, nhiệm vụ tạm dừng phân phối; nếu không đủ căn cứ thì trả lại kho.
- Khi thất bại cuối cùng, nhiệm vụ đóng vĩnh viễn; phần quỹ 20% chưa sử dụng trở về kho chung và linh hồn người ủy thác chấm dứt sau quyết toán. Vi phạm của người ủy thác vẫn được xử lý riêng, không tự động quyết định kết quả nhiệm vụ.

### SYS-010 – Phân biệt vé 1 tỷ và 10 tỷ
- Vé 1 tỷ là vé cá nhân, gắn với người mua ban đầu; người mua có thể kích hoạt mà không trả thêm.
- Người khác đang giữ vé cá nhân muốn kích hoạt phải trả phần chênh 9 tỷ; có thể trả trước để chuyển vé thành vé vô danh.
- Vé mua 10 tỷ là vé vô danh, người giữ hợp lệ có thể kích hoạt mà không cần trả thêm.
- Khoản chênh 9 tỷ chỉ thu một lần cho mỗi vé; sau khi vé thành vé vô danh, chuyển giao nhiều lần không phát sinh thêm phí.
- Giữ nguyên khả năng trao tay không giới hạn, không cần chỉ định người nhận trước và không yêu cầu chứng minh nguồn gốc nhận vé.

### Trạng thái
- Ba nhóm vấn đề được ghi nhận trong danh sách vấn đề chưa chốt đã có quyết định và được cập nhật đồng bộ vào tài liệu chuyên biệt cùng SYSTEM_BIBLE.md v1.20.
- Các quy tắc đã chốt trước đó được giữ nguyên; không thay đổi công thức E₀, Kp, Kt, Ks nền tảng, giá vé hoặc các quy tắc thất bại cá nhân.

---

## 2026-11-11 – Chốt phân cấp 16 thế giới nhiệm vụ

**Tài liệu cập nhật:**
- `TT/Truyện Xuyên Nhanh/THẾ GIỚI/WORLD_INDEX.md`
- `TT/Truyện Xuyên Nhanh/THẾ GIỚI/MISSION_CLASSIFICATION.md`

### Nội dung đã chốt
- Chốt danh mục 16 thế giới và cấp nhiệm vụ theo hồ sơ thiết kế: D (2), C (2), B (3), A (5), S (3), SS (1).
- Chốt 5 mức liên quan Tổng bộ: M0 (10 thế giới), M1 (3), M2 (1), M3 (1), M4 (1).
- Mức liên quan Tổng bộ là nhãn quản lý tuyến bí mật cốt truyện, độc lập với cấp nhiệm vụ SYS-002.
- Giữ nguyên thứ tự và mã WORLD_001–WORLD_016; số thứ tự hồ sơ không đồng nghĩa số nhiệm vụ cá nhân.
- Ghi rõ điểm thành phần và điểm tổng SYS-002 chưa được chấm cho các thế giới chưa có hồ sơ nhiệm vụ chi tiết; không tự tạo điểm số. Cấp đã chốt hiện là cấp thiết kế của hồ sơ, sẽ được đối chiếu khi nhiệm vụ cụ thể hoàn thiện.

### Trạng thái
- WORLD_INDEX.md được cập nhật thành danh mục 16 thế giới.
- Tạo MISSION_CLASSIFICATION.md làm hồ sơ quản lý cấp nhiệm vụ và mức độ liên quan Tổng bộ.
- Không thay đổi SYSTEM_BIBLE.md hoặc các quy tắc SYS-002.
- Không tự tạo hồ sơ chi tiết WORLD_003–WORLD_016 trong lần cập nhật này.

---

## 2026-11-11 – SYSTEM_BIBLE.md v1.12

**Tài liệu cập nhật:** `TT/Truyện Xuyên Nhanh/SYSTEM_BIBLE.md`  
**Phiên bản:** 1.11 → 1.12  
**Phạm vi:** Cơ chế năng lượng hợp đồng, linh hồn người ủy thác và ngoại lệ giá vé SYS-015.

### Người ủy thác – phân chia năng lượng và sự tồn tại của linh hồn
- Chốt người ủy thác không chuyển hóa toàn bộ thành năng lượng sau khi ký hợp đồng; linh hồn vẫn tồn tại trong thế giới nhiệm vụ.
- 80% tổng năng lượng hợp đồng được chuyển hóa và đưa vào kho năng lượng chung của Tổng bộ ngay sau khi ký.
- Linh hồn người ủy thác giữ 20% năng lượng hợp đồng để duy trì sự tồn tại và quan sát nhiệm vụ.
- Khi nhiệm vụ thực sự hoàn thành, người ủy thác tự quyết định dùng bao nhiêu trong 20% năng lượng còn lại để thưởng điểm cho ký chủ; không có mức tối thiểu/tối đa cố định. Phần dư được chuyển hóa về kho chung của Tổng bộ.
- Thất bại ở một lượt ký chủ không làm nhiệm vụ kết thúc; nhiệm vụ quay lại kho để phân phối tiếp và 20% năng lượng còn lại tiếp tục do linh hồn người ủy thác giữ cho đến khi nhiệm vụ hoàn thành.
- Nếu Tổng bộ hủy nhiệm vụ do hành vi phá hoại đã xác minh, phần 20% chưa thanh toán bị thu hồi; 80% đã thanh toán trước vẫn thuộc Tổng bộ và linh hồn người ủy thác bị tiêu diệt.
- Khoản thưởng tự nguyện thêm điểm cho ký chủ và/hoặc năng lượng cho hệ thống đồng hành được xác định là khoản riêng, không lấy từ 20% năng lượng hợp đồng đang giữ để quan sát; có thể trao kể cả khi nhiệm vụ thất bại.

### SYS-015 – Ngoại lệ giá vé
- Giữ giá 10 tỷ điểm/vé như đã chốt.
- Làm rõ giá SYS-015 là giá cố định cho mỗi vé, không phân biệt ký chủ mua để tự sử dụng hay chỉ định người khác làm người nhận.
- Đây là ngoại lệ riêng về giá so với SYS-010; các cơ chế chung khác vẫn kế thừa theo quy định đã ghi.

### Trạng thái
- Các nội dung trên đã được cập nhật vào SYSTEM_BIBLE.md v1.12 và các quy tắc tổng hợp liên quan.
- Các nội dung canon khác được giữ nguyên.

---

## 2026-11-11 – SYSTEM_BIBLE.md v1.11

**Tài liệu cập nhật:** `TT/Truyện Xuyên Nhanh/SYSTEM_BIBLE.md`  
**Phiên bản:** 1.10 → 1.11  
**Phạm vi:** SYS-003, SYS-009, SYS-015 và quy tắc người ủy thác/linh hồn/hợp đồng.

### SYS-003 – Tiện ích mở khóa theo cấp ký chủ
- Chốt bốn mốc tiện ích: F–E, D–C, B–A và S–SS.
- F–E: hồ sơ ký chủ, sổ tay nhiệm vụ, ghi chú cá nhân, quản lý kho đồ và lịch sử giao dịch.
- D–C: thống kê/phân tích cá nhân, so sánh vật phẩm/kỹ năng, quản lý và chuẩn bị nhiệm vụ, mở rộng/phân khu/tìm kiếm kho, lưu bộ trang bị, mở rộng sổ tay và tiện ích theo dõi giao dịch.
- B–A: phân tích nhiệm vụ, mô phỏng tình huống, quản lý tài nguyên nâng cao, mở rộng kho nâng cao, bộ hồ sơ nhiệm vụ, tra cứu chéo và quản lý giao dịch nâng cao.
- S–SS: cá nhân hóa giao diện/bảng điều khiển, quản lý kho cao cấp, phân tích chuyên sâu, quản lý tài nguyên/giao dịch và tự động hóa thao tác.
- Chốt nguyên tắc mở khóa tính năng không đồng nghĩa nâng cấp miễn phí; các tiện ích không cấp quyền hành chính hoặc truy cập bí mật, không dự đoán tương lai và chỉ xử lý dữ liệu ký chủ có quyền tiếp cận.

### SYS-009 – Giỏ hàng tham chiếu và tương thích thế giới
- Mở rộng giỏ hàng tham chiếu thành 7 nhóm: nhu yếu phẩm; sinh hoạt; y tế; công cụ/vật liệu; vũ khí/trang bị; hàng hóa đặc thù; dịch vụ.
- Chốt cơ cấu và trọng số giỏ hàng thay đổi theo từng thế giới, dựa trên nền kinh tế, mức độ phổ biến, tính thiết yếu và sức mua thực tế.
- Hệ thống nghiệp vụ tự thu thập dữ liệu, phân tích và tính trọng số; Tổng bộ kiểm tra/phê duyệt khi biến động lớn hoặc dữ liệu bất thường.
- Chốt cập nhật định kỳ 3 tháng/lần và cập nhật đột xuất khi có biến động kinh tế lớn; không cập nhật chỉ vì vài mặt hàng biến động ngắn hạn.
- Hàng hóa có sản phẩm tương đương được đối chiếu theo công dụng; hàng hóa không có tương đương được ghi nhận thành nhóm đặc thù.
- Khi thiếu thị trường hoặc dữ liệu đáng tin cậy, Tổng bộ tự định giá dựa trên công dụng, độ khan hiếm, mức độ phổ biến, giá trị sử dụng và điều kiện kinh tế; có thể đối chiếu thế giới khác. Ký chủ chỉ xem giá quy đổi cuối cùng và tỷ giá, không xem công thức hay dữ liệu kinh tế nội bộ.
- Chốt nguyên tắc tương thích thế giới: hệ thống kiểm tra và thông báo trước khi dùng; tùy vật phẩm có thể hoạt động bình thường, bị hạn chế, chuyển trạng thái tương thích nếu cơ chế cho phép hoặc vô hiệu hóa công năng không tương thích. Không thay đổi quy luật nền tảng của thế giới.

### SYS-015 – Vé quay lại thế giới nhiệm vụ đã hoàn thành
- Chốt giá 10 tỷ điểm/vé; bán trực tiếp trong cửa hàng hệ thống; không giới hạn số lượng mua nếu đủ điểm và điều kiện; mỗi vé dùng một lần.
- Ký chủ được chọn thời điểm quay lại sau khi thế giới nhiệm vụ đã hoàn thành.
- Các quy tắc mua, lưu trữ, chỉ định người nhận, kích hoạt và xử lý khi người nhận tử vong kế thừa SYS-010; đích đến là thế giới nhiệm vụ đã hoàn thành thay vì thế giới thực.
- Kích hoạt khi đang làm nhiệm vụ bắt buộc được xử lý sau khi nhiệm vụ hiện tại có kết quả; nếu thất bại phải xử lý hình phạt và còn sống mới được quay lại.
- Giữ hai lựa chọn thân phận cũ/thân phận mới và quyền ở lại đã chốt trước đó.

### Người ủy thác – linh hồn, hợp đồng và quyền quan sát
- Chốt thanh toán trước 80% năng lượng hợp đồng; phần còn lại do người ủy thác tự chọn tỷ lệ, không có mức tối thiểu/tối đa cố định và chỉ thanh toán khi nhiệm vụ hoàn thành.
- Thất bại của một ký chủ chỉ kết thúc lượt thực hiện; nhiệm vụ trở lại kho để phân phối tiếp cho ký chủ khác cho đến khi hoàn thành. Phần năng lượng còn lại tiếp tục chờ, không bị xem là thất bại cuối cùng.
- Người ủy thác quan sát nhiệm vụ như khán giả theo thời gian thực; không giao tiếp với ký chủ, không tương tác vật lý, không tua lại/xem lại. Có thể tạm dừng và tiếp tục quan sát; thời gian bỏ lỡ không thể xem lại.
- Cảnh thân mật, sinh hoạt cá nhân riêng tư, thay quần áo và vệ sinh cá nhân được che khuất; không mở rộng tự động sang các cuộc trò chuyện riêng tư.
- Người ủy thác không được sử dụng năng lượng linh hồn hoặc phương thức bất thường để can thiệp vào thế giới vì mục đích cá nhân; việc không hợp tác/không cung cấp thông tin tự nó không phải phá hoại.
- Tổng bộ giám sát năng lượng linh hồn; khi có dấu hiệu bất thường thì xác minh nguồn và hành vi. Chỉ kết luận phá hoại khi có căn cứ về hành vi can thiệp trái phép, không chỉ dựa vào hiện tượng lạ.
- Nếu phá hoại được xác minh: hủy hợp đồng và nhiệm vụ; ký chủ nhận 50% điểm thưởng cơ bản, EXP theo công việc thực tế; người ủy thác bị cưỡng chế tiêu diệt, linh hồn biến mất; năng lượng chưa thanh toán bị thu hồi, 80% đã trả trước vẫn thuộc Tổng bộ.
- Sau khi ký hợp đồng, người ủy thác không thể đơn phương rút/hủy; ngoại lệ là Tổng bộ hủy do phá hoại đã xác minh.
- Người ủy thác có thể tự nguyện thưởng thêm điểm cho ký chủ và năng lượng cho hệ thống đồng hành; không có mức thưởng cố định, chuyển trực tiếp vào tài khoản tương ứng, độc lập với phần thưởng nhiệm vụ và có thể trao dù nhiệm vụ thất bại.

### Trạng thái
- SYS-003, SYS-009 ở phạm vi nguyên tắc đã thống nhất, SYS-015 và quy tắc người ủy thác vừa cập nhật được ghi nhận trong SYSTEM_BIBLE.md v1.11.
- Không bổ sung các công thức, ngưỡng hoặc cơ chế kỹ thuật mà tác giả chưa yêu cầu; nội dung chi tiết chỉ được mở rộng khi cần cho cốt truyện.
- Các nội dung canon trước đó được giữ nguyên, trừ những chỗ cập nhật trạng thái và chi tiết được nêu trong mục này.

---

## 2026-11-11 – SYSTEM_BIBLE.md v1.10

**Tài liệu cập nhật:** `TT/Truyện Xuyên Nhanh/SYSTEM_BIBLE.md`  
**Phiên bản:** 1.9 → 1.10  
**Phạm vi:** SYS-001, SYS-003, SYS-007, SYS-009, SYS-013, SYS-014 và SYS-015.

### SYS-001 – Nguồn gốc Tổng bộ Nguyện Vọng
- Chốt Tổng bộ Nguyện Vọng đã tồn tại từ rất lâu và hình thành tự nhiên từ năng lượng ước nguyện.
- Không có cá nhân hay thực thể sáng lập.
- Tổng bộ chỉ là tổ chức có cơ cấu, quy tắc và các đơn vị vận hành; không xây dựng thêm ý thức tập thể hoặc lịch sử nguồn gốc sâu hơn.

### SYS-003 – Quyền hạn ký chủ
- Chia quyền hạn thành quyền mặc định áp dụng cho mọi ký chủ và quyền tiện ích/chức năng hỗ trợ được mở khóa theo cấp.
- Quyền mở khóa không bao gồm quyền quản lý, điều hành, khiếu nại hoặc can thiệp vào hoạt động nội bộ Tổng bộ.
- Cấp ký chủ không đồng nghĩa với quyền lực hành chính.

### SYS-007 – Chi phí can thiệp
- Chốt hệ thống chọn tỷ lệ cụ thể trong khoảng phí theo đánh giá tổng thể ba yếu tố: độ phức tạp, thời gian thực hiện và phạm vi tác động.
- Không dùng công thức cứng chung cho mọi trường hợp.
- Mỗi lần can thiệp phải lưu căn cứ xác định tỷ lệ để có thể kiểm tra.

### SYS-009 – Tỷ giá quy đổi sang S
- Chốt giỏ hàng tham chiếu gồm nhu yếu phẩm, dịch vụ phổ biến và chi phí sinh hoạt cơ bản.
- Hệ thống so sánh tổng giá trị giỏ hàng giữa các thế giới để xác định tỷ giá theo sức mua thực tế.
- Giỏ hàng được cập nhật định kỳ hoặc khi sức mua biến động đáng kể.
- Tỷ giá được khóa tại thời điểm giao dịch; không điều chỉnh hồi tố.

### SYS-011 – Quan hệ thời gian và quy tắc trở về
- Làm rõ không cần đặt thêm tỷ lệ quy đổi thời gian thực–nhiệm vụ cho cơ chế vé Về Nhà: vé đưa ký chủ về đúng thời điểm ngay trước tai nạn, với thân thể khỏe mạnh, an toàn và lành lặn.
- Giữ nguyên quy tắc thời gian Tổng bộ và thế giới nhiệm vụ đồng bộ 1:1 đã có.

### SYS-013 – Mất ký chủ hoặc hệ thống bị phá hủy
- Ký chủ tử vong: hệ thống mất liên kết, có thể trở về Tổng bộ và tiếp tục tìm ký chủ mới.
- Hệ thống bị phá hủy nhưng ký chủ còn sống: ký chủ vẫn làm nhiệm vụ; Tổng bộ phân công hệ thống mới.
- Hệ thống cũ có thể được khôi phục từ dữ liệu sao lưu bằng điểm; chi phí bằng giá vé Về Nhà dành cho chính ký chủ (hiện là 1 tỷ điểm).
- Chỉ ký chủ từng liên kết mới có quyền đổi điểm khôi phục. Không khôi phục thì hệ thống cũ biến mất vĩnh viễn.
- Dữ liệu sao lưu có ký ức và tình cảm; mức độ khôi phục phụ thuộc mức độ lưu trữ.

### SYS-014 – Kho năng lượng chung
- Chốt Tổng bộ có một kho năng lượng chung, phân phối năng lượng cho các đơn vị trực thuộc; không có nguồn độc lập tách rời cho từng đơn vị.

### SYS-015 – Vé quay lại thế giới nhiệm vụ đã hoàn thành
- Ký chủ tự chọn thời điểm quay lại.
- Có thể chọn thân phận cũ và giữ toàn bộ ký ức, trải nghiệm, quan hệ đã hình thành; hoặc chọn thân phận mới hoàn toàn, tồn tại hợp pháp và không kế thừa cuộc đời nhân vật cũ.
- Sau khi quay lại, ký chủ có thể tiếp tục ở lại thế giới đó nếu muốn.
- Giá vé, nguồn nhận, giới hạn số lần và giới hạn can thiệp khác chưa được quyết định.

### Trạng thái
- Các quy tắc đã xác nhận được cập nhật vào SYSTEM_BIBLE.md v1.10.
- SYS-001, SYS-003, SYS-007, SYS-013 và SYS-014 được chuyển khỏi danh sách chưa chốt.
- SYS-009 chỉ còn các chi tiết kỹ thuật sâu hơn của giỏ hàng tham chiếu nếu cần.
- SYS-015 chỉ còn các chi tiết giá, nguồn nhận vé và giới hạn sử dụng khác nếu cần.
- SYS-011 không còn là một vấn đề độc lập cần đặt tỷ lệ thời gian cho cơ chế trở về; quy tắc neo thời điểm trở về vào trước tai nạn được giữ trong SYS-010.

---

## 2026-11-11 – SYSTEM_BIBLE.md v1.9

**Tài liệu cập nhật:** `TT/Truyện Xuyên Nhanh/SYSTEM_BIBLE.md`  
**Phiên bản:** 1.8 → 1.9  
**Phạm vi:** SYS-002, SYS-009, SYS-010 và các quy tắc tổng hợp liên quan.

### SYS-002 – Đánh giá và phân cấp nhiệm vụ
- Chốt danh mục 7 loại nhiệm vụ: Điều tra, Sinh tồn, Cứu viện, Bảo vệ, Tranh đấu, Thu thập và Can thiệp.
- Chốt hệ số cho 5 tiêu chí của từng loại nhiệm vụ; hệ số được nhân với trọng số cơ bản rồi chuẩn hóa về tổng 100%.
- Chốt cách tổng hợp hệ số của nhiệm vụ đa loại theo tỷ trọng bản chất/mục tiêu nhiệm vụ.
- Bổ sung các trường hợp nguy hiểm đặc biệt có thể làm căn cứ độc lập để nâng cấp nhiệm vụ; thông tin chưa xác minh hoặc đối tượng chỉ đơn thuần chưa phân loại không tự động làm tăng cấp.

### SYS-009 – Kỹ năng, cửa hàng và giao dịch
- Chốt quy tắc mỗi kỹ năng có cấp tối đa, bảng giá, điều kiện nâng cấp và cấp ký chủ tối thiểu riêng; không có bảng cấp kỹ năng chung.
- Chốt giới hạn cấp ký chủ là điều kiện bắt buộc khi mua/nâng cấp.
- Chốt danh sách kỹ năng ngẫu nhiên được tạo một lần khi nhiệm vụ bắt đầu, cố định trong nhiệm vụ và không thể làm mới bằng điểm.
- Ký chủ được nâng cấp kỹ năng vĩnh viễn đã sở hữu trong nhiệm vụ dù kỹ năng không xuất hiện trong danh sách ngẫu nhiên, nếu đáp ứng đủ điều kiện và điểm.
- Chốt phân biệt kỹ năng dùng trong một nhiệm vụ và kỹ năng vĩnh viễn; quy tắc hết hạn, bảo lưu khi thất bại, mất khi tử vong, không hoàn điểm và không chuyển nhượng.
- Chốt điểm chỉ được chuyển như khoản thanh toán trong giao dịch mua bán chính thức qua chợ do hệ thống ghi nhận. Không tặng, cho vay, góp, gộp hoặc chuyển điểm trực tiếp.
- Trao đổi trực tiếp không được dùng điểm làm phương thức thanh toán.
- Chốt phương pháp xác định tỷ giá dựa trên giỏ hàng hóa/dịch vụ tham chiếu và sức mua thực tế; công thức định lượng cụ thể vẫn là nội dung cần hoàn thiện.

### SYS-010 – Vé Về Nhà và dấu ấn sau khi trở về
- Vé gắn cố định với người nhận được chỉ định; không thể đổi người nhận. Nếu người nhận tử vong trước khi kích hoạt, vé mất hiệu lực, không hoàn điểm và không thể chuyển cho người khác.
- Kích hoạt vé trong thế giới nhiệm vụ đưa vé vào trạng thái chờ trở về, không lập tức đưa ký chủ về hiện thực.
- Vé được xử lý sau khi nhiệm vụ bắt buộc hiện tại kết thúc: thành công thì trở về ngay, không cần hoàn thành nhiệm vụ tự chọn; thất bại thì xử lý hình phạt trước, chỉ trở về nếu ký chủ còn sống. Vé không cứu người tử vong do hình phạt.
- Ký chủ trở về thời điểm ngay trước tai nạn, thân thể khỏe mạnh, an toàn và lành lặn, kèm khoản tiền thưởng hợp pháp.
- Tất cả ký chủ trở về giữ ký ức hành trình dưới dạng mơ hồ như giấc mơ. Cảm giác thân thuộc khi gặp lại người từng quen phụ thuộc mức độ cảm xúc và gắn kết, không bảo đảm nhận ra ngay.
- Ký chủ giữ lại thay đổi về tính cách, tư duy, thói quen, phản xạ, kiến thức và kỹ năng tương thích với thế giới thực; có thể biết và làm được mà không nhớ rõ nguồn gốc.
- Năng lực siêu nhiên không tương thích với quy luật thế giới thực không thể sử dụng sau khi trở về.

### Trạng thái
- Các nội dung trên đã được cập nhật vào SYSTEM_BIBLE.md v1.9.
- SYS-010 về vé Về Nhà và bảo lưu sau khi trở về được chuyển khỏi danh sách vấn đề chưa chốt.
- SYS-007 vẫn còn phần tiêu chí định lượng chi phí can thiệp cần hoàn thiện.


## 2026-11-11 – SYSTEM_BIBLE.md v1.13

**Tài liệu cập nhật:** `TT/Truyện Xuyên Nhanh/SYSTEM_BIBLE.md`  
**Phiên bản:** 1.12 → 1.13  
**Phạm vi:** Hoàn thiện các điểm lệch được rà soát; đồng bộ quy tắc nhiệm vụ, hệ thống thay thế/khôi phục và cơ chế linh hồn người ủy thác.

### Nhiệm vụ bắt buộc và nhiệm vụ tự chọn
- Chốt mỗi ký chủ phải có một nhiệm vụ bắt buộc; không được chỉ tham gia nhiệm vụ tự chọn mà không có nhiệm vụ bắt buộc.
- Trong thời gian thực hiện nhiệm vụ bắt buộc, ký chủ có thể nhận thêm nhiệm vụ tự chọn nếu đáp ứng điều kiện.
- Bổ sung nguyên tắc này vào Mục 5.1, phạm vi Mục 16 và quy tắc nhanh.

### Thất bại và hủy nhiệm vụ
- Làm rõ thất bại của một lượt ký chủ chỉ khiến nhiệm vụ trở lại kho để tiếp tục phân phối; không đồng nghĩa nhiệm vụ bị hủy.
- Ngoại lệ: nhiệm vụ bị Tổng bộ hủy khi hành vi phá hoại của người ủy thác được xác minh theo Mục 21.5.

### Khế ước và thế giới nhiệm vụ
- Chốt thế giới nhiệm vụ được xác định ngay tại thời điểm ký khế ước.
- Bổ sung vào trình tự ký kết và chuyển hóa năng lượng.

### Hệ thống mới và hệ thống cũ được khôi phục
- Hệ thống mới tiếp quản là cá thể độc lập, chỉ nhận dữ liệu nghiệp vụ cần thiết; không nhận ký ức, cảm xúc hoặc nhân cách của hệ thống cũ.
- Khôi phục từ bản sao lưu là khôi phục chính cá thể hệ thống cũ, tùy mức độ dữ liệu còn lại.
- Hai cá thể không ghi đè, xóa hoặc thay thế dữ liệu tồn tại của nhau.

### Người ủy thác – sửa đổi cơ chế 20% năng lượng
- Giữ nguyên tỷ lệ 80% chuyển vào kho chung ngay khi ký khế ước và 20% do linh hồn người ủy thác nắm giữ.
- Chốt 20% là nguồn duy nhất để người ủy thác tự nguyện đổi thành điểm thưởng cho ký chủ; không tồn tại khoản thưởng riêng nằm ngoài 20%.
- Người ủy thác có thể phân bổ một phần hoặc toàn bộ 20% để thưởng trong quá trình nhiệm vụ, kể cả khi một lượt ký chủ chưa hoàn thành hoặc đã thất bại.
- Khi một lượt ký chủ thất bại, phần 20% chưa sử dụng vẫn do linh hồn nắm giữ; nhiệm vụ trở lại kho để phân phối tiếp.
- Khi nhiệm vụ thực sự hoàn thành, phần 20% chưa sử dụng chuyển về Tổng bộ và linh hồn người ủy thác tan biến.
- Nếu nhiệm vụ bị hủy do phá hoại đã xác minh, phần 20% chưa sử dụng bị thu hồi; linh hồn bị cưỡng chế tiêu diệt.
- Mục 21.6 được đổi từ “phần thưởng tự nguyện độc lập” thành “phân bổ phần thưởng từ 20% năng lượng hợp đồng”. Các mô tả cũ tại nhật ký v1.11 và v1.12 về khoản thưởng độc lập ngoài 20% đã bị thay thế bởi quyết định này.

### Quyền cung cấp thông tin và giới hạn can thiệp
- Người ủy thác không có nghĩa vụ cung cấp toàn bộ thông tin; có thể im lặng, không hợp tác hoặc che giấu thông tin trước khi ký khế ước.
- Việc không cung cấp hoặc cung cấp thông tin không đầy đủ tự thân không bị xem là phá hoại; mục tiêu và điều kiện có hiệu lực là nội dung đã xác nhận trong khế ước.
- Người ủy thác không thể giao tiếp với ký chủ hoặc nhân vật trong thế giới nhiệm vụ.
- Phá hoại chỉ được kết luận khi có căn cứ về hành vi dùng năng lượng linh hồn hoặc phương thức bất thường để can thiệp trái phép; hiện tượng bất thường đơn thuần không đủ.

### Các điểm đã rà soát và đồng bộ
- Quy tắc nhanh 94–97 được sửa theo cơ chế hợp đồng mới.
- Mục 6.5 bổ sung ngoại lệ hủy nhiệm vụ do phá hoại đã xác minh.
- Các nội dung chưa được tác giả quyết định vẫn được giữ ở trạng thái chưa chốt, không tự suy diễn.
- Bổ sung tệp `SYSTEM_CHARACTER_BIBLE.md` làm nơi lưu các nguyên tắc đã xác nhận về ba hệ thống đồng hành; chi tiết riêng của từng hệ thống tiếp tục để trống cho đến khi tác giả quyết định.

### Trạng thái
- Các cập nhật trên đã được ghi vào `SYSTEM_BIBLE.md` v1.13.
- Những mô tả cũ trái với các quyết định mới trong nhật ký phiên bản trước không còn được áp dụng.


### Bổ sung kiểm tra nhất quán trong v1.13
- Đồng bộ phần tổng quan Mục 1.2, nguyên tắc khế ước Mục 3.3 và quy tắc nhanh Mục 12 với quyền phân bổ 20% năng lượng kể cả khi một lượt ký chủ thất bại.
- Ghi nhận một điểm chưa chốt để không tự suy diễn: nếu người ủy thác đã phân bổ hết 20% làm phần thưởng trước khi nhiệm vụ thực sự hoàn thành, trạng thái tồn tại của linh hồn trong khoảng thời gian còn lại chưa được xác định.


## 2026-11-11 – Bổ sung quy tắc linh hồn khi đã dùng hết 20% năng lượng

- Chốt: Nếu người ủy thác đã phân bổ toàn bộ 20% năng lượng hợp đồng làm phần thưởng trước khi nhiệm vụ thực sự hoàn thành, linh hồn vẫn tiếp tục tồn tại và theo dõi nhiệm vụ bình thường.
- Việc linh hồn tiếp tục tồn tại và quan sát không phụ thuộc vào lượng năng lượng 20% còn lại.
- Khi 20% đã dùng hết, người ủy thác không còn năng lượng để phân bổ thêm phần thưởng; tuy nhiên vẫn giữ quyền quan sát cho đến khi nhiệm vụ thực sự hoàn thành hoặc bị hủy theo quy định.
- Khi nhiệm vụ hoàn thành, linh hồn tan biến theo quy tắc đã chốt. Nếu nhiệm vụ bị hủy do phá hoại đã xác minh, áp dụng chế tài tại Mục 21.5.
- Điểm chưa chốt trước đó về trạng thái linh hồn khi 20% đã dùng hết được đóng lại.
- Đã đồng bộ Mục 21.1 và 21.2 trong `SYSTEM_BIBLE.md`; không thay đổi tỷ lệ 80%/20% hoặc cơ chế thưởng.


## 2026-11-11 – Tổ chức hồ sơ thế giới nhiệm vụ

**Tài liệu mới:**
- `TT/Truyện Xuyên Nhanh/THẾ GIỚI/WORLD_INDEX.md`
- `TT/Truyện Xuyên Nhanh/THẾ GIỚI/WORLD_001.md`
- `TT/Truyện Xuyên Nhanh/THẾ GIỚI/WORLD_002.md`

### Quy tắc đánh số
- Mỗi thế giới có mã hồ sơ riêng `WORLD_XXX`; số mã là thứ tự hồ sơ trong dự án.
- Số nhiệm vụ của vợ, chồng và con được tính độc lập; không suy ra số nhiệm vụ của người này từ người khác.
- Thời điểm bắt đầu và tổng thời lượng trải qua nhiệm vụ của từng thành viên có thể khác nhau.
- Giữ quy tắc SYSTEM_BIBLE về thời gian tại Tổng bộ và thế giới nhiệm vụ đồng bộ 1:1; không diễn giải thành yêu cầu mọi thành viên phải bắt đầu cùng lúc hoặc trải qua cùng thời lượng.

### WORLD_001
- Ghi nhận đây là nhiệm vụ thứ nhất của người vợ.
- Chưa có đủ dữ kiện về bối cảnh, thân phận, nhiệm vụ và diễn biến; tạo hồ sơ khung chờ tác giả bổ sung.
- Không tự bịa nội dung để lấp chỗ trống.

### WORLD_002 – Kinh Thành Dưới Màn Mưa
- Ghi nhận đây là nhiệm vụ thứ hai của người vợ và nhiệm vụ thứ tám của người chồng; hành trình của con độc lập.
- Đây là thế giới đoàn tụ đầu tiên của vợ chồng; chồng nhận ra vợ trước, vợ ban đầu chưa nhận ra chồng.
- Sau khi xác nhận riêng tư, hai người chủ động giả vờ bất hòa trước mặt người ngoài.
- Tách hai tuyến nhiệm vụ điều tra quân lương và cái chết của Trần Bá; mỗi người phải có kết quả điều tra riêng.
- Lưu bối cảnh, phương án thân phận, cơ chế thất thoát, nhân vật, chứng cứ, timeline, khung 16 chương và nguyên tắc nhất quán trong hồ sơ WORLD_002.
- Tên riêng, số liệu, ngày tháng và một số chi tiết trong hồ sơ được đánh dấu là phương án làm việc/chờ xác nhận, không tự động nâng thành canon.

### Trạng thái
- Đã tạo mục lục và hai hồ sơ thế giới riêng trên nhánh `main`.
- Không thay đổi SYSTEM_BIBLE hoặc CHARACTER_BIBLE trong lần cập nhật này.


## 2026-11-12 – Bổ sung hai thế giới và cập nhật tuổi của con

**Tài liệu cập nhật:**
- `TT/Truyện Xuyên Nhanh/CHARACTER_BIBLE.md`
- `TT/Truyện Xuyên Nhanh/THẾ GIỚI/WORLD_INDEX.md`
- `TT/Truyện Xuyên Nhanh/THẾ GIỚI/MISSION_CLASSIFICATION.md`

### Tuổi của con
- Cập nhật tuổi canon của con trai từ 3 tuổi lên **4,5 tuổi** trong CHARACTER_BIBLE.md.
- Khi xây dựng lời thoại, hành vi và năng lực nhận thức, giữ đúng đặc điểm của trẻ 4,5 tuổi; không viết bé như người trưởng thành thu nhỏ.
- Tuổi thân phận ở từng thế giới nhiệm vụ vẫn cần ghi riêng nếu khác tuổi canon; không tự suy ra tuổi tại mọi vị diện.

### Bổ sung và sắp xếp thế giới
- Bổ sung **WORLD_017 – Bố Và Con Đồng Hành**, nhân vật tham gia: bố và con. Vị diện này đặt sau WORLD_008 (mẹ báo cho bố biết đã tìm thấy con) và trước WORLD_010 (tuyến mẹ-con), tạo cuộc gặp riêng của bố và con.
- Bổ sung **WORLD_018 – Tinh Hải Cơ Giáp**, cả gia đình tham gia. Đây là thế giới cơ giáp nơi gia đình thể hiện năng lực và sự phối hợp khiến người khác ngưỡng mộ; nhiệm vụ ban đầu đơn giản nhưng có biến cố gần cuối để tạo cao trào. Không biến nội dung thành cuộc thi sức mạnh đơn thuần hoặc một vị diện chỉ nghỉ ngơi.
- Giữ nguyên mã hồ sơ của 16 thế giới đã có. Thứ tự trong WORLD_INDEX thể hiện trình tự cốt truyện dự kiến, không bắt buộc mã hồ sơ tăng liên tục.
- WORLD_018 đặt sau WORLD_014 và trước WORLD_015–016 trong mạch truyện.
- Chưa tự gán cấp nhiệm vụ hoặc mức liên quan Tổng bộ cho WORLD_017 và WORLD_018; chờ xây dựng nhiệm vụ cụ thể và quyết định của tác giả.

### Trạng thái
- Danh mục được mở rộng từ 16 lên 18 thế giới.
- Cập nhật tuổi canon của con lên 4,5 tuổi.
- Không thay đổi SYSTEM_BIBLE.md hoặc các quy tắc hệ thống.
- Chưa tạo hồ sơ chi tiết riêng cho WORLD_017 và WORLD_018.


## 2026-11-12 – SYSTEM_BIBLE.md v1.14 và tách hồ sơ SYS

**Tài liệu cập nhật:**
- `TT/Truyện Xuyên Nhanh/SYSTEM_BIBLE.md`
- `TT/Truyện Xuyên Nhanh/SYS/README.md`
- `TT/Truyện Xuyên Nhanh/SYS/SYS-002.md`
- `TT/Truyện Xuyên Nhanh/SYS/SYS-007.md`
- `TT/Truyện Xuyên Nhanh/SYS/SYS-009.md`
- `TT/Truyện Xuyên Nhanh/SYS/SYS-010.md`

### SYS-002 – Đánh giá và phân cấp nhiệm vụ
- Thay bảng trọng số chung và bộ hệ số cũ bằng trọng số trực tiếp theo tám loại nhiệm vụ: Điều tra, Sinh tồn, Cứu viện, Bảo vệ, Tranh đấu, Hộ tống, Thu thập và Phát triển.
- Chốt trọng số theo năm tiêu chí cho từng loại; mỗi hàng có tổng 100%.
- Nhiệm vụ đa loại: loại chủ đạo 70%; các loại phụ chia đều 30%.
- Giữ thang điểm 1–5, định nghĩa năm tiêu chí và ngưỡng F–SS; làm rõ ngưỡng cấp là ngưỡng chung, không tự điều chỉnh theo loại nhiệm vụ.
- Làm rõ quy trình tăng/hạ cấp: thông thường phải báo cáo và được Tổng bộ/Cục Điều Phối phê duyệt; trường hợp khẩn cấp đủ điều kiện có thể tự động tăng một cấp rồi gửi xác minh. Mỗi lần đánh giá lại tối đa một cấp; có thể đánh giá lại tiếp khi xuất hiện dữ liệu mới.
- Điều kiện tăng cấp tập trung vào nguy hiểm mới chưa được tính đến, mức nguy hiểm thực tế tăng đáng kể và tác động rõ đến khả năng hoàn thành hoặc nguy cơ tử vong. Hạ cấp dựa trên bằng chứng cho thấy đánh giá ban đầu cao hơn đáng kể so với thực tế.
- Chuẩn hóa thông báo: “Xác nhận có bất thường. Tăng cấp nhiệm vụ.” / “Xác nhận có bất thường. Hạ cấp nhiệm vụ.”

### SYS-007 – Năng lượng và chi phí can thiệp
- Bổ sung công thức chi phí: E = E₀ × Kp × Kt × Ks.
- Chốt E₀ theo bốn cấp độ: Nhẹ 1 NL, Trung bình 3 NL, Cao 10 NL, Đặc biệt 30 NL.
- Chốt hệ số phạm vi Kp: cá nhân 1; nhóm nhỏ 2; khu vực 5; thành phố 10; quốc gia 30; toàn thế giới 100; nhiều thế giới 300.
- Chốt hệ số thời gian Kt: dưới 1 phút 1; 1–10 phút 2; 10–60 phút 5; 1–24 giờ 10; 1–7 ngày 30; trên 7 ngày 100.
- Chốt hệ số thay đổi thực tại Ks: chỉ thông tin/nhận thức 1; thay đổi nhỏ dễ đảo ngược 2; thay đổi cục bộ có ý nghĩa 5; thay đổi lớn/kéo dài 10; thay đổi quy luật/cấu trúc 30; can thiệp quy luật nền tảng 100.
- Làm rõ chi phí tính theo hiệu ứng thực sự tiêu hao năng lượng; hiệu ứng độc lập tính riêng, hệ quả kỹ thuật tất yếu không tính lặp; nhiều hệ thống chia chi phí theo mức đóng góp.
- Giữ các quy tắc dung lượng, duy trì, lương, sập, hạ cấp, đóng băng và khôi phục đã có.

### SYS-009 – Điểm và chợ giao dịch
- Giữ nguyên nguyên tắc điểm là tài sản cá nhân; không tặng, cho vay, góp, gộp hoặc chuyển trực tiếp.
- Điểm chỉ được chuyển giữa ký chủ như khoản thanh toán cho giao dịch mua bán thực tế qua chợ do hệ thống ghi nhận.
- Chợ hỗ trợ đối giá bằng điểm tích lũy, tiền tệ thế giới hoặc vật phẩm; hệ thống định giá theo S và thực hiện chuyển giao theo thỏa thuận đã ghi nhận.
- Phí 5% do người bán chịu, khấu trừ trước khi người bán nhận thanh toán; người mua không chịu thêm phí 5%.
- Trao đổi trực tiếp vẫn chỉ dùng tiền thật, vật phẩm, hình thức kết hợp hoặc trao tay miễn phí; không dùng điểm, không chịu phí chợ và không có thời gian chờ.
- Giữ các quy tắc kiểm định, tỷ giá theo sức mua thực tế, kỹ năng và cửa hàng đã xác nhận.

### SYS-010 – Vé Về Nhà
- Giá mua cho bản thân: 1 tỷ điểm; mua để chuyển cho người khác: 10 tỷ điểm.
- Không chỉ định người nhận tại thời điểm mua; vé được trao tay vật lý và có thể chuyển qua nhiều người, không giới hạn số lần.
- Vé không có thời hạn, không thừa kế; người đang giữ vé hợp lệ có quyền kích hoạt.
- Báo mất/báo trộm không tự động khóa vé; hệ thống không yêu cầu người kích hoạt chứng minh nguồn gốc nhận vé.
- Nếu người giữ vé tử vong trước khi kích hoạt, vé mất hiệu lực. Người giữ có quyền từ chối kích hoạt; không có cơ chế cưỡng ép.
- Giữ nguyên cơ chế chờ trở về sau khi nhiệm vụ bắt buộc có kết quả và các điều kiện trở về đã xác nhận.

### Người ủy thác – khế ước và chế tài
- Chọn phương án B: người ủy thác phải khai báo trung thực thông tin trọng yếu mình biết có thể ảnh hưởng đáng kể đến mục tiêu, điều kiện hoàn thành, nguy cơ hoặc trở ngại của nhiệm vụ. Không bắt buộc cung cấp mọi thông tin riêng tư hoặc không liên quan.
- Cố ý che giấu thông tin trọng yếu thuộc Cấp 1 – Che giấu; thông tin sai lệch do nhầm lẫn thuộc Cấp 0 – Sai lệch.
- Chốt bốn cấp vi phạm: Cấp 0 – Sai lệch; Cấp 1 – Che giấu; Cấp 2 – Gây khó dễ; Cấp 3 – Phá hoại.
- Chế tài tăng theo cấp nhưng phải căn cứ hành vi, mức độ cố ý và hậu quả thực tế. Không có tỷ lệ khấu trừ cố định; không cấp nào tự động dẫn đến tiêu diệt toàn bộ linh hồn.
- Thay cơ chế cũ “hủy hợp đồng + ký chủ nhận 50% điểm + tiêu diệt linh hồn” bằng chế tài theo bốn cấp; vi phạm không tự động hủy nhiệm vụ hoặc thay đổi kết quả/quyền lợi của ký chủ.
- Quỹ 20% là một nguồn thưởng hợp nhất, người ủy thác chọn phân bổ thành điểm cho ký chủ và/hoặc năng lượng cho hệ thống đồng hành. Có thể đổi lựa chọn trước quyết toán; chi trả sau khi ký chủ rời thế giới nhiệm vụ và Tổng bộ xác minh kết quả.
- Bổ sung báo cáo quyết toán cho ký chủ sau xác minh: cấp nhiệm vụ, kết quả, điểm, tiền thưởng, năng lượng hệ thống, vật phẩm, các khoản khấu trừ/hủy và lý do. Nhiệm vụ thất bại vẫn phải có báo cáo; không chi thưởng hoàn thành từ quỹ 20%.

### Các điểm còn mở
- Cách khấu trừ phí 5% khi đối giá là vật phẩm không thể chia nhỏ chưa được xác định.
- Tỷ lệ quy đổi cụ thể giữa điểm thưởng cho ký chủ và năng lượng thưởng cho hệ thống đồng hành trong quỹ 20% chưa được xác định.

### Trạng thái
- Đã cập nhật SYSTEM_BIBLE.md lên v1.14.
- Đã tạo thư mục SYS với bốn tài liệu chuyên biệt và README.
- Các quy tắc cũ mâu thuẫn đã được thay thế trong bản tổng hợp; SYSTEM_BIBLE.md là nguồn canon ưu tiên.

## 2026-11-12 – SYSTEM_BIBLE.md v1.15: chốt phí vật phẩm nguyên vẹn và tỷ lệ quy đổi quỹ 20%

**Tài liệu cập nhật:**
- `TT/Truyện Xuyên Nhanh/SYSTEM_BIBLE.md`
- `TT/Truyện Xuyên Nhanh/SYS/SYS-007.md`
- `TT/Truyện Xuyên Nhanh/SYS/SYS-009.md`

### SYS-009 – Phí giao dịch khi người bán nhận vật phẩm không thể chia nhỏ
- Chốt: vật phẩm được chuyển giao nguyên vẹn theo thỏa thuận; không chia nhỏ, phá hủy hoặc thay thế vật phẩm để thu phí.
- Phí 5% vẫn do người bán chịu; nếu đối giá là vật phẩm không thể chia nhỏ, hệ thống khấu trừ khoản phí quy đổi thành điểm từ tài khoản điểm cá nhân của người bán.
- Người mua không chịu thêm phí.
- Điểm còn mở: cách xử lý nếu tài khoản điểm của người bán không đủ để khấu trừ toàn bộ phí. Không tự suy diễn cho phép âm điểm, treo giao dịch hay từ chối giao dịch.

### Quỹ thưởng 20% của người ủy thác
- Người dùng xác nhận tỷ lệ quy đổi cố định **100 điểm = 1 NL**.
- Quỹ 20% tiếp tục là một nguồn thưởng hợp nhất; người ủy thác có thể phân bổ thành điểm cho ký chủ và/hoặc năng lượng cho hệ thống đồng hành.
- Tổng giá trị phân bổ không vượt quá năng lượng còn lại trong quỹ; người ủy thác được thay đổi phương án trước khi quyết toán, sau quyết toán thì phương án được khóa.
- Tỷ lệ 100 điểm = 1 NL chỉ áp dụng cho việc phân bổ quỹ 20% này; không áp dụng cho giao dịch chợ, cửa hàng hoặc cơ chế quy đổi thông thường khác.
- Năng lượng thưởng do Tổng bộ cấp từ nhiệm vụ chính/nhiệm vụ phụ vẫn là khoản riêng, không nhập chung với quỹ 20%.

### Trạng thái
- Cập nhật `SYSTEM_BIBLE.md` từ v1.14 lên **v1.15**.
- Đồng bộ quy tắc phí vật phẩm nguyên vẹn vào SYS-009 và tỷ lệ quy đổi quỹ thưởng vào SYS-007.
- Điểm chưa chốt duy nhất phát sinh trong lần cập nhật này: xử lý giao dịch khi người bán không đủ điểm để trả phí 5% trong trường hợp nhận vật phẩm không thể chia nhỏ.



## 2026-11-12 – Chốt thu phí trước khi đăng bán trên chợ (SYSTEM_BIBLE.md v1.16)

**Tài liệu cập nhật:**
- `TT/Truyện Xuyên Nhanh/SYSTEM_BIBLE.md`
- `TT/Truyện Xuyên Nhanh/SYS/SYS-009.md`

### Quy tắc phí đăng bán
- Phí chợ 5% được xác định theo giá trị niêm yết quy đổi theo S và do người bán chịu.
- Người bán thanh toán phí bằng điểm từ tài khoản cá nhân; hệ thống khấu trừ thành công trước khi vật phẩm được đưa lên kệ.
- Phí đã thu không hoàn lại, kể cả khi người bán gỡ hàng hoặc không bán được.
- Tin đăng đang hoạt động không được chỉnh sửa giá hoặc thông tin niêm yết; người bán được gỡ hàng xuống.
- Nếu đăng lại cùng vật phẩm với giá khác, đó là lượt đăng bán mới và phải nộp phí 5% mới theo giá mới.
- Không thu thêm phí khi giao dịch hoàn tất; người mua thanh toán theo giá niêm yết và không chịu thêm phí 5%.
- Quy tắc này thay thế cách thu phí trước đây là khấu trừ khi người bán nhận đối giá, bao gồm cả cơ chế riêng xử lý phí bằng điểm khi đối giá là vật phẩm không thể chia nhỏ. Không cần chia nhỏ hoặc can thiệp vào vật phẩm để thu phí vì phí đã được thu trước khi đăng.
- Điểm còn mở: cách xử lý khi người bán không đủ điểm để thanh toán phí đăng bán trước khi đưa hàng lên kệ. Không tự suy diễn cho phép âm điểm, cho nợ phí, giữ tin chờ hay từ chối đăng bán.

### Trạng thái
- Cập nhật `SYSTEM_BIBLE.md` từ v1.15 lên **v1.16**.
- Đồng bộ toàn bộ cơ chế phí đăng bán trong `SYS-009.md`.
- Các mô tả lịch sử về thu phí khi quyết toán giao dịch được giữ lại trong nhật ký để truy vết, nhưng không còn là quy tắc hiện hành.


## 2026-11-12 – Chốt xử lý khi người bán không đủ điểm trả phí đăng bán (SYSTEM_BIBLE.md v1.17)

**Tài liệu cập nhật:**
- `TT/Truyện Xuyên Nhanh/SYSTEM_BIBLE.md`
- `TT/Truyện Xuyên Nhanh/SYS/SYS-009.md`

### Quy tắc người bán không đủ điểm
- Người bán phải có đủ điểm trong tài khoản cá nhân để thanh toán toàn bộ phí đăng bán 5% trước khi vật phẩm được đưa lên kệ.
- Nếu số dư không đủ, hệ thống từ chối đăng bán; không tạo tin đăng và không đưa vật phẩm vào trạng thái chờ.
- Không cho phép âm điểm, ghi nợ hoặc đăng bán trước rồi thu phí sau.

### Trạng thái
- Cập nhật `SYSTEM_BIBLE.md` từ v1.16 lên **v1.17**.
- Đồng bộ quy tắc vào tài liệu chuyên biệt `SYS-009.md`.
- Điểm chưa chốt về điều kiện không đủ phí đăng bán đã được đóng.


## 2026-11-12 – Dọn lỗi đồng bộ tài liệu (SYSTEM_BIBLE.md v1.17)

**Tài liệu cập nhật:**
- `TT/Truyện Xuyên Nhanh/SYSTEM_BIBLE.md`
- `TT/Truyện Xuyên Nhanh/SYS/SYS-002.md`
- `TT/Truyện Xuyên Nhanh/SYS/SYS-007.md`
- `TT/Truyện Xuyên Nhanh/SYS/SYS-009.md`
- `TT/Truyện Xuyên Nhanh/SYS/SYS-010.md`
- `TT/Truyện Xuyên Nhanh/THẾ GIỚI/MISSION_CLASSIFICATION.md`

### Nội dung chỉnh sửa
- Sửa metadata đầu `SYSTEM_BIBLE.md` từ v1.16 thành v1.17, thống nhất với phiên bản ở cuối tài liệu và nhật ký quyết định.
- Cập nhật thông tin đồng bộ của `SYS-002.md`, `SYS-007.md` và `SYS-010.md` theo `SYSTEM_BIBLE.md` v1.17.
- Đổi tiêu đề mục 6 trong `SYS-009.md` vì quy tắc người bán không đủ điểm trả phí đăng bán đã được chốt, không còn là điểm chưa quy định.
- Xóa bảng trọng số chung cũ khỏi `MISSION_CLASSIFICATION.md`; thay bằng nguyên tắc dẫn chiếu bộ trọng số theo tám loại nhiệm vụ và cơ chế nhiệm vụ đa loại trong SYS-002.

### Phạm vi
- Đây là đợt sửa metadata và đồng bộ tham chiếu; không thay đổi cấp nhiệm vụ đã chốt, công thức SYS-002, quy tắc năng lượng SYS-007, giá vé SYS-010 hoặc bất kỳ quyết định canon nào khác.


## 2026-11-12 – Sửa các đoạn tài liệu lệch theo canon mới nhất

**Tài liệu cập nhật:**
- `TT/Truyện Xuyên Nhanh/SYSTEM_BIBLE.md`
- `TT/Truyện Xuyên Nhanh/CONTINUITY_LOG.md`

### Nội dung chỉnh sửa
- Mục 1.2: bỏ cách diễn đạt có thể khiến người đọc hiểu rằng vi phạm của người ủy thác tự dẫn đến hủy nhiệm vụ; thay bằng nguyên tắc xử lý theo Mục 21.5, không tự động hủy nhiệm vụ hoặc thay đổi kết quả/quyền lợi ký chủ.
- Mục 9.5: thay bảng phân biệt cửa hàng/chợ cũ, không còn phản ánh đầy đủ phương thức đối giá và cơ chế phí đăng bán hiện hành, bằng phần dẫn chiếu thống nhất với Mục 9.2.
- Mục 13: loại bỏ hai ghi chú đã được chốt ở v1.15 và v1.17; ghi nhận lại các điểm còn mở đã được nhận diện, không tự quyết định thay tác giả.
- CONTINUITY_LOG: bỏ tiêu đề tài liệu bị lặp giữa nhật ký; giữ nguyên các bản ghi lịch sử và thứ tự thời gian.

### Phạm vi
- Đây là đợt chỉnh sửa lỗi tài liệu và tham chiếu theo các quyết định canon mới nhất; không thay đổi quy tắc nghiệp vụ đã chốt, không tự quyết định các điểm còn mở.

## 2026-11-12 – Đồng bộ quyết định mới về Kp, Kt và Ks trong SYS-007 (SYSTEM_BIBLE.md v1.18)

**Tài liệu cập nhật:**
- TT/Truyện Xuyên Nhanh/SYS/SYS-007.md
- TT/Truyện Xuyên Nhanh/SYSTEM_BIBLE.md
- TT/Truyện Xuyên Nhanh/CONTINUITY_LOG.md

### Kt – Thời gian duy trì
- Thay các khoảng thời gian cũ có điểm biên chồng lấn bằng các khoảng không giao nhau: dưới 1 phút = 1; từ 1 đến dưới 10 phút = 2; từ 10 đến dưới 60 phút = 5; từ 60 phút đến dưới 24 giờ = 10; từ 24 giờ đến hết 7 ngày = 30; trên 7 ngày = 100.
- Xác nhận đúng 24 giờ thuộc Kt 30 và đúng 7 ngày vẫn thuộc Kt 30.

### Kp – Phạm vi tác động
- Giữ nguyên các hệ số: cá nhân 1; nhóm nhỏ 2; khu vực 5; thành phố 10; quốc gia 30; toàn thế giới 100; nhiều thế giới 300.
- Bổ sung tiêu chí phạm vi thực tế; định nghĩa nhóm nhỏ 2–10 đối tượng có liên hệ thực tế/chức năng và cùng chịu hiệu ứng chung; không gom nhóm chỉ vì cùng nằm trong một lệnh/danh sách.
- Nhóm trên 10 chỉ được chia nếu các nhóm thực sự độc lập; hiệu ứng tác động trên toàn khu vực dùng Kp khu vực dù số người hưởng lợi trực tiếp ít.
- Hiệu ứng độc lập tính riêng; các bước kỹ thuật của cùng hiệu ứng không tách riêng.
- Khi phạm vi mở rộng, chỉ tính phần chi phí tăng thêm; nếu chỉ Kp thay đổi: ΔE = E₀ × Kt × Ks × (Kp_mới − Kp_cũ). Thu hẹp phạm vi không tự động hoàn năng lượng; mở rộng nhiều lần chỉ thu phần vượt mức chi phí cao nhất đã tính/thu.
- Giữ mở hai vấn đề: nhóm thống nhất trên 10 thành viên phân bố nhiều thành phố; ranh giới khu vực/thành phố và phạm vi địa lý rời rạc.

### Ks – Mức độ thay đổi thực tại
- Thay bảng phân loại cũ bằng tiêu chí dựa trên bản chất/cơ chế thực tế: Ks 1 thông tin/nhận thức/ký ức; Ks 2 điều chỉnh trạng thái nhỏ; Ks 5 khôi phục/điều chỉnh chức năng trong cơ chế vốn có; Ks 10 thay đổi cấu trúc/cơ chế đối tượng hoặc tạo hiệu ứng mới bằng cơ chế riêng; Ks 30 thiết lập quy tắc dị thường trong phạm vi thực tại; Ks 100 trực tiếp sửa đổi/tạo ngoại lệ đối với định luật nền tảng.
- Ghi rõ các ví dụ đã chốt: xóa/sửa ký ức Ks 1; chữa lành hoàn toàn cơ thể Ks 5; tạo vật chất/năng lượng bằng cơ chế riêng Ks 10; dịch chuyển vật thể bằng năng lực riêng Ks 10; áp đặt quy tắc giảm trọng lực trong khu vực Ks 30; ngoại lệ nhân quả trong phòng, ngoại lệ định luật chuyển động trên một xe và ngoại lệ bảo toàn năng lượng tại máy phát điện Ks 100.
- Phân biệt mô phỏng biểu hiện bằng cơ chế riêng với việc thực sự áp đặt quy tắc hoặc can thiệp định luật.
- Một hiệu ứng thống nhất lấy Ks cao nhất mà hiệu ứng thực sự đạt tới; hiệu ứng độc lập tính riêng. Ks độc lập Kp/Kt; thời gian ngắn, khả năng đảo ngược hoặc tầm quan trọng đối với cá nhân không tự làm giảm/tăng Ks.

### Các điểm chưa chốt được giữ nguyên hoặc làm rõ
- E₀: tiêu chí chọn cấp khi mức can thiệp nằm giữa hai cấp.
- Kp: nhóm thống nhất trên 10 thành viên phân bố ở nhiều thành phố; ranh giới khu vực/thành phố và phạm vi địa lý rời rạc.
- Tương tác khi nhiều hệ số thay đổi đồng thời; cách phân loại hiệu ứng khi bản chất/mức tác động thay đổi trong thời gian tồn tại.
- Các điểm mở khác tại Mục 13, gồm điều kiện nhiệm vụ kết thúc thất bại và lỗ hổng giá vé SYS-010, không bị thay đổi.

### Phạm vi
- Cập nhật SYSTEM_BIBLE.md từ v1.17 lên v1.18.
- Đồng bộ nội dung SYS-007 theo nguồn quy tắc tại SYSTEM_BIBLE Mục 15.
- Không thay đổi E₀, công thức chi phí tổng thể, quy tắc sập/khôi phục hoặc tự quyết định các vấn đề còn mở.


## 2026-11-13 – Chốt tiêu chí phân loại E₀ trong SYS-007 (SYSTEM_BIBLE.md v1.19)

**Tài liệu cập nhật:**
- `TT/Truyện Xuyên Nhanh/SYS/SYS-007.md`
- `TT/Truyện Xuyên Nhanh/SYSTEM_BIBLE.md`
- `TT/Truyện Xuyên Nhanh/CONTINUITY_LOG.md`

### E₀ – Cấp độ can thiệp
- Chốt thước đo chính: phạm vi trạng thái hoặc cấu trúc mà hệ thống thực sự can thiệp bên trong từng mục tiêu.
- Nhẹ – 1 NL: can thiệp vào một trạng thái hoặc bộ phận cục bộ, phạm vi cấu trúc hạn chế.
- Trung bình – 3 NL: can thiệp vào một cấu trúc hoặc hệ thống chính, kể cả khi cần phục hồi toàn bộ cấu trúc đó.
- Cao – 10 NL: can thiệp vào nhiều cấu trúc hoặc hệ thống chức năng độc lập trong cùng một mục tiêu.
- Đặc biệt – 30 NL: can thiệp gần như toàn bộ cấu trúc và hệ thống chức năng của mục tiêu.
- Chỉ tính phần thực sự được can thiệp; không tính phần hư hỏng nhưng không được xử lý.
- Mức độ nghiêm trọng của tổn thương không tự động làm tăng E₀ nếu phạm vi vẫn giới hạn ở một cấu trúc đơn lẻ.
- Không dùng số lượng bước kỹ thuật/thao tác làm tiêu chí; các bước cùng tạo một hiệu ứng thống nhất được xét theo phạm vi can thiệp thực tế.
- Tiêu chí áp dụng cho cả mục tiêu sinh học và phi sinh học.
- Làm rõ E₀ độc lập với Kp, Kt và Ks; các hệ số lần lượt đo phạm vi đối tượng, thời gian duy trì và bản chất/cấp độ thay đổi thực tại.

### Ví dụ đã kiểm thử
- E₀ = 1: điều chỉnh trạng thái sinh lý cục bộ; sửa một linh kiện máy tính; chỉ sửa phần mái bị dột.
- E₀ = 3: can thiệp một cơ quan đơn lẻ dù tổn thương nghiêm trọng; phục hồi toàn bộ cấu trúc mái nhà.
- E₀ = 10: phục hồi đồng thời tim, phổi và gan; sửa nhiều hệ thống độc lập của máy tính/ô tô; phục hồi nhiều hệ thống chức năng trong một tầng nhà.
- E₀ = 30: phục hồi gần như toàn bộ cơ thể; phục hồi toàn bộ kết cấu và hệ thống chức năng của tòa nhà, cây cổ thụ hoặc con tàu.

### Trạng thái
- Cập nhật SYSTEM_BIBLE.md từ v1.18 lên v1.19.
- Đồng bộ tiêu chí E₀ vào SYS-007.md.
- Loại bỏ tiêu chí chọn cấp E₀ khỏi danh sách vấn đề chưa chốt.
- Các điểm mở khác của SYS-007, gồm tương tác khi nhiều hệ số thay đổi đồng thời, biến động bản chất/mức tác động theo thời gian và ranh giới Kp, được giữ nguyên; không tự quyết định trong lần cập nhật này.
