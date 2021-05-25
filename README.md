# filesManagerSystem

├─fileSave                   // 存放项目文件
├─fileStorage                // 存放完成、删除、备份、下载文件
├─filesystem_back            // 后端Php源代码（默认账号/密码：admin/admin）
├─filesystem_front           // 前端Vue源代码
├─company_file_system.sql    // 数据库结构（内容除一组账号外为空）
└─源代码包结构.txt

作品亮点：
1.已投入车间实际使用，半年内除新增功能外，一直稳定运作无维护请求；
2.独立完成包括：需求分析、软件架构、程序开发、现场部署……在内的所有工作；
3.制定方案时以“易部署”为原则挑选技术栈，所以即便车间没有专业人员，也可以自行完成部署和维护；
4.解决了实际问题，节省了工时管理的人力，规范了数据以实现更多维度分析；
5.使用局域网进行数据信息交互，取代了每天发送、接收Excel的管理方式；

技术栈：
1.C#（.Net）-系统主体：在现场使用的win系统中，无需任何环境，即开即用，无专业知识也可轻松部署。
2.Sqlite-数据库：文件型数据库，无需安装环境和开启服务，和文件相同的管理方式，无专业知识也可轻松部署。
3.Python-数据处理：可轻松地操作数据和office，封装成exe后在win7以上系统无需环境即可使用。

项目背景：
本项目来源于对试制车间的现行工时的记录与统计方式的考察。
与相关人员交流后，发现原制度存在以下问题：
1.班组成员填写数据不规范，需额外花费精力校正；
2.对数据进行统计或分析时，多使用Excel自带函数有一定局限性，且对于多张记录的联合分析更为繁琐，对于不规范的填写也很难处理；
4.表格的数量随时间增长，对历史数据的查询和统计的也愈加繁琐。

因此，我对现行管理体系进行调研，以原有的流程逻辑为基础，结合现场环境和可用资源开发一款工时管理软件，使得任务在分配和汇报时更加便捷、在填写和计算时更加规范，在统计和分析时更加智能。
