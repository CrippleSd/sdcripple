# CRIPPLE SD
<!DOCTYPE html>
<html>
<head>
</head>
<body>
<i>
<h1>Option Menu App</h1>
<h2>Steps of Creating App With Option Menu:</h2>
<h4>1. Get your simple AndroidManifest.xml</h4>
<i style="color: blue">
<b><p><</b>?xml version="1.0" encoding="utf-8"?></p>
<b><p><</b>manifest xmlns:android="http://schemas.android.com/apk/res/android"</p>
<menu>
package="my.option.menu">

<b><p><</b>uses-sdk</p>
<p> android:minSdkVersion="12"</p>
<p> android:targetSdkVersion="30" /></p>
<menu>
<b><p><</b>application</p></menu>
<menu><p>android:allowBackup="true"</p>
<p>android:label="Option Menu App"</p>
<p>android:supportsRtl="true"></p></menu>
<menu><b><p><</b>activity android:name=".MenuActivity"></p></menu>
<b><p><</b>intent-filter></p>
<b><p><</b>action android:name="android.intent.action.MAIN" /></p>

<b><p><</b>category android:name="android.intent.category.LAUNCHER" /></p>
<menu><b><p><</b>/intent-filter></p></menu>
<menu> <b><p><</b>/activity></p></menu>
<b><p><</b>/application></p>
</menu>


<b><p><</b>/manifest></p>
</i>
<h4>2. Create the xml file in res/layout/main.xml</h4>
<i style="color: blue">
<b style="color: blue"><</b>?xml version="1.0" encoding="utf-8"?>
<b style="color: blue"><p><</b>LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"</p>
<menu>
<p>android:layout_width="match_parent"</p>
<p>android:layout_height="match_parent"</p>
<p>android:gravity="center"</p>
<p>android:orientation="vertical"></p>

</menu>
<p><b style="color: blue"><</b>/LinearLayout></p>
</i>
<h4>3. Define menu items in res/menu/menu.xml</h4>
<b style="color: blue"><</b>
<p><b style="color: blue"><i>menu xmlns:android="http://schemas.android.com/apk/res/android"></b></p>
<menu>
<p><b style="color: blue"><</b><b style="color: blue">item</b></p>
<p><cite style="color: grey">android</cite>:<i style="color: red">id</i>="<i style="color: purple">@+id/item1"</p>
<p><cite style="color: gray">android</cite>:<i style="color: red">title</i>="Item1"<b style="color: blue">/></b></p>
<b style="color: blue"><</b>
<b style="color: blue">item</b>
<p><cite style="color: gray">android</cite>:<i style="color: red">id</i>="@+id/item2"</p>
<p><cite style="color: gray">android</cite>:<i style="color: red">title</i>="Item2" <b style="color: blue">/></p></b>
<b style="color: blue"><</b>
<b style="color: blue">item</b>
<p><cite style="color: grey">android</cite>:<i style="color: red">id</i>="@+id/item3"</p>
<p><cite style="color: grey">android</cite>:<i style="color: red">title</i>="Item3" <b style="color: blue">/></p></b>
</menu>
<b style="color: blue"><</b>
<b style="color: blue">/menu></b>
</i>
<h4>4. Call your menu items in src/MenuActivity.java</h4>
<i style="color: blue">
<p><b>package  </b>  my.option.menu;</p>


<p><b>import</b> android.app.Activity;</p>
<p><b>import</b> android.os.Bundle;</p>


<p>public class MenuActivity extends Activity {

<p>@Override</p>
<p>protected void onCreate(Bundle savedInstanceState) {</p>
<menu>
<p>super.onCreate(savedInstanceState);</p>
<p>setContentView(R.layout.main);</p>
</menu>
     
<p>@Override
<p> public boolean onCreateOptionsMenu(Menu menu) {</p>
<menu>
<p>// Inflate menu.xml
<p>MenuInflater Inflater = getMenuInflater();</p>
<p>Inflater.inflate(R.menu.menu, menu);</p>
<p>return true;
<p><a style="color: white">__   _ _ </a><param>}</param></p>
    
</menu>
<p>@Override</p>
<p>public boolean onOptionsItemSelected (MenuItem item) {</p>
<menu>
<p>switch (item.getItemId())</p>
<p>{</p>
<p>case R.id.item1:</p>
<p>//Your Code here</p>
<p>return true;</p>
<p>case R. id.item2:</p>
<p>//Your Code here</p>
<p>return true;</p>
<p>case R.id.item3:</p>
<p>//Your Code here</p>
<p>return true;</p>
</menu>
return super.onOptionsItemSelected(item);
<menu>
<a style="color: white">__---   -- _ _ </a><param>}</param>
<p><a style="color: white">_ -  _ </a><param>}</param></p>

</menu>
<menu>
<p>}</p>
</menu>
<p>}</p>
</i>
<center><fieldset>THE END</fieldset></center>
<br>
<br>
<br>
<h2>After Build The App</h2>
<img src="https://cripplesdtech.simdif.com/images/public/sd_63ddc1a4cbd83.png?no_cache=1675481054"></img>
<img src="https://cripplesdtech.simdif.com/images/public/sd_63ddc1fbd21a9.jpg?no_cache=1675481109"></img>
<hr>
<hr>
<hr>
<h3><fieldset><cite><i><center>BY CRIPPLE SD TECHNOLOGY</center></i></cite></fieldset></h3>
<hr>
</body>
</html>
