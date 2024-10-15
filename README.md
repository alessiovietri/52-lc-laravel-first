# Come installare Laravel

a. Con il comando composer create-project

1. Soluzioni possibili:
- composer create-project laravel/laravel:^10.0 .                           -> Questo clona la repo laravel/laravel nella cartella attuale
- composer create-project laravel/laravel:^10.0 nome-progetto               -> Questo clona la repo laravel/laravel in una nuova cartella che si chiamerà "nome-progetto"

b. Clonando una propria repo laravel da github

1. Clono la repo
2. Copio il file .env.example (già presente nella repo), lo incollo nella stessa posizione e lo rinomino in .env
3. Eseguo nel terminale il comando composer install
4. Al termine dell'esecuzione del comando composer install, sempre nel terminale, mi copio dal file composer.json il comando php artisan key:generate --ansi e lo eseguo

INDIPENDENTEMENTE DA QUALE DELLE DUE SOLUZIONI ABBIAMO SCELTO

Dopo aver completato i passi precedenti, nel terminale, eseguiamo php artisan serve per avviare il server locale
