FROM gibdfrcu/storm:alpine_jdk1.8.112_1.0.2



MAINTAINER Ramiro Rivera <ramarivera@gmail.com>


EXPOSE 6700
EXPOSE 6701
EXPOSE 6702
EXPOSE 6703
EXPOSE 8000


RUN /usr/bin/config-supervisord.sh supervisor && \
	/usr/bin/config-supervisord.sh logviewer


CMD /usr/bin/start-supervisor.sh




