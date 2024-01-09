![coredot-chat-demo](logo.svg)

Redis를 이용한 채팅 구현의 이해를 돕기 위해서 만든 데모.

## 활용 라이브러리
- redis==4.6.0
- starlette==0.27.0
- broadcaster[redis]==0.2.0

## 이용방법
```bash
uvicorn run:app --reload --port 8000
```