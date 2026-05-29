FROM python:3.11-slim

WORKDIR /app

RUN pip install pandas numpy matplotlib seaborn scikit-learn

COPY . .

CMD ["python", "--version"]