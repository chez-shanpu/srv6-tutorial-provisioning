[netgroup/rose-srv6-tutorial](https://github.com/netgroup/rose-srv6-tutorial)が動作する環境を構築する．

依存しているミドルウェアのインストールと，ホームディレクトリ以下にnetgroup/rose-srv6-tutorialをクローンを行う．

## 動作確認環境
- ubuntu 20.04
- ansible 2.9.7
- python 3.8.2

## 使い方
```bash
$ ansible-playbook provision.yaml

# Run tutorial [8routers-isis-ipv6]
$ cd ~/rose-srv6-tutorial/nets/8routers-isis-ipv6
$ sudo python3 ./isis8d.py
```