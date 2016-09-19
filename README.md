#自定义控件

这是一个Android项目

----------

**名称：智慧短信**

**开发环境：Android Studio**

**基于：黑马Android项目-自定义控件**

----------

##详细

本项目基于黑马Android项目-自定义控件，采用-Android studio-进行逐步开发，做了部分修改，并加注了详细标注，方便了部分**Android Studio初学者**的学习与使用。

##build.gradle
	apply plugin: 'com.android.application'
	
	android {
	    compileSdkVersion 23
	    buildToolsVersion '24.0.1'
	
	    defaultConfig {
	        applicationId "com.example.originalview"
	        minSdkVersion 15
	        targetSdkVersion 23
	        versionCode 1
	        versionName "1.0"
	    }
	    buildTypes {
	        release {
	            minifyEnabled false
	            proguardFiles getDefaultProguardFile('proguard-android.txt'), 'proguard-rules.pro'
	        }
	    }
	}
	
	dependencies {
	    compile fileTree(include: ['*.jar'], dir: 'libs')
	    testCompile 'junit:junit:4.12'
	    compile 'com.android.support:appcompat-v7:23.0.1'
	}