<div id="top"></div>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

<br />

<div align="center">
  <h1 align="center">Project Management App</h1>

  <br />

  <p align="center">
    A simple app built for the purpose of learning GraphQL.
    <br />
    <br />
    <a href="https://github.com/coreyhellwege/project-management-app/issues">Report Bug</a>
    ·
    <a href="https://github.com/coreyhellwege/project-management-app/issues">Request Feature</a>
  </p>
</div>

<br />

## GraphQL

GraphQL is an open-source data query and manipulation language for APIs. 
It is an alternative to a REST API, with some added benefits such as the ability to request the exact data you want to fetch from the server.

You can think of GraphQL as kind of a cross between a REST API and SQL because you get the same type of HTTP operations as a REST API but you also have the control of the request and response like you would with SQL.

#### REST API

![Image][rest-api]

#### GraphQL API

![Image][graphql-api]

#### GraphQL queries & responses

![Image][query-response]

### GraphQL mutations

For the equivalent of HTTP POST, PUT and DELETE methods in GraphQL you use mutations.
Mutations are formatted similarly to queries. Inside the parentheses is where you specify data and inside the curly brackets are where you specify what data you want returned.

![Image][mutation]

### GraphiQL tool

When building a REST API you usually use a tool like Postman to make HTTP requests to your server when testing your endpoints. 

The GraphiQL tool comes with your GraphQL server and allows you to test out queries and mutations. 

#### GraphQL schemas and types

GraphQL servers have a schema that specifies all of the fields as well as their types. 

GraphQL is a strongly typed language. Data types must be predefined.

The most basic components of a GraphQL schema are object types.

There are also Scalar types, such as String, Int, Float, Boolean, ID.

![Image][object-type]

<p align="right"><a href="#top">back to top</a></p>

<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/coreyhellwege/project-management-app.svg?style=for-the-badge
[contributors-url]: https://github.com/coreyhellwege/project-management-app/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/coreyhellwege/project-management-app.svg?style=for-the-badge
[forks-url]: https://github.com/coreyhellwege/project-management-app/network/members
[stars-shield]: https://img.shields.io/github/stars/coreyhellwege/project-management-app.svg?style=for-the-badge
[stars-url]: https://github.com/coreyhellwege/project-management-app/stargazers
[issues-shield]: https://img.shields.io/github/issues/coreyhellwege/project-management-app.svg?style=for-the-badge
[issues-url]: https://github.com/coreyhellwege/project-management-app/issues
[graphql-api]: /images/graphql-api.png
[rest-api]: /images/rest-api.png
[mutation]: /images/mutation.png
[object-type]: /images/object-type.png
[query-response]: /images/query-response.png