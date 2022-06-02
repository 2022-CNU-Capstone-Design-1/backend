## Installation  
- Python 3.9 사용
- kospeech에서 제공하는 Acoustic Model 중 deepspeech2(ds2) model 사용
- flask_restx를 사용하여 API 구현
- 현재 Repository에 서버에 해당하는 코드와 학습된 deepspeech2 model 모두 포함

### Virtual Environment
```
conda create -n project_name python==3.9
```

### Prerequisites  
- Numpy : `pip install numpy`  
- Pandas : `pip install pandas`
- Matplotlib : `pip install matplotlib`
- librosa : `conda install -c conda-forge librosa`
- torchaudio : `pip install torchaudio==0.8.0`
- tqdm : `pip install tqdm`
- hydra : `pip install hydra-core --upgrade`
- flask : `pip install flask`
- flask_restx : `pip install flask_restx`
- python-docx : `pip install python-docx`

### Install from source
```
pip install -r requirements_backend.txt
```

### Start Server
```
python start_server.py
```
http://localhost:5000 로 접속하여 Swagger API로 스펙 확인 가능
