##Sandbox


###goals:

1. *play around*<br/>
2. waste time<br/>

###linking
[The link](http://en.wikipedia.org/wiki/Kitten#mediaviewer/File:Kitten_in_Rizal_Park,_Manila.jpg)

####html
<table>
<tr>
	<td>x</td>
	<td>o</td>
	<td></td>	
</tr>
<tr>
	<td>o</td>
	<td>o</td>
	<td></td>
</tr>
<tr>
	<td>x</td>
	<td>x</td>
	<td>x</td>
</tr>
</table>

###code
```ruby
def count_fib x, pp, p 
	if x == 2
		p + pp
    else
	   count_fib x - 1, p, p + pp
	end
end
def fib x
    neg = x < 0 ? -1 : 1
	x = x * neg
	if x == 0 || x == 1
		neg * x
	else
		neg * (count_fib x, 0 ,1)
	end
end
```

(-10..10).each { |x| print "#{x}:#{(fib x)} " }
`

####quotes:

> You become responsible, forever, for what you have tamed.<br/>
