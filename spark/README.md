# Spark local 실행 docker-compose

## 실행 방법


1. Clone the repository:

```sh
git clone https://github.com/brickstudy/infra-docs.git
```

2. Run docker-compose

- spark 경로 접속!!

```sh
cd ./infra-docs/spark
```


- 경로에 docker-compsoe 파일 확인
- 해당 경로에서 아래 실행

```sh
docker-compose up -d
```

- docker 배포가 완료 된후 `localhost:8888` 경로 접속
    - (주의!!) jupyterlab에서 작업 work 폴더 내에서 작업해야 본인 로컬 컴퓨터에도 해당 파일이 저장됩니다!!
- spakr cluster 실행은 `localhost:8080` 경로에서 확인

### 참고사항

- 해당 spark docker 실행의 경우 별도의 설정없이 기본으로 구성되어 있어 특정 작업 시 오류가 발생할 수 있습니다.
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

