# ECMAScript & ES6

This next section is a primer on the background of JavaScript. By learning some of the history of the language, we can better understand the importance of ECMAScript and ES6. As the primary front-end scripting language of the internet, JavaScript is a massive iceberg of information; not all of it is visible from the surface. We believe that understanding how the language came about will better your growth as a JavaScript developer.

## What's in a name

This might come as a surprise, but JavaScript wasn't always called JavaScript. Originally, it was called Mocha during development. After the first beta release, the name was changed to LiveScript. Not too long after, a certain browser vendor called Netscape decided to again rename the language to JavaScript, feeding off of the success of the popular language Java.

Fast forward a couple decades, and now even the name JavaScript doesn't necessarily tell the whole story. In order for us to truly understand the JavaScript landscape, we're going to need to understand how the language is standardized.

## Enter ECMAScript

Nowadays, JavaScript is the *de facto* front end scripting language of the internet. It's an incredibly widespread technology that has to work consistently across all the major browsers and interpreters. Due to this, JavaScript needed a formal process to further the language without alienating browser vendors, users, or developers. The end result is a sort of 'master reference' that the JavaScript interpreters should be understanding JavaScript as. This is our standardization.

The ECMA, or European Computer Manufacturer's Association, maintains the current up-to-date standardization of JavaScript, called ECMAScript. The name ECMAScript, oftentimes shortened as ES, ended up being nothing more than a compromise amongst the different organizations involved in the specification process.

For us as developers, the takeaway is quite simple:

- ECMAScript is the standardization of JavaScript
- JavaScript is the implementation of the ECMA Standard

Most of the JavaScript you've been exposed to is a version of the standard called ES5, standardized in 2009 and sometimes called ECMAScript 5.

## ES6 and Beyond

ES2015, or ES6, is the newest standard. It is a superset of ES5, meaning it contains all the features of ES5, plus all the new additions of ES6. This is a common theme for JavaScript standardizations, where new standards are often included as a superset of the old standard, rarely deprecating features.

## Takeaways

- ES6 is a superset of ES5. Because ES6 is not a full language in itself, we must learn both.
- The vast majority of existing JavaScript is still ES5, including libraries, legacy code bases, and examples you encounter on the web.
- Many of ES6's most important features are syntactic sugar - not necessarily needed, but they make the language sweeter to write.
- JavaScript is the language, ECMAScript is the standard.
- We will be learning ES5 and ES6 in parallel, with the new ES6 features clearly marked.

Let's keep exploring JavaScript by focusing on [naming and variables](variables_names.md).
