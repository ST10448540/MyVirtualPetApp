# MyVirtualPetApp
IMAD Assignment 2
1. **Purpose**

‘Louie the pug is an entertaining application which keeps young children busy. This app is designed to bring joy to all dog lovers. ‘Louie the pug’ app offers features that allows the user using the app to feed the pug, play with the pug, bath the pug and put the pug to sleep. The app represents an educational friendly atmosphere to everyone who uses it which emphasises the sense of responsibility. Children who use this app receive educational content on pet care and dog training, preparing them for any responsibility they have when it comes to pet care.

‘Louie the pug’ app is surely an app to brighten every child’s day.

1. **Design Considerations**

In this app I used various designs when creating this app, such as:

- Buttons
- Text Views
- Images
- Text size adjustments
- Background colour
- Constraints

The general design of this app emphasises on the joyful atmosphere it has, since this app can mostly be used by young children the design is very playful. From top to bottom the app is designed very simple. It allows you to navigate, users should be able to navigate, clear, and type in information by using the organised buttons. Accessibility ensures that the app is useable making the app more understandable.

1. **GitHub and GitHub Actions**

Insert the link to your Assignment 2 GitHub repository here.

[Create new workflow · ST10448540/MyVirtualPetApp (github.com)](https://github.com/ST10448540/MyVirtualPetApp/actions/new)

&nbsp;

1. **YouTube Link:** [**https://www.youtube.com/watch?v=EvtrZO2Qbps**](https://www.youtube.com/watch?v=EvtrZO2Qbps)
2. **Code (for all activities)**

Activity (1, 2, 3, 4, and 5)

1. package com.example.myvirtualpetapp  
    <br/>import android.annotation.SuppressLint  
    import android.content.Intent  
    import androidx.appcompat.app.AppCompatActivity  
    import android.os.Bundle  
    import android.widget.Button  
    <br/>class MainActivity : AppCompatActivity() {  
    @SuppressLint("MissingInflatedId")  
    override fun onCreate(savedInstanceState: Bundle?) {  
    super.onCreate(savedInstanceState)  
    setContentView(R.layout._activity_main_)  
    val start_button = findViewById&lt;Button&gt;(R.id._startButton_)  
    <br/>start_button.setOnClickListener**{  
    **val Intent = Intent(this, MainActivity2::class._java_)  
    startActivity(Intent)  
    <br/>**}  
    <br/>**}  
    <br/><br/><br/>}  
    <br/><br/>
2. package com.example.myvirtualpetapp  
    <br/>import android.annotation.SuppressLint  
    import android.content.Intent  
    import androidx.appcompat.app.AppCompatActivity  
    import android.os.Bundle  
    import android.widget.Button  
    <br/>class MainActivity2 : AppCompatActivity() {  
    @SuppressLint("MissingInflatedId")  
    override fun onCreate(savedInstanceState: Bundle?) {  
    super.onCreate(savedInstanceState)  
    setContentView(R.layout._activity_main2_)  
    val njabulo: Button = findViewById(R.id._eatButton_)  
    <br/>njabulo.setOnClickListener**{  
    **val Intent = Intent(this, MainActivity3::class._java_)  
    startActivity(Intent)  
    <br/>**}  
    **}  
    <br/><br/>}  

3. package com.example.myvirtualpetapp  
    <br/>import android.content.Intent  
    import androidx.appcompat.app.AppCompatActivity  
    import android.os.Bundle  
    import android.widget.Button  
    <br/>class MainActivity3 : AppCompatActivity() {  
    override fun onCreate(savedInstanceState: Bundle?) {  
    super.onCreate(savedInstanceState)  
    setContentView(R.layout._activity_main3_)  
    val njabulo: Button = findViewById(R.id._playButton_)  
    <br/>njabulo.setOnClickListener **{  
    **val Intent = Intent (this, MainActivity4::class._java_)  
    startActivity(Intent)  
    **}  
    **}  
    <br/><br/><br/><br/>}  
    <br/><br/>
4. package com.example.myvirtualpetapp  
    <br/>import android.annotation.SuppressLint  
    import android.content.Intent  
    import androidx.appcompat.app.AppCompatActivity  
    import android.os.Bundle  
    import android.widget.Button  
    import com.example.myvirtualpetapp.R.id._cleanMeButton  
    <br/>_class MainActivity4 : AppCompatActivity() {  
    @SuppressLint("MissingInflatedId")  
    override fun onCreate(savedInstanceState: Bundle?) {  
    super.onCreate(savedInstanceState)  
    setContentView(R.layout._activity_main4_)  
    val cleanMeButton: Button = findViewById(_cleanMeButton_)  
    <br/>cleanMeButton.setOnClickListener **{  
    **val Intent = Intent (this, MainActivity5::class._java_)  
    startActivity(Intent)  
    <br/>**}  
    <br/>**}  
    <br/><br/>}
5. package com.example.myvirtualpetapp  
    <br/>import android.content.Intent  
    import androidx.appcompat.app.AppCompatActivity  
    import android.os.Bundle  
    import android.widget.Button  
    <br/>class MainActivity5 : AppCompatActivity() {  
    override fun onCreate(savedInstanceState: Bundle?) {  
    super.onCreate(savedInstanceState)  
    setContentView(R.layout._activity_main5_)  
    val njabulo: Button=findViewById(R.id._relaxButton_)  
    val backButton: Button=findViewById(R.id._backButton_)  
    <br/>backButton.setOnClickListener **{  
    **val Intent = Intent (this, MainActivity::class._java_)  
    startActivity(Intent)  
    <br/>**}  
    **}  

6. **References**

\*About the app

<https://www.data.ai/apps/amazon-appstore/app/B07FJMDL9Q/>

&nbsp;
