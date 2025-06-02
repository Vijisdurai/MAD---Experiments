# BASIC-ANDROID-_EX_01

# Ex.No:1 Implementation of a Hello world Activity using all lifecycles methods using Android Studio.
## AIM:
To create Hello world Activity using all lifecycles methods to display messages using android studio.

## EQUIPMENTS REQUIRED:
Android Studio(Min. required Artic Fox)

## ALGORITHM:
Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next.

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
Program to implement a Hello world Activity using all lifecycles methods using Android Studio . 
### MainActivity.java:
```
package com.example.exp1;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }


    protected void onStart(){
        super.onStart();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStart Executed",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onResume() {
        super.onResume();
        Toast toast = Toast.makeText(getApplicationContext(), "OnResume Executed", Toast.LENGTH_LONG);
        toast.show();

    }
    protected void onPause(){
        super.onPause();
        Toast toast=Toast.makeText(getApplicationContext(),"OnPause Executed",Toast.LENGTH_LONG);
        toast.show();

    }
    protected void onStop(){
        super.onStop();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStop Executed",Toast.LENGTH_LONG);
        toast.show();

    }
    protected void onRestart(){
        super.onRestart();
        Toast toast=Toast.makeText(getApplicationContext(),"OnRestart Executed",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onDestroy(){
        super.onDestroy();
        Toast toast=Toast.makeText(getApplicationContext(),"OnDestroy Executed",Toast.LENGTH_LONG);
        toast.show();
    }
}
```
### activity_main.xml:
```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>

```

## OUTPUT:

![Screenshot 2024-09-14 105211](https://github.com/user-attachments/assets/ec75b30e-f56a-43e7-afff-8c723b00eb7a)![Screenshot 2024-09-14 104938](https://github.com/user-attachments/assets/33434b43-bcd4-4081-adf4-0cad6605bc76)
![Screenshot 2024-09-14 104958](https://github.com/user-attachments/assets/671c7641-b10f-479a-aece-188d8265e5b0)
![Screenshot 2024-09-14 105044](https://github.com/user-attachments/assets/104e4248-f7b3-4e49-a686-317eb9882437)
![Screenshot 2024-09-14 105104](https://github.com/user-attachments/assets/31d00dfe-9f43-481e-8141-655fe097fe7d)

## RESULT:
Thus a program to implement the various life cycles of an activity is written and successfully executed using Android Studio.
