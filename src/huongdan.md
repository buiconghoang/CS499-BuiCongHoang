## Nơi lưu trữ mã nguồn của khóa luận
data: https://drive.google.com/drive/folders/1MX3e3DUYX0DOQDn3Wgc05oZG6CmoYw_2?usp=sharing

hướng dẫn chạy code:
cài darknet: https://github.com/thtrieu/darkflow
tạo folder ckpt ở folder source -> cop dữ liệu từ folder detectVN hoặc detect_GTS ở googledrive vào folder vừa tạo
chạy file test_yolo_7_10, tùy theo muốn load tại epochs bao nhiêu thì thay đổi thông số ở 
options ={
    'model':'cfg/tiny-yolo-voc-28c.cfg',
    'load':10400, <---- here
    'threshold':0.5,
    'gpu': 0.5
}
thay đổi video_path: đường dẫn đầu vào
thay đổi video_save: đường dẫn save