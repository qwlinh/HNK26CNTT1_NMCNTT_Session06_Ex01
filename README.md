# YÊU CẦU ĐẦU RA

## Phần 1; Phân tích
 - Lệnh "Cat" của Nam thực hiện hiệu quả vì Lệnh "Cat" là lệnh viết tắt của lệnh "Get-Content"
 - Notepad là nơi soạn thảo văn bản và tải toàn bộ dữ liệu vào RAM. Khi gặp file dung lương lên đến 500MB khiến RAM của máy trở nên quá tải và là đứng máy
## Phần 2; Hoàn thiện
 - Lệnh PowerShell để xem toàn bộ file theo từng trang dựa trên gợi ý là:
 
   Get-content sever_log_500MB.log | more
 - Lệnh PowerShell để chie xem 10 dòng cuối cùng nhắm tìm ra lỗi là:

   Get-contten sever_log_500MB -Tail 10 -encoding utf8
