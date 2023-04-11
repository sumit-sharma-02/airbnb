<h1 align="center">Airbnb</h1> 

<h2 align="center">A Full Stack Airbnb Clone Application </h2>

<br />
<p align="center">
    <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Nextjs" />
    <img src="https://img.shields.io/badge/React.js-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="Reactjs" />
    <img src="https://img.shields.io/badge/MongoDB-339933?style=for-the-badge&logo=mongodb&logoColor=white" alt="Mongodb" />
    <img src="https://img.shields.io/badge/Prisma-5A67D8?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma" />
    <img src="https://img.shields.io/badge/Leaflet-green?style=for-the-badge&logo=leaflet&logoColor=white" alt="Leaflet" />
    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind" />
    <img src="https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary-css&logoColor=white" alt="Cloudinary" />
</p>

<p align="center"> 
    <br />&#10023;
    <a href="#Quick-Start">Quick Start</a>   &#10023;    
    <a href="https://github.com/sumit-sharma-02/airbnb/issues">Report Bug</a>   &#10023;
    <a href="#Contact">Author</a>&#10023;
  </p>
  
  <h3 align="center"><a href="https://rental-hotels.vercel.app/"><strong>« Try the demo here »</strong></a></h3>

<p align="center"> 
    Airbnb is an online marketplace that connects people who want to rent out their homes with people who are looking for accommodations in specific locales. Airbnb offers people an easy, relatively stress-free way to earn some income from their property.
</p>

![airbnb-poster](https://user-images.githubusercontent.com/52236473/231196090-648f81df-9805-4714-a300-41092dad5561.png)
<br />

## 🚀 Features
- Fully Responsive
- Credential Authentication
- Google Authentication
- Github Authentication
- Property Listing
- Booking / Reservation System
- Guest Reservation Cancellation
- Owner Reservation Cancellation
- Creation and Deletion of Properties
- Search by Category, Date Range, Map Location, Number of Guests, Rooms and Bathrooms
- Add Favorites
- Shareable URL filters
<br />

## Some Screenshots of Airbnb:
<table>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/52236473/231175742-9c093b0c-6209-43d8-afa8-bc624a3e9c1c.png" alt="home" /></td>
    <td><img src="https://user-images.githubusercontent.com/52236473/231176262-9a917bb9-a9cc-416e-8f53-2750a5ecfc58.png" alt="listing" /></td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/52236473/231177066-a6cd7c95-bf24-4fb9-a0fc-9a025e82de8c.png" alt="properties" /></td>
    <td><img src="https://user-images.githubusercontent.com/52236473/231177497-2b262e92-23f1-4406-a043-0c68759bb4d7.png" alt="home" /></td>
  </tr>
</table>
<br/>

## Quick Start

```shell
$ git clone https://github.com/sumit-sharma-02/airbnb.git
$ cd airbnb
$ npm install
```

### Env Variables

Add your config variables values in the .env file which will be in the root directory.

```js
DATABASE_URL = Go to mongodb atlas website -> login -> create database -> free -> add you username, pass -> finish -> connect -> connect with VS Code -> Copy the link paste here in the .env file -> replace <password> with the password you added while creating

NEXTAUTH_SECRET = 'NEXTAUTH_SECRET'

GOOGLE_CLIENT_ID = go to "https://console.cloud.google.com/getting-started" -> create a new project -> once project is created search api in searchbar -> go to Enabled APIs and services -> OAuth consent screen -> external -> create -> fill mandatory fields with you name and emailid -> continue X3. Now go to credentials on the left -> create credentials -> create OAuth Client ID -> application type - web application -> Add "http://localhost:3000/api/auth/callback/google" in the Authorized redirect URIs -> create -> Copy ClientID and paste it here in the .env file.

GOOGLE_CLIENT_SECRET = Copy Client Secret and paste it here in the .env file.

GITHUB_ID = Go to your github -> settings -> developer settings -> OAuth Apps -> Add new -> Add "http://localhost:3000" in homepage and authorization callback url -> generate -> copy paste client id here in .env file.

GITHUB_SECRET = Continuing above step below client id click on generate client secret and paste in here in the .env file.

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME = Go to Cloudinary website -> Login -> Dashboard -> copy the cloud name and paste it here in the .env file.
```

### Setup Prisma

```shell
npx prisma db push

```

### Start the app

```shell
npm run dev
```


## Contact
If you want to contact me, you can reach me through below handles.

[![linkedin](https://img.shields.io/badge/Sumit_Sharma-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sumitsharma002/)
[![Github](https://img.shields.io/badge/Sumit_Sharma-20232A?style=for-the-badge&logo=Github&logoColor=white)](https://github.com/sumit-sharma-02/)

## Show your support

Give it a ⭐️ if you like it.

