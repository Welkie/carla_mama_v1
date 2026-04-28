b/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (12.4.99)
Requirement already satisfied: nvidia-cuda-runtime-cu12==12.4.99 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (12.4.99)
Requirement already satisfied: nvidia-cuda-cupti-cu12==12.4.99 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (12.4.99)
Requirement already satisfied: nvidia-cudnn-cu12==9.1.0.70 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (9.1.0.70)
Requirement already satisfied: nvidia-cublas-cu12==12.4.2.65 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (12.4.2.65)
Requirement already satisfied: nvidia-cufft-cu12==11.2.0.44 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (11.2.0.44)
Requirement already satisfied: nvidia-curand-cu12==10.3.5.119 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (10.3.5.119)
Requirement already satisfied: nvidia-cusolver-cu12==11.6.0.99 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (11.6.0.99)
Requirement already satisfied: nvidia-cusparse-cu12==12.3.0.142 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (12.3.0.142)
Requirement already satisfied: nvidia-nccl-cu12==2.20.5 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (2.20.5)
Requirement already satisfied: nvidia-nvtx-cu12==12.4.99 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (12.4.99)
Requirement already satisfied: nvidia-nvjitlink-cu12==12.4.99 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (12.4.99)
Requirement already satisfied: triton==3.0.0 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (3.0.0)
Requirement already satisfied: MarkupSafe>=2.0 in /usr/local/lib/python3.12/dist-packages (from jinja2->torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (3.0.3)
Requirement already satisfied: mpmath<1.4,>=1.1.0 in /usr/local/lib/python3.12/dist-packages (from sympy->torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (1.3.0)
Downloading termcolor-2.4.0-py3-none-any.whl (7.7 kB)
Downloading seaborn-0.13.0-py3-none-any.whl (294 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 294.6/294.6 kB 6.6 MB/s eta 0:00:00
Downloading faiss_cpu-1.13.2-cp310-abi3-manylinux_2_27_x86_64.manylinux_2_28_x86_64.whl (23.8 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 23.8/23.8 MB 66.1 MB/s eta 0:00:00
Building wheels for collected packages: easydict
  Building wheel for easydict (setup.py) ... done
  Created wheel for easydict: filename=easydict-1.10-py3-none-any.whl size=6492 sha256=0d5d8a6a0acda46d5dc41e00128726b853dbbc624159e5c2ff7f493799f74ce1
  Stored in directory: /root/.cache/pip/wheels/6b/76/56/33ab6d7f4a2ebd12c1a2c05eccf4cd886421ea55b8fa490fa8
Successfully built easydict
Installing collected packages: easydict, termcolor, faiss-cpu, seaborn
  Attempting uninstall: easydict
    Found existing installation: easydict 1.13
    Uninstalling easydict-1.13:
      Successfully uninstalled easydict-1.13
  Attempting uninstall: termcolor
    Found existing installation: termcolor 3.3.0
    Uninstalling termcolor-3.3.0:
      Successfully uninstalled termcolor-3.3.0
  Attempting uninstall: seaborn
    Found existing installation: seaborn 0.13.2
    Uninstalling seaborn-0.13.2:
      Successfully uninstalled seaborn-0.13.2
ERROR: pip's dependency resolver does not currently take into account all the packages that are installed. This behaviour is the source of the following dependency conflicts.
tpot 1.1.0 requires seaborn>=0.13.2, but you have seaborn 0.13.0 which is incompatible.
Successfully installed easydict-1.10 faiss-cpu-1.13.2 seaborn-0.13.0 termcolor-2.4.0
!git clean -fd     # xóa output rác
!git pull
Already up to date.
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
Max GPU Memory after M-6: 852.99 MB

Running dataset: M-1
Max GPU Memory after M-1: 930.81 MB

Running dataset: M-2
Max GPU Memory after M-2: 930.81 MB

Running dataset: S-2
Max GPU Memory after S-2: 930.81 MB

Running dataset: P-10
Max GPU Memory after P-10: 6859.53 MB

Running dataset: T-4
Max GPU Memory after T-4: 6859.53 MB

Running dataset: T-5
Max GPU Memory after T-5: 6859.53 MB

Running dataset: F-7
Max GPU Memory after F-7: 6859.53 MB

Running dataset: M-3
Max GPU Memory after M-3: 6859.53 MB

Running dataset: M-4
Max GPU Memory after M-4: 6859.53 MB

Running dataset: M-5
Max GPU Memory after M-5: 6859.53 MB

Running dataset: P-15
Max GPU Memory after P-15: 6859.53 MB

Running dataset: C-1
Max GPU Memory after C-1: 6859.53 MB

Running dataset: C-2
Max GPU Memory after C-2: 6859.53 MB

Running dataset: T-12
Max GPU Memory after T-12: 6859.53 MB

Running dataset: T-13
Max GPU Memory after T-13: 6859.53 MB

Running dataset: F-4
Max GPU Memory after F-4: 6859.53 MB

Running dataset: F-5
Max GPU Memory after F-5: 6859.53 MB

Running dataset: D-14
Max GPU Memory after D-14: 6859.53 MB

Running dataset: T-9
Max GPU Memory after T-9: 6859.53 MB

Running dataset: P-14
Max GPU Memory after P-14: 6859.53 MB

Running dataset: T-8
Max GPU Memory after T-8: 6859.53 MB

Running dataset: P-11
Max GPU Memory after P-11: 6859.53 MB

Running dataset: D-15
Max GPU Memory after D-15: 6859.53 MB

Running dataset: D-16
Max GPU Memory after D-16: 6859.53 MB

Running dataset: M-7
Max GPU Memory after M-7: 6859.53 MB

Running dataset: F-8
Max GPU Memory after F-8: 6859.53 MB

==============================
DONE ALL MSL DATASETS
Total time: 5525.33 s
Avg / dataset: 204.64 s
==============================

Time results saved to results/msl/time_results.json

==============================
STARTING EVALUATION (PAPER STYLE)
==============================
/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:407: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
  warnings.warn(
Error M-6: not enough values to unpack (expected 4, got 1)
/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:407: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
  warnings.warn(
Error M-1: not enough values to unpack (expected 4, got 1)
/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:407: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
  warnings.warn(
Error M-2: not enough values to unpack (expected 4, got 1)
/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:407: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
  warnings.warn(
Error S-2: not enough values to unpack (expected 4, got 1)
P-10: PR-AUC=0.9676, TP=1397, FP=0, FN=112
/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:407: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
  warnings.warn(
Error T-4: not enough values to unpack (expected 4, got 1)
/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:407: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
  warnings.warn(
Error T-5: not enough values to unpack (expected 4, got 1)
/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:407: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
  warnings.warn(
Error F-7: not enough values to unpack (expected 4, got 1)
/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:407: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
  warnings.warn(
Error M-3: not enough values to unpack (expected 4, got 1)
M-4: PR-AUC=0.7902, TP=785, FP=213, FN=2
/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:407: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
  warnings.warn(
Error M-5: not enough values to unpack (expected 4, got 1)
/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:407: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
  warnings.warn(
Error P-15: not enough values to unpack (expected 4, got 1)
/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:407: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
  warnings.warn(
Error C-1: not enough values to unpack (expected 4, got 1)
/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:407: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
  warnings.warn(
Error C-2: not enough values to unpack (expected 4, got 1)
/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:407: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
  warnings.warn(
Error T-12: not enough values to unpack (expected 4, got 1)
/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:407: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
  warnings.warn(
Error T-13: not enough values to unpack (expected 4, got 1)
F-4: PR-AUC=0.9350, TP=704, FP=210, FN=17
F-5: PR-AUC=0.8777, TP=352, FP=149, FN=19
/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:407: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
  warnings.warn(
Error D-14: not enough values to unpack (expected 4, got 1)
/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:407: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
  warnings.warn(
Error T-9: not enough values to unpack (expected 4, got 1)
P-14: PR-AUC=0.9924, TP=1482, FP=0, FN=42
/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:407: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
  warnings.warn(
Error T-8: not enough values to unpack (expected 4, got 1)
/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:407: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
  warnings.warn(
Error P-11: not enough values to unpack (expected 4, got 1)
/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:407: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
  warnings.warn(
Error D-15: not enough values to unpack (expected 4, got 1)
/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:407: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
  warnings.warn(
Error D-16: not enough values to unpack (expected 4, got 1)
/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:407: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
  warnings.warn(
Error M-7: not enough values to unpack (expected 4, got 1)
/usr/local/lib/python3.12/dist-packages/sklearn/metrics/_classification.py:407: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
  warnings.warn(
Error F-8: not enough values to unpack (expected 4, got 1)

==============================
FINAL RESULTS (PAPER STYLE)
==============================
PRECISION: 0.8919
RECALL: 0.9609
F1: 0.9251
AUPR_MEAN: 0.9126
AUPR_STD: 0.0808
TP: 4720
TN: 6882
FP: 572
FN: 192
TOTAL_DATASETS: 5

================ SUMMARY ================
Precision : 0.8919
Recall    : 0.9609
F1-score  : 0.9251
AUPR mean : 0.9126
AUPR std  : 0.0808

Total time     : 5525.33 s
Avg / dataset  : 204.64 s
GPU max memory : 6859.53 MB
=========================================

Summary written to results/msl/ketqua.txt
trả lời tiếng việt cho tui đây là lỗi gì và fix