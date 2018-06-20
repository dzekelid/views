---
name: Rotten Tomatoes
x-slug: rotten-tomatoes
description: Rotten Tomatoes is a website launched in August 1998 devoted to film
  reviews and news; it is widely known as a film review aggregator. Coverage now includes
  TV content as well. The name derives from the practice of audiences throwing rotten
  tomatoes when disapproving of a poor stage performance. The company was created
  by Senh Duong and since January 2010 has been owned by Flixster, which itself was
  acquired in 2011 by Warner Bros.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/rotten-tomatoes-logo.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Views
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/views/master/_listings/rotten-tomatoes/apis.md
specificationVersion: "0.14"
apis:
- name: Rotten Tomatoes Get Movies Reviews
  x-api-slug: rotten-tomatoes
  description: Get movies reviews.json.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/rotten-tomatoes-logo.png
  humanURL: http://rottentomatoes.com
  baseURL: https://api.rottentomatoes.com//api/public/v1.0//movies/{id}/reviews.json
  tags: Movies,Reviews
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/views/master/_listings/rotten-tomatoes/moviesidreviews-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/views/master/_listings/rotten-tomatoes/moviesidreviews-json-get-openapi.md
- name: Rotten Tomatoes
  x-api-slug: rotten-tomatoes
  description: 'Rotten Tomatoes is a website containing information about movies:
    information, news, reviews and ratings, pictures, etx. The Rotten Tomatoes API
    is RESTful web service that was designed to be easy to explore and use. Developers
    can use the API to access the Rotten Tomatoes&#039; database of movie data by
    using the Lists, Movies, or DVDs sections of the API.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/rotten-tomatoes-logo.png
  humanURL: http://rottentomatoes.com
  baseURL: https://api.rottentomatoes.com//api/public/v1.0
  tags: Views
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/views/master/_listings/rotten-tomatoes/openapi.md
x-common:
- type: x-developer
  url: http://developer.rottentomatoes.com/
- type: x-twitter
  url: https://twitter.com/RottenTomatoes
- type: x-website
  url: http://rottentomatoes.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---