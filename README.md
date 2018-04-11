<img align="top" width="500" src="listview_recycler.jpg" alt="ff" />

"Inflation" is a term that refers to parsing XML and turning it into UI-oriented data structures.
</br>ex: `setContentView(R.layout.main)`

To obtain a handle to it in your Activity, use the following snippet:


`RecyclerView rv = (RecyclerView)findViewById(R.id.rv);`</br>
If you are sure that the size of the RecyclerView won't be changing, you can add the following to improve performance:</br>
`rv.setHasFixedSize(true);`


look here for tuts:
https://www.androidhive.info/2016/01/android-working-with-recycler-view/
https://code.tutsplus.com/tutorials/getting-started-with-recyclerview-and-cardview-on-android--cms-23465
