---
name: BigOven
x-slug: bigoven
description: Free recipe app for home cooks. Create a meal plan, grocery list and
  more from your favorite recipes. Organize your recipe collection and take it anywhere.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
x-kinRank: "8"
x-alexaRank: "117577"
tags: Views
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/views/master/_listings/bigoven/apis.md
specificationVersion: "0.14"
apis:
- name: Big Oven Get paged list of reviews for a recipe. Each review will have at
    most one FeaturedReply, as well as a ReplyCount.
  x-api-slug: big-oven
  description: Get paged list of reviews for a recipe. each review will have at most
    one featuredreply, as well as a replycount..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com////recipe/{recipeId}/reviews
  tags: Recipes,Recipe,RecipeId,Reviews
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/views/master/_listings/bigoven/reciperecipeidreviews-get-openapi.md
- name: Big Oven Get a list of recipes that the authenticated user has most recently
    viewed
  x-api-slug: big-oven
  description: Get a list of recipes that the authenticated user has most recently
    viewed.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com////recipes/recentviews
  tags: Recipes,Recipes,Recentviews
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/views/master/_listings/bigoven/recipesrecentviews-get-openapi.md
- name: Big Oven
  x-api-slug: big-oven
  description: Free recipe app for home cooks. Create a meal plan, grocery list and
    more from your favorite recipes. Organize your recipe collection and take it anywhere.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Views
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/views/master/_listings/bigoven/openapi.md
x-common:
- type: x-website
  url: http://www.bigoven.com
- type: x-base
  url: http://api.bigoven.com/
- type: x-blog
  url: http://blog.bigoven.com/
- type: x-blog-rss
  url: http://blog.bigoven.com/index.php/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/bigoven
- type: x-crunchbase
  url: http://www.crunchbase.com/company/bigoven
- type: x-developer
  url: http://api.bigoven.com
- type: x-documentation
  url: http://api2.bigoven.com/
- type: x-email
  url: support@bigoven.com
- type: x-twitter
  url: https://twitter.com/bigoven
- type: x-website
  url: http://bigoven.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---