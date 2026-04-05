Sistema de Gestión de Contactos 📱
Este proyecto es una aplicación de consola desarrollada en Python que permite organizar y administrar información personal de clientes de manera eficiente. Fue creado como parte de la evaluación del Módulo 3 (ABP) del Bootcamp de Análisis de Datos.

📝 Descripción
El sistema funciona como una agenda interactiva donde el usuario puede realizar operaciones CRUD (Crear, Leer, Actualizar y Borrar) sobre una base de datos de contactos almacenada en memoria. El proyecto pone en práctica conceptos fundamentales de Programación Orientada a Objetos (POO) y manejo de estructuras de datos dinámicas.

🚀 Funcionalidades
El sistema ofrece un menú interactivo con las siguientes opciones:

- Registrar Contactos: Permite ingresar nombre, teléfono, email y dirección.
- Listar Contactos: Muestra de forma organizada todos los registros actuales.
- Buscar Contactos: Búsqueda insensible a mayúsculas/minúsculas por nombre.
- Editar Contactos: Permite actualizar campos específicos (teléfono, email o dirección) sin afectar el resto de la información.
- Eliminar Contactos: Borra registros de la agenda de forma definitiva.

🛠️ Tecnologías Utilizadas
- Lenguaje: Python 3.x
- Entorno: Google Colab / Jupyter Notebook
- Estructuras de Datos: Listas y Diccionarios.
- Paradigma: Programación Orientada a Objetos (Clases, Métodos, Encapsulamiento básico).

🏗️ Estructura del Código
El desarrollo se divide en tres pilares lógicos:

- Clase Contacto: Define la "plantilla" de cada cliente. Incluye un método para convertir los datos a diccionario y una representación en cadena (__str__) personalizada con formato de tuberías (|) para mejorar la legibilidad.
- Clase Agenda: Actúa como el controlador del sistema. Maneja una lista de contactos y contiene la lógica para agregar, buscar, filtrar y remover elementos.
- Función menu(): Implementa un bucle while infinito que gestiona la interacción con el usuario, validando las entradas y comunicándose con la clase Agenda.

💻 Instrucciones de Uso
- Abre el archivo .ipynb en Google Colab o cualquier entorno compatible con Jupyter.
- Ejecuta las celdas de definición de clases (Contacto y Agenda).
- Ejecuta la celda del Menú Interactivo.
- Sigue las instrucciones en pantalla ingresando los números del 1 al 6 según la acción que desees realizar.

Autor: Francisco Javier Vergara Correa
Bootcamp: Análisis de Datos
