# 🏥 CRUD Hospital - Proyecto Java con MySQL y JSON

Este proyecto es una aplicación de consola en Java que simula la gestión de un hospital, permitiendo realizar operaciones CRUD (**Crear**, **Leer**, **Actualizar** y **Eliminar**) sobre entidades las entidades **Hospitales**, **Médicos** y **Pacientes**.

Lo he diseñado con una arquitectura modular basada en:
- ✅ POJO (entidades)
- ✅ DAO (Data Access Object)
- ✅ Uso de interfaces para el CRUD genérico y específico de cada entidad.
- ✅ Base de datos MySQL
- ✅ JSON con datos iniciales para insertar en la BD
- ✅ Registro de logs

## 🛠 Tecnologías Usadas

- 🧠 **Java 23**
- 📦 **Maven**
- 🛢️ **MySQL**
- 📄 **Gson (Google)** para manejo de JSON

  ## ⚙ Configuración y Ejecución
### ⚠️ IMPORTANTE: Verifica las credenciales en la clase conexionDB.java y ajustalas según tu configuración.
  Ejecuta el contenido del fichero hospital.sql en tu servidor MySQL para generar la base de datos y tablas.
  Ejecuta el Main.java para poner la aplicación en funcionamiento. 😁
  
  Al ejecutar el programa se insertarán algunos datos predeterminados en la base de datos, una vez ejecutado por primera vez asegurate de comentar las 2 lineas del Main.java que realizan esta función:
  
  ![image](https://github.com/user-attachments/assets/8e93609c-9422-43f3-8765-fb9db8c7c167)

