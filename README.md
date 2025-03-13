## структура проекта
```splive-react-clone/
├── public/
│   ├── favicon.ico (скопировать с оригинального сайта)
│   ├── index.html
│   └── assets/ (для статических изображений)
├── src/
│   ├── assets/
│   │   ├── images/ (все изображения с сайта)
│   │   └── fonts/ (шрифты с сайта)
│   ├── components/
│   │   ├── common/
│   │   │   ├── Header/
│   │   │   ├── Footer/
│   │   │   ├── Breadcrumbs/
│   │   │   └── Navigation/
│   │   ├── home/
│   │   │   ├── Banner/
│   │   │   ├── PopularProducts/
│   │   │   ├── AboutNumbers/
│   │   │   ├── BlogSection/
│   │   │   └── ContactSection/
│   │   ├── catalog/
│   │   │   ├── ProductCard/
│   │   │   ├── ProductList/
│   │   │   ├── CategoryList/
│   │   │   └── Filters/
│   │   ├── product/
│   │   │   ├── ProductGallery/
│   │   │   ├── ProductSpecs/
│   │   │   └── RelatedProducts/
│   │   ├── contact/
│   │   │   ├── ContactInfo/
│   │   │   └── Map/
│   │   └── ui/ (переиспользуемые UI компоненты)
│   │       ├── Button/
│   │       ├── Input/
│   │       ├── Modal/
│   │       └── Dropdown/
│   ├── pages/
│   │   ├── HomePage.jsx
│   │   ├── CatalogPage.jsx
│   │   ├── CategoryPage.jsx
│   │   ├── ProductPage.jsx
│   │   ├── ContactPage.jsx
│   │   ├── AboutPage.jsx
│   │   ├── ServicesPage.jsx
│   │   ├── BlogPage.jsx
│   │   └── NotFoundPage.jsx
│   ├── services/ (API и другие сервисы)
│   │   ├── api.js
│   │   └── cartService.js
│   ├── context/
│   │   ├── CartContext.jsx
│   │   └── CatalogContext.jsx
│   ├── hooks/
│   │   ├── useResponsive.js
│   │   └── useScrollPosition.js
│   ├── utils/
│   │   ├── formatPrice.js
│   │   └── validators.js
│   ├── routes.jsx (маршрутизация)
│   ├── App.jsx
│   ├── index.jsx
│   └── styles/
│       ├── global.css
│       ├── variables.css
│       └── mixins.css
└── package.json```
