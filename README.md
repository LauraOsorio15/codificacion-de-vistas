# codificacion-de-vistas
<!-- res/layout/activity_main.xml -->
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/textViewTitle"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Mi Aplicación"
        android:textSize="24sp"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="16dp"/>

    <Button
        android:id="@+id/buttonSubmit"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Enviar"
        android:layout_below="@id/textViewTitle"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="16dp"/>
    
    <!-- Agrega más vistas según las maquetas de tu aplicación -->

</RelativeLayout>
// MainActivity.java
package com.tu.paquete;

import android.os.Bundle;
import androidx.appcompat.app.AppCompatActivity;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        // Puedes agregar código adicional aquí para manejar eventos, lógica, etc.
    }
}
