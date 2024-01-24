# Fast API

## Installation
- fastapi 뿐만 아니라 설치에 필요한 모든 패키지를 설치하는 명령어는 다음과 같다.
```bash
pip install "fastapi[all]"
# or
pip install -r requirements.txt
```

## Run
```bash
uvicorn main:app --reload
# or
./run.sh
```

## Swagger API
swagger api는 다음과 같은 경로에서 확인할 수 있다.
- http://{address}:{port}/docs 