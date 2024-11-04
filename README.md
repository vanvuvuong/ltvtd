## Mục lục

- [(cẩm nang) Lập trình viên thực dụng](#cẩm-nang-lập-trình-viên-thực-dụng)
  - [II. Triết lý thực dụng](#ii-triết-lý-thực-dụng)
    - [1. Đó là cuộc đời của bạn](#1-đó-là-cuộc-đời-của-bạn)
    - [2. Mèo đớp mất source code của tôi rồi](#2-mèo-đớp-mất-source-code-của-tôi-rồi)
  - [II. (Cách) Tiếp cận thực dụng](#ii-cách-tiếp-cận-thực-dụng)
  - [III. Công cụ cơ bản](#iii-công-cụ-cơ-bản)
    - [16. Sức mạnh của văn bản thuần túy](#16-sức-mạnh-của-văn-bản-thuần-túy)
    - [17. Shell games](#17-shell-games)
- [Lời thề của lập trình viên web](#lời-thề-của-lập-trình-viên-web)

# [(cẩm nang) Lập trình viên thực dụng](#mục-lục)

> Đây là nội dung tổng hợp từ cuốn sách The Pragmatic Programmer. Mua sách tại [The Pragmatic Programmer, 20th Anniversary Edition: your journey to mastery by David Thomas, Andrew Hunt](https://pragprog.com/titles/tpp20/the-pragmatic-programmer-20th-anniversary-edition/) để ủng hộ tác giả.

> Tuyên bố miễn trừ trách nhiệm: Toàn bộ nội dung thuộc repo này được tạo ra với mục đích tự giáo dục phi thương mại. Những hoạt động thương mại liên quan đến nội dung repo này đều thuộc trách nhiệm của những cá nhân & tổ chức trực tiếp thực hiện. Chủ của repo này không có bất cứ mối quan hệ tài chính nào với các cá nhân & tổ chức thực hiện hành vi đó.

> Nếu bạn là nhà xuất bản & thấy rằng repo này không nên để public, hãy liên hệ tôi qua Gmail: <vanvuvuong3@gmail.com> tôi sẽ đổi sang trạng thái private.

## [II. Triết lý thực dụng](#mục-lục)

### [1. Đó là cuộc đời của bạn](#triết-lý-thực-dụng)

> Tôi sống không phải để đáp ứng kỳ vọng của bạn, và bạn sống cũng không phải để đáp ứng kỳ vọng của tôi. ~Lý Tiểu Long

Cuộc sống của bạn, bạn sở hữu nó, lăn lộn & kiến tạo nó. Rất nhiều lập trình viên liên tục than vãn về những thất vọng của họ, rằng họ muốn chuyển đi sống ở một nơi khác, ở châu Âu, châu Á hoặc làm việc từ xa.

Câu trả lời là: _"Tại sao bạn không tạo ra sự thay đổi?"_

> **Bạn có quyền tự chủ.**

Môi trường làm việc thiếu chuyên nghiệp? Đồng nghiệp/Sếp toxic? Công việc nhàm chán? Kỹ năng của bạn chưa đủ tốt?

Hãy dành thời gian để tạo ra sự thay đổi. Đổi sếp, đổi công việc, đổi domain, đổi vị trí chuyên môn, đổi NNLT,... Hãy tạo ra sự thay đổi mà bạn hằng mong muốn.

### [2. Mèo đớp mất source code của tôi rồi](#triết-lý-thực-dụng)

> Sợ bị trông là yếu đuối là chính sự yếu đuối kinh khủng nhất.

## [II. (Cách) Tiếp cận thực dụng](#mục-lục)

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



# [Lời thề của lập trình viên web](#mục-lục)

> Nguyên gốc từ [đây](https://fullstackopen.com/en/part1/a_more_complex_state_debugging_react_apps#web-programmers-oath)

- Tôi sẽ mở `console` mọi lúc khi tôi mở trình duyệt lên.
- Tôi sẽ phát triển một cách từ từ.
- Tôi sẽ viết rất nhiều câu lệnh `console.log` để tôi có thể chắc luồng code chạy như thế nào & xác định được bug nhanh chóng.
- Nếu code của tôi không chạy được, tôi sẽ dừng viết code & xóa code cho đến khi nó chạy được hoặc chuyển thể code về phiên bản có thể chạy được.
- Khi tôi cần tới sự giúp đỡ, tôi sẽ chuẩn bị câu hỏi một cách đầy đủ & rõ ràng.
