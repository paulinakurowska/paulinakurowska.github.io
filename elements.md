---
title: Projects
feature_text: |
  Here you will get an overview of my featuring projects
feature_image: "https://picsum.photos/2560/600?image=873"
excerpt: "Here you will get an overview of my featuring projects"
aside: true
---

# Cooperation on publications and research
- [Monitor:Vorerkrankungen mit erhöhtem Risiko für schwere COVID-19-Verläufe](https://wido.de/fileadmin/Dateien/Dokumente/News/Pressemitteilungen/2020/2020_Monitor_Vorerkrankungen_mit_erhoehtem_Risiko_fuer_schwere_COVID-19-Verlaeufe_final.pdf)          

- [Gesundheitsatlas](https://wido.de/publikationen-produkte/buchreihen/gesundheitsatlas/). 

# Data Visualisations
## Shiny 

- [Shiny for recent infections for COVID-19 in Germany](https://pkurowska.shinyapps.io/covid_app/?_ga=2.210297045.1525717498.1603123894-132976359.1603123894)
<iframe src="https://pkurowska.shinyapps.io/covid_app/?_ga=2.210297045.1525717498.1603123894-132976359.1603123894" 
          title="Shiny Dashboard COVID-19 active infections" width="100%" height="550" style="border:none;"></iframe>

More projects can be found at my {% include button.html text="my GitHub" link="https://github.com/paulinakurowska/" icon="github" %}.  


## HTML Includes

### Contact form

{% include site-form.html %}

``` html
{% raw %}{% include site-form.html %}{% endraw %}
```

### Demo map embed

{% include map.html id="1UT-2Z-Vg_MG_TrS5X2p8SthsJhc" title="Coffee shop map" %}

``` html
{% raw %}{% include map.html id="XXXXXX" title="Coffee shop map" %}{% endraw %}
```

### Button include

{% include button.html text="A button" link="https://david.darn.es" %}

{% include button.html text="A button with icon" link="https://twitter.com/daviddarnes" icon="twitter" %}

``` html
{% raw %}{% include button.html text="A button" link="https://david.darn.es" %}
{% include button.html text="A button with icon" link="https://twitter.com/daviddarnes" icon="twitter" %}{% endraw %}
```

### Icon include

{% include icon.html id="twitter" title="twitter" %} [{% include icon.html id="linkedin" title="twitter" %}](https://www.linkedin.com/in/daviddarnes)

``` html
{% raw %}{% include icon.html id="twitter" title="twitter" %}
[{% include icon.html id="linkedin" title="twitter" %}](https://www.linkedin.com/in/daviddarnes){% endraw %}
```

### Video include

{% include video.html id="zrkcGL5H3MU" title="Siteleaf tutorial video" %}

``` html
{% raw %}{% include video.html id="zrkcGL5H3MU" title="Siteleaf tutorial video" %}{% endraw %}
```


### Image includes

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Image with caption" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Right aligned image" position="right" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Left aligned image" position="left" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/1600/800?image=894" alt="Image with just alt text" %}

``` html
{% raw %}{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Image with caption" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Right aligned image" position="right" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Left aligned image" position="left" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/1600/800?image=894" alt="Image with just alt text" %}{% endraw %}
```
