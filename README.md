# 🗓️ 스터디 일정 요약 (10월 말 ~ 11월 초 리뷰 예정)

---

## ✅ 1단계 — Flask 기본 웹앱 구현

**목표:**  
Python Flask로 간단한 웹 서버 구축

**내용:**  
- “Hello World” 페이지 띄우기

**참고:**  
- 로컬 PC에 Docker 설치  
- [http://127.0.0.1:5000](http://127.0.0.1:5000) 로 접속 테스트

---

## ✅ 2단계 — Docker 이미지 빌드 및 푸시 자동화

**목표:**  
Flask 앱을 Docker 이미지로 빌드 후 ECR에 업로드

**내용:**  
- `Dockerfile` 작성  
- GitHub Actions로 CI 파이프라인 구성 (빌드 → ECR Push)

**결과:**  
- ECR에 최신 Flask 이미지 확인

---

## ✅ 3단계 — Argo CD를 통한 배포 자동화

**목표:**  
Argo CD에서 ECR 이미지를 Pull하여 배포 테스트

**내용:**  
- Auto Sync / Manual Sync 방식 비교  
- EKS 또는 로컬 k8s 환경 중 선택

---

## ✅ 4단계 — Argo CD Image Updater 조사

**목표:**  
이미지 자동 업데이트 동작 구조 및 설정 방식 이해

**내용:**  
- Application annotation 예시  
- Git write-back / pull-request 방식 비교
