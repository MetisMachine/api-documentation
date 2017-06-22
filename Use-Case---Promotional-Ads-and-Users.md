
With provided themed lists, a list of primary influencers on Instagram related to a given theme could be provided.

## Use Case - The Trendy Clothing Company

If there was a trendy clothing company, ClothingCo, with intentions of promoting their product through ad placements or Instagram influencers, a list popular Instagrammers that would be likely to promote ClothingCo's products would be provided.

### Querying for the top Users in our Data 

Below, is an example query that could search for the information requested based on a given theme. In this example, the information being acquired is the top 10 influencers on Instagram for the trendy clothing company. 

The specified information desired is the user's username, location, and number of followers. Using the graphql interface, this information could be queried for with the following input. 

**Query Input**
```
{
trendyClothing(limit: 10, service: "instagram"){
    username
    location
    followers 	
 }  
}
```

The output will produce the top ten users with their Instagram username, location, and number of followers.

**Query Results**
```
{
  data: {
    "trendyClothing": [
     {
     "username": "@zarinares", 
     "location": "Los Angeles, CA",
     "followers": "4,978"
      },
      {
     "username": "@vbiancav", 
     "location": "New York, NY",
     "followers": "3,673"
      },
      {
     "username": "@kaylenschmidt", 
     "location": "Portland, OR",
     "followers": "5,824"
      },
      {
     "username": "@riverheads", 
     "location": "Los Angeles, CA",
     "followers": "1,498"
      },
      {
     "username": "@blackchanel_janet", 
     "location": "Taipei, Taiwan",
     "followers": "6,775"
      },
      {
     "username": "@loo_ana", 
     "location": "Brazil",
     "followers": "8,826"
      },
     {
     "username": "@nogophoto", 
     "location": "Brazil",
     "followers": "9,933"
      },
      {
     "username": "@photochanel", 
     "location": "Seattle, WA",
     "followers": "3,487"
      },
      {
     "username": "@bohochic", 
     "location": "Los Angeles, CA",
     "followers": "4,576"
      },
      {
     "username": "@citycasual", 
     "location": "New York, NY",
     "followers": "3,442"
      }	
    ]
  }
}
```

## GraphQL View 
![](https://user-images.githubusercontent.com/6729106/27456106-b1be0a3c-576d-11e7-849a-9cd9c3dfcf05.png)

