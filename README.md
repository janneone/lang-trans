# Translator app
Language translator built for Resurs

For some reason the GIF got very blurry in the initial state...

## Demo
![Language translator demo](https://github.com/janneone/lang-trans/blob/master/lang-trans-github.gif)


## Core features
This app acts like a middleman between a Web client and Bitbucket.
It's a monorepo entirely built upon JavaScript with a backend running Express and a frontend running React.
The user loads different projects from a config file that has a appointed folder path and file suffix, i.e.

```
--some
----cool
------path
--------i18n
----------sv
----------en
----------dk
----------etc...
```

The data is then fetched from Bitbucket using their own API and mutated in such way to standardize the way that the foundation of these translations were supposed to work. 
After the user did translations, they could save their data which would then create a PR and notify the developers that were supposed to approve the translations performed.


## Main technologies used
### Backend
* Express
* JWT

### Frontend
* React
* Redux
* Redux-thunk

* ... and other libraries in order to build and serve a fullstack app. 

## Built by
[janneone](https://github.com/janneone)
