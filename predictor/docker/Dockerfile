# predictor/Dockerfile
FROM python:3.11

# Set working directory
WORKDIR /app

# Copy application files
COPY . .

# Install dependencies
RUN pip install -r requirements.txt

# Expose port
EXPOSE 3085

CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "3085"]
