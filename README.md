# Testing new frameworks for future builds.

This project is intended to discover new ideas and libraries that could help in future builds.

## Development needs
* Authentication
* Background Processing with [Android Priority Job Queue](https://github.com/yigit/android-priority-jobqueue)
* Debugging/Logging
    * [Timber](https://github.com/JakeWharton/timber)
    * [logger](https://github.com/orhanobut/logger) looks nice
    * [hugo](https://github.com/JakeWharton/hugo) for debugging
    * [LoggingInterceptor](https://github.com/ihsanbal/LoggingInterceptor) to log JSON data nice
    * [LeakCanary](https://github.com/square/leakcanary)
* Dependency Injection
    * [Dagger2](https://google.github.io/dagger/)
* Crash reporting
    * [Localytics :(](https://www.localytics.com/)
    * [Fabric](https://get.fabric.io/)
* HTTP Request handling
    * Retrofit2
        * GSON
        * Moshi
* ImageLoading
    * [Glide](https://github.com/bumptech/glide)
* Payment Processing
    * Stripe
* Credit Card scanning
    * Card.io
* Testing
    * [Testing Support Library](https://developer.android.com/topic/libraries/testing-support-library/index.html)
    * Espresso
    * Android JUnit Runner
    * JUnit4 Rules
    * UI Automator
    * [Samples](https://github.com/googlesamples/android-testing)
* DataBinding
    * [Android Official Data-Binding](https://developer.android.com/topic/libraries/data-binding/index.html)
* Functional Reactive stuff?
    * [RxJava vs. LiveData](https://www.reddit.com/r/androiddev/comments/6u3ilt/main_advantages_to_architecture_components/)
* Persistence
    * Room from Android Architecture Components
* Services?
* Camera2
    * [TensorFlow integration](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/examples/android)
* Transitions
* NFC Capabilities
    * [CardEmulation app](https://github.com/googlesamples/android-CardEmulation)
    * [CardReader app](https://github.com/googlesamples/android-CardReader)

## UI Libraries [Material Overview](http://blog.iamsuleiman.com/mega-guide-android-material-design-components/?utm_content=buffera3ab2&utm_medium=social&utm_source=plus.google.com&utm_campaign=buffer#flexible-space)
* [SwipeRefreshLayout](https://developer.android.com/reference/android/support/v4/widget/SwipeRefreshLayout.html)
* FABs
* Snackbars
* Endless Scrolling
* ConstraintLayout
* RecyclerView
* CardView

## Our Needs
* Splash Screen
* Home Screen (KeyChain)
* KeyScan Detail
    * Rename
    * Delete
    * Share
    * Purchase
    * Find at Kiosk
* Login / Register
    * E-mail
    * Google Sign In
    * Google Smart Lock
    * Facebook Login
* Camera
* Profile
    * Change password
    * Delete Account
    * Delete Fingerprint
    * Add/Delete Payment Method
* Map
* Style Catalog
* Style Detail
* Shopping Cart
* Checkout Process
* Empty / Loading States
* Notifications
* About KeyMe
* Accepting Key Shares
* Contact Customer Support

## Design needs
* A concrete color palette with only a few colors.
* Bottom Navigation
* New image assets for keys
    * 9 patch images
    * VectorDrawables
* Consistent icons, preferably native to the platform.
* Animation
* Consistent and concise wording

## Experimental Libraries/Classes
* Architecture Components (still in Alpha)
    * [LifeCycle](https://developer.android.com/topic/libraries/architecture/lifecycle.html)
    * [LiveData](https://developer.android.com/topic/libraries/architecture/livedata.html)
    * [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel.html)
    * [Room](https://developer.android.com/topic/libraries/architecture/room.html)
        * Database
        * Entity
        * DAO (Data Access Object)
    * [Google example Github app](https://github.com/googlesamples/android-architecture-components/tree/e33782ba54ebe87f7e21e03542230695bc893818/GithubBrowserSample)
    * [Yigit talk on it](http://androidbackstage.blogspot.com/2017/06/episode-72-architecture-components-1.html)
* Kotlin Support

## Experimental UI Libraries
* Rebound (by facebook)
* Epoxy (by Airbnb)
* Lottie for Android


