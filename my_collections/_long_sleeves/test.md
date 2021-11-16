---
layout: wrapper
title: test
name: test
permalink: /test/
product-id: 7449460080865
product-component-id: 1637031225779
---

<!----------BBBB capture section 1-------------->
{% capture first-section %}{{ page.product-id }}{% endcapture %}
<!----------EEEE capture section 1-------------->



<!----------BBBB capture section 2-------------->

{% capture second-section %}{{ page.product-component-id }}{% endcapture %}
<!----------EEEE capture section 2-------------->



<!----------BBBB include the template for multiple content insertions-------------->
{% include shopify-buybutton-template.html %}
<!----------EEEE include the template for multiple content insertions-------------->
