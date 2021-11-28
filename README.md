# GirlScript-Hackathon-Basic-Needs-App
The project for the GirlScript Hackathon2k21, concerning a project that will help local people to rise from the loss suffered during covid.

## Steps to Install
Run _git clone [repository link]_ to clone the repository
**The first, third and fourth applications are made using flutter and dart and in order to run teh applications in any android phone, we need to runn the following:**
1. After opening the particular folders, we need to run flutter run after connecting to any device or emulator.

**The second application is made using Reactjs based on JavaScript, we can run the application by following:**
1. Open to the folder
2. Run _npm install_
3. Then run _npm start_

[Website link of Admin Portal](basic-needs-admin-portal.netlify.app)

## Major Application Images(Basic Needs Application)
![Basic Needs Application](https://cdn.discordapp.com/attachments/913788780324991007/914543429453766656/WhatsApp_Image_2021-11-28_at_11.53.30_1.jpeg)

![Products Page](https://cdn.discordapp.com/attachments/913788780324991007/914543429667680276/WhatsApp_Image_2021-11-28_at_11.53.30.jpeg)

## Vendor Side Application(Basic Needs Application)
![Products page Vendor Application](https://cdn.discordapp.com/attachments/913788780324991007/914543429839618088/WhatsApp_Image_2021-11-28_at_11.53.32.jpeg)

![Orders Page Vendor Application](https://cdn.discordapp.com/attachments/913788780324991007/914543430040948796/WhatsApp_Image_2021-11-28_at_11.53.34.jpeg)

## Delivery Boys Application(Basic Needs Application)
![Delivery Boys Orders Page](https://cdn.discordapp.com/attachments/913788780324991007/914543430300999730/WhatsApp_Image_2021-11-28_at_11.53.35.jpeg)

## Admin Portal(Basic Needs Application)
![Admin Portal Banner Page](https://cdn.discordapp.com/attachments/913788780324991007/914541296906018826/WhatsApp_Image_2021-11-28_at_11.57.25.jpeg)

![Vendor List Page](https://cdn.discordapp.com/attachments/913788780324991007/914541297157673031/WhatsApp_Image_2021-11-28_at_11.57.54.jpeg)

![Delivery Boys Information Page](https://cdn.discordapp.com/attachments/913788780324991007/914541297409351680/WhatsApp_Image_2021-11-28_at_11.58.27.jpeg)

![Categories Page](https://cdn.discordapp.com/attachments/913788780324991007/914541297749098566/WhatsApp_Image_2021-11-28_at_11.58.55.jpeg)

![Subcategory for each category](https://cdn.discordapp.com/attachments/913788780324991007/914541298063663114/WhatsApp_Image_2021-11-28_at_11.59.16.jpeg)

**Here firebase is used as a backend service to use the authentication with firestore database.**
_Following is the firestore database link_
![Firestore database](https://cdn.discordapp.com/attachments/913788780324991007/914602791765430362/unknown.png)

## Inspiration
Covid has been a curse to mankind.  It has affected every walk of life, from the education sector to the business sector. The local vendors who were dependent on the daily customers who bought their items from their shops have been affected the most. Small businesses have suffered a lot. So team Technocrats has decided to step up in this hour of need and we have proposed an idea of an application which shall be helpful for both the customers as well as the vendors. "CovMart" shall be the one-stop solution for both the parties as it shall deliver to you the best of the products from the trusted vendors of your locality.

## What it does
"CovMart" shall be the one-stop solution for both the parties as it shall deliver to you the best of the products from the trusted vendors of your locality.

## Need of the application
This app will help the vendors to start their own business with zero investment. During the pandemic, the vendors faced a huge loss from this app they were able to connect with the customer. It uplifted the small scale business and the vendors are also trustworthy from your own locality in this way this app is beneficial for both i.e. for the vendors as well as the customers.

## How we built it
The major languages used here are flutter, ReactJs, and firebase. The project includes 3 android applications and one website. Amongst the 3 apps present in this project we have one major application which is the “Basic Needs App” which serves as the main application of our “CovMart Project”. This application is a customer end application created using flutter, which will be used by the customers to select from the shops present in their locality via GPS location. Then the customers can choose one store and view its products. Then the customer can select category-based items if he or she wants, even the choice of direct selection of items is also available. Then the items can be added to the cart, and after selecting the items, the customer can open the cart, where the option to add more and remove is available, Then the customer can go to the payment options where there are two options one is cash on delivery and other is paying online. The online payment options available are using payment via cards through either Razorpay or stripe.  After the payment, the customer can view the orders in the orders tab. The customer needs to provide his or her delivery address along with the name, contact number, and email id to place an order. Options to change the address or apply coupon codes are also available in this application. This application comes with a vendor-side application where the vendors can register their shops with a name, email id, address, image of the shop, and contact number. Then the vendor can add products by giving them names, categories, stock, brand, and price. Then after adding products the vendor can publish the products once he is convinced that all things are ok. The vendor also has the facility to edit or delete products when wanted. The vendor has the option to create coupons during offers for the customers, which will be valid for a particular period of time. The vendor also has the facility to add his banner for an attractive look to the customers. After the vendor, receives the orders, e can accept or reject them according to his wish. Then the vendor can allocate a delivery boy closest to his place, which notifies the customer at his or her end that the order is accepted. This application is accompanied by the delivery boy application, where the delivery boys can register themselves and once the vendor allocates them an order, the delivery boy can pick it up and then deliver it to the particular location. The options to show his up-gradation is available in this application. If there is a Cash On Delivery on the particular order, the delivery boy is notified to collect the cash from the customer once delivered. Finally, we have the admin portal of this application which is a website made using Reactjs, where the application regulators can add banners for our application, can mark shops as top picked, rated, or even remove in case of bad reviews from the application. The facility to add and remove major and minor categories is available in this application. The facility to approve the delivery boys according to the details available from the delivery boy end is also available in this application. This sums up the entire application. Here we have used firebase as our backend service to regulate the real-time database along with the authentication options available. The major application has a phone number and OTP authentication, the vendor side, and delivery side have authentication via email and password, and the admin side has anonymous login authentication, but for specified users only. All these applications function together making it a complete model best for the upliftment of small-scale business during this pandemic along with the customers receiving best products from their trustworthy vendors starting from food to medicines to other needful stuff.

## Challenges we ran into
The first challenge we faced was to have a bit of research on what were the major points of suffering that the people have suffered during this pandemic. Then the losses suffered by the small businesses came to our notice. We then framed a solution for how this can be solved, which in turn led us to research the working of the large applications in the market. The problems we found led us to work on these applications. The next major problem that we faced during the creation of the application was to have a real-time database to accompany the frontend part of our application. Thus we came up with firebase, the complete solution to all our required services starting from authentication to database. Finally, with much toil, we succeeded in framing the application.

## Accomplishments that we're proud of
We have been successful in making an application that caters to the needs of society. Developing an application of this magnitude is something which we all are proud of at Technocrats. A contribution towards society by helping the upliftment of the small scale businesses at times of crisis is a thing upon which Technocrats takes pride.

## What we learned
The major aspects that we learned during the creation of this application include the frameworks and the languages that we have used in creating this application. This includes flutter majorly for the application building along with dart language, followed by Reactjs as a framework and javascript language. We learned how we can manage our database structure with respect to the creation and maintenance of a business-level project. We also learned how firebase can work as a great technology to be used in the backend of applications starting from small-scale to large-scale applications. We learned how model view control can be inherited as an architecture for the creation of large scalable business-oriented applications.

## What's next for CovMart
Improvisation with respect to the Ui as well as making favorites with respect to products is a feature that can be added, Besides that, the vendor application can be improvised for vendors to edit stuff related to their shops like images, names, etc. The delivery boy application, which is more of a prototype can be improvised to make it a real-world functional application. Once this idea works with the small-scale businesses, we can work to implement it with the large wholesale businesses.

