# Emoji art

Turn your picture into emoji art!

![example](docs/assets/example.jpg)

## Using

1. Copy this repository:
```bash
git clone https://github.com/Ostrill/emoji.git
```

2. Install required libraries:
```bash
pip install numpy==1.26.4
pip install pillow==10.2.0
```

3. Use it:
```Python
from utils import draw

draw(image='images/example.png', 
     save_as='images/result.png')
```

> More examples and details in [`documentation`](docs/EN.md)