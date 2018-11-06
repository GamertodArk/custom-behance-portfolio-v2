# Custom behance portfolio (improved)

This is a custom behance portfolio built with NodeJS. I have another custom behance portfolio where you can check it [here](https://github.com/GamertodArk/custom-behance-portfolio), this version is improved in the code structure, security and the FrontEnd

## Some important updates

- The App Key is not in the FrontEnd
- The call to the Behance API ara called from the BackEnd
- The projects are shown 3 in a row

## How to install 

Run this line

```
git clone git@github.com:GamertodArk/custom-behance-portfolio-v2.git
```

Then create a new file called `.env` and add the following data
```
APP_PORT=<port for the app>

BEHANCE_API_KEY=<behance api key>
BEHANCE_USER_ID=<behance user id>
BEHANCE_PER_PAGE=<the max number of project shown>
``` 
Now install the dependencies

```
npm install
```

And run the app
```
node app.js
```