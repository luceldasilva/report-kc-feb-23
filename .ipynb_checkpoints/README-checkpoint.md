# Reporte Copa KC Febrero 2023

![](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)![](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)![](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white) 

Puede encontrarlo también en [![](https://img.shields.io/badge/Deepnote-3793EF?style=for-the-badge&logo=Deepnote&logoColor=white)](https://deepnote.com/@luceldasilva/KC-Cup-FEB-2023-ac0e62ae-54fb-4f6c-aee5-9b37d3ae9485)

![](https://s3.duellinksmeta.com/img/content/tournaments/kc-cup/dlm-kc-intro.webp)

Contiene mazos Nd. MAX de la KC Cup en YuGiOh! Duel Links Edición Febrero 2023 de la comunidad hispanohablante

## Conociendo los datos

Se usa la estrucura de la [API de recolección de mazos](https://github.com/luceldasilva/api-kc-report-duel-links)

| Columna | Tipo de Dato |Descripción | 
| :---: | :---: | :---: | 
| id | String | Id característico de registro en MongoDB |
| duelist | Integer | Código identificatorio universal del usuario |
| deck | String | El mazo usado |
| skill | String | La habilidad usada para el deck |
| zerotg | Boolean | Usuario perteneciente a la comunidad [ZeroTG](https://www.youtube.com/c/ZeroTG) |
| zephra | Boolean | Usuario perteneciente a la comunidad [ZephraCarl](https://www.youtube.com/c/ZephraCarl) |
| bryan | Boolean | Usuario perteneciente a la comunidad [Bryan Norén](https://www.youtube.com/c/BryanNorén) |
| ndmax | String | Fecha que llegó al rango máximo del torneo |