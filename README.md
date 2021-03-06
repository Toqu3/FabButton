##FabProgress
 Android Circular floating action button with intergrated progress indicator ring
[As per material design docs](http://www.google.com/design/spec/components/progress-activity.html#progress-activity-types-of-indicators)

##Demo:

![FabButton](example.gif)
![365 Body Workout](365.gif)

 [![alt text][2]][1]
 
   [1]: https://play.google.com/store/apps/details?id=com.peirr.workout.play
   [2]: https://developer.android.com/images/brand/en_app_rgb_wo_45.png (365 Body workout)
   
##HOW TO ADD TO YOUR PROJECT
 [ ![Download](https://api.bintray.com/packages/ckurtm/maven/FabButton/images/download.svg) ](https://bintray.com/ckurtm/maven/FabButton/_latestVersion)

 Gradle:
 ```groovy
 dependencies {
         compile 'mbanje.kurt:fabbutton:1.0.5'
 }
 ```

##Usage

-	Use FabButton: (check the demo app included)
```xml
<view
        android:layout_width="@dimen/button_size"
        android:layout_height="@dimen/button_size"
        class="mbanje.kurt.fabbutton.FabButton"
        android:id="@+id/indeterminate"
        android:layout_gravity="center"
        android:color="#aa66cc"
        android:src="@drawable/ic_fab_play"
        android:visibility="visible"
        android:indeterminate="true"
        android:max="100"
        app:fbb_autoStart="true"
        app:fbb_progressColor="#0099cc"
        app:fbb_progressWidthRatio="0.2"
        android:layout_centerHorizontal="true"
        android:layout_above="@+id/determinate"
        android:layout_marginBottom="48dp"
        />
```

##License

The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
