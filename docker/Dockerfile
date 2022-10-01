# Base container image
FROM python:3.10.7

# Install the following packages
RUN apt-get update && apt-get install -y git curl wget

WORKDIR /workdir

RUN git clone https://github.com/kennethleungty/Educative-Advanced-Pandas.git /workdir

RUN pip install -r requirements.txt