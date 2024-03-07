# Ex.No:2 To create a HelloWorld Activity using all lifecycles methods to display messages.


## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
```
/*
Program to print the text “Hello World”.
Developed by: kayyuru Tharani
Registeration Number : 212221040080
*/

import android.os.Bundle;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast toast = Toast.makeText(getApplicationContext(), "onCreate Called", Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onStart() {
        super.onStart();
        Toast toast = Toast.makeText(getApplicationContext(), "onStart Called", Toast.LENGTH_LONG);
        toast.show();
    }
    @Override

    protected void onRestart() {
        super.onRestart();
        Toast toast = Toast.makeText(getApplicationContext(), "onRestart Called", Toast.LENGTH_LONG);
        toast.show();

    }
    protected void onPause() {
        super.onPause();
        Toast toast = Toast.makeText(getApplicationContext(), "onPause Called", Toast.LENGTH_LONG);
        toast.show();

    }
    protected void onResume(){
        super.onResume();
        Toast toast = Toast.makeText(getApplicationContext(), "onResume Called", Toast.LENGTH_LONG);
        toast.show();

    }
    protected void onStop() {
        super.onStop();
        Toast toast = Toast.makeText(getApplicationContext(), "onStop Called", Toast.LENGTH_LONG);
        toast.show();

    }
    protected void onDestroy() {
        super.onDestroy();
        Toast toast = Toast.makeText(getApplicationContext(), "onDestroy Called", Toast.LENGTH_LONG);
        toast.show();

    }
}
```

## OUTPUT

![Screenshot (67)](https://github.com/KayyuruTharani/lifecyclemethods/assets/142209319/eeb98155-de63-4c4b-bab5-c212893009c3)

![Screenshot (72)](https://github.com/KayyuruTharani/lifecyclemethods/assets/142209319/e17132f5-4586-4998-9d78-f8ad1c995315)

![Screenshot (71)](https://github.com/KayyuruTharani/lifecyclemethods/assets/142209319/d198476d-8c03-4ec0-9f78-e769c01ae549)

![Screenshot (76)](https://github.com/KayyuruTharani/lifecyclemethods/assets/142209319/4cd618f2-41b3-449b-92eb-579afcbf8892)

![Screenshot (70)](https://github.com/KayyuruTharani/lifecyclemethods/assets/142209319/3613f716-cbd9-4031-a01c-194683d18b6c)

![Screenshot (65)](https://github.com/KayyuruTharani/lifecyclemethods/assets/142209319/98be1e8c-0fa6-4a8d-94ca-b0607ceb1d42)

![Screenshot (66)](https://github.com/KayyuruTharani/lifecyclemethods/assets/142209319/af2f7d41-b3b4-4a28-88bc-155e004d5342)













## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
