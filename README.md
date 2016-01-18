## Inspiration
The inspiration for "Skin On Me" was to help identify a skin disorder some person may have but are not aware of what it actually is. This would have the potential to save many lives by catching preventable skin disorder early.

## What it does
 With the application the user can easily able to identify any possible skin disorder with a degree of confidence. First, the user will take a photo of their condition under normal light conditions, then the application will process the image through IBM Watsons' Visual Recognition API to determine what the skin disorder might be. The application will return the most likely skin disorder and provide useful information to the user about where to get treatment.
## How we built it
We built this application using IBM Bluemix, more specifically IBM Watson APIs and services for Visual Recognition. First we created an application through Bluemix using the Internet of Things boiler plate using Node RED. With Node RED we created flows to interact with the Visual Recognition service and process our images. Results will be returned back to our web application where the user can view it.
## Challenges we ran into
When creating the application using Node RED with Visual Recognition(beta), we came across through many technical issue due to unavailability of proper documentation, we ran into some serious challenges, including problems encountered with the custom classifiers, which took couple hours to figure it out.
## Accomplishments that we're proud of
We contributed with the knowledge of functionality of IBM's latest API with filling in the loopholes in incomplete documentation and figuring out the API eventually after getting help from IBM personnel's.

## What we learned
We learned about IBM Bluemix products and services, mainly creating applications and using the Watson services for Visual Recognition. Additionally we gained practice of using Node RED for creating flows with IBMs services, and using Postman to test data calls. 

## What's next for Skin On Me
We intend to get Watson to work as intended, currently waiting on updates to Node RED before we can continue. 
