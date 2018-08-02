# KsAudioRecorder 简介

基于系统AudioRecord接口和MediaCodec实现的一个简单音频录制库，
目前已实现aac格式编码，同时提供了自定义编码器扩展和音频PCM过滤器功能

## 在项目中使用

1. Add the JitPack repository to your build file

    ```groovy
    allprojects {
            repositories {
            
          maven { url 'https://jitpack.io' }
          
         }
      }
    ```

2. Add the dependency 

    ![](https://jitpack.io/v/KevinSuo/KsAudioRecorder.svg)

    ```groovy
      dependencies {
              implementation 'com.github.KevinSuo:KsAudioRecorder:v0.0.1'
        }
    ```
    
    

