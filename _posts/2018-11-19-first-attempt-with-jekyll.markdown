---
title:  "First attempt with Jekyll! Erster Versuch mit Jekyll!"
date:   2018-11-19 21:15:02 +0100
categories: jekyll github
header:
  teaser: "/assets/images/img_building_sicily.jpg"
---

{% include figure image_path="/assets/images/img_building_sicily.jpg" %}

I have finally decided to make good use of GitHub Pages, for the following reasons (ordered in the priority of considerations):

- Write/publish decent articles
- Save on web hosting fees
- Learn [Github Pages][github-pages], [Jekyll][jekyllrb], [Bundler][bundler]
- Practise Web Design, Markdown
- Inplement [Jekyll themes][jekyll-themes] e.g. [Minimal Mistakes][minimal-mistakes]
- Blog using [Octopress][octopress]

And Jekyll offers powerful support for code snippets:

{% highlight ruby %}
def print_hw(name)
  puts "Hello World, #{name}"
end
print_hw('ahfant')
#=> prints 'Hello World, ahfant' to STDOUT.
{% endhighlight %}

***
_Auf Deutsch_
------

Ich habe mich schließlich entschieden, die GitHub-Pages aus folgenden Gründen sinnvoll zu gestalten (geordnet nach Priorität der Überlegungen):

- Schreiben/Publizieren anständiger Artikeln.
- Sparen der Webhosting-Kosten
- Lernen von [Github-Pages][github-pages], [Jekyll][jekyllrb], [Bundler][bundler]
- Übung von Webdesign, Markdown
- Implementierung von [Jekyll-Themen][jekyll-themes] z.B. [Minimal Mistakes][minimal-mistakes]
- Bloggen mit [Octopress][octopress]

Und Jekyll bietet leistungsstarke Unterstützung für Codeausschnitte:

{% highlight ruby %}
def print_hw(name)
  puts "Hallo Welt, #{name}"
end
print_hw('ahfant')
#=> 'Hallo Welt, ahfant' nach STDOUT ausdrucken.
{% endhighlight %}


[github-pages]: https://pages.github.com
[jekyllrb]: https://jekyllrb.com
[bundler]: https://bundler.io
[jekyll-themes]: https://jekyllthemes.io
[minimal-mistakes]: https://mmistakes.github.io/minimal-mistakes
[octopress]: https://github.com/octopress/octopress