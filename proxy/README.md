# Proxy 학습

프록시 개념을 기초부터 정리한다. 개념 정리 `.md`와 실습 설정(`examples/`)으로 구성.

## 프록시란?

클라이언트와 서버 사이에 위치해 요청/응답을 대신 전달(중계)하는 중간 서버.
"누구를 대신하느냐"에 따라 방향(Forward / Reverse)이 갈린다.

```
[Forward Proxy]  Client → (Proxy) → Internet/Server     # 클라이언트를 대신
[Reverse Proxy]  Client → Internet → (Proxy) → Server   # 서버를 대신
```

## 로드맵

### 1. 기초
- [ ] 프록시 개념과 필요성 (왜 중간 서버를 두는가)
- [ ] Forward Proxy vs Reverse Proxy 차이
- [ ] 프록시 vs 게이트웨이 vs 로드밸런서 용어 정리

### 2. Forward Proxy
- [ ] 동작 방식 (클라이언트 설정, 아웃바운드 제어)
- [ ] 활용: 캐싱, 접근 제어, 익명화, 콘텐츠 필터링

### 3. Reverse Proxy
- [ ] 동작 방식 (단일 진입점, 백엔드 숨김)
- [ ] 활용: 로드밸런싱, SSL 종료, 캐싱, 압축, 보안
- [ ] 대표 구현체: Nginx, HAProxy, Envoy

### 4. 관련 개념
- [ ] 로드밸런서 (L4 vs L7)
- [ ] API Gateway
- [ ] CDN과의 관계
- [ ] TLS/SSL Termination
- [ ] Sidecar Proxy (서비스 메시, Envoy/Istio)

### 5. 실습
- [ ] Nginx 리버스 프록시 설정 예제
- [ ] 로드밸런싱 설정 예제

## 진행 기록

| 날짜 | 내용 |
|------|------|
| 2026-10-07 | 프록시 학습 폴더 및 로드맵 셋업 |
