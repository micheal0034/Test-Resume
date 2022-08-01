FROM python:3.9

WORKDIR /resume-ranker

COPY . /resume-ranker/

RUN python3 -m pip install -r requirements.txt

ENTRYPOINT ["python"]
CMD ["app.py"]

ENV FLASK_APP=resume-ranker
ENV FLASK_ENV=development


