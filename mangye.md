仅作sysu的train.py

sysu的test.py结果

test

(HI-CMD) student2@scw4750:~/Cross-Modal-Re-ID-baseline-master$ python test.py --mode all --resume 'model_path' --gpu 1 --dataset sysu
==> Building model..
==> Loading data..
==> Resuming from checkpoint..
==> no checkpoint found at model_path

Dataset statistics:
  ------------------------------

  subset   | # ids | # images
  ------------------------------

  query    |    96 |     3803

  gallery  |    96 |      301
  ------------------------------

Data Loading Time:	 6.833
Extracting Query Feature...
Extracting Time:	 21.575
Extracting Gallery Feature...
Extracting Time:	 5.817
Test Trial: 0
POOL:   Rank-1: 2.37% | Rank-5: 10.65% | Rank-10: 18.41%| Rank-20: 31.21%| mAP: 4.27%| mINP: 2.06%
FC:   Rank-1: 2.39% | Rank-5: 10.52% | Rank-10: 18.46%| Rank-20: 31.29%| mAP: 4.26%| mINP: 2.05%
Extracting Gallery Feature...
Extracting Time:	 1.164
Test Trial: 1
POOL:   Rank-1: 2.79% | Rank-5: 10.15% | Rank-10: 17.85%| Rank-20: 30.45%| mAP: 4.17%| mINP: 1.73%
FC:   Rank-1: 2.81% | Rank-5: 10.18% | Rank-10: 17.91%| Rank-20: 30.61%| mAP: 4.17%| mINP: 1.73%
Extracting Gallery Feature...
Extracting Time:	 1.116
Test Trial: 2
POOL:   Rank-1: 2.79% | Rank-5: 10.99% | Rank-10: 18.22%| Rank-20: 30.06%| mAP: 4.15%| mINP: 1.72%
FC:   Rank-1: 2.79% | Rank-5: 10.91% | Rank-10: 18.17%| Rank-20: 30.03%| mAP: 4.15%| mINP: 1.71%
Extracting Gallery Feature...
Extracting Time:	 1.091
Test Trial: 3
POOL:   Rank-1: 2.87% | Rank-5: 10.10% | Rank-10: 17.57%| Rank-20: 30.42%| mAP: 4.19%| mINP: 2.01%
FC:   Rank-1: 2.87% | Rank-5: 10.12% | Rank-10: 17.59%| Rank-20: 30.45%| mAP: 4.19%| mINP: 2.01%
Extracting Gallery Feature...
Extracting Time:	 1.152
Test Trial: 4
POOL:   Rank-1: 3.55% | Rank-5: 11.57% | Rank-10: 19.04%| Rank-20: 30.82%| mAP: 4.54%| mINP: 1.92%
FC:   Rank-1: 3.63% | Rank-5: 11.52% | Rank-10: 19.14%| Rank-20: 30.79%| mAP: 4.55%| mINP: 1.92%
Extracting Gallery Feature...
Extracting Time:	 1.187
Test Trial: 5
POOL:   Rank-1: 2.47% | Rank-5: 9.62% | Rank-10: 16.78%| Rank-20: 29.50%| mAP: 4.10%| mINP: 1.86%
FC:   Rank-1: 2.45% | Rank-5: 9.65% | Rank-10: 16.83%| Rank-20: 29.53%| mAP: 4.09%| mINP: 1.86%
Extracting Gallery Feature...
Extracting Time:	 1.151
Test Trial: 6
POOL:   Rank-1: 2.84% | Rank-5: 11.20% | Rank-10: 19.14%| Rank-20: 31.32%| mAP: 4.23%| mINP: 1.75%
FC:   Rank-1: 2.84% | Rank-5: 11.18% | Rank-10: 19.04%| Rank-20: 31.24%| mAP: 4.23%| mINP: 1.75%
Extracting Gallery Feature...
Extracting Time:	 1.175
Test Trial: 7
POOL:   Rank-1: 2.45% | Rank-5: 10.54% | Rank-10: 17.51%| Rank-20: 30.55%| mAP: 4.13%| mINP: 1.84%
FC:   Rank-1: 2.45% | Rank-5: 10.49% | Rank-10: 17.51%| Rank-20: 30.50%| mAP: 4.13%| mINP: 1.84%
Extracting Gallery Feature...
Extracting Time:	 1.125
Test Trial: 8
POOL:   Rank-1: 2.81% | Rank-5: 9.91% | Rank-10: 17.04%| Rank-20: 28.98%| mAP: 4.02%| mINP: 1.76%
FC:   Rank-1: 2.79% | Rank-5: 9.97% | Rank-10: 17.04%| Rank-20: 28.98%| mAP: 4.01%| mINP: 1.76%
Extracting Gallery Feature...
Extracting Time:	 1.121
Test Trial: 9
POOL:   Rank-1: 1.71% | Rank-5: 8.20% | Rank-10: 16.17%| Rank-20: 29.19%| mAP: 3.75%| mINP: 1.85%
FC:   Rank-1: 1.71% | Rank-5: 8.10% | Rank-10: 16.09%| Rank-20: 29.32%| mAP: 3.75%| mINP: 1.85%
All Average:
Test Trial: 9
POOL:   Rank-1: 2.66% | Rank-5: 10.29% | Rank-10: 17.77%| Rank-20: 30.25%| mAP: 4.15%| mINP: 1.85%
FC:   Rank-1: 2.67% | Rank-5: 10.26% | Rank-10: 17.78%| Rank-20: 30.27%| mAP: 4.15%| mINP: 1.85%



regdb的test.py结果

