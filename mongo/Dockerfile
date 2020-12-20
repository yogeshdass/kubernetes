FROM python:3.7-alpine
WORKDIR /build
COPY . .
RUN cd simplifi-devicemanagement && \
    pip instal requests boto3 && \
    pip install -r requirements.txt
EXPOSE 5000
CMD ["flask", "run"]