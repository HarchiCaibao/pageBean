# pageBean
使用Java加JavaScript实现分页功能

1、通过一个JavaBean来保存分页信息，具体属性如下：
  private int currentPage;//当前页数
	private int total; //总记录数
	private int pageSize;//每页记录数，page size
	private List<T> beanList;//当前页的记录内容
2、在前端页面使用JavaScript解析分页信息，形成分页条，实现点击上一页，下一页的功能。
	
3、需要在Servlet中指定每页显示的记录条数，供dao使用。
