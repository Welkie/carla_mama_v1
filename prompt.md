!python run_kpi.py
Found Kaggle HDF5 at: /kaggle/input/datasets/minhanhphm1676/kpi-anomaly-dectection/KPI-Anomaly-Detection-master/Finals_dataset/phase2_ground_truth.hdf/phase2_ground_truth.hdf
Reading HDF5 file: /kaggle/input/datasets/minhanhphm1676/kpi-anomaly-dectection/KPI-Anomaly-Detection-master/Finals_dataset/phase2_ground_truth.hdf/phase2_ground_truth.hdf
HDF5 loaded — shape: (2918847, 4), columns: ['timestamp', 'value', 'label', 'KPI ID']
Detected columns — kpi_id: KPI ID, value: value, label: label, timestamp: timestamp
Found 29 KPI series.
  KPI 05f10d3a-239c-3bef-9bdc-a2feeb0037aa: train=74565 rows (605 anomalies), test=74565 rows (386 anomalies)
  KPI 0efb375b-b902-3661-ab23-9a0bb799f4e3: train=4392 rows (63 anomalies), test=4392 rows (8 anomalies)
  KPI 1c6d7a26-1f1a-3321-bb4d-7a9d969ec8f0: train=74578 rows (346 anomalies), test=74578 rows (287 anomalies)
  KPI 301c70d8-1630-35ac-8f96-bc1b6f4359ea: train=4392 rows (102 anomalies), test=4392 rows (104 anomalies)
  KPI 42d6616d-c9c5-370a-a8ba-17ead74f3114: train=74580 rows (277 anomalies), test=74581 rows (1619 anomalies)
  KPI 43115f2a-baeb-3b01-96f7-4ea14188343c: train=55314 rows (413 anomalies), test=55315 rows (526 anomalies)
  KPI 431a8542-c468-3988-a508-3afd06a218da: train=55783 rows (878 anomalies), test=55783 rows (2408 anomalies)
  KPI 4d2af31a-9916-3d9f-8a8e-8a268a48c095: train=55685 rows (947 anomalies), test=55685 rows (1638 anomalies)
  KPI 54350a12-7a9d-3ca8-b81f-f886b9d156fd: train=3808 rows (79 anomalies), test=3808 rows (29 anomalies)
  KPI 55f8b8b8-b659-38df-b3df-e4a5a8a54bc9: train=74566 rows (2915 anomalies), test=74567 rows (3176 anomalies)
  KPI 57051487-3a40-3828-9084-a12f7f23ee38: train=55839 rows (0 anomalies), test=55840 rows (46 anomalies)
  KPI 6a757df4-95e5-3357-8406-165e2bd49360: train=55438 rows (901 anomalies), test=55438 rows (1737 anomalies)
  KPI 6d1114ae-be04-3c46-b5aa-be1a003a57cd: train=74561 rows (357 anomalies), test=74561 rows (404 anomalies)
  KPI 6efa3a07-4544-34a0-b921-a155bd1a05e8: train=74574 rows (2184 anomalies), test=74574 rows (3099 anomalies)
  KPI 7103fa0f-cac4-314f-addc-866190247439: train=54212 rows (18 anomalies), test=54213 rows (50 anomalies)
  KPI 847e8ecc-f8d2-3a93-9107-f367a0aab37d: train=74561 rows (448 anomalies), test=74562 rows (342 anomalies)
  KPI 8723f0fb-eaef-32e6-b372-6034c9c04b80: train=74559 rows (382 anomalies), test=74559 rows (429 anomalies)
  KPI 9c639a46-34c8-39bc-aaf0-9144b37adfc8: train=55318 rows (418 anomalies), test=55318 rows (571 anomalies)
  KPI a07ac296-de40-3a7c-8df3-91f642cc14d0: train=55653 rows (784 anomalies), test=55654 rows (1475 anomalies)
  KPI a8c06b47-cc41-3738-9110-12df0ee4c721: train=3789 rows (53 anomalies), test=3789 rows (74 anomalies)
  KPI ab216663-dcc2-3a24-b1ee-2c3e550e06c9: train=5390 rows (118 anomalies), test=5390 rows (69 anomalies)
  KPI adb2fde9-8589-3f5b-a410-5fe14386c7af: train=74577 rows (294 anomalies), test=74578 rows (1398 anomalies)
  KPI ba5f3328-9f3f-3ff5-a683-84437d16d554: train=74566 rows (3007 anomalies), test=74566 rows (3770 anomalies)
  KPI c02607e8-7399-3dde-9d28-8a8da5e5d251: train=4392 rows (51 anomalies), test=4392 rows (10 anomalies)
  KPI c69a50cf-ee03-3bd7-831e-407d36c7ee91: train=74579 rows (354 anomalies), test=74580 rows (348 anomalies)
  KPI da10a69f-d836-3baa-ad40-3e548ecf1fbd: train=53583 rows (4050 anomalies), test=53584 rows (4700 anomalies)
  KPI e0747cad-8dc8-38a9-a9ab-855b61f5551d: train=4392 rows (106 anomalies), test=4392 rows (10 anomalies)
  KPI f0932edd-6400-3e63-9559-0a9860a1baa9: train=56074 rows (1188 anomalies), test=56075 rows (1654 anomalies)
  KPI ffb82d38-5f00-37db-abc0-5d2e4e4cb6aa: train=55698 rows (946 anomalies), test=55698 rows (1909 anomalies)

