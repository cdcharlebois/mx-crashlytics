:warning: | Due to a breaking change in the underlying API, this module will cause apps developed in Mendix versions 9.13 and up to fail to startup. A fix is in progress and this module still works as expected up to, and including, 9.12.x. See the table below for details.
:---: | :---

Mx Version | MxCrashlytics 2.0.0 | MxCrashlytics 3.0.0
:---: | :---: | :---:
9.6.0 - 9.12.x | ✅ | ✅ 
9.13.0 - 9.15.x | ❌ | ❌
9.16.0+ | ❌ | ✅ 



# mx-crashlytics
A plug-n-play wrapper for [Firebase Crashlytics](https://rnfirebase.io/reference/crashlytics) in your Mendix Native app

Firebase Crashlytics is a real time crash reporting tool, helps you prioritize and fix your most pervasive crashes based on the impact on real users. This module instruments your Mendix native app to send logs, error reports, and crashes to your Crashlytics dashboard.

* 🔌 **Plug-n-play**. Zero configuration means you can install this module and immediately see data reported to Crashlytics 😎
* 💪 **Runtime loglevel adjustment**. Need more output? Add the included snippet to a page in your native app to let the user change the logging verbosity. Helpful for those tricky issues 🐞
* 💻 **Extensible**. Implements the most common methods from the RNFB Crashlytics module. Go beyond the plug-n-play configuration to instrument your model how you see fit 🏆
