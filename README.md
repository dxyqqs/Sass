# Sass
Sass学习

###unit.scss
    @mixin  query($query)  针对屏幕和三种设备尺寸进行的媒体查询
            $query   phone      手机
                     tablet     平板
                     desktop    PC
                     [condition] 自定媒体条件
            @content CSS样式
    
    @mixin  fontFace  引入web字体
            $name web字体定义名称
            $path 字体路径，不包含字体格式名
            @content CSS样式

    @mixin  triangle CSS生成三角形
            $width  箭头顶端到底部的宽度
            $height 箭头高度
            $color  箭头的颜色
            $direct 箭头朝向