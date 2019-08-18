# MLog

## Log 微服务监控 及 微信群x24h报警

### 一、面临问题

### 随着分布式微服务容器技术的发展，传统监控系统面临许多问题 ?
```
容器如何监控

微服务如何监控

集群性能如何进行分析计算

如何管理agent端大量配置脚本

这些都是传统监控所要面临的棘手问题，如何解决当前遇到的问题，GPE横空出世。
```
### 二、系统监控

### 目标群体：系统日志、服务器、容器、系统软件运行指标 ?
```
日志架构：ELK (Elasticsearch+Logstash+Kibana+Redis)

监控架构：GPE (Grafana+Prometheus+Exporter+Consul)

报警方式：Vbot、邮件、短信、钉钉以及自定义webhook，监控中心7×24小时
```
### 三、项目计划
### 年前计划
```
① 一期：完成全量业务监控demo（基于MySQL）

② 二期：完成及时微信群通知demo（基于WeChat）

③ 三期：完成实时日志搜索demo（基于ElasticSearch）
```
### 年后计划
```
④四期：完成告警归集和存储（基于Redis和MySQL）

⑤五期：完成后台可视化分析（基于React和node.js）
```

## 金字塔计划
```
1、基于一个人的力量是有现的

2、有精力的小伙伴可以考虑加入

3、有微服务监控可以提 `痛点issue`

4、有想法的路人甲可以提 `创意issue`

5、让我们一起！在微服务监控的 `金字塔 : 增砖添瓦`

```
.

.

.

### DO The List

#### ① 一期：设计Demo


![One Demo](https://github.com/m-sql/mlog/blob/master/imgs/proxy.png)

#### ① 一期：新增 设计图、功能PK图

![design PK](https://github.com/m-sql/mlog/blob/master/src/pk.jpg)

##### 参考链接：
* 1、https://github.com/grafana/loki
* 2、https://grafana.com/blog/2018/12/12/loki-prometheus-inspired-open-source-logging-for-cloud-natives
* 3、https://blog.giantswarm.io/grafana-logging-using-loki
* 4、https://cloud.tencent.com/developer/news/18509
* 5、http://book.open-falcon.org/zh/intro/index.html
* 6、https://help.aliyun.com/knowledge_detail/68035.html
* 7、https://jasper-zhang1.gitbooks.io/influxdb/content/Concepts/storage_engine.html
* 8、https://github.com/bergquist/fake-simple-json-datasource
* 9、https://github.com/grafana/simple-json-datasource

