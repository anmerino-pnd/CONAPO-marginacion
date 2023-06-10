#  Índices de Marginación en México

Este es un proyecto que buscar hacer un estudio multidimensional del índice de marginación en México. ¿Por qué? Bueno, dado que la marginación en México es un problema persistente que afecta a millones de personas, además, se caracteriza por la falta de acceso a servicios básicos, bajos niveles de educación, carencia de empleo digno, pobreza extrema y desigualdad. Esta realidad impactante refleja las brechas sociales y económicas que existen en el país, y representa un desafío para lograr un desarrollo equitativo y sostenible.  para construir un 

Siendo que es fundamental abordar la marginación para un México más justo y próspero para todas(os). Se decidió hacer este análisis y encontrar relaciones entre problemáticas reales que afectan a las(os) mexicanas(os), esto puede ser de bastante ayuda, dado que si encontramos una relación, entre dos variables, lo suficientemente fuerte, podemos atacar una esperando que la otra disminuya por igual.

## ¡Comencemos!
- La base de [datos](https://www.gob.mx/conapo/documentos/indices-de-marginacion-2020-284372) se descargó de la página oficial del Gobierno de México.
- Los imports necesarios para llevar a cabo el análisis son:
  ```python 
  import pandas as pd
  import matplotlib.pyplot as plt
  import seaborn as sns
  ``` 

  
ATENCIÓN :heavy_exclamation_mark::heavy_exclamation_mark::heavy_exclamation_mark: \
Dado que el archivo de descarga es un archivo excel con 3 pestañas, es necesario seleccionar la segunda pestaña.
![image](https://github.com/anmerino-pnd/CONAPO-marginacion/assets/30573365/4e63a1ac-7d15-4ae5-ba53-0328678ca8b1)

Después, debe guardar el archivo como *csv*.
![image](https://github.com/anmerino-pnd/CONAPO-marginacion/assets/30573365/4e3204eb-88d9-46ca-97ff-367ae706a785) \
De lo contrario, a la hora de la lectura del archivo, puede haber errores.

De aquí en adelante, puede checar nuestra [Jupyter Notebook](https://github.com/anmerino-pnd/CONAPO-marginacion/blob/main/IMM_2020.ipynb) donde le indica paso a paso, y bien explicado, todo el proceso y análisis riguroso que se siguió.

## Agradecimientos
Este proyecto fue posible gracias a la ayuda y enseñanza de
<a href="https://mcd.unison.mx">
<img src="site/img/logo_mcd.png" alt="Maestría en Ciencia de Datos" height="50"/>

  

## Referencias
* Gobierno de México (2020). Índices de marginación 2020. Gob.mx. https://www.gob.mx/conapo/documentos/indices-de-marginacion-2020-284372

‌
