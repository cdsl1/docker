FROM tutum/mysql:5.6

RUN cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime

ADD run.sh /run.sh
RUN chmod 755 /run.sh
CMD ["/run.sh"]