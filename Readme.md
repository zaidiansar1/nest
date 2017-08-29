<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="http://kamilmysliwiec.com/public/nest-logo.png" alt="Nest Logo" /></a>
</p>

[travis-image]: https://api.travis-ci.org/kamilmysliwiec/nest.svg?branch=master
[travis-url]: https://travis-ci.org/kamilmysliwiec/nest
[linux-image]: https://img.shields.io/travis/kamilmysliwiec/nest/master.svg?label=linux
[linux-url]: https://travis-ci.org/kamilmysliwiec/nest
  
  <p align="center">Modern, powerful web application framework for <a href="http://nodejs.org" target="blank">Node.js</a>.</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore"><img src="https://img.shields.io/npm/dm/@nestjs/core.svg" alt="NPM Downloads" /></a>
<a href="https://travis-ci.org/kamilmysliwiec/nest"><img src="https://api.travis-ci.org/kamilmysliwiec/nest.svg?branch=master" alt="Travis" /></a>
<a href="https://travis-ci.org/kamilmysliwiec/nest"><img src="https://img.shields.io/travis/kamilmysliwiec/nest/master.svg?label=linux" alt="Linux" /></a>
<a href="https://coveralls.io/github/kamilmysliwiec/nest?branch=master"><img src="https://coveralls.io/repos/github/kamilmysliwiec/nest/badge.svg?branch=master" alt="Coverage Status" /></a>
<a href="https://gitter.im/nestjs/nestjs?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=body_badge"><img src="https://badges.gitter.im/nestjs/nestjs.svg" alt="Gitter" /></a>
<a href="https://opencollective.com/nest#backer"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="https://opencollective.com/nest#sponsor"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
</p>
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->

## Description

