# Creating a clock

### 필수 사항

- 날짜 보이기: 년, 월, 일
- 시간 보이기: 시, 분, 초
- 실시간으로 계속 업데이트되어야 합니다.
- 스타일은 자유 형식입니다.
- 보너스: 스톱워치 기능 추가

---

### 도움말

- [Date](https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Global_Objects/Date)
- [이벤트 걸기](https://developer.mozilla.org/ko/docs/Web/API/EventTarget/addEventListener)
- [이벤트 종류](https://developer.mozilla.org/ko/docs/Web/Reference/Events)
- [Element 만들기](https://developer.mozilla.org/ko/docs/Web/API/Document/createElement)
- [여러개의 Element 찾기](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelectorAll)
- [하나의 Element 찾기](https://developer.mozilla.org/ko/docs/Web/API/Document/querySelector)
- [Element HTML 수정](https://developer.mozilla.org/ko/docs/Web/API/Element/innerHTML)
- [Element 텍스트 변경](https://developer.mozilla.org/ko/docs/Web/API/Node/textContent)
- [Element 뒤로 추가](https://developer.mozilla.org/ko/docs/Web/API/Node/appendChild)
- [Element 앞에 추가](https://developer.mozilla.org/ko/docs/Web/API/Node/insertBefore)
- [Document API](https://developer.mozilla.org/ko/docs/Web/API/Document)
- [Element API](https://developer.mozilla.org/ko/docs/Web/API/Element)
- [Node API](https://developer.mozilla.org/ko/docs/Web/API/Node)

---

### Installation

- 우선 repository를 본인 Github 계정으로 fork해주세요. (바닐라코딩 vanilla-clock repository 페이지 오른쪽 상단에 보시면 fork 버튼이 있습니다.)

```
// ** 본인이 원하는 디렉토리내에서 실행할 것. **

// fork해온 프로젝트를 본인 컴퓨터에 다운받는 명령어
git clone REMOTE_URL

// 방금 clone한 디렉토리로 이동
cd vanilla-clock

// 작업에 필요한 구성 요소 설치
npm install
```

---

### 쉽게 작업하는 법

```
// 프로젝트 디렉토리로 이동 후, 아래의 명령어를 실행시켜 보세요.
// 브라우저에 자동으로 작업하는 페이지가 열리고,
// 작업을 하시면서 변동 사항을 저장하시면 자동으로 브라우저는 변화를 감지하고 새로운 화면을 보여줍니다.
npm start

// 작업 끝내기
MAC/Window: control + C
```

---

### 작업 내용 저장하는 법

```
// 프로젝트 디렉토리에서 아래의 명령어를 순서대로 실행한다.
git status
git add FILE_NAME
git commit -m "COMMIT_MSG"
git push origin master
```

---

### 작업 내용 Ken과 공유하는 법

작업 내용 저장 후, 다음 링크의 방법을 따라하세요.[PR 만들기](https://help.github.com/articles/creating-a-pull-request-from-a-fork/)

**영어 잘 이해 안되시면 사슴나라 슬랙 채널에 물어보세요!**
