tinh chỉnh các ý này vào run_yahoo.py và file liên quan nếu cần theo yêu cầu này:
Lưu ý: ko làm thay đổi logic của file gốc
# Bỏ hẳn 12 file — train và evaluate đều trên 55 file
EXCLUDE_FILES = {
    # 3 file không có anomaly
    'real_35.csv', 'real_59.csv', 'real_64.csv',
    # 8 file anomaly rơi hết vào train
    'real_5.csv', 'real_14.csv', 'real_18.csv', 'real_36.csv',
    'real_44.csv', 'real_48.csv', 'real_49.csv', 'real_54.csv',
    # 1 file anomaly bị sliding window cắt
    'real_61.csv'
}