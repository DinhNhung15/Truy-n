# **06\. CONTINUITY\_LOG\_Update\_v1.2.md**

**Bộ truyện:** Căn phòng không có tiếng động  
**Mã vụ án:** TKN-CASE-001  
**Phiên bản:** v1.2  
**Trạng thái:** BẢN CẬP NHẬT QUẢN LÝ TÍNH NHẤT QUÁN — CHỜ ĐỐI CHIẾU TOÀN BỘ HỒ SƠ

---

## **1\. MỤC ĐÍCH VÀ QUY ƯỚC QUẢN LÝ**

### **1.1. Mục đích**

`CONTINUITY_LOG` là hồ sơ theo dõi tính nhất quán của bộ truyện, dùng để ghi nhận:

* Những quyết định sáng tác đã được người dùng duyệt.  
* Trạng thái hiện tại của từng hồ sơ.  
* Các vấn đề chưa giải quyết và điều kiện để đóng chúng.  
* Những thay đổi được đề xuất, phê duyệt hoặc từ chối.  
* Các nguy cơ mâu thuẫn giữa sự thật nền, dòng thời gian, chứng cứ và diễn biến truyện.  
* Những chi tiết từ bản nháp cũ được giữ lại, loại bỏ hoặc cần kiểm tra trước khi tái sử dụng.

Tài liệu này không thay thế các hồ sơ chuyên trách:

* `STORY_BIBLE`: Quy tắc và định hướng tổng thể của bộ truyện.  
* `CHARACTER_BIBLE`: Thông tin, tính cách, quan hệ và giới hạn hiểu biết của nhân vật.  
* `CASE_FILE`: Sự thật nền, động cơ, phương thức gây án và cấu trúc vụ án.  
* `CLUE_LEDGER`: Danh mục manh mối, nguồn gốc, giá trị chứng minh và trạng thái kiểm chứng.  
* `TIMELINE`: Trình tự sự kiện, mốc thời gian và khả năng tiếp cận.  
* `CHAPTER_OUTLINE`: Cấu trúc và mục tiêu của từng chương.

Khi một quyết định thay đổi, hồ sơ chuyên trách phải được cập nhật trước hoặc đồng thời với nhật ký này. Không được chỉ sửa `CONTINUITY_LOG` rồi mặc nhiên coi các hồ sơ còn lại đã đồng bộ.

### **1.2. Quy ước trạng thái**

| Trạng thái | Ý nghĩa |
| ----- | ----- |
| **ĐÃ KHÓA** | Người dùng đã duyệt; không tự ý thay đổi. |
| **ĐỀ XUẤT** | Phương án đang được xem xét, chưa trở thành sự thật chính thức của truyện. |
| **CHƯA XÁC ĐỊNH** | Chưa đủ dữ kiện hoặc chưa có quyết định. |
| **CẦN KIỂM TRA** | Có nguy cơ mâu thuẫn, thiếu căn cứ hoặc chưa hoàn thiện chuỗi suy luận. |
| **LOẠI KHỎI CANON HIỆN TẠI** | Không được sử dụng làm sự thật nền của phiên bản đang phát triển. |

**Nguyên tắc bắt buộc:** Việc một chi tiết xuất hiện trong bản nháp, lời khai hoặc giả thuyết của nhân vật không đồng nghĩa chi tiết đó đã được xác nhận là sự thật.

---

## **2\. NHỮNG QUYẾT ĐỊNH ĐÃ KHÓA**

### **2.1. Sự thật nền của vụ án**

| Mã | Quyết định đã khóa | Trạng thái |
| ----- | ----- | ----- |
| CANON-001 | C03 là người trực tiếp gây ra cái chết của C02. | ĐÃ KHÓA |
| CANON-002 | Động cơ nền của C03 là che giấu sai phạm tài chính. | ĐÃ KHÓA |
| CANON-003 | C02 và C03 xảy ra giằng co trong cuộc đối đầu. | ĐÃ KHÓA |
| CANON-004 | Trong lúc giằng co, C03 cố ý đẩy C02. | ĐÃ KHÓA |
| CANON-005 | C02 ngã, va đầu vào cạnh cứng của đồ nội thất và bị thương chí mạng. | ĐÃ KHÓA |
| CANON-006 | Sau cú ngã, C03 nhận thấy C02 có thể đang gặp nguy hiểm nhưng rời đi mà không gọi cấp cứu. | ĐÃ KHÓA |
| CANON-007 | C03 khóa cửa từ phía hành lang bằng chìa khóa dự phòng mà C02 từng đưa cho mình. | ĐÃ KHÓA |
| CANON-008 | C05 nói dối về một việc riêng không liên quan trực tiếp đến hành vi gây án. | ĐÃ KHÓA Ở MỨC KHÁI QUÁT |
| CANON-009 | C04 có thể được xem xét như một giả thuyết cạnh tranh nếu chứng cứ thực tế hỗ trợ. | ĐÃ KHÓA VỀ NGUYÊN TẮC |

