slidenumbers: true
# Daangn Market
## Back-end

---

## Contents
1. Deploy Model
2. Prerequisites
3. Setup
4. Dependency
5. 문제 해결
6. 추가 요소
7. API documents

---

## 1. Deploy Model

![inline](https://daangn-market.s3.ap-northeast-2.amazonaws.com/daangn_deploy.png)

---

## 2. Prerequisites
* Secrets JSON File
`<project-root>/secrets.json`
* Firebase SDK
* Firebase Config JSON
* [GeoDjango](https://docs.djangoproject.com/en/3.0/ref/contrib/gis/install/#homebrew)  

---

## 3. Setup
* Database
`POSTGIS="2.5.2 r17328"`
* Extension
 `drf-yasg` : API description generator
 `sentry-sdk`: Error Tracking
 `django-debug-toolbar`: Debuging helper
 `django-extensions`: shell helper

---

## 4. Dependency
```toml
python = "^3.7"
django = "^3.0.4"
djangorestframework = "^3.11.0"
django-filter = "^2.2.0"
markdown = "^3.2.1"
django-import-export = "^2.0.2"
psycopg2-binary = "^2.8.4"
Pillow = "^7.0.0"
requests = "^2.23.0"
supervisor = "^4.1.0"
gunicorn = "^20.0.4"
drf-yasg = "^1.17.1"
sentry-sdk = "^0.14.3"
ssv = "^0.1.1"
flex = "^6.14.1"
firebase-admin = "^4.0.0"
django-cors-headers = "^3.2.1"
django-push-notifications = "^2.0.0"
django-storages = "^1.9.1"
boto3 = "^1.12.39"

django-debug-toolbar = "^2.2"
django-extensions = "^2.2.9"
```

---

## 6. 문제 해결
**문제** : 기준 위치 설정과 위도,경도 값 데이터 필요
**해결** : 동 데이터 가공

* data.seoul.go.kr
* 네이버 maps API

---

## 6. 추가 요소
# [fit]Chat
# [fit]Test Code
# [fit]CI/DI

---

## 7. API document

# [fit]daangnmarket.shinjam.xyz/docs


