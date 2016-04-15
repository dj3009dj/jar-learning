# jar-learning
jar包的全称是java archive file，即java档案文件。<br/>
在java中时很常见的，实际上我的理解就是，将一些.class/.java文件打包，其他的类就可以用。<br/>
1. Intellij中将当前project打包的方法是：
<pre>
   File>Project Structure>Artifacts中点击"+"按钮
   下拉菜单中选择JAR中，JAR中徐娜则"From modules with dependencies",点击OK
   Build>Build Artifact
</pre>
另外，cmd中使用jar指令也可以生成jar包<br/>
2. 在另外的工程中导入jar包
<pre>
    File>Projecr Structure>Modules中选择Dependencies，点击"+"按钮，选择相应jar包，OK
    在External Libraries中可以看到刚刚添加的.jar包
</pre>
可以直接使用jar包中包含的类，此时不需要import包名，并且jar包中的文件不允许改变
