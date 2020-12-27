# 📈🗳️Elecciones Catalunya 2021

[![GitHub commit](https://img.shields.io/github/license/endikasatu/catalunya-2021-model)](https://github.com/endikasatu/catalunya-2021-model/blob/main/LICENSE) [![GitHub commit](https://img.shields.io/github/last-commit/endikasatu/catalunya-2021-model)](https://github.com/endikasatu/catalunya-2021-model/commits/main) 

Resultados de un  modelo electoral probabilístico para las elecciones autonómicas del 14 de febrero de 2021 en Catalunya.

Los resultados se pueden encontrar en el siguiente directorio: <a href="/data"><span><code>/catalunya-2021-model/data</code></span></a>

Creado por [Endika Nuñez](https://www.twitter.com/endikasatu)

Publicado en [TheElectoralReport](https://www.electoralreport.com)

## Archivos disponibles

En los siguientes archivos encontrarás los resultados actualizados del modelo y toda la información relevante al respecto. Los archivos se irán subiendo acorde a los próximos lanzamientos.

- `pde-resumen-catalunya-2021.csv` - Resumen de los resultados actualizados del promedio de encuestas
- `pde-plus-polls-catalunya-2021.csv` - Evolución del promedio de encuestas día-a-día con algunos sondeos publicados. Estos sondeos sirven para dibujar el gráfico, por lo que si hay varios el mismo día sólo se registrará uno de ellos. Se pueden consultar todas las encuestas en el siguiente archivo.
- `polls-catalunya-2021.csv` - Intención de voto de todas las encuestas y proyecciones publicadas. Los datos provienen de [Wikipedia](https://en.wikipedia.org/wiki/2021_Catalan_regional_election#Opinion_polls).

## Utilización de los datos

Los resultados del modelo son compartidos en su totalidad con la intención de que terceros puedan hacer uso de ellos. Para ello, debe realizarse una mención a TheElectoralReport y añadir el link a este repositorio. 

Puedes copiar y pegar la siguiente cita:

> [Modelo de TheElectoralReport](https://github.com/endikasatu/catalunya-2021-model)

Además, puedes consultar las condiciones de la licencia del proyecto [en este enlace](https://github.com/endikasatu/catalunya-2021-model/blob/main/LICENSE) o ponerte en contacto con nosotros mandando un correo a [contacto@electoralreport.com](mailto:contacto@electoralreport.com).

## Variables

### Partidos

- `ERC`: Esquerra Republicana de Catalunya
- `Junts`: Junts, per Catalunya
- `PDeCAT`: Partit Demòcrata Europeu Català
- `CUP`: Candidatura d'Unitat Popular
- `UP_Conf`: Catalunya En Comú
- `PSC`: Partido de los Socialistas de Catalunya
- `PP`: Partido Popular de Cataluña
- `Cs`: Ciutadans
- `Vox`: Vox

### Bloques

- `Indepe`: Bloque formado por ERC, Junts y CUP.
- `Indepe_plus`: Bloque formado por ERC, Junts, CUP y PDeCAT.
- `No_Indepe`: Bloque formado por PSC, PP, Cs y Vox.
- `No_Indepe_plus`: Bloque formado por PSC, PP, Cs, Vox y UP_Conf.
- `Izq`: Bloque formado por ERC, PSC y UP_Conf.
- `Izq_plus`: Bloque formado por ERC, PSC, UP_Conf y CUP.
- `Dch`:  Bloque formado por PP, Cs, Vox.
- `Dch_plus`: Bloque formado por PP, Cs, Vox, Junts y PDeCAT.

### Otros

- `fecha`: Fecha del cálculo del modelo.
- `fecha_export`: Fecha y hora de ejecución del modelo.
- `encuestadora_comisionado`: Empresa demoscópica que realiza el sondeo y el medio que lo publica. 
- `trabajo_campo`: Fechas de realización del trabajo de campo.
- `last_day`: Último día de trabajo de campo.
- `e_day`: Día electoral.
- `dias_rest`: Días restantes desde el último día de trabajo de campo hasta el día de elecciones.
- `muestra`: El tamaño de muestra utilizado.
- `participacion`: Porcentaje de participación estimada por la encuestadora.
- `v1x2`: Ventaja en puntos porcentual de las dos primeras candidaturas más votadas.
- `fuente`: Fuente original de la encuesta o la noticia del medio que lo publica.

- `titular`: Titular de la noticia del medio que publica la encuesta.
- `urlDW`: encuestadora_comisionado con la URL de la fuente para las tablas en Datawrapper.

## Qué es TheElectoralReport

[TheElectoralReport ](https://electoralreport.com) es un blog independiente y apartidista y no está vinculado a ninguna organización pública ni privada. Creado y editado por Endika Nuñez.

Es un blog sobre datos en política y la actualidad. El objetivo principal de este blog es ofrecer análisis de encuestas y demográficos, elecciones y predicciones electorales, además de servir como agregador de encuestas.

## Contacto

Puedes contactar conmigo abriendo una *issue* en Github o  por alguna de las siguientes vías:

- **Email**: [contacto@electoralreport.com](mailto:contacto@electoralreport.com) | [endika.nunez@electoralreport.com](mailto:endika.nunez@electoralreport.com)
- **Twitter**: [TheElectoralReport](https://twitter.com/TheElectoralRep) | [Endika Nuñez](https://twitter.com/endikasatu)



