#!name=APP启动页去广告ultra+
#!desc=APP启动页去广告融合ultra+
#!icon=https://raw.githubusercontent.com/deezertidal/private/main/icons/startingad.png
#!homepage=https://whatshub.top
#!author=Mixed
# 由whatshub.top自动维护 202406042246
https?:\/\/res\.xiaojukeji\.com\/resapi\/activity\/get(Ruled|Preload|PasMultiNotices) url reject-200
https?:\/\/m\.sd\.10086\.cn\/zapi\/app_common\/homeWelcome\/welcome.do url reject-dict
https?:\/\/m\.sd\.10086\.cn\/zapi\/app_common\/homeWelcome\/welcome.do url reject-200
https?:\/\/helper\.2bulu\.com\/(greenPea\/queryTasks|proSpecial\/allData|saveSplashFrequencyStatistics|getPopInfo|getAppEntranceConfig|promote\/list|getSplash|outing\/reqFoundNewList|outing\/reqIndex) url reject-200
https?:\/\/helper\.2bulu\.com\/(greenPea\/queryTasks|proSpecial\/allData|saveSplashFrequencyStatistics|getPopInfo|getAppEntranceConfig|promote\/list|getSplash|outing\/reqFoundNewList|outing\/reqIndex) url reject
https?:\/\/awg\.enmonster\.com\/apa\/(advert\/demand\/home\/poster|index\/advert\/skin) url reject-dict
https?://res\.xiaojukeji\.com\/resapi\/activity\/mget url reject-200
https://zone.guiderank-app.com/guiderank-web/app/ad/listLaunchADByCity.do url reject-200
https://yunmk.feidee.net/cab-market-ws/market/v2/contents url reject-dict
https://yun.feidee.net/cab-vip-ws/terminal/v1/vip-users/show-info url script-response-body https://raw.githubusercontent.com/ddgksf2013/MoYu/master/suishouji.js
https://yun.feidee.net/cab-query-ws/v1/comet/vtable/score-card url reject-dict
https://yun.feidee.net/cab-draw-activity-ws/terminal/v1/draw-record/user-draw-result url reject-dict
https://userapi.feidee.net/v1/profile/basic_info url script-response-body https://raw.githubusercontent.com/ddgksf2013/MoYu/master/suishouji.js
https://top-widgets-api.xiaozujian.com/api/ad/config url reject-200
https://tg.feidee.com/vis-ad-engine-ws/api/show url reject
https://tg.feidee.com/online_ad/api/search.do url reject
https://tagit.hyhuo.com/recover/list url reject-200
https://support.you.163.com/appversync/check.do url reject-200
https://support.you.163.com/appversync/check.do url reject
https://open3.vistastory.com/v3/api/index/loading_ad url reject-200
https://open3.vistastory.com/v3/api.*get_popup url reject-200
https://new-app-api.ylyk.com/v1/user/myinfo/adviser url reject-200
https://new-app-api.ylyk.com/v1/user/myinfo/adviser url reject
https://moneymarket.ssjlicai.com/finance-common-operation-ws/api/actShelve/v1/actShelveShowTipInfo url reject
https://mgesq.api.mgtv.com/v2/user/center/icon url reject-dict
https://mgesq.api.mgtv.com/dsl/index.+ url script-response-body https://raw.githubusercontent.com/Sliverkiss/QuantumultX/main/AdBlock/xmApp/xmApp.js
https://mapi.appvipshop.com/vips-mobile/rest/activity/advertisement/get url reject-200
https://ios.sspai.com/api/v3/recommend/page/get\?ad.*ios_home_modal url reject-200
https://ios.sspai.com/api/v3/recommend/page/get\?ad.*ios_home_modal url reject
https://homefront.qunar.com/front/splash/ad url reject-200
https://guanyu.longfor.com/app-server/api/v1/main/start url reject-200
https://fbchina.flipchina.cn/v2/ad/query/* url reject-200
https://edith.xiaohongshu.com/api/sns/v\d/note/comment/list url response-body red_id response-body fmz200
https://dynamicad.kfc.com.cn/api/app5/homepage/ai/popup url reject-200
https://dl-cu-hz.lechange.cn/oms-online/advertisementPush/* url reject-200
https://community.feidee.com/api/v1/home/top url reject-200
https://ci.xiaohongshu.com/system_config/watermark url reject-img
https://ccsp-egmas.sf-express.com/cx-app-base/base/app/ad/queryInfoFlow url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/shunfeng_json.js
https://ccsp-egmas.sf-express.com/cx-app-base/base/app/ad/queryAdImages url reject-200
https://beta-api.crunchyroll.com/cms url response-body offset_ms":\d+ response-body offset_ms":99999999999999
https://b.appsimg.com/upload/momin/ url reject
https://apis.lifeweek.com.cn/api/baseConfig/getIosNewConfig url reject-200
https://apis.lifeweek.com.cn/api/baseConfig/getIosNewConfig url reject
https://api.rr.tv/watch/v4 url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/rrtv_json.js
https://api.rr.tv/v3plus/index/channel\?pageNum=1&position=CHANNEL_INDEX url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/rrtv_json.js
https://api.rr.tv/user/profile url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/rrtv_json.js
https://api.rr.tv/storage/business/rootName/app/homePage\?dataType=JSON url reject-dict
https://api.juxingclub.com/v3plus/index/channel\?pageNum=1&position=CHANNEL_INDEX url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/rrtv_json.js
https://api.juxingclub.com/storage/business/rootName/app/homePage\?dataType=JSON url reject-dict
https://api.feidee.net/v1/configs/client/configs url reject-200
https://api-global.soulapp.me/app/open/get url reject
https://access.mypikpak.com/access_controller/v1/area_accessible url reject-200
https://access.mypikpak.com/access_controller/v1/area_accessible url reject
http:\/\/ad\.myfriday\.cn\/d\/json\/1\.1 url reject
^https\:\/\/(weixin110\.qq|security\.wechat)\.com\/cgi-bin\/mmspamsupport-bin\/newredirectconfirmcgi\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/wechat/wechat110.js
^https\:\/\/(weixin110\.qq|security.wechat)\.com\/cgi-bin\/mmspamsupport-bin\/newredirectconfirmcgi\? url script-response-body https://raw.githubusercontent.com/zZPiglet/Task/master/asset/UnblockURLinWeChat.js
^https\:\/\/(weixin110\.qq|security.wechat)\.com\/cgi-bin\/mmspamsupport-bin\/newredirectconfirmcgi\? url script-response-body https://raw.githubusercontent.com/ddgksf2013/Scripts/master/weixin110.js
^https?:\/\/zua\.zhidiantianxia\.cn\/api\/adverts url reject
^https?:\/\/ztoread\.ziroom\.com\/ymerApi\/v\d\/index\/open url reject-dict
^https?:\/\/ztoread\.ziroom\.com\/ymerApi\/v\d\/index\/open url reject-200
^https?:\/\/ztoread\.ziroom\.com\/foka-card-api\/popup\/v2\/get url reject-dict
^https?:\/\/zt-app\.go189\.cn\/zt-app\/welcome\/.*?Animation url reject-img
^https?:\/\/zone\.guiderank-app\.com\/guiderank-web\/app\/ad\/listLaunchADByCity\.do url reject
^https?:\/\/zlsdk\.1rtb\.net\/sdk\/req_ad\? url reject-200
^https?:\/\/zlsdk\.1rtb\.net\/sdk\/req_ad url reject-dict
^https?:\/\/zjmbank\.js96008\.com:8090\/gw\/advert\/oprAdvertQry url reject-200
^https?:\/\/zjdr666\.com\/zjdr\.php\/v\d\/(version|top_notice\?|advert\?position=[^2]+) url reject-200
^https?:\/\/zjdr666\.com\/zjdr\.php\/v\d\/(version|top_notice\?|advert\?position=[^2]+) url reject
^https?:\/\/zhuanlan\.zhihu\.com\/api\/articles\/\d+\/recommendation url reject
^https?:\/\/zgrb\.epicc\.com\.cn\/G-HAPP\/mpageconfig\/myPageConfigList\/v3 url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/picc/picc_ads.js
^https?:\/\/zgrb\.epicc\.com\.cn\/G-HAPP\/h\/headlines\/queryHeadlines url reject
^https?:\/\/zgrb\.epicc\.com\.cn\/G-HAPP\/a\/update\/startupPage\/v1 url reject-dict
^https?:\/\/zgrb\.epicc\.com\.cn\/G-HAPP\/a\/config\/homeInit\/v3 url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/picc/picc_ads.js
^https?:\/\/zgrb\.epicc\.com\.cn\/G-HAPP\/a\/config\/guessYouLike\/v3 url reject-dict
^https?:\/\/zconfig\.alibabausercontent\.com\/zconfig url reject-200
^https?:\/\/zconfig\.alibabausercontent\.com\/zconfig url reject
^https?:\/\/z\.onewo\.com\/passer\/api\/ads\/v1\/8\/list url reject-200
^https?:\/\/yunbusiness\.ccb\.com\/clp_service\/txCtrl\?txcode=A3341A00(2|9) url reject-200
^https?:\/\/yunbusiness\.ccb\.com\/clp_service\/txCtrl\?txcode=A3341A00(2|6|9) url reject-200
^https?:\/\/yunbusiness\.ccb\.com\/basic_service\/txCtrl\?txcode=A3341AB05 url echo-response application/json echo-response https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/ccbLife/A3341AB05.json
^https?:\/\/yunbusiness\.ccb\.com\/basic_service\/txCtrl\?txcode=A3341AB04 url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/ccbLife/ccbLifeAds.js
^https?:\/\/yunbusiness\.ccb\.com\/basic_service\/txCtrl\? url response-body "TAG_AD_INFO" response-body "TAG_AD_INFO0"
^https?:\/\/yun\.tuitiger\.com\/mami-media url reject-200
^https?:\/\/ytmsout\.radio\.cn\/publish\/recScreen\/getLoadPage url reject-200
^https?:\/\/yghsh\.cebbank\.com\/static\/picture\/.*.jpg url reject-200
^https?:\/\/yanxuan\.nosdn\.127\.net\/.*\.mp4 url reject-200
^https?:\/\/yanxuan\.nosdn\.127\.net\/.*\.mp4 url reject
^https?:\/\/y\.gtimg\.cn\/music\/common\/upload\/targeted_ads url reject-img
^https?:\/\/y\.gtimg\.cn\/music\/common\/upload\/t_splash_info\/ url reject
^https?:\/\/y\.gtimg\.cn\/music\/common\/\/upload\/kg_ad\/.+?\d{3,4}x\d{4} url reject-200
^https?:\/\/y\.gtimg\.cn\/music\/common\/\/upload\/kg_ad/.*?\d{4}\.jpg url reject-img
^https?:\/\/y\.gtimg\.cn\/music\/.*?_Ad/\d+\.png url reject-img
^https?:\/\/xyz\.cnki\.net\/resourcev7\/api\/manualpush\/SlidsList$ url reject-200
^https?:\/\/xyst\.yuanfudao\.com\/iphone\/splashesV\d url reject-200
^https?:\/\/xxyx-client-api\.xiaoxiaoyouxuan\.com\/agent_ad url reject
^https?:\/\/xxyx-client-api\.xiaoxiaoyouxuan\.com\/activity\/show url reject
^https?:\/\/xqimg\.imedao\.com\/[a-z0-9]{24}\.jpg$ url reject-200
^https?:\/\/xhtz.oss-cn-guangzhou\.aliyuncs\.com\/home\/member\/.+\.png$ url reject-200
^https?:\/\/xapi\.xinmanhua\.net\/splashgroups\?include=splashs url reject-200
^https?:\/\/wxs-weixin\.sd\.zhumanggroup\.com\/api\/v2\/ad url reject-dict
^https?:\/\/wx\.mygolbs\.com\/WxBusServer\/ApiData\.do url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/zhangshanggongjiao.js
^https?:\/\/wx\.mygolbs\.com\/WxBusServer\/ApiData\.do url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/zhangshanggongjiao.js
^https?:\/\/wx\.17u\.cn\/xcxhomeapi\/((aggregator\/index)|(home\/(screen|banner|converge)))$ url reject
^https?:\/\/wx\.17u\.cn\/crapi\/query\/getAdImgUrlByCode url reject-dict
^https?:\/\/www\.zhihu\.com\/commercial_api\/banners_v3\/mobile_banner url reject
^https?:\/\/www\.zhihu\.com\/appview\/v2\/zhmore url reject
^https?:\/\/www\.zhihu\.com\/appview\/v2\/answer\/.*(entry=(?!(preload-topstory|preload-search|preload-subscription)))? url script-response-body https://gist.githubusercontent.com/blackmatrix7/f5f780d0f56b319b6ad9848fd080bb18/raw/zheye.min.js
^https?:\/\/www\.zhihu\.com\/api\/v\d\/articles\/\d+\/recommendation\? url script-response-body https://gist.githubusercontent.com/blackmatrix7/f5f780d0f56b319b6ad9848fd080bb18/raw/zheye.min.js
^https?:\/\/www\.zhihu\.com\/api\/v\d\/answers\/\d+\/recommendations url reject-dict
^https?:\/\/www\.zhihu\.com\/api\/v\d+\/search\/related_queries\/answer url reject-dict
^https?:\/\/www\.zhihu\.com\/api\/v\d+\/brand\/question/\d+/card\? url reject-dict
^https?:\/\/www\.zhihu\.com\/api\/v4\/search\/related_queries\/(answer|article)\/\d+ url reject-dict
^https?:\/\/www\.zhihu\.com\/api\/v4\/mcn\/v2\/linkcards\? url reject
^https?:\/\/www\.zhihu\.com\/api\/v4\/hot_recommendation url reject
^https?:\/\/www\.zhihu\.com\/api\/v4\/comment_v5\/answers\/\d+\/abstract_comment\? url script-response-body https://gist.githubusercontent.com/blackmatrix7/f5f780d0f56b319b6ad9848fd080bb18/raw/zheye.min.js
^https?:\/\/www\.zhihu\.com\/api\/v4\/(answers|articles)\/\d+\/recommendations? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/zhihu.js
^https?:\/\/www\.zhihu\.com\/api\/v4/(questions|anwsers)\/\d+/related-readings url reject
^https?:\/\/www\.xiaoxiongmeishu\.com\/api\/home\/v1\/config\/appInit\?uid=588888763519696896 url reject-dict
^https?:\/\/www\.xiaohongshu\.com\/api\/sns\/v\d\/(tag\/)?ads url reject-dict
^https?:\/\/www\.xiaohongshu\.com\/api\/sns\/(v\d\/ads\/resource|v2\/hey\/\w+\/hey_gallery) url reject-dict
^https?:\/\/www\.xiaohongshu\.com\/api\/marketing\/box\/trigger\? url reject-dict
^https?:\/\/www\.tsytv\.com\.cn\/api\/app\/ios\/ads url reject-img
^https?:\/\/www\.pushplus\.plus.* url response-body (<head>) response-body $1<style type="text/css">  div.container.py-3.text-center {display: none! important} </style />
^https?:\/\/www\.pansearch\.me\/api\/adsite url reject-dict
^https?:\/\/www\.oschina\.net\/action\/apiv2\/get_launcher url reject-img
^https?:\/\/www\.onstar\.com\.cn\/mssos\/sos\/social\/v1\/community\/article\/page url reject-dict
^https?:\/\/www\.nfmovies\.com\/uploads\/images\/play\.jpg url reject-img
^https?:\/\/www\.nfmovies\.com\/templets\/default\/images\/logos url reject-img
^https?:\/\/www\.nfmovies\.com\/pic\/tu\/ url reject-img
^https?:\/\/www\.meituan\.com\/api\/v\d\/appstatus\? url reject
^https?:\/\/www\.kujiale\.com\/app\/queryOpenPage url reject-200
^https?:\/\/www\.iyingdi\.cn\/ad url reject-200
^https?:\/\/www\.icourse163\.org\/mob\/j\/v1\/mobRecommendRPCBean\.getMaxWeightAdvertisement\.rpc url reject-200
^https?:\/\/www\.i3zh\.com url response-body cm-pop-up-banners response-body random_body
^https?:\/\/www\.gcores\.com\/gapi\/v1\/app-start-pages\?page url reject-dict
^https?:\/\/www\.flyert\.com\/source\/plugin\/mobile\/mobile\.php\?module=threadpost&.+?&page=1 url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/fly.js
^https?:\/\/www\.flyert\.com\/source\/plugin\/mobile\/mobile\.php\?module=advis url reject-200
^https?:\/\/www\.flyert\.com\/api\/mobile\/index\.php\?version=\d&mobile=yes&module=basicdata&type=forumlist url response-body adv response-body ddgksf2013
^https?:\/\/www\.flyert\.com\/.*plugin url script-response-body https://raw.githubusercontent.com/zirawell/Ad-Cleaner/main/Collection/js/flyert.js
^https?:\/\/www\.flyert\.com\/.*\.php\?module=advis url reject-dict
^https?:\/\/www\.didapinche\.com\/app\/adstat\/ url reject-200
^https?:\/\/www\.cntv\.cn\/nettv\/adp\/ url reject-200
^https?:\/\/www\.cmbc\.com\.cn\/m\/image\/loadingpage\/ url reject-200
^https?:\/\/www\.cmbc\.com\.cn\/m\/image\/banner\/.*.png url reject-200
^https?:\/\/www\.banyuetanapp\.com\/byt-api\/ad\/getAdvertList\?adSpaceId=100000002 url reject-200
^https?:\/\/www\.ahzs10000\.com\/palmhall\/client\/base\/newVerson_getStartUp\.action url reject-200
^https?:\/\/www\.1314zhilv\.com\/ltsstnew\/(guideScenic\/getRecentlyUpdatedScenic|city\/getWeatherByCityName) url reject-dict
^https?:\/\/www\.1314zhilv\.com\/ltsstnew\/(common\/getJGQIconNew|city\/getAllBannelByCity) url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/lvtusuishenting/ltsst-ad.js
^https?:\/\/www\.(binance|yingwangtech)\.(com|info|net)\/bapi\/composite\/v1\/public\/market\/holiday-atmosphere url reject-dict
^https?:\/\/www1\.elecfans\.com\/www\/delivery\/ url reject
^https?:\/\/www1.elecfans.com\/www\/delivery\/ url reject-200
^https?:\/\/www.icourse163.org\/.*?(Advertisement) url reject-img
^https?:\/\/www.baidu.com\/?action=static&ms=1&version=css_page_2@0.*? url reject
^https?:\/\/wrapper\.cyapi\.cn\/v1\/activity\? url echo-response application/json echo-response https://raw.githubusercontent.com/Keywos/rule/main/mocks/caiyun.json
^https?:\/\/wmapi\.meituan\.com\/api\/v\d\/startpicture url reject
^https?:\/\/wmapi\.meituan\.com\/api\/v\d+\/loadInfo\? url reject
^https?:\/\/wmapi\.meituan\.com\/api\/v7\/(loadInfo|openscreen|startpicture)\? url reject-dict
^https?:\/\/weibointl\.api\.weibo\.cn\/portal\.php\?a=user_center url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/weibo_json.js
^https?:\/\/weibointl\.api\.weibo\.cn\/portal\.php\?a=search_topic url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/weibo_json.js
^https?:\/\/weibointl\.api\.weibo\.cn\/portal\.php\?a=open_app url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/weibo_json.js
^https?:\/\/weibointl\.api\.weibo\.c(n|om)\/portal\.php\?a=hot_search_users url reject-dict
^https?:\/\/weibointl\.api\.weibo\.c(n|om)\/portal\.php.*user&a=get_searching_info url echo-response text/html echo-response https://github.com/ddgksf2013/Scripts/raw/master/weibo_search_info.json
^https?:\/\/weibointl\.api\.weibo\.c(n|om)\/portal\.php.*get_coopen_ads url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/weibo_json.js
^https?:\/\/weibointl\.api\.weibo\.c(n|om)\/portal\.php.*feed&a=trends url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/weibo_json.js
^https?:\/\/weibointl\.api\.weibo\.c(n|om)\/portal\.php.*feed&a=search_topic url echo-response text/html echo-response https://github.com/ddgksf2013/Scripts/raw/master/weibo_search_topic.json
^https?:\/\/wechat\.tf\.cn\/mini-financial\/model\/queryPopup url reject-dict
^https?:\/\/webcdn\.m\.qq\.com\/qiantu\/upload\/202[0-9]{5}\/.*.(jpg|png) url reject-200
^https?:\/\/webboot\.zhangyue\.com\/zycl\/api\/ad\/ url reject
^https?:\/\/webappcfg\.paas\.cmbchina\.com\/v\d\/func\/getmarketconfig url reject-200
^https?:\/\/web\.chelaile\.net\.cn\/api\/adpub\/ad url reject-200
^https?:\/\/web\.chelaile\.net\.cn\/api\/adpub\/ad url reject
^https?:\/\/wcprd\.hilton\.com\.cn\/app-middleware\/graphql\?type=splashAd url reject-200
^https?:\/\/wap\.spdb\.com\.cn\/mspmk-web-homeassist\/OpenScreenAdv\.ah$ url reject
^https?:\/\/wap\.ngchina\.cn\/news\/adverts\/ url reject-200
^https?:\/\/wap\.ngchina\.cn\/news\/adverts url reject-200
^https?:\/\/wap\.js\.10086\.cn\/jsmccClient\/cd\/market_content\/api\/v\d\/market_content\.page\.query url reject-200
^https?:\/\/wap\.js\.10086\.cn\/jsmccClient\/cd\/market_content\/api\/v\d\/market_content\.page\.query url reject
^https?:\/\/wap\.js\.10086\.cn\/jsmccClient\/cd\/market_content\/api\/v1\/market_content\.page\.queryHasIt url reject-dict
^https?:\/\/wap.bank\.ecitic\.com:6443\/NMBFOServer\/cbframework\.do\?act=CUBEPAGEDATA url reject-200
^https?:\/\/wanciwangdata\.oss-cn-beijing\.aliyuncs\.com\/startup\/resource\/content.+ url reject
^https?:\/\/wallpaper\.soutushenqi\.com\/v\d\/home\/dialog url reject-200
^https?:\/\/wallpaper\.soutushenqi\.com\/v\d\/dateSignature\/random url reject-200
^https?:\/\/wallet\.lakala\.com\/m\/lama\/mgt\/activity\/bank\/query\/list url reject-dict
^https?:\/\/wallet\.lakala\.com\/m\/a\/message\/v\d\/fetchMsgList url reject-dict
^https?:\/\/wallet\.lakala\.com\/m\/a\/lama\/mgt\/activity\/biz\/query\/byMerInfo url reject-dict
^https?:\/\/vv\.video\.qq\.com\/getvmind\? url reject-200
^https?:\/\/vv\.video\.qq\.com\/getvinfo url request-body &sppreviewtype=\d(.*)&spsrt=\d request-body &sppreviewtype=0$1&spsrt=0
^https?:\/\/vv\.video\.qq\.com\/(diff|get)vmind url reject-dict
^https?:\/\/vip7\.fzwdyy\.cn:8083\/api\/(getAdvertInfo|getGOOGAdvert) url reject-200
^https?:\/\/vip1\.kuwo\.cn\/vip\/v\d\/user\/vip\?op=ui url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/break/kuwo.js
^https?:\/\/vip1\.kuwo\.cn\/vip\/(enc\/user\/vip\?op=ui|v\d\/theme\?op=gd) url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/break/kuwo.js
^https?:\/\/vidz\.3hxq\.cn\/api\/app\/(miscs\/mine\/extensions|announcements\/home) url reject-dict
^https?:\/\/venus\.yhd\.com\/memhome\/launchConfig url reject-200
^https?:\/\/venus\.yhd\.com\/memhome\/launchConfig url reject
^https?:\/\/vapp\.tmuyun\.com\/api\/app_start_page\/list\/new url reject-dict
^https?:\/\/v\.icbc\.com\.cn\/userfiles\/Resources\/WAP\/advertisement\/ url reject-200
^https?:\/\/v3\.wufazhuce\.com:8000\/api\/adpreloadlist url reject-dict
^https?:\/\/ut2\.shuqistat\.com\/.+\.gif url reject
^https?:\/\/user-api\.smzdm\.com\/vip\/creator_user_center url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/smzdm/smzdm_ads.js
^https?:\/\/user-api\.smzdm\.com\/vip\/bottom_card_list url script-response-body https://raw.githubusercontent.com/ZenmoFeiShi/Qx/main/Smzdm.js
^https?:\/\/user-api\.smzdm\.com\/vip url script-response-body https://raw.githubusercontent.com/ZenmoFeiShi/Qx/main/Smzdm.js
^https?:\/\/us\.l\.qq\.com\/exapp\?spsa=\d url reject
^https?:\/\/us\.l\.qq\.com\/exapp url reject-200
^https?:\/\/us\.l\.qq\.com\/exapp url reject
^https?:\/\/upos-sz-static\.bilivideo\.com\/ssaxcode\/\w{2}\/\w{2}\/\w{32}-1-SPLASH url reject-dict
^https?:\/\/upload-bbs\.mihoyo\.com\/upload\/202[2-9]{1}\/[0-9]{2}\/[0-9]{2}\/[a-z0-9]{32}_[a-z0-9]{19}\.(jpg|png)$ url reject-200
^https?:\/\/update\.pan\.baidu\.com\/statistics url reject
^https?:\/\/un-acs\.youku\.com\/gw\/mtop\.youku\.play\.ups\.appinfo\.get url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/ump\.sz\.creditcard\.ecitic\.com\/citiccard\/cm-ump\/ump-gateway\/ump-net-app\/ump-net-app\/adv url reject-dict
^https?:\/\/ump\.sz\.creditcard\.ecitic\.com\/citiccard\/cm-ump\/ump-gateway\/ump-net-app\/ump-net-app\/adv url reject-200
^https?:\/\/ucmp\.sf-express\.com\/proxy\/operation-platform\/info-flow-adver\/query$ url reject-200
^https?:\/\/ucmp\.sf-express\.com\/proxy\/operation-platform\/info-flow-adver\/query url reject-dict
^https?:\/\/ucmp\.sf-express\.com\/proxy\/esgcempcore\/memberManage\/memberEquity\/queryRecommendEquity url reject-dict
^https?:\/\/ucmp\.sf-express\.com\/proxy\/esgcempcore\/memberGoods\/pointMallService\/goodsList url reject-dict
^https?:\/\/ucmp\.sf-express\.com\/proxy\/esgcempcore\/memberActLengthy\/fullGiveActivityService\/fullGiveInfo url reject-dict
^https?:\/\/ucmp-static\.sf-express\.com\/proxy\/wxbase\/wxTicket\/wxLiveStreamInfo\?pageNo url reject-dict
^https?:\/\/track\.mm\.taou\.com/v\d\/track url reject-200
^https?:\/\/track\.mm\.taou\.com/v\d\/track url reject
^https?:\/\/tower\.ubixioe\.com\/mob\/mediation url reject
^https?:\/\/top-widgets-api\.xiaozujian\.com\/api\/ad\/config url reject
^https?:\/\/toblog\.ctobsnssdk\.com url reject-200
^https?:\/\/tk\.lanjiyin\.com\.cn\/ad\/getAdList url reject-200
^https?:\/\/tk\.lanjiyin\.com\.cn\/ad\/getAdList url reject
^https?:\/\/tiku\.fenbi\.com\/activity\/app\/launcher\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/fenbi.js
^https?:\/\/thor\.weidian\.com\/ares\/home\.splash url reject-200
^https?:\/\/tft-app\.cdtft\.cn\/gateway-customer\/tftapp\/tft-ams\/api\/appAd url response-body officialAdvertResultVo response-body random-response
^https?:\/\/tft-app\.cdtft\.cn\/gateway-customer\/tftapp\/tft-ams\/api\/appAd url response-body officialAdvertResultVo response-body ddgksf2013
^https?:\/\/tfsmy\.chengdu\.gov\.cn\/api\/v5\/core\/version url reject-200
^https?:\/\/testflight\.apple\.com\/v2\/accounts\/.*\/apps\/\d*/builds/\d*/install url request-body storefrontId" : ".*" request-body storefrontId" : "143441-1,29"
^https?:\/\/td\.cgmcare\.cn\/api\/ad url reject-200
^https?:\/\/tcmobileapi\.17usoft\.com\/appindexnew\/index\/getappindexconfig url reject-200
^https?:\/\/tbgapplet\.carlsberg\.asia\/tuborg\/banner\/(loading|index) url reject-dict
^https?:\/\/tb2\.bdstatic\.com\/tb\/mobile\/spb\/widget\/jump url reject-img
^https?:\/\/tb1\.bdstatic\.com\/tb\/cms\/ngmis\/adsense\/*.jpg url reject
^https?:\/\/tagit\.hyhuo\.com\/recover\/list url reject
^https?:\/\/t\d{2}\.baidu\.com url reject-img
^https?:\/\/t1\.market\.xiaomi\.com\/thumbnail\/webp\/w1170q100\/ url reject-200
^https?:\/\/t1\.market\.xiaomi\.com\/thumbnail\/webp\/w1170q100\/ url reject
^https?:\/\/t-dsp\.pinduoduo\.com url reject-200
^https?:\/\/szdmobile\.suzhou\.gov\.cn\/thirdapp-center\/appUpdate\/update url reject-dict
^https?:\/\/syh\.zybang\.com\/com\/adx\/impress url reject-200
^https?:\/\/syh\.zybang\.com\/com\/adx\/ url reject-200
^https?:\/\/switch\.jumpvg\.com\/jump\/(getlaunchad|recommend\/ad_conf) url reject-200
^https?:\/\/supportda\.ofo\.com\/adaction\? url reject
^https?:\/\/support\.you\.163\.com\/xhr\/boot\/getBootMedia\.json url reject-200
^https?:\/\/support\.you\.163\.com\/xhr\/boot\/getBootMedia\.json url reject
^https?:\/\/superapp\.xgimi\.com\/api/v1\/app\/ad\/configs\?_sort=createdAt:Adesc url reject-200
^https?:\/\/staticsns\.cdn\.bcebos\.com\/amis\/.+/banner.png url reject
^https?:\/\/staticlive\.douyucdn\.cn\/upload\/signs\/ url reject
^https?:\/\/staticlive\.douyucdn\.cn\/.+\/getStartSend url reject
^https?:\/\/staticlive\.douyucdn\.cn\/.+?\/getStartSend url reject-img
^https?:\/\/static\.shihuocdn\.cn\/admin\/imgs/202[0-9]{5}\/[a-z0-9]{32}_750x1624\.png url reject-200
^https?:\/\/static\.shihuocdn\.cn\/admin\/imgs/202[0-9]{5}\/[a-z0-9]{32}_513x777\.png url reject-200
^https?:\/\/static\.mobile-bank\.psbc\.com\/mgs url reject
^https?:\/\/static\.gameplus\.qq\.com\/img\/\d{10}-\d{4}$ url reject
^https?:\/\/static\.creditcard\.hxb\.com\.cn\/mcube\/apps\/group\d\/M00\/00\/2[A-Z0-9]{1}\/amRG7WO.+\.jpg url reject-200
^https?:\/\/static\.api\.m\.panda\.tv\/index\.php\?method=clientconf\.firstscreen&__version=(play_cnmb|(\d+\.){0,3}\d+)&__plat=ios&__channel=appstore url reject-img
^https?:\/\/static\.95508\.com\/mmg\/images\/ads\/.+\/(.+1125?.+2436|.+%.+%|.+_.+_) url reject-dict
^https?:\/\/static\.95508\.com\/mmg\/ciop\/sysabbr\/cmep\/images\/apppopupads url reject-dict
^https?:\/\/static\.95508\.com\/icppweb\/images\/modelMaterial\/advertising\/202\d{5}\/.*.(png|jpg) url reject-200
^https?:\/\/static\.95508\.com\/icppweb\/images\/modelMaterial\/accurate\/202\d{5}\/.*.(png|jpg) url reject-200
^https?:\/\/static1\.keepcdn\.com\/ark_optimus\/202\d\/*\/*\/.*.(png|jpg) url reject-200
^https?:\/\/static01\.versa-ai\.com\/upload\/ec0ba51d68f9\/.*.jpg url reject-200
^https?:\/\/static.xyzq.cn\/image\/splash\/opera3.*.jpg url reject-200
^https?:\/\/static.psbc.com:8090\/mbank_f\/images\/[0-9]+\.png url reject-200
^https?:\/\/stat\.peopleapp\.com\/ url reject-200
^https?:\/\/stat\.peopleapp\.com\/ url reject
^https?:\/\/stat\.10jqka\.com\.cn\/q\?ld=mobile&id=ad url reject-dict
^https?:\/\/ssp\.soulapp\.cn\/api\/q url reject-dict
^https?:\/\/ssp\.soulapp\.cn\/api\/ad\/config url reject-dict
^https?:\/\/sso\.ifanr\.com\/jiong\/IOS\/appso\/splash\/ url reject
^https?:\/\/sso.ifanr.com\/jiong\/IOS\/appso\/splash\/ url reject-200
^https?:\/\/ssl\.kohsocialapp\.qq\.com:\d+\/game\/buttons url reject
^https?:\/\/ssl\.kohsocialapp\.qq\.com:10001\/game\/buttons url reject-200
^https?:\/\/ss0\.bdstatic\.com/.+?_\d{3}_\d{4}\.jpg url reject-200
^https?:\/\/sq\.sljkj\.com\/api\/sdk\/ads2 url reject
^https?:\/\/sports3\.gtimg\.com\/community\/20cf93884470434eaf38b2e77ab7796a\.png url reject
^https?:\/\/splashqqlive\.gtimg\.com\/website\/\d{6} url reject-img
^https?:\/\/spclient\.wg\.spotify\.com\/(ad-logic|ads|.+ad_slot|.+banners|.+canvases|.+cards|.+crashlytics|.+doubleclick.net|.+enabled-tracks|.+event|.+sponsored|.+promoted|.+promoted_offer) url reject-img
^https?:\/\/sp\.kaola\.com\/api\/openad url reject-200
^https?:\/\/social\.blued\.cn\/users\/recommend url reject-dict
^https?:\/\/social\.blued\.cn\/users\/no_auth\/benefit url reject-dict
^https?:\/\/social\.blued\.cn\/users\/.+\/more\/ios\?v=2 url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/blued.js
^https?:\/\/snailsleep\.net\/snail\/v\d\/screen\/qn\/get\? url reject
^https?:\/\/snailsleep\.net\/snail\/v\d\/adTask\/ url reject
^https?:\/\/smkmp\.96225\.com\/smkcenter\/ad/ url reject
^https?:\/\/smart\.789\.image\.mucang\.cn\/advert url reject-img
^https?:\/\/smarket\.dian\.so url reject-dict
^https?:\/\/slapi\.oray\.net\/client\/ad url reject-200
^https?:\/\/slapi\.oray\.net\/client\/ad url reject
^https?:\/\/slapi\.oray\.net\/adver url reject-200
^https?:\/\/slapi\.oray\.net\/adver url reject
^https?:\/\/sichuan\.95504\.net\/v\d\/gd\/index\/get url reject-200
^https?:\/\/shopic\.sf-express\.com\/crm\/mobile\/common\/flashscreen url reject-200
^https?:\/\/shopapi\.io\.mi\.com\/mtop\/mf\/resource\/homePage\/pageConfig url reject-200
^https?:\/\/shop-api\.retail\.mi\.com\/mtop\/navi\/skywheel\/mishop\/splash url reject-200
^https?:\/\/shcss\.suning\.com\/shcss-web\/api\/appImage\/queryAppImage\.do url reject-200
^https?:\/\/sh-gateway\.shihuo\.cn\/v\d\/services\/sh-adapi\/home\/screen url response-body egin_time":"\d{4} response-body egin_time":"2099
^https?:\/\/sh-gateway\.shihuo\.cn\/v\d\/services\/sh-adapi\/home\/(screen|ad) url reject
^https?:\/\/sfo\.mddcloud\.com\.cn\/api\/v\d\/sfo\/popup_displays? url reject-dict
^https?:\/\/sf3-be-pack\.pglstatp-toutiao\.com\/img\/ad\.union\.api url reject
^https?:\/\/service\.iciba\.com\/popo\/open\/screens\/v\d\?adjson url reject-200
^https?:\/\/service\.haiersmarthomes\.com\/management\/banner\/getBannerList\?source=4 url reject-dict
^https?:\/\/service\.busi\.inke\.cn\/api\/flash\/screen url reject-200
^https?:\/\/service\.busi\.inke\.cn\/api\/flash\/screen url reject
^https?:\/\/service\.4gtv\.tv\/4gtv\/Data\/(?>GetAD|ADLog) url reject-200
^https?:\/\/search\.video\.iqiyi\.com\/q\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/sdkapp\.uve\.weibo\.com\/interface\/sdk\/sdkconfig\.php url reject
^https?:\/\/sdk\.alibaba\.com\.ailbaba\.me\/xgapp\.php\/v\d\/version url reject-200
^https?:\/\/sdk\.alibaba\.com\.ailbaba\.me\/xgapp\.php\/v\d\/top_notice\? url reject-200
^https?:\/\/sdk\.alibaba\.com\.ailbaba\.me\/xgapp\.php\/v\d\/advert\?position=[^2]+ url reject-200
^https?:\/\/sdk\.alibaba\.com\.ailbaba\.me\/.*?\/v\d\/(version|top_notice\?|advert\?position=[^2]+) url reject-200
^https?:\/\/sdk\.alibaba\.com\.ailbaba\.me\/(dsx|xgapp)\.php\/v\d\/(top_notice\?|version|advert\?position=[^2]+) url reject-200
^https?:\/\/sdk\.1rtb\.net\/sdk\/req_ad url reject-200
^https?:\/\/sdk1xyajs\.data\.kuiniuca\.com url reject
^https?:\/\/sapphire\.api\.microsoftapp\.net\/config\/api\/v1\/get url script-response-body https://raw.githubusercontent.com/ddgksf2013/Scripts/master/bing.js
^https?:\/\/saad\.ms\.zhangyue\.net\/ad\/ url reject-200
^https?:\/\/saad\.ms\.zhangyue\.net\/ad url reject
^https?:\/\/sa\d\.tuisong\.baidu\.com url reject-img
^https?:\/\/s\.jiediankeji\.com\/adv url reject-dict
^https?:\/\/s\.go\.sohu\.com\/adgtr\/\?gbcode= url reject-img
^https?:\/\/s3plus\.meituan\.net\/v1\/mss_a002 url reject-img
^https?:\/\/s3plus\.meituan\.net\/.+?\/linglong\/ url reject
^https?:\/\/s3plus\.meituan\.net\/.*\/brandcpt-vedio\/.*\?time url reject
^https?:\/\/s1\.api\.tv\.itc\.cn\/v4\/mobile\/control\/switch\.json url reject-200
^https?:\/\/rtbapi\.douyucdn\.cn\/japi\/sign\/app\/getinfo url reject-200
^https?:\/\/rp\.hpplay\.cn\/logouts url reject
^https?:\/\/router-app-api\.jdcloud\.com\/v\d\/board\/routerAppSplash url reject-200
^https?:\/\/richmanrules\.ksedt\.com\/intellectWaterfall(Bidding)?\/find url reject
^https?:\/\/richmanmain\.jxedt\.com\/advertisement\/fallback url reject-img
^https?:\/\/richmanapi\.jxedt\.com\/api\/(ad|adplus|banadplus)\/ url reject-200
^https?:\/\/restapi\.iyunmai\.com\/api\/ios\/ad\/ url reject-200
^https?:\/\/restapi\.iyunmai\.com\/ad-api\/ url reject-200
^https?:\/\/res\.xiaojukeji\.com\/resapi\/activity\/xpget url script-response-body https://raw.githubusercontent.com/ZenmoFeiShi/Qx/main/Didichuxing.js
^https?:\/\/res\.xiaojukeji\.com\/resapi\/activity\/mget url script-response-body https://raw.githubusercontent.com/ZenmoFeiShi/Qx/main/Didichuxing.js
^https?:\/\/res\.xiaojukeji\.com\/resapi\/activity\/mget url reject
^https?:\/\/res\.xiaojukeji\.com\/resapi\/activity\/get(Ruled|Preload|PasMultiNotices) url reject
^https?:\/\/res\.pizzahut\.com\.cn\/CRM\/phad\/member\/app\/member url reject-200
^https?:\/\/res\.pizzahut\.com\.cn\/CRM\/phad\/apphome\/apphome url reject-200
^https?:\/\/res\.pizzahut\.com\.cn\/CRM\/phad\/apphome\/apphome url reject
^https?:\/\/res\.mi\.baidu\.com\/imeres\/ime-res\/advertisement\/files\/.+\.jpg url reject
^https?:\/\/res\.mall\.10010\.cn\/mall\/common\/js\/fa\.js?referer= url reject-img
^https?:\/\/res\.kfc\.com\.cn\/CRM\/kfcad\/apphome6\/\w+\.json\? url reject-dict
^https?:\/\/res\.kfc\.com\.cn\/CRM\/kfcad\/apphome5\/apphome url reject-200
^https?:\/\/res\.kfc\.com.\cn\/advertisement\/ url reject
^https?:\/\/res\.hongyibo\.com\.cn\/os\/gs\/resapi\/activity\/mget\?_t url reject-dict
^https?:\/\/res.kfc.com.cn\/advertisement\/ url reject-200
^https?:\/\/res.kfc.com.cn\/CRM\/kfcad\/apphome6\/apphome.*json url response-body bootStrapAd response-body ddgksf2013
^https?:\/\/res-release\.wuta-cam\.com\/json\/ads_component_cache\.json url reject
^https?:\/\/rengine-platform\.llsapp\.com\/auth\/api\/remoteResource\/darwin url reject-200
^https?:\/\/referee\.xiaohongshu\.com\/v\d\/stateReport url reject-dict
^https?:\/\/recite\.perfectlingo\.com\/api\/recite\/floating-window\/v\d\/get-show.+ url reject-dict
^https?:\/\/recite\.perfectlingo\.com\/api\/recite\/content-recommend\/v\d\/get-by-uid.+ url reject-dict
^https?:\/\/recite\.perfectlingo\.com\/api\/recite\/app-act\/act-list.+ url reject-dict
^https?:\/\/r\.inews\.qq\.com\/(getBannerAds|getNewsRemoteConfig|getSplash|searchHotCatList|upLoadLoc) url reject-200
^https?:\/\/r\.inews\.qq\.com\/(getBannerAds|getNewsRemoteConfig|getSplash|searchHotCatList|upLoadLoc) url reject
^https?:\/\/r\.inews\.qq\.com\/(adsBlacklist|getFullScreenPic|getQQNewsRemoteConfig) url reject-200
^https?:\/\/r\.inews\.qq\.com\/(adsBlacklist|getFullScreenPic|getQQNewsRemoteConfig) url reject
^https?:\/\/r6\.mo\.baidu\.com\/res\/file/advertisement\/files\/.+\.jpg url reject
^https?:\/\/qzonestyle\.gtimg\.cn\/qzone\/biz\/gdt\/mob\/sdk\/ios\/v2\/ url reject-img
^https?:\/\/quanguo\.mygolbs\.com:8081\/MyBusServer\/servlet\/MyGoServer\.HttpPool\.HttpHandlerServlet url reject-200
^https?:\/\/qt\.qq\.com\/lua\/mengyou\/get_splash_screen_info url reject-200
^https?:\/\/qt\.qq\.com\/lua\/mengyou\/get_splash_screen_info url reject
^https?:\/\/qimg\.cdnmama\.com\/rd url reject-dict
^https?:\/\/qidian\.qpic\.cn\/qidian_common url reject-img
^https?:\/\/qianbao\.smzdm\.com\/v\d\/app\/home url script-response-body https://raw.githubusercontent.com/ZenmoFeiShi/Qx/main/Smzdm.js
^https?:\/\/qde\.qunar\.com\/preload url reject-200
^https?:\/\/qcwx\.medproad\.com:8080\/ad\/ url reject-200
^https?:\/\/qadx\.qinlinad\.com\/ad\/ url reject-200
^https?:\/\/pzoap\.moedot\.net\/xgapp\.php\/v2\/top_notice url reject-200
^https?:\/\/pzoap\.moedot\.net\/xgapp\.php\/v2\/top_notice url reject
^https?:\/\/pv\.elife\.icbc\.com\.cn\/OFSTPV\/utm\.gif url reject-200
^https?:\/\/push\.m\.youku\.com\/collect-api\/get_push_interval_config_wx\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/ptmpcap\.caocaokeji\.cn\/advert-bss\/ url reject-img
^https?:\/\/ptf\.flyertrip\.com\/common\/cf\/.*.jpg url reject-200
^https?:\/\/pt-starimg\.didistatic\.com\/static\/starimg\/node\/.*.(jpg|png|gif) url reject-200
^https?:\/\/pss\.txffp\.com\/piaogen\/images\/launchScreen/ url reject-200
^https?:\/\/promotion\.medlive\.cn\/getcover-v2\?app_name url reject-200
^https?:\/\/promote-trx\.helipay\.com\/promote-business-client\/pos\/appAdvertisement\/appAdvertisementList url reject-200
^https?:\/\/prom\.mobile\.gome\.com\.cn\/mobile\/promotion\/promscms\/sale\w+\.jsp url reject
^https?:\/\/prom\.mobile\.gome\.com\.cn\/mobile\/promotion\/promscms\/\w+\.jsp url reject
^https?:\/\/preprod\.cdzghome\.com:8100\/banner\/bootUp url reject-200
^https?:\/\/post\.soulapp\.cn\/v\d\/post\/homepage\/guide\/card url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/soul/soul_ads.js
^https?:\/\/post\.soulapp\.cn\/hot\/soul\/rank url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/soul/soul_ads.js
^https?:\/\/portal\.zjzwfw\.gov\.cn\/app_api\/appHome\/selectStartPic url reject-200
^https?:\/\/portal-xunyou\.qingcdn\.com\/api\/v\d\/ios\/configs\/(?>splash_ad|ad_urls) url reject-200
^https?:\/\/portal-xunyou\.qingcdn\.com\/api\/v\d\/ios\/ads\/ url reject-200
^https?:\/\/portal-portm\.meituan\.com\/horn_ios\/mergeRequest url reject-dict
^https?:\/\/poplayer\.template\.alibaba\.com\/\w+\.json url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/myBlockAds.js
^https?:\/\/pocketuni\.net\/\?app=api&mod=Message&act=ad url reject-200
^https?:\/\/plough\.babytree\.com\/plough\.do url reject-200
^https?:\/\/pipi\.4kya\.com\/\/xgapp\.php\/v3\/advert\.position=[^2]+ url reject-200
^https?:\/\/pipi\.4kya\.com\/\/xgapp\.php\/v3\/advert\.position=[^2]+ url reject
^https?:\/\/pic\.k\.sohu\.com\/img\d\/wb\/tj\/ url reject
^https?:\/\/pic\.k\.sohu\.com\/img8\/wb\/tj\/ url reject-200
^https?:\/\/pic\.edaijia\.cn\/adsplash\/ url reject-200
^https?:\/\/pic1\.chelaile\.net\.cn\/adv\/ url reject
^https?:\/\/pic1.chelaile.net.cn\/adv\/ url reject-200
^https?:\/\/photocdn\.sohu\.com\/tvmobilemvms url reject-img
^https?:\/\/peisongapi\.meituan\.com\/client\/getInitiateImage url reject-200
^https?:\/\/pb\d\.pstatp.com\/origin url reject
^https?:\/\/pan\.baidu\.com\/rest\/\d\.\d\/pcs\/adx url reject
^https?:\/\/pan\.baidu\.com\/rest\/2\.0\/pcs\/ad url reject-200
^https?:\/\/pan\.baidu\.com\/rest\/2\.0\/pcs\/ad url reject
^https?:\/\/pan\.baidu\.com\/rest\/.+\/pcs\/adx url reject
^https?:\/\/pan\.baidu\.com\/pmall\/order\/privilege\/info url reject
^https?:\/\/pan\.baidu\.com\/component\/view\/(1510|1130)\?vip url reject
^https?:\/\/pan\.baidu\.com\/api\/useractivity\/activity url reject
^https?:\/\/pan\.baidu\.com\/api\/certuser\/get url reject
^https?:\/\/pan\.baidu\.com\/act\/v\d\/(bchannel|welfare)\/list url reject-200
^https?:\/\/pan\.baidu\.com\/act\/v\d\/(bchannel|welfare)\/list url reject
^https?:\/\/pan\.baidu\.com\/act\/api\/activityentry url reject-200
^https?:\/\/pan\.baidu\.com\/act\/api\/activityentry url reject
^https?:\/\/pan\.baidu\.com\/act\/.+\/bchannel\/list url reject
^https?:\/\/pan-api\.bitqiu\.com\/activity\/getPromoteGuide url reject-200
^https?:\/\/pan-api\.bitqiu\.com\/activity\/getPromoteGuide url reject
^https?:\/\/pages\.xiaohongshu\.com\/data\/native\/matrix_switches url reject-dict
^https?:\/\/pagead2\.googlesyndication\.com\/pagead\/ url reject-img
^https?:\/\/pacdn\.m\.stock\.pingan\.com\/images\/ url reject-dict
^https?:\/\/p\d{1}\.meituan\.net\/(adunion|display|mmc|wmbanner)\/ url reject
^https?:\/\/p\d\.pstatp.com\/origin url reject
^https?:\/\/p\d\.music\.126\.net\/\w+==\/\d+\.jpg$ url reject
^https?:\/\/p\d\.meituan\.net\/wmbanner\/[A-Za-z0-9]+?\.jpg url reject-200
^https?:\/\/p\d\.meituan\.net\/movie\/\w+\.jpg\?may_covertWebp url reject-200
^https?:\/\/p\d\.meituan\.net\/movie\/[A-Za-z0-9]+?\.jpg\?may_covertWebp url reject-200
^https?:\/\/p\d\.meituan\.net\/(bizad|wmbanner)\/\w+\.jpg url reject-200
^https?:\/\/p\d.meituan.net\/movie\/.*?\?may_covertWebp url reject-img
^https?:\/\/p\.kuaidi100\.com\/mobile\/mobileapi\.do url reject
^https?:\/\/p\.du\.163\.com\/ad\/ url reject-200
^https?:\/\/p\.c\.music\.126.net\/.*?jpg$ url reject
^https?:\/\/p[^4](c)?\.music\.126\.net\/\w+==\/10995\d{13}\.jpg$ url reject-img
^https?:\/\/p1\-lm\.adukwai\.com\/bs2\/adUnionVideo url reject
^https?:\/\/p0\.pipi\.cn\/adAdmin\/\w+.jpg\? url reject-img
^https?:\/\/p0\.pipi\.cn\/adAdmin\/.+\.jpg\?imageMogr2\/quality\/85\?may_covertWebp url reject-dict
^https?:\/\/oxadmin\.cp\.com\.cn\/api\/hot\/index url reject-dict
^https?:\/\/oxadmin\.cp\.com\.cn\/api\/advertise\/banner url reject-dict
^https?:\/\/overseas.weico.cc\/portal.php\?a=get_coopen_ads url reject-200
^https?:\/\/overseas.weico.cc\/portal.php\?a=get_coopen_ads url reject
^https?:\/\/ossweb-img\.qq\.com\/upload\/adw\/image\/[0-9]{3}\/202[0-9]{5}\/[a-z0-9]{32}\.(jpg|jpeg) url reject-200
^https?:\/\/ossgw.alicdn.com\/creatives-assets\/image\/ url reject-200
^https?:\/\/osg-static\.sgcc\.com\.cn\/omg-static\/.*.jpg url reject-200
^https?:\/\/oral\.youdao\.com\/oral\/adInfo url reject-img
^https?:\/\/optimus-ads\.amap\.com\/uploadimg\/ url reject
^https?:\/\/operationapi\.fosunhanig\.com\/ad\/v\d\/(PopupAdList|ScreenAdList|BannerList) url reject-200
^https?:\/\/openapi\.boc\.cn\/unlogin\/app\/cbsp\/query_ad_list url reject-200
^https?:\/\/open\.taou\.com\/maimai\/launch_ad url reject-200
^https?:\/\/open\.taou\.com\/maimai\/(launch_ad|ad?) url reject
^https?:\/\/open\.qyer\.com\/qyer\/startpage\/ url reject-200
^https?:\/\/open\.qyer\.com\/qyer\/config\/get url reject
^https?:\/\/open\.fitdays\.cn\/uploads\/ad\/ url reject
^https?:\/\/open\.e\.kuaishou\.com\/rest\/e\/v\d\/open\/univ$ url script-response-body https://raw.githubusercontent.com/app2smile/rules/master/js/adsense.js
^https?:\/\/open\.e\.kuaishou\.com\/rest\/e\/v3\/open\/univ url reject
^https?:\/\/open\.e\.kuaishou\.cn\/rest\/e\/v3\/open\/univ url reject
^https?:\/\/open3\.vistastory\.com\/v\d\/api\/index\/loading_ad url reject
^https?:\/\/open3\.vistastory\.com\/v\d\/api\/inde/loading_ad url reject-200
^https?:\/\/open3\.vistastory\.com\/v\d\/api.*get_popup url reject
^https?:\/\/open-cms-api\.(uc|quark)\.cn\/open-cms url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/quark.js
^https?:\/\/open-cms-api\.(uc|quark)\.cn\/open-cms url script-response-body https://raw.githubusercontent.com/ddgksf2013/Scripts/master/quark.js
^https?:\/\/oneapph5\.dongfeng-nissan\.com\.cn\/mb-gw\/vmsp-discover\/rest\/business-service\/v1\/advert\/advertinfo url reject-dict
^https?:\/\/one-app-h5\.faw-vw\.com\/prod-api\/mobile\/one-app\/general\/public\/v1\/official_activity\/get_animation_putaway_list\?appkey.* url reject-200
^https?:\/\/one-app-h5\.faw-vw\.com\/prod-api\/mobile\/one-app\/general\/public\/v1\/first_page\/get_carousel_list?appkey.* url reject-200
^https?:\/\/omgup[0-9]{1}\.xiaojukeji\.com\/api url reject-200
^https?:\/\/ok\.166\.net\/reunionpub\/202[2-9]{1}-[0-9]{2}-[0-9]{2}\/ntesgod_cms\/.*.jpg$ url reject-200
^https?:\/\/oimage\w\d\.ydstatic\.com\/image\?.+?=adpublish url reject-img
^https?:\/\/oimage([a-z])([0-9])\.ydstatic\.com\/.+adpublish url reject
^https?:\/\/ocrifs\.ejoy\.sinopec\.com\/advertitfs\/advert\/findAdvertInfo url reject-dict
^https?:\/\/ocean\.shuqireader\.com\/api\/route\/iosReadPage\/ad.+ url reject
^https?:\/\/ocean\.shuqireader\.com\/api\/ad\/adserver\/.+ url reject
^https?:\/\/oauth\.secure\.pixiv\.net\/(auth\/token) url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/pixivAds.js
^https?:\/\/notify\.baicizhan\.com\/rpc\/notify\/get_latest_notify url reject-200
^https?:\/\/notch\.qdaily\.com\/api\/v\d\/boot_ad url reject
^https?:\/\/nnapp\.cloudbae\.cn\/mc\/api\/advert/ url reject
^https?:\/\/nnapp\.cloudbae\.cn:\d+\/mc\/api\/advert/ url reject
^https?:\/\/nex.163.com\/q url reject
^https?:\/\/news\.ssp\.qq\.com\/app url reject
^https?:\/\/newclient\.map\.baidu\.com\/client\/usersystem\/home\/dynamic url reject-200
^https?:\/\/newclient\.map\.baidu\.com\/client\/phpui2\/\?qt=ads url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/baidumap.js
^https?:\/\/newclient\.map\.baidu\.com\/client\/phpui2\/\?qt=ads url reject-200
^https?:\/\/newclient\.map\.baidu\.com\/client\/phpui.*qt=hw url reject-200
^https?:\/\/newclient\.map\.baidu\.com\/client\/crossmarketing url reject-200
^https?:\/\/newapp2\.szsmk\.com\/app\/config\/queryMainAd url reject-200
^https?:\/\/ndstatic\.cdn\.bcebos\.com\/activity\/welfare\/js\/.+\.js url reject
^https?:\/\/ndstatic\.cdn\.bcebos\.com\/activity\/welfare\/index\.html url reject
^https?:\/\/napi\.ithome\.com\/api\/(news\/index|topmenu\/getfeeds) url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/ithome.js
^https?:\/\/musicpay\.kuwo\.cn\/music\.pay url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/break/kuwo.js
^https?:\/\/mtteve\.beacon\.qq\.com\/analytics url reject-img
^https?:\/\/ms\.jr\.jd\.com\/gw\/generic\/aladdin\/(new)?na\/m\/getLoadingPicture url reject-200
^https?:\/\/ms\.jr\.jd\.com\/gw\/generic\/aladdin\/(new)?na\/m\/getLoadingPicture url reject
^https?:\/\/mrp\.mcloud\.139\.com\/mc\/mc-client-service\/openapi\/letter\/query url reject-dict
^https?:\/\/mrobot\.pconline\.com\.cn\/s\/onlineinfo\/ad\/ url reject-200
^https?:\/\/mrobot\.pconline\.com\.cn\/s-900\/onlineinfo\/cms\/launch url reject-200
^https?:\/\/mrobot\.pcauto\.com\.cn\/xsp\/s\/auto\/info\/(ad|preload) url reject
^https?:\/\/mrobot\.(pcauto|pconline)\.com\.cn\/v\d\/ad\dp url reject
^https?:\/\/mres\.aibank\.com\/app\/resource\/cim\/cim0000001\/.+\.jpg url reject-200
^https?:\/\/mps\.95508\.com\/mps\/club\/cardPortals\/adv\/\d{25}\.(png|jpg) url reject-img
^https?:\/\/mpos-pic\.helipay\.com\/upload\/images\/advertisment\/image url reject
^https?:\/\/mpos-pic\.helipay\.com\/upload\/images\/advertisment url reject-200
^https?:\/\/mpcs\.suning\.com\/mpcs\/dm\/getDmInfo url reject-200
^https?:\/\/mpcs\.suning\.com\/mpcs\/dm\/getDmInfo url reject
^https?:\/\/mp\.weixin\.qq\.com\/mp\/getappmsgad url response-body advertisement response-body random_body
^https?:\/\/mp\.weixin\.qq\.com\/mp\/getappmsgad url response-body advertisement response-body ddgksf2013
^https?:\/\/mp\.weixin\.qq\.com\/mp\/cps_product_info\?action url reject-dict
^https?:\/\/mp\.weixin\.qq\.com\/mp\/cps_product_info url reject-200
^https?:\/\/mobileso\.bz\.mgtv\.com\/spotlight\/search\/v1\? url reject-dict
^https?:\/\/mobileso\.bz\.mgtv\.com\/mobile\/recommend\/v2\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/mobilepaas\.abchina\.com\.cn:441\/mgw\.htm url script-response-header https://raw.githubusercontent.com/ddgksf2013/Scripts/master/abchina.js
^https?:\/\/mobile\.yangkeduo\.com\/proxy\/api\/api\/express\/post\/waybill\/red_packet\/goods_list$ url response-body "list":\[.+\] response-body "list":[]
^https?:\/\/mobile\.flightradar24\.com\/mobile\/(user-session|subscribe) url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/QuantumultX/scripts/Flightradar24.js
^https?:\/\/mobile\.cebbank\.com\/cebclient\/ClientNoticeList url reject-200
^https?:\/\/mobile\.api\.mgtv\.com\/v2\/mobile\/checkUpdate\? url reject-dict
^https?:\/\/mobile\.api\.mgtv\.com\/v10\/video\/info\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/mobile\.api\.mgtv\.com\/mobile\/config\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/mobile\.1qianbao\.com\/mtp-web\/ui\/op_common_query_business_yqb\.json url reject-200
^https?:\/\/mobile-thor\.api\.mgtv\.com\/v1\/vod\/info\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/mobile-pic\.cache\.iciba\.com\/feeds_ad\/ url reject-200
^https?:\/\/mobile-pic\.cache\.iciba\.com\/feeds_ad\/ url reject
^https?:\/\/mobile-api\.imlaidian\.com\/api\/args url reject-dict
^https?:\/\/mobile-api2011\.elong\.com\/ad(?>v|gateway) url reject-200
^https?:\/\/mobads\.baidu\.com\/cpro\/ui\/mads.php url reject-200
^https?:\/\/mobads\.baidu\.com\/cpro\/ui\/mads.+ url reject
^https?:\/\/mobads-pre-config\.cdn\.bcebos\.com\/preload\.php url reject-200
^https?:\/\/mob\.mddcloud\.com\.cn\/adApi\/advert\/(first|third)part\/advertList url reject-dict
^https?:\/\/mob\.mddcloud\.com\.cn\/adApi\/advert url reject-200
^https?:\/\/mob-st\.bz\.mgtv\.com\/odin\/c1\/channel\/index\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/mmgr\.gtimg\.com\/gjsmall\/qqpim\/public\/ios\/splash\/.+?\/\d{4}_\d{4} url reject-img
^https?:\/\/mmgr\.gtimg\.com\/gjsmall\/qiantu\/upload\/ url reject-img
^https?:\/\/mmg\.aty\.sohu\.com\/pvlog? url reject-img
^https?:\/\/mmg\.aty\.sohu\.com\/mqs? url reject-img
^https?:\/\/mlol\.qt\.qq\.com\/go\/recommend url reject-200
^https?:\/\/mlol\.qt\.qq\.com\/go\/recommend url reject
^https?:\/\/mlife\.jf365\.boc\.cn\/AppPrj\/FirstPic\.do\?txnId=2PIC000001 url reject-200
^https?:\/\/mkt-gateway\.tuhu\.cn\/mkt-scene-marketing-service\/api\/scene\/queryScheme url reject-dict
^https?:\/\/mix-api\.camera360\.com\/v\d\/operational-positions url reject-200
^https?:\/\/misc-api-prd-mx\.wandafilm\.com\/commend\/common_banner_batch\.api\?bannerInfos=%5B%7B%22cinemaI url response-body "WX_index_mp-&-boxAD" response-body "WX_index_mp-&-boxAD0"
^https?:\/\/minipro\.95504\.net\/app\/json\/ad\/getPopAdData url reject-dict
^https?:\/\/minipro\.95504\.net\/app\/json\/ad\/getIndexAdData url reject-dict
^https?:\/\/mime\.baidu\.com\/v\d\/activity\/advertisement url reject-200
^https?:\/\/mime\.baidu\.com\/v\d\/activity\/advertisement url reject
^https?:\/\/mime\.baidu\.com\/v\d\/IosStart\/getStartInfo url reject-200
^https?:\/\/mime\.baidu\.com\/v\d\/IosStart\/getStartInfo url reject
^https?:\/\/mime\.baidu\.com\/v5\/start_screen_ads\/list url reject
^https?:\/\/mime\.baidu\.com\/v5\/start_screen_ads/list url reject-dict
^https?:\/\/mime\.baidu\.com\/v5\/hotpatch\/check\?hotpatch url reject
^https?:\/\/mime\.baidu\.com\/v5\/activity\/advertisementnonrealtime url reject
^https?:\/\/mime\.baidu\.com\/sapi\/v1\/lccorpus\/(applist|pannellist) url reject-dict
^https?:\/\/mime\.baidu\.com\/sapi\/v1\/circle\/joinedlist url reject-dict
^https?:\/\/mime\.baidu\.com\/commer\/pocket_api\/enterprise_list url reject-dict
^https?:\/\/middle\.yun\.139\.com\/openapi\/cardConfig\/queryCardInfoV3 url reject-200
^https?:\/\/midc\.cdn-static\.abchina\.com\.cn\/distributecenterimg\/file\/download\/(?!bbc2|f015|1655|0992|4678|a194|d8e2|c513|e51c|0ee1|166e|05ca|c882|d5b8|22ed|a0dc|a55a|6f89|3bf9|3c71|52ec|5b62|ve7a|001c|923d|accf|4a10|0bd7|be7a|5b62|5dd6|1f24|006c|775d|bd02|b983|5251|806b|d119|db14|43c9|41d3|8570|2c10|85ea|1435|814e|f422|aec7|738c|d7c8|0538|02b4|fd20|7647|f6ef|07c5|885b|e4cb|685b|30aa|c23b|9603|f27f|eaf8|8011|a5eb|409d|724c|3f2a|e07f|6744|60a6|158c|8ce3) url reject-dict
^https?:\/\/mi\.gdt\.qq\.com\/gdt_mview\.fcg\?posid= url reject-dict
^https?:\/\/mi\.gdt\.qq\.com\/gdt_mview\.fcg url reject
^https?:\/\/message\.shuqireader\.com\/message\/.+ url reject
^https?:\/\/media\.qyer\.com\/ad\/ url reject
^https?:\/\/mea\.meitudata\.com\/kaiping url reject
^https?:\/\/me\.bz\.mgtv\.com\/v3\/module\/list\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/mcs-mimp-web\.sf-express\.com\/mcs-mimp\/integralPlanet\/getCxAdvertiseList url reject-dict
^https?:\/\/mcmm\.caiyun\.feixin\.10086\.cn:80\/mcmm\/api\/v\d\/getAdverts url reject-200
^https?:\/\/mcmm\.caiyun\.feixin\.10086\.cn:80\/mcmm\/api\/IAdvert url reject-200
^https?:\/\/mcc.psbc.com:9090\/mcc\/resources\/[0-9]+\.(jpg|png) url reject-200
^https?:\/\/mbs\.boc\.cn\/ubas-mgateway-static\/images\/advertType\/.+.jpg url reject-200
^https?:\/\/mbmodule-openapi\.paas\.cmbchina\.com\/graphic\/v2\/module\/graphic url reject-dict
^https?:\/\/mbd\.baidu\.com\/newspage\/api\/getmobads\?page\=landingshare url reject
^https?:\/\/mbd\.baidu\.com\/ccs\/v1\/start\/confsync\?appname=baidu_input url reject-dict
^https?:\/\/mbasecc\.(bas|bcs)\.cmbchina\.com\/Edge\/api\/mlife\.clientface\.clientservice\.api\.advertiseService\/preCacheAdvertiseSec url reject-dict
^https?:\/\/mbank\.grcbank\.com\/ydyh\/resources\/startpage\/.*.(jpg|png) url reject-200
^https?:\/\/mapiweb\.babytree\.com\/newapi\/luban\/behavior\/receive url reject-200
^https?:\/\/mapi\.xiaotucc\.com\/(mall\/main|main_page\/index\/getActivity) url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/xiaotucc.js
^https?:\/\/mapi\.txcmapp\.com\/api\/open\/atx2\/ad\.php url reject-200
^https?:\/\/mapi\.sichuanair\.com\/zt\/tribeport\/encrypt_translate_key url reject-200
^https?:\/\/mapi\.sfbest\.com\/brokerservice-server\/cms\/getPositionById.* url reject
^https?:\/\/mapi\.mafengwo\.cn\/widget\/note\/get_widget_note url reject
^https?:\/\/mapi\.mafengwo\.cn\/system\/update\/check_update url reject-dict
^https?:\/\/mapi\.mafengwo\.cn\/system\/push\/get_local_push_config url reject
^https?:\/\/mapi\.mafengwo\.cn\/system\/config\/mark_alert_config url reject-dict
^https?:\/\/mapi\.mafengwo\.cn\/system\/config\/get_push_config url reject-dict
^https?:\/\/mapi\.mafengwo\.cn\/system\/config\/get_alert_config url reject-dict
^https?:\/\/mapi\.mafengwo\.cn\/(travelguide\/)?ad url reject-200
^https?:\/\/mapi\.dangdang\.com\/index\.php\?action=init url reject-200
^https?:\/\/mapi\.dangdang\.com\/index\.php\?action=init url reject
^https?:\/\/mapi\.appvipshop\.com\/vips-mobile\/rest\/layout\/productList\/eventData\/v url reject-200
^https?:\/\/mapi\.appvipshop\.com\/vips-mobile\/rest\/iosAdInfo\/report url reject
^https?:\/\/mapi\.appvipshop\.com\/vips-mobile\/rest\/activity\/coupon\/float_entrance\/get\?api_key url reject-200
^https?:\/\/mapi\.appvipshop\.com\/vips-mobile\/rest\/activity\/advertisement\/get url reject-200
^https?:\/\/mapi-app\.bestpay\.com\.cn\/gapi\/appclient\/noEnc\/getAppPopup url reject-dict
^https?:\/\/mapi-app\.bestpay\.com\.cn\/gapi\/appClient\/noEnc\/getHomePageAds url reject-dict
^https?:\/\/mangaapi\.manhuaren\.com\/v\d\/public\/getStartPageAds url reject
^https?:\/\/manga\.bilibili\.com\/twirp\/comic\.v\d\.Comic\/(Flash|ListFlash|GetActivityTab) url reject-dict
^https?:\/\/mama\.dxy\.com\/api\/cms\/client\/popup-window\/list url reject-200
^https?:\/\/mall\.meituan\.com\/api\/c\/homepage\/splash url reject-dict
^https?:\/\/mall\.meituan\.com\/api\/c\/homepage\/bubble\/operate\/info url reject-dict
^https?:\/\/maicai\.api\.ddxq\.mobi\/homeApi\/getHomeAdPop url reject-dict
^https?:\/\/maicai\.api\.ddxq\.mobi\/advert\/getAd\?ad_id url reject-dict
^https?:\/\/maicai\.api\.ddxq\.mobi\/advert\/getAd url response-body rt_time":\d{2} response-body rt_time":40
^https?:\/\/magev\d\.if\.qidian\.com\/argus\/api\/v\d\/client\/getsplashscreen url reject-200
^https?:\/\/magev6\.if\.qidian\.com\/argus\/api\/v2\/adv\/getadvlistbatch url reject-dict
^https?:\/\/magev6\.if\.qidian\.com\/argus\/api\/v1\/followsubscribe url reject-dict
^https?:\/\/magev6\.if\.qidian\.com\/argus\/api\/v1\/bookshelf\/getTopOperation url reject-dict
^https?:\/\/magev6\.if\.qidian\.com\/argus\/api\/v1\/adv\/getadvlistbatch url reject
^https?:\/\/magev6\.if\.qidian\.com\/argus\/api\/v1\/adv url reject-dict
^https?:\/\/magev6\.if\.qidian\.com\/argus\/api\/(v4\/client\/getsplashscreen|v2\/deeplink\/geturl|v1\/(client\/getconf|adv\/getadvlistbatch\?positions=iOS_tab|dailyrecommend\/getdailyrecommend)) url script-response-body https://raw.githubusercontent.com/app2smile/rules/master/js/qidian.js
^https?:\/\/magev6\.if\.qidian\.com\/argus\/api\/(v1\/assembly\/toolbar|v3\/user\/getaccountpage) url script-response-body https://raw.githubusercontent.com/Yu9191/Rewrite/main/Qidian_my.js
^https?:\/\/mage\.if\.qidian\.com\/argus\/api\/v\d\/client\/getsplashscreen url reject
^https?:\/\/mage\.if\.qidian\.com\/Atom\.axd\/Api\/Client\/GetConfIOS url reject-img
^https?:\/\/ma\.ofo\.com\/ads url reject
^https?:\/\/ma\.ofo\.com\/adImage\/ url reject
^https?:\/\/ma-adx\.ctrip\.com\/_ma\.gif url reject
^https?:\/\/m\d\.amap\.com\/ws\/valueadded\/alimama\/splash_screen\/ url reject-200
^https?:\/\/m\.you\.163\.com\/activity\/popWindow url reject-200
^https?:\/\/m\.you\.163\.com\/activity\/popWindow url reject
^https?:\/\/m\.yap\.yahoo\.com\/v\d{2}\/getAds\.do url reject
^https?:\/\/m\.tuniu\.com\/api\/operation\/splash\/ url reject-200
^https?:\/\/m\.stock\.pingan\.com\/restapi\/rmd\/open\/O\/api\/openAd url reject-200
^https?:\/\/m\.qianbao\.qq\.com\/pages\/walletHome\?invisible url reject
^https?:\/\/m\.pvp\.xoyo\.com\/conf\/server-mapping url reject-dict
^https?:\/\/m\.prod\.app\.hsbcfts\.com\.cn\/api\/sapp\/biz\/config\/open\/queryappversion\?channelCode= url reject-dict
^https?:\/\/m\.msyc\.cc\/app\/getBootPage\/v\d url reject-200
^https?:\/\/m\.lkcoffee\.com\/ecapi\/resource\/m\/member\/exchange\/page url response-body \{.+\} response-body {"status":"SUCCESS"}
^https?:\/\/m\.lkcoffee\.com\/capi\/resource\/m\/growUp\/main url response-body "popTitle":".+?" response-body "popTitle":""
^https?:\/\/m\.ibuscloud\.com\/v\d\/app\/getStartPage url reject
^https?:\/\/m\.ctrip\.com\/restapi\/soa2\/\d+\/scjson\/tripAds url reject-200
^https?:\/\/m\.ctrip\.com\/restapi\/soa2\/[0-9]{5}\/json\/getTimeZoneServerIpList\?__gw_os=IOS url reject-200
^https?:\/\/m\.ctrip\.com\/restapi\/soa2\/13916\/scjson\/tripAds url reject-dict
^https?:\/\/m\.ctrip\.com\/restapi\/soa2\/13916\/json\/tripAds url reject-200
^https?:\/\/m\.creditcard\.ecitic\.com\/citiccard\/mbk\/appspace-getway\/getWay\/dkkj-system-web\/system\/v\d\/init-config url reject-200
^https?:\/\/m\.client\.10010\.com\/uniAdmsInterface\/getWelcomeAd url reject-200
^https?:\/\/m\.client\.10010\.com\/uniAdmsInterface\/(getHomePageAd|getWelcomeAd) url reject-img
^https?:\/\/m\.client\.10010\.com\/uniAdmsInterface\/(getHomePageAd|getWelcomeAd) url reject-200
^https?:\/\/m\.client\.10010\.com\/mobileService\/customer\/getclientconfig\.htm url reject-dict
^https?:\/\/m\.client\.10010\.com\/mobileService\/(activity|customer)\/(accountListData|get_client_adv|get_startadv) url reject-img
^https?:\/\/m\.client\.10010\.com\/mobileService\/(activity|customer)\/(accountListData|get_client_adv|get_startadv) url reject-200
^https?:\/\/m\.aty\.sohu\.com\/openload? url reject-img
^https?:\/\/m\.360buyimg\.com\/babel\/jfs\/t1\/[0-9]{6}\/[0-9]{2}\/[0-9]{5}\/[0-9]{6}\/.*.jpg url reject-200
^https?:\/\/m\.360buyimg\.com\/babel\/jfs\/t1\/180291\/5\/23800\/294871\/625f5da2E13ac0ba3\/230238c767c61b6d\.jpg url reject
^https?:\/\/m?api\.weibo\.c(n|om)\/\d\/video/(community_tab|remind_info|tiny_stream_video_list) url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/weibo_json.js
^https?:\/\/m?api\.weibo\.c(n|om)\/\d\/statuses/(unread_)?friends(/|_)timeline url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/weibo_json.js
^https?:\/\/m?api\.weibo\.c(n|om)\/\d\/statuses/(container_timeline|unread_hot_timeline|extend|video_mixtimeline|unread_topic_timeline) url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/weibo_json.js
^https?:\/\/m?api\.weibo\.c(n|om)\/\d\/search/(finder|container_timeline|container_discover) url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/weibo_json.js
^https?:\/\/m?api\.weibo\.c(n|om)\/\d\/profile/(me|container_timeline) url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/weibo_json.js
^https?:\/\/m?api\.weibo\.c(n|om)\/\d\/hot\/hours_spotlight url reject-dict
^https?:\/\/m?api\.weibo\.c(n|om)\/\d\/groups/timeline url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/weibo_json.js
^https?:\/\/m?api\.weibo\.c(n|om)\/\d\/cardlist url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/weibo_json.js
^https?:\/\/m?api\.weibo\.c(n|om)\/\d\/ad\/weibointl\? url reject-dict
^https?:\/\/m?api\.weibo\.c(n|om)\/\d\/\w{5}\/cardlist url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/weibo_json.js
^https?:\/\/m?api\.weibo\.c(n|om)\/\d\/(searchall|page\?|messageflow) url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/weibo_json.js
^https?:\/\/m?api\.weibo\.c(n|om)\/\d\/(checkin/show|\!/live/media_homelist|comments/build_comments|container/get_item) url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/weibo_json.js
^https?:\/\/m?api\.weibo\.c(n|om)\/\d/push/daily url reject-dict
^https?:\/\/m5\.amap\.com\/ws\/valueadded\/ url reject
^https?:\/\/m5\.amap\.com\/ws\/shield\/dsp\/app\/startup\/init\? url reject-dict
^https?:\/\/m1\.ad\.10010\.com\/noticeMag\/images\/imageUpload\/2\d{3} url reject-img
^https?:\/\/m.ibuscloud.com\/v2\/app\/getStartPage url reject-200
^https?:\/\/m.360buyimg\.com\/mobilecms\/s1125x2436_jfs\/ url reject-200
^https?:\/\/m-cloud\.zhihu\.com\/api\/cloud\/config\/all\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/zhihu.js
^https?:\/\/m-cloud\.zhihu\.com\/api\/cloud\/config\/all\? url script-response-body https://gist.githubusercontent.com/blackmatrix7/f5f780d0f56b319b6ad9848fd080bb18/raw/zheye.min.js
^https?:\/\/luckman\.suning\.com\/luck-web\/policy\/v\d\/msf\/index\.do url reject-200
^https?:\/\/log.+?baidu\.com url reject
^https?:\/\/lofter\.lf127\.net\/ad\-material url reject-200
^https?:\/\/lives\.l\.qq\.com\/livemsg\?sdtfrom= url reject-img
^https?:\/\/live\.inst-service\.htsc\.com\/live url reject-dict
^https?:\/\/list-app-m\.i4\.cn\/getopfstadinfo\.xhtml url reject-200
^https?:\/\/list-app-m\.i4\.cn\/getopfstadinfo\.xhtml url reject
^https?:\/\/lf\-cdn\-tos\.bytescm\.com\/obj\/static\/ad url reject
^https?:\/\/lens\.leoao\.com\/lens\/conduct\/app\/rpc\/v2\/com\.lefit\.dubbo\.cms\.api\.front\.AppAdvertisingFrontService\/getAppAdvertisingNew url reject-dict
^https?:\/\/lens\.leoao\.com\/lens\/conduct\/app\/rpc\/v2\/com\.lefit\.dubbo\.cms\.api\.front\.AdvertiseConfigFrontService\/getAdvertiseConfigNew url reject-dict
^https?:\/\/lens\.leoao\.com\/lens\/conduct\/app\/rpc\/v2\/com\.lefit\.dubbo\.cms\.api\.bff\.ClientFrontFacade\/queryHomeMiddleInfo url reject-dict
^https?:\/\/learn\.chaoxing\.com\/apis\/service\/appConfig\? url reject
^https?:\/\/learn\.chaoxing\.com\/apis\/service\/appConfig url reject-200
^https?:\/\/lchttpapi\.xczim\.com\/1\.1\/functions\/getLaunchImageForIOS url reject-200
^https?:\/\/lchttpapi\.xczim\.com\/1\.1\/functions\/getLaunchImageForIOS url reject
^https?:\/\/lcen\.xiaote\.net\/api\/graphql url response-body screenSplashAd response-body random-response
^https?:\/\/lcen\.xiaote\.net\/api\/graphql url response-body screenSplashAd response-body ddgksf2013
^https?:\/\/lban\.spdb\.com\.cn\/mspmk-web-component\/prefetchAdvList\.ah url reject
^https?:\/\/lban\.spdb\.com\.cn\/mspmk-web-component\/getAdvertisementList\.ah url reject
^https?:\/\/lban\.spdb\.com\.cn\/mspmk-web-component\/getAdvList\.ah$ url reject
^https?:\/\/lban\.spdb\.com\.cn\/mspmk-web-component\/(getAdvList|prefetchAdvList)\.ah url reject-200
^https?:\/\/lamb\.lakala\.com\/lamo\/adv\/access\/queryMaterialUrl url reject-dict
^https?:\/\/l[0-9]{1}\.51fanli\.net\/app\/images\/splash\/202\d{1}\/\d{2}\/.*.jpg url reject-200
^https?:\/\/l[0-9]{1}\.51fanli\.net\/app\/images\/splash\/2022\/1[0-2]{1}\/.*.jpg url reject-200
^https?:\/\/l[0-9]{1}\.51fanli\.net\/app\/images\/splash\/2022\/0[4-9]{1}\/.*.jpg url reject-200
^https?:\/\/kaola-haitao\.oss\.kaolacdn.com\/.+?_\d{3,4}_\d{4}\.jpg\?x-oss-process=image\/resize,m_mfit,w_\d{3,4},h_\d{4}\/format,webp\/quality,Q_85 url reject-200
^https?:\/\/kano\.guahao\.cn\/[a-zA-Z0-9]{12} url reject-200
^https?:\/\/kano\.guahao\.cn\/.+?\?resize=\d{3}-\d{4} url reject-img
^https?:\/\/kad\.gotokeep\.com\/op-engine-webapp\/v\d\/ad url reject-200
^https?:\/\/kad\.gotokeep\.com\/op-engine-webapp\/v\d\/ad url reject
^https?:\/\/jz\.wacaijizhang\.com\/api\/banners\/newSplash url reject-200
^https?:\/\/js-ad\.ayximgs\.com\.ad-universe-cdn\.hzhcbkj\.cn\/xgapp\.php\/v2\/top_notice url reject-200
^https?:\/\/js-ad\.ayximgs\.com\.ad-universe-cdn\.hzhcbkj\.cn\/xgapp\.php\/v2\/top_notice url reject
^https?:\/\/jiucaigongshe\.oss-cn-beijing\.aliyuncs\.com\/[A-Z0-9]{8}-[A-Z0-9]{4}-[A-Z0-9]{4}-[A-Z0-9]{4}-[A-Z0-9]{12}\.png url reject-200
^https?:\/\/jdread-api\.jd\.com\/jdread\/api\/popup url reject-200
^https?:\/\/jdread-api\.jd\.com\/jdread\/api\/channel\/module\/opens url reject-200
^https?:\/\/jad-api\.jin10\.com\/ad url reject-200
^https?:\/\/jad-api\.jin10\.com\/ad url reject
^https?:\/\/j5\.dfcfw\.com\/WG\/conf\/202[0-9]{5}/.*.(jpg|png) url reject-200
^https?:\/\/j5\.dfcfw\.com\/WG\/appconf\/202[0-9]{5}/.*.(jpg|png) url reject-200
^https?:\/\/j1\.pupuapi\.com\/client\/marketing\/banner\/v\d\?position url script-response-body https://raw.githubusercontent.com/ddgksf2013/Scripts/master/pupumarket.js
^https?:\/\/j1\.pupuapi\.com\/client\/marketing\/banner\/v7\?position_types=2(%[A-Z0-9]+)+&store_id url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/PupuSplashAds.js
^https?:\/\/j1\.pupuapi\.com\/client\/marketing\/banner\/v7\?position_types=(?!2)(.*)&store_id url reject
^https?:\/\/j1\.pupuapi\.com\/client\/marketing\/banner\/v7\?position url reject
^https?:\/\/j-image\.missfresh\.cn\/img_(.+)\.gif$ url reject
^https?:\/\/j-image\.missfresh\.cn\/img_(.+)\.(jpg|jpeg|gif|png)\?iopcmd=convert&dst=webp&q=85$ url reject
^https?:\/\/issuecdn\.baidupcs\.com\/issue\/netdisk\/ts_ad\/ url reject-200
^https?:\/\/issuecdn\.baidupcs\.com\/issue\/netdisk\/guanggao\/ url reject-200
^https?:\/\/issuecdn\.baidupcs\.com\/issue\/netdisk\/guanggao url reject
^https?:\/\/iqushangwang\.8quan\.com\/index\.php\/i\/index\/index url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/QuDa.js
^https?:\/\/iphone\.ac\.qq\.com\/.*\/Support\/(getSystemConf|bootScreen) url reject-200
^https?:\/\/iphone\.ac\.qq\.com\/.*\/Support\/(getSystemConf|bootScreen) url reject
^https?:\/\/ios\.wps\.cn\/ad-statistics-service url reject
^https?:\/\/ios\.lantouzi\.com\/api\/startpage url reject
^https?:\/\/ios-api\.lucklyworld\.com\/v6\/api\/config\/startup url reject-dict
^https?:\/\/iobs\.pingan\.com\.cn\/download\/icore-aops-base-dmz-prd\/(YourSystemName|icore-apps-ad) url reject-200
^https?:\/\/iobs\.pingan\.com\.cn\/download\/bweb-per-sf-prd\/bweb url reject-200
^https?:\/\/interface\.aomiapp\.com\/aomi-ads url reject
^https?:\/\/interface3?\.music\.163\.com\/w?e?api\/(search\/(chart|default|rcmd\/keyword|specialkeyword)|(resource-exposure\/|middle\/clientcfg\/config)|activity\/bonus\/playpage\/time\/query) url reject-dict
^https?:\/\/interface3?\.music\.163\.com\/eapi\/(vipcenter\/tspopup\/get|vipauth\/app\/auth|music-vip-membership\/client\/vip\/info|zone\/songplay\/entry\/get) url reject-dict
^https?:\/\/interface3?\.music\.163\.com\/eapi\/(side-bar\/mini-program\/music-service\/account|delivery\/batch-deliver) url reject-dict
^https?:\/\/interface3?\.music\.163\.com\/eapi\/(mlivestream\/entrance\/playpage|link\/(position\/show\/(strategy|resource)|scene\/show)) url reject-dict
^https?:\/\/interface3?\.music\.163\.com\/eapi\/(community\/friends\/fans-group\/artist\/group\/get|user\/sub\/artist|music\/songshare\/text\/recommend\/get|mine\/applet\/redpoint|resniche\/position\/play\/new\/get) url reject-dict
^https?:\/\/interface3?\.music\.163\.com\/eapi\/(comment\/(feed\/inserted|hotcomment\/collect|tips\/v\d\/get)|v\d\/content\/exposure\/comment\/banner) url reject-dict
^https?:\/\/interface3?\.music\.163\.com/eapi/(ad|abtest|sp|hot|store|mlog|search/(specialkeyword|defaultkeyword|hot)) url reject-img
^https?:\/\/interface(\d)?\.music\.163\.com\/w?e?eapi\/resource-exposure\/config url reject-dict
^https?:\/\/interface(\d)?\.music\.163\.com\/w?e?api\/vipcenter/tspopup\/get url reject-dict
^https?:\/\/interface(\d)?\.music\.163\.com\/w?e?api\/v1\/content\/exposure\/comment url reject-dict
^https?:\/\/interface(\d)?\.music\.163\.com\/w?e?api\/sp\/flow url reject-dict
^https?:\/\/interface(\d)?\.music\.163\.com\/w?e?api\/search\/specialkeyword url reject-dict
^https?:\/\/interface(\d)?\.music\.163\.com\/w?e?api\/search\/rcmd\/keyword url reject-dict
^https?:\/\/interface(\d)?\.music\.163\.com\/w?e?api\/search\/default\/keyword url reject-dict
^https?:\/\/interface(\d)?\.music\.163\.com\/w?e?api\/search\/default url reject-dict
^https?:\/\/interface(\d)?\.music\.163\.com\/w?e?api\/resource-exposure\/activity\/config url reject-dict
^https?:\/\/interface(\d)?\.music\.163\.com\/w?e?api\/music\/partner\/picked\/user\/top url reject-dict
^https?:\/\/interface(\d)?\.music\.163\.com\/w?e?api\/link\/scene\/show\/resource url reject-dict
^https?:\/\/interface(\d)?\.music\.163\.com\/w?e?api\/link\/position\/show\/resource url reject-dict
^https?:\/\/interface(\d)?\.music\.163\.com\/w?e?api\/lbs\/gpsStatus\/upload url reject-dict
^https?:\/\/interface(\d)?\.music\.163\.com\/w?e?api\/ios\/upgrade url reject-dict
^https?:\/\/interface(\d)?\.music\.163\.com\/w?e?api\/homepage\/daily\/song\/elf\/notice url reject-dict
^https?:\/\/interface(\d)?\.music\.163\.com\/w?e?api\/comment\/hotcomment\/collect url reject-dict
^https?:\/\/interface(\d)?\.music\.163\.com\/w?e?api\/comment\/feed\/inserted url reject-dict
^https?:\/\/interface(\d)?\.music\.163\.com\/w?e?api\/ad\/ url reject-dict
^https?:\/\/intellicc\.bcs\.cmbchina\.com\/Edge\/api\/mlife\.intelli\.adrender\.api\.AdWork\/getAdsBySlotId url reject-dict
^https?:\/\/intellicc\.bas\.cmbchina\.com\/Edge\/api\/mlife\.intelli\.render\.api\.render\/getDynamicDataSec url reject
^https?:\/\/init\.sms\.mob\.com\/.*sdk\/init.* url reject
^https?:\/\/info\.mina\.mi\.com\/advertise\/splash url reject-200
^https?:\/\/impservice\.dictapp\.youdao\.com\/imp\/request url reject-img
^https?:\/\/imgx\.jampp\.com\/imgsrv\/tn url reject-img
^https?:\/\/imgcache\.qq\.com\/qqlive\/ url reject-img
^https?:\/\/img\d\.doubanio\.com\/view\/dale-online\/dale_ad\/ url reject
^https?:\/\/img\.yun\.01zhuanche\.com\/statics\/app\/advertisement\/.+?-750-1334 url reject-img
^https?:\/\/img\.wukongtv\.com\/wkremote\/AD\/iOS\/.*.(jpg|png|jpeg) url reject-200
^https?:\/\/img\.meituan\.net\/dpmobile\/.+93241\.png url reject-dict
^https?:\/\/img\.meituan\.net\/dpmobile\/.*.(gif|jpg) url reject-200
^https?:\/\/img\.meituan\.net\/bizad\/.*.jpg url reject-200
^https?:\/\/img\.meituan\.net\/(bizad|brandCpt)\/\w+\.(png|jpg) url reject-200
^https?:\/\/img\.meituan\.net\/(bizad|brandCpt)\/\w+\.(png|jpg) url reject
^https?:\/\/img\.meituan\.net\/(adunion|display|midas)\/\w+\.(gif|jpg|jpg\.webp)$ url reject-200
^https?:\/\/img\.meituan\.net\/(?>adunion|display|midas)\/.+?\.(gif|jpg|jpg\.webp)$ url reject-200
^https?:\/\/img\.jiemian\.com\/ads\/ url reject-200
^https?:\/\/img\.jiemian\.com\/ads\/ url reject
^https?:\/\/img\.gdoil\.cn\/upload\/ad\/.*.(jpg|png) url reject-200
^https?:\/\/img\.ddrk\.me\/cover\.png url reject-img
^https?:\/\/img\.ddrk\.me\/ad190824 url reject-img
^https?:\/\/img\.dailmo\.com\/img\/6\/90585d9e96c73dd49644af57d8501624\.jpg url reject
^https?:\/\/img\.dailmo\.com\/img\/61\/23c7125bfe6166d69f3bff5b0ca4d31e\.jpg url reject
^https?:\/\/img\.dailmo\.com\/img\/5\/6cb2aa237ce1f65944aa1ecb29fbdeef\.jpg url reject
^https?:\/\/img\.dailmo\.com\/img\/50\/edb40c6392f848df37f9c31d8a6f90f6\.jpg url reject
^https?:\/\/img\.allahall\.com\/img\/6\/90585d9e96c73dd49644af57d8501624\.jpg url reject
^https?:\/\/img\.allahall\.com\/img\/61\/23c7125bfe6166d69f3bff5b0ca4d31e\.jpg url reject
^https?:\/\/img\.allahall\.com\/img\/5\/6cb2aa237ce1f65944aa1ecb29fbdeef\.jpg url reject
^https?:\/\/img\.allahall\.com\/img\/59\/6a13a75dfe46ebfdac96bd27ef098885\.jpg url reject
^https?:\/\/img\.allahall\.com\/img\/50\/edb40c6392f848df37f9c31d8a6f90f6\.jpg url reject
^https?:\/\/img\.admobile\.top\/admobile-adRequest\/.*.(jpg|png) url reject-200
^https?:\/\/img14.360buyimg.com\/mcoss\/jfs\/t1\/183719\/8\/13358\/190450\/60e82bedE10b64e23\/ url reject-200
^https?:\/\/img11\.360buyimg.com\/dl\/jfs\/t1\/195304\/29\/12317\/268480\/60e6fd21E02a8fb2a\/ url reject-200
^https?:\/\/img1.126.net\/channel14\/ url reject
^https?:\/\/img1.126.net\/.+dpi=\w{7,8} url reject
^https?:\/\/img0[1-9]{1}\.luckincoffeecdn\.com\/group\d/M00/[A-Z0-9]{2}/[A-Z0-9]{2}/[a-zA-Z0-9]{29}\.(jpg|jpeg)_\.webp url reject-200
^https?:\/\/img0[1-9]{1}\.benlailife\.com\/AppHomePageImage\/upload\/files\/.*.jpg url reject-200
^https?:\/\/img01\.10101111cdn\.com\/adpos\/share\/ url reject-img
^https?:\/\/img-tailor\.11222\.cn\/pm\/app\/.+\.gif url reject
^https?:\/\/img-tailor\.11222\.cn\/cms\/upload\/img\/.+ url reject
^https?:\/\/imeclient\.openspeech\.cn\/adservice\/ url reject-200
^https?:\/\/imcs\.citicbank\.com\/cloud\/.+(1125.+2436|1242.+2688|750.+1638|563.+1218) url reject-dict
^https?:\/\/images\.pinduoduo\.com\/marketing\_api url reject-200
^https?:\/\/images\.client\.vip\.xunlei\.com\/.+?\/advert\/ url reject-200
^https?:\/\/images\.cib\.com\.cn\/commons\/uploads\/commons\/[a-zA-Z0-9]{32}\.jpg\?ver=20230[1-9]{1} url reject-200
^https?:\/\/images\.cib\.com\.cn\/commons\/uploads\/commons\/[a-zA-Z0-9]{32}\.jpg\?ver=20221[1-2]{1} url reject-200
^https?:\/\/image\.suning\.cn\/uimg\/ma\/ad\/ url reject-200
^https?:\/\/image\.spdbccc\.com\.cn\/group\d\/M00\/[A-Z0-9]{2}\/[A-Z0-9]{2}\/.+(4038|0571|M511|V-008|g549|b0628|fg817|5w501|Jo341|Z4583|oo845|i4905|MY245|YU472|Y401|w428|s000) url reject-dict
^https?:\/\/ih2\.ireader\.com\/zycl\/api\/ad\/ url reject-200
^https?:\/\/ih2\.ireader\.com\/zycl\/api\/ad url reject-200
^https?:\/\/ih2\.ireader\.com\/zyapi\/self\/screen\/ad url reject-200
^https?:\/\/ih2\.ireader\.com\/zyapi\/bookstore\/ad\/ url reject-200
^https?:\/\/ih2\.ireader\.com\/zyapi\/bookstore\/ad url reject-200
^https?:\/\/igetcool-gateway\.igetcool\.com\/app-api-other-server\/white\/open\/ads.json url reject-200
^https?:\/\/iface2\.iqiyi\.com\/views_pop\/3\.0\/pop_control\? url reject-dict
^https?:\/\/iface2\.iqiyi\.com\/views\/3\.0\/(bottom_theme|home_top_menu)\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/iface2\.iqiyi\.com\/video\/3\.0\/v_interface_proxy\? url reject-dict
^https?:\/\/iface2\.iqiyi\.com\/ivos\/interact\/video\/data\? url reject-dict
^https?:\/\/iface2\.iqiyi\.com\/fusion\/3\.0\/common_switch\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/iface2\.iqiyi\.com\/control\/3\.0\/init_proxy\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/iface2\.iqiyi\.com\/aggregate\/3\.0\/getMyMenus\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/icc\.one\/iFreeTime\/xid32uxaoecnfv2\/ url reject
^https?:\/\/iapi\.bishijie\.com\/actopen\/advertising\/ url reject
^https?:\/\/iadmusicmatvideo\.music\.126\.net url reject
^https?:\/\/iadmusicmat\.music.126.net\/.*?jpg$ url reject
^https?:\/\/i\d\.hoopchina\.com\.cn/blogfile\//d+\//d+\/BbsImg\.(?<=(big.(png|jpg)))$ url reject-img
^https?:\/\/i\d\.hdslb\.com\/bfs\/manga-static\/\w+\.(jpg|png)$ url reject-200
^https?:\/\/i\d\.hdslb\.com\/bfs\/fawkes url reject-dict
^https?:\/\/i\.ys7\.com\/api\/ads\/ url reject-200
^https?:\/\/i\.ys7\.com\/api\/ads url reject
^https?:\/\/i9\.taou\.com\/maimai\/p\/[0-9]{5}\/[0-9]{3,4}_[0-9]{3}_[a-zA-Z0-9]{16}$ url reject-200
^https?:\/\/i1\.hoopchina\.com\.cn\/blogfile\/.+_\d{3}x\d{4} url reject-img
^https?:\/\/hz\.yxzq\.com\/news-configserver\/api\/v1\/query\/banner_advertisement url reject-dict
^https?:\/\/hui\.sohu\.com\/predownload2\/? url reject-img
^https?:\/\/httpdns\.music\.163\.com url reject
^https?:\/\/httpdns\.baidubce\.com url reject-200
^https?:\/\/httpdns.n\.netease\.com url reject
^https?:\/\/homepage-api\.smzdm\.com\/v3\/home url script-response-body https://raw.githubusercontent.com/ZenmoFeiShi/Qx/main/Smzdm.js
^https?:\/\/homefront\.qunar\.com\/front\/splash\/ad url reject-dict
^https?:\/\/home\.mi\.com\/cgi-op\/api\/v\d\/recommendation\/banner url reject
^https?:\/\/home\.mi\.com\/cgi-op\/api\/v1\/recommendation\/(banner|myTab)\? url reject-dict
^https?:\/\/hfapp-service\.qweather\.net\/v\d\.\d\/app\/ad\/list\? url reject-dict
^https?:\/\/hfapp-service\.qweather\.net\/.*\/ad\/ url reject-200
^https?:\/\/heic\.alicdn\.com\/tps\/i4\/.+?\.jpg_1200x1200q90\.jpg_\.heic$ url reject-200
^https?:\/\/hdgateway\.zto\.com\/track url reject-dict
^https?:\/\/hdgateway\.zto\.com\/listJumperShow url reject-dict
^https?:\/\/hdgateway\.zto\.com\/getApolloConfig url reject-dict
^https?:\/\/hdgateway\.zto\.com\/getAdInfo url reject-dict
^https?:\/\/hd\.xiaojukeji\.com\/d url reject-dict
^https?:\/\/hcz-member\.pingan\.com\.cn\/micro-api\/homepage\/do\/app\/popbox\/getTopPopBox url reject
^https?:\/\/hc-ssp\.sm\.cn url reject-200
^https?:\/\/hb-boom\.api\.mgtv\.com\/release\/pullReleaseInfo url reject-dict
^https?:\/\/haojia-api\.smzdm\.com\/home\/list url script-response-body https://raw.githubusercontent.com/ZenmoFeiShi/Qx/main/Smzdm.js
^https?:\/\/h5app\.kuwo\.cn\/m\/kwtemplatePage\/index\.html\?id=1157&app=bodianhdzx url reject-dict
^https?:\/\/h5app\.kuwo\.cn\/m\/bdvipact2205\/index\.html\?fromsrc=huodong url reject-dict
^https?:\/\/h5api\.sginput\.qq\.com\/v1\/gcenter\/ios\/homepage url reject-dict
^https?:\/\/gx\.10086\.cn\/zt-portal\/gxhzg\/portal\/app\/api\/v url reject-200
^https?:\/\/gx\.10086\.cn\/zt-portal\/gxhzg\/portal\/app\/api\/v url reject
^https?:\/\/gw\.kaola\.com\/gw\/dgmobile\/newOpenAd url reject-200
^https?:\/\/gw\.kaola\.com\/gw\/dgmobile\/newOpenAd url reject
^https?:\/\/gw\.csdn\.net\/cms-app\/v\d+\/home_page\/open_advertisement url reject
^https?:\/\/gw\.alicdn\.com\/tfs\/TB1.+?750-\d{4} url reject-200
^https?:\/\/gw\.alicdn\.com\/tfs\/.+\d{3,4}-\d{4} url reject
^https?:\/\/gw\.alicdn\.com\/tfs\/.+?\d{4}-\d{4}\/[a-z]{3}$ url reject-200
^https?:\/\/gw\.alicdn\.com\/mt\/ url reject
^https?:\/\/gw\.alicdn\.com\/imgextra\/\w{2}\/[\w!]+-\d-tps-\d{3}-\d{4}\.(jpg|png)$ url reject
^https?:\/\/gw\.aihuishou\.com\/app-portal\/home\/getadvertisement url reject
^https?:\/\/gw.aihuishou.com\/app-portal\/home\/getadvertisement url reject-200
^https?:\/\/gw-passenger\.01zhuanche\.com\/gw-passenger\/zhuanche-passengerController\/notk\/passenger\/recommendADs url reject
^https?:\/\/gw-passenger\.01zhuanche\.com\/gw-passenger\/zhuanche-passenger-token\/leachtoken\/webservice\/homepage\/queryADs url reject
^https?:\/\/gw-passenger\.01zhuanche\.com\/gw-passenger\/car-rest\/webservice\/passenger\/recommendADs url reject-200
^https?:\/\/gurd\.snssdk\.com\/src\/server\/v3\/package url reject
^https?:\/\/guide-acs\.m\.taobao\.com\/gw\/mtop\.taobao\.wireless\.home\.splash\.awesome\.get url reject-200
^https?:\/\/guide-acs\.m\.taobao\.com\/gw\/mtop\.taobao\.(volvo\.secondfloor\.getconfig|wireless\.home\.newface\.awesome\.get) url reject-dict
^https?:\/\/guide-acs\.m\.taobao\.com\/gw\/mtop\.taobao\.(cloudvideo\.video\.query|wireless\.home\.splash\.awesome\.get) url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/myBlockAds.js
^https?:\/\/guide-acs\.m\.taobao\.com\/gw\/mtop\.cainiao\.nbmensa\.research\.researchservice\.consultmerge url reject-200
^https?:\/\/guide-acs\.m\.taobao\.com\/gw\/mtop\.cainiao\.guoguo\.nbnetflow\.ads\.show url reject-200
^https?:\/\/guide-acs\.m\.taobao\.com\/gw\/mtop\.cainiao\.guoguo\.nbnetflow\.ads\.mshow url script-response-body https://raw.githubusercontent.com/ddgksf2013/Scripts/master/cainiao_json.js
^https?:\/\/guide-acs\.m\.taobao\.com\/gw\/mtop\.cainiao\.adx\.flyad\.getad url reject-200
^https?:\/\/gugongmini\.dpm\.org\.cn\/gugong_applet\/open-screen url reject-dict
^https?:\/\/guanyu\.longfor\.com\/app-server\/api\/v1\/main\/start url reject
^https?:\/\/gss0\.bdstatic\.com\/.+?\/static\/wiseindex\/img\/bd_red_packet\.png url reject-img
^https?:\/\/gsp\.gacmotor\.com\/gateway\/webapi\/baseinfo\/advertise\/getAdvertiseByPositionCode\?positionCode=1 url reject-dict
^https?:\/\/gsp\.gacmotor\.com\/gateway\/app-api\/app\/version\/latestupdate\?flatform=2&innerVersion= url reject-dict
^https?:\/\/gslb.*\.xima.*\.com\/ url reject
^https?:\/\/gql(-fed)?\.reddit\.com url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/reddit.js
^https?:\/\/gorgon\.youdao\.com\/gorgon url reject-200
^https?:\/\/gongdu\.youshu\.cc\/m\/open_screen\/list_by_udid url reject-200
^https?:\/\/gongdu\.youshu\.cc\/m\/open_screen\/list_by_udid url reject
^https?:\/\/god\.gameyw\.netease\.com\/v\d\/ad\/serving\/app-start url reject-200
^https?:\/\/god\.gameyw\.netease\.com\/v\d\/ad\/serving\/(common|app-start) url reject-dict
^https?:\/\/goblin\.hupu\.com\/.+\/interfaceAd\/getOther url reject-200
^https?:\/\/goblin\.hupu\.com\/.+\/interfaceAd\/getOther url reject
^https?:\/\/go\.babytree\.com\/go_tool\/api\/feeding_record\/get_home_banner_info url reject-dict
^https?:\/\/go\.babytree\.com\/go_pregnancy\/api\/index_activity\/get_app_index_activity url reject-200
^https?:\/\/gha\.ghac\.cn\:8081\/base\/app\/api\/ad\/query\?adType=1 url reject-200
^https?:\/\/gha\.ghac\.cn\:8081\/base\/app\/api\/ad\/query\?adType url reject-200
^https?:\/\/ggx\.cmvideo\.cn\/request\/ url reject-200
^https?:\/\/ggic\d?\.cmvideo\.cn\/ad\/ url reject-200
^https?:\/\/gg\w+?\.cmvideo\.cn\/v\d\/iflyad\/ url reject-200
^https?:\/\/gg\.caixin\.com\/s\?z=caixin&op=1&c=3362 url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/caixin/caixinAd.js
^https?:\/\/gg\.caixin\.com\/s\?z=caixin&op=1&c=3362 url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/caixinads.js
^https?:\/\/gfp\.veta\.naver\.com\/adcall\? url reject
^https?:\/\/geetest\.htsc\.com:8888\/pre_get_token url reject-200
^https?:\/\/gd\.10086\.cn\/gmccapp\/serv\/\?servicename=GMCCAPP_704_002_001_001 url reject-200
^https?:\/\/gd\.10086\.cn\/gmccapp\/serv\/\?servicename=GMCCAPP_704_002_001_001 url reject
^https?:\/\/gateway\.shouqiev\.com\/fsda\/app\/bootImage\.json url reject-200
^https?:\/\/gateway\.shouqiev\.com\/fsda\/app\/bootImage\.json url reject
^https?:\/\/gateway\.benewtech\.cn\/resources-app\/app\/startup\/prepage url reject-dict
^https?:\/\/gateway\.abite\.com\/cotti-capi\/customer\/position\/list\?code=cotti-launch-window url reject-200
^https?:\/\/gateway\.36kr\.com\/api\/adx\/ad\/show url reject-200
^https?:\/\/gateway\.36kr\.com\/api\/adx\/ad\/show url reject
^https?:\/\/gateway-mobile-gray\.soulapp\.cn\/mobile\/app\/version\/queryIos url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/soul/soul_ads.js
^https?:\/\/gateway-api\.dushu365\.com\/chief-orch\/config\/config\/v100\/appConfig url reject-200
^https?:\/\/gateway-api\.dushu365\.com\/chief-orch\/config\/config\/v100\/appConfig url reject
^https?:\/\/games\.mobileapi\.hupu\.com\/interfaceAdMonitor url reject-img
^https?:\/\/games\.mobileapi\.hupu\.com\/\d\/(?:\d\.){2}\d\/status\/init url reject
^https?:\/\/games\.mobileapi\.hupu\.com\/.+\/(search|interfaceAdMonitor|status|hupuBbsPm)/(hotkey|init|hupuBbsPm)\. url reject-img
^https?:\/\/games\.mobileapi\.hupu\.com\/.+?\/status\/init url reject
^https?:\/\/games\.mobileapi\.hupu\.com\/.+?\/(search|interfaceAdMonitor|status|hupuBbsPm)/(hotkey|init|hupuBbsPm)\. url reject-img
^https?:\/\/games\.mobileapi\.hupu\.com\/.+?\/(interfaceAdMonitor|interfaceAd)\/ url reject
^https?:\/\/gab\.122\.gov\.cn\/eapp\/m\/sysquery\/adver$ url reject
^https?:\/\/ga-album-cdnqn\.52tt\.com\/prod-yunying\/.+.jpg url reject-dict
^https?:\/\/g\.alicdn\.com\/.*o2o-ad url script-response-body https://raw.githubusercontent.com/zirawell/Ad-Cleaner/main/Collection/js/alicdn.js
^https?:\/\/g1.163.com\/madfeedback url reject
^https?:\/\/fuwu\.nhsa\.gov\.cn\/ebus\/fuwu\/api\/base\/cms\/iep\/web\/cms\/hmpgcfg\/queryAppHmpgCfgByApp url reject
^https?:\/\/fuss10\.elemecdn\.com\/.+\/w\/750\/h\/\d{3,4} url reject
^https?:\/\/fuss10\.elemecdn\.com\/.+\/w\/640\/h\/\d{3,4} url reject
^https?:\/\/fuss10\.elemecdn\.com\/.+?\.mp4 url reject-img
^https?:\/\/fuss10.elemecdn.com\/.+\/w\/750\/h\/\d{3,4} url reject-200
^https?:\/\/fuss10.elemecdn.com\/.+\/w\/640\/h\/\d{3,4} url reject-200
^https?:\/\/fuss10.elemecdn.com\/.+.mp4 url reject-200
^https?:\/\/ftapi\.10jqka\.com\.cn\/futgwapi\/api\/om\/v\d\/ad\/common\/transfer url reject-200
^https?:\/\/frodo\.douban\.com\/api\/v2\/movie\/banner url reject
^https?:\/\/freight\.xiaojukeji\.com\/gateway url script-response-body https://raw.githubusercontent.com/ZenmoFeiShi/Qx/main/Didichuxing.js
^https?:\/\/fmapp\.chinafamilymart\.com\.cn\/api\/app\/biz\/base\/appversion\/latest url reject
^https?:\/\/fm\.fenqile\.com\/routev2\/other\/startImg\.json url reject-img
^https?:\/\/fm\.fenqile\.com\/routev2\/other\/getfloatAd\.json url reject-img
^https?:\/\/flowplus\.meituan\.net\/v\d\/\w+\/linglong\/\d+\.(gif|jpg|mp4) url reject
^https?:\/\/firefly\.abchina\.com\.cn\/firefly-collection\/Collect url reject-200
^https?:\/\/fintechappdr\.cgws\.com\/api\/business-operation\/app\/a\/flash\/window\/get\?type=2 url reject-dict
^https?:\/\/file\.dian\.so\/c\/leto url reject-dict
^https?:\/\/file\.cibfintech\.com\/file\/M0[1-9]{1}\/*\/*\/.*.zip url reject-img
^https?:\/\/feedback\.uc\.cn\/feedback\/api\/get_unread_status url reject
^https?:\/\/fcvbjbcebos\.baidu\.com\/.+?\.mp4 url reject-img
^https?:\/\/fcvbjbcebos\.baidu\.com\/.+.mp4 url reject
^https?:\/\/fc-video\.cdn\.bcebos\.com url reject
^https?:\/\/fbchina\.flipchina\.cn\/v\d\/ad\/query url reject
^https?:\/\/fastbuyer\.zbj\.com\/configure\/screenAdConfig\/v2 url reject-200
^https?:\/\/facade-api\.black-unique\.com\/app\/v1\/startScreen\?cityId=102923&channelId=0&width=1170&height=2532 url reject-dict
^https?:\/\/facade-api\.black-unique\.com\/app\/v1\/startScreen\?.* url reject-dict
^https?:\/\/facade-api\.black-unique\.com\/advertise\/v1\/get\?cityId=102923&positions=mine_popup url reject-dict
^https?:\/\/facade-api\.black-unique\.com\/advertise\/v1\/get\?.* url reject-dict
^https?:\/\/explorer\.tratao\.com\/api\/client\/v4\/xtransfer\/ad\/ url reject-200
^https?:\/\/explorer\.tratao\.com\/api\/client\/v4\/xtransfer\/ad\/ url reject
^https?:\/\/evs\.500\.com\/esinfo\/loading\/loading url reject-200
^https?:\/\/evs\.500\.com\/esinfo\/loading\/loading url reject
^https?:\/\/erebor\.douban\.com\/count\/\?ad= url reject
^https?:\/\/entry\.ubixioe\.com\/mob\/sdk\/v\d\/endpoint url reject-200
^https?:\/\/entree-ws\.igetget\.com\/oms\/front\/start\/push url reject-200
^https?:\/\/enjoy\.cdn-static\.abchina\.com\/yx-engine-web\/file\/download\/(?!7dc2|fe96|cea3|06a8|1b11|d57b|6918|61db|2d58|aa23|) url reject-200
^https?:\/\/emdcadvise\.eastmoney\.com\/infoAdviseService$ url reject-200
^https?:\/\/emdcadvertise\.eastmoney\.com\/infoService\/v\d url reject-200
^https?:\/\/emdcadvertise\.eastmoney\.com\/infoService\/v\d url reject
^https?:\/\/emdcadvertise\.eastmoney\.com\/infoService\/v2 url reject-200
^https?:\/\/elife\.icbc\.com\.cn\/OFSTNEWBASE\/floorinfo\/getMantlePages\.do url reject-200
^https?:\/\/elemecdn\.com\/.+\/sitemap url reject
^https?:\/\/elemecdn.com\/.+\/sitemap url reject-200
^https?:\/\/editor\.sm\.cn\/launch_picture url reject
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/user\/teenager\/status url reject-dict
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/system_service\/splash_config$ url script-response-body https://github.com/fmz200/wool_scripts/raw/main/Scripts/xiaohongshu/xiaohongshu.js
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/system_service\/splash_config url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/redbook_json.js
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/system_service\/config\? url script-response-body https://github.com/fmz200/wool_scripts/raw/main/Scripts/xiaohongshu/xiaohongshu.js
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/system_service\/config\? url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/redbook_json.js
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/surprisebox\/(get_style|open|submit_action) url reject-dict
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/search\/trending url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/redbook_json.js
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/search\/notes\? url script-response-body https://github.com/fmz200/wool_scripts/raw/main/Scripts/xiaohongshu/xiaohongshu.js
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/search\/hot_list url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/redbook_json.js
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/search\/hint url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/redbook_json.js
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/search\/(hint|trending)\? url script-response-body https://github.com/fmz200/wool_scripts/raw/main/Scripts/xiaohongshu/xiaohongshu.js
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/search\/(banner|hot)_list url script-response-body https://github.com/fmz200/wool_scripts/raw/main/Scripts/xiaohongshu/xiaohongshu.js
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/note\/widgets url script-response-body https://github.com/fmz200/wool_scripts/raw/main/Scripts/xiaohongshu/xiaohongshu.js
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/note\/widgets url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/redbook_json.js
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/note\/videofeed\? url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/redbook_json.js
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/note\/redtube\? url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/redbook_json.js
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/note\/imagefeed url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/redbook_json.js
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/note\/guide\? url reject-dict
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/note\/feed\? url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/redbook_json.js
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/note\/(imagefeed|live_photo\/save) url script-response-body https://github.com/fmz200/wool_scripts/raw/main/Scripts/xiaohongshu/xiaohongshu.js
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/homefeed\? url script-response-body https://github.com/fmz200/wool_scripts/raw/main/Scripts/xiaohongshu/xiaohongshu.js
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/homefeed\? url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/redbook_json.js
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/homefeed\/categories url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/redbook_json.js
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/guide\/user_banner url reject-dict
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/guide\/home_guide url reject-dict
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d\/followfeed\? url script-response-body https://github.com/fmz200/wool_scripts/raw/main/Scripts/xiaohongshu/xiaohongshu.js
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/v\d+\/search\/notes\? url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/redbook_json.js
^https?:\/\/edith\.xiaohongshu\.com\/api\/sns\/(v\d\/note\/feed|v3\/note\/videofeed)\? url script-response-body https://github.com/fmz200/wool_scripts/raw/main/Scripts/xiaohongshu/xiaohongshu.js
^https?:\/\/edit\.sinaapp\.com\/ua\?t=adv url reject-200
^https?:\/\/ecard\.shenzhentong\.com\/wxweb\/bwxppub2\/QryAdvertList\.do url reject-200
^https?:\/\/easyreadfs\.nosdn\.127\.net\/ad-material\/ url reject-200
^https?:\/\/e\.weather\.com\.cn\/weChat\/typhoonNull\.json url reject-dict
^https?:\/\/e\.dangdang\.com\/media\/api.+\?action=getDeviceStartPage url reject
^https?:\/\/e\.dangdang\.com\/.+?getDeviceStartPage url reject-200
^https?:\/\/e\.dangdang\.com\/.+?getDeviceStartPage url reject
^https?:\/\/e.dangdang.com\/media\/api.+\?action=getDeviceStartPage url reject-200
^https?:\/\/e-static\.aia\.com\.cn\/kyh\/resourcefolder\/ads url reject-dict
^https?:\/\/dyncdn\.me\/static\/\d{0,2}\/js\/showads\.js$ url response-body true response-body false
^https?:\/\/dyncdn\.me\/static\/\d{0,2}\/js\/expla\d{0,4}\.js$ url reject-200
^https?:\/\/dxy\.com\/app\/i\/ask\/biz\/feed\/launch url reject
^https?:\/\/du\.hupucdn\.com\/\w+h\d{4} url reject-img
^https?:\/\/dss0\.bdstatic\.com\/.+/tam-ogel\/.+\.(jpg|mp4) url reject
^https?:\/\/dss0\.bdstatic\.com\/-0U0bnSm1A5BphGlnYG\/ url reject-200
^https?:\/\/dsp\.toutiao\.com\/api\/xunfei\/ads\/ url reject-200
^https?:\/\/dsp\.toutiao\.com\/api\/xunfei\/ads\/ url reject
^https?:\/\/dsp\-x\.jd\.com\/adx\/sdk url reject
^https?:\/\/dsp-impr2\.youdao\.com\/adload url reject-200
^https?:\/\/dsa-mfp\.fengshows\.cn\/mfp\/mfpMultipleDelivery\.do\?.+?adunitid url reject
^https?:\/\/dq\.dxy\.cn\/api\.php\?action=getpostbanners url reject-200
^https?:\/\/dq\.dxy\.cn\/api\.php\?action=getpostbanners url reject
^https?:\/\/douyucdn\.cn\/.+\/appapi\/getinfo url reject
^https?:\/\/douyucdn\.cn\/.+?\/appapi\/getinfo url reject-img
^https?:\/\/dns\.jd\.com\/ url reject
^https?:\/\/dl\.app\.gtja\.com\/dzswem\/kvController url reject-200
^https?:\/\/djcapp\.game\.qq\.com\/daoju\/igw\/main\/\?_service=welink\.ad\.list&_ret_key=result&site_set url reject-200
^https?:\/\/djcapp\.game\.qq\.com\/daoju\/igw\/main\/\?_service=welink\.ad\.list url reject-200
^https?:\/\/dj\.palmestore\.com\/zybk\/api\/ad url reject-200
^https?:\/\/display\.wting\.info\/.*.jpeg url reject-200
^https?:\/\/dispatcher\.camera360\.com\/api\/v\d\/list$ url reject
^https?:\/\/dispatcher\.camera360\.com\/api\/v1\/list$ url reject-200
^https?:\/\/discuz\.gtimg\.cn\/cloud\/scripts\/discuz_tips\.js url reject-img
^https?:\/\/direct\.z-bank\.com\/portal\/AdvertImageDownLoad4Mobile\.do url reject-200
^https?:\/\/dili\.bdatu\.com\/jiekou\/ad\/ url reject
^https?:\/\/dili\.bdatu\.com\/jiekou\/ad url reject-200
^https?:\/\/dictvip-business\.youdao\.com\/home\/ad url reject-dict
^https?:\/\/dict\.youdao\.com\/vip\/activity\/couponinfo url reject-dict
^https?:\/\/dict\.youdao\.com\/dictusertask\/system url reject-dict
^https?:\/\/dict\.youdao\.com\/course\/tab\/translateTab url reject-dict
^https?:\/\/dict\.youdao\.com\/commonsearch url reject-dict
^https?:\/\/dict\.youdao\.com\/(homepage\/promotion|course\/tab\/home|homepage\/tile) url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/youdao/dict-youdao-ad.js
^https?:\/\/dict-mobile\.iciba\.com\/interface\/index\.php\?.+(c=ad|collectFeedsAdShowCount|KSFeedsAdCardViewController) url reject
^https?:\/\/device-box\.onethingpcs\.com\/.+\/adConf url reject-200
^https?:\/\/delivery-api\.imdada\.cn\/v2_0\/dada\/promote\/imax\?privacyParam url reject-dict
^https?:\/\/delivery-api\.imdada\.cn\/v1_0\/transporter\/screen\/ads_list url reject-dict
^https?:\/\/delivery-api\.imdada\.cn\/v1_0\/transporter\/ad url reject-dict
^https?:\/\/ddrk\.me\/wp-content\/plugins\/advanced-floating-content-lite\/public\/images\/close\.png url reject-img
^https?:\/\/ddrk\.me\/image\/logo_footer\.png url reject-img
^https?:\/\/dc2?\.bz\.mgtv\.com\/dynamic\/v1\/channel\/(index|vrsList)\/\w url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/dapis\.mting\.info\/yyting\/advertclient\/ClientAdvertList\.action url reject-img
^https?:\/\/daoyu\.sdo\.com\/api\/userCommon\/getAppStartAd url reject-200
^https?:\/\/daoyu\.sdo\.com\/api\/userCommon\/getAppStartAd url reject
^https?:\/\/damang\.api\.mgtv\.com\/station\/album\/red\/dot\? url reject-dict
^https?:\/\/daijia\.kuaidadi\.com\/gateway\?api=prado\.cms\.delivery\.batch&apiVe url reject-dict
^https?:\/\/daijia\.kuaidadi\.com\/gateway url script-response-body https://raw.githubusercontent.com/ZenmoFeiShi/Qx/main/Didichuxing.js
^https?:\/\/daijia\.kuaidadi\.com:443\/gateway url script-response-body https://raw.githubusercontent.com/ZenmoFeiShi/Qx/main/Didichuxing.js
^https?:\/\/d\.psbc\.com:9091\/mcc\/resources\/[0-9]+\.(jpg|png|jpeg) url reject-200
^https?:\/\/cupid\.51job(app)?\.com\/open\/noauth\/recommend\/job-tab-dynamic url script-response-body https://raw.githubusercontent.com/zirawell/Ad-Cleaner/main/Collection/js/51job.js
^https?:\/\/cupid\.51job(app)?\.com\/open\/index\/recommend-infos url reject
^https?:\/\/cube\.elemecdn\.com\/\w\/\w{2}\/\w+mp4\.mp4\? url reject
^https?:\/\/cube\.elemecdn\.com\/[\w\/]+\.jpeg\?x-oss-process=image\/resize,m_fill,w_\d{3},h_\d{4}\/format,webp\/ url reject
^https?:\/\/cube\.elemecdn\.com\/[\w\/]+\.jpeg\?x-oss-process=image\/resize,m_fill,w_6\d{2},h_8\d{2}\/format,webp\/ url reject
^https?:\/\/cube\.elemecdn\.com\/[\w\/]+\.jpeg\?x-oss-process=image\/resize,m_fill,w_1\d{3},h_2\d{3}\/format,webp\/ url reject
^https?:\/\/ct\.xiaojukeji\.com\/agent\/v3\/feeds url script-response-body https://raw.githubusercontent.com/ZenmoFeiShi/Qx/main/Didichuxing.js
^https?:\/\/ct\.xiaojukeji\.com\/agent\/v3\/feeds url reject
^https?:\/\/cstore-en-public-tx\.seewo\.com\/easinote5_public url reject-dict
^https?:\/\/creditcardapp\.bankcomm\.com\/rcg\/index\.html\?callbackurl=rcg\/index\.html&orclogin=1& url script-response-body https://raw.githubusercontent.com/zirawell/Ad-Cleaner/main/Collection/js/mdb.js
^https?:\/\/creditcardapp\.bankcomm\.com\/mapp\/common\/(queryGuidePageAds|getPopAds)\.do$ url reject-200
^https?:\/\/creditcardapp\.bankcomm\.cn\/mappweb_interface\/common\/(qryPopAds|qryLaunchAds)\.do url reject-200
^https?:\/\/creditcardapp\.bankcomm\.(com|cn)\/mappweb_interaction\/appInfo\/appNewestVersion url reject-200
^https?:\/\/creditcard\.bankcomm\.com\/tfimg\/public00\/M00\/4C\/6F url reject-img
^https?:\/\/cover\.baidu\.com\/cover\/page\/dspSwitchAds\/ url reject
^https?:\/\/consumer\.fcbox\.com\/v\d\/ad\/ url reject
^https?:\/\/conf\.diditaxi\.com\.cn\/homepage\/v\d\/other\/fast url script-response-body https://raw.githubusercontent.com/ZenmoFeiShi/Qx/main/Didichuxing.js
^https?:\/\/conf\.diditaxi\.com\.cn\/homepage\/v\d\/core url script-response-body https://raw.githubusercontent.com/ZenmoFeiShi/Qx/main/Didichuxing.js
^https?:\/\/conf\.diditaxi\.com\.cn\/dynamic\/conf url script-response-body https://raw.githubusercontent.com/ZenmoFeiShi/Qx/main/Didichuxing.js
^https?:\/\/conf-darwin\.xycdn\.com url reject-dict
^https?:\/\/compus\.xiaofubao\.com\/compus\/advertising\/getStartupAdvertising url reject-dict
^https?:\/\/compus\.xiaofubao\.com\/compus\/advertising url reject-200
^https?:\/\/common\.diditaxi\.com\.cn\/common\/v\d\/usercenter\/me url script-response-body https://raw.githubusercontent.com/ZenmoFeiShi/Qx/main/Didichuxing.js
^https?:\/\/common\.diditaxi\.com\.cn\/common\/v5 url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/didi/didi.js
^https?:\/\/comment-card\.iqiyi\.com\/views_comment\/3\.0\/long_video_comments\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/comicapi\.manhuashe\.com\/v\d\/(ads\/adstrategys|public\/startupactivity) url reject-200
^https?:\/\/cn-acs\.m\.cainiao\.com\/gw\/mtop\.nbfriend\.message\.conversation\.list\.cn url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cainiao.js
^https?:\/\/cn-acs\.m\.cainiao\.com\/gw\/mtop\.com\.cainiao\.longquan\.place\.getpageresourcecontent\.cn url reject-dict
^https?:\/\/cn-acs\.m\.cainiao\.com\/gw\/mtop\.com\.cainiao\.cncreditmarket\.hit\.getactivityhit\.cn url reject-dict
^https?:\/\/cn-acs\.m\.cainiao\.com\/gw\/mtop\.com\.cainiao\.cnactivitycenter url reject-dict
^https?:\/\/cn-acs\.m\.cainiao\.com\/gw\/mtop\.cainiao\.nbpresentation\.protocol\.homepage\.get\.cn url script-response-body https://raw.githubusercontent.com/ddgksf2013/Scripts/master/cainiao_json.js
^https?:\/\/cn-acs\.m\.cainiao\.com\/gw\/mtop\.cainiao\.nbpresentation\.homepage\.merge\.get\.cn url script-response-body https://raw.githubusercontent.com/ddgksf2013/Scripts/master/cainiao_json.js
^https?:\/\/cn-acs\.m\.cainiao\.com\/gw\/mtop\.cainiao\.nbpresentation\.(pickup\.empty\.page|protocol\.homepage)\.get\.cn url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cainiao.js
^https?:\/\/cn-acs\.m\.cainiao\.com\/gw\/mtop\.cainiao\.nbpresentation\.(homepage\.merge|tabbar\.marketing)\.get\.cn url reject-dict
^https?:\/\/cn-acs\.m\.cainiao\.com\/gw\/mtop\.cainiao\.nbopen\.miniapp\.recommend\.cpc\.cn url reject-dict
^https?:\/\/cn-acs\.m\.cainiao\.com\/gw\/mtop\.cainiao\.nbmensa\.research\.researchservice\.(acquire|event|close)\.cn url reject-dict
^https?:\/\/cn-acs\.m\.cainiao\.com\/gw\/mtop\.cainiao\.guoguo\.nbnetflow\.ads\.m?show\.cn url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cainiao.js
^https?:\/\/cn-acs\.m\.cainiao\.com\/gw\/mtop\.cainiao\.guoguo\.nbnetflow\.ads\.index\.cn url script-response-body https://raw.githubusercontent.com/ddgksf2013/Scripts/master/cainiao_json.js
^https?:\/\/cn-acs\.m\.cainiao\.com\/gw\/mtop\.cainiao\.guoguo\.nbnetflow\.ads\.(show|mshow)\.cn\/ url reject-200
^https?:\/\/cn-acs\.m\.cainiao\.com\/gw\/mtop\.cainiao\.guoguo\.nbnetflow\.ads\.(batch\.show\.v2|index)\.cn url reject-dict
^https?:\/\/cn-acs\.m\.cainiao\.com\/gw\/mtop\.cainiao\.cncommunity\.my\.station\.query\.cn url reject-dict
^https?:\/\/cn-acs\.m\.cainiao\.com\/gw\/mtop\.cainiao\.adkeyword\.get\.cn url reject-dict
^https?:\/\/cn-acs\.m\.cainiao\.com\/gw\/mtop\.cainiao\.adkeyword url script-response-body https://raw.githubusercontent.com/ddgksf2013/Scripts/master/cainiao_json.js
^https?:\/\/cmsfile\.wifi8\.com\/uploads\/png\/ url reject-img
^https?:\/\/cmsapi\.wifi8\.com\/v\d\/(emptyAd|adNew)\/ url reject
^https?:\/\/cms\.daydaycook\.com\.cn\/api\/cms\/advertisement\/ url reject
^https?:\/\/cloud\.189\.cn\/include\/splash\/ url reject
^https?:\/\/client\.tujia\.com\/bnbapp-node\/app\/portal\/getportalconfig\/bnb\/v2 url response-body "banners":\[.+\], response-body "banners":[],
^https?:\/\/client\.tujia\.com\/bnbapp-node\/app\/portal\/getStartPictureAdvertising url reject-200
^https?:\/\/client\.tujia\.com\/bnbapp-node\/app\/(promotion\/popup\/getpopupups\/bnb|portal\/getStartPictureAdvertising) url reject
^https?:\/\/client\.tujia\.com\/bnbapp-node url reject-dict
^https?:\/\/client\.qunar\.com\/pitcher-proxy\?qrt=p_splashAd url reject-200
^https?:\/\/client\.qunar\.com\/pitcher-proxy\?qrt=p_splashAd url reject
^https?:\/\/client\.mail\.163\.com\/apptrack\/confinfo\/searchMultiAds url reject-200
^https?:\/\/client\.mail\.163\.com\/apptrack\/confinfo\/searchMultiAds url reject
^https?:\/\/client\.mail\.163\.com\/apptrack\/confinfo\/(searchMultiAds|showAds) url reject
^https?:\/\/client\.mail\.163.com\/apptrack\/confinfo\/(searchMultiAds.do|showAds.do) url reject-200
^https?:\/\/client\.app\.coc\.10086\.cn\/biz-orange\/DN\/init\/startInit url reject-200
^https?:\/\/client\.app\.coc\.10086\.cn\/biz-orange\/DN\/explorePage\/getAdverList url reject-200
^https?:\/\/client\.app\.coc\.10086\.cn\/biz-orange\/DN\/explorePage\/getAdverList url reject
^https?:\/\/client-api\.oray\.com\/materials\/SLCC_IOS_STARTUP\?lang=zh-Hans-CN url reject-200
^https?:\/\/client-api-v2\.oray\.com\/materials\/SUNLOGIN_CLIENT_IOS_PROMOTION url reject-dict
^https?:\/\/client-api-v2\.oray\.com\/materials\/SLCC_IOS_STARTUP url reject-dict
^https?:\/\/client-api-v2\.oray\.com\/materials\/SLCC_IOS_DEVICE url reject-dict
^https?:\/\/client-api-v2\.oray\.com\/materials\/(SUNLOGIN_CLIENT_IOS_PROMOTION|SLCC_IOS_DEVICE|SLCC_IOS_STARTUP) url reject-200
^https?:\/\/chl\.tf\.cn\/channelmg\/sys\/socso\/socsonew\/queryIsRealNameAdertInfo url reject-dict
^https?:\/\/chl\.tf\.cn\/channelmg\/sys\/socso\/order\/queryOrderInfo url response-body "imgUrl" response-body "imgUrl0"
^https?:\/\/cheyouapi\.ycapp\.yiche\.com\/appforum\/getusermessagecount url reject-img
^https?:\/\/channel\.beitaichufang\.com\/channel\/api\/v\d\/promote\/ios\/start\/page url reject
^https?:\/\/cgbank\.oss-cn-shenzhen\.aliyuncs\.com\/visual\/advertisingImg\/.+.jpg url reject-200
^https?:\/\/cds\.wifi188\.com\/feeds\.sec url reject-dict
^https?:\/\/cdnmobibank\.bankofbeijing\.com\.cn\/cdn\/MarketingCloud\/.+\/.+\/99_1\/.+\.jpg url reject-200
^https?:\/\/cdnfile1\.msstatic\.com\/cdnfile\/appad\/ url reject-img
^https?:\/\/cdn\.wup\.huya\.com\/launch\/queryHttpDns$ url reject
^https?:\/\/cdn\.sdb\.com\.cn\/widget\/pb\/pb-plugins-recomend-content url reject-dict
^https?:\/\/cdn\.sdb\.com\.cn\/widget\/magic-module-sprite\/general-banner url reject-200
^https?:\/\/cdn\.sdb\.com\.cn\/widget\/magic-module-sprite\/dialog-normal url reject-dict
^https?:\/\/cdn\.poizon\.com\/node-common\/.*.jpg url reject-200
^https?:\/\/cdn\.kuaidi100\.com\/images\/open\/appads url reject-img
^https?:\/\/cdn\.jlbank\.com\.cn\/jlstaticresource\/APPSTART url reject-200
^https?:\/\/cdn\.dianshihome\.com\/static\/ad\/ url reject-200
^https?:\/\/cdn\.dianshihome\.com\/static\/ad\/ url reject
^https?:\/\/cdn\.cmgadx\.com\/sdk\/pool\/m8uTS50pt3DC0Xd6\.json url reject-200
^https?:\/\/cdn\.cmgadx\.com\/sdk\/pool\/\w+\.json url reject-200
^https?:\/\/cdn\.cmgadx\.com\/sdk\/pool\/\w+\.json url reject
^https?:\/\/cdn\.\w{3}\.chelaileapp\.cn\/(api\/)?adpub url reject-200
^https?:\/\/cdn\.\w{3}\.chelaileapp\.cn\/(api\/)?adpub url reject
^https?:\/\/cdn\.133\.cn\/md\/gtgj\/.+\/.+720x1280 url reject-dict
^https?:\/\/cdn-xyk-app\.bankofbeijing\.com\.cn\/cdn\/resource\/image\/advertise url reject-200
^https?:\/\/cdn-oss\.00bang\.cn\/image\/LLB_OSSC8A54C9913CA475DABECA1054A219CA2\.jpg url reject-200
^https?:\/\/cdn-oss\.00bang\.cn\/image\/LLB_OSS50140C35669841B7A4218215C8C5338A\.jpg url reject-200
^https?:\/\/cdn-oss\.00bang\.cn\/image\/LLB_OSS32D553B6981546909417BEF3B7A3BC4D\.jpg url reject-200
^https?:\/\/cdn-oss\.00bang\.cn\/image\/LLB_OSS2FC543D52E7447678660A4D9EC4F6C60\.jpg url reject-200
^https?:\/\/cdn-evone-ceph\.echargenet\.com\/gw-emas-cdn\/63c4e3b558bb610008969f89 url reject-200
^https?:\/\/cdn-evone-ceph\.echargenet\.com\/gw-emas-cdn url reject-200
^https?:\/\/cdke\.youdao\.com\/course3\/recommend\/dict\/startup url reject-dict
^https?:\/\/cdke\.youdao\.com\/course3\/recommend\/dict\/startup url reject-200
^https?:\/\/cdb\.meituan\.com\/marketing\/source\/getPageSlotList url reject-dict
^https?:\/\/ccsp-egmas\.sf-express\.com\/cx-app-video\/video\/app\/video\/labelClusterList url reject-dict
^https?:\/\/ccsp-egmas\.sf-express\.com\/cx-app-base\/base\/app\/bms\/queryRecommend url reject-dict
^https?:\/\/ccsp-egmas\.sf-express\.com\/cx-app-base\/base\/app\/appVersion\/detectionUpgrade url reject-200
^https?:\/\/ccsp-egmas\.sf-express\.com\/cx-app-base\/base\/app\/ad\/queryInfoFlow url reject-dict
^https?:\/\/ccmsupport-sz\.tenpay\.com\/cgi-bin\/common\/ccm_page_element.cgi url reject
^https?:\/\/careapi\.oclean\.com\/mall\/v\d\/User\/GetUserCenter url response-body banner" response-body ddgksf2013"
^https?:\/\/careapi\.oclean\.com\/mall\/v\d\/Temporary\/SafetyGetStartAdvert url reject-200
^https?:\/\/cards\.iqiyi\.com\/views_search\/3\.0\/(hot_query_)?search\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/cards\.iqiyi\.com\/views_plt\/3\.0\/player_tabs_v2\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/cards\.iqiyi\.com\/views_category\/3\.0\/(category_home|categorylib_content|film_hybrid)\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/cards\.iqiyi\.com\/(views_home\/3\.0\/qy_home|waterfall\/3\.0\/feed)\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/carapp\.gtmc\.com\.cn\/api\/appgtmc\/homePage\/HomePageAction\/queryHomePageImg\.json url reject-200
^https?:\/\/capis.*didapinche\.com\/ad\/cx\/startup url reject-200
^https?:\/\/capis(-\d)?\.didapinche\.com\/adbase url reject
^https?:\/\/capis(-\d)?\.didapinche\.com\/ad\/ url reject
^https?:\/\/capis(-?\w*)?\.didapinche\.com\/publish\/api\/upgrade url reject-dict
^https?:\/\/capi\.mwee\.cn\/app-api\/V\d{2}\/app\/(ad|getstartad) url reject
^https?:\/\/capi\.lkcoffee\.com\/resource\/m\/sys\/app\/adposNew url reject
^https?:\/\/capi\.lkcoffee\.com\/resource\/m\/sys\/(homePage\/contactor\/modules|app\/adposNew) url reject-200
^https?:\/\/capi\.douyucdn\.cn\/lapi\/sign\/app(api)?\/getinfo\?client_sys=ios url reject
^https?:\/\/capi\.douyucdn\.cn\/api\/v1\/getStartSend?client_sys=ios url reject-img
^https?:\/\/capi\.douyucdn\.cn\/api\/ios_app\/check_update url reject-img
^https?:\/\/capi.mwee.cn\/app-api\/V12\/app\/getstartad url reject-200
^https?:\/\/cap\.caocaokeji\.cn\/advert-bss\/ url reject
^https?:\/\/c\.zhangle\.com\/pic\/mktg\/diversity\/.+\.jpg$ url reject-dict
^https?:\/\/c\.m\.163\.com\/nc\/gl\/ url reject-200
^https?:\/\/c\.m\.163\.com\/nc\/gl\/ url reject
^https?:\/\/business\.msstatic\.com\/advertiser\/material url reject-200
^https?:\/\/business\.msstatic\.com\/advertiser\/material url reject
^https?:\/\/btrace\.qq\.com url reject-200
^https?:\/\/bp-image\.bestv\.com\.cn\/[a-zA-Z0-9]{8}-[a-zA-Z0-9]{4}-[a-zA-Z0-9]{4}-[a-zA-Z0-9]{4}-[a-zA-Z0-9]{25}\.jpg url reject-200
^https?:\/\/bp-api\.bestv\.com\.cn\/cms\/api\/free\/open\/advertisingV2 url reject-200
^https?:\/\/bp-api\.bestv\.com\.cn\/cms\/api\/free\/open\/advertisingV2 url reject
^https?:\/\/bp-api\.bestv\.com\.cn\/cms\/api\/audit\/home\/getCommonMixData url script-response-body https://raw.githubusercontent.com/ddgksf2013/Scripts/master/baishitv.js
^https?:\/\/boot.*weibo\.com\/v\d\/ad\/realtime url reject-200
^https?:\/\/boot.*weibo\.com\/v\d\/ad\/preload url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/weibo_json.js
^https?:\/\/book\.img\.ireader\.com\/group6\/M00 url reject-img
^https?:\/\/bohe\.sfo-tx-shanghai-01\.saas\.sensorsdata\.cn\/api\/v2\/sfo\/user_popup_configs url reject-dict
^https?:\/\/bodianimgcdn\.kuwo\.cn\/images\/198c0b313fe9e53b03240c7b30b4acc9 url reject-dict
^https?:\/\/bodianimgcdn\.kuwo\.cn\/images\/0e83c1821cd2681de08e20bec73d1e75 url reject-dict
^https?:\/\/blog\.nilbt\.com\/static\/api\/update url reject-200
^https?:\/\/bla\.gtimg\.com\/qqlive\/\d{6}.+?\.png url reject-img
^https?:\/\/bid\.adview\.cn\/agent\/getAd url reject
^https?:\/\/bgw\.xinyue\.qq\.com\/xyapi\.PageService\/GetIndexPopFlash url reject-200
^https?:\/\/beta-api\.crunchyroll\.com\/cms url response-body offset_ms":\d+ response-body offset_ms":99999999999999
^https?:\/\/beehiveapi\.58\.com\/adplace\/zcm url reject-dict
^https?:\/\/bd-api\.kuwo\.cn\/api\/service\/finds\/module\?moduleId url reject-dict
^https?:\/\/bd-api\.kuwo\.cn\/api\/service\/banner\/myPage\?uid url reject-dict
^https?:\/\/bd-api\.kuwo\.cn\/api\/play\/listening\/entrance\/music\?musicId url reject-dict
^https?:\/\/bbs-api\.miyoushe\.com\/apihub\/api\/getAppSplash url reject-200
^https?:\/\/baichuan\.baidu\.com\/rs\/adpmobile\/launch url reject-img
^https?:\/\/baichuan\.baidu\.com\/rs\/adpmobile\/launch url reject
^https?:\/\/b\.appsimg\.com\/upload\/momin url reject
^https?:\/\/b2baifanfan\.baidu\.com\/crm\/web\/b2b\/im\/common\/getConfigByDeviceNum url reject-200
^https?:\/\/b-api\.ins\.miaopai\.com\/\d\/ad/ url reject
^https?:\/\/axxd\.xmseeyouyima\.com\/v\d\/getad url reject-200
^https?:\/\/audiobookpay\.kuwo\.cn\/a\.p\?op=get_advertright_endtime url reject-dict
^https?:\/\/audiobookpay\.kuwo\.cn\/a\.p url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/break/kuwo.js
^https?:\/\/atrace\.chelaile\.net\.cn\/exhibit\?&adv_image url reject-img
^https?:\/\/atrace\.chelaile\.net\.cn\/adpub\/ url reject-img
^https?:\/\/atrace.chelaile.net.cn\/exhibit\?&adv_image url reject-200
^https?:\/\/atrace.chelaile.net.cn\/adpub\/ url reject-200
^https?:\/\/assets\.msn\.com\/service\/weather\/locations\/search url reject-dict
^https?:\/\/asp\.cntv\.myalicdn\.com\/.+?\?maxbr=850 url reject-200
^https?:\/\/as\.xiaojukeji\.com\/ep\/as\/conf\?ns=daijia-front&name= url reject-dict
^https?:\/\/article-api\.smzdm\.com\/publish\/get_bubble url script-response-body https://raw.githubusercontent.com/ZenmoFeiShi/Qx/main/Smzdm.js
^https?:\/\/appwk\.baidu\.com\/xpage\/interface\/wknaad url reject-200
^https?:\/\/apps\.workair\.cn\/app\/version url response-body ads" response-body ddgksf2013"
^https?:\/\/apps\.api\.ke\.com\/config\/config\/(bootpage|getactivityconfig) url reject-200
^https?:\/\/apps\.api\.ke\.com\/config\/config\/(bootpage|getactivityconfig) url reject
^https?:\/\/apphw\.ddpai\.com:\d+\/onroad\/api\/v\d\/\w+\/list url reject-dict
^https?:\/\/appgw\.ddpai\.com.*\/ad\/list.* url reject
^https?:\/\/appdmkj\.5idream\.net\/v2\/login\/message\/tip url reject-dict
^https?:\/\/appdmkj\.5idream\.net\/appPic\/homepage url reject-dict
^https?:\/\/appconf\.mail\.163\.com\/mmad\/get\.do url reject-200
^https?:\/\/appconf\.mail\.163\.com\/mmad\/ url reject-200
^https?:\/\/appconf\.mail\.163\.com\/mmad\/ url reject
^https?:\/\/appcloud2\.zhihu\.com\/v\d+\/config url script-analyze-echo-response https://gist.githubusercontent.com/blackmatrix7/f5f780d0f56b319b6ad9848fd080bb18/raw/zheye.min.js
^https?:\/\/appcloud2\.zhihu\.com\/v3\/resource\?group_name=mp url reject-dict
^https?:\/\/appcloud2\.zhihu\.com\/v3\/config url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/zhihu.js
^https?:\/\/appapi\.huazhu\.com:\d{4}\/client\/app\/getAppStartPage\/ url reject-200
^https?:\/\/appapi\.huazhu\.com:\d{4}\/client\/app\/getAppStartPage\/ url reject
^https?:\/\/appapi\.51job(app)?\.com\/api\/market\/(adtrace|get_launch|get_prompt) url reject
^https?:\/\/appactive\.1234567\.com\.cn\/AppoperationApi\/OperationService\/GetAppStartImg url reject-200
^https?:\/\/appactive\.1234567\.com\.cn\/AppoperationApi\/OperationService\/GetAppStartImg url reject
^https?:\/\/app\.zhuanzhuan\.com\/zzx\/transfer\/getConfigInfo url reject-dict
^https?:\/\/app\.zhuanzhuan\.com\/zzx\/transfer\/getConfigInfo url reject-200
^https?:\/\/app\.zhuanzhuan\.com\/zz\/v2\/zzinfoshow\/getchoicegoodsinfos url response-body infoData response-body random_body
^https?:\/\/app\.zhuanzhuan\.com\/zz\/transfer\/userred\?scene=homePage url reject-dict
^https?:\/\/app\.zhuanzhuan\.com\/zz\/transfer\/getmyprofilev3 url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/zhuanzhuan/zhuanzhuan.js
^https?:\/\/app\.zhoudamozi\.com\/ad\/.+ url reject-200
^https?:\/\/app\.yinxiang\.com\/ads\/ url reject-200
^https?:\/\/app\.xinpianchang\.com\/open_screen\? url reject
^https?:\/\/app\.wy\.guahao\.com\/json\/white\/dayquestion\/getpopad url reject
^https?:\/\/app\.variflight\.com\/v\d\/advert\/ url reject
^https?:\/\/app\.variflight\.com\/ad\/ url reject
^https?:\/\/app\.peopleapp\.com\/Api\/\d+/HomeApi\/(adv|getAdvertImage) url reject
^https?:\/\/app\.missevan\.com\/site\/launch\? url reject
^https?:\/\/app\.meruki\.cn\/\?n=Sig\.Front\.AppFront\.GetOpenAdDoorzo url reject-dict
^https?:\/\/app\.ibuscloud\.com\/v\d\/(app\/getSkipAdvert|notice\/getNoticeWithAdvByCity) url reject-200
^https?:\/\/app\.homeinns\.com\/api\/landing url reject-200
^https?:\/\/app\.homeinns\.com\/api\/landing url reject
^https?:\/\/app\.hbooker\.com\/setting\/get_startpage_url_list url reject-200
^https?:\/\/app\.hbooker\.com\/setting\/get_startpage_url_list url reject
^https?:\/\/app\.flymodem\.com\.cn\/Appapi\/Public\/welecome url reject-200
^https?:\/\/app\.dewu\.com\/api\/v1\/app\/advertisement url reject
^https?:\/\/app\.chinahxzq\.com\.cn\/starway\/adShow url reject-dict
^https?:\/\/app\.chinahxzq\.com\.cn:9302\/starway-api\/ad url reject-dict
^https?:\/\/app\.ceair\.com\/customize\/security\/update url reject-200
^https?:\/\/app\.ceair\.com\/customize\/main\/adScreen url reject-dict
^https?:\/\/app\.c\.nf\.migu\.cn\/.*column\/start(-)?up-pic url reject-200
^https?:\/\/app\.bilibili\.com\/x\/v2\/feed\/index url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/bilibili_json.js
^https?:\/\/app\.bilibili\.com\/x\/v2\/account\/myinfo\? url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/bilibili_json.js
^https?:\/\/app\.bilibili\.com\/x\/v2\/account\/mine url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/bilibili_json.js
^https?:\/\/app\.bilibili\.com\/x\/resource\/top\/activity url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/bilibili_json.js
^https?:\/\/app\.bilibili\.com\/x\/resource\/show\/tab url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/bilibili_json.js
^https?:\/\/app\.bilibili\.com\/x\/resource\/ip url reject
^https?:\/\/app\.badmintoncn\.com\/mag\/operative\/v\d\/ad\/listNotEndByPlace\?place=first_page url reject-200
^https?:\/\/app\.api\.versa-ai\.com\/launch\/ads\? url reject-200
^https?:\/\/app\.api\.qjjfin\.com\/publicize\/allList url reject-200
^https?:\/\/app\.api\.d3yuiw4\.com\/api\/app\/ad url reject
^https?:\/\/app\.aa-ab\.com\/home url reject-200
^https?:\/\/app\.95598pay\.com\/debapi\/adsite\/ url reject-200
^https?:\/\/app\.58\.com\/api\/log\/ url reject
^https?:\/\/app\.58\.com\/api\/home\/invite\/popupAdv url reject-200
^https?:\/\/app\.58\.com\/api\/home\/(advertising|appadv)\/ url reject
^https?:\/\/app\.58\.com\/api\/home\/(advertising|appadv) url reject-200
^https?:\/\/app\.10099\.com\.cn\/contact-web\/api\/version\/getFlashScreenPage url reject-200
^https?:\/\/app3\.qdaily\.com\/app\d\/boot_advertisements\.json url reject-200
^https?:\/\/app3\.qdaily\.com\/app3\/boot_advertisements\.json url reject
^https?:\/\/app2\.autoimg\.cn\/apppdfs\/ url reject-img
^https?:\/\/app2.autoimg.cn\/appdfs\/ url reject-200
^https?:\/\/app02\.vgtime\.com:8080\/vgtime-app\/api\/v2\/init\/ad\.json$ url reject-dict
^https?:\/\/app02\.vgtime\.com:8080\/vgtime-app\/api\/v2\/init\/ad\.json url script-response-body https://raw.githubusercontent.com/app2smile/rules/master/js/vgtime.js
^https?:\/\/app-izz\.zhengzhou\.gov\.cn:10019\/bizgw\/gateway\.do url response-body "imgUrl19_5x9":".+?" response-body "imgUrl19_5x9":""
^https?:\/\/app-gw\.csdn\.net\/silkroad-api\/api\/v\d\/assemble\/list\/pub\/channel\/app_open_screen_ad url reject-200
^https?:\/\/app-gw\.csdn\.net\/silkroad-api\/api\/v\d\/assemble\/list\/pub\/channel\/app_open_screen_ad url reject
^https?:\/\/app-gw\.csdn\.net\/abtesting\/v2\/getList? url reject
^https?:\/\/app-gateway\.leisuapi\.com\/v\d\/app\/mobile\/(banners|ads) url reject-200
^https?:\/\/app-cdn\.2q10\.com\/app\/\w+\/honored url reject-200
^https?:\/\/app-api\.smzdm\.com\/util\/update url script-response-body https://raw.githubusercontent.com/ZenmoFeiShi/Qx/main/Smzdm.js
^https?:\/\/app-api\.smzdm\.com\/util\/loading url script-response-body https://raw.githubusercontent.com/ZenmoFeiShi/Qx/main/Smzdm.js
^https?:\/\/app-api\.niu\.com\/v\d\/advertisement\/ url reject
^https?:\/\/app-api\.medsci\.cn\/app-advertisement-space\/showAdList url reject-200
^https?:\/\/apiwz\.midukanshu\.com\/config\/getAds$ url reject
^https?:\/\/apiwz\.midukanshu\.com\/advert\/treasureInfo$ url reject
^https?:\/\/apiwz\.midukanshu\.com\/advert\/getPopup$ url reject
^https?:\/\/apio\.zhengqi100\.com\/forum\/thread\/listsHome url reject-dict
^https?:\/\/apimobile\.meituan\.com\/group\/v1\/recommend\/unity\/recommends url reject
^https?:\/\/apimobile\.meituan\.com\/appupdate\/mach\/checkUpdate? url reject
^https?:\/\/apicloud\.zol\.com\.cn\/Article\/WapLaunchLogo url reject-dict
^https?:\/\/api\d\.tuisong\.baidu\.com url reject-img
^https?:\/\/api\d\.sparke\.cn\/admodel\/list\?adspace=spgg&flag=\d$ url reject
^https?:\/\/api\d\.futunn\.com\/ad\/ url reject
^https?:\/\/api\d?\.musical\.ly\/api\/ad\/ url reject-img
^https?:\/\/api\.zhihu\.com\/v5\.1\/topics\/answer\/\d+\/relation url reject-dict
^https?:\/\/api\.zhihu\.com\/v2\/topstory\/hot-lists\/everyone-seeing\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/zhihu.js
^https?:\/\/api\.zhihu\.com\/user-credit\/basis url script-response-body https://gist.githubusercontent.com/blackmatrix7/f5f780d0f56b319b6ad9848fd080bb18/raw/zheye.min.js
^https?:\/\/api\.zhihu\.com\/unlimited\/go\/my_card url reject
^https?:\/\/api\.zhihu\.com\/topstory\/hot-lists?(\?|\/) url script-response-body https://gist.githubusercontent.com/blackmatrix7/f5f780d0f56b319b6ad9848fd080bb18/raw/zheye.min.js
^https?:\/\/api\.zhihu\.com\/settings\/blocked_users url script-response-body https://gist.githubusercontent.com/blackmatrix7/f5f780d0f56b319b6ad9848fd080bb18/raw/zheye.min.js
^https?:\/\/api\.zhihu\.com\/search\/recommend_query\/v2\? url response-body "recommend_queries":\{.+\} response-body "recommend_queries":{}
^https?:\/\/api\.zhihu\.com\/search\/preset_words\? url script-response-body https://gist.githubusercontent.com/blackmatrix7/f5f780d0f56b319b6ad9848fd080bb18/raw/zheye.min.js
^https?:\/\/api\.zhihu\.com\/search\/preset_words url reject-dict
^https?:\/\/api\.zhihu\.com\/root\/window url reject-dict
^https?:\/\/api\.zhihu\.com\/people\/ url script-response-body https://gist.githubusercontent.com/blackmatrix7/f5f780d0f56b319b6ad9848fd080bb18/raw/zheye.min.js
^https?:\/\/api\.zhihu\.com\/notifications\/v3\/(message|timeline\/entry\/system_message) url script-response-body https://gist.githubusercontent.com/blackmatrix7/f5f780d0f56b319b6ad9848fd080bb18/raw/zheye.min.js
^https?:\/\/api\.zhihu\.com\/next\? url script-response-body https://gist.githubusercontent.com/blackmatrix7/f5f780d0f56b319b6ad9848fd080bb18/raw/zheye.min.js
^https?:\/\/api\.zhihu\.com\/next-(data|bff|render) url script-response-body https://gist.githubusercontent.com/blackmatrix7/f5f780d0f56b319b6ad9848fd080bb18/raw/zheye.min.js
^https?:\/\/api\.zhihu\.com\/next-(bff|data|render)\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/zhihu.js
^https?:\/\/api\.zhihu\.com\/moments_v3\? url script-response-body https://gist.githubusercontent.com/blackmatrix7/f5f780d0f56b319b6ad9848fd080bb18/raw/zheye.min.js
^https?:\/\/api\.zhihu\.com\/moments\/tab_v2 url reject-dict
^https?:\/\/api\.zhihu\.com\/moments\/recent url reject-dict
^https?:\/\/api\.zhihu\.com\/me\/guides url reject-dict
^https?:\/\/api\.zhihu\.com\/feed\/render\/tab\/config url script-analyze-echo-response https://gist.githubusercontent.com/blackmatrix7/f5f780d0f56b319b6ad9848fd080bb18/raw/zheye.min.js
^https?:\/\/api\.zhihu\.com\/feed\/render\/revisit\/tag_config url reject-dict
^https?:\/\/api\.zhihu\.com\/feed\/render\/revisit\/current_reading url reject-dict
^https?:\/\/api\.zhihu\.com\/feed-root\/block url script-analyze-echo-response https://gist.githubusercontent.com/blackmatrix7/f5f780d0f56b319b6ad9848fd080bb18/raw/zheye.min.js
^https?:\/\/api\.zhihu\.com\/distribute\/rhea\/qa_ad_card\/h5\/recommendation\? url reject-dict
^https?:\/\/api\.zhihu\.com\/content-distribution-core\/bubble\/common\/settings url reject-dict
^https?:\/\/api\.zhihu\.com\/commercial_api\/real_time_launch_v2\? url reject-dict
^https?:\/\/api\.zhihu\.com\/commercial_api\/launch_v2\? url reject-dict
^https?:\/\/api\.zhihu\.com\/commercial_api\/banners_v3\/app_topstory_banner url reject-dict
^https?:\/\/api\.zhihu\.com\/commercial_api\/app_float_layer url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/zhihu.js
^https?:\/\/api\.zhihu\.com\/commercial_api\/(banners_v3\/app_topstory_banner|launch_v2|real_time_launch_v2) url reject-dict
^https?:\/\/api\.zhihu\.com\/commercial_api.*launch_v2 url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/zhihu_openads.js
^https?:\/\/api\.zhihu\.com\/comment_v5\/answers\/\d+\/list-headers url reject-dict
^https?:\/\/api\.zhihu\.com\/brand\/question\/\d+/card\? url reject-dict
^https?:\/\/api\.zhihu\.com\/api\/v4\/ecom_data\/config url reject-dict
^https?:\/\/api\.zhihu\.com\/ad-style-service\/request url reject-dict
^https?:\/\/api\.zhihu\.com\/ad-style-service\/request url reject
^https?:\/\/api\.zhihu\.com\/ab\/api\/v1\/products\/zhihu\/platforms\/ios\/config url reject
^https?:\/\/api\.zhihu\.com\/(v4\/)?questions\/\d+\/(feeds|answers)\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/zhihu.js
^https?:\/\/api\.zhihu\.com\/(v4\/)?questions\/\d+ url script-response-body https://gist.githubusercontent.com/blackmatrix7/f5f780d0f56b319b6ad9848fd080bb18/raw/zheye.min.js
^https?:\/\/api\.zhihu\.com\/(notifications\/v\d\/count) url reject-dict
^https?:\/\/api\.zhihu\.com\/(moments_v3|topstory\/recommend(_v2)?) url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/zhihu.js
^https?:\/\/api\.zhihu\.com\/(moments\/lastread|drama\/hot-drama-list) url reject-dict
^https?:\/\/api\.zhihu\.com\/(comment_v5\/)?(answers|comments?|articles|pins)\/\d+\/(root_|child_)?comments? url script-response-body https://gist.githubusercontent.com/blackmatrix7/f5f780d0f56b319b6ad9848fd080bb18/raw/zheye.min.js
^https?:\/\/api\.ys7\.com\/api\/ads url reject-200
^https?:\/\/api\.yonghuivip\.com\/web\/shensuan\/ad\/getAd url reject-200
^https?:\/\/api\.yikaobang\.com\.cn\/index\.php\/version\/version\/check url reject
^https?:\/\/api\.yikaobang\.com\.cn\/index\.php\/Client\/main\/startPage url reject-200
^https?:\/\/api\.yikaobang\.com\.cn\/index\.php\/Client\/main\/startPage url reject
^https?:\/\/api\.yikaobang\.com\.cn\/client\/main\/homePageSmallAd url reject-200
^https?:\/\/api\.yikaobang\.com\.cn\/client\/main\/homePageSmallAd url reject
^https?:\/\/api\.ycapp\.yiche\.com\/yicheapp\/getadlist url reject-img
^https?:\/\/api\.ycapp\.yiche\.com\/appnews\/getadlist url reject-img
^https?:\/\/api\.xueqiu\.com\/snowpard\/launch_strategy\/query\.json\? url reject-dict
^https?:\/\/api\.xueqiu\.com\/snowpard\/launch_strategy\/query\.json url reject-200
^https?:\/\/api\.xueqiu\.com\/brand\/search\/v1\.json\? url reject
^https?:\/\/api\.xiachufang\.com\/v\d\/ad/ url reject
^https?:\/\/api\.xbxxhz\.com\/big_data\/v1\/home_pages url reject
^https?:\/\/api\.wmpvp\.com\/api\/v\d\/config\/promote url reject-200
^https?:\/\/api\.wmpvp\.com\/api\/v\d\/config\/promote url reject
^https?:\/\/api\.winbull8\.com\/v1\/marketing\/(advert|activity)\/(list|page) url reject-dict
^https?:\/\/api\.wfdata\.club\/v\d\/yesfeng\/(infoCenterAd|yesList) url reject
^https?:\/\/api\.wfdata\.club\/v2\/yesfeng\/(infoCenterAd|yesList) url reject-200
^https?:\/\/api\.weibo\.cn\/\d\/video\/tiny_stream_mid_detail url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/weibo_json.js
^https?:\/\/api\.weibo\.cn\/\d\/profile\/recommend_popuser url reject-dict
^https?:\/\/api\.weibo\.cn\/\d\/groups\/allgroups\/v\d url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/weibo_json.js
^https?:\/\/api\.weibo\.cn\/\d\/cardlist\?v_f=.*Weibo_intl url reject-dict
^https?:\/\/api\.weibo\.cn\/\d\/ad\/preload url reject-dict
^https?:\/\/api\.weibo\.cn\/\d\/\w{5}\/(statuses_unread_hot_timeline|timeline) url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/weibo_json.js
^https?:\/\/api\.weibo\.cn\/\d\/!\/huati\/discovery_home_bottom_getdotinfo url reject-dict
^https?:\/\/api\.wallstreetcn\.com\/apiv\d\/advertising\/ url reject
^https?:\/\/api\.vistopia\.com\.cn\/api\/v\d\/home\/advertisement url reject
^https?:\/\/api\.ulife\.group\/signintask\/adServing url reject-dict
^https?:\/\/api\.ulife\.group\/market\/memberCard\/listMemberCard\?isShowSecondaryCard=1 url reject-dict
^https?:\/\/api\.ulife\.group\/market\/frontEntrance\/getThirdAdvertising\?displayPort=1&type=15 url reject-dict
^https?:\/\/api\.ulife\.group\/auth\/account\/getUpgradeStrategy url reject-dict
^https?:\/\/api\.ulife\.group\/auth\/account\/entrance url reject-dict
^https?:\/\/api\.u51\.com\/liabilitygateway\/api\/v\d\/homepage\/liabilityline url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/51card.js
^https?:\/\/api\.u51\.com\/generic-config-gateway\/api\/v\d\/guanjia\/me-tab2\/config url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/51card.js
^https?:\/\/api\.u51\.com\/(generic-config-gateway|rs-resys)\/api\/v\d\/(creditpage-config|recommend) url reject-200
^https?:\/\/api\.touker\.com\/v2\/IAdvertisementAPI\.queryStartAdvertisement url reject-200
^https?:\/\/api\.tipsoon\.com\/api\/v\d\/top\/ad url reject-200
^https?:\/\/api\.tipsoon\.com\/api\/v1\/top\/ad url reject-img
^https?:\/\/api\.taptapdada\.com\/startup-logo\/v\d\/combo\? url reject-dict
^https?:\/\/api\.taou\.com\/sdk\/global\/splash_ad url reject-200
^https?:\/\/api\.taou\.com\/sdk\/global\/splash_ad url reject
^https?:\/\/api\.sogaha\.cn\/ssp\/ad\/get\?ip url reject-dict
^https?:\/\/api\.sodalife\.xyz\/v1\/posters\?location=SODA_APP%3AREWARDS%3ACENTER url reject-dict
^https?:\/\/api\.sodalife\.xyz\/v1\/posters\?location=SODA_APP%3AMINE%3ABOTTOM url reject-dict
^https?:\/\/api\.sodalife\.xyz\/v1\/posters\?location=SODA_APP%3AHOME%3ATOP url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/soda.js
^https?:\/\/api\.sodalife\.xyz\/v1\/posters\?location=SODA_APP%3AHOME%3ACENTER url reject-dict
^https?:\/\/api\.sodalife\.xyz\/v1\/posters\?location=SODA_APP%3AHOME%3ABOTTOM url reject-dict
^https?:\/\/api\.sodalife\.xyz\/v1\/goods url reject-dict
^https?:\/\/api\.shenyin\.name\/stay-fork\/browse\/featured$ url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/stay.js
^https?:\/\/api\.shanghaionstar\.com\/sos\/contentinfo\/v1\/public\/landingpage url reject-dict
^https?:\/\/api\.sfacg\.com\/ioscfg url reject
^https?:\/\/api\.rr\.tv\/v3plus\/index\/channel\?pageNum=1&position=CHANNEL_MY url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/rrtv_json.js
^https?:\/\/api\.rr\.tv\/user\/privilege\/list url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/rrtv_json.js
^https?:\/\/api\.rr\.tv\/drama\/app\/get_combined_drama_detail url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/rrtv_json.js
^https?:\/\/api\.rr\.tv\/app\/config\/h5NativeBar url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/rrtv_json.js
^https?:\/\/api\.rr\.tv\/ad\/getAll url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/rrtv_json.js
^https?:\/\/api\.rr\.tv\/\w{3}\/level\/info url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/rrtv_json.js
^https?:\/\/api\.rr\.tv\/.*?Version url reject
^https?:\/\/api\.qbb6\.com\/ad\/ url reject
^https?:\/\/api\.pinduoduo\.com\/api\/ktt_gateway\/activity\/feeds\/personal_home_page\/ url reject
^https?:\/\/api\.petkit\.cn\/6\/\/device\/relatedProductsInfo url reject-dict
^https?:\/\/api\.nj\.nbtv\.cn\/v\d\/common\/system-boot-inform\/detail url reject-200
^https?:\/\/api\.nj\.nbtv\.cn\/v2\/advertise\/advertise-r1\/get-list\?data=u8obKDIrIWt2NR9wBuMwQ5O61eEsP url reject-200
^https?:\/\/api\.ncarzone\.com\/superapi\/canary\/popupDialogFacade\/popupDialogList url reject-200
^https?:\/\/api\.ncarzone\.com\/superapi\/canary\/bannerFacade\/app\/list url reject-200
^https?:\/\/api\.ncarzone\.com\/superapi\/canary\/appHomeFacade\/getNewUserPlateActivity url reject-200
^https?:\/\/api\.msn\.com\/weather url reject-dict
^https?:\/\/api\.mgzf\.com\/renter-operation\/home\/startHomePage url reject
^https?:\/\/api\.merach\.com\/app\/AppAdvertisingController\/getAdvert url reject-200
^https?:\/\/api\.mcd\.cn\/bff\/portal\/home\/splash url reject-200
^https?:\/\/api\.mcd\.cn\/bff\/portal\/(richpop|home\/splash) url reject-200
^https?:\/\/api\.m\.mi\.com\/v\d\/app\/start url reject-200
^https?:\/\/api\.m\.mi\.com\/v1\/app\/start url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/weibo.js
^https?:\/\/api\.m\.mi\.com\/v1\/app\/start url reject-200
^https?:\/\/api\.m\.jd\.com\/client\.action\?functionId=start url reject-img
^https?:\/\/api\.m\.jd\.com\/client\.action\?functionId=lite_advertising url response-body jdLiteAdvertisingVO response-body random_body
^https?:\/\/api\.m\.jd\.com\/client\.action\?functionId=lite_advertising url response-body jdLiteAdvertisingVO response-body ddgksf2013
^https?:\/\/api\.m\.jd\.com\/client\.action\?functionId=lite_advertising url reject
^https?:\/\/api\.m\.jd\.com\/client\.action\?functionId=lite_SmartPush url response-body pushData response-body random_body
^https?:\/\/api\.m\.jd\.com\/client\.action\?functionId=lite_SmartPush url response-body pushData response-body ddgksf2013
^https?:\/\/api\.m\.jd\.com\/client\.action\?functionId=home_launchConfig url reject-200
^https?:\/\/api\.m\.jd\.com\/client\.action\?functionId=getWidgetV1052 url reject
^https?:\/\/api\.m\.jd\.com\/client\.action\?functionId=(start|queryMaterialAdverts) url reject-200
^https?:\/\/api\.m\.jd\.com\/client\.action\?functionId=(server|basic)Config url response-body "dnsvip"\:".+" response-body "dnsvip":""
^https?:\/\/api\.m\.jd\.com\/client\.action\?functionId=(hotWords|hotSearchTerms) url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/jd_json.js
^https?:\/\/api\.m\.jd\.com\/client\.action\?functionId=(deliverLayer|getTabHomeInfo|myOrderInfo|orderTrackBusiness|personinfoBusiness|start|welcomeHome) url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/myBlockAds.js
^https?:\/\/api\.m\.jd\.com\/api\?functionId=delivery_show url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/jingxiAd.js
^https?:\/\/api\.m\.jd\.com\/api\?functionId=delivery_show url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/startup.js
^https?:\/\/api\.live\.bilibili\.com\/xlive\/e-commerce-interface\/v\d\/ecommerce-user\/get_shopping_info\? url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/bilibili_json.js
^https?:\/\/api\.live\.bilibili\.com\/xlive\/app-room\/v1\/index\/getInfoByRoom url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/bilibili_json.js
^https?:\/\/api\.live\.bilibili\.com\/xlive\/app-interface\/v2\/index\/feed url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/bilibili_json.js
^https?:\/\/api\.laifeng\.com\/v\d\/start\/ads url reject
^https?:\/\/api\.kmovie\.gifshow\.com\/rest\/n\/kmovie\/app\/(resource|banner) url reject-200
^https?:\/\/api\.kkmh\.com\/v\d\/advertisement\/ url reject-200
^https?:\/\/api\.kkmh\.com\/v\d\/ad\/show url reject-200
^https?:\/\/api\.k\.sohu\.com\/api\/news\/adsense url reject-200
^https?:\/\/api\.k\.sohu\.com\/api\/channel\/ad\/ url reject-img
^https?:\/\/api\.jxedt\.com\/jump\/EMiCcDNp url reject-img
^https?:\/\/api\.jxedt\.com\/ad\/ url reject-200
^https?:\/\/api\.jxedt\.com\/ad\/ url reject
^https?:\/\/api\.jr\.mi\.com\/v\d\/adv\/ url reject-200
^https?:\/\/api\.jr\.mi\.com\/jr\/api\/playScreen url reject-200
^https?:\/\/api\.izuiyou\.com\/ad\/ url reject-200
^https?:\/\/api\.izuiyou\.com\/ad\/ url reject
^https?:\/\/api\.internetofcity\.cn\/api\/resource\/anon\/popups\/(getSplashList|getList) url reject-200
^https?:\/\/api\.internetofcity\.cn\/api\/resource\/anon\/popups\/(getSplashList|getList) url reject
^https?:\/\/api\.indeedpower\.com\/v1\/m\/edu\/module\/homepage_banner\/\?randomStr url reject-dict
^https?:\/\/api\.huomao\.com\/channels\/loginAd url reject
^https?:\/\/api\.htp\.ad-scope\.com\.cn.* url reject
^https?:\/\/api\.hengdianfilm\.com\/\/cinema\/queryAvailableBannerInfo\/4\?cid= url reject-dict
^https?:\/\/api\.hengdianfilm\.com\/\/cinema\/queryAvailableBannerInfo\/2\?cid= url reject-dict
^https?:\/\/api\.hengdianfilm\.com\/\/cinema\/queryAvailableBannerInfo\/1 url 302 https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/hengdian.json
^https?:\/\/api\.haohaozhu\.cn\/index\.php\/home\/AppInit\/getStartPhoto url reject-200
^https?:\/\/api\.haohaozhu\.cn\/index\.php\/home\/AppInit\/getStartPhoto url reject
^https?:\/\/api\.hanju\.koudaibaobao\.com\/api\/carp\/kp\? url reject
^https?:\/\/api\.gotokeep\.com\/twins\/v4\/feed\/course url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/keepStyle.js
^https?:\/\/api\.gotokeep\.com\/training\/box\/config url reject-200
^https?:\/\/api\.gotokeep\.com\/training\/box\/config url reject
^https?:\/\/api\.gotokeep\.com\/sportpage\/sport\/v\d\/mysport url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/keep.js
^https?:\/\/api\.gotokeep\.com\/search\/v\d\/hotword\/list url reject-200
^https?:\/\/api\.gotokeep\.com\/search\/v\d\/hotword\/list url reject
^https?:\/\/api\.gotokeep\.com\/search\/v\d\/hotCourse\/list url reject-200
^https?:\/\/api\.gotokeep\.com\/search\/v\d\/hotCourse\/list url reject
^https?:\/\/api\.gotokeep\.com\/search\/v\d\/default\/keyword\/list url reject-200
^https?:\/\/api\.gotokeep\.com\/search\/v\d\/default\/keyword\/list url reject
^https?:\/\/api\.gotokeep\.com\/running\/v\d\/home\/dialog url reject-200
^https?:\/\/api\.gotokeep\.com\/op-engine-webapp\/v\d\/ad url reject-200
^https?:\/\/api\.gotokeep\.com\/op-engine-webapp\/v\d\/ad url reject
^https?:\/\/api\.gotokeep\.com\/nuocha\/course\/v\d/\w+\/preview url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/keep.js
^https?:\/\/api\.gotokeep\.com\/kprime\/v\d\/popups\/primeGuide url reject-200
^https?:\/\/api\.gotokeep\.com\/kprime\/v\d\/popups\/primeGuide url reject
^https?:\/\/api\.gotokeep\.com\/homepage\/v\d\/tab url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/keep.js
^https?:\/\/api\.gotokeep\.com\/guide-webapp\/v\d\/popup\/getPopUp url reject-200
^https?:\/\/api\.gotokeep\.com\/guide-webapp\/v\d\/popup\/getPopUp url reject
^https?:\/\/api\.gotokeep\.com\/config\/v\d\/basic url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/keep.js
^https?:\/\/api\.gotokeep\.com\/config\/v\d\/basic url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/keepStyle.js
^https?:\/\/api\.gotokeep\.com\/athena\/v\d\/people\/my$ url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/keep.js
^https?:\/\/api\.gotokeep\.com\/athena\/v\d\/people\/my$ url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/keepStyle.js
^https?:\/\/api\.gotokeep\.com\/anno\/v\d\/upgrade\/check url reject-200
^https?:\/\/api\.gotokeep\.com\/anno\/v\d\/upgrade\/check url reject
^https?:\/\/api\.gotokeep\.com\/ads\/v\d\/ads\/preload url reject-200
^https?:\/\/api\.gotokeep\.com\/ads\/v\d\/ads\/preload url reject
^https?:\/\/api\.gaoqingdianshi\.com\/api\/v\d\/ad\/ url reject-200
^https?:\/\/api\.gaoqingdianshi\.com\/api\/v\d\/ad\/ url reject
^https?:\/\/api\.gamer\.com\.tw\/mobile_app\/anime\/v\d\/anime_get_question\.php url reject-dict
^https?:\/\/api\.gamer\.com\.tw\/mobile_app\/anime\/v\d/(token|m3u8).php\? url script-response-body https://raw.githubusercontent.com/NobyDa/Script/master/Bahamut/BahamutAnimeAds.js
^https?:\/\/api\.gameplus\.qq\.com\/community\.OnloadSrv\/GetPreloadScreenInfo url reject-200
^https?:\/\/api\.futunn\.com\/v\d\/ad\/ url reject
^https?:\/\/api\.futunn\.com\/v2\/optimus\/my-homepage-config url reject-dict
^https?:\/\/api\.futunn\.com\/v2\/config\/promote-config url reject-dict
^https?:\/\/api\.futunn\.com\/treasure-chest\/box-data url reject
^https?:\/\/api\.fengshows\.com\/api\/launchAD url reject-img
^https?:\/\/api\.douban\.com\/v\d\/app_ads\/ url reject-dict
^https?:\/\/api\.douban\.com\/v2\/app_ads\/splash url reject-200
^https?:\/\/api\.douban\.com\/b.*\/common_ads\?.* url reject-dict
^https?:\/\/api\.douban\.com\/b.*\/common_ads\?.* url reject-200
^https?:\/\/api\.daydaycook\.com\.cn\/daydaycook\/server\/ad\/ url reject
^https?:\/\/api\.dangdang\.com\/mapi\d\/mobile\/init url reject-200
^https?:\/\/api\.dangdang\.com\/mapi\d\/mobile\/init url reject
^https?:\/\/api\.coolapk\.com\/v6\/search\?.*type=hotSearch url reject-dict
^https?:\/\/api\.coolapk\.com\/v6\/page\/dataList\? url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/coolapk.js
^https?:\/\/api\.coolapk\.com\/v6\/main\/(dataList|indexV8|init) url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/coolapk.js
^https?:\/\/api\.coolapk\.com\/v6\/feed\/(detail|replyList)\? url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/coolapk.js
^https?:\/\/api\.coolapk\.com\/v6\/(feed\/(replyList|detail)|main\/indexV8|dataList) url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/coolapk.js
^https?:\/\/api\.club\.lenovo\.cn\/common\/open_ad url reject
^https?:\/\/api\.cloud\.189\.cn\/guns\/getOpenscreenBanners url reject-200
^https?:\/\/api\.cloud\.189\.cn\/guns\/(img\/recommendedPosition|getOpenscreenBanners) url reject-dict
^https?:\/\/api\.chelaile\.net\.cn\/goocity\/advert\/ url reject
^https?:\/\/api\.caiyunapp\.com\/v1\/activity url reject-dict
^https?:\/\/api\.caijingmobile\.com\/(ad|advert)\/ url reject-200
^https?:\/\/api\.caijingmobile\.com\/(ad|advert)\/ url reject
^https?:\/\/api\.bwton\.com\/bff\/app\/index\/recommend url reject-dict
^https?:\/\/api\.bwton\.com\/bff\/app\/index\/goods url reject-dict
^https?:\/\/api\.bwton\.com\/bff\/app\/h5\/v1\/station\/goods url reject-dict
^https?:\/\/api\.bwton\.com\/bas\/ad url reject-200
^https?:\/\/api\.boohee\.com\/shop-interface\/api\/v1\/home\/index url reject-dict
^https?:\/\/api\.boohee\.com\/meta-interface\/v1\/index\/record_index url response-body articles response-body random_body
^https?:\/\/api\.boohee\.com\/meta-interface\/v1\/index\/(discover_chosen|page_float_bubbles) url reject-dict
^https?:\/\/api\.boohee\.com\/app-interface\/v1\/record\/record_tool(_pop)?_ad url reject-dict
^https?:\/\/api\.blibee\.com\/cvsnotify-api\/cvs\/notify\/app\/banner\/v\d+$ url reject-200
^https?:\/\/api\.bjxkhc\.com\/index\.php\/app\/ios\/ver/index_ios$ url reject
^https?:\/\/api\.bjxkhc\.com\/index\.php\/app\/ios\/pay/ok$ url reject-dict
^https?:\/\/api\.bjxkhc\.com\/index\.php\/app\/ios\/ads\/ url reject
^https?:\/\/api\.bilibili\.com\/x\/vip\/ads\/material\/report url reject-dict
^https?:\/\/api\.bilibili\.com\/pgc\/season\/player\/ogv\/cards url reject-dict
^https?:\/\/api\.bilibili\.com\/pgc\/activity\/deliver\/material\/receive url reject-dict
^https?:\/\/api\.bili(api|bili)\.(net|com)\/pgc\/season\/app\/related\/recommend\? url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/bilibili_json.js
^https?:\/\/api\.ahmobile\.cn:443\/eip\?eip_serv_id=app\.getAllNew url reject-200
^https?:\/\/api\.ahmobile\.cn:443\/eip\?eip_serv_id=app\.getAllNew url reject
^https?:\/\/api\.21jingji\.com\/ad\/ url reject
^https?:\/\/api\.21ec74\.com\/v2\.5\/ad url reject-200
^https?:\/\/api\.21ec74\.com\/v2\.5\/ad url reject
^https?:\/\/api\.17kjs\.com\/meta\/ads_targets url reject
^https?:\/\/api\.00bang\.cn\/llb\/baseinfo\/advertise\/getAdvertiseByPageCode url reject-200
^https?:\/\/api\.(pinduoduo|yangkeduo)\.com\/api\/cappuccino\/splash url reject-200
^https?:\/\/api\.(pinduoduo|yangkeduo)\.com\/api\/cappuccino\/splash url reject
^https?:\/\/api\.(bilibili|biliapi)\.(com|net)\/pgc\/page\/cinema\/tab\? url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/bilibili_json.js
^https?:\/\/api\.(bilibili|biliapi)\.(com|net)\/pgc\/page\/bangumi url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/bilibili_json.js
^https?:\/\/api\-cfg\.wtzw\.com\/v1\/(adv|reward|operation) url reject
^https?:\/\/api4\.bybutter\.com\/v\d\/app\/placements\/\d\/advertisements url reject-200
^https?:\/\/api4\.bybutter\.com\/v\d\/app\/placements\/\d\/advertisements url reject
^https?:\/\/api3\.cls\.cn\/v1\/boot\/ad url reject-200
^https?:\/\/api3\.cls\.cn\/v1\/boot\/ad url reject
^https?:\/\/api2\.helper\.qq\.com\/game\/buttons url reject-img
^https?:\/\/api1\.34580\.com\/wx\/Home\/AdvertisementPhotoshootRequest url reject-200
^https?:\/\/api.xueqiu.com\/ucprofile\/api\/user\/batchGetUserBasicInfo.json url reject-dict
^https?:\/\/api.psy-1.com\/cosleep\/startup url reject-200
^https?:\/\/api.psy-1.com\/cosleep\/startup url reject
^https?:\/\/api.kkmh.com\/v\d\/(ad|advertisement)\/ url reject-200
^https?:\/\/api.juxingclub.com\/v3plus\/index\/channel\?pageNum=1&position=CHANNEL_MY url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/rrtv_json.js
^https?:\/\/api.juxingclub.com\/app\/config\/h5NativeBar url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/rrtv_json.js
^https?:\/\/api.gotokeep.com/cauchy/growth/init url reject-200
^https?:\/\/api.gotokeep.com/cauchy/growth/init url reject
^https?:\/\/api.coolapk.com\/v6\/main\/init url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/coolapk.js
^https?:\/\/api.coolapk.com\/v6\/main\/indexV8 url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/coolapk.js
^https?:\/\/api.coolapk.com\/v6\/feed\/replyList url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/coolapk.js
^https?:\/\/api.coolapk.com\/v6\/feed\/detail url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/coolapk.js
^https?:\/\/api.coolapk.com\/v6\/dataList url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/coolapk.js
^https?:\/\/api.chelaile.net.cn\/goocity\/advert\/ url reject-200
^https?:\/\/api.chelaile.net.cn\/adpub\/ url reject-200
^https?:\/\/api-wanda\.liepin\.com\/api\/com\.liepin\.cbp\.baizhong\.op\.v2-show-4app url reject-200
^https?:\/\/api-user\.soulapp\.cn\/furion\/position\/content url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/soul/soul_ads.js
^https?:\/\/api-shoulei-ssl\.xunlei\.com\/flowhub\/v\d\/slots:batchGet url reject-200
^https?:\/\/api-sams\.walmartmobile\.cn\/api\/v\d\/sams\/trade\/order\/getOftenBuyGoods url reject-dict
^https?:\/\/api-sams\.walmartmobile\.cn\/api\/v\d\/sams\/sams-user\/(window\/getGoUpPlus|screen_promotion\/get) url reject
^https?:\/\/api-sams\.walmartmobile\.cn\/api\/v\d\/sams\/goods-portal\/spu\/searchRecommendPool url reject-dict
^https?:\/\/api-sams\.walmartmobile\.cn\/api\/v\d\/sams\/configuration\/personCenterEntrance\/query url reject-dict
^https?:\/\/api-sams\.walmartmobile\.cn\/api\/v\d\/sams\/configuration\/appVersionUpdate\/getAppVersionUpdateInfo url reject-dict
^https?:\/\/api-sams\.walmartmobile\.cn\/api\/v\d\/sams\/channel\/portal\/AdgroupData url reject-dict
^https?:\/\/api-sams\.walmartmobile\.cn\/api\/v1\/sams\/sams-user\/(window\/getGoUpPlus|screen_promotion\/get) url reject-200
^https?:\/\/api-release\.wuta-cam\.com\/ad_tree url reject-200
^https?:\/\/api-pay\.soulapp\.cn\/vip\/meet\/userInfo url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/soul/soul_ads.js
^https?:\/\/api-pay\.soulapp\.cn\/privilege\/supervip\/status url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/soul/soul_ads.js
^https?:\/\/api-overmind\.youdao\.com\/openapi\/get\/luna\/dict\/dict-mobile\/prod\/dictCommonConfig url reject-dict
^https?:\/\/api-one-wscn\.awtmt\.com\/apiv\d\/advertising\/ads url reject-200
^https?:\/\/api-one-wscn\.awtmt\.com\/apiv1\/advertising\/ads\/13424\/materials url reject-dict
^https?:\/\/api-new\.app\.acfun\.cn\/rest\/app\/flash\/screen\/ url reject-200
^https?:\/\/api-new\.app\.acfun\.cn\/rest\/app\/flash\/screen\/ url reject
^https?:\/\/api-miprint\.hannto\.com\/v1\/c\/res\/app\/ad\/\?app_version url reject-dict
^https?:\/\/api-mifit\.huami\.com\/discovery\/mi\/discovery\/training_video_ad\? url reject-img
^https?:\/\/api-mifit\.huami\.com\/discovery\/mi\/discovery\/step_detail_ad\? url reject-img
^https?:\/\/api-mifit\.huami\.com\/discovery\/mi\/discovery\/sport_training_ad\? url reject-img
^https?:\/\/api-mifit\.huami\.com\/discovery\/mi\/discovery\/sport_summary_ad\? url reject-img
^https?:\/\/api-mifit\.huami\.com\/discovery\/mi\/discovery\/sleep_ad\? url reject-img
^https?:\/\/api-mifit\.huami\.com\/discovery\/mi\/discovery\/homepage_ad\? url reject-img
^https?:\/\/api-mifit.+?\.huami\.com\/discovery\/mi\/discovery\/.+?_ad\? url reject-200
^https?:\/\/api-mifit-cn2\.huami\.com\/discovery\/mi\/cards\/startpage_ad url reject
^https?:\/\/api-marketing\.zhinengxiyifang\.cn\/api\/v2\/cloudcode\/wechat\/bid url reject
^https?:\/\/api-cslp-emt\.amazon\.cn\/gateway\/recommend url reject-dict
^https?:\/\/api-cslp-emt\.amazon\.cn\/gateway\/content\/widget\/popup url reject-200
^https?:\/\/api-chat\.soulapp\.cn\/chat\/limitInfo url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/soul/soul_ads.js
^https?:\/\/api-ad-product\.huxiu\.com\/Api\/Product\/SDK\/Advert\/Query\/queryAdvertListInfo url reject
^https?:\/\/api-account\.soulapp\.cn\/teenager\/config url reject-dict
^https?:\/\/api-access\.pangolin-sdk-toutiao\.com\/api\/ad\/.+ url reject
^https?:\/\/api-access\.pangolin-sdk-toutiao-b\.com\/api\/ad\/union\/sdk\/get_ads url reject
^https?:\/\/api-access\.(pangolin-sdk-toutiao|pangolin-sdk-toutiao1)\.com\/api\/ad url reject
^https?:\/\/api-ac\.liepin\.com\/api\/com\.liepin\.cyclops\.live\.get-ad-cards url reject-dict
^https?:\/\/api-a\.soulapp\.cn\/v2\/post\/gift\/list url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/soul/soul_ads.js
^https?:\/\/api-a\.soulapp\.cn\/official\/scene\/module url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/soul/soul_ads.js
^https?:\/\/apd-vlive\.apdcdn\.tc\.qq\.com\/vmind\.qqvideo\.tc\.qq\.com\/\w+ url reject
^https?:\/\/apd-\w+\.v\.smtcdns\.com\/(defaultts|omts|vmind\.qqvideo)\.tc\.qq\.com\/\w+ url reject
^https?:\/\/apapia-sqk\.manmanbuy\.com\/index_json\.ashx url response-body splashAD response-body ddgksf2013
^https?:\/\/ap\.dongqiudi\.com\/plat\/v4 url echo-response text/json echo-response https://raw.githubusercontent.com/ddgksf2013/Scripts/master/dongqiudi.js
^https?:\/\/ap\.dongqiudi\.com\/plat\/v url reject
^https?:\/\/ams-cdn\.cdtft\.cn\/prod\/tft-ams\/ url reject-dict
^https?:\/\/amdc\.m\.taobao\.com\/amdc\/mobileDispatch$ url script-response-header https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/header.js
^https?:\/\/alt-r\.my\.com\/mobile url reject-dict
^https?:\/\/als\.baidu\.com\/clog\/clog url reject
^https?:\/\/aimg\.babytreeimg\.com\/group1\/M00\/*\/*\/.*.jpg url reject-200
^https?:\/\/agn\.aty\.sohu\.com\/m? url reject-img
^https?:\/\/agent-count\.pconline\.com\.cn\/counter\/adAnalyse\/ url reject
^https?:\/\/afd\.baidu\.com\/afd\/entry url reject-img
^https?:\/\/afd\.baidu\.com\/afd\/entry url reject
^https?:\/\/aes\.acfun\.cn\/s\?adzones url reject
^https?:\/\/adx.*anythinktech\.com\/bid url reject-200
^https?:\/\/adx-cn\.anythinktech\.com\/bid url reject-dict
^https?:\/\/adx-cn\.anythinktech\.com\/bid url reject-200
^https?:\/\/adv\.ccb\.com\/ebda\/ctm_adv url reject-200
^https?:\/\/adstatic\.peopleapp\.com\/upload\/AppLoad\/.*.(jpg|png) url reject-200
^https?:\/\/adsoss\.zhinengxiyifang\.cn\/ads url reject
^https?:\/\/adservice\.sigmob\.cn\/extconfig url response-body false response-body true
^https?:\/\/ads\.zhinengxiyifang\.cn\/api\/v1\.1\/ads\/* url reject-200
^https?:\/\/ads\.iconntech\.com\/resource-delivery\/*\/.*.(jpg|png) url reject-200
^https?:\/\/ads\.closeli\.cn\/ url reject-200
^https?:\/\/adproxy\.autohome\.com\.cn\/AdvertiseService\/ url reject-img
^https?:\/\/adproxy.autohome.com.cn\/AdvertiseService\/ url reject-200
^https?:\/\/adpai\.thepaper\.cn\/.+&ad= url reject-200
^https?:\/\/adpai\.thepaper\.cn\/.+&ad= url reject
^https?:\/\/adm\.10jqka\.com\.cn\/interface\/ad\/recommend url reject-200
^https?:\/\/adapi\.izuiyou\.com\/ad\/fetch_api_ads\? url reject-dict
^https?:\/\/adapi\.izuiyou\.com\/ url reject-200
^https?:\/\/adapi\.izuiyou\.com\/ url reject
^https?:\/\/ad\.ysepay\.com\/yst-ad\/ST101001\/[0-9]{11}\.jpg url reject
^https?:\/\/ad\.xiaotucc\.com\/advert url reject
^https?:\/\/ad\.shunchangzhixing\.com\/getAd url reject-dict
^https?:\/\/ad\.mcloud\.139\.com\/advertapi\/adv-filter\/adv-filter\/AdInfoFilter\/getAdInfos$ url reject-200
^https?:\/\/ad\.mcloud\.139\.com\/advertapi\/adv-filter\/adv-filter\/AdInfoFilter\/getAdInfos url reject-dict
^https?:\/\/ad\.lofter\.com\/.*yitou\/madr url reject-200
^https?:\/\/ad\.lofter.com\/v1\.1\/yitou\/madr url reject-200
^https?:\/\/ad\.life\.360\.cn\/v2\/app\/advertisement\/config\?sdk_ver= url reject-dict
^https?:\/\/ad\.cj\.sina\.cn\/(osa\/adpreload|fax\/impress) url reject-200
^https?:\/\/ad\.12306\.cn\/ad\/ser\/getAdList url script-analyze-echo-response https://raw.githubusercontent.com/kokoryh/Script/master/js/12306.js
^https?:\/\/ad\.12306\.cn\/ad\/ser\/getAdList url script-analyze-echo-response https://github.com/ddgksf2013/Scripts/raw/master/12306.js
^https?:\/\/activity2\.api\.ofo\.com\/ofo\/Api\/v2\/ads url reject
^https?:\/\/act\.vip\.iqiyi\.com\/interact\/api\/v2\/show\? url reject-dict
^https?:\/\/acs\.youku\.com\/gw\/mtop\.youku\.soku\.yksearch url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/acs\.youku\.com\/gw\/mtop\.youku\.huluwa\.dispatcher\.youthmode\.config2 url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/acs\.youku\.com\/gw\/mtop\.youku\.haidai\.lantern\.appconfig\.get url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/acs\.youku\.com\/gw\/mtop\.youku\.columbus\.(gateway\.new\.execute|home\.feed|home\.query|uc\.query|ycp\.query) url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/acs\.youku\.com\/gw\/mtop\.youku\.(pisp\.scripts\.get|xspace\.play\.position\.preload\.query|xspace\.poplayer\.position\.query) url reject-dict
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.wdk\.render\.querysinglepage url reject-200
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.trip\.activity\.querytmsresources\/1\.0\?type=originaljson url reject-img
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.trip\.activity\.querytmsresources url reject-dict
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.taobao\.idle\.home\.welcome url reject-dict
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.o2o\.ad\.gateway\.get url reject-dict
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.fliggy\.crm\.screen\.(allresource|predict) url reject-dict
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.film\.mtopadvertiseapi\.queryadvertise\/ url reject-200
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.film\.mtopadvertiseapi\.queryadvertise url reject-dict
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.film\.mtopadvertiseapi\.(queryadvertise|queryloadingbanner)\/ url reject
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.etao\.noah\.query\/.+tao_splash url reject-dict
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.etao\.noah\.query\/.+tao_splash url reject
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.etao\.noah\.query.*etao_splash url reject-200
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.damai\.wireless\.home\.welcome url reject-200
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.damai\.mec\.popup\.get url reject-200
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.alimusic\.common\.mobileservice\.startinit\/ url reject
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.alimusic\.common\.mobileservice\.startinit url reject-dict
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.alimama\.etao\.config\.query\/.+?etao_advertise url reject-dict
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.alimama\.etao\.config\.query\/.+?etao_advertise url reject
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.alimama\.etao\.config\.query url reject-200
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.alibaba\.advertisementservice\.getadv\/ url reject-200
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.alibaba\.advertisementservice\.getadv\/ url reject
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.alibaba\.advertisementservice\.getadv url reject-dict
^https?:\/\/acs4miniapp-inner\.m\.taobao\.com\/gw\/mtop\.alimama\.abyss\.unionpage\.get url reject-200
^https?:\/\/acs-m\.freshippo\.com\/gw\/mtop\.wdk\.render\.querysinglepage url reject-200
^https?:\/\/acs(\.|-)m\.(taobao|freshippo)\.com\/gw\/mtop\.wdk\.sg\.querysinglescene url reject-dict
^https?:\/\/acs(\.|-)m\.(taobao|freshippo)\.com\/gw\/mtop\.wdk\.render\.querytabfeedstream url reject-200
^https?:\/\/acs(\.|-)m\.(taobao|freshippo)\.com\/gw\/mtop\.wdk\.render\.querysinglepage url reject-200
^https?:\/\/acs(\.|-)m\.(taobao|freshippo)\.com\/gw\/mtop\.wdk\.render\.query(index|my)page url script-response-body https://raw.githubusercontent.com/zirawell/Ad-Cleaner/main/Collection/js/freshippo.js
^https?:\/\/acs(\.|-)m\.(taobao|freshippo)\.com\/gw\/mtop\.wdk\.hippotown\.tabbar\.info url reject
^https?:\/\/acs(\.|-)m\.(taobao|freshippo)\.com\/gw\/mtop\.wdk\.fc\.recommend\.feedscommondservice url reject-dict
^https?:\/\/access\.if\.iqiyi\.com\/3f1\/cards\.iqiyi\.com\/(views_category\/3\.0\/category_home|views_home\/3\.0\/qy_home|waterfall\/3\.0\/feed)\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/aag\.enmonster\.com\/apa\/index\/advert\/skin url reject
^https?:\/\/a\.sinopecsales\.com\/app\/cms url reject-dict
^https?:\/\/a\.qiumibao\.com\/ios\/config\/\?version_code= url reject-200
^https?:\/\/a\.qiumibao\.com\/ios\/config\/\?version_code= url reject
^https?:\/\/a\.qiumibao\.com\/activities\/config\.php$ url reject-200
^https?:\/\/a\.qiumibao\.com\/activities\/config\.php url reject
^https?:\/\/\w+\.kakamobi\.cn\/api\/open\/v\d\/advert-sdk\/ url reject-200
^https?:\/\/\w+\.kakamobi\.cn\/api\/open\/v\d\/advert-sdk\/ url reject
^https?:\/\/\w+\.beacon\.qq\.com url reject
^https?:\/\/\w+?\.kingsoft-office-service\.com\/ad url reject-200
^https?:\/\/[a-z]*\.rsscc\.com\/[a-z]*\/adver url reject
^https?:\/\/[a-zA-Z0-9_-]+(\.[a-zA-Z0-9_-]+){1,3}(:\d+)?\/api\/v\d\/movie\/index_recommend url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/555Ad.js
^https?:\/\/[a-zA-Z0-9_-]+(\.[a-zA-Z0-9_-]+){1,3}(:\d+)?\/.*?\/v\d\/(version$|notice\?|top_notice\?|advert\?position=[^2]+) url reject-200
^https?:\/\/[a-zA-Z0-9-]+(\.[a-zA-Z0-9-]+){1,3}(:\d+)?\/api\/v\d\/movie\/index_recommend url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/555Ad.js
^https?:\/\/[a-zA-Z0-9-]+(\.[a-zA-Z0-9-]+){1,3}(:\d+)?\/api\/v\d\/advert url reject
^https?:\/\/[^(apple|10010)]+\.(com|cn)\/(a|A)d(s|v)?(\/|\.js) url reject-img
^https?:\/\/[\w-]+\.snssdk\.com\/.+_ad\/ url reject
^https?:\/\/[\w-]+\.amemv\.com\/aweme\/v\d\/ad\/ url reject
^https?:\/\/[\s\S]*\.baidu\.com/.*?ad[xs]\.php url reject-img
^https?:\/\/[\d\.]+\/odin\/c1\/(channel\/ads|skin\/config)\? url reject-dict
^https?:\/\/[\d\.]+\/3f1\/cards\.iqiyi\.com\/(views_home\/3\.0\/qy_home|waterfall\/3\.0\/feed)\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/[\d\.]+:\d{5}\/\?cmd=indexes url reject
^https?:\/\/[\d\.]+:8000\/v1\/resource\/\w{32}-1-SPLASH url reject-dict
^https?:\/\/[\d\.:]*\/?(defaultts\.tc|vmind\.qqvideo\.tc|finderpdd\.video)\.qq\.com\/\w+ url reject
^https?:\/\/789\.kakamobi\.cn\/.+adver url reject-img
^https?:\/\/4gimg\.map\.qq\.com\/mwaSplash\/ url reject-200
^https?:\/\/47\.110\.187\.87\/winterfell\/v2\/getIpByDomain url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/soul/soul_ads.js
^https?:\/\/47\.100\.65\.202\/source\/plugin\/mobile\/mobile\.php\?module=threadpost&.+?&page=1 url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/fly.js
^https?:\/\/47\.100\.65\.202\/source\/plugin\/mobile\/mobile\.php\?module=advis url reject
^https?:\/\/47\.100\.65\.202\/api\/mobile\/index\.php\?version=\d&mobile=yes&module=basicdata&type=forumlist url response-body adv response-body random_body
^https?:\/\/3gimg\.qq\.com\/tencentMapTouch\/splash\/ url reject-200
^https?:\/\/3gimg\.qq\.com\/tencentMapTouch\/app\/activity\/ url reject-200
^https?:\/\/3g\.csair\.com\/CSMBP\/bookProcess\/homepopup\/queryAdvertisement url reject-200
^https?:\/\/2402:4e00:1200:ed00:0:9089:6dac:96b6 url reject-200
^https?:\/\/2024.05.29/v2.0.480 url reject-200
^https?:\/\/1jietu\.com\/apiv\d\/ad url reject-200
^https?:\/\/182\.92\.244\.70\/d\/json url reject-dict
^https?:\/\/119\.29\.29\.98\/d url reject-200
^https?:\/\/118\.89\.204\.198 url reject-dict
^https?:\/\/118\.178\.214\.118\/yyting\/advertclient\/ClientAdvertList\.action url reject-img
^https?:\/\/103\.91\.210\.141\:2515\/xgapp\.php\/v2\/top_notice url reject-200
^https?:\/\/103\.91\.210\.141\:2515\/xgapp\.php\/v2\/top_notice url reject
^https?:\/\/103\.41\.167\.237 url reject-dict
^https?:\/\/101\.91\.69\.26:8080\/.+ url reject
^https?:\/\/.+\.snssdk\.com\/video\/play\/1\/toutiao\/.+\/mp4 url reject
^https?:\/\/.+\.snssdk\.com\/motor\/operation\/activity\/display\/config\/V2\/ url reject-200
^https?:\/\/.+\.snssdk.com\/api\/ad\/.+ url reject
^https?:\/\/.+\.shuqireader\.com\/sapi\/.+ url reject
^https?:\/\/.+\.pstatp\.com\/obj\/mosaic-legacy\/.+\?from\=ad url reject
^https?:\/\/.+\.pstatp\.com\/bytecom\/resource\/track_log\/src\/.+ url reject
^https?:\/\/.+\.pipix\.com\/bds\/user\/check_in\/ url script-response-body https://raw.githubusercontent.com/ZenmoFeiShi/Qx/main/PPX.js
^https?:\/\/.+\.pipix\.com\/bds\/feed\/channel_list\/ url script-response-body https://raw.githubusercontent.com/ZenmoFeiShi/Qx/main/PPX.js
^https?:\/\/.+\.pglstatp-toutiao\.com\/.+\/toutiao\.mp4 url reject
^https?:\/\/.+\.pglstatp-toutiao\.com url reject
^https?:\/\/.+\.pangolin-sdk-toutiao\.com\/api\/ad\/union\/sdk\/(get_ads|stats|settings)\/ url reject
^https?:\/\/.+\.googleapis.com/adsmeasurement url reject-img
^https?:\/\/.+\.googleapis.com/.+log_event url reject-img
^https?:\/\/.+\.googleapis.com/.+ad_break url reject-img
^https?:\/\/.+\.byteimg\.com\/web\.business\.image url reject
^https?:\/\/.+\.byteimg\.com\/ad-app-package url reject
^https?:\/\/.+\.byteimg.com/tos-cn-i-1yzifmftcy\/(.+)-jpeg\.jpeg url reject
^https?:\/\/.+\.amemv\.com\/.+stats url reject-img
^https?:\/\/.+\.amemv\.com\/.+report url reject-img
^https?:\/\/.+\.amemv\.com\/.+app_log url reject-img
^https?:\/\/.+\.(pglstatp-toutiao|pstatp)\.com\/obj\/ad-pattern\/renderer url reject
^https?:\/\/.+\.(pglstatp-toutiao|pstatp)\.com\/(obj|img)\/web\.business\.image\/.+ url reject
^https?:\/\/.+\.(pglstatp-toutiao|pstatp)\.com\/(obj|img)\/(ad-app-package|ad)\/.+ url reject
^https?:\/\/.+\.(amemv|musical|snssdk|tiktokv)\.com\/(api|motor)\/ad\/ url reject-200
^https?:\/\/.+?\/music\/common\/upload\/t_splash_info\/ url reject
^https?:\/\/.+?\/cdn-adn\/ url reject-200
^https?:\/\/.+?\.kingsoft-office-service\.com url reject
^https?:\/\/.+?\.58cdn\.com\.cn\/brandads\/ url reject-200
^https?:\/\/.+?\.(pipi|fuli|xiang(jiao|xiang))apps\.com\/(ucp\/index|getGlobalData|(\/|)vod\/reqplay\/) url script-response-body https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/File/xjsp.js
^https?:\/\/.*yuanfudao\.com\/leo-mis\/iphone\/splashes url reject-200
^https?:\/\/.*yuanfudao\.com\/iphone\/splashes url reject-200
^https?:\/\/.*v2ex\.com\/($|t\/\d+) url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/v2ex.js
^https?:\/\/.*umetrip\.com\.cn\/gateway\/api\/umetrip\/native$ url script-response-header https://github.com/ddgksf2013/Scripts/raw/master/hanglvzongheng.js
^https?:\/\/.*ubixioe\.com\/mob\/sdk\/v\d\/endpoint url reject-200
^https?:\/\/.*tipatipa\.xyz\/announcements url reject-200
^https?:\/\/.*mting\.info\/advert\/ClientAdvertList\.action url reject-200
^https?:\/\/.*map\.baidu\.com\/.*govui\/rich_content url reject-200
^https?:\/\/.*mangaapi\.manhuaren\.\w{2,4}\/v\d\/public\/(getStartUpMessage|getStartPageAds|getShelfActivity) url reject-200
^https?:\/\/.*mangaapi\.manhuaren\.\w{2,4}\/v\d\/public\/(getStartUpMessage|getStartPageAds|getShelfActivity) url reject
^https?:\/\/.*mangaapi\.manhuaren\.\w{2,4}\/v\d\/ad url reject-200
^https?:\/\/.*mangaapi\.manhuaren\.\w{2,4}\/v\d\/ad url reject
^https?:\/\/.*dcloud\.net\.cn\/(app\/acs|uad) url reject-200
^https?:\/\/.*cupid\.iqiyi\.com\/mixer\? url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/iqiyi_open_ads.js
^https?:\/\/.*aastocks\.com\/ad\/ url reject-200
^https?:\/\/.*\/yyting\/advertclient\/ClientAdvertList.action url reject-200
^https?:\/\/.*\/yyting\/advertclient\/ClientAdvertList.action url reject
^https?:\/\/.*\.yuxueyuan\.cn\/yxy-api-gateway\/api\/json\/advert\/getsAdStartScreen url reject-200
^https?:\/\/.*\.xmcdn\.com\/\w{8}\/\w{4}-\w{16}\/.+gif$ url reject
^https?:\/\/.*\.xima.*\.com\/ting\/(loading|feed|home)? url reject
^https?:\/\/.*\.xima.*\.com\/social-web\/bottomTabs\/dynamicEntrance\/status url reject
^https?:\/\/.*\.xima.*\.com\/mobile\/discovery\/v\d\/location url reject
^https?:\/\/.*\.xima.*\.com\/mobile-user\/v\d\/homePage url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/xmly_json.js
^https?:\/\/.*\.xima.*\.com\/mobile-user\/v\d\/homePage url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/ximalaya_json.js
^https?:\/\/.*\.xima.*\.com\/mobile-user\/unread url reject
^https?:\/\/.*\.xima.*\.com\/mobile-playpage\/view\/ url reject
^https?:\/\/.*\.xima.*\.com\/hotWord url reject
^https?:\/\/.*\.xima.*\.com\/focus-mobile\/focusPic url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/xmly_json.js
^https?:\/\/.*\.xima.*\.com\/focus-mobile\/focusPic url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/ximalaya_json.js
^https?:\/\/.*\.xima.*\.com\/discovery-feed\/v\d\/mix url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/xmly_json.js
^https?:\/\/.*\.xima.*\.com\/discovery-feed\/v\d\/mix url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/ximalaya_json.js
^https?:\/\/.*\.xima.*\.com\/discovery-feed\/isShowUserGiftPendant url reject
^https?:\/\/.*\.xima.*\.com\/discovery-feed\/focus\/queryF url reject
^https?:\/\/.*\.xima.*\.com\/discovery-category\/v\d/category url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/xmly_json.js
^https?:\/\/.*\.xima.*\.com\/discovery-category\/v\d/category url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/ximalaya_json.js
^https?:\/\/.*\.xima.*\.com\/discovery-category\/customCategories url script-response-body https://raw.githubusercontent.com/fmz200/wool_scripts/main/Scripts/xmly_json.js
^https?:\/\/.*\.xima.*\.com\/discovery-category\/customCategories url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/ximalaya_json.js
^https?:\/\/.*\.xima.*\.com\/collector\/xl\/v\d url reject
^https?:\/\/.*\.xima.*\.com\/chaos-notice-web\/v1\/message\/preview\/list url reject
^https?:\/\/.*\.xima.*\.com\/butler-portal\/versionCheck url reject
^https?:\/\/.*\.xima.*\.com\/api\/v\d\/adRealTime url reject
^https?:\/\/.*\.xima.*\.com\/(hub\/)?hotWordBillboard url reject
^https?:\/\/.*\.xima.*\.com\/(hub\/)?hotWord url reject
^https?:\/\/.*\.xima.*\.com\/(hub)?guideWord url reject
^https?:\/\/.*\.xima.*\.com\/(dog-portal\/checkOld|(child-mobile\/child|aged-mobile\/aged)\/mode\/query) url reject
^https?:\/\/.*\.xima.*\.com/mobile-user/minorProtection/pop url reject
^https?:\/\/.*\.townmalls\.cn:1890\/mossapi\/mossp\.BannerManager\/activityList.* url reject
^https?:\/\/.*\.pglstatp-toutiao\.com\/.*ad.* url reject
^https?:\/\/.*\.meituan\.com\/api\/v\d\/(openscreen\?ad|appstatus\?ad|loadInfo\?|startpicture) url reject-200
^https?:\/\/.*\.i18n-pglstatp\.com\/obj\/ad-pattern-sg url reject
^https?:\/\/.*\.amap\.com\/ws\/valueadded\/weather url reject-dict
^https?:\/\/.*\.amap\.com\/ws\/valueadded\/alimama\/splash_screen url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/amap.js
^https?:\/\/.*\.amap\.com\/ws\/shield\/search\/new_hotword url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/amap.js
^https?:\/\/.*\.amap\.com\/ws\/shield\/search\/nearbyrec_smart url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/amap.js
^https?:\/\/.*\.amap\.com\/ws\/shield\/scene\/recommend url reject-dict
^https?:\/\/.*\.amap\.com\/ws\/shield\/frogserver\/aocs\/updatable url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/amap.js
^https?:\/\/.*\.amap\.com\/ws\/shield\/dsp\/profile\/index\/nodefaas url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/amap.js
^https?:\/\/.*\.amap\.com\/ws\/promotion-web\/resource url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/amap.js
^https?:\/\/.*\.amap\.com\/ws\/msgbox\/pull url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/amap.js
^https?:\/\/.*\.amap\.com\/ws\/message\/notice\/list url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/amap.js
^https?:\/\/.*\.amap\.com\/ws\/faas\/amap-navigation\/main-page url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/amap.js
^https?:\/\/.*\.amap\.com\/ws\/faas\/amap-navigation\/card-service-route-plan\? url reject-dict
^https?:\/\/.*\.amap\.com\/ws\/boss\/order_web\/\w{8}_information url reject-200
^https?:\/\/.*\.amap\.com\/ws\/asa\/ads_attribution url reject
^https?:\/\/.*\.amap\.com\/uploadimg\/\w+\.gif url reject-img
^https?:\/\/.*(xbwpys|ahhhhfs)\.com\/($|[0-9a-zA-Z_/]+\/$) url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/ahfs.js
^https?:\/\/(s3plus|flowplus)\.meituan\.net\/v\d\/\w+\/linglong\/\w+\.(gif|jpg|mp4) url reject-200
^https?:\/\/(s3plus|flowplus)\.meituan\.net\/v\d\/\w+\/linglong\/\w+\.(gif|jpg|mp4) url reject
^https?:\/\/(preload-click|preload-impression)\.uve\.weibo\.com\/(interface\/wbpullad\/wbpullad_click\.php|wbapplua\/get_wbpullad_log\.lua) url reject
^https?:\/\/(nr-op|cube)\.elemecdn\.com\/.+\.jpeg\?x-oss-process=image\/resize,m_fill,w_\d{4,},h_\d{4,}\/($|format,webp\/$) url reject
^https?:\/\/(news\.ssp\.qq\.com\/app|r\.inews\.qq\.com\/(get(QQNewsUnreadList|TagFeedList)|gw\/page\/event_detail|news_feed\/hot_module_list)) url script-response-body https://raw.githubusercontent.com/app2smile/rules/master/js/qq-news.js
^https?:\/\/(mobile|shop)\.laichon\.com\/api\/(v1\/goods\/goodsList|exposureAdvStatistics|getWebAdvList) url reject-200
^https?:\/\/(mobile|shop)\.laichon\.com\/api\/(v1\/goods\/goodsList|exposureAdvStatistics|getWebAdvList) url reject
^https?:\/\/(mgxhtj|nmobi|searchrecterm)\.kuwo\.cn\/(mgxh|mobi|recterm)\.s url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/break/kuwo.js
^https?:\/\/(kjp|t7z)\.cupid\.iqiyi\.com\/mixer\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cnftp.js
^https?:\/\/(ipv4|interface3?)\.music\.163\.com\/eapi\/ad url reject-dict
^https?:\/\/(gw|img)\.alicdn\.com\/imgextra\/.+\/[\w!]+\d+-\d+-.+-\b([8-9]\d{2,}|[1-9]\d{3,})\b-\b([5-9]\d{2,}|[1-9]\d{3,})\b url reject-dict
^https?:\/\/(gw|heic)\.alicdn\.com\/imgextra\/\w{2}\/[\w!]+-\d-tps-\d{3,4}-\d{4}\.jpg_(1\d{3}|9\d{2})x(1\d{3}|9\d{2})q\d0\.jpg_\.(heic|webp)$ url reject
^https?:\/\/(gw|heic)\.alicdn\.com\/imgextra\/.+\d{4}-\d{4}\.jpg_(9\d{2}|\d{4}) url reject
^https?:\/\/(gw|heic)\.alicdn\.com\/\w{2}s\/[\w\/.-]+\.jpg_(9\d{2}|\d{4}) url reject
^https?:\/\/(grpc\.biliapi\.net|app\.bilibili\.com)\/bilibili\.polymer\.app\.search\.v1\.Search\/SearchAll$ url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/bilibili_proto_beta.js
^https?:\/\/(ec|c)api\.lkcoffee\.com\/resource\/m\/eorder\/product\/popAppTagProductList url reject
^https?:\/\/(discardrp|startup)\.umetrip\.com\/gateway\/api\/umetrip\/native url reject-200
^https?:\/\/(client\.app\.coc|h\.app\.coc|app)\.10086\.cn\/biz-orange\/DN\/emotionMarket url reject
^https?:\/\/(bdsp-x|dsp-x)\.jd\.com\/adx\/ url reject-200
^https?:\/\/(app\.bilibili\.com|grpc\.biliapi\.net)\/bilibili\.community\.service\.dm\.v1\.DM\/(DmView|DmSegMobile) url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/bilibili_proto_beta.js
^https?:\/\/(app\.bilibili\.com|grpc\.biliapi\.net)\/bilibili\.app\.interface\.v1\.Search\/Default url reject
^https?:\/\/(app\.bilibili\.com|grpc\.biliapi\.net)\/bilibili\.app\.dynamic\.v2\.Dynamic\/Dyn(All|Video)$ url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/bilibili_proto_beta.js
^https?:\/\/(app\.bilibili\.com|grpc\.biliapi\.net)\/bilibili\.app\.(view|viewunite)\.v1\.View\/(View|TFInfo)$ url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/bilibili_proto_beta.js
^https?:\/\/(api|atrace)\.chelaile\.net\.cn\/adpub\/ url reject
^https?:\/\/(api|api-bk\d+)\.tv\.sohu\.com\/agg\/api\/app\/config\/bootstrap url reject
^https?:\/\/(api-mifit|api-mifit-\w+)\.huami\.com\/discovery\/mi\/discovery\/\w+_ad\? url reject
^https?:\/\/(adse\.wsa|adse|adbehavior|xdcs-collector)\.xima.*\.com\/.* url reject
^https?:\/\/(?>heic|gw)\.alicdn\.com\/tfs\/TB1.+?-\d{4}-\d{4}\.jpg_1200x1200q90\.jpg_\.\w{3,4}$ url reject-200
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/music\/common\/upload\/t_splash_info\/ url reject
^https?://zone\.guiderank-app\.com/guiderank-web/app/ad/listLaunchADByCity\.do url reject
^https?://zjh5api\.189smarthome\.com:\d+/xygj-config-api/queryData url reject
^https?://yxyapi\d\.drcuiyutao\.com/yxy-api-gateway/api/json/advert/ url reject
^https?://you\.163\.com/ url 302 https://you.163.com/
^https?://www\.zhihu\.com/api/v\d/answers/\d+/recommendations url reject
^https?://www\.xiaohongshu\.com/api/sns/v\d/(tag/)?ads url reject-200
^https?://www\.inoreader\.com/adv/ url reject
^https?://www\.flyertea\.com/source/plugin/mobile/mobile\.php\?module=advis url reject
^https?://www\.didapinche\.com/app/adstat/ url reject
^https?://www\.cntv\.com/nettv/adp/ url reject
^https?://www\.bodivis\.com\.cn/app/splashAdvertise url reject
^https?://wmapi\.meituan\.com/api/v\d/startpicture url reject
^https?://weibointl\.api\.weibo\.cn/portal\.php\?a=get_coopen_ads url reject
^https?://webboot\.zhangyue\.com/zycl/api/ad/ url reject
^https?://webboot\.zhangyue\.com/zyapi/bookstore/ad/ url reject
^https?://web\.chelaile\.net\.cn/api/adpub/ url reject
^https?://wap\.ngchina\.cn/news/adverts/ url reject
^https?://wap\.js\.10086\.cn/jsmccClient/cd/market_content/api/v\d/market_content\.page\.query url reject
^https?://venus\.yhd\.com/memhome/launchConfig url reject
^https?://v\d-api\.miaopai\.com/miaopai/advertisement/ url reject
^https?://u\d\.iqiyipic\.com/image/[\w/]+/oad_ url reject
^https?://translate\.google\.cn url 302 https://translate.google.com
^https?://tracker-download\.oss-cn-beijing\.aliyuncs\.com/SIMPlus/(ad_|AD/) url reject
^https?://tqt\.weibo\.cn/overall/redirect\.php\?r=tqtad url reject
^https?://tqt\.weibo\.cn/overall/redirect\.php\?.+?tqt_sdkad url reject
^https?://tqt\.weibo\.cn/api/advert/ url reject
^https?://tqt\.weibo\.cn/.+advert\.index url reject
^https?://tiku\.zhan\.com/Common/newAd/ url reject
^https?://thor\.weidian\.com/ares/home\.splash/ url reject
^https?://syh\.zybang\.com/com/adx/ url reject
^https?://switch\.jumpvg\.com/jump/(getlaunchad|recommend/ad_conf) url reject
^https?://support\.you\.163\.com/xhr/boot/getBootMedia\.json url reject
^https?://status\.boohee\.com/api/v\d/app_square/start_up_with_ad$ url reject
^https?://ssp\.dzh\.com\.cn/v2api/adgroupjson url reject-200
^https?://ssp\.dzh\.com\.cn/v2api/adgroupjson url reject
^https?://ssl\.kohsocialapp\.qq\.com:\d+/game/buttons url reject
^https?://spclient.wg.spotify.com/(ad-logic|ads|.+ad_slot|.+banners|.+canvases|.+cards|.+crashlytics|.+doubleclick.net|.+enabled-tracks|.+promoted_offer) url reject-img
^https?://sns\.amap\.com/ws/msgbox/pull_mp\? url reject-dict
^https?://smkmp\.96225.com/smkcenter/ad/ url reject
^https?://slapi\.oray\.net/client/ad url reject
^https?://slapi\.oray\.net/adver url reject
^https?://shopic\.sf-express\.com/crm/mobile/common/flashscreen url reject
^https?://shopapi\.io\.mi\.com/mtop/mf/resource/homePage/pageConfig url reject
^https?://shop-api\.retail\.mi\.com/mtop/navi/skywheel/mishop/splash url reject-dict
^https?://sh-gateway\.shihuo\.cn/v\d/services/sh-adapi/home/screen url reject
^https?://service\.iciba\.com/popo/open/screens/v\d\?adjson url reject
^https?://service\.4gtv\.tv/4gtv/Data/(GetAD|ADLog) url reject
^https?://s\d\.zdmimg\.com/www/api/v\d/api/thirdAd\.php url reject
^https?://s1\.api\.tv\.itc\.cn/v\d/mobile/control/switch\.json url reject
^https?://rtbapi\.douyucdn\.cn/japi/sign/app/getinfo url reject
^https?://rs.creditcard.cmbc.com.cn/mmc/img/126f35586ece469aa2daf2e451ba7b4d.jpg url reject-200
^https?://res-release\.wuta-cam\.com/json/ads_component_cache\.json url reject
^https?://render-oss-cdn\.amap\.com/render/studio-dev/image/ url reject-200
^https?://r\.inews\.qq\.com/(adsBlacklist|getFullScreenPic|getQQNewsRemoteConfig) url reject
^https?://qt\.qq\.com/lua/mengyou/get_splash_screen_info url reject
^https?://pubads.g.doubleclick.net/gampad/ads url reject
^https?://pss\.txffp\.com/piaogen/images/launchScreen/ url reject
^https?://pic\d\.ajkimg\.com/mat/\w+\?imageMogr\d/format/jpg/thumbnail/\d{3}x\d{4}$ url reject
^https?://pic\.k\.sohu\.com/img\d/wb/tj/ url reject
^https?://pic\.edaijia\.cn/adsplash/ url reject
^https?://pan\.baidu\.com/rest/\d\.\d/pcs/ad url reject
^https?://pan\.baidu\.com/act/v\d/(bchannel|welfare)/list url reject
^https?://pan\.baidu\.com/act/api/activityentry url reject
^https?://pagead2.googleadservices.com/pagead/adview url reject
^https?://p\.du\.163\.com/ad/ url reject
^https?://otheve.beacon.qq.com\/analytics\/upload\?sid=.* url reject
^https?://optimus-ads\.amap\.com/uploadimg/ url reject-200
^https?://open\.qyer\.com/qyer/startpage/ url reject
^https?://open\.qyer\.com/qyer/config/get url reject
^https?://nnapp\.cloudbae\.cn:\d+/mc/api/advert/ url reject
^https?://news\.ssp\.qq\.com/app url reject
^https?://newclient\.map\.baidu\.com/client/usersystem/home/dynamic url reject
^https?://newclient\.map\.baidu\.com/client/phpui2/\?qt=ads url reject
^https?://newclient\.map\.baidu\.com/client/phpui.*qt=rgc url reject
^https?://newclient\.map\.baidu\.com/client/phpui.*qt=hw url reject
^https?://newclient\.map\.baidu\.com/client/crossmarketing url reject
^https?://ms\.jr\.jd\.com/gw/generic/base/na/m/adInfo url reject
^https?://ms\.jr\.jd\.com/gw/generic/aladdin/(new)?na/m/getLoadingPicture url reject
^https?://mrobot\.pconline\.com\.cn/s/onlineinfo/ad/ url reject
^https?://mrobot\.pcauto\.com\.cn/xsp/s/auto/info/(ad|preload) url reject
^https?://mrobot\.(pcauto|pconline)\.com\.cn/v\d/ad\dp url reject
^https?://mpcs\.suning\.com/mpcs/dm/getDmInfo url reject
^https?://mp\.weixin\.qq\.com/mp/getappmsgad url response-body "advertisement_num":\d,"advertisement_info":\[.+\], response-body "advertisement_num":0,"advertisement_info":[],
^https?://mobileapi-v6\.elong\.com/adgateway/ url reject
^https?://mob\.mddcloud\.com\.cn/api/(ad|advert)/ url reject
^https?://mime\.baidu\.com/v\d/activity/advertisement url reject
^https?://mime\.baidu\.com/v\d/IosStart/getStartInfo$ url reject
^https?://media\.qyer\.com/ad/ url reject
^https?://mbasecc\.bas\.cmbchina\.com/Edge/api/mlife\.clientface\.clientservice\.api\.advertiseService/preCacheAdvertiseSec url reject
^https?://mapi\.mafengwo\.cn/(travelguide/)?ad/ url reject
^https?://mangaapi\.manhuaren\.com/v\d/public/getStartPageAds url reject
^https?://manga\.bilibili\.com/twirp/comic\.v\d\.Comic/Flash url reject
^https?://maicai\.api\.ddxq\.mobi/advert/ url reject
^https?://magev6\.if\.qidian\.com/argus/api/v\d/client/getsplashscreen url reject
^https?://magev6.if.qidian.com/argus/api/v4/client/getsplashscreen? url reject
^https?://magev6.if.qidian.com/argus/api/v1/client/iosad url reject
^https?://magev6.if.qidian.com/argus/api/v1/bookshelf/getad url reject
^https?://m\d\.amap\.com/ws/valueadded/alimama/splash_screen? url reject-200
^https?://m\d\.amap\.com/ws/shield/(scene/recommend|search/new_hotword)\? url reject-dict
^https?://m\d\.amap\.com/ws/message/notice/list\? url reject-dict
^https?://m\d\.amap\.com/ws/mapapi/hint_text/offline_data\? url reject-dict
^https?://m\d\.amap\.com/ws/faas/amap-navigation/main-page-(assets|location)\? url reject-dict
^https?://m\.tuniu\.com/api/operation/splash/ url reject
^https?://m\.ctrip\.com/restapi/[\w/]+tripAds url reject
^https?://m\.client\.10010\.com/uniAdmsInterface/getWelcomeAd url reject
^https?://m\.client\.10010\.com/mobileService/customer/accountListData\.htm url reject
^https?://m\.caijing\.com\.cn/startup_ad_ios\.html$ url reject
^https?://logoshejishi\.mairuan\.com/ url 302 https://www.sothink.com/product/logo-design-software/
^https?://live-ads\.huya\.com/live/getAllEntrance.*$ url reject-dict
^https?://list-app-m\.i4\.cn/getopfstadinfo\.xhtml url reject
^https?://jxd524\.github\.io/iFreeTime/xid32uxaoecnfv2/ url reject
^https?://itunes\.apple\.com/lookup\?id=575826903 url reject
^https?://issuecdn\.baidupcs\.com/issue/netdisk/guanggao url reject
^https?://intl\.iqiyi\.com/video/advertise url reject
^https?://intl\.iqiyi\.com/ad_external/ url reject
^https?://interface(\d)?.music.163.com/eapi/ad/ url reject
^https?://img\d+\.10101111cdn\.com/adpos/ url reject
^https?://img2\.autoimg\.cn/admdfs/ url reject
^https?://imeclient\.openspeech\.cn/adservice/ url reject
^https?://image\.suning\.cn/uimg/ma/ad/ url reject
^https?://iface\.iqiyi\.com/api/getNewAdInfo url reject
^https?://icc\.one/iFreeTime/xid32uxaoecnfv2/ url reject
^https?://ib-soft\.net/icleaner/txt/ad_priority\.txt$ url reject
^https?://i\.ys7\.com/api/ads url reject
^https?://hypersnap\.mairuan\.com/ url 302 https://www.keyshot.com/
^https?://hypersnap\.mairuan\.com/ url 302 https://www.hyperionics.com/
^https?://home\.mi\.com/cgi-op/api/v\d/recommendation/(banner|myTab|openingBanner) url reject-dict
^https?://gw\.kaola\.com/gw/dgmobile/newOpenAd url reject-200
^https?://gw\.alicdn\.com/imgextra/\w{2}/[\w!]+-\d-tps-\d{3}-\d{4}\.(jpg|png)$ url reject-200
^https?://gw-passenger\.01zhuanche\.com/gw-passenger/zhuanche-passengerController/notk/passenger/recommendADs url reject
^https?://gfp\.veta\.naver\.com/adcall\? url reject
^https?://gateway\.shouqiev\.com(:8443)?/fsda/app/bootImage\.json url reject
^https?://gateway\.cotticoffee\.com/cotti-capi/customer/position/list\?code=cotti-launch-window url reject-dict
^https?://gateway\.abite\.com/cotti-capi/customer/position/list\?code=cotti-launch-window url reject-dict
^https?://gab\.122\.gov\.cn/eapp/m/sysquery url reject
^https?://foodie-api\.yiruikecorp\.com/v\d/(banner|notice)/overview url reject
^https?://flowplus\.meituan\.net/v\d/\w+/linglong/\d+\.(gif|jpg|mp4) url reject
^https?://explorer\.tratao\.com/api/client/v4/xtransfer/ad/ url reject
^https?://esdk\.tymcdn\.com/dbGold/m/v2/mobileLiveReveal\.do\? url reject-dict
^https?://edith\.xiaohongshu\.com/api/sns/v\d/system_service/splash_config url reject-200
^https?://edith\.xiaohongshu\.com/api/sns/v\d/system_service/config\? url reject-200
^https?://e\.dangdang\.com/media/api\d\.go\?action=getDeviceStartPage url reject
^https?://dsa-mfp\.fengshows\.cn/mfp/mfpMultipleDelivery\.do\?.+adunitid url reject
^https?://dl\.app\.gtja\.com/dzswem/kvController/[\w/]+\.jpg$ url reject
^https?://dili\.bdatu\.com/jiekou/ad/ url reject
^https?://daoyu\.sdo\.com/api/userCommon/getAppStartAd url reject
^https?://cube\.elemecdn\.com/\w/\w{2}/\w+mp4\.mp4\? url reject
^https?://cube\.elemecdn\.com/[\w/]+\.jpeg\?x-oss-process=image/resize,m_fill,w_\d{3},h_\d{4}/format,webp/ url reject
^https?://cube\.elemecdn\.com/[\w/]+\.jpeg\?x-oss-process=image/resize,m_fill,w_6\d{2},h_8\d{2}/format,webp/ url reject
^https?://cube\.elemecdn\.com/[\w/]+\.jpeg\?x-oss-process=image/resize,m_fill,w_1\d{3},h_2\d{3}/format,webp/ url reject
^https?://creditcardapp\.bankcomm\.cn/mappweb_interface/common/(qryPopAds|qryLaunchAds)\.do url reject
^https?://cn\.ultraiso\.net/ url 302 https://cn.ezbsystems.com/ultraiso/
^https?://cn-acs\.m\.cainiao\.com/gw/mtop\.cainiao\.guoguo\.nbnetflow\.ads\.(show|mshow)\.cn/ url reject-200
^https?://cmsapi\.wifi8\.com/v\d/(emptyAd|adNew)/ url reject
^https?://cloud\.189\.cn/include/splash/ url reject
^https?://clientaccess\.10086\.cn/biz-orange/DN/init/startInit url reject
^https?://cdn\.fivecdm\.com/cr/ url reject
^https?://cdn\.dianshihome\.com/static/ad/ url reject
^https?://cdn\.api\.fotoable\.com/Advertise/ url reject
^https?://ccsp-egmas\.sf-express\.com/cx-app-base/base/app/ad/ url reject
^https?://capis(-\d)?\.didapinche\.com/ad/ url reject
^https?://capi\.mwee\.cn/app-api/V\d+/app/(ad|getstartad) url reject
^https?://cap\.caocaokeji\.cn/advert-bss/ url reject
^https?://c\.tieba\.baidu\.com/c/f/forum/getAdInfo url reject
^https?://c\.tieba\.baidu\.com/\w+/\w+/(sync|newRnSync|mlog) url reject
^https?://business\.msstatic\.com/advertiser/ url reject
^https?://bk\.bingo\.qq\.com/bk/crx/data/videoAd.*$ url reject-dict
^https?://appconf\.mail\.163\.com/mmad/ url reject
^https?://app\.yinxiang\.com/ads/ url reject
^https?://app\.variflight\.com/v\d/advert/ url reject
^https?://app\.variflight\.com/ad/ url reject
^https?://app\.mixcapp\.com/mixc/api/v\d/ad url reject
^https?://app\.dewu\.com/api/v\d/app/advertisement/ url reject
^https?://app\.ddpai\.com/d/api/v\d/config/get/bootscreen url reject
^https?://app\.badmintoncn\.com/mag/operative/v\d/ad/ url reject
^https?://app\.api\.ke\.com/config/config/bootpage url reject
^https?://app\.58\.com/api/log/ url reject
^https?://app\.58\.com/api/home/invite/popupAdv url reject
^https?://app\.58\.com/api/home/(advertising|appadv)/ url reject
^https?://app-gw\.csdn\.net/cms-app/v\d/home_page/open_advertisement url reject
^https?://app-api\.smzdm\.com/util/loading url reject
^https?://app-api\.niu\.com/v\d/advertisement/ url reject
^https?://api\d\.futunn\.com/ad/ url reject
^https?://api\.zhuishushenqi\.com/user/bookshelf-updated url reject
^https?://api\.zhuishushenqi\.com/splashes/ios url reject
^https?://api\.zhuishushenqi\.com/notification/shelfMessage url reject
^https?://api\.zhihu\.com/fringe/ad url reject
^https?://api\.zhihu\.com/commercial_api/ url reject
^https?://api\.zhihu\.com/appview/api/v\d/answers/\d+/recommendations url reject
^https?://api\.zhihu\.com/ad url reject
^https?://api\.zhihu\.com/\w+/\d+/comments/featured-comment-ad url reject
^https?://api\.yizhibo\.com/common/api/(api_)?pz$ url reject
^https?://api\.xueqiu\.com/snowpard/launch_strategy/query\.json url reject
^https?://api\.xueqiu\.com/brand/search/v1\.json url reject
^https?://api\.xiachufang\.com/v\d/ad/ url reject
^https?://api\.waitwaitpay\.com//api/splash url reject
^https?://api\.vuevideo\.net/api/v\d/ad/ url reject
^https?://api\.vistopia\.com\.cn/api/v\d/home/advertisement url reject
^https?://api\.smzdm\.com/v\d/util/loading url reject
^https?://api\.rr\.tv/ad/ url reject
^https?://api\.qiuduoduo\.cn/guideimage url reject
^https?://api\.qbb6\.com/ad/ url reject
^https?://api\.mgzf\.com/renter-operation/home/startHomePage url reject
^https?://api\.m\.mi\.com/v\d/app/start url reject
^https?://api\.m\.jd.com/client\.action\?functionId=home_launchConfig url reject
^https?://api\.m\.jd.com/client\.action\?functionId=(start|queryMaterialAdverts) url reject
^https?://api\.laifeng\.com/v\d/start/ads url reject
^https?://api\.kkmh\.com/v\d+/(ad|advertisement)/ url reject
^https?://api\.k\.sohu\.com/api/news/adsense url reject
^https?://api\.jxedt\.com/ad/ url reject
^https?://api\.jr\.mi\.com/jr/api/splashScreen url reject
^https?://api\.izuiyou\.com/ad/ url reject
^https?://api\.hanju\.koudaibaobao\.com/api/carp/kp\? url reject
^https?://api\.gotokeep\.com/op-engine-webapp/v\d/ad url reject
^https?://api\.gotokeep\.com/ads url reject
^https?://api\.gaoqingdianshi\.com/api/v\d/ad/ url reject
^https?://api\.futunn\.com/v\d/ad/ url reject
^https?://api\.douban\.com/v\d/app_ads/ url reject
^https?://api\.dangdang\.com/mapi\d/mobile/init url reject
^https?://api\.club\.lenovo\.cn/common/open_ad url reject
^https?://api\.chelaile\.net\.cn/goocity/advert/ url reject
^https?://api\.chelaile\.net\.cn/adpub/ url reject
^https?://api\.cdmcaac\.com/ad/ url reject
^https?://api\.caijingmobile\.com/(ad|advert)/ url reject
^https?://api\.bjxkhc\.com/index\.php/app/ios/ads/ url reject
^https?://api\.applovefrom\.com/api/v\d/splash/ url reject
^https?://api\.abema\.io/v\d/ip/check url reject-200
^https?://api\.21jingji\.com/ad/ url reject
^https?://api\.(pinduoduo|yangkeduo)\.com/api/cappuccino/splash url reject
^https?://api3\.cls\.cn/v1/boot/ad\? url reject-dict
^https?://api.xiaoyi.com\/v5\/app\/mobile\/ads url reject
^https?://api.xiaoyi.com\/v5\/app\/config\?userid=.* url reject
^https?://api-release\.wuta-cam\.com/ad_tree url reject
^https?://api-one\.wallstcn\.com/apiv\d/advertising/ url reject
^https?://api-new\.app\.acfun\.cn/rest/app/flash/screen/ url reject
^https?://api-mifit\.huami\.com/discovery/mi/discovery/\w+_ad\? url reject
^https?://api-mifit-cn2\.zepp\.com/discovery/mi/cards/(startpage_ad|homepage_ad)\? url reject
^https?://api-access\.pangolin-sdk-toutiao\.com/api/ad/union/sdk/ url reject
^https?://amap-aos-info-nogw\.amap\.com/ws/aos/alimama/ url reject-200
^https?://advertise\.bczeducation\.cn\/rpc\/advertise url reject-200
^https?://ads-img-al\.xhscdn\.com/hera/ url reject
^https?://act\.vip\.iqiyi\.com/interact/api/v\d/show url reject
^https?://act\.vip\.iqiyi\.com/interact/api/show\.do url reject
^https?://acs\.m\.taobao\.com/gw/mtop\.film\.mtopadvertiseapi\.(queryadvertise|queryloadingbanner)/ url reject-200
^https?://acs\.m\.taobao\.com/gw/mtop\.etao\.noah\.query/.+tao_splash url reject-200
^https?://acs\.m\.taobao\.com/gw/mtop\.damai\.wireless\.home\.welcome/ url reject-200
^https?://acs\.m\.taobao\.com/gw/mtop\.alimama\.etao\.config\.query/.+?etao_advertise url reject-200
^https?://acs\.m\.taobao\.com/gw/mtop\.alibaba\.advertisementservice\.getadv/ url reject-200
^https?://a\.qiumibao\.com/activities/config\.php url reject
^https?://\w+\.kingsoft-office-service\.com/ad url reject
^https?://\w+\.kakamobi\.cn/api/open/v\d/advert-sdk/ url reject
^https?://[\w-]+\.snssdk\.com/motor/operation/activity/display/config/V2/ url reject
^https?://[\w-]+\.snssdk\.com/.+_ad/ url reject
^https?://[\w-]+\.amemv\.com/aweme/v\d/ad/ url reject
^https?://[\w-]+\.(amemv|musical|snssdk|tiktokv)\.(com|ly)/(api|motor)/ad/ url reject
^https?://4gimg\.map\.qq\.com/mwaSplash/ url reject
^https?://.+\.58cdn\.com\.cn/brandads/ url reject
^https?://.+?\.tc\.qq\.com/.+?p20\d\.1\.mp4\? url reject
^https?://.+?\.tc\.qq\.com/.+?_p20\d_ url reject
^https?://.+?\.ott\.cibntv\.net/[\w/-]+.mp4\?sid= url reject-200
^https?://.+?/promotion/(display_cache|display_ad|feed_display|search_ad) url reject
^https?://.+?/music/common/upload/t_splash_info/ url reject
^https?://.+?/img/ad\.union\.api/ url reject
^https?://.+?/c/s/splashSchedule url reject
^https?://.+?/brand/search/v1\.json url reject
^https?://.+?/api/v\d/adRealTime url reject
^https?://.+?/allOne\.php\?ad_name url reject
^https?://.+?/(outadservice|ting/preload)/ url reject
^https?://.+?(:\d+)?/V\d/splash/getSplashV\d\.action$ url reject
^https?://(www.)?zbrushcn.com/ url 302 https://pixologic.com/
^https?://(www.)?yuanchengxiezuo\.com/ url 302 https://www.teamviewer.com/
^https?://(www.)?yhd\.com/ url 302 https://yhd.com/
^https?://(www.)?xshellcn\.com/ url 302 https://www.netsarang.com/zh/xshell/
^https?://(www.)?vegaschina\.cn/ url 302 https://www.vegascreativesoftware.com/
^https?://(www.)?taobao\.com/ url 302 https://taobao.com/
^https?://(www.)?suning\.com/ url 302 https://suning.com/
^https?://(www.)?shankejingling\.com/ url 302 https://www.sothink.com/product/flashdecompiler/
^https?://(www.)?photozoomchina\.com/ url 302 https://www.benvista.com/
^https?://(www.)?pdfexpert\.cc/ url 302 https://pdfexpert.com/zh
^https?://(www.)?passwordrecovery\.cn/ url 302 https://cn.elcomsoft.com/aopr.html
^https?://(www.)?overturechina\.com/ url 302 https://sonicscores.com/
^https?://(www.)?officesoftcn\.com/ url 302 https://www.microsoft.com/zh-cn/microsoft-365
^https?://(www.)?ntfsformac\.cn/ url 302 https://china.paragon-software.com/home-mac/ntfs-for-mac/
^https?://(www.)?ntfsformac\.cc/ url 302 https://www.tuxera.com/products/tuxera-ntfs-for-mac-cn/
^https?://(www.)?nicelabel\.cc/ url 302 https://www.nicelabel.com/zh/
^https?://(www.)?mindmapper\.cc/ url 302 https://www.mindmapper.com/
^https?://(www.)?mindmanager\.(cc|cn)/ url 302 https://www.mindjet.com/cn/
^https?://(www.)?mi\.com/ url 302 https://www.mi.com/
^https?://(www.)?mathtype\.cn/ url 302 https://www.dessci.com/
^https?://(www.)?luping\.net\.cn/ url 302 https://www.techsmith.com/
^https?://(www.)?logoshejishi\.com url 302 https://www.sothink.com/product/logo-design-software/
^https?://(www.)?kingdeecn\.cn/ url 302 http://www.kingdee.com/
^https?://(www.)?jihehuaban\.com\.cn/ url 302 https://www.chartwellyorke.com/sketchpad/x24795.html
^https?://(www.)?jd\.com/ url 302 https://www.jd.com/
^https?://(www.)?imindmap\.cc/ url 302 https://www.ayoa.com/previously-imindmap/
^https?://(www.)?imazingchina\.com/ url 302 https://imazing.com/zh
^https?://(www.)?ign\.xn--fiqs8s/ url 302 http://cn.ign.com/ccpref/us
^https?://(www.)?idmchina\.net/ url 302 https://www.internetdownloadmanager.com/
^https?://(www.)?iconworkshop\.cn/ url 302 https://www.axialis.com/
^https?://(www.)?hypeapp\.cn/ url 302 https://tumult.com/hype/
^https?://(www.)?huishenghuiying\.com\.cn/ url 302 https://www.coreldraw.com/cn/
^https?://(www.)?guitarpro\.cc/ url 302 https://www.guitar-pro.com/
^https?://(www.)?formysql\.com/ url 302 https://www.navicat.com.cn/
^https?://(www.)?folxchina\.cn/ url 302 https://mac.eltima.com/cn/download-manager.html
^https?://(www.)?flstudiochina\.com/ url 302 https://www.image-line.com/
^https?://(www.)?firefox\.com\.cn/(download/)?$ url 302 https://www.mozilla.org/zh-CN/firefox/new/
^https?://(www.)?ediuschina\.com/ url 302 https://www.grassvalley.com/
^https?://(www.)?easyrecoverychina\.com/ url 302 https://www.ontrack.com/
^https?://(www.)?earmasterchina\.cn/ url 302 https://www.earmaster.com/
^https?://(www.)?dongmansoft\.com/ url 302 https://www.udongman.cn/
^https?://(www.)?crossoverchina\.com/ url 302 https://www.codeweavers.com/
^https?://(www.)?coreldrawchina\.com/ url 302 https://www.coreldraw.com/cn/
^https?://(www.)?codesoftchina\.com/ url 302 https://www.teklynx.com/
^https?://(www.)?chemdraw\.com\.cn/ url 302 https://www.perkinelmer.com.cn/
^https?://(www.)?bingdianhuanyuan\.cn/ url 302 https://www.faronics.com/zh-hans/products/deep-freeze
^https?://(www.)?beyondcompare\.cc/ url 302 https://www.scootersoftware.com/
^https?://(www.)?bartender\.cc/ url 302 https://www.macbartender.com/
^https?://(www.)?anydeskchina\.cn/ url 302 https://anydesk.com/zhs
^https?://(www.)?alienskins\.cn/ url 302 https://exposure.software/
^https?://(www.)?abbyychina\.com/ url 302 https://www.abbyy.cn/
^https?://(www.)?(mycleanmymac|xitongqingli)\.com/ url 302 https://macpaw.com/
^https?://(www.)?(g|google)\.cn url 302 https://www.google.com
^https?://(www.)?(betterzipcn|betterzip)\.(com|net)/ url 302 https://macitbetter.com/
^https?://(sdk|wb)app\.uve\.weibo\.com(/interface/sdk/sdkad.php|/wbapplua/wbpullad.lua) url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/weibo_json.js
^https?://(ios|android)\.sogou\.com/[^/]+/sogou_input_[^/]+/[^/]+/index\.html url reject
^https?://(gw|heic)\.alicdn\.com/imgextra/\w{2}/[\w!]+-\d-tps-\d{3,4}-\d{4}\.jpg_(1\d{3}|9\d{2})x(1\d{3}|9\d{2})q\d0\.jpg_\.(heic|webp)$ url reject-200
^https?://(ditu|maps)\.google\.cn url 302 https://maps.google.com
^https?://(discardrp|startup)\.umetrip\.com/gateway/api/umetrip/native url reject
^https?://(bdsp-x|dsp-x)\.jd\.com/adx/ url reject
^https?://(api|promo)\.xueqiu\.com/promotion/(display_cache|display_ad|feed_display|search_ad) url reject
^https?://(api|b)\.zhuishushenqi\.com/advert url reject
^https?://(api|api-bk\d+)\.tv\.sohu\.com/agg/api/app/config/bootstrap url reject
^https:\/\/zlsdk\.1rtb\.net\/sdk\/req_ad\?sdk_version=\d+\.\d+\.\d+\.\d+&device_os=iOS&accept_ad_type=\d+&app_id=\d+&pid=\d+&sdk_version_code=\d+ url reject-dict
^https:\/\/youtubei\.googleapis\.com\/youtubei\/v1\/(browse|get_watch|next|player|reel\/reel_watch_sequence) url script-request-body https://github.com/Maasea/sgmodule/raw/master/Script/Youtube/dist/youtube.request.preview.js
^https:\/\/www\.ymm56\.com\/short-distance-match-app\/openAppAd url reject-dict
^https:\/\/www\.jianshu\.com\/go-wild\?ac=\d&url= url script-echo-response https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/noRedirect.js
^https:\/\/www1.elecfans.com\/www\/delivery url reject
^https:\/\/web\.chelaile\.net\.cn\/api\/adpub url reject
^https:\/\/wallet\.95516\.com(:10533)?\/s\/wl\/icon\/large\/1 url reject
^https:\/\/us\.l\.qq\.com\/exapp\?spsa=\d url reject-200
^https:\/\/tiebac\.baidu\.com\/tiebaads\/commonbatch\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/baidu/tiebaJson.js
^https:\/\/ssp\.soulapp\.cn\/api\/q\? url reject-dict
^https:\/\/shop-api\.retail\.mi\.com\/mtop\/navi\/(rec\/merge\/|skywheel\/mishop\/splash) url reject-dict
^https:\/\/saas-ad\.cloudpnr\.com\/huifuad-base-api\/api\/tactics\/ad url script-response-body https://gitlab.com/lodepuly/vpn_tool/-/raw/master/Resource/Script/WexinMiniPrograms/huifu/huifu_remove_ads.js
^https:\/\/s3plus\.meituan\.net\/v1\/mss_\w+\/(brandcpt-vedio|waimai-alita)\/\w+\.zip$ url reject-dict
^https:\/\/s3plus\.meituan\.net\/ocean-blk-index\/index\/blk_conf_73\.json url reject-dict
^https:\/\/router-app-api\.jdcloud\.com\/v\d\/board\/routerAppSplash url reject-200
^https:\/\/res\.kfc\.com\.cn\/advertisement url reject
^https:\/\/qiye\.gaoding\.com\/api\/v3\/oc\/v2\/delivery-pits\/ios-splash\/ url reject-dict
^https:\/\/poplayer\.template\.alibaba\.com\/\w+\.json url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/myBlockAds.js
^https:\/\/pic\d\.ajkimg\.com\/mat\/\w+\?imageMogr\d\/format\/jpg\/thumbnail\/\d{3}x\d{4}$ url reject
^https:\/\/pan\.baidu\.com\/rest\/2\.0\/membership\/user url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/baidu/baiduCloud.js
^https:\/\/pan\.baidu\.com\/api\/getsyscfg\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/baidu/baiduCloud.js
^https:\/\/pan\.baidu\.com\/(act\/api\/activityentry|act\/v2\/|rest\/2\.0\/pcs\/ad) url reject-dict
^https:\/\/p0\.pipi\.cn\/adAdmin\/\w+\.jpg\?imageMogr2\/quality\/ url reject-dict
^https:\/\/p0\.pipi\.cn\/adAdmin\/\w+\.(jpg|png)\?imageMogr2\/thumbnail\/(860x0|!165x165|!1049x1169) url reject-dict
^https:\/\/osg-service\.sgcc\.com\.cn:18600\/emss-pfa-appset-front\/bootpageoutter\/ url reject-dict
^https:\/\/open\.e\.kuaishou\.com\/rest\/e\/v3\/open\/univ url reject-200
^https:\/\/open\.e\.kuaishou\.cn\/rest\/e\/v3\/open url reject-dict
^https:\/\/nex\.163\.com\/q url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/news163.js
^https:\/\/newclient\.map\.baidu\.com\/client\/phpui2\/\?qt=ads url script-response-body https://raw.githubusercontent.com/app2smile/rules/master/js/baidumap.js
^https:\/\/mxsa\.mxbc\.net\/api\/v1\/adinfo\/limitedAds$ url reject-200
^https:\/\/mp\.weixin\.qq\.com\/mp\/(cps_product_info|getappmsgad|masonryfeed|relatedarticle)\? url reject-dict
^https:\/\/mobilepaas\.abchina\.com\.cn:441\/mgw\.htm$ url script-response-header https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/header.js
^https:\/\/mobile\.12306\.cn\/otsmobile\/app\/mgs\/mgw\.htm$ url script-response-header https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/header.js
^https:\/\/mi\.gdt\.qq\.com\/gdt_mview\.fcg url reject-200
^https:\/\/mgesq\.api\.mgtv\.com\/v2\/goods\/guess_you_like url reject-dict
^https:\/\/mgesq\.api\.mgtv\.com\/user\/center\/config url reject-dict
^https:\/\/mgesq\.api\.mgtv\.com\/search\/goods\/rank url reject-dict
^https:\/\/member\.alipan\.com\/v2\/activity\/sign_in_luckyBottle url reject-dict
^https:\/\/member\.alipan\.com\/v1\/users\/onboard_list url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/adrive.js
^https:\/\/mbd\.baidu\.com\/newspage\/api\/getmobads\?page\=landingshare url reject-200
^https:\/\/mapi\.appvipshop\.com\/vips-mobile\/rest\/iosAdInfo\/report url reject-200
^https:\/\/ma-adx\.ctrip\.com\/_ma\.gif url reject-200
^https:\/\/m\.airchina\.com\.cn\/airchina\/gateway\/v\d(\.\d)*\/api\/services url script-response-header https://raw.githubusercontent.com/zirawell/Ad-Cleaner/main/Collection/js/airchina.js
^https:\/\/list-app-m\.i4\.cn\/(adclickcb|getHotSearchList|getopfstadinfo)\.xhtml url reject
^https:\/\/links\.jianshu\.com\/go\?to= url script-echo-response https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/noRedirect.js
^https:\/\/jzts\.cmpassport\.com\/personalized\/getPushContent url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cloud139.js
^https:\/\/img\.meituan\.net\/bizad\/bizad_brandCpt_\d+\.jpg url reject-dict
^https:\/\/img01\.51jobcdn\.com\/im\/mkt/(?:tg/((19|20)\d{2})banner/(?!jcgz2/)|\d{4}/bd/\d{4}/).*\.jpg url reject
^https:\/\/imcs\.citicbank\.com\/cloud\/([a-fA-F0-9]{32})\.(jpg|png) url reject
^https:\/\/home\.mi\.com\/cgi-op\/api\/v1\/recommendation\/(banner|carousel\/banners|myTab|openingBanner) url reject-dict
^https:\/\/heic\.alicdn\.com\/imgextra\/i\d\/\d*\/?[\w!]+-\d-(octopus|tps-1125-1602|tps-1080-1920)\.(jp|pn)g_(1\d{3}|9\d{2})x(1\d{3}|9\d{2})q[59]0 url reject-dict
^https:\/\/gw\.m\.163\.com\/nc\/api\/v1\/search\/hot-word url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/news163.js
^https:\/\/gw\.m\.163\.com\/nc\/api\/v1\/feed\/dynamic\/headline-list\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/news163.js
^https:\/\/gw\.chuangkit\.com\/team\/app\/common\/ad\/ url reject-dict
^https:\/\/gw\.alicdn\.com\/tps\/.+\d{3,4}-\d{4} url reject
^https:\/\/gw\.alicdn\.com\/tfs\/.+\d{3,4}-\d{4} url reject
^https:\/\/gw\.alicdn\.com\/mt\/ url reject
^https:\/\/gw.aihuishou.com\/app-portal\/home\/getadvertisement url reject
^https:\/\/guide-acs\.m\.taobao\.com\/gw\/mtop\.taobao\.(volvo\.secondfloor\.getconfig|wireless\.home\.newface\.awesome\.get) url reject-dict
^https:\/\/guide-acs\.m\.taobao\.com\/gw\/mtop\.taobao\.(cloudvideo\.video\.query|wireless\.home\.splash\.awesome\.get) url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/myBlockAds.js
^https:\/\/guide-acs\.m\.taobao\.com\/gw\/mtop\.cainiao\.guoguo\.nbnetflow\.ads\.mshow url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cainiao.js
^https:\/\/guide-acs\.m\.taobao\.com\/gw\/mtop\.cainiao\.adx\.flyad\.getad url reject-dict
^https:\/\/gab\.122\.gov\.cn\/eapp\/m\/sysquery\/adver$ url reject
^https:\/\/gab\.122\.gov\.cn\/eapp\/m\/sysquery url reject-200
^https:\/\/fuss10.elemecdn.com\/.+\/w\/750\/h\/\d{3,4} url reject
^https:\/\/fuss10.elemecdn.com\/.+\/w\/640\/h\/\d{3,4} url reject
^https:\/\/fuss10.elemecdn.com\/.+\.mp4 url reject
^https:\/\/flowplus\.meituan\.net\/v1\/mss_\w+\/linglong\/\d+\.jpg url reject-dict
^https:\/\/elemecdn.com\/.+\/sitemap url reject
^https:\/\/dl-cu-hz\.lechange\.cn\/oms-online\/advertisementPush url reject
^https:\/\/data-collector\.soulapp\.cn\/api\/data\/report$ url reject-200
^https:\/\/client\.app\.coc\.10086\.cn\/biz-orange\/DN\/(explorePage\/getAdverList|init\/startInit) url reject-dict
^https:\/\/assets\.msn\.com\/service\/news\/feed\/pages\/startmhp url reject-dict
^https:\/\/app\.peopleapp\.com\/Api\/\d+/HomeApi\/(adv|getAdvertImage) url reject-200
^https:\/\/app\.dewu\.com\/api\/v1\/app\/advertisement\/ url reject-200
^https:\/\/app\.bilibili\.com\/x\/v2\/splash\/list url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/bilibili_json.js
^https:\/\/app\.api\.versa-ai\.com\/launch\/ads\? url reject-200
^https:\/\/app\.58\.com\/api\/log\/ url reject
^https:\/\/app\.58\.com\/api\/home\/invite\/popupAdv url reject
^https:\/\/app\.58\.com\/api\/home\/(advertising|appadv) url reject
^https:\/\/app-gw\.csdn\.net\/cms-app\/v\d\/home_page\/open_advertisement url reject
^https:\/\/api\.zhihu\.com\/topstory\/recommend url script-response-body https://gist.githubusercontent.com/blackmatrix7/f5f780d0f56b319b6ad9848fd080bb18/raw/zheye.min.js
^https:\/\/api\.xiachufang\.com\/v\d\/ad/ url reject-200
^https:\/\/api\.sfacg\.com\/ioscfg url reject-200
^https:\/\/api\.m\.mi\.com\/v2\/search\/search_default$ url reject-dict
^https:\/\/api\.m\.mi\.com\/v1\/misearch\/search_input$ url reject-dict
^https:\/\/api\.m\.mi\.com\/v1\/home\/page_feed(_v5)?$ url reject-dict
^https:\/\/api\.m\.mi\.com\/v1\/app\/popup_info$ url reject-dict
^https:\/\/api\.m\.mi\.com\/v1\/(app\/start|order\/expressView) url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/myBlockAds.js
^https:\/\/api\.m\.jd\.com\/client\.action\?functionId=lite_advertising url response-body jdLiteAdvertisingVO response-body rucu6
^https:\/\/api\.m\.jd\.com\/client\.action\?functionId=(searchBoxWord|stationPullService|uniformRecommend[06]) url reject-dict
^https:\/\/api\.m\.jd\.com\/client\.action\?functionId=(deliverLayer|getTabHomeInfo|myOrderInfo|orderTrackBusiness|personinfoBusiness|start|welcomeHome) url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/jingdong.js
^https:\/\/api\.jr\.mi\.com\/v\d\/adv url reject
^https:\/\/api\.jr\.mi\.com\/jr\/api\/playScreen url reject
^https:\/\/api\.huachenjie\.com\/run-front\/home\/sports\/getPopup url reject-dict
^https:\/\/api\.huachenjie\.com\/run-front\/ai\/getAICategory url reject-dict
^https:\/\/api\.huachenjie\.com\/run-front\/ad url reject-dict
^https:\/\/api\.gameplus\.qq\.com\/community\.OnloadSrv\/GetPreloadScreenInfo url reject-200
^https:\/\/api\.flydigi\.com\/android\/v2\/ad url reject-dict
^https:\/\/api\.douban\.com\b.*\/common_ads\? url reject
^https:\/\/api\.douban\.com\/v2\/app_ads\/splash url reject
^https:\/\/api\.coolapk\.com\/v6\/search\?.*type=hotSearch url reject-dict
^https:\/\/api\.coolapk\.com\/v6\/page\/dataList\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/coolapk.js
^https:\/\/api\.coolapk\.com\/v6\/main\/(dataList|indexV8|init) url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/coolapk.js
^https:\/\/api\.coolapk\.com\/v6\/feed\/(detail|replyList)\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/coolapk.js
^https:\/\/api\.chelaile\.net\.cn\/goocity\/advert url reject
^https:\/\/api\.chelaile\.net\.cn\/adpub url reject
^https:\/\/api\.caiyunapp\.com\/v1\/activity url reject-200
^https:\/\/api\.alipan\.com\/apps\/v2\/users\/home\/(news|widgets) url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/adrive.js
^https:\/\/api\.alipan\.com\/adrive\/v1\/file\/getTopFolders url reject-dict
^https:\/\/api5\.youonbike\.com\/ibike-rest-service\/user\/fun_IBF_GetAdvert url reject-dict
^https:\/\/api.juxingclub.com\/ad\/getAll url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/rrtv_json.js
^https:\/\/api-ad-product\.huxiu\.com\/Api\/Product\/SDK\/Advert\/Query\/queryAdvertListInfo url reject-200
^https:\/\/ad\.mcloud\.139\.com\/advertapi\/adv-filter\/ url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/cloud139.js
^https:\/\/ad\.12306\.cn\/ad\/ser\/getAdList$ url script-analyze-echo-response https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/12306.js
^https:\/\/acs\.m\.taobao\.com\/gw\/mtop\.trip\.activity\.querytmsresources url reject-dict
^https:\/\/acs\.m\.taobao\.com\/gw\/mtop\.taobao\.idle\.home\.welcome url reject-dict
^https:\/\/acs\.m\.taobao\.com\/gw\/mtop\.taobao\.idle\.home\.welcome url reject
^https:\/\/acs\.m\.taobao\.com\/gw\/mtop\.o2o\.ad\.gateway\.get url reject-dict
^https:\/\/acs\.m\.taobao\.com\/gw\/mtop\.fliggy\.crm\.screen\.allresource url reject-200
^https:\/\/acs\.m\.taobao\.com\/gw\/mtop\.fliggy\.crm\.screen\.(allresource|predict) url reject-dict
^https:\/\/acs\.m\.taobao\.com\/gw\/mtop\.film\.mtopadvertiseapi\.queryadvertise url reject-dict
^https:\/\/acs\.m\.taobao\.com\/gw\/mtop\.etao\.noah\.query\/.+tao_splash url reject-dict
^https:\/\/acs\.m\.taobao\.com\/gw\/mtop\.alimusic\.common\.mobileservice\.startinit url reject-dict
^https:\/\/acs\.m\.taobao\.com\/gw\/mtop\.alimama\.etao\.config\.query\/.+?etao_advertise url reject-dict
^https:\/\/acs\.m\.taobao\.com\/gw\/mtop\.alibaba\.advertisementservice\.getadv url reject-dict
^https:\/\/2023\.redircdn\.com\/web\/mob_post\.js\? url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/myBlockAds.js
^https:\/\/.+\.58cdn\.com\.cn\/brandads url reject
^https:\/\/(grpc\.biliapi\.net|app\.bilibili\.com)\/bilibili\.app\.interface\.v1\.Teenagers\/ModeStatus url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/bilibili_proto_beta.js
^https:\/\/(api\.hechuangxinxi\.xyz|jdforrepam\.com)\/api\/(v1\/(ads|startup|users)|v4\/movies\/\w+) url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/myBlockAds.js
^https:\/\/(api-access\.pangolin-sdk-toutiao\.com\/api\/ad\/union\/sdk\/get_ads|open\.e\.kuaishou\.com\/rest\/e\/v3\/open\/univ$|mi\.gdt\.qq\.com\/gdt_mview\.fcg\?) url script-response-body https://raw.githubusercontent.com/app2smile/rules/master/js/adsense.js
^https://otheve.beacon.qq.com\/analytics\/upload\?sid=.* url reject-200
^https://new.vip.weibo.cn/littleskin/preview url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/weibo_json.js
^https://msg\.umengcloud\.com/admsg/ url reject
^https://mapi.sfbest.com\/brokerservice-server\/cms\/getPositionById.* url reject-200
^https://mapi.mafengwo.cn\/ad\/get_launch_ad_list\/v2 url reject-200
^https://app.bilibili.com/x/v2/splash/show url reject-dict
^https://app.bilibili.com/x/v2/search/square url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/bilibili_json.js
^https://api.xiaoyi.com\/v5\/app\/mobile\/ads url reject-200
^https://api.xiaoyi.com\/v5\/app\/config\?userid=.* url reject-200
^https://api.weibo.cn/2/!/client/light_skin url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/weibo_json.js
^https://api.bilibili.com/pgc/season/player/cards url reject-dict
^http[s]?:\/\/magev6\.if\.qidian\.com\/argus\/api\/v1\/bookshelf\/refresh url reject-200
^http?:\/\/tianqi\.2345\.com\/api\/content\/getContentFeeds\.php url reject-dict
^http?:\/\/amdc\.m\.taobao\.com\/amdc\/mobileDispatch %E9%A3%9E%E7%8C%AA%E6%97%85%E8%A1%8C url-and-header reject-dict
^http?:\/\/(discardrp|startup)\.umetrip\.com\/gateway\/api\/umetrip\/native url reject
^http?:\/\/(114\.115\.217\.129)|(home\.umetrip\.com)\/gateway\/api\/umetrip\/native$ url script-response-body https://gitlab.com/lodepuly/vpn_tool/-/raw/master/Resource/Script/Umetrip/Umetrip_remove_ads.js
^http:\/\/wmapi\.meituan\.com\/api\/v7\/(loadInfo|openscreen|startpicture)\? url reject-dict
^http:\/\/s3plus\.meituan\.net\/.*\/brandcpt-vedio\/.*\?time url reject-200
^http:\/\/open\.fitdays\.cn\/uploads\/ad\/ url reject-200
^http:\/\/m\.meitun\.com\/newapi\/router\/topic\/hometptf\/feedRecommend url reject-200
^http:\/\/ipv4\.music\.163\.com\/e?api\/ad\/loading\/current url reject-200
^http:\/\/image1\.ccb\.com\/newsinfo\/eBranch\/check\/(nf\/newfin\/activity|po\/poortheme\/activity)\/\w+\.png url reject
^http:\/\/gateway2\.etnet\.com\.hk\/etnetApp\/theme\/seasonal\/v30\/theme.json url reject-200
^http:\/\/c\.tieba\.baidu\.com\/c\/s\/sync$ url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/baidu/tiebaJson.js
^http:\/\/c\.tieba\.baidu\.com\/c\/f\/(excellent\/personalized|frs\/(generalTabList|page|threadlist)|pb\/(pic)?page)\?cmd url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/baidu/tiebaProto.js
^http:\/\/c\.tieba\.baidu\.com\/c\/f\/(excellent\/personalized|frs\/(generalTabList|page|threadlist)|pb\/(pic)?page)$ url script-response-body https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/baidu/tiebaJson.js
^http:\/\/app\.api\.d3yuiw4\.com\/api\/app\/ad url reject-200
^http:\/\/app-cdn\.2q10\.com\/app\/ical\/honored\? url reject-dict
^http:\/\/amdc\.m\.taobao\.com\/amdc\/mobileDispatch$ url script-response-header https://raw.githubusercontent.com/RuCu6/QuanX/main/Scripts/header.js
^http:\/\/amdc\.m\.taobao\.com url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/amdc.js
^http:\/\/ad\.shunchangzhixing\.com\/getAd url reject-dict
^http:\/\/\w{32}\.jddebug\.com\/diagnose\? url reject
^http:\/\/.*babytree\.com/(plough\.do|go_search\/api\/mobile_search_new\/get_multi_search_default_keywords) url reject-200
^http://(www.)?aicoin\.cn/$ url 302 https://www.aicoin.com/
^http(s:\/\/tiebac|:\/\/c\.tieba)\.baidu\.com\/c\/f\/(frs\/(page|threadlist|generalTabList)|pb\/page|excellent\/personalized)\?cmd url script-response-body https://raw.githubusercontent.com/app2smile/rules/master/js/tieba-proto.js
^http(s:\/\/tiebac|:\/\/c\.tieba)\.baidu\.com\/(c\/f\/(frs\/(page|threadlist|generalTabList)|pb\/page|excellent\/personalized)$|tiebaads\/commonbatch|c\/s\/sync$) url script-response-body https://raw.githubusercontent.com/app2smile/rules/master/js/tieba-json.js
^(http|https):\/\/mp\.weixin\.qq\.com\/mp\/getappmsgad url response-body advertisement response-body ddgksf2013
^(https?://)?([a-zA-Z0-9]+(-[a-zA-Z0-9]+)*\.)+[a-zA-Z]{2,}(:\d+)?/wp-json/[a-zA-Z0-9_-]+/(mp\/)?v\d/posts url script-response-body https://github.com/ddgksf2013/Scripts/raw/master/applet.js
^(http:\/\/www\.vgtime\.com\/app\/topic\/\d+\.jhtml\?.*?&close_ad=)false(&page=\d&sign=\w+&timestamp=\d+&font_size=\d$) url 302 $1true$2
(^https?://passport\.biliintl\.com/x/intl/passport-login/.+)(&s_locale=zh-Hans_[A-Z]{2})(.+)(&sim_code=\d+)(.+) url 302 $1&s_locale=zh-Hans_PH$35&sim_code=51503$5
(^https?://app\.biliintl\.com/(x/)?(intl|dm|reply|history|v\d/(fav|msgfeed)).+?)(&s_locale=zh-Hans_[A-Z]{2})(.+?)(&sim_code=\d+)(.+) url 302 $1&s_locale=zh-Hans_PH$6&sim_code=51503$8
hostname = *-release.wuta-cam.com,*.58cdn.com.cn,*.ahhhhfs.com,*.amap.com,*.anythinktech.com,*.api.weibo.*,*.bili*.*,*.bilibili.*,*.bilibili.com,*.chelaile.net.cn,*.dcloud.net.cn,*.ddly666.top,*.didapinche.com,*.ecoliving168.com,*.feidee.*,*.google.cn,*.hoopchina.com,*.k.sohu.com,*.kakamobi.cn,*.kingsoft-office-service.com,*.laichon.com,*.mting.info,*.peopleapp.com,*.qyfxgd.cn,*.smkj33.top,*.ssjlicai.*,*.tipatipa.xyz,*.tslt.xyz,*.tv.sohu.com,*.ubixioe.com,*.umetrip.com,*.uve.weibo.com,*.v2ex.com,*.weilai555.com,*.xbwpys.com,*.xima*.*,*.xmcdn.*,*.yuanfudao.com,*.yuxueyuan.cn,*.zhuishushenqi.com,*biliapi.net,*cupid.iqiyi.com,*gaoqingdianshi.com,*mangaapi.manhuaren.*,-*cdn*.biliapi.net,-*tracker*.biliapi.net,-broadcast.chat.bilibili.com,101.201.175.228,103.41.167.*,103.41.167.226,103.41.167.234,103.41.167.235,103.41.167.236,103.41.167.237,103.91.210.141,116.85.2.14,116.85.2.15,118.178.214.118,118.89.204.198,120.241.*,140.179.224.63,180.76.76.200,182.92.251.113,1jietu.com,2023.redircdn.com,212.129.159.79,2402:4e00:1200:ed00:0:9089:6dac:96b6,3dd0be8a-54fe-43ff-a0e7-f670c4f20432.bspapp.com,3g.csair.com,42.187.199.248,47.100.65.202,4gimg.map.qq.com,4thdimension.top,a.jxjt888.top,a.qiumibao.com,access.mypikpak.com,acs-m.freshippo.com,acs.m.taobao.com,acs4miniapp-inner.m.taobao.com,act.vip.iqiyi.com,ad.12306.cn,ad.cj.sina.cn,ad.lofter.com,ad.mcloud.139.com,adapi.izuiyou.com,adm.10jqka.com.cn,adpai.thepaper.cn,adproxy.autohome.com.cn,ads-img-al.xhscdn.com,ads.closeli.cn,adv.ccb.com,advertise.bczeducation.cn,adx-cn.anythinktech.com,afd.baidu.com,amap-aos-info-nogw.amap.com,ap*.smzdm.com,ap.dongqiudi.com,apapia-sqk.manmanbuy.com,api*.futunn.com,api-access.pangolin-sdk-toutiao.com,api-ad-product.huxiu.com,api-mifit-cn2.zepp.com,api-mifit.huami.com,api-new.app.acfun.cn,api-one-wscn.awtmt.com,api-one.wallstcn.com,api-sams.walmartmobile.cn,api.00bang.cn,api.21ec74.com,api.21jingji.com,api.abema.io,api.ahmobile.cn,api.alipan.com,api.bjxkhc.com,api.blibee.com,api.bspapp.com,api.caijingmobile.com,api.caiyunapp.com,api.chelaile.net.cn,api.cloud.189.cn,api.club.lenovo.cn,api.coolapk.com,api.dangdang.com,api.douban.com,api.gameplus.qq.com,api.gamer.com.tw,api.gotokeep.com,api.haohaozhu.cn,api.hechuangxinxi.xyz,api.internetofcity.cn,api.izuiyou.com,api.jr.mi.com,api.juxingclub.com,api.jxedt.com,api.kkmh.com,api.kmovie.gifshow.com,api.live.bilibili.com,api.m.jd.com,api.m.mi.com,api.mcd.cn,api.merach.com,api.mgzf.com,api.msn.com,api.mwee.cn,api.pinduoduo.com,api.psy-1.com,api.qbb6.com,api.rr.tv,api.sfacg.com,api.shenyin.name,api.taou.com,api.tipsoon.com,api.touker.com,api.vistopia.com.cn,api.vuevideo.net,api.waitwaitpay.com,api.weibo.*,api.weibo.cn,api.wfdata.club,api.wmpvp.com,api.xiachufang.com,api.xiaoyi.com,api.xueqiu.com,api.yangkeduo.com,api.yikaobang.com.cn,api.yizhibo.com,api.yonghuivip.com,api.ys7.com,api.zhihu.com,api1.34580.com,api3.cls.cn,apis.lifeweek.com.cn,app-api.medsci.cn,app-api.niu.com,app-cdn.2q10.com,app-gateway.leisuapi.com,app-gw.csdn.net,app.10099.com.cn,app.58.com,app.ap.d3yuiw4.com,app.api.ke.com,app.api.qjjfin.com,app.api.versa-ai.com,app.badmintoncn.com,app.bilibili.com,app.biliintl.com,app.c.nf.migu.cn,app.dewu.com,app.flymodem.com.cn,app.hbooker.com,app.homeinns.com,app.ibuscloud.com,app.mixcapp.com,app.yinxiang.com,app.zhuanzhuan.com,app2.autoimg.cn,app3.qdaily.com,appactive.1234567.com.cn,appapi.huazhu.com,appcloud2.zhihu.com,appconf.mail.163.com,apps.api.ke.com,apps.workair.cn,appwk.baidu.com,assets.msn.com,awg.enmonster.com,axxd.xmseeyouyima.com,b.appsimg.com,b.tslt.xyz,bbs-api.miyoushe.com,bdsp-x.jd.com,beta-api.crunchyroll.com,bgw.xinyue.qq.com,boot.biz.weibo.com,bp-api.bestv.com.cn,business.msstatic.com,c.jxjt888.top,cap.caocaokeji.cn,capi.lkcoffee.com,capi.mwee.cn,capis*.didapinche.com,carapp.gtmc.com.cn,careapi.oclean.com,ccsp-egmas.sf-express.com,cdke.youdao.com,cdn-evone-ceph.echargenet.com,cdn.*.chelaileapp.cn,cdn.cmgadx.com,cdn.fivecdm.com,client-api-v2.oray.com,client-api.oray.com,client.app.coc.10086.cn,client.mail.163.com,client.qunar.com,client.tujia.com,clientaccess.10086.cn,cloud.189.cn,cn-acs.m.cainiao.com,comicapi.manhuashe.com,compus.xiaofubao.com,creditcardapp.bankcomm.cn,creditcardapp.bankcomm.com,d.syshhc.top,daoyu.sdo.com,dapis.mting.info,data-collector.soulapp.cn,device-box.onethingpcs.com,dili.bdatu.com,discardrp.umetrip.com,dispatcher.camera360.com,dj.palmestore.com,djcapp.game.qq.com,dl-cu-hz.lechange.cn,dl.app.gtja.com,dq.dxy.cn,dsa-mfp.fengshows.cn,dsp-x.jd.com,dynamicad.kfc.com.cn,e.dangdang.com,easyreadfs.nosdn.127.net,edith.xiaohongshu.com,elemecdn.com,emdcadvertise.eastmoney.com,emdcadvise.eastmoney.com,entree-ws.igetget.com,entry.ubixioe.com,esdk.tymcdn.com,evs.500.com,explorer.tratao.com,fbchina.flipchina.cn,flowplus.meituan.net,ftapi.10jqka.com.cn,fuss10.elemecdn.com,g.syshhc.top,gab.122.gov.cn,gateway-api.dushu365.com,gateway.36kr.com,gateway.abite.com,gateway.cotticoffee.com,gateway.shouqiev.com,gd.10086.cn,gfp.veta.naver.com,gg.caixin.com,gha.ghac.cn,gjsx.vip,goblin.hupu.com,god.gameyw.netease.com,gongdu.youshu.cc,gorgon.youdao.com,grpc.biliapi.net,guanyu.longfor.com,guide-acs.m.taobao.com,gw-passenger.01zhuanche.com,gw.aihuishou.com,gw.alicdn.com,gw.kaola.com,gw.m.163.com,gx.10086.cn,gz.gongzijx.com,hc-ssp.sm.cn,heic.alicdn.com,helper.2bulu.com,hfapp-service.qweather.net,hkj178.com,home.mi.com,homefront.qunar.com,httpdns.baidubce.com,i.ys7.com,ib-soft.net,icc.one,igetcool-gateway.igetcool.com,ih2.ireader.com,image.mybank.icbc.com.cn,imeclient.openspeech.cn,img*.10101111cdn.com,img.jiemian.com,img.meituan.net,img.rr.tv,img2.autoimg.cn,info.mina.mi.com,interface*.music.163.com,intl.iqiyi.com,ios.sspai.com,iosoi.cn,iphone.ac.qq.com,issuecdn.baidupcs.com,j1.pupuapi.com,jabi.coding.net,jad-api.jin10.com,jdforrepam.com,jdread-api.jd.com,js-ad.ayximgs.com,jt.jxjt888.top,jxd524.github.io,jz.wacaijizhang.com,jzts.cmpassport.com,kad.gotokeep.com,lban.spdb.com.cn,lcen.xiaote.net,lchttpapi.xczim.com,learn.chaoxing.com,links.jianshu.com,list-app-m.i4.cn,lysl2020.com,m*.amap.com,m-cloud.zhihu.com,m.client.10010.com,m.ctrip.com,m.ibuscloud.com,m.msyc.cc,m.sd.10086.cn,m.stock.pingan.com,m.tuniu.com,m.xgjyouhui.com,m.you.163.com,ma-adx.ctrip.com,mage*.if.qidian.com,magev6.if.qidian.com,maicai.api.ddxq.mobi,mama.dxy.com,manga.bilibili.com,mapi.appvipshop.com,mapi.dangdang.com,mapi.mafengwo.cn,mapi.sfbest.com,mapi.weibo.*,mapi.weibo.com,mbasecc.bas.cmbchina.com,mbd.baidu.com,media.qyer.com,member.alipan.com,mgw.mpaas.cn-hangzhou.aliyuncs.com,mi.gdt.qq.com,mime.baidu.com,mix-api.camera360.com,mlol.qt.qq.com,mob.mddcloud.com.cn,mobads.baidu.com,mobile.12306.cn,mobileapi-v6.elong.com,mobilepaas.abchina.com.cn,mp.weixin.qq.com,mpcs.suning.com,mpos-pic.helipay.com,mrobot.pcauto.com.cn,mrobot.pconline.com.cn,ms.jr.jd.com,msg.umengcloud.com,mxsa.mxbc.net,new-app-api.ylyk.com,new.vip.weibo.cn,newapp2.szsmk.com,newclient.map.baidu.com,news.ssp.qq.com,nex.163.com,nnapp.cloudbae.cn,notify.baicizhan.com,oauth.secure.pixiv.net,open-cms-api.quark.cn,open-cms-api.uc.cn,open.e.kuaishou.com,open.fitdays.cn,open.qyer.com,open.taou.com,open3.vistastory.com,optimus-ads.amap.com,osg-service.sgcc.com.cn,otheve.beacon.qq.com,overseas.weico.cc,p*.meituan.net,p.du.163.com,p0.pipi.cn,pages.xiaohongshu.com,pan-api.bitqiu.com,pan.baidu.com,passport.biliintl.com,peisongapi.meituan.com,pic?.ajkimg.com,pipi.4kya.com,poplayer.template.alibaba.com,promo.xueqiu.com,promotion.medlive.cn,pss.txffp.com,pzoap.moedot.com,qadx.qinlinad.com,qj.bpojie.com,r.inews.qq.com,referee.xiaohongshu.com,render-oss-cdn.amap.com,rengine-platform.llsapp.com,res.kfc.com.cn,res.pizzahut.com.cn,res.xiaojukeji.com,restapi.iyunmai.com,router-app-api.jdcloud.com,rtbapi.douyucdn.cn,s3plus.meituan.net,saad.ms.zhangyue.net,sapphire.api.microsoftapp.net,sdk.1rtb.net,sdk.alibaba.com.ailbaba.me,security.wechat.com,service.4gtv.tv,service.busi.inke.cn,sh-gateway.shihuo.cn,shop-api.retail.mi.com,shopapi.io.mi.com,shopic.sf-express.com,slapi.oray.net,smkmp.96225.com,sns.amap.com,sp.kaola.com,spclient.wg.spotify.com,ssl.kohsocialapp.qq.com,sso.ifanr.com,ssp.dzh.com.cn,ssp.soulapp.cn,startup.umetrip.com,superapp.xgimi.com,support.you.163.com,switch.jumpvg.com,syh.zybang.com,t1.market.xiaomi.com,tagit.hyhuo.com,tan.ipnas.ltd,tcmobileapi.17usoft.com,td.cgmcare.cn,testflight.apple.com,tft-app.cdtft.cn,thor.weidian.com,tiebac.baidu.com,tiku.zhan.com,tk.lanjiyin.com,top-widgets-api.xiaozujian.com,tqt.weibo.cn,track.mm.taou.com,tvapp.guilaile.cn,ucmp.sf-express.com,ugc.map.baidu.com,ump.sz.creditcard.ecitic.com,us.l.qq.com,v?-api.miaopai.com,venus.yhd.com,vidz.3hxq.cn,vip7.fzwdyy.cn,wallet.95516.com,wallpaper.soutushenqi.com,wap.js.10086.cn,wap.ngchina.cn,wcprd.hilton.com,web.chelaile.net.cn,webboot.zhangyue.com,weibointl.api.weibo.cn,weixin110.qq.com,wmapi.meituan.com,wp3.lobdol.cn,www.bbkj.work,www.benbenfx.xyz,www.bodivis.com.cn,www.cntv.com,www.firefox.com.cn,www.flyert.com,www.flyertea.com,www.freeheikeji.cn,www.i3zh.com,www.inoreader.com,www.jianshu.com,www.kujiale.com,www.laoguikeji.cn,www.meituan.com,www.pansearch.me,www.xiaohongshu.com,www.zhihu.com,www1.elecfans.com,wx.mygolbs.com,wx.wxqqurl.cn,wxa.wxs.qq.com,xapi.xinmanhua.net,xcx.xianbaow.com,yanxuan.nosdn.127.net,ytmsout.radio.cn,yunbusiness.ccb.com,yxyapi*.drcuiyutao.com,zconfig.alibabausercontent.com,zhuanlan.zhihu.com,zjdr666.com,zjmbank.js96008.com,zlsdk.1rtb.net,zone.guiderank-app.com,ztoread.ziroom.com
