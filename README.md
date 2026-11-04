# Virtual Patient Lab
### AI-Based Virtual Patient Simulation for Physical Therapy Education

**Virtual Patient Lab**은 물리치료학과 학생들의 임상의사결정(Clinical Decision Making) 능력 향상을 위해 개발된 AI 기반 가상 환자 시뮬레이션 웹 애플리케이션이다.

학생들은 다양한 임상 사례의 가상 환자와 대화하며 주관적 정보(Subjective Data)를 수집하고, 필요한 물리치료 검사를 요청하여 객관적 정보(Objective Data)를 확인할 수 있다. 이후 수집한 정보를 바탕으로 임상적 평가(Assessment)와 치료계획(Plan)을 수립하고 SOAP 형식의 결과물을 작성한다.

## 1. 프로젝트 목적

- 실제 임상 상황을 반영한 가상 환자 시뮬레이션 제공
- 환자 문진 및 임상정보 수집 능력 향상
- 물리치료 검사 선택과 결과 해석 능력 강화
- 임상적 추론(Clinical Reasoning) 및 문제해결 능력 향상
- SOAP 기록 작성과 근거 기반 치료계획 수립 훈련

## 2. 주요 기능

| 기능 | 설명 |
|---|---|
| AI 가상 환자 대화 | 환자의 증상, 병력, 기능적 제한 등에 대한 문진 |
| 임상 사례 선택 | 근골격계 및 신경계 질환을 포함한 7개 사례 제공 |
| 물리치료 검사 | 검사 목적과 필요성을 제시한 후 검사 결과 확인 |
| 임상정보 수집 | 주관적·객관적 정보를 단계적으로 수집 |
| SOAP 기록 | 수집한 정보를 바탕으로 평가 및 치료계획 작성 |
| PDF 결과물 | 작성한 임상 기록을 PDF 파일로 저장 |
| 질문 횟수 제한 | 문진 질문을 최대 40회로 제한하여 효율적인 정보 수집 유도 |

## 3. 가상 환자 시나리오

총 7개의 임상 사례로 구성되어 있다.

| 사례 | 임상 상황 |
|---|---|
| Case 1 | 무릎관절 전치환술(TKA) 후 재활 |
| Case 2 | 요추 추간판탈출증 |
| Case 3 | 회전근개 봉합술 후 재활 |
| Case 4 | 무릎 아래 절단(BKA) 후 재활 |
| Case 5 | 뇌졸중으로 인한 편마비 |
| Case 6 | 척수손상(SCI) |
| Case 7 | 외상성 뇌손상(TBI) |

각 사례에는 환자의 병력, 주요 증상, 기능적 제한 및 물리치료 평가 결과 등이 설정되어 있으며, 학생의 질문과 검사 요청에 따라 관련 정보가 제공된다.

## 4. 학습 진행 과정

**STEP 1. 가상 환자 선택**

학습자는 제시된 임상 사례 중 하나를 선택한다.

**STEP 2. 환자 문진(Subjective Examination)**

AI 가상 환자에게 질문하여 증상, 병력, 통증, 일상생활의 제한 등 주관적 정보를 수집한다.

**STEP 3. 물리치료 검사(Objective Examination)**

환자 상태에 적합한 검사를 선택하고 검사 목적과 이유를 제시한 후 결과를 확인한다.

**STEP 4. 임상적 평가(Assessment)**

수집한 정보를 종합하여 주요 문제점, 기능적 제한 및 치료 우선순위를 판단한다.

**STEP 5. 치료계획 수립(Plan)**

환자의 상태에 따른 치료 목표와 물리치료 중재계획을 수립한다.

**STEP 6. 결과물 제출**

SOAP 형식의 임상 기록을 PDF 파일로 저장하여 학습 결과물로 제출한다.

## 5. 개발 환경

| 구분 | 사용 기술 |
|---|---|
| Programming Language | Python |
| Web Framework | Streamlit |
| Generative AI | Google Gemini API |
| PDF Generation | ReportLab |
| Version Control | Git / GitHub |

## 6. 교육적 활용

본 애플리케이션은 물리치료학과 임상의사결정 수업의 실습 도구로 개발되었다.

학생들은 가상 환자를 대상으로 문진과 검사를 수행하면서 단순한 지식 암기를 넘어 임상정보의 수집, 해석, 문제점 도출 및 치료계획 수립 과정을 경험할 수 있다.

특히 AI 가상 환자는 학생의 질문에 따라 정보를 제공하므로, 학습자의 능동적인 참여와 자기주도적 학습을 유도할 수 있다.

## 7. 사용 시 유의사항

- 본 애플리케이션은 물리치료 교육 및 실습을 목적으로 개발되었다.
- 모든 환자 사례는 교육용으로 구성된 가상 시나리오이다.
- AI가 생성하는 답변에는 부정확하거나 일관성이 부족한 정보가 포함될 수 있다.
- 실제 환자의 진단이나 치료 결정을 위한 목적으로 사용해서는 안 된다.
- Gemini API 사용량 및 서비스 상태에 따라 응답이 지연되거나 제한될 수 있다.

## 8. 프로젝트 정보

- **Project:** Virtual Patient Lab
- **Field:** Physical Therapy Education
- **Category:** AI-Based Clinical Simulation
- **Purpose:** Clinical Decision Making & Clinical Reasoning Training
- **Development:** 2026
- **Status:** Educational Prototype

---

*Virtual Patient Lab — Enhancing Clinical Reasoning Through AI-Based Patient Simulation*
