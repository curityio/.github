# Proposed Guidelines for Setting Topics

This suggests some guidelines for topics in public GitHub repos.\
The goal is to make the overall set of public repos coherent and consistent.

## Code Examples

All code examples use the `code-example` topic, to enable this type of search:

- topic:code-example topic:haapi

I have added these default topics to each code example repo, which could be refined further.\
Most commonly clients use OAuth2 and OIDC features, whereas APIs are primarily OAuth2 focused:

| Type | Default Tags |
| ---- | ------------ |
| API | api, oauth2, jwt-validation, scopes, claims, zero-trust |
| SPA | spa, oauth2, openid-connect |
| Website | website, oauth2, openid-connect |
| Mobile App | mobile, oauth2, openid-connect |

## Programming Languages

To search on a programming language, use the language selector.\
According to docs, type of search is also supposed to work:

- language:java
- language:c#

This type of technology stack can also be searched on:

- topic:spring-boot
- topic:dotnet

## Utility Components

Some code example components are not really example apps:

| Type | Default Tags |
| ---- | ------------ |
| sdk | A library that you plug in, has tags named after the type of component it is used in |
| oauth-agent | A utility API that you deploy |

You can find all instances with a search like this:

- topic:sdk
- topic:oauth-agent

## Plugins

For all plugins I have added the tag `plugin` and also ensured that the type is included.\
Other than that I have mostly left tags alone, though some should be removed.

- topic:plugin topic:authentication-action

Topics such as these should be removed from plugins I think:

- curity
- login (for authenticators)
- oauth
- oauth2
