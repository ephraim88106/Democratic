# 민주주의 제도 들여다보기

권력은 어떻게 견제되는가 — 한국 민주주의 제도를 '확인된 사실'과 '제기된 주장'으로
엄격히 구분해 정리하는 심층 시리즈입니다.

## 구조

- `index.html` — 시리즈 허브(홈) 페이지
- `posts/01-선관위.html` — 제1편: 대한민국 선거관리위원회
- `assets/style.css` — 공용 스타일

## 로컬 미리보기

```bash
python3 -m http.server 8080
```

브라우저에서 `http://localhost:8080` 접속. (IDX 미리보기는 자동으로 실행됩니다.)

## 배포 (Firebase Hosting)

`firebase.json`은 저장소 루트를 그대로 호스팅하도록 설정돼 있습니다.
`.firebaserc`의 `YOUR_FIREBASE_PROJECT_ID`를 실제 프로젝트 ID로 바꾼 뒤:

```bash
firebase deploy --only hosting
```
