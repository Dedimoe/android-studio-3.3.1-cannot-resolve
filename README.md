# android-studio-3.3.1-cannot-resolve
Cannot resolve symbol '@style/Widget.Design.CoordinatorLayout'

file app/build.graddle if using :

''''
dependencies {
    implementation 'com.android.support:appcompat-v7:28.0.0'
...
''''

change :
<item name="coordinatorLayoutStyle">@style/Widget.Design.CoordinatorLayout</item>

to :
<item name="coordinatorLayoutStyle">@style/Widget.Support.CoordinatorLayout</item>
