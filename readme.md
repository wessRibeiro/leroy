### How to install (use sudo if you need)
```
* chmod 777 -R storage
* chmod 777 -R bootstrap/cache;
* composer install
* cp .env.example .env (if haven't)
* php artisan key:generate
* php artisan migrate
```

### CODE DESCRIPTION
````
| 200  | OK            | 
| 201  | Created       | 
| 204  | Deleted       | 
| 400  | Bad Request   | 
| 401  | Unauthorized  |
| 404  | Page not found|
| 500  | Server Error  |
````

### About
this code have:
````
* queue
* tdd
* mockery
* rest
* json
````
endpoint's:
````
* products (manage products)
* files/history (show files history)
````
### Flow code:
route -> controller -> service -> model

### File to test:
products_teste.xlsx (into te repo)