# Mô tả cách thiết lập tính năng Files On-Demand để chỉ tải file xuống khi cần mở thực tế.
## Cơ chế hoạt động :
 - khi bật files on demand toàn bộ danh sách 500gb sẽ hiển thị dưới dạng bản sao ảo 
## cách thức truy xuất thực tế 
 - giải phóng dung lượng : sau khi xem xong hoặc xử lý xong hệ thống sẽ tự động đưa file vào cloud,xóa file bộ nhớ tạm và trả lại không gian trống cho SSD
 - cloud only: khi cần xem lại một video cũ . Chỉ cần nhấn vào file , ứng dụng sẽ tự động tải file đó từ cloud xún bộ nhớ đệm tạm thời trên SSD
# Báo cáo dung lượng
| chỉ số thông số | trạng thái đồng bộ toàn bộ | files on-demnad |
|:--- | :---: | ---: |
|Dung lượng ổ nguồn | 500GB | 500GB |
|Dung lượng ổ cứng | 256GB | 256GB |
|Dung lượng thực tế | 500GB | chỉ còn 10GB đến 20GB |
|Trạng thái hệ thống | treo máy | chạy mượt mà |
|Khả năng xử lý | bất khả thỉ | hoàn toàn khả thi |
 ## giải pháp khi dung lượng cloud lớn hơn dung lượng local SSD nhiều lần
 - giới hạn tốc độ upload trong cloud tránh không làm treo đường truyền internet cảu cả nhà trọ
 - bật window search control panel rồi ấn enter chọn power opitons rồi chọn change what closing the lid does -> ở dòng when i press the sleep button chọn 2 cột on battery và plugged in chuyển sang do nothing rồi bấm change
