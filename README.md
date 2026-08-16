<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=random&height=180&text=jaehwan&fontColor=000000&fontSize=70" />
</div>

<div align="center">

### AI Service Developer

**끊임없이 배우고 성장하는 AI 서비스 개발자입니다.**

</div>


## 🛠️ Tech Stacks

### 📚 Languages
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
</p>

### 🤖 AI / Machine Learning
<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square"/>
  <img src="https://img.shields.io/badge/LangGraph-4B8BBE?style=flat-square"/>
</p>

### ⚙️ Backend
<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
</p>

### 🗄️ Database
<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
</p>

### ☁️ Cloud & Infra
<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
</p>

### 🛠️ Tools
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
</p>

---
## 🚀 Featured Project
### 🔴 HAPP:ME - 청년 정책·혜택 맞춤 추천 서비스 (2026.06.10 ~ 2026.08.04)

> 청년들이 자신에게 맞는 정책·혜택을 쉽게 찾지 못하는 문제를 해결하기 위해, 이미지 속 정책 정보를 AI가 인식·요약하고 사용자 프로필에 맞춰 신청 가능한 정책과 미래 시나리오별 정책을 추천해주는 서비스입니다.

**담당 기능**
- **이미지 탐지 파이프라인 구축 및 파인튜닝**: Faster R-CNN·YOLOv11 기반 2단계 객체 탐지 파이프라인 설계 및 파인튜닝
- **OCR·임베딩 매칭 및 LLM 정책 판정 로직**: PaddleOCR·SBERT·watsonx.ai를 결합한 4단계 AI 파이프라인 구현
- **AWS 인프라 배포 및 CI/CD 자동화**: S3/ECS/EC2 기반 프로덕션 인프라 설계·배포 및 GitHub Actions CI/CD 구축
- **소셜 로그인 및 인증 시스템 구현**: Google·Kakao·Naver 소셜 로그인 및 JWT 기반 인증 시스템 구현
- **청년 실태조사 군집분석 시장조사**: K-means 군집분석으로 청년 유형 도출 및 서비스 기능 방향 설계

**GitHub(Repo)**:
- Frontend: [PARKJAEKYUNG0525/bene_frontend](https://github.com/PARKJAEKYUNG0525/bene_frontend)
- Backend: [PARKJAEKYUNG0525/bene_backend](https://github.com/PARKJAEKYUNG0525/bene_backend)
- AI: [PARKJAEKYUNG0525/bene_ai](https://github.com/PARKJAEKYUNG0525/bene_ai)

**🛠️ Tech 🛠️**

**FE**: <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>  
**BE**: <img src="https://img.shields.io/badge/FASTAPI-009485?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/SQLALCHEMY-D71F00?style=flat-square&logo=python&logoColor=white"/>  
**AI**: <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/watsonx.ai-052FAD?style=flat-square&logo=ibm&logoColor=white"/>  
**Infra**: <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>


### 🟠 DevTrouble AI - 개발자 트러블슈팅 지식 베이스 · RAG 검색 플랫폼 (2026.06.20 ~ 2026.08.13)
> 개발 중 마주친 트러블슈팅 사례를 지식 베이스로 쌓고, RAG 기반 AI 검색으로 유사 문제와 해결책을 빠르게 찾아주는 서비스입니다.

**담당 기능**
- **RAG 파이프라인 설계 및 구현**: LangGraph 기반 6단계 파이프라인(질문 재구성→분류→검색→재랭킹→생성→검증) 설계, 조건부 엣지로 재시도 루프 연결
- **캐싱 레이어 구현**: Redis 기반 Context Caching으로 반복 LLM 호출 및 임베딩 결과 캐싱, 개발/운영 환경 분리(InMemoryCache/RedisCache)
- **AWS EKS 인프라 배포**: EKS·RDS·ElastiCache 기반 프로덕션 인프라 설계·배포
- **GitOps 배포 파이프라인 구축**: GitHub Actions push 방식에서 Argo CD 기반 GitOps(pull 방식)로 전환, Sealed Secrets로 민감정보 관리
- **Software Architect 역할 수행**: Backend/Frontend/DevOps 전 영역 아키텍처 설계 및 구현

**GitHub(Repo)**:
- [jaehwan990319-cyber/devtrouble-ai](https://github.com/jaehwan990319-cyber/devtrouble-ai)

**🛠️ Tech 🛠️**

**FE**: <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>

**BE**: <img src="https://img.shields.io/badge/FASTAPI-009485?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/SQLALCHEMY-D71F00?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/> <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white"/>

**AI**: <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/> <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/>

**Infra**: <img src="https://img.shields.io/badge/AWS%20EKS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/> <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/> <img src="https://img.shields.io/badge/Argo%20CD-EF7B4D?style=flat-square&logo=argo&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
