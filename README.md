# Power-Apps-AF-47133---Grupo-99735

Repositorio de apoyo para un curso de Power Apps.

Este proyecto contiene archivos de datos en formato CSV para realizar cargas de prueba y validar escenarios tipicos dentro de una aplicacion de Power Apps (contactos, cuentas y productos).

## Objetivo

Disponer de un set de datos sencillo para:

- practicar importacion de datos,
- modelar relaciones basicas,
- probar formularios, galerias y filtros,
- validar flujos funcionales durante el curso.

## Estructura del repositorio

```text
.
|-- Carga de datos/
|   |-- contactos.csv
|   |-- Cuentas.csv
|   `-- Productos.csv
|-- Presentacion/
|   `-- Presentacion Instructor Curso Power Apps.pdf
|-- Documentacion MSLearn.docx
`-- README.md
```

## Archivos de carga de prueba

Los CSV usan `;` como separador de columnas.

### 1) contactos.csv

Datos de personas de ejemplo.

- Filas aproximadas: 10 (incluyendo cabecera).
- Columnas: Nombre de pila, Apellidos, Fecha de nacimiento, Correo electronico, Empresa.

### 2) Cuentas.csv

Datos de cuentas/empresas de ejemplo.

- Filas aproximadas: 11 (incluyendo cabecera).
- Columnas: Nombre de empresa, Calle, Codigo Postal, Provincia, Ciudad, Pais, NIF.

### 3) Productos.csv

Catalogo de productos de ejemplo.

- Filas aproximadas: 20 (incluyendo cabecera).
- Columnas: Nombre, Id. Producto, Stock.

## Uso sugerido en Power Apps

1. Crear una app nueva en Power Apps.
2. Importar los tres archivos CSV desde la carpeta `Carga de datos`.
3. Crear pantallas para listado de contactos, cuentas y productos, junto con formularios de alta/edicion.
4. Implementar busqueda y filtros basicos.
5. Validar reglas simples (campos obligatorios, formatos, etc.).

## Notas

- El contenido esta orientado a practicas del curso.
- Los datos no representan informacion real de clientes.
