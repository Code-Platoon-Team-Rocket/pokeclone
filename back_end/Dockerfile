From python:3.11-slim

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

WORKDIR /app

COPY requirements.txt .

COPY . . 

EXPOSE 8000

CMD ["gunicoorn", "pokeclone_proj.wsgi:application", "--bind", "0.0.0.0:8000"]

