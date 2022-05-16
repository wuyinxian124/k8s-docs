1. 概要
k8s 系统扩展包括几个部分：

内部组件API Server支持基于Webhook的认证、授权和准入控制扩展、CRD、自定义控制器，甚至是自定义的API Server
kubelet支持的CNI、CRI、CSI和Device Plugins
调度器基于调度框架支持的调度插件扩展等
Service Catalog，以及自定义控制器和Operator等
2. 扩展详情
2.1. webhook


2.2. CRD


2.3. api server


2.4. controller


2.5. operator


2.6. Service Catalog


2.7. 调度策略扩展


3. 参考
扩展 Kubernetes https://kubernetes.io/zh/docs/concepts/extend-kubernetes/
