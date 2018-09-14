## React Single Page Application with MaterialUI tarter-kit.

### Using:
- [MaterialUI](https://github.com/mui-org/material-ui)
- Alexis Mangin's [medium post](https://medium.com/@alexmngn/how-to-better-organize-your-react-applications-2fd3ea1920f1) as a guide to     better structure scalable React projects folder grouped by features or routes.
```
/src
  /components 
    /Button 
    /Notifications
      /components
        /ButtonDismiss  
          /images
          /locales
          /specs 
          /index.js
          /styles.scss
      /index.js
      /styles.scss
  /scenes
    /Home 
      /components 
        /ButtonLike
      /services
        /processData
      /index.js
      /styles.scss
    /Sign 
      /components 
        /FormField
      /scenes
        /Login
        /Register 
          /locales
          /specs
          /index.js
          /styles.scss
  /services
    /api
    /geolocation
    /session
      /actions.js
      /index.js
      /reducer.js
    /users
      /actions.js
      /api.js
      /reducer.js
  index.js 
  store.js
  ```
> "Each component, scene or service (a feature) has everything it needs to work on its own, such as its own styles, images,                translations,   set of actions as well as unit or integration tests. You can see a feature like an independent piece of code you will    use in your app   (a bit like node modules)." - Alexis Mangin

### Features
- Basic admin structure with Async Routes configured
- Sass


### Todo
- [ ] State management

<br/>
<br/>

<p align="center"><img src="https://avatars2.githubusercontent.com/u/20846473?s=70&v=4" width="35" height="35"/></p>
<p align="center">
<sub>A little project by <a href="http://www.jeffersonribeiro.com/">Jefferson Ribeiro</a></sub>
</p>
