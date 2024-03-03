# Clone git repository using ansible playbook
1. Write clone.yml file and run command
```   
ansible-playbook -u debian clone.yml
```
&nbsp;
![ansible playbook](https://github.com/dharmaraj257/3.0v/assets/100831265/778948b1-216f-4163-a35f-8f552faa12d0)

&nbsp;
2. Build docker image and run conatiainer 

```
docker build -t dharmaraj257/helloworld:v1 .
```
```
docker run -d -p 80:80 dharmaraj257/helloworld:v1
```
&nbsp;
![docker in linux](https://github.com/dharmaraj257/3.0v/assets/100831265/e4eca531-7315-421b-90d1-dea6ae6f57f2)
&nbsp;

Output:

![git docker run in linux](https://github.com/dharmaraj257/3.0v/assets/100831265/93f6e417-7bc0-4e4d-8892-1cae7413d823)

