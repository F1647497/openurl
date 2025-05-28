功能：
前端操作：
第三方注册、登录、余额查询加扣款  api
拉单
报表操作
http://ynpay.kongjudo.com/paycenter/game/cmd/getBalance  余额查询加扣款

原型：
https://uvjb9m.axshare.com/?id=6kz3xc&p=%E6%B3%95%E5%B8%81%E6%8F%90%E6%AC%BE%EF%BC%88%E5%B7%B2%E5%AE%A1%E6%A0%B8%EF%BC%89&g=1
https://o9eucr.axshare.com/?id=kuna1q&p=%E8%BF%90%E8%90%A5%E9%85%8D%E7%BD%AE&g=1
https://www.figma.com/design/42NnzFjZHRn0N6GCtG73F1/Uponly-Product?node-id=0-1&t=qrG9CrbMntctt1q3-0
https://uvjb9m.axshare.com/?id=kj3d11&p=profile___1&g=1
https://uvjb9m.axshare.com/?id=reyow4&p=%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8F%E8%AF%A6%E6%83%85%E9%A1%B5%EF%BC%88%E5%8E%9F%E5%89%8D%E7%BD%AE%E5%BC%B9%E7%AA%97%EF%BC%89&g=1
https://o9eucr.axshare.com/?id=xfqrh0&p=rfc%E6%80%BB%E8%A7%88%E8%A1%A8%EF%BC%88%E5%BE%85%E5%AE%9A%EF%BC%89&g=1
https://allwecan.info/api-doc/single-wallet/PRD#tag/singleWalletApiFunctions/operation/PlaceBet
https://studio.evolutiongaming.com/api/evo-std-rest/docs/index.html

https://uponlypdtech.atlassian.net/jira/core/projects/UP/board

账号信息：
http://13.215.6.152:8080/view/TEST-JAVA/
william    1234qwer


rancher-test
https://18.140.115.53/dashboard/auth/login
admin
teED#$^&(*@!UE89608%



nacos
http://172.31.150.223:8848/nacos/#/configurationManagement?serverId=center&group=&dataId=&namespace=vic-local&pageSize=&pageNo=&appName=&namespaceShowName=vic-local      


casino app端
https://2uptest.com/    2up123      cody1111019    123456qwer    william01    123456qwer


后台管理系统
https://admin.2uptest.com/bettingmanagement/betting-casino-management    william01    william01


casino  原型
https://uvjb9m.axshare.com/?id=vgnstd&p=%E8%B5%8C%E5%9C%BA%E6%B8%B8%E6%88%8F%E9%80%BB%E8%BE%91_casino&g=1   app端
https://o9eucr.axshare.com/?id=cspxns&p=%E8%B5%8C%E5%9C%BA%E5%85%A5%E5%8F%A3%E8%B7%B3%E8%BD%AC%E5%B1%82%E7%BA%A7%E7%AE%A1%E7%90%86&g=1  后台管理系统
shon和vic 这是我本地的swagger网址 可以加到我的最爱  
老虎机:
http://localhost:8866/java-portal/swagger-ui/swagger-ui/index.html
http://localhost:8811/java-admin/swagger-ui/swagger-ui/index.html
http://localhost:8855/java-wallet/swagger-ui/swagger-ui/index.html
http://localhost:8877/java-rank/swagger-ui/swagger-ui/index.html
CASINO:
http://localhost:8833/docs/casino-service/swagger-ui/index.html
老虎机  真人  体育  彩票


其它：
直播管理配置  backup_live_wins_conf
直播管理记录  backup_live_wins_record
big_win实时大赢阈值配置  big_wins_conf
big_win实时大赢阈值配置  big_wins_conf_copy1

推广管理   promotion_management
厂商配置信息表  provider_conf
供应商前台(客户端)显示筛选表  provider_visible
rebet_explaination
推荐管理  recommended_management


轮播图  slot_banner
游戏表  slot_management
跑马灯类型  slot_marquee
地区 slot_region
游戏表  slot_w_new
注单赢钱记录  slot_win_record
注单表 slots_bet_order
注单表 slots_bet_order_new_0525
游戏的top用户赔付金额统计表 slots_game_top_record
注单请求日志表   slots_order_log
返利记录表 slots_rebate_record
钱包结算记录表（失败记录） slots_settle_log_bak
用户收藏游戏表 user_favorite
用户和收藏游戏关系表 users_collections
用户返水 users_rebet
用户游戏表 big_wins_management  


轮播图  casino_banner 暂时没有用
游戏标签 casino_gametag  没有


