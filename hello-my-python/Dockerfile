FROM python:latest
WORKDIR /service
COPY . .
RUN pip install --upgrade pip
RUN pip install -r requirements.txt
#COPY . .
EXPOSE 8080
ENTRYPOINT ["python3", "app.py","service"]
