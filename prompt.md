Đây là bảng kết quả mới:
Dataset	Wsz	Method	Precision	Recall	F1-score	AU-PR	Total Time (s)	Avg./File (s)	GPU Mem. (MB)
MSL	200	ResNet	0.3910	0.8025	0.5258	0.4866 ± 0.2519	12351.98	457.48	1230.80
  128	MAMBA							
  256		0.4196	0.8048	0.5516	0.5126 ± 0.2327	12056.33	446.53	1549.12
  512		0.6132	0.8487	0.7120	0.6987 ± 0.1693	10789.86	399.62	2884.31
  1024		0.8186	0.9488	0.8789	0.8286 ± 0.1703	8939.5	331.09	4978.65
  2048		0.9630	0.9873	0.9750	0.9838 ± 0.0469	5598.14	207.34	6859.53
  4096		0.9576	0.9916	0.9743	0.9851 ± 0.0469	4440.39	164.46	5838.87
SMAP	200	ResNet	0.4233	0.7589	0.5435	0.4396 ± 0.3217	33924.34	616.81	382.69
  128	MAMBA	0.2756	0.8260	0.4133	0.3168 ± 0.3065	36051.42	655.48	369.43
  256		0.3189	0.8322	0.4611	0.3663 ± 0.3137	30623.82	556.80	469.62
  512								
  1024		0.3586	0.9061	0.5138	0.3806 ± 0.2760	30044.19	546.26	1297.81
  2048		0.5749	0.9275	0.7098	0.5836 ± 0.2511	18645.16	339.00	1176.39
  4096		0.8338	0.9874	0.9041	0.8121 ± 0.1936	19155.87	348.29	1176.35
  6000		0.9923	1.0000	0.9961	0.9905 ± 0.0676	14015.99	254.84	1176.3
SMD	200	ResNet	0.3144	0.5987	0.4123	0.3870 ± 0.1908	33763.76	1205.85	1540.48
  128	MAMBA							
  256								
  512		0.3884	0.8340	0.5300	0.4401 ± 0.1808	33093.38	1181.91	3840.36
  800		0.4835	0.8804	0.6242	0.5564 ± 0.1856	35260.63	1259.31	5926.61
  1024		Không chạy được do vượt giới hạn cho phép của kaggle GPU T4						
SWaT	200	ResNet	0.7917	0.6126	0.6908	0.5193	1142.35	1142.35	206.96
  64	MAMBA	0.9866	0.8764	0.9282	0.9442	943.38	943.38	189.02
  128		1.0000	0.8909	0.9423	0.9175	1190.11	1190.11	623.77
  256		1.0000	0.5907	0.7427	0.6457	1124.73	1124.73	467.78
  512		1.0000	0.3379	0.5051	0.4196	1478.38	1478.38	914.62
WADI	400	ResNet	0.2202	0.8824	0.3525	0.1771	1496.77	1496.77	179.48
  128	MAMBA							
  256								
  512		0.2298	0.7314	0.3497	0.1959	1433.61	1433.61	297.37
  1024		0.3226	1.0000	0.4878	0.3056	1661.55	1661.55	569.73
  2048		0.4840	1.0000	0.6523	0.5322	2877.58	2877.58	1127.98
  2300		Không chạy được do vượt giới hạn cho phép của kaggle GPU T4						
Yahoo-A1	250	ResNet	0.6946	0.9746	0.8111	0.7761 ± 0.3397	5609.75	102.00	42.39
  128	MAMBA	0.4707	0.9546	0.6305	0.6157 ± 0.3447	8070.21	146.73	165.65
  256		0.5864	0.9867	0.7356	0.6355 ± 0.3941	5845.12	106.27	92.93
  512		0.8047	0.9948	0.8897	0.7835 ± 0.3677	3444.7	62.63	165.87
  1024		0.7964	0.9948	0.8846	0.7705 ± 0.3769	3155.92	57.38	165.87
