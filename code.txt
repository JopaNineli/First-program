package com.aide.trainer.myapp;

import android.app.*;
import android.os.*;
import android.view.*;
import android.widget.*;

public class MainActivity extends Activity
{
    /** Called when the activity is first created. */
    @Override
    public void onCreate(Bundle savedInstanceState)
	{
        super.onCreate(savedInstanceState);
        
        // Set main.xml as user interface layout
        setContentView(R.layout.main);
    }
    
    public void onYesButtonClick(View view) 
    {
    	// This Java code shows a toast
    	Toast.makeText(this, "Correct!", Toast.LENGTH_LONG).show();
	}
	
	public void onNoButtonClick(View view) 
    {
    	Toast.makeText(this, "Wrong!", Toast.LENGTH_LONG).show();}}
	
 
