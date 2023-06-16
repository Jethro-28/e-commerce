# E-Commerce

## E-Commerce Setup

```
git clone https://github.com/Jethro-28/e-commerce.git or you can download it

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

![Screenshot 2022-12-19 at 14 33 10](https://user-images.githubusercontent.com/108229029/211271467-926303ac-9e21-4557-bd2e-df781697283f.png)

And **Checkout**

![Screenshot 2022-12-19 at 14 33 32](https://user-images.githubusercontent.com/108229029/211272867-c81d401f-9e37-44e3-bc82-df8407b30247.png)

Connect Mailtrap

Add the details to **.env**

Now run this command to start the project 
```
npm i

npm run dev

php artisan serve
```

You should be good to go!

