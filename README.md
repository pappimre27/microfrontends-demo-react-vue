# microfrontends-demo-react-vue

## Deployment 

Want to deploy each microfrontend independently (including the container)

Location of child app remoteEntry.js files must be known at build time

Many front-end deployment solutions assume you're deploying a single project 
- we need something that can handle multiple diffrent ones

Probably need a CI/CD pipeline of some sort

At present, the remoteEntry.js file name is fixed! Need to think about caching issues
