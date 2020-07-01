# Android-Workshop
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:padding="16dp">

    <TextView
        android:id="@+id/tvCountryName"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="india"
        android:textSize="18sp"
        android:textStyle="bold"
        android:textColor="@color/colorPrimary"
        app:layout_constraintTop_toTopOf="parent" />

    <TextView
        android:id="@+id/tvTitleTotalCases"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="16dp"
        android:text="Total cases"
        android:textSize="16sp"
        android:textStyle="bold"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/tvCountryName" />

    <TextView
        android:id="@+id/tvNoTotalCases"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="8dp"
        android:text="4000"
        android:textColor="#5D4037"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/tvTitleTotalCases" />

    <TextView
        android:id="@+id/tvTitleNewCases"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="16dp"
        android:text="New cases"
        android:textSize="16sp"
        android:textStyle="bold"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/tvCountryName" />

    <TextView
        android:id="@+id/tvNoNewCases"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="8dp"
        android:text="100"
        android:textColor="#F4511E"
        app:layout_constraintStart_toStartOf="@+id/tvTitleNewCases"
        app:layout_constraintTop_toBottomOf="@+id/tvTitleNewCases" />

    <TextView
        android:id="@+id/tvCountryName1"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginTop="160dp"
        android:text="China"
        android:textSize="18sp"
        android:textStyle="bold"
        android:textColor="@color/colorPrimary"
        app:layout_constraintTop_toTopOf="parent"
        tools:layout_editor_absoluteX="16dp" />

    <TextView
        android:id="@+id/tvTitleTotalCases1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="16dp"
        android:text="Total cases"
        android:textSize="16sp"
        android:textStyle="bold"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/tvCountryName1" />

    <TextView
        android:id="@+id/tvNoTotalCases1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="8dp"
        android:text="99000"
        android:textColor="#5D4037"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/tvTitleTotalCases1" />

    <TextView
        android:id="@+id/tvTitleNewCases1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="16dp"
        android:text="New cases"
        android:textSize="16sp"
        android:textStyle="bold"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/tvCountryName1" />

    <TextView
        android:id="@+id/tvNoNewCases1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="8dp"
        android:text="109"
        android:textColor="#F4511E"
        app:layout_constraintStart_toStartOf="@+id/tvTitleNewCases1"
        app:layout_constraintTop_toBottomOf="@+id/tvTitleNewCases1" />

    <TextView
        android:id="@+id/tvCountryName2"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginTop="424dp"
        android:text="singapore"
        android:textSize="18sp"
        android:textStyle="bold"
        android:textColor="@color/colorPrimary"
        app:layout_constraintTop_toTopOf="parent"
        tools:layout_editor_absoluteX="16dp" />

    <TextView
        android:id="@+id/tvTitleTotalCases2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="16dp"
        android:text="Total cases"
        android:textSize="16sp"
        android:textStyle="bold"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/tvCountryName2" />

    <TextView
        android:id="@+id/tvNoTotalCases2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="8dp"
        android:text="7009"
        android:textColor="#5D4037"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/tvTitleTotalCases2" />

    <TextView
        android:id="@+id/tvTitleNewCases2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="16dp"
        android:text="New cases"
        android:textSize="16sp"
        android:textStyle="bold"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/tvCountryName2" />

    <TextView
        android:id="@+id/tvNoNewCases2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="8dp"
        android:text="900"
        android:textColor="#F4511E"
        app:layout_constraintStart_toStartOf="@+id/tvTitleNewCases2"
        app:layout_constraintTop_toBottomOf="@+id/tvTitleNewCases2" />

    <TextView
        android:id="@+id/tvCountryName3"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginTop="288dp"
        android:text="USA"
        android:textSize="18sp"
        android:textStyle="bold"
        android:textColor="@color/colorPrimary"
        app:layout_constraintTop_toTopOf="parent"
        tools:layout_editor_absoluteX="16dp" />

    <TextView
        android:id="@+id/tvTitleTotalCases3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="16dp"
        android:text="Total cases"
        android:textSize="16sp"
        android:textStyle="bold"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/tvCountryName3" />

    <TextView
        android:id="@+id/tvNoTotalCases3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="8dp"
        android:text="98000"
        android:textColor="#5D4037"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/tvTitleTotalCases3" />

    <TextView
        android:id="@+id/tvTitleNewCases3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="16dp"
        android:text="New cases"
        android:textSize="16sp"
        android:textStyle="bold"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/tvCountryName3" />

    <TextView
        android:id="@+id/tvNoNewCases3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="8dp"
        android:text="190"
        android:textColor="#F4511E"
        app:layout_constraintStart_toStartOf="@+id/tvTitleNewCases3"
        app:layout_constraintTop_toBottomOf="@+id/tvTitleNewCases3" />


</androidx.constraintlayout.widget.ConstraintLayout>
