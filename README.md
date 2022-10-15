# 

hostname= api.revenuecat.com,wallpaper.soutushenqi.com,api.xiuxiu.meitu.com,buy.itunes.apple.com,m2u-api.getkwai.com,partner-ai-api.quthing.com,api.xunyou.mobi,subscription-api.notedapp.io,user-kaji-api.b612kaji.com,www.xmind.cn,api.meiyan.com,fcapi.91por.vip,%APPEND% api4.bybutter.com,www.freshhome.top,cubox.pro,apigate.zymk.cn,notability.com,vipapi.jxedt.com,lcs-mobile-cops.adobe.io,photos.adobe.io,ap*.intsig.net,awvp.aoscdn.com,account.wps.cn,api.qingning6.com,user.xiaozaoapp.com,mp.weixin.qq.com,commerce-api.faceu.mobi,wx-xmlb.lanfeitech.com,changeclothes.szsszykj.com,cn-rest.dhcn.greenergrass.games,www.caaaat.com,curriculum-api.yizhiweixin.com,api.sortedapp.com,*.kuwo.cn, *.lrts.me,dict.youdao.com,server1.xxxy.dayukeji.com,update.kl321.com,top-widgets-api.xiaozujian.com,bladecn.mofishgames.com,wx-bingdu.lanfeitech.com,license.pdfexpert.com,jiliapi.xndplqq.cn,yxgs-tf-yx.tapenjoy.com,mid.zineapi.com,ttdy.aslk2018.com,scibug.com,pay.wecut.com,baimiao.uzero.cn,api-weather.andy.works,closet.jinjian.tech,p.du.163.com,api.vistopia.com.cn,i.weread.qq.com,api.v1.esread.com,yyy.bosum.com,gateway.ergedd.com,fufei.fengyunsoft.cn,api-sub.meitu.com,api.apphud.com,simh5.soloknight.xyz,gjzwwx.game.jingyougz.com,xmct.qszhg.6hwan.com,www.njmc.vip,service.ilovepdf.com,shared.lc-cn-n1-shared.com,https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/mksp.js,tutugushiapi.tutuerge.com,iap.etm.tech,api-v3.speedtest.cn,bmall.camera360.com,xy-viva.kakalili.com,api-chn.rthdo.com,pgapi.ksmobile.com,miniapi.52muyou.com,wxsdk-data.d3games.com,saomiao.34354.com,www.weikeduo.top,api.memrise.com,qianji.xxoojoke.com,xluser-ssl.xunlei.com,ssl-api.itranslateapp.com,hi.weshine.im,appapi.*,api.*.com,xiaobai.mcfifa.cn,dev.fish.17fish.cool,api.duitang.com,cm.szsszykj.com,commerce-api.faceu.mobi,data.ufbae.com,restore-access.indream.app,scanner.jianse.tv,api2.mubu.com,cn.invit.vip,app.api.versa-ai.com,flomoapp.com,nowapi.navoinfo.cn,dq.xiangha.com,apiios_dq.xiangha.com,gateway.caixin.com,ipadcms.caixin.com,restore-access.indream.app,vira.llsapp.com,app-live.planefinder.net,account.wps.cn,*account.wps.com,*.lingdu2019.cn,nomo.dafork.com,api.feidee.net,userapi.feidee.net,tg.feidee.com,community.feidee.com,api.revenuecat.com,api.meiease.cn,server.yoyiapp.com,buy.itunes.apple.com,apiios.xiangha.com,apiios_dq.xiangha.com,appweb_dq.xiangha.com,101.200.225.157,*.wtzw.com,api.infzm.com,tagit.hyhuo.com,*.youyu*,txv04.com,*.gotokeep.com,*mt*.com,apiw.9waquan.com,*.chuniao.*,app.weilaixushi.com,api.orientlion.com,app.qdjdswkj.com,api.0954auto.com,appapi.xmblgg.com,api.tidal.com,*.*xima*.*,*.xmcdn.com,shukego.com,yiliang8888.com,91mingyang.com,mnter.com,f5bc.club,sjapp.o3aqqc.work,yimuapp.com,app.api.versa-ai.com,o0o0plpl11.xinai99.com,zjgeo.eqobc.com,xnour.xonap.com,opzzy.kefsww.com,tqrbq.mpckv.com,subscription.grammarly.com,sjapi.juqianpu.com,ys.huajibh.com,api.gygarden.cn,api.xminiapp.cn,api.petsbang.cn,api.yngenji.cn,api.*.cn,media.deezer.com,ios-api-2.duolingo.cn,lvv2.com,ts1i.dk.y8848.xyz,api.neuralprisma.com,cn.pornhubpremium.com,*.wallpaperscraft.com,api3.umu168.com,huo.hzzykj.net,apiclb.djshow.cn,js.wpadmngr.com,a.realsrv.com,syndication.realsrv.com,rtbrennab.com,madou.club,poweredby.jads.co,vyfrxuytzn.com,bg4nxu2u5t.com,*.pssy.xyz

#Noto 笔记+解锁订阅
^https?:\/\/api\.revenuecat\.com\/v1\/(receipts|subscribers\/\$RCAnonymousID%3A\w{32})$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/noto.js

#音频剪辑- 音乐剪辑大师+解锁订阅
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/ypjj.js

#菜谱大全+解锁VIP
^https:\/\/apiios_dq\.xiangha\.com url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/cpdq.js

#航旅追踪+解锁订阅
^https:\/\/api\.revenuecat\.com\/.+\/(receipts$|subscribers\/(\$RCAnonymousID%)?(\w)*$) url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/hlzz.js

#Now冥想-助眠白噪音乐+解锁VIP内容
^https:\/\/nowapi\.navoinfo\.cn url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Now.js

#手机硬件管家+解锁订阅
^https:\/\/api\.revenuecat\.com\/.+\/(receipts$|subscribers\/(\$RCAnonymousID%)?(\w)*$) url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/sjyjgj.js

#Spark Mail-智能邮箱+解锁订阅
^https:\/\/api\.revenuecat\.com\/.+\/(receipts$|subscribers\/(\$RCAnonymousID%)?(\w)*$) url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/SparkMail.js

