# UbankaApp-challenge
Analisis exploratorio de datos sobre habitos de ahorro de usuarios de Ubank App

La base de datos esta compuesta por 4 tablas

1.- Test_projects (Proyectos u objetivos que tienen los usuarios para ahorrar)

Ubank le solicita a los usuarios que ingresen una meta de ahorro, la cual le llamamos proyecto, y que además escoja una o más reglas por cada proyecto con las cuales puede ir ahorrando. 

Debes considerar que los proyectos van a tener un nombre, una fecha que es meta para lograrlo, una categoría y monto esperado para ahorrar.

2.- Test Rules (Reglas que eligen los usuarios para ahorrar)
Por otro lado,las reglas tienen el proyecto asociado (en donde la relación es que todo proyecto tiene una o más reglas)  y el tipo de regla

Cada tipo de regla implica un mecanismo de ahorro distinto. Algunos ejemplos de dichas reglas son: 
Regla % de tu sueldo: Ahorrar un % del sueldo
Regla placer culpable: Ahorrar un % del monto de compra definido por ti cada vez que hagas un consumo de algo que te gusta mucho. Ejemplo: Starbucks, Café en minimarkets, Restaurantes y pubs, etc
Regla pasión futbolera: Ahorrar cada vez que tu equipo de fútbol preferido gane

3.- Test_transactions 

Las transacciones (del consumo) que tienen una descripción del comercio donde se hace , la fecha de transacción y el monto de la transacción. A continuación se muestra un ejemplo de esto:

"user_id","description","transaction_date","amount"
"0001c38e1231436eb1218b4caf1090d6",OXXO MARIA,"2019-12-06 00:00:00.0",-335.00
"0001c38e1231436eb1218b4caf1090d6",RESTAURANT UMAI,"2019-12-17 00:00:00.0",-605.00
"0001c38e1231436eb1218b4caf1090d6",Lima Limón,"2019-12-17 00:00:00.0",-605.00

Los montos están en pesos mexicanos y la descripción es un texto. Considera que son transacciones realizadas en México.


4.-Catalog (Un catálogo que explica los tipos de proyectos y reglas que tenemos. La persona siempre escoge una de las categorías de “project categories”)
