# Dependencies

Retrofit:

implementation 'com.squareup.retrofit2:retrofit:2.9.0'

implementation 'com.google.code.gson:gson:2.10'

implementation "com.squareup.okhttp3:okhttp:4.10.0"

compile 'com.squareup.retrofit2:converter-gson:2.3.0'



Lifecycle / LiveData:

def lifecycle_version = "2.5.1"
    
// ViewModel
    
implementation("androidx.lifecycle:lifecycle-viewmodel-ktx:$lifecycle_version")
    
// ViewModel utilities for Compose
    
implementation("androidx.lifecycle:lifecycle-viewmodel-compose:$lifecycle_version")
    
// LiveData
    
implementation("androidx.lifecycle:lifecycle-livedata-ktx:$lifecycle_version")
    
// Lifecycles only (without ViewModel or LiveData)
    
implementation("androidx.lifecycle:lifecycle-runtime-ktx:$lifecycle_version")

// Saved state module for ViewModel
    
implementation("androidx.lifecycle:lifecycle-viewmodel-savedstate:$lifecycle_version")

// Annotation processor
    
kapt("androidx.lifecycle:lifecycle-compiler:$lifecycle_version")

//Fragment
 
implementation("androidx.fragment:fragment-ktx:$fragment_version")

//Coroutines
    
implementation("org.jetbrains.kotlinx:kotlinx-coroutines-android:1.3.9")
    