Các quyết định trên xác lập sự thật nền dành cho tác giả, nhưng không tự động xác lập rằng quá trình điều tra trong truyện đã có đủ chứng cứ để chứng minh mọi chi tiết.

Không được suy diễn rằng:

* C03 đã lên kế hoạch giết C02 từ trước.  
* C03 biết chắc C02 đã chết khi rời đi.  
* C03 là người duy nhất có khả năng tiếp cận căn hộ hoặc khóa cửa.  
* Việc cửa bị khóa tự nó chứng minh C03 là hung thủ.  
* Động cơ tài chính tự nó chứng minh C03 đã trực tiếp đẩy C02.  
* Lời thú nhận của C03, nếu xuất hiện, có thể thay thế toàn bộ chứng cứ độc lập.

  ### **2.2. Sự thật về sai phạm tài chính**

Các dữ kiện nền sau đã được xác lập:

* Công ty trong vụ án là một doanh nghiệp thương mại hoặc phân phối quy mô vừa tại Việt Nam.  
* C03 phụ trách các công việc liên quan đến thanh toán, công nợ hoặc đối chiếu hồ sơ.  
* C03 có thể chuẩn bị chứng từ, tổng hợp hồ sơ, theo dõi chi phí hoặc đề xuất giao dịch, nhưng không tự mình nắm toàn bộ quyền phê duyệt và chuyển tiền.  
* C02 là kế toán thanh toán, có nhiệm vụ kiểm tra chứng từ, nhập hoặc cập nhật dữ liệu thanh toán và xử lý giao dịch được chuyển đến theo quy trình.  
* C03 lợi dụng sự phân chia công việc và những điểm thiếu hoàn chỉnh trong hồ sơ cũ.  
* Các giao dịch ban đầu có dấu hiệu bất thường nhưng chưa đủ căn cứ độc lập để xác định ai khởi xướng hoặc chủ ý thực hiện sai phạm.  
* Những giao dịch về sau thể hiện rõ hơn vai trò của C02 trong quy trình xử lý.  
* C02 tuyên bố đã tìm được đầu mối mới có thể liên hệ C03 với sai phạm ban đầu, nhưng thực tế C02 chưa có chứng cứ thật sự chứng minh điều đó.  
* Chứng cứ giả được nhắc đến là hình ảnh hoặc ảnh chụp màn hình chứng từ giao dịch đã bị chỉnh sửa.  
* C02 tuyên bố đã gửi hoặc lưu một bản sao dự phòng ở nơi khác, nhưng lời tuyên bố này là giả.  
* C02 muốn C03 không thể sống thanh thản sau khi C02 phải gánh chịu hậu quả liên quan đến vụ việc.

**Các chi tiết chưa được khóa:** Bản chất chính xác của sai phạm, số tiền, thời gian thực hiện, người hưởng lợi, chuỗi giao dịch cụ thể và nguồn chứng cứ độc lập có thể kiểm tra.

Không tự bổ sung các con số, tài khoản, giao dịch hoặc tài liệu giả định rồi sử dụng chúng như dữ kiện chính thức.

### **2.3. Nhân vật C01**

Các dữ kiện đã xác lập:

* C01 là nam, 23 tuổi.  
* C01 tương đối trầm, giao tiếp xã hội chưa tốt nhưng có khả năng quan sát và suy luận đáng chú ý.  
* C01 biết đến vụ việc thông qua mối quan hệ quen biết với C03.  
* C01 không mặc nhiên được giao nhiệm vụ điều tra chính thức.  
* Năng lực của C01 phải thể hiện qua việc quan sát, đối chiếu và nhận ra mâu thuẫn trong phạm vi thông tin hợp lý.

**Vai trò nghề nghiệp cụ thể của C01 vẫn CHƯA XÁC ĐỊNH.**

Cho đến khi vai trò này được chốt, không được tự ý trao cho C01 quyền:

* Khám nghiệm hiện trường hoặc tử thi.  
* Thu giữ, niêm phong hay tự kiểm tra vật chứng thuộc quyền quản lý của cơ quan chức năng.  
* Thẩm vấn chính thức người liên quan.  
* Truy cập hồ sơ nghiệp vụ, dữ liệu cá nhân hoặc dữ liệu doanh nghiệp không thuộc quyền tiếp cận.  
* Ra lệnh điều tra hoặc yêu cầu người khác cung cấp tài liệu theo thẩm quyền mà C01 không có.

