# iOS - Technical Test

Thank you for taking the time to do our technical test. The test consists of two parts:

* A coding test

* A few technical questions

In order to avoid bounced emails we would like you to submit your results by uploading the relevant **zip** file to a shared Google Drive folder. 

In order to supply you with the URL for this folder please send an email to tech.recruitment@just-eat.com stating your Google email address or let your agent know your Google address as early as possible. If you don't already have a Google email address, please obtain one so that you can be given access to the test results folder. 

Please make this a single zip file named {yourname}-{role-you-apply-for}.zip containing a single markdown file with the answers to the technical questions and one folder containing the technical test.

## Coding

**We expect coding standards to be inline with that of a real application but we understand that everyone does not have the same artistic flair when it comes to design and UX. Please feel free to work on this until you feel it reaches a standard that best showcases your ability but we understand if some areas have room for improvment**

JUST EAT has a public API available (details below) that you can use to get restaurant information, including which restaurants deliver to what areas. We want you to use this to build an app to show these restaurants.

#### How to use the API

##### With the following headers:

Accept-Tenant: uk

Accept-Language: en-GB

Accept-Charset: utf-8

Authorization: Basic  VGVjaFRlc3RBUEk6dXNlcjI=

User-Agent: The API requires that you send a User-Agent header as part of the request. If you have problems connecting then please check that you’re including a User-Agent.

Host: api-interview.just-eat.com

##### GetRestaurants

* [http://api-interview.just-eat.com/](http://www.google.com/url?q=http%3A%2F%2Fapi.just-eat.com%2Frestaurants%3Fq%3Dse19&sa=D&sntz=1&usg=AFQjCNGDTQ2r7AuFD45sUZl1a6dDucGMUg)[restaurants?q=se19](http://api.just-eat.com/restaurants?q=se19) returns a list of restaurants that deliver to an outcode, including some basic restaurant information (for outcode = se19)


### What you need to do

Please create an app with the following requirements: 

1. Its locates the current postcode that the user is geographically situated in 

2. Allows the user to enter a postcode manually

3. The app should then display the following information about each restaurant that delivers to that postcode:

	1. Name

	2. Average rating

	3. Restaurant logo - URL format to get the image: http://je-cdn-production.s3-eu-west-1.amazonaws.com/uk/images/restaurants/{restaurant_id}.gif 

4. The restaurants should be ordered from highest average rating to lowest average rating 

5. Must use ARC

6. Must compile and run directly from xcode in one step

## Questions

1. Did you have time to complete the coding test? What would you add to your solution if you had more time?

2. What was the most useful feature in your opinion that was added to iOS 7 ? Please include a snippet of code that shows how you've used it.

3. What's your favourite programming language? Why?

4. How would you track down a performance bottleneck in an app? Have you ever had to do this?

5. How would you make the Just Eat public API you used in this interview better

6. Which of your apps in the App Store are you most proud of? Why?

7. Please describe yourself using JSON.
