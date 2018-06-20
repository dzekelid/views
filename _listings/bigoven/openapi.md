---
swagger: "2.0"
x-collection-name: BigOven
x-complete: 1
info:
  title: Big Oven
  description: documentationthis-is-the-documentation-for-the-partner-endpoint-of-the-bigoven-recipe-and-grocery-list-api-the-update-brings-with-it-swaggerbased-documentation--swaggerhttpswagger-io-is-an-emerging-standard-for-describing-restbased-apis-and-with-this-swaggercompliant-endpoint-above-you-can-make-readytogo-interface-libraries-for-your-code-via-swaggercodegenhttpsgithub-comswaggerapiswaggercodegen--for-instance-its-easy-to-generate-libraries-for-node-js-java-ruby-asp-net-mvc-jquery-php-and-moreyou-can-also-try-out-the-endpoint-calls-with-your-own-api-key-right-here-on-this-page--be-sure-to-enter-your-api-key-above-to-use-the-try-it-out-buttons-on-this-page-start-heredevelopers-new-to-the-bigoven-api-should-start-with-this-version-not-with-the-legacy-api--well-be-making-improvements-to-this-api-over-time-and-doing-only-bug-fixes-on-the-v1-api-to-pretend-youre-a-bigoven-user-for-instance-to-get-your-recently-viewed-recipes-or-your-grocery-list-you-need-to-pass-in-basic-authentication-information-in-the-header-just-as-with-the-v1-api--we-do-now-require-that-you-make-all-calls-via-https--you-need-to-pass-your-api-key-in-with-every-call-though-this-can-now-be-done-on-the-header-send-a-request-header-xbigovenapikey-set-to-your-api-key-value-e-g--requestxbigovenapikeyyourkeyhere-migration-notesfor-existing-partners-we-encourage-you-to-migratehttpapi2-bigoven-com-and-while-at-this-writing-we-have-no-hardandfast-termination-date-for-the-v1-api-we-strongly-prefer-that-you-migrate-by-january-1-2017--while-the-changes-arent-overly-complex-there-are-several-breaking-changes-including-refactoring-of-recipe-search-and-results-and-removal-of-support-for-xml--this-is-not-a-simply-plugandplay-replacement-to-the-v1-api--with-respect-to-an-exclusive-focus-on-json-the-world-has-spoken-and-it-prefers-json-for-restbased-apis--weve-taken-numerous-steps-to-refactor-the-api-to-make-it-more-restcompliant--note-that-this-v2-api-will-be-the-preferred-api-from-this-point-onward-so-we-encourage-developers-to-migrate-to-this-new-format--we-have-put-together-some-migration-noteswebdocumentationmigrationtov2-that-we-encourage-you-to-read-carefully-photossee-our-photos-documentationhttpapi2-bigoven-comwebdocumentationrecipeimages--for-more-information-on-usage-of-this-api-including-features-pricing-rate-limits-terms-and-conditions-please-visit-the-bigoven-api-websitehttpapi2-bigoven-com-
  termsOfService: Please see our [terms of service](http://api2.bigoven.com/web/documentation/termsofuse
  version: partner
host: api2.bigoven.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /recipe/{recipeId}/reviews:
    get:
      summary: Get paged list of reviews for a recipe. Each review will have at most
        one FeaturedReply, as well as a ReplyCount.
      description: Get paged list of reviews for a recipe. each review will have at
        most one featuredreply, as well as a replycount..
      operationId: Review_GetReviews
      x-api-path-slug: reciperecipeidreviews-get
      parameters:
      - in: query
        name: pg
        description: the page (int), starting with 1
      - in: path
        name: recipeId
        description: recipe id (int)
      - in: query
        name: rpp
        description: results per page (int)
      responses:
        200:
          description: OK
      tags:
      - Recipes
      - Recipe
      - RecipeId
      - Reviews
  /recipes/recentviews:
    get:
      summary: Get a list of recipes that the authenticated user has most recently
        viewed
      description: Get a list of recipes that the authenticated user has most recently
        viewed.
      operationId: Recipe_RecentViews
      x-api-path-slug: recipesrecentviews-get
      parameters:
      - in: query
        name: pg
        description: Page number starting with 1
      - in: query
        name: rpp
        description: results per page
      responses:
        200:
          description: OK
      tags:
      - Recipes
      - Recipes
      - Recentviews
---