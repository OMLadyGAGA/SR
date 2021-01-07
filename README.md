# SR

Training SR with VDSR.

```

#train
python train.py --dataroot drive/MyDrive/DNN/Hw4/ --scale-factor 3 --lr 0.1 --cuda --epochs 100

#test
python test_image.py --file drive/MyDrive/DNN/Hw4/test/ --scale-factor 3 --weights weights/vdsr_100.pth --cuda

```


Reference:

https://github.com/Lornatang/VDSR-PyTorch
