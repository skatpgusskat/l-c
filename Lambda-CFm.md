## 람다

1. "안녕" 로그를 출력하는 람다 함수 만들기
2. 현재 Account의 구동중인 EC2의 ID를 출력하는 람다 함수와 Role 만들기
3. 구동중인 EC2 인스턴스의 타입 별 갯수를 출력하는 람다 함수와 Role 만들기

## CloudFormation

1. EC2 타입을 파라미터로 입력받아 EC2 인스턴스를 만드는 CFm 템플릿 만들기
2. AMI ID를 파라미터로 입력받아 EC2 인스턴스를 만드는 CFm 템플릿 만들기
3. "안녕"로그를 출력하는 람다 소스코드를 zip으로 압축하여 S3에 업로드 하기. 그 후 zip 파일의 S3 URL 주소를 파라미터로 받아 람다 함수를 만드는 CFm 템플릿 만들기
4. 구동중인 EC의 ID를 출력하는 람다 소스코드를 zip으로 압축하여 S3에 업로드 하기. 그 후 zip 파일의 S3 URL 주소를 파라미터로 받아 람다 함수를 만들고, 람다 함수에 필요한 IAM Role을 추가하는 CFm 템플릿 만들기

## 람다 트리거

1. 5분마다 "안녕" 로그를 출력하는 람다를 실행하는 환경 만들기
   - Advanced : CFm 템플릿으로 환경 코드화하기
2. API Gateway의 URL을 통해 "안녕" 로그를 출력하는 람다를 실행시키는 환경 만들기
   - Advanced : CFm 템플릿으로 환경 코드화하기
3. DynamoDB를 사용하여 간단한 Todo List Serverless Application 만들기


