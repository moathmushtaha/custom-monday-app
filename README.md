# Custom Monday App
Small Monday.com app to display board item information and update the item details from the board to the item view.

## Content
 #### [Custom Integration](https://github.com/moazmoshtha/custom-integration)
-  Listen on item column changes then update it or store -if not exists- in MongoDB.
-  Getting data from Monday.com using custom item mapping. 

 #### [Custom Item View](https://github.com/moazmoshtha/custom-item-view.git)
 -  Show item details from Monday.com Borads and edit it.
 
 #### [Custom Board](https://github.com/moazmoshtha/custom-board) 
 -  Show items details (name - status - description) in table.
 
 
 ## Libraries and Techniques
1- GraphQL:
- Used to communicate with Monday.com api.
- Fetch and modify Item from Monday.com using Query and Mutations.

2- Monday-sdk:
- Access Monday.com account data, by utilizing the GraphQL.
- Used in server-side and client-side to listen to any changes or send API.

3- Express-graphql:
- Test server APIs and Functionality locally by using one endpoint for all graphql queries, mutations, and subscriptions.

4- Mongoose:
- Communicate with MongoDB.
- Create item model.

5- Ngrok:
-  Host project on the internet -public URL- for testing and preview.

6- Monday UI, Bootstrap, Ka-table:
- Custom style.

7- Monday Integration Recipes:
- Create custom recipes using workflow blocks (custom actions). 
- execute actions ("store in MongoDB" or "update in MongoDB") when item created or updated.

 ## Run and Test
 Included in each project repository.


