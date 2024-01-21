### RobertLD's worthless ramblings
This is the collection of my thoughts, and things that my interest has been piqued in recently


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
