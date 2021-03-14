# Markdown
* Markdown là ngôn ngữ đánh dấu giống HTML nhưng đơn giản hơn HTML.
* Markdown dùng để viết văn bản thô, có thể xuất sang HTML với cách đơn giản nhất.
## Table Content
1. Thẻ, tiêu đề
2. Chỉ mục
3. Gạch đầu dòng
4. Đánh dấu xuống dòng
5. Trích dẫn
6. Highlight
7. Inline code
8. Ký tự in đậm
9. In nghiêng
10. Gạch ngang chữ
11. Gạch ngắt trang
12. Chèn link
13. Chèn ảnh
14. Chèn mỏ neo
15. Tạo bảng
___
### 1. Thẻ, tiêu đề
Markdown sử dụng ký tự `#` để đánh dấu 1 đoạn văn bản là `tiêu đề`.<br/>
Tùy theo số lượng ký tự `#` phía trước ta có số cấp tiêu đề tương ứng.<br/>

Cấp độ tiêu đề hiển thị|Cách viết
----------|----------
Tiêu đề cấp 1|# Tiêu đề cấp 1
Tiêu đề cấp 2|## Tiêu đề cấp 2
Tiêu đề cấp 3|### Tiêu đề cấp 3
Tiêu đề cấp 4|#### Tiêu đề cấp 4
Tiêu đề cấp 5|##### Tiêu đề cấp 5
Tiêu đề cấp 6|###### Tiêu đề cấp 6
___
### 2. Chỉ mục
Markdown sử dụng số kèm theo dấu chấm `.` để đánh chỉ mục.<br/>
Ví dụ:
```
1. mục 1
1. mục 2
1. mục 3
```
Kết quả nhận được:
1. mục 1
2. mục 2
3. mục 3

Markdown không quan tâm số chỉ mục đánh có theo thứ tự hay không.<br/>
Chỉ cần là 1 danh sách chỉ mục từ trên xuống, kèm theo cặp `số` và dấu `.` trước mỗi mục.<br/>
Thì Markdown sẽ tự động hiển thị theo thứ tự tăng dần của chỉ mục.
___
### 3. Gạch đầu dòng
Có nhiều cách để thể hiện gạch đầu dòng trong Markdown.<br/>
Ta có thể sử dụng dấu `*` hoặc `+` hoặc `-` kèm với 1 dấu cách trước mỗi dòng cần đánh dấu.<br/>
Ta có thể thêm những gạch đầu dòng phụ, bằng cách thụt vào trong `3 dấu cách`.<br/>
Ví dụ:
```
* Dòng 1
   * Dòng phụ 1.1
   + Dòng phụ 1.2
+ Dòng 2
   * Dòng phụ 2.1
   - Dòng phụ 2.2
```
Kết quả nhận được:
* Dòng 1
   - Dòng phụ 1.1
   + Dòng phụ 1.2
+ Dòng 2
   * Dòng phụ 2.1
   - Dọng phụ 2.2
___
### 4. Đánh dấu xuống dòng
Để xuống dòng trong cùng 1 đoạn văn, ta sử dụng thẻ đánh dấu `\<br/>`, mọi thông tin phía sau<br/>
thẻ này đều hiển thị ở dòng mới trong cùng 1 đoạn văn.

Để xuống dòng, và chuyển sang 1 đoạn văn mới, ta chỉ việc nhấn `Enter` 2 lần,<br/>
sẽ có 1 dòng trắng ngăn cách giữa 2 đoạn văn riêng biệt.
___
### 5. Trích dẫn
Sử dụng ký tự `>` để đánh dấu câu trích dẫn.<br/>
Hoặc có thể tăng ký tự `>` lồng trích dẫn vào nhau.<br/>
Ví dụ:
```
> Đây là câu trích dẫn bla bla ...
> chu pa pi mô nha nhố mô nha nhố ....
>> mô nha nhố tiếp nek !!!
```
Kết quả nhận được:
> Đây là câu trích dẫn bla bla ...<br/>
> chu pa pi mô nha nhố mô nha nhố ....
> > mô nha nhố tiếp nek !!!
___
### 6. Highlight
Để highlight làm nổi bật 1 ký tự, 1 chữ, hay 1 câu.<br/>
Ta cho chúng vào trong cặp nháy ngược \``.<br/>
Ví dụ:
```
`>` và `highlight`
```
Kết quả nhận được:<br/>
`>` và `highlight`
___
### 7. Inline code
Để hiển thị chính xác format của đoạn code trong Markdow.<br/>
Ta đặt 3 dấu nháy ngược ở đầu, và 3 dấu nháy ngược ở cuối của đoạn code đó.<br/>
Sau 3 dấu nháy ngược ở đầu đoạn code, ta viết thêm tên ngôn ngữ của đoạn code đó.<br/>
Ví dụ:
```
   \`\`\`java
      public class Example{
         public static void main(String[] args) {
            // something here
         }
      }
   \`\`\`
```
Kết quả nhận được:
```java
      public class Example{
         public static void main(String[] args) {
            // something here
         }
      }
```