#PDF Viewer Pro+解锁订阅
^https:\/\/api\.revenuecat\.com\/v1\/subscribers.+ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/PDFViewer.js

#Usage: System+解锁订阅
^https:\/\/api\.revenuecat\.com\/v1\/subscribers.+ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Usage.js

#WidgetArt-自定义桌面小组件+恢复订阅
^https:\/\/api\.revenuecat\.com\/v1\/subscribers.+ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/WidgetArt.js

#Motivation-Daily quotes+解锁订阅
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Motivation.js

#flomo 浮墨-卡片笔记+解锁pro
^https:\/\/flomoapp\.com\/api\/v1\/user\/me url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/flomo.js

#Retake-Al照片修复+解锁订阅
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Retake.js

#percento-轻松管理你的资产+解锁订阅
^https?:\/\/api\.revenuecat\.com\/v1\/(receipts|subscribers\/\$RCAnonymousID%3A\w{32})$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/percento.js

#色采 -配色助手+解锁订阅
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/sc.js

#马卡龙玩图 +解锁订阅
https://app.api.versa-ai.com/pay/order/iap/check url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/mklwt.js

#Color Widgets+解锁订阅
^https?:\/\/api\.revenuecat\.com\/v1\/(receipts|subscribers\/\$RCAnonymousID%3A\w{32})$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/ColorWidgets.js

#卡片日记+解锁订阅
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/kprj.js

#奇妙组件+解锁订阅
^https?:\/\/api\.revenuecat\.com\/v1\/(receipts|subscribers\/\$RCAnonymousID%3A\w{32})$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/qmzj.js

#电子请柬制作+解锁VIP
^https:\/\/cn\.invit\.vip\/users\/info url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/dzqjzz.js

