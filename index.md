<h2>{{ site.data.samplelist.docs_list_title }}</h2>
<ul>
   {% for item in site.data.samplelist.docs %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
   {% endfor %}
</ul>

## About Us

The Honeynet Project is an international non-profit (501c3) research organisation dedicated to investigate the latest attacks and develop open source tools to improve cybersecurity. 

### Our Mission

To learn the tools, tactics, and motives involved in cyber attacks, and share the lessons learned. 

### Our 3 Main Pillars

#### Research
#### Tools
#### Awareness