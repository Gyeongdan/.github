# 🍡 경단(Gyeongdan)

> 경제를 단순하게, 경제 지식 플랫폼

경단은 복잡한 경제 개념을 단순하고 명확하게 설명하기 위해 설계된 AI 기반 프로젝트입니다. 경제 원리, 현재 경제 사건 및 재정 결정을 쉽게 이해할 수 있도록 도와드립니다.

## 📋 목차

1. [배경](#-배경)
2. [목표](#-목표)
3. [서비스 기획](#-서비스-기획)
4. [기술적 개요](#-기술적-개요)
5. [배포 및 사용](#-배포-및-사용)
6. [구성원](#-구성원)

## 🌁 배경

**✔️ 청년을 중심으로 한 투자 실패 사례 급증**

청년층의 경제적 취약성과 금융 및 경제 교육의 부족으로 인한 청년 투자 실패 사례가 급증하고 있습니다. 시험 위주의 경제 교육과 경제 공부에 대한 거부감이 문제를 심화시키고 있습니다.

**✔️ 경제 지식이 부족한 일반인 및 청년들을 위한 플랫폼 필요**

경제 지식이 부족한 일반인 및 청년들도 쉽게 이해하고 경제적 의사 결정에 도움이 되는 경제 지식 플랫폼이 필요합니다. 생성 AI와 방대한 데이터를 적절히 융합하여 사용자 맞춤형 인터페이스로 제공하면 이해도를 높일 수 있습니다.

**✔️ 경제 공부가 어렵지 않다는 인식 전환 필요**

시험 위주의 학습에서 벗어나, "일상 속 수치들도 경제 지표가 될 수 있다"는 것을 인식시키고자 합니다. 이를 통해 청년들이 스스로 경제적 인사이트를 유추할 수 있도록 돕고자 합니다.

## ⛳️ 목표

경단의 목표는 경제를 쉽게 이해할 수 있도록 도와주는 것입니다. 친근하고 유익한 태도로 경제 지식을 전달하며, 독자가 경제에 대한 흥미와 이해를 높일 수 있도록 지원합니다.

## 🎬 서비스 기획

**1. 어려운 경제 기사의 재생성**

- 기능: 자연어처리 모델과 사용자 맞춤형 필터링을 통해 경제 기사를 쉽게 재작성합니다.
- 기술: AI 기반 자연어처리(NLP) 모델 사용, 간편한 사용자 인터페이스(UI) 제공
- 추가 기능: 어려운 용어를 간단히 설명, 사용자 피드백 반영하여 지속적으로 개선

**2. 데이터 인사이트 제공**

- 기능: 대화형 인포그래픽 시각화 생성 AI를 활용하여 공공데이터 시각화
- 기술: AI 기반 시각화 도구 사용
- 추론 예시: “한국에서 가장 삼겹살이 비싼 곳은 어디인가?” 데이터 시각화

**3. 추천 시스템**

- 기능: 사용자 맞춤형 데이터 제공을 위한 추천 시스템 구축
- 기술: AI와 머신러닝 활용, 사용자 선호도와 행동 데이터 분석

**4. 대화형 인터페이스**

- 기능: 챗봇이나 커뮤니티를 통해 질문하고 답변을 받을 수 있도록 지원
- 기술: 대화형 AI와 자연어처리 기술 사용

**5. ESG 문제 해결**

- 기능: ESG 문제를 해결하는 데 기여하며, MZ세대를 타겟으로 하는 주제 다룸
- 기술: 생성형 AI와 다양한 데이터 결합, 사용자가 함께 만들어가는 신문 서비스 제공
- 예시: “1인 가구”, “숨겨진 명소”, “여행” 등 MZ세대 관심 주제 반영 콘텐츠 제공

## 🛠 기술적 개요
경단은 최신 AI 및 머신러닝 기술을 활용하여 경제 지식을 쉽고 친근하게 전달합니다. 주요 기술 요소는 다음과 같습니다:

- **생성 AI(Generative AI)**: 텍스트 생성, 요약 및 재구성을 통해 사용자가 이해하기 쉬운 경제 관련 콘텐츠를 자동으로 생성합니다.
- **자연어처리(NLP)**: 경제 기사를 분석하고 쉽게 재작성하기 위해 사용됩니다.
- **RAG(검색 증강 생성)**: 최신 정보 검색과 데이터의 정확도 및 신뢰성을 높이기 위해 활용합니다.
- **LangChain(랭체인)**: 대화형 AI 모델 간의 효율적인 데이터 흐름을 관리하여 더 정확하고 일관된 답변을 제공하기 위해 사용합니다.
- **데이터 시각화**: 대화형 인포그래픽을 통해 데이터를 시각적으로 표현합니다.
- **추천 시스템**: 개인화된 추천을 제공하기 위해 AI와 머신러닝을 사용합니다.
- **대화형 인터페이스**: 사용자가 질문에 답변을 받을 수 있는 챗봇과 커뮤니티 기능을 제공합니다.


경단은 LLM을 활용하며 한계를 보완하기 위해 추천 시스템, LangChain, RAG를 활용하여 사용자에게 더욱 정확하고 개인화된 정보를 제공합니다.

더 자세한 기술적 내용은 다음 링크에서 확인할 수 있습니다:

- 인공지능과 관련된 기술: [Gyeongdan FastAPI Repo Readme File](https://github.com/Gyeongdan/gyeongdan-server-fastapi)
- 전반적인 서버 구성 및 배포, 인가에 관련된 기술: [Gyeongdan Spring Repo Readme File](https://github.com/Gyeongdan/gyeongdan-server-spring)
- UI/UX/Design: [Gyeongdan Frontend Repo Readme](https://github.com/Gyeongdan/gyeongdan-frontend)


## 🚀 배포 및 사용

경단은 7월 중순에 베타 버전을 출시할 예정입니다.

- 웹 애플리케이션: [경단 웹사이트]() - 아직은 배포 x

### 🧑‍💻 구성원

경단은 4명의 FastAPI/Java-Kotlin Spring 개발자와 1명의 NextJS 개발자로 구성된 부산대학교 대학생으로 구성되어있습니다. 스택을 나누지 않고 함께 개발하며, 서로의 지식을 공유하고 발전시키며 프로젝트를 진행하고 있습니다.
<table>
  <tr>
    <td align="center" width="200px">
      <a href="https://github.com/stopmin" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/108014449?v=4" alt="지민 프로필" />
      </a>
    </td>
    <td align="center" width="200px">
      <a href="https://github.com/pykido" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/77539625?v=4" alt="태윤 프로필" />
      </a>
    </td>
    <td align="center" width="200px">
      <a href="https://github.com/Vackam" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/53655740?v=4" alt="요환 프로필" />
      </a>
    </td>
    <td align="center" width="200px">
      <a href="https://github.com/yeonddori" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/126975394?v=4" alt="서연 프로필" />
      </a>
    </td>
    <td align="center" width="200px">
      <a href="https://github.com/YunseongJeong" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/88422717?v=4" alt="윤성 프로필" />
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/stopmin" target="_blank">
        정지민
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/pykido" target="_blank">
        김태윤
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Vackam" target="_blank">
        이요환
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/yeonddori" target="_blank">
        이서연
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/YunseongJeong" target="_blank">
        정윤성
      </a>
    </td>
  </tr>
</table>
