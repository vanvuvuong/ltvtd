## Mục lục

- [(cẩm nang) Lập trình viên thực dụng](#cẩm-nang-lập-trình-viên-thực-dụng)
  - [I. Triết lý thực dụng](#i-triết-lý-thực-dụng)
    - [1. Đó là cuộc đời của bạn](#1-đó-là-cuộc-đời-của-bạn)
    - [2. Mèo đớp mất source code của tôi rồi](#2-mèo-đớp-mất-source-code-của-tôi-rồi)
    - [3. (Tính) Bất ổn (của) Phần mềm](#3-tính-bất-ổn-của-phần-mềm)
    - [4. Nồi xúp đá (cuội) và Luộc ếch](#4-nồi-xúp-đá-cuội-và-luộc-ếch)
    - [5. Phần mềm Đủ-Tốt](#5-phần-mềm-đủ-tốt)
    - [6. Danh mục kiến thức của bạn](#6-danh-mục-kiến-thức-của-bạn)
    - [7. Giao tiếp](#7-giao-tiếp)
  - [II. (Cách) Tiếp cận thực dụng](#ii-cách-tiếp-cận-thực-dụng)
    - [8. Điều cần thiết của một thiết kế tốt](#8-điều-cần-thiết-của-một-thiết-kế-tốt)
  - [III. Công cụ cơ bản](#iii-công-cụ-cơ-bản)
    - [16. Sức mạnh của văn bản thuần túy](#16-sức-mạnh-của-văn-bản-thuần-túy)
    - [17. Shell games](#17-shell-games)
- [Lời thề của lập trình viên web](#lời-thề-của-lập-trình-viên-web)

# [(cẩm nang) Lập trình viên thực dụng](#mục-lục)

> Đây là nội dung tổng hợp từ cuốn sách The Pragmatic Programmer. Mua sách tại [The Pragmatic Programmer, 20th Anniversary Edition: your journey to mastery by David Thomas, Andrew Hunt](https://pragprog.com/titles/tpp20/the-pragmatic-programmer-20th-anniversary-edition/) để ủng hộ tác giả.

> Tuyên bố miễn trừ trách nhiệm: Toàn bộ nội dung thuộc repo này được tạo ra với mục đích tự giáo dục phi thương mại. Những hoạt động thương mại liên quan đến nội dung repo này đều thuộc trách nhiệm của những cá nhân & tổ chức trực tiếp thực hiện. Chủ của repo này không có bất cứ mối quan hệ tài chính nào với các cá nhân & tổ chức thực hiện hành vi đó.

> Nếu bạn là nhà xuất bản & thấy rằng repo này không nên để public, hãy liên hệ tôi qua Gmail: <dinhdong24@proton.me> tôi sẽ đổi sang trạng thái private.

## [I. Triết lý thực dụng](#mục-lục)

### [1. Đó là cuộc đời của bạn](#i-triết-lý-thực-dụng)

> Tôi sống trên đời không phải để đáp ứng kỳ vọng của bạn, và bạn sống trên đời cũng không phải để đáp ứng kỳ vọng của tôi. ~Lý Tiểu Long

Cuộc sống của bạn, bạn sở hữu nó, lăn lộn & kiến tạo nó. Rất nhiều lập trình viên liên tục than vãn về những thất vọng của họ, rằng họ muốn chuyển đi sống ở một nơi khác, ở châu Âu, châu Á hoặc làm việc từ xa.

Câu trả lời của chúng tôi luôn là: _"Tại sao bạn không tạo ra sự thay đổi?"_

> **Bạn có quyền tự chủ.**

Môi trường làm việc tồi tệ? Công việc nhàm chán? Hãy có gắng sửa chúng. Nhưng đừng thử sửa mãi mãi.

Nếu công nghệ (này) trông có vẻ cỗ lỗ, hãy dành thời gian để học thứ mới mẻ trông có vẻ thú vị hơn. Bạn đầu tư vào bản thân, làm việc đó khi ngoài giờ làm việc là hợp lý rồi.

Muốn làm từ xa? Bạn đã thử hỏi (sếp) chưa? Nếu họ nói không, hãy tìm ai đồng ý.

### [2. Mèo đớp mất source code của tôi rồi](#i-triết-lý-thực-dụng)

> Sợ bị trông là yếu đuối là chính sự yếu đuối kinh khủng nhất. ~J.B. Bossuet, Politics from Holy Writ, 1709

Một trong những nền tảng của triết lý thực dụng là nhận trách nhiệm của bản thân & hành động của mình trong sự nghiệp, học hành, những dự án của mình & công việc hàng ngày.

Lập trình viên thực dụng (LTVTD) nắm mọi quyền trong việc lựa chọn sự nghiệp & không ngại thừa nhận sự thiếu hiểu biết hay sai lầm.

Dù cho một dự án có suôn sẻ đến đâu, trải qua thử nghiệm, tài liệu chỉnh chu, tự động hóa tốt, những vấn đề kỹ thuật không lường trước sẽ xuất hiện gây ảnh hưởng đến việc bàn giao hệ thống.

Chúng diễn ra và chúng ta nỗ lực xử lý chúng chuyên nghiệp nhất có thể. **Điều này có nghĩa là hãy trung thực & thẳng thắn.** Chúng ta có thể tự hào về năng lực của mình nhưng chúng ta phải thừa nhận những thiếu sót, sự ngu muội & sai lầm của mình.

**Lòng tin đội ngũ**

Trên tất cả, đội ngũ của bạn tin tưởng & dựa vào bạn - và bạn cần thoải mái với việc dựa vào người khác nữa. Lòng tin trong đội ngũ là một điều thiết yếu cho sự sáng tạo & hợp tác.

**Nhận trách nhiệm**

> Tip 4: Hãy đưa ra những lựa chọn, đừng đưa ra những lời đổ lỗi vô nghĩa.

Trách nhiệm là thứ gì đó bạn chủ động đồng ý. Bạn cam kết làm một cái gì đó xong, nhưng bạn không cần phải kiểm soát mọi khía cạnh của nó.

Trong khi bạn làm mọi thứ có thể, bạn cần phải phân tích những rủi ro nằm ngoài tầm với của mình & bạn có quyền không chịu trách nhiệm cho những tình huống bất khả thi, hoặc rủi ro quá lớn.

Trước khi bạn đến nói với ai đó điều gì không thể hoàn thành bởi vì bla, bla, bla... Hãy nói điều đó với cái màn hình, hay với con mèo ấy. Bạn thấy cái lí do đó nghe có hợp lý ko, hay ngu xuẩn? Bạn nghĩ sếp bạn nghe cái lý do đó nghĩ sao?

Trước khi bạn kể lể vấn đề với người khác, bạn đã thử điều này, điều kia chưa?

Đừng viện cớ này nọ, hãy đưa giải pháp.

### [3. (Tính) Bất ổn (của) Phần mềm](#i-triết-lý-thực-dụng)

> Đừng sống với chiêc cửa sổ hỏng

Đừng để "những chiếc của sổ hỏng" (thiết kế tệ hại, quyết định sai lầm, những dòng mã ngớ ngẩn) ko được sửa. Sửa từng cái một ngay khi chúng được phát hiện. Nếu không đủ thời gian để sửa chúng một cách chính xác, hãy vã nó lại. Thêm dòng bình luận vào đoạn mã, hiển thị thông báo "Chưa triển khai". Chí ít hãy làm điều gì đó để ngăn chặn những thiệt hai và cho thấy bạn kiểm soát tình hình.

**Đầu tiên, đừng gây hại**

### [4. Nồi xúp đá (cuội) và Luộc ếch](#i-triết-lý-thực-dụng)

> Hãy trở thành nhân tố xúc tách cho sự thay đổi
> Hãy nhớ bức tranh tổng quan

### [5. Phần mềm Đủ-Tốt](#i-triết-lý-thực-dụng)

> Biến chất lượng thành đòi hỏi bắt buộc

### [6. Danh mục kiến thức của bạn](#i-triết-lý-thực-dụng)

> Đầu tư vào kiến thức luôn là lãi nhất ~ Benjamin Franklin

**Danh mục kiến thức của bạn**
Quản lý danh mục kiến thức cũng hệt như quản lý danh mục đầu tư:

1. Nhà đầu tư nghiên túc đầu tư đều đặn - như một thói quen
2. Đa dạng hóa là chìa khóa cho thành công dài hạn
3. Nhà đầu tư thông minh cân bằng giữa những danh mục ít rủi ro và rủi ro cao, lãi cao
4. Nhà đầu tư cố mua thấp và bán cao để tối đa hóa lợi nhuận
5. Danh mục cần được xem và tái cân bằng định kỳ

**Xây dựng danh mục của bạn**
_Đầu tư đều đặn_
Lên kế hoạch kiên trì sử dụng một khoảng thời gian và địa điểm, trốn khỏi mọi sự phiền nhiễu để hoàn thành mục tiêu.

_Đa dạng hóa_
Bạn càng biết nhiều thứ khác nhau, bạn càng có nhiều giá trị. Bạn càng thành thạo nhiều công nghệ khác nhau, bạn càng dễ thích nghi với thay đổi. Và đừng quên cải thiện cả những kỹ năng ko-liên-quan tới kỹ thuật.

_Quản trị rủi ro_

_Mua thấp, bán cao_
Học một loại công nghệ trước khi chúng trở nên phổ biến cũng khó như là việc đi kiếm những cổ phiếu được định giá thấp vậy, nhưng đổi lại là phần thưởng lớn.

_Xem lại và tái cân bằng_

**Mục tiêu**
_Học ít nhất một ngôn ngữ lập trình mỗi năm_
_Đọc một cuốn sách kỹ thuật mỗi tháng_
_Đọc một cuốn sách không liên quan tới kỹ thuật nữa_
_Tham gia các khóa học_
_Tham gia các hội nhóm địa phương_
_Thử nghiệm môi trường khác nhau_
_Cập nhật tin tức_

**Cơ hội cho việc học hành**

**Suy nghĩ chín chắn**

### [7. Giao tiếp](#i-triết-lý-thực-dụng)

## [II. (Cách) Tiếp cận thực dụng](#mục-lục)

### [8. Điều cần thiết của một thiết kế tốt](#ii-cách-tiếp-cận-thực-dụng)

> Tip 14: Thiết kế tốt sẽ dễ để thay đổi hơn là một thiết kế tồi

Easy to change (ETC) - Dễ để thay đổi là một giá trị, không phải một quy tắc

## [III. Công cụ cơ bản](#mục-lục)

### [16. Sức mạnh của văn bản thuần túy](#công-cụ-cơ-bản)

> văn bản thuần túy: plain text
> Tip 25: Lưu kiến thức ở dạng văn bản thuần túy

Vấn đề của các định dạng văn bản kiểu binary là cần 1 ứng dụng hoặc môi trường tương ứng để giải mã chúng. Nó đã tách biệt dữ liệu & ý nghĩa của chúng. Dữ liệu được mã hóa thì vô nghĩa nếu như không có 1 ứng dụng giải mã tương ứng. Còn văn bản thuần túy thì khác.

Văn bản thuần túy (VBTT) là kiểu dạng:

```text
* đây là một
* danh sách
hoặc một cụm chữ vô nghĩa như: fndasicdasf
```

VBTT có thể lưu ở các dạng HTML, JSON, YAML, XML ... chứ không nhất thiết phải là `.txt`.

### [17. Shell games](#công-cụ-cơ-bản)

Để lập trình viên có thể quản trị các file văn bản, công cụ hữu dụng nhất là shell. Từ shell, bạn có thể tận dụng được toàn bộ những chúng năng của công cụ, kết hợp output theo cái cách mà đến cả những người tạo ra những tools đó còn không nghĩ ra được. Từ shell, bạn có thể tìm kiếp files, debug, mở trình duyệt, mở editor & những công cụ khác.

Không phải là chúng ta có thể thực hiện những điều trên bằng GUI sao? Vậy sao chúng ta không làm trên GUI cho tiện?
Câu trả lời là không.

> Hãy tận dụng sức mạnh của Câu lệnh Shells (Command Shells)

Lợi ích của GUI là **WYSIWYG** (What You See Is What You Get) - những gì bạn thấy là tất cả những gì bạn nhận (được) & bất lợi là **WYSIAYG** (What You See Is All You Get) - những gì bạn thấy là **tất cả** những gì bạn nhận (được)

```shell
grep '^import ' *.java | sed -e's/^import  *//' -e's/;.*$//' | sort -u >list
```

# [Lời thề của lập trình viên web](#mục-lục)

> Nguyên gốc từ [đây](https://fullstackopen.com/en/part1/a_more_complex_state_debugging_react_apps#web-programmers-oath)

- Tôi sẽ mở `console` mọi lúc khi tôi mở trình duyệt lên.
- Tôi sẽ phát triển một cách từ từ.
- Tôi sẽ viết rất nhiều câu lệnh `console.log` để tôi có thể chắc luồng code chạy như thế nào & xác định được bug nhanh chóng.
- Nếu code của tôi không chạy được, tôi sẽ dừng viết code & xóa code cho đến khi nó chạy được hoặc chuyển thể code về phiên bản có thể chạy được.
- Khi tôi cần tới sự giúp đỡ, tôi sẽ chuẩn bị câu hỏi một cách đầy đủ & rõ ràng.
