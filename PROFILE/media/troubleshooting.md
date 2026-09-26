## 🧯 Troubleshooting

### ROS2 の通信がうまくいかないとき

1. 起動中の`Topic`を表示する
```bash
ros2 topic list
```
2. 通信相手のIPアドレスを調べる
```bash
ip a
```
3. 疎通確認
```bash
ping 10.20.162.xxx
```