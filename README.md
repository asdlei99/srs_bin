# SRS BIN
本仓库仅仅提供给以下相关的同学：
* 不擅长编译
* 不擅长编程
* 不会使用srs的docker，或环境无法允许docker允许
* 对srt新直播协议敢兴趣
  
## 1. 运行环境
centos

相关链接库：
<pre>
<code>
ldd ./objs/srs
	linux-vdso.so.1 =>  (0x00007ffd2a1e7000)
	libdl.so.2 => /lib64/libdl.so.2 (0x00007fb53f8bf000)
	libstdc++.so.6 => /lib64/libstdc++.so.6 (0x00007fb53f5b8000)
	libm.so.6 => /lib64/libm.so.6 (0x00007fb53f2b6000)
	libgcc_s.so.1 => /lib64/libgcc_s.so.1 (0x00007fb53f0a0000)
	libpthread.so.0 => /lib64/libpthread.so.0 (0x00007fb53ee84000)
	libc.so.6 => /lib64/libc.so.6 (0x00007fb53eab6000)
	/lib64/ld-linux-x86-64.so.2 (0x00007fb53fac3000)

</code>
</pre>

## 2. 运行
git clone https://github.com/runner365/srs_bin.git <br/>
cd srs_bin <br/>
./objs/srs -c conf/srt.conf <br/>

## 3. 更多的wiki
srt in srs4.0: [srt_wiki](https://github.com/ossrs/srs/wiki/v4_CN_SRTWiki)
<br/>

srt issues in srs: [srt_issues](https://github.com/ossrs/srs/issues/1147)