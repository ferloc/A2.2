# A2.2

En este proyecto usare la base de datos una base de datos de nombre 'BancoFull' del ,[UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/222/bank+marketing)
Los datos están relacionados con campañas de marketing directo (llamadas telefónicas) de una entidad bancaria portuguesa. El objetivo de la clasificación es predecir si el cliente suscribirá un depósito a plazo (variable y).
Se usara en esta base de datos : regresion logistica, LDA(Linear Discriminant Analysis ) y arbol de decisiones.


Las variables son las siguientes



| **Variable** | **Descripción** | **Tipo** |
|--------------|-----------------|----------|
| age          | Edad del cliente | Numérica |
| job          | Tipo de trabajo | Categórica: "admin.", "unknown", "unemployed", "management", "housemaid", "entrepreneur", "student", "blue-collar", "self-employed", "retired", "technician", "services" |
| marital      | Estado civil | Categórica: "married", "divorced", "single" (nota: "divorced" incluye divorciado o viudo) |
| education    | Nivel educativo | Categórica: "unknown", "secondary", "primary", "tertiary" |
| default      | ¿Tiene crédito en default? | Binaria: "yes", "no" |
| balance      | Balance promedio anual, en euros | Numérica |
| housing      | ¿Tiene préstamo de vivienda? | Binaria: "yes", "no" |
| loan         | ¿Tiene préstamo personal? | Binaria: "yes", "no" |
| contact      | Tipo de comunicación de contacto | Categórica: "unknown", "telephone", "cellular" |
| day          | Día del último contacto del mes | Numérica |
| month        | Mes del último contacto del año | Categórica: "jan", "feb", "mar", ..., "nov", "dec" |
| duration     | Duración del último contacto, en segundos | Numérica |
| campaign     | Número de contactos realizados durante esta campaña y para este cliente | Numérica |
| pdays        | Número de días que han pasado desde el último contacto con el cliente en una campaña anterior | Numérica (-1 significa que el cliente no fue contactado previamente) |
| previous     | Número de contactos realizados antes de esta campaña y para este cliente | Numérica |
| poutcome     | Resultado de la campaña de marketing anterior | Categórica: "unknown", "other", "failure", "success" |
| y            | ¿El cliente ha suscrito un depósito a plazo? | Binaria: "yes", "no" |

**Aquí  Y es la variable de salida de esta base de datos.**



**Indice**
