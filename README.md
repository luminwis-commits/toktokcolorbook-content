# 톡톡컬러북 서버 그림

톡톡컬러북 앱이 받아 쓰는 그림 파일이에요. 앱 업데이트 없이 그림을 늘리기 위한 저장소예요.

- `v1/catalog.json`: 그림 목록 (앱이 켤 때 받는다)
- `v1/files/`: 그림 원본(WebP)·썸네일·레벨별 도안(gzip)

이 저장소는 직접 고치지 않는다. 프로젝트의 `tools/update_content.py` → `tools/publish_content.py`로 만들고 올린다.
