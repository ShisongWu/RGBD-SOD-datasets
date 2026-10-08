# RGBD-SOD-datasets
## Training
1. Download the training datasets  from [Baidu Driver](https://pan.baidu.com/s/1tjghcXQ7b1CmNQboXoZ4qw?pwd=3jms) (PSW: 3jms) and save it at './dataset/train/'.
2. Download the pre_trained models from [Baidu Driver](https://pan.baidu.com/s/1xWdV_l6Kqk1BfYvFdX0pGw?pwd=4xsc) (PSW: 4xsc) to './checkpoints/'.
3. Run `python train.py` in terminal.

## Testing
1. Download the testing datasets (DUT、NJU2K、SIP、NLPR、STERE and LFSD) from [Baidu Driver](https://pan.baidu.com/s/1e4tCpxaMd_xzXA2QxvHxyQ?pwd=urpa) (PSW: urpa) and save it at './dataset/test/'.
2. Download the trained model from [Baidu Driver](https://pan.baidu.com/s/1S6J0HBsveDSXXqcf83OXZg?pwd=92t4) (PSW: 92t4, DetNet.pth) to './checkpoints/'.
3. Run `python test.py` in the terminal.