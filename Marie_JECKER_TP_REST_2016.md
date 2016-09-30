# TD-intro-web

##Author

**Operation** | **Verb** | **URI** | **Description**
------------- | -------- | ------- | ---------------
Read (all) | GET | */author* | Return the list of authors
Create | POST | */author* | Create a new author
Read | GET | */author/id* | Return one author from its id
Update | PUT | */author/id* | Update the author whose id is given in the URI
Destroy | DELETE | */author/id* | Delete the author whose id is given in the URI

##Article

**Operation** | **Verb** | **URI** | **Description**
------------- | -------- | ------- | ---------------
Read (all) | GET | */author/id/article* | Return the list of article of the author whose id is given
Create | POST | */author/id/article* | Create a new article for the author whose id is given
Read | GET | */author/id/article/aid* | Return the article whose id is "aid" and from the author whose id is "id"
Update | PUT | */author/id/article/aid* | Update the article whose id is "aid" and from the author whose id is "id"
Destroy | DELETE | */author/id/article/aid* | Delete the article whose id is "aid" and from the author whose id is "id"

##Picture

**Operation** | **Verb** | **URI** | **Description**
------------- | -------- | ------- | ---------------
Read (all) | GET | */author/id/article/aid/picture* | Return the list of pictures of the article whose id is "aid" from the author whose id is "id"
Create | POST | */author/id/article/aid/picture* | Create a new picture for the article whose id is "aid" from the author whose id is "id"
Read | GET | */author/id/article/aid/picture/pid* | Return the picture whose id is "pid" and from the article whose id is "aid", from the author whose id is "id"
Update | PUT | */author/id/article/aid/picture/pid* | Update the picture whose id is "pid" and from the article whose id is "aid", from the author whose id is "id"
Destroy | DELETE | */author/id/article/aid/picture/pid* | Delete the picture whose id is "pid" and from the article whose it is "aid, from the author whose id is "id"

##Comment
