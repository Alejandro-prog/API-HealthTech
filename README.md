
# API-HealthTech

![image](https://img.shields.io/github/downloads/TcNobo/TcNo-Acc-Switcher/total?color=%23AEEA7A&label=Django&logo=Django&logoColor=%23AEEA7A&style=for-the-badge)
![image](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![image](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![image](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)

Instalación de Python en Windows
Dirigirse a https://python.org
Ir a la sección de descargas
Descargar cualquier versión superior a 3.6.*
Instalación de Python en Linux
Correr:
add-apt-repository -y ppa:jonathonf/python-3.6
apt-get update -y
apt-get install -y python3.6
apt-get install -y python3.6-dev
apt-get install -y python3.6-distutils
ln -s /usr/bin/python3.6 /usr/local/bin/python3
wget https://bootstrap.pypa.io/get-pip.py -O /home/ubuntu/get-pip.py
python3.6 /home/ubuntu/get-pip.py
rm /home/ubuntu/get-pip.py
ln -s /usr/local/bin/pip /usr/local/bin/pip3
``

## Verificación de la descarga

1. Correr `python3 --version`
2. Correr `pip3 --version`

## Entorno virtual

1. Correr `python3 -m venv ENTORNO` donde `ENTORNO` sea el nombre deseado
2. Correr `source ENTORNO/bin/activate` para activar el entorno
3. Correr `deactivate` para desactivar el entorno

## Instalación de django

1. Activar entorno virtual
2. Correr `pip install django -U`

## Librerias

1. Intalar `pip install djangorestframework` 
2. Intalar `pip install Pillow`

## CONECTAR CON LA API

**horarioMedico**

GET 🎈
```
- http://127.0.0.1:8000/api/horarioMedico/
```

POST 📃
```
- http://127.0.0.1:8000/api/horarioMedico/

{
    "hora_inicio": "16:22:00",
    "hora_fin": "22:22:00"
} 
```
