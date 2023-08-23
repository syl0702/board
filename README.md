- 프로젝트 생성/앱 생성
```bash
django-admin startproject <pjt-name>
django-admin startapp <app-name>
```

- 그 나머지
```bash
python manage.py <command>
```


## HTTP status code

- 200 : OK
- 30X : redirect
- 4XX : client error 사이트를 사용하려는 사용자의 잘못!
    - 401 : Unauthorized
    - 403 : forbidden
    - 404 : not found
- 500 : server error 코드 잘못
