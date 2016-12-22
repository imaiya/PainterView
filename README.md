# PainterView
Android画板控件,可以写字画画并生成图片

## 引用 ##
最新版本号[![](https://jitpack.io/v/chenzhenboy/PainterView.svg)](https://jitpack.io/#chenzhenboy/PainterView)
### Gradle ###

Project.gradle

    allprojects {
    	repositories {
        	jcenter()
        	maven { url "https://jitpack.io" }
    	}
	}

app.gradle

    compile 'com.github.chenzhenboy:PainterView:0.9'

### Maven ###
	<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
and

	<dependency>
	    <groupId>com.github.chenzhenboy</groupId>
	    <artifactId>PainterView</artifactId>
	    <version>0.8</version>
	</dependency>

## 使用 ##
使用自定义属性:

    <com.unco.library.PainterView
        android:id="@+id/painter"
        android:layout_width="match_parent"
        android:layout_height="match_parent"/>


## 关于作者 ##

- 简	书:[uncochen](http://www.jianshu.com/users/1695117cc969 )
- 新浪微博:[@Chen丶振](http://weibo.com/724132180 )



## License ##

    Copyright 2016 chenzhenboy

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

