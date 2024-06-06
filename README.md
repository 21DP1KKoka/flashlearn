# flashlearn

#### FlashLearn ir mācību vietne latviešu valodā, kur mācības notiek ar atmiņas kartītēm.


## Uzstādīšana

1. Klonē repozitoriju un atzipo failus
   Repozitorija:https://github.com/21DP1KKoka/flashlearn/edit/main

2. Lejupielādēt un uzstādīt nepieciešamos rīkus, kas nepieciešami vietnes darbībai.

XAMPP priekš php, datubāzes un apache servera.
```sh
  https://www.apachefriends.org/download.html
  ```

Composer nepieciešams priekš laravel un vue.js.
```sh
  https://getcomposer.org/download/
  ```

Node.js kopā ar npm lai palaistu vue.js failus
```sh
  https://nodejs.org/en/download/package-manager
  ```


3. Lai palaistu programmu, nepieciešams ieslēgt "apache" un datubāžu serveri caur XAMPP
4. Komandu panelī jāpalaiž migrācijas priekš datubāzes.
```sh
  php artisan migrate
  ```

5. Tad divos komandu paneļos atverot programmas direktoriju, ar šīm komandām jāpalaiž laravel un vue.js

```sh
  php artisan serve 
  ```
```sh
  npm run dev
  ```
Kad tas viss izdarīts vietne ir uzstādīta, un to var sākt lietot.



