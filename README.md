[![](https://jitpack.io/v/THEAccess/compose-shimmer.svg)](https://jitpack.io/#THEAccess/compose-shimmer)

<h1 align="center">
<img src="images/shimmer.gif?raw=true" alt="Shimmer" height="600"/><br />
compose-shimmer </h1>

A Jetpack compose modifier to add a shimmering effect to any widget.
Forked from https://github.com/kazemihabib/compose-shimmer

    MyComponent( modifier = Modifier.shimmer() )
    
    
##### Compatible with Compose version **1.0.0-alpha09**

## Download

Available through jitpack.

Add the maven repo to your root `build.gradle`

```groovy
allprojects {
    repositories {
        maven { url 'https://jitpack.io' }
    }
}
```

Add the dependency:
```groovy
dependencies {
    implementation 'com.github.THEAccess:compose-shimmer:1.0.2'
}
```
