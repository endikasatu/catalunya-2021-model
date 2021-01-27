# 📈🗳️Elecciones Catalunya 2021

[![GitHub commit](https://img.shields.io/github/license/endikasatu/catalunya-2021-model)](https://github.com/endikasatu/catalunya-2021-model/blob/main/LICENSE) [![GitHub commit](https://img.shields.io/github/last-commit/endikasatu/catalunya-2021-model)](https://github.com/endikasatu/catalunya-2021-model/commits/main)

Resultados de un  modelo electoral probabilístico para las elecciones autonómicas del 14 de febrero de 2021 en Catalunya. 

Los resultados se pueden encontrar en el siguiente directorio: <a href="/data"><span><code>/catalunya-2021-model/data</code></span></a>

Creado por [Endika Nuñez](https://www.twitter.com/endikasatu)

Publicado en [TheElectoralReport](https://www.electoralreport.com) y [elDiario.es]()

Metodología: [Metodología de la predicción para las elecciones en Catalunya paso a paso]()

## Artículos en prensa

Artículos y análisis publicados en prensa con los datos ofrecidos por el modelo.

| Medio                                                        | Fecha      | Titular                                                      | URL                                                          |
| ------------------------------------------------------------ | ---------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| <b style="padding: 1px 4px; color:#ffffff; background: #004a7f; border-radius:3px; font-size: 12px; letter-spacing: 1px; text-transform: uppercase; border: 1px solid #004a7f;">elDiario</b> | 21-01-2021 | El CIS catapulta a Illa gracias a un batacazo independentista sin precedentes | [🔗](https://www.eldiario.es/catalunya/cis-catapulta-illa-gracias-batacazo-independentista-precedentes_1_6999727.html) |
| <b style="padding: 1px 4px; color:#ffffff; background: #004a7f; border-radius:3px; font-size: 12px; letter-spacing: 1px; text-transform: uppercase; border: 1px solid #004a7f;">elDiario</b> | 12-01-2021 | El 'efecto Illa' impulsa al PSC pero aún no desbanca a ERC   | [🔗](https://www.eldiario.es/catalunya/efecto-illa-impulsa-psc-no-desbanca-erc_1_6746770.html) |

## Archivos disponibles

En los siguientes archivos encontrarás los resultados actualizados del modelo y toda la información relevante al respecto. Los archivos se irán subiendo acorde a los próximos lanzamientos.

- `pde-plus-polls-catalunya-2021.csv` - Evolución del promedio de encuestas día-a-día con algunos sondeos publicados. Estos sondeos sirven para dibujar el gráfico, por lo que si hay varios el mismo día sólo se registrará uno de ellos. Se pueden consultar todas las encuestas en el siguiente archivo.
- `polls-catalunya-2021.csv` - Intención de voto de todas las encuestas y proyecciones publicadas. Los datos provienen de [Wikipedia](https://en.wikipedia.org/wiki/2021_Catalan_regional_election#Opinion_polls).
- `resumen-prediccion.csv` - Resumen de la predicción para los partidos: votos y escaños.
- `probabilidades-mayorias-bloques.csv` - Resumen de la predicción para los bloques: votos, escaños y probabilidades de mayoría.
- `estvotoescanos-provincias.csv` -  Predicción de escaños con su horquilla para cada provincia.
- `probabilidades-escanos-enjuego.csv` - Probabilidad de obtener los escaños: escaños seguros (>99%), probables (75-99%) y en juego (25-75%).
- `probabilidades-posicion-votos.csv` - Probabilidad de quedar en cierta posición en votos a nivel autonómico.
-  `probabilidades-posicion-escanos.csv` - Probabilidad de quedar en cierta posición en escaños a nivel autonómico.

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
- `Comuns`: Catalunya En Comú
- `PSC`: Partido de los Socialistas de Catalunya
- `PP`: Partido Popular de Cataluña
- `Cs`: Ciutadans
- `Vox`: Vox

### Bloques

- `Independentistas`: Bloque formado por ERC, Junts, CUP y PDeCAT.
- `No-Indpendentistas`: Bloque formado por PSC, Cs, PP y Vox.
- `Izquierdas`: Bloque formado por ERC, PSC, Comuns y CUP.
- `Tripartito`: Bloque formado por ERC, PSC y Comuns.
- `Govern actual`: Bloque formado por ERC y Junts

## Qué es TheElectoralReport

[TheElectoralReport ](https://electoralreport.com) es un blog independiente y apartidista y no está vinculado a ninguna organización pública ni privada. Creado y editado por Endika Nuñez.

Es un blog sobre datos en política y la actualidad. El objetivo principal de este blog es ofrecer análisis de encuestas y demográficos, elecciones y predicciones electorales, además de servir como agregador de encuestas.

## Contacto

Puedes contactar conmigo abriendo una *issue* en Github o  por alguna de las siguientes vías:

- **Email**: [contacto@electoralreport.com](mailto:contacto@electoralreport.com) | [endika.nunez@electoralreport.com](mailto:endika.nunez@electoralreport.com)
- **Twitter**: [TheElectoralReport](https://twitter.com/TheElectoralRep) | [Endika Nuñez](https://twitter.com/endikasatu)



