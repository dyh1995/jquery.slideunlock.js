jquery.slideunlock.js
==================================

a slideunlock plugin based on jQuery

### Param(参数说明)
#####   SliderUnlock(elm, options, success){}
1.        elm ： 元素
2.        options ： 初始化设置
3.        success ： 解锁成功回调函数

### How to use(使用方法)

#####   example： 
             <div id="slider">
                 <div id="slider_bg"></div>
                 <span id="label">>></span>
                 <span id="labelTip">请按住滑块，拖动到最右边</span>
             </div>

            <script>
                $(function () {
                    var slider = new SliderUnlock("#slider", {}, function () {
                    });
        
                    slider.init();
                })
            </script>
        
#####   options：
1.     successLabelTip ：解锁后提示文字   
2.     duration ：动画持续时间   

### Attention(注意事项)