C01 có thể hình thành giả thuyết và báo lại điều mình nhận thấy cho người có thẩm quyền. Mọi kết luận quan trọng phải được kiểm tra bằng chứng cứ phù hợp.

### **2.4. Những dữ kiện về hiện trường và phát hiện C02 đã khóa**

* Phòng khách căn hộ C02 có cửa sổ hướng ra khoảng thông thoáng hoặc giếng trời bên ngoài.  
* Dàn nóng điều hòa của căn hộ bên cạnh được bố trí ở góc cho phép người đang sửa chữa nhìn chéo qua cửa sổ phòng khách của C02.  
* Người thợ sửa điều hòa vô tình nhìn thấy một người nằm trên sàn phòng khách.  
* Người thợ không thể chỉ từ góc nhìn đó xác định người nằm dưới sàn đã chết, đang bất tỉnh hay bị thương vì nguyên nhân gì.  
* Người thợ nhanh chóng báo cho chủ căn hộ bên cạnh.  
* Chủ căn hộ bên cạnh lo sợ, sang gõ cửa căn hộ C02 nhưng không nhận được phản hồi.  
* Sau đó, người này báo cho ban quản lý tòa nhà.  
* Ban quản lý phối hợp xử lý và liên hệ cơ quan có thẩm quyền.  
* Không mặc nhiên cho rằng ban quản lý có quyền tự ý mở căn hộ, khám xét hoặc điều tra thay cơ quan chức năng.

Các chi tiết về tầng nhà, kích thước cửa sổ, khoảng cách, góc nhìn và thời gian chính xác vẫn chưa được khóa.

---

## **3\. TRẠNG THÁI CÁC HỒ SƠ**

Trạng thái dưới đây phản ánh quá trình làm việc đã ghi nhận. Việc có bản cập nhật không đồng nghĩa bản cập nhật đó đã được phê duyệt thành canon chính thức.

| Hồ sơ | Trạng thái hiện tại | Công việc tiếp theo |
| ----- | ----- | ----- |
| STORY\_BIBLE | Có bản gốc v1.0 và bản cập nhật đề xuất v1.1. | Đối chiếu, xác nhận và hợp nhất sau khi người dùng duyệt. |
| CHARACTER\_BIBLE | Có bản gốc v1.0 và bản cập nhật đề xuất v1.1. | Chốt vai trò nghề nghiệp C01; rà soát quan hệ, động cơ và giới hạn hiểu biết của từng nhân vật. |
| CASE\_FILE | Có bản tổng hợp đề xuất v1.2; chưa khóa toàn bộ. | Hoàn thiện sai phạm tài chính, hoàn cảnh cuộc gặp, cơ chế cửa và chuỗi chứng cứ. |
| CLUE\_LEDGER | Có bản v1.2 đã được yêu cầu chốt; bản v1.3 là đề xuất cập nhật chưa hoàn thiện. | Hoàn thiện nguồn gốc, giá trị chứng minh và giới hạn của từng manh mối; ưu tiên thiết kế E8. |
| TIMELINE | Có bản dự thảo v1.2 và các bản tái cấu trúc đề xuất v1.3–v1.4. | Đối chiếu với sự thật nền, chuỗi phát hiện C02 và nguồn xác minh từng mốc thời gian. |
| CHAPTER\_OUTLINE | Chưa đủ điều kiện khóa. | Chờ các vấn đề cốt lõi trong CASE\_FILE, CLUE\_LEDGER và TIMELINE được giải quyết. |
| CONTINUITY\_LOG | Bản cập nhật quản lý tính nhất quán v1.2. | Tiếp tục ghi nhận quyết định được duyệt, thay đổi và mâu thuẫn phát sinh. |

**Lưu ý về phiên bản:** Không coi một bản đề xuất mới hơn là bản chính thức chỉ vì số phiên bản cao hơn. Trạng thái phê duyệt của tài liệu quan trọng hơn số phiên bản.

---

## **4\. CÁC VẤN ĐỀ CÒN MỞ**

### **OPEN-001 — Cụ thể hóa sai phạm tài chính**

**Đã khóa:**

C03 có sai phạm tài chính và muốn che giấu sai phạm đó. Đây là động cơ nền của vụ án.

**Chưa xác định hoặc chưa hoàn thiện:**

