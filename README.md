#ASERT Keyboard Layout

We want to take the QWERTY keyboard and vertically realign it to be more efficient.

Middle row is prioritized over top and top over bottom.

##Groups

Vertical letter groups. We will use these to change things up.

	qaz  wsx  edc  rfv  tgb  yhn  ujm  ik,  ol.  p;/

#Layouts

There are three layouts.

* `asert`		takes the most common letters in each columns and puts them on the home row. Then the second
most common goes in the top row. It is explained more below.
* `asert-pure`	swaps the top and middle rows (includes semicolon)
* `asert-swap`	swaps the top and middle rows (DOES NOT INCLUDE a & s, q & w, ; & p)

##ASERT ("standard") explained

###Frequencies

Most common typed words:

	e t a o i n s h r d l c u m w f g y p b v k j x q z

![Chart](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b0/English_letter_frequency_%28frequency%29.svg/640px-English_letter_frequency_%28frequency%29.svg.png)

However with the populization of the QWERTY keyboard it makes more sense to keep more keys consistent rather than radically changing it.

###The layout

<pre>
Tab q w <b><i>d</i></b> <b><i>f</i></b> <b><i>g</i></b> y <b><i>j</i></b> <b><i>k</i></b> <b><i>l</i></b> <b><i>;</i></b>
<b><i>Ctrl</i></b> a s <b><i>e</i></b> <b><i>r</i></b> <b><i>t</i></b> h <b><i>u</i></b> <b><i>i</i></b> <b><i>o</i></b> <b><i>p</i></b>
Shift z x c v b n m , . /
<b><i>Hyper</b></i>
</pre>

###Normal Qwerty

<pre>
Tab q w <b><i>e</i></b> <b><i>r</i></b> <b><i>t</i></b> y <b><i>u</i></b> <b><i>i</i></b> <b><i>o</i></b> <b><i>p</i></b>
<b><i>Caps</i></b> a s <b><i>d</i></b> <b><i>f</i></b> <b><i>g</i></b> h <b><i>j</i></b> <b><i>k</i></b> <b><i>l</i></b> <b><i>;</i></b>
Shift z x c v b n m , . /
<b><i>Ctrl</i></b>
</pre>

###So what changed?

* d and e	switched places (`e d c` => `d e c`)
* f and r	switched places (`r f v` => `f r v`)
* g and t	switched places (`t g b` => `g t b`)
* j and u	switched places (`u j m` => `j u m`)
* k and i	switched places (`i k ,` => `k i ,`)
* l and o	switched places (`o l .` => `l o .`)
* ; and p	switched places (`p ; /` => `; p /`)
* CapsLock functions as Control.
* Control functions as Hyper, a key not on most modern keyboards, making it very useful for hotkeys.

The first two and the sixth columns and the bottom row is still the same!
