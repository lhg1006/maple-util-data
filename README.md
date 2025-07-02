# Maple Util Data CDN

이 디렉토리는 메이플스토리 데이터를 CDN으로 서빙하기 위한 JSON 파일들을 포함합니다.

## 파일 구조
- `items-[n].json`: 아이템 데이터 (청크로 분할)
- `items-index.json`: 아이템 청크 인덱스
- `monsters.json`: 몬스터 데이터
- `maps.json`: 맵 데이터

## 사용 방법
jsDelivr CDN을 통해 접근:
```
https://cdn.jsdelivr.net/gh/[username]/[repo]@main/items-1.json
```

## 업데이트
매주 자동으로 업데이트됩니다.
