FROM tomcat:7-jre8
ENV JAVA_OPTS=-Dlistening_address=${LISTEN_ADDRESS:-0.0.0.0}
RUN echo JAVA_OPTS
RUN echo $JAVA_OPTS
COPY server.xml /usr/local/tomcat/conf/
