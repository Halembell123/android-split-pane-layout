Android Split Pane Layout
===========

An Android layout which splits the available space between two child views. An optionally movable bar exists between the children which allows the user to redistribute the space allocated to each view.

Usage
=====
Add a reference to the split-pane-layout library project, or copy the necessary files into your project. Add a SplitPaneLayout as follows:

    <com.mobidevelop.widget.SplitPaneLayout
        xmlns:android="http://schemas.android.com/apk/res/android"
        xmlns:spl="http://schemas.android.com/apk/res-auto"
        android:layout_width="fill_parent"
        android:layout_height="fill_parent"
        spl:orientation="vertical"
        spl:splitterSize="12dip"
        spl:splitterPosition="33%"
        spl:splitterBackground="@drawable/splitter_bg_v"
        >
        <TextView
            android:layout_width="fill_parent"
            android:layout_height="wrap_content"
            android:text="Child1" />
        <TextView
            android:layout_width="fill_parent"
            android:layout_height="wrap_content"
            android:text="Child2" />
    </com.mobidevelop.widget.SplitPaneLayout>

**NOTE**: A SplitPaneLayout **MUST** have exactly two children.  

Precompiled Demo APK
====================
<https://github.com/downloads/MobiDevelop/android-split-pane-layout/SplitPaneLayout-Demo.apk>
![QR](https://chart.googleapis.com/chart?cht=qr&chs=300x300&chl=https://github.com/downloads/MobiDevelop/android-split-pane-layout/SplitPaneLayout-Demo.apk)