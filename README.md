# <div align="center">BidBay</div>
link to website = https://bidbay.vercel.app

<div align="center">
  <img src= "https://github.com/Rahul21sai/BidBay_mern/assets/110412514/7917bacb-a93f-4985-8c88-c7fd4d421adb"
/>

  ![image](https://github.com/Rahul21sai/BID_BAY/assets/110412514/23c897d5-9708-40e9-a250-b3ebd3757d9a)

  ![image](https://github.com/Rahul21sai/BID_BAY/assets/110412514/50bd7a34-cb1d-45c5-8e06-b19b8b07f6af)

  ![image](https://github.com/Rahul21sai/BID_BAY/assets/110412514/475e3cfa-cc7e-4a8b-97dc-7554f528d2fd)

  ![image](https://github.com/Rahul21sai/BID_BAY/assets/110412514/ab6c119b-812f-44bb-be20-cf5058605e3f)

  ![image](https://github.com/Rahul21sai/BID_BAY/assets/110412514/2a2e5cca-5928-4f2c-94e2-7fa1cbe9dce3)





</div>

<br/>

<p>
An innovative and comprehensive e-commerce website with a unique twist—an integrated auction house! This project, developed using the popular MERN stack, provides a glimpse into the dynamic world of ecommerce and auctions. Designed with a focus on functionality and user-friendliness, this website carries to the needs of both buyers and sellers, offering a seamless experience for all. <br/>

Featuring a multi-user system, our platform accommodates admins, sellers, and buyers, each with their dedicated sections. This ensures that interactions and transactions occur effortlessly, contributing to a smooth and efficient experience across roles. <br/>

The project showcases a diverse range of products spanning electronics, clothing, home goods, accessories, and more. The integration of an auction house introduces an element of excitement, allowing users to bid on their favorite items and potentially secure great deals. <br/>

To guarantee secure transactions, we've implemented an integrated payment method through PayPal. Our additional verification headers add an extra layer of security, prioritizing the protection of user personal information throughout their online journey. <br/>

Emphasizing a user-centric design and a robust set of features, our web application stands as a testament to the capabilities of modern web development. Explore the functionalities and dynamics of online shopping and auctions with our project.

</p>

## Features

- Interactive home page displaying products in a card view

- React context API for cart data, user data, shipping address, and payment method selection

- Search page for searching, sorting, and filtering products

- PayPal payment gateway integration

- Cloudinary integration for storing and using images

- Axios for promise-based HTTP API requests

- Google Charts for creating charts and graphs

- Tailwind CSS for building custom designs with minimal CSS code

- Font Awesome for customizable icons

- Local Storage API for storing key/value pairs in a web browser

- Multi-vendor support for Users, Sellers, and Admin

- Real-time bidding system using socket.io

- Product management features for Admin and Seller (add, delete, etc.)

- User authentication and profile editing

- Express Async Handler, JSON Web Tokens, Bcrypt JS, CORS, and Dot Env for backend security

- Pagination for user-friendly interface

<br/>

## Project Live On

<a href="">vercel</a>
<br/>


## Technology Used

<div align="center">  
<a href="https://reactjs.org/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/react-original-wordmark.svg" alt="React" height="50" /></a>  
<a href="https://www.w3schools.com/css/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/css3-original-wordmark.svg" alt="CSS3" height="50" /></a>  
<a href="https://en.wikipedia.org/wiki/HTML5" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/html5-original-wordmark.svg" alt="HTML5" height="50" /></a>  
<a href="https://www.javascript.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/javascript-original.svg" alt="JavaScript" height="50" /></a>  
<a href="https://nodejs.org/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/nodejs-original-wordmark.svg" alt="Node.js" height="50" /></a>  
<a href="https://expressjs.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/express-original-wordmark.svg" alt="Express.js" height="50" /></a>  
<a href="https://github.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/git-scm-icon.svg" alt="Git" height="50" /></a>  
<a href="http://tailwindcss.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/tailwindcss.svg" alt="Tailwind" height="50" /></a>  
<a href="http://mongodb.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/mongodb-original-wordmark.svg" alt="MongoDB" height="50" /></a>  
</div>

<br/>

## Commands

### Backend

```bash
$ npm install
```

Installs all the required packages for backend

```bash
$ npm start
```

Starts the server using nodemon

## Frontend

```bash
$ npm install
```

Installs all the required packages for frontend

```bash
$ npm start
```

Runs frontend on localhost(React App)

```bash
$ npm run build
```

Creates an optimized production build

<br/>

## Folder Structure

```
EcomBidding/
├── backend/
│   ├── models/
│   │   ├── auctionModel.js
│   │   ├── orderModel.js
│   │   ├── productModel.js
│   │   └── userModel.js
│   ├── routes/
│   │   ├── auctionRoutes.js
│   │   ├── orderRoutes.js
│   │   ├── productRoutes.js
│   │   ├── seedRoutes.js
│   │   ├── uploadRoutes.js
│   │   └── userRoutes.js
│   ├── .env
│   ├── index.js
│   └── utils.js
├── frontend/
│   ├── public/
│   │   ├── favicon.png
│   │   └── index.html
│   ├── src/
│   │   ├── Components/
│   │   │   ├── AdminRoute/
│   │   │   │   └── AdminRoute.js
│   │   │   ├── AuctionItem/
│   │   │   │   └── AuctionItem.js
│   │   │   ├── Categories/
│   │   │   │   ├── Categories.css
│   │   │   │   └── Categories.js
│   │   │   ├── CheckoutSteps/
│   │   │   │   └── CheckoutSteps.js
│   │   │   ├── ErrorPage/
│   │   │   │   ├── ErrorPage.css
│   │   │   │   └── ErrorPage.js
│   │   │   ├── Loading/
│   │   │   │   └── Loading.js
│   │   │   ├── LoadingDots/
│   │   │   │   ├── LoadingDots.css
│   │   │   │   └── LoadingDots.js
│   │   │   ├── Product/
│   │   │   │   └── Product.js
│   │   │   ├── ProtectedRoute/
│   │   │   │   └── ProtectedRoute.js
│   │   │   ├── Rating/
│   │   │   │   └── Rating.js
│   │   │   └── SellerRoute/
│   │   │       └── SellerRoute.js
│   │   ├── Pages/
│   │   │   ├── AddressPage/
│   │   │   │   ├── AddressPage.css
│   │   │   │   └── AddressPage.js
│   │   │   ├── Auction/
│   │   │   │   ├── Auction.css
│   │   │   │   └── Auction.js
│   │   │   ├── AuctionDetails/
│   │   │   │   ├── AuctionDetail.css
│   │   │   │   └── AuctionDetail.js
│   │   │   ├── CartPage/
│   │   │   │   ├── CartPage.css
│   │   │   │   └── CartPage.js
│   │   │   ├── CreateAuction/
│   │   │   │   ├── CreateAuction.css
│   │   │   │   └── CreateAuction.js
│   │   │   ├── Dashboard/
│   │   │   │   ├── Dashboard.css
│   │   │   │   └── Dashboard.js
│   │   │   ├── Footer/
│   │   │   │   └── Footer.js
│   │   │   ├── Header/
│   │   │   │   └── Header.js
│   │   │   ├── Home/
│   │   │   │   ├── Home.css
│   │   │   │   └── Home.js
│   │   │   ├── OrderHistory/
│   │   │   │   ├── OrderHistory.css
│   │   │   │   └── OrderHistory.js
│   │   │   ├── OrderListPage/
│   │   │   │   ├── OrderListPage.css
│   │   │   │   └── OrderListPage.js
│   │   │   ├── OrderPage/
│   │   │   │   ├── OrderPage.css
│   │   │   │   └── OrderPage.js
│   │   │   ├── PaymentMethod/
│   │   │   │   ├── PaymentMethod.css
│   │   │   │   └── PaymentMethod.js
│   │   │   ├── PlaceOrder/
│   │   │   │   ├── PlaceOrder.css
│   │   │   │   └── PlaceOrder.js
│   │   │   ├── ProductEditPage/
│   │   │   │   ├── ProductEditPage.css
│   │   │   │   └── ProductEditPage.js
│   │   │   ├── ProductListPage/
│   │   │   │   ├── ProductListPage.css
│   │   │   │   └── ProductListPage.js
│   │   │   ├── ProfilePage/
│   │   │   │   ├── ProfilePage.css
│   │   │   │   └── ProfilePage.js
│   │   │   ├── SearchPage/
│   │   │   │   └── SearchPage.js
│   │   │   ├── SignIn/
│   │   │   │   ├── Assets/
│   │   │   │   │   ├── avatar.svg
│   │   │   │   │   ├── unlock.svg
│   │   │   │   │   └── wave.png
│   │   │   │   └── SignIn.js
│   │   │   ├── SignUp/
│   │   │   │   ├── Assets/
│   │   │   │   │   ├── avatar.svg
│   │   │   │   │   ├── unlock.svg
│   │   │   │   │   └── wave.png
│   │   │   │   └── SignUp.js
│   │   │   ├── UserEditPage/
│   │   │   │   ├── UserEditPage.css
│   │   │   │   └── UserEditPage.js
│   │   │   └── UserListPage/
│   │   │       ├── UserListPage.css
│   │   │       └── UserListPage.js
│   │   ├── App.css
│   │   ├── App.js
│   │   ├── index.css
│   │   ├── index.js
│   │   ├── Store.js
│   │   └── utils.js
│   ├── .env
│   └── tailwind.config.js
├── .gitignore
└── README.md
```
# Bidbay
# Bidbay
