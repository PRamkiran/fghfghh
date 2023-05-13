1.AIM:Create an Android application that shows Hello + name of the user and run it
on an emulator.
XML CODE:
<?xml version="1.0" encoding="utf-8"?>
<LinearLayoutxmlns:android="http://schemas.android.com/apk/res/android"
xmlns:app="http://schemas.android.com/apk/res-auto"
xmlns:tools="http://schemas.android.com/tools"
android:layout_width="match_parent"
android:layout_height="match_parent"
android:orientation="vertical"
android:gravity="center"
tools:context=".MainActivity"
>
<TextView
android:layout_width="wrap_content"
android:layout_height="wrap_content"
android:layout_marginLeft="11dp"
android:textSize="40sp"
android:textColor="@color/black"
android:text="Hello XYZ"
android:textStyle="bold"
>
</TextView>
</LinearLayout>
2 | P a g e
JAVA CODE:
package com.example.csbs01;
import androidx.appcompat.app.AppCompatActivity;
import android.os.Bundle;
public class MainActivity extends AppCompatActivity {
 @Override
 protected void onCreate(Bundle savedInstanceState) {
super.onCreate(savedInstanceState);
 setContentView(R.layout.activity_main);
 //No change in java code
 }
}
