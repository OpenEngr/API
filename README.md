Requirements and Background
-------------

In order to access the API you will need an API Token. Tokens are unique to each user and should not be shared. As such, no token is included in this repository. To get your token, first login to the <a href="https://osf.io">OSF site</a>. Visit [https://osf.io/settings/tokens/](https://osf.io/settings/tokens/). The "New Token" button will generate a new token specific to your account.

Once you have the token, open the file named `api_token.py` and paste your token in place of `AUTHTOKEN`.

The API call is handled through the OSF here: https://api.osf.io/v2/preprints/?filter[provider]=engrxiv&filter[reviews_state][ne]=initial


TO DO
---------

Please note, this code is currently very preliminary and only used for testing. It does not (yet) extract all values returned from the API. Development will continue over the next few weeks and the code may be updated often. 