Prepared 29 KPI CSVs → datasets/kpi/train/ and datasets/kpi/test/

Processing 29 KPI series: 05f10d3a-239c-3bef-9bdc-a2feeb0037aa.csv ... ffb82d38-5f00-37db-abc0-5d2e4e4cb6aa.csv

==============================
STARTING EXPERIMENTS — KPI
==============================
GPU available: Tesla T4

Running dataset: 05f10d3a-239c-3bef-9bdc-a2feeb0037aa.csv
Error running pretext for 05f10d3a-239c-3bef-9bdc-a2feeb0037aa.csv: Command '['/usr/bin/python3', 'carla_pretext.py', '--config_env', 'configs/env.yml', '--config_exp', 'configs/pretext/carla_pretext_kpi.yml', '--fname', '05f10d3a-239c-3bef-9bdc-a2feeb0037aa.csv']' returned non-zero exit status 1.
Traceback (most recent call last):
  File "/kaggle/working/carla_mama_v1/carla_pretext.py", line 241, in <module>
    main()
  File "/kaggle/working/carla_mama_v1/carla_pretext.py", line 144, in main
    train_dataset = get_train_dataset(p, train_transforms, sanomaly, to_augmented_dataset=True)
                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/kaggle/working/carla_mama_v1/utils/common_config.py", line 154, in get_train_dataset
    dataset = AugmentedDataset(dataset)
              ^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/kaggle/working/carla_mama_v1/data/custom_dataset.py", line 33, in __init__
    self.create_pairs()
  File "/kaggle/working/carla_mama_v1/data/custom_dataset.py", line 42, in create_pairs
    item = self.dataset.__getitem__(index)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/kaggle/working/carla_mama_v1/data/KPI.py", line 83, in __getitem__
    ts_org = torch.from_numpy(self.data[index]).float().to(device)  # cuda
             ^^^^^
NameError: name 'torch' is not defined

Error running classification for 05f10d3a-239c-3bef-9bdc-a2feeb0037aa.csv: Command '['/usr/bin/python3', 'carla_classification.py', '--config_env', 'configs/env.yml', '--config_exp', 'configs/classification/carla_classification_kpi.yml', '--fname', '05f10d3a-239c-3bef-9bdc-a2feeb0037aa.csv']' returned non-zero exit status 1.
Traceback (most recent call last):
  File "/kaggle/working/carla_mama_v1/carla_classification.py", line 214, in <module>
    main()
  File "/kaggle/working/carla_mama_v1/carla_classification.py", line 52, in main
    train_dataset = get_aug_train_dataset(p, train_transformations, to_neighbors_dataset = True)
                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/kaggle/working/carla_mama_v1/utils/common_config.py", line 174, in get_aug_train_dataset
    dataloader = torch.load(p['contrastive_dataset'], weights_only=False)
                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 1065, in load
    with _open_file_like(f, 'rb') as opened_file:
         ^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 468, in _open_file_like
    return _open_file(name_or_buffer, mode)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 449, in __init__
    super().__init__(open(name, mode))
                     ^^^^^^^^^^^^^^^^
FileNotFoundError: [Errno 2] No such file or directory: 'results/kpi/05f10d3a-239c-3bef-9bdc-a2feeb0037aa.csv/pretext/con_train_dataset.pth'

