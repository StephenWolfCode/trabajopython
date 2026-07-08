# Sistema de Gestion de Veterinaria

Trabajo Final Integrador - Laboratorio de Python  
Algoritmos y Estructuras de Datos - ISI - Ciclo 2026

## Integrantes del grupo

- Collazo, raúl
- Echavarria, Ithan Xavier
- Ledesma, Adán Ruben
- Silva, Eleazar Isaías
- Viera, Tomás

## Comision

Comision K1.2

## Descripcion general del sistema

Sistema de gestion para una veterinaria que permite:

- **Registro de animales**: Alta, baja y listado de mascotas con datos del propietario y del animal.
- **Agendar turnos**: Asignacion de turnos a mascotas registradas con fecha y hora.
- **Consulta de atencion medica**: Visualizacion del historial clinico y atenciones de cada mascota.
- **Control de servicios realizados**: Gestion de atencion de turnos pendientes con registro de servicios (consulta general, vacunacion, cirugia).
- **Estadisticas**: Visualizacion de servicios mas solicitados y total recaudado por servicio.

## Requisitos

- Python 3.8 o superior

## Instrucciones de ejecucion

1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/StephenWolfCode/trabajopython.git]
   cd [trabajopython]
   ```

2. Instalar dependencias (opcional, solo para los banners con figlet):
   ```bash
   pip install -r requirements.txt
   ```

3. Ejecutar el programa:
   ```bash
   python main.py
   ```

4. Seguir las opciones del menu interactivo.

> **Nota:** pyfiglet es opcional. Si no está instalado, el programa funciona igual sin los banners decorativos.

## Estructura del codigo

El sistema esta organizado en funciones modulares:

- Funciones de validacion (entradas del usuario)
- Funciones de utilidad (limpieza de pantalla)
- Funciones del menu principal
- Sub-funciones de registro (registrar, eliminar, mostrar)
- Funciones de negocio (turnos, atencion, servicios, estadisticas)
