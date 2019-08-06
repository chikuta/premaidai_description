# README

## 検証環境

* Ubuntu 18.04 LTS / ROS melodic
* Ubuntu 16.04 LTS / ROS kinetic

## 環境整備

```
  $ mkdir -p ros_ws/src
  $ cd ros_ws
  $ catkin init
  $ cd src
  $ git clone https://github.com/chikuta/premaidai_description
  $ cd ..
  $ catkin build
```

## 起動方法

以下の方法で動作確認ができます。

```
  $ cd ros_ws
  $ source devel/setup.bash
  $ roslaunch premaidai_description display.launch
```

## 同梱モデルについて

同梱モデルは黒イワシ(twitetr:@Schwarz_Sardine)さんのモデルを分解し、ROS用に再構築しています。
Apache2.0ライセンス下で使用許可を得ています。ここに記して感謝します。 こちらがリポジトリです。
https://github.com/kuroiwasi/PremaidAI_Model

## 参考

* [PremaindAI_TechVerification](https://github.com/neon-izm/PremaindAI_TechVerification)
* [PremaindAI_Model](https://github.com/kuroiwasi/PremaidAI_Model)
* [プリメイドAIパーツ軽量](https://drive.google.com/file/d/18qxGj2l_tFbyiChA9kbnJ-sgjDKE4dCX/view)


## TODO

- [ ] Joint limit設定
- [ ] Gazebo対応
- [ ] Controller系実装
