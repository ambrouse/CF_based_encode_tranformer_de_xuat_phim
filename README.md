## XÂY DỰNG MÔ HÌNH NHẬN DIỆN TÉ NGÃ ĐỘT QUỴ VỚI YOLO V8 BẢNG CẢI TIẾNG
<img src="./readme_assets/mau.png" alt="!!err image loading." width="700"/>

## Lời mở đầu 
-Trong thời đại số hóa, lượng nội dung phim ảnh ngày càng gia tăng, khiến người dùng gặp khó khăn trong việc lựa chọn phim phù hợp với sở thích cá nhân. Các hệ thống đề xuất thông minh đã trở thành một giải pháp quan trọng nhằm nâng cao trải nghiệm người dùng, giúp họ dễ dàng khám phá những bộ phim yêu thích dựa trên sở thích và hành vi trước đó.

-Dự án này tập trung vào việc xây dựng một hệ thống đề xuất phim dựa trên Collaborative Filtering (CF) kết hợp với Encoder Transformer. Thay vì sử dụng phương pháp truyền thống như Matrix Factorization, chúng tôi áp dụng Transformer để mã hóa thông tin người dùng và phim, từ đó tạo ra các vector biểu diễn giàu ngữ nghĩa. Mô hình sau đó sử dụng Fully Connected Neural Network (FNN) để dự đoán mức độ phù hợp giữa người dùng và phim, giúp tối ưu hóa độ chính xác của hệ thống đề xuất.

-Hệ thống này không chỉ tận dụng sức mạnh của Deep Learning trong việc xử lý dữ liệu phi cấu trúc mà còn khắc phục các hạn chế của Collaborative Filtering truyền thống như vấn đề cold start và sparsity. Bằng cách học các đặc trưng tiềm ẩn từ dữ liệu, mô hình có khả năng dự đoán và đề xuất phim một cách linh hoạt, cá nhân hóa hơn cho từng người dùng.

-Dự án này hứa hẹn mang đến một giải pháp mạnh mẽ, cải thiện đáng kể chất lượng gợi ý phim, giúp người dùng có những trải nghiệm xem phim tối ưu và thuận tiện nhất.

## Thành viên thực hiện 
- Nguyễn Lê Quốc Bảo - tham gia đóng góp 100% (bản thân) (Cài đặt huấn luyện mô hình, code xử lý data, tìm kiếm nguồn data, code demo cho mô hình sau huấn luyện, viết báo cáo).

## Các vị trí trong dự án
- Ba (phân tích mô hình, tìm kiếm mô hình, tìm kiếm data, viết báo cáo).
- leader (Điều hành, quản lý dự án)

## Vị trí của bản thân
- Dev, leader

## Mô hình sử dụng và lĩnh vực 
- Collaborative Filtering (CF) với lõi chính là lớp encode của tranformer(đồng thời áp dụng mullti embeding biểu diễn mối quan hệ trong từng ngữ cảnh của dữ liệu)
- Lĩnh vực xử lý ngôn ngữ tự nhiên

## Các thư viện và ngôn ngữ sử dụng trong dự án
- Ngôn ngữ Python
- Opencv
- Numpy
- Tensorflow
- Sklean
- Pandas

## Các công cụ hỗ trợ 
- Jupyter lab (trainning).
- IDE: vscode(tạo dữ liệu mẫu, xử lý dữ liệu, kiểm tra mô hình, xây dựng mô hình).

## Kiến trúc mô hình
<img src="./readme_assets/model.png" alt="!!err image loading." width="700"/>

## Loss sau 60 epochs
<img src="./result/loss.png" alt="!!err image loading." width="400"/>

## Phân bố nhãn
<img src="./result/probability distribution.png" alt="!!err image loading." width="400"/>

## Phân bố dự đoán
<img src="./result/probability distribution true-pre.png" alt="!!err image loading." width="400"/>

## Ma trận dự đoán
<img src="./result/confusion matrix.png" alt="!!err image loading." width="400"/>

## Các thông số khác
<img src="./result/result.png" alt="!!err image loading." width="700"/>


## Video demo cho dự án 
[![Watch video](https://img.youtube.com/vi/CivdCAs3dYY/0.jpg)](https://www.youtube.com/watch?v=CivdCAs3dYY)

## Tài liệu
- [Báo cáo chi tiết dự án](report/nguyen_le_quoc_bao_2100004053.docx)
- [Báo cáo tóm tắt dự án bản pp](report/bao_cao_de_xuat_phim.pptx)

## Link data và mô hình (file trọng số).
- [Data](https://drive.google.com/drive/folders/1loOymzPCEYAU3fz-B6TRfFGKKHBf9Va-?usp=sharing)
- [Trọng số mô hình (dùng tf để load)](https://drive.google.com/drive/folders/1hqKIXfcUNyF4ySWlBAMjTWI-jJBjSwgI?usp=sharing)





