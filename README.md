
# API-HealthTech

![image](https://img.shields.io/github/downloads/TcNobo/TcNo-Acc-Switcher/total?color=%23AEEA7A&label=Django&logo=Django&logoColor=%23AEEA7A&style=for-the-badge)
![image](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![image](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![image](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)

## CONECTAR CON LA API
** HealthTech **

 **API horarioMedico**

 POST horarioMedicoPOST
 ```
https://healt-tech-back.herokuapp.com/api/horarioMedico/
 ```

Body raw (json)
 ```
{
  "hora_inicio": "16:22:00",
  "hora_fin": "22:22:00"
}
 ```

PUT horarioMedicoPUT
 ```
https://healt-tech-back.herokuapp.com/api/horarioMedico/<id>/
 ```


 POST horarioMedicoPOST
 ```
https://healt-tech-back.herokuapp.com/api/horarioMedico/
 ```

Bodyraw (json)
 ```
{
  "hora_inicio": "23:22:00",
  "hora_fin": "11:22:00"
}
 ```

DEL horarioMedicoDELETE
 ```
https://healt-tech-back.herokuapp.com/api/horarioMedico/<id>/
 ```
 -----------------------------------------------------
 **API medico**

 POST medico
 ```
https://healt-tech-back.herokuapp.com/api/medico/
 ```

Body raw (json)
 ```
{
       "tipo_documento": "cc",
        "numero_documento": "10234757",
        "nombre_usuario": "Fabian Gonzales XD",
        "contrasena": "990518",
        "correo": "amata@gmail.com",
        "telefono": "20928937",
        "sexo": "M",
        "fecha_nacimiento": "2021-10-06",
        "grupo_sanguineo": "+O",
        "estrato": 3,
        "estado_civil": "soltero",
        "id_perfil": 3,
        "id_agenda": 5,
        "id_especialidad": 2
}
 ```

PUT medico PUT
 ```
https://healt-tech-back.herokuapp.com/api/medico/<id>/
 ```
 ```
 {
         "tipo_documento": "CC",
         "numero_documento": "1013688458",
         "nombre_usuario": "Maruan Enrique:)",
         "contrasena": "12345",
         "correo": "maruan02@gmail.com",
         "telefono": "3015012832",
         "sexo": "M",
         "fecha_nacimiento": "1999-10-28",
         "grupo_sanguineo": "O+",
         "estrato": 2,
         "estado_civil": "Soltero",
         "id_perfil": 1,
         "id_agenda": 1,
         "id_especialidad": 1
 }
 ```

 POST horarioMedicoPOST
 ```
https://healt-tech-back.herokuapp.com/api/medico/
 ```

Bodyraw (json)
 ```
{
        " tipo_documento": "cc",
        "numero_documento": "10234757",
        "nombre_usuario": "Fabian Gonzales XD",
        "contrasena": "990518",
        "correo": "amata@gmail.com",
        "telefono": "20928937",
        "sexo": "M",
        "fecha_nacimiento": "2021-10-06",
        "grupo_sanguineo": "+O",
        "estrato": 3,
        "estado_civil": "soltero",
        "id_perfil": 3,
        "id_agenda": 5,
        "id_especialidad": 2
}
 ```

DEL medicoDELETE
 ```
https://healt-tech-back.herokuapp.com/api/medico/<id>/
 ```
 
 -----------------------------------------------------
**API Consultorios**
 Metodo GET 🎈 --> Consultar
 ```
  /api/medico/
 ```
 Metodo POST 📃 --> Crear
 ```
  {
        "codigo": "1155",
        "estado": "Activo",
        "id_consultorio": 99,
        "nombre": "eget",
        "piso": 50
},
  ```

 Metodo  PUT    --> Actualizar

 Metodo DELETE  --> Eliminar

 -----------------------------------------------------
**API especialidad**
 Metodo GET 🎈 --> Consultar
 ```
  /api/medico/
 ```
 Metodo POST 📃 --> Crear
 ```
{
        "descripcion": "Medicina Interna",
        "estado": "Activa",
        "id_especialidad": 8,
        "name": "Medicina Interna"
    }


  ```
Metodo DELETE  --> Eliminar

Metodo  PUT    --> Actualizar
