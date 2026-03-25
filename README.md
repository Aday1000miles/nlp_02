# nlp_02

1、环境切换
打开conda终端，先激活nlp_***环境。
2、依赖安装
pip install jieba安装Jieba分词库。
3、目录与文件创建
新建作业二项目（不要复用作业一的！），在项目目录下启动jupyter notebook，新建main_jieba.ipynb文件。
4、Jupyter Notebook单元格类型的切换
第一个单元格放“结巴分词实践”一级标题，第二个单元格放“结巴分词的三种模式”二级标题
Jupyter中Markdown的操作方法可参考：https://www.jb51.net/python/313228k2j.htm 
5、分词模式实践
参考jieba仓库（GitHub：https://github.com/fxsjy/jieba 、Gitee：https://gitee.com/fxsjy/jieba）README里的示例，
	在“精确模式”三级标题下，对句子“我来到北京清华大学”执行精确模式分词。
	在“全模式”三级标题下，对句子“我来到北京清华大学”执行全模式分词。
	在“搜索引擎模式”三级标题下，对句子“小明硕士毕业于中国科学院计算所，后在日本京都大学深造”执行搜索引擎模式分词。
示例：
 
6、自定义词典配置
参考README中指定自定义词典方法，创建userdict.txt文件，按格式把你的姓名加进去。
格式参考：
GitHub：https://github.com/fxsjy/jieba/blob/master/test/userdict.txt
Gitee：https://gitee.com/fxsjy/jieba/blob/master/test/userdict.txt 
注意确保文件路径正确，避免路径错误导致加载失败。
7、词典加载验证
在“载入词典”二级标题下，使用jieba.cut方法，设置参数HMM=False，对句子“***（你的姓名）即将是自然语言处理方面的高手。”进行分词，确保姓名部分被正确切分。
示例：
 
要求
	不要复用作业一的目录，请新建项目目录！
	所有代码单元格下方需显示运行结果。
	载入词典部分出现非本人名字则整个作业二无效
	等待与任务四一起作为作业二上传至GitHub/Gitee。
