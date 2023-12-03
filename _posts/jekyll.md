---
 layout: page                  # or any appropriate layout 
 category: topic-a
 ---

{% for entry in site.posts %}
   {% if entry.category == type-a %}
      <!-- do A stuff -->
   {% elsif entry.category == type-b %}
      <!-- do B stuff -->
   {% endif %}
{% endfor %}
