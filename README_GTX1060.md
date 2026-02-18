# GTX1060 Installation Instructions

## Installation

First install python3.10 as appropriate for your platform and then run

```bash
python3.10 -m venv venv
pip install torch==2.3.1+cu118 torchvision==0.18.1+cu118 torchaudio==2.3.1 transformers==4.57.5 --extra-index-url https://download.pytorch.org/whl/cu118
pip install -r requirements.txt
python main.py --lowvram --disable-cuda-malloc --dont-upcast-attention --listen
```
