### Задача 1

#### 1.1

https://github.com/a148ru/shvirtd-example-python

#### 1.2

```docker
FROM python:3.9-slim
WORKDIR /app
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY . .
CMD ["python3","main.py"]
EXPOSE 5000
```

![alt text](image-1.png)
![alt text](image-2.png)

#### 1.3*

#### 1.4*

### Задача 2*

[vulnerabilities.csv](vulnerabilities.csv)


### Задача 3

#### 1.[1-2]

![alt text](image.png)
![alt text](image-3.png)

#### 1.[3-4]

![img](image-4.png)


### Задача 4
main.py
![alt text](image-5.png)

not_tested_main.py
![alt text](image-6.png)

### Задача 5*


### Задача 6

#### 6
![img](image-7.png)
![alt text](image-8.png)
копировать не стал,оно у меня уже есть:
```bash
$ whereis terraform 
terraform: /usr/local/bin/terraform
$ terraform -v
Terraform v1.9.8
on linux_amd64
$ 
```
#### 6.1
![alt text](image-9.png)


#### 6.2**

### Задача 7***