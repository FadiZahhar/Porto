# Porto (Software Architectural Pattern)

**Porto** is a modern Software Architectural Pattern, designed to help developers organize their Code in a super maintainable way.

It consists of 3 Layers `Containers`, `Services` and `Kernel`. And a set of `Components` with predefined responsibilities.

Porto is very helpful for big and long term projects, as these projects tend to have higher complexity with time.

It is inspired by the DDD (Domain Driven Design) and MVC (Model View Controller) patterns.
It adapts techniques from multiple architectures (Layered, Service Oriented, Modular and Command Oriented). 
And it adheres to the best design principles (SOLID, LIFT, Generalization, GRASP and more).

**Porto is Laravel 5 friendly :)**

![](https://s31.postimg.org/v0tfzzevf/Porto_Logo.png)

## Quality Attributes

- Reusable Code (Containers of Business Logic).
- Easy to understand by any developer (less magic, more readable code).
- Fast Development (easy to implement new features).
- Decoupled Code (editing this doesn’t break that).
- Organized Code base.
- Easy Maintenance (easy to adapt changes).
- Zero Technical debt (low communication between Developers).
- Scalable Code (easy to modify and add features).
- Easy to Test (test driven).
- Easy Framework Upgrade.
- Zero Code Decoupling.
- Simple folders structure. (easy to locate anything and everything).
- Clear workflow (predefined and documented).


## Request Life Cycle

*In a typical scenario:*

1. `User` calls an Endpoint *(defined in a `Route` file)*.
2. `Endpoint` calls a `Controller`.
3. (`Request` injected in the `Controller` automatically applies the request validation rules).
4. `Controller` run a `Task` and pass the `Request` data to it.
5. `Task` run multiple `Subtasks` (takes data from one and pass it to another one).
6. `Subtasks` performs the business logic (can also call some `Services`).
7. `Subtasks` returns result data to the `Task`.
8. `Task` returns the collected results data to the `Controller`.
9. `Controller` builds the response and send it back to the `User`.

## Full Documentation


- **Porto Layers**
	- [Containers](https://laravel-porto.readme.io/docs/containers)
	- [Services](https://laravel-porto.readme.io/docs/services)
	- [Kernel](https://laravel-porto.readme.io/docs/kernel)
- **Container's Main Components**
	- [Routes](https://laravel-porto.readme.io/docs/routes)
	- [Controllers](https://laravel-porto.readme.io/docs/controllers)
	- [Tasks](https://laravel-porto.readme.io/docs/tasks)
	- [Subtasks](https://laravel-porto.readme.io/docs/subtasks)
	- [Models](https://laravel-porto.readme.io/docs/models)
	- [Views](https://laravel-porto.readme.io/docs/views)
- **Container's Additional Components**
	- *Documentations under final review, links will be available in few days.*

<!--	
	- [Requests](https://laravel-porto.readme.io/docs/requests)
	- [Repositories](https://laravel-porto.readme.io/docs/repositories)
	- [Providers](https://laravel-porto.readme.io/docs/providers)
	- [Middlewares](https://laravel-porto.readme.io/docs/middlewares)
	- [Policies](https://laravel-porto.readme.io/docs/policies)
	- [Events](https://laravel-porto.readme.io/docs/events)
	- [Exceptions](https://laravel-porto.readme.io/docs/exceptions)
	- [Tests](https://laravel-porto.readme.io/docs/tests)
	- [Migrations](https://laravel-porto.readme.io/docs/migrations)
	- [Transformers](https://laravel-porto.readme.io/docs/transformers)
	- [Criterias](https://laravel-porto.readme.io/docs/criterias)
	- [Jobs](https://laravel-porto.readme.io/docs/jobs)
	- [Commands](https://laravel-porto.readme.io/docs/commands)
	- [Consols](https://laravel-porto.readme.io/docs/consols)
	- [Factories](https://laravel-porto.readme.io/docs/factories)
	- [Seeders](https://laravel-porto.readme.io/docs/seeders)
-->

## Diagrams

Coming soon..

## Projects

> Ready to see it in action!

- Build anything with [Laravel Porto](https://github.com/Mahmoudz/laravel-porto) *(an implementation of the Porto SAP in Laravel 5.1)*.
- Build API-Centric Apps with [Hello API](https://github.com/Mahmoudz/Hello-API) *(an API starter, built with Laravel Porto)*.




## Credits

| Authors      | Twitter                                           | Site                      | Contact         |
|--------------|---------------------------------------------------|---------------------------|-----------------|
| Mahmoud Zalt | [@Mahmoud_Zalt](https://twitter.com/Mahmoud_Zalt) | [zalt.me](http://zalt.me) | mahmoud@zalt.me |


