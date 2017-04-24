maven bug
1.错误: 找不到或无法加载主类 org.codehaus.plexus.classworlds.launcher.
解决方法：配置PATH时将$M2_HOME/bin放在系统$PATH前就可以了。
export M2_HOME=/opt/maven
export PATH=$M2_HOME/bin:$PATH