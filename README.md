To run locally:

- Install Python3
- Clone repository `git clone https://github.com/al-jshen/pytorch-flask.git`
- Enter cloned directory `cd pytorch-flask`
- Install dependencies `pip3 install -r requirements.txt`
- Deploy the app `python3 deploy.py`
- Open a web browser and go to `http://localhost:8000`

![Demo](https://i.imgur.com/TGXyavF.gifv)

Predicts 102 different flowers species. Built for use with a resnet152 model. Applies test time augmentation (tencrop) to increase accuracy.


