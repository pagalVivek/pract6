package com.example.pract6

import android.os.Bundle
import android.view.Menu
import android.view.MenuItem
import android.widget.Toast
import androidx.activity.enableEdgeToEdge
import androidx.appcompat.app.AppCompatActivity
import androidx.core.view.ViewCompat
import androidx.core.view.WindowInsetsCompat

class MainActivity : AppCompatActivity() {
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        enableEdgeToEdge()
        setContentView(R.layout.activity_main)
        setSupportActionBar(findViewById(R.id.my_toolbar))
    }

    override fun onCreateOptionsMenu(menu: Menu?): Boolean {
        menuInflater.inflate(R.menu.menu,menu)
        return super.onCreateOptionsMenu(menu)
    }

    override fun onOptionsItemSelected(item: MenuItem): Boolean {
        when(item.itemId){
            R.id.search->{
                Toast.makeText(this, "you clicked on search icon", Toast.LENGTH_SHORT).show()
            }
            R.id.account->{
                Toast.makeText(this, "you clicked on account", Toast.LENGTH_SHORT).show()
            }
            R.id.service->{
                Toast.makeText(this, "you clicked on service", Toast.LENGTH_SHORT).show()
            }
            R.id.feedback->{
                Toast.makeText(this, "you clicked on feedback", Toast.LENGTH_SHORT).show()
            }
            R.id.myaccount->{
                Toast.makeText(this, "you clicked on myaccount", Toast.LENGTH_SHORT).show()
            }
            R.id.personalaccount->{
                Toast.makeText(this, "you clicked on personalaccount", Toast.LENGTH_SHORT).show()
            }
        }
        return super.onOptionsItemSelected(item)
    }
}
