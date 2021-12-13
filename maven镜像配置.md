```xml
<?xml version="1.0" encoding="UTF-8"?>
<settings xmlns="http://maven.apache.org/SETTINGS/1.0.0"
          xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
          xsi:schemaLocation="http://maven.apache.org/SETTINGS/1.0.0 http://maven.apache.org/xsd/settings-1.0.0.xsd">

<!-- 本地仓库的路径 设置的是D盘maven/repo目录下 (自行配置一个文件夹即可，默认是 ~/.m2/repository) -->
<localRepository>D:\maven\repo</localRepository>  
 
<!-- 配置阿里云镜像服务器-->
<mirrors> 
  <mirror>    
      <id>alimaven</id>    
      <name>aliyun maven</name>    
      <url>http://maven.aliyun.com/nexus/content/groups/public/</url>    
      <mirrorOf>central</mirrorOf>            
  </mirror>
</mirrors> 
  
</settings>
```

