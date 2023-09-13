## maven


项目根目录 build.gradle 添加仓库地址 ：
	
	allprojects {
    	repositories {
			maven { url 'https://wzlyandroid.github.io/maven' }
 			//maven { url 'https://github.com/WZLYAndroid/maven/raw/main' }
			//maven { url 'file://' + new File(rootDir.parentFile, 'maven').absolutePath }
    	}
	}
	
项目中依赖所需库：

	dependencies {
    
  		implementation 'com.wzly.module:widget:1.0.0'
   		implementation 'com.wzly.module:base:1.0.0'
		implementation 'com.wzly.module:http-retrofit:1.0.0'

	} 
