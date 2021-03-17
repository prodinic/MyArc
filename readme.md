# 강의계획서

## 목표
대규모 아키텍처를 설계할 수 있다. 

## 목차



### 모듈 1 - Introduction 
* well-architected 프레임워크 [참고](https://aws.amazon.com/architecture/well-architected/?wa-lens-whitepapers.sort-by=item.additionalFields.sortDate&wa-lens-whitepapers.sort-order=desc)
    * 안정성 - 컴퓨팅 리소스를 동적으로 확보하여 수요를 충족 
    * 비용최적화 - 불필요한 비용 제거
    * 보안 - 추적 및 거버넌스 구축
    * 성능효율성 - 효율적인 리소스를 선택하고 수요 변화에 맞춰 효율성 유지 
        * mechanical sympathy - 어떻게 잘 이용할 수 있는 지에 대한 이해를 바탕으로 툴이나 시스템을 사용하는 것
    * 운영우수성
* 글로벌 인프라
    * 데이터센터
    * 가용영역
    * 리전
    * 엣지로케이션
    * 리전 엣지 캐시 - 엣지 로케이션의 엣지 로케이션
* 대규모 아키텍처

### 모듈 2 - Simplest Architectures
* S3
    * 내구성이란 무엇인가? 저장된 데이터의 안전성. 여러 리전에 데이터를 복제 및 저장. 내구성 및 가용성 확보. 
    * S3 ACL - 레거시 엑세스 컨트롤 매커니즘. 그대로 사용해도 됨. 어떤 계정이나 그룹이 접근 권한이 있고 어떤 종류를 갖고 있는 지 정의할 수 있다. [참고](https://aws.amazon.com/blogs/security/iam-policies-and-bucket-policies-and-acls-oh-my-controlling-access-to-s3-resources/)
    * S3 엑세스 제어 정책 - S3의 버킷 레벨에 부여할 수 있는 정책. 정책 안의 모든 오브젝트에 영향을 미침.
    * S3 엑세스 포인트
    * CORS(Cross-Origin Resource Sharing) - 한 도메인에서 로드되어 다른 도메인에 있는 리소스와 상호 작용하는 클라이언트 웹 애플리케이션에 대한 방법. 
    * 멀티 파트 업로드 - 멀티 파트 업로드 API를 사용하면 대형 객체를 여러 개로 나누어 업로드 가능. 
    * S3 Transfer Acceleration
    * S3 로 데이터 이동
        * 온라인으로
        * 오프라인으로
* S3 Glacier - 아카이빙 서비스
    * 스토리지 클래스 
    * 수명 주기 정책
* 데모 1 - 정적 웹 호스팅


### 모듈 3



### 모듈 4




### 모듈 9 - 




### 모듈 10




### 모듈 11




