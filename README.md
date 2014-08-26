Angular example blog app based on https://github.com/btford/angular-express-blog, where the Node server references the Rollbase REST Api. The blog can be viewed on http://angularrollbase-21755.onmodulus.net/
<br/><br/>
<h2>How to get the application run</h2><br/>
1. Create an Object in Rollbase. Its integration name will be use in objectIntegrationName variable located at routes\api.js file<br/>
2. Create a new field with the type of text, label it as "text". Make sure the integration name is "text" as well.<br/>
3. Supply the credential in routes\api.js <br/>
4. Run the application by invoking #node app.js <br/>
