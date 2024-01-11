## **sans merde / no shit / без говна**

![image from Conann, 2023](https://github.com/sansmerde/sansmerde.github.io/assets/156181842/6e27578b-8ba7-482d-9284-ed3b47498214)

texts on social sciences methodology, epistemology, knowledge politics, anti-philosophy, and anti-authoritarian/anti-fascist activism

in english и на российском языке

сырые тексты сначала появляются в [телеграм-канале](https://t.me/sans_merde)

```
<ul>
  {% for tag in site.tags %}
  {% assign t = tag | first %}
    <li><a href="/{{ site.tag_page_dir }}/{{ t | slugify: 'pretty' }}/">{{ t }}</a></li>
  {% endfor %}
</ul>
```
