ccc
===

CSS Command Centers (#CCC) is an organizational framework you can use to leverage the power of object-oriented CSS concepts in your projects.

Traditionally as designers / developers, we haven't architected CSS in an object-oriented way, as we may have with other front-end tools, such as JavaScript. As a result, our CSS may become fragile - code that is too closely attached to IDs and can't be used elsewhere. Or even worse - repetitive, loosely structured, re-use unfriendly code that is a resource-drain to maintain.

CSS preprocessors offer components that make it easier to infuse object-oriented concepts into CSS, but it also helps to have a definite, overall structure to keep everything organized. Just as we might use an organizational framework like Backbone to lend structure to what may otherwise be spaghetti custom JavaScript code, we can use a framework like #CCC to organize our custom CSS.

<p>#CCC leverages DRY (don't repeat yourself) principles where possible - and endeavors to make your CSS more manageable, scalable and modular with reusable components.</p>

<p>#CCC also strives for maximal flexibility by having no hard file dependencies. By utilizing Sass partials, you choose à la carte which #CCC components or external components to include in your project. Want to use #CCC's grid? Use the import directive of Sass to add CCC's grid partial into your project. Don't need #CCC's grid system? Easily switch it for Susy, Bourbon Neat, or anything else better suited for your project.</p>

Above all, Command Centers are used extensively as hubs in your codebase to manipulate specific, sweeping aspects of CSS - colors, grids, typography, breakpoints, etc. - instantly.
