Step 1: !git clone https://github.com/WongKinYiu/yolov7 
Step 2: %cd yolov7

Nạp ảnh cần check vào Folder inference/images

Step 3: !python detect.py --weights yolov7.pt --conf 0.25 --img-size 640 --source inference/images/cai-noi.jpg Kết quả check trả ra tại folder runs/detect
