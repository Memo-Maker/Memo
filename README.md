# 📝MEMO

MEMO는 유튜브 영상을 AI로 요약하고 메모할 수 있는 웹서비스

## 팀원 구성

<div align="center">

|                                                                **박시현**                                                                |                                                                   **김택신**                                                                   |                                                                 **정진혁**                                                                 |                                                                 **최영서**                                                                  |
|:-------------------------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------:|
| [<img src="https://avatars.githubusercontent.com/u/93407332?v=4" height=150 width=150> <br/> @sihyun](https://github.com/boxion) | [<img src="https://avatars.githubusercontent.com/u/90402009?v=4" height=150 width=150> <br/> @taeksin](https://github.com/taeksin) | [<img src="https://avatars.githubusercontent.com/u/117005839?v=4" height=150 width=150> <br/> @jinhyuk Jeong](https://github.com/wjdwlsgurdla) | [<img src="https://avatars.githubusercontent.com/u/115892001?v=4" height=150 width=150> <br/> @yeongseo](https://github.com/zeroseoS2) |

</div>


- **팀원 및 담당 분야:**
    - 박시현: 프론트엔드, 기획
    - 김택신: 프론트엔드, Flask AI 서버 구현
    - 정진혁: 백엔드, DB설계
    - 최영서: 백엔드, DB설계

## 주요 기능
- AI를 이용한 유튜브 영상 요약
- 메모 작성 및 수정
- 메모 검색 기능
- ChatGPT
- 카테고리별 저장 기능
- 사용자 인증 및 권한 관리

### Memo 실행 화면
![HomePage](https://github.com/Memo-Maker/Memo/assets/90402009/df2f4407-829f-4a12-b588-f28a69d8a81b)
![HomePage_검색](https://github.com/Memo-Maker/Memo/assets/90402009/717cb8eb-d23e-4a55-b573-1ed55e967437)
![MemoryPage](https://github.com/Memo-Maker/Memo/assets/90402009/3adc09cb-02ae-40fb-8788-f10a80106ce7)
![MemoryPage_gpt](https://github.com/Memo-Maker/Memo/assets/90402009/fac78a08-80fd-4e6b-aeba-a99d4a267beb)
![MemoryPage_Save](https://github.com/Memo-Maker/Memo/assets/90402009/eb63c9b6-1946-4e91-b592-c7c8b252a298)
![MyPage](https://github.com/Memo-Maker/Memo/assets/90402009/25bd65bb-e284-4408-80d3-44bf7cbfc78c)


## 프로젝트 구조
<img width="726" alt="image" src="https://github.com/Memo-Maker/Memo/assets/93407332/f792fc20-d490-44e0-b66d-dc65934d5366">


## 사용 기술

- **프론트엔드:** React, styled-components, react-toastify, draft-wysiwyg
- **백엔드:** Spring Boot, JPA, MySQL
- **인공지능:** Flask, OpenAI Whisper, LangChain, Chat Gpt

## 기대효과

- **영상 요약 기능 제공:** 사용자는 AI를 활용하여 영상의 내용을 요약할 수 있습니다. 이를 통해 시간을 절약하고 영상의 핵심 내용을 빠르게 파악하고, 원하는 정보를 빠르게 찾을 수 있습니다.
- **메모 기능 제공:** 사용자는 영상을 스트리밍하면서 메모를 작성할 수 있습니다. 영상에서 중요한 정보나 생각을 즉시 메모할 수 있어서 나중에 정보가 기억이 안 날 때 영상을 다시 보지 않아도 빠르게 파악할 수 있습니다. 또한 메모할 때 모르는 내용을 바로 GPT에게 질문 할 수 있는 기능을 제공합니다.
- **편리한 사용성:** Memo 서비스는 사용자 친화적인 UI/UX를 제공하여 쉽게 영상을 요약하고 메모할 수 있도록 합니다. 또한 검색기능을 통해 작성했던 메모의 내용을 검색 가능하고, 사용자만의 기준을 가지고 영상을 카테고리별로 저장하고, 분류 및 정리가 가능합니다.

## 기여 방법

1. 이 저장소를 포크합니다.
2. 새로운 브랜치를 만듭니다 (`git checkout -b feature/your-feature`).
3. 변경 사항을 커밋합니다 (`git commit -m 'Add some feature'`).
4. 브랜치에 푸시합니다 (`git push origin feature/your-feature`).
5. 풀 리퀘스트를 작성합니다.

## 라이선스

이 프로젝트는 MIT 라이선스를 따릅니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참고하세요.

## 문의

프로젝트에 대한 문의 사항은 [psh2968@naver.com](mailto:psh2968@naver.com)으로 연락해 주세요.

위의 `Readme.md` 파일은 Memo 웹사이트의 주요 정보와 설치 및 실행 방법을 포함하고 있으며, 실제 사용하는 화면의 사진도 추가되어 있습니다. 필요한 부분을 수정하거나 추가하여 사용하시면 됩니다.
