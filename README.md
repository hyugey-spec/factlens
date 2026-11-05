# 팩트렌즈

지역 언론사 기자용 팩트체크 도구. 주장을 입력하면 Tavily로 근거를 최대 5건 검색하고 Gemini가 근거만 보고 6단계로 판정합니다.

## 실행

```bash
python3 -m http.server 8000
```

브라우저에서 `http://localhost:8000/index.html`을 열고, 설정 창에 Tavily·Gemini API 키를 입력합니다. 키는 파일에 저장되지 않고 이 브라우저에만 저장됩니다.
