# 용어집 (Glossary)

AB-731 에서 자주 나오는 핵심 용어 정리입니다.

## 생성형 AI 기본

| 용어 | 설명 |
| --- | --- |
| **Generative AI** | 학습한 패턴으로 새로운 콘텐츠(텍스트/이미지/코드 등)를 생성하는 AI |
| **Large language model (LLM)** | 대규모 텍스트로 학습된 언어 생성 모델 |
| **Token** | 모델이 처리하는 텍스트 조각. 과금/컨텍스트 단위 |
| **Context window** | 모델이 한 번에 다룰 수 있는 토큰 길이 |
| **Pretrained model** | 대규모 공개 데이터로 이미 학습된 범용 모델 |
| **Fine-tuning** | pretrained 모델을 자사 데이터로 추가 학습 |
| **Reasoning model** | 다단계 추론에 특화된 모델 |
| **Fabrication (hallucination)** | 사실이 아닌 내용을 그럴듯하게 생성하는 현상 |
| **Bias** | 학습 데이터의 편향이 결과에 반영되는 문제 |

## 품질/근거 기법

| 용어 | 설명 |
| --- | --- |
| **Prompt** | 모델에 주는 입력/지시 |
| **Prompt engineering** | 더 나은 출력을 위해 prompt 를 설계하는 기법 |
| **Grounding** | 응답을 신뢰할 수 있는 실제 데이터에 근거시키는 것 |
| **RAG** | Retrieval-Augmented Generation. 검색한 문서를 근거로 응답 생성 |
| **Knowledge mining** | 대량의 콘텐츠에서 인덱싱/검색으로 정보를 발굴 |

## Microsoft 제품/서비스

| 용어 | 설명 |
| --- | --- |
| **Microsoft Copilot** | 공개 웹 기반 무료 AI 채팅 (조직 데이터 미접근) |
| **Microsoft 365 Copilot** | Microsoft Graph 기반, 조직 데이터로 작동하는 업무 생산성 AI |
| **Microsoft 365 Copilot Chat** | 조직 컨텍스트의 안전한 채팅 경험 (web/mobile) |
| **Copilot Studio** | low-code 로 커스텀 copilot/agent 를 만드는 도구 |
| **Microsoft Graph** | Microsoft 365 데이터/관계를 노출하는 통합 데이터 계층 |
| **Graph connectors** | 외부 데이터를 Graph 에 인덱싱해 Copilot 이 활용하게 함 |
| **Researcher** | Copilot 의 심층 리서치 agent |
| **Analyst** | Copilot 의 데이터 분석 agent |
| **Microsoft Foundry** | 생성형 AI 개발/운영 통합 플랫폼 (Azure AI Foundry) |
| **Foundry Tools** | Foundry 계열 AI 서비스 모음 |
| **Azure AI Search** | 인덱싱/검색 서비스 (RAG, knowledge mining) |
| **Azure AI Vision** | 이미지/영상 분석 서비스 |
| **Azure AI Document Intelligence** | 문서에서 구조화 데이터 추출 |
| **Azure Machine Learning** | ML lifecycle 전체를 관리하는 플랫폼 |

## 도입/거버넌스

| 용어 | 설명 |
| --- | --- |
| **Responsible AI** | 공정/안전/신뢰할 수 있는 AI 사용 원칙 |
| **AI council** | AI 전략/거버넌스를 이끄는 교차 기능 조직 |
| **Adoption team** | AI 도입을 실행/확산하는 팀 |
| **AI champions** | 부서 내 도입을 돕는 얼리어답터 |
| **Governance** | AI 정책/위험/감사를 제도화하는 통제 구조 |
| **Shadow AI** | 조직 통제 밖에서 개인적으로 쓰는 AI (위험) |
| **Over-sharing** | 과도하게 공유된 데이터가 Copilot 등을 통해 노출되는 위험 |
| **Pay-as-you-go** | 사용량 기반 과금 모델 |
| **Commitment tier** | 사전 약정 기반 할인 과금 모델 |

## Responsible AI 6대 원칙

| 원칙 | 의미 |
| --- | --- |
| **Fairness** | 공정성 - 편향 최소화 |
| **Reliability & Safety** | 신뢰성과 안전 |
| **Privacy & Security** | 개인정보와 보안 |
| **Inclusiveness** | 포용성 - 접근성 |
| **Transparency** | 투명성 - 설명 가능 |
| **Accountability** | 책임성 - 사람이 책임 |

!!! info "출처"
	[Microsoft Learn - Study guide for Exam AB-731](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/ab-731), [Microsoft Learn - Microsoft 365 Copilot overview](https://learn.microsoft.com/en-us/microsoft-365/copilot/microsoft-365-copilot-overview), [Microsoft Learn - Microsoft Foundry documentation](https://learn.microsoft.com/en-us/azure/ai-foundry/)
