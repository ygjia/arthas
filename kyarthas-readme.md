## Release Note For kyarthas

#### 发版
./mvnw clean deploy -DskipTests -P dev -P full

### 3.6.7-kyarthas-r3
修复 `/tmp` 目录有 noexec 属性时，arthas 无法打火焰图，无法使用`vmtool`命令的问题(KE-39770)

### 3.6.7-kyarthas-r2
解决安全漏洞问题(KE-40431)

### 3.6.7-kyarthas-r1
升级到arthas 3.6.7版本, 解决安全漏洞问题(KE-40331)

### 3.6.3-kyarthas-r2
修复自定义配置不生效的问题
KE-37696 fix arthasConfigMap params missing

### 3.6.3-kyarthas-r1
修复和KE中Ehcache的classloader冲突问题。
KE-37696 fix libattach.so classloader
