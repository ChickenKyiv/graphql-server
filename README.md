# graphql-server


static data: imported from @groceristar/groceristar-fetch plugin
More about this plugin [here](https://medium.com/groceristar/groceristar-fetch-small-module-that-weve-created-8b4a62bd5d7b)


database(we'll use it later):
```
"recipeDS": {
"url": "mongodb://heroku_p0dxgncb:gl2rr2bi235aoqfdojelqspjn1@ds147052.mlab.com:47052/heroku_p0dxgncb"
}

```

this is our database schema
![schema](https://github.com/ChickenKyiv/database-visuals/blob/master/Recipe-ChickenKyiv-Release%231%20Schema%20%20%20SqlDBM.png)


this is our separated server, but his main logic is similar - we're trying to setup a better search experience.
attaching this schema for a future discussion
![search](https://github.com/ChickenKyiv/database-visuals/blob/master/RecipeAPI_Search_Schema%20%20%20SqlDBM.png)

This is our main documentation space, related to Groceristar project: https://chickenkyiv.github.io/documentation/


This is a strucuture that we have in our models:
https://github.com/ChickenKyiv/database-visuals/tree/master/rapi/models

same structure we use at groceristar-fetch, so we can easy grab data, that we need.

#### Articles:

We have at least few databases and I prepare some plan so we actually will not just replicate logic of our current API servers, but we also will extend and update it. Some details please read here:

https://medium.com/groceristar/chickenkyiv-database-logic-intro-part-1-b2c449d92aa3
https://medium.com/groceristar/chickenkyiv-database-logic-simple-samples-part-2-1ee3ccc6b3d
https://medium.com/groceristar/chicken-kyiv-recipe-db-schema-part3-b80f33ec5d96



I have some collection of tutorials, websites, related to GraphQL topic, storing it here: https://github.com/ChickenKyiv/awesome-graphql-beginner-links
