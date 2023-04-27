# Finding Resources by Topic

## Repository Types

Each repository has one of the following roles:

| Type | Description |
| ---- | ----------- |
| code-example | An OAuth example application, such as an API, mobile app or web app |
| sdk | A library used by an application, eg, to validate JWTs in APIs or to implement a code flow in a client |
| plugin | A component that extends the behavior of the Curity Identity Server |
| module | A utility component or module that you deploy, which implements security, eg a gateway plugin |
| deployment | Demonstrates an example end-to-end deployment, such as to AWS or Kubernetes |
| devops | Demonstrates an operational task, such as logging or monitoring |
| use-case | An end-to-end use case to demonstrate an identity related solution |

Keywords can be combined in order to narrow down your search:

```text
topic:code-example topic:api topic:spring-boot
topic:code-example topic:haapi
```

## Code Examples

The following topic keywords are the most common application types:

| Application Type | Description |
| ---------------- | ----------- |
| api | An API or microservice |
| spa | A single page application |
| website | A website with a backend |
| mobile | A mobile application |

Use the language selector to filter on a particular programming language.\
Use the following search to filter on a particular technology stack:

```text
topic:api topic:spring-boot
topic:website topic:dotnet
```

## Plugins

The following are the main types of plugin for the Curity Identity Server:

```text
alarm-handler
authenticator
authentication-action
authorization-manager
claims-provider
consentor
data-access-provider
email-sender
event-listener
sms-sender
token-procedure
```

You can therefore search on particular types of plugin as follows:

```text
topic:plugin topic:authentication-action
```
