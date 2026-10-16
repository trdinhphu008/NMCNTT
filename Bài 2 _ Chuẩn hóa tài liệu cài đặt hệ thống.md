
# 1.Báo cáo phân tích (I/O)
-  Input (đầu vào): Văn bản Markdown thô gồm nội dung hướng dẫn, câu lệnh Terminal, code Python, bảng so sánh cảm biến và danh sách công việc.
 -   Output (đầu ra): Tài liệu được hiển thị rõ ràng, có tiêu đề, bảng, danh sách kiểm tra và `code Python` có tô màu cú pháp.
     
     Các cú pháp cần sử dụng:

-   Inline Code: Dùng dấu huyền ngược, ví dụ như : `humidity`.
    
-   Code Block: Dùng ba dấu huyền ngược và tên ngôn ngữ `python` để hỗ trợ tô màu cú pháp.
    
-   Table: Dùng dấu gạch đứng `|` để chia cột.
    
-   Task List: Dùng `- [ ]` cho công việc chưa hoàn thành và `- [x]` cho công việc đã hoàn thành.
    
-   Escape: Dùng dấu `\` trước ký tự đặc biệt nếu muốn hiển thị nguyên dạng, ví dụ `\*` hoặc `\#`.


# 2.Source code – file Markdown hoàn chỉnh
## Chương trình điều khiển máy bơm theo độ ẩm 

**humidity = 35
threshold = 40
if humidity < threshold:
    print("Do am thap: Bat may bom")
    pump_on = True
else:
    print("Do am du: Tat may bom")
    pump_on = False
print("Trang thai may bom:", "BAT" if pump_on else "TAT")**

## bảng so sánh cảm biến
|tiêu chí| cảm biến loại cũ | cảm biến loại mới |
|:-------:|:-------:|:-------:|
|nguyên lý|đo độ ẩm bằng điện trở|đo độ ẩm bằng điện dung
|  độ bền   |dễ bị ăn mòn|chống ăn mòn tốt hơn
|độ chính xác|có thể bị lệch bởi sự ăn mòn|thường ổn định hơn
|giá thành| dễ mua, rẻ hơn | đắt hơn 
| bảo trì | bảo trì thường xuyên | ít phải bảo trì hơn
```code python```
