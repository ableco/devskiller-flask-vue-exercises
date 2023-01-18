FROM python:3

WORKDIR /app

COPY . .

RUN pip3 install -q -e .

CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0"]