* Sai phạm cụ thể được thực hiện bằng cách nào.  
* Khoản tiền, giao dịch hoặc hồ sơ nào có liên quan.  
* C03 thực hiện phần việc nào trong quy trình và lợi ích thu được là gì.  
* Vai trò thực tế của C02 trong các giao dịch.  
* C02 đã phát hiện được những dấu hiệu nào và vào thời điểm nào.  
* Có những chứng cứ tài chính nào có thể được kiểm tra độc lập.  
* Vì sao việc C02 tuyên bố có đầu mối mới khiến C03 cảm thấy bị đe dọa.

**Điều kiện đóng:**

Sai phạm phải có cơ chế rõ ràng, phù hợp với phân công công việc tại doanh nghiệp và tạo được các manh mối có thể kiểm tra. Không được xây dựng sai phạm dựa trên giả định C03 có toàn quyền kiểm soát hệ thống thanh toán.

### **OPEN-002 — Hoàn cảnh cuộc gặp và diễn biến dẫn đến cú đẩy**

**Đã khóa:**

C02 và C03 đối đầu; trong lúc giằng co, C03 cố ý đẩy C02.

**Chưa xác định:**

* Ai chủ động đề nghị hoặc sắp xếp cuộc gặp.  
* Lý do trực tiếp khiến hai người gặp nhau.  
* Thời điểm và địa điểm chính xác.  
* C02 đã nói hoặc làm gì khiến mâu thuẫn leo thang.  
* Diễn biến cụ thể dẫn từ tranh cãi sang giằng co.  
* Cú đẩy xảy ra trong hoàn cảnh nào và điều gì khiến C03 hành động như vậy.

**Điều kiện đóng:**

Diễn biến phải phù hợp với tính cách, quan hệ, động cơ và khả năng hành động của hai nhân vật. Không được tạo ra một cuộc xô xát chỉ để phục vụ kết quả vụ án mà thiếu nguyên nhân thuyết phục.

### **OPEN-003 — Chuỗi chứng cứ chứng minh C03 trực tiếp đẩy C02**

**Đã khóa ở cấp độ sự thật nền:**

C03 trực tiếp đẩy C02.

**Chưa giải quyết ở cấp độ điều tra:**

Chưa có manh mối độc lập được phê duyệt để phân biệt chắc chắn giả thuyết C03 trực tiếp đẩy C02 với giả thuyết C03 có mặt nhưng C02 ngã do một nguyên nhân khác.

Đây là lỗ hổng trọng yếu của vụ án và phải được xử lý trước khi khóa dàn ý chương.

**Nguyên tắc xử lý:**

* Không tự tạo chứng cứ vật lý, dữ liệu ghi hình, lời khai nhân chứng hoặc kết luận giám định rồi coi đó là dữ kiện đã khóa.  
* Không dùng động cơ tài chính làm bằng chứng trực tiếp cho hành vi đẩy.  
* Không coi việc C03 nói dối hoặc có lời khai mâu thuẫn là bằng chứng tự đủ để xác định cơ chế gây ngã.  
* Không coi việc C03 khóa cửa là bằng chứng trực tiếp cho cú đẩy.  
* Không để lời thú nhận cuối truyện bù đắp cho một chuỗi chứng cứ trước đó không đủ căn cứ.  
* Mọi manh mối mới phải có nguồn gốc, cách phát hiện, quyền tiếp cận và giới hạn chứng minh hợp lý.

**Điều kiện đóng:**

Có một chuỗi chứng cứ đủ chặt để phân biệt các giả thuyết cạnh tranh, hoặc câu chuyện phải thể hiện trung thực giới hạn chứng minh nếu không thể phân biệt chúng. Phương án cụ thể vẫn là **ĐỀ XUẤT**, chưa được khóa.

### **OPEN-004 — Chìa khóa dự phòng và cơ chế cửa**

**Đã khóa:**

C03 rời căn hộ rồi khóa cửa từ phía hành lang bằng chìa khóa dự phòng mà C02 từng đưa cho mình. Không có lối thoát bí mật hoặc cơ chế khóa từ xa được xác lập.

**Chưa xác định:**

* Loại khóa cụ thể.  
* Thời điểm và lý do C02 đưa chìa khóa dự phòng cho C03.  
* Những ai khác có quyền tiếp cận chìa khóa.  
* Cơ chế khóa có thể được kiểm tra như thế nào.  
* Những dữ liệu hoặc dấu vết nào thực tế có thể giúp xác minh việc khóa cửa.

**Điều kiện đóng:**

Cơ chế cửa phải khả thi về mặt vật lý và phù hợp với trình tự sự kiện. Không mặc nhiên coi cửa bị khóa là bằng chứng C03 là người duy nhất có thể ra vào.

