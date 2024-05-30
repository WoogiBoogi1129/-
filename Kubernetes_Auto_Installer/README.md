# Kubernetes Cluster 자동 구축기
- 가끔 Kubernetes 실습하다가 하기 싫을 때가 있습니다. 매번 밀어버리고 다시 설치하는 것도 일이라고 생각해서 만들었습니다.
- Version: 1.29v
- Cluster: Kubeadm
## 사용방법
- git으로 파일을 가져오거나, sh파일 코드를 복사 붙여넣기 해서 sh파일 생성
```sh
git clone [url]

# 또는 그대로 복사해서 Local에 sh파일로 생성해도 됨.
vi [file name].sh
## 이후 코드 복사해서 저장
```

- sh파일 권한 부여
```sh
chmod +x kubernetes_auto_installer.sh
```

- sh 파일 실행
```sh
sudo ./kubernetes_auto_installer.sh
```
