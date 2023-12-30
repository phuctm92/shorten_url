
# THE URL SHORTENER CHALLENGE (Re-summarize)
*Source: Spiderbox*

## 1. REQUIREMENTS

**As a visitor**, I want to create an account for the app, so that I become an active user. Acceptance Criteria:
 - Application needs my name, email, and password.
 - Duplicated emails are not allowed.
 - Validates email input.

**As an active user**, I must be able to put a URL into the home page and get back a URL of the shortest possible length.  Acceptance Criteria:
 - You shouldn't use any gem or library that provides the short url algorithm
 - Inputting a valid URL should result in displaying the new shortened URL to the user.
 - Inputting an invalid URL should result in displaying errors to the user.

**As an active user,** I must be able to manage my links, edit, create, destroy, etc.

**As an active user,** every time I share this link, I must be redirected to the full URL when we enter the short URL (ex: http://app.com/aSdF​ =>​ ​https://google.com​).

**As an active user,** I want to see a list of my links, ordered by creation date.

**As an active user,** I want to click on my links to see details and stats. Acceptance Criteria:
 - I want to see how many times my link was clicked.

**As an active user,** I want an API key to access and integrate any other platform with this shortener. Acceptance Criteria:
 - I want an endpoint to access all my links.
 - All endpoint results must be paginated.
 - I want an endpoint to shorten new URLs.

**Note:** Research and understand how Bit.ly and TinyURL work before you decide on how to generate URLs of the shortest possible length. There must be a view for the Top 100 most frequently accessed URLs.

## 2. Tech stacks
- Ruby 3.2
- Rails 7.1.2
- postgres 16.0
- Stimulusjs (optional)
- Frontend (Bootstrap v5, tailwindcss *(recommend)* ....)
- Plus point if use Reactjs, Docker, Rspec
