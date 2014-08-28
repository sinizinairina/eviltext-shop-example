# 99 Bottles

Simple JS script puzzle, see it [running](99-bottles/run.html)

``` JavaScript
if (confirm("Are you old enough to read about beer\n" +
	    "according to your local community standards?")) {
  for (i = 99 ; i > 0 ; i--) {
    j = i - 1;
    if (i != 1) {
      icase = "bottles";
    } else {
      icase = "bottle";
    }
    if (j != 1) {
      jcase = "bottles";
    } else {
      jcase = "bottle";
    }
    document.writeln(i + " " + icase + " of beer on the wall,");
    document.writeln(i + " " + icase + " of beer,");
    document.writeln("take 1 down, pass it around,");
    if (j != 0) {
      document.writeln(j + " " + jcase + " of beer on the wall.<br/>");
    } else {
      document.writeln("No more bottles of beer on the wall!<br/>");
    }
    document.writeln()
  }
} else {
  document.write("You might want think about moving to another community.")
}
```

*Use code samples in writings and accompany it with any custom files*

- Date : 2014/1/1
- Tags : Technology