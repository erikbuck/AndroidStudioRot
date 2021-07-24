# AndroidStudioRot
*Exasperation with the treadmill called Android development*

## The Good
It's good that the Android Software Development Kit SDK continues to improve at a rapid pace. It's good that Android Studio continues to improve. 

## A Tower of Cards on a Shaky Table

I teach Mobile App Development. One year ago, I created a simple Android App using one of the templates provided with Android Studio. I added a small amount of code and a simple one-Activity user interface. This App was intened to be a small sample for students. I used the Android Studio's Analyze->Inspect Code... tool to resolve all identified questionable code and comment constructs. The App built and ran satisfactorrily.

Fast forward a year. I startup the latest Android Studio version and open the existing project. It fails to even open in Android Studio. I update all of the components that the brand new install of Android Studio claims to need uodated. After File->Invalidate Caches and Restart, setting the SDK version, setting the path to the Java Development Kit (JDK), the project at least opens. It doesn't build.

**Hint to Google**: If your Integrated Development Environment (IDE) needs a "Invalidate Caches and Restart" menu, you might want to reconsider your design.

**Question**: Why does the Android Studio Gradle Plugin need to be updated every single time Android Studio is started?

**Hint to Google**: If your template projects and the sample code you recommend produce more than 50 warnings and at least 4 errors when running "Inspect Code.." on the unmodifed projects, you might consider whether "Inspect Code..." is broken or your templates and samples are broken.

The project doesn't build because Google changed the theme and the locations and names of colors. Sitting in GitHub for a year has made the sample project intended to show best pratcices rot into a state where it can't even be built. Actually, my sample project didn't rot. Android Studio rotted.