地区  casino_game_region
游戏类型  casino_game_type
游戏订单  casino_order
游戏订单历史  casino_order_history  定时从第三方拉取注单数据，去更新 casino_order
游戏供应商表 casino_provider
游戏推荐  casino_recommend
用户  casino_user
游戏入口表 casino_game_entrance
游戏收藏表 casino_favorite 
投注配置表 casino_bigwins_conf  
第三方游戏表 casino_game_original


上榜大赢家  根据后台大赢家配置进行判断， 上榜大赢家

游戏分类

收藏  全部游戏  
活动（后台配置为推广展示）


接下来后面是分类游戏入口






定时任务
定时从第三方拿取注单数据结果，放入casino_order_history，更新 casino_order表

定时任务把数据推送钱包和报表数据
定时任务1：  EVOJob
getEVOGameList


投注次数：用户生涯投注次数，每投注一次数值+1

总投注额：用户生涯投注总额，每次投注金额的累加数值

获胜次数：用户生涯投注获胜的次数，半赢与全赢均+1，半输/输/平局不计入

被跟注次数：用户生涯被其它用户跟注的次数，每被跟注一次数值+1


平均赔率：用户生涯投注的平均赔率

公式 = 投注赔率的总和 / 投注次数的总和


平均投注额：用户生涯投注的平均投注额

公式 = 投注金额的总和 / 投注次数的总和



总投注额     用户生涯投注总额，每次投注金额的累加数值
获胜次数     用户生涯投注获胜的次数，半赢与全赢均+1，半输/输/平局不计入
平均获胜额    总获胜额/获胜次数


StatisticsController


 @Operation(summary = "查询个人统计数据")
    @RequestMapping(value = "/list", method = RequestMethod.POST)
    @ResponseBody
    public Result<StatisticsVO> statisticsList(@RequestHeader("Slanguage") String slanguage,
                                               @RequestParam("uid") Long uid,
                                               @RequestHeader("Sregion") Integer region) {
											   
											   使用此服务器以安全地访问开放互联网：

1) 为您的设备下载并安装 Outline 应用：

- iOS：https://itunes.apple.com/app/outline-app/id1356177741
- MacOS：https://itunes.apple.com/app/outline-app/id1356178125
- Windows：https://s3.amazonaws.com/outline-releases/client/windows/stable/Outline-Client.exe
- Linux：https://s3.amazonaws.com/outline-releases/client/linux/stable/Outline-Client.AppImage
- Android：https://play.google.com/store/apps/details?id=org.outline.android.client
- Android 替代链接：https://s3.amazonaws.com/outline-releases/client/android/stable/Outline-Client.apk

2) 您会收到一个以 ss:// 开头的访问密钥。收到该密钥后，请复制此访问密钥。

3) 打开 Outline 客户端应用。如果系统自动检测到您的访问密钥，请点按“连接”并继续。如果系统未自动检测您的访问密钥，请将其粘贴到该字段中，然后点按“连接”并继续。

您可以使用开放互联网了！为了确保您已成功连接到服务器，请尝试在 Google 搜索中搜索“what is my ip”。Google 中显示的 IP 地址应与 Outline 客户端中的 IP 地址一致。

如需详细了解 Outline，请访问 https://getoutline.org/



ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTppTTNDZDRKNW02NVdwY0lpVUpjUDZh@out.2upnow.com:55171/?outline=1

进入游戏 ：  类型大厅（game_lobby）、大厅（lobby）、游戏（game）

使用outline vpn后
java nacos
http://middleware.2uptest.com:8848
redis
middleware.2uptest.com:6379
kafka
middleware.2uptest.com:9091
middleware.2uptest.com:9092
middleware.2uptest.com:9093
mysql
database-test1.cvjrqhcoolrr.ap-southeast-1.rds.amazonaws.com:3306
谷歌邮箱：https://mail.google.com/mail/u/0/#inbox
微软邮箱：https://www.office.com/?auth=2
GitLab地址：https://gitlab.2upnow.com/uponly/uponly-slot
jira处理平台https://uponlypdtech.atlassian.net/browse/UP-2405
Jenkins： http://13.215.6.152:8080/login?from=%2F
k8s： https://18.140.115.53/dashboard/c/c-m-8drc7zbv/explorer/pod  U： admin P： teED#$^&(*@!UE89608%
admin后台测试环境：https://admin.2uptest.com/operations/ad-management
H5测试环境：https://app.2uptest.com/   password: 2up123

admin后台原型图：https://o9eucr.axshare.com/?id=ys01aa&p=_______slots_management&g=1
H5原型图：https://uvjb9m.axshare.com/?id=fp6dv3&p=%E6%9B%B4%E6%96%B0%E6%97%A5%E5%BF%97&g=1