KPI	200	ResNet	0.1500	0.7206	0.2483	0.2644 ± 0.2343	62356.69	2150.23	371.06
  128	MAMBA							
  256								
  512		0.2453	0.8415	0.3798	0.3235 ± 0.2276	66186.61	2282.30	316.46
  1024		0.3766	0.9352	0.5369	0.4664 ± 0.2278	73381.32	2530.39	596.48
  3100		0.6887	0.9768	0.8078	0.7879 ± 0.2227	80907.62	2789.92	1715.25
  4096		Không chạy được do vượt giới hạn cho phép của kaggle GPU T4						

bạn đọc các file data\msl.py, run_msl.py và các file liên quan tại sao code lại mang đến kết quả tốt ở tăng dần ở mức window size 6000
series  length  dims
   A-1    2880    25
   A-2    2648    25
   A-3    2736    25
   A-4    2690    25
   A-5     705    25
   A-6     682    25
   A-7    2879    25
   A-8     762    25
   A-9     762    25
   B-1    2435    25
   C-1    2158    55
   C-2     764    55
   D-1    2849    25
  D-11    2611    25
  D-12     312    25
  D-13    1490    25
  D-14    3675    55
  D-15    2074    55
  D-16    1451    55
   D-2    2880    25
   D-3    2880    25
   D-4    2833    25
   D-5    2561    25
   D-6    2594    25
   D-7    2583    25
   D-8    2602    25
   D-9    2583    25
   E-1    2880    25
  E-10    2880    25
  E-11    2880    25
  E-12    2880    25
  E-13    2880    25
   E-2    2880    25
   E-3    2880    25
   E-4    2880    25
   E-5    2880    25
   E-6    2880    25
   E-7    2769    25
   E-8    2880    25
   E-9    2880    25
   F-1    2869    25
   F-2    2861    25
   F-3    2880    25
   F-4    2244    55
   F-5    2598    55
   F-7    2511    55
   F-8    3342    55
   G-1    2820    25
   G-2    2478    25
   G-3    2624    25
   G-4    2551    25
   G-6    2881    25
   G-7    2446    25
   M-1    2209    55
   M-2    2208    55
   M-3    2037    55
   M-4    2076    55
   M-5    2032    55
   M-6    1565    55
   M-7    1587    55
   P-1    2872    25
  P-10    4308    55
  P-11    3969    55
  P-14    2880    55
  P-15    3682    55
   P-2    2821    25
   P-3    2855    25
   P-4    2609    25
   P-7    2853    25
   R-1    2874    25
   S-1    2818    25
   S-2     926    55
   T-1    2875    25
  T-10     425    55
  T-12    1145    55
  T-13    1145    55
   T-2    2855    25
   T-3    2876    25
   T-4    2272    55
   T-5    2272    55
   T-8     748    55
   T-9     439    55

Total series: 82
Total train points: 196,746

=== Distribution stats ===
count      82.000000
mean     2399.341463
std       832.017453
min       312.000000
25%      2170.500000
50%      2669.000000
75%      2880.000000
max      4308.000000
Name: length, dtype: float64

Min length : 312  (D-12)
Max length : 4,308  (P-10)
Mean length: 2399
Median     : 2669

Series có length >= 6000: 0/82
Series có length < 6000: 82/82

Series ngắn hơn W_best=6000:
series  length
   A-1    2880
   A-2    2648
   A-3    2736
   A-4    2690
   A-5     705
   A-6     682
   A-7    2879
   A-8     762
   A-9     762
   B-1    2435
   C-1    2158
   C-2     764
   D-1    2849
  D-11    2611
  D-12     312
  D-13    1490
  D-14    3675
  D-15    2074
  D-16    1451
   D-2    2880
   D-3    2880
   D-4    2833
   D-5    2561
   D-6    2594
   D-7    2583
   D-8    2602
   D-9    2583
   E-1    2880
  E-10    2880
  E-11    2880
  E-12    2880
  E-13    2880
   E-2    2880
   E-3    2880
   E-4    2880
   E-5    2880
   E-6    2880
   E-7    2769
   E-8    2880
   E-9    2880
   F-1    2869
   F-2    2861
   F-3    2880
   F-4    2244
   F-5    2598
   F-7    2511
   F-8    3342
   G-1    2820
   G-2    2478
   G-3    2624
   G-4    2551
   G-6    2881
   G-7    2446
   M-1    2209
   M-2    2208
   M-3    2037
   M-4    2076
   M-5    2032
   M-6    1565
   M-7    1587
   P-1    2872
  P-10    4308
  P-11    3969
  P-14    2880
  P-15    3682
   P-2    2821
   P-3    2855
   P-4    2609
   P-7    2853
   R-1    2874
   S-1    2818
   S-2     926
   T-1    2875
  T-10     425
  T-12    1145
  T-13    1145
   T-2    2855
   T-3    2876
   T-4    2272
   T-5    2272
   T-8     748
   T-9     439
