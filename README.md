**RETO - CAMPAÑA DE MARKETING DE UN BANCO PORTUGUÉS**

Basado en el reto guiado impartido de las últimas formaciones académicas en thePower D&A


**Stack Data & Analyst**

- Python
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Plotly


**Propósito del reto**

El propósito de este reto es poner en práctica los conocimientos de:

- EDA: análisis exploratorio de los datos
- Limpieza de datos
- Gestión de nulos
- Visualización de datos
- Justificar las conclusiones del caso propuesto

Contexto del caso, finalidad y datasets
Se proporciona unas fuentes de datos extraídas de unas campañas de _marketing_ de una institución bancaria portuguesa. Las campañas de marketing se basaron en llamadas telefónicas. A menudo, se requería más de un contacto con el mismo cliente para determinar si el producto (depósito a plazo bancario) sería suscrito o no.

Tras analizar los datasets, habría que ser capaz de responder: ¿ Ha sido esta campaña eficaz para ganar suscripciones en productos finacieros de la entidad bancaia ?

Para ello se nos proporcionan dos datasets.

Las colummas que tenemos en el primer _dataset_ ('bank-additional.csv') son:

- **age**: La edad del cliente.
- **job**: La ocupación o profesión del cliente.
- **marital**: El estado civil del cliente.
- **education**: El nivel educativo del cliente.
- **default**: Indica si el cliente tiene algún historial de incumplimiento de pagos (1: Sí, 0: No).
- **housing**: Indica si el cliente tiene un préstamo hipotecario (1: Sí, 0: No).
- **loan**: Indica si el cliente tiene algún otro tipo de préstamo (1: Sí, 0: No).
- **contact**: El método de contacto utilizado para comunicarse con el cliente.
- **duration**: La duración en segundos de la última interacción con el cliente.
- **campaign**: El número de contactos realizados durante esta campaña para este cliente.
- **pdays**: Número de días que han pasado desde la última vez que se contactó con el cliente durante esta campaña.
- **previous**: Número de veces que se ha contactado con el cliente antes de esta campaña.
- **poutcome**: Resultado de la campaña de marketing anterior.
- **emp.var.rate**: La tasa de variación del empleo.
- **cons.price.idx**: El índice de precios al consumidor.
- **cons.conf.idx**: El índice de confianza del consumidor.
- **euribor3m**: La tasa de interés de referencia a tres meses.
- **nr.employed**: El número de empleados.
- **y**: Indica si el cliente ha suscrito un producto o servicio (Sí/No).
- **date**: La fecha en la que se realizó la interacción con el cliente.
- **contact_month**: Mes en el que se realizó la interacción con el cliente durante la campaña de marketing.
- **contact_year**: Año en el que se realizó la interacción con el cliente durante la campaña de marketing.
- **id\_**: Un identificador único para cada registro en el dataset.

Además, se proporciona un excel que nos da información sobre las características demográficas y comportamiento de compra de los clientes del banco. Este excel consta de tres hojas de trabajo diferentes, y en cada una de ellas tenemos los clientes que entraron en el banco en diferentes años.
Las colummas que tenemos en el segundo _dataset_ ('customer-details.xlsx') son:

- **Income**: Representa el ingreso anual del cliente en términos monetarios.
- **Kidhome**: Indica el número de niños en el hogar del cliente.
- **Teenhome**: Indica el número de adolescentes en el hogar del cliente.
- **Dt_Customer**: Representa la fecha en que el cliente se convirtió en cliente de la empresa.
- **NumWebVisitsMonth**: Indica la cantidad de visitas mensuales del cliente al sitio web de la empresa.
- **ID**: Identificador único del cliente.
