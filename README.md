# 하루걸음

**맞춤형 장소·코스 추천 +  AI 챗봇 응답** 기능을 제공하는 프로젝트입니다.

---

## 🔧 개발 환경

- Python 3.11 (Conda 가상환경 권장)
- 패키지 설치: `pip install -r requirements.txt`

---

## 🗂️ 주요 구성

- `data/` : 원본 및 전처리 데이터
- `src/` : 전처리, 모델, API, 챗봇 코드
- `notebooks/` : EDA 및 실험 노트북
- `mlruns/` : MLflow 실험 로그
- `logs/` : 로그 수집 (ELK 연동)
- `Dockerfile`, `docker-compose.yml` : 배포 설정
- `dvc.yaml`, `params.yaml` : DVC 파이프라인

---

## ⚙️ 핵심 도구

- **MLOps**: MLflow, DVC, Docker, Jenkins
- **API**: FastAPI 
- **모델**: 추천 시스템 +  딥러닝 챗봇 (LLM 기반)
- **모니터링**: ELK Stack (Elasticsearch, Logstash, Kibana)
