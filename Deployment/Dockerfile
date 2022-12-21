FROM --platform=linux/x86_64 python:3.10.7
MAINTAINER Priyankan Kiru "pkirupaharan@uri.edu"
COPY . /app
WORKDIR /app
# RUN python -m pip install --upgrade pip
RUN pip install tensorflow==2.10.0
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["emojiflask.py"]