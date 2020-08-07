# maven-framework-project

[![Build Status](https://travis-ci.org/v5developer/maven-framework-project.svg?branch=master)](https://travis-ci.org/v5developer/maven-framework-project)

这里不仅生产代码，还搬运代码


# 项目描述


较上个*[maven-framework-project](https://github.com/sxyx2008/maven-framework-project)*过去已经一年多了，在上个*[maven-framework-project](https://github.com/sxyx2008/maven-framework-project)*中，由于没有采用maven的继承和聚合。在介绍各种框架时配置杂乱、不易梳理。故再次有了这个示例项目。同时也意味着*[maven-framework-project](https://github.com/sxyx2008/maven-framework-project)*将不再继续下去。

因之前帐号已经存在*[maven-framework-project](https://github.com/sxyx2008/maven-framework-project)*，且这年头github上也流行`Organizations`，故抢注了`v5developer`这个组织名。该组织下目前有三名成员(*[v5china](https://github.com/v5china)*、*[ios8](https://github.com/ios8)*、*[sxyx2008](https://github.com/sxyx2008)*)当然都是我啦。如果您有什么意见和建议，欢迎您的加入。

该示例仅仅只是一系列教程集(不仅限于Java)，不做一个完整的项目。不会像*[springside4](https://github.com/springside/springside4)*那样强大。当然如果有你的加入，我想她也许会的。

该项目将长期维护下去，也算是从业以来经验和知识的积累。

这里不仅生产代码，还搬运代码。欢迎*[fork](https://github.com/v5developer/maven-framework-project/fork)*和*[star](https://github.com/v5developer/maven-framework-project/stargazers)*

如果你有好的示例项目或教程可与我联系。我会以`git submodule`的方式添加进来，一来是尊重原作者的劳动成果，二来实时与原作者库同步，保持最新。


# 项目托管


*[https://github.com/v5developer/maven-framework-project](https://github.com/v5developer/maven-framework-project)*

*[https://git.oschina.net/sxyx2008/maven-framework-project](https://git.oschina.net/sxyx2008/maven-framework-project)*

*[https://github.com/sxyx2008/maven-framework-project](https://github.com/sxyx2008/maven-framework-project)* *较早版本(已不再更新维护)*


# 克隆到本地


该项目争取做到每一个示例项目都可以直接运行。各示例项目之间不相互依赖。由于提交了一些参考书籍*[reference](https://github.com/v5developer/maven-framework-project/tree/master/reference)*导致目前体积较大。因此克隆时间较长，请您耐心等待。

项目使用了`git submodule`，因此克隆后需要执行下面的操作(在项目根目录中，与.gitmodules同一目录下)。

```
git submodule init

git submodule update
```

具体用法参照*[http://git-scm.com/book/zh/](http://git-scm.com/book/zh/)*



# 酷站分享


该部分内容主要分享一些本人收集的与Java有关的站点。主要包括Maven Repository、Maven Plugins、Java Tutorials。欢迎补充!


## Maven Repository

*[http://mvnrepository.com/](http://mvnrepository.com/)*

*[http://search.maven.org/#browse](http://search.maven.org/#browse)*

*[http://mojo.codehaus.org/](http://mojo.codehaus.org/)*

*[http://dev.nightlabs.org/maven-repository/repo/](http://dev.nightlabs.org/maven-repository/repo/)*

*[http://opensource.kantega.no/nexus/content/groups/public/](http://opensource.kantega.no/nexus/content/groups/public/)*

*[http://nexus.betaconceptframework.org/nexus/content/groups/public/](http://nexus.betaconceptframework.org/nexus/content/groups/public/)*

*[https://app.camunda.com/nexus/content/groups/public/](https://app.camunda.com/nexus/content/groups/public/)*

*[http://repo1.maven.org/maven/mule/dependencies/maven2/](http://repo1.maven.org/maven/mule/dependencies/maven2/)*

*[https://maven-us.nuxeo.org/nexus/content/groups/public/](https://maven-us.nuxeo.org/nexus/content/groups/public/)*

*[http://repo.yongtai.com.cn/nexus/content/repositories/public/](http://repo.yongtai.com.cn/nexus/content/repositories/public/)*

*[https://maven.alfresco.com/nexus/content/repositories/public/](https://maven.alfresco.com/nexus/content/repositories/public/)*

*[https://repository.jboss.org/nexus/content/repositories/public/](https://repository.jboss.org/nexus/content/repositories/public/)*

*[http://mirrors.ibiblio.org/maven/mule/dependencies/maven2/](http://mirrors.ibiblio.org/maven/mule/dependencies/maven2/)*

*[http://repo.squashtest.org/maven2/releases/](http://repo.squashtest.org/maven2/releases/)*

*[https://repository.jboss.org/nexus/content/repositories/thirdparty-releases/](https://repository.jboss.org/nexus/content/repositories/thirdparty-releases/)*

*[http://repo.spring.io/milestone/](http://repo.spring.io/milestone/)*

*[http://repo.spring.io/snapshot/](http://repo.spring.io/snapshot/)*

*[https://oss.sonatype.org/content/repositories/sourceforge-releases/](https://oss.sonatype.org/content/repositories/sourceforge-releases/)*

*[http://maven.in.softeu.cz/nexus/content/repositories/public/](http://maven.in.softeu.cz/nexus/content/repositories/public/)*

*[http://maven.oschina.net/content/groups/public/](http://maven.oschina.net/content/groups/public/)*

*[http://maven.kaifazhe.me/content/groups/public/](http://maven.kaifazhe.me/content/groups/public/)*

*[http://repo.spring.io/release/](http://repo.spring.io/release/)*

*[http://mirrors.ibiblio.org/maven2/](http://mirrors.ibiblio.org/maven2/)*


*欢迎补充*


## Maven Plugins

*[http://mojo.codehaus.org/](http://mojo.codehaus.org/)*

*[http://tomcat.apache.org/maven-plugin-2.1/](http://tomcat.apache.org/maven-plugin-2.1/)*

*[http://maven.apache.org/plugins/index.html](http://maven.apache.org/plugins/index.html)*

*[http://docs.codehaus.org/display/JETTY/Maven+Jetty+Plugin](http://docs.codehaus.org/display/JETTY/Maven+Jetty+Plugin)*

*[https://docs.jboss.org/jbossas/7/plugins/maven/](https://docs.jboss.org/jbossas/7/plugins/maven/)*

*[http://mojo.codehaus.org/jboss-maven-plugin/](http://mojo.codehaus.org/jboss-maven-plugin/)*

*[https://maven.apache.org/plugins/index.html](https://maven.apache.org/plugins/index.html)*

*[https://code.google.com/p/maven-db-plugin/](https://code.google.com/p/maven-db-plugin/)*


*欢迎补充*


## Java Tutorials

*[http://www.mkyong.com/](http://www.mkyong.com/)*

*[http://www.dzone.com/tutorials/java](http://www.dzone.com/tutorials/java)*

*[http://viralpatel.net/blogs/](http://viralpatel.net/blogs/)*

*[http://www.hascode.com/](http://www.hascode.com/)*

*[http://www.journaldev.com/](http://www.journaldev.com/)*

*[http://verylearning.com/](http://verylearning.com/)*

*[http://www.roseindia.net/](http://www.roseindia.net/)*

*[http://docs.oracle.com/javaee/5/tutorial/doc/docinfo.html](http://docs.oracle.com/javaee/5/tutorial/doc/docinfo.html)*

*[http://www.mastertheboss.com/index.php](http://www.mastertheboss.com/index.php)*

*[http://www.vogella.com/](http://www.vogella.com/)*

*[http://www.solrtutorial.com/index.html](http://www.solrtutorial.com/index.html)*

*[http://refcardz.dzone.com/](http://refcardz.dzone.com/)*

*[http://www.springbyexample.org/](http://www.springbyexample.org/)*

*[http://www.coreservlets.com/](http://www.coreservlets.com/)*

*[http://www.programcreek.com/](http://www.programcreek.com/)*

*[http://www.mortardata.com/](http://www.mortardata.com/)*

*[http://www.pluralsight.com/training/](http://www.pluralsight.com/training/)*

*[https://tutsplus.com/](https://tutsplus.com/)*

*[http://www.mossle.com/docs/activiti/](http://www.mossle.com/docs/activiti/)*

*[http://blog.sae.sina.com.cn/](http://blog.sae.sina.com.cn/)*

*[http://www.baeldung.com/](http://www.baeldung.com/)*

*[http://www.javacodegeeks.com/tutorials/java-tutorials/enterprise-java-tutorials/](http://www.javacodegeeks.com/tutorials/java-tutorials/enterprise-java-tutorials/)*

*[http://www.tutorialspoint.com/](http://www.tutorialspoint.com/)*

*[http://www.javaworld.com/](http://www.javaworld.com/)*

*[http://www.codejava.net/](http://www.codejava.net/)*

*[http://www.javatips.net/](http://www.javatips.net/)*

*[http://www.codesuggestions.com/java/apache-commons-dbutils-tutorial/](http://www.codesuggestions.com/java/apache-commons-dbutils-tutorial/)*

*[http://www.javatips.net/blog/2014/03/apache-dbutils-tutorial](http://www.javatips.net/blog/2014/03/apache-dbutils-tutorial)*

*[http://www.javabeat.net/](http://www.javabeat.net/)*

*[http://www.concretepage.com/](http://www.concretepage.com/)*

*[http://www.petrikainulainen.net/programming/spring-framework/spring-data-jpa-tutorial-part-two-crud/](http://www.petrikainulainen.net/programming/spring-framework/spring-data-jpa-tutorial-part-two-crud/)*

*[http://fruzenshtein.com/spring-jpa-data-hibernate-mysql/](http://fruzenshtein.com/spring-jpa-data-hibernate-mysql/)*

*[http://howtodoinjava.com/](http://howtodoinjava.com/)*

*[http://websystique.com/](http://websystique.com/)*

*[http://blog.zenika.com/category/tribus/java/](http://blog.zenika.com/category/tribus/java/)*

*[https://tutswiki.com/](https://tutswiki.com/)*

*欢迎补充*



# 与我联系

* QQ:*184675420*

* Email:*sxyx2008#gmail.com*(#替换为@)

* HomePage:*[aimeizi.net](http://aimeizi.net)*

* Weibo:*[http://weibo.com/qq184675420](http://weibo.com/qq184675420)*(荧星诉语)

* Twitter:*[https://twitter.com/sxyx2008](https://twitter.com/sxyx2008)*



# License

MIT

Copyright (c) 2014 雪山飞鹄
