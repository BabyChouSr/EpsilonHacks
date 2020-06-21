## Inspiration
We noticed that many of our favorite restaurants could not continue to survive such as Sweet Tomatoes. We knew we had to create a platform where users and restaurants can collaborate to not only support restaurants but also create a pathway for support towards charities, helping the socioeconomically disadvantaged. 

## What it does
Using Bread and Butter, users are able to create posts, invite friends, and make orders at their favorite restaurants, knowing that they will be supporting charities as well. Users can even take the app on the go, analyzing receipts and different transactions which will directly support various charities in their community.

## How we built it
Our team used a variety of tools and frameworks to build Bread and Butter. We built our front end, which is the dynamic website that serves as a tool for restaurants and users to communicate with our app, in Flask, Python and Bootstrap (HTML, CSS, JavaScript and SASS). As for our backend, we used various APIs such as the stripe API for the checkout gateway, Google Cloud Vision API for the OCR, and AWS S3 for the database and connection between mobile and web app. The restaurant recommender utilized various packages in NLTK while the map in the dashboard utilized the folium library. For the iOS app, we utilized the Vision library for the OCR and for the web app, we used SQLAlchemy for the database management. 

## Challenges we ran into
Due to the complexity of our project, we encountered a lot of difficulties with our website, machine learning model and rest API backend.

One of the biggest challenges we had to face was dealing with the mobile app's integration with the web app. We utilized Firebase at the beginning of the Hackathon but we noticed that it wasn't working out which is why we switched to AWS S3 database instead. Also, it was difficult to create the dashboard for the restaurants but we ended up working it out, especially after integrating plotly.express for the bar chart.

## Accomplishments that we are proud of
Considering that we went into this hackathon with low expectations (as we couldn't imagine ourselves building a working website, app and backend in less than one week), we were really proud of our final result. We stepped up to the challenge and pushed our limits, and we were pleasantly surprised at our end result. Although there were a lot of features that we didn't get to adding, we ended up creating a product that incorporated a lot of the original ideas. Creating a working app that united the community under the goal of supporting restaurants and charities was truly fulfilling and satisfying.

## What we learned

We learned how to utilize the AWS S3 Database as well as mastering the use of Flask for different needs throughout the app. Although the mobile app was a challenge, we ended up getting it to work as well, fomenting our skills in Swift.

## What's next for Bread and Butter
Bread and Butter will soon contact many restaurants around the area that might seek assistance, allowing them to survive and continue. It will help various charities such as The Innocence Project, George Floyd Memorial Fund, or even the Alameda Food County Bank. Future implementations will contain more personalized messages and additions curated for the user's spending habits and activities.
