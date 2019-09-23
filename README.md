Xamaridea
=========

Update 9/22/2019:  I forked this project and updated it to make it work in Visual Studio 2019.  I'm not a Visual Studio extension developer, and at this point I don't intend to publish this fork to the Visual Studio Marketplace.  If you want to use Xamaridea in Visual Studio 2019, please clone or fork this repo, set the build to Release, and compile the solution.  You will find a the .vsix file in Xamaridea\Xamaridea.VisualStudioPlugin\bin\Release.

I took the liberty of updating the project template as well, since Android 26 and the associated support libs are several years old now.  The new template has dependencies on Android API level 28.  The extension won't replace the old template with the new one if you have previously installed Xamaridea.  If you'd like to use the updated Android project template, I suggest uninstalling Xamaridea and deleting the following directory:  %userprofile%\AppData\Roaming\Xamaridea\Template_v.1.0.1.  When you reinstall the extension by running the Xamaridea.VisualStudioPlugin.vsix you compiled, the updated project template will be installed.

Visual Studio extension, allows editing .axml files in **IntelliJ IDEA** or **Android Studio** (Xamarin.Android). It creates a fake android project and uses resources from your Xamarin.Android project by link (thanks to gradle) so every change made in Android IDE will be saved. Available at https://visualstudiogallery.msdn.microsoft.com/9f5a516a-f4d0-4228-9d25-d0273abebf33

**WARNING:** Plugin may change your project structure (Resources folder), do not use it without version control (it's alfa version).

Tired?

![Alt text](http://habrastorage.org/files/485/2b5/c99/4852b5c9907f4e268ccc5b97fdf504ce.png)

Plugin will help!

![Alt text](Xamaridea.gif)
