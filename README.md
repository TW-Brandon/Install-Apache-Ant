Install-Apache-Ant
==================
Download Apache Ant and Save to /opt or other Path
==================
http://ant.apache.org/bindownload.cgi

Decompress Apache Ant(* is number)
==================
*Dont use root to decompress*

tar zvxf apache-ant-*.tar.gz


Edit /etc/profile
==================
*Add to this code*

ANT_HOME=/opt/apache-ant-*
PATH=$ANT_HOME/bin:$PATH

Restart source
==================
source  /etc/profile

Check Ant version 
==================
ant -version

