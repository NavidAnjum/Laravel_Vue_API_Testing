<p align="center"><b><a href="https://laravelaura.com" target="_blank">Demo APP For Learning Laravel ,Vue , API ,PDF and Excel </a></b></p>

## About  Admin Panel

We've developed this admin panel using laravel and bootstrap:

- Bootstrap based Admin Panel

## 
1.Login
2.PR Creation
3.PO Creation
4.PO Receive
5.Bar Code Genration
6.PDF
7.Report Generation with Laravel Excel

## About API
# Login
Run: 

(1) php artisan tinker 

(2) DB::table('users')->insert(['name'=>'admin','email'=>'thisis@myemail.com','phone_number'=>'123456','password'=>Hash::make('123456')])

(3) DB::table('user_roles')->insert(['user_id'=>1,'role'=>'admin'])

Then you can login where laravel auth used for authentication

# PR Creation
From resources->js->componets->pr-creation.vue has the get and post api for getting the name of type of raw material of cotton and saving the PR creation form.

# PO Creation
From resources->js->componets->po-creation.vue has the get and post api for getting the name of raw material of cotton and saving the PO creation form.

# PO Receive
From resources->js->componets->po-receive.vue has the get and post api for getting the PO and saving the PO receive form.

# Bar Code Genration
URL:http://127.0.0.1:8000/pdf/PO-TSML-1
After receiving the PO a barcode has been generated in pdf

# Report
Developd report with blade and laravel-excel

## License

All rights reserved to <a href="https://laravelaura.com" target="_blank">LaravelAura</a>
