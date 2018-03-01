
# Hadoop 2.9 
### =====================================
Build docker images (Debian stretch for hadoop 2.9)


### - Link for the docker image
<a href="https://hub.docker.com/r/bhntools/hadoop29stretch/">https://hub.docker.com/r/bhntools/hadoop29stretch</a> 


### - Build the docker image
```bash
docker pull bhntools/hadoop29stretch:latest
```

### - Run the docker image
```bash
 docker run -it -p 22 bhntools/hadoop29stretch:latest /bin/bash 
```

### - Check hadoop version
```bash
 hadoop version 
```

<mark>
==OUTPUT== 

Hadoop 2.9.0<br>
Subversion https://git-wip-us.apache.org/repos/asf/hadoop.git -r 756ebc8394e473ac25feac05fa493f6d612e6c50<br>
Compiled by arsuresh on 2017-11-13T23:15Z
Compiled with protoc 2.5.0<br>
From source with checksum 0a76a9a32a5257331741f8d5932f183<br>
This command was run using /usr/local/hadoop/share/hadoop/common/hadoop-common-2.9.0.jar<br>

<mark>
==OUTPUT==

### - References:
#### * Installation: 
##### ** Source : 
<a href="http://hadoop.apache.org/docs/r2.9.0/hadoop-project-dist/hadoop-hdfs/WebHDFS.html">http://hadoop.apache.org/docs/r2.9.0/hadoop-project-dist/hadoop-hdfs/WebHDFS.html</a>
##### ** How : 
<a href="https://www.guru99.com/how-to-install-hadoop.html">https://www.guru99.com/how-to-install-hadoop.html</a>
<a href="http://www.professionalcipher.com/2018/01/how-to-install-hadoop-on-ubuntu-1604.html">http://www.professionalcipher.com/2018/01/how-to-install-hadoop-on-ubuntu-1604.html</a>
#### * Tutorials : 
##### ** <a href="https://www.tutorialspoint.com/hadoop/index.html">https://www.tutorialspoint.com/hadoop/index.html</a>
##### ** <a href="https://www.safaribooksonline.com/library/view/hadoop-fundamentals-livelessons/9780134052489/">https://www.safaribooksonline.com/library/view/hadoop-fundamentals-livelessons/9780134052489/</a>
#### * Certification: 
<a href="https://www.cloudera.com/more/training/certification/cca-data-analyst.html">https://www.cloudera.com/more/training/certification/cca-data-analyst.html</a>

### - Authors & Maintainer
BEN HASSINE Najla.

### - License
MIT License.


