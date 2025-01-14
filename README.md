
<h1 align="center">React Awesome Loaders</h1> 
<h3 align="center"> 🚀 High quality, super responsive and </br> completely customisable Loading Animations. </h3>

<p align="center"> 
    <img src="doc/images/showcase.gif"></img>
  </a>
</p>

# Getting Started 🎬

The easiest way to use one of the loaders from **Awesome Loaders** is to install the NPM package and import the particular loader to use it.

## Install NPM Package

```bash
npm install react-awesome-loaders
```

## Import And Use

```jsx highlight={1,6}
import { LoaderName } from "react-awesome-loaders"
...
function LoadingComponent(props) {
    return (
        ...
        <LoaderName {...passParametersToCustomise} />
        ...
    );
}
export default LoadingComponent
```

The loaders are very flexible to import and use wherever you want and in any web framework that uses NPM.  
The loaders are auto-responsive. i.e. The size of loader automatically adjusts itself on smaller screen sizes.  
Ofcourse, you can set different sizes for different screens by passing props `desktopSize` and `mobileSize`.  

# License 📄

This project is licensed under the MIT License - see the [LICENSE.md]

