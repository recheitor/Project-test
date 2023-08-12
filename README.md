| **HTTP Method** 	|    **URl Path**    	    |   **Description**   	| **JSON** 	|
|:---------------:	|  :------------------:	    |:-------------------:	|:--------:	|
|       GET       	|          /           	    |      Home-page      	|          	|
|       GET       	|    /auth/signup    	    |   User form render  	|          	|
|      POST       	|    /auth/signup    	    |  User form handler  	|          	|
|       GET       	|     /auth/login    	    |  User access render 	|          	|
|      POST       	|     /auth/login       	| User access handler 	|          	|
|       GET       	|    /auth/logout       	|     User logout     	|          	|
|       GET       	|    /restaurants       	|  Restaurants render 	|          	|
|       GET       	| /user/{id}/profile       	|  User detail render 	|          	|
|       GET       	|   /user/{id}/edit  	    |   User edit render  	|          	|
|       POST      	|   /user/{id}/edit  	    |  User edit handler  	|          	|
|       POST      	|    /user/{id}/delete   	|     Remove user      	|          	|
|       GET       	|        /recipes        	|  Recipe list render  	|          	|
|       GET       	|      /recipes/new      	|  Add new recipe rend 	|          	|
|       POST      	|      /recipes/new      	| Add new recipe handl 	|          	|
|       GET       	|   /recipes/{id}/edit   	|   Edit recipe rend   	|          	|
|       POST      	|   /recipes/{id}/edit   	|   Edit recipe handl  	|          	|
|       GET       	|  /recipes/{id}/delete  	|     Remove recipe    	|          	|
|       GET       	| /recipes/{id}/favorite 	|  Add favorite recipe 	|          	|
|       GET       	|      /api/recipes      	|   Recipe api render  	|     V    	|
|       GET       	|    /api/recipes/{id}   	|   Recipe id render   	|     V    	|