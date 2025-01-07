## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.


display:"swap" 解决字体不显示的问题

next.js 中，布局可以进行共享，在多个页面中共享 

目录就是映射的路径  /app 下的 page.tsx 是代表根路径
                  /app/dashboard  文件下的 page.tsx  代表的路径是 /dashboard

可以在根组件下设置样式，那么根组件下的所有子组件都共享这个设置的样式   

.env 中存储的是数据库的链接

继承数据库，seed 文件夹下是初始化数据库中的表，并且为表填写字段

            query 下的是去执行sql，返回查询语句
            
            在export 导出语句里边写的 东西就是 在访问路由的时候需要执行的方法
