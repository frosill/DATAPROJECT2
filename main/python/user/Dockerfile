FROM python:3.8.16-slim

WORKDIR /app

COPY user.py user.py
COPY requirements.txt requirements.txt
COPY data-project-2-376316-a19138ce1e45.json arctic-cursor-376010-87f1bcaf048d.json

RUN pip install -r requirements.txt

CMD [ "python", "-u", "user.py" ]