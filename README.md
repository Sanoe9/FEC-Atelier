# Atelier - Team Feta

*Project Owners: Salma Noe, Chris Monteilh, Will Casey, and Richard Medina*


## Project Overview
Our goal was to update an outdated client-facing retail web-portal that has been proven to be hurting sales numbers.   This project comprises a complete redesign of the retail portal designed to address this concern and modernize the site.  The following widgets will makeup our user interface which will allow customers to browser our retail catalog - this project will only contain the product detail page, not any other type of page for the site.

### Table of Contents
- [Description](#description)
- [Installation](#installation)

## Description

The product page has been divided into the following 4 modules:

### *Product Overview* - Salma NOE
The Overview module will be the top-most module on the Product Detail page.  The functionality contained within this module can be divided into several pieces:
- Image gallery 
- Product information
- Style selector
- Add to cart

This component will guide the customer through selecting a specific style and size to add to their cart.   As such, portions of the Overview module, such as the image gallery and cart selection, will be specific to a SKU chosen as opposed to the overarching product.

### *Related Products* - Chris MONTEILH
The Related Items & Comparison module will display two sets of related products.  The first set will be a list of products, determined internally, that are related to the product currently being viewed.  The second set will be a list, custom created by the user, of products which the user has grouped with the current product into an ‘outfit’.  
### *Questions and Answers* - Will CASEY
The Questions & Answers module will allow asking and answering of questions for the product selected.  The functionality contained within this module can be divided into several pieces:

- View questions
- Search for a question
- Asking a question
- Answering a question

This component will extend the ability to view and search questions, ask questions, answer questions and provide feedback on questions about the current product. 
All questions will be asked and answered per product.  Specific styles will not be accounted for within the Questions & Answers module.

### *Reviews* - Richard MEDINA
The Ratings & Reviews module will allow viewing and submission of reviews for the product selected.  The functionality contained within this module can be divided into several pieces:

- Write new review
- Reviews List
- Sorting 
- Rating Breakdown
- Product Breakdown

This component will extend the ability to write, read, and browse through reviews for the current product. 
All reviews will be saved per product.  Specific styles will not be accounted for within the review module.

## Installation
- Clone to local machine
- Create .env file from example.env
- Run NPM install to install all necessary dependencies
- Run NPM start to transpile code into bundle.js file
- Run NPM run server to run express server locally
- To view in the browser, go to localhost:4000 in your broswer of choice

## Demo
![Demo](demo.gif)


