# reoAIWorks2

AI 기반 Java 코드 분석 및 시각화 시스템

---

## 📁 프로젝트 구조

```
reoAIWorks2/
├── alembic/                # DB 마이그레이션 관리
├── config/                 # 환경설정
├── data/                   # 데이터 샘플/결과
├── docs/                   # 문서화 자료
├── logs/                   # 로그 파일
├── models/                 # (ORM 모델 등, 현재 비어있음)
├── src/
│   ├── api/                # FastAPI 엔드포인트
│   ├── core/               # 환경설정, 로깅 등
│   ├── database/           # DB 연동 (비어있음)
│   ├── logs/               # 서비스 로그
│   ├── models/             # (ORM 모델 등, 현재 비어있음)
│   ├── services/           # 비즈니스 로직 (Java 코드 분석 등)
│   ├── static/             # 정적 리소스
│   ├── templates/          # Jinja2 템플릿 (웹 UI)
│   ├── utils/              # 유틸리티
│   └── main.py             # FastAPI 앱 진입점
├── tests/                  # 테스트 코드 (unit, integration)
├── visualizations/         # 시각화 결과/샘플
├── requirements.txt        # 파이썬 패키지 목록
├── setup.py                # 패키지 메타/의존성
├── alembic.ini             # Alembic 설정
└── ... (기타 데이터/샘플)
```

---

## 🛠️ 주요 기능

- **Java 코드 정적 분석**
  - Java 프로젝트/파일 내 클래스, 메서드, 호출/상속관계 자동 추출
  - javalang 기반 AST 파싱

- **Mermaid.js 기반 시각화**
  - 호출/상속관계 그래프를 Mermaid 다이어그램으로 변환
  - 웹 UI에서 즉시 시각화 및 전체화면 지원

- **RESTful API & 웹 UI**
  - FastAPI 기반 REST API 제공
  - Jinja2 기반 웹 폼 및 결과 페이지 제공

- **분석 결과 제공**
  - JSON 및 Mermaid 그래프 동시 제공
  - 분석 요약, 상세 구조, 시각화 결과 확인 가능

- **확장성**
  - DB 연동, 마이그레이션, 테스트, 문서화 등 확장 구조 내장
  - AI 기반 코드 품질 분석, 리팩토링 등 추가 가능

---

## ⚙️ 기술 스택

- **Backend**: Python 3.8+, FastAPI, Uvicorn, Pydantic, SQLAlchemy, Alembic
- **Frontend**: Jinja2, Mermaid.js
- **Java 분석**: javalang (Python용 Java 파서)
- **DB**: PostgreSQL (psycopg2), Alembic (마이그레이션)
- **기타**: python-dotenv, redis (옵션), pydantic-settings

---

## 🧩 오픈소스/의존성 버전

- fastapi >= 0.104.0
- uvicorn >= 0.24.0
- sqlalchemy >= 2.0.0
- alembic >= 1.16.0
- redis >= 5.0.0
- psycopg2-binary >= 2.9.0
- pydantic >= 2.4.0
- pydantic-settings >= 2.0.0
- python-dotenv >= 1.0.0
- javalang (별도 설치 필요)

---

## 🗄️ 데이터베이스

- **기본 지원**: PostgreSQL
- **ORM/마이그레이션**: SQLAlchemy, Alembic
- **모델/마이그레이션 스크립트**: 현재 없음(확장 가능)

---

## 🚀 설치 및 실행

```bash
# 의존성 설치
pip install -r requirements.txt

# FastAPI 서버 실행
uvicorn src.main:app --reload

# 웹 UI 접속
http://localhost:8000/
```

---

## 👨‍💻 전문가 관점 요약

### 파이썬 전문가
- FastAPI 기반 비동기 REST API, Pydantic 데이터 검증
- SQLAlchemy, Alembic 통한 DB 확장성
- 서비스/유틸리티/엔드포인트 계층 분리

### AI 전문가
- Java 코드의 정적 분석 및 호출/상속관계 추출 자동화
- Mermaid.js로 복잡한 그래프 시각화
- 추후 코드 요약, 품질 분석, AI 기반 리팩토링 등 확장 가능

### Java 전문가
- javalang을 통한 Java 소스코드 파싱 및 AST 분석
- 메서드/클래스/상속/호출관계 등 핵심 구조 자동 추출
- 대규모 Java 프로젝트의 구조적 이해 및 문서화에 최적화

---

## 📢 참고/확장

- DB 모델 및 마이그레이션은 추후 확장 가능
- 테스트 코드, 문서화, 샘플 데이터 등 docs/ 및 tests/에 추가 예정
- Java 코드 분석 외 AI 기반 코드 품질 분석, 리팩토링 등 확장 가능 
