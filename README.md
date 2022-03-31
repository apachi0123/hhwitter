# 602277120 정희헌

---

## 3월 30일 실무프로젝트 수업 내용 정리

---

> 1. FireBase 프로젝트 생성

[FireBase 페이지](https://firebase.google.com/ "Firebase link")

> 2.  FireBase SDK 설치

- <pre><code>npm install firebase</code></pre>

> 3.  firebase.js 파일 생성

> 4.  index.js 파일에 firebase 관련 import

> > Firebase 8버전 이하

```javascript
import firebase from "firebase/app";
import "firebase/auth";
import "firebase/firestore";
```

> > [firebase 9버전 이상]

```javascript
import firebase from "firebase/compat/app";
import "firebase/compat/auth";
import "firebase/compat/firestore";
```

> 5. .env 파일 설정
>
> > 1.  .env 파일 생성하기
> > 2.  .gitignore 파일에 .env 등록
> > 3.  firebase.js 파일 각각의 값을 변수로 변경 및 변수명 앞에 process.env. 추가하여 참조
>
> 6. 프로젝트 루트에 components 및 routes 폴더 생성하기
>
> 7. App.js 파일을 components 폴더로 이동
> 8. EditProfile.js, Auth.js, Home.js, Profile.js 파일을 routes 폴더에 생성 , 파일안에 코드는 아래와 같이 추가

> >

```javascript
const 컴포넌트 = () => <span>컴포넌트</span>;
export default 컴포넌트;
```

> 9.react-router-dom 설치

```
npm install react-router-dom
```

> 10. Router.js 파일 생성하기

```javascript
import { HashRouter as Router, Route, Switch } from "react-router-dom";

const AppRouter = () => {
  return (
    <Router>
      <Switch>
        <Route />
      </Switch>
    </Router>
  );
};
```
