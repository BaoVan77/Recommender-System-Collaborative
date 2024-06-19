# Recommender-System-Collaborative

1. Dữ liệu:
   - Tên: MovieLens_100k, được thu thập bởi Dự án nghiên cứu GroupLens tại Đại học Minnesota.
   - Thời gian: 7 tháng từ 19/09/1997 đến 22/04/1998.
   - Đã được clean những người dùng có ít hơn 20 lượt xếp hạng
   - Kích thước:
     - 100.000 lượt xếp hạng từ 1-5
     - 943 người dùng
     - 1682 bộ phim

2. Đặt vấn đề:
   - Mục tiêu: Tạo hệ thống RS-Collab có độ chính xác >= 80%
   - Ý tưởng: Xác định mức độ quan tâm của một người dùng tới một sản phẩm dựa trên hành động của những người dùng khác có độ tương đồng với người dùng này
     - Lập ma trận user - item: Để nhận biết người dùng thích bộ phim nào và không thích bộ phim nào
     - Gọi biến các bộ phim là i, chọn tất cả người dùng xếp hạng cho phim i.
     - Tính độ tương đồng của người dùng muốn biết với tất cả những người xếp hạng cho phim i
     - Chọn số k người có độ tương đồng cao nhất
     - Giới thiệu các bộ phim mà người tương đồng thích cho người dùng muốn biết.
    
3. Prepare data
   - Xóa đi những cột không cần thiết
   - 

