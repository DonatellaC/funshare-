# funshare®

funshare® is an app to virtually connect boardgame lovers and allow them to meet and play in the real world! 🎲🃏

## 🍀 Getting started

- Install mongoDB
- In app.js there is connection set up using mongoose and funshare collection is created

## 🍀 Dependencies

1. Run `yarn install` in project directory to install Express.`yarn start` to run servers on port 5001
2. `cd client` and `yarn install` to install React. `yarn start` to run servers on port 3000.

## 🍀 API

Create a `.env` file

- visit https://opencagedata.com/, register and create your own API key
- create a variable REACT*APP_OCD_API_KEY=*\*\* and replace the \_ with your own key

## 🍀 User Flow Diagram

![User Flow Diagram](images/userFlowFunshare.png)

## 🍀 User Flow in Pictures

Sign In form

![funshare ](images/funshare_home1.png)

About funshare®

![funshare ](images/funshare_about.png)

Registration form

![funshare ](images/funshare_register.png)

Filter for other players

![funshare ](images/funshare_dashboard.png)

Player's profile

![funshare ](images/funshare_profile.png)

The player can add/delete her/his games

![funshare ](images/funshare_mygames.png)

Add fun games events

![funshare ](images/funshare_createevent.png)

## 🍀 Database schema

![User Schema](images/UserSchema.png)

![Event Schema](images/EventSchema.png)

## 🍀 API routes plan

![User Get](images/usersGet.png)
![User Id Get](images/usersIdGet.png)
![User Category Get](images/usersCategoryGet.png)
![User City Get](images/usersCityGet.png)
![User Filter Get](images/usersFilterGet.png)
![User Auth Post](images/usersAuthPost.png)
![User Add Post](images/usersAddPost.png)
![User Id Patch](images/usersIdPatch.png)
![User Id Delete](images/usersIdDelete.png)
![Events](images/events.png)

## 🍀 Used technologies

For authentication:

- Passport
- bcrypt
- JWT

### Frontend

- React
- React Router
- Bootstrap - styling
- Axios
- Leaflet - library for interactive map

### Backend

- Express - to create server and API routes
- Node.js - to run the server
- mongoose - communicate with mongoDb

### Database

- mongoDB

## 🍀 Future features

- Deploy on Heroku
- User communication, direct messages or chat
- User can add avatar
- Geospatial data to find users in specific location/radious
- Using API for game recognition
- User can add event and it's saved to their DB Schema
- Map to show events from DB
- Recommended places friendly for playing boardgames
- Forum where people can ask questions
