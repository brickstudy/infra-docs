# Spark local 실행 docker-compose

## 실행 방법


1. Clone the repository:

```sh
git clone https://github.com/brickstudy/infra-docs.git
```

2. AWS configuration
spark, aws 인프라 간 연결을 위한 자격증명을 구성해야합니다.<br>
해당 구성 관련 파일은 1. spark/aws/credentials 2. spark/conf/spark-defaults.conf 파일입니다.<br>
해당 파일의 기본 템플릿이 .template posfix로 생성되어있습니다. 이를 복사하여 access key, secure key를 명시해줍니다.


3. Run docker-compose

- spark 경로 접속!!

```sh
cd ./infra-docs/spark
```


- 경로에 docker-compose.yaml 파일 확인
- 해당 경로에서 아래 실행

```sh
docker-compose up -d
```
- docker container instance 실행된 후 `localhost:8888` 인터페이스로 jupyter notebook 작업 가능

### 참고사항

- 오류가 발생할 경우 github 이슈에서 `Bug Template`을 활용하여 이슈를 공유해주시고 해결 진행해주시면 됩니다.



<br>


## Contributing

Contributions are welcome! If you would like to contribute to ArtCore-Go, please follow these steps:

1. Fork the repository.

2. Create a new branch:

```sh
git checkout -b my-feature
```


3. Make your changes and commit them:

```sh
git commit -m "Add my feature"
```

4. Push to your forked repository:

```sh
git push origin my-feature
```

5. Open a pull request. 

<br>

