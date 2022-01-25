# Marvel Character Finder

Create a Marvel character finder in Next JS, hosted on Vercel.

### Next JS (https://nextjs.org/)

Next JS is a modern, ultra productive framework for front-end 
web development built on an iso-morphic, Node JS/React stack.

It provides easy routing, server-side rendering, static page generation, 
and serverless cloud functions while allowing developers to build their front-end 
interface in React.

### Vercel (https://vercel.com/)

Vercel is the company who developed Next JS; they also provide a seamlessly integrated
infrastructure system for Next coupled with GitHub. 
You can deploy a Next JS project almost instantly with Vercel as long as the project is in GitHub.

## Building the Character Finder

Depending on your prior experience you may need to familiarise yourself with these
technologies in order to build the finder:

* Javascript / Typescript
* React JS 
* Next JS
* Data fetching (one or more of: fetch, axios, swr)
* CSS including flexbox and responsive

Recommended Courses:
(not all required to build the finder)

* https://frontendmasters.com/courses/next-js/
* https://frontendmasters.com/courses/css-grid-flexbox-v2/
* https://frontendmasters.com/courses/react-typescript/
* https://frontendmasters.com/courses/typescript-v3/

### Requirements

The requirements of the character finder project are deliberately loose, 
but here are some basic items the finder should have:

Basic/Junior:

* A search box - When a user searches for a Marvel character name, the respective matches
are displayed in a list or grid format below.
* Each character "card" should show at least the character image (or placeholder if no image), 
and the character's name.
* The character finder page should present well on various screen sizes.
* Clicking on a character card will present additional information about the character
either on a new page, or within the same interface.
* You have full say on the visual representation of the finder elements. UI libraries are OK.

Advanced Requirements:

* Implement an API proxy in Next cloud functions.
* Usalise a React context/provider.
* Implement some kind of state storage/caching.
* Implement in TypScript.
* Add tests.

Extra Items:

* Integrated a headless CMS to create editable content within the finder, such as a landing banner banner/content area, FAQs page or about page.
* Ideally use GraphQL

###  Marvel API

Marvel provides a free developer API for listing characters. 
Sign up for a free account and review their API documentation - https://developer.marvel.com/

Once you create an account, Marvel will issue you with an API key and Token.
You will need to add your domain (probably localhost:3000 at first) to "Your authorized referrers".

Marvel provides more information about how to authenticate with the API here:
https://developer.marvel.com/documentation/authorization.

##  Concepts to Consider

* API security
* Responsive layout and usability
* Documenting
* GitHub, Commits, Pull Requests

Optionally use TypeScript to build the project.

If you get stuck on any element of the challenge - you can ask for help.

