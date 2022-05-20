# k8s-ingress-nginx
k8s的ingress-nginx的yaml，可以直接使用kubectl apply -f 安装
## 使用
```bash
kubectl apply -f 
```
## 其他
因ingress-nginx的镜像是在gcr上的，国内无法拉取，这里采用好心人做得国内镜像拉取的
好心人的仓库地址：https://github.com/anjia0532/gcr.io_mirror
参考这个进行配置：https://blog.csdn.net/weixin_43988498/article/details/122792536
