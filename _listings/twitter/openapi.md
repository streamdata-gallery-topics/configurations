swagger: "2.0"
x-collection-name: Twitter
x-complete: 1
info:
  title: Twitter
  description: the-twitter-api-gives-you-programmatic-control-over-any-twitter-account-and-most-aspect-of-the-platform--allowing-developers-to-build-social-applications-that-use-the-platform-and-automate-interactions-between-users-
  version: "1.1"
host: api.twitter.com
basePath: /1.1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /help/configuration:
    get:
      summary: Help Configuration
      description: Returns the current configuration used by Twitter including twitter.com
        slugs which are not usernames
      operationId: returns-the-current-configuration-used-by-twitter-including-twittercom-slugs-which-are-not-usernames
      x-api-path-slug: helpconfiguration-get
      responses:
        200:
          description: OK
      tags:
      - Help
      - Configuration