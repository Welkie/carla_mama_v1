!python run_smap.py
Found Kaggle dataset at: /kaggle/input/datasets/patrickfleith/nasa-anomaly-detection-dataset-smap-msl
Copying /kaggle/input/datasets/patrickfleith/nasa-anomaly-detection-dataset-smap-msl/labeled_anomalies.csv to /kaggle/working/carla_mama_v1/datasets/smap/labeled_anomalies.csv...
Copying /kaggle/input/datasets/patrickfleith/nasa-anomaly-detection-dataset-smap-msl/data/data/train to /kaggle/working/carla_mama_v1/datasets/smap/train...
Copying /kaggle/input/datasets/patrickfleith/nasa-anomaly-detection-dataset-smap-msl/data/data/test to /kaggle/working/carla_mama_v1/datasets/smap/test...

==============================
STARTING EXPERIMENTS
==============================
GPU available: Tesla T4

Running dataset: P-1
Max GPU Memory after P-1: 468.30 MB

Running dataset: S-1
Max GPU Memory after S-1: 468.30 MB

Running dataset: E-1
Max GPU Memory after E-1: 469.47 MB

Running dataset: E-2
Max GPU Memory after E-2: 469.47 MB

Running dataset: E-3
Error running classification for E-3: Command '['/usr/bin/python3', 'carla_classification.py', '--config_env', 'configs/env.yml', '--config_exp', 'configs/classification/carla_classification_smap.yml', '--fname', 'E-3']' returned non-zero exit status 1.
/kaggle/working/carla_mama_v1/utils/common_config.py:63: FutureWarning: You are using `torch.load` with `weights_only=False` (the current default value), which uses the default pickle module implicitly. It is possible to construct malicious pickle data which will execute arbitrary code during unpickling (See https://github.com/pytorch/pytorch/blob/main/SECURITY.md#untrusted-models for more details). In a future release, the default value for `weights_only` will be flipped to `True`. This limits the functions that could be executed during unpickling. Arbitrary objects will no longer be allowed to be loaded via this mode unless they are explicitly allowlisted by the user via `torch.serialization.add_safe_globals`. We recommend you start setting `weights_only=True` for any use case where you don't have full control of the loaded file. Please open an issue on GitHub for any issues related to this experimental feature.
  state = torch.load(pretrain_path, map_location='cpu')
Traceback (most recent call last):
  File "/kaggle/working/carla_mama_v1/carla_classification.py", line 214, in <module>
    main()
  File "/kaggle/working/carla_mama_v1/carla_classification.py", line 190, in main
    predictions = get_predictions(p, val_dataloader, model, False, False)
                  ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/utils/_contextlib.py", line 116, in decorate_context
    return func(*args, **kwargs)
           ^^^^^^^^^^^^^^^^^^^^^
  File "/kaggle/working/carla_mama_v1/utils/evaluate_utils.py", line 74, in get_predictions
    res = model(ts.view(bs, h, w), forward_pass='return_all')
          ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/nn/modules/module.py", line 1553, in _wrapped_call_impl
    return self._call_impl(*args, **kwargs)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/nn/modules/module.py", line 1562, in _call_impl
    return forward_call(*args, **kwargs)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/nn/parallel/data_parallel.py", line 186, in forward
    outputs = self.parallel_apply(replicas, inputs, module_kwargs)
              ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/nn/parallel/data_parallel.py", line 201, in parallel_apply
    return parallel_apply(replicas, inputs, kwargs, self.device_ids[:len(replicas)])
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/nn/parallel/parallel_apply.py", line 109, in parallel_apply
    output.reraise()
  File "/usr/local/lib/python3.12/dist-packages/torch/_utils.py", line 706, in reraise
    raise exception
TypeError: Caught TypeError in replica 1 on device 1.
Original Traceback (most recent call last):
  File "/usr/local/lib/python3.12/dist-packages/torch/nn/parallel/parallel_apply.py", line 84, in _worker
    output = module(*input, **kwargs)
             ^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/nn/modules/module.py", line 1553, in _wrapped_call_impl
    return self._call_impl(*args, **kwargs)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/nn/modules/module.py", line 1562, in _call_impl
    return forward_call(*args, **kwargs)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
TypeError: ClusteringModel.forward() missing 1 required positional argument: 'x'


Max GPU Memory after E-3: 469.47 MB

Running dataset: E-4
Max GPU Memory after E-4: 469.47 MB

Running dataset: E-5
Max GPU Memory after E-5: 469.47 MB

Running dataset: E-6
Max GPU Memory after E-6: 469.47 MB

Running dataset: E-7
Max GPU Memory after E-7: 469.47 MB

Running dataset: E-8
Max GPU Memory after E-8: 469.47 MB

Running dataset: E-9
Max GPU Memory after E-9: 469.47 MB

Running dataset: E-10
Max GPU Memory after E-10: 469.47 MB

Running dataset: E-11
Max GPU Memory after E-11: 469.47 MB

Running dataset: E-12
Max GPU Memory after E-12: 469.47 MB

Running dataset: E-13
Max GPU Memory after E-13: 469.48 MB

Running dataset: A-1
Max GPU Memory after A-1: 469.48 MB

Running dataset: D-1
Max GPU Memory after D-1: 469.48 MB

Running dataset: P-2
Max GPU Memory after P-2: 469.48 MB

Running dataset: P-3
Max GPU Memory after P-3: 469.48 MB

Running dataset: D-2
Max GPU Memory after D-2: 469.48 MB

Running dataset: D-3
Max GPU Memory after D-3: 469.48 MB

Running dataset: D-4
Max GPU Memory after D-4: 469.48 MB

Running dataset: A-2
Max GPU Memory after A-2: 469.48 MB

Running dataset: A-3
Max GPU Memory after A-3: 469.48 MB

Running dataset: A-4
Max GPU Memory after A-4: 469.48 MB

Running dataset: G-1
Max GPU Memory after G-1: 469.48 MB

Running dataset: G-2
Max GPU Memory after G-2: 469.48 MB

Running dataset: D-5
Max GPU Memory after D-5: 469.48 MB

Running dataset: D-6
Max GPU Memory after D-6: 469.48 MB

Running dataset: D-7
Max GPU Memory after D-7: 469.48 MB

Running dataset: F-1
Max GPU Memory after F-1: 469.48 MB

Running dataset: P-4
Max GPU Memory after P-4: 469.48 MB

Running dataset: G-3
Error running classification for G-3: Command '['/usr/bin/python3', 'carla_classification.py', '--config_env', 'configs/env.yml', '--config_exp', 'configs/classification/carla_classification_smap.yml', '--fname', 'G-3']' returned non-zero exit status 1.
/kaggle/working/carla_mama_v1/utils/common_config.py:63: FutureWarning: You are using `torch.load` with `weights_only=False` (the current default value), which uses the default pickle module implicitly. It is possible to construct malicious pickle data which will execute arbitrary code during unpickling (See https://github.com/pytorch/pytorch/blob/main/SECURITY.md#untrusted-models for more details). In a future release, the default value for `weights_only` will be flipped to `True`. This limits the functions that could be executed during unpickling. Arbitrary objects will no longer be allowed to be loaded via this mode unless they are explicitly allowlisted by the user via `torch.serialization.add_safe_globals`. We recommend you start setting `weights_only=True` for any use case where you don't have full control of the loaded file. Please open an issue on GitHub for any issues related to this experimental feature.
  state = torch.load(pretrain_path, map_location='cpu')
Traceback (most recent call last):
  File "/kaggle/working/carla_mama_v1/carla_classification.py", line 214, in <module>
    main()
  File "/kaggle/working/carla_mama_v1/carla_classification.py", line 190, in main
    predictions = get_predictions(p, val_dataloader, model, False, False)
                  ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/utils/_contextlib.py", line 116, in decorate_context
    return func(*args, **kwargs)
           ^^^^^^^^^^^^^^^^^^^^^
  File "/kaggle/working/carla_mama_v1/utils/evaluate_utils.py", line 74, in get_predictions
    res = model(ts.view(bs, h, w), forward_pass='return_all')
          ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/nn/modules/module.py", line 1553, in _wrapped_call_impl
    return self._call_impl(*args, **kwargs)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/nn/modules/module.py", line 1562, in _call_impl
    return forward_call(*args, **kwargs)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/nn/parallel/data_parallel.py", line 186, in forward
    outputs = self.parallel_apply(replicas, inputs, module_kwargs)
              ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/nn/parallel/data_parallel.py", line 201, in parallel_apply
    return parallel_apply(replicas, inputs, kwargs, self.device_ids[:len(replicas)])
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/nn/parallel/parallel_apply.py", line 109, in parallel_apply
    output.reraise()
  File "/usr/local/lib/python3.12/dist-packages/torch/_utils.py", line 706, in reraise
    raise exception
TypeError: Caught TypeError in replica 1 on device 1.
Original Traceback (most recent call last):
  File "/usr/local/lib/python3.12/dist-packages/torch/nn/parallel/parallel_apply.py", line 84, in _worker
    output = module(*input, **kwargs)
             ^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/nn/modules/module.py", line 1553, in _wrapped_call_impl
    return self._call_impl(*args, **kwargs)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/usr/local/lib/python3.12/dist-packages/torch/nn/modules/module.py", line 1562, in _call_impl
    return forward_call(*args, **kwargs)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
TypeError: ClusteringModel.forward() missing 1 required positional argument: 'x'


Max GPU Memory after G-3: 469.48 MB

Running dataset: T-1
Max GPU Memory after T-1: 469.48 MB

Running dataset: T-2
Max GPU Memory after T-2: 469.48 MB

Running dataset: D-8
Max GPU Memory after D-8: 469.48 MB

Running dataset: D-9
Max GPU Memory after D-9: 469.48 MB

Running dataset: F-2
Max GPU Memory after F-2: 469.48 MB

Running dataset: G-4
Max GPU Memory after G-4: 469.48 MB

Running dataset: T-3
Max GPU Memory after T-3: 469.48 MB

Running dataset: D-11
Max GPU Memory after D-11: 469.48 MB

Running dataset: D-12
Max GPU Memory after D-12: 469.48 MB

Running dataset: B-1
Max GPU Memory after B-1: 469.48 MB

Running dataset: G-6
Max GPU Memory after G-6: 469.62 MB

Running dataset: G-7
Max GPU Memory after G-7: 469.62 MB

Running dataset: P-7
Max GPU Memory after P-7: 469.62 MB

Running dataset: R-1
Max GPU Memory after R-1: 469.62 MB

Running dataset: A-5
Max GPU Memory after A-5: 469.62 MB

Running dataset: A-6
Max GPU Memory after A-6: 469.62 MB

Running dataset: A-7
Max GPU Memory after A-7: 469.62 MB

Running dataset: D-13
Max GPU Memory after D-13: 469.62 MB

Running dataset: P-2
Max GPU Memory after P-2: 469.62 MB

Running dataset: A-8
Max GPU Memory after A-8: 469.62 MB

Running dataset: A-9
Max GPU Memory after A-9: 469.62 MB

Running dataset: F-3
Max GPU Memory after F-3: 469.62 MB

==============================
DONE ALL SMAP DATASETS
Total time: 32155.19 s
Avg / dataset: 584.64 s
==============================

Time results saved to results/smap/time_results.json

==============================
STARTING EVALUATION (PAPER STYLE)
==============================
Skip P-1 (missing files)
Skip S-1 (missing files)
Skip E-1 (missing files)
Skip E-2 (missing files)
Skip E-3 (missing files)
Skip E-4 (missing files)
Skip E-5 (missing files)
Skip E-6 (missing files)
Skip E-7 (missing files)
Skip E-8 (missing files)
Skip E-9 (missing files)
Skip E-10 (missing files)
Skip E-11 (missing files)
Skip E-12 (missing files)
Skip E-13 (missing files)
Skip A-1 (missing files)
Skip D-1 (missing files)
Skip P-2 (missing files)
Skip P-3 (missing files)
Skip D-2 (missing files)
Skip D-3 (missing files)
Skip D-4 (missing files)
Skip A-2 (missing files)
Skip A-3 (missing files)
Skip A-4 (missing files)
Skip G-1 (missing files)
Skip G-2 (missing files)
Skip D-5 (missing files)
Skip D-6 (missing files)
Skip D-7 (missing files)
Skip F-1 (missing files)
Skip P-4 (missing files)
Skip G-3 (missing files)
Skip T-1 (missing files)
Skip T-2 (missing files)
Skip D-8 (missing files)
Skip D-9 (missing files)
Skip F-2 (missing files)
Skip G-4 (missing files)
Skip T-3 (missing files)
Skip D-11 (missing files)
Skip D-12 (missing files)
Skip B-1 (missing files)
Skip G-6 (missing files)
Skip G-7 (missing files)
Skip P-7 (missing files)
Skip R-1 (missing files)
Skip A-5 (missing files)
Skip A-6 (missing files)
Skip A-7 (missing files)
Skip D-13 (missing files)
Skip P-2 (missing files)
Skip A-8 (missing files)
Skip A-9 (missing files)
Skip F-3 (missing files)
No results!

fix lỗi missing files và những file chạy bị lỗi