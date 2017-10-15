FROM python:3

RUN mkdir /code
WORKDIR /code

# install python dependencies
ADD requirements.txt /code/
RUN pip install -r requirements.txt

# copy app code onto container
ADD . /code/

CMD ["python3", "manage.py", "runserver", "0.0.0.0:8000"]