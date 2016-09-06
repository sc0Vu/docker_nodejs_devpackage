FROM mhart/alpine-node:6.5

MAINTAINER Peter Lai <alk03073135@gmail.com>

# install some npm package
RUN npm install -g pm2 && \
    npm install -g mocha && \
    npm install -g webpack

# Set default work directory
WORKDIR /src

CMD ["true"]