# Kubernetes 학습

k8s를 기초부터 하나씩 정리한다. 각 챕터는 개념 정리 `.md`와 실습 매니페스트(`manifests/`)로 구성.

## 로드맵

### 1. 기초 개념
- [ ] 컨테이너 vs 오케스트레이션 (왜 k8s가 필요한가)
- [ ] 클러스터 구조: Control Plane(API Server, etcd, Scheduler, Controller Manager) / Node(kubelet, kube-proxy, container runtime)
- [ ] `kubectl` 기본 사용법

### 2. 워크로드
- [ ] Pod
- [ ] ReplicaSet / Deployment
- [ ] StatefulSet / DaemonSet
- [ ] Job / CronJob

### 3. 네트워킹
- [ ] Service (ClusterIP / NodePort / LoadBalancer)
- [ ] Ingress
- [ ] DNS, 서비스 디스커버리

### 4. 설정과 스토리지
- [ ] ConfigMap / Secret
- [ ] Volume, PV / PVC, StorageClass

### 5. 운영
- [ ] Namespace, 리소스 쿼터
- [ ] 라벨 / 셀렉터 / 어노테이션
- [ ] Liveness / Readiness Probe
- [ ] 리소스 requests / limits, HPA
- [ ] RBAC

### 6. 실습 환경
- [ ] 로컬 클러스터 (minikube / kind / Docker Desktop)
- [ ] 샘플 앱 배포해보기

## 진행 기록

| 날짜 | 내용 |
|------|------|
| 2026-10-07 | 레포 및 학습 구조 셋업 |
