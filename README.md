# Statamic-Fancy-Ampersands
Turn those boring old ampersands into the stunning conjunctions of your dreams.

![](http://than.to/1en0L.png)

---------------------

#### Usage

Pipe Fancy Amps into your variable like any other modifier: `{{ content|fancyamps }}`

Fancy Amps takes any space-padded ampersand in your output and replaces it with ` <span class="fancyamp">&amp;</span> `. (The padding spaces remain intact.)

Add the following CSS into your site's theme and you so fancy.

`.fancyamp { color: inherit; font-size: inherit; font-family: Baskerville, Palatino, "Palatino Linotype", "Book Antiqua", "Constantia", serif; font-style:italic; }`

Don't like the look of Baskerville's **&amp;**? See [Use the Best Available Ampersand](http://simplebits.com/notebook/2008/08/14/ampersands-2/) for more suggestions.
