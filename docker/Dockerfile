FROM python:3.12
EXPOSE 8000
WORKDIR /usr/src/app
RUN apt-get update && apt-get install -y netcat-openbsd
COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt
COPY . .