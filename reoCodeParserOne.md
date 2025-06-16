# AI 소스코드 분석 에이전트

이 프로젝트는 AI를 활용하여 소스코드를 분석하고 이해하는 도구입니다.

## 주요 기능

- OpenAI GPT API 또는 Anthropic Claude API를 활용한 소스코드 분석
- LangChain을 통한 AI Agent 개발
- LlamaIndex를 활용한 문서 인덱싱 및 검색
- 소스코드 파싱 및 분석
- 데이터베이스 저장 및 캐싱

## 기술 스택

- Python 3.9+
- FastAPI
- LangChain
- LlamaIndex
- ChromaDB/Pinecone
- PostgreSQL
- Redis

## 설치 방법

1. 가상환경 생성 및 활성화:
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
```

2. 필요한 패키지 설치:
```bash
pip install -r requirements.txt
```

## 프로젝트 구조

```
reoAIWorks2/
├── src/           # 소스 코드
├── tests/         # 테스트 코드
├── config/        # 설정 파일
├── docs/          # 문서
└── requirements.txt
```

## 환경 설정

1. `.env` 파일을 생성하고 필요한 환경 변수를 설정하세요:
```
OPENAI_API_KEY=your_api_key
DATABASE_URL=your_database_url
REDIS_URL=your_redis_url
```

## 라이센스

이 프로젝트는 MIT 라이센스를 따릅니다. 
