<h2>{{ site.data.samplelist.docs_list_title }}</h2>
<ul>
   {% for item in site.data.samplelist.docs %}
      <li><a href="{{ item.url }}">	  ![Page preview]({{ item.layout }})  </a></li>

   {% endfor %}
</ul>


![Page preview](/photos/mexico.jpg)