mặc dù không có cái nào = 6000, các data có dim = 25 là của smap 
giải thích bằng tiếng việt
tại sao kết quả lại tốt hơn 4096, nó đang sử dụng cơ chế auto reducing window size hay là padding
nếu nó sử dụng auto reducing thì kết quả phải bằng 4096 chứ

đây là code data\msl.py khi 6000:
import os
import pandas
import numpy as np
from torch.utils.data import Dataset
from utils.mypath import MyPath
import ast
from sklearn.preprocessing import MinMaxScaler, StandardScaler
import torch

device = torch.device("cuda" if torch.cuda.is_available() else "cpu")


class MSL(Dataset):
    base_folder = ''

    def __init__(self, fname, root=MyPath.db_root_dir('msl'), train=True, transform=None, sanomaly= None, mean_data=None, std_data=None):

        super(MSL, self).__init__()
        self.root = root
        self.transform = transform
        self.sanomaly = sanomaly
        self.train = train  # training set or test set
        self.classes = ['Normal', 'Anomaly']
        self.data = []
        self.targets = []

        with open(os.path.join(self.root, 'labeled_anomalies.csv'), 'r') as file:
            csv_reader = pandas.read_csv(file, delimiter=',')

        data_info = csv_reader[csv_reader['chan_id'] == fname]

        if self.train:
            self.base_folder += 'train'
        else:
            self.base_folder += 'test'
            labels = []
            for index, row in data_info.iterrows():
                anomalies = ast.literal_eval(row['anomaly_sequences'])
                length = row.iloc[-1]
                label = np.zeros([length], dtype=bool)
                for anomaly in anomalies:
                    label[anomaly[0]:anomaly[1] + 1] = True
                labels.extend(label)
            self.targets = np.asarray(labels)

            self.mean, self.std = mean_data, std_data

        file_path = os.path.join(self.root, self.base_folder, fname+'.npy')
        temp = np.load(file_path)
        if np.any(sum(np.isnan(temp))!=0):
            print('Data contains NaN which replaced with zero')
            temp = np.nan_to_num(temp)

        if self.train:
            self.mean = np.mean(temp, axis=0)
            self.std = np.std(temp , axis=0)
            # min_column = np.amin(temp, axis=0)
            # max_column = np.amax(temp, axis=0)
            # self.mean, self.std = min_column, max_column 
        else:
            self.mean, self.std = mean_data, std_data
            # range_val = (std_data - mean_data) + 1e-20
            # temp = (temp - mean_data) / range_val
            self.std[self.std == 0.0] = 1.0
            temp = (temp - self.mean) / self.std

        self.data = np.asarray(temp)

        # Auto-reduce window size if dataset is too short
        wsz = 6000
        stride = 1
        if len(self.data) < wsz:
            if len(self.data) >= 4096:
                wsz = 4096
                print(f"[MSL] {fname}: Dataset length {len(self.data)} < 4096, auto-reduced window size to {wsz}")
            elif len(self.data) >= 2048:
                wsz = 2048
                print(f"[MSL] {fname}: Dataset length {len(self.data)} < 2048, auto-reduced window size to {wsz}")
            elif len(self.data) >= 1024:
                wsz = 1024
                print(f"[MSL] {fname}: Dataset length {len(self.data)} < 1024, auto-reduced window size to {wsz}")
            elif len(self.data) >= 512:
                wsz = 512
                print(f"[MSL] {fname}: Dataset length {len(self.data)} < 512, auto-reduced window size to {wsz}")
            elif len(self.data) >= 256:
                wsz = 256
                print(f"[MSL] {fname}: Dataset length {len(self.data)} < 256, auto-reduced window size to {wsz}")
            else:
                raise ValueError(
                    f"[MSL] {fname}: Dataset too short ({len(self.data)} samples) for minimum window size 256. "
                    f"Try a larger split or smaller window."
                )

        self.data, self.targets = self.convert_to_windows(wsz, stride)

    def convert_to_windows(self, w_size, stride):
        windows = []
        wlabels = []
        
        # pad if shorter than/equal to w_size to ensure at least one window
        if self.data.shape[0] <= w_size:
            pad_size = w_size - self.data.shape[0] + stride
            self.data = np.pad(self.data, ((0, pad_size), (0, 0)), 'constant')
            if len(self.targets) > 0:
                self.targets = np.pad(self.targets, (0, pad_size), 'constant')
                
        sz = int((self.data.shape[0]-w_size)/stride)
        for i in range(0, sz):
            st = i * stride
            w = self.data[st:st+w_size]
            if sum(self.targets[st:st+w_size]) > 0:
                lbl = 1
            else: lbl=0
                    
            windows.append(w)
            wlabels.append(lbl)
        return np.stack(windows), np.stack(wlabels)

    def __getitem__(self, index):
        """
        Args:
            index (int): Index
        Returns:
            dict: {'ts': ts, 'target': index of target class, 'meta': dict}
        """
        # ts_org = self.data[index]
        ts_org = torch.from_numpy(self.data[index]).float().to(device)  # cuda

        if len(self.targets) > 0:
            # target = self.targets[index].astype(int)
            target = torch.tensor(self.targets[index].astype(int), dtype=torch.long).to(device)
            class_name = self.classes[target]
        else:
            target = 0
            class_name = ''

        ts_size = (ts_org.shape[0], ts_org.shape[1])

        out = {'ts_org': ts_org, 'target': target, 'meta': {'ts_size': ts_size, 'index': index, 'class_name': class_name}}

        return out

    def get_ts(self, index):
        ts = self.data[index]
        return ts

    def get_info(self):
        return self.mean, self.std

    def concat_ds(self, new_ds):
        self.data = np.concatenate((self.data, new_ds.data), axis=0)
        self.targets = np.concatenate((self.targets, new_ds.targets), axis=0)

    def __len__(self):
        return len(self.data)

    def extra_repr(self):
        return "Split: {}".format("Train" if self.train is True else "Test")

