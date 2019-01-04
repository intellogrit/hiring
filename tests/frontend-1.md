## Customer Repository Web Application

We have some customer records in a JSON file hosted on a remote server ([here](https://api.myjson.com/bins/1extxw)).

Create a web application which has the following modules

* A page for showing all the customers. It should display all customer details. It should have two views, list view and map view.  In the list view, show customer id and name. In map view, show all customers as a pin on the map. When clicked on the pin, it should show a bubble on map with customer details (id and name).

* Create a search for the above mentioned list page which allows a user to search by name and by location radius. What a location radius search essentially does, is, find all customers within that radius from a base point. For this, you can configure the base point as our office location which is `28.615728, 77.378831` (latitude and longitude respectively). For example, if I put location radius as `5`, it should find all customers whose location is within `5 kms` from the base point. Please use `km` as the default unit for distance.

**Hint:**
You can use the first formula from [this Wikipedia article](https://en.wikipedia.org/wiki/Great-circle_distance) to calculate distance. Don't forget, you'll need to convert degrees to radians.


You are free to use any frontend framework of your choice (Angular, React, VueJS). Please note, since this test is for a frontend developer, applications submitted with vanilla javascript code will be rejected.

Please see the [submission guidelines](../submission-guidelines.md) to know how to submit your code.