(HI-CMD) student2@scw4750:~/Cross-Modal-Re-ID-baseline-master$ python test.py --trial 1 --resume 'model_path' --gpu 1 --dataset regdb
==> Building model..
==> Loading data..
Data Loading Time:	 8.007
Extracting Query Feature...
Extracting Time:	 15.892
Extracting Gallery Feature...
Extracting Time:	 6.415
Test Trial: 0
POOL:   Rank-1: 5.15% | Rank-5: 11.41% | Rank-10: 15.92%| Rank-20: 22.72%| mAP: 5.14%| mINP: 2.15%
FC:   Rank-1: 5.19% | Rank-5: 11.36% | Rank-10: 15.97%| Rank-20: 22.77%| mAP: 5.14%| mINP: 2.15%
Data Loading Time:	 56.918
Extracting Query Feature...
Extracting Time:	 6.315
Extracting Gallery Feature...
Extracting Time:	 6.892
Test Trial: 1
POOL:   Rank-1: 4.85% | Rank-5: 9.95% | Rank-10: 14.42%| Rank-20: 21.36%| mAP: 5.03%| mINP: 2.69%
FC:   Rank-1: 4.90% | Rank-5: 9.95% | Rank-10: 14.32%| Rank-20: 21.26%| mAP: 5.03%| mINP: 2.69%
Data Loading Time:	 96.780
Extracting Query Feature...
Extracting Time:	 6.547
Extracting Gallery Feature...
Extracting Time:	 6.941
Test Trial: 2
POOL:   Rank-1: 5.34% | Rank-5: 12.57% | Rank-10: 17.82%| Rank-20: 25.58%| mAP: 5.14%| mINP: 1.98%
FC:   Rank-1: 5.39% | Rank-5: 12.62% | Rank-10: 17.82%| Rank-20: 25.68%| mAP: 5.14%| mINP: 1.97%
Data Loading Time:	 136.870
Extracting Query Feature...
Extracting Time:	 6.365
Extracting Gallery Feature...
Extracting Time:	 6.933
Test Trial: 3
POOL:   Rank-1: 5.05% | Rank-5: 12.67% | Rank-10: 18.16%| Rank-20: 26.12%| mAP: 4.81%| mINP: 1.98%
FC:   Rank-1: 5.05% | Rank-5: 12.67% | Rank-10: 18.20%| Rank-20: 26.17%| mAP: 4.80%| mINP: 1.98%
Data Loading Time:	 176.860
Extracting Query Feature...
Extracting Time:	 6.622
Extracting Gallery Feature...
Extracting Time:	 6.914
Test Trial: 4
POOL:   Rank-1: 4.17% | Rank-5: 11.02% | Rank-10: 16.70%| Rank-20: 23.50%| mAP: 4.21%| mINP: 1.75%
FC:   Rank-1: 4.27% | Rank-5: 11.07% | Rank-10: 16.80%| Rank-20: 23.83%| mAP: 4.21%| mINP: 1.75%
Data Loading Time:	 216.964
Extracting Query Feature...
Extracting Time:	 6.411
Extracting Gallery Feature...
Extracting Time:	 6.925
Test Trial: 5
POOL:   Rank-1: 5.00% | Rank-5: 10.78% | Rank-10: 14.95%| Rank-20: 22.91%| mAP: 4.68%| mINP: 2.31%
FC:   Rank-1: 5.05% | Rank-5: 10.78% | Rank-10: 15.05%| Rank-20: 22.77%| mAP: 4.68%| mINP: 2.31%
Data Loading Time:	 256.823
Extracting Query Feature...
Extracting Time:	 6.597
Extracting Gallery Feature...
Extracting Time:	 6.935
Test Trial: 6
POOL:   Rank-1: 4.08% | Rank-5: 10.29% | Rank-10: 15.19%| Rank-20: 21.70%| mAP: 4.15%| mINP: 1.77%
FC:   Rank-1: 4.17% | Rank-5: 10.34% | Rank-10: 15.24%| Rank-20: 21.84%| mAP: 4.15%| mINP: 1.77%
Data Loading Time:	 296.917
Extracting Query Feature...
Extracting Time:	 6.419
Extracting Gallery Feature...
Extracting Time:	 6.992
Test Trial: 7
POOL:   Rank-1: 6.17% | Rank-5: 12.91% | Rank-10: 16.99%| Rank-20: 24.22%| mAP: 5.69%| mINP: 2.67%
FC:   Rank-1: 6.17% | Rank-5: 12.91% | Rank-10: 16.84%| Rank-20: 24.37%| mAP: 5.68%| mINP: 2.66%
Data Loading Time:	 336.952
Extracting Query Feature...
Extracting Time:	 6.603
Extracting Gallery Feature...
Extracting Time:	 6.995
Test Trial: 8
POOL:   Rank-1: 3.74% | Rank-5: 10.73% | Rank-10: 16.12%| Rank-20: 21.94%| mAP: 3.95%| mINP: 1.56%
FC:   Rank-1: 3.64% | Rank-5: 10.68% | Rank-10: 16.07%| Rank-20: 21.89%| mAP: 3.94%| mINP: 1.56%
Data Loading Time:	 377.124
Extracting Query Feature...
Extracting Time:	 6.451
Extracting Gallery Feature...
Extracting Time:	 6.912
Test Trial: 9
POOL:   Rank-1: 5.78% | Rank-5: 12.33% | Rank-10: 16.89%| Rank-20: 25.63%| mAP: 5.25%| mINP: 2.39%
FC:   Rank-1: 5.83% | Rank-5: 12.28% | Rank-10: 16.89%| Rank-20: 25.44%| mAP: 5.26%| mINP: 2.39%
All Average:
Test Trial: 9
POOL:   Rank-1: 4.93% | Rank-5: 11.47% | Rank-10: 16.32%| Rank-20: 23.57%| mAP: 4.81%| mINP: 2.39%
FC:   Rank-1: 4.97% | Rank-5: 11.47% | Rank-10: 16.32%| Rank-20: 23.60%| mAP: 4.80%| mINP: 2.39%



