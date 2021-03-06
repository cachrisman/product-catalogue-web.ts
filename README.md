# Product catalogue web application

This is an example application built in Angular2/Typescript. In the default setup the app gets content from the Contentful read-only [Product Catalogue Space Template][5]. Our example applications for [iOS][3] and [Android][4] happen to use the same space template as well.

### What is Contentful
[Contentful][1] is a content management platform for web applications, mobile apps and connected devices. It allows you to create, edit & manage content in the cloud and publish it anywhere via powerful API. Contentful offers tools for managing editorial teams and enabling cooperation between organizations.

![Screenshots of Product Catalogue Web demo App](./src/images/product-catalogue-web-spash.png?raw=true "Screenshots")



## Live Demo
The real benefit of the app is the capability to connect it to any space which uses the [Product Catalogue Space Template][5]. Once the app is connected to a user-controlled version of the [Product Catalogue Space Template][5], all changes to the space in [the Contentful UI][6] will be reflected in the app.

1. Prepare a Contentful demo space
    - Create a new space in https://app.contentful.com
    - **IMPORTANT**: make sure to create it from the [Product Catalogue Space Template][5]
2. Connect the space to the demo application
    - Open the hosted version of the demo application [https://contentful-labs.github.com/product-catalogue-web.ts][7]
    - Open settings
    - Paste in your API key and space ID
    - Save session and/or save the deep link for your convenience
    - **Optional**: bookmark the deep link for later usage


![Screenshots of Product Catalogue Web demo App](./src/images/product-catalogue-web-editing.png?raw=true "Contentful in action")

##Local Deployment

- Clone or fork this repository
- run `npm install` to install dependencies
- run `npm start` to fire up dev server
- open browser to `http://localhost:8080`


###Links


There are other implementations of the product catalogue demo available for iOS and Android 

[Product Catalogue for iOS][3]
[Product Catalogue for Andorid][4]

###License


Copyright (c) 2015 Contentful GmbH. Code released under the MIT license. See [LICENSE][2] for further details.
 
###Disclaimer / Maintenance

This is a project created for demo purposes and not officially supported. Report problems via the issues page but please don't expect a quick and prompt response.

 [1]: https://www.contentful.com
 [2]: LICENSE
 [3]: https://github.com/contentful/product-catalogue-ios
 [4]: https://github.com/contentful/product-catalogue-android
 [5]: https://www.contentful.com/blog/2015/01/30/introducing-space-templates/
 [6]: https://app.contentful.com
 [7]: https://contentful-labs.github.com/product-catalogue-web.ts