còn đây là data\msl.py khi 4096:
import os
import pandas
import numpy as np
from torch.utils.data import Dataset
from utils.mypath import MyPath
import ast
from sklearn.preprocessing import MinMaxScaler, StandardScaler
import torch

device = torch.device("cuda" if torch.cuda.is_available() else "cpu")


class MSL(Dataset):
    base_folder = ''

    def __init__(self, fname, root=MyPath.db_root_dir('msl'), train=True, transform=None, sanomaly= None, mean_data=None, std_data=None):

        super(MSL, self).__init__()
        self.root = root
        self.transform = transform
        self.sanomaly = sanomaly
        self.train = train  # training set or test set
        self.classes = ['Normal', 'Anomaly']
        self.data = []
        self.targets = []

        with open(os.path.join(self.root, 'labeled_anomalies.csv'), 'r') as file:
            csv_reader = pandas.read_csv(file, delimiter=',')

        data_info = csv_reader[csv_reader['chan_id'] == fname]

        if self.train:
            self.base_folder += 'train'
        else:
            self.base_folder += 'test'
            labels = []
            for index, row in data_info.iterrows():
                anomalies = ast.literal_eval(row['anomaly_sequences'])
                length = row.iloc[-1]
                label = np.zeros([length], dtype=bool)
                for anomaly in anomalies:
                    label[anomaly[0]:anomaly[1] + 1] = True
                labels.extend(label)
            self.targets = np.asarray(labels)

            self.mean, self.std = mean_data, std_data

        file_path = os.path.join(self.root, self.base_folder, fname+'.npy')
        temp = np.load(file_path)
        if np.any(sum(np.isnan(temp))!=0):
            print('Data contains NaN which replaced with zero')
            temp = np.nan_to_num(temp)

        if self.train:
            self.mean = np.mean(temp, axis=0)
            self.std = np.std(temp , axis=0)
            # min_column = np.amin(temp, axis=0)
            # max_column = np.amax(temp, axis=0)
            # self.mean, self.std = min_column, max_column 
        else:
            self.mean, self.std = mean_data, std_data
            # range_val = (std_data - mean_data) + 1e-20
            # temp = (temp - mean_data) / range_val
            self.std[self.std == 0.0] = 1.0
            temp = (temp - self.mean) / self.std

        self.data = np.asarray(temp)

        # Auto-reduce window size if dataset is too short
        wsz = 4096
        stride = 1
        if len(self.data) < wsz:
            if len(self.data) >= 2048:
                wsz = 2048
                print(f"[MSL] {fname}: Dataset length {len(self.data)} < 1024, auto-reduced window size to {wsz}")
            elif len(self.data) >= 1024:
                wsz = 1024
                print(f"[MSL] {fname}: Dataset length {len(self.data)} < 1024, auto-reduced window size to {wsz}")
            elif len(self.data) >= 512:
                wsz = 512
                print(f"[MSL] {fname}: Dataset length {len(self.data)} < 512, auto-reduced window size to {wsz}")
            elif len(self.data) >= 256:
                wsz = 256
                print(f"[MSL] {fname}: Dataset length {len(self.data)} < 256, auto-reduced window size to {wsz}")
            else:
                raise ValueError(
                    f"[MSL] {fname}: Dataset too short ({len(self.data)} samples) for minimum window size 256. "
                    f"Try a larger split or smaller window."
                )

        self.data, self.targets = self.convert_to_windows(wsz, stride)

    def convert_to_windows(self, w_size, stride):
        windows = []
        wlabels = []
        
        # pad if shorter than/equal to w_size to ensure at least one window
        if self.data.shape[0] <= w_size:
            pad_size = w_size - self.data.shape[0] + stride
            self.data = np.pad(self.data, ((0, pad_size), (0, 0)), 'constant')
            if len(self.targets) > 0:
                self.targets = np.pad(self.targets, (0, pad_size), 'constant')
                
        sz = int((self.data.shape[0]-w_size)/stride)
        for i in range(0, sz):
            st = i * stride
            w = self.data[st:st+w_size]
            if sum(self.targets[st:st+w_size]) > 0:
                lbl = 1
            else: lbl=0
                    
            windows.append(w)
            wlabels.append(lbl)
        return np.stack(windows), np.stack(wlabels)

    def __getitem__(self, index):
        """
        Args:
            index (int): Index
        Returns:
            dict: {'ts': ts, 'target': index of target class, 'meta': dict}
        """
        # ts_org = self.data[index]
        ts_org = torch.from_numpy(self.data[index]).float().to(device)  # cuda

        if len(self.targets) > 0:
            # target = self.targets[index].astype(int)
            target = torch.tensor(self.targets[index].astype(int), dtype=torch.long).to(device)
            class_name = self.classes[target]
        else:
            target = 0
            class_name = ''

        ts_size = (ts_org.shape[0], ts_org.shape[1])

        out = {'ts_org': ts_org, 'target': target, 'meta': {'ts_size': ts_size, 'index': index, 'class_name': class_name}}

        return out

    def get_ts(self, index):
        ts = self.data[index]
        return ts

    def get_info(self):
        return self.mean, self.std

    def concat_ds(self, new_ds):
        self.data = np.concatenate((self.data, new_ds.data), axis=0)
        self.targets = np.concatenate((self.targets, new_ds.targets), axis=0)

    def __len__(self):
        return len(self.data)

    def extra_repr(self):
        return "Split: {}".format("Train" if self.train is True else "Test")

Tui đã chạy thử nhiều lần rồi và kết quả vẫn y vậy, mọi code còn lại là y chang giữa 2 lần chạy đó, không chỉnh thêm bất cứ thứ gì. Vậy rốt cuộc nó sử dụng cơ chế gì để cho ra kết quả như vậy?