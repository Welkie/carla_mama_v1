opying real_61.csv ...
267.8s	437	Copying real_62.csv ...
267.8s	438	Copying real_63.csv ...
267.8s	439	Copying real_64.csv ...
267.8s	440	Copying real_65.csv ...
267.8s	441	Copying real_66.csv ...
267.8s	442	Copying real_67.csv ...
267.8s	443	
267.8s	444	Found 67 Yahoo-A1 files: real_1.csv ... real_67.csv
267.8s	445	
267.8s	446	==============================
267.8s	447	STARTING EXPERIMENTS — Yahoo-A1
267.8s	448	==============================
268.1s	449	GPU available: Tesla T4
268.1s	450	
268.1s	451	Running dataset: real_1.csv
278.9s	452	Error running pretext for real_1.csv: Command '['/usr/bin/python3', 'carla_pretext.py', '--config_env', 'configs/env.yml', '--config_exp', 'configs/pretext/carla_pretext_yahoo.yml', '--fname', 'real_1.csv']' returned non-zero exit status 1.
278.9s	453	Traceback (most recent call last):
278.9s	454	  File "/kaggle/working/carla_mama_v1/carla_pretext.py", line 240, in <module>
278.9s	455	    main()
278.9s	456	  File "/kaggle/working/carla_mama_v1/carla_pretext.py", line 134, in main
278.9s	457	    train_dataset = get_train_dataset(p, train_transforms, sanomaly,
278.9s	458	                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
278.9s	459	  File "/kaggle/working/carla_mama_v1/utils/common_config.py", line 154, in get_train_dataset
278.9s	460	    dataset = AugmentedDataset(dataset)
278.9s	461	              ^^^^^^^^^^^^^^^^^^^^^^^^^
278.9s	462	  File "/kaggle/working/carla_mama_v1/data/custom_dataset.py", line 33, in __init__
278.9s	463	    self.create_pairs()
278.9s	464	  File "/kaggle/working/carla_mama_v1/data/custom_dataset.py", line 65, in create_pairs
278.9s	465	    ts_ss_augment = self.subseq_anomaly(ts_org)
278.9s	466	                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^
278.9s	467	  File "/kaggle/working/carla_mama_v1/data/augment.py", line 121, in __call__
278.9s	468	    num_dims = np.random.randint(int(num_features/10), int(num_features/2)) #(int(num_features/5), int(num_features/2))
278.9s	469	               ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
278.9s	470	  File "numpy/random/mtrand.pyx", line 798, in numpy.random.mtrand.RandomState.randint
278.9s	471	  File "numpy/random/_bounded_integers.pyx", line 1334, in numpy.random._bounded_integers._rand_int64
278.9s	472	ValueError: high <= 0
278.9s	473	
283.4s	474	Error running classification for real_1.csv: Command '['/usr/bin/python3', 'carla_classification.py', '--config_env', 'configs/env.yml', '--config_exp', 'configs/classification/carla_classification_yahoo.yml', '--fname', 'real_1.csv']' returned non-zero exit status 1.
283.4s	475	Traceback (most recent call last):
283.4s	476	  File "/kaggle/working/carla_mama_v1/carla_classification.py", line 214, in <module>
283.4s	477	    main()
283.4s	478	  File "/kaggle/working/carla_mama_v1/carla_classification.py", line 52, in main
283.4s	479	    train_dataset = get_aug_train_dataset(p, train_transformations, to_neighbors_dataset = True)
283.4s	480	                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
283.4s	481	  File "/kaggle/working/carla_mama_v1/utils/common_config.py", line 174, in get_aug_train_dataset
283.4s	482	    dataloader = torch.load(p['contrastive_dataset'], weights_only=False)
283.4s	483	                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
283.4s	484	  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 1065, in load
283.4s	485	    with _open_file_like(f, 'rb') as opened_file:
283.4s	486	         ^^^^^^^^^^^^^^^^^^^^^^^^
283.4s	487	  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 468, in _open_file_like
283.4s	488	    return _open_file(name_or_buffer, mode)
283.4s	489	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
283.4s	490	  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 449, in __init__
283.4s	491	    super().__init__(open(name, mode))
283.4s	492	                     ^^^^^^^^^^^^^^^^
283.4s	493	FileNotFoundError: [Errno 2] No such file or directory: 'results/yahoo/real_1.csv/pretext/con_train_dataset.pth'
283.4s	494	
283.4s	495	Max GPU Memory after real_1.csv: 0.00 MB
283.4s	496	
