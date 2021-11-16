---
layout: wrapper
title: test
name: test
permalink: /test/
---

<!----------BBBB content section 1-------------->
{% capture first-section %}

    Here is my first section content!

{% endcapture %}
<!----------EEEE content section 1-------------->



<!----------BBBB content section 1-------------->

{% capture second-section %}

    Here is the second section!

{% endcapture %}
<!----------EEEE content section 1-------------->



<!----------BBBB include the template for multiple content insertions-------------->
{% include template-trash.html %}
<!----------EEEE include the template for multiple content insertions-------------->
