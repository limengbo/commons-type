2015-6-9 21:55:27
【1】.如果某一个类型是默认类型，应这样书写：以“DEFAULT_”为前缀。例如：
String com.lofter.youyoulearning.quxinyong.constant.WebFormEncType.DEFAULT_TEXT = "text/plain"


【2】.如果某个类中的类型比较多，应该使用前缀进行分类。例如：
public static final String MS_DOC="application/msword";
	public static final String MS_XLS="application/vnd.ms-excel";
	public static final String MS_PPT="application/vnd.ms-powerpoint";
	public static final String MS_DOCX="application/vnd.openxmlformats-officedocument.wordprocessingml.document";
	public static final String MS_XLSX="application/vnd.openxmlformats-officedocument.spreadsheetml.sheet";
	public static final String MS_PPTX="application/vnd.openxmlformats-officedocument.presentationml.presentation";
	public static final String MS_DOTX="application/vnd.openxmlformats-officedocument.wordprocessingml.template";
	public static final String MS_VISIO="application/vnd.viso";
	
【3】
