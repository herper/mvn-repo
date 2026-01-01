# mvn-repo

## English Version

### Introduction
#### Thanks to Mr. Cai, the developer of the SpringReport project, for his open source contributions. The SpringReport project address is: https://github.com/SpringReport/SpringReport.

### 1. Project Introduction
This project is a Maven repository for the open source SpringReport project, used to store SpringReport's dependencies.

The purpose of this project is to facilitate use by other projects and prevent dependency package download failures caused by network issues.

The project code is hosted on GitHub at: https://github.com/SpringReport/mvn-repo

The project's Maven repository address is: https://raw.githubusercontent.com/SpringReport/mvn-repo/master/repo

### 2. Java Dependency Packages
This repository contains some Java dependency packages that cannot be downloaded from Maven Central Repository.

#### Dependency Packages for SpringReport Project

**Packages List:**
- SpringReport/com/dm/DmJdbcDriver
- SpringReport/com/kingbase8
- SpringReport/com/microsoft/sqlserver/sqljdbc4
- SpringReport/com/springreport/excel2pdf

### 3. Usage Instructions

#### Maven Configuration
Add the following repository configuration to your `pom.xml` file:

```xml
<repositories>
    <repository>
        <id>springreport-mvn-repo</id>
        <url>https://raw.githubusercontent.com/SpringReport/mvn-repo/master/repo</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
</repositories>
```

#### Gradle Configuration
Add the following repository configuration to your `build.gradle` file:

```groovy
repositories {
    maven {
        url 'https://raw.githubusercontent.com/SpringReport/mvn-repo/master/repo'
    }
}
```

---

## 中文版本

### 项目介绍
#### 感谢SpringReport项目的开发者蔡老师的开源贡献，SpringReport项目地址为：https://github.com/SpringReport/SpringReport。

### 1. 项目介绍
该项目是开源项目SpringReport的Maven仓库，用于存储SpringReport项目的依赖包。

该项目的目的是为了方便其他项目使用，避免因为网络问题导致的依赖包下载失败。

该项目的代码托管在GitHub上，项目地址为：https://github.com/SpringReport/mvn-repo

该项目的Maven仓库地址为：https://raw.githubusercontent.com/SpringReport/mvn-repo/master/repo

### 2. Java依赖包
该仓库包含一些无法从Maven中央仓库下载的Java依赖包。

#### SpringReport项目的依赖包

**依赖包列表：**
- SpringReport/com/dm/DmJdbcDriver
- SpringReport/com/kingbase8
- SpringReport/com/microsoft/sqlserver/sqljdbc4
- SpringReport/com/springreport/excel2pdf

### 3. 使用说明

#### Maven配置
在你的 `pom.xml` 文件中添加以下仓库配置：

```xml
<repositories>
    <repository>
        <id>springreport-mvn-repo</id>
        <url>https://raw.githubusercontent.com/SpringReport/mvn-repo/master/repo</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
</repositories>
```

#### Gradle配置
在你的 `build.gradle` 文件中添加以下仓库配置：

```groovy
repositories {
    maven {
        url 'https://raw.githubusercontent.com/SpringReport/mvn-repo/master/repo'
    }
}
```

---

**Project Maintainer**: SpringReport Team  
**Last Updated**: 2026-01-01

