# nft-preview-card-component-main


### Links

- Solution URL: 
- Live Site URL: 


Web width 1440px:
![image](https://user-images.githubusercontent.com/51845541/191851628-766e1fe8-047d-4a9e-80ba-cea7eea11963.png)


Mobile width 375px:

![image](https://user-images.githubusercontent.com/51845541/191851358-e1f8186b-349a-4c3e-9ce7-28a3b17516e0.png)


- Semantic HTML5 markup
- CSS custom properties
- Bootstrap
- Flexbox

### What I learned
Como utlizar hover
```css
.div-imagenes {
  position: relative;
  width: 100%;
  background-color: #00fff7;
}

.img-cubo {
  opacity: 1;
  display: block;
  width: 100%;
  height: auto;
  transition: 0.5s ease;
  -webkit-backface-visibility: hidden;
          backface-visibility: hidden;
}

.div-ojo {
  transition: 0.1s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  text-align: center;
}

.div-imagenes:hover .img-cubo {
  opacity: 0.3;
  cursor: pointer;
}

.div-imagenes:hover .div-ojo {
  opacity: 1;
}

```


## Author
- Frontend Mentor - [@Sebaplz](https://www.frontendmentor.io/profile/Sebaplz)
