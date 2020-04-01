FROM  eurolinux/eurolinux-7


LABEL maintainer="WZ <wz@euro-linux.com>"
LABEL org.label-schema.schema-version="1.0" \
 org.label-schema.name="EuroLinux 7" \
 org.label-schema.vendor="EuroLinux" \
 org.label-schema.url="https://euro-linux.com"


RUN    yum install -y  epel-release \  
    && yum install -y  python-pip \ 
    && yum clean all



CMD ["/usr/bin/python"]


