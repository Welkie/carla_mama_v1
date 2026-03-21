242.2s	444	Found 67 Yahoo-A1 files: real_1.csv ... real_67.csv
242.2s	445	
242.2s	446	==============================
242.2s	447	STARTING EXPERIMENTS — Yahoo-A1
242.2s	448	==============================
242.4s	449	GPU available: Tesla T4
242.4s	450	
242.4s	451	Running dataset: real_1.csv
252.2s	452	Error running pretext for real_1.csv: Command '['/usr/bin/python3', 'carla_pretext.py', '--config_env', 'configs/env.yml', '--config_exp', 'configs/pretext/carla_pretext_yahoo.yml', '--fname', 'real_1.csv']' returned non-zero exit status 1.
252.2s	453	Traceback (most recent call last):
252.2s	454	  File "/kaggle/working/carla_mama_v1/carla_pretext.py", line 240, in <module>
252.2s	455	    main()
252.2s	456	  File "/kaggle/working/carla_mama_v1/carla_pretext.py", line 134, in main
252.2s	457	    train_dataset = get_train_dataset(p, train_transforms, sanomaly,
252.2s	458	                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
252.2s	459	  File "/kaggle/working/carla_mama_v1/utils/common_config.py", line 154, in get_train_dataset
252.2s	460	    dataset = AugmentedDataset(dataset)
252.2s	461	              ^^^^^^^^^^^^^^^^^^^^^^^^^
252.2s	462	  File "/kaggle/working/carla_mama_v1/data/custom_dataset.py", line 33, in __init__
252.2s	463	    self.create_pairs()
252.2s	464	  File "/kaggle/working/carla_mama_v1/data/custom_dataset.py", line 42, in create_pairs
252.2s	465	    item = self.dataset.__getitem__(index)
252.2s	466	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
252.2s	467	  File "/kaggle/working/carla_mama_v1/data/Yahoo.py", line 78, in __getitem__
252.2s	468	    ts_size = (ts_org.shape[0], ts_org.shape[1])
252.2s	469	                                ~~~~~~~~~~~~^^^
252.2s	470	IndexError: tuple index out of range
252.2s	471	
256.7s	472	Error running classification for real_1.csv: Command '['/usr/bin/python3', 'carla_classification.py', '--config_env', 'configs/env.yml', '--config_exp', 'configs/classification/carla_classification_yahoo.yml', '--fname', 'real_1.csv']' returned non-zero exit status 1.
256.7s	473	Traceback (most recent call last):
256.7s	474	  File "/kaggle/working/carla_mama_v1/carla_classification.py", line 214, in <module>
256.7s	475	    main()
256.7s	476	  File "/kaggle/working/carla_mama_v1/carla_classification.py", line 52, in main
256.7s	477	    train_dataset = get_aug_train_dataset(p, train_transformations, to_neighbors_dataset = True)
256.7s	478	                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
256.7s	479	  File "/kaggle/working/carla_mama_v1/utils/common_config.py", line 174, in get_aug_train_dataset
256.7s	480	    dataloader = torch.load(p['contrastive_dataset'], weights_only=False)
256.7s	481	                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
256.7s	482	  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 1065, in load
256.7s	483	    with _open_file_like(f, 'rb') as opened_file:
256.7s	484	         ^^^^^^^^^^^^^^^^^^^^^^^^
256.7s	485	  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 468, in _open_file_like
256.7s	486	    return _open_file(name_or_buffer, mode)
256.7s	487	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
256.7s	488	  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 449, in __init__
256.7s	489	    super().__init__(open(name, mode))
256.7s	490	                     ^^^^^^^^^^^^^^^^
256.7s	491	FileNotFoundError: [Errno 2] No such file or directory: 'results/yahoo/real_1.csv/pretext/con_train_dataset.pth'
256.7s	492	
256.7s	493	Max GPU Memory after real_1.csv: 0.00 MB
256.7s	494	
256.7s	495	Running dataset: real_2.csv
263.1s	496	Error running pretext for real_2.csv: Command '['/usr/bin/python3', 'carla_pretext.py', '--config_env', 'configs/env.yml', '--config_exp', 'configs/pretext/carla_pretext_yahoo.yml', '--fname', 'real_2.csv']' returned non-zero exit status 1.
263.1s	497	Traceback (most recent call last):
263.1s	498	  File "/kaggle/working/carla_mama_v1/carla_pretext.py", line 240, in <module>
263.1s	499	    main()
263.1s	500	  File "/kaggle/working/carla_mama_v1/carla_pretext.py", line 134, in main
263.1s	501	    train_dataset = get_train_dataset(p, train_transforms, sanomaly,
263.1s	502	                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
263.1s	503	  File "/kaggle/working/carla_mama_v1/utils/common_config.py", line 

lỗi được hiển thị khi tui chạy run_yahoo.py