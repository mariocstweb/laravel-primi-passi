nome repo: laravel-primi-passi
Ciao ragazzi,
oggi iniziamo a muovere i primi passi con questo fantastico framework che è Laravel!
Per prima cosa, creiamo un nuovo progetto Laravel 10, utilizzando questo comando:
composer create-project laravel/laravel laravel-primi-passi
Al termine dell'installazione apriamo il progetto con Visual Studio Code e avviamolo con uno di questi due comandi:
php artisan serve oppure php -S localhost:8000 -t public
Creiamo poi il repository con il primo push su Github
A questo punto, iniziamo a prendere confidenza con le rotte e le views:
 cancelliamo la view welcome.blade.php e creiamo una nostra homepage.
Facciamo quindi sì che la rotta / visualizzi la vista home.blade.php
Inizialmente stampiamo un Hello World, poi passiamo dei dati alla view in modo da visualizzarli dinamicamente con Blade.
Bonus:
Creiamo più di una pagina e visualizziamo un header menu con i link di tutte le pagine, utilizzando la funzione route()
Buon Laralavoro! :laravel_icon: