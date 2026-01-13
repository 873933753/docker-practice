FROM python:3.9.5-slim
WORKDIR /src
RUN pip install flask
ENV FLASK=app.py
COPY app.py .

CMD ["flask","run","-h","0.0.0.0"]

EXPOSE 5000
