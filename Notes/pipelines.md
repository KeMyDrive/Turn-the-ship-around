## iOS CI/CD Pipelines

In order to enable frequent releases of iOS apps, let's setup and maintain CI/CD pipelines.

_One of the painful thing during iOS development is to release the app, it involves many activities that can be error-prone broing, repetitive and time-consuming. The rol of CI/CD pipelines is to automate all the boring tasks._ 

The typical iOS release pipelines consist of the following,

* Checkout the source code
* Static Analysis of the Swift Code (e.g. SwiftLint)
* Compiling and Building the App
* Running different kinds of tests. e.g. unit, integration, UI, Performance, Security
* Code Sign and Archive iOS app
* Distribute iOS app to iTunesConnect or other Third-party services
* Create tags or release on Source Control e.g. Github Releases
* Last but not least, Notify people about the new build with release notes

