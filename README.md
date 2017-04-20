# ExpandableMenu

# Download

Include `jitpack.io` inside of **root** project `build.gradle`:

```groovy
allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}
```

After that you can easily include the library in your **app** `build.gradle`:

```groovy
dependencies {
	        compile 'com.github.mahendramahi:ExpandableMenu:1.0'
	}
```

# Instructions

Add ExpandableMenuView to your xml fule

```groovy
    <io.mahendra.expandablemenu.ExpandableMenuView
            android:id="@+id/expanded_menu"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            app:bottom_drawable="@drawable/location_selector"
            app:left_drawable="@drawable/play_selector"
            app:menu_color="@color/menu_color"
            app:menu_drawable="@drawable/menu_icon"
            app:menu_expanded_radius="@dimen/big_radius"
            app:menu_radius="@dimen/small_radius"
            app:right_drawable="@drawable/phone_selector"
            app:top_drawable="@drawable/camera_selector" />
```
Most of xml attributes are self explanatory.  


Add menu click callback in java -

```groovy

        mExpandableMenuView.setOnMenuListener(new ExpandableMenuView.MenuListener() {

            @Override
            public void rightPressed() {
            }

            @Override
            public void leftPressed() {
            }

            @Override
            public void topPressed() {
            }

            @Override
            public void bottomPressed() {
            }
        });
```

--



# Download

<a href='https://ko-fi.com/A67613FQ' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://az743702.vo.msecnd.net/cdn/kofi2.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>


This Is Demo for Test
