# alpine-py27
alpine3.7的python环境，python版本为2.7.14
<pre>
参考该<a href="https://github.com/docker-library/python/blob/b1512ead24c6b111506a8d4229134a29da240597/2.7/alpine3.6/Dockerfile">Dockerfile</a>

做了以下两个调整：
1、将源改成了aliyun的源
2、增加alpine与宿主机的时间同步
3、安装uwsgi
参考http://note.qidong.name/2017/06/28/uwsgi-in-docker/
</pre>
