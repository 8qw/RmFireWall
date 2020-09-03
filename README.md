## Description

RmFireWall 是真全局代理的流量加密軟體。全部的 "TCP、UDP" 數據包在傳出之前都會通過 "TLS 1.3、DTLS 1.2" 加密。對於 "2.6.0.0 Version" 使用 "EUDP" 加密 "UDP" ,因爲就算開啓 "不强自息" 模式,在困苦艱難的環境也會出現短暫的斷流。

### Documentation

[幫助文檔](https://github.com/8qw/RmFireWall/wiki)

### Platforms

[下載](https://github.com/8qw/RmFireWall/releases)

<ul>
 <li>Linux
  <ul>
    <li>Ubuntu 20.04(x64)</li>
    <li>Centos 8(x64)</li>
  </ul>
 </li>

 <li>Windows
  <ul>
    <li>Windows Server 2016(x64) Over</li>
    <li>Windows 8(x64) Over</li>
  </ul>
 </li>

 <li>MacOS
  <ul>
   <li>沒有</li>
  </ul>
 </li>
 
 <li>Android
  <ul>
   <li>沒有</li>
  </ul>
 </li>
 
 <li>Iphone
  <ul>
   <li>沒有</li>
  </ul>
 </li>
 
</ul>

### Config Server

```markdown
# RmFireWall Server TCP
root@host: tar -xJ -f RmFireWall_linux_server_tcp-X64-Release.tar.xz
root@host: cd RmFireWall_linux_server_tcp-X64-Release
root@host: chmod +x ./start.sh
root@host: ./start.sh
root@host: nohup: appending output to 'nohup.out'
[Enter]
root@host: cat nohup.out
Load Default File [default.tpcf]
Read Successful
Run Status:0
Ok

# RmFireWall Server UDP
root@host: tar -xJ -f RmFireWall_linux_server_udp-X64-Release.tar.xz
root@host: cd RmFireWall_linux_server_udp-X64-Release
root@host: chmod +x ./start.sh
root@host: ./start.sh
root@host: nohup: appending output to 'nohup.out'
[Enter]
root@host: cat nohup.out
Load Default File [default.upcf]
Read Successful
Run Status:0
Ok


RmFireWall Group.

Copyright (c) 2020 兲朝
