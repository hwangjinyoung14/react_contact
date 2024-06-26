
# 연락처 관리 애플리케이션

이 프로젝트는 React와 Redux를 사용하여 만든 간단한 연락처 관리 애플리케이션입니다. 사용자는 이름과 전화번호를 입력하여 새로운 연락처를 추가할 수 있고, 이름으로 연락처를 검색하고 연락처 목록을 볼 수 있습니다.

## 🚀 기능

1. **연락처 등록 폼:** 사용자는 이름과 전화번호를 입력하여 새로운 연락처를 추가할 수 있습니다.
2. **연락처 목록:** 연락처 목록을 표시하며 이름으로 연락처를 필터링할 수 있는 검색 창이 있습니다.
3. **검색 기능:** 사용자는 검색 창에 이름을 입력하여 연락처를 검색할 수 있습니다.
4. **아이템 개수 표시:** 현재 목록에 표시된 연락처의 개수를 보여줍니다.

## 🛠️ 사용된 기술

- **React**: UI 구성 및 상태 관리
- **Redux**: 애플리케이션 상태 관리
- **React Bootstrap**: UI 디자인 컴포넌트 사용
- **CSS**: 스타일링 (App.css로 스타일링)

## 🌐 배포

데모파일은 [여기](https://admirable-praline-f05930.netlify.app/)에서 확인할 수 있습니다.

## 📁 폴더 구조

```
├── public
│   ├── index.html
├── src
│   ├── components
│   │   ├── ContactForm.js
│   │   ├── ContactItem.js
│   │   ├── ContactList.js
│   │   ├── SearchBox.js
│   ├── style
│   │   ├── App.css
│   ├── reducer
│   │   ├── reducer.js
│   ├── App.js
│   ├── index.js
├── package.json
```

