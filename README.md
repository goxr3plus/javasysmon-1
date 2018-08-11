# JavaSysMon2 - New Edition with new Features

I see people forking this project and adding new features , but nobody is combining them in one . Guess what ?
I do it here so here we go , i am taking the features from all the following forks and combining them inside this repository.

**NEW**

1) [Fixed windows 32bit dll was incorrectly compiled as 64bit](https://github.com/jezhumble/javasysmon/issues/35)

> TODO
2) [The CPU usage of a process for a period of time](
https://github.com/lliuxiangke0210/javasysmon/commit/3aa4442fbcbc204ce533381d22745cfab45d7683)

3) [Kill linux process](https://github.com/wangzw/javasysmon/commit/44c78588d9f3e84e200c8ffc92b177f5280556e5)

4) [Returning free memory in Linux even with cached and buffer values](https://github.com/danielflower/javasysmon/commit/869bad136a30a88ec9812b6a50adaf41753a34a5)

# Using JitPack.io
https://jitpack.io/#goxr3plus/javasysmon2

**Maven**

``` XML
<repositories>
  <repository>
    <id>jitpack.io</id> 
    <url>https://jitpack.io</url>
  </repository>
</repositories>
```

``` XML
<dependency>
  <groupId>com.github.goxr3plus</groupId>
  <artifactId>javasysmon2</artifactId>
  <version>8.0.0</version>
</dependency>
```

**Gradle**

``` SCALA
allprojects {
   repositories {
      ... 
      maven { url 'https://jitpack.io' }
   }
 }
```

``` JAVA
dependencies {
   implementation 'com.github.goxr3plus:javasysmon2:8.0.0'
}
```



