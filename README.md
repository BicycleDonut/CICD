Создал файл с тестовой job в локальном репозитории. Создал новый проект и в нем файл с еще одной тестовой job.
remote.smoke.gitlab-ci.yml
remote-smoke-test:
   script:
    -echo "REMOTE SMOKE"
Указал в pipeline первого проекта include.
![](pipeline.png)

Результат локальной тестовой job.
![](result1.png)

Результат удаленной тестовой job.
![](result2.png)