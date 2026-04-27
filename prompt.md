Your notebook tried to use more disk space than is available.0
Requirement already satisfied: ninja in /usr/local/lib/python3.12/dist-packages (from causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (1.13.0)
184.1s	214	Requirement already satisfied: filelock in /usr/local/lib/python3.12/dist-packages (from torch->causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (3.20.1)
184.1s	215	Requirement already satisfied: typing-extensions>=4.8.0 in /usr/local/lib/python3.12/dist-packages (from torch->causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (4.15.0)
184.1s	216	Requirement already satisfied: sympy in /usr/local/lib/python3.12/dist-packages (from torch->causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (1.13.3)
184.1s	217	Requirement already satisfied: networkx in /usr/local/lib/python3.12/dist-packages (from torch->causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (3.5)
184.1s	218	Requirement already satisfied: jinja2 in /usr/local/lib/python3.12/dist-packages (from torch->causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (3.1.6)
184.1s	219	Requirement already satisfied: fsspec in /usr/local/lib/python3.12/dist-packages (from torch->causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (2025.10.0)
184.1s	220	Requirement already satisfied: setuptools in /usr/local/lib/python3.12/dist-packages (from torch->causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (75.2.0)
184.1s	221	Requirement already satisfied: nvidia-cuda-nvrtc-cu12==12.4.99 in /usr/local/lib/python3.12/dist-packages (from torch->causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (12.4.99)
184.1s	222	Requirement already satisfied: nvidia-cuda-runtime-cu12==12.4.99 in /usr/local/lib/python3.12/dist-packages (from torch->causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (12.4.99)
184.1s	223	Requirement already satisfied: nvidia-cuda-cupti-cu12==12.4.99 in /usr/local/lib/python3.12/dist-packages (from torch->causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (12.4.99)
184.1s	224	Requirement already satisfied: nvidia-cudnn-cu12==9.1.0.70 in /usr/local/lib/python3.12/dist-packages (from torch->causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (9.1.0.70)
184.1s	225	Requirement already satisfied: nvidia-cublas-cu12==12.4.2.65 in /usr/local/lib/python3.12/dist-packages (from torch->causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (12.4.2.65)
184.1s	226	Requirement already satisfied: nvidia-cufft-cu12==11.2.0.44 in /usr/local/lib/python3.12/dist-packages (from torch->causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (11.2.0.44)
184.1s	227	Requirement already satisfied: nvidia-curand-cu12==10.3.5.119 in /usr/local/lib/python3.12/dist-packages (from torch->causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (10.3.5.119)
184.1s	228	Requirement already satisfied: nvidia-cusolver-cu12==11.6.0.99 in /usr/local/lib/python3.12/dist-packages (from torch->causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (11.6.0.99)
184.1s	229	Requirement already satisfied: nvidia-cusparse-cu12==12.3.0.142 in /usr/local/lib/python3.12/dist-packages (from torch->causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (12.3.0.142)
184.1s	230	Requirement already satisfied: nvidia-nccl-cu12==2.20.5 in /usr/local/lib/python3.12/dist-packages (from torch->causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (2.20.5)
184.1s	231	Requirement already satisfied: nvidia-nvtx-cu12==12.4.99 in /usr/local/lib/python3.12/dist-packages (from torch->causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (12.4.99)
184.1s	232	Requirement already satisfied: nvidia-nvjitlink-cu12==12.4.99 in /usr/local/lib/python3.12/dist-packages (from torch->causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (12.4.99)
184.1s	233	Requirement already satisfied: triton==3.0.0 in /usr/local/lib/python3.12/dist-packages (from torch->causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (3.0.0)
184.2s	234	Requirement already satisfied: MarkupSafe>=2.0 in /usr/local/lib/python3.12/dist-packages (from jinja2->torch->causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (3.0.3)
184.2s	235	Requirement already satisfied: mpmath<1.4,>=1.1.0 in /usr/local/lib/python3.12/dist-packages (from sympy->torch->causal-conv1d==1.5.2+cu12torch2.4cxx11abiFALSE) (1.3.0)
186.0s	236	Installing collected packages: causal-conv1d
188.4s	237	Successfully installed causal-conv1d-1.5.2
189.7s	238	Processing ./mamba_ssm-2.2.5+cu12torch2.4cxx11abiFALSE-cp312-cp312-linux_x86_64.whl
190.9s	239	Requirement already satisfied: torch in /usr/local/lib/python3.12/dist-packages (from mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (2.4.1+cu124)
190.9s	240	Requirement already satisfied: triton in /usr/local/lib/python3.12/dist-packages (from mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (3.0.0)
190.9s	241	Requirement already satisfied: ninja in /usr/local/lib/python3.12/dist-packages (from mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (1.13.0)
190.9s	242	Requirement already satisfied: einops in /usr/local/lib/python3.12/dist-packages (from mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (0.8.1)
190.9s	243	Requirement already satisfied: transformers in /usr/local/lib/python3.12/dist-packages (from mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (4.38.2)
190.9s	244	Requirement already satisfied: packaging in /usr/local/lib/python3.12/dist-packages (from mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (25.0)
190.9s	245	Requirement already satisfied: setuptools>=61.0.0 in /usr/local/lib/python3.12/dist-packages (from mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (75.2.0)
190.9s	246	Requirement already satisfied: filelock in /usr/local/lib/python3.12/dist-packages (from torch->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (3.20.1)
190.9s	247	Requirement already satisfied: typing-extensions>=4.8.0 in /usr/local/lib/python3.12/dist-packages (from torch->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (4.15.0)
190.9s	248	Requirement already satisfied: sympy in /usr/local/lib/python3.12/dist-packages (from torch->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (1.13.3)
190.9s	249	Requirement already satisfied: networkx in /usr/local/lib/python3.12/dist-packages (from torch->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (3.5)
190.9s	250	Requirement already satisfied: jinja2 in /usr/local/lib/python3.12/dist-packages (from torch->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (3.1.6)
190.9s	251	Requirement already satisfied: fsspec in /usr/local/lib/python3.12/dist-packages (from torch->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (2025.10.0)
190.9s	252	Requirement already satisfied: nvidia-cuda-nvrtc-cu12==12.4.99 in /usr/local/lib/python3.12/dist-packages (from torch->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (12.4.99)
190.9s	253	Requirement already satisfied: nvidia-cuda-runtime-cu12==12.4.99 in /usr/local/lib/python3.12/dist-packages (from torch->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (12.4.99)
190.9s	254	Requirement already satisfied: nvidia-cuda-cupti-cu12==12.4.99 in /usr/local/lib/python3.12/dist-packages (from torch->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (12.4.99)
190.9s	255	Requirement already satisfied: nvidia-cudnn-cu12==9.1.0.70 in /usr/local/lib/python3.12/dist-packages (from torch->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (9.1.0.70)
190.9s	256	Requirement already satisfied: nvidia-cublas-cu12==12.4.2.65 in /usr/local/lib/python3.12/dist-packages (from torch->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (12.4.2.65)
190.9s	257	Requirement already satisfied: nvidia-cufft-cu12==11.2.0.44 in /usr/local/lib/python3.12/dist-packages (from torch->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (11.2.0.44)
190.9s	258	Requirement already satisfied: nvidia-curand-cu12==10.3.5.119 in /usr/local/lib/python3.12/dist-packages (from torch->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (10.3.5.119)
190.9s	259	Requirement already satisfied: nvidia-cusolver-cu12==11.6.0.99 in /usr/local/lib/python3.12/dist-packages (from torch->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (11.6.0.99)
190.9s	260	Requirement already satisfied: nvidia-cusparse-cu12==12.3.0.142 in /usr/local/lib/python3.12/dist-packages (from torch->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (12.3.0.142)
190.9s	261	Requirement already satisfied: nvidia-nccl-cu12==2.20.5 in /usr/local/lib/python3.12/dist-packages (from torch->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (2.20.5)
190.9s	262	Requirement already satisfied: nvidia-nvtx-cu12==12.4.99 in /usr/local/lib/python3.12/dist-packages (from torch->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (12.4.99)
190.9s	263	Requirement already satisfied: nvidia-nvjitlink-cu12==12.4.99 in /usr/local/lib/python3.12/dist-packages (from torch->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (12.4.99)
191.0s	264	Requirement already satisfied: huggingface-hub<1.0,>=0.19.3 in /usr/local/lib/python3.12/dist-packages (from transformers->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (0.36.0)
191.0s	265	Requirement already satisfied: numpy>=1.17 in /usr/local/lib/python3.12/dist-packages (from transformers->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (2.0.2)
191.0s	266	Requirement already satisfied: pyyaml>=5.1 in /usr/local/lib/python3.12/dist-packages (from transformers->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (6.0.3)
191.0s	267	Requirement already satisfied: regex!=2019.12.17 in /usr/local/lib/python3.12/dist-packages (from transformers->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (2025.11.3)
191.0s	268	Requirement already satisfied: requests in /usr/local/lib/python3.12/dist-packages (from transformers->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (2.32.5)
191.0s	269	Requirement already satisfied: tokenizers<0.19,>=0.14 in /usr/local/lib/python3.12/dist-packages (from transformers->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (0.15.2)
191.0s	270	Requirement already satisfied: safetensors>=0.4.1 in /usr/local/lib/python3.12/dist-packages (from transformers->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (0.6.2)
191.0s	271	Requirement already satisfied: tqdm>=4.27 in /usr/local/lib/python3.12/dist-packages (from transformers->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (4.67.1)
191.0s	272	Requirement already satisfied: hf-xet<2.0.0,>=1.1.3 in /usr/local/lib/python3.12/dist-packages (from huggingface-hub<1.0,>=0.19.3->transformers->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (1.2.1rc0)
191.1s	273	Requirement already satisfied: MarkupSafe>=2.0 in /usr/local/lib/python3.12/dist-packages (from jinja2->torch->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (3.0.3)
191.1s	274	Requirement already satisfied: charset_normalizer<4,>=2 in /usr/local/lib/python3.12/dist-packages (from requests->transformers->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (3.4.4)
191.1s	275	Requirement already satisfied: idna<4,>=2.5 in /usr/local/lib/python3.12/dist-packages (from requests->transformers->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (3.11)
191.1s	276	Requirement already satisfied: urllib3<3,>=1.21.1 in /usr/local/lib/python3.12/dist-packages (from requests->transformers->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (2.6.2)
191.1s	277	Requirement already satisfied: certifi>=2017.4.17 in /usr/local/lib/python3.12/dist-packages (from requests->transformers->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (2025.11.12)
191.1s	278	Requirement already satisfied: mpmath<1.4,>=1.1.0 in /usr/local/lib/python3.12/dist-packages (from sympy->torch->mamba-ssm==2.2.5+cu12torch2.4cxx11abiFALSE) (1.3.0)
192.9s	279	Installing collected packages: mamba-ssm
198.0s	280	Successfully installed mamba-ssm-2.2.5
204.0s	281	OK
204.2s	282	Cloning into 'carla_mama_v1'...
204.7s	283	remote: Enumerating objects: 368, done.[K
204.7s	284	remote: Counting objects:   0% (1/154)[K
remote: Counting objects:   1% (2/154)[K
remote: Counting objects:   2% (4/154)[K
remote: Counting objects:   3% (5/154)[K
remote: Counting objects:   4% (7/154)[K
remote: Counting objects:   5% (8/154)[K
remote: Counting objects:   6% (10/154)[K
remote: Counting objects:   7% (11/154)[K
remote: Counting objects:   8% (13/154)[K
remote: Counting objects:   9% (14/154)[K
remote: Counting objects:  10% (16/154)[K
remote: Counting objects:  11% (17/154)[K
remote: Counting objects:  12% (19/154)[K
remote: Counting objects:  13% (21/154)[K
remote: Counting objects:  14% (22/154)[K
remote: Counting objects:  15% (24/154)[K
remote: Counting objects:  16% (25/154)[K
remote: Counting objects:  17% (27/154)[K
remote: Counting objects:  18% (28/154)[K
remote: Counting objects:  19% (30/154)[K
remote: Counting objects:  20% (31/154)[K
remote: Counting objects:  21% (33/154)[K
remote: Counting objects:  22% (34/154)[K
remote: Counting objects:  23% (36/154)[K
remote: Counting objects:  24% (37/154)[K
remote: Counting objects:  25% (39/154)[K
remote: Counting objects:  26% (41/154)[K
remote: Counting objects:  27% (42/154)[K
remote: Counting objects:  28% (44/154)[K
remote: Counting objects:  29% (45/154)[K
remote: Counting objects:  30% (47/154)[K
remote: Counting objects:  31% (48/154)[K
remote: Counting objects:  32% (50/154)[K
remote: Counting objects:  33% (51/154)[K
remote: Counting objects:  34% (53/154)[K
remote: Counting objects:  35% (54/154)[K
remote: Counting objects:  36% (56/154)[K
remote: Counting objects:  37% (57/154)[K
remote: Counting objects:  38% (59/154)[K
remote: Counting objects:  39% (61/154)[K
remote: Counting objects:  40% (62/154)[K
remote: Counting objects:  41% (64/154)[K
remote: Counting objects:  42% (65/154)[K
remote: Counting objects:  43% (67/154)[K
remote: Counting objects:  44% (68/154)[K
remote: Counting objects:  45% (70/154)[K
remote: Counting objects:  46% (71/154)[K
remote: Counting objects:  47% (73/154)[K
remote: Counting objects:  48% (74/154)[K
remote: Counting objects:  49% (76/154)[K
remote: Counting objects:  50% (77/154)[K
remote: Counting objects:  51% (79/154)[K
remote: Counting objects:  52% (81/154)[K
remote: Counting objects:  53% (82/154)[K
remote: Counting objects:  54% (84/154)[K
remote: Counting objects:  55% (85/154)[K
remote: Counting objects:  56% (87/154)[K
remote: Counting objects:  57% (88/154)[K
remote: Counting objects:  58% (90/154)[K
remote: Counting objects:  59% (91/154)[K
remote: Counting objects:  60% (93/154)[K
remote: Counting objects:  61% (94/154)[K
remote: Counting objects:  62% (96/154)[K
remote: Counting objects:  63% (98/154)[K
remote: Counting objects:  64% (99/154)[K
remote: Counting objects:  65% (101/154)[K
remote: Counting objects:  66% (102/154)[K
remote: Counting objects:  67% (104/154)[K
remote: Counting objects:  68% (105/154)[K
remote: Counting objects:  69% (107/154)[K
remote: Counting objects:  70% (108/154)[K
remote: Counting objects:  71% (110/154)[K
remote: Counting objects:  72% (111/154)[K
remote: Counting objects:  73% (113/154)[K
remote: Counting objects:  74% (114/154)[K
remote: Counting objects:  75% (116/154)[K
remote: Counting objects:  76% (118/154)[K
remote: Counting objects:  77% (119/154)[K
remote: Counting objects:  78% (121/154)[K
remote: Counting objects:  79% (122/154)[K
remote: Counting objects:  80% (124/154)[K
remote: Counting objects:  81% (125/154)[K
remote: Counting objects:  82% (127/154)[K
remote: Counting objects:  83% (128/154)[K
remote: Counting objects:  84% (130/154)[K
remote: Counting objects:  85% (131/154)[K
remote: Counting objects:  86% (133/154)[K
remote: Counting objects:  87% (134/154)[K
remote: Counting objects:  88% (136/154)[K
remote: Counting objects:  89% (138/154)[K
remote: Counting objects:  90% (139/154)[K
remote: Counting objects:  91% (141/154)[K
remote: Counting objects:  92% (142/154)[K
remote: Counting objects:  93% (144/154)[K
remote: Counting objects:  94% (145/154)[K
remote: Counting objects:  95% (147/154)[K
remote: Counting objects:  96% (148/154)[K
remote: Counting objects:  97% (150/154)[K
remote: Counting objects:  98% (151/154)[K
remote: Counting objects:  99% (153/154)[K
remote: Counting objects: 100% (154/154)[K
remote: Counting objects: 100% (154/154), done.[K
204.8s	285	remote: Compressing objects:   0% (1/108)[K
remote: Compressing objects:   1% (2/108)[K
remote: Compressing objects:   2% (3/108)[K
remote: Compressing objects:   3% (4/108)[K
remote: Compressing objects:   4% (5/108)[K
remote: Compressing objects:   5% (6/108)[K
remote: Compressing objects:   6% (7/108)[K
remote: Compressing objects:   7% (8/108)[K
remote: Compressing objects:   8% (9/108)[K
remote: Compressing objects:   9% (10/108)[K
remote: Compressing objects:  10% (11/108)[K
remote: Compressing objects:  11% (12/108)[K
remote: Compressing objects:  12% (13/108)[K
remote: Compressing objects:  13% (15/108)[K
remote: Compressing objects:  14% (16/108)[K
remote: Compressing objects:  15% (17/108)[K
remote: Compressing objects:  16% (18/108)[K
remote: Compressing objects:  17% (19/108)[K
remote: Compressing objects:  18% (20/108)[K
remote: Compressing objects:  19% (21/108)[K
remote: Compressing objects:  20% (22/108)[K
remote: Compressing objects:  21% (23/108)[K
remote: Compressing objects:  22% (24/108)[K
remote: Compressing objects:  23% (25/108)[K
remote: Compressing objects:  24% (26/108)[K
remote: Compressing objects:  25% (27/108)[K
remote: Compressing objects:  26% (29/108)[K
remote: Compressing objects:  27% (30/108)[K
remote: Compressing objects:  28% (31/108)[K
remote: Compressing objects:  29% (32/108)[K
remote: Compressing objects:  30% (33/108)[K
remote: Compressing objects:  31% (34/108)[K
remote: Compressing objects:  32% (35/108)[K
remote: Compressing objects:  33% (36/108)[K
remote: Compressing objects:  34% (37/108)[K
remote: Compressing objects:  35% (38/108)[K
remote: Compressing objects:  36% (39/108)[K
remote: Compressing objects:  37% (40/108)[K
remote: Compressing objects:  38% (42/108)[K
remote: Compressing objects:  39% (43/108)[K
remote: Compressing objects:  40% (44/108)[K
remote: Compressing objects:  41% (45/108)[K
remote: Compressing objects:  42% (46/108)[K
remote: Compressing objects:  43% (47/108)[K
remote: Compressing objects:  44% (48/108)[K
remote: Compressing objects:  45% (49/108)[K
remote: Compressing objects:  46% (50/108)[K
remote: Compressing objects:  47% (51/108)[K
remote: Compressing objects:  48% (52/108)[K
remote: Compressing objects:  49% (53/108)[K
remote: Compressing objects:  50% (54/108)[K
remote: Compressing objects:  51% (56/108)[K
remote: Compressing objects:  52% (57/108)[K
remote: Compressing objects:  53% (58/108)[K
remote: Compressing objects:  54% (59/108)[K
remote: Compressing objects:  55% (60/108)[K
remote: Compressing objects:  56% (61/108)[K
remote: Compressing objects:  57% (62/108)[K
remote: Compressing objects:  58% (63/108)[K
remote: Compressing objects:  59% (64/108)[K
remote: Compressing objects:  60% (65/108)[K
remote: Compressing objects:  61% (66/108)[K
remote: Compressing objects:  62% (67/108)[K
remote: Compressing objects:  63% (69/108)[K
remote: Compressing objects:  64% (70/108)[K
remote: Compressing objects:  65% (71/108)[K
remote: Compressing objects:  66% (72/108)[K
remote: Compressing objects:  67% (73/108)[K
remote: Compressing objects:  68% (74/108)[K
remote: Compressing objects:  69% (75/108)[K
remote: Compressing objects:  70% (76/108)[K
remote: Compressing objects:  71% (77/108)[K
remote: Compressing objects:  72% (78/108)[K
remote: Compressing objects:  73% (79/108)[K
remote: Compressing objects:  74% (80/108)[K
remote: Compressing objects:  75% (81/108)[K
remote: Compressing objects:  76% (83/108)[K
remote: Compressing objects:  77% (84/108)[K
remote: Compressing objects:  78% (85/108)[K
remote: Compressing objects:  79% (86/108)[K
remote: Compressing objects:  80% (87/108)[K
remote: Compressing objects:  81% (88/108)[K
remote: Compressing objects:  82% (89/108)[K
remote: Compressing objects:  83% (90/108)[K
remote: Compressing objects:  84% (91/108)[K
remote: Compressing objects:  85% (92/108)[K
remote: Compressing objects:  86% (93/108)[K
remote: Compressing objects:  87% (94/108)[K
remote: Compressing objects:  88% (96/108)[K
remote: Compressing objects:  89% (97/108)[K
remote: Compressing objects:  90% (98/108)[K
remote: Compressing objects:  91% (99/108)[K
remote: Compressing objects:  92% (100/108)[K
remote: Compressing objects:  93% (101/108)[K
remote: Compressing objects:  94% (102/108)[K
remote: Compressing objects:  95% (103/108)[K
remote: Compressing objects:  96% (104/108)[K
remote: Compressing objects:  97% (105/108)[K
remote: Compressing objects:  98% (106/108)[K
remote: Compressing objects:  99% (107/108)[K
remote: Compressing objects: 100% (108/108)[K
remote: Compressing objects: 100% (108/108), done.[K
208.8s	286	Receiving objects:   0% (1/368)
Receiving objects:   1% (4/368)
Receiving objects:   2% (8/368)
Receiving objects:   3% (12/368)
Receiving objects:   4% (15/368)
Receiving objects:   5% (19/368)
Receiving objects:   6% (23/368)
Receiving objects:   7% (26/368)
Receiving objects:   8% (30/368)
Receiving objects:   9% (34/368)
Receiving objects:  10% (37/368)
Receiving objects:  11% (41/368)
Receiving objects:  12% (45/368)
Receiving objects:  13% (48/368)
Receiving objects:  14% (52/368)
Receiving objects:  15% (56/368)
Receiving objects:  16% (59/368)
Receiving objects:  17% (63/368)
Receiving objects:  18% (67/368)
Receiving objects:  19% (70/368)
Receiving objects:  20% (74/368)
Receiving objects:  21% (78/368)
Receiving objects:  22% (81/368)
Receiving objects:  23% (85/368)
Receiving objects:  24% (89/368)
Receiving objects:  25% (92/368)
Receiving objects:  26% (96/368)
Receiving objects:  27% (100/368)
Receiving objects:  28% (104/368)
Receiving objects:  29% (107/368)
Receiving objects:  30% (111/368)
Receiving objects:  31% (115/368)
Receiving objects:  32% (118/368)
Receiving objects:  33% (122/368), 8.30 MiB | 16.58 MiB/s
Receiving objects:  33% (123/368), 18.79 MiB | 18.78 MiB/s
Receiving objects:  34% (126/368), 18.79 MiB | 18.78 MiB/s
Receiving objects:  35% (129/368), 18.79 MiB | 18.78 MiB/s
Receiving objects:  36% (133/368), 29.10 MiB | 19.40 MiB/s
Receiving objects:  36% (135/368), 39.98 MiB | 19.98 MiB/s
Receiving objects:  37% (137/368), 39.98 MiB | 19.98 MiB/s
Receiving objects:  38% (140/368), 39.98 MiB | 19.98 MiB/s
Receiving objects:  39% (144/368), 50.16 MiB | 20.06 MiB/s
Receiving objects:  40% (148/368), 50.16 MiB | 20.06 MiB/s
Receiving objects:  41% (151/368), 50.16 MiB | 20.06 MiB/s
Receiving objects:  42% (155/368), 50.16 MiB | 20.06 MiB/s
Receiving objects:  43% (159/368), 50.16 MiB | 20.06 MiB/s
Receiving objects:  44% (162/368), 50.16 MiB | 20.06 MiB/s
Receiving objects:  45% (166/368), 50.16 MiB | 20.06 MiB/s
Receiving objects:  46% (170/368), 50.16 MiB | 20.06 MiB/s
Receiving objects:  47% (173/368), 50.16 MiB | 20.06 MiB/s
Receiving objects:  48% (177/368), 50.16 MiB | 20.06 MiB/s
Receiving objects:  48% (180/368), 50.16 MiB | 20.06 MiB/s
Receiving objects:  49% (181/368), 67.60 MiB | 22.53 MiB/s
Receiving objects:  50% (184/368), 67.60 MiB | 22.53 MiB/s
Receiving objects:  51% (188/368), 67.60 MiB | 22.53 MiB/s
Receiving objects:  52% (192/368), 88.17 MiB | 25.19 MiB/s
Receiving objects:  53% (196/368), 88.17 MiB | 25.19 MiB/s
Receiving objects:  54% (199/368), 88.17 MiB | 25.19 MiB/s
Receiving objects:  54% (199/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  55% (203/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  56% (207/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  57% (210/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  58% (214/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  59% (218/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  60% (221/368), 106.19 MiB | 26.54 MiB/s
remote: Total 368 (delta 90), reused 97 (delta 46), pack-reused 214 (from 2)[K
208.8s	287	Receiving objects:  61% (225/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  62% (229/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  63% (232/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  64% (236/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  65% (240/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  66% (243/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  67% (247/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  68% (251/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  69% (254/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  70% (258/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  71% (262/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  72% (265/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  73% (269/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  74% (273/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  75% (276/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  76% (280/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  77% (284/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  78% (288/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  79% (291/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  80% (295/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  81% (299/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  82% (302/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  83% (306/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  84% (310/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  85% (313/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  86% (317/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  87% (321/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  88% (324/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  89% (328/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  90% (332/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  91% (335/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  92% (339/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  93% (343/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  94% (346/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  95% (350/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  96% (354/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  97% (357/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  98% (361/368), 106.19 MiB | 26.54 MiB/s
Receiving objects:  99% (365/368), 106.19 MiB | 26.54 MiB/s
Receiving objects: 100% (368/368), 106.19 MiB | 26.54 MiB/s
Receiving objects: 100% (368/368), 107.74 MiB | 26.59 MiB/s, done.
210.0s	288	Resolving deltas:   0% (0/155)
Resolving deltas:   1% (2/155)
Resolving deltas:   2% (4/155)
Resolving deltas:   3% (5/155)
Resolving deltas:   4% (7/155)
Resolving deltas:   5% (8/155)
Resolving deltas:   6% (10/155)
Resolving deltas:   7% (11/155)
Resolving deltas:   8% (13/155)
Resolving deltas:   9% (14/155)
Resolving deltas:  10% (16/155)
Resolving deltas:  11% (18/155)
Resolving deltas:  12% (19/155)
Resolving deltas:  13% (21/155)
Resolving deltas:  14% (22/155)
Resolving deltas:  15% (24/155)
Resolving deltas:  16% (25/155)
Resolving deltas:  17% (27/155)
Resolving deltas:  18% (28/155)
Resolving deltas:  19% (30/155)
Resolving deltas:  20% (31/155)
Resolving deltas:  21% (33/155)
Resolving deltas:  22% (35/155)
Resolving deltas:  23% (36/155)
Resolving deltas:  24% (38/155)
Resolving deltas:  24% (38/155)
Resolving deltas:  25% (39/155)
Resolving deltas:  26% (41/155)
Resolving deltas:  27% (42/155)
Resolving deltas:  28% (44/155)
Resolving deltas:  29% (45/155)
Resolving deltas:  30% (47/155)
Resolving deltas:  31% (49/155)
Resolving deltas:  32% (50/155)
Resolving deltas:  33% (52/155)
Resolving deltas:  34% (53/155)
Resolving deltas:  35% (55/155)
Resolving deltas:  36% (56/155)
Resolving deltas:  37% (58/155)
Resolving deltas:  38% (59/155)
Resolving deltas:  39% (61/155)
Resolving deltas:  40% (62/155)
Resolving deltas:  41% (64/155)
Resolving deltas:  42% (66/155)
Resolving deltas:  43% (67/155)
Resolving deltas:  44% (69/155)
Resolving deltas:  45% (70/155)
Resolving deltas:  46% (72/155)
Resolving deltas:  47% (73/155)
Resolving deltas:  48% (75/155)
Resolving deltas:  49% (76/155)
Resolving deltas:  50% (78/155)
Resolving deltas:  51% (80/155)
Resolving deltas:  52% (81/155)
Resolving deltas:  53% (83/155)
Resolving deltas:  54% (84/155)
Resolving deltas:  55% (86/155)
Resolving deltas:  56% (87/155)
Resolving deltas:  57% (89/155)
Resolving deltas:  58% (90/155)
Resolving deltas:  59% (92/155)
Resolving deltas:  60% (93/155)
Resolving deltas:  61% (95/155)
Resolving deltas:  62% (97/155)
Resolving deltas:  63% (98/155)
Resolving deltas:  64% (100/155)
Resolving deltas:  65% (101/155)
Resolving deltas:  66% (103/155)
Resolving deltas:  67% (104/155)
Resolving deltas:  68% (106/155)
Resolving deltas:  69% (107/155)
Resolving deltas:  70% (109/155)
Resolving deltas:  71% (111/155)
Resolving deltas:  72% (112/155)
Resolving deltas:  73% (114/155)
Resolving deltas:  74% (115/155)
Resolving deltas:  75% (117/155)
Resolving deltas:  76% (118/155)
Resolving deltas:  77% (120/155)
Resolving deltas:  78% (121/155)
Resolving deltas:  79% (123/155)
Resolving deltas:  80% (124/155)
Resolving deltas:  81% (126/155)
Resolving deltas:  82% (128/155)
Resolving deltas:  83% (129/155)
Resolving deltas:  84% (131/155)
Resolving deltas:  85% (132/155)
Resolving deltas:  86% (134/155)
Resolving deltas:  87% (135/155)
Resolving deltas:  88% (137/155)
Resolving deltas:  89% (138/155)
Resolving deltas:  90% (140/155)
Resolving deltas:  91% (142/155)
Resolving deltas:  92% (143/155)
Resolving deltas:  93% (145/155)
Resolving deltas:  94% (146/155)
Resolving deltas:  95% (148/155)
Resolving deltas:  96% (149/155)
Resolving deltas:  97% (151/155)
Resolving deltas:  98% (152/155)
Resolving deltas:  99% (154/155)
Resolving deltas: 100% (155/155)
Resolving deltas: 100% (155/155), done.
210.6s	289	/kaggle/working/carla_mama_v1
211.8s	290	Requirement already satisfied: numpy>=1.24.0 in /usr/local/lib/python3.12/dist-packages (from -r requirements.txt (line 18)) (2.0.2)
211.8s	291	Requirement already satisfied: pandas>=2.1.0 in /usr/local/lib/python3.12/dist-packages (from -r requirements.txt (line 19)) (2.2.2)
211.8s	292	Requirement already satisfied: scipy>=1.10 in /usr/local/lib/python3.12/dist-packages (from -r requirements.txt (line 20)) (1.15.3)
211.8s	293	Requirement already satisfied: scikit-learn in /usr/local/lib/python3.12/dist-packages (from -r requirements.txt (line 21)) (1.6.1)
211.8s	294	Requirement already satisfied: PyYAML>=6.0 in /usr/local/lib/python3.12/dist-packages (from -r requirements.txt (line 24)) (6.0.3)
212.0s	295	Collecting easydict==1.10 (from -r requirements.txt (line 25))
212.1s	296	  Downloading easydict-1.10.tar.gz (6.4 kB)
213.0s	297	  Preparing metadata (setup.py) ... [?25l[?25hdone
213.1s	298	Collecting termcolor==2.4.0 (from -r requirements.txt (line 26))
213.1s	299	  Downloading termcolor-2.4.0-py3-none-any.whl.metadata (6.1 kB)
213.1s	300	Requirement already satisfied: tqdm>=4.66.0 in /usr/local/lib/python3.12/dist-packages (from -r requirements.txt (line 27)) (4.67.1)
213.1s	301	Requirement already satisfied: matplotlib>=3.7.0 in /usr/local/lib/python3.12/dist-packages (from -r requirements.txt (line 30)) (3.10.0)
213.2s	302	Collecting seaborn==0.13.0 (from -r requirements.txt (line 31))
213.2s	303	  Downloading seaborn-0.13.0-py3-none-any.whl.metadata (5.3 kB)
213.2s	304	Requirement already satisfied: torchmetrics>=1.0.1 in /usr/local/lib/python3.12/dist-packages (from -r requirements.txt (line 34)) (1.8.2)
213.3s	305	Collecting faiss-cpu (from -r requirements.txt (line 37))
213.3s	306	  Downloading faiss_cpu-1.13.2-cp310-abi3-manylinux_2_27_x86_64.manylinux_2_28_x86_64.whl.metadata (7.6 kB)
213.3s	307	Requirement already satisfied: python-dateutil>=2.8.2 in /usr/local/lib/python3.12/dist-packages (from pandas>=2.1.0->-r requirements.txt (line 19)) (2.9.0.post0)
213.3s	308	Requirement already satisfied: pytz>=2020.1 in /usr/local/lib/python3.12/dist-packages (from pandas>=2.1.0->-r requirements.txt (line 19)) (2025.2)
213.3s	309	Requirement already satisfied: tzdata>=2022.7 in /usr/local/lib/python3.12/dist-packages (from pandas>=2.1.0->-r requirements.txt (line 19)) (2025.3)
213.4s	310	Requirement already satisfied: joblib>=1.2.0 in /usr/local/lib/python3.12/dist-packages (from scikit-learn->-r requirements.txt (line 21)) (1.5.3)
213.4s	311	Requirement already satisfied: threadpoolctl>=3.1.0 in /usr/local/lib/python3.12/dist-packages (from scikit-learn->-r requirements.txt (line 21)) (3.6.0)
213.4s	312	Requirement already satisfied: contourpy>=1.0.1 in /usr/local/lib/python3.12/dist-packages (from matplotlib>=3.7.0->-r requirements.txt (line 30)) (1.3.3)
213.4s	313	Requirement already satisfied: cycler>=0.10 in /usr/local/lib/python3.12/dist-packages (from matplotlib>=3.7.0->-r requirements.txt (line 30)) (0.12.1)
213.4s	314	Requirement already satisfied: fonttools>=4.22.0 in /usr/local/lib/python3.12/dist-packages (from matplotlib>=3.7.0->-r requirements.txt (line 30)) (4.60.1)
213.4s	315	Requirement already satisfied: kiwisolver>=1.3.1 in /usr/local/lib/python3.12/dist-packages (from matplotlib>=3.7.0->-r requirements.txt (line 30)) (1.4.9)
213.4s	316	Requirement already satisfied: packaging>=20.0 in /usr/local/lib/python3.12/dist-packages (from matplotlib>=3.7.0->-r requirements.txt (line 30)) (25.0)
213.4s	317	Requirement already satisfied: pillow>=8 in /usr/local/lib/python3.12/dist-packages (from matplotlib>=3.7.0->-r requirements.txt (line 30)) (11.3.0)
213.4s	318	Requirement already satisfied: pyparsing>=2.3.1 in /usr/local/lib/python3.12/dist-packages (from matplotlib>=3.7.0->-r requirements.txt (line 30)) (3.2.5)
213.4s	319	Requirement already satisfied: torch>=2.0.0 in /usr/local/lib/python3.12/dist-packages (from torchmetrics>=1.0.1->-r requirements.txt (line 34)) (2.4.1+cu124)
213.4s	320	Requirement already satisfied: lightning-utilities>=0.8.0 in /usr/local/lib/python3.12/dist-packages (from torchmetrics>=1.0.1->-r requirements.txt (line 34)) (0.15.2)
213.4s	321	Requirement already satisfied: setuptools in /usr/local/lib/python3.12/dist-packages (from lightning-utilities>=0.8.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (75.2.0)
213.4s	322	Requirement already satisfied: typing_extensions in /usr/local/lib/python3.12/dist-packages (from lightning-utilities>=0.8.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (4.15.0)
213.5s	323	Requirement already satisfied: six>=1.5 in /usr/local/lib/python3.12/dist-packages (from python-dateutil>=2.8.2->pandas>=2.1.0->-r requirements.txt (line 19)) (1.17.0)
213.5s	324	Requirement already satisfied: filelock in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (3.20.1)
213.5s	325	Requirement already satisfied: sympy in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (1.13.3)
213.5s	326	Requirement already satisfied: networkx in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (3.5)
213.5s	327	Requirement already satisfied: jinja2 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (3.1.6)
213.5s	328	Requirement already satisfied: fsspec in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (2025.10.0)
213.5s	329	Requirement already satisfied: nvidia-cuda-nvrtc-cu12==12.4.99 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (12.4.99)
213.5s	330	Requirement already satisfied: nvidia-cuda-runtime-cu12==12.4.99 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (12.4.99)
213.5s	331	Requirement already satisfied: nvidia-cuda-cupti-cu12==12.4.99 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (12.4.99)
213.5s	332	Requirement already satisfied: nvidia-cudnn-cu12==9.1.0.70 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (9.1.0.70)
213.5s	333	Requirement already satisfied: nvidia-cublas-cu12==12.4.2.65 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (12.4.2.65)
213.5s	334	Requirement already satisfied: nvidia-cufft-cu12==11.2.0.44 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (11.2.0.44)
213.5s	335	Requirement already satisfied: nvidia-curand-cu12==10.3.5.119 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (10.3.5.119)
213.5s	336	Requirement already satisfied: nvidia-cusolver-cu12==11.6.0.99 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (11.6.0.99)
213.5s	337	Requirement already satisfied: nvidia-cusparse-cu12==12.3.0.142 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (12.3.0.142)
213.5s	338	Requirement already satisfied: nvidia-nccl-cu12==2.20.5 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (2.20.5)
213.5s	339	Requirement already satisfied: nvidia-nvtx-cu12==12.4.99 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (12.4.99)
213.5s	340	Requirement already satisfied: nvidia-nvjitlink-cu12==12.4.99 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (12.4.99)
213.5s	341	Requirement already satisfied: triton==3.0.0 in /usr/local/lib/python3.12/dist-packages (from torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (3.0.0)
213.6s	342	Requirement already satisfied: MarkupSafe>=2.0 in /usr/local/lib/python3.12/dist-packages (from jinja2->torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (3.0.3)
213.6s	343	Requirement already satisfied: mpmath<1.4,>=1.1.0 in /usr/local/lib/python3.12/dist-packages (from sympy->torch>=2.0.0->torchmetrics>=1.0.1->-r requirements.txt (line 34)) (1.3.0)
213.6s	344	Downloading termcolor-2.4.0-py3-none-any.whl (7.7 kB)
213.6s	345	Downloading seaborn-0.13.0-py3-none-any.whl (294 kB)
213.7s	346	[?25l   [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m0.0/294.6 kB[0m [31m?[0m eta [36m-:--:--[0m
[2K   [91m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m[91m╸[0m[90m━[0m [32m286.7/294.6 kB[0m [31m9.8 MB/s[0m eta [36m0:00:01[0m
[2K   [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m294.6/294.6 kB[0m [31m7.0 MB/s[0m eta [36m0:00:00[0m
213.7s	347	[?25hDownloading faiss_cpu-1.13.2-cp310-abi3-manylinux_2_27_x86_64.manylinux_2_28_x86_64.whl (23.8 MB)
213.9s	348	[?25l   [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m0.0/23.8 MB[0m [31m?[0m eta [36m-:--:--[0m
[2K   [91m━━━━━[0m[91m╸[0m[90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m3.4/23.8 MB[0m [31m101.6 MB/s[0m eta [36m0:00:01[0m
[2K   [91m━━━━━━━━━━━━━━━━━━━━[0m[90m╺[0m[90m━━━━━━━━━━━━━━━━━━━[0m [32m12.0/23.8 MB[0m [31m223.7 MB/s[0m eta [36m0:00:01[0m
[2K   [91m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m[91m╸[0m[90m━━━━[0m [32m21.2/23.8 MB[0m [31m261.7 MB/s[0m eta [36m0:00:01[0m
[2K   [91m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m[91m╸[0m [32m23.8/23.8 MB[0m [31m255.9 MB/s[0m eta [36m0:00:01[0m
[2K   [91m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m[91m╸[0m [32m23.8/23.8 MB[0m [31m255.9 MB/s[0m eta [36m0:00:01[0m
[2K   [91m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m[91m╸[0m [32m23.8/23.8 MB[0m [31m255.9 MB/s[0m eta [36m0:00:01[0m
[2K   [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m23.8/23.8 MB[0m [31m76.1 MB/s[0m eta [36m0:00:00[0m
214.0s	349	[?25hBuilding wheels for collected packages: easydict
215.4s	350	  Building wheel for easydict (setup.py) ... [?25l[?25hdone
215.4s	351	  Created wheel for easydict: filename=easydict-1.10-py3-none-any.whl size=6492 sha256=4fe0f74c49bdc42e21fd4d2baa28c391f3ed4bb165ac1d5fc6c890270a09561a
215.4s	352	  Stored in directory: /root/.cache/pip/wheels/6b/76/56/33ab6d7f4a2ebd12c1a2c05eccf4cd886421ea55b8fa490fa8
215.4s	353	Successfully built easydict
217.4s	354	Installing collected packages: easydict, termcolor, faiss-cpu, seaborn
217.4s	355	  Attempting uninstall: easydict
217.7s	356	    Found existing installation: easydict 1.13
217.7s	357	    Uninstalling easydict-1.13:
217.7s	358	      Successfully uninstalled easydict-1.13
218.3s	359	  Attempting uninstall: termcolor
218.6s	360	    Found existing installation: termcolor 3.1.0
218.6s	361	    Uninstalling termcolor-3.1.0:
218.6s	362	      Successfully uninstalled termcolor-3.1.0
219.4s	363	  Attempting uninstall: seaborn
219.6s	364	    Found existing installation: seaborn 0.13.2
219.6s	365	    Uninstalling seaborn-0.13.2:
219.7s	366	      Successfully uninstalled seaborn-0.13.2
221.8s	367	Successfully installed easydict-1.10 faiss-cpu-1.13.2 seaborn-0.13.0 termcolor-2.4.0
222.4s	368	Already up to date.
226.7s	369	Found Kaggle dataset at: /kaggle/input/datasets/mgusat/smd-onmiad/ServerMachineDataset
226.7s	370	Copying /kaggle/input/datasets/mgusat/smd-onmiad/ServerMachineDataset/train to /kaggle/working/carla_mama_v1/datasets/smd/train...
230.9s	371	Copying /kaggle/input/datasets/mgusat/smd-onmiad/ServerMachineDataset/test to /kaggle/working/carla_mama_v1/datasets/smd/test...
235.1s	372	Copying /kaggle/input/datasets/mgusat/smd-onmiad/ServerMachineDataset/test_label to /kaggle/working/carla_mama_v1/datasets/smd/test_label...
235.3s	373	Found total 28 datasets in smd.
235.3s	374	PHASE 1: Running first 14 datasets.
235.3s	375	
235.3s	376	==============================
235.3s	377	STARTING EXPERIMENTS SMD - PHASE 1
235.3s	378	==============================
235.6s	379	GPU available: Tesla T4
235.6s	380	
235.6s	381	Running dataset: machine-1-1.txt
1655.6s	382	Max GPU Memory after machine-1-1.txt: 7444.18 MB
1655.6s	383	
1655.6s	384	Running dataset: machine-1-2.txt
2828.7s	385	Max GPU Memory after machine-1-2.txt: 7444.18 MB
2828.7s	386	
2828.7s	387	Running dataset: machine-1-3.txt
4002.0s	388	Max GPU Memory after machine-1-3.txt: 7444.18 MB
4002.0s	389	
4002.0s	390	Running dataset: machine-1-4.txt
5186.2s	391	Max GPU Memory after machine-1-4.txt: 7444.18 MB
5186.2s	392	
5186.2s	393	Running dataset: machine-1-5.txt
6368.5s	394	Max GPU Memory after machine-1-5.txt: 7444.18 MB
6368.5s	395	
6368.5s	396	Running dataset: machine-1-6.txt
7552.1s	397	Max GPU Memory after machine-1-6.txt: 7444.18 MB
7552.1s	398	
7552.1s	399	Running dataset: machine-1-7.txt
8727.2s	400	Max GPU Memory after machine-1-7.txt: 7444.18 MB
8727.2s	401	
8727.2s	402	Running dataset: machine-1-8.txt
9897.3s	403	Max GPU Memory after machine-1-8.txt: 7444.18 MB
9897.3s	404	
9897.3s	405	Running dataset: machine-2-1.txt
11073.3s	406	Max GPU Memory after machine-2-1.txt: 7444.18 MB
11073.3s	407	
11073.3s	408	Running dataset: machine-2-2.txt
12257.0s	409	Max GPU Memory after machine-2-2.txt: 7444.18 MB
12257.0s	410	
12257.0s	411	Running dataset: machine-2-3.txt
13433.4s	412	Max GPU Memory after machine-2-3.txt: 7444.18 MB
13433.4s	413	
13433.4s	414	Running dataset: machine-2-4.txt
14621.3s	415	Max GPU Memory after machine-2-4.txt: 7444.18 MB
14621.3s	416	
14621.3s	417	Running dataset: machine-2-5.txt
15806.0s	418	Max GPU Memory after machine-2-5.txt: 7444.18 MB
15806.0s	419	
15806.0s	420	Running dataset: machine-2-6.txt
15998.6s	421	OSError: [Errno 28] No space left on device
15998.6s	422	
15998.6s	423	During handling of the above exception, another exception occurred:
15998.6s	424	
15998.6s	425	Traceback (most recent call last):
15998.6s	426	  File "/usr/local/lib/python3.12/dist-packages/papermill/clientwrap.py", line 72, in papermill_execute_cells
15998.6s	427	    self.execute_cell(cell, index)
15998.6s	428	  File "/usr/local/lib/python3.12/dist-packages/nbclient/util.py", line 84, in wrapped
15998.6s	429	    return just_run(coro(*args, **kwargs))
15998.6s	430	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
15998.6s	431	  File "/usr/local/lib/python3.12/dist-packages/nbclient/util.py", line 62, in just_run
15998.6s	432	    return loop.run_until_complete(coro)
15998.6s	433	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
15998.6s	434	  File "/usr/lib/python3.12/asyncio/base_events.py", line 691, in run_until_complete
15998.6s	435	    return future.result()
15998.6s	436	           ^^^^^^^^^^^^^^^
15998.6s	437	  File "/usr/local/lib/python3.12/dist-packages/nbclient/client.py", line 949, in async_execute_cell
15998.6s	438	    exec_reply = await self.task_poll_for_reply
15998.6s	439	                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
15998.6s	440	  File "/usr/local/lib/python3.12/dist-packages/nbclient/client.py", line 735, in _async_poll_for_reply
15998.6s	441	    await asyncio.wait_for(task_poll_output_msg, self.iopub_timeout)
15998.6s	442	  File "/usr/lib/python3.12/asyncio/tasks.py", line 520, in wait_for
15998.6s	443	    return await fut
15998.6s	444	           ^^^^^^^^^
15998.6s	445	  File "/usr/local/lib/python3.12/dist-packages/nbclient/client.py", line 766, in _async_poll_output_msg
15998.6s	446	    self.process_message(msg, cell, cell_index)
15998.6s	447	  File "/usr/local/lib/python3.12/dist-packages/papermill/clientwrap.py", line 107, in process_message
15998.6s	448	    self.nb_man.autosave_cell()
15998.6s	449	  File "/usr/local/lib/python3.12/dist-packages/papermill/engines.py", line 76, in wrapper
15998.6s	450	    return func(self, *args, **kwargs)
15998.6s	451	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^
15998.6s	452	  File "/usr/local/lib/python3.12/dist-packages/papermill/engines.py", line 166, in autosave_cell
15998.6s	453	    self.save()
15998.6s	454	  File "/usr/local/lib/python3.12/dist-packages/papermill/engines.py", line 76, in wrapper
15998.6s	455	    return func(self, *args, **kwargs)
15998.6s	456	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^
15998.6s	457	  File "/usr/local/lib/python3.12/dist-packages/papermill/engines.py", line 152, in save
15998.6s	458	    write_ipynb(self.nb, self.output_path)
15998.6s	459	  File "/usr/local/lib/python3.12/dist-packages/papermill/iorw.py", line 486, in write_ipynb
15998.6s	460	    papermill_io.write(nbformat.writes(nb), path)
15998.6s	461	  File "/usr/local/lib/python3.12/dist-packages/papermill/iorw.py", line 102, in write
15998.6s	462	    return self.get_handler(path, extensions).write(buf, path)
15998.6s	463	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
15998.6s	464	  File "/usr/local/lib/python3.12/dist-packages/papermill/iorw.py", line 214, in write
15998.6s	465	    with open(path, 'w', encoding="utf-8") as f:
15998.6s	466	         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
15998.6s	467	OSError: [Errno 28] No space left on device
15998.6s	468	
15998.6s	469	During handling of the above exception, another exception occurred:
15998.6s	470	
15998.6s	471	OSError: [Errno 28] No space left on device
15998.6s	472	
15998.6s	473	During handling of the above exception, another exception occurred:
15998.6s	474	
15998.6s	475	Traceback (most recent call last):
15998.6s	476	  File "/usr/local/lib/python3.12/dist-packages/papermill/engines.py", line 370, in execute_notebook
15998.6s	477	    cls.execute_managed_notebook(nb_man, kernel_name, log_output=log_output, **kwargs)
15998.6s	478	  File "/usr/local/lib/python3.12/dist-packages/papermill/engines.py", line 442, in execute_managed_notebook
15998.6s	479	    return PapermillNotebookClient(nb_man, **final_kwargs).execute()
15998.6s	480	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
15998.6s	481	  File "/usr/local/lib/python3.12/dist-packages/papermill/clientwrap.py", line 45, in execute
15998.6s	482	    self.papermill_execute_cells()
15998.6s	483	  File "/usr/local/lib/python3.12/dist-packages/papermill/clientwrap.py", line 77, in papermill_execute_cells
15998.6s	484	    self.nb_man.cell_complete(self.nb.cells[index], cell_index=index)
15998.6s	485	  File "/usr/local/lib/python3.12/dist-packages/papermill/engines.py", line 76, in wrapper
15998.6s	486	    return func(self, *args, **kwargs)
15998.6s	487	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^
15998.6s	488	  File "/usr/local/lib/python3.12/dist-packages/papermill/engines.py", line 273, in cell_complete
15998.6s	489	    self.save()
15998.6s	490	  File "/usr/local/lib/python3.12/dist-packages/papermill/engines.py", line 76, in wrapper
15998.6s	491	    return func(self, *args, **kwargs)
15998.6s	492	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^
15998.6s	493	  File "/usr/local/lib/python3.12/dist-packages/papermill/engines.py", line 152, in save
15998.6s	494	    write_ipynb(self.nb, self.output_path)
15998.6s	495	  File "/usr/local/lib/python3.12/dist-packages/papermill/iorw.py", line 486, in write_ipynb
15998.6s	496	    papermill_io.write(nbformat.writes(nb), path)
15998.6s	497	  File "/usr/local/lib/python3.12/dist-packages/papermill/iorw.py", line 102, in write
15998.6s	498	    return self.get_handler(path, extensions).write(buf, path)
15998.6s	499	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
15998.6s	500	  File "/usr/local/lib/python3.12/dist-packages/papermill/iorw.py", line 214, in write
15998.6s	501	    with open(path, 'w', encoding="utf-8") as f:
15998.6s	502	         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
15998.6s	503	OSError: [Errno 28] No space left on device
15998.6s	504	
15998.6s	505	During handling of the above exception, another exception occurred:
15998.6s	506	
15998.6s	507	OSError: [Errno 28] No space left on device
15998.6s	508	
15998.6s	509	During handling of the above exception, another exception occurred:
15998.6s	510	
15998.6s	511	Traceback (most recent call last):
15998.6s	512	  File "<string>", line 1, in <module>
15998.6s	513	  File "/usr/local/lib/python3.12/dist-packages/papermill/execute.py", line 116, in execute_notebook
15998.6s	514	    nb = papermill_engines.execute_notebook_with_engine(
15998.6s	515	         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
15998.6s	516	  File "/usr/local/lib/python3.12/dist-packages/papermill/engines.py", line 48, in execute_notebook_with_engine
15998.6s	517	    return self.get_engine(engine_name).execute_notebook(nb, kernel_name, **kwargs)
15998.6s	518	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
15998.6s	519	  File "/usr/local/lib/python3.12/dist-packages/papermill/engines.py", line 373, in execute_notebook
15998.6s	520	    nb_man.notebook_complete()
15998.6s	521	  File "/usr/local/lib/python3.12/dist-packages/papermill/engines.py", line 76, in wrapper
15998.6s	522	    return func(self, *args, **kwargs)
15998.6s	523	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^
15998.6s	524	  File "/usr/local/lib/python3.12/dist-packages/papermill/engines.py", line 301, in notebook_complete
15998.6s	525	    self.save()
15998.6s	526	  File "/usr/local/lib/python3.12/dist-packages/papermill/engines.py", line 76, in wrapper
15998.6s	527	    return func(self, *args, **kwargs)
15998.6s	528	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^
15998.6s	529	  File "/usr/local/lib/python3.12/dist-packages/papermill/engines.py", line 152, in save
15998.6s	530	    write_ipynb(self.nb, self.output_path)
15998.6s	531	  File "/usr/local/lib/python3.12/dist-packages/papermill/iorw.py", line 486, in write_ipynb
15998.6s	532	    papermill_io.write(nbformat.writes(nb), path)
15998.6s	533	  File "/usr/local/lib/python3.12/dist-packages/papermill/iorw.py", line 102, in write
15998.6s	534	    return self.get_handler(path, extensions).write(buf, path)
15998.6s	535	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
15998.6s	536	  File "/usr/local/lib/python3.12/dist-packages/papermill/iorw.py", line 214, in write
15998.6s	537	    with open(path, 'w', encoding="utf-8") as f:
15998.6s	538	         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
15998.6s	539	OSError: [Errno 28] No space left on device
15998.9s	540	/bin/bash: line 19: echo: write error: No space left on device
16001.0s	541	/usr/local/lib/python3.12/dist-packages/mistune.py:435: SyntaxWarning: invalid escape sequence '\|'
16001.0s	542	  cells[i][c] = re.sub('\\\\\|', '|', cell)
16001.2s	543	/usr/local/lib/python3.12/dist-packages/nbconvert/filters/filter_links.py:36: SyntaxWarning: invalid escape sequence '\_'
16001.2s	544	  text = re.sub(r'_', '\_', text) # Escape underscores in display text
16002.2s	545	/usr/local/lib/python3.12/dist-packages/traitlets/traitlets.py:2915: FutureWarning: --Exporter.preprocessors=["remove_papermill_header.RemovePapermillHeader"] for containers is deprecated in traitlets 5.0. You can pass `--Exporter.preprocessors item` ... multiple times to add items to a list.
16002.2s	546	  warn(
16002.2s	547	Traceback (most recent call last):
16002.2s	548	  File "/usr/local/lib/python3.12/dist-packages/traitlets/utils/importstring.py", line 32, in import_item
16002.2s	549	    pak = getattr(module, obj)
16002.2s	550	          ^^^^^^^^^^^^^^^^^^^^
16002.2s	551	AttributeError: module 'remove_papermill_header' has no attribute 'RemovePapermillHeader'
16002.2s	552	
16002.2s	553	The above exception was the direct cause of the following exception:
16002.2s	554	
16002.2s	555	Traceback (most recent call last):
16002.2s	556	  File "/usr/local/bin/jupyter-nbconvert", line 10, in <module>
16002.2s	557	    sys.exit(main())
16002.2s	558	             ^^^^^^
16002.2s	559	  File "/usr/local/lib/python3.12/dist-packages/jupyter_core/application.py", line 284, in launch_instance
16002.2s	560	    super().launch_instance(argv=argv, **kwargs)
16002.2s	561	  File "/usr/local/lib/python3.12/dist-packages/traitlets/config/application.py", line 992, in launch_instance
16002.2s	562	    app.start()
16002.2s	563	  File "/usr/local/lib/python3.12/dist-packages/nbconvert/nbconvertapp.py", line 369, in start
16002.2s	564	    self.convert_notebooks()
16002.2s	565	  File "/usr/local/lib/python3.12/dist-packages/nbconvert/nbconvertapp.py", line 536, in convert_notebooks
16002.2s	566	    self.exporter = cls(config=self.config)
16002.2s	567	                    ^^^^^^^^^^^^^^^^^^^^^^^
16002.2s	568	  File "/usr/local/lib/python3.12/dist-packages/nbconvert/exporters/exporter.py", line 118, in __init__
16002.2s	569	    self._init_preprocessors()
16002.2s	570	  File "/usr/local/lib/python3.12/dist-packages/nbconvert/exporters/exporter.py", line 275, in _init_preprocessors
16002.2s	571	    self.register_preprocessor(preprocessor, enabled=True)
16002.2s	572	  File "/usr/local/lib/python3.12/dist-packages/nbconvert/exporters/exporter.py", line 236, in register_preprocessor
16002.2s	573	    preprocessor_cls = import_item(preprocessor)
16002.2s	574	                       ^^^^^^^^^^^^^^^^^^^^^^^^^
16002.2s	575	  File "/usr/local/lib/python3.12/dist-packages/traitlets/utils/importstring.py", line 34, in import_item
16002.2s	576	    raise ImportError("No module named %s" % obj) from e
16002.2s	577	ImportError: No module named RemovePapermillHeader
16004.6s	578	/usr/local/lib/python3.12/dist-packages/traitlets/traitlets.py:2915: FutureWarning: --Exporter.preprocessors=["nbconvert.preprocessors.ExtractOutputPreprocessor"] for containers is deprecated in traitlets 5.0. You can pass `--Exporter.preprocessors item` ... multiple times to add items to a list.
16004.6s	579	  warn(
16004.6s	580	[NbConvertApp] Converting notebook __notebook__.ipynb to html
16004.6s	581	Traceback (most recent call last):
16004.6s	582	  File "/usr/local/lib/python3.12/dist-packages/nbformat/reader.py", line 19, in parse_json
16004.6s	583	    nb_dict = json.loads(s, **kwargs)
16004.6s	584	              ^^^^^^^^^^^^^^^^^^^^^^^
16004.6s	585	  File "/usr/lib/python3.12/json/__init__.py", line 346, in loads
16004.6s	586	    return _default_decoder.decode(s)
16004.6s	587	           ^^^^^^^^^^^^^^^^^^^^^^^^^^
16004.6s	588	  File "/usr/lib/python3.12/json/decoder.py", line 338, in decode
16004.6s	589	    obj, end = self.raw_decode(s, idx=_w(s, 0).end())
16004.6s	590	               ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
16004.6s	591	  File "/usr/lib/python3.12/json/decoder.py", line 354, in raw_decode
16004.6s	592	    obj, end = self.scan_once(s, idx)
16004.6s	593	               ^^^^^^^^^^^^^^^^^^^^^^
16004.6s	594	json.decoder.JSONDecodeError: Unterminated string starting at: line 8568 column 19 (char 383628)
16004.6s	595	
16004.6s	596	The above exception was the direct cause of the following exception:
16004.6s	597	
16004.6s	598	Traceback (most recent call last):
16004.6s	599	  File "/usr/local/bin/jupyter-nbconvert", line 10, in <module>
16004.6s	600	    sys.exit(main())
16004.6s	601	             ^^^^^^
16004.6s	602	  File "/usr/local/lib/python3.12/dist-packages/jupyter_core/application.py", line 284, in launch_instance
16004.6s	603	    super().launch_instance(argv=argv, **kwargs)
16004.6s	604	  File "/usr/local/lib/python3.12/dist-packages/traitlets/config/application.py", line 992, in launch_instance
16004.6s	605	    app.start()
16004.6s	606	  File "/usr/local/lib/python3.12/dist-packages/nbconvert/nbconvertapp.py", line 369, in start
16004.6s	607	    self.convert_notebooks()
16004.6s	608	  File "/usr/local/lib/python3.12/dist-packages/nbconvert/nbconvertapp.py", line 541, in convert_notebooks
16004.6s	609	    self.convert_single_notebook(notebook_filename)
16004.6s	610	  File "/usr/local/lib/python3.12/dist-packages/nbconvert/nbconvertapp.py", line 506, in convert_single_notebook
16004.6s	611	    output, resources = self.export_single_notebook(notebook_filename, resources, input_buffer=input_buffer)
16004.6s	612	                        ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
16004.6s	613	  File "/usr/local/lib/python3.12/dist-packages/nbconvert/nbconvertapp.py", line 435, in export_single_notebook
16004.6s	614	    output, resources = self.exporter.from_filename(notebook_filename, resources=resources)
16004.6s	615	                        ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
16004.6s	616	  File "/usr/local/lib/python3.12/dist-packages/nbconvert/exporters/exporter.py", line 190, in from_filename
16004.6s	617	    return self.from_file(f, resources=resources, **kw)
16004.6s	618	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
16004.6s	619	  File "/usr/local/lib/python3.12/dist-packages/nbconvert/exporters/exporter.py", line 208, in from_file
16004.6s	620	    return self.from_notebook_node(nbformat.read(file_stream, as_version=4), resources=resources, **kw)
16004.6s	621	                                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
16004.6s	622	  File "/usr/local/lib/python3.12/dist-packages/nbformat/__init__.py", line 174, in read
16004.6s	623	    return reads(buf, as_version, capture_validation_error, **kwargs)
16004.6s	624	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
16004.6s	625	  File "/usr/local/lib/python3.12/dist-packages/nbformat/__init__.py", line 92, in reads
16004.6s	626	    nb = reader.reads(s, **kwargs)
16004.6s	627	         ^^^^^^^^^^^^^^^^^^^^^^^^^
16004.6s	628	  File "/usr/local/lib/python3.12/dist-packages/nbformat/reader.py", line 75, in reads
16004.6s	629	    nb_dict = parse_json(s, **kwargs)
16004.6s	630	              ^^^^^^^^^^^^^^^^^^^^^^^
16004.6s	631	  File "/usr/local/lib/python3.12/dist-packages/nbformat/reader.py", line 25, in parse_json
16004.6s	632	    raise NotJSONError(message) from e
16004.6s	633	nbformat.reader.NotJSONError: Notebook does not appear to be JSON: '{\n "cells": [\n  {\n   "cell_type": "c...
16006.3s	634	Traceback (most recent call last):
16006.3s	635	  File "/usr/local/bin/nbdev_export", line 10, in <module>
16006.3s	636	    sys.exit(nbdev_export())
16006.3s	637	             ^^^^^^^^^^^^^^
16006.3s	638	  File "/usr/local/lib/python3.12/dist-packages/fastcore/script.py", line 125, in _f
16006.3s	639	    return tfunc(**merge(args, args_from_prog(func, xtra)))
16006.3s	640	           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
16006.3s	641	  File "/usr/local/lib/python3.12/dist-packages/nbdev/doclinks.py", line 159, in nbdev_export
16006.3s	642	    add_init(get_config().lib_path)
16006.3s	643	  File "/usr/local/lib/python3.12/dist-packages/nbdev/config.py", line 270, in add_init
16006.3s	644	    path.mkdir(exist_ok=True)
16006.3s	645	  File "/usr/lib/python3.12/pathlib.py", line 1311, in mkdir
16006.3s	646	    os.mkdir(self, mode)
16006.3s	647	OSError: [Errno 28] No space left on device: '/kaggle/nbdev/package'

Tui chạy trên kaggle
fix 