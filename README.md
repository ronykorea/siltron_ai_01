# SK 실트론 동반성장 포털

SK 실트론 협력사를 위한 동반성장 포털 웹사이트입니다.

## 🎨 디자인 소스

이 프로젝트는 Figma에서 디자인되어 HTML/CSS/JavaScript로 구현되었습니다.

## 📋 주요 기능

### 1. 메인 페이지
- **Hero Section**: 동반성장 비전과 핵심 메시지 전달
- **통계 섹션**: 4가지 핵심 성과 지표 표시
- **프로그램 섹션**: 금융/기술/교육/경영 지원 프로그램 소개
- **공지사항**: 최신 소식 및 공지사항
- **반응형 디자인**: 모바일, 태블릿, 데스크톱 지원

### 2. 사용자 경험
- 스무스 스크롤 네비게이션
- 카드 호버 애니메이션
- 통계 카운터 애니메이션
- Scroll-to-top 버튼
- 모바일 햄버거 메뉴

## 🚀 시작하기

### 필요 환경
- 최신 웹 브라우저 (Chrome, Firefox, Safari, Edge)
- 로컬 웹 서버 (선택사항)

### 설치 및 실행

1. **저장소 클론**
```bash
cd /Users/rony/dev/siltron_project_01
```

2. **파일 구조 확인**
```
siltron_project_01/
├── index.html          # 메인 HTML 파일
├── styles.css          # 스타일시트
├── script.js           # JavaScript 기능
└── README.md          # 프로젝트 문서
```

3. **실행 방법**

   **방법 1: 직접 열기**
   - `index.html` 파일을 더블클릭하여 브라우저에서 열기

   **방법 2: 로컬 서버 사용 (권장)**
   ```bash
   # Python 3을 사용하는 경우
   python3 -m http.server 8000
   
   # Python 2를 사용하는 경우
   python -m SimpleHTTPServer 8000
   
   # Node.js의 http-server를 사용하는 경우
   npx http-server -p 8000
   ```
   
   브라우저에서 `http://localhost:8000` 접속

## 🎨 디자인 시스템

### 색상 팔레트
- **Primary (SK Red)**: `#D91A26`
- **Text Dark**: `#333333`
- **Text Gray**: `#666666`
- **Text Light**: `#808080`
- **Background Gray**: `#F7F7F7`
- **Border Gray**: `#E6E6E6`
- **White**: `#FFFFFF`

### 타이포그래피
- **Primary Font**: Noto Sans KR
- **Fallback**: -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif

### 반응형 브레이크포인트
- **Desktop**: 1200px 이상
- **Tablet**: 768px ~ 1199px
- **Mobile**: 767px 이하

## 📱 반응형 디자인

이 웹사이트는 다음과 같이 반응합니다:

- **Desktop (1200px+)**: 4열 그리드 프로그램 카드
- **Tablet (768px-1199px)**: 2열 그리드, 조정된 간격
- **Mobile (<768px)**: 1열 레이아웃, 모바일 메뉴

## 🔧 커스터마이징

### CSS 변수 수정
`styles.css` 파일의 `:root` 섹션에서 색상을 변경할 수 있습니다:

```css
:root {
    --sk-red: #D91A26;
    --text-dark: #333333;
    /* 기타 변수들... */
}
```

### 콘텐츠 수정
- **텍스트**: `index.html` 파일에서 직접 수정
- **이미지**: `index.html`의 이미지 경로 변경
- **스타일**: `styles.css`에서 CSS 수정
- **기능**: `script.js`에서 JavaScript 수정

## 📦 향후 개발 계획

### Phase 1: 기능 확장
- [ ] 로그인/회원가입 시스템
- [ ] 협력사 대시보드
- [ ] 프로그램 신청 시스템
- [ ] 온라인 교육 플랫폼

### Phase 2: 고도화
- [ ] AI 챗봇 통합
- [ ] 실시간 알림 시스템
- [ ] 협력사 커뮤니티
- [ ] 모바일 앱 (PWA)

### Phase 3: 데이터 분석
- [ ] Google Analytics 연동
- [ ] 성과 측정 대시보드
- [ ] A/B 테스트 시스템

## 🔒 보안 고려사항

향후 추가될 기능:
- HTTPS 적용
- CSRF 보호
- XSS 방지
- SQL Injection 방지
- 2단계 인증 (2FA)

## 🌐 브라우저 지원

- Chrome (최신 2개 버전)
- Firefox (최신 2개 버전)
- Safari (최신 2개 버전)
- Edge (최신 2개 버전)
- 모바일 브라우저 (iOS Safari, Chrome)

## 📞 문의

**SK 실트론 동반성장 포털**
- 주소: 경기도 구미시 공단로 57 SK실트론
- 전화: 054-460-8114
- 이메일: partner@sksiltron.com

## 📄 라이선스

© 2024 SK Siltron. All rights reserved.

---

**개발 정보**
- 디자인: Figma
- 개발: HTML5, CSS3, Vanilla JavaScript
- 버전: 1.0.0
- 최종 업데이트: 2024.10.31

