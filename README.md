#FreeDBlog#
FreeDBlog is an open source none-DB blog system based on ASP.NET 5.

All components are compatible with DNX 5.0 Core. You can deploy this application on any DNX 5.0 Core compatible operating system.

Before you using your blog system, you should configure your articles folder and app domain. Although this blog is DB free indeed, it based on http request and file system. Inner app domain and dependable inner network will enhance your blog rendering speed.

This blog system is really light -- you can only manage your posts using file manager such as FTP. Your article name is your file name and that is your article id too. So you can not put two articles which their titles are completely the same in spite of the fact that the content is different. I abandon it to make the blog rendering faster, because we find few people will do like that.
