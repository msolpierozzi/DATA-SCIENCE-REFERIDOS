<body>
    <h1>DATASET REFERIDOS</h1>
    <p>
        El dataset seleccionado para analizar, esta compuesto por los referidos
        de un Sistema que otorga Créditos Personales a una población que no sería
        aprobada para un préstamo en una entidad bancaria. Los datos son analizados
        por un Motor de Riesgos que determinará si finalmente se consideran aptos
        para recibir una oferta o no (Los clientes aprobados serán identificados con
        la variable approved en True). Para saber si una persona puede optar o no por
        un crédito, la politica que se encuentra en el motor de decisión se basa en el
        análisis de distintos aspectos socioeconómicos de la persona, para luego
        asignarles a cada uno un puntaje o score. Este puntaje obtenido, sera pieza
        fundamental para determinar la decisión final; ya que de él depende la aprobación
        o el monto que se le otorgará al cliente. Los referidos, se agrupan por su nivel
        socioeconómico y su situación actual (Que muestra la mora que presenta un cliente
        con otras entidades) y es posible identificar si su género es masculino o femenino.
        Por otro lado, los montos máximos otorgados también dependerán del análisis de Riesgo
        mencionado anteriormente. Por ello, encontramos importante observar cómo se comporta
        el monto según situación actual, score, género y nivel socioeconómico; ya que esto
        nos permitirá atraer una mejor población para incrementar la otorgacion y disminuir
        la mora. En este caso, quisiéramos resolver las siguientes interrogantes:
    </p>
    <ul>
        <li>
            ¿Cuál es el monto máximo otorgado? ¿Y el mínimo?
        </li>
        <li>
            Se otorgan más montos de mayor o de menor valor?
            ¿Existe una relación entre monto y cantidad de créditos otorgados?
        </li>
        <li>
            Comparando los referidos entre hombres y mujeres,
            ¿Existe una diferencia notable entre esta cantidad?
            ¿A quiénes se le otorgan mayores montos?
        </li>
        <li>
            ¿Cuál es el grupo de Nivel Socioeconómico que posee mayor puntaje de Riesgo?
            ¿Existe una diferencia significativa entre los puntajes?
        </li>
    </ul>
    <hr>
    <h2>DEFINICIÓN DEL OBJETIVO</h2>
    <p>El objetivo principal de nuestro análisis es identificar los rasgos de los
        referidos que posiblemente serán aprobados por el motor para así poder tomar
        acciones por ej: campañas de publicidad para poder atraer a ese grupo poblacional.
    </p>
    <hr>
    <h2>CONTEXTO COMERCIAL</h2>
    <p>En el sistema, los clientes pueden provenir de dos fuentes. Por un lado, se
        encuentran aquellos que inician una solicitud directamente desde la web y,
        por el otro se encuentran los Referidos. Estos últimos, son una fuente fundamental
        para el ingreso de clientes puesto que proveen información sobre clientes potenciales
        (podrán ser aprobados o rechazados). En este caso, nos centraremos únicamente en el
        funcionamiento de los referidos. Por ello, es importante analizar los rasgos que
        identifican al sector que finalmente es apto para recibir un crédito. De esta manera,
        será posible presentar los resultados obtenidos a los Referidos y así poder tomar
        acciones preventivas para incrementar el número de referidos exitosos.
    </p>
    <hr>
    <h2>CONTEXTO ANALÍTICO</h2>
    <p>El equipo de riesgos ha recibido datos sobre los últimos 50.000 referidos recibidos
        desde el 30 de Agosto de 2022. Los mismos, identifican mediante la variable approved si han sido o
        no aprobados respectivamente. Debemos utilizar modelos de agrupamiento para abordar
        este problema de aprendizaje no supervisado.
    </p>
</body>
