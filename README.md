"# appcenter" 

The current most recent version of appcenter is causing the following error for react native 0.72 and 0.73
```
* What went wrong:
A problem occurred configuring project ':appcenter'.
> Could not create an instance of type com.android.build.api.variant.impl.LibraryVariantBuilderImpl.
   > Namespace not specified. Specify a namespace in the module's build file. See https://d.android.com/r/tools/upgrade-assistant/set-namespace for information about setting the namespace.

     If you've specified the package attribute in the source AndroidManifest.xml, you can use the AGP Upgrade Assistant to migrate to the namespace value in the build file. Refer to https://d.android.com/r/tools/upgrade-assistant/agp-upgrade-assistant for general information about using the AGP Upgrade Assistant.

* Try:
> Run with --info or --debug option to get more log output.
> Run with --scan to get full insights.

* Exception is:
org.gradle.api.ProjectConfigurationException: A problem occurred configuring project ':appcenter'.
```

in order to fix it use this repo as a dependency. 
