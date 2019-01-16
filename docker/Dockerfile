FROM ruby:2.5

MAINTAINER Juan Jesús Ojeda <juanje.ojeda@ual.es>

# Install Jekyll and bundler gems
RUN gem install jekyll bundler

# Set the path where is allocated the pgmlab website
RUN cd home

# Clone the repository of the template
RUN git clone https://github.com/altosaar/jaan.io.git

# Rename the repository folder  
RUN mv jaan.io pgmlab 

# Set the path where is allocated the pgmlab website
WORKDIR /home/pgmlab




