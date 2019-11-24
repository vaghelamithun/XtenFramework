# XtenFramework [ ![Download](https://api.bintray.com/packages/vaghelamithun/xtensolutions/xten-framework/images/download.svg) ](https://bintray.com/vaghelamithun/xtensolutions/xten-framework/_latestVersion)
The purpose of this framework only to reduce the complexity of development.
This framework contain the many android basic component which are we often
use in our android project like RecyclerView, FloatingActionButton, DrawerLayout,
SwipeRefreshLayout, Fragment, ActionBar, Snackbar and Toolbar.

### Basic features of Xten-Framework

- Fast Development.
- Managing and handling the clear and well structure programing.
- Auto Handling hamburger icon to arrow vice versa on child page change
- No need to initialize contained basic component.
- Handling android version compatibility.
- Managing Activity Stack
- File icon base on its extensions.
- Get resources using app compat.
- Local manage and save data object with list using key
- Pagination or load more

### Application level abstract class

- CoreApp require to extend application class to use some resource related utils class.

### Basic component activity abstract classes which need to extend are
Just extend any `Activity`and override some required method into your activity to maping and handle some basic UI component easyly and reduce the complexity and line of code.

- [CoreSplashActivity](https://github.com/riontech-xten/XtenFramework) extends by AppCompatActivity
- [CoreBaseActivity](https://github.com/riontech-xten/XtenFramework/blob/master/COREBASEACTIVITY.md) extends by AppCompatActivity
- [CoreActionBarActivity](https://github.com/riontech-xten/XtenFramework) extends by CoreBaseActivity
- [CoreFragmentActivity](https://github.com/riontech-xten/XtenFramework) extends by CoreActionBarActivity
- [CoreDrawerActivity](https://github.com/riontech-xten/XtenFramework) extends by CoreFragmentActivity
- [CoreRecyclerActivity](https://github.com/riontech-xten/XtenFramework) extends by CoreActionBarActivity

### Base data binding adapters abstract classes

- BaseRecyclerViewAdapter
- BaseSelectedRecyclerViewAdapter
- BaseListAdapter
- BaseSelectedListAdapter

### Base adapter holder abstract classes

- BaseRecyclerHolder
- BaseViewHolder

### RecyclerView Item Decoration

- LinearItemDecoration
- GridItemDecoration

### Fragment abstract classes

- CoreBaseFragment
- CoreRecyclerViewBaseFragment

### Utils classes

- ActivityLifecycle
- ActivityStack
- AppLog
- CompatibilityUtil
- DeviceUtils
- DialogUtils
- ErrorUtils
- FileExtensionUtils
- ImageUtils
- KeyboardUtils
- NetworkUtil
- PermissionUtils
- ReflectionUtil
- ResourceUtils
- SharedPrefsHelper
- SlideAnimationUtil
- SpannableUtils
- StorageUtils
- StringUtils
- Toaster
- VersionUtils

### Local data save wrapper class

- DataWrapper


### Dependency Setup
To use **XtenFramework** in your projects, simply add the library as a dependency to your build.

##### Maven
```
<dependency>
  <groupId>com.xtensolution.support</groupId>
  <artifactId>xten-framework</artifactId>
  <version>1.0.2</version>
  <type>pom</type>
</dependency>
```
##### Gradle
```
dependencies {
  implementation 'com.xtensolution.support:xten-framework:1.0.2'
}
```

##### Require other dependencies
```
dependencies {
  implementation 'androidx.appcompat:appcompat:1.1.0'
  implementation 'androidx.recyclerview:recyclerview:1.1.0-beta04'
}
```


The library is currently configured to be built via Gradle only. It has the following dependencies:

* Android Gradle plugin - com.android.tools.build:gradle:3.4.2
* Android Support appcompt - androidx.appcompat:appcompat:1.1.0
* Compiled SDK Version        - Android P - 28
* Supported Version           - >= 2.1


### Licence
```
Copyright (c) 2016 riontech-xten

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```




