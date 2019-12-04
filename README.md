# Kubernetes---EFK-hq-pv

/ceph-es
	pv 后端连接cephfs存储
	pvc 动态申请pv
	secret 

/es
  	es-endpoint.yaml  本地Endpointd
	es-ingress.yaml   部署elaticsearch
	es-job.yaml	  定时删除pod

/fluentd
	收集日志config文件

/hq
	hq面板控件yaml文件

/kibana
	kibana控制面板yaml文件

