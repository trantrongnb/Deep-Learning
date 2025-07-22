Fine tunning

I.Giới thiệu

-Về cơ bản thì Fine tunning là 1 phần của transfer learning
-Tức là lấy một phần của mô hình có sẵn được huấn luyện với lượng data lớn để huấn luyện mô hình của mình.

-Thường thì những layer đầu ta sẽ không đóng băng mà những layer nào ta thấy cần thiết phải cập nhập lại trọng số mô hình cho phù hợp với mô hình của chúng ta

-Ta có thể thêm một số layer để mô hình học tốt hơn.

II.Tác dụng

-Tác dung của Fine tunning là ta sẽ không phải train toàn bộ mô hình mà chỉ train những layer không bị đóng băng và layer thêm mới.
-Tốc độ tính toán nhanh, tiết kiệm bộ nhớ

III.Nhược điểm

-Đôi khi việc cập nhập các layer lại làm độ chính xác giảm.
-Với bộ data ít dữ liệu ta có thể bị over fitting
-Đối với bộ data của chúng ta quá riêng biệt với Imagenet thì độ chính xác của mô hình sẽ giảm.
<img width="468" height="608" alt="image" src="https://github.com/user-attachments/assets/6aa2cdcd-9387-4c4a-8fed-d1260b7ec8e9" />
