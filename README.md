# Project Title 
# Fake new detection

![image](https://github.com/user-attachments/assets/76f6148b-e0c2-42b5-bd15-a1bdf99e6870)


### Các bước trong dự án:
- Thu thập và tiền xử lý dữ liệu. ( Dữ liệu ở đây mình sử dụng là của Kaggle )
- Khám phá và phân tích dữ liệu (EDA).
- Xây dựng và huấn luyện các mô hình học máy.
- Đánh giá mô hình và tinh chỉnh tham số.
- Triển khai mô hình  ( Ở đây mình test trên nhiều Model có sẵn trong thư viện sklearn như LogisticRegression,RandomForest,MultinomialNB ,SVC,XGBClassifier .... )
  Và ta được model tốt nhất là **Random Forest**
- Hình ảnh chứng minh **Random Forest** là model tốt nhất trong các model được train
- ![image](https://github.com/user-attachments/assets/f85a130a-6665-4536-b7b6-af9415f9ba62)
- ![image](https://github.com/user-attachments/assets/6fb4361c-253f-4bb7-a2ee-c6b2836545d3)
- ![image](https://github.com/user-attachments/assets/a702383e-2c72-4f7c-8b12-759a636df3cd)


- Và giá trị tốt nhất sau khi fine-tuning bằng RandomizedSearchCV là :
- ![image](https://github.com/user-attachments/assets/e473bef6-b8b6-4294-b147-3cb6331bfeef)



## Các công nghệ sử dụng

- **Python**: Ngôn ngữ lập trình chính.
- **Pandas**: Xử lý và phân tích dữ liệu.
- **NumPy**: Các phép toán số học.
- **Matplotlib** và **Seaborn**: Trực quan hóa dữ liệu.
- **scikit-learn**: Các thuật toán học máy cơ bản và các công cụ hỗ trợ.
- **XGBoost** (nếu bạn sử dụng): Thư viện học máy mạnh mẽ cho các bài toán học máy.


## Cài đặt
  
### Cài đặt môi trường:
Để chạy dự án này, bạn cần cài đặt các thư viện sau:
Trước khi chạy code bạn có thể dùng lệnh **pip install -r requirements.txt** để cài các thư viện cần để chạy được code 
1. **Clone repository**:
   ```bash
   git clone https://github.com/Kietnehi/Fake-news-detection.git
   cd repository-name
