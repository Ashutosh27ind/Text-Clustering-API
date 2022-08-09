FROM continuumio/anaconda3:4.4.0

MAINTAINER Ashutosh, ashutoshind2017@outlook.com

COPY ./flask_demo /usr/local/python/

EXPOSE 8180

WORKDIR /usr/local/python/
RUN pip install -r requirements.txt

CMD python flask_predict_api.py