### **OPEN-005 — Mốc thời gian và trình tự phát hiện C02**

**Đã khóa về trình tự khái quát:**

Người thợ sửa điều hòa nhìn thấy người nằm trên sàn; báo cho chủ căn hộ bên cạnh; người này gõ cửa C02 nhưng không nhận được phản hồi; sau đó báo ban quản lý; ban quản lý phối hợp và liên hệ cơ quan có thẩm quyền.

**Chưa xác định:**

* Ngày giờ chính xác của từng sự kiện.  
* Khoảng thời gian từ khi C03 rời đi đến khi C02 được phát hiện.  
* Nguồn có thể xác minh độc lập từng mốc thời gian.  
* Có ai khác tiếp cận căn hộ trong khoảng thời gian đó hay không.  
* Những thay đổi có thể xảy ra tại hiện trường trước khi cơ quan chức năng tiếp nhận.

**Điều kiện đóng:**

Dòng thời gian phải dựa trên nguồn có thể xác minh, chẳng hạn dữ liệu ghi nhận thực tế nếu có, lời khai được đối chiếu hoặc tài liệu hình thành trong quá trình xử lý vụ việc. Không tự đặt giờ chính xác chỉ để làm cho câu chuyện thuận tiện.

### **OPEN-006 — Lời nói dối của C05**

**Đã khóa:**

C05 nói dối về một việc riêng không liên quan trực tiếp đến hành vi gây án. C05 nghe thấy một âm thanh không rõ nguồn nhưng không thể xác định âm thanh đó phát ra từ đâu hoặc suy ra tình trạng của C02.

**Chưa xác định:**

* Nội dung cụ thể của lời nói dối.  
* Lý do C05 che giấu việc riêng.  
* Thời điểm lời nói dối bị phát hiện.  
* Nguồn thông tin dùng để kiểm tra lời khai.  
* Mức độ liên quan của C05 với dòng thời gian vụ án.

**Điều kiện đóng:**

Lời nói dối phải có chức năng hợp lý trong truyện, giúp tạo ra một giả thuyết hoặc sự hiểu nhầm có thể kiểm chứng. Không biến việc C05 nói dối thành bằng chứng buộc tội khi chưa có căn cứ độc lập.

C05 không phải đồng phạm và không được tự ý chuyển thành hung thủ trong quá trình phát triển cốt truyện.

### **OPEN-007 — Vai trò nghề nghiệp và con đường tiếp cận thông tin của C01**

**Đã khóa:**

C01 là nam, 23 tuổi, có năng lực quan sát và suy luận nhưng không mặc nhiên có quyền điều tra chính thức.

**Chưa xác định:**

* Chức danh và đơn vị làm việc.  
* Công việc thường ngày.  
* Mối quan hệ cụ thể với C03 và các nhân vật liên quan.  
* Nguồn thông tin C01 được phép tiếp cận.  
* Cách C01 chuyển những nhận xét của mình đến người có thẩm quyền.

**Điều kiện đóng:**

C01 phải có con đường hợp lý để biết từng dữ kiện cần thiết. Không được cho C01 biết tài liệu mật, kết quả giám định hoặc nội dung lời khai chưa được tiết lộ cho mình nếu chưa xây dựng được nguồn tiếp cận hợp lý.

### **OPEN-008 — Hoàn thiện giá trị chứng minh của các manh mối**

**Tình trạng:** CẦN KIỂM TRA.

Các nhóm chứng cứ đã được tổ chức trong CLUE\_LEDGER, nhưng không phải mọi nhóm đều đã có nguồn cụ thể hoặc đủ sức phân biệt các giả thuyết.

Những điểm phải kiểm tra:

* Dấu vết tại hiện trường có nguồn gốc và giới hạn chứng minh gì.  
* Kết luận giám định có thể xác định điều gì và không thể xác định điều gì.  
* Dữ liệu tài chính chứng minh sự bất thường, vai trò xử lý hay ý định của một người đến mức nào.  
* Lời khai của C05 có thể xác nhận thời điểm hoặc chỉ cung cấp thông tin không chắc chắn.  
* Các mâu thuẫn trong lời khai C03 có được đối chiếu bằng dữ kiện độc lập không.  
* Manh mối E8 có đủ sức phân biệt giả thuyết C03 đẩy C02 với khả năng C02 ngã do nguyên nhân khác hay chưa.  
* E9 có thực sự kiểm tra các giả thuyết cạnh tranh hay chỉ lặp lại kết luận đã định sẵn.

**Điều kiện đóng:**

