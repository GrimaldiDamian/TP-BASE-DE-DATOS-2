# Proyecto de Data Mart - The Drinking Company (TDC)
## Descripción del Proyecto
Este proyecto forma parte de un trabajo académico en el cual asumimos el rol de administradores de base de datos para una compañía llamada The Drinking Company (TDC). El objetivo es desarrollar un Data Mart para gestionar y analizar la información relacionada con las ventas de productos de la empresa, que comercializa bebidas en diversas categorías en los mercados minorista y mayorista.

La compañía opera durante todo el año y ha experimentado un crecimiento significativo en los últimos 4 años. Nuestro Data Mart facilitará el análisis del rendimiento de ventas en función de diversas dimensiones como:

Regiones geográficas: Este (east), Oeste (west), Centro (central) y Sur (south).
Productos: Colas, cervezas, sodas, jugos y bebidas energizantes.
Presentaciones: Botellas de 1 litro, botellas de 2 litros, botellas de 670 cm³, latas de 330 cm³ y latas de 500 cm³.
Clientes: Información sobre los clientes mayoristas y minoristas.
Períodos de tiempo: Años, meses, días, entre otros.
El proyecto busca facilitar el análisis, pronóstico y rastreo de ingresos de ventas sin sobrecargar las bases de datos operacionales.

## Objetivos del Proyecto
Diseñar e implementar un Data Mart para optimizar las consultas y análisis relacionados con las ventas.
Desarrollar un esquema de datos que permita rastrear el rendimiento de ventas por región, producto, cliente y período de tiempo.
Implementar procesos ETL (Extracción, Transformación y Carga) para limpiar y transformar los datos operacionales en datos informativos.
Crear consultas e informes que permitan al área de finanzas de TDC analizar las ventas de manera más eficiente.
## Tecnologías Utilizadas
Para el desarrollo del Data Mart se utilizaron las siguientes tecnologías:

SQL Server: Base de datos para almacenar y gestionar los datos de ventas.
Integration Services (SSIS): Para los procesos de ETL.
Reporting Services (SSRS): Generación de informes.
SQL: Para la creación de tablas, consultas y procedimientos almacenados.
Visual Studio: Para la integración con SSIS y SSRS.
## Estructura de Datos
El Data Mart consta de varias tablas dimensionales y una tabla de hechos para modelar las ventas. Las tablas más relevantes son:

Dim_Producto: Información sobre los productos de TDC, incluyendo categorías y presentaciones.
Dim_Region: Información sobre las 4 regiones geográficas.
Dim_Cliente: Datos de clientes mayoristas y minoristas.
Dim_Tiempo: Tabla de tiempo que permite desglosar las ventas por períodos específicos.
Dim_RangoEtario: Tabla de rango etario donde se desglosa, varios rango como Teenagers, adultos medios, adultos mayores.
Fact_ventas: Almacena las transacciones de ventas, vinculadas a las tablas dimensional
