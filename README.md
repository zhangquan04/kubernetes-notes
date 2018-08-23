## kubernetes-notes
> Kubernetes 学习笔记

## Summary
* [Introduction](README.md)

* [安装与配置]()
    * [使用kubespray安装kubernetes](setup/install-k8s-by-kubespray.md)
    * [使用minikube安装kubernetes](setup/install-k8s-by-minikube.md)
* [基本概念]()
    * [kubernetes架构]()
        * [Kubernetes总架构图](concepts/architecture/kubernetes-architecture.md)
        * [基于Docker及Kubernetes技术构建容器云（PaaS）平台概述](concepts/architecture/paas-based-on-docker-and-kubernetes.md)
    * [kubernetes对象]()
        * [理解kubernetes对象](concepts/object/understanding-kubernetes-objects.md)
        * [kubernetes常用对象说明](concepts/object/kubernetes-basic-concepts.md)
        * [Pod详解](concepts/object/kubernetes-pod-introduction.md)
* [核心原理]()
    * [Api Server](principle/kubernetes-core-principle-api-server.md)
    * [Controller Manager](principle/kubernetes-core-principle-controller-manager.md)
    * [Scheduler](principle/kubernetes-core-principle-scheduler.md)
    * [Kubelet](principle/kubernetes-core-principle-kubelet.md)
* [运维指南]()
    * [kubernetes集群问题排查](operation/kubernetes-troubleshooting.md)
    * [指定Node调度与隔离](operation/nodeselector-and-taint.md)
* [监控体系]()
    * [监控体系介绍](monitor/kubernetes-cluster-monitoring.md)
    * [cAdvisor介绍](monitor/cadvisor-introduction.md)
    * [Heapster介绍](monitor/heapster-introduction.md)
    * [Influxdb介绍](monitor/influxdb-introduction.md)
  