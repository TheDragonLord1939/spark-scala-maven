

# SPARK 源码分析技术分享汇总 (带bilibili视频)
【本站点正在持续更新中......2018-12-05......】

- SPARK 1.6.0-cdh5.15.0
- Hadoop 2.6.0-cdh5.15.0
- spark-scala-maven 
- 微信(技术交流) : thinktothings
- SPARK 源码分析技术分享(视频汇总套装视频): https://www.bilibili.com/video/av37442139/
- SPARK 源码分析技术分享(视频汇总在线看):https://blog.csdn.net/thinktothings/article/details/84726769
- SPARK 源码分析技术分享 (github) :  https://github.com/opensourceteams/spark-scala-maven


### RDD依赖 Dependency

#### NarrowDependency
- OneToOneDependency
   - bilibili 视频:  https://www.bilibili.com/video/av37442139/?p=1
   - 详细说明文档： https://github.com/opensourceteams/spark-scala-maven/blob/master/md/OneToOneDenpendency.md
   
   <iframe   width="800" height="500" src="//player.bilibili.com/player.html?aid=37442139&cid=65822237&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
   
   
- RangeDependency
   - bilibili 视频:  https://www.bilibili.com/video/av37442139/?p=2 
   - 详细说明文档： https://github.com/opensourceteams/spark-scala-maven/blob/master/md/RangeDependency.md
   
   <iframe src="//player.bilibili.com/player.html?aid=37442139&cid=65822237&page=2" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
   
- PruneDependency filter
   - bilibili 视频:  https://www.bilibili.com/video/av37442139/?p=3
   - 详细说明文档： https://github.com/opensourceteams/spark-scala-maven/blob/master/md/PruneDependency.md
   
   <iframe src="//player.bilibili.com/player.html?aid=37442139&cid=65822237&page=3" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
   
- PruneDependency RangePartitioner
   - bilibili 视频:  https://www.bilibili.com/video/av37442139/?p=4
   - 详细说明文档： https://github.com/opensourceteams/spark-scala-maven/blob/master/md/PruneDependencyRangePartitioner.md
   
   <iframe src="//player.bilibili.com/player.html?aid=37442139&cid=65822237&page=4" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>


#### ShuffleDependency
   - bilibili 视频:  https://www.bilibili.com/video/av37442139/?p=5
   - 详细说明文档：https://github.com/opensourceteams/spark-scala-maven/blob/master/md/ShuffleDependency.md
   
   <iframe src="//player.bilibili.com/player.html?aid=37442139&cid=65822237&page=5" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
   

