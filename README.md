# FlyGo_Maven_Ali
文档地址：https://www.flygo520.com/docs/maven/maven-1an0r58biooso

修改工程中的 `pom.xml` 配置文件，填写你的私服地址。

```bash
<distributionManagement>
  <repository>
    <!-- 对应Maven setting.xml配置文件中 server 一一对应 -->
    <id>rdc-releases</id>
    <name>RDC Release Repository</name>
    <url>https://${你的阿里云私服地址}/</url>
  </repository>
  <snapshotRepository>
    <!-- 对应Maven setting.xml配置文件中 server 一一对应 -->
    <id>rdc-snapshots</id>
    <name>RDC snapshot Repository</name>
    <url>https://${你的阿里云私服地址}/</url>
    </snapshotRepository>
</distributionManagement>
