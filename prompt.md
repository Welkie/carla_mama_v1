!python run_msl.py
Found Kaggle dataset at: /kaggle/input/datasets/patrickfleith/nasa-anomaly-detection-dataset-smap-msl
Copying /kaggle/input/datasets/patrickfleith/nasa-anomaly-detection-dataset-smap-msl/labeled_anomalies.csv to /kaggle/working/carla_mama_v1/datasets/msl/labeled_anomalies.csv...
Copying /kaggle/input/datasets/patrickfleith/nasa-anomaly-detection-dataset-smap-msl/data/data/train to /kaggle/working/carla_mama_v1/datasets/msl/train...
Copying /kaggle/input/datasets/patrickfleith/nasa-anomaly-detection-dataset-smap-msl/data/data/test to /kaggle/working/carla_mama_v1/datasets/msl/test...

==============================
STARTING EXPERIMENTS
==============================
GPU available: Tesla T4

Running dataset: M-6
Max GPU Memory after M-6: 819.99 MB

Running dataset: M-1
Max GPU Memory after M-1: 1304.85 MB

Running dataset: M-2
Max GPU Memory after M-2: 1304.85 MB

Running dataset: S-2
Max GPU Memory after S-2: 1304.85 MB

Running dataset: P-10
Max GPU Memory after P-10: 2884.31 MB

Running dataset: T-4
Max GPU Memory after T-4: 2884.31 MB

Running dataset: T-5
Max GPU Memory after T-5: 2884.31 MB

Running dataset: F-7
Max GPU Memory after F-7: 2884.31 MB

Running dataset: M-3
Max GPU Memory after M-3: 2884.31 MB

Running dataset: M-4
Max GPU Memory after M-4: 2884.31 MB

Running dataset: M-5
Max GPU Memory after M-5: 2884.31 MB

Running dataset: P-15
Max GPU Memory after P-15: 2884.31 MB

Running dataset: C-1
Max GPU Memory after C-1: 2884.31 MB

Running dataset: C-2
Max GPU Memory after C-2: 2884.31 MB

Running dataset: T-12
Max GPU Memory after T-12: 2884.31 MB

Running dataset: T-13
Max GPU Memory after T-13: 2884.31 MB

Running dataset: F-4
Max GPU Memory after F-4: 2884.31 MB

Running dataset: F-5
Max GPU Memory after F-5: 2884.31 MB

Running dataset: D-14
Max GPU Memory after D-14: 2884.31 MB

Running dataset: T-9
Error running pretext for T-9: Command '['/usr/bin/python3', 'carla_pretext.py', '--config_env', 'configs/env.yml', '--config_exp', 'configs/pretext/carla_pretext_msl.yml', '--fname', 'T-9']' returned non-zero exit status 1.
Traceback (most recent call last):
  File "/kaggle/working/carla_mama_v1/carla_pretext.py", line 240, in <module>
    main()
  File "/kaggle/working/carla_mama_v1/carla_pretext.py", line 196, in main
    tmp_loss = pretext_train(train_dataloader, model, criterion, optimizer, epoch, prev_loss, device=device)
               ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/kaggle/working/carla_mama_v1/utils/train_utils.py", line 49, in pretext_train
    return loss
           ^^^^
UnboundLocalError: cannot access local variable 'loss' where it is not associated with a value

Error running classification for T-9: Command '['/usr/bin/python3', 'carla_classification.py', '--config_env', 'configs/env.yml', '--config_exp', 'configs/classification/carla_classification_msl.yml', '--fname', 'T-9']' returned non-zero exit status 1.
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
FileNotFoundError: [Errno 2] No such file or directory: 'results/msl/T-9/pretext/con_train_dataset.pth'

Max GPU Memory after T-9: 2884.31 MB

Running dataset: P-14
Max GPU Memory after P-14: 2884.31 MB

Running dataset: T-8
Max GPU Memory after T-8: 2884.31 MB

Running dataset: P-11
Max GPU Memory after P-11: 2884.31 MB

Running dataset: D-15
Max GPU Memory after D-15: 2884.31 MB

Running dataset: D-16
Max GPU Memory after D-16: 2884.31 MB

Running dataset: M-7
Max GPU Memory after M-7: 2884.31 MB

Running dataset: F-8
Max GPU Memory after F-8: 2884.31 MB

==============================
DONE ALL MSL DATASETS
Total time: 11069.01 s
Avg / dataset: 409.96 s
==============================

Time results saved to results/msl/time_results.json

==============================
STARTING EVALUATION (PAPER STYLE)
==============================
M-6: PR-AUC=0.9429, TP=185, FP=0, FN=13
M-1: PR-AUC=0.6396, TP=1166, FP=575, FN=0
M-2: PR-AUC=0.9557, TP=926, FP=26, FN=240
S-2: PR-AUC=0.4682, TP=454, FP=546, FN=68
P-10: PR-AUC=0.5208, TP=300, FP=0, FN=342
T-4: PR-AUC=0.3537, TP=535, FP=910, FN=45
T-5: PR-AUC=0.3890, TP=442, FP=710, FN=95
F-7: PR-AUC=0.5763, TP=1699, FP=1665, FN=257
M-3: PR-AUC=0.8395, TP=619, FP=320, FN=143
M-4: PR-AUC=0.6812, TP=685, FP=502, FN=77
M-5: PR-AUC=0.7097, TP=635, FP=449, FN=177
P-15: PR-AUC=0.6290, TP=244, FP=1, FN=288
C-1: PR-AUC=0.8914, TP=715, FP=84, FN=160
C-2: PR-AUC=0.7699, TP=857, FP=419, FN=44
T-12: PR-AUC=0.7290, TP=453, FP=272, FN=179
T-13: PR-AUC=0.7539, TP=1141, FP=777, FN=0
F-4: PR-AUC=0.7863, TP=369, FP=131, FN=213
F-5: PR-AUC=0.8009, TP=290, FP=122, FN=81
D-14: PR-AUC=0.7349, TP=823, FP=202, FN=59
Skip T-9 (missing files)
P-14: PR-AUC=0.7526, TP=493, FP=0, FN=199
T-8: PR-AUC=0.7359, TP=624, FP=298, FN=24
P-11: PR-AUC=0.4105, TP=1132, FP=1679, FN=40
D-15: PR-AUC=0.5337, TP=594, FP=651, FN=63
D-16: PR-AUC=0.8194, TP=1162, FP=517, FN=0
M-7: PR-AUC=0.8725, TP=427, FP=8, FN=185
F-8: PR-AUC=0.6487, TP=452, FP=265, FN=84

==============================
FINAL RESULTS (PAPER STYLE)
==============================
PRECISION: 0.6102
RECALL: 0.8499
F1: 0.7104
AUPR_MEAN: 0.6902
AUPR_STD: 0.1667
TP: 17422
TN: 27694
FP: 11129
FN: 3076
TOTAL_DATASETS: 26

================ SUMMARY ================
Precision : 0.6102
Recall    : 0.8499
F1-score  : 0.7104
AUPR mean : 0.6902
AUPR std  : 0.1667

Total time     : 11069.01 s
Avg / dataset  : 409.96 s
GPU max memory : 2884.31 MB

fix T-9 sử dụng wsz = 256, còn lại 512 đi