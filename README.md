<h1><img src="https://noticon-static.tammolo.com/dgggcrkxq/image/upload/v1566919384/noticon/gr2nxbn8xoqdoria9mqh.png" width="28px">&nbsp;&nbsp;프로젝트 관리 서비스</h1>

## 0. 목차

1.  [팀원 소개](#1._팀원_소개)
2.  [프로젝트 개요](#2._프로젝트_개요)
3.  [기술 스택](#3._기술_스택)
4.  [와이어프레임](#4._와이어프레임)
5.  [ERD](#5._ERD)
6.  [API 명세서](#6._API_명세서)
7.  [트러블 슈팅](#7._트러블_슈팅)
8.  [프로젝트 회고](#8._프로젝트_회고)

<br>

## 1. 팀원 소개
<div align="center">

| <img src="https://img.shields.io/badge/Team_Leader-FF5733" /> | <img src="https://img.shields.io/badge/Team_Member-485696" /> | <img src="https://img.shields.io/badge/Team_Member-485696" /> | <img src="https://img.shields.io/badge/Team_Member-485696" /> | <img src="https://img.shields.io/badge/Team_Member-485696" /> |
| :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------------------: | :-----------------------------------------------------------: | :-----------------------------------------------------------: |
|      <img src="https://avatars.githubusercontent.com/u/129417004?v=4" width="120px;" alt=""/>      |      <img src="https://avatars.githubusercontent.com/u/32188154?v=4" width="120px;" alt=""/>      |            <img src="https://avatars.githubusercontent.com/u/175296677?v=4" width="120px;" alt=""/>            |    <img src="https://avatars.githubusercontent.com/u/101707266?v=4" width="120px;" alt=""/>     |    <img src="https://avatars.githubusercontent.com/u/46590521?v=4" width="120px;" alt=""/>     |
|           [조준호](https://github.com/JUNO0432)           |           [김나람](https://github.com/kim-na-ram)           |                 [나유화](https://github.com/fargoe)                |         [정지윤](https://github.com/jiyumi00)          |         [황호진](https://github.com/ballqs)          |
|                            카드<br>담당자<br>인덱싱                            |                            사용자<br>리스트<br>Spring Security<br>CI/CD                            |                                  보드<br>로그 수집<br>모니터링 시스템                                  |                          댓글<br>알람<br>SSE                           |                          워크 스페이스<br>Redis 동시성 제어                           |

</div>
<br>

## 2. 프로젝트 개요

개발 기간 : 24.10.14 - 24.10.17 (1주)

`Trello Clone`은 프로젝트를 효율적으로 관리할 수 있는 Trello의 클론 프로젝트입니다.  
사용자는 워크스페이스 생성, 멤버 초대, 역할 관리, 보드 생성 및 수정, 리스트와 카드 관리를 통해 협업을 더욱 효율적으로 진행할 수 있습니다.

<br>

## 3. 기술 스택

### 💻 개발
![Java](https://img.shields.io/badge/java-%23ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Spring](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=Spring&logoColor=white)
![Spring](https://img.shields.io/badge/Spring%20JPA-6DB33F?style=for-the-badge&logo=Spring&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/docker-2395EC.svg?style=for-the-badge&logo=docker&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31.svg?style=for-the-badge&logo=amazons3&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github_actions-2088FF.svg?style=for-the-badge&logo=githubactions&logoColor=white)
[![Elasticsearch](https://img.shields.io/badge/elasticsearch-005571.svg?style=for-the-badge&logo=elasticsearch&logoColor=white)](https://www.elastic.co/elasticsearch/)
[![Logstash](https://img.shields.io/badge/logstash-005571.svg?style=for-the-badge&logo=logstash&logoColor=white)](https://www.elastic.co/logstash)
[![Kibana](https://img.shields.io/badge/kibana-005571.svg?style=for-the-badge&logo=kibana&logoColor=white)](https://www.elastic.co/kibana/)
[![Prometheus](https://img.shields.io/badge/prometheus-E6522C.svg?style=for-the-badge&logo=prometheus&logoColor=white)](https://prometheus.io/)
[![Grafana](https://img.shields.io/badge/grafana-F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)](https://grafana.com/)

### 💫 그 외
![Figma](https://img.shields.io/badge/Figma-F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

<br>

## 4. 와이어프레임
![스크린샷 2025-03-30 오전 12 48 37](https://github.com/user-attachments/assets/f3905906-02c2-44cb-b947-faadf55e754d)

[Figma](https://www.figma.com/proto/qQXpAfUTnn0wtCwxr0giZ5/Trello-Clone?node-id=0-1&t=lRYxj6UDqxuUymbV-1)

<br>

## 5. ERD
<div>
  <img src="https://github.com/user-attachments/assets/d9367381-5f80-4a8a-9b77-db6bbf390802" width="80%" />
</div>

<br>

## 6. API 명세서
![image](https://github.com/user-attachments/assets/9fad27cf-ed1d-48ce-ab2a-052c019dfa4c)
![image](https://github.com/user-attachments/assets/bb1529ab-f646-4708-be0d-6fbe4320453b)
![image](https://github.com/user-attachments/assets/c5c221f5-0497-4663-9c44-832ac2875230)
![image](https://github.com/user-attachments/assets/9caf4236-0c3c-46b2-9c95-60e3598d8bdd)
![image](https://github.com/user-attachments/assets/9d90e969-17fd-454c-89b5-dcb3b1a97a91)
![image](https://github.com/user-attachments/assets/1ed70796-c140-4d7a-bedf-714c24cd008e)

<br>

## 7. 트러블 슈팅
💡 다른 팀원들의 트러블 슈팅은 <ins>실제</ins> 팀 프로젝트 저장소의 [README.md](https://github.com/Golden-Age-Center/trello-clone-app)에 작성되어 있습니다.  

### Github Actions CI 성능 개선
#### 🔍 문제 원인
- CI가 완료되기까지 3분 10초가 소요되면서 코드 병합에 문제가 없는지 확인하는 데 효율성이 떨어짐.
- CI가 실패할 때마다 로그를 별도로 확인해야 하는데 이 과정은 번거롭고 시간이 소요됨.

#### 💡 해결 방법
- **빌드, 테스트 병렬 실행.**
    - `build`와 `test`는 순차적으로 실행될 필요가 없음.
        - `build`와 `test`를 병렬로 실행하여 전체 실행 시간을 단축.
- **PR 코멘트에 CI의 테스트 결과 자동 게시.**

#### 👩🏻‍💻 도입 전후 비교
- **도입 전**
  - ```build```가 완료된 후, ```test```를 순차적으로 실행하며 총 **3분 10초 소요**.
  - CI 실패 시, (1) PR이 실패함을 확인 (2) Actions 탭으로 진입 (3) 실패한 Action의 상세 확인 (4) 실패한 job의 단계 확인 (4) 실패한 이유 확인.

<br>

- **도입 후**
  - ```build```와 ```test```를 병렬로 실행하며 총 **2분 39초 소요**.
  - CI 실패 시, (1) PR이 실패함을 확인 (2) 코멘트의 ```this check```를 클릭 (3) 로그 확인.

#### 🌟 성능 개선 요약
![image](https://github.com/user-attachments/assets/daa2074c-9f1d-42ce-9bf4-d9611146bb23)

순차 실행에서 병렬 실행으로 수정한 후, 3분 10초였던 실행 시간을 2분 39초로 단축. (약 **16.32% 개선**)  
PR의 코멘트를 통해 오류 로그를 빠르게 확인할 수 있어 개발자가 오류에 신속히 대처 가능.

<br>

## 8. 프로젝트 회고
### 조준호
많은걸 배워가는 느낌이었습니다. 접근 방식과 트러블 슈팅과 여러 회의를 통해 좋은 내용을 알아가는 시간이었습니다.

### 김나람
GitHub Actions를 배우고 CI를 적용해 빌드와 테스트를 자동화할 수 있었습니다. 
덕분에 코드 병합 후에도 개발자의 이슈로 인해 빌드가 실패하는 문제 없이 안정적으로 개발을 진행할 수 있어 편리했습니다.

### 나유화
ELK 및 Grafana를 통한 시스템 모니터링 방법을 습득할 수 있었습니다.

### 정지윤
SSE 기반의 실시간 통신과 이벤트에 관한 내용을 알게 되었습니다.

### 황호진
Redis Cluster를 하면서 많이 힘들었지만 많은 것을 알게 되었습니다. 덕분에 docker-compose 또한 완벽하게 터득할수 있었습니다.
