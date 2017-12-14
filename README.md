# RegistrationWithImageScrapper
Express Login with JSONWebToken

### Login And Registration page with Express,Mongoose,Image-Scraper

1. This Application is using the JSONwebToken Authentication for login and each and every res is handled with tokens,
2. Using Image Scraper to get the Scraped images,
3. Using JIMP for cropping the images of 50*50, 
4. This images to be stored at the cloud Mlab MongoDB.
5. Get the Stored images and display the images at the Screen.
6. Test cases is handling through the mocha nyc.

## installation Process

#Installing packages

npm install

npm install --save--dev--nyc

#starting the process

npm start

#Testing the test Cases

npm test

###Usage

This applicaiton is used as image search engine.
while searching the by image name, it will fetch the top of the image search at google,
 crop it through JIMP api and download to database. 

## License

This application is a open source MIT license any one can use it for their project and other resources.


