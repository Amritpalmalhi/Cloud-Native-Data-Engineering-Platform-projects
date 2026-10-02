FROM apache/airflow:2.8.0

WORKDIR /opt/airflow/

COPY requirements.txt .

# pip install to install requirement.txt file that stores sensitive and relevant informations
RUN pip3 install --no-cache-dir -r requirements.txt
