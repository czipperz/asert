#ASERT Keyboard Layout

We want to take the QWERTY keyboard and vertically realign it to be more efficient.

Middle row is prioritized over top and top over bottom.

##Normal Qwerty

	Tab q w e r t y u i o p
	CpL a s d f g h j k l ;
	Shf z x c v b n m , . /

##Groups

Vertical letter groups. We will use these to change things up.

	qaz  wsx  edc  rfv  tgb  yhn  ujm  ik,  ol.  p;/

#Layouts

There are three layouts.

* `asert`		takes the most common letters in each columns and puts them on the home row. Then the second
most common goes in the top row. It is explained more below.
* `asert-pure`	swaps the top and middle rows (includes semicolon)
* `asert-swap`	swaps the top and middle rows (DOES NOT INCLUDE a & s, q & w, ; & p)

##ASERT

###Frequencies

Most common typed words:

	e t a o i n s h r d l c u m w f g y p b v k j x q z

![Chart](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b0/English_letter_frequency_%28frequency%29.svg/640px-English_letter_frequency_%28frequency%29.svg.png)

However with the populization of the QWERTY keyboard it makes more sense to keep more keys consistent rather than radically changing it.

<pre>
Tab q w <b><i>d</i></b> <b><i>f</i></b> <b><i>g</i></b> y <b><i>j</i></b> <b><i>k</i></b> <b><i>l</i></b> <b><i>;</i></b>
<b><i>DEL</i></b> a s <b><i>e</i></b> <b><i>r</i></b> <b><i>t</i></b> h <b><i>u</i></b> <b><i>i</i></b> <b><i>o</i></b> <b><i>p</i></b>
Shf z x c v b n m , . /
</pre>

####So what changed?

* d and e	switched places (`e d c` => `d e c`)
* f and r	switched places (`r f v` => `f r v`)
* g and t	switched places (`t g b` => `g t b`)
* u and j	switched places (`u j m` => `j u m`)
* k and i	switched places (`i k ,` => `k i ,`)
* l and o	switched places (`o l .` => `l o .`)
* ; and p	switched places (`p ; /` => `; p /`)
* CapsLock makes DELETE. Shift CapsLock makes ESCAPE!

The first two and the sixth columns and the bottom row is still the same!
