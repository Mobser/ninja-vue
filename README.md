# ninja-vue
我想我可以自己写一个我喜欢的有关django和vue的后台管理系统

#### 背景

- 目前有关django和vue的优秀项目有很多,它们的功能都很强大
- 它们大多采用的是[Django REST framework](https://www.django-rest-framework.org/)(以下简称drf)来构建的Web API
- 不得不承认使用极少的代码就可以很优雅的实现RESTful风格的api
- 但随着开发日渐深入各个模块都需要编写自定义方法来取代drf默认的功能,这是一件令人十分头疼的事情
- 在这里我要承认,我对drf并没有太多的熟练度,以致于我在重写某些方法的时候总是在挠头

#### 目标

- 最近我在学习[django-ninja](https://django-ninja.rest-framework.com/),并尝试将其作为默认构建Web API的工具
- vue使用3.x版本, 并使用TypeScript
- UI组件库使用Element Plus
- 支持定时任务
- 支持WebSocket
- 尽量写好每一句注释,避免出现代码写完后只有神仙才知道具体实现了什么功能
- 我是一名站在了巨人肩膀上的无名小卒,做这些也仅仅是为了达到更好的学习效果
