# B.S. Bot

## To do

- Add Typescript JSON validation for the API
  - https://github.com/mojotech/json-type-validation/tree/master/docs
  - https://github.com/typestack/class-validator#installation
  - https://medium.com/@ottoki/runtime-type-checking-with-io-ts-in-typescript-14465169fb02
- Put these dictionaries into a database
- Combine adjectives and adverbs into one object
- Add exclamations, proper nouns
- Add tags to words (ex. {2:noun#insult#band}), and templates (ex. "tagline", "paragraph", "insult", etc.)

# Starter kit

## Includes

- Typescript
- React frontend
- Express backend
- "client" and "server" sibling directories
- "shared" directory for client/server shared code
- Restyped for end-to-end typed REST APIs

## Not included/Yet to add

- Absolute path imports
- Limit imports (server shouldn't look at client, client shouldn't look at server)
- Testing infrastructure, including Typescript syntax checking, build errors, linting
- Code coverage for tests
- Linting infrastructure for JS, accessibility, styles, templates, i18n, package.json ordering
- Lint-on-commit infrastructure
- Greenkeeper
- Travis CI
- Yarn policy
- Styled components
- i18n strings and pipeline
- Favicon placeholder
- Build-time variables like "app name" and stuff
- Performance testing for page load times
- Analytics library (Google Analytics, Mixpanel, Segment, etc.)
