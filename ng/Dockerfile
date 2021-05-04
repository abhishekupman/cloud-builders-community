FROM node:12

ARG ng_version=latest
RUN npm install -g @angular/cli@$ng_version --unsafe-perms && \
    ng version
RUN npm install -g @ionic/cli

ENTRYPOINT ["ng"]
