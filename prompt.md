Fix lỗi 32 datasets fail 

Trong paper carla sử dụng resnet cho cả 2 giai đoạn kết quả của tác giả là cho tập dataset yahoo-A1 là:
Precision	0.5747
Recall	0.9755
F1-score	0.7233
AUPR mean	0.645
AUPR std	0.352

Vậy mà tui chạy bị lỗi datasets mà kết quả còn thấp nữa trong khi tui sử dụng mamba-resnet. Tinh chỉnh và fix cho tui 