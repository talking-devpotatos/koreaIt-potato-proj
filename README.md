# koreaIt-potato-proj

## 시작하기 (Backend 세팅)

이 프로젝트는 **FastAPI**를 사용합니다. 아래 순서대로 환경을 설정해주세요.

### 1. 가상환경 생성 및 활성화
```bash
# 가상환경 만들기
python -m venv venv

# 가상환경 활성화 (Windows)
venv\Scripts\activate

# 가상환경 활성화 (Mac/Linux)
source venv/bin/activate

# 필수 라이브러리 설치
pip install -r requirements.txt

# 서버 실행
uvicorn app.main:app --reload
