# RelativeRadioGroup
RadioGroup holds the property of LinearLayout. So it organizes RadioButton either Vertical or Horizontal. But this one holds the property of RelativeLayout. So RadioButtons can be organized relatively.

<img src="https://github.com/mmb4rn0/RelativeRadioGroup/blob/master/website/static/device-2017-04-22-233215.png" width="200" height="356">

[![](https://jitpack.io/v/mmb4rn0/RelativeRadioGroup.svg)](https://jitpack.io/#mmb4rn0/RelativeRadioGroup)

# Download
Grab via gradle-
  Step 1. Add the JitPack repository to your build file
  ```grovy
   allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  ```  
  Step 2. Add the dependency 
  ```grovy	
   dependencies {
	        compile 'com.github.mmb4rn0:RelativeRadioGroup:v1.0.0'
	}
  ```
or via Maven-
  Step 1. Add the JitPack repository to your build file
  ```xml
   <repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
  ```
  Step 2. Add the dependency
  ```xml
   <dependency>
	    <groupId>com.github.User</groupId>
	    <artifactId>Repo</artifactId>
	    <version>Tag</version>
	</dependency>
  ```
# Sample Code
```xml
<com.mmbarno.library.RelativeRadioGroup
        android:layout_width="match_parent"
        android:layout_height="wrap_content">

        <RadioButton
            android:id="@+id/button1"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:checked="true"
            android:text="Button 1" />

        <RadioButton
            android:id="@+id/button2"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginLeft="30dp"
            android:layout_toRightOf="@+id/button1"
            android:text="Button 2" />

        <RadioButton
            android:id="@+id/button3"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_below="@+id/button1"
            android:text="Button 3" />

        <RadioButton
            android:id="@+id/button4"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_alignLeft="@+id/button2"
            android:layout_alignTop="@+id/button3"
            android:layout_toRightOf="@+id/button3"
            android:text="Button 4" />
   </com.mmbarno.library.RelativeRadioGroup>
   ```
   
   # License
   MIT License

Copyright (c) 2017 Manzur E Mehedi Barno

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
   
