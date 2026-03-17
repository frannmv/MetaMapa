# MetaMapa

> Trabajo práctico anual desarrollado en la materia *Diseño de Sistemas de Información* - UTN FRBA (2025).

## Descripción

MetaMapa es una plataforma colaborativa para la recopilación, agregación y visualización de hechos geolocalizados provenientes de múltiples fuentes.

A los administradores se les ofrece un panel de administración donde podrán:
- actualizar las colecciones: cambiar nombre, descripción, fuentes o algoritmos de consenso
- manejo de solicitudes de eliminación de hechos
- obtener estadísticas de cada colección
- importar hechos desde un archivo CSV


## Funcionalidades para Usuarios
- Navegar y buscar hechos geolocalizados en distintas colecciones

- Visualizar hechos en un mapa interactivo

- Contribuir nuevos hechos a la plataforma, incluyendo imágenes y videos

- Solicitar la eliminación de aquellos hechos que consideren inapropiados

---

## Funcionalidades para Administradores
El sistema provee un panel de administración que permite:

- **Gestionar colecciones**
    - Editar nombre y descripción
    - Configurar fuentes de datos
    - Definir algoritmos de consenso

- **Moderación de contenido**
    - Gestionar solicitudes de eliminación de hechos

- **Análisis**
    - Consultar estadísticas por colección

- **Importación de hechos**
    - Cargar hechos desde archivos CSV

---

## Tecnologías Utilizadas
- Java
- Javalin
- Handlebars (cliente liviano)
- Hibernate + JPA
- PostgreSQL
- Docker
- Maven
- Render

## Arquitectura

El sistema sigue una arquitectura MVC, separando responsabilidades entre lógica de dominio, persistencia y presentación.

### Capas del sistema

- **Cliente Web (Handlebars)**
  Interfaz de usuario basada en un cliente liviano.

- **API REST (Javalin)**
  Expone los endpoints del sistema.

- **Lógica de Dominio**

- **Persistencia (Hibernate + JPA)**
  Mapeo Objeto-Relacional.

- **Base de Datos (PostgreSQL)**
