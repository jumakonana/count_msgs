# 経過時間計測パッケージ用のメッセージファイル定義パッケージ
rbsys25_as2[https://github.com/jumakonana/rbsys25_as2.git] のためのメッセージ型を作成するメッセージファイル

2つのuint8型のデータを扱う
```
uint8 minute
uint8 second
```
minuteが分, secondが秒の値となる

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
                     
