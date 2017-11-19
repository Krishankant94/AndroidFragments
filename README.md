# AndroidFragments
Simple Introduction to Fragments

/*
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical" >
  <Button
        android:id="@+id/button1"
        android:layout_width="fill_parent"
        android:layout_height="wrap_content"
        android:text="Fragment No.1"
        android:onClick="selectFrag" />

     <Button
         android:id="@+id/button2"
         android:layout_width="fill_parent"
         android:layout_height="wrap_content"
         android:onClick="selectFrag"
         android:text="Fragment No.2" /> 

   <fragment
        android:name="com.javacodegeeks.android.fragmentstest.FragmentOne"
        android:id="@+id/fragment_place"
   		android:layout_width="match_parent"
   		android:layout_height="match_parent" />
    
</LinearLayout>
*/
In the fragment Tag : 
When we add a <fragment> element in a layout, we have to contain the android:name and android:id attributes. 
The android:name defines an object of a Fragment Class, that we want to be instantiated and
 the android:id specifies the unique id of that fragment.
