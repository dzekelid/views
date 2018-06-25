---
name: Google Play
x-slug: google-play
description: 'The Google Play Developer API allows you to perform a number of publishing
  and app-management tasks. It includes two components: The Subscriptions and In-App
  Purchases API lets you manage in-app purchases and subscriptions. The Publishing
  API lets you upload and publish apps, and perform other publishing-related tasks.'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Views
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/views/master/_listings/google-play/apis.md
specificationVersion: "0.14"
apis:
- name: Google Play Get Reviews
  x-api-slug: google-play
  description: Returns a list of reviews. Only reviews from last week will be returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https://///{packageName}/reviews
  tags: Reviews
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/views/master/_listings/google-play/packagenamereviews-get-openapi.md
- name: Google Play Get Review
  x-api-slug: google-play
  description: Returns a single review.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https://///{packageName}/reviews/{reviewId}
  tags: Reviews
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/views/master/_listings/google-play/packagenamereviewsreviewid-get-openapi.md
- name: Google Play Reply To Review
  x-api-slug: google-play
  description: Reply to a single review, or update an existing reply.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https://///{packageName}/reviews/{reviewId}:reply
  tags: Reviews
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/views/master/_listings/google-play/packagenamereviewsreviewidreply-post-openapi.md
- name: Google Play
  x-api-slug: google-play
  description: 'The Google Play Developer API allows you to perform a number of publishing
    and app-management tasks. It includes two components: The Subscriptions and In-App
    Purchases API lets you manage in-app purchases and subscriptions. The Publishing
    API lets you upload and publish apps, and perform other publishing-related tasks.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https:///
  tags: Views
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/views/master/_listings/google-play/openapi.md
x-common:
- type: x-blog
  url: https://blog.google/products/google-play/
- type: x-blog-rss
  url: https://blog.google/products/google-play/rss
- type: x-developer
  url: https://developers.google.com/android-publisher/
- type: x-facebook
  url: https://www.facebook.com/GooglePlay
- type: x-getting-started
  url: https://developers.google.com/android-publisher/getting_started
- type: x-twitter
  url: https://twitter.com/GooglePlay
- type: x-website
  url: https://play.google.com/store
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---