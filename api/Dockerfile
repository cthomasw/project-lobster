#the format for this is always ImageName : label
FROM ruby:2.6

#/usr/src/app is generally a good default
WORKDIR /usr/src/app

RUN gem install rack

#Copy anything needed as a prerequisite to run the application
COPY server.rb ./

CMD [ "ruby", "./server.rb" ]