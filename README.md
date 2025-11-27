# FidyBoost - Plataforma de Conexión Deportiva

Proyecto del Módulo Semilla Intermodular · Grupo 1 - 2º DAW · CIFP
Carlos III (Cartagena)

## Descripción del Proyecto

FidyBoost es una aplicación web destinada a conectar a deportistas y
facilitar la organización de actividades físicas. Su objetivo es
resolver la dificultad de encontrar compañeros de entrenamiento o
completar equipos para deportes grupales en la zona del usuario.

El proyecto forma parte de la iniciativa **Semilla Intermodular**,
integrando diseño de interfaces, desarrollo frontend y experiencia de
usuario.

## Funcionalidades Principales

-   **Dashboard Interactivo:** Vista general de próximas actividades con
    filtros por categoría.\
-   **Buscador en Tiempo Real:** Filtrado dinámico sin recargar la
    página.\
-   **Sistema de Guardados:** Permite marcar actividades como favoritas
    y añadirlas a un calendario personal.\
-   **Calendario Personalizado:** Organización por pestañas: *Todos*,
    *Asistiré*, *Guardados*.\
-   **Descubrimiento de Grupos:** SPA para explorar grupos deportivos en
    la zona.\
-   **Diseño Mobile-First:** Navegación optimizada para dispositivos
    móviles.

## Tecnologías Utilizadas

-   **Frontend:** React.js\
-   **Estilos:** Bootstrap 5 + CSS3\
-   **Iconografía:** Bootstrap Icons\
-   **Gestión de Estado:** React State\
-   **Datos:** Mock Data simulando estructuras JSON

## Instalación y Despliegue

Clonar el repositorio:

``` bash
git clone https://github.com/usuario/fidyboost.git
cd fidyboost
```

Instalar dependencias:

``` bash
npm install
```

Ejecutar el servidor de desarrollo:

``` bash
npm run dev
```

Abrir en el navegador:

    http://localhost:5173

## Estructura del Proyecto

    src/
    ├── components/
    │   ├── Header.jsx          # Barra de navegación superior y perfil
    │   ├── SearchSection.jsx   # Buscador y filtros
    │   ├── ActivityItem.jsx    # Tarjeta de actividad reutilizable
    │   ├── GroupsList.jsx      # Descubrimiento de grupos
    │   └── BottomNav.jsx       # Navegación móvil
    ├── data/
    │   └── mockData.js         # Datos simulados
    ├── App.jsx                 # Componente principal
    └── main.jsx                # Punto de entrada

## Autores - Grupo 1

Proyecto desarrollado por alumnos de 2º DAW:

-   **Diego**
-   **Youssef**
-   **Fulgencio** 
-   **Iker**
-   **Jose Luis**

Desarrollado con dedicación en el CIFP Carlos III.
