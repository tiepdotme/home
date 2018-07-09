---
published: false
layout: product
permalink: /shop/test-series/
title: TEST
series: 800
type: spinning
price: "849.00"
description: The 800 series spinning reel is designed for heavy surf fishing and medium offshore duties.
long_description: |
  The 800 series spinning reel is IRT’s largest reel to date and is designed for heavy surf fishing and medium offshore duties, such as trolling for kingfish in the ocean. 

  This is the reel that will best handle larger wahoo, tuna, amberjack, shark, and gaffer sized mahi mahi. 
  
  Dual Drag increases the drag capacity to 55-65 lbs

braided-line-capacity: 
    - 490/65
    - 450/80
    - 390/100
mono-line-capacity:
    - 300/25
    - 190/40
    - 140/50
weight: 28 oz.
max-drag: 40 lbs.
dual-drag: 55-65 lbs.
gear-ratio:  4.78
bearings: 9
line-retrieval: 39 inches
image: /assets/images/products/800-spg-gold-gold.gif
fish: /assets/images/fish--shark.png
fish_recommendation:
    - Sharks   
    - Big Tarpon
    - Tuna 
    - Wahoo
photos:
  - /media/0-800-spg-l
  - /media/0-800-spg-b
  - /media/0-800-spg-f
  - /media/0-800-spg-r
---
<div id='collection-component-01dde8ad840'></div>
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
      domain: 'irt-reels.myshopify.com',
      apiKey: '370c0d56b9837807aef6962ddba4493f',
      appId: '6',
    });

    ShopifyBuy.UI.onReady(client).then(function (ui) {
      ui.createComponent('collection', {
        id: 60217753668,
        node: document.getElementById('collection-component-01dde8ad840'),
        moneyFormat: '%24%7B%7Bamount%7D%7D',
        options: {
  "product": {
    "variantId": "all",
    "contents": {
      "imgWithCarousel": false,
      "variantTitle": false,
      "description": false,
      "buttonWithQuantity": false,
      "quantity": false
    },
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "calc(25% - 20px)",
          "margin-left": "20px",
          "margin-bottom": "50px"
        }
      }
    }
  },
  "cart": {
    "contents": {
      "button": true
    },
    "styles": {
      "footer": {
        "background-color": "#ffffff"
      }
    }
  },
  "modalProduct": {
    "contents": {
      "img": false,
      "imgWithCarousel": true,
      "variantTitle": false,
      "buttonWithQuantity": true,
      "button": false,
      "quantity": false
    },
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "100%",
          "margin-left": "0px",
          "margin-bottom": "0px"
        }
      }
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
  }
}
      });
    });
  }
})();
/*]]>*/
</script>