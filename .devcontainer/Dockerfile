FROM sapmachine:21

# Install Node.js 22
RUN apt-get update
RUN apt-get install -y curl
RUN curl -fsSL https://deb.nodesource.com/setup_22.x | bash
RUN apt-get install -y nodejs

# Install git
RUN apt-get install -y git

# Install maven
RUN apt-get install maven -y

WORKDIR /app
