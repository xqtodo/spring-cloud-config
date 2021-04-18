# SpringCloud-Config配置中心

> **测试上传config配置文件**

1、配置文件内容

```yaml
config:
  info: main branch,spring-cloud-config/config-dev.yaml version=1
```

2、读取规则

`/{label}/{application}-{profile}.yaml`

> 例如：http://config-3344.com:3344/main/config-dev.yaml
