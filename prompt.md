STARTING EXPERIMENTS — Yahoo-A1
273.1s	448	==============================
273.4s	449	GPU available: Tesla T4
273.4s	450	
273.4s	451	Running dataset: real_1.csv
284.2s	452	Error running pretext for real_1.csv: Command '['/usr/bin/python3', 'carla_pretext.py', '--config_env', 'configs/env.yml', '--config_exp', 'configs/pretext/carla_pretext_yahoo.yml', '--fname', 'real_1.csv']' returned non-zero exit status 1.
284.2s	453	Traceback (most recent call last):
284.2s	454	  File "/kaggle/working/carla_mama_v1/carla_pretext.py", line 240, in <module>
284.2s	455	    main()
284.2s	456	  File "/kaggle/working/carla_mama_v1/carla_pretext.py", line 104, in main
284.2s	457	    df = pandas.read_csv(filename)
284.2s	458	         ^^^^^^^^^^^^^^^^^^^^^^^^^
284.2s	459	  File "/usr/local/lib/python3.12/dist-packages/pandas/io/parsers/readers.py", line 1026, in read_csv
284.2s	460	    return _read(filepath_or_buffer, kwds)
284.2s	461	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
284.2s	462	  File "/usr/local/lib/python3.12/dist-packages/pandas/io/parsers/readers.py", line 620, in _read
284.2s	463	    parser = TextFileReader(filepath_or_buffer, **kwds)
284.2s	464	             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
284.2s	465	  File "/usr/local/lib/python3.12/dist-packages/pandas/io/parsers/readers.py", line 1620, in __init__
284.2s	466	    self._engine = self._make_engine(f, self.engine)
284.2s	467	                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
284.2s	468	  File "/usr/local/lib/python3.12/dist-packages/pandas/io/parsers/readers.py", line 1880, in _make_engine
284.2s	469	    self.handles = get_handle(
284.2s	470	                   ^^^^^^^^^^^
284.2s	471	  File "/usr/local/lib/python3.12/dist-packages/pandas/io/common.py", line 873, in get_handle
284.2s	472	    handle = open(
284.2s	473	             ^^^^^
284.2s	474	FileNotFoundError: [Errno 2] No such file or directory: '/kaggle/working/carla_mama_v1/datasets/yahoo/real_1.csv'
284.2s	475	
289.2s	476	Error running classification for real_1.csv: Command '['/usr/bin/python3', 'carla_classification.py', '--config_env', 'configs/env.yml', '--config_exp', 'configs/classification/carla_classification_yahoo.yml', '--fname', 'real_1.csv']' returned non-zero exit status 1.
289.2s	477	Traceback (most recent call last):
289.2s	478	  File "/kaggle/working/carla_mama_v1/carla_classification.py", line 214, in <module>
289.2s	479	    main()
289.2s	480	  File "/kaggle/working/carla_mama_v1/carla_classification.py", line 52, in main
289.2s	481	    train_dataset = get_aug_train_dataset(p, train_transformations, to_neighbors_dataset = True)
289.2s	482	                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
289.2s	483	  File "/kaggle/working/carla_mama_v1/utils/common_config.py", line 174, in get_aug_train_dataset
289.2s	484	    dataloader = torch.load(p['contrastive_dataset'], weights_only=False)
289.2s	485	                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
289.2s	486	  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 1065, in load
289.2s	487	    with _open_file_like(f, 'rb') as opened_file:
289.2s	488	         ^^^^^^^^^^^^^^^^^^^^^^^^
289.2s	489	  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 468, in _open_file_like
289.2s	490	    return _open_file(name_or_buffer, mode)
289.2s	491	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
289.2s	492	  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 449, in __init__
289.2s	493	    super().__init__(open(name, mode))
289.2s	494	                     ^^^^^^^^^^^^^^^^
289.2s	495	FileNotFoundError: [Errno 2] No such file or directory: 'results/yahoo/real_1.csv/pretext/con_train_dataset.pth'
289.2s	496	
289.2s	497	Max GPU Memory after real_1.csv: 0.00 MB
289.2s	498	
289.2s	499	Running dataset: real_2.csv
296.2s	500	Error running pretext for real_2.csv: Command '['/usr/bin/python3', 'carla_pretext.py', '--config_env', 'configs/env.yml', '--config_exp', 'configs/pretext/carla_pretext_yahoo.yml', '--fname', 'real_2.csv']' returned non-zero exit status 1.
296.2s	501	Traceback (most recent call last):
296.2s	502	  File "/kaggle/working/carla_mama_v1/carla_pretext.py", line 240, in <module>
296.2s	503	    main()
296.2s	504	  File "/kaggle/working/carla_mama_v1/carla_pretext.py", line 104, in main
296.2s	505	    df = pandas.read_csv(filename)
296.2s	506	         ^^^^^^^^^^^^^^^^^^^^^^^^^
296.2s	507	  File "/usr/local/lib/python3.12/dist-packages/pandas/io/parsers/readers.py", line 1026, in read_csv
296.2s	508	    return _read(filepath_or_buffer, kwds)
296.2s	509	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
296.2s	510	  File "/usr/local/lib/python3.12/dist-packages/pandas/io/parsers/readers.py", line 620, in _read
296.2s	511	    parser = TextFileReader(filepath_or_buffer, **kwds)
296.2s	512	             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
296.2s	513	  File "/usr/local/lib/python3.12/dist-packages/pandas/io/parsers/readers.py", line 1620, in __init__
296.2s	514	    self._engine = self._make_engine(f, self.engine)
296.2s	515	                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
296.2s	516	  File "/usr/local/lib/python3.12/dist-packages/pandas/io/parsers/readers.py", line 1880, in _make_engine
296.2s	517	    self.handles = get_handle(
296.2s	518	                   ^^^^^^^^^^^
296.2s	519	  File "/usr/local/lib/python3.12/dist-packages/pandas/io/common.py", line 873, in get_handle
296.2s	520	    handle = open(
296.2s	521	             ^^^^^
296.2s	522	FileNotFoundError: [Errno 2] No such file or directory: '/kaggle/working/carla_mama_v1/datasets/yahoo/real_2.csv'
296.2s	523	
301.3s	524	Error running classification for real_2.csv: Command '['/usr/bin/python3', 'carla_classification.py', '--config_env', 'configs/env.yml', '--config_exp', 'configs/classification/carla_classification_yahoo.yml', '--fname', 'real_2.csv']' returned non-zero exit status 1.
301.3s	525	Traceback (most recent call last):
301.3s	526	  File "/kaggle/working/carla_mama_v1/carla_classification.py", line 214, in <module>
301.3s	527	    main()
301.3s	528	  File "/kaggle/working/carla_mama_v1/carla_classification.py", line 52, in main
301.3s	529	    train_dataset = get_aug_train_dataset(p, train_transformations, to_neighbors_dataset = True)
301.3s	530	                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
301.3s	531	  File "/kaggle/working/carla_mama_v1/utils/common_config.py", line 174, in get_aug_train_dataset
301.3s	532	    dataloader = torch.load(p['contrastive_dataset'], weights_only=False)
301.3s	533	                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
301.3s	534	  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 1065, in load
301.3s	535	    with _open_file_like(f, 'rb') as opened_file:
301.3s	536	         ^^^^^^^^^^^^^^^^^^^^^^^^
301.3s	537	  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 468, in _open_file_like
301.3s	538	    return _open_file(name_or_buffer, mode)
301.3s	539	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
301.3s	540	  File "/usr/local/lib/python3.12/dist-packages/torch/serialization.py", line 449, in __init__
301.3s	541	    super().__init__(open(name, mode))
301.3s	542	                     ^^^^^^^^^^^^^^^^
301.3s	543	FileNotFoundError: [Errno 2] No such file or directory: 'results/yahoo/real_2.csv/pretext/con_train_dataset.pth'
301.3s	544	
301.3s	545	Max GPU Memory after real_2.csv: 0.00 MB

link dataset: /kaggle/input/datasets/saostken/yahoo-a1/yahoo_A1/real_1.csv