Mỗi manh mối quan trọng phải có nguồn gốc, người phát hiện hoặc cung cấp, thời điểm xuất hiện, giá trị chứng minh, giới hạn và quan hệ với các giả thuyết. E8 vẫn là vấn đề ưu tiên, chưa được phép coi là đã giải quyết.

---

## **5\. NHÁNH CỐT TRUYỆN ĐÃ LOẠI**

### **5.1. Nhánh C08 là hung thủ**

**Trạng thái:** LOẠI KHỎI CANON HIỆN TẠI.

Các bản nháp cũ trong đó C08 là hung thủ, C03 không phải hung thủ hoặc vụ án được giải thích bằng những manh mối chỉ phù hợp với nhánh C08 không còn là nguồn sự thật hiện hành.

### **5.2. Quy tắc xử lý tài liệu cũ**

* Không sử dụng nhánh C08 để sửa đổi sự thật nền đã xác lập C03 là hung thủ.  
* Không tự động thay toàn bộ tên C08 bằng C03 trong các bản thảo cũ.  
* Không mặc định giữ lại bản ghi âm, tin nhắn, vật chứng hoặc lời khai từng được tạo riêng cho nhánh đã loại.  
* Chỉ tái sử dụng chi tiết cũ sau khi kiểm tra nguồn gốc, chức năng và mức độ tương thích với canon hiện tại.  
* Khi tham khảo tài liệu cũ, phải ghi rõ nội dung nào đã được xác nhận, nội dung nào chỉ là tham khảo và nội dung nào đã bị loại.  
* Không xóa toàn bộ nhân vật hoặc chi tiết cũ một cách máy móc. Chỉ loại khỏi canon những nội dung xung đột, chưa được duyệt hoặc không còn phù hợp.

Việc tái sử dụng một chi tiết cũ không đồng nghĩa với việc khôi phục toàn bộ nhánh cốt truyện cũ.

---

## **6\. QUY TRÌNH QUẢN LÝ THAY ĐỔI**

Mọi thay đổi có thể ảnh hưởng đến sự thật vụ án, chuỗi chứng cứ, động cơ, nhân vật hoặc dòng thời gian phải được ghi nhận theo mẫu sau.

### **6.1. Mẫu ghi nhận thay đổi**

**Mã thay đổi:** CHANGE-XXX  
**Nội dung trước thay đổi:**  
**Nội dung đề xuất:**  
**Lý do:**  
**Hồ sơ bị ảnh hưởng:**  
**Tác động đến sự thật nền:**  
**Tác động đến dòng thời gian:**  
**Tác động đến manh mối và giả thuyết:**  
**Tác động đến nhân vật và giới hạn hiểu biết:**  
**Mâu thuẫn mới phát sinh (nếu có):**  
**Trạng thái phê duyệt:** Chưa duyệt / Đã duyệt / Từ chối  
**Phiên bản hồ sơ cần cập nhật:**

### **6.2. Nguyên tắc thực hiện**

1. Không tự ý thay đổi dữ kiện đã khóa.  
2. Không coi đề xuất của trợ lý là quyết định đã được người dùng phê duyệt.  
3. Không sửa riêng một chi tiết nếu các chi tiết phụ thuộc vào nó chưa được rà soát.  
4. Trước khi cập nhật canon, phải xác định phạm vi ảnh hưởng đến các hồ sơ liên quan.  
5. Nếu thay đổi một mốc thời gian, phải kiểm tra cơ hội tiếp cận, lời khai, dữ liệu xác minh và trạng thái manh mối.  
6. Nếu thay đổi một chứng cứ, phải kiểm tra nguồn gốc, khả năng thu thập, giá trị chứng minh và các giả thuyết cạnh tranh.  
7. Nếu thay đổi vai trò của một nhân vật, phải kiểm tra động cơ, kiến thức, quan hệ và khả năng hành động.  
8. Sau khi được duyệt, cập nhật đồng bộ các hồ sơ chịu ảnh hưởng và ghi lại phiên bản mới.

   ### **6.3. Cách xử lý khi phát hiện mâu thuẫn**

Khi phát hiện hai dữ kiện không tương thích, cần ghi rõ:

* Hai dữ kiện đang xung đột.  
* Nguồn và trạng thái của từng dữ kiện.  
* Những sự kiện hoặc suy luận bị ảnh hưởng.  
* Các phương án sửa có thể thực hiện.  
* Ưu điểm, rủi ro và hệ quả của từng phương án.  
* Phương án được khuyến nghị cùng lý do.  
* Trạng thái chờ người dùng phê duyệt.

