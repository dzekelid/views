---
name: Blogger
x-slug: blogger
description: Blogger is a blog-publishing service that allows multi-user blogs with
  time-stamped entries. It was developed by Pyra Labs, which was bought by Google
  in 2003. Generally, the blogs are hosted by Google at a subdomain of blogspot.com.
  Blogs can also be hosted in the registered custom domain of the blogger (like www.example.com).
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/blogger-icon.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Views
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/views/master/_listings/blogger/apis.md
specificationVersion: "0.14"
apis:
- name: Blogger API Get Blog Page Views
  x-api-slug: blogger-api
  description: Retrieve pageview stats for a Blog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/blogger-icon.png
  humanURL: https://www.blogger.com
  baseURL: ://www.googleapis.com//blogger/v3//blogs/{blogId}/pageviews
  tags: Page Views
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/views/master/_listings/blogger/blogsblogidpageviews-get-openapi.md
- name: Blogger API
  x-api-slug: blogger-api
  description: The Blogger API v3 allows client applications to view and update Blogger
    content. Your client application can use Blogger API v3 to create new blog posts,
    edit or delete existing posts, and query for posts that match particular criteria.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/blogger-icon.png
  humanURL: https://www.blogger.com
  baseURL: ://www.googleapis.com//blogger/v3
  tags: Views
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/views/master/_listings/blogger/openapi.md
x-common:
- type: x-blog
  url: https://blogger.googleblog.com/
- type: x-website
  url: https://www.blogger.com
- type: x-blog-rss
  url: http://buzz.blogger.com/atom.xml
- type: x-developer
  url: https://developers.google.com/blogger/
- type: x-twitter
  url: https://twitter.com/Blogger
- type: x-getting-started
  url: https://developers.google.com/blogger/docs/3.0/getting_started
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---