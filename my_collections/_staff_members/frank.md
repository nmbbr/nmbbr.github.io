---
title: frank doe
name: Frank Doe
position: Designer 
image: /assets/img/staff_members/frank-doe.jpg

---


## Frank Doe aka LSS 101


<div id='product-component-1637023204556'></div>
<script type="text/javascript">
/*<![CDATA[*/
(function () {
  var scriptURL = 'https://sdks.shopifycdn.com/buy-button/latest/buy-button-storefront.min.js';
  if (window.ShopifyBuy) {
    if (window.ShopifyBuy.UI) {
      ShopifyBuyInit();
    } else {
      loadScript();
    }
  } else {
    loadScript();
  }
  function loadScript() {
    var script = document.createElement('script');
    script.async = true;
    script.src = scriptURL;
    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(script);
    script.onload = ShopifyBuyInit;
  }
  function ShopifyBuyInit() {
    var client = ShopifyBuy.buildClient({
      domain: 'number-shirts.myshopify.com',
      storefrontAccessToken: 'ecdff15321044e9d50802317cf5b5046',
    });
    ShopifyBuy.UI.onReady(client).then(function (ui) {
      ui.createComponent('product', {
        id: '7434305241313',
        node: document.getElementById('product-component-1637023204556'),
        moneyFormat: '%24%7B%7Bamount%7D%7D',
        options: {
  "product": {
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "100%",
          "margin-left": "0",
          "margin-bottom": "50px"
        },
        "text-align": "left"
      },
      "title": {
        "font-size": "26px"
      },
      "button": {
        "font-size": "17px",
        "padding-top": "16.5px",
        "padding-bottom": "16.5px",
        "color": "#e7e420",
        ":hover": {
          "color": "#e7e420",
          "background-color": "#cb6b36"
        },
        "background-color": "#e1773c",
        ":focus": {
          "background-color": "#cb6b36"
        },
        "border-radius": "0px"
      },
      "quantityInput": {
        "font-size": "17px",
        "padding-top": "16.5px",
        "padding-bottom": "16.5px"
      },
      "price": {
        "font-size": "18px"
      },
      "compareAt": {
        "font-size": "15.299999999999999px"
      },
      "unitPrice": {
        "font-size": "15.299999999999999px"
      }
    },
    "layout": "horizontal",
    "contents": {
      "img": false,
      "imgWithCarousel": true,
      "description": true
    },
    "width": "100%",
    "text": {
      "button": "Add to cart"
    }
  },
  "productSet": {
    "styles": {
      "products": {
        "@media (min-width: 601px)": {
          "margin-left": "-20px"
        }
      }
    }
  },
  "modalProduct": {
    "contents": {
      "img": false,
      "imgWithCarousel": true
    },
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "100%",
          "margin-left": "0px",
          "margin-bottom": "0px"
        }
      },
      "button": {
        "font-size": "17px",
        "padding-top": "16.5px",
        "padding-bottom": "16.5px",
        "color": "#e7e420",
        ":hover": {
          "color": "#e7e420",
          "background-color": "#cb6b36"
        },
        "background-color": "#e1773c",
        ":focus": {
          "background-color": "#cb6b36"
        },
        "border-radius": "0px"
      },
      "quantityInput": {
        "font-size": "17px",
        "padding-top": "16.5px",
        "padding-bottom": "16.5px"
      },
      "title": {
        "font-family": "Helvetica Neue, sans-serif",
        "font-weight": "bold",
        "font-size": "26px",
        "color": "#4c4c4c"
      },
      "price": {
        "font-family": "Helvetica Neue, sans-serif",
        "font-weight": "normal",
        "font-size": "18px",
        "color": "#4c4c4c"
      },
      "compareAt": {
        "font-family": "Helvetica Neue, sans-serif",
        "font-weight": "normal",
        "font-size": "15.299999999999999px",
        "color": "#4c4c4c"
      },
      "unitPrice": {
        "font-family": "Helvetica Neue, sans-serif",
        "font-weight": "normal",
        "font-size": "15.299999999999999px",
        "color": "#4c4c4c"
      }
    },
    "text": {
      "button": "Add to cart"
    }
  },
  "option": {},
  "cart": {
    "styles": {
      "button": {
        "font-size": "17px",
        "padding-top": "16.5px",
        "padding-bottom": "16.5px",
        "color": "#e7e420",
        ":hover": {
          "color": "#e7e420",
          "background-color": "#cb6b36"
        },
        "background-color": "#e1773c",
        ":focus": {
          "background-color": "#cb6b36"
        },
        "border-radius": "0px"
      },
      "cart": {
        "background-color": "#b1a0a0"
      },
      "footer": {
        "background-color": "#b1a0a0"
      }
    },
    "text": {
      "title": "Cartppppp",
      "total": "Subtotal",
      "empty": "Your cart is emptypo09",
      "notice": "Shipping and discount codes are added at checkout.\nthanks for fdfafafd",
      "button": "Checkoutlkk",
      "noteDescription": "Special instructions for seller.yablfaopafdsfsdfsdfsfdsfs dsfsdfsdfdsfsf\nfsdfdsfsfs\ndsfsfsfsf\n"
    },
    "contents": {
      "note": true
    },
    "popup": false
  },
  "toggle": {
    "styles": {
      "toggle": {
        "background-color": "#e1773c",
        ":hover": {
          "background-color": "#cb6b36"
        },
        ":focus": {
          "background-color": "#cb6b36"
        }
      },
      "count": {
        "font-size": "17px",
        "color": "#e7e420",
        ":hover": {
          "color": "#e7e420"
        }
      },
      "iconPath": {
        "fill": "#e7e420"
      }
    }
  }
},
      });
    });
  }
})();
/*]]>*/
</script>