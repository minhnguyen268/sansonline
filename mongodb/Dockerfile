FROM mongo:4.4.6
RUN echo "password" > /keyfile \
    && chmod 600 /keyfile \
    && chown 999 /keyfile \
    && chgrp 999 /keyfile
CMD ["--bind_ip_all", "--keyFile", "/keyfile", "--replSet", "rs0", "--port", "27017"]


# mongo -u admin -p nv6eJUZ7tuC7DCeq
# rs.secondaryOk()
# rs.initiate()
