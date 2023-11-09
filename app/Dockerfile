FROM python:3.10
WORKDIR /app
COPY . /app
RUN pip install -r requirements.txt
EXPOSE 8050
CMD ["gunicorn", "--bind", "0.0.0.0:8050", "app:server"]
