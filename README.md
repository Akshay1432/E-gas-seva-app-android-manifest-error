# E-gas-seva-app-android-manifest-error
demo



<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    package="com.aks.akshay.shere"
    xmlns:tools="http://schemas.android.com/tools">

    <uses-permission android:name="android.permission.INTERNET" />

    <application
        android:allowBackup="true"
        android:icon="@mipmap/ic_launcher"
        android:label="E-Gas Seva"
        android:roundIcon="@mipmap/ic_launcher_round"
        android:supportsRtl="true"
        android:theme="@style/AppTheme">
        <activity
            android:name=".MainActivity"
            android:windowSoftInputMode="stateHidden">
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />

                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
        <activity
            android:name=".SignUp"
            android:windowSoftInputMode="stateHidden" />
        <activity
            android:name=".Home"
            android:label="@string/title_activity_home"
            android:theme="@style/AppTheme"
            android:windowSoftInputMode="stateHidden" />
        <activity android:name=".ThankYou" />
        <activity android:name=".ForgotPassword" />
        <activity android:name=".Cart" />
        <activity android:name=".UserProfile" />
        <activity android:name=".UserFeedback" />
        <activity android:name=".OrderStatus" />
        <activity
            android:name=".About"
            android:label="@string/title_activity_about"
            android:theme="@style/AppTheme" />
        <activity
            android:name=".ContactUs2"
            android:label="@string/title_activity_contact_us2"
            android:theme="@style/AppTheme" />
    </application>

</manifest>
