FROM ruby:3.0.0

RUN apt-get update && apt-get install -y build-essential --no-install-recommends && apt-get clean && rm -rf /var/lib/apt/lists/*

WORKDIR /usr/src/app

ADD checker_example.rb .
ADD solution_example.rb .
ADD Makefile .
