<?xml version="1.0" encoding="utf-8"?>

<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"

xmlns:app="http://schemas.android.com/apk/res-auto"

xmlns:tools="http://schemas.android.com/tools"

android:layout_width="match_parent"

android:layout_height="match_parent"

tools:context="com.codinginflow.internalstorageexample.MainActivity">

<EditText

android:id="@+id/edit_text"

android:layout_width="match_parent"

android:layout_height="200dp" />

<Button

android:id="@+id/button_save"

android:layout_width="wrap_content"

android:layout_height="wrap_content"

android:layout_below="@+id/edit_text"

android:layout_centerHorizontal="true"

android:layout_marginTop="16dp"

android:text="save"

android:onClick="save"/>

<Button

android:id="@+id/button_load"

android:layout_width="wrap_content"

android:layout_height="wrap_content"

android:layout_alignStart="@+id/button_save"

android:layout_below="@+id/button_save"

android:layout_marginTop="17dp"

android:text="load"

android:onClick="load"/>

</RelativeLayout>

