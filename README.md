# 제이스칸 교육 말하기대회 연습앱

음성 파일을 업로드하고 반복 연습할 수 있는 웹 애플리케이션입니다.

## 🎯 주요 기능

- **음성 파일 업로드**: MP3, WAV, M4A 등 다양한 오디오 형식 지원
- **반복 재생**: 연습을 위한 반복 재생 기능
- **로컬 저장**: IndexedDB를 사용한 브라우저 로컬 저장
- **파일 관리**: 업로드된 파일 목록 확인 및 삭제
- **반응형 디자인**: 모바일과 데스크톱에서 모두 사용 가능

## 🚀 사용 방법

1. 음성 파일을 업로드 영역에 드래그하거나 클릭하여 선택
2. 업로드된 파일을 클릭하여 재생
3. 반복 재생 체크박스를 활성화하여 연속 재생
4. 불필요한 파일은 삭제 버튼으로 제거

## 🛠️ 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: Tailwind CSS 프레임워크
- **JavaScript**: ES6+ 클래스 기반 구조
- **IndexedDB**: 로컬 데이터베이스 저장
- **Font Awesome**: 아이콘 라이브러리

## 📱 배포

이 프로젝트는 GitHub Pages를 통해 배포됩니다.

### 로컬에서 실행

1. 프로젝트를 클론합니다:
```bash
git clone https://github.com/your-username/worclejacekhan.git
cd worclejacekhan
```

2. `index.html` 파일을 웹 브라우저에서 열거나 로컬 서버를 실행합니다:
```bash
# Python 3
python -m http.server 8000

# 또는 Node.js
npx serve .
```

3. 브라우저에서 `http://localhost:8000`으로 접속

### GitHub Pages 배포

1. GitHub 저장소 설정에서 Pages 활성화
2. Source를 "Deploy from a branch"로 설정
3. Branch를 `main`으로 선택
4. Save 클릭

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다.

## 🤝 기여

버그 리포트나 기능 제안은 이슈를 통해 해주세요.

---

**개발자**: 제이스칸 교육팀  
**버전**: 1.0.0  
**최종 업데이트**: 2024년 