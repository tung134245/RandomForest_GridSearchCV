## RandomForest_GridSearchCV
# Bộ dữ liệu:
Bệnh tim mạch (CVD) là nguyên nhân gây tử vong số 1 trên toàn cầu, cướp đi sinh mạng của khoảng 17,9 triệu người mỗi năm, chiếm 31% tổng số ca tử vong trên toàn thế giới. Bốn trong số 5 ca tử vong do bệnh tim mạch là do đau tim và đột quỵ, và một phần ba số ca tử vong này xảy ra sớm ở những người dưới 70 tuổi. Suy tim là một biến cố phổ biến do CVD gây ra và bộ dữ liệu này chứa 11 đặc điểm có thể được sử dụng để dự đoán bệnh tim có thể xảy ra. 

Những người mắc bệnh tim mạch hoặc có nguy cơ tim mạch cao (do có một hoặc nhiều yếu tố nguy cơ như tăng huyết áp, tiểu đường, tăng lipid máu hoặc đã mắc bệnh) cần được phát hiện và quản lý sớm trong đó mô hình học máy có thể giúp ích rất nhiều.
# Mô tả các thuộc tính
1) Age: tuổi của bệnh nhân [năm]
2) Giới tính: giới tính của bệnh nhân [M: Nam, F: Nữ]
3) ChestPainType: loại đau ngực [TA: Đau thắt ngực điển hình, ATA: Đau thắt ngực không điển hình, NAP: Không đau thắt ngực, ASY: Không có triệu chứng ]
4) RestingBP: huyết áp lúc nghỉ [mm Hg]
5) Cholesterol: cholesterol huyết thanh [mm/dl]
6) FastingBS: lượng đường trong máu lúc đói [1: FastingBS > 120 mg/dl, 0: trường hợp còn lại]
7) RestingECG: kết quả điện tâm đồ khi lúc nghỉ [Nornal: Bình thường, ST: có bất thường sóng ST-T (đảo ngược sóng T và/hoặc ST chênh lên hoặc chênh xuống > 0,05 mV), LVH: biểu hiện phì đại thất trái có thể xảy ra hoặc rõ ràng theo tiêu chuẩn Estes]
8) MaxHR: nhịp tim tối đa đạt được [Giá trị số từ 60 đến 202]
9) ExerciseAngina: đau thắt ngực do tập thể dục [Y: Có, N: Không]
10) Oldpeak: oldpeak = ST [Giá trị số đo được trong trầm cảm]
11) ST_Slope: độ dốc của đoạn ST tập luyện đỉnh cao [Up: độ dốc tăng, Flat: không thay đổi, Down: độ dốc giảm]
12) HeartDisease: loại đầu ra [1: bệnh tim, 0: Bình thường]

