FROM python:3.6-alpine3.6
ENV PYTHONUNBUFFERED=1
COPY ./backend/ /code/
WORKDIR /code/
RUN pip install -r requirements.txt
CMD ["python", "backend/manage.py", "runserver", "0.0.0.0:8000"]