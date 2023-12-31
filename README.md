<br/>
<p align="center">
  <a href="https://github.com/AyushManiSharma/Happy-Feet-Deals">
    <img src="https://png.pngtree.com/template/20191203/ourmid/pngtree-shoes-design-logo-vector-image_337938.jpg" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Happy-Feet-Deals</h3>

  <p align="center">
    Explore beyond comfort! 
    <br/>
    <br/>
    <a href="https://github.com/AyushManiSharma/Happy-Feet-Deals"><strong>Explore the docs »</strong></a>
    <br/>
    <br/>
    <a href="https://github.com/AyushManiSharma/Happy-Feet-Deals">View Demo</a>
    .
    <a href="https://github.com/AyushManiSharma/Happy-Feet-Deals/issues">Report Bug</a>
    .
    <a href="https://github.com/AyushManiSharma/Happy-Feet-Deals/issues">Request Feature</a>
  </p>
</p>

![Downloads](https://img.shields.io/github/downloads/AyushManiSharma/Happy-Feet-Deals/total) ![Contributors](https://img.shields.io/github/contributors/AyushManiSharma/Happy-Feet-Deals?color=dark-green) ![Forks](https://img.shields.io/github/forks/AyushManiSharma/Happy-Feet-Deals?style=social) ![Stargazers](https://img.shields.io/github/stars/AyushManiSharma/Happy-Feet-Deals?style=social) ![Issues](https://img.shields.io/github/issues/AyushManiSharma/Happy-Feet-Deals) ![License](https://img.shields.io/github/license/AyushManiSharma/Happy-Feet-Deals) 

## Table Of Contents

* [About the Project](#about-the-project)
* [Built With](#built-with)
* [License](#license)
* [Authors](#authors)

## About The Project

![Screen Shot](https://cdn.discordapp.com/attachments/1161753809719152824/1162191360531644436/image.png?ex=653b0a0c&is=6528950c&hm=67b60731e961539921c41a8bca6829e3edc263b2881be468140620c2712cce49&)

Happy Feet Deals is an online platform dedicated to the retail of footwear. Customers have the option to establish an account, sign in, and peruse the website's extensive inventory to identify their preferred shoe selections. Upon making a decision, they can conveniently add their chosen items to their shopping cart and proceed with the purchase.

## Built With

- Express
- React
- Node
- Stripe
- Apollo
- JWT
- Mongoose

## License

Distributed under the MIT License.

## Authors

* **Ayush Sharma** - *Back-End* - [Ayush Sharma](https://github.com/AyushManiSharma) - *server/config, server/server.js, client/components*
* **Anvar Ganiev** - *Font-End* - [Anvar Ganiev](https://github.com/99Anvar99) - *client/public, client/app.js, index.js, index.css, serviceworker.js*
* **Michael Oloruntoba** - *Front-Back Ends* - [Michael Oloruntoba](https://github.com/MichaelToba) - *server/utils, client/pages, client/utils*
* **Hung Quoc Dang** - *Back-End* - [Hung Quoc Dang](https://github.com/HungQuocDang) - *server/models, server/schemas*

## links

Here is the Heroku link https://shielded-harbor-32787-11953ac1c80a.herokuapp.com/  

It works until after the payment is processed with message “cannot get/ success”, perhaps stripe is used for working in a browser and not for Heroku, probably related to severed security of the transaction.

After cloning from https://github.com/AyushManiSharma/Happy-Feet-Deals.git , do npm i, npm run seed which will seed the database in MongoDB Atlas, and not to the MongoDB Compass, at mongodb+srv://Hung1:Test1234@cluster0.xpplqfx.mongodb.net/happyfeet-shoppinga?retryWrites=true&w=majorit

Then by npm run develop, the localhost:3000 will open, where one can open http://localhost:3001/graphql and insomnia to add users to the database on the cloud that allow to login with those added users’ credentials to buy shoes at checkout with Stripe with no issues.  And the MongoDB Compass will have no affectations at all.

When clicking the Heroku link https://shielded-harbor-32787-11953ac1c80a.herokuapp.com/  and due to npm run seed and previously affecting the cloud database from localhost:3000 ,  http://localhost:3001/graphql and insomnia ; the app allows to do sign up many new users with no issues, but until after the payment is processed with message “cannot get/ success”, perhaps stripe is used for working in a browser and not for Heroku, probably related to severed security of the transaction.

Heroku link:       

https://shielded-harbor-32787-11953ac1c80a.herokuapp.com/ 

GitHub link:      

https://github.com/AyushManiSharma/Happy-Feet-Deals 

GitHub deployment link:               https://ayushmanisharma.github.io/Happy-Feet-Deals/ 

 

My GitHub profile : https://github.com/HungQuocDang 

My GitHub link to Project-3:  https://github.com/HungQuocDang/Project-3 

