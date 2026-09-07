## 🌐 LIVE DEMO
https://ykyoo0110-code.github.io/

[KKUGI_STORE README.md](https://github.com/user-attachments/files/31905775/KKUGI_STORE.README.md)
# 🛍️ KKUGI STORE

> React를 활용하여 제작한 쇼핑몰 웹사이트 포트폴리오 프로젝트입니다.  
> 상품 탐색부터 상세 페이지, 장바구니, 주문, 로그인까지 쇼핑몰의 기본적인 사용자 흐름을 구현했습니다.

---

## 📌 PROJECT OVERVIEW

**KKUGI STORE**는 React 기반으로 제작한 쇼핑몰 웹사이트입니다.

단순한 메인 페이지 구현에 그치지 않고 사용자가 상품을 선택하고 상세 정보를 확인한 후 장바구니와 주문 단계로 이동하는 **실제 쇼핑몰의 사용자 흐름(User Flow)​**을 중심으로 제작했습니다.

또한 컴포넌트를 기능별로 분리하여 코드의 재사용성과 유지보수성을 고려했습니다.

---

## 🛠️ TECH STACK

### Frontend

- React
- JavaScript
- HTML5
- CSS3
- React Router

### Development

- Vite
- npm
- GitHub

---

## ✨ MAIN FEATURES

### 🏠 MAIN PAGE

- 쇼핑몰 메인 화면 구성
- 상품 및 콘텐츠 영역 구성
- 상품 클릭 시 상세 페이지 이동
- 스크롤에 따른 콘텐츠 등장 효과 적용
- Header / Footer 등 공통 UI 구성

---

### 🛍️ PRODUCT DETAIL

- 상품 이미지 및 상세 정보 제공
- 상품 옵션 및 수량 선택
- 상품 가격 정보 표시
- 장바구니 연결
- 관련 상품 영역 구성

---

### 🛒 SHOPPING CART & ORDER

- 선택한 상품 장바구니 추가
- 장바구니 상품 목록 확인
- 상품 수량 변경
- 상품 삭제
- 수량에 따른 금액 계산
- 전체 주문 금액 확인
- 장바구니에서 주문 단계로 이어지는 사용자 흐름 구현

---

### 🔐 LOGIN FLOW

- Header의 로그인 버튼과 로그인 페이지 연결
- 아이디 / 비밀번호 입력 UI 구성
- React Router를 활용한 페이지 이동
- 메인 페이지와 로그인 페이지의 사용자 흐름 구현

---

## 🔄 USER FLOW

```text
MAIN
  │
  ├── PRODUCT LIST
  │       │
  │       ▼
  │   PRODUCT DETAIL
  │       │
  │       ▼
  │   SHOPPING CART
  │       │
  │       ▼
  │      ORDER
  │
  └── LOGIN
```

---

## 📂 PROJECT STRUCTURE

```text
KKUGI_STORE
│
├── public
│
├── src
│   ├── assets
│   ├── components
│   ├── pages
│   └── ...
│
├── index.html
├── package.json
├── package-lock.json
└── vite.config.js
```

> 프로젝트 구조는 기능과 화면을 기준으로 컴포넌트와 페이지를 분리하여 관리할 수 있도록 구성했습니다.

---

## 💡 TROUBLESHOOTING

### 상품 및 페이지 데이터 연결

여러 화면에서 상품 정보를 사용할 수 있도록 데이터 구조와 컴포넌트 간 전달 방식을 정리했습니다.

### Shopping Cart 상태 관리

장바구니 상품의 추가, 삭제, 수량 변경에 따라 화면과 주문 금액이 함께 변경되도록 구현했습니다.

### React Router 페이지 연결

메인, 상품 상세, 장바구니, 로그인 등의 페이지를 React Router로 연결하여 SPA 방식의 화면 이동을 구현했습니다.

### Scroll Animation

사용자가 페이지를 스크롤하면 콘텐츠가 자연스럽게 나타나도록 스크롤 이벤트 기반의 애니메이션 효과를 적용했습니다.

---

## 📚 WHAT I LEARNED

프로젝트를 진행하면서 다음 내용을 학습했습니다.

- React 컴포넌트 구조 설계
- Props를 활용한 데이터 전달
- State를 활용한 화면 상태 관리
- 이벤트 처리
- 배열 데이터 렌더링
- React Router를 이용한 페이지 이동
- 장바구니 데이터 처리
- 조건부 렌더링
- 사용자 중심의 쇼핑몰 페이지 흐름 설계
- 컴포넌트 재사용과 코드 분리의 중요성

---

## 🚀 NEXT STEP

향후 다음 기능을 추가하여 프로젝트를 확장할 수 있습니다.

- 실제 회원가입 / 로그인 기능
- Backend API 연동
- Database 연동
- 실제 주문 및 결제 시스템
- 상품 검색 및 필터링
- 관리자 상품 관리 기능
- 사용자 주문 내역 관리

---

## ▶️ RUN PROJECT

프로젝트를 내려받은 후 패키지를 설치합니다.

```bash
npm install
```

개발 서버를 실행합니다.

```bash
npm run dev
```

배포용 파일을 생성합니다.

```bash
npm run build
```

Vite 프로젝트이므로 빌드가 완료되면 `dist` 폴더가 생성됩니다.

---

## 📑 PORTFOLIO

프로젝트의 상세한 기획 및 구현 내용은 함께 등록된 **KKUGI STORE 포트폴리오 PPT**에서 확인할 수 있습니다.

---

## 👨‍💻 PROJECT

**KKUGI STORE**

React Shopping Mall Portfolio Project
