**Introduction**

jqmPhp is a package of PHP classes that facilitates the creation HTML files for use with jQuery Mobile Framework.  All classes in the jqmPhp package can be converted to string and printed with an **echo** function.

```
echo(new jqmPhp());
```

For more information visit http://www.jqmphp.com .

**Minimalist Example**
```
<?php
    include 'lib/jqmPhp.php';
    $j = new jqmPhp();
    $j->addBasicPage('', 'Hello World', 'It\'s works!');
    echo $j;
?>
```

**Download**

http://code.google.com/p/jqmphp/downloads/detail?name=jqmphp-0.02.zip

**Bugs and Suggestions**

[jqmphp@googlegroups.com](http://groups.google.com/group/jqmphp)