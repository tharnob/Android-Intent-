//main xml file


<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:background="#298be1"
    android:padding="10dp"
    android:gravity="center"
    android:orientation="vertical"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">


    <Button
        android:id="@+id/BangladeshId"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="@string/Button1"
        android:textStyle="bold"
        android:background="#9cf256"
        android:layout_margin="10dp"
        android:textSize="20sp"
        android:drawableLeft="@drawable/bangladesh"
        />

    <Button
        android:id="@+id/RussiaId"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="@string/Button2"
        android:textStyle="bold"
        android:background="#9cf256"
        android:layout_margin="10dp"
        android:textSize="20sp"
        android:drawableLeft="@drawable/russia"
        />

    <Button
        android:id="@+id/AmericaId"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="@string/Button3"
        android:textSize="20sp"
        android:textStyle="bold"
        android:background="#9cf256"
        android:layout_margin="10dp"
        android:drawableLeft="@drawable/america"
        />

</LinearLayout>
