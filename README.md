# BÁO CÁO PHÂN TÍCH VÀ ỨNG DỤNG HỌC MÁY TRONG DỰ ĐOÁN NGUY CƠ MẮC BỆNH ĐÁI THÁO ĐƯỜNG

## Thành viên nhóm
- Bùi Kim Chi
- Lý Khả Di
- Lê Thị Diễm Liêl
- Nguyễn Thị Thùy Linh

## Nội dung repository

- `data/`: chứa dataset PIMA
- `BAO_CAO_DIABETES.pdf`: file báo cáo PDF của nhóm
- `Diabetes_Pima.ipynb`: file notebook chứa code dự đoán bệnh

## Mục tiêu chính
Mục đích cốt lõi của dự án này là phân tích dữ liệu sức khỏe của một nhóm đối tượng là người phụ nữ da đỏ Pima từ 21 tuổi trở lên. Để dự đoán liệu họ có bị bệnh tiểu đường hay không.

## Dữ liệu sử dụng 
Dự án dùng một bộ dữ liệu từ Viện Quốc gia về Bệnh Tiểu đường và Bệnh Tiêu hóa – Thận (National Institute of Diabetes and Digestive and Kidney Diseases). Bộ dữ liệu này chứa:

Các chỉ số y tế khác nhau (biến dự đoán): 

* Số lần mang thai (Pregnancies)
      
* Mức đường huyết (Glucose)
      
* Huyết áp (BloodPressure)
      
* Độ dày da (SkinThickness)
      
* Mức Insulin (Insulin)
      
* Chỉ số khối cơ thể (BMI)
      
* Tuổi (Age)
  
Kết quả chẩn đoán (biến mục tiêu): Đây là biến mà mô hình cần dự đoán. Biến này có hai giá trị: 
* `0`: không bị mắc bệnh
* `1`: bị mất bệnh

Nói cách khác, dự án dùng thông tin sức khỏe có sẵn để xây dựng một mô hình, giúp máy tính có thể dự đoán nguy cơ mắc bệnh tiểu đường cho những phụ nữ thuộc nhóm này.
