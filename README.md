# assignment2-swarna
# Swarna Ashok kumar
##### Cricket
**The game of cricket is a good exercise for the body, and  in the body Every muscle in the body makes strong and physically and mentally  very strong**, And a lot of sweat comes from the body, the patience in the body goes away and new **enthusiasm** comes again, that's why I am playing cricket
-------
# my favorite cricket team players
my favorite cricket team CSK

1. Jadeja.sr
2. Raina suresh
3. Dheepakv chahar
4. Ambatti rayadu
* Ms dhoni (wk)
* Ganguly
* Dravid
* Zahir khan

[Link to AboutMe](AboutMe.md)

----
## Countries that should be visited
The table's first column has country name. The second column has the reason to travel the country and the third column has the number of the days you should spend.
| Country | Travel reason | Days |
|---------|---------------|-------|
| Uganda | Economical | 20 |
| Singapore | Development | 365 |
| Srilanka | Nature | 10 |
| Argentina | Farming | 120

------
## Funny quotes
> “I love being married. It's so great to find that one special person you want to annoy for the rest of your life.” — *Rita Rudner*

> "I want my children to have all the things I couldn't afford. Then I want to move in with them.”
— *Phyllis Diller*

------
# 
> Ways to protect email on websites<https://stackoverflow.com/questions/308772/what-are-some-ways-to-protect-emails-on-websites-from-spambots>
```
<?php
	function php_split_js_make_email($phpemail)
	{
		$pieces = explode("@", $phpemail);
	
		echo '
			<script type="text/javascript">
				var a = "<a href=\'mailto:";
				var b = "' . $pieces[0] . '";
				var c = "' . $pieces[1] .'";
				var d = "\' class=\'email\'>";
				var e = "</a>";
				document.write(a+b+"@"+c+d+b+"@"+c+e);
			</script>
			<noscript>Please enable JavaScript to view emails</noscript>
		';
	}
?>
```
source for above code<https://css-tricks.com/snippets/php/email-protector/>