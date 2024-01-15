## Graph use case in MongoDB 

In this repo you'll learn how to implement a graph use case in MongoDB Atlas through 3 examples.

<h3>Setup</h3>

1. Configure Laptop

Ensure MongoDB version 3.6+ is already installed your laptop, mainly to enable MongoDB command line tools to be used (no MongoDB databases will be run on the laptop for this proof)
Download and install Compass on your laptop
2. Configure Atlas Environment

Log-on to your Atlas account (using the MongoDB SA preallocated Atlas credits system) and navigate to your SA project
In the project's Security tab, choose to add a new user called main_user, and for User Privileges specify Atlas Admin (make a note of the password you specify)
Create an M10 based 3 node replica-set in a single cloud provider region of your choice with default settings (auditing is not available for tiers lower than M10)
In the Security tab, add a new IP Whitelist for your laptop's current IP address
In the Atlas console, for the database cluster you deployed, click the Connect button, select Connect with the Mongo Shell, and in the Run your connection string in your command line section copy the connection command line - make a note of this connection command line to be used later

<h3>Example 1</h3>

<h3>Example 2</h3>

<h3>Example 3</h3>

<p> Atlas Search Store implements many Atlas Search features from autocomplete to custom function scoring. Using the $search operator in a MongoDB aggregation pipeline, we can build fine-grained searches across text, numerics, and geospatial data. By building out this application, you'll learn all sorts of ways MongoDB allows you to build complex, fine-grained full-text searches on your Atlas data.</p>

**No additional servers or software needed. No need to keep data in sync. Everything is done in MongoDB Atlas.**

Current features implemented in this e-commerce application include:

- fuzzy matching
- highlighting
- autocomplete
- relevance-based scoring
- custom function scoring

Future Atlas Search features to implement can include:

- [ ] range queries
- [ ] facets
- [ ] synonyms

<h2 align="center"><a href="https://searchstore-zhtzd.mongodbstitch.com/">https://searchstore-zhtzd.mongodbstitch.com</a></h2>

<p>This application was created using:</p>

- React
- Tailwind CSS
- MongoDB Realm for backend HTTPs endpoints and webhooks
- A sample dataset of Amazon products

<h3>API Points of Integration</h3>
This application is hosted entirely on Realm and calls 2 API endpoints:
 
 * getProductsEndpoint in the Home.js page on line 24
 * Suggestions_AC_Endpoint, used for autocompleted product names, in the Header.js component on line 17.

<p><em>Currently this app is not suitable for mobile, but feel free to send a PR.</em> 😊</p>

<h3>Prerequisites</h3>

- A MongoDB Atlas account. Get one for free <a href="https://www.mongodb.com/cloud/atlas">here.</a>
- A recent version of Node.js and npm.
- Amazon product sample dataset
- (Recommended) <a href="https://www.mongodb.com/try/download/compass">MongoDB Compass - GUI</a>

<h3>Instructions</h3>

In the project directory, you can run:

#### `npm install`

#### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### Atlas Search Hackathon Template:

https://github.com/jamesmilesmdb/atlas-search-hackathon-22

React Components:
<br/>

<div align="center">
<img src="HomePage.png" width="450"  />
</div>
<br/>
<br/>
<div align="center">
<img src="ProdDescription.png" width="450"  />
</div>
<br/>
<div align="center">
<img src="SearchArchitecture.png" width="700"  />
</div>
<br/>

If you have any questions or feedback about this repo, feel free to create an Issue or PR in this repo or reach out to me on Twitter @YouOldMaid.

Also please join our online <a href="https://developer.mongodb.com/community/forums/">MongoDB Community</a> to interact with our product and engineering teams along with thousands of other MongoDB and Realm users. <br/><br/>Have fun and happy coding!
