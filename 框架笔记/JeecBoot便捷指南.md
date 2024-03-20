###Excel

#####Excel导入

详细内容可以访问：[jeecgboot 新建子模块 使用@EXCEL实现实现导入导出功能](https://blog.csdn.net/intmainreturn/article/details/136560849)

> 首先，要在实体类这里动手脚，要导出的字段上加上@Excel注解，注解里是name和width参数，代表 方格名称和方格宽度
> 
> 其次，你要做好你自己的代码排序
> 
> 然后，生成一个 ModelAndView 对象，例如：`ModelAndView mv = new ModelAndView(new JeecgEntityExcelView());`
> 
> 最后，给 Mav 对象完善数据，例如：文件名、导出详情






