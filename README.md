# Semester Project 2022 - Shoe Store

![image](https://rebekkarustad.netlify.app/images/shoe-store.png)

Semester project from spring 2022. We were to create an e-commerce website with both customer-facing and admin sections.

## Description

I have built an e-commerce website for a shoe store. The logo is simple and made by me for this project.

The website has a customer-facing section that includes:

- Home - Includes a hero banner from Strapi and a list of featured products.
- Product list - The list is from Strapi, and the page includes a functional search text box.
- Product detail - This is seen when you click on the products with all the details of each product.
- Cart pages - When adding a product to the cart, it ends up here.

And it also has an admin section that includes:

- Login page - You can log in with the credentials from Strapi. You will be kept logged in through local storage.
- Create products - You can create a new product when logged in.
- Update products - When logged in, you can update all products.
- Delete products - When logged in, you can delete all products.

The website is responsive on all devices.

## Built With

- [Sass](https://sass-lang.com/)
- [FontAwesome](https://fontawesome.com/)
- [Strapi](https://strapi.io/)
- [Bootstrap](https://getbootstrap.com)

## Getting Started

### Installing

1. Clone the repo:

```bash
git clone git@github.com:rebekkarustad/semester-project-2022
```

2. Deploy locally

For the website to work, you will have to run this Strapi project locally.

```bash
git clone git@github.com:NoroffFEU/strapi-sp2
npm install
npm run develop
```

User credentials:

```bash
email: admin@admin.com
username: admin
password: Pass1234
```

3. Make sure you have "Live Server" installed

[Install Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

4. Open with Live Server
