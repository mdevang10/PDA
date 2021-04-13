# RasodaHouse
<div style="display : flex; justify-content : center; flex-direction : column; align-items : center">
<img src="https://rasodahouse.me/static/media/FooterLogo.515c047e.png"  width="200">
<br/>
<a href="www.rasodahouse.me" target="_blank">www.rasodahouse.me</a>
<br/>
</div>

RasodaHouse is a food ordering website that enables users to order fresh and home-cooked food. 
The website has below mentioned features
* User Profile.
* Menu Card along with their prices.
* Order placing and tracking with the help of order status.
* View past orders.
* Review and rate the dish right from your orders or by viewing more information on the dish.
* View reviews and ratings by other customers on the dish.

# Architecture Diagram
<img src="https://res.cloudinary.com/mdevang10/image/upload/v1618332384/Architecture_mxrujv.png">

### <a href="https://github.com/mdevang10/rasodahouse-backend" target="_blank"> Rasoda House Backend</a>
### <a href="https://github.com/mdevang10/rasoda-house-admin-mobile-app" target="_blank"> Rasoda House Admin Mobile App</a>

# Tech stack 
- React JS 
    - Used to build light weight components making use of out of the box  features like react-router, context API,react hooks etc.
- Strapi  
    - Simple Headless CMS with out of the box CRUD operaion API exposed along with user Authentication requiring minimal setup efforts.
- Postgress 
    - Strapi and postgress goes hand in hand and strapi provide great support out of box for Postgress database.
- Cloudinary  
    - Since the website is image heavy cloudinary have been used as CDN to reduce the image load time as well as server space.
- Ionic 
    - Since website is written in react and ionic supports react component, code sharing between front-end and mobile app was easier.

# Libraries Used

* formik
    - Used for form validation that included both field level and form level validations.
* axios
    -  Used to call the backend API.
* react-moment
    - Used for date time formating.
* react-star-rating-component
    - Used a pre built Star rating component in rating the dish.
* react-toast-notifications
    - Used to show Toast Notifications to User while adding/removing dishes to/from cart.
* react-bootstrap 
    - With bootstrap at its core and lots of UI components exposed out od the box it enables us to take advanted and build response UI faster.
* react-icons 
    - A great library for widely used icons.

# Screenshots 
### Home Page
<img src="https://res.cloudinary.com/mdevang10/image/upload/v1618307840/HomePage_sgswrl.png" style="width:800px">

# <br>

### Dishes Page
<img src="https://res.cloudinary.com/mdevang10/image/upload/v1618307823/DishesPage_u7mw1v.png" style="width:800px">

# <br>

### Login Sign Up Page
<img src="https://res.cloudinary.com/mdevang10/image/upload/v1618307831/Login-SignUp_vyrzpd.png" style="width:800px">

# <br>

### User Address Profile Page
<img src="https://res.cloudinary.com/mdevang10/image/upload/v1618307823/UserProfile_Address_qxxq38.png" style="width:800px">

# <br>

### Cart Page
<img src="https://res.cloudinary.com/mdevang10/image/upload/v1618307829/CartPage_qqlemj.png" style="width:800px">

# <br>

### Checkout Page
<img src="https://res.cloudinary.com/mdevang10/image/upload/v1618307838/CheckOut_xqyhje.png" style="width:800px">

# <br>

### Orders Page
<img src="https://res.cloudinary.com/mdevang10/image/upload/v1618307828/Orders_necvnb.png" style="width:800px">

# Getting started

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