#幕布-大纲笔记+解锁VIP
^https:\/\/api2.mubu.com\/v3\/api\/user/* url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/mubu.js

#极速扫描仪+解锁订阅
^https:\/\/scanner\.jianse\.tv\/api\/users\/loginUser url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/jssmy.js

#Nicegram: Unlimited Text+解锁订阅
https?:\/\/restore-access\.indream\.app\/restoreAccess\?id=\d{5,10} url echo-response text/json echo-response https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Nicegram.js

#指尖笔记+解锁永久VIP
http:\/\/data\.ufbae\.com\/User\/GetUser url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/zjbj.js

#轻颜相机+解锁VIP
^https:\/\/commerce-api\.faceu\.mobi\/commerce\/v1\/subscription\/user_info? url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/qyxj.js

#趣制作-视频剪辑+解锁VIP
^https:\/\/cm\.szsszykj\.com\/interface\/GetVip\.php url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/qzzvip.js

#堆糖-爱豆壁纸美图社区+解锁VIP
^https:\/\/api\.duitang\.com\/napi url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/duitang.js

#实况钓鱼+无限金币
^https:\/\/dev\.fish\.17fish\.cool:6008\/api\/livefishing\/v10\/getProgress url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/yx/skdy.js

#神弓守护者+无限钻石金币
^https:\/\/xiaobai\.mcfifa\.cn\/data_sjdata? url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/yx/sgsfz.js

#91视频(TF版)+解锁VIP
^https://(app|api).*.com/m_user/info url script-request-header https://raw.githubusercontent.com/89996462/Quantumult-X/main/ghs/91tv.js

#闪萌表情-解锁VIP
^https:\/\/hi\.weshine\.im\/v3\.0\/account\/profile url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/smbq.js

#iranslate 翻译+解锁订阅
https://ssl-api.itranslateapp.com/accounts/v4/subscriptions/verify/ios url script-request-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/iTranslate.js

#Fabulous每日动力泉源+解锁订阅
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/fabulous.js

#迅雷-你的专享云盘+解锁VIP
https://xluser-ssl.xunlei.com/xluser.core.login/v3/getuserinfo url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/xunlei.js

#Darkroom：照片和视频编辑器+解锁
^https?:\/\/api\.revenuecat\.com\/v1\/(receipts|subscribers\/\$RCAnonymousID%3A\w{32})$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/darkroom.js

#钱迹-存钱记账小能手+解锁VIP
^https:\/\/qianji\.xxoojoke\.com\/vip\/configios url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/qj.js

#移动扫描仪+解锁VIP
^https:\/\/saomiao\.34354\.com\/api\/open\/member\/level url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/ydsmy.js

#gear浏览器插件+解锁订阅
^https?:\/\/api\.revenuecat\.com\/v1\/(receipts|subscribers\/\$RCAnonymousID%3A\w{32})$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/gear.js

#搜图神器+解锁VIP
http:\/\/wallpaper\.soutushenqi\.com\/api\/v1\/account url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/stsq.js

#美图秀秀+解锁VIP
^https:\/\/api\.xiuxiu\.meitu\.com\/v1 url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/mtxx.js

#https抓包+解锁订阅
^https?:\/\/buy\.itunes\.apple\.com\/verifyReceipt$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/https.js

#一甜相机+解锁VIP
^https?:\/\/m2u-api\.getkwai\.com\/api-server\/api\/v2\/vip\/vipUserInfo url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/ytxj.js

#PrettyUp视频美化+解锁订阅
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/upp.js

#来音智能陪练+解锁VIP
^https:\/\/partner-ai-api\.quthing\.com\/ai\/vip\/state url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/ly.js

#幻影相册+解锁VIP
^https?:\/\/buy\.itunes\.apple\.com\/verifyReceipt$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/hyxc.js

#迅游手游加速器+解锁VIP
^https:\/\/api\.xunyou\.mobi\/api\/v1\/android\/sessions url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/xyjsq.js

#Noted-录音笔记+解锁订阅
^https:\/\/subscription-api\.notedapp\.io\/api\/verifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/noteb.js

#B612咔叽+解锁VIP
^https:\/\/user-kaji-api\.b612kaji\.com\/v1\/purchase\/subscription\/subscriber\/status url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/bj.js

#XMind思维导图+解锁订阅
^https:\/\/www\.xmind\.cn\/_res\/devices url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/xmind.js

#美颜相机+解锁VIP
^https:\/\/api\.meiyan\.com\/vip\/user_info\.json url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/myxj.js

#文件管理器+解锁订阅
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/wjglq.js

#1blocker+解锁订阅
^https:\/\/api\.revenuecat\.com\/v1\/subscribers url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/blocker.js

#old roll复古相机+解锁订阅
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/old.js

#Picsew滚动截图+解锁订阅
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Picsew.js

#Pixelmator Photo+解锁订阅
https:\/\/api\.revenuecat\.com\/v1\/(subscribers|receipts) url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Pixelmator.js

#Proknockout扣图神器+解锁VIP
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Proknockout.js

#美队tv（18+）+解锁VIP会员
^https:\/\/fcapi\.91por\.vip\/api\/video\/user\/info url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/mgtv.js

#黄油相机+解锁VIP
https:\/\/api4\.bybutter\.com\/v4\/* url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/hy.js

#如期-扫码记录保质期+解锁VIP
^https:\/\/www\.freshhome\.top\/mngruqi url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/rq.js

#cubox-收藏阅读+解锁VIP
^https:\/\/cubox\.pro\/c\/api\/userInfo url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/cubox.js

#Launch Center Pro+解锁订阅
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/pro.js

#Grow - 你的健康+恢复订阅
^https:\/\/api\.revenuecat\.com\/v1\/subscribers.+ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Grow.js

#VSCO:照片编辑+恢复订阅
^https:\/\/api\.revenuecat\.com\/v1\/subscribers.+ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/vsco.js

#知音漫客+解锁VIP
^https:\/\/apigate\.zymk\.cn url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/zymk.js

#Notability +解锁订阅
^https?:\/\/notability\.com\/subscriptions url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Notability.js

#图图记账+恢复订阅
^https:\/\/api\.revenuecat\.com\/v1\/subscribers.+ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/ttjz.js

#驾校一点通+解锁VIP
^https:\/\/vipapi\.jxedt\.com\/store\/vip\/check url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/jxydt.js

#Photoshop Express +解锁高级用户
^https:\/\/lcs-mobile-cops\.adobe\.io\/mobile_profile url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Photoshop.js

#Lr Adobe Lightroom+解锁订阅
^https:\/\/photos\.adobe\.io\/v2\/accounts* url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/lightroom.js

#扫描全能王-手机扫描仪+解锁VIP
^https:\/\/(api|api-cs)\.intsig\.net\/purchase\/cs\/query_property\? url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/smqnw.js

#Pandora-管理你的订阅+恢复订阅
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Pandora.js

#傲软抠图-专业图片+解锁VIP
^https:\/\/awvp\.aoscdn\.com\/base\/vip\/client\/authorizations url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/arqt.js

#WPS Office+解锁VIP
^https?:\/\/account\.wps\.cn\/api\/users url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/wps.js

#青柠海报设计+解锁VIP
^https:\/\/api\.qingning6\.com\/api\/user\/getUserInfo url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/qnhb.js

#CEO周课+解锁VIP
^https:\/\/user\.xiaozaoapp\.com\/app\/ceouser\/loginAuto url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/ceo.js

#Apollo-记录你的影视生活
^https?:\/\/api\.revenuecat\.com\/v1\/(receipts|subscribers\/\$RCAnonymousID%3A\w{32})$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Apollo.js

#白云天气-感知自然呼吸+解锁订阅
^https?:\/\/api\.revenuecat\.com\/v1\/(receipts|subscribers\/\$RCAnonymousID%3A\w{32})$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/bytq.js

#MoneyThings—记账+解锁订阅
^https?:\/\/api\.revenuecat\.com\/v1\/(receipts|subscribers\/\$RCAnonymousID%3A\w{32})$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/MoneyThings.js

#Scanner Pro+解锁订阅
^https?:\/\/api\.revenuecat\.com\/v1\/(receipts|subscribers\/\$RCAnonymousID%3A\w{32})$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Scanner.js

#微信自动阅读+薅羊毛
^https?://mp\.weixin\.qq\.com/s\?.* url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/wechat.js

#醒图+解锁VIP
^https:\/\/commerce-api\.faceu\.mobi\/commerce\/v1\/subscription url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/xt.js

#熊掌记- Markdown+解锁订阅
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/xzj.js

#三国全明星+无限兑换元宝
^https:\/\/wx-xmlb\.lanfeitech\.com\/api\/api\/exchange_cdkey url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/sgqmx.js

#最美证件照+解锁VIP
^https:\/\/fufei\.fengyunsoft\.cn\/api\/client\/info url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/zmzjz.js

#骰子猎人+解锁无限钻石金币
^https:\/\/cn-rest\.dhcn\.greenergrass\.games\/v1\/sync\/Player url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/szlr.js

#买怪打装备+无限兑换钻石
^https:\/\/www\.caaaat\.com:5502\/cdk\/getcdk url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/mzbdgs.js

#快手小程序+易知课堂+解锁观看
^https:\/\/curriculum-api\.yizhiweixin\.com\/curriculum\/newDetail url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/ksyzkt.js

#fileball+解锁订阅
^https?:\/\/api\.revenuecat\.com\/v1\/(receipts|subscribers\/\$RCAnonymousID%3A\w{32})$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/fileball.js

#疯狂消消消+无限钻石金币
^https:\/\/wxsdk-data\.d3games\.com\/game\/merge\/get url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/fkxxx.js

#AI换脸秀+解锁VIP
^https:\/\/changeclothes\.szsszykj\.com\/interface\/GetIosVip.php url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/aihlx.js

#谜底时钟 +解锁订阅
^https?:\/\/api\.revenuecat\.com\/v1\/(receipts|subscribers\/\$RCAnonymousID%3A\w{32})$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/mdsz.js

#documents文件管理器+解锁订阅
^https:\/\/license\.pdfexpert\.com\/api\/2\.0\/documents\/subscription\/refresh url script-request-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/documents.js

#Chic-Stylish Camera+解锁VIP
^https:\/\/api-sub\.meitu\.com\/v2\/user\/vip_info\.json url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Chic.js

#Fin -预算与开销追踪+解锁订阅
^https?:\/\/api\.revenuecat\.com\/v1\/(receipts|subscribers\/\$RCAnonymousID%3A\w{32})$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/fin.js

#Sorteds - 日历+解锁订阅
^https:\/\/api\.sortedapp\.com\/receipts\/verify url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Sorted.js

#Panda Widget+解锁订阅
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/pandavip.js

#酷我音乐+解锁VIP【广告➕VIP➕数字➕下载】
^https?:\/\/.*\.(kuwo|lrts)\.(cn|me)\/(a\.p|music\.pay|(vip\/(v2|enc)\/(theme|user\/vip))|(EcomResource|(Mobile)?Ad)Serv(er|ice)).* url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/kwyy.js

#网易有道词典+解锁VIP
^https:\/\/dict\.youdao\.com\/vip\/user\/status url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/wyydcd.js

#荒野日记—孤岛+无限贝壳
http:\/\/server1\.xxxy\.dayukeji\.com:15009\/Logic\/user\/querymail1 url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/hyrz.js

#地下城割草+ 无限钻石和金币
^https:\/\/update\.kl321\.com\/funservice\/s01\/prefetch\/unifiedfetch url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/yx/dxcgc.js

#Planny • 智能待办+解锁订阅
^https?:\/\/api\.revenuecat\.com\/v1\/(receipts|subscribers\/\$RCAnonymousID%3A\w{32})$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Planny.js

#TopWidgets-小组件+解锁订阅
^https:\/\/top-widgets-api\.xiaozujian\.com\/api\/app\/config\/userConfig url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/widgets.js

#刀剑大作战+无限钻石金币
^https:\/\/bladecn\.mofishgames\.com\/bladesrv\/login url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/yx/djdzz.js

#Pillow： 睡眠周期跟踪器+解锁订阅
^https?:\/\/api\.revenuecat\.com\/v1\/(receipts|subscribers\/\$RCAnonymousID%3A\w{32})$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Pillow.js

#消灭病毒+无限钻石金币
^https:\/\/wx-bingdu\.lanfeitech\.com\/api\/archive\/get url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/yx/xmbd.js

#PDF—Expert点睛+解锁订阅
^https:\/\/license\.pdfexpert\.com\/api\/2\.0\/pdfexpert6\/subscription\/refresh url script-request-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/PDFExpert.js

#探花视频+解锁VIP—9.27更新
^https:\/\/jiliapi\.xndplqq\.cn\/api\/member\/info url script-request-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ghs/thsp.js

#小兵别嚣张+无限钻石和金币材料
http:\/\/yxgs-tf-yx\.tapenjoy\.com\/api\/user\/dl url script-request-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/yx/xbbxz.js

#拼图鸭相机-解锁VIP
^https:\/\/puzzle\.xcxsc\.net\/v5\/user\/info url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/ptyxj.js

#拼图酱+解锁订阅
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/ptj.js

#Varlens 微单相机+解锁VIP
^https:\/\/mid\.zineapi\.com\/@varlens\/api\/user\/info\/ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Varlens.js

#Focos+解锁订阅
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Focos.js

#微信小游戏天天钓鱼+解锁无限金币
^https:\/\/ttdy\.aslk2018\.com\/v2\/game\/download url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/yx/ttdy.js

#Symbolab计算器 +解锁订阅
^https?:\/\/scibug\.com\/appleSubscriptionValidate$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Symbolab.js

#MolyCam+解锁PRO
^https:\/\/pay\.wecut\.com\/apple\/iosVerifyReceipt\.php$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/MolyCam.js

#白描-OCR 文字识别+解锁黄金会员
^https?:\/\/baimiao\.uzero\.cn\/api\/v\d\.user\/appLaunchWithUser$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/baimiao.js

#Not Boring +解锁订阅
^https?:\/\/api-weather\.andy\.works\/v\d\/\w{18}$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/NotBoring.js

#尽简衣橱+解锁VIP
^https:\/\/closet\.jinjian\.tech\/api\/v3\/apple_app_store\/resolve_receipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/jjyc.js

#网易蜗牛读书+解锁VIP
^https:\/\/p\.du\.163\.com\/gain\/readtime\/info\.json url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/yywnds.js

#看理想-看见另一种可能+解锁VIP
^https:\/\/api\.vistopia\.com\.cn\/api url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/kanlixiang.js

#微信读书+解锁无限卡会员
^https:\/\/i\.weread\.qq\.com\/pay\/memberCardSummary url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/txwxds.js

#向日葵阅读+解锁VIP
^https:\/\/api\.v1\.esread\.com url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/xiangrikui.js

#博商小麦+解锁会员内容
http:\/\/yyy\.bosum\.com\/enterprise url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/boshangxiaomai.js

#儿歌点点+解锁VIP
http:\/\/gateway\.ergedd\.com url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/egdd.js

#音频剪辑提取+解锁订阅
^https:\/\/fufei\.fengyunsoft\.cn\/api\/client\/info url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/ypjjtq.js

#Wink-像修图一样修视频+解锁VIP
^https:\/\/api-sub\.meitu\.com\/v2\/user\/vip_info_by_group url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Wink.js

#EFEKT美易一视频特效+解锁订阅
^https:\/\/api\.apphud\.com\/v1\/subscriptions url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/EFEKT.js

#进站请刷卡+无限钻石金币
^https:\/\/miniapi\.52muyou\.com\/api\/init\/METRO url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/yx/jzqsk.js

#目标地图+解锁订阅
^https?:\/\/api\.revenuecat\.com\/v1\/(receipts|subscribers\/\$RCAnonymousID%3A\w{32})$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/mbdt.js

#photoGrid-照片拼图+解锁订阅
^https:\/\/pgapi\.ksmobile\.com\/v1\/ios\/auth url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/photoGrid.js

#小影-视频剪辑制作+解锁VIP
^https:\/\/(xy-viva\.kakalili|api-chn.rthdo)\.com\/api\/rest\/u\/vipVerifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/xiaoyin.js

#MX滤镜大师+解锁订阅
https?:\/\/bmall\.camera360\.com\/api\/mix\/recovery url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/MIX.js

#网速管家+解锁VIP
^https:\/\/api-v3\.speedtest\.cn\/user\/info url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/wsgj.js

#网速测试大师+解锁订阅
^https:\/\/iap\.etm\.tech\/receipts url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/wscsds.js

#Pixelance Al照片修复+解锁订阅
^https:\/\/iap\.etm\.tech\/receipts url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Pixelance.js

#Collart 拼图趣+解锁订阅
^https:\/\/iap\.etm\.tech\/receipts url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Collart.js

#印章生成器+解锁订阅
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/yzscq.js

#阿布睡前故事+解锁VIP
http:\/\/tutugushiapi\.tutuerge\.com url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/abushuiqiangushi.js

#大佬别嚣张+无限金币钻石
^https:\/\/yyqq1\.youngwingtec\.com:8777\/guest_login url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/yx/dlbxz.js

#米克锁屏+解锁订阅
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/mksp.js

#全能小组件- Quike+解锁订阅
^https:\/\/shared\.lc-cn-n1-shared\.com\/1\.1\/classes\/Users url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Quike.js

#Colorful—Widget+解锁订阅
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/ColorfulWidget.js

#Widgetsmith+解锁订阅
https://api.revenuecat.com/v1/(receipts|subscribers)/* url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/widgetSmith.js

#LovepDF-PDF+解锁订阅
https://service.ilovepdf.com/v1/user url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/lovePdf.js

#vision-个人OKR目标+解锁订阅
^https?:\/\/api\.revenuecat\.com\/v1\/(receipts|subscribers\/\$RCAnonymousID%3A\w{32})$ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/vision.js

#APTV+解锁订阅
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/aptv.js

#土豆地下城+无限钻石
^https:\/\/www\.njmc\.vip:5051\/download_savedata url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/yx/tddxc.js

#熊猫餐厅+无限竹子珍珠
^https:\/\/xmct\.qszhg\.6hwan\.com\/user\/get_player_data url script-request-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/yx/xmct.js

#植物反击战+无限钻石金币
^https:\/\/gjzwwx\.game\.jingyougz\.com\/api\/v1\/users\/login url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/yx/zwfjz.js

#房东模拟器+无限钞票钻石
^https:\/\/simh5\.soloknight\.xyz:9443\/FDH5Server\/game\/wx\/loadArchive url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/yx/fdmlq.js

#三国创业记+无限钻石
^https:\/\/www\.weikeduo\.top:8646\/ url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/yx/sgcyj.js

#Memrise跟忆术家学语言+解锁订阅
^https:\/\/api\.memrise\.com\/v1\.18 url script-response-body https://raw.githubusercontent.com/89996462/Quantumult-X/main/ycdz/Memrise.js

#麻豆社去除ADS
/static/adManager.js url reject-200
/static/adManager.m.js url reject-200
/npc/sdk/wp-banners.js url reject-200
/ad-provider.js url reject-200
/v1/api.php url reject-200
syndication.realsrv.com url reject-200
rtbrennab.com url reject-200
/ezkrxztkjxcuxul.php url reject-200
/js/jads.js url reject-200
/chicken.gif url reject-200
/solid.gif url reject-200
pssy.xyz url reject-200
vyfrxuytzn.com url reject-200

#DJ秀无限制下载
^https:\/\/apiclb\.djshow\.cn\/api\/banzou\/detail.php url script-response-body https://gitlab.com/ioshkj/quantumultx/-/raw/main/vipjs/djxiu.js

#Facelab解锁高级会员
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://gitlab.com/ioshkj/quantumultx/-/raw/main/vipjs/facelabvip.js

#火狐影视恢复永久会员
^http:\/\/huo\.hzzykj\.net\/\/app\/api\/MembershipInformation url script-response-body https://gitlab.com/ioshkj/quantumultx/-/raw/main/vipjs/huohuvip.js

#财新会员 （解锁财新文章阅读与音频限制）
^https?:\/\/gateway\.caixin\.com\/api\/app\-api\/auth\/(validate|validateAudioAuth) url script-request-header https://raw.githubusercontent.com/I-am-R-E/Functional-Store-Hub/Master/CaiXin/Script/CaiXin.js

#财新周刊会员
^https?:\/\/ipadcms\.caixin\.com\/(api|tmp|power)\/(articles?|myfree(v\d+)?) url script-response-body https://raw.githubusercontent.com/I-am-R-E/Functional-Store-Hub/Master/CaiXinWeekly/Script/CaiXinWeekly.js

#Nicegram会员
^https?:\/\/restore-access\.indream\.app\/restoreAccess\?id=\w+$ url script-echo-response https://raw.githubusercontent.com/I-am-R-E/Functional-Store-Hub/Master/Nicegram/Script/Nicegram.js

#流利说·阅读 (解锁流利说·阅读会员、解锁阅读权限、解锁音频权限等)
^https?:\/\/vira\.llsapp\.com\/api\/v\d\/\w+\/\w+$ url script-response-body https://raw.githubusercontent.com/I-am-R-E/Functional-Store-Hub/Master/LiuLiShuoYueDu/Script/LiuLiShuoYueDu.js

#PlaneFinder 解锁高级订阅
^https?:\/\/app\-live\.planefinder\.net\/api\/v\d+\/account\/\w+\/login url script-response-body https://raw.githubusercontent.com/I-am-R-E/Functional-Store-Hub/Master/PlaneFinder/Script/PlaneFinder.js

#WPS会员 (WPS解锁本地会员)
^https?:\/\/.*?account\.wps\.(com|cn)(:\d+)?\/api\/users\/\w+\/overview$ url script-response-body https://raw.githubusercontent.com/I-am-R-E/Functional-Store-Hub/Master/WPSOffice/Script/WPS.js

#绅士解锁批量下载
^https://(.+).lingdu2019.cn/ios_api/portrait/goods_(detail|detail_comment_list|down_detail) url script-response-body https://raw.githubusercontent.com/nameking77/Qx/main/rewrite/shenshi.js

#NoMo Cam 解锁订阅
^https?:\/\/nomo\.dafork\.com\/api\/v2\/iap\/ios_verify$ url script-request-body https://raw.githubusercontent.com/yqc007/QuantumultX/master/NoMoCamProCrack.js

#随手记
^https?:\/\/((user)?api|community)\.feidee\.(net|com)\/(v\d\/(pay/vip|profile/basic_info|app_themes/types)|transfer\/gapi\/accurat\/v\d\/tasks) url script-response-body https://raw.githubusercontent.com/I-am-R-E/QuantumultX/main/JavaScript/SuiShouJi.js
^https?:\/\/api\.feidee\.net\/v\d\/app_themes\/\d+\/download url script-echo-response https://raw.githubusercontent.com/I-am-R-E/QuantumultX/main/JavaScript/SuiShouJi.js
^https?:\/\/tg\.feidee\.com\/online_ad\/ url reject

#AudioMack解锁永久订阅
^https?:\/\/api\.revenuecat\.com\/v1\/subscribers\/(identify|\d+)$ url script-response-body https://raw.githubusercontent.com/yqc007/QuantumultX/master/AudioMackFProCrack.js

#Picsart
^https?:\/\/api\.meiease\.cn\/shop\/subscription\/validate url script-response-body https://raw.githubusercontent.com/I-am-R-E/QuantumultX/main/JavaScript/Picsart.js

#FIMO解锁全部胶卷
^https?:\/\/server\.yoyiapp\.com\/fimo-user\/apple\/certificate$ url script-response-body https://raw.githubusercontent.com/yqc007/QuantumultX/master/FiMoCameraProCrack.js

#TextEditor
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/I-am-R-E/QuantumultX/main/JavaScript/TextEditor.js	

#香哈菜谱
^https?:\/\/apiios\.xiangha\.com\/main\d+\/ url script-response-body https://raw.githubusercontent.com/I-am-R-E/QuantumultX/main/JavaScript/XiangHaCaiPu.js

#菜谱大全
^https?:\/\/apiios_dq\.xiangha\.com\/v\d\/ url script-response-body https://raw.githubusercontent.com/I-am-R-E/QuantumultX/main/JavaScript/CaiPuDaQuan.js
^https?:\/\/appweb_dq\.xiangha\.com\/center\/pay\/home url script-response-body https://raw.githubusercontent.com/I-am-R-E/QuantumultX/main/JavaScript/CaiPuDaQuan.js

#七猫小说
^https?:\/\/(api-\w+|xiaoshuo)\.wtzw\.com\/api\/v\d\/ url script-response-body https://raw.githubusercontent.com/I-am-R-E/QuantumultX/main/JavaScript/QiMaoXiaoShuo.js

#南方周末
^https?:\/\/api\.infzm\.com\/mobile\/(user|contents\?|contents\/\d+\?|contents\/\d+\/isview\?|course_borrow|courses\/\d+\?|mall|course_items) url script-response-body https://raw.githubusercontent.com/I-am-R-E/QuantumultX/main/JavaScript/NanFangZhouMo.js

#拦截100解锁超级会员
^https?:\/\/tagit\.hyhuo\.com\/cypt\/block100\/get_vip_info$ url script-response-body https://raw.githubusercontent.com/yqc007/QuantumultX/master/Block100SVIPCrack.js

#鱿鱼视频解锁会员
^https?:\/\/api\.youyu.*\/api\/account\/loginBy(Phone|Password)$ url script-response-body https://raw.githubusercontent.com/yqc007/QuantumultX/master/YYSPCrack.js

#糖心VLog网页版解锁会员
^https?:\/\/txv04\.com\/h5\/user\/findQrcode$ url script-response-body https://raw.githubusercontent.com/yqc007/QuantumultX/master/TXVWCrack.js

#解锁keep会员视频
^https://(.+).gotokeep.com(/athena/v5/people/my|/nuocha/plans) url script-response-body https://raw.githubusercontent.com/nameking77/Qx/main/rewrite/keep

#PlaneVPN解锁订阅
^https?:\/\/buy\.itunes\.apple\.com\/verifyReceipt$ url script-response-body https://raw.githubusercontent.com/yqc007/QuantumultX/master/PlaneVPNProCrack.js

#蜜桃视频解锁无限次数
\/t\w{4}\/\d\/t\/ url 307 /token/5d10208372cbd649de04b9731c1b55db/t/
^https?:\/\/.*mt.*\.com\/api\/Video\/m3u8\/id.+ url script-request-header https://raw.githubusercontent.com/yqc007/QuantumultX/master/MTSPCrack.js

#健康视频解锁会员
^https?:\/\/apiw\.9waquan\.com\/sw2\/.+ url script-request-header https://raw.githubusercontent.com/yqc007/QuantumultX/master/JKSPCrack.js

#雏鸟短视频解锁会员
^https?:\/\/.+\.chuniao\..+\/app\/api\/user\/info$ url script-response-body https://raw.githubusercontent.com/yqc007/QuantumultX/master/CNSPCrack.js
^https?:\/\/.+\.chuniao\..+\/app\/api\/video\/info$ url request-header (\r\n)X-TOKEN:.+(\r\n) request-header $1X-TOKEN: xOIby5DWr2tCf/OxKvnSZoHnD36X8YyzazHwXpj8r+Vqkqa30wWe5PIarCBfLcUuYQfrSQKrtwdb7Un7dQesn3opn4Dw39HpJtFipm7B7Np0SCBYKelhyBMOy9ZKbIhpWA22y6C9NxEQOk9JVEgPj+NsSTs6jq8akUhr8HshbjHde4aL62R6FsHdGVpTdNR/2MMATg+o6K2tqWGUEW7dX0GIpe09mb8oW3qBAsYOB8qZvj28Ecilb9D60QY0aEN/X/1AlsrpeFNdn6Kxi+ZdAvIFwEXvB8f+jr01ueiyjz1yOTgMVrnhdI+s4pEAmVmtej8ckZPmEYdrfkeaONj+3ua/M1rOBqh/UqN+44uIq/xpSH7xYSC69ZuE5lRB45/YXXKsDOkbhBE38GbL4iyOve44mvsnSFejoLGJoi2+4u8tOn+6S79ZOKjf4J5Yc9e29wbm+PojVBPmORdU/XW5nRfQcHdtgM8uoQvGkSW/dskaP/LaP8lOYGYhZCr7Yt6SoPpAhwrh5rl1Jc7F+3aTvASrHLXnqz5JNlWsnsY5/UsH83sltAOXRGShDHmqHprH9Ag9Rw4zSZdjOswtI/XqVOXmm6Ya3CTJ12C2MzLjy0j/cSkfPsLg4eypUahQzc7gPtcTyteiU+AEv8fTmm79uqRAe90j6/JMU7Co1jtOpGc=$2
^https?:\/\/.+\.chuniao\..+\/app\/api\/(sendmsg|user\/bindphone) url reject-200

#91视频解锁会员
^https?:\/\/ap\w{1,4}\.(weilaixushi|orientlion|qdjdswkj|0954auto|xmblgg)\.com\/m_user\/info url script-response-body https://raw.githubusercontent.com/yqc007/QuantumultX/master/91SPCrack.js
^https?:\/\/.*\/m_sns\/(film|video|short_video)\/(film_detail|detail_list|apply_play) url request-header (\r\n)X-AUTH-TOKEN:.+(\r\n) request-header $1X-AUTH-TOKEN: eyJhbGciOiJIUzUxMiIsImlhdCI6MTY1ODU4NzYxMSwiZXhwIjoxNjc0MTM5NjExfQ.eyJpZCI6OTg1MTU4MDV9.fA63_1SLzMNKvknO3Mcz2K-swMbrEe4rBW7HtlpH0hFcexF_5zXs6B9quX0LMJTKJyR5y2zBkHskOEjhr-ME6Q$2
^https?:\/\/.*\/(common\/splash_config|m_user\/(check_phone|behavior_verification_code)) url reject-200

#TIDAL解锁HiFi Plus
^https?:\/\/api\.tidal\.com\/v1\/users\/\d+\/subscription.+ url script-response-body https://raw.githubusercontent.com/yqc007/QuantumultX/master/TIDALHiFiPlusCrack.js
^https?:\/\/api\.tidal\.com\/v1\/tracks/\d+\/playbackinfopostpaywall.+ url script-analyze-echo-response https://raw.githubusercontent.com/yqc007/QuantumultX/master/TidalHiFiPlusCrack.js

#喜马拉雅
^http[s]?:\/\/((.+ximalaya.+)|(.+xmcdn.+)) url script-request-header https://raw.githubusercontent.com/nameking77/Qx/main/rewrite/xmly.js

#JavDB解锁会员
^https?:\/\/.+\/api\/v1\/(movies\/.*\/play|startup) url script-request-header https://raw.githubusercontent.com/yqc007/QuantumultX/master/JavDBCrack.js

#色界视频解锁会员
^https?:\/\/sjapp\.o3aqqc\.work\/user\/(info|fansAndUpAndAttentionCnt)$ url script-response-body https://raw.githubusercontent.com/yqc007/QuantumultX/master/SJSPCrack.js
^https?:\/\/sjapp\.o3aqqc\.work\/mov\/browse url request-header (\r\n)Authorization:.+(\r\n) request-header $1Authorization: 0547064bb9a5557d332023ab513a2e3784e38dc54f844f53cbb804d3a687c48b6c2e670c6aba3e564f$2
^https?:\/\/sjapp\.o3aqqc\.work\/(home\/message\/get|user\/getUserActivity|activityDialog\/getActivityDialogList|banner\/list2\?location=0|game\/programGameList) url reject-200

#解锁一木记账会员
^https?:\/\/yimuapp\.com(:8082)?\/bookkeeping\/user\/getUser\/ url script-response-body https://raw.githubusercontent.com/I-am-R-E/QuantumultX/main/JavaScript/YiMuJiZhang.js

#InShot解锁订阅
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://raw.githubusercontent.com/I-am-R-E/QuantumultX/main/JavaScript/InShot.js

#马卡龙玩图
^https?:\/\/app\.api\.versa-ai\.com\/pay\/order\/iap\/check url script-response-body https://raw.githubusercontent.com/I-am-R-E/QuantumultX/main/JavaScript/MaKaLongWanTu.js

#克拉壁纸解锁订阅
^https?:\/\/buy\.itunes\.apple\.com\/verifyReceipt$ url script-response-body https://raw.githubusercontent.com/yqc007/QuantumultX/master/ClarityPaperProCrack.js

#香蕉视频解锁无限次数
^https?:\/\/.+\/(index|ucp\/index|vod\/(show|reqplay\/)|getGlobalData).+ url script-response-body https://raw.githubusercontent.com/yqc007/QuantumultX/master/BananaVideoCrack.js

#欲漫涩解锁会员漫画&视频
^https?:\/\/.*\.com\/api\/app\/user\/info$ url script-response-body https://raw.githubusercontent.com/yqc007/QuantumultX/master/PornComicsCrack.js
^https?:\/\/.*\.com\/api\/app\/media url script-request-header https://raw.githubusercontent.com/yqc007/QuantumultX/master/PornVideosCrack.js

#Grammarly解锁订阅
^https?:\/\/subscription\.grammarly\.com\/api\/v1\/subscription$ url script-response-body https://raw.githubusercontent.com/yqc007/QuantumultX/master/GrammarlyPremiumCrack.js

#涩蕉视频解锁会员
^https?:\/\/sjapi\.juqianpu\.com\/api\/(video|app\/play_page) url script-request-body https://raw.githubusercontent.com/yqc007/QuantumultX/master/PainedBashoCrack.js
^https?:\/\/sjapi\.juqianpu\.com\/api\/member\/info$ url response-body .+ response-body XUxzDgEDZV15WQ4RL3V6RFYKV1F5UC9GBUx+EnAMMFBccnwNLF9EWFFrMwoBZXkGUEF+CVduNFkrX3oWdAsFT3VxfB0uSEBYaWQNDSpcX0p5e35PV240WStfehZ0NQlCdl9wEy5yQFhTdAkQAVtlWXpRfQp4Qw4FKU9cVHclOwl2THAXKlwCQWkBEg8sX3p5bGBiQmx9J0k+WG4IdSIoCllteA0sW1xCeV07FgBwCVxQcHZIVVQwWStfehh3JQkJdnFaVi5lZgR8cCsMAQRcRXxSWw15bQ4FK2FcEnAPME5ccn8XOwJ1WVVgKFAudUdZUX8NSmxuUVkrXH0MYDUrDHVPdwwtW3lYf3cvDi5MfQV7bG0Je1MjWj1PUFB0CytAdlh/CTpifkJ5XSMOBmAJR2xgekJSC1xJPnMODFsmJFZxX1YQLmJAWFFrLwA5BWZcVgtlUXlTJEMtWFsbYVMkUlxyVVY5Yn4HfWAWDwcEdgBsClxeUn4JRD5mfld0IhVRWwdREgBfZVdUASdWOgRYVlF/WExsaiwGKXZACFpSMFBcfW8eKltYSXxwKxE6blxWbG9MS39TClkpdgMWdCIrS3Fbcwg5AmVBUmQ0DyxcdQJ7bFcKe20GSStxbhJwDyRPYAZvFDlyfgd9cBYPAG5yVmwKDUhUUCwGLV9cVHY1CQ13Zg0TKlhAWFNrIwABYQlFb2BfUXlQLAUrYVxUdjUJTXV2cBcqX1NeamQ3FTsEaklvb2JeVFczRC1fWBl1IihTYm1jFDlyfgd5WSRULWJTAnhsV0F5fSRIKl9uUnc1Jwh1X3wNBWkGCA==

#悦色视频解锁会员
^https?:\/\/ys\.huajibh\.com\/api\/video url script-request-header https://raw.githubusercontent.com/yqc007/QuantumultX/master/PleasantVideoCrack.js

#蝴蝶传媒解锁会员
^https?:\/\/api\..+\.cn\/api\/video\/play url script-request-header https://raw.githubusercontent.com/yqc007/QuantumultX/master/ButterflyMediaCrack.js
^https?:\/\/api\..+\.cn\/api\/user\/counter\/$ url response-body .+ response-body bIEgwLM52F1dpQMqi/ViqoPQ/5DT5dSBL84CoJNnbMB3lBbylhz8EOi3ci0TwntHsMqycd2CiiqIre9ROCIv6wi8sWOoFcVaJq01deboiA2I8/OW+qaubZoiKbke04VOL5Vdr5XkRNQl0fLp2V2bCXajz+D6K0UAtDV8uvQXMa5MWkiYAQyfKBOrRPb5pe5reEvA2uGw5KY45VrRVB94IV8bQwrK7osGSDD7g9i3Z6zVGGxXGDtkyIjxjQAnwaPhFzGg3NV3VXzqscjmS/ZEevb+IoK5w0yFHVI/E5DQfRvyfMY75aI7LXy4DbVSHIqO+M9Z8hekdyzbQxOrxsFG8OA/J9VxZ8pMToALEOYTJiBB2CCl5Ko7c1hi6gTQhxsIZjQFlW9G+h+Qz1qs7SVzeg==
^https?:\/\/api\..+\.cn\/user\/profile$ url request-body .+ request-body bIEgwLM52F1dpQMqi/ViqoPQ/5DT5dSBL84CoJNnbMB3lBbylhz8EOi3ci0TwntHJaI2mJm5x4HCXIISOLDXPQi8sWOoFcVaJq01deboiA2I8/OW+qaubZoiKbke04VOgifMpuwtSHu7HVB+9RP2tIQA6UWKyvahbwKFvkD7X31Pn7lNw4ORVMf20XnNIzIDUVntigOg8XISbJjk8BwQxHFjYS4T9ZYE54B7o1HMr20P6z7pYbHFKgVriXTwOWUGVie3tUSlSXGLSpadG5VCLkcOkGyUrDg3q8PJ/7X4HpriW1Vi1NBrgmzIyJEq9Sx8FCm2EXoR81FQ6tT1lSke9yTg45gR7SiS6XKbjjN0bYSlrqg63hOX7iRIDNReVM1WXBLDdbTrYkrbFHjUsT122g==
^https?:\/\/api\..+\.cn\/ap(i|iv2)\/(ad\/click|notices|advert|game|subcategories\/list) url reject-200

#Deezer解锁Hi-Fi订阅
^https?:\/\/media\.deezer\.com\/v1\/get_url$ url script-request-body https://raw.githubusercontent.com/yqc007/QuantumultX/master/DeezerHiFiProCrack.js

#多邻国解锁Plus
^https?:\/\/ios-api-2\.duolingo\.cn\/2017-06-30\/login$ url script-request-body https://raw.githubusercontent.com/yqc007/QuantumultX/master/DuolingoPlusCrack.js

#Lvv2Porn
^https?:\/\/lvv2\.com\/tag\/porn url script-response-body https://raw.githubusercontent.com/I-am-R-E/QuantumultX/main/JavaScript/Lvv2Porn.js

#抖窥短视频解锁永久会员
^https?:\/\/ts1i\.dk\.y8848\.xyz\/app\/api\/user\/info$ url script-response-body https://raw.githubusercontent.com/yqc007/QuantumultX/master/DKSPCrack.js
^https?:\/\/ts1i\.dk\.y8848\.xyz\/app\/api\/(sms\/send|user\/bindphone) url reject-200

#Prisma解锁订阅
^https:\/\/api\.neuralprisma\.com\/receipt\/ios\/status\/prisma\/.+ url script-response-body https://raw.githubusercontent.com/LiangYi520/QuantumultX-Script/main/Prisma.js

#PornHub Unlock Premium
^https?:\/\/cn\.pornhubpremium\.com\/ url script-request-header https://raw.githubusercontent.com/yqc007/QuantumultX/master/PornHubPremiumCrack.js

#WallCraft解锁永久专业版
^https?:\/\/billing-ios\.wallpaperscraft\.com\/verify_receipt\/remove_ads$ url script-response-body https://raw.githubusercontent.com/yqc007/QuantumultX/master/WallCraftFProCrack.js

#唔姆解锁无限制下载
^https:\/\/api3\.umu168\.com\/download\/checker url script-response-body https://gitlab.com/ioshkj/quantumultx/-/raw/main/vipjs/wumu.js
