# Translation_Server
Translation应用的服务端<br>
开发环境:jdk7+myeclipse2014+mysql5.6

请在config文件夹下的properties.properties文件修改对应的属性。

注意
--

请修改你的Tomcat根目录下的Conf/Server.xml文件，配置虚拟目录，在host节点末尾处添加如下节点：<br>
```<Context path="/file" docBase="G:\tomcat\file" reloadable="true" debug="0"></Context>```<br>

注意docBase的值必须跟上面的properties.properties文件的uploadFileBasePath属性的值相同。<br>
注意，注意，注意，重要的事情说三遍，配置错误将导致读取不到上传的图片等问题。
