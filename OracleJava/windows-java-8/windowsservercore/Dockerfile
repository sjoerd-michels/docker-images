FROM microsoft/windowsservercore:latest

ENV JAVA_PKG=server-jre-8u161-windows-x64.tar.gz \
    JAVA_HOME=C:\\jdk1.8.0_161

ADD $JAVA_PKG /

RUN setx /M PATH %PATH%;%JAVA_HOME%\bin
