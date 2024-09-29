# Data-Science
### Proyecto Final

El Dataset que elegí me parece bastante interesante porque permite visualizar a simple vista el nivel de crecimiento de los empleos relacionados con la Ciencia de Datos y la evolución y composición de los salarios de esta disciplina en auge y constante crecimiento.

### A continuación se incluye una descripción de las columnas del Dataset

work_year = Año de pago

experience_level = Seniority (EN: Nivel Inicial; MI: Nivel Junior / Medio; SE: Nivel Senior; EX: Nivel Experto)

employment_type = Tipo de empleo (PT: Part-time; FT: Full-time; CT: Por Contrato; FL: Independiente / Freelance)

job_title = Título de la posición laboral

salary = Salario bruto pagado

salary_currency = Moneda de pago

salary_in_usd = Salario expresado en Dólares Estadounidenses

employee_residence = País de residencia

remote_ratio = Ratio de trabajo remoto: 0 No Remoto (menos del 20%); 50 Parcialmente Remoto; 100 Totalmente Remoto (más del 80%)

company_location = País de origen de la empresa (ISO 3166)

company_size = Tamaño de la empresa medido en cantidad de empleados: S Menos de 50 empleados (small); M Entre 50 y 250 empleados (medium); L más de 250 empleados (large)

### Hipotesis de interés y tipo de aprendizaje del modelo

Elijo como variable objetivo salary_in_usd y el tipo de aprendizaje será supervisado por regresión lineal

### Conclusiones generales

Al tratarse de un dataset pequeño no es para nada representativo y el modelo seguramente está overfiteado y ante algún cambio de variables no va a responder para nada bien
El algoritmo que tuvo mejores resultados fue XGBOOST con un 99% de grado de acierto.

Más allá de esto por los gráficos obtenidos se puede afirmar que en el período de post-pandemia se incrementaron notoriamente los salarios del rubro Data Science.
Un punto llamativo es que quienes perciben salarios más altos son las personas que trabajan de manera presencial.
Si sólo nos centramos en en el ingreso por experiencia quienes perciben mayor salario son los Expertos cómo se puede suponer a priori.






