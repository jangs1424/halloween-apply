# 할로윈 축제 신청 QR

고정 주소: https://jangs1424.github.io/halloween-apply/

## 신청폼 연결 또는 변경

1. 이 저장소의 `config.json`을 열고 연필(Edit) 버튼을 누릅니다.
2. `destinationUrl`의 빈 따옴표 안에 신청폼의 전체 HTTPS 주소를 넣습니다.
3. Commit changes로 저장하고 GitHub Pages 배포가 끝나면 QR을 스캔해 확인합니다.

예시:
```json
{
  "destinationUrl": "https://forms.gle/실제신청폼주소"
}
```

빈 문자열 `""`로 두면 ‘신청 준비 중입니다’가 표시됩니다.
QR에는 위 고정 주소가 들어 있으므로 신청폼만 바꿔도 재인쇄할 필요가 없습니다.
GitHub 계정명, 저장소 이름, Pages 주소를 바꾸거나 저장소를 삭제하면 기존 QR 연결이 끊길 수 있습니다.
신청자 데이터는 이 저장소에 저장하지 않습니다.
