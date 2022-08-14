Some GIT commands
# When you are getting some pubspec.lock related issue
git pull origin master --rebase
git clean -f

Some Flutter commands
# In case you change some version for example. In foodpanda_riders_app\android\build.gradle if we change kotlin version.
buildscript {
    ext.kotlin_version = '1.6.10'
    repositories {
        google()
        mavenCentral()
    }
    
flutter pub upgrade
flutter clean
flutter pub get
