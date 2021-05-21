FROM arm64v8/centos:latest
MAINTAINER James Turnbull "james@example.com"
ENV REFRESHED_AT 2016-06-01
RUN yum -y install ruby rubygems rubygem-rake
COPY . . 
RUN gem install --no-rdoc --no-ri rspec ci_reporter_rspec
