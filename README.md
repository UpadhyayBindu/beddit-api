# Beddit web API documentation (Beta)

[Beddit](http://www.beddit.com) is a sleep monitoring device and mobile
application. It has an ultra-thin film sensor that you place in your bed, under
the bed sheet. All you have to do is to sleep on it. Beddit connects wirelessly
to your mobile device and provides you with an overall sleep analysis every morning. 
The Beddit Sleep Monitor measures the user's sleep stages, heart and breathing rates, 
snoring, and more.

When a Beddit user signs into Beddit, all her sleep data is automatically synced
to the Beddit servers (Amazon AWS). The web API gives developers the possibility 
to use Beddit sleep data in the context of their mobile application or web service.

The only catch is that we kindly ask you to mention Beddit when you use data
provided by the Beddit API. We also appreciate when our partners include a link 
back to www.beddit.com on their website/app etc. 

You can use the following assets:

![Beddit logo](images/beddit_logo.png)

![Beddit small logo](images/beddit_logo_small.png)

![Powered by Beddit](images/powered_by_beddit.png)

Now for you to be totally awesome, please mention Beddit in, for example, 
your publicly available graphs/drawings etc. that are based on Beddit sleep data. 
If graphical assets are not easily applicable in these cases, you can simply 
use "Powered by Beddit" as a text snippet.

Do let us know about anything cool that you build on top of our data so we can
share it in our channels!

The API is free for all during the Beta period. At all times, Beddit reserves
the right to make changes to its API policy.

On a more serious note, please understand that sleep data is very personal and sensitive.
You should take extra care to use and store it according to the best privacy and security
practices. It is a good policy to inform your user how you intend to use her data and in what
context.

If you intend to use the API for commercial purposes, please contact us using
[this form](https://docs.google.com/forms/d/14Dic31uJwmMULG1zEBZYDIbHa0O_lYJwWrpwCcQGvTg/viewform?usp=send_form).

By using the Beddit API you agree that you are fully responsible for your own
conduct and content, for any possible consequences and you cannot hold Beddit
Ltd., its affiliates or partners liable for possible violations in such cases. 
You agree not to use the Beddit API for any illegal activities and agree to 
comply with all relevant and applicable laws and regulations. You also agree 
to comply with Beddit's privacy policy and API policies.

The documentation is divided into following chapters.

To stay updated about changes and new features in Beddit API, please subscribe
for our API updates newsletter here:

http://beddit.us4.list-manage.com/subscribe?u=0b978891a5fbf9cb71fa51181&id=01962bce78


## [General](1-General.md)

Documents the general conventions used throughout the API.

## [Authentication](2-Authentication.md)

All access to user data in Beddit is authenticated with access tokens. This
chapter describes how authentication works and how access token is obtained.

## Resources

### [User account related resources](3_1-UserResources.md)

This chapter describes the resources for retrieving user data.

### [Sleep data resources](3_2-SleepResources.md)

This chapter describes the resources for retrieving sleep data.

### [Session data resources](3_3-SessionResources.md)

This chapter describes the resources for retrieving session data.


If you need help in using the API, please contact our customer support:
support@beddit.com.
