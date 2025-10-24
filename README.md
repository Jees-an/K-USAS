# 🧩 K-USAS: Korean UCREL Semantic Analysis System
- 📂 [USAS](https://ucrel.lancs.ac.uk/usas/)
- 📂 [Multilingual-USAS](https://github.com/UCREL/Multilingual-USAS)

## 1. 개요

**K-USAS**는 영국 **Lancaster University**의 **UCREL Semantic Analysis System (USAS)**을  
한국어의 언어 유형론적 특성에 맞게 확장·이식한 **의미 분석 시스템**입니다.

본 어휘집은 **단일어 사전**과 **다단어 표현 사전**으로 구성되며,  
각 항목은 다음 정보를 포함합니다.

- 한국어-영어 대응쌍  
- USAS 의미 태그  
- 의미론 및 말뭉치언어학 기반 수작업 검수  

> ⚙️ 현재 **K-USAS**는 **어휘집 구축 단계**에 있으며, 향후 **Lancaster University의 PyMUSAS 프레임워크**와 연동하여 **한국어 자동 의미 태깅 시스템**으로 개발·배포될 예정입니다.

---

## 2. K-USAS 어휘집 규모

| 구분 | 항목 수 |
|------|---------:|
| **단어** | 23,431 |
| **MWE** | 24,356 |
| **합계** | **47,787** |

> **K-USAS Lexicon ver. 1.0** (2025-10-24)

---

## 3. K-USAS 어휘집 예시

| 한국어 단어 | 영어 단어 | 의미 태그 | 의미 범주 |
|--------------|------------|-------------|-------------|
| 정부 | government | G1.1c | GOVT. & THE PUBLIC DOMAIN |
| 중국 | China | Z2 | NAMES & GRAMMATICAL WORDS |
| 각각 | respectively | A6.1- | GENERAL & ABSTRACT TERMS |
| 새롭다 | new | T3- | TIME |
| 좋다 | good | A5.1+ G2.2+ A1.5.2+ | GENERAL & ABSTRACT TERMS |
| 중요하다 | important | A11.1+ | GENERAL & ABSTRACT TERMS |
| 설명하다 | explain | Q2.2/A7+ A2.2 | LINGUISTIC ACTIONS, STATES & PROCESSES |

> ⚠️ 본 어휘집은 **지속적인 업데이트**를 통해 확장될 예정이며, 일부 항목의 의미 태그는 **향후 검수 과정**에서 변경될 수 있습니다.

---

## 4. K-USAS 개발 타임라인

| 일시 | 내용 |
|------|------|
| **2023년 7월 3일** | Paul Rayson 교수 연구 팀과 공동 연구 협의 |
| **2023년 9월 20일** | 킥오프 미팅 |
| **2024년 1월–6월** | K-USAS Lexicon 1차 시범 구축 (6,000여 개 항목) 및 의미 주석 매핑 |
| **2024년 7월–12월** | K-USAS Lexicon 2차 시범 구축 (4,000여 개 항목) 및 의미 주석 매핑 |
| **2025년 7월 1일** | *Corpus Linguistics 2025* (Birmingham Univ) 참가 및 중간 점검 회의 |
| **2025년 10월 24일** | **K-USAS Lexicon ver. 1.0 공개** |
| **2025년 10월~현재** | **K-USAS 전체 파이프라인 설계 진행 중** |

---

## 5. 참고문헌

- 남길임·안진산·송현주 (2025). 「**K-USAS 어휘집 구축을 위한 삼각측량 방법론 연구**」 (*forthcoming*)  
- [박민준 (2024), 「텍스트 의미 분석 시스템의 구현과 활용」, *인문과학연구* 38호.](https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART003053428)

---

## 🧑‍🏫 주요 기여자

- **남길임**  
  연세대학교 국어국문학과 교수  
  📧 nki@yonsei.ac.kr  

- **박민준**  
  덕성여자대학교 글로벌융합대학 중어중문학전공 조교수  
  📧 karmalet@duksung.ac.kr  

- **송현주**  
  경북대학교 국어교육과 부교수  
  📧 songhj@knu.ac.kr  

- **안진산**  
  경북대학교 국어국문학과 외래교수  |  언어정보연구센터 연구원  
  📧 san@knu.ac.kr