# Biến số

Phân loại:
  - Định tính:
    - Định danh: dân tộc (kinh, hoa, khác), tôn giáo (Phật giáo, Thiên Chúa giáo, khác), ...
    - Thứ tự: thang đo likert, giai đoạn ung thư (1, 2, 3, 4), ...
    - Nhị giá: giới tính (nam, nữ), bệnh (có, không), ...

  - Định lượng:
    - Rời rạc, khác biệt: năm sinh
    - Rời rạc, tỷ số: số ngày nằm viện, số người trong gia đình, ...
    - Liên tục, khác biệt: pH, nhiệt độ theo độ C hoặc độ F
    - Liên tục, tỷ số: nhiệt độ theo độ K, chiều cao, cân nặng, ...

Phân biệt chuyển đổi, mã hóa biến số:
  - Chuyển đổi: Thay đổi phân loại, không chuyển ngược lại được
  - Mã hóa: Không đổi phân loại, chuyển ngược lại được

# Trình bày số liệu

Lựa chọn:
  - 1 định tính: biểu đồ cột, tròn, bảng PP tần số 1 chiều
    - Nhị giá: văn bản
  - 1 định lượng: histogram, boxplot
  - 2 định tính: bảng chéo, biểu đồ cột chồng
  - 2 định lượng: scatter plot
  - 1 định tính, 1 định lượng: biểu đồ cột, boxplot

# Các giá trị đặc trưng

Lựa chọn:

  - Phân phối bình thường: trung bình, độ lệch chuẩn
  - Không phải phân phối bình thường: trung vị, khoảng tứ phân vị

Giới hạn sinh lý bình thường:
  - Phân phối bình thường: trung bình +/- 2 độ lệch chuẩn
  - Không phải phân phối bình thường: [V3; V97]
  - Ví dụ: GHSLBT của nhịp tim là 60 - 100:
    - nhịp tim 75 --> bình thường, KL có nguy cơ sai lầm beta không tính được
    - nhịp tim 120 --> bất thường, KL có nguy cơ sai lầm alpha = 0.05

# Lý thuyết kiểm định

So sánh chiều cao trung bình giữa A, B

  - H0: A = B
  - H1: A != B --> Kiểm định 2 phía
  - Sai lầm loại 1: A = B nhưng lại kết luận A != B
  - Sai lầm loại 2: A != B nhưng lại kết luận A = B
  - Độ mạnh: Kết luận đúng A != B
  - Giá trị p LÀ xác suất tính được giá trị kiểm định như vậy nếu H0 đúng
  - Giá trị p KHÔNG PHẢI LÀ xác suất H0 đúng
  - Sai lầm loại 1, 2, độ mạnh và giá trị p là xác suất có điều kiện

# Kiểm định t

Lựa chọn:
  - Điểm TB môn thống kê có khác 5 hay không --> t một mẫu
  - Điểm TB môn thống kê lớp A, B có khác nhau không --> t độc lập
  - Điểm TB môn thống kê và môn tin học có khác nhau không --> t bắt cặp

Điều kiện kiểm định t:
  - t một mẫu: PP bình thường
  - t độc lập: PP bình thường trong từng nhóm
  - t bắt cặp: PP bình thường của hiệu số

# Kiểm định chi bình phương

Lựa chọn:
  - Tỷ lệ rớt môn thống kê có khác 0.5 hay không --> chi bình phương goodness-of-fit
  - Tỷ lệ rớt môn thống kê lớp A, B có khác nhau không --> chi bình phương độc lập
  - Tỷ lệ rớt môn thống kê và môn tin học có khác nhau không --> Mc Nemar

Điều kiện chi bình phương: Tất cả tần số lý thuyết >= 5