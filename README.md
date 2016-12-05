# Sass
Sass学习

###unit.scss
    @mixin  query($query)  针对屏幕和三种设备尺寸进行的媒体查询
            $query   phone      手机
                     tablet     平板
                     desktop    PC
            @content CSS样式

    @mixin  addPrefix 添加不同厂商前缀
            $addPrefix  webkit,moz,ms,o !default  默认厂商前缀
            $prop  属性名
            $value 属性值
            $type  添加方式 0 为属性值添加前缀  1 为属性名添加前缀，默认
    
    @mixin  fontFace  引入web字体
            $name web字体定义名称
            $path 字体路径，不包含字体格式名
            @content CSS样式