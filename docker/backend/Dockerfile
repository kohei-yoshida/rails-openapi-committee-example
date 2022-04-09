FROM ruby:3.1.0

ENV LANG C.UTF-8
RUN curl https://dl.yarnpkg.com/debian/pubkey.gpg | apt-key add -
RUN echo "deb https://dl.yarnpkg.com/debian/ stable main" | tee /etc/apt/sources.list.d/yarn.list
RUN set -x && apt upgrade && apt update && apt install -y build-essential cmake mariadb-client nodejs yarn
RUN gem update --system && gem install --no-document bundler:2.3.3
