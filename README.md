# Домашнее задание к занятию «GitLab» - `Уляшев Дмитрий`




### Задание 1


![alt text](https://github.com/slav1power/8-03/blob/main/jop.png)


---

### Задание 2

1) Готовый gitlab-ci.yml:

tages:          
  - test


test_go:
    stage: test
    image: golang:1.17
    script:
        - go test

2) Скриншот с готовыми билдами

![alt text](https://github.com/slav1power/8-03/blob/main/job2.png)

