# traffic_sign
2-9:
  - train với ảnh được crop theo object và enhance, giữ nguyên màu
  - file thông tin dữ liệu test sai (sai class id) => tỉ lệ dự đoán 0.3
9/9:
	- sửa lại ảnh đầu vào về gray và chuyen gia tri pixel ve khoang [0,1]
	- train: 30 epoches
	- acc on data test: 0.98
	
7/10:
	detect lệch nhiều,err khoảng 2.3 
