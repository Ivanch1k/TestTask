FROM python:3.6-alpine3.6
ENV PYTHONUNBUFFERED=1
WORKDIR /code
RUN ls
COPY backend /code/
RUN pip install -r requirements.txt
CMD ["python", "backend/manage.py", "runserver", "0.0.0.0:8000"]