train regDB

(HI-CMD) student2@scw4750:~/Cross-Modal-Re-ID-baseline-master$ python train.py --dataset regdb --lr 0.1 --method agw --gpu 1
==========
Args:Namespace(arch='resnet50', batch_size=8, dataset='regdb', gpu='1', img_h=288, img_w=144, log_path='log/', lr=0.1, margin=0.3, method='agw', mode='all', model_path='save_model/', num_pos=4, optim='sgd', resume='', save_epoch=20, seed=0, test_batch=64, test_only=False, trial=1, vis_log_path='log/vis_log/', workers=4)
==========
==> Loading data..
Dataset regdb statistics:
  ------------------------------
  subset   | # ids | # images
  ------------------------------
  visible  |   206 |     2060
  thermal  |   206 |     2060
  ------------------------------
  query    |   206 |     2060
  gallery  |   206 |     2060
  ------------------------------
Data Loading Time:	 8.242
==> Building model..
==> Start Training...
==> Preparing Data Loader...
0
[522 523 526 ... 456 454 454]
[526 525 527 ... 451 457 459]
Epoch: [0][0/64] Time: 13.730 (13.730) lr:0.010 Loss: 38.7887 (38.7887) iLoss: 5.3306 (5.3306) TLoss: 33.4581 (33.4581) Accu: 0.00
Epoch: [0][50/64] Time: 0.680 (0.915) lr:0.010 Loss: 4.9557 (10.5530) iLoss: 4.4887 (4.5806) TLoss: 0.4670 (5.9724) Accu: 30.39
==> Preparing Data Loader...
1
[758 753 753 ... 643 649 641]
[759 751 751 ... 643 641 640]
Epoch: [1][0/64] Time: 1.008 (1.008) lr:0.020 Loss: 2.5960 (2.5960) iLoss: 2.1213 (2.1213) TLoss: 0.4747 (0.4747) Accu: 72.66
Epoch: [1][50/64] Time: 0.680 (0.686) lr:0.020 Loss: 1.1162 (2.4654) iLoss: 0.6993 (1.9930) TLoss: 0.4169 (0.4724) Accu: 74.79
==> Preparing Data Loader...
2
[1794 1797 1790 ...  513  519  510]
[1799 1790 1790 ...  513  518  516]
Epoch: [2][0/64] Time: 1.019 (1.019) lr:0.030 Loss: 3.0136 (3.0136) iLoss: 2.7176 (2.7176) TLoss: 0.2960 (0.2960) Accu: 78.12
Epoch: [2][50/64] Time: 0.680 (0.686) lr:0.030 Loss: 0.6940 (1.5766) iLoss: 0.4357 (1.1686) TLoss: 0.2583 (0.4080) Accu: 83.64
Test Epoch: 2
Extracting Gallery Feature...
Extracting Time:	 12.858
Extracting Query Feature...
Extracting Time:	 6.972
Evaluation Time:	 18.828
POOL:   Rank-1: 26.75% | Rank-5: 41.80% | Rank-10: 48.93%| Rank-20: 57.18%| mAP: 24.60%| mINP: 15.05%
FC:   Rank-1: 24.32% | Rank-5: 35.24% | Rank-10: 42.57%| Rank-20: 52.77%| mAP: 22.13%| mINP: 13.47%
Best Epoch [2]
==> Preparing Data Loader...
3
[792 796 790 ... 351 357 353]
[796 798 796 ... 358 355 358]
Epoch: [3][0/64] Time: 0.930 (0.930) lr:0.040 Loss: 0.7050 (0.7050) iLoss: 0.4117 (0.4117) TLoss: 0.2933 (0.2933) Accu: 94.53
Epoch: [3][50/64] Time: 0.679 (0.676) lr:0.040 Loss: 0.8600 (1.6344) iLoss: 0.4645 (1.2458) TLoss: 0.3955 (0.3886) Accu: 82.11
==> Preparing Data Loader...
4
[ 750  755  752 ... 1386 1386 1380]
[ 757  753  757 ... 1389 1389 1380]
Epoch: [4][0/64] Time: 0.975 (0.975) lr:0.050 Loss: 2.8903 (2.8903) iLoss: 2.6091 (2.6091) TLoss: 0.2812 (0.2812) Accu: 76.56
Epoch: [4][50/64] Time: 0.680 (0.686) lr:0.050 Loss: 0.5281 (2.2980) iLoss: 0.2498 (1.8850) TLoss: 0.2784 (0.4129) Accu: 78.05
Test Epoch: 4
Extracting Gallery Feature...
Extracting Time:	 6.959
Extracting Query Feature...
Extracting Time:	 6.960
Evaluation Time:	 18.831
POOL:   Rank-1: 24.95% | Rank-5: 38.16% | Rank-10: 44.85%| Rank-20: 53.01%| mAP: 21.00%| mINP: 10.88%
FC:   Rank-1: 27.28% | Rank-5: 40.19% | Rank-10: 47.57%| Rank-20: 55.78%| mAP: 22.21%| mINP: 11.35%
Best Epoch [4]
==> Preparing Data Loader...
5
[956 953 952 ... 725 723 724]
[950 952 958 ... 721 727 720]
Epoch: [5][0/64] Time: 1.356 (1.356) lr:0.060 Loss: 3.8409 (3.8409) iLoss: 3.1689 (3.1689) TLoss: 0.6720 (0.6720) Accu: 50.78
Epoch: [5][50/64] Time: 0.680 (0.686) lr:0.060 Loss: 3.9140 (3.2002) iLoss: 3.4279 (2.7022) TLoss: 0.4861 (0.4981) Accu: 70.94
==> Preparing Data Loader...
6
[ 298  297  297 ... 1445 1445 1447]
[ 292  293  294 ... 1449 1442 1446]
Epoch: [6][0/64] Time: 0.950 (0.950) lr:0.070 Loss: 2.2063 (2.2063) iLoss: 1.8214 (1.8214) TLoss: 0.3849 (0.3849) Accu: 78.91
Epoch: [6][50/64] Time: 0.681 (0.686) lr:0.070 Loss: 3.5672 (2.9990) iLoss: 2.8297 (2.5513) TLoss: 0.7375 (0.4477) Accu: 76.58
Test Epoch: 6
Extracting Gallery Feature...
Extracting Time:	 6.962
Extracting Query Feature...
Extracting Time:	 6.940
Evaluation Time:	 18.595
POOL:   Rank-1: 29.42% | Rank-5: 45.00% | Rank-10: 52.52%| Rank-20: 63.16%| mAP: 25.81%| mINP: 14.18%
FC:   Rank-1: 35.24% | Rank-5: 49.27% | Rank-10: 57.43%| Rank-20: 64.95%| mAP: 29.51%| mINP: 16.79%
Best Epoch [6]
==> Preparing Data Loader...
7
[1013 1017 1015 ...    4    0    9]
[1014 1011 1013 ...    4    1    2]
Epoch: [7][0/64] Time: 1.375 (1.375) lr:0.080 Loss: 0.9215 (0.9215) iLoss: 0.5609 (0.5609) TLoss: 0.3607 (0.3607) Accu: 90.62
Epoch: [7][50/64] Time: 0.680 (0.688) lr:0.080 Loss: 2.0862 (1.7091) iLoss: 1.7748 (1.3437) TLoss: 0.3114 (0.3654) Accu: 87.10
==> Preparing Data Loader...
8
[1494 1492 1493 ... 1551 1550 1553]
[1491 1490 1493 ... 1552 1552 1555]
Epoch: [8][0/64] Time: 0.952 (0.952) lr:0.090 Loss: 1.8134 (1.8134) iLoss: 1.4069 (1.4069) TLoss: 0.4065 (0.4065) Accu: 85.94
Epoch: [8][50/64] Time: 0.680 (0.686) lr:0.090 Loss: 0.2756 (1.0120) iLoss: 0.0593 (0.7058) TLoss: 0.2163 (0.3062) Accu: 91.94
Test Epoch: 8
Extracting Gallery Feature...
Extracting Time:	 6.966
Extracting Query Feature...
Extracting Time:	 6.914
Evaluation Time:	 18.742
POOL:   Rank-1: 47.38% | Rank-5: 63.16% | Rank-10: 71.21%| Rank-20: 78.50%| mAP: 40.61%| mINP: 24.71%
FC:   Rank-1: 52.43% | Rank-5: 66.17% | Rank-10: 73.16%| Rank-20: 80.05%| mAP: 43.16%| mINP: 26.78%
Best Epoch [8]
==> Preparing Data Loader...
9
[1734 1732 1733 ... 1497 1495 1498]
[1733 1733 1732 ... 1490 1497 1498]
Epoch: [9][0/64] Time: 1.334 (1.334) lr:0.100 Loss: 1.7656 (1.7656) iLoss: 1.5214 (1.5214) TLoss: 0.2442 (0.2442) Accu: 89.06
Epoch: [9][50/64] Time: 0.681 (0.688) lr:0.100 Loss: 0.5363 (0.6888) iLoss: 0.3624 (0.4481) TLoss: 0.1739 (0.2407) Accu: 95.14
==> Preparing Data Loader...
10
[1610 1611 1616 ...  617  614  611]
[1610 1613 1610 ...  615  617  616]
Epoch: [10][0/64] Time: 1.004 (1.004) lr:0.100 Loss: 0.3110 (0.3110) iLoss: 0.1230 (0.1230) TLoss: 0.1881 (0.1881) Accu: 96.88
Epoch: [10][50/64] Time: 0.681 (0.688) lr:0.100 Loss: 0.0965 (0.3302) iLoss: 0.0067 (0.1527) TLoss: 0.0898 (0.1775) Accu: 97.53
Test Epoch: 10
Extracting Gallery Feature...
Extracting Time:	 6.953
Extracting Query Feature...
Extracting Time:	 6.980
Evaluation Time:	 18.709
POOL:   Rank-1: 56.94% | Rank-5: 71.17% | Rank-10: 78.11%| Rank-20: 85.15%| mAP: 51.22%| mINP: 35.73%
FC:   Rank-1: 61.02% | Rank-5: 75.00% | Rank-10: 81.41%| Rank-20: 87.52%| mAP: 53.94%| mINP: 37.83%
Best Epoch [10]
==> Preparing Data Loader...
11
[ 694  692  695 ... 1921 1921 1921]
[ 690  696  693 ... 1921 1927 1927]
Epoch: [11][0/64] Time: 1.354 (1.354) lr:0.100 Loss: 0.1888 (0.1888) iLoss: 0.0278 (0.0278) TLoss: 0.1610 (0.1610) Accu: 100.00
Epoch: [11][50/64] Time: 0.683 (0.691) lr:0.100 Loss: 0.1548 (0.1345) iLoss: 0.0025 (0.0300) TLoss: 0.1523 (0.1044) Accu: 99.43
==> Preparing Data Loader...
12
[ 100  109  103 ... 2036 2031 2033]
[ 102  107  102 ... 2033 2032 2039]
Epoch: [12][0/64] Time: 0.983 (0.983) lr:0.100 Loss: 0.2621 (0.2621) iLoss: 0.2106 (0.2106) TLoss: 0.0515 (0.0515) Accu: 96.88
Epoch: [12][50/64] Time: 0.681 (0.687) lr:0.100 Loss: 0.0899 (0.1206) iLoss: 0.0441 (0.0442) TLoss: 0.0458 (0.0763) Accu: 99.56
Test Epoch: 12
Extracting Gallery Feature...
Extracting Time:	 6.994
Extracting Query Feature...
Extracting Time:	 6.960
Evaluation Time:	 18.696
POOL:   Rank-1: 62.14% | Rank-5: 74.61% | Rank-10: 81.70%| Rank-20: 87.72%| mAP: 55.80%| mINP: 41.69%
FC:   Rank-1: 68.74% | Rank-5: 80.39% | Rank-10: 86.21%| Rank-20: 90.83%| mAP: 59.33%| mINP: 41.32%
Best Epoch [12]
==> Preparing Data Loader...
13
[684 683 689 ... 363 366 361]
[687 688 689 ... 367 367 367]
Epoch: [13][0/64] Time: 1.342 (1.342) lr:0.100 Loss: 0.0910 (0.0910) iLoss: 0.0368 (0.0368) TLoss: 0.0542 (0.0542) Accu: 99.22
Epoch: [13][50/64] Time: 0.681 (0.688) lr:0.100 Loss: 0.0339 (0.0715) iLoss: 0.0000 (0.0102) TLoss: 0.0338 (0.0613) Accu: 99.72
==> Preparing Data Loader...
14
[1738 1731 1734 ... 1738 1738 1732]
[1737 1737 1730 ... 1730 1738 1736]
Epoch: [14][0/64] Time: 0.986 (0.986) lr:0.100 Loss: 0.1240 (0.1240) iLoss: 0.0038 (0.0038) TLoss: 0.1201 (0.1201) Accu: 100.00
Epoch: [14][50/64] Time: 0.681 (0.687) lr:0.100 Loss: 0.0431 (0.0480) iLoss: 0.0009 (0.0023) TLoss: 0.0422 (0.0457) Accu: 99.92
Test Epoch: 14
Extracting Gallery Feature...
Extracting Time:	 6.936
Extracting Query Feature...
Extracting Time:	 6.962
Evaluation Time:	 18.671
POOL:   Rank-1: 67.62% | Rank-5: 79.32% | Rank-10: 84.61%| Rank-20: 90.92%| mAP: 61.43%| mINP: 46.96%
FC:   Rank-1: 73.83% | Rank-5: 84.47% | Rank-10: 89.42%| Rank-20: 93.79%| mAP: 65.18%| mINP: 47.92%
Best Epoch [14]
==> Preparing Data Loader...
15
[1998 1998 1993 ... 1669 1669 1669]
[1991 1996 1991 ... 1668 1661 1660]
Epoch: [15][0/64] Time: 1.307 (1.307) lr:0.100 Loss: 0.0199 (0.0199) iLoss: 0.0007 (0.0007) TLoss: 0.0193 (0.0193) Accu: 100.00
Epoch: [15][50/64] Time: 0.681 (0.687) lr:0.100 Loss: 0.0559 (0.0374) iLoss: 0.0060 (0.0033) TLoss: 0.0499 (0.0341) Accu: 99.97
==> Preparing Data Loader...
16
[ 485  484  484 ... 1445 1445 1442]
[ 480  488  489 ... 1446 1445 1448]
Epoch: [16][0/64] Time: 0.982 (0.982) lr:0.100 Loss: 0.0739 (0.0739) iLoss: 0.0001 (0.0001) TLoss: 0.0739 (0.0739) Accu: 100.00
Epoch: [16][50/64] Time: 0.681 (0.687) lr:0.100 Loss: 0.0390 (0.0396) iLoss: 0.0052 (0.0040) TLoss: 0.0338 (0.0356) Accu: 99.92
Test Epoch: 16
Extracting Gallery Feature...
Extracting Time:	 6.974
Extracting Query Feature...
Extracting Time:	 6.927
Evaluation Time:	 18.565
POOL:   Rank-1: 66.46% | Rank-5: 78.79% | Rank-10: 83.88%| Rank-20: 90.05%| mAP: 61.60%| mINP: 47.87%
FC:   Rank-1: 72.91% | Rank-5: 84.66% | Rank-10: 89.03%| Rank-20: 93.83%| mAP: 65.45%| mINP: 48.67%
Best Epoch [14]
==> Preparing Data Loader...
17
[1593 1596 1593 ... 1128 1125 1121]
[1591 1596 1592 ... 1122 1126 1129]
Epoch: [17][0/64] Time: 0.911 (0.911) lr:0.100 Loss: 0.0303 (0.0303) iLoss: 0.0032 (0.0032) TLoss: 0.0271 (0.0271) Accu: 100.00
Epoch: [17][50/64] Time: 0.679 (0.680) lr:0.100 Loss: 0.0330 (0.0526) iLoss: 0.0003 (0.0200) TLoss: 0.0327 (0.0325) Accu: 99.80
==> Preparing Data Loader...
18
[894 894 897 ... 122 123 126]
[896 893 893 ... 129 121 123]
Epoch: [18][0/64] Time: 0.992 (0.992) lr:0.100 Loss: 0.0310 (0.0310) iLoss: 0.0028 (0.0028) TLoss: 0.0282 (0.0282) Accu: 100.00
Epoch: [18][50/64] Time: 0.680 (0.686) lr:0.100 Loss: 0.0119 (0.0300) iLoss: 0.0003 (0.0010) TLoss: 0.0117 (0.0290) Accu: 99.97
Test Epoch: 18
Extracting Gallery Feature...
Extracting Time:	 6.989
Extracting Query Feature...
Extracting Time:	 7.004
Evaluation Time:	 18.715
POOL:   Rank-1: 66.99% | Rank-5: 79.42% | Rank-10: 85.19%| Rank-20: 90.92%| mAP: 62.50%| mINP: 49.41%
FC:   Rank-1: 74.61% | Rank-5: 86.07% | Rank-10: 90.83%| Rank-20: 94.76%| mAP: 67.32%| mINP: 50.64%
Best Epoch [18]
==> Preparing Data Loader...
19
[404 401 401 ... 635 638 632]
[408 403 408 ... 631 635 635]
Epoch: [19][0/64] Time: 1.306 (1.306) lr:0.100 Loss: 0.0300 (0.0300) iLoss: 0.0001 (0.0001) TLoss: 0.0299 (0.0299) Accu: 100.00
Epoch: [19][50/64] Time: 0.680 (0.687) lr:0.100 Loss: 0.0174 (0.0226) iLoss: 0.0007 (0.0012) TLoss: 0.0167 (0.0214) Accu: 100.00
==> Preparing Data Loader...
20
[ 896  898  896 ... 1707 1703 1702]
[ 899  890  897 ... 1705 1707 1708]
Epoch: [20][0/64] Time: 0.972 (0.972) lr:0.010 Loss: 0.0217 (0.0217) iLoss: 0.0001 (0.0001) TLoss: 0.0216 (0.0216) Accu: 100.00
Epoch: [20][50/64] Time: 0.679 (0.686) lr:0.010 Loss: 0.0805 (0.0232) iLoss: 0.0073 (0.0018) TLoss: 0.0732 (0.0213) Accu: 99.98
Test Epoch: 20
Extracting Gallery Feature...
Extracting Time:	 7.114
Extracting Query Feature...
Extracting Time:	 6.983
Evaluation Time:	 18.634
POOL:   Rank-1: 67.86% | Rank-5: 79.51% | Rank-10: 85.19%| Rank-20: 90.58%| mAP: 63.43%| mINP: 50.55%
FC:   Rank-1: 75.05% | Rank-5: 85.78% | Rank-10: 90.92%| Rank-20: 95.00%| mAP: 68.07%| mINP: 51.84%
Best Epoch [20]
==> Preparing Data Loader...
21
[  94   99   92 ... 1727 1722 1724]
[  99   98   99 ... 1726 1721 1723]
Epoch: [21][0/64] Time: 1.088 (1.088) lr:0.010 Loss: 0.0464 (0.0464) iLoss: 0.0009 (0.0009) TLoss: 0.0455 (0.0455) Accu: 100.00
Epoch: [21][50/64] Time: 0.680 (0.682) lr:0.010 Loss: 0.0269 (0.0238) iLoss: 0.0012 (0.0015) TLoss: 0.0257 (0.0223) Accu: 99.97
==> Preparing Data Loader...
22
[ 639  630  634 ... 1516 1510 1519]
[ 632  630  638 ... 1510 1513 1518]
Epoch: [22][0/64] Time: 0.962 (0.962) lr:0.010 Loss: 0.0404 (0.0404) iLoss: 0.0005 (0.0005) TLoss: 0.0399 (0.0399) Accu: 100.00
Epoch: [22][50/64] Time: 0.680 (0.686) lr:0.010 Loss: 0.0110 (0.0216) iLoss: 0.0005 (0.0017) TLoss: 0.0105 (0.0199) Accu: 99.95
Test Epoch: 22
Extracting Gallery Feature...
Extracting Time:	 6.981
Extracting Query Feature...
Extracting Time:	 6.952
Evaluation Time:	 19.037
POOL:   Rank-1: 67.48% | Rank-5: 78.93% | Rank-10: 84.71%| Rank-20: 90.39%| mAP: 63.41%| mINP: 50.65%
FC:   Rank-1: 75.73% | Rank-5: 86.17% | Rank-10: 91.60%| Rank-20: 95.05%| mAP: 68.17%| mINP: 51.67%
Best Epoch [22]
==> Preparing Data Loader...
23
[1012 1011 1018 ... 1187 1189 1182]
[1013 1010 1018 ... 1181 1180 1182]
Epoch: [23][0/64] Time: 1.316 (1.316) lr:0.010 Loss: 0.0207 (0.0207) iLoss: 0.0010 (0.0010) TLoss: 0.0197 (0.0197) Accu: 100.00
Epoch: [23][50/64] Time: 0.680 (0.688) lr:0.010 Loss: 0.0177 (0.0267) iLoss: 0.0004 (0.0018) TLoss: 0.0173 (0.0250) Accu: 99.98
==> Preparing Data Loader...
24
[1049 1048 1046 ...  837  830  834]
[1042 1045 1048 ...  834  833  837]
Epoch: [24][0/64] Time: 0.983 (0.983) lr:0.010 Loss: 0.0186 (0.0186) iLoss: 0.0053 (0.0053) TLoss: 0.0133 (0.0133) Accu: 100.00
Epoch: [24][50/64] Time: 0.680 (0.686) lr:0.010 Loss: 0.0225 (0.0223) iLoss: 0.0017 (0.0019) TLoss: 0.0208 (0.0204) Accu: 100.00
Test Epoch: 24
Extracting Gallery Feature...
Extracting Time:	 7.019
Extracting Query Feature...
Extracting Time:	 6.947
Evaluation Time:	 18.732
POOL:   Rank-1: 67.96% | Rank-5: 79.76% | Rank-10: 85.49%| Rank-20: 90.87%| mAP: 63.85%| mINP: 50.95%
FC:   Rank-1: 75.29% | Rank-5: 86.70% | Rank-10: 92.14%| Rank-20: 95.15%| mAP: 68.25%| mINP: 51.91%
Best Epoch [22]
==> Preparing Data Loader...
25
[1591 1599 1594 ... 1773 1771 1779]
[1599 1595 1590 ... 1771 1777 1770]
Epoch: [25][0/64] Time: 0.933 (0.933) lr:0.010 Loss: 0.0266 (0.0266) iLoss: 0.0053 (0.0053) TLoss: 0.0213 (0.0213) Accu: 100.00
Epoch: [25][50/64] Time: 0.680 (0.681) lr:0.010 Loss: 0.0323 (0.0263) iLoss: 0.0015 (0.0019) TLoss: 0.0308 (0.0244) Accu: 100.00
==> Preparing Data Loader...
26
[1706 1704 1700 ... 1624 1624 1621]
[1700 1701 1705 ... 1620 1623 1620]
Epoch: [26][0/64] Time: 1.004 (1.004) lr:0.010 Loss: 0.0295 (0.0295) iLoss: 0.0007 (0.0007) TLoss: 0.0288 (0.0288) Accu: 100.00
Epoch: [26][50/64] Time: 0.680 (0.686) lr:0.010 Loss: 0.0374 (0.0225) iLoss: 0.0222 (0.0016) TLoss: 0.0152 (0.0209) Accu: 99.98
Test Epoch: 26
Extracting Gallery Feature...
Extracting Time:	 6.991
Extracting Query Feature...
Extracting Time:	 7.015
Evaluation Time:	 18.709
POOL:   Rank-1: 68.06% | Rank-5: 79.85% | Rank-10: 85.34%| Rank-20: 90.68%| mAP: 63.89%| mINP: 50.98%
FC:   Rank-1: 74.51% | Rank-5: 86.31% | Rank-10: 90.97%| Rank-20: 94.42%| mAP: 67.90%| mINP: 51.75%
Best Epoch [22]
==> Preparing Data Loader...
27
[ 993  993  996 ... 1789 1788 1784]
[ 991  993  996 ... 1780 1780 1781]
Epoch: [27][0/64] Time: 0.938 (0.938) lr:0.010 Loss: 0.0306 (0.0306) iLoss: 0.0030 (0.0030) TLoss: 0.0276 (0.0276) Accu: 100.00
Epoch: [27][50/64] Time: 0.680 (0.681) lr:0.010 Loss: 0.0169 (0.0217) iLoss: 0.0005 (0.0017) TLoss: 0.0163 (0.0200) Accu: 99.98
==> Preparing Data Loader...
28
[1149 1143 1140 ...  213  217  213]
[1145 1148 1149 ...  214  214  213]
Epoch: [28][0/64] Time: 0.994 (0.994) lr:0.010 Loss: 0.0170 (0.0170) iLoss: 0.0005 (0.0005) TLoss: 0.0165 (0.0165) Accu: 100.00
Epoch: [28][50/64] Time: 0.679 (0.687) lr:0.010 Loss: 0.0124 (0.0223) iLoss: 0.0022 (0.0013) TLoss: 0.0102 (0.0209) Accu: 100.00
Test Epoch: 28
Extracting Gallery Feature...
Extracting Time:	 6.958
Extracting Query Feature...
Extracting Time:	 6.978
Evaluation Time:	 18.718
POOL:   Rank-1: 67.72% | Rank-5: 80.00% | Rank-10: 85.19%| Rank-20: 90.87%| mAP: 63.88%| mINP: 51.18%
FC:   Rank-1: 75.10% | Rank-5: 86.07% | Rank-10: 91.12%| Rank-20: 95.00%| mAP: 68.21%| mINP: 52.15%
Best Epoch [22]
==> Preparing Data Loader...
29
[2047 2049 2042 ...  437  436  430]
[2046 2040 2048 ...  430  430  432]
Epoch: [29][0/64] Time: 0.930 (0.930) lr:0.010 Loss: 0.0258 (0.0258) iLoss: 0.0008 (0.0008) TLoss: 0.0250 (0.0250) Accu: 100.00
Epoch: [29][50/64] Time: 0.680 (0.682) lr:0.010 Loss: 0.0137 (0.0214) iLoss: 0.0007 (0.0015) TLoss: 0.0130 (0.0200) Accu: 100.00
==> Preparing Data Loader...
30
[1161 1160 1169 ...  275  270  274]
[1164 1168 1164 ...  273  275  279]
Epoch: [30][0/64] Time: 1.014 (1.014) lr:0.010 Loss: 0.0238 (0.0238) iLoss: 0.0005 (0.0005) TLoss: 0.0232 (0.0232) Accu: 100.00
Epoch: [30][50/64] Time: 0.680 (0.687) lr:0.010 Loss: 0.0185 (0.0204) iLoss: 0.0010 (0.0014) TLoss: 0.0175 (0.0189) Accu: 100.00
Test Epoch: 30
Extracting Gallery Feature...
Extracting Time:	 6.933
Extracting Query Feature...
Extracting Time:	 6.933
Evaluation Time:	 18.721
POOL:   Rank-1: 68.30% | Rank-5: 80.05% | Rank-10: 85.39%| Rank-20: 90.83%| mAP: 64.08%| mINP: 51.18%
FC:   Rank-1: 75.15% | Rank-5: 86.21% | Rank-10: 91.21%| Rank-20: 94.56%| mAP: 68.40%| mINP: 52.39%
Best Epoch [22]
==> Preparing Data Loader...
31
[833 837 831 ... 857 855 854]
[834 836 839 ... 859 859 853]
Epoch: [31][0/64] Time: 0.952 (0.952) lr:0.010 Loss: 0.0167 (0.0167) iLoss: 0.0006 (0.0006) TLoss: 0.0162 (0.0162) Accu: 100.00
Epoch: [31][50/64] Time: 0.680 (0.680) lr:0.010 Loss: 0.0234 (0.0210) iLoss: 0.0003 (0.0013) TLoss: 0.0231 (0.0198) Accu: 100.00
==> Preparing Data Loader...
32
[1549 1543 1547 ...  505  509  507]
[1546 1540 1545 ...  508  508  502]
Epoch: [32][0/64] Time: 1.004 (1.004) lr:0.010 Loss: 0.0126 (0.0126) iLoss: 0.0009 (0.0009) TLoss: 0.0118 (0.0118) Accu: 100.00
Epoch: [32][50/64] Time: 0.680 (0.686) lr:0.010 Loss: 0.0070 (0.0184) iLoss: 0.0007 (0.0010) TLoss: 0.0063 (0.0174) Accu: 100.00
Test Epoch: 32
Extracting Gallery Feature...
Extracting Time:	 6.980
Extracting Query Feature...
Extracting Time:	 6.976
Evaluation Time:	 18.639
POOL:   Rank-1: 68.54% | Rank-5: 79.85% | Rank-10: 85.39%| Rank-20: 91.12%| mAP: 64.10%| mINP: 51.20%
FC:   Rank-1: 75.53% | Rank-5: 86.41% | Rank-10: 90.92%| Rank-20: 94.76%| mAP: 68.47%| mINP: 52.41%
Best Epoch [22]
==> Preparing Data Loader...
33
[1705 1704 1700 ...   35   31   33]
[1705 1709 1706 ...   35   39   33]
Epoch: [33][0/64] Time: 0.942 (0.942) lr:0.010 Loss: 0.0085 (0.0085) iLoss: 0.0008 (0.0008) TLoss: 0.0076 (0.0076) Accu: 100.00
Epoch: [33][50/64] Time: 0.679 (0.681) lr:0.010 Loss: 0.0070 (0.0219) iLoss: 0.0004 (0.0014) TLoss: 0.0065 (0.0204) Accu: 99.98
==> Preparing Data Loader...
34
[748 743 745 ... 295 292 294]
[749 742 743 ... 296 293 290]
Epoch: [34][0/64] Time: 0.922 (0.922) lr:0.010 Loss: 0.0108 (0.0108) iLoss: 0.0008 (0.0008) TLoss: 0.0100 (0.0100) Accu: 100.00
Epoch: [34][50/64] Time: 0.680 (0.686) lr:0.010 Loss: 0.0183 (0.0209) iLoss: 0.0004 (0.0012) TLoss: 0.0179 (0.0197) Accu: 99.98
Test Epoch: 34
Extracting Gallery Feature...
Extracting Time:	 7.119
Extracting Query Feature...
Extracting Time:	 6.952
Evaluation Time:	 18.635
POOL:   Rank-1: 68.54% | Rank-5: 80.49% | Rank-10: 85.44%| Rank-20: 90.73%| mAP: 64.10%| mINP: 51.17%
FC:   Rank-1: 74.76% | Rank-5: 86.36% | Rank-10: 90.92%| Rank-20: 94.66%| mAP: 68.11%| mINP: 52.22%
Best Epoch [22]
==> Preparing Data Loader...
35
[1037 1038 1035 ... 1503 1504 1506]
[1037 1035 1034 ... 1500 1501 1508]
Epoch: [35][0/64] Time: 0.963 (0.963) lr:0.010 Loss: 0.0129 (0.0129) iLoss: 0.0016 (0.0016) TLoss: 0.0114 (0.0114) Accu: 100.00
Epoch: [35][50/64] Time: 0.681 (0.682) lr:0.010 Loss: 0.0309 (0.0226) iLoss: 0.0009 (0.0017) TLoss: 0.0300 (0.0210) Accu: 100.00
==> Preparing Data Loader...
36
[133 133 131 ... 931 938 939]
[133 134 131 ... 939 934 930]
Epoch: [36][0/64] Time: 0.939 (0.939) lr:0.010 Loss: 0.0141 (0.0141) iLoss: 0.0011 (0.0011) TLoss: 0.0130 (0.0130) Accu: 100.00
Epoch: [36][50/64] Time: 0.681 (0.686) lr:0.010 Loss: 0.0333 (0.0213) iLoss: 0.0022 (0.0017) TLoss: 0.0311 (0.0196) Accu: 100.00
Test Epoch: 36
Extracting Gallery Feature...
Extracting Time:	 7.049
Extracting Query Feature...
Extracting Time:	 6.959
Evaluation Time:	 18.706
POOL:   Rank-1: 68.83% | Rank-5: 80.49% | Rank-10: 85.78%| Rank-20: 91.46%| mAP: 64.48%| mINP: 51.45%
FC:   Rank-1: 75.05% | Rank-5: 86.36% | Rank-10: 91.60%| Rank-20: 94.81%| mAP: 68.58%| mINP: 52.84%
Best Epoch [22]
==> Preparing Data Loader...
37
[130 130 133 ... 801 808 800]
[139 136 138 ... 808 802 806]
Epoch: [37][0/64] Time: 0.925 (0.925) lr:0.010 Loss: 0.0132 (0.0132) iLoss: 0.0004 (0.0004) TLoss: 0.0128 (0.0128) Accu: 100.00
Epoch: [37][50/64] Time: 0.679 (0.680) lr:0.010 Loss: 0.0103 (0.0196) iLoss: 0.0004 (0.0016) TLoss: 0.0100 (0.0180) Accu: 99.98
==> Preparing Data Loader...
38
[645 649 648 ... 704 702 708]
[647 644 648 ... 700 702 709]
Epoch: [38][0/64] Time: 0.974 (0.974) lr:0.010 Loss: 0.0120 (0.0120) iLoss: 0.0003 (0.0003) TLoss: 0.0117 (0.0117) Accu: 100.00