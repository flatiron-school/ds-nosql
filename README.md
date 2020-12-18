# ds-nosql

# Foursquare API Example

## Register

* Please [register for the Foursquare API](https://foursquare.com/developers/apps) and create an app. When you create the app, you can indicate that you're affiliated with Flatiron School and that you're a student.
* Create a file called `.secrets/credentials.json` based on `.secrets/credentials-example.json`
  ```
  cd .secrets
  cp credentials-example.json credentials.json
  vim credentials.json  # use your favorite editor to paste in your client ID and client secret
  cd ..
  git status  # credentials.json should not show up because .secrets/ is in .gitignore
  ```

## Review Documentation

* https://developer.foursquare.com/docs/api/venues/search

This repository describes MongoDB and its utility for working with unstructured (NoSQL) data. It was created with love by the Flatiron School.
