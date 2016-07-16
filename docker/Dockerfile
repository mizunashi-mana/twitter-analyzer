FROM node:6-slim

ADD entrypoint.sh /sbin/entrypoint.sh
RUN chmod +x /sbin/entrypoint.sh

ENTRYPOINT ['/sbin/entrypoint.sh']
CMD ['app:start']
