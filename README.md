# 経過時間メッセージ定義パッケージ
ROS2において, 経過時間([分]:[秒])を扱うためのメッセージ型を作成するパッケージ

パブリッシャ・サブスクライバによる通信を想定

## Count.msg
経過時間([分]:[秒])のメッセージ定義ファイル

2つのuint8型のデータを生成する

- メッセージ名: `Count`
```
minute  (分) 
second  (秒)
```

以下のようなパッケージで利用できる

- rbsys25_as2 [https://github.com/jumakonana/rbsys25_as2.git]



## パッケージの構造
```
count_msgs/
├── CMakeLists.txt
├── README.md
├── include
│   └── count_msgs
├── msg
│   └── Count.msg
├── package.xml
└── src
```

## 必要なソフト
- Python
- ROS 2

このソフトウェアパッケージは, 3条項BSDライセンスの下, 再頒布
および使用が許可されます.

© 2026 Kyohei Tanaka
                     
