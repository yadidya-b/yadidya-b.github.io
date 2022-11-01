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
I'm B. Yadidya, a Senior Research Fellow (Ph.D. candidate) at the [Centre for Atmospheric Sciences](https://cas.iitd.ac.in/), [Indian Insitute of Technology Delhi](https://home.iitd.ac.in/).
My Ph.D. is funded by the Department of Science and Technology, India under the INSPIRE fellowship. 
I worked on the **"Variability of Internal waves in the Andaman Sea"** under the supervision of [Prof. A. D. Rao](https://web.iitd.ac.in/~adrao/) and [Prof. Vimlesh Pant](https://web.iitd.ac.in/~vimlesh/). I submitted by thesis in October 2022. 
During my PhD, I've looked at the variability of internal waves across multiple timescales ranging from diurnal, seasonal, interannual to climate scales in one of the hotspot regions for large-amplitude internal waves - the Andaman Sea. 


---

**I'm currently searching for a post-doc position**

---

# Publications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}