
FROM python:3.10-slim

WORKDIR /app
COPY . .
RUN pip install --no-cache-dir -r requirements.txt

CMD ["uvicorn", "sensores:app", "--host", "0.0.0.0", "--port", "8000"]

