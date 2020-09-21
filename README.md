# Simple-Pipeline-Google-Cloud-Composer (Airflow)

Use cloud composer to create simple pipeline

[t1, t2] >> t3 >> t4

t1 = get online retail data from db

t2 = get gbp to thb rate using API

t3 = join data then convert currency and save result to cloud storage

t4 = load result to big query
