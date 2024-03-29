---
title: Onboarding
weight: 1
---

-   Install
    -   Docker & Rancher:  [FE - How to use Docker without Docker Desktop](https://wiki.navercorp.com/display/NVN/FE+-+How+to+use+Docker+without+Docker+Desktop)

-   Server (ncloud)
    -   `ssh vuhakeio@dgw01.nhnsystem.com / ssh vuhakeio@gateway`
        -   `kinit`  (password: **Naver122530**)
        -   `ssh irteam@dev-cvkeio01-ncl`
    -   Centos/Fedora OS
        ```
        cat /etc/os-release
        sudo dnf list installed | grep mysql
        
        sudo dnf install java-1.8.0-openjdk
        # Switch Java version
            sudo alternatives --config java
            
        sudo dnf install maven
        ```

- JDK
  https://jdk.java.net/archive/
  https://repo.nhnsystem.com/webapps/application/jdk/
  https://adoptium.net/

- Request Yubikey
  https://wiki.navercorp.com/display/NVN/Guide_Submit+a+general+request+to+IT+Support

https://apms.navercorp.com/
-> View custom format

https://apms.navercorp.com/aprvDoc/view/AP24037674174
TeamLeader: YOON YOUNGJUN