### SparkContext 分析
 - SparkContext原理分析(Youtube视频): https://youtu.be/euIuutjAB4I
 - SparkContext源码分析(Youtube视频):  https://youtu.be/tUH7QnCcwgg
 - SparkContext源码分析(文档详解）： https://github.com/opensourceteams/spark-scala-maven/blob/master/md/SparkContext.md
 
 <iframe src="//player.bilibili.com/player.html?aid=37442161&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
 
 

### Spark 通信原理分析
 - Spark通信原理分析(Youtube视频):  https://youtu.be/3vUVwbEGf1E
 - Spark通信原理分析（文档详解）： https://github.com/opensourceteams/spark-scala-maven/blob/master/md/OutBoxAndInBox.md
- bilibili : https://www.bilibili.com/video/av37442199/

<iframe src="//player.bilibili.com/player.html?aid=37442199&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>


### Spark Master启动源码分析
 - Spark Master启动源码分析(Youtube视频):  https://youtu.be/74q1nddoaiY​
 - Spark Master启动源码分析(Bilibili视频):   https://www.bilibili.com/video/av37442271/
 - Master启动源码分析详细说明文档： https://github.com/opensourceteams/spark-scala-maven/blob/master/md/StartMaster.md

<iframe src="//player.bilibili.com/player.html?aid=37442271&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

 
 - Spark Master资源调度--worker向master注册(Youtube视频):  https://youtu.be/74q1nddoaiY​
  - Spark Master资源调度--worker向master注册(Bilibili视频):   https://www.bilibili.com/video/av37442280/
 - Spark Master资源调试--worker向master注册(文档详解)： https://github.com/opensourceteams/spark-scala-maven/blob/master/md/MasterScheduler_workerRegisterMaster.md

<iframe src="//player.bilibili.com/player.html?aid=37442280&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>


 - Spark Master资源调度--SparkContext向所有master注册(Youtube视频):  https://youtu.be/AXxCnCc5Mh0​ 
  - Spark Master资源调度--SparkContext向所有master注册(Bilibili视频):  https://www.bilibili.com/video/av37442295/
 - Spark Master资源调度--SparkContext向所有master注册(文档详解): https://github.com/opensourceteams/spark-scala-maven/blob/master/md/MasterScheduler_SparkContextRegisterMaster.md

<iframe src="//player.bilibili.com/player.html?aid=37442295&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>



### Spark Worker启动源码分析
 - Spark Worker 启动源码分析(Youtube视频):   https://youtu.be/ll_Ae6rP7II​​
 - Spark Worker 启动源码分析(Bilibili视频):   https://www.bilibili.com/video/av37442247/
 - Spark Worker 启动源码分析(文档详解):  https://github.com/opensourceteams/spark-scala-maven/blob/master/md/StartWorker.md

<iframe src="//player.bilibili.com/player.html?aid=37442247&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
 
 
### Spark Executor启动源码分析
  - Spark Executor启动源码分析(Youtube视频):   https://youtu.be/1qg4UMPV3pQ
  - Spark Executor启动源码分析(Bilibili视频):    https://www.bilibili.com/video/av37442311/
  - Spark Executor启动源码分析(文档详解)：   https://github.com/opensourceteams/spark-scala-maven/blob/master/md/CoarseGrainedExecutorBackend_start.md

<iframe src="//player.bilibili.com/player.html?aid=37442311&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
 
 
### Spark 触发Job提交
 - Spark 触发Job提交(youtube视频) : https://youtu.be/X49RIqz2AjM
 - Spark 触发Job提交(bilibili视频) :  https://www.bilibili.com/video/av37445008/
 - Spark 触发Job提交(文档详解)：https://github.com/opensourceteams/spark-scala-maven/blob/master/md/jobSubmitTrigger.md

<iframe src="//player.bilibili.com/player.html?aid=37445008&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

 
### Spark DAG调度器事件循环处理器
 - Spark DAG调度器事件循环处理器(Youtube视频) : https://youtu.be/fT-dpf0KFOA
 - Spark DAG调度器事件循环处理器(Bilibili视频) :  https://www.bilibili.com/video/av37445034/
 - Spark DAG调度器事件循环处理器(文档详解)：https://github.com/opensourceteams/spark-scala-maven/blob/master/md/DAGSchedulerEventProcessLoop.md 

<iframe src="//player.bilibili.com/player.html?aid=37445034&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

 
### Spark FinalStage处理(Stage划分)
 - Spark FinalStage处理(Stage划分)(Youtube视频) : https://youtu.be/yFJugOV0Fak
 - Spark FinalStage处理(Stage划分)(Bilibili视频) :  https://www.bilibili.com/video/av37445057/
 - Spark FinalStage处理(Stage划分)(文档详解)：https://github.com/opensourceteams/spark-scala-maven/blob/master/md/FinalStage.md 

<iframe src="//player.bilibili.com/player.html?aid=37445057&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
 
### Spark Stage提交
 - Spark Stage提交(Youtube视频) :  https://youtu.be/NI8-_X6mbl4
 - Spark Stage提交(Bilibili视频) :   https://www.bilibili.com/video/av37445077/
 - Spark Stage提交(文档详解)：https://github.com/opensourceteams/spark-scala-maven/blob/master/md/SubmitStage.md 
 

<iframe src="//player.bilibili.com/player.html?aid=37445077&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>






======================================================================================


## Youtub 视频
- [HadoopRdd源码分析-读取本地文件需求分析-01](https://youtu.be/PtNo5S3g3zc "HadoopRdd源码分析-读取本地文件需求分析-01") 
- [HadoopRDD源码分析-文件拆分partition划分-02](https://youtu.be/kesUJxGBWFA "HadoopRDD源码分析-文件拆分partition划分-02")
- [HadoopRdd源码分析 本地文件读取源码分析 03](https://youtu.be/EuNaoJhK-x4 "HadoopRdd源码分析 本地文件读取源码分析 03")
- [HadoopRdd源码分析 本地文件读取源码分析 04](https://youtu.be/GcPi9b-iltE "HadoopRdd源码分析 本地文件读取源码分析 04")

### Spark 远程调试
 - 详细说明文档： https://github.com/opensourceteams/spark-scala-maven/blob/master/md/SparkRemoteDebug.md



#### 相关链接

- [HadoopRDD源码分析说明文档详细](https://github.com/opensourceteams/spark-scala-maven/blob/master/md/hadoopRdd.md "HadoopRDD源码分析说明文档")
