### jconfirm

### 使用方法
引用jconfirm.js和jconfirm.css
```js
 $('.example-p-1').on('click', function() {
            console.log($)
            $.alert({
                content: '确定下线该商品信息吗？',
                columnClass: 'col-md-622',
                closeIcon: true,
                confirm: function() {
                    alert('Okay action clicked.');
                }
            });
        });
```
### 兼容性
ie9+和主流的的浏览器