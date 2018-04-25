FROM lucee/lucee4-nginx:latest
RUN set -x \
	&& apt-get update \
  && apt-get install --no-install-recommends --no-install-suggests -y gettext-base 

# Set Tomcat config to load Lucee
COPY server.xml /usr/local/tomcat/conf/server.xml
