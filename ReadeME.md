Possible Airflow error on Mac

Same issue here. I have solved by downgrading the version of airflow I was trying to install:

'''pip install "apache-airflow[celery]==2.6.1" --constraint "https://raw.githubusercontent.com/apache/airflow/constraints-2.6.1/constraints-3.7.txt" '''

https://stackoverflow.com/questions/76881884/error-in-airflow-installation-failed-at-building-wheel-for-google-re2-greenle
