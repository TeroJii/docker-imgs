FROM ubuntu:jammy

# an environment variable for setting the timezone
ENV TZ=Europe/Helsinki
# set the timezone
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

#install R
RUN apt-get update && apt-get install -y r-base

CMD ["R"]