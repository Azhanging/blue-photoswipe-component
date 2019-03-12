# blue-photoswipe-component

Photoswipe in vue

##Requirements

[PhotoSwipe](https://github.com/dimsemenov/PhotoSwipe)

##Use

####use in ES6

```javascript
import { photoSwipe, photoSwipeComponent } from 'blue-photoswipe-component';
Vue.use(photoSwipe,PhotoSwipeOptions);
Vue.component('blue-photoswipe-component',photoSwipeComponent);
```

####Vue directive

v-blue-photoswipe

```html
<div>
  <div>
    <img src="" alt="" v-blue-photoswipe="{photoswipeOptions,itemTagName:'DIV'}">  
  </div>
</div>
```

####about options itemTagName (default:'LI')
this option is closest img parentNode tagName same this itemTagName









