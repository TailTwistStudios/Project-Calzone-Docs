# About Project Calzone

Project Calzone is a prototype federated social VR platform. It's purpose is to enable more ethical and human-centered social vr experiences.

Project Calzone takes great inspiration from the Fediverse and aims to inevitably join it. 

# A breif Introduction to the Fediverse
The Fediverse is a global network if independent social media platforms, that enable seemless interoperability accross multiple websites. Users of one website can communicate and coexist with eachother, even if one or the other are on completely different types of platforms. 

All of these website know how to communicate with eachother over well defined public standards. By using public standards, platforms completely different from each other can coexist, allowing users of both to communicate.

If all of this seems far-fetched, the global Email networks are *already* operating like this. 

# Project Calzone is a two-fold Project
The *whole* of Project Calzone exists as two separate project working in tandem:

- [**Project Calzone Game**](./game/index.md) is a Godot 4 based game client. This is the game that Project Calzone users actually download and run.
- [**Project Calzone Web**](./web/index.md) is an ExpressJS based REST API that handles the game client's login, session management, friends-lists, and federation needs. 

# Project Philosophy
These guidelines define 
1. **Users need not understand the inner workings of the software in order to be able to use it.**
2. **The software should provide explanation when something goes wrong.**
3. **The project should be as self contained as possible and avoid using tools and libraries that unnessecarily complicate it's maintanance and use.**
4. **No update shall be released without reasonable effort to update official documentation beforehand. Documentation updates should be considered a core part of maintaining the software.**
5. **The project should prioritize open source or otherwise freely distributable libraries over proprietary ones.**
6. **If a paid or proprietary library must be used, then if at all possible; the project should be organized as to not tie itself to one proprietary product.**