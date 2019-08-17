# superman

### superman是什么
`superman`是自定义的`archetype`，通过使用`superman archetype`可以生成满足我们项目需求的工程模板，提高开发效率的同时可以统一团队内的项目结构风格

### 使用步骤
1. mvn clean install
2. mvn archetype:generate -DgroupId=com.jd.medicine.demo -DartifactId=medicine-demo -Dversion=1.0.0-SNAPSHOT -DarchetypeGroupId=wrx.xing -DarchetypeArtifactId=superman -DarchetypeVersion=1.0-SNAPSHOT -X -DarchetypeCatalog=local



### 参数说明 
  `-DgroupId`组ID，默认项目的包名的组ID相同  
  `DartifactId`：项目唯一标识符，即项目名称  
  `-DarchetypeGroupId`：superman的组ID，值不需要进行修改  
  `-DarchetypeArtifactId`：superman的artifactId，值不需要进行改变 
  `-X`：debug
