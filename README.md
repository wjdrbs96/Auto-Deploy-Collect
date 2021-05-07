# `자동화 배포 한눈에 정리하기`

<br>

## `1. Jenkins 자동화 배포`

![1](https://user-images.githubusercontent.com/45676906/113641161-05c6de00-96b8-11eb-8e93-6b3c300bc7d6.png)

- [자동화 배포 과정 정리](https://devlog-wjdrbs96.tistory.com/295)

<br>

### `사용된 도구`

- Spring Boot
- Github
- Jenkins
- EC2 Linux 2 2대
- CodeDeploy
- S3 
- Docker

<br>

## `2. 무중단 자동화 배포`

![2](https://camo.githubusercontent.com/cc9fd5ff1b28c4d41067f7bdfd6563f7d01c610f14305a74b5c788d5f91821d1/68747470733a2f2f74312e6461756d63646e2e6e65742f6366696c652f746973746f72792f393936463736334435413733463931453236)

- [자동화 배포 과정 정리](https://devlog-wjdrbs96.tistory.com/309)

<br>

### `사용된 도구`

- Spring Boot
- Github
- EC2 Linux 2
- S3
- CodeDeploy
- Nginx
- Shell Script 
- Travis CI


<br>

## `3. Blue/Green 무중단 배포`

![3](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2Fby4d1E%2Fbtq3nJCj6b2%2FoNwktmk0VKIeMRkd9HfCR1%2Fimg.png)

- [Blue/Green 자동화 배포 정리](https://devlog-wjdrbs96.tistory.com/305)

<br>

### `사용된 도구`

- Spring Boot
- Github
- EC2 Linux 2 2대
- S3
- CodeDeploy(Blue/Green)
- Load-Balancer
- Auto-Scaling 
- Travis CI

<br>

## `4. 현재 위치 무중단 배포하기`

![4](https://user-images.githubusercontent.com/45676906/115248229-782cc900-a162-11eb-8e41-0ace35929b7c.png)

- [과정 정리1](https://devlog-wjdrbs96.tistory.com/306)
- [과정 정리2](https://devlog-wjdrbs96.tistory.com/303)

<br>

### `사용된 도구`

- Spring Boot
- Github
- EC2 Linux 2
- S3
- CodeDeploy(In-Place)
- Load-Balancer
- Travis CI

<br>

## `5. Docker로 무중단 배포`

![5](https://user-images.githubusercontent.com/45676906/116240690-13472380-a79f-11eb-92e5-af383f1693b3.png)

- [과정 정리1](https://github.com/wjdrbs96/Today-I-Learn/blob/master/AWS/Deploy/Docker%2C%20Nginx%EB%A1%9C%20%EB%AC%B4%EC%A4%91%EB%8B%A8%20%EB%B0%B0%ED%8F%AC%ED%95%98%EA%B8%B0-1.md)
- [과정 정리2](https://github.com/wjdrbs96/Today-I-Learn/blob/master/AWS/Deploy/Docker%2C%20Nginx%EB%A1%9C%20%EB%AC%B4%EC%A4%91%EB%8B%A8%20%EB%B0%B0%ED%8F%AC%ED%95%98%EA%B8%B0-2.md)

<br>

### `사용된 도구`

- Spring Boot
- Github
- EC2 Linux 2
- S3
- CodeDeploy(In-Place)
- Nginx, Docker
- Shell Script
- Travis CI