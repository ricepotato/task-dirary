# Task Diary

## 2024-15-18

### 해야할 일
- waas 개발
- vpc 내 ecs 보안 설정 리서치
 - 테스트 app 배포 인터넷접근/ssm 접근 가능한지 확인

### 어제 한 일

- waas 개발
- waas 코드리뷰
  - fix/billing 코드리뷰
  - WAAS-9 코드리뷰
- vpc 내 ecs 보안 설정 리서치
 - 테스트 app 배포 인터넷접근/ssm 접근 가능한지 확인

## 2024-15-17

### 해야할 일
- waas 개발
- waas 코드리뷰
  - fix/billing 코드리뷰
  - WAAS-9 코드리뷰
- vpc 내 ecs 보안 설정 리서치
 - 테스트 app 배포 인터넷접근/ssm 접근 가능한지 확인

### 어제 한일
- vpc 내 ecs 보안 설정 리서치
 - 테스트 app 배포 인터넷접근/ssm 접근 가능한지 확인
- AWW-182 merge, dev/stg 환경에 patch
- waas 일정 회의

## 2024-15-16

### 해야할 일

- vpc 내 ecs 보안 설정 리서치
  - 테스트 app 배포 인터넷접근/ssm 접근 가능한지 확인
- AWW-182 merge, dev/stg 환경에 patch

### 어제 한 일

- NFT Viewer 패치/모니터링 (0.8.4)
- AWW-182 skeleton, placeholder 추가 작업
- WaaS 일정 회의


## 2024-01-15

### 해야할 일

- NFT Viewer 패치/모니터링 (AWW-179)
- vpc 내 ecs 보안 설정 리서치
  - 테스트 app 배포 인터넷접근/ssm 접근 가능한지 확인

### 어제 한 일

- vpc 내 ecs 보안 설정 리서치
- waas 코드리뷰 (오프라인)
- NFT Viewer 이슈 확인 (AWW-179)

## 2024-01-12

### 해야할 일
- vpc 내 ecs 보안 설정 리서치
- waas 코드리뷰 (오프라인)
- NFT Viewer 이슈 확인 (AWW-179)

### 어제 한 일
- waas 개발
  - organizations 화면 구현
- ethanol 코드 리뷰(오프라인)
- waas 코드 리뷰 (온라인)
- vpc 내 ecs 보안 설정 리서치

## 2024-01-11

### 해야할 일
- waas 개발
  - organizations 화면 구현
- ethanol 코드 리뷰(오프라인)
- vpc 내 ecs 보안 설정 리서치

### 어제 한 일

- waas super admin project 화면 구현
- waas 코드 리뷰(온라인)
- ethanol 코드 리뷰(온라인)
- parameter store 에서 데이터를 가져와 ecs 에서 사용하는 방법 연구


## 2024-01-10

### 해야할 일

- parameter store 에서 데이터를 가져와 ecs 에서 사용하는 방법 연구
  - parameter store 의 값을 암호화 하고 복호화 해서 환경변수에 추가할 수 있으면 좋을듯

### 어제 한 일

- parameter store 에서 값을 가져와 amplify 에서 사용하는 방법
  - amplify 에서 service role 에 권한을 주어도 IAM 권한을 얻을 수 없음
  - amplify service role 은 lambda edge runtime 에 적용되지 않음
  - AWS_ACCESS_KEY_ID, AWS_SECRET_ACCESS_KEY 를 환경변수에 추가하는 방법으로 가능
  - amplify 에서는 AWS_ 로 시작하는 환경변수를 직접 추가할 수 없음

## 2024-01-09

### 해야할 일

- parameter store 에서 데이터를 가져와 앱에 적용 기능 구현

### 어제 한 일

- parameter store 리서치
- WaaS Users 페이지 구현
- Waas Logger 개선
  - logstash logger 제거
  - 개발중, 운영중일 때 logger format 이 다르게 출력되게 변경

## 2024-01-08

### 해야할 일

- waas User List 화면 구현

### 지난주 한 일

- cloudwatch 검색 방법 리서치


## 2024-01-04

### 해야할 일

#### foreground tasks
- [ ] waas 코드 리뷰
- [ ] cloudwatch 검색 방법 리서치

#### background tasks
- [ ] indexer research


### 어제 한일
- ECS 배포 방법 리서치
  - github action 으로 ECS 배포
  - secret manager 에서 값을 가져와 ECS 배포 컨테이너에 환경변수 추가하는 방법

### 표현  
- 선행기술 연구
- 연구개발
- 공부
- 적용 가능성 리서치
