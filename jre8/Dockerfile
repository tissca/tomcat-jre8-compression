FROM tomcat:7-jre8
ENV JAVA_OPTS=-Dlistening_address=${LISTEN_ADDRESS:-0.0.0.0}
RUN ECHO JAVA_OPTS
RUN ECHO $JAVA_OPTS
COPY server.xml /usr/local/tomcat/conf/
