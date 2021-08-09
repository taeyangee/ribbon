# spc-ribbon 官网

# vs 原生ribbon的依赖关系

```text
|    \--- org.springframework.cloud:spring-cloud-starter-netflix-ribbon:2.2.5.RELEASE
|         +--- org.springframework.cloud:spring-cloud-starter:2.2.5.RELEASE
|         |    +--- org.springframework.boot:spring-boot-starter:2.3.2.RELEASE (*)
|         |    +--- org.springframework.cloud:spring-cloud-context:2.2.5.RELEASE (*)
|         |    +--- org.springframework.cloud:spring-cloud-commons:2.2.5.RELEASE (*)
|         |    \--- org.springframework.security:spring-security-rsa:1.0.9.RELEASE
|         |         \--- org.bouncycastle:bcpkix-jdk15on:1.64
|         |              \--- org.bouncycastle:bcprov-jdk15on:1.64
|         +--- org.springframework.cloud:spring-cloud-netflix-ribbon:2.2.5.RELEASE
|         |    \--- org.springframework.cloud:spring-cloud-netflix-archaius:2.2.5.RELEASE
|         +--- org.springframework.cloud:spring-cloud-starter-netflix-archaius:2.2.5.RELEASE
|         |    +--- org.springframework.cloud:spring-cloud-starter:2.2.5.RELEASE (*)
|         |    +--- org.springframework.cloud:spring-cloud-netflix-ribbon:2.2.5.RELEASE (*)
|         |    +--- org.springframework.cloud:spring-cloud-netflix-archaius:2.2.5.RELEASE
|         |    +--- com.netflix.archaius:archaius-core:0.7.6
|         |    \--- commons-configuration:commons-configuration:1.8
|         |         \--- commons-lang:commons-lang:2.6
|         +--- com.netflix.ribbon:ribbon:2.3.0
|         +--- com.netflix.ribbon:ribbon-core:2.3.0
|         +--- com.netflix.ribbon:ribbon-httpclient:2.3.0
|         +--- com.netflix.ribbon:ribbon-loadbalancer:2.3.0
```

# spc-ribbon整合ribbon之后新的玩法
- 配置方式
- rest+ ribbon
- feign + ribbon

# spc-ribbon增强、实现了哪些接口