Max GPU Memory after 05f10d3a-239c-3bef-9bdc-a2feeb0037aa.csv: 0.00 MB

Running dataset: 0efb375b-b902-3661-ab23-9a0bb799f4e3.csv
Error running pretext for 0efb375b-b902-3661-ab23-9a0bb799f4e3.csv: Command '['/usr/bin/python3', 'carla_pretext.py', '--config_env', 'configs/env.yml', '--config_exp', 'configs/pretext/carla_pretext_kpi.yml', '--fname', '0efb375b-b902-3661-ab23-9a0bb799f4e3.csv']' returned non-zero exit status 1.
Traceback (most recent call last):
  File "/kaggle/working/carla_mama_v1/carla_pretext.py", line 241, in <module>
    main()
  File "/kaggle/working/carla_mama_v1/carla_pretext.py", line 144, in main
    train_dataset = get_train_dataset(p, train_transforms, sanomaly, to_augmented_dataset=True)
                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/kaggle/working/carla_mama_v1/utils/common_config.py", line 154, in get_train_dataset
    dataset = AugmentedDataset(dataset)
              ^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/kaggle/working/carla_mama_v1/data/custom_dataset.py", line 33, in __init__
    self.create_pairs()
  File "/kaggle/working/carla_mama_v1/data/custom_dataset.py", line 42, in create_pairs
    item = self.dataset.__getitem__(index)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/kaggle/working/carla_mama_v1/data/KPI.py", line 83, in __getitem__
    ts_org = torch.from_numpy(self.data[index]).float().to(device)  # cuda
             ^^^^^
NameError: name 'torch' is not defined

Error running classification for 0efb375b-b902-3661-ab23-9a0bb799f4e3.csv: Command '['/usr/bin/python3', 'carla_classification.py', '--config_env', 'configs/env.yml', '--config_exp', 'configs/classification/carla_classification_kpi.yml', '--fname', '0efb375b-b902-3661-ab23-9a0bb799f4e3.csv']' returned non-zero exit status 1.
Traceback (most recent call last):
  File "/kaggle/working/carla_mama_v1/carla_classification.py", line 214, in <module>
    main()
  File "/kaggle/working/carla_mama_v1/carla_classification.py", line 52, in main
    train_dataset = get_aug_train_dataset(p, train_transformations, to_neighbors_dataset = True)
                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/kaggle/working/carla_mama_v1/utils/common_config.py", line 174, in get_aug_train_dataset
    dataloader = torch.load(p['contrastive_dataset'], weights_only=False)
                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 1065, in load
    with _open_file_like(f, 'rb') as opened_file:
         ^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 468, in _open_file_like
    return _open_file(name_or_buffer, mode)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 449, in __init__
    super().__init__(open(name, mode))
                     ^^^^^^^^^^^^^^^^
FileNotFoundError: [Errno 2] No such file or directory: 'results/kpi/0efb375b-b902-3661-ab23-9a0bb799f4e3.csv/pretext/con_train_dataset.pth'

Max GPU Memory after 0efb375b-b902-3661-ab23-9a0bb799f4e3.csv: 0.00 MB

Running dataset: 1c6d7a26-1f1a-3321-bb4d-7a9d969ec8f0.csv
Error running pretext for 1c6d7a26-1f1a-3321-bb4d-7a9d969ec8f0.csv: Command '['/usr/bin/python3', 'carla_pretext.py', '--config_env', 'configs/env.yml', '--config_exp', 'configs/pretext/carla_pretext_kpi.yml', '--fname', '1c6d7a26-1f1a-3321-bb4d-7a9d969ec8f0.csv']' returned non-zero exit status 1.
Traceback (most recent call last):
  File "/kaggle/working/carla_mama_v1/carla_pretext.py", line 241, in <module>
    main()
  File "/kaggle/working/carla_mama_v1/carla_pretext.py", line 144, in main
    train_dataset = get_train_dataset(p, train_transforms, sanomaly, to_augmented_dataset=True)
                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/kaggle/working/carla_mama_v1/utils/common_config.py", line 154, in get_train_dataset
    dataset = AugmentedDataset(dataset)
              ^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/kaggle/working/carla_mama_v1/data/custom_dataset.py", line 33, in __init__
    self.create_pairs()
  File "/kaggle/working/carla_mama_v1/data/custom_dataset.py", line 42, in create_pairs
    item = self.dataset.__getitem__(index)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/kaggle/working/carla_mama_v1/data/KPI.py", line 83, in __getitem__
    ts_org = torch.from_numpy(self.data[index]).float().to(device)  # cuda
             ^^^^^
