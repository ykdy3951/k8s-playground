# Base image
FROM python:3.10

# Set working directory
WORKDIR /app

# Install dependencies
COPY requirements.txt ./requirements.txt
RUN pip install -r requirements.txt

# Copy source code
COPY ./main.py /app/

CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "8000"]