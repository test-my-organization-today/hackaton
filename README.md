# hackaton

```

<html>
<body>
<div align="center">
<h2>Opens in the Same Page</h2>
<form id="form1" name="form1" method="post" action="">
<pre><input type="text" name="thecode" id="thecode" /> 
<input type="button" name="submit" id="submit" value="Submit">
<script>
document.getElementById('submit').onclick = function() {
    location.href = 'https://mylabel.globalint.info/' + document.getElementById('thecode').value.toUpperCase();
};
</script>
</pre>
</form>
<h3>Test with "SYD25GUCCAA" </h3>
<br />
<h2>Open in a New Page</h2>
<form id="form2" name="form2" method="post" action="">
<pre><input type="text" name="thecode2" id="thecode2" />
<input type="button" name="submit2" id="submit2" value="Submit">
<script>
document.getElementById('submit2').onclick = function() {
    window.open(
         'https://mylabel.globalint.info/' + document.getElementById('thecode2').value.toUpperCase(),
 '_blank' // <- This is what makes it open in a new window.
);
};
</script>
</pre>
</form>
</div>
</body>
</html>
```
