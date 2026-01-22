Full-Stack Developer | Continuously Contributing & Building

## 💻 Skills

#### 🚀 Programming Languages
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=OpenJDK&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

#### ⚙️ Frameworks & Library
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)

#### 🛢️ Database
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)

#### 🛠️ DevOps / CI & CD
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

#### 📚 Currently Studying
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)

#### 🏆 Certifications
<a href="https://www.credly.com/badges/5f295cb0-30fd-44d4-a7c6-9eb4d97a992e/public_url">
  <img src="https://images.credly.com/size/340x340/images/0e284c3f-5164-4b21-8660-0d84737941bc/image.png" alt="AWS Certified Solutions Architect - Associate" width="75"/>
</a>

---

## 🌟 Open Source Contributions

### 🔧 Major Contributions
- **[fastexcel](https://github.com/dhatim/fastexcel)**
  - `fastexcel-reader`가 엑셀 파일의 1904 날짜 체계를 정상적으로 인식하지 못하는 현상 수정
  - Pull Request: [#PR521](https://github.com/dhatim/fastexcel/pull/527)

- **[tabulator](https://github.com/olifolkerd/tabulator)** 
  - 테이블을 임시적으로 DOM에서 지운 상태에서 행을 추가하고, 다시 테이블을 DOM에 그릴 때 행 추가 상태가 반영되지 않는 현상 수정
  - Pull Request: [#PR4756](https://github.com/olifolkerd/tabulator/pull/4756)
 
- **[filepond](https://github.com/pqina/filepond)** 
  - 스크롤이 생길 정도로 데이터가 많을 경우, 드래그 앤 드랍으로 소팅할 때 드랍 데이터 포지션이 이상하게 잡히는 현상 수정
  - Pull Request: [#PR1057](https://github.com/pqina/filepond/pull/1057)

### 📝 Documentation & Minor Fixes
- ComposerRuntime 문서 오타 수정 ([#PR2412](https://github.com/assistant-ui/assistant-ui/pull/2412))

## 🎯 Portfolio

### [한글챗](https://github.com/mumberrymountain/hanguelchat)
> 한글 문서(HWP/HWPX)를 업로드하여 문서 내용을 AI로 분석하는 챗봇 애플리케이션

**🔗 Links:** [Repository](https://github.com/mumberrymountain/hanguelchat)

**📌 주요 기능**
- HWP/HWPX 파일을 업로드하여, 해당 문서를 기반으로 문서 내용을 요약합니다. 
- 문서 컨텍스트를 활용한 AI 챗봇 인터페이스를 제공합니다.
- 한국어, 영어, 아랍어(RTL 실습용) 등 다양한 언어를 지원합니다.
- 다크 모드/라이트 모드 테마를 지원합니다.
- RTL 모드를 지원합니다. 

**🛠️ Tech Stack**
- **Frontend**: TypeScript, React 19, Next.js 15, Tailwind CSS
- **Backend**: Java 21, Spring Boot 3.5.5, Spring AI, Spring Data JPA, Spring Data Redis,  Spring WebFlux (SSE Streaming)
- **Database**: MySQL 8
- **Cache**: Redis 7
- **Library**: hwpxlib, hwplib (한글 문서 처리)
- **State Management**: Zustand
- **i18n**: next-intl
- **Theme**: next-themes
- **Infrastructure**: Docker

**🎯 핵심 성과 & 학습 내용**
- Spring AI를 활용하여 OpenAI API와의 통합을 간소화하고, 문서 컨텍스트를 활용한 RAG(Retrieval-Augmented Generation) 패턴을 구현했습니다.
- Next.js 15의 App Router와 next-intl을 활용하여 다국어 지원(한국어, 영어, 아랍어)을 구현하고, 글로벌 사용자 경험을 개선했습니다.
- next-themes와 커스텀 테마 시스템을 구축하여 다크모드/라이트모드 전환 기능을 구현하고, 사용자 선호도에 맞는 UI를 제공했습니다.
- HTML dir 속성과 Tailwind CSS의 RTL 유틸리티를 활용하여 아랍어 사용자를 위한 RTL 레이아웃을 지원하고, 다문화 사용자 경험을 향상시켰습니다.
- Zustand를 활용한 경량 상태 관리로 스레드 및 대화 기록 관리를 효율적으로 구현했습니다.
- Docker Compose와 Kubernetes 설정을 통해 개발 환경과 프로덕션 배포 환경을 분리하여 운영 효율성을 높였습니다.
- React 19와 Next.js 15의 최신 기능을 활용하여 성능 최적화된 프론트엔드를 구축했습니다.

---

### [HWPXTemplater](https://github.com/mumberrymountain/hwpxtemplater)
> HWPX 템플릿 파일을 기반으로 데이터를 주입하여 문서를 생성하는 Java 라이브러리

**🔗 Links:** [Repository](https://github.com/mumberrymountain/hwpxtemplater) | [Documentation](https://mumberrymountain.github.io/hwpxtemplater/) | [Maven Central](https://central.sonatype.com/artifact/io.github.mumberrymountain/hwpxtemplater)

**📌 주요 기능**
- 템플릿 파일 기반으로 HWPX 문서에 데이터를 주입하여 생성하는 라이브러리를 구현했습니다.
- 기본 태그, 조건문 태그, 반복문 태그, 이미지 태그, 테이블 태그 등 다양한 태그 기능을 활용하여 문서를 생성할 수 있도록 구현했습니다. 
- 커스터마이징 가능한 템플릿 문법 및 인터셉터 시스템 설계
- Maven Central에 배포하여 라이브러리를 공개적으로 사용할 수 있도록 구현했습니다.

**🛠️ Tech Stack**
- **Language:** Java 8+
- **Build Tool:** Maven
- **Code Review:** CodeRabbit (AI-powered code review)
- **Documentation:** MkDocs, GitHub Pages

**🎯 핵심 성과 & 학습 내용**
- HWPX의 OOXML 구조를 기반으로 파일을 파싱하여 데이터를 렌더링하는 알고리즘을 개발했습니다.
- 팩토리 패턴, 빌더 패턴 등 다양한 디자인 패턴을 적용하여 유지보수성과 확장성을 향상시켰습니다.
- JUnit을 활용한 단위 테스트를 작성하여 코드 안정성을 확보했습니다.
- Maven Central에 실제로 라이브러리를 배포하는 프로세스를 경험했습니다.
- CodeRabbit을 활용하여 자동화된 코드 리뷰 시스템 구축을 구축하여 코드의 품질을 향상시켰습니다.
- MkDocs를 활용하여 체계적인 사용자 매뉴얼을 구축했습니다.

---

### [HWPXTemplater Sample Site](https://github.com/mumberrymountain/hwpxtemplater-sample)
> HWPXTemplater 라이브러리의 기능을 시연하는 서버리스 풀스택 샘플 애플리케이션

**🔗 Links:** [Website](https://www.hwpxtemplater.link/) | [Repository](https://github.com/mumberrymountain/hwpxtemplater-sample)

**📌 주요 기능**
- HWPXTemplater 라이브러리의 다양한 기능들을 시연합니다.
- 사용자가 직접 데이터를 입력하여 HWPX 파일 생성을 체험할 수 있습니다.

**🛠️ Tech Stack**
- **Frontend:** TypeScript, React/Next.js
- **Backend:** Java, AWS Lambda
- **Library:** HWPXTemplater
- **Infrastructure:** AWS S3 (Frontend Hosting), AWS Lambda (Serverless Backend)
- **CI/CD:** GitHub Actions

**🎯 핵심 성과 & 학습 내용**
- 개발한 오픈소스 라이브러리의 동작을 시연하는 데모 애플리케이션을 구현했습니다.
- AWS Lambda를 활용하여 EC2 온디맨드와 대비해 비용효율적이며 가용성도 높은 서버리스 아키텍쳐를 설계하고 구현했습니다.
- S3 + CloudFront + ACM + Route53 조합으로 안전하고 빠른 글로벌 콘텐츠 배포 환경을 구축했습니다.
- ACM으로부터 인증서를 발급받아 CloudFront에 연동하여 HTTPS를 적용했습니다.
- Route53을 통해 커스텀 도메인을 설정하고 DNS를 관리했습니다.
- React와 TypeScript를 활용하여 인터랙티브한 프론트엔드 페이지를 개발했습니다.

---

## 📫 Contact
- ✉️ email: mumberrymountain@naver.com
- 💼 Blog: https://velog.io/@mumberrymountain
