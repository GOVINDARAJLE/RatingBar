# RatingBar
*RatingBar*
_Android RatingBar can be used to get the rating from the user. The Rating returns a floating-point number. It may be 2.0, 3.5, 4.0 etc.
Android RatingBar displays the rating in stars. Android RatingBar is the subclass of AbsSeekBar class.
The getRating() method of android RatingBar class returns the rating number._
_Let's see the simple example of rating bar in android._
`<
<Button  
        android:layout_width="wrap_content"  
        android:layout_height="wrap_content"  
        android:text="submit"  
        android:id="@+id/button"  
        app:layout_constraintBottom_toBottomOf="parent"  
        app:layout_constraintLeft_toLeftOf="parent"  
        app:layout_constraintRight_toRightOf="parent"  
        app:layout_constraintTop_toTopOf="parent"  
        app:layout_constraintVertical_bias="0.615" />  
  
    <RatingBar  
        android:id="@+id/ratingBar"  
        android:layout_width="wrap_content"  
        android:layout_height="wrap_content"  
        android:layout_marginLeft="72dp"  
        android:layout_marginTop="60dp"  
        app:layout_constraintStart_toStartOf="parent"  
        app:layout_constraintTop_toTopOf="parent" />  
  >`
