# Project 4 Planning

## Team

- Mindy Marmol
- Rixio Barrios
- Qusai Fares
- Sage Kearney

## About

Food waste is a real problem in our society. In the United States, 40% of all food gets wasted.
For Food's Sake is an app made to alleviate some of that waste from those farms, markets, restaurants and homes.

## User Stories

### Who will use it?

- Proactive millenials conscious about environment etc.

#### Seller:

- Farms/market/restaurant with food waste

##### Reasons to use:

- Extra cash
- Environment

#### Buyer:

- Proactive millenials conscious about environment etc who isn't afraid of getting food second-hand.

##### Reasons to use:

- Cheap food
- Environment

## MVP

**Bronze version**

- [ ]


### Functionality

#### Buyer

- Login
- Search by type of food, type of vendor, location near you, vendor name.
- Select listing and process transaction
- Recieve confirmation with scheduled time and place

* Fields: Name, email address, phone number, address, past transactions (Gold).
* Home page contains postings made around your location

#### Seller

- Fields: Name, organization name, email address, phone number, address, past transactions (Gold).

### Tech

- PayPal
- Google Maps

### Why we chose this app???

`To make it easy for lazy ass people to participate in protecting the environment`
-Mindy Marmol 2020

`I feel the app is a call to action`
-Rixio Barrios 2020

`I'm hoping one day I can make a shit ton of money off this`
-Qusai Fares 2020

`The more resources people have to make a difference, the easier it is to make a difference. DIFFERENCE`
-Sage Kearney 2020

`To create an app that is a driving force for change, where people who are conscious about their impact can come together.`
-Mindy Marmol 2020


```PY
def food_listing(request):
    listings = Listing.objects.all()
    return # Response generate by our API
```
