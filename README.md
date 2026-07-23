# RIGFORGE Seat Decal Builder v13.1

GitHub Pages에서 바로 작동하는 정적 웹사이트입니다.

## 이번 수정 내용
- PDF 벡터 원본 기준으로 37개 로고 PNG 전면 교체
- 각 PNG 실제 외곽의 좌우 투명 여백 0px
- logos.json의 ratio와 productionHeightAt220 전면 재계산
- 제작용 미리보기와 시트 적용 시뮬레이션의 강제 시각 보정 제거
- 모든 로고를 컨테이너 중앙에 정확히 배치
- 브라우저 캐시 방지를 위한 v13.1 쿼리 적용
- PLAYSEAT 중복 파일 제거

## GitHub 반영 방법
1. 이 ZIP의 압축을 풉니다.
2. GitHub 저장소의 기존 파일을 모두 삭제하거나, 같은 이름의 파일을 전부 덮어씁니다.
3. 반드시 다음 항목이 함께 교체되어야 합니다.
   - index.html
   - logos.json
   - logos 폴더 전체
4. seat_back_mockup.png도 그대로 업로드합니다.
5. Commit changes를 누릅니다.
6. GitHub Pages 반영 후 브라우저에서 Ctrl+F5로 강력 새로고침합니다.

## 정상 파일 수
- logos 폴더: PNG 37개
- PLAYSEAT 파일명: Playseat.png 하나만 존재

## 주의
기존 logos 폴더에 파일을 일부만 덮어쓰지 말고, 폴더 전체를 교체해야 중복 파일과 캐시 문제가 남지 않습니다.
