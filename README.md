# Current-News-using-News-API

A simple demo app for displaying top news using News API based on MVVM clean architecture.

App Features: #Users can view list of latest news. #Users can view headline and whole description about news.

App Architecture: #Based on MVVM architecture and repository pattern. #Whole app is writtten in Kotlin.

The app includes the following main components: #Repository that works with the Api service, providing a unified data interface. #ViewModel that provides data specific for the UI. #The UI, which shows a visual representation of the data in the ViewModel.

App Packages: #model - contains data classes needed for API request and response. #networking - contains the repository classes, responsible for triggering api requests and parsing the response. #ui - contains classes needed to display Activity and Fragment. #viewmodel - responsible for wrapping the model data and preparing the data for the view.

App Specs: #Minimum SDK 19. #Java8 & Kotlin. #MVVM Architecture. #Android Architecture Components (LiveData, ViewModel, Navigation Component, ConstraintLayout). #RxJava2 and RxAndroid for implementing Observable pattern. #Retrofit 2 for API integration. #Glide for image loading. #Custom Views: Loading, Background drawable for camera icon. 
