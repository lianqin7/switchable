# History

---

## 1.0.0

`tag:fixed` [#20](https://github.com/aralejs/switchable/issues/20) Circular bugfix.

`tag:changed` 去除配置项 pauseOnHover, pauseOnScroll.

`tag:changed` 去除 obj.triggers/obj.panels, 以 obj.get('triggers')/obj.get('panels') 取代之

`tag:changed` 去除 new Obj() 之后的 render(). 对于 Switchable 来说, 不需要手工调用 render(), 直接 new 完就是初始状态.
不过如果用户再次调用 render(), 也没关系. render 中有判断是否已经 render 过, 也不会重复绑定事件和插入 DOM

## 0.9.15

`tag:improved` 升级 arale/widget@1.1.1

## 0.9.14

`tag:improved` 对 arale/widget 的依赖从 1.0.3 升级到 1.1.0 。

## 0.9.12

`tag:fixed` [#9](https://github.com/aralejs/switchable/issues/9) Carousel 上页滚屏的时候出现空白页。

`tag:fixed` [#10](https://github.com/aralejs/switchable/issues/10) className 可以通过配置取消。

`tag:improved` 依赖升级到 arale.widget@1.0.3 。

