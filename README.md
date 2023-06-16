## E-Commerce Setup

git clone https://github.com/Jethro-28/e-commerce.git 
or you can download it

composer install 

cp .env.example .env 

php artisan key:generate
```

Create the DB
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=e_commerce
DB_USERNAME=root
DB_PASSWORD=
```
Now migrate your DB
```
php artisan migrate

php artisan db:seed
```
Now go to https://stripe.com/en-gb-us

Create a public and private KEY.

Add your new PRIVATE API KEY to **CheckoutController.php**

![Screenshot 2023-06-16 134914.png](<Screenshot 2023-06-16 134914.png>)

And **Checkout**

![Screenshot 2023-06-16 135733.png](<Screenshot 2023-06-16 135733.png>)

Screenshot 2023-06-16 135733.png

Add the details to **.env**

Add the details to **.env**
```
npm i

npm run dev

php artisan serve

You should be good to go!
```
