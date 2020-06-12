# GRABHUB (Food Delivery Website)
A simple food delivery website with database support. Users can order food using Cash on Delivery option or their desired Payment method.
They can view the restaurant details including its location. Our interface will also show the time needed to deliver the customer's food. Once an order is placed they will be assigned a food delivery partner (details will be shared) who will then deliver it to their location.

<p align="center">
   <br><br>
   <b>Welcome Page</b>
  <img src="https://github.com/psil123/GRABHUB/blob/master/resources/images/demo1.JPG" border="0"/>
  <br><br>
   <b>Restaurant List</b>
  <img src="https://github.com/psil123/GRABHUB/blob/master/resources/images/demo2.JPG" border="0"/>
  <br><br>
   <b>Restaurant Menu</b>
  <img src="https://github.com/psil123/GRABHUB/blob/master/resources/images/demo3.JPG" border="0"/>
  <br><br>
   <b>Restaurant Cart</b>
  <img src="https://github.com/psil123/GRABHUB/blob/master/resources/images/demo4.JPG" border="0"/>
  <br><br>
   <b>Administrative Panel</b>
  <img src="https://github.com/psil123/GRABHUB/blob/master/resources/images/demo5.JPG" border="0"/>
</p>

### Prerequisites

Install XAAMP in your pc or host this in an online sever hosting jsp

### Installing

Download and Install Xampp from [here](https://www.apachefriends.org/download.html)

## Deployment

<b>NOTE : </b>You must change all login information in each JSP file (i.e. your username and password in order to connect to your MySQL database).<br><br>
Deployment on a local PC:
*	Copy all the files to a folder called “GRABHUB” under 
*	Copy the folder “GRABHUB” to the "ROOT" folder inside xampp installation directory (The default position of ROOT will be xampp\tomcat\webapps\ROOT)
*	Open XAMPP and start both MySQL and Tomcat 
*	Open a web browser (i.e. Google Chrome or Mozilla Firefox).
*	Visit phpmyadmin using : localhost/phpmyadmin
* Create en empty database "granhub"
* Now execute createDB.jsp using localhost/GRABHUB/createDB.jsp (This will create all the necessary database tables)
* Your Setup is complete
* Visit localhost/GRABHUB/index.html to begin your journey (Signup to create an account and then login)

## Built With

* [JSP](https://en.wikipedia.org/wiki/JavaServer_Pages) - The backend was built using JSP
* [JavaScript](https://www.javascript.com/) - The frontend has been built using Jquery, Bootstrap
* [mapbox API](https://www.mapbox.com/) - For maps
* [Razorpay API](https://razorpay.com/) - As our payment gateway

## Authors

* **Arjya Das** - *Frontend* - [arjya11](https://github.com/arjya11)
* **Koyel Nath** - *Frontend* - [koyelnath98](https://github.com/koyelnath98)
* **Pritam Sil** - *Backend* - [psil123](https://github.com/psil123)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
