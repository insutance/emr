## 1) 데이터 베이스 및 스키마 생성
Q1~Q6 를 하기 위해서는 데이터베이스 및 스키마를 생성해야 한다.

1. 데이터 베이스 생성 : `create database 'test';`
2. 데이터 베이스 연결 : `\connect test;`
3. 스키마 생성 : `create schema emr;`

`Q1.md`에서 데이터 복사를 할 때, `FROM` 절에서는 데이터 저장경로를 직접 입력해야 합니다.

## 2) `psycopg2` 설치
```
pip install psycopg2
```
`Q7.py` 파일 4번째 줄 데이터 베이스 연결 정보를 직접 입력 해야한다.