MarsPhotos
==================================

Developed using the starter code from the course: [Android Basics in Kotlin](https://developer.android.com/courses/android-basics-kotlin/course).

Introduction
------------

A demo app that shows actual images of Mar's surface. These images are
real-life photos from Mars captured by NASA's Mars rovers. The data is stored on a Web server
as a REST web service.  The solution app will demonstrate the use of [Retrofit](https://square.github.io/retrofit/) to make REST requests to the web service, [Moshi](https://github.com/square/moshi) to
handle the deserialization of the returned JSON to Kotlin data objects, and [Coil](https://coil-kt.github.io/coil/) to load images by URL.

The app also leverages coroutines, ViewModel, LiveData, and Data Binding with binding adapters.
