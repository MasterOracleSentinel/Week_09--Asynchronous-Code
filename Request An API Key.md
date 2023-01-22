Request An API Key

Preface
In this activity your application will interface with an API hosted on the internet that provides weather information. As part of this activity, you will need to request an API key to the weather API. The main purpose of an API key is to identify your application. Additionally, API keys will often allow the API to do things like rate limit, meaning it can control how many requests it processes from your application during a given period of time. This weather API has rate limiting. Your application will be allowed to send 60 requests per minute before being denied. It’s important to know since your application is identified by the API key, do not share it on the internet. For example, do not commit this key to a public git repository or paste it in a support forum. 


Create an Account
-----------------
* Go to https://openweathermap.org/
* On the right side of the navigation bar, click “Sign In”
* Click the “Create an Account” 
  I. Enter a Username, your Email, and a password.
  II. Check “I am 16 years old and over” and “I agree with Privacy Policy…”
  III. Check “I am not a robot”
  IV. Click the “Create Account” button
* You will be prompted to disclose how and where you will use the API
  I. Leave the Company field blank
  II. For the Purpose field, select “Education/Science” from the dropdown.
  III. Click the “Save” button

Access API Key
---------------
* To access your API key go to https://home.openweathermap.org/api_keys
* Copy the key, it should look something like 125a227a8361eb6f2e52482b227a46464
