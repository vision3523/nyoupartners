# NYOUPARTNERS Website

![NYOUPARTNERS Logo](images/company/nyoupartners_logo.jpg)

## 📋 프로젝트 개요

NYOUPARTNERS는 급여/인사 시스템 컨설팅 및 운영 서비스를 제공하는 기업의 공식 웹사이트입니다. 현대적이고 반응형 디자인을 적용하여 모바일과 데스크톱 환경에서 최적의 사용자 경험을 제공합니다.

## 🚀 주요 기능

- **반응형 디자인**: 모바일, 태블릿, 데스크톱 최적화
- **현대적 UI/UX**: 보라색 그라데이션 테마와 카드 기반 레이아웃
- **CEO 커리어 섹션**: 업종별로 분류된 파트너사 로고 그리드
- **인터랙티브 요소**: 스크롤 애니메이션 및 호버 효과
- **한국어 콘텐츠**: 비즈니스 환경에 적합한 존댓말 사용

## 📁 프로젝트 구조

```
nyoupartners/
├── index.html              # 홈페이지
├── service.html            # 서비스 소개
├── members.html            # 팀 소개 (CEO 커리어 섹션 포함)
├── partners.html           # 파트너사
├── contact.html            # 문의하기
├── css/
│   └── styles.css          # 메인 스타일시트
├── js/
│   └── script.js           # 메인 JavaScript
├── images/
│   └── company/            # 회사 로고 (25개)
│       ├── hyundai-mobis.png
│       ├── valeo.png
│       ├── borgwarner.png
│       └── ... (기타 로고들)
├── .cursor/
│   └── rules/              # Cursor AI 규칙들
└── README.md               # 프로젝트 문서
```

## 🎨 디자인 시스템

### 색상 팔레트
- **주요 그라데이션**: `linear-gradient(135deg, #667eea 0%, #764ba2 100%)`
- **카드 배경**: `#ffffff` (그림자 효과 포함)
- **텍스트**: `#333333` (주요), `#666666` (보조)

### 타이포그래피
- **폰트 패밀리**: Inter, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif
- **폰트 웨이트**: 400 (일반), 500 (중간), 600 (세미볼드), 700 (볼드)

### 공통 컴포넌트
- `.common-card`: 카드 레이아웃
- `.common-icon`: 원형 아이콘 컨테이너
- `.common-hero`: 히어로 섹션
- `.common-section`: 표준 섹션

### 애니메이션 클래스
- `.animate-on-scroll`: 스크롤 기반 페이드인
- `.animate-scale`: 확대 애니메이션
- `.animate-delay-1~4`: 순차적 애니메이션

## 🏢 CEO 커리어 섹션

대표이사의 주요 경력을 업종별로 분류하여 시각적으로 표현:

### 업종별 분류
1. **제조업**: 현대모비스, Valeo, BorgWarner, Hilti
2. **IT/기술**: Eugene Technology, AMD, BESPIN GLOBAL, TEL
3. **식품/외식**: 맥도날드, Tyson, Mom's Touch, 조스떡볶이
4. **화장품/제약**: Cocodor, Dr.Jart+, Nutrione, 유영제약
5. **인사/급여 시스템**: 더존, 이수시스템, 화이트정보, 뉴젠, NAVER Cloud Platform, 영림원, 매직소프트, 예타

### 특별 사항
- **Araline**: base64 인코딩으로 직접 포함 (다운로드 이슈)
- **그리드 레이아웃**: 컨설팅 회사는 4열, 기타는 3열
- **호버 효과**: 그레이스케일에서 컬러로 전환

## 📱 반응형 디자인

### 브레이크포인트
- **모바일**: `@media (max-width: 600px)`
- **태블릿**: `@media (max-width: 900px)`
- **데스크톱**: 기본 스타일

### 모바일 최적화
- 햄버거 메뉴 네비게이션
- 터치 친화적 버튼 크기 (최소 45px)
- 단일 컬럼 그리드 레이아웃
- 최적화된 텍스트 크기

## 🛠 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: Flexbox, Grid, 애니메이션
- **JavaScript (ES6+)**: 인터랙티브 기능
- **Font Awesome**: 아이콘
- **Google Fonts**: Inter 폰트

## 🚀 시작하기

### 로컬 개발 환경 설정

1. **저장소 클론**
   ```bash
   git clone [repository-url]
   cd nyoupartners
   ```

2. **로컬 서버 실행**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js (http-server 설치 필요)
   npx http-server
   
   # PHP
   php -S localhost:8000
   ```

3. **브라우저에서 확인**
   ```
   http://localhost:8000
   ```

## 📝 개발 가이드라인

### 파일 구조 규칙
- **JavaScript**: `js/` 폴더에 저장
- **이미지**: 회사 로고는 `images/company/` 폴더에 저장
- **CSS**: 단일 파일 `css/styles.css` 사용

### 명명 규칙
- **클래스명**: kebab-case 사용 (예: `common-card`)
- **파일명**: 회사 로고는 kebab-case (예: `hyundai-mobis.png`)
- **이미지 alt 텍스트**: 설명적이고 접근성 고려

### 코드 스타일
- **HTML**: 시맨틱 마크업 사용
- **CSS**: 공통 클래스 우선 사용
- **JavaScript**: ES6+ 문법 사용

## 🔧 유지보수

### 최근 완료된 작업
- ✅ JavaScript 파일을 `script/`에서 `js/` 폴더로 이동
- ✅ 모든 HTML 파일의 스크립트 참조 업데이트
- ✅ 25개 회사 로고 다운로드 및 로컬 저장
- ✅ CEO 커리어 섹션 디자인 개선
- ✅ 반응형 그리드 레이아웃 구현

### 향후 고려사항
- 로고 품질 모니터링 및 업데이트
- 추가 인터랙티브 기능 구현
- 이미지 로딩 성능 최적화
- 반응형 디자인 지속적 개선

## 📞 문의

프로젝트 관련 문의사항이 있으시면 언제든지 연락주세요.

---

**NYOUPARTNERS** - 급여/인사 시스템 컨설팅 전문기업 