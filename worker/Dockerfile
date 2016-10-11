FROM bkkdocker.htqk.ly:5000/python:2-alpine
RUN pip install redis
RUN pip install requests
COPY worker.py /
CMD ["python", "worker.py"]
