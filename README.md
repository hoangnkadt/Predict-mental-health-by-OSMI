# Predict-mental-health-by-OSMI

OSMI(Open Sourcing Mental Illness) in 2014, 2016, 2017, 2018, 2019

<b> Đồ án được chia làm ba phần chính:</b> <br>
-	Data cleaning
- 	Data analysis
-	MachineLearning
Tệp dữ liệu được lấy ở Open Sourcing Mental Illness, bao gồm năm 2014,2016,2017,2018,2019,2020,2021 (không có dữ liệu năm 2015)
Dữ liệu 2020, 2021 quá bé chỉ hơn 100 row, không có ý nghĩ nên loại bỏ
Chỉ dùng 2014,2016,2017,2018,2019
 
Dữ liệu khi được gộp các năm với nhau.
Dữ liệu sau khi thu được cần được làm sạch bằng các cách:
-	Đặt lại tên cột
-	Bỏ các cột không cần thiết
-	Chuẩn hóa dữ liệu về dạng phù hợp
o	Tuổi
	Loại bỏ các trường hợp <10 và >100
	Chia độ tuổi thành các nhóm ("0-20", "21-30", "31-40", "41-65", "66-100")
o	Giới tính: Dữ liệu giới tính chứa nhiều kiểu và font chữ khác nhau cần chuyển về một dạng
o	Sought treament: chuyển về dạng boolean
o	Anonymous: chuyển về dạng boolean
o	

