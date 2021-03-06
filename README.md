# xlayout
自定义Android常用组件（包括一些常用属性:圆角、边框等）
#### 使用
```gradle
  //添加依赖
  implementation 'com.github.bingoloves:xlayout:1.0.2'
```
```xml
        <declare-styleable name="XUILayout">
              <attr name="android:maxWidth" />
              <attr name="android:maxHeight" />
              <attr name="android:minWidth" />
              <attr name="android:minHeight" />
              <!--底部分割线的高度，默认0-->
              <attr name="bottomDividerHeight" format="dimension" />
              <!--底部分割线的颜色，默认R.attr.xui_config_color_separator_light-->
              <attr name="bottomDividerColor" format="color|reference" />
              <!--底部分割线左侧的边距，默认0-->
              <attr name="bottomDividerInsetLeft" format="dimension" />
              <!--底部分割线右侧的边距，默认0-->
              <attr name="bottomDividerInsetRight" format="dimension" />
              <!--顶部分割线的高度，默认0-->
              <attr name="topDividerHeight" format="dimension" />
              <!--顶部分割线的颜色，默认R.attr.xui_config_color_separator_light-->
              <attr name="topDividerColor" format="color|reference" />
              <!--顶部分割线左侧的边距，默认0-->
              <attr name="topDividerInsetLeft" format="dimension" />
              <!--顶部分割线右侧的边距，默认0-->
              <attr name="topDividerInsetRight" format="dimension" />
              <!--左侧分割线的高度，默认0-->
              <attr name="leftDividerWidth" format="dimension" />
              <!--左侧分割线的颜色，默认R.attr.xui_config_color_separator_light-->
              <attr name="leftDividerColor" format="color|reference" />
              <!--左侧分割线顶部的边距，默认0-->
              <attr name="leftDividerInsetTop" format="dimension" />
              <!--左侧分割线底部的边距，默认0-->
              <attr name="leftDividerInsetBottom" format="dimension" />
              <!--右侧分割线的高度，默认0-->
              <attr name="rightDividerWidth" format="dimension" />
              <!--右侧分割线的颜色，默认R.attr.xui_config_color_separator_light-->
              <attr name="rightDividerColor" format="color|reference" />
              <!--右侧分割线顶部的边距，默认0-->
              <attr name="rightDividerInsetTop" format="dimension" />
              <!--右侧分割线底部的边距，默认0-->
              <attr name="rightDividerInsetBottom" format="dimension" />
              <!--圆角度数，默认0-->
              <attr name="radius" format="dimension" />
              <!--边框颜色，默认0-->
              <attr name="borderColor" format="color" />
              <!--边框宽度，默认1px-->
              <attr name="borderWidth" format="dimension" />
              <!--21版本下，裁剪圆角边框的镂空颜色-->
              <attr name="outerNormalColor" format="color|reference" />
              <!--隐藏圆角的类型，默认none-->
              <attr name="hideRadiusSide" format="enum">
                  <enum name="none" value="0" />
                  <enum name="top" value="1" />
                  <enum name="right" value="2" />
                  <enum name="bottom" value="3" />
                  <enum name="left" value="4" />
              </attr>
              <!--是否显示边框-->
              <attr name="showBorderOnlyBeforeL" format="boolean" />
              <!--阴影的大小，默认0-->
              <attr name="shadowElevation" format="dimension" />
              <!--是否使用主题的阴影大小，默认是false,主题默认阴影大小是14dp-->
              <attr name="useThemeGeneralShadowElevation" format="boolean" />
              <!--阴影的透明度，默认0.25-->
              <attr name="shadowAlpha" format="float" />
              <!--轮廓的顶部边距-->
              <attr name="outlineInsetTop" format="dimension" />
              <!--轮廓的左侧边距-->
              <attr name="outlineInsetLeft" format="dimension" />
              <!--轮廓的右侧边距-->
              <attr name="outlineInsetRight" format="dimension" />
              <!--轮廓的底部边距-->
              <attr name="outlineInsetBottom" format="dimension" />
              <!--轮廓是否使用内边距-->
              <attr name="outlineExcludePadding" format="boolean" />
          </declare-styleable>
```
