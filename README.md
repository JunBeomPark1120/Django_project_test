# django

1. 프로젝트 생성

```bash
django-admin startproject <pjt name> .
```

2. 가상환경 설정
```bash
python -m venv venv
```

3. 가상환경 활성화
```bash
source venv/Scripts/activate
deactivate
```

4. 가상환경 내부에 django설치
```bash
pip install django
```

5. 서버 실행 확인(종료 : 'Ctrl + c')
```bash
python manage.py runserver
```

6. 앱 생성
```bash
django-admin startapp <appname>
```

7. 앱 등록
- 'settings.py'의 'INSTALLED_APPS'에 등록
    - 