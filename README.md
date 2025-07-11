# MyDependecies


```xml
plugins {
    id ("kotlin-kapt")
}

  buildFeatures {
         viewBinding = true
     }

dependencies {
 
    implementation("androidx.core:core-ktx:1.12.0")
    implementation("androidx.appcompat:appcompat:1.6.0")
    implementation("com.google.android.material:material:1.12.0")
    implementation("androidx.constraintlayout:constraintlayout:2.1.4")

    //  Networking libraries
    // Volley
    implementation("com.android.volley:volley:1.2.1")
     // Retrofit 
     implementation ("com.squareup.retrofit2:retrofit:2.11.0")
     // Okhtttp  
    implementation("com.squareup.okhttp3:okhttp:4.12.0")
    //// // /
    
     // Gson Convert library
     implementation ("com.squareup.retrofit2:converter-gson:2.11.0")
      
     // Please Wait Progress Dialog
     implementation("io.github.tashilapathum:please-wait:0.5.0")
  
    // Glide Image Handleing libaray
    implementation("com.github.bumptech.glide:glide:4.16.0")

    // Room Db Library
    val  room_version = "2.6.0"
    implementation ("androidx.room:room-runtime:$room_version")
    kapt ("androidx.room:room-compiler:$room_version")

    // Kotlin Extensions and Coroutines support for Room
    implementation ("androidx.room:room-ktx:$room_version")

    // ViewModel and LiveData Library
    val  lifecycle_version = "2.6.2"
    implementation ("androidx.lifecycle:lifecycle-viewmodel-ktx:$lifecycle_version")
    implementation ("androidx.lifecycle:lifecycle-livedata-ktx:$lifecycle_version")

    // Kotlin Coroutines Library
    val coroutines_version = "1.3.7"
    implementation ("org.jetbrains.kotlinx:kotlinx-coroutines-core:$coroutines_version")

}
```