本地启动后，swagger地址：
老虎机:
http://localhost:8866/java-portal/swagger-ui/swagger-ui/index.html
http://localhost:8811/java-admin/swagger-ui/swagger-ui/index.html
http://localhost:8855/java-wallet/swagger-ui/swagger-ui/index.html
http://localhost:8877/java-rank/swagger-ui/swagger-ui/index.html

CASINO:
http://localhost:8833/docs/casino-service/swagger-ui/index.html



spring:
  jackson:
    time-zone: Asia/Shanghai
  redis:
    redisson:
      config: |
        singleServerConfig:
          password: null
          address: "redis://test-master-slave.vnt2qy.ng.0001.apse1.cache.amazonaws.com:6379"
          database: 1
        threads: 0
        nettyThreads: 0
        # codec: !<org.redisson.codec.FstCodec> {}
        transportMode: "NIO"
  kafka:
    consumer:
      bootstrap-servers: kafka-0.kafka-headless:9092,kafka-1.kafka-headless:9092,kafka-2.kafka-headless:9092
      # 是否自动提交
      enable-auto-commit: false
      # 消费者组
      group-id: himanshu_consumer_group
      # 消费偏移配置
      # none：如果没有为消费者找到先前的offset的值,即没有自动维护偏移量,也没有手动维护偏移量,则抛出异常
      # earliest：在各分区下有提交的offset时：从offset处开始消费；在各分区下无提交的offset时：从头开始消费
      # latest：在各分区下有提交的offset时：从offset处开始消费；在各分区下无提交的offset时：从最新的数据开始消费
      auto-offset-reset: earliest
      key-deserializer: org.apache.kafka.common.serialization.ByteArrayDeserializer
      value-deserializer: org.apache.kafka.common.serialization.ByteArrayDeserializer
    producer:
      bootstrap-servers: kafka-0.kafka-headless:9092,kafka-1.kafka-headless:9092,kafka-2.kafka-headless:9092
      # 重试次数，设置大于0的值，则客户端会将发送失败的记录重新发送
      retries: 3
      # 批量处理大小，16K
      batch-size: 16384
      # 缓冲存储大，32M
      buffer-memory: 33554432
      # procedure要求leader在考虑完成请求之前收到的确认数，用于控制发送记录在服务端的持久化，其值可以为如下：
      # acks = 0 如果设置为零，则生产者将不会等待来自服务器的任何确认，该记录将立即添加到套接字缓冲区并视为已发送。在这种情况下，无法保证服务器已收到记录，并且重试配置将不会生效（因为客户端通常不会知道任何故障），为每条记录返回的偏移量始终设置为-1。
      # acks = 1 这意味着leader会将记录写入其本地日志，但无需等待所有副本服务器的完全确认即可做出回应，在这种情况下，如果leader在确认记录后立即失败，但在将数据复制到所有的副本服务器之前，则记录将会丢失。
      # acks = all 这意味着leader将等待完整的同步副本集以确认记录，这保证了只要至少一个同步副本服务器仍然存活，记录就不会丢失，这是最强有力的保证，这相当于acks = -1的设置。
      #可以设置的值为：all, -1, 0, 1
      acks: 1
      key-serializer: org.apache.kafka.common.serialization.StringSerializer
      value-serializer: org.apache.kafka.common.serialization.StringSerializer
    # 监听
    listener:
      # record：当每一条记录被消费者监听器ListenerConsumer处理之后提交
      # batch：当每一批poll()的数据被ListenerConsumer处理之后提交
      # time：当每一批poll()的数据被ListenerConsumer处理之后，距离上次提交时间大于TIME时提交
      # count：当每一批poll()的数据被ListenerConsumer处理之后，被处理record数量大于等于COUNT时提交
      # count_time：TIME或COUNT中有一个条件满足时提交
      # manual：当每一批poll()的数据被ListenerConsumer处理之后, 手动调用Acknowledgment.acknowledge()后提交
      # manual_immediate：手动调用Acknowledgment.acknowledge()后立即提交，一般推荐使用这种
      ack-mode: manual_immediate
## master ?????
master:
  datasource:
    url: jdbc:mysql://database-test1.cvjrqhcoolrr.ap-southeast-1.rds.amazonaws.com:3306/db_2up_slots?serverTimezone=Asia/Shanghai&useSSL=false&useUnicode=true&characterEncoding=UTF-8
    username: devadmin
    password: BKun3DY5aFvU
    driverClassName: com.mysql.cj.jdbc.Driver

    
