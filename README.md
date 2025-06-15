# 航海冒险游戏

温州商人的船只误入小丑鲨的领地，商人们要想办法避开礁石和小丑鲨，坚持五分钟之后就可以离开小丑鲨的领地。

## 运行方法

### 使用Python运行
```bash
pip install pygame
python sea_adventure.py
```

### 打包为exe
```bash
pip install pyinstaller
pyinstaller --onefile --windowed --icon=game_icon.ico sea_adventure.py
```

## 操作说明
- ↑键 - 前进
- ↓键 - 后退
- ←→键 - 转向
- 空格键 - 开始/重新开始游戏

## 开发环境
- Python 3.10+
- Pygame 2.6.0+