Không được tự quyết định thay đổi quan trọng chỉ để giúp dàn ý thuận tiện hơn hoặc tạo ra một cú twist.

---

## **7\. ĐIỀU KIỆN TRƯỚC KHI KHÓA CHAPTER\_OUTLINE**

Chưa đủ điều kiện khóa `CHAPTER_OUTLINE` cho đến khi các vấn đề cốt lõi dưới đây được xử lý.

### **7.1. Sự thật nền và động cơ**

* Cụ thể hóa sai phạm tài chính.  
* Xác định vai trò của C03 và C02 trong quy trình liên quan.  
* Làm rõ C02 đã phát hiện được gì và điều gì vẫn chỉ là lời tuyên bố giả.  
* Hoàn thiện mối liên hệ nhân quả giữa sai phạm, cuộc đối đầu và hành vi của C03.

  ### **7.2. Diễn biến gây án**

* Xác định hoàn cảnh cuộc gặp.  
* Xây dựng diễn biến hợp lý dẫn đến tranh cãi và giằng co.  
* Kiểm tra tính nhất quán giữa cú đẩy đã khóa và các dữ kiện hiện trường.  
* Không thêm thương tích, dấu vết hoặc phương thức gây án chưa được xác lập.

  ### **7.3. Chuỗi chứng cứ và giả thuyết**

* Hoàn thiện CLUE\_LEDGER và trạng thái của từng manh mối.  
* Thiết kế và kiểm tra E8 nhằm phân biệt các giả thuyết về nguyên nhân C02 ngã.  
* Đánh giá các giả thuyết cạnh tranh bằng chứng cứ, không bằng trực giác của nhân vật.  
* Kiểm tra giới hạn chứng minh của giám định, dấu vết vật lý, dữ liệu tài chính và lời khai.  
* Bảo đảm lời thú nhận, nếu có, không phải căn cứ duy nhất cho kết luận cuối cùng.

  ### **7.4. Hiện trường và dòng thời gian**

* Hoàn thiện cơ chế cửa và nguồn gốc chìa khóa dự phòng.  
* Đối chiếu trình tự phát hiện C02 với TIMELINE.  
* Xác định những mốc thời gian có thể kiểm chứng và nguồn xác minh tương ứng.  
* Đánh giá khả năng tiếp cận căn hộ của những người liên quan.  
* Kiểm tra khả năng hiện trường bị thay đổi trước khi cơ quan chức năng tiếp nhận.

  ### **7.5. Nhân vật và tính nhất quán**

* Chốt vai trò nghề nghiệp của C01.  
* Xác định con đường C01 tiếp cận từng dữ kiện quan trọng.  
* Giữ nhất quán kiến thức và động cơ của C02, C03, C04, C05 và các nhân vật khác.  
* Kiểm tra các chi tiết tái sử dụng từ bản nháp cũ.  
* Đối chiếu CASE\_FILE, CLUE\_LEDGER, TIMELINE và STORY\_BIBLE trước khi khóa dàn ý.

Chỉ chuyển sang giai đoạn lập dàn ý chương khi những lỗ hổng ảnh hưởng trực tiếp đến lời giải đã được xử lý hoặc có quyết định rõ ràng về giới hạn của chúng.

---

## **8\. TRẠNG THÁI CUỐI PHIÊN BẢN**

### **8.1. Canon đã khóa**

* C03 là hung thủ.  
* Động cơ nền của C03 là che giấu sai phạm tài chính.  
* C02 và C03 giằng co; C03 cố ý đẩy C02.  
* C02 ngã, va đầu vào cạnh cứng của đồ nội thất và bị thương chí mạng.  
* C03 nhận thấy C02 có thể đang gặp nguy hiểm nhưng rời đi mà không gọi cấp cứu.  
* C03 tìm giấy tờ sau cú ngã vì sợ C02 có chứng cứ liên quan đến sai phạm tài chính.  
* C03 khóa cửa từ phía hành lang bằng chìa khóa dự phòng.  
* C05 nói dối về việc riêng không liên quan trực tiếp đến hành vi gây án.  
* Người thợ sửa điều hòa là người đầu tiên nhìn thấy người nằm trên sàn qua cửa sổ phòng khách; thông tin sau đó được chuyển đến chủ căn hộ bên cạnh, ban quản lý và cơ quan có thẩm quyền theo trình tự đã xác lập.  
* Nhánh C08 là hung thủ đã bị loại khỏi canon hiện tại.

  ### **8.2. Các vấn đề chưa đủ điều kiện khóa**

