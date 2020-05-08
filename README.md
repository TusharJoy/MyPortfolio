# tusharghoshjoy
Dist folder or generated static pages form nuxt

Static Generated Deployment (Pre-rendered)

Nuxt.js gives you the ability to host your web application on any static hosting.

To generate our web application into static files:

npm run generate
It will create a dist folder with everything inside ready to be deployed on a static hosting site.

To return a non-zero status code when a page error is encountered and let the CI/CD fail the deployment or build, you can use the --fail-on-error argument.

npm run generate --fail-on-error

// OR

yarn generate --fail-on-error
If you have a project with dynamic routes, take a look at the generate configuration to tell Nuxt.js how to generate these dynamic routes.

When generating your web application with nuxt generate, the context given to asyncData and fetch will not have req and res.
