# STARTUP IDEA
# lpu_food_delivery
# Problem_Statement_no : CBB28
# Problem_title : Food_Delivery In_Campus at your door step
# Ideas : Food_Courts in the campus are not able to fulrish due to unavailability of delivery services thats why we are making a application that can connect with all the food_courts and supply food all accross the campus, making a hive network between the consumer and seller.
# Objectives: Create a centralized platform that aggregates food options from various campus food courts and vendors.
    Develop a user-friendly mobile application for ordering food with ease and convenience.
    Establish a reliable delivery infrastructure to ensure timely and efficient food delivery across the campus.
    Foster collaboration with campus food vendors to expand menu offerings and enhance service quality.
# Benefits: Variety: Our application offers a wide range of food options from different vendors, catering to diverse tastes and preferences.
    Efficiency: The centralized ordering and delivery system streamlines the food delivery process, reducing waiting times and enhancing overall efficiency.
    Revenue Generation: By expanding their customer reach and streamlining operations, campus food vendors can increase sales and revenue opportunities.
    Community Building: Hive Eats fosters a sense of community by connecting students, faculty, and staff through shared dining experiences and support for local vendors.

#Platform: Android Studio 
#language used:  Java


App Code: plugins {
    id 'com.android.application'
    id 'com.google.gms.google-services'
}

android {
    compileSdkVersion 30
    buildToolsVersion "30.0.3"

    defaultConfig {
        applicationId "com.dataflair.fooddeliveryapp"
        minSdkVersion 18
        targetSdkVersion 30
        versionCode 1
        versionName "1.0"

        testInstrumentationRunner "androidx.test.runner.AndroidJUnitRunner"
    }

    buildTypes {
        release {
            minifyEnabled false
            proguardFiles getDefaultProguardFile('proguard-android-optimize.txt'), 'proguard-rules.pro'
        }
    }
    compileOptions {
        sourceCompatibility JavaVersion.VERSION_1_8
        targetCompatibility JavaVersion.VERSION_1_8
    }
}

dependencies {

    implementation 'androidx.appcompat:appcompat:1.3.0'
    implementation 'com.google.android.material:material:1.3.0'
    implementation 'androidx.constraintlayout:constraintlayout:2.0.4'
    implementation 'androidx.legacy:legacy-support-v4:1.0.0'
    implementation 'org.jetbrains:annotations:15.0'
    implementation 'com.google.firebase:firebase-storage:20.0.0'
    testImplementation 'junit:junit:4.+'
    androidTestImplementation 'androidx.test.ext:junit:1.1.2'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.3.0'
    implementation 'com.google.firebase:firebase-database:20.0.0'
    implementation 'com.google.android.gms:play-services-auth:19.0.0'
    implementation platform('com.google.firebase:firebase-bom:27.1.0')
    implementation 'com.google.firebase:firebase-auth
    implementation 'de.hdodenhof:circleimageview:3.1.0'
    implementation 'com.firebaseui:firebase-ui-database:7.1.1'
    implementation 'com.squareup.picasso:picasso:2.71828'

}

#Request :- Sir, Given time we can accomplish our goal of making a food delivery application during this event and present our work on playstore, please support our startup idea

