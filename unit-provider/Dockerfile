FROM swr.cn-east-3.myhuaweicloud.com/op_svc_cse/openjdk-x86_64:8-1.2.0
WORKDIR /home/app/
ADD unit-provider/target/unit-provider-4.0.0.jar .
ENTRYPOINT ["java","-jar","-Xmx2048m","./unit-provider-4.0.0.jar"]
