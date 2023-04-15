# Entregable de laboratorio 4
#### Laboratorio 4 (14/04/23) - Uso de Bitalino para  ECG

## Tabla de contenidos
---
* [Intregantes](#integrantes)
* [Objetivos](#objetivos)
* [Materiales y Equipos](#materiales-y-equipos)
* [Procedimiento](#procedimiento)
* [Conexiones Usadas](#conexiones-usadas)
* [Señales medidas](#señales-medidas)
* [Ploteos en OpenSignals](#ploteo-de-la-señal-en-opensignals)
    * [Archivos](#archivos)
* [Resumen y explicación de la señal ploteada](#resumen-y-explicación-de-la-señal-ploteada)
* [Ploteos en Python](#ploteo-en-python)
    * [Archivos]()
* [Bibliografía](#bibliografia)

## Integrantes
---
* Joseph Jesus Melgarejo Castillo -joseph.melgarejo@upch.pe
* Gabriel Adolfo Narvaez Montalvo- gabriel.narvaez@upch.pe
* Mauricio Leonardo Ramos Gallegos -  mauricio.ramos@upch.pe
* Diego Alejandro Celis Matias - diego.celis@upch.pe 
* Ricardo Alonso Muñoz Quiroz- ricardo.munoz@upch.pe

## Objetivos
---
* El objetivo de adquirir señales biomédicas de ECG es obtener mediciones precisas de las señales eléctricas del corazón para evaluar su función y detectar posibles anomalías
* El objetivo de configurar correctamente el dispositivo BiTalino es garantizar que las señales ECG se adquieran de manera óptima, con parámetros adecuados y sin interferencias externas que puedan afectar la precisión de las mediciones.
* El objetivo de extraer información de las señales ECG con el software OpenSignals (r)evolution es procesar y analizar los datos obtenidos de manera eficiente, aplicando herramientas y técnicas adecuadas para visualizar y obtener información relevante de las señales ECG. Esto permite obtener una comprensión más profunda de la función cardíaca y detectar posibles patologías.

## Materiales y equipos
---
| Modelo | Descripción | Cantidad | Referencias |
| :---         |     :---:      |     :---: | ---:|
| (R)EVOLUTION   | Kit BiTalino     | 1    |<img src="Repositorio/Bitalino.jpg" alt="Bitalino" width="300">|
| -     | Laptop o PC       | 1      ||


## Procedimiento
---
### **Conexiones Usadas**
* BiTalino - Cables
    <p align="justify">Las conexiones que se hicieron en el módulo Bitalino se hicieron en base al manual guía de como se usa bitalino. </p>

    <img src="Repositorio/Conexion_bit.jpg" alt="Biotalino Conexion" width="300">


* Electrodos - Cuerpo

   

    <img src="Repositorio/Conexio_cuer.jpg" alt="Cuerpo Conexion" width="300">

    Las conexiones que se hicieron en el primer paciente fueron:

| Zona |Electrodo | Polaridad |
| :---  | :---: | ---:|
| En la muñeca izquierda|Rojo| Positivo|
| En la muñeca derecha |Negro| Negativo |
| Cresta Iliaca|Blanco| Referencia|



|   Vista Superior | Vista Frontal- | 
| :---         |     :---:      |
|   <img src="Repositorio/vsuperior.jpg" alt="Conexion Frontal" width="300">|  <img src="Repositorio/vfrontal.jpg" alt="Conexion Superior" width="300">|

---Explicar sobre el siguiente paciente ---

|   Referencia | Posicionamiento | 
| :---         |     :---:      |
|   ![BiTalino_guia_conexion2of](https://user-images.githubusercontent.com/101833633/231614819-e85cac50-2ecf-4bbe-bde6-d4ec18c68100.png) |   |