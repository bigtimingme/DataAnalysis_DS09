Proyecto Data Analysis
Telecomunicaciones

Alumno: Francisco Jiménez de Aréchaga
Cuenta Github: bigtimingme
Repositorio: DataAnalysis_DS09

Rol a desarrollar:
Una empresa prestadora de servicios de telecomunicaciones nos encarga la realización de un análisis completo que permita reconocer el comportamiento de este sector a nivel nacional. A Considerar: la principal actividad de la empresa es brindar acceso a internet, pero también es importante considerar el comportamiento asociado al resto de los servicios de comunicación, con el fin de orientar a la empresa en brindar una buena calidad de sus servicios, identificar oportunidades de crecimiento y poder plantear soluciones personalizadas a sus posibles clientes.

Tareas a realizar:
1. EDA(Exploratory Data Analysis) de la situación actual del Internet en Argentina:
   El EDA está localizado en el archivo EDA.ipynb

2. Crear un Dashboard coherente con el EDA previo:
   El Dashboard está en el archivo ENACOM.pbix

3. Armar 4 KPI e incluírlos en el Dashboard del punto 2.

   KPI 1: Aumentar 2% la penetración de Internet a nivel provincial el próximo trimestre

   KP1 2: Disminuir 1% el consumo de la tecnología ADSL a nivel nacional en el próximo trimestre.

   KPI 3: Aumentar 2% el consumo de la tecnología Cablemodem a nivel nacional en el próximo trimestre.

   KPI 4: Aumentar 2% el consumo de Fibra Óptica en el próximo trimestre a nivel nacional.


Reporte de Análisis:

En base al EDA del punto 1, se pueden ver tendencias interesantes. En primer lugar, desde el 2014 se ve un incremento constante en el Acceso a Internet por cada 100 hogares a nivel nacional. También vemos en la primer visualización el incremento muy bajo del acceso a internet por cada 100 habitantes. Esto se podría explicar por los niveles desorbitantes de pobreza en Argentina y la brecha enorme que se está propagando en el acceso a internet. Según el Indec (https://www.indec.gob.ar/indec/web/Nivel3-Tema-4-46), los niveles de pobreza alcanzan al 40% de la población.
A nivel provincial, se ven cosas interesantes como la oscilación de Capital Federal alrededor de 112 de accesos por cada 100 hogares. Las provincias que más han aumentado su acceso a internet son La Rioja y San Luis.

En el plano tecnológico, vemos que las cuatro tecnologías más importantes en Argentina son Cablemodem, ADSL(Asymmetric Digital Suscriber Line), Fibra Óptica y Wireless. Hubo un cambio en la jerarquía de las mismas en los últimos 10 años, siendo en el 2014 la tecnología más usada ADSL y ahora (2022) siendo la segunda, detrás de Cablemodem. 
Esto responde a dos cuestiones:
1. La necesidad de mayor velocidad de bajada: La tecnología ADSL tiene un techo de 24 Mbps y mientras se aleja de la central que transmite el Internet, va perdiendo valor real de velocidad. Las necesidades/costumbres actuales van en camino hacia un constante aumento del consumo de Internet (servicios de streaming, redes sociales, teletrabajo), y si vamos sumando todos los aparatos electrónicos que utilizan internet simultáneamente, 24 Mpbs van quedando cortos.

2. Caída del consumo del teléfono fijo: ADSL usa el mismo sistema de cableado que el teléfono fijo, y por mucho tiempo, al ser el teléfono fijo algo necesario en cada hogar, las empresas telefónicas eran las líderes en la prestación de Internet armando paquetes entre la línea de teléfono y el Internet. Al ser reemplazado el teléfono hogareño por el celular, en una tendencia macro hacia el consumo individualizado, el teléfono fijo quedó obsoleto.

Por otro lado, al comparar el crecimiento de la tecnología Cablemodem y el consumo de televisión por cable, vemos que el consumo de cable modem se va acercando a la televisión por cable. Dado que ambos se transmiten por el mismo medio, podría muy bien significar que las personas que optan por consumir televisión por cable están uniendo su consumo de Internet al mismo. La mayoría de las empresas que prestan servicios de televisión por cable dan servicios de internet por Cablemodem y hacen paquetes de promoción. El paso de ADSL a Cablemodem se explica por la mayor velocidad de bajada de Cablemodem, yendo desde los 2Mbps hasta las 100Mbps.

Por último, la tecnología de Fibra Óptica es la opción del futuro. Es la otra tecnología que más ha crecido en estos últimos 10 años. Los límites de la Fibra Óptica están constantemente siendo testeados, y cada vez parecen ser más grandes, llegando en tests hechos por la empresa australiana Telstra a 30Tbps (https://www.adslzone.net/reportajes/internet/limites-velocidad-fibra-optica/).