Nest is a powerful web framework for [Node.js](http://nodejs.org), which helps you effortlessly build efficient, scalable applications. It uses modern JavaScript, is built with [TypeScript](http://www.typescriptlang.org) and combines best concepts of both OOP (Object Oriented Progamming) and FP (Functional Programming).

Nest is using well-known—[Express](https://github.com/expressjs/express) library under the hood. This means that you can quickly start using Nest without worrying about third party plugins.

## Installation

**Install the TypeScript Starter Project with Git::**
```bash
$ git clone https://github.com/kamilmysliwiec/nest-typescript-starter.git project
$ cd project
$ npm install
$ npm run start
```

**Start a New Project from Scratch with NPM:**
```bash
$ npm i --save @nestjs/core @nestjs/common @nestjs/microservices @nestjs/websockets @nestjs/testing reflect-metadata rxjs
```

## Philosophy

JavaScript is awesome. This language is no longer just a trash to create simple animations in the browser. Now, the front end world is rich in variety of tools. We have a lot of amazing frameworks / libraries such as [Angular](https://angular.io/), [React](https://github.com/facebook/react) or [Vue](https://github.com/vuejs/vue), which improves our development process and makes our applications fast and flexible. 

[Node.js](http://nodejs.org) gave us a possibility to use this language also on the server side. There are a lot of superb libraries, helpers and tools for node, but non of them do not solve the main problem - the architecture. 

We want to create scalable, loosely coupled and easy to maintain applications. Let's show the entire world node.js potential together!

## Features

- Built on top of [TypeScript](http://www.typescriptlang.org)
- Easy to learn - syntax is similar to [Angular](https://angular.io/)
- Based on well-known libraries ([Express](https://github.com/expressjs/express) / [socket.io](https://github.com/socketio/socket.io)) so you could share your experience 
- Supremely useful Dependency Injection, built-in asynchronous **Inversion of Control** container
- **Hierarchical injector** - increase abstraction in your application by creating reusable, loosely coupled modules with type injection
- **WebSockets** module (based on [socket.io](https://github.com/socketio/socket.io), although you can use any other library using adapter)
- Own modularity system (split your system into reusable modules)
- Reactive **microservices** support with messages patterns (built-in transport via TCP / [Redis](https://redis.io/), but you can use any other type of communication using `CustomTransportStrategy`)
- Exceptions handler layer, exception filters, **synchronous & asynchronous pipes** layer
- **Guards** & Reflector - attach additional logic in more declaritive way (e.g. role-based access control)
- **Interceptors** built on top of [RxJS](https://github.com/Reactive-Extensions/RxJS) library,
- Testing utilities (both **e2e & unit** tests)

## Documentation & Quick Start

[Documentation & Tutorial](http://docs.nestjs.com)

## Starter repos

- [TypeScript](https://github.com/kamilmysliwiec/nest-typescript-starter)
- [Babel](https://github.com/kamilmysliwiec/nest-babel-starter/)

## Useful references

- [Modules](http://docs.nestjs.com/modules.html) 
- [Examples](http://docs.nestjs.com/examples.html)
- [API Reference](http://docs.nestjs.com/api-reference.html)

## People

- Author - [Kamil Myśliwiec](http://kamilmysliwiec.com)
- Website - [http://nestjs.com](http://nestjs.com/)

## Backers

I am on a mission to provide an architecture to create truly flexible, scalable and loosely coupled systems using Node.js platform. It takes a lot of time, so if you want to support me, let's [become a backer / sponsor]((https://opencollective.com/nest#backer)). I'll appreciate each help. Thanks!

<a href="https://opencollective.com/nest/backer/0/website" target="_blank"><img src="https://opencollective.com/nest/backer/0/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/1/website" target="_blank"><img src="https://opencollective.com/nest/backer/1/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/2/website" target="_blank"><img src="https://opencollective.com/nest/backer/2/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/3/website" target="_blank"><img src="https://opencollective.com/nest/backer/3/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/4/website" target="_blank"><img src="https://opencollective.com/nest/backer/4/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/5/website" target="_blank"><img src="https://opencollective.com/nest/backer/5/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/6/website" target="_blank"><img src="https://opencollective.com/nest/backer/6/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/7/website" target="_blank"><img src="https://opencollective.com/nest/backer/7/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/8/website" target="_blank"><img src="https://opencollective.com/nest/backer/8/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/9/website" target="_blank"><img src="https://opencollective.com/nest/backer/9/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/10/website" target="_blank"><img src="https://opencollective.com/nest/backer/10/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/11/website" target="_blank"><img src="https://opencollective.com/nest/backer/11/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/12/website" target="_blank"><img src="https://opencollective.com/nest/backer/12/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/13/website" target="_blank"><img src="https://opencollective.com/nest/backer/13/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/14/website" target="_blank"><img src="https://opencollective.com/nest/backer/14/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/15/website" target="_blank"><img src="https://opencollective.com/nest/backer/15/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/16/website" target="_blank"><img src="https://opencollective.com/nest/backer/16/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/17/website" target="_blank"><img src="https://opencollective.com/nest/backer/17/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/18/website" target="_blank"><img src="https://opencollective.com/nest/backer/18/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/19/website" target="_blank"><img src="https://opencollective.com/nest/backer/19/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/20/website" target="_blank"><img src="https://opencollective.com/nest/backer/20/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/21/website" target="_blank"><img src="https://opencollective.com/nest/backer/21/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/22/website" target="_blank"><img src="https://opencollective.com/nest/backer/22/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/23/website" target="_blank"><img src="https://opencollective.com/nest/backer/23/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/24/website" target="_blank"><img src="https://opencollective.com/nest/backer/24/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/25/website" target="_blank"><img src="https://opencollective.com/nest/backer/25/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/26/website" target="_blank"><img src="https://opencollective.com/nest/backer/26/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/27/website" target="_blank"><img src="https://opencollective.com/nest/backer/27/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/28/website" target="_blank"><img src="https://opencollective.com/nest/backer/28/avatar.svg"></a>
<a href="https://opencollective.com/nest/backer/29/website" target="_blank"><img src="https://opencollective.com/nest/backer/29/avatar.svg"></a>

## License

  [MIT](LICENSE)
