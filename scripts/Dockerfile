FROM python:3.7
ENV TimeZone=Asia/Shanghai
RUN ln -snf /usr/share/zoneinfo/$TimeZone /etc/localtime && echo $TimeZone > /etc/timezone
WORKDIR /app
CMD ["bash", "./scripts/run.sh"]