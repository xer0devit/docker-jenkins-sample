FROM arm64v8/debian:jessie
MAINTAINER James Turnbull "james@example.com"
ENV REFRESHED_AT 2016-06-01
RUN apt-get update
RUN apt-get -y install ruby rake
COPY . . 
RUN gem install --no-rdoc --no-ri rspec ci_reporter_rspec
