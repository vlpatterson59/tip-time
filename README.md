# Tip Time app


## What I Learned

* How to use view binding instead of ```findViewById()``` to more easily write code that interacts with views
    ```Gradle Script -> build.gradle (Module: Tip_Time.app) -> android{}```
````
    buildFeatures {
        viewBinding = true
    }
````

* How to use string parameters to  dynamically create strings

* How to use ```Logcat``` in Android Studio to find problems in an app

## Future Modifications and Enhancements

- [ ] Tighten up code by removing unnecessary variables and moving redundant code to helper functions

## References and Resources

### Android

* [Gravity](https://developer.android.com/reference/android/view/Gravity)
* [NumberFormat](https://developer.android.com/reference/java/text/NumberFormat)
* [View Binding](https://developer.android.com/topic/libraries/view-binding)
* [Write and View Logs with Logcat](https://developer.android.com/studio/debug/am-logcat)

### Kotlin

* [numeric data types in Kotlin](https://kotlinlang.org/docs/basic-types.html#numbers)
* [toDouble](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/to-double.html)

### Material Design

* [Typography Theming](https://material.io/develop/android/theming/typography)

### Miscellaneous