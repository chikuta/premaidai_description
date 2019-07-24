# README

## 検証環境

* Ubuntu 18.04 LTS
* ROS melodic

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

## 参考

* [PremaindAI_TechVerification](https://github.com/neon-izm/PremaindAI_TechVerification)


## TODO

- [ ] Joint limit設定
- [ ] Gazebo対応
- [ ] Controller系実装