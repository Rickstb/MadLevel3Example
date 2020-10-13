# MadLevel3Example vragen level 3

#1 Which stages of an activity lifecycle exists?
onCreate(), onStart(), onResume(), onPause(), onStop(), en onDestroy()

#2 Which are the two kind of intents, and what is the difference?
Android ondersteunt twee soorten intenties: expliciet en impliciet. Wanneer een applicatie zijn doelcomponent in een intentie definieert, is dat een expliciete intentie. Als de toepassing geen doelcomponent noemt, is dat een impliciete bedoeling.

#3 What is the difference between Parcelables and Serializables?
Serializable interface is not a part of Android SDK and it uses reflection for marshaling operations and creates lots of temp objects. In Parcelable, you are able to choose which field you want to serialize. Because of the temp object creation and garbage collection, Serialization is slower than Parcelable

#4 What is the purpose of the analyzer?
Android Studio includes an APK Analyzer that provides immediate insight into the composition of your APK after the build process completes. Using the APK Analyzer can reduce the time you spend debugging issues with DEX files and resources within your app, and help reduce your APK size.
