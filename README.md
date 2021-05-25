# filesManagerSystem
├─fileSave                   // 存放项目文件  
├─fileStorage                // 存放完成、删除、备份、下载文件  
├─filesystem_back            // 后端Php源代码（默认账号/密码：admin/admin）  
├─filesystem_front           // 前端Vue源代码  
├─company_file_system.sql    // 数据库结构（内容除一组账号外为空）  
└─源代码包结构.txt  

作品亮点：
1.已投入研究所试用，能够正常运作；  
2.独立完成前后端分离项目，亦负责需求分析和部署；  
3.解决了实际问题，节省了档案管理时的人力；  
4.有进一步扩展为“项目管理系统”的可能（已有部分功能）；  

技术栈：  
1.Vue-前端：无特殊考虑；  
2.ThinkPhp-后端：热部署，适合经常改变需求的情况；  
3.Python-文件管理：比起Php操作文件，以shutil为代表的Py库可以更加轻松；  
4.MySQL-数据库：无特殊考虑；  

项目背景：  
本项目来源于在所内档案管理办法实施时，所遭遇的：管理人员负担重、使用人员不规范、流程执行不严谨等问题。  

因此，我对研究所的项目体系进行调研（因为我刚来），以可用资源为基础，研发一款基于B/S的档案管理系统，意图减轻管理人员的压力，强制规范的执行。  

主要界面展示：  
1.项目浏览  
可进行项目的创建、筛选、权限等操作。  
![image](https://user-images.githubusercontent.com/46466354/119429281-24089c00-bd41-11eb-90e9-d3aafadb9edc.png)


2.文件管理  
可对文件或文件夹进行上传、下载、删除、改名等操作（使用右键菜单实现）。  
![image](https://user-images.githubusercontent.com/46466354/119429290-27038c80-bd41-11eb-98da-093ab50ae04b.png)



3.权限管理  
管理人员的权限，修改、查看密码。  
![image](https://user-images.githubusercontent.com/46466354/119429303-2b2faa00-bd41-11eb-98bf-877dfb90fa46.png)


4.文件备份  
对档案文件进行备份的手动版本（自动版运行同样的py文件，只是每日定时运行）  
![image](https://user-images.githubusercontent.com/46466354/119429305-2d920400-bd41-11eb-9e44-e485d9157731.png)


5.进度管理  
可以管理项目的进度，将已完成的项目打包，不再参与每日备份。  
此部分功能有进一步扩展的可能。  
![image](https://user-images.githubusercontent.com/46466354/119429314-2ff45e00-bd41-11eb-8605-707c5bd77a2d.png)


6.删除管理  
对删除的项目进行回收、彻底删除的操作。  
![image](https://user-images.githubusercontent.com/46466354/119429319-34b91200-bd41-11eb-8868-36a547e05c5f.png)


7.数据可视  
将文件所占空间进行可视化处理，更加直观。  
此部分功能有进一步扩展的可能。  
![image](https://user-images.githubusercontent.com/46466354/119429326-371b6c00-bd41-11eb-93e4-48b3a85706e7.png)


如有兴趣进行更全面的了解请参考上面分享的源代码。  