* Bản chất và chi tiết cụ thể của sai phạm tài chính.  
* Hoàn cảnh cuộc gặp và diễn biến dẫn đến giằng co.  
* Cơ chế khóa cửa chi tiết và các khả năng tiếp cận liên quan.  
* Các mốc giờ chính xác và nguồn xác minh.  
* Giá trị chứng minh của từng nhóm manh mối.  
* Manh mối E8 có thể phân biệt cú đẩy với khả năng ngã do nguyên nhân khác.  
* Vai trò nghề nghiệp và giới hạn tiếp cận thông tin của C01.  
* Diễn biến lời khai và quá trình tâm lý của C03 trong giai đoạn điều tra.  
* Sự đồng bộ chính thức giữa các bản cập nhật hồ sơ.

  ### **8.3. Thứ tự công việc khuyến nghị**

1. Hoàn thiện các điểm còn thiếu trong `CASE_FILE`.  
2. Thiết kế E8 và rà soát toàn bộ `CLUE_LEDGER`.  
3. Đối chiếu `TIMELINE` với nguồn xác minh từng mốc.  
4. Chốt vai trò nghề nghiệp và con đường tiếp cận thông tin của C01.  
5. Xây dựng tiến trình lời khai của C03, bảo đảm phù hợp với tính cách và chứng cứ.  
6. Đồng bộ `STORY_BIBLE`, `CHARACTER_BIBLE`, `CASE_FILE`, `CLUE_LEDGER` và `TIMELINE`.  
7. Chỉ sau đó mới lập và khóa `CHAPTER_OUTLINE`.

**Kết luận quản lý:** Sự thật nền về người gây án và diễn biến cốt lõi đã được xác lập, nhưng chuỗi chứng cứ giúp người đọc hiểu vì sao C03 bị xác định là người trực tiếp đẩy C02 vẫn chưa hoàn thiện. Không được coi vụ án đã giải quyết trọn vẹn về mặt logic cho đến khi lỗ hổng này được xử lý. Không tự động chuyển sang viết chương khi người dùng chưa yêu cầu và hồ sơ chưa đủ điều kiện.

* 



---

## CHANGE-012 — Đồng bộ chìa khóa chính và tuyến nhận thức Nguyên

**Đã chốt ngày 04/11/2026.**

1. Thay “chìa dự phòng” bằng **chìa khóa chính căn hộ C02**; Long mang nó về sau khi khóa cửa căn hộ Bình từ bên ngoài.
2. Tại nhà Long, thứ tự bắt buộc: Long về nhà với điện thoại Bình và chìa khóa trong túi → ngồi gần cửa ôm trán → bạn gọi vào điện thoại Long hỏi việc chuẩn bị/phân chia việc → Long lấy điện thoại mình ra nghe, chìa khóa rơi xuống dưới ghế mà Long không biết → sau cuộc gọi Long lấy điện thoại Bình, tắt và giấu → Nguyên đến, làm rơi đồ → Nguyên nhặt đồ và nhặt cả chìa khóa → đặt tất cả lên bàn → mọi người thu dọn, cất đồ vào ngăn kéo bàn.
3. Nguyên không chứng kiến các sự việc trước lúc cậu đến. Không viết cậu hồi tưởng hành động Long.
4. Cơ quan điều tra phát hiện chìa khóa chính thiếu tại căn hộ Bình trước, hỏi vợ Bình để nhận dạng, rồi mới tìm thấy chìa khóa tương ứng trong ngăn kéo nhà Long.
5. Dấu vân tay Nguyên trên chìa khóa được thông báo sau khi vật chứng được xác định. Nguyên nhớ việc nhặt chìa và sau đó kiểm tra ảnh/video cũ trong nhóm chat; hình ảnh xác nhận chìa khóa của Bình đã xuất hiện tại nhà Long.
6. Nguyên ban đầu tin Long vô tội, chủ động tìm cách minh oan. Manh mối xuất hiện từng bước; chìa khóa, dấu vân tay và ảnh nhóm làm Nguyên lung lay nhưng không tự chứng minh Long là hung thủ. Các manh mối độc lập khác tiếp tục hướng về Long.
7. Không dùng quyền nghiệp vụ của Nguyên để truy cập trái phép hồ sơ, camera hoặc dữ liệu. Tôn trọng việc rút khỏi phần việc có xung đột lợi ích.
8. CHANGE-012 thay thế các chi tiết cũ trái ngược trong CHANGE-008/011 và outline: chìa dự phòng, chìa rơi vào khe tủ, Nguyên gạt chìa khỏi bờ tủ. Không thay đổi sự thật nền về cú đẩy, việc bỏ mặc C02, động cơ tài chính, bản ghi âm iCloud và cấu trúc E8.
