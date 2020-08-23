Este es un ejemplo de un api REST que tiene implementados 4 verbos HTTP:

GET
POST
PUT
DELETE

Para esta implementación se ha considerado el uso de una base de datos y se ha utilizado los siguiente recursos:

RUTAS

Se encuentran implementadas en el archivo: /routes/web.php

MODELO

Se implementa un model en el archivo: /app/Developer.php

CONTROLLER

Se implementa un controller en el archivo: /app/Http/Controllers/DeveloperController.php

MIGRATIONS

Se implementa una migration en el archivo: /database/migrations/2020_08_22_151624_create_developers_table.php

CONSUMO DE API

Las llamadas al API se debe hacerlas de la siguiente manera:

GET : [DominioAplicacion]/developers

POST: [DominioAplicacion]/developers
Los campos que se deben enviar son: nombres_completos, link_github, tecnologias_conocidas, todos son campos de tipo texto.

PUT: [DominioAplicacion]/developers/{id}
Los campos que se deben enviar son: nombres_completos, link_github, tecnologias_conocidas, todos son campos de tipo texto.

DELETE: [DominioAplicacion]/developers/{id}

