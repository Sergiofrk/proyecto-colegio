# Arquitectura del proyecto

El proyecto utiliza una estructura basada en el patrón MVC (Modelo, Vista y Controlador).

## Flujo de registro de estudiante

Vista (formulario de registro)
        ↓
Controlador (EstudianteController)
        ↓
Modelo (Estudiante)
        ↓
Controlador
        ↓
Vista (listado o mensaje de error)

## Flujo de registro de docente

Vista (formulario de registro)
        ↓
Controlador (DocenteController)
        ↓
Modelo (Docente)
        ↓
Controlador
        ↓
Vista (listado o mensaje de error)