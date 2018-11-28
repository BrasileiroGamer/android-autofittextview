# AutoFitTextView

A TextView that automatically resizes text to fit perfectly within its bounds.

**NOTE:** This is an updated version that is compatible with the latest Android APIs. The project and the example were also updated.

![Example Image](/website/static/autofittextview.gif?raw=true)


## Usage

```cson
Unfortunately this version I updated is not on maven...
```

Enable any View extending TextView in code:

```java
AutofitHelper.create(textView);
```

Enable any View extending TextView in XML:

```xml
<me.grantland.widget.AutofitLayout
    android:layout_width="match_parent"
    android:layout_height="wrap_content">

    <Button
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:maxLines="1" />
</me.grantland.widget.AutofitLayout>
```

Use the built in Widget in code or XML:
```xml
<RootElement
    xmlns:autofit="http://schemas.android.com/apk/res-auto"
    ...
```   

```xml
<me.grantland.widget.AutofitTextView
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:maxLines="2"
    android:textSize="40sp"
    autofit:minTextSize="16sp" />
```


## License

    Copyright 2014 Grantland Chew

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
