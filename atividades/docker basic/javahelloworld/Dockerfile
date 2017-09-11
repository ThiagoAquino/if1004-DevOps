FROM java:8
COPY src /home/root/javahellorworld/src
WORKDIR /home/root/javahelloworld
RUN javac -d bin src/HelloWorld.java
ENTRYPOINT ["java","-cp","bin","HelloWorld"]
