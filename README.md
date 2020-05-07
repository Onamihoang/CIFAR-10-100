# CIFAR-10-100
Kiểm tra các mode CNN với dữ liệu CIFAR-10 và CIFAR-100 (https://www.cs.toronto.edu/~kriz/cifar.html)

Bộ dữ liệu CIFAR (tập con của bộ dữ liệu TiniImage 80 triệu ảnh) là tập hợp các ảnh thường để sử dụng để đâò tạo các thuật toán về Computer Vision (CV). 

CIFAR 10 : Với 60.000 ảnh màu kích thước 32x32 trong 10 loại khác nhau
CIFAR 100 : có 100 l khác nhau nằm trong 20 siêu nhóm

Từ trang paperwithcode,ta có thể thấy được thông kê các model và kết quả của nó đi kèm 


Với bộ dữ liệu CIFA-10, mình đã thử tự xây dựng model VGG và đạt được acc ~ 86% với một vài tip áp dụng thêm :
(https://machinelearningmastery.com/how-to-develop-a-cnn-from-scratch-for-cifar-10-photo-classification/)
  - BatchNorm
  - Dropout
  - Data Augmentation
  
 Trong bài CIFAR này, mình đã test nhiều đến mức phải dùng 3 tài khoản Colab để có 90h train. Dùng chrome trên điện thoại cũng có thể train được nhé.
