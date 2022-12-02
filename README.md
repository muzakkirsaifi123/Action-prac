## Workflow to deploy your flask application on the heroku.

#### This is a flask application. With the use of this workflow we will deploy this application on the heroku. You just need to install the heroku in your system and run the below commands:

## Commands:

### Step 1: Install the heroku in your system.
----
#### You can follow this [link](https://devcenter.heroku.com/articles/heroku-cli) to install the heroku.

---

#### Step 2: Login the heroku account using terminal. Run the below command:
    heroku login -i 

#### Step 3: Create the heroku application
    heroku create

#### Step 4: Generate the heroku token.
    heroku authorization:create

### copy the token and save in secret og your repository. This will use in your workflow.
------

### Whenever you push the code in this repository. This workflow will trigger and deploy your application on heroku.
