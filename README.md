
![banner-01](https://user-images.githubusercontent.com/1287098/47606030-f76c3680-da16-11e8-8508-92b26b68f3f8.png)


## MDI**DX** - Same Material Design icons, Better DX 


MDI**DX** (this repository) is a ~*fork* (+ fixes) of Google's [Material Design icons](https://github.com/google/material-design-icons) repository. 
Sadly, Google allocates **low maintenance and low support** for issues reported by software developers having trouble using the Material Design icons library.
 

MDI**DX** helps modern **web developers** to use and include the (awesome) Material Design icons library in their project.
 
 
 

### Installation


using bower 
```
bower install material-design-icons-iconfont --save
```

using npm
```
npm install material-design-icons-iconfont --save
```


### Usage


Visit the [Demo Page](https://jossef.github.io/material-design-icons-iconfont),


- Using `bower`
 
    bower IMO is the simplest way to use this project        
    Add this inside your `<head>` 

      <link href="bower_components/material-design-icons-iconfont/dist/material-design-icons.css" rel="stylesheet">
    
    Later on, reference your desired icon `<i class="material-icons">` + icon-id + `</i>`. For instance:

      <i class="material-icons">contact_support</i>

    Visit the [Demo Page](https://jossef.github.io/material-design-icons-iconfont) for the full icons list

 
 
### What's the difference? Why forking?


- **Performance** - 
    When you checkout Google's [original repository](https://github.com/google/material-design-icons)  ( via git, npm and bower) you experience an unwanted delay. This **checkout delay** is caused by **thousands** of separate source graphic `svg,png,...` files. 
    
    Needless to say that these file are **irrelevant** for the average developer's purposes and **cause build congestion** (especially when using in CI systems)
   
    In this fork all irrelevant files have been **removed** while keeping only the required files. 


- **SCSS Support** - Modern developers need support for `scss`. You can customize the referenced font's files filename and path 


- **Maintenance** - The original repository's release has **missing icons** that should be included according to [https://material.io/tools/icons](https://material.io/tools/icons)
