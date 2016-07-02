DIM v4 is an application that lets users manipulate and inspect their items in [Destiny]. This document will outline large parts of the DIM's architecture to help developers understand the layout of the product. This is a high level document and it is expected that detailed discussion of aspects be done in child pages.

# Client Targets
Our goal is to deliver DIM where users need DIM.  This is on both desktop, tablet, and phone form factors.  Each of these have specific user scenarios that take advantage of the additional screen space.  

The desktop targets are based around browser extensions which allow DIM to use existing authentication with Bungie.net to bypass CORS requirements with the Bungie.net Destiny API.

The hybrid apps being developed for iOS and Android which are able to utilize features of their platforms that are unique.

A possibility of a Progressive Web App that could unify the code base is a possibility if Bungie is able to implement an OAuth2 implementation.

# Dependencies
## Ionic 2
The hybrid apps are using Ionic 2 as a means to deliver a consistent experience between iOS, Android, and the Windows Mobile platform.  

## Angular 2
The next generation framework for Angular has many improvements that we'll take advantage of for DIM v4.  Improved change detection is by far the largest improvement.  This is a disruptive update but one that will let DIM grow.

## ngrx
This is a state storage library that allows features of the application to update a centralized state storage. It's benefit will be improvements to testing the application.  This includes unit and regression testing.

[Destiny]: http://www.destinythegame.com