# Teste de Programação Jurid

- O objetivo do teste é criar um aplicativo (APP) com Django que integre o armazenamento do Django com o AWS S3.

### Funcionalidades

- Foi criado um aplicativo chamado "Album de Foto" que permite o registro de usuários para login.
- É possível fazer o upload de imagens e criar categorias para uma melhor organização, tanto no frontend quanto no backend.

## 🚀 Tecnologias Utilizadas

Aqui estão as tecnologias usadas neste projeto:

- Django versão 4.0.3
- Python 3.10 x64

## 📋 Serviços Utilizados

- GitHub
- Amazon S3

## 🔧 Pacotes Python

- asgiref==3.5.0
- boto3==1.21.37
- botocore==1.24.37
- Django==4.0.3
- django-storages==1.12.3
- jmespath==1.0.0
- Pillow==9.1.0
- python-dateutil==2.8.2
- s3transfer==0.5.2
- six==1.16.0
- sqlparse==0.4.2
- tzdata==2022.1
- urllib3==1.26.9

## ⚙️ Como Começar

Siga estas etapas para iniciar o projeto:

1. Crie um ambiente virtual: `$ python -m venv venv`
2. Ative o ambiente virtual (Windows): `$ .\venv\Scripts\Activate.bat`
3. Inicie um novo projeto Django: `$ django-admin startproject photoshare`
4. Crie um novo aplicativo: `$ python manage.py startapp fotos`
5. Instale as dependências necessárias: 
`$ pip install boto3`
`$ pip install django pillow`
`$ pip install django-storages`
6. Crie um super usuário: `$ python manage.py createsuperuser`
7. Colete os arquivos estáticos: `$ python manage.py collectstatic`
8. Execute o projeto: `$ python manage.py runserver`

## 🖇️ Funcionalidades

- Integração do Django com o AWS S3

## 📄 Links

- Repositório: [https://github.com/itagabriel/app_photo_album_django_s3](https://github.com/itagabriel/app_photo_album_django_s3)

## Versionamento

Versão: 1.0.0.0

## 🎁 Referências

- [Tutorial em vídeo](https://www.youtube.com/watch?v=sSquD2u5Ie0)

## 🎁 Autor

- **Gabriel Ita**: [@itagabriel](https://github.com/itagabriel)
