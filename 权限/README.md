# K8s 中身份与权限

Kubernetes 集群可以同时管理大量互不相关的工作负载，而组织通常会选择将不同团队创建的项目部署到共享集群上。随着数量的增加，部署对象常常很快就会变得难以管理，拖慢操作响应速度，并且会增加危险错误出现的概率。Kubernetes 中提供了良好的多租户认证管理机制，如 RBAC、ServiceAccount 还有各种 Policy 等。
