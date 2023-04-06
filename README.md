**Bối cảnh**

Bạn là ứng viên đang muốn ứng tuyển vào vị trí data analyst thuộc team Marketplace của công ty X. Công ty X có sản phẩm chủ đạo là website ABC, là website tìm kiếm và so sánh booking khách sạn lớn thuộc top đầu thế giới. Team Marketplace là một team lớn gồm các data analysts, data scientists đến từ nhiều quốc gia khác nhau. Nhiệm vụ của team là cung cấp các phân tích dữ liệu nhằm hỗ trợ việc đưa ra quyết định của công ty X.

Team Marketplace đưa ra đầu bài cho bạn như sau, và lưu ý bạn rằng không có giải pháp nào là hoàn hảo, nhưng cách bạn tư duy, tìm kiếm giải pháp mới là điều quan trọng nhất với họ. Lãnh đạo của team khuyên bạn hãy đưa ra những giải pháp sáng tạo, nhưng cũng phải thực tiễn.

**Bộ dữ liệu:**

Bạn được cung cấp dữ liệu daily performance của 3 nhà quảng cáo (advertisers) trên website ABC trong năm 2019 tại 1 quốc gia (trong tổng số rất nhiều quốc gia mà website ABC có hoạt động)

Các nhà quảng cáo đưa ra mức giá khác nhau đối với 3 phân khúc khách hàng khác nhau dựa trên thời gian “time-to-travel” (TTT) (được tính bằng số ngày kể từ ngày khách hàng đặt phòng khách sạn cho đến ngày khách hàng check-in tại khách sạn đã đặt. 3 phân khúc khách hàng dựa trên TTT bao gồm:



* Short: 0 – 14 ngày
* Medium: 15 – 60 ngày
* Long: hơn 60 ngày

**Yêu cầu 1: Market trend                    **

Bộ dữ liệu bạn được cung cấp bao gồm 3 nhà quảng cáo chính trong thị trường này, là nhà quảng cáo “A”, “B”, và “C”.

Với mỗi nhà quảng cáo nói trên, bạn được cung cấp các thông số sau:



* Clicks: số lượng clicks mà người dùng website ABC thực hiện
* Cost: số tiền nhà quảng cáo phải trả cho website ABC (theo mô hình cost-per-click)
* Bookings: số lượng booking khách sạn được thực hiện bởi người dùng website ABC
* Booking_rev: số tiền mà người dùng tiêu cho booking khách sạn (tức chính là gross revenue của mỗi nhà quảng cáo                      

Một trong những chỉ tiêu mà team Marketplace quan tâm đó là tỷ lệ chuyển đổi của người dùng              (conversion rate of users). Nói cách khác, họ  quan tâm tới tỷ lệ người dùng mà có thể tìm được booking khách sạn phù hợp với nhu cầu của họ trên website ABC. Một cách để xác định điều này đó là tính tỷ lệ chuyển đổi booking (booking conversion), tính bằng cách lấy số lượng booking chia cho số lượng clicks.

Bạn hãy:



* Vẽ biểu đồ daily booking conversion cho cả năm 2019 cho website ABC
* Bạn có nhận thấy xu hướng gì không? Những yếu tố nào thúc đẩy xu hướng này? (What are the main drivers of this trend?)
* Bạn có đoán được những dữ liệu này là của quốc gia nào không? Bạn phỏng đoán dựa trên cơ sở nào?

**Yêu cầu 2: Advertiser performance**

Một trong những nhiệm vụ chính của bạn khi trở thành 1 Market Data Analyst là hiểu được hiệu quả hoạt động của các nhà quảng cáo (advertisers’ performance), sử dụng những bộ dataset tương tự như bộ mà bạn đã được cung cấp. Nếu nhìn từ góc độ của nhà quảng cáo:



* Giả sử mọi nhà quảng cáo đều có biên lợi nhuận (profit margin, tính bằng lợi nhuận / doanh thu từ booking) là 15% đối với mọi phân khúc khách hàng (short, medium, long), hãy tính tổng lợi nhuận (total profit) của mỗi nhà quảng cáo trong năm. 
* Dựa trên xu hướng mà bạn đã phát hiện được, bạn có đề xuất gì đối với mỗi nhà quảng cáo để cải thiện các chiến dịch quảng cáo của họ trong năm 2020?
