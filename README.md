# product-card

### my name is sematary

![my photo](https://i.pinimg.com/736x/ed/16/c0/ed16c04e92dbeee65ecd5d9046ac95ea.jpg)

*There is example of my code:*
```javascript
  class Product {
    productName;
    imgLink;
    productPrice;
    constructor(name, price, link){
        this.productName = name;
        this.imgLink = link;
        this.productPrice = price;
        const prod = document.createElement("div");
        prod.innerHTML = `<h1>${this.productName}</h1><h2>${this.productPrice}</h2><img src="${this.imgLink}"><button>купить</button>`
        document.body.append(prod);
    }
}


new Product("shoes", 120, "https://www.barkershoes.com/cdn/shop/files/SS20_HOMEPAGE_MCCLEANPAIR_880x550_crop_center.jpg?v=1614334815");
```

This is Unordered list:
*[my facebook](https://github.com)

