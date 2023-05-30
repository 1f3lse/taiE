预计6月底、7月初公开一版 


![image](https://user-images.githubusercontent.com/43382381/231047284-12b4e049-5059-4d49-9cf9-03f998320277.png)




相传，泰阿剑是楚国的镇国之宝，由欧冶子和干将两位当世铸剑大师合力铸造，可是两位高手却不那样觉得，说泰阿剑是一把诸侯国威道之刃，早就存有。仅仅无形、无迹，可是剑气早就存于天地间，只等候机会，凝聚起来。天时、地利、人和，三道归一，此剑在楚国筑成。出剑之时，剑身纯天然刻写篆体“泰阿”二字，由此可见欧冶子、莫邪所言不假。泰阿剑自铸成之日起，就被冠以“威道之剑”的英名，意即只有发自内心的虔诚之威，才可以激发出泰阿剑的剑气之威。此剑即成剑气逼人，威力遮天蔽日，非威武之主不能驾驭。





由Apt_t00ls二开原作者工具连接：https://github.com/White-hua/Apt_t00ls    
  
  
  
  开发支持：ohh 
  
  
  
  2023.05.30. 
  
  添加 泛微E-mobile v9.5任意文件上传漏洞. 
  
  
  
  
-------红帆iOffice--------

红帆iOffice注入5个，文件上传2个，账号读取1个，其中多数为未公开漏洞，谨慎使用

SQL注入 CNVD-2022-62404

文件上传 CNVD-2022-62439  
CNVD-2023-34068  

CNVD-2023-34071  



ioRepPicAdd_upload 文件上传   
HtmlEdit_image_upload 文件上传   
iorepsavexml_upload 文件上传

-------泛微OA--------

e-cology workrelate_uploadOperation.jsp-RCE (默认写入冰蝎4.0.3aes)

e-cology page_uploadOperation.jsp-RCE (暂未找到案例 仅供检测poc)

e-cology WorkflowServiceXml-RCE (默认写入内存马 冰蝎 3.0 beta11)

e-cology BshServlet-RCE (可直接执行系统命令)

e-cology KtreeUploadAction-RCE (默认写入冰蝎4.0.3aes)

e-office logo_UploadFile.php-RCE (默认写入冰蝎4.0.3aes)

e-office doexecl.php-RCE (写入phpinfo,需要getshell请自行利用)

e-office10 OfficeServer.php-RCE (默认写入冰蝎4.0.3aes)

e-mobile_6.6 messageType.do-SQlli (sqlmap利用，暂无直接shell的exp)

e-office8 upload.php-RCE (默认写入冰蝎4.0.3aes)


-------蓝凌OA--------

landray_sysSearchMain-RCE (多个payload，写入哥斯拉 3.03 密码 yes)

landray_treexmlTmpl-RCE (可直接执行系统命令)

landray_datajson-RCE (可直接执行系统命令)

landray_fileupload_sysSearch (默认写入冰蝎)


-------万户OA--------

wanhu_OfficeServer-RCE (可直接执行系统命令)

wanhu_smartUpload-RCE (可直接执行系统命令)

wanhuoa_OfficeServerservlet-RCE(默认写入冰蝎4.0.3aes)

wanhu_DocumentEdit-SQlli (mssql数据库 可 os-shell)

wanhuoa_fileUploadController-RCE (默认写入冰蝎4.0.3aes)


-------通达OA--------

tongdaoa_getdata-RCE (直接执行系统命令)

tongdaoa_apiali-RCE (默认写入冰蝎4.0.3aes)

tongdaoa_2017_ueditor_upload(默认写入冰蝎4.0.3aes)

tongdaoa_2016_PDF_upload(默认写入冰蝎4.0.3aes)


-------用友OA--------

yongyou_chajet-RCE (用友畅捷通T+ rce 默认写入哥斯拉 Cshap/Cshap_aes_base64)

yongyou_NC_bsh.servlet.BshServlet-RCE (可直接执行系统命令)

yongyou_NC_NCFindWeb 目录遍历漏洞 (可查看是否存在历史遗留webshell)

yongyou_NC_FileReceiveServlet-RCE (默认写入冰蝎4.0.3aes)

yongyou_GRP_UploadFileData-RCE (默认写入冰蝎4.0.3aes)

yongyou_KSOA_imageUpload-RCE (默认写入冰蝎4.0.3aes)

yongyou_GRP_U8_upload (默认写入冰蝎4.0.3aes)

yongyou_aim_upload (默认写入冰蝎4.0.3aes)

yongyou_GRP_U8_sql注入漏洞

yongyou_nc_NCFindWeb_bypass任意文件读取漏洞

yongyou_KSOA_Attachmentupload-RCE漏洞

yongyou_nc_uploadServlet文件上传漏洞

yongyou_U8_AppProxy文件上传漏洞

yongyou_uapjs_upload文件上传漏洞


-------致远OA--------

seeyonoa_main_log4j2-RCE (仅支持检测)

seeyonoa_wpsAssistServlet-RCE (默认写入冰蝎4.0.3aes)

seeyonoa_htmlofficeservlet-RCE (默认写入冰蝎4.0.3aes)

seeyonoa_ajaxBypass-RCE (写入天蝎 密码sky)


-------IIS--------

IIS_PUT_RCE (emm暂时没办法getshell  仅支持检测 java没有MOVE方法)


-------Cacti--------

Cacti 前台命令注入漏洞（CVE-2022-46169）


-------Node.js--------

Node.js命令注入漏洞（CVE-2021-21315）



-------H3C--------

H3C SecPath 网关设备任意文件上传

H3C CAS 云服务任意文件上传，不支持检测，一键shell，慎用

H3C imc管理平台远程命令执行漏洞


-------Jellyfin--------

Jellyfin任意文件读取漏洞CVE-2021-21402


-------Tomcat--------

CVE-2017-12615 任意文件写入漏洞


-------Weblogic--------

CVE-2017-10271 XMLDecoder反序列化漏洞


-------Nacos--------

Nacos 认证绕过漏洞（CVE-2021-29441）


-------Apache Spark--------

CVE-2022-33891 Apache Spark命令注入漏洞

Apache Spark unacc未授权访问漏洞


-------Zabbix--------

CVE_2020_11800 Zabbix远程代码执行漏洞,默认端口10051[该漏洞需要服务端开启了自动注册功能]

jsrpc.php SQL注入


-------ThinkPHP--------

ThinkPHP 2.X tp2_lite_code_exec 远程代码执行

ThinkPHP 5.X tp5_construct_code_exec 远程代码执行

ThinkPHP 5.X tp5_index_construct_exec 远程代码执行

ThinkPHP 5.X tp5_invoke_func_code_exec 远程代码执行

ThinkPHP SQL注入


-------Struts2--------

s2-001、s2-005、s2-007、s2-008、s2-009、s2-012

s2-013、s2-016、s2-019、s2-029、s2-032、s2-033

s2-037、s2-045、s2-046、s2-048、s2-053、s2-057

s2-061、s2-devMode


-------海康--------

海康威视DS-A81016S管理系统 版本CVR V2.3.8-3 任意代码执行漏洞

海康威视CVE-2021-36260远程命令执行漏洞

海康威视CVE-2017-7921未授权访问漏洞

综合安防_applyCT_fastjson-RCE(仅支持检测,自行使用ladp服务利用)


-------奇安信--------

网康下一代防火墙_ngfw_waf_route-RCE(写入菜刀shell 密码:nishizhu)

天擎client_upload_file.json任意文件上传RCE


-------锐捷--------

锐捷Smartweb管理系统命令注入漏洞（CNVD-2021-17291）


-------飞塔--------

FortiNAC keyUpload文件上传漏洞（CVE-2022-39952）

FortiNAC 用户名密码泄漏漏洞  


-------其他--------

网御星云账号密码泄露

金电网安可信运维管理系统RCE(可直接执行系统命令)

KEDACOM数字系统接入网关任意文件读取漏洞

