# java
一个运行java的基础镜像,包含open-jdk、arthas、启动脚本


## 环境变量清单
<table>
<tr>
    <td>变量名称</td>
    <td>是否必填</td>
    <td>默认值</td>
    <td>备注</td>
</tr>
<tr>
    <td>JAR_NAME</td>
    <td>是</td>
    <td>无</td>
    <td>JAR文件名称</td>
</tr>
<tr>
    <td>JVM_XMX</td>
    <td>否</td>
    <td>128M</td>
    <td>最大堆</td>
</tr>
<tr>
    <td>JVM_XMS</td>
    <td>否</td>
    <td>64M</td>
    <td>初始堆</td>
</tr>
<tr>
    <td>JVM_XMN</td>
    <td>否</td>
    <td>jvm默认值</td>
    <td>新生代</td>
</tr>
<tr>
    <td>JVM_XSS</td>
    <td>否</td>
    <td>jvm默认值</td>
    <td>线程堆栈</td>
</tr>
<tr>
    <td>JVM_SURVIVOR_RATIO</td>
    <td>否</td>
    <td>jvm默认值</td>
    <td>Eden与Survivor比值</td>
</tr>
<tr>
    <td>JVM_MAX_PERM_SIZE</td>
    <td>否</td>
    <td>jvm默认值</td>
    <td>持久代</td>
</tr>
<tr>
    <td>JVM_HEAP_DUMP_PATH</td>
    <td>否</td>
    <td>jvm默认值</td>
    <td>内存溢出快照文件保存路径</td>
</tr>
<tr>
    <td>JVM_MAX_TENURING_THRESHOLD</td>
    <td>否</td>
    <td>jvm默认值</td>
    <td>垃圾最大年龄</td>
</tr>
<tr>
    <td>JVM_SERVER</td>
    <td>否</td>
    <td>jvm默认值</td>
    <td></td>
</tr>
<tr>
    <td>JVM_CLASS_PATH</td>
    <td>否</td>
    <td>无</td>
    <td>指定依赖路径</td>
</tr>
<tr>
    <td>REMOTE_DEBUG_PORT</td>
    <td>否</td>
    <td>无</td>
    <td>远程debug端口</td>
</tr>
</table>
