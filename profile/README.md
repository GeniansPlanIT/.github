<p align="center">
  <img width="1787" height="1006" alt="스크린샷 2025-12-07 오후 10 15 19" src="https://github.com/user-attachments/assets/6d3eb959-06ab-4ec0-ba52-c419f0668e8e" />
</p>
<p><span style="color:gray;"><em>PlanitMDR 초기화면(대시보드)</em></span></p>
<br/>
<br/>


<h1 align="center">AI 기반 자동화 MDR 서비스 구축 프로젝트</h1>

<p align="center">EDR × NAC × AI 기반 차세대 MDR 프로토타입</p>

---

## 🚀 프로젝트 소개

PlanIT 팀은 **EDR/NAC 로그 기반 위협 탐지 → AI 분석 → 대응 자동화 → 보고서 생성**까지  
전 과정을 자동화한 **AI 기반 MDR 프로토타입**을 구축했습니다.

본 프로젝트는  
- 분석가 반복 업무 절감  
- 중소기업 환경에서의 실사용 가능성  
- AI + 보안 융합 자동화 기술
을 목표로 개발되었습니다.

---

## 🧩 핵심 기능

### 🔹 1. AI 기반 위협 분석
- 전후 60초 Syslog 기반 문맥 분석
- LLM 기반 악성/정상 판단
- Self-Eval, Devil’s Advocate 적용

### 🔹 2. 자동 티켓 생성·그룹핑
- RAG 기반 공격 흐름 식별
- AWS Bedrock + OpenSearch VectorDB  
- 유사 티켓 자동 연결(Generative Grouping)

### 🔹 3. 대응 자동화(EDR + NAC)
- 프로세스 종료 / 네트워크 격리 자동화  
- NAC 기반 비인가 단말 대응
- Step Functions Serverless 파이프라인 구축

### 🔹 4. 분석가 중심 UI/UX
- 티켓 주요 통계 대시보드
- 위험등급, 상태 기반 티켓 관리
- 과거 유사 티켓 자동 조회
- CTI 검사결과 하이퍼링크 연동 & 장비접속 링크

### 🔹 5. 분석 어시스턴트 챗봇
- 과거데이터 조회, IP&Hash 악성조회, 보안관련질문 가능

### 🔹 6. 고객사 채널에 레포트 및 알림 전송
- 각 고객사 채널(slack)에 주간/월간 리포트 자동 전송
- 티켓 발생 시 자동 알림 전송

---

## 🧬 시스템 아키텍처
<img width="785" height="478" alt="스크린샷 2025-12-07 오후 10 03 46" src="https://github.com/user-attachments/assets/d08dcd9c-22cb-493a-ae47-6c43cd382134" />

---
## 🧬 분석&대응 워크플로우
<img width="1289" height="381" alt="스크린샷 2025-12-04 오전 7 06 22" src="https://github.com/user-attachments/assets/1e8ee9a4-d9ce-4872-b246-e40cdf2edbe2" />

---
## 🌐 프로젝트 차별점
- **EDR + NAC 연동**으로 커버리지 확장  
- 과거 유사 티켓 조회, 개별 EDR이벤트 그룹핑  
- 워크플로우 기반 자동/반자동 대응  
- 경량 인프라(Serverless)로 중소기업 적용 가능

---

## 🔮 확장 가능성
- 다중 고객사 멀티테넌시 구조
- NAC,EDR외 타 장비 연동 확장 가능
- TI 연동 확대

---
## 👥 팀 구성

| 이름 | 역할 | 담당 |
|------|------|------|
| **강서현** | PM · Backend | 전체 기획, 일정, 데이터 파이프라인 |
| **김동혁** | Backend | API·인프라·매핑 로직 |
| **김진솔** | AI/ML | 위협 분석 모델·유사도 모델 |
| **이시하** | Frontend | UI/UX, React Portal |

---

## 🔗 문서 & 자료

📘 **Notion 프로젝트 문서**  
[Notion 링크](https://www.notion.so/nyarmit/IT-2242853de2da8038968ec2fd3b4503e7?source=copy_link)

📄 **최종 결과보고서(PDF)**  
[결과보고서_최종_플랜IT조.pdf](https://github.com/user-attachments/files/24015748/_._.IT.pdf)

📊 **최종 발표자료(PDF)**  
[S-개발자 기업프로젝트 최종 발표.pdf](https://github.com/user-attachments/files/24015746/S-.pdf)




