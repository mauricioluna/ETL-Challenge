# ETL-Challenge
Desafío para evaluar postulantes al cargo de Analista ETL y su capacidad de análisis.

¡¡Lea todo el challenge antes de comenzar!!

Se espera que no trabaje más allá de 5 horas, por lo que se le recomienda priorizar las tareas donde tiene más aptitudes y en las que pueda avanzar mediante pseudo codigo o explicaciones, también se evaluará el razonamiento lógico, por lo que no será tiempo perdido.

# Instrucciones
Vamos a trabajar con la información del sitio booking.com, el objetivo es persistir información sobre hoteles ubicados en Chile en una base de datos mongodb en una instancia de capa gratuita de AWS.

El desafio tiene por objetivo evaluar sus capacidades tanto de análisis de la estructura de un sitio, sus data types y cuales serían los pipelines necesarios para persistir recurrentemente la información en una base de datos no relacional.

Se espera que realice un fork de este repositorio y trabaje en lenguaje python en particular en jupyter notebooks, para que deje comentado sus analisis, hallazgos o explicaciones sobre los pasos seguidos en su código.



## Documentos Esperados
### notebook sobre "Analisis del Sitio"
- La forma en que se puede realizar extracciones
- Los parametros que deben manejarse para extraer la información de manera correcta
- Las definiciones y transformaciones necesarias para validar y preparar la data para el almacenado en base de datos
### notebook sobre "Extracción"
- Identificación de los requests necesarios y sus parametros para realizar una descarga correcta
- Desarrollo de script para descarga concurrente (si le toma mucho tiempo puede usar pseudo código o si maneja algún framework también puede utilizarlo)
- Describir o desarrollar un script para extracciones diarias
### notebook sobre "Persistencia"
- Creación de instancia en EC2 de AWS, de manera segura
- Creación de Base de Datos con autenticación
- Creación de usuario para revisar la información persistida



Cualquier duda, estaremos en este canal de Gitter: https://gitter.im/InflowChile/ETL-Challenge
