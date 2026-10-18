FROM python:3.13-slim

# print() 출력이 docker logs 에 바로 보이도록 (stdout 버퍼링 해제)
ENV PYTHONUNBUFFERED=1

WORKDIR /app

COPY . .

RUN pip install --no-cache-dir flask==3.1.3

EXPOSE 5000

CMD ["python", "app.py"]
