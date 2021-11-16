---
layout: wrapper
title: test
name: test
permalink: /test/
product-id: 7449460080865
product-component-id: 1637031225779
---

<!----------BBBB content section 1-------------->
{% capture first-section %}

    Here is my first section content!
    {{ page.productid }}
{% endcapture %}
<!----------EEEE content section 1-------------->



<!----------BBBB content section 1-------------->

{% capture second-section %}

    Here is the second section!

{% endcapture %}
<!----------EEEE content section 1-------------->



<!----------BBBB include the template for multiple content insertions-------------->
{% include template-trash-2.html %}
<!----------EEEE include the template for multiple content insertions-------------->
