1. Dựa vào các file code của run_msl.py và các file liên quan để học logic, luồng xử lý,...

Xây dựng file run_yahoo.py của tui tương tự, tui code trên kaggle bằng GPU T4
Link dataset: /kaggle/input/datasets/saostken/yahoo-a1/yahoo_A1
## Thông tin dataset Yahoo-A1
- **Cấu trúc:** 67 file CSV độc lập (`real_1.csv` → `real_67.csv`)
- **Các cột:** `timestamp`, `value`, `is_anomaly`
- **Số chiều:** 1 (univariate time series)
- **Tỉ lệ anomaly:** ~1.76% (mất cân bằng cao)
### Train/Test split
- Yahoo-A1 KHÔNG có predefined split (khác MSL)
- Chia 50/50: **nửa đầu** mỗi file → train, **nửa sau** → test
- Train set: KHÔNG dùng nhãn (unsupervised/self-supervised)

2. Kiểm tra và trả lời qua tin nhắn là file run_smap.py và các file liên quan vẫn chạy ổn đúng ko?