# Tic-tac-toe
Andela Android Beginner Project
The journey to becoming an Android Developer just started

<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context="com.example.userpc.xs_os.MainActivity">

    <RelativeLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content">

        <TextView
            android:id="@+id/text_view_p1"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Player 1:0"
            android:textSize="30sp" />

        <TextView
            android:id="@+id/text_view_p2"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_below="@id/text_view_p1"
            android:text="Player 2:0"
            android:textSize="30sp" />

        <Button
            android:id="@+id/button_reset"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_alignParentEnd="true"
            android:layout_alignParentRight="true"
            android:layout_centerVertical="true"
            android:layout_marginEnd="19dp"
            android:layout_marginRight="19dp"
            android:text="reset" />
    </RelativeLayout>
    
        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0dp"
            android:layout_weight="1"
            android:orientation="horizontal">

            <Button
                android:id="@+id/button_00"
                android:layout_width="0dp"
                android:layout_weight="1"
                android:layout_height="match_parent"/>

            <Button
                android:id="@+id/button_01"
                android:layout_width="0dp"
                android:layout_weight="1"
                android:layout_height="match_parent"/>

            <Button
                android:id="@+id/button_02"
                android:layout_width="0dp"
                android:layout_weight="1"
                android:layout_height="match_parent"/>
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0dp"
            android:layout_weight="1">
            <Button
                android:id="@+id/button_10"
                android:layout_width="0dp"
                android:layout_weight="1"
                android:layout_height="match_parent"/>

            <Button
                android:id="@+id/button_11"
                android:layout_width="0dp"
                android:layout_weight="1"
                android:layout_height="match_parent"/>

            <Button
                android:id="@+id/button_12"
                android:layout_width="0dp"
                android:layout_weight="1"
                android:layout_height="match_parent"/>
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0dp"
            android:layout_weight="1">
            <Button
                android:id="@+id/button_20"
                android:layout_width="0dp"
                android:layout_weight="1"
                android:layout_height="match_parent"/>

            <Button
                android:id="@+id/button_21"
                android:layout_width="0dp"
                android:layout_weight="1"
                android:layout_height="match_parent"/>

            <Button
                android:id="@+id/button_22"
                android:layout_width="0dp"
                android:layout_weight="1"
                android:layout_height="match_parent"/>
        </LinearLayout>


</LinearLayout>
