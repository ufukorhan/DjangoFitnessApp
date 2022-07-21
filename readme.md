# Best Fitness

In this Django project, i am building a membership site that is able to share content with users and collect payments. This project covers setting up the checkout for the site, managing users, configuring access controls, and releasing premium content to subscribers.

* Using APIs
* Leveraging the Stripe dashboard
* Building a checkout page
* Configuring payment periods
* Working with the Stripe frontend
* Handling data
* Implementing a coupon system
* Processing payments
* Analyzing Stripe data
* Creating user models
* Allowing for subscription cancellations


![image](https://user-images.githubusercontent.com/91383831/180262640-209ee634-4ae5-43f4-b6c4-896a6edb7cab.png)
![image](https://user-images.githubusercontent.com/91383831/180262720-161fe5f3-c8b4-42bc-be1c-bfa15a99b63d.png)
![image](https://user-images.githubusercontent.com/91383831/180262897-c3e71884-fba3-44d1-92c5-7bf81302e695.png)
![image](https://user-images.githubusercontent.com/91383831/180263292-432be9b6-42d2-4276-b70e-854cf8decbf1.png)
![image](https://user-images.githubusercontent.com/91383831/180263342-ec4b705e-fa6b-4fa7-a6b8-f5b60a49d148.png)
![image](https://user-images.githubusercontent.com/91383831/180263543-6eb92856-d76d-451e-acdc-d316f35d0cf2.png)

You can manage your customers info and more from stripe dashboard.
![image](https://user-images.githubusercontent.com/91383831/180299828-1fa0766c-4c15-4739-9513-09abac3a6e48.png)




## Getting Started

### Installing

Open your terminal screen and clone the project from the Github to your computer.
```
git clone https://github.com/ufukorhnn/DjangoFitnessApp.git
```
Then open your cloned project from github

### Dependencies

* In the project directory you need to create a new virtualenv and activate it. (If pip3 gives an error you can try pip)
```
pip3 install virtualenv
```
```
virtualenv venv
```
```
source venv/bin/activate
```
After that you can install packages in requirements.txt with this code.
```
pip3 install -r requirements.txt
```

### Executing program

```
cd fitness_app
```
```
python3 manage.py migrate
```
```
python3 manage.py loaddata plans.json
```
```
python3 manage.py runserver
```

After these all steps you can start development server.

## Note

If you have any problem with the api key you have to create a stripe account (taking 2 min.) then use api key.
![image](https://user-images.githubusercontent.com/91383831/180306947-539f9d49-e796-441e-bc76-b3e3a42c82c5.png)

You can use this key in views.py
![image](https://user-images.githubusercontent.com/91383831/180307473-4541cc68-7139-416a-95ee-7942d45fd054.png)

Also in view.py you need to use plan id for yearly and monthly
![image](https://user-images.githubusercontent.com/91383831/180307781-c351d862-a91b-4fc9-a1a2-6c828bc0abb6.png)
![image](https://user-images.githubusercontent.com/91383831/180308573-b77a8290-ffee-41fa-80b4-7ac1e07eca08.png)

## Finally

If you need fake credit card number, you can use 4242424242424242 or 5555555555554444 and the other spaces does not matter. In the upper right, there is more fake information.
![image](https://user-images.githubusercontent.com/91383831/180309684-7312a7c2-a36c-4339-bdf6-e931de087822.png)

* If you would you like to detais of customers, plans and more you have to use https://dashboard.stripe.com/ 
