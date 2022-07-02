# FINAL PROJECT

Repository này được tạo và điều chỉnh dựa trên [hand-gesture-recognition-using-mediapipe](https://github.com/Kazuhito00/hand-gesture-recognition-using-mediapipe) của Kazuhito00. Ngoài README.md này, repository sẽ đính kèm theo README.md gốc của [hand-gesture-recognition-using-mediapipe](https://github.com/Kazuhito00/hand-gesture-recognition-using-mediapipe).

Final Project của chúng em được chia làm 2 phần:
* Tạo dataset và huấn luyện AI do *Lê Quang Tuấn* đảm nhiệm.
* Tạo web do *Lê Phúc Khang* đảm nhiệm.

Do 2 phần được chúng em thực hiện song song, đồng thời chúng em còn nhiều hạn chế về kiến thức về Javascript, chúng em chưa thể kết hợp 2 phần này lại với nhau.

Những điều đã đạt được:

Lê Quang Tuấn: 
* Huấn luyện thành công mô hình nhận dạng ngôn ngữ ký hiệu của 26 chữ alphabet từ American Sign Language.
* Mô hình chạy mượt trên python và webcam trong khoảng 20-25 fps.

Lê Phúc Khang:
* Làm được web đơn giảng, dễ nhìn.
* Import được API mediapipe vào HTML.

Cách sử dụng đơn giản trên python:
1. Tải file creating_and_training_AI
2. Run app.py

*Lưu ý: 
- Trước khi run app.py, tải [dataset](https://drive.google.com/file/d/19JjeUrHIyGfD-lq4-Sr5i3jam5caETto/view?usp=sharing) này và cho vào path: creating_and_training_AI/model/keypoint_classifier/keypoint.csv
- Requirements:
mediapipe >=0.8.1
opencv-python >= 3.4.2
tensorflow >= 2.3.0
tf-nightly >= 2.5.0-dev
scikit-learn >= 0.23.2 
matplotlib >= 3.3.2


# Directory
<pre>
├─creating_and_training_AI
|  │  app.py
|  │  keypoint_classification.ipynb
|  │  point_history_classification.ipynb
|  │  
|  ├─model
|  │  ├─keypoint_classifier
|  │  │  │  keypoint.csv
|  │  │  │  keypoint_classifier.hdf5
|  │  │  │  keypoint_classifier.py
|  │  │  │  keypoint_classifier.tflite
|  │  │  └─ keypoint_classifier_label.csv
|  │  │          
|  │  └─point_history_classifier
|  │      │  point_history.csv
|  │      │  point_history_classifier.hdf5
|  │      │  point_history_classifier.py
|  │      │  point_history_classifier.tflite
|  │      └─ point_history_classifier_label.csv
|  │          
|  └─utils
|      └─cvfpscalc.py
|
├─my-static-site-main 2
|
|
|
</pre>
