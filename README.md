# MelanomaCnn

Main goal of the project is: Detecting melanoma with CNN architecture. (Range: 1-0)

## 10th Epoch Results:
10th epoch is the best result, with LearningRate=0.001
<b> Confussion Matrix </b>
![alt text](https://github.com/TkRsln/MelanomaCnn/blob/main/IMG/epoch_10.png)

## AI Architecture
    (network): Sequential(
        (0): Conv2d(3, 32, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
        (1): ReLU()
        (2): Conv2d(32, 64, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
        (3): ReLU()
        (4): MaxPool2d(kernel_size=2, stride=2, padding=0, dilation=1, ceil_mode=False)
        (5): Conv2d(64, 128, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
        (6): ReLU()
        (7): Conv2d(128, 128, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
        (8): ReLU()
        (9): MaxPool2d(kernel_size=2, stride=2, padding=0, dilation=1, ceil_mode=False)
        (10): Conv2d(128, 128, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
        (11): ReLU()
        (12): Conv2d(128, 128, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
        (13): ReLU()
        (14): MaxPool2d(kernel_size=2, stride=2, padding=0, dilation=1, ceil_mode=False)
        (15): Flatten(start_dim=1, end_dim=-1)
        (16): Linear(in_features=131072, out_features=500, bias=True)
        (17): ReLU()
      )
      (last): Sequential(
        (0): Linear(in_features=500, out_features=200, bias=True)
        (1): ReLU()
        (2): Linear(in_features=200, out_features=1, bias=True)
        (3): Sigmoid()
      )

## All Moduls
in every epoch, moduls saved. This is the chart of confuse matrix of all moduls
![alt text](https://github.com/TkRsln/MelanomaCnn/blob/main/IMG/AllModuls.png)

