FROM testcafe/testcafe

USER root

ENV NODE_PATH=/opt:/usr/lib/node_modules:/opt/testcafe/node_modules

RUN cd /opt/testcafe && npm install testcafe-reporter-html request totp-generator

USER root