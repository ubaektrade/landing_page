# 유백무역 (U-Back Trade) - 랜딩페이지

삼성 물산 스타일의 프리미엄 기업 랜딩페이지를 Next.js로 구현하는 프로젝트입니다.

## 📋 프로젝트 개요

### 기업 정보
- **회사명**: 유백무역 (U-Back Trade)
- **업종**: 화장품/잡화/명품 글로벌 유통 및 수출무역
- **핵심사업**: 라이브커머스 기반 글로벌 수출 전문기업
- **목표**: 프리미엄 K-뷰티/패션 수출 플랫폼 이미지 구축

### 회사 소개
원청라인 및 총판 가격 절감 후, **화장품, 건식, 악세사리, 가방, 잡화** 등의 물류를 국내 및 글로벌 수출 도·소매 유통과 수출 무역하는 전문 기업입니다.

**빅셀러들과 탄탄한 물류 유통망**을 대량 보유하고 있으며, **라이브 커머스**를 통해 국내는 물론 **러시아, 몽골, 베트남** 등 해외 각국에 물류 수출을 주관하고 있습니다.

### 주요 목표
- K-뷰티/패션 글로벌 진출의 든든한 파트너
- 라이브커머스 기반 혁신적인 유통 플랫폼
- 원청/총판 직접 연결을 통한 가격 경쟁력
- 검증된 글로벌 물류 네트워크 구축

## 🎯 랜딩페이지 구조 (원페이지)

### 1. 히어로 섹션
```
🏢 메인 비주얼
- 강력한 카피문구
- 회사 핵심 가치 제시
- CTA 버튼 (연락하기/상담문의)

🎯 핵심 메시지
- "K-뷰티를 세계로, 라이브로 연결하다"
- 원청 직접 연결을 통한 최고의 가격 경쟁력
- 라이브커머스 + 글로벌 물류의 혁신적 결합
- 30+ 프리미엄 브랜드와 함께하는 신뢰
```

### 2. 사업 영역 (핵심)
```
💼 4대 핵심 사업
- 💄 K-뷰티 수출: 화장품 브랜드 글로벌 진출 지원
- 👜 패션/잡화: 악세사리, 가방, 의류 등 종합 유통
- 🌟 명품 유통: 디올, 샤넬 등 럭셔리 브랜드 취급
- 📺 라이브커머스: 실시간 방송을 통한 글로벌 판매

📊 핵심 성과 지표
- 협력 브랜드 30+ (디올, 샤넬, 셀트리온 등)
- 글로벌 진출국 (러시아, 몽골, 베트남 등)
- 빅셀러 물류 유통망 보유
- 원청-총판 직접 연결 시스템
```

### 3. 회사 소개 & 협력 브랜드
```
🌟 회사 강점
- 원청/총판 직접 연결을 통한 가격 경쟁력
- 빅셀러 물류 유통망 대량 보유
- 라이브커머스 전문 노하우

🤝 주요 협력 브랜드
💄 화장품: 디올, 샤넬, 그린셀렙, 이자녹스, 셀트리온, 메디필, 메디힐, 제이준, 빌리프, 아누아, 성분에디터, 조선미녀, 차앤박, 사임당, 스킨1004
👜 패션/잡화: 비비안, 디어마이듀 등 명품/패션 브랜드

🌍 글로벌 진출 지역
- 러시아: 라이브커머스 기반 K-뷰티 수출
- 몽골: 화장품/잡화 유통
- 베트남: 종합 물류 수출
- 국내: 도소매 유통 네트워크
```

### 4. 연락처 & CTA
```
📞 수출/유통 상담 문의
- 글로벌 진출 컨설팅
- 라이브커머스 진행 문의
- 물류/유통 파트너십

🤝 브랜드 파트너십
- 신규 브랜드 입점 문의
- 글로벌 수출 대행 서비스
- 빅셀러 네트워크 연결
- 원청/총판 직접 거래 상담
```

## 🛠️ 기술 스택 (랜딩페이지 최적화)

### Frontend
- **Next.js 14** (App Router + SSG)
- **TypeScript**
- **Tailwind CSS**
- **Framer Motion** (스크롤 애니메이션)
- **React Hook Form** (문의 폼)

### UI/UX
- **Shadcn/ui** (컴포넌트)
- **Lucide React** (아이콘)
- **Embla Carousel** (슬라이더)
- **React Intersection Observer** (스크롤 효과)

### 배포 (Vercel Only)
- **Vercel** (호스팅 + 도메인)
- **Vercel Analytics** (방문자 분석)
- **Next.js Image Optimization** (이미지 최적화)
- **Static Export** (정적 사이트 생성)

## 📁 프로젝트 구조 (랜딩페이지)

```
src/
├── app/                    # Next.js App Router
│   ├── page.tsx           # 메인 랜딩페이지 (원페이지)
│   ├── layout.tsx         # 루트 레이아웃
│   ├── globals.css        # 전역 스타일
│   └── favicon.ico        # 파비콘
├── components/            # 랜딩페이지 섹션들
│   ├── sections/          # 메인 섹션 컴포넌트
│   │   ├── Hero.tsx       # 히어로 섹션
│   │   ├── Business.tsx   # 사업영역 섹션
│   │   ├── About.tsx      # 회사소개 섹션
│   │   ├── Stats.tsx      # 성과 지표 섹션
│   │   └── Contact.tsx    # 연락처 섹션
│   ├── ui/               # 재사용 UI 컴포넌트
│   └── common/           # 공통 컴포넌트 (헤더, 푸터)
├── lib/                  # 유틸리티 함수
├── hooks/               # 커스텀 훅 (스크롤 등)
├── types/               # TypeScript 타입
├── data/                # 정적 데이터 (회사정보 등)
└── public/              # 정적 에셋 (이미지, 아이콘)
    ├── images/          # 회사 이미지
    └── icons/           # 아이콘 파일
```

## 🚀 개발 계획 (랜딩페이지)

### Phase 1: 기본 셋업 (1일)
- [ ] Next.js 프로젝트 초기화
- [ ] Tailwind CSS + Shadcn/ui 설정
- [ ] 기본 레이아웃 및 헤더/푸터
- [ ] Vercel 연결 및 배포 설정

### Phase 2: 핵심 섹션 (2-3일)
- [ ] 히어로 섹션 (강력한 첫인상)
- [ ] 사업영역 소개 (4개 부문)
- [ ] 회사 소개 및 강점
- [ ] 성과 지표 (애니메이션)

### Phase 3: 인터랙션 (1-2일)
- [ ] 스크롤 애니메이션 (Framer Motion)
- [ ] 문의 폼 구현
- [ ] 반응형 디자인 완성
- [ ] 이미지 최적화

### Phase 4: 최종 배포 (1일)
- [ ] SEO 메타태그 설정
- [ ] 성능 최적화 검증
- [ ] Vercel Analytics 연결
- [ ] 최종 배포 및 도메인 연결

## 📱 주요 기능 (랜딩페이지)

### 1. 인터랙티브 요소
- 스크롤 트리거 애니메이션
- 섹션별 Fade-in 효과
- 숫자 카운트업 애니메이션
- 부드러운 스크롤 네비게이션

### 2. 사용자 경험
- 원페이지 스크롤 랜딩
- 빠른 로딩 속도
- 모바일 최적화
- 직관적인 CTA 배치

### 3. 성능 최적화 (Vercel)
- Next.js 이미지 최적화
- 정적 사이트 생성 (SSG)
- 자동 코드 스플리팅
- Vercel Edge Functions

## 🎨 디자인 컨셉

### 컬러 팔레트
```css
/* Primary Colors */
--primary-blue: #1e40af;      /* 신뢰성, 전문성 */
--primary-dark: #1e293b;      /* 안정감, 권위 */
--accent-gold: #fbbf24;       /* 프리미엄, 성공 */

/* Secondary Colors */
--secondary-gray: #64748b;    /* 중립성, 균형 */
--light-gray: #f8fafc;        /* 깔끔함, 명료성 */
--white: #ffffff;             /* 순수함, 투명성 */
```

### 타이포그래피
- **제목**: Pretendard Bold/SemiBold
- **본문**: Pretendard Regular
- **영문**: Inter

### 레이아웃 원칙
- 깔끔하고 전문적인 디자인
- 충분한 여백 활용
- 계층적 정보 구조
- 직관적인 네비게이션

## 📊 성능 목표

### Core Web Vitals
- **LCP**: < 2.5초
- **FID**: < 100ms  
- **CLS**: < 0.1

### 접근성
- **WCAG 2.1 AA** 준수
- 키보드 네비게이션 지원
- 스크린 리더 호환

## 🔒 보안 및 SEO

### 보안
- HTTPS 적용
- CSP 헤더 설정
- XSS/CSRF 방어
- 입력값 검증

### SEO
- 메타 태그 최적화
- 구조화된 데이터
- 사이트맵 생성
- 페이지 속도 최적화

## 🚀 시작하기

### 개발 환경 설정
```bash
# 저장소 클론
git clone https://github.com/your-username/ubaek-trade
cd ubaek-trade

# 의존성 설치
npm install

# 환경변수 설정
cp .env.example .env.local

# 개발 서버 실행
npm run dev
```

### 환경변수 (필요시)
```env
# 문의 폼 이메일 전송 (선택사항)
RESEND_API_KEY=""
CONTACT_EMAIL=""

# Vercel Analytics (자동 설정)
VERCEL_ANALYTICS_ID=""
```

## 📝 기여 방법

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다.

## 📞 연락처

- **개발팀**: dev@ubaek-trade.com
- **기획팀**: planning@ubaek-trade.com
- **GitHub**: [https://github.com/ubaek-trade](https://github.com/ubaek-trade)

---

*"글로벌 네트워크로 연결하는 미래의 가치" - 유백무역*
