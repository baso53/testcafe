FROM testcafe/testcafe
USER root

RUN  npm install -g testcafe-reporter-html request totp-generator --save-dev
EXPOSE 1337 1338
ENTRYPOINT ["/opt/testcafe/docker/testcafe-docker.sh"]