NameError: name 'torch' is not defined

Error running classification for 1c6d7a26-1f1a-3321-bb4d-7a9d969ec8f0.csv: Command '['/usr/bin/python3', 'carla_classification.py', '--config_env', 'configs/env.yml', '--config_exp', 'configs/classification/carla_classification_kpi.yml', '--fname', '1c6d7a26-1f1a-3321-bb4d-7a9d969ec8f0.csv']' returned non-zero exit status 1.
Traceback (most recent call last):
  File "/kaggle/working/carla_mama_v1/carla_classification.py", line 214, in <module>
    main()
  File "/kaggle/working/carla_mama_v1/carla_classification.py", line 52, in main
    train_dataset = get_aug_train_dataset(p, train_transformations, to_neighbors_dataset = True)
                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/kaggle/working/carla_mama_v1/utils/common_config.py", line 174, in get_aug_train_dataset
    dataloader = torch.load(p['contrastive_dataset'], weights_only=False)
                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 1065, in load
    with _open_file_like(f, 'rb') as opened_file:
         ^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 468, in _open_file_like
    return _open_file(name_or_buffer, mode)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 449, in __init__
    super().__init__(open(name, mode))
                     ^^^^^^^^^^^^^^^^
FileNotFoundError: [Errno 2] No such file or directory: 'results/kpi/1c6d7a26-1f1a-3321-bb4d-7a9d969ec8f0.csv/pretext/con_train_dataset.pth'

Max GPU Memory after 1c6d7a26-1f1a-3321-bb4d-7a9d969ec8f0.csv: 0.00 MB

Running dataset: 301c70d8-1630-35ac-8f96-bc1b6f4359ea.csv
Error running pretext for 301c70d8-1630-35ac-8f96-bc1b6f4359ea.csv: Command '['/usr/bin/python3', 'carla_pretext.py', '--config_env', 'configs/env.yml', '--config_exp', 'configs/pretext/carla_pretext_kpi.yml', '--fname', '301c70d8-1630-35ac-8f96-bc1b6f4359ea.csv']' returned non-zero exit status 1.
Traceback (most recent call last):
  File "/kaggle/working/carla_mama_v1/carla_pretext.py", line 241, in <module>
    main()
  File "/kaggle/working/carla_mama_v1/carla_pretext.py", line 144, in main
    train_dataset = get_train_dataset(p, train_transforms, sanomaly, to_augmented_dataset=True)
                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/kaggle/working/carla_mama_v1/utils/common_config.py", line 154, in get_train_dataset
    dataset = AugmentedDataset(dataset)
              ^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/kaggle/working/carla_mama_v1/data/custom_dataset.py", line 33, in __init__
    self.create_pairs()
  File "/kaggle/working/carla_mama_v1/data/custom_dataset.py", line 42, in create_pairs
    item = self.dataset.__getitem__(index)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/kaggle/working/carla_mama_v1/data/KPI.py", line 83, in __getitem__
    ts_org = torch.from_numpy(self.data[index]).float().to(device)  # cuda
             ^^^^^
NameError: name 'torch' is not defined

Error running classification for 301c70d8-1630-35ac-8f96-bc1b6f4359ea.csv: Command '['/usr/bin/python3', 'carla_classification.py', '--config_env', 'configs/env.yml', '--config_exp', 'configs/classification/carla_classification_kpi.yml', '--fname', '301c70d8-1630-35ac-8f96-bc1b6f4359ea.csv']' returned non-zero exit status 1.
Traceback (most recent call last):
  File "/kaggle/working/carla_mama_v1/carla_classification.py", line 214, in <module>
    main()
  File "/kaggle/working/carla_mama_v1/carla_classification.py", line 52, in main
    train_dataset = get_aug_train_dataset(p, train_transformations, to_neighbors_dataset = True)
                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/kaggle/working/carla_mama_v1/utils/common_config.py", line 174, in get_aug_train_dataset
    dataloader = torch.load(p['contrastive_dataset'], weights_only=False)
                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 1065, in load
    with _open_file_like(f, 'rb') as opened_file:
         ^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 468, in _open_file_like
    return _open_file(name_or_buffer, mode)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 449, in __init__
    super().__init__(open(name, mode))