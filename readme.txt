================================================================
  B2B VWE 계산기 (B2B Value Word Equation Calculator)
  나눔경영컨설팅
================================================================

[프로젝트 개요]
B2B 영업에서 고객사에 비용 절감 효과를 시각적으로 보여주기 위한
VWE(Value Word Equation) 계산기 웹앱 모음입니다.
경쟁사 대비 자사 솔루션의 TCO(총소유비용) 절감 효과를 계산하고,
차트와 시뮬레이션 테이블로 직관적으로 비교합니다.

[VWE 개념]
VWE(Value Word Equation)는 B2B 영업에서 사용하는 가치 제안 공식입니다.
경쟁사 솔루션과 자사 솔루션의 총비용을 비교하여
고객이 얻을 수 있는 절감 효과를 수치로 증명합니다.

공식: (경쟁사 총비용) - (자사 총비용) = TCO 절감액

[폴더 구조]
02_B2B-vwe/
├── readme.txt                          : 프로젝트 설명 (이 파일)
├── .gitignore                          : Git 추적 제외 설정
└── 01.nanum_consulting/                : 나눔경영컨설팅 VWE 계산기
    └── b2b-vwe-nanum.html              : VWE 계산기 웹앱

※ 향후 기업별로 폴더를 추가하여 각 기업 맞춤 VWE 계산기를 관리합니다.
   예) 02.company_a/, 03.company_b/ ...

[01. 나눔경영컨설팅 VWE 계산기]
- 파일: 01.nanum_consulting/b2b-vwe-nanum.html
- 용도: 전력/장비/인건비 기반 TCO 비교 계산기
- 주요 기능:
  · 경쟁사 vs 자사 솔루션 비용 비교 (전력비, 장비비, 인건비)
  · 시뮬레이션 기간 설정 (1~10년)
  · 연도별 누적비용 시뮬레이션 테이블
  · BEP(손익분기점) 자동 계산 및 표시
  · 비용 비교 바 차트 (애니메이션)
  · 자동 요약 텍스트 생성
  · 경쟁사 조건 동일 적용 체크박스
  · 반응형 디자인 (모바일 대응)
- 입력 항목:
  · KW(소비전력), 장비수, 가동시간, 전기요금단가
  · 사업장수, 장비단가, 장비당 인원, 1인당 연봉
- 기술: HTML5, CSS3, Vanilla JavaScript (단일 파일, 백엔드 불필요)
- 폰트: Pretendard (Google Fonts CDN)

[기술 스택]
- 프론트엔드: HTML5, CSS3, Vanilla JavaScript
- 백엔드: 없음 (순수 프론트엔드 계산기)
- 폰트: Pretendard (Google Fonts)
- 호스팅: GitHub Pages (jazzmania74.github.io/B2B-vwe)

[개발 환경 및 배포]
- 소스 코드: Google Drive (01.나눔경영컨설팅 웹앱(코딩)★/02_B2B-vwe/)
- Git 저장소: Google Drive 폴더에서 직접 Git 관리
- GitHub: jazzmania74/B2B-vwe (main 브랜치)
- 배포 URL: https://jazzmania74.github.io/B2B-vwe/01.nanum_consulting/b2b-vwe-nanum.html
- 수정 후 배포: git add → git commit → git push origin main → GitHub Pages 자동 반영

[기업별 VWE 계산기 추가 방법]
1. 새 폴더 생성: XX.company_name/
2. HTML 파일 작성 (기존 파일을 템플릿으로 활용)
3. 비교 항목을 해당 기업/산업에 맞게 수정
4. git add → git commit → git push

[주의사항]
- 각 VWE 계산기는 독립적인 단일 HTML 파일로 관리됩니다
- 백엔드가 필요 없으므로 GitHub Pages만으로 배포 가능합니다
- 새 기업 추가 시 폴더 네이밍 규칙: XX.company_name (번호.영문이름)

================================================================
