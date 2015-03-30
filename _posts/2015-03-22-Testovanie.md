---
layout: post
title: Testovanie
categories: zdravie
---


Tak zvany `Toto je citacia kde sa pouzil iba jeden znak na rozdiel od carpetu.
Automaticky mi to generuje ako <code> object`

***

<br/>

Yesterday, [the autobiographical post I wrote for The
Setup](http://tom.preston-werner.usesthis.com/) went live. I wrote that post
over a year ago and then entered into an epic battle with
[@waferbaby](http://twitter.com/#!/waferbaby) about the length of my "Who are
you, and what do you do?" section. He said it was too long. I said it could
not be . And so the post sat for a 

> - Čo sa stane ak  toto bude ruzove? Aj s line breakom cez `<br/>` mi

> - beria html object - no VYBORNE !!!


```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
bolog

    return now iand text int

blog

    toto fungueje teiz

```ruby
alert('hello');
```

    return now iand text int


**bold** __italic__ 
About a month ago I decided that it was foolish to let the words I had written rot on my hard d
rive and so I did the only thing I knew how to do: overreact. So I cut the original nine-hundre
d words of my bio down to fourteen words and resubmitted it to Daniel. Those are the words you see in the post now.

```bash
$ git clone git://github.com/hugomaiavieira/pygments-style-github.git

$ cd pygments-style-github/

$ (sudo) python setup.py install

$ pygmentize -S github -f html > syntax.css
```

niecoc

```sh
$ grep -Ril 'markdown' 
```

{% highlight bash %} $ pwd home/majo {% endhighlight %}
nieco

    $ npm i -g gulp

<br/>

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |


return

{% highlight ruby %}
return "Hello!";
def(i):
    for i in range(0,5):
        print(i)
{% endhighlight %}

retur


{% highlight ruby %} return "Hello!"; {% endhighlight %}

Posts handled in a special way by Jekyll. The date you specify in the filename is used to 
construct the URL in the generated site. This post, for instance, ends up at
<code>http://tom.preston-werner.com/2008/11/17/blogging-like-a-hacker.html</code>.

Files that do not reside in directories prefixed with an underscore are mirrored into a corresp
onding directory structure in the generated site. If a file does not have a YAML preface, it is
not run through the Liquid interpreter. Binary files are copied over unmodified.

<pre class="terminal"><code>$ jekyll /path/to/raw/site /path/to/place/generated/site</code></pre>

<code>$ jekyll /path/to/raw/site /path/to/place/generated/site</code>

nejakye text

## Novy titul

nejaky text

    $ jekyll /path/to/raw/site /path/to/place/generated/site

dalsi text

{% highlight ruby %}
# Public: Duplicate some text an abitrary number of times.
#
# text  - The String to be duplicated.
# count - The Integer number of times to duplicate the text.
#
# Examples
#
#   multiplex('Tom', 4)
#   # => 'TomTomTomTom'
#
# Returns the duplicated String.
def multiplex(text, count)
    text * count
    return(text)
print(count)
{% endhighlight %}

Hele dalsi kod

{% highlight ruby %}
klass = Class.new
{% endhighlight %}

Takze tu je python doplnovanie

```python
@require
for i in range(0,5):
    l = []
    l.append(i)

# comment
class something
print(i)

def multiple(text, count)
    text * count
    return(text)
print(count)
```

{% highlight r %}
# tak tu mame R-kovy kod
library(ggplot2)

centre <- function(x, type, ...) {
  switch(type,
         mean = mean(x),
         median = median(x),
         trimmed = mean(x, trim = .1))
}

myVar1
myVar.2
data$x
foo "bar" baz
# test "test"
"test # test"

(123) (1) (10) (0.1) (.2) (1e-7)
(1.2e+7) (2e) (3e+10) (0x0) (0xa)
(0xabcdef1234567890) (123L) (1L)
(0x10L) (10000000L) (1e6L) (1.1L)
(1e-3L) (4123.381E-10i)
(3.) (3.E10) # BUG: .E10 should be part of number
{% endhighlight %}

```r
clean <- data.frame(old = c("[()-,]","std","BodyBody","mean"), new =
c("","Std", "Body","Mean"))
# clean the features labels through lapply with gsub conditions - change
# old variables for new variables
g <- lapply(1:4, function(x) features[, label := gsub(clean$old[x],
clean$new[x], label)])
# change train_test colnames as sucject, activity and features label names
setnames(train_test, c("subject", "activity", features$label))
library(data.table)
# create data table for merging propdmgexp
prop_token <- data.table(propdmgexp = c("K", "M", "B"), dollars =
as.numeric(c("1000", "10e5", "10e8")))

# merge and convert propdmgexp tokens into dollars
prop_merge <- merge(prop_token, data, by = "propdmgexp")

prop_merge
```

 
 
```{r setup, echo=FALSE, message=FALSE}
## Change if you want other options
require("knitr")
opts_chunk$set(fig.width=5, fig.height=5, cache=TRUE)
 
## Load knitcitations with a clean bibliography
library(knitcitations)
cleanbib()
cite_options(tooltip=TRUE)
 
## I made my own citing function since citep() doesn't work like I want to with
## urls that are not really pages themselves like part of a GitHub repo.
mycitep <- function(x, short=NULL, year=substr(date(), 21, 24), tooltip=TRUE) {
res <- tmp <- citep(x)
if(!is.null(short)) {
res <- gsub("></a>", paste0(">", short, "</a>"), tmp)
}
if(tooltip) {
res <- gsub("\\?\\?\\?\\?", year, res)
}
res <- gsub("span> ", "span>", res)
res
}
 
## Here's an example
# mycitep("https://github.com/lcolladotor/lcollado753", "Collado, 2013")
```
```{r bibsetup, echo=FALSE, message=FALSE, warning=FALSE}
write.bibtex(c("knitcitations" = citation("knitcitations")), file = "pkgs.bib")
bib <- read.bibtex("pkgs.bib")
```
 
 
 
Start post
 
 
### References
 
Citations made with `knitcitations` `r mycitep(bib[["knitcitations"]], "Boettiger, 2013")`.
 
 
```{r bibliography, results='asis', echo=FALSE, cache=FALSE}
## Print bibliography
bibliography()
```
 
### Reproducibility
 
```{r reproducbility}
sessionInfo()
``` 
