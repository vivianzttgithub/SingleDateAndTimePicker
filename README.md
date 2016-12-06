# SingleDateAndTimePicker

[![screen](https://raw.githubusercontent.com/florent37/SingleDateAndTimePicker/master/media/simple_small.png)](https://www.github.com/florent37/SingleDateAndTimePicker)

# Usage

```java
new DatePickerBottomSheet(this)
            .setTitle("My title")
            .setListener(new DatePickerBottomSheet.Listener() {
                @Override
                public void onDateSelected(Date date) {
                
                }
            }
        ).display();
```

## Select 2 dates

[![screen](https://raw.githubusercontent.com/florent37/SingleDateAndTimePicker/master/media/double_small.png)](https://www.github.com/florent37/SingleDateAndTimePicker)

```java
new DoubleDatePickerBottomSheet(this)
            .setTitle("My title")
            .setTab0Text("First tab")
            .setTab1Text("Second Tab")
            .setListener(new DoubleDatePickerBottomSheet.Listener() {
                @Override
                public void onDateSelected(List<Date> dates) {
                
                }
            }
        ).display();
```

## Include in a layout

[![screen](https://raw.githubusercontent.com/florent37/SingleDateAndTimePicker/master/media/double_small.png)](https://www.github.com/florent37/SingleDateAndTimePicker)

```xml
<com.github.florent37.singledateandtimepicker.SingleDateAndTimePicker
        android:layout_width="wrap_content"
        android:layout_height="230dp"
        app:picker_curved="true"
        app:picker_cyclic="true"
        app:picker_canBeOnPast="false"
        app:picker_visibleItemCount="7"
        />
```

#Credits

Author: Florent Champigny [http://www.florentchampigny.com/](http://www.florentchampigny.com/)

<a href="https://plus.google.com/+florentchampigny">
  <img alt="Follow me on Google+"
       src="https://raw.githubusercontent.com/florent37/DaVinci/master/mobile/src/main/res/drawable-hdpi/gplus.png" />
</a>
<a href="https://twitter.com/florent_champ">
  <img alt="Follow me on Twitter"
       src="https://raw.githubusercontent.com/florent37/DaVinci/master/mobile/src/main/res/drawable-hdpi/twitter.png" />
</a>
<a href="https://www.linkedin.com/in/florentchampigny">
  <img alt="Follow me on LinkedIn"
       src="https://raw.githubusercontent.com/florent37/DaVinci/master/mobile/src/main/res/drawable-hdpi/linkedin.png" />
</a>


License
--------

    Copyright 2016 florent37, Inc.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
