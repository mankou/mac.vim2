# ,ma 临时自定义系列

# ,mt 时间系列
* ,mt 设置快速插入当前日期及时间
* ,mtt 设置快速插入当前时间的快捷键

# ,mf 文件名系列
* ,mft 插入文件名不包含路径 
* ,mfp 插入文件名包含路径
* ,mfs 快速在sql文件中插入文件名 如prompt BU_CHANGE_STORE_PLAN.sql的字样
* ,mff 快速取出路径中文件名

# ,mw 工作常用相关的处理
* ,mwm 快速将vimrc中与,m有关的注释提取出来 
* ,mwt tms 写日报用 因从evernote中复制过来后需要去掉空行再复制到剪切板
* ,mwd 快速删除当前文件中的debugger;的行 快捷命令DelDebugger
* ,mwLoad 快速格式化装载机派工日志
* ,mwp 在url上快速加上ip 并复制到剪切板
* ,mw# 快速删除shell中注释信息
* ,mw: 快速删除批处理bat中注释信息
* ,mwmac  将z:\xx 改成 /Users/mang/xx
* ,mwmac2 将\\Mac\Home\xx 的路径 替换成 /Users/mang/xx 
* ,mwz 快速将z:\xx 变成 \\Mac\Home\ 的形式
* ,mw\ 快速将\转换成/ 常用于windows中的路径转换中linux中的路径 
* ,mwl 快速在每行前面加一行号.空格 如1. 
* ,mwj 快速转换成json格式
* ,mwc 快速将峰驼形式的单词变成下划线分隔 如将 testClientId变成test_Client_Id
* ,mwC 快捷将下划线分隔的单词转换成峰驼式 如test_client_id 变成testClientId
* ,mwdruidd 快速生成用于druid摄入文件的dimensions列
* ,mwdruidm 快速生成用于druid摄入文件的metrics
* ,mwg 快速将一个方法中的get方法提取出来
* ,mws 快速将一个方法中的set方法提取出来
* ,mm 将光标快速定位到行的中间

# ,ms sql语句处理
* ,mss 将导出的insert语句中的id换成s_test.nextval

# ,mg割接使用

## ,mgs 系列 sequence 系列 s取sequence的意思
* ,mgsn 将sequence导出后的语句处理成select sequence.nextval from dual;的语句
* ,mgsd 快速将导出的sequence的语句整理成drop sequence的语句
* ,mgsc 快速将导出的sequence整理成先drop 再创建 再nextvalue 50次

## ,mgt 系列 table 系列 t取table的意思
* ,mgt0 快速将导出的建表语句中的comment设置成空
* ,mgta 快速将导出的建表语句中的comment语句取出
* ,mgts 快速将表组织成表选择的方式
* ,mgtc 从建表语句中快速提取字段名

# ,m自定义函数
* ,m-CopyMatches
* ,m-KeepLines
* ,m-PickMysqlColumn 快速从mysql建表语句中提取出字段名
* ,m-GetTableColumn 快速从建表语句中提取字段名-方法2 其使用了,mgtc快捷键
