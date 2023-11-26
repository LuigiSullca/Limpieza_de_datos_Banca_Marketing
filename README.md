# Limpieza_de_datos_Banca_Marketing

#1. PROBLEMA DEL NEGOCIO:
Una entidad bancaria contrata a una empresa de marketing encargada de contactar telefónicamente a posibles clientes para determinar si están interesados o no en adquirir un certificado de depósito a término con el banco.

¿Qué perfil tienen los clientes con mayor potencial de conversión?

#2. SET DE DATOS:

La información recolectada por la empresa de mercadeo se encuentra en un archivo CSV (dataset_banco.csv) con 45215 filas y 17 columnas.

Cada registro contiene 16 características (las primeras 16 columnas) y una categoría ("yes" o "no" dependiendo de si la persona está o no interesada en adquirir el producto). Las columnas son:

#"age": edad (numérica)
#"job": tipo de trabajo (categórica: "admin.", "unknown", "unemployed", "management", "housemaid", "entrepreneur", "student", "blue-collar","self-employed", #"retired", "technician", "services")
#"marital": estado civil (categórica: "married", "divorced", "single")
#"education": nivel educativo (categórica: "unknown", "secondary", "primary", "tertiary")
#"default": si dejó de pagar sus obligaciones (categórica: "yes", "no")
#"balance": saldo promedio anual en euros (numérica)
#"housing": ¿tiene o no crédito hipotecario? (categórica: "yes", "no")
#"loan": ¿tiene créditos de consumo? (categórica: "yes", "no")
#"contact": medio a través del cual fue contactado (categórica: "unknown", "telephone", "cellular")
#"day": último día del mes en el que fue contactada (numérica)
#"month": último mes en el que fue contactada (categórica: "jan", "feb", "mar", ..., "nov", "dec")
#"duration": duración (en segundos) del último contacto (numérica)
#"campaign": número total de veces que fue contactada durante la campaña (numérica)
#"pdays": número de días transcurridos después de haber sido contactado antes de la campaña actual (numérica. -1 indica que no fue contactado previamente)
#"previous": número de veces que ha sido contactada antes de esta campaña (numérica)
#"poutcome": resultado de la campaña de marketing anterior (categórica: "unknown", "other", "failure", "success")
#"y": categoría ¿el cliente se suscribió a un depósito a término? (categórica: "yes", "no")

# Como sugerencia, revisemos y entendamos la función de cada columna en el dataset para comprender la información que tenemos frente al problema de negocio para poder realizar una limpieza de datos óptima.
