# javascript-starter
A few simple examples to help you get started using the Clarifai Javascript client and API

## How to get started
Download this repo, simply invoke  
```script
$ npm install
```

## Usage

To get started, create an account at [developer.clarifai.com](http://developer.clarifai.com).

Create an application, and get your API Key.

This basic starter uses your API Key to make prediction calls. This will never expire so you only have to fill it in once.

You'll notice that in the `.gitignore` file, it references a `keys.js` file. This is for security purposes, so you don't share your API Key with others.  Add the following to that file:

```
var myApiKey = 'YOUR API KEY HERE';
```

You'll also notice a custom_train.js file which serves as a reference for Custom Training. Any custom models that you create (under these credentials) will appear in the dropdown menu on index.html, next to the "Custom" label


Edamam API:

After the clarifai AI recognizes the content of the picture and delivers the ingredients, we collect these pieces of information and we store them in variables. Those variables then will be used to feed the Edamam API request that will result in searching for all of the recepies that can be prepared out of these ingredients. After the magic happens, we retrieve the recepies and show them in a gallary of photos for each recepie, along with the calorie count of each meal. 

Once the user decides which meal they prefare, they can click on the image of the meal, then a new browser will open to list the instructions to prepare the recepies, along with full details of the meal nutritional facts. 



