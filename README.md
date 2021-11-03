# GitOps-Manifest
Manifest files for implementing GitOps

## 이슈
### PostgreSQL
- 만약 PV 마운트해서 사용할 경우 1001 -> 0으로 전부 권한 root로 바꿔줘야함. 안그러면 mkdir 하는데 권한 문제 발생함
  - 이러면 로그인을 못하는데, 이러면 bitnami로 wrapping된 거 사용하지 말고 공식 postgres사용하는게 좋을 듯 함.
