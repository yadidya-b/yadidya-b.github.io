---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi!
I'm **B. Yadidya**, a Senior Research Fellow (PhD candidate) at the [Centre for Atmospheric Sciences](https://cas.iitd.ac.in/), [Indian Insitute of Technology Delhi](https://home.iitd.ac.in/).
My PhD is funded by the Department of Science and Technology, India under the INSPIRE fellowship. 
I worked on the **"Variability of Internal waves in the Andaman Sea"** under the supervision of [Prof. A. D. Rao](https://web.iitd.ac.in/~adrao/) and [Prof. Vimlesh Pant](https://web.iitd.ac.in/~vimlesh/). I submitted by thesis in October 2022. 
During my PhD, I've looked at the variability of internal waves across multiple timescales ranging from [diurnal](https://www.nature.com/articles/s41598-021-90426-w), [seasonal](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2021JC018321), [interannual](https://www.nature.com/articles/s41598-022-15301-8) to [climate](https://www.nature.com/articles/s43247-022-00574-8) scales in one of the hotspot regions for large-amplitude internal waves - the Andaman Sea. 


---
<span style="color:red"> ***I'm currently searching for a post-doc position*** </span>


---

# Publications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}