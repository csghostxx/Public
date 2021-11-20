## 自动同步官方GitHub仓库至Gitee仓库。
 [![.github/workflows/Auto-Sync.yml](https://github.com/Tangsan99999/tv/actions/workflows/Auto-Sync.yml/badge.svg)](https://gitee.com/tangsan99999/CatVodTVSpider) [![.github/workflows/Auto-Fetch.yml](https://github.com/Tangsan99999/tv/actions/workflows/Auto-Fetch.yml/badge.svg)](https://github.com/catvod/CatVodTVSpider)

---

<details>
<summary>▶请点我(不再更新，只作为参考)◀ 【配置内容】</summary>

```json 
{ 
// 壁纸
"wallpaper": "https://raw.githubusercontent.com/Tangsan99999/Public/main/wallpapertip_hd-stock-wallpapers_143866.jpg",
	
// 国内请把jar地址上传至gitee或其他
// 例： "spider":"https://gitee.com/tangsan99999/CatVodTVSpider/raw/master/jar/custom_spider.jar",
// 注意：小心引流，不懂编辑爬虫，建议使用官方jar即可
// 国内镜像
// "spider": "https://litecucumber.coding.net/p/cat/d/config/git/raw/master/custom_spider.txt",
"spider":"https://github.com/catvod/CatVodTVSpider/blob/master/jar/custom_spider.jar?raw=true",
		
// 以下配置作为参考，有些我也没用过，只是测试过能用，若有问题自行解决。	
"sites": [

{"key":"爬虫","name":"⇩⇩爬虫⇩⇩","type":0,"api":""}, // 不懂编辑语言，建议勿改勿问。
{"key":"csp_Juhi","name":"剧嗨(爬虫)","type":3,"api":"csp_Juhi","searchable":1,"quickSearch":1,"filterable":1},
{"key":"csp_Nfx","name":"NFXHD(爬虫)","type":3,"api":"csp_Nfx","searchable":1,"quickSearch":1,"filterable":1},
{"key":"csp_Djx","name":"瓜皮TV(爬虫)","type":3,"api":"csp_Djx","searchable":1,"quickSearch":1,"filterable":1},
{"key":"csp_Imaple","name":"枫林网(爬虫)","type":3,"api":"csp_Imaple","searchable":1,"quickSearch":1,"filterable":1},
{"key":"csp_Jumi","name":"剧迷(爬虫)","type":3,"api":"csp_Jumi","searchable":1,"quickSearch":1,"filterable":1},
{"key":"csp_Aidi","name":"爱迪(爬虫)","type":3,"api":"csp_Aidi","searchable":1,"quickSearch":1,"filterable":1},
{"key":"csp_Auete","name":"Auete(爬虫)","type":3,"api":"csp_Auete","searchable":1,"quickSearch":1,"filterable":1},
{"key":"csp_Cokemv","name":"Cokemv(爬虫)","type":3,"api":"csp_Cokemv","searchable":1,"quickSearch":1,"filterable":1},
{"key":"csp_Ysgc","name":"影视工厂(爬虫)","type":3,"api":"csp_Ysgc","searchable":1,"quickSearch":1,"filterable":1},
{"key":"csp_Nekk","name":"9E看看","type":3,"api":"csp_Nekk","searchable":1,"quickSearch":0,"filterable":1},
	

{"key":"XPATH","name":"⇩⇩XPATH⇩⇩","type":0,"api":""},  // 不懂编辑语言，建议勿改勿问。
{"key": "csp_xpath_vipmv","name": "追剧(XPMac)","type": 3,"api": "csp_XPathMac","searchable": 1,"quickSearch": 1,"filterable": 0,"ext": "https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/vipmv.json"},
{"key": "csp_xpath_xkys","name": "星空(XPMac)","type": 3,"api": "csp_XPathMac","searchable": 1,"quickSearch": 1,"filterable": 0,"ext": "https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/xkys.json"},
{"key": "csp_xpath_4kyu","name": "一只鱼4K(XPMac)","type": 3,"api": "csp_XPathMac","searchable": 1,"quickSearch": 1,"filterable": 0,"ext": "https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/4kyu.json"},
{"key":"csp_xpath_555","name":"555电影(XPMac)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/555.json"},
{"key":"csp_xpath_cjt","name":"CJT影视(XPMac)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/cjtys.json"},
{"key":"csp_xpath_gimytv","name":"GimyTV(XPMac)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/gimytv.json"},
{"key":"csp_xpath_jpyszl","name":"极品(XPMac)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/jpys.json"},
{"key":"csp_xpath_jumi","name":"剧迷(XPMac)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/jumi.json"},
{"key":"csp_xpath_lezhutv","name":"lezhu(XPMac)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/lezhutv.json"},
{"key":"csp_xpath_miniku","name":"迷你库(XPMac)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/miniku.json"},
{"key":"csp_xpath_Ole","name":"欧乐(XPMac)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/onedianshi.json"},
{"key":"csp_xpath_Onedian","name":"ONE蓝光(XPMac)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/olevod.json"},
{"key":"csp_xpath_pianba","name":"片库(XPMac)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/pianba.json"},
{"key":"csp_xpath_sky4k","name":"天空4K(XPMac)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/sky4k.json"},
{"key":"csp_xpath_tvci","name":"大师兄(XPMac)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/tvci.json"},
{"key":"csp_xpath_duboku","name":"独播库(XPMac)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/duboku.json" },
{"key":"csp_xpath_duboku2","name":"独播库2(XPMac)","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/duboku2.json" },

{"key":"csp_xpath_dd520","name":"多多(XPath)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/dd520.json"},
{"key":"csp_xpath_fantuan","name":"饭团(XPath)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/fantuan.json"},
{"key":"csp_xpath_axx","name":"爱西西(XPath)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/aixixi.json"},
{"key":"csp_xpath_jpys","name":"极品(XPath)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/jpys.json"},
{"key":"csp_xpath_94sm","name":"94神马(XPath)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/94sm.json"},
{"key":"csp_xpath_age","name":"AGE动漫(XPath)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/agefans.json"},
{"key":"csp_xpath_dm84","name":"动漫巴士(XPath)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/dm84.json"},
{"key":"csp_xpath_newfli","name":"newfli(XPath)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/newfli.json"},
{"key":"csp_xpath_saohuotv","name":"骚火电影(XPath)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/saohuotv2.json"},
{"key":"csp_xpath_egg","name":"蛋蛋影院(XPath)","type":3,"api":"csp_XPathEgg","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/egg.json"},
{"key":"csp_yysdali","name":"YYDS影视(XPath)","type":3,"api":"csp_YydsAli","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/yyds.json"},
{"key":"csp_yinghua","name":"樱花动漫(XPath)","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable": 0,"ext":"https://cdn.jsdelivr.net/gh/Tangsan99999/Public@main/xpath/yinghua.json"},



{"key":"XML","name":"⇩⇩XML⇩⇩","type":0,"api":""},
{"key":"唐人街","name":"唐人街","type": 0,"api":"https://www.tangrenjie.tv/api.php/provide/vod/at/xml","playUrl":""},
{"key":"4K影院","name":"4K影院","type": 0,"api":"http://www.dijiaxia.com/api.php/provide/vod/at/xml","playUrl":""},
{"key":"虾米资源","name":"虾米资源","type": 0,"api":"https://zy.xmflv.vip/api.php/provide/vod/at/xml","playUrl":""},
{"key":"OmoFun动漫","name":"OmoFun动漫","type":1,"api":"https://www.omofun.com/api.php/provide/vod/","playUrl":"","categories":["动漫","剧场版","国产","欧美"]},
{"key":"w7tv","name":"w7tv","type":1,"api":"http://w7tv.com/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"小蜻蜓APP","name":"小蜻蜓APP","type":1,"api":"http://3ketv.com/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"番茄资源","name":"番茄资源","type":0,"api":"http://api.fqzy.cc/api.php/provide/vod/at/xml/","playUrl":"https://jx.fqzy.cc/jx.php?url=","categories":[]},
{"key":"畅视影视","name":"畅视影视","type":1,"api":"http://app.reboju.net/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"追剧吧APP","name":"追剧吧APP","type":1,"api":"http://data.zju8.cc:1234/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"真不卡","name":"真不卡","type":1,"api":"http://db.taijuwang.cc/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"饭团影视","name":"饭团影视","type":1,"api":"http://fantuan.wkfile.com/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"竹嘎(蓝光解析)","name":"竹嘎(蓝光解析)","type":1,"api":"http://m.ycccyk.cn/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"爱看啦","name":"爱看啦","type":1,"api":"http://v.aik.la/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"侦探APP","name":"侦探APP","type":1,"api":"http://ys.huangguay.com/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"BL视频","name":"BL视频","type":1,"api":"https://bljiex.com/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"淘片资源","name":"淘片资源","type":0,"api":"https://taopianzy.com/home/cjapi/c4ca4238a0b923820dcc509a6f75849b/vod/xml","playUrl":"","categories":[]},
{"key":"北斗星资源备","name":"北斗星资源备","type":0,"api":"https://v8.bdxzyapi.com/inc/api.php","playUrl":"","categories":[]},
{"key":"九九美剧","name":"九九美剧","type":1,"api":"https://www.999meiju.com/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"YT影视","name":"YT影视","type":1,"api":"http://ytys.cc/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"火星2048","name":"火星2048","type":1,"api":"https://www.hx2048.com/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"游艺资源","name":"游艺资源","type":1,"api":"http://360.hexh.ink/api.php/provide/vod/","playUrl":"http://api.u1o.net/?url=","categories":[]},
{"key":"三零资源","name":"三零资源","type":1,"api":"http://api.000zy.com/provide/vod/","playUrl":"https://jx.3jx.net/?url=","categories":[]},
{"key":"萌果资源","name":"萌果资源","type":1,"api":"http://api.appearoo.top/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"艾特","name":"艾特","type":0,"api":"http://tv.aitesucai.xyz/api.php/provide/vod/at/xml","playUrl":"","categories":[]},
{"key":"天堂资源","name":"天堂资源","type":1,"api":"http://vipmv.cc/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"M3U8.TV资源","name":"M3U8.TV资源","type":0,"api":"http://www.zycaiji.net:7788/api.php/provide/vod/at/xml","playUrl":"","categories":[]},
{"key":"8090资源","name":"8090资源","type":1,"api":"http://zy.yilans.net:8090/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"2A资源","name":"2A资源","type":0,"api":"http://zy.zcocc.com/api.php/provide/vod/at/xml/","playUrl":"https://www.2ajx.com/vip.php?url=","categories":[]},
{"key":"清欢Free资源","name":"清欢Free资源","type":1,"api":"https://free.qinghuanzy.com/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"任我云","name":"任我云","type":1,"api":"https://www.renwoyun.cn/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"7K(虾米)资源","name":"7K(虾米)资源","type":1,"api":"https://zy.xmflv.vip/api.php/provide/vod/","playUrl":"https://jx.xmflv.vip/?url=","categories":["电影","连续剧","综艺","动漫","动作片","喜剧片","爱情片","科幻片","恐怖片","剧情片","战争片","国产剧","港台剧","日韩剧","欧美剧","其他片"]},
{"key":"融兴资源","name":"融兴资源","type":1,"api":"https://www.rongxingvr.com/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"无极影院","name":"无极影院","type":1,"api":"http://wujiys.com/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"爱看1080","name":"爱看1080","type":0,"api":"http://www.ik1080.com/api.php/provide/vod/at/xml/","playUrl":"","categories":[]},
{"key":"KK看剧","name":"KK看剧","type":0,"api":"http://www.kkkanju.com/api.php/provide/vod/at/xml","playUrl":"","categories":[]},
{"key":"蓝果APP","name":"蓝果APP","type":1,"api":"http://www.languotv.com/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"飞鱼影视","name":"飞鱼影视","type":1,"api":"https://app.feiyu5.com/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"39影视","name":"39影视","type":0,"api":"https://www.39kan.com/api.php/provide/vod/at/xml/","playUrl":"","categories":[]},
{"key":"白熊影院","name":"白熊影院","type":1,"api":"https://www.bxyy5.com/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"嗨哆咪影视","name":"嗨哆咪影视","type":1,"api":"http://hdmys1.com/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"热映网","name":"热映网","type":1,"api":"http://hl.reying.vip/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"飘花电影","name":"飘花电影","type":1,"api":"http://www.zzrhgg.com/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"蜂鸟视频","name":"蜂鸟视频","type":1,"api":"https://v.fnsp0.com/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"随便看电影","name":"随便看电影","type":0,"api":"https://www.sbkdy.com/inc/api.php","playUrl":"","categories":[]},
{"key":"乐多资源1","name":"乐多资源1","type":0,"api":"http://cj.leduocaiji.com/inc/seacmsapi.php","playUrl":"https://ldy.jx.cn/wp-api/ifr.php?vid=","categories":[]},
{"key":"豆瓣资源","name":"豆瓣资源","type":1,"api":"http://api.dbyunzy.com/api.php/provide/vod?ac=list","playUrl":"","categories":[]},
{"key":"乐多资源2","name":"乐多资源2","type":0,"api":"http://api.leduosj.com/inc/api.php","playUrl":"https://ldy.jx.cn/wp-api/ifr.php?vid=","categories":[]},
{"key":"天空资源","name":"天空资源","type":1,"api":"http://api.tiankongapi.com/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"穿梭资源","name":"穿梭资源","type":1,"api":"http://ok.888hyk.com/api.php/provide/vod?ac=list","playUrl":"","categories":[]},
{"key":"U酷资源","name":"U酷资源","type":1,"api":"http://ukuzy.com/api.php/provide/vod?ac=list","playUrl":"","categories":[]},
{"key":"605资源","name":"605资源","type":0,"api":"http://www.605zy.co/inc/api.php","playUrl":"","categories":[]},
{"key":"88资源","name":"88资源","type":0,"api":"http://www.88zy.live/inc/api.php","playUrl":"","categories":[]},
{"key":"韩剧资源","name":"韩剧资源","type":0,"api":"http://www.hanjuzy.com/inc/api.php","playUrl":"","categories":[]},
{"key":"快播资源","name":"快播资源","type":1,"api":"http://www.kuaibozy.com/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"百度资源","name":"百度资源","type":1,"api":"https://api.apibdzy.com/api.php/provide/vod?ac=list","playUrl":"","categories":[]},
{"key":"酷点资源","name":"酷点资源","type":1,"api":"https://kudian8.com/api.php/provide/vod?ac=list","playUrl":"","categories":[]},
{"key":"北斗星资源","name":"北斗星资源","type":1,"api":"https://api.bdxzyapi.com/api.php/provide/vod?ac=list","playUrl":"","categories":[]},
{"key":"红牛资源","name":"红牛资源","type":1,"api":"https://www.hongniuzy.com/inc/apijson_vod.php","playUrl":"https://www.tutukiki.com/m3u8/?url=","categories":[],"searchable":0},
{"key":"奇乐(优剧)资源","name":"奇乐(优剧)资源","type":1,"api":"https://zy.ujuba.com/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"无尽资源","name":"无尽资源","type":1,"api":"https://wuzy9.com/api.php/provide/vod/","playUrl":"","categories":[]},
{"key":"测试","name":"测试","type":1,"api":"http://107.150.5.146:39000/maccms10-main/api.php/provide/vod/","playUrl":"","categories":[]},


{"key":"APP影视","name":"⇩⇩APP影视⇩⇩","type":0,"api":""}, // 建议勿改勿问。
{"key":"csp_appys_xiaogui_007影视", "name":"007影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_007影视"},
{"key":"csp_appys_xiaogui_555电影", "name":"555电影(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_555电影"},
{"key":"csp_appys_xiaogui_5060影院", "name":"5060影院(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_5060影院"},
{"key":"csp_appys_xiaogui_913e影视", "name":"913e影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_913e影视"},
{"key":"csp_appys_xiaogui_BD电影", "name":"BD电影(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_BD电影"},
{"key":"csp_appys_xiaogui_COKEMV", "name":"COKEMV(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_COKEMV"},
{"key":"csp_appys_xiaogui_one影视", "name":"one影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_one影视"},
{"key":"csp_appys_xiaogui_爱尚影视", "name":"爱尚影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_爱尚影视"},
{"key":"csp_appys_xiaogui_爱影吧", "name":"爱影吧(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_爱影吧"},
{"key":"csp_appys_xiaogui_播放呀", "name":"播放呀(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_播放呀"},
{"key":"csp_appys_xiaogui_畅视影视", "name":"畅视影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_畅视影视"},
{"key":"csp_appys_xiaogui_迪迪影院", "name":"迪迪影院(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_迪迪影院"},
{"key":"csp_appys_xiaogui_嘀哩嘀哩", "name":"嘀哩嘀哩(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_嘀哩嘀哩"},
{"key":"csp_appys_xiaogui_毒舌电影", "name":"毒舌电影(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_毒舌电影"},
{"key":"csp_appys_xiaogui_饭团影院", "name":"饭团影院(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_饭团影院"},
{"key":"csp_appys_xiaogui_大师兄", "name":"大师兄(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_大师兄"},
{"key":"csp_appys_xiaogui_段友影视", "name":"段友影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_段友影视"},
{"key":"csp_appys_xiaogui_瓜皮TV", "name":"瓜皮TV(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_瓜皮TV"},
{"key":"csp_appys_xiaogui_海胆影视", "name":"海胆影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_海胆影视"},
{"key":"csp_appys_xiaogui_火箭影视", "name":"火箭影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_火箭影视"},
{"key":"csp_appys_xiaogui_海绵影视", "name":"海绵影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_海绵影视"},
{"key":"csp_appys_xiaogui_海棠视频", "name":"海棠视频(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_海棠视频"},
{"key":"csp_appys_xiaogui_京广航", "name":"京广航(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_京广航"},
{"key":"csp_appys_xiaogui_九合视频", "name":"九合视频(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_九合视频"},
{"key":"csp_appys_xiaogui_久九影视", "name":"久九影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_久九影视"},
{"key":"csp_appys_xiaogui_蓝果影视", "name":"蓝果影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_蓝果影视"},
{"key":"csp_appys_xiaogui_琳琅影视", "name":"琳琅影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_琳琅影视"},
{"key":"csp_appys_xiaogui_极乐阁", "name":"极乐阁(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_极乐阁"},
{"key":"csp_appys_xiaogui_抹茶猪", "name":"抹茶猪(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_抹茶猪"},
{"key":"csp_appys_xiaogui_萌蛋蛋", "name":"萌蛋蛋(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_萌蛋蛋"},
{"key":"csp_appys_xiaogui_迷你库", "name":"迷你库(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_迷你库"},
{"key":"csp_appys_xiaogui_思古影视", "name":"思古影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_思古影视"},
{"key":"csp_appys_xiaogui_双十电影", "name":"双十电影(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_双十电影"},
{"key":"csp_appys_xiaogui_天方影视", "name":"天方影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_天方影视"},
{"key":"csp_appys_xiaogui_天空影视", "name":"天空影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_天空影视"},
{"key":"csp_appys_xiaogui_糖果影视", "name":"糖果影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_糖果影视"},
{"key":"csp_appys_xiaogui_污妖动漫", "name":"污妖动漫(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_污妖动漫"},
{"key":"csp_appys_xiaogui_小龟视频", "name":"小龟视频(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_小龟视频"},
{"key":"csp_appys_xiaogui_星空影视", "name":"星空影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_星空影视"},
{"key":"csp_appys_xiaogui_雪人影视", "name":"雪人影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_雪人影视"},
{"key":"csp_appys_xiaogui_小易影视", "name":"小易影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_小易影视"},
{"key":"csp_appys_xiaogui_影视工场", "name":"影视工场(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_影视工场"},
{"key":"csp_appys_xiaogui_追剧达人", "name":"追剧达人(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"xiaogui_追剧达人"},
{"key":"csp_appys_v1_80影视", "name":"80影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_80影视"},
{"key":"csp_appys_v1_80K影视", "name":"80K影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_80K影视"},
{"key":"csp_appys_v1_CJT影院", "name":"CJT影院(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_CJT影院"},
{"key":"csp_appys_v1_HG影视", "name":"HG影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_HG影视"},
{"key":"csp_appys_v1_U5影视", "name":"U5影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_U5影视"},
{"key":"csp_appys_v1_VIP影视", "name":"VIP影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_VIP影视"},
{"key":"csp_appys_v1_爱影视", "name":"爱影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_爱影视"},
{"key":"csp_appys_v1_艾特影视", "name":"艾特影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_艾特影视"},
{"key":"csp_appys_v1_阿姨追剧", "name":"阿姨追剧(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_阿姨追剧"},
{"key":"csp_appys_v1_白菜追剧", "name":"白菜追剧(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_白菜追剧"},
{"key":"csp_appys_v1_比邻影视", "name":"比邻影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_比邻影视"},
{"key":"csp_appys_v1_百讯视频", "name":"百讯视频(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_百讯视频"},
{"key":"csp_appys_v1_沧海影视", "name":"沧海影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_沧海影视"},
{"key":"csp_appys_v1_菜鸟动漫", "name":"菜鸟动漫(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_菜鸟动漫"},
{"key":"csp_appys_v1_畅优视界", "name":"畅优视界(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_畅优视界"},
{"key":"csp_appys_v1_初心影视", "name":"初心影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_初心影视"},
{"key":"csp_appys_v1_多多影视", "name":"多多影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_多多影视"},
{"key":"csp_appys_v1_大海影视", "name":"大海影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_大海影视"},
{"key":"csp_appys_v1_东南影院", "name":"东南影院(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_东南影院"},
{"key":"csp_appys_v1_大熊追剧", "name":"大熊追剧(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_大熊追剧"},
{"key":"csp_appys_v1_段友影视", "name":"段友影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_段友影视"},
{"key":"csp_appys_v1_蝶众影院", "name":"蝶众影院(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_蝶众影院"},
{"key":"csp_appys_v1_二狗电影", "name":"二狗电影(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_二狗电影"},
{"key":"csp_appys_v1_饭后电影", "name":"饭后电影(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_饭后电影"},
{"key":"csp_appys_v1_飞捷影视", "name":"飞捷影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_飞捷影视"},
{"key":"csp_appys_v1_疯狂看", "name":"疯狂看(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_疯狂看"},
{"key":"csp_appys_v1_公主影视", "name":"公主影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_公主影视"},
{"key":"csp_appys_v1_辉哥影视", "name":"辉哥影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_辉哥影视"},
{"key":"csp_appys_v1_黄河影视", "name":"黄河影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_黄河影视"},
{"key":"csp_appys_v1_哈尼视频", "name":"哈尼视频(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_哈尼视频"},
{"key":"csp_appys_v1_红兔视频", "name":"红兔视频(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_红兔视频"},
{"key":"csp_appys_v1_盒子影院", "name":"盒子影院(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_盒子影院"},
{"key":"csp_appys_v1_筋斗云", "name":"筋斗云(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_筋斗云"},
{"key":"csp_appys_v1_极简影视", "name":"极简影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_极简影视"},
{"key":"csp_appys_v1_久久追剧", "name":"久久追剧(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_久久追剧"},
{"key":"csp_appys_v1_剧迷视频", "name":"剧迷视频(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_剧迷视频"},
{"key":"csp_appys_v1_橘子影视", "name":"橘子影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_橘子影视"},
{"key":"csp_appys_v1_看剧吧", "name":"看剧吧(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_看剧吧"},
{"key":"csp_appys_v1_阔贼影院", "name":"阔贼影院(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_阔贼影院"},
{"key":"csp_appys_v1_蓝光视频", "name":"蓝光视频(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_蓝光视频"},
{"key":"csp_appys_v1_林谷影视", "name":"林谷影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_林谷影视"},
{"key":"csp_appys_v1_绿箭影视", "name":"绿箭影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_绿箭影视"},
{"key":"csp_appys_v1_乐看视频", "name":"乐看视频(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_乐看视频"},
{"key":"csp_appys_v1_蓝猫影视", "name":"蓝猫影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_蓝猫影视"},
{"key":"csp_appys_v1_冷视TV", "name":"冷视TV(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_冷视TV"},
{"key":"csp_appys_v1_木白影视", "name":"木白影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_木白影视"},
{"key":"csp_appys_v1_麻瓜视频", "name":"麻瓜视频(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_麻瓜视频"},
{"key":"csp_appys_v1_麻腾TV", "name":"麻腾TV(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_麻腾TV"},
{"key":"csp_appys_v1_喵乐影视", "name":"喵乐影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_喵乐影视"},
{"key":"csp_appys_v1_命运影视", "name":"命运影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_命运影视"},
{"key":"csp_appys_v1_喵影影视", "name":"喵影影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_喵影影视"},
{"key":"csp_appys_v1_木子电影", "name":"木子电影(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_木子电影"},
{"key":"csp_appys_v1_麻子追剧", "name":"麻子追剧(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_麻子追剧"},
{"key":"csp_appys_v1_南府追剧", "name":"南府追剧(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_南府追剧"},
{"key":"csp_appys_v1_南府影视", "name":"南府影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_南府影视"},
{"key":"csp_appys_v1_暖光影视", "name":"暖光影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_暖光影视"},
{"key":"csp_appys_v1_美剧虫", "name":"美剧虫(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_美剧虫"},
{"key":"csp_appys_v1_内涵影视", "name":"内涵影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_内涵影视"},
{"key":"csp_appys_v1_柠檬影视", "name":"柠檬影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_柠檬影视"},
{"key":"csp_appys_v1_皮影视", "name":"皮影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_皮影视"},
{"key":"csp_appys_v1_奇趣影视", "name":"奇趣影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_奇趣影视"},
{"key":"csp_appys_v1_骑士影院", "name":"骑士影院(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_骑士影院"},
{"key":"csp_appys_v1_人人动漫", "name":"人人动漫(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_人人动漫"},
{"key":"csp_appys_v1_神马影视", "name":"神马影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_神马影视"},
{"key":"csp_appys_v1_视听星球", "name":"视听星球(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_视听星球"},
{"key":"csp_appys_v1_手指影视", "name":"手指影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_手指影视"},
{"key":"csp_appys_v1_淘剧社", "name":"淘剧社(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_淘剧社"},
{"key":"csp_appys_v1_天天影视", "name":"天天影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_天天影视"},
{"key":"csp_appys_v1_团夕影院", "name":"团夕影院(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_团夕影院"},
{"key":"csp_appys_v1_兔子窝", "name":"兔子窝(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_兔子窝"},
{"key":"csp_appys_v1_我爱电影", "name":"我爱电影(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_我爱电影"},
{"key":"csp_appys_v1_我爱跟剧", "name":"我爱跟剧(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_我爱跟剧"},
{"key":"csp_appys_v1_吾爱影视", "name":"吾爱影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_吾爱影视"},
{"key":"csp_appys_v1_蜗牛看鸭", "name":"蜗牛看鸭(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_蜗牛看鸭"},
{"key":"csp_appys_v1_忘忧果TV", "name":"忘忧果TV(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_忘忧果TV"},
{"key":"csp_appys_v1_渔渔影视", "name":"渔渔影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_渔渔影视"},
{"key":"csp_appys_v1_小城影视", "name":"小城影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_小城影视"},
{"key":"csp_appys_v1_先锋视频", "name":"先锋视频(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_先锋视频"},
{"key":"csp_appys_v1_小极影视", "name":"小极影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_小极影视"},
{"key":"csp_appys_v1_星空影视", "name":"星空影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_星空影视"},
{"key":"csp_appys_v1_玺娜影视", "name":"玺娜影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_玺娜影视"},
{"key":"csp_appys_v1_小蜻蜓", "name":"小蜻蜓(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_小蜻蜓"},
{"key":"csp_appys_v1_休闲影视", "name":"休闲影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_休闲影视"},
{"key":"csp_appys_v1_星影相随", "name":"星影相随(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_星影相随"},
{"key":"csp_appys_v1_小易影视", "name":"小易影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_小易影视"},
{"key":"csp_appys_v1_益达影院", "name":"益达影院(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_益达影院"},
{"key":"csp_appys_v1_元芳影视", "name":"元芳影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_元芳影视"},
{"key":"csp_appys_v1_雨果影视", "name":"雨果影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_雨果影视"},
{"key":"csp_appys_v1_颖家影院", "name":"颖家影院(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_颖家影院"},
{"key":"csp_appys_v1_月亮影视", "name":"月亮影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_月亮影视"},
{"key":"csp_appys_v1_影视热剧", "name":"影视热剧(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_影视热剧"},
{"key":"csp_appys_v1_杨桃影视", "name":"杨桃影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_杨桃影视"},
{"key":"csp_appys_v1_月色影视", "name":"月色影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_月色影视"},
{"key":"csp_appys_v1_影阅阁", "name":"影阅阁(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_影阅阁"},
{"key":"csp_appys_v1_优全影视", "name":"优全影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_优全影视"},
{"key":"csp_appys_v1_优优影院", "name":"优优影院(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_优优影院"},
{"key":"csp_appys_v1_一只鱼", "name":"一只鱼(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_一只鱼"},
{"key":"csp_appys_v1_追番猫", "name":"追番猫(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_追番猫"},
{"key":"csp_appys_v1_追剧吧", "name":"追剧吧(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_追剧吧"},
{"key":"csp_appys_v1_追剧影院", "name":"追剧影院(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_追剧影院"},
{"key":"csp_appys_v1_宅男影院", "name":"宅男影院(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_宅男影院"},
{"key":"csp_appys_v1_侦探影视", "name":"侦探影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_侦探影视"},
{"key":"csp_appys_v1_追影兔", "name":"追影兔(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_追影兔"},
{"key":"csp_appys_v1_猪猪影院", "name":"猪猪影院(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"v1_猪猪影院"},
{"key":"csp_appys_gctv_555TV", "name":"555TV(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"gctv_555TV"},
{"key":"csp_appys_gctv_红牛影视", "name":"红牛影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"gctv_红牛影视"},
{"key":"csp_appys_iptv_2号币", "name":"2号币(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"iptv_2号币"},
{"key":"csp_appys_iptv_HG影视", "name":"HG影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"iptv_HG影视"},
{"key":"csp_appys_iptv_傲视影院", "name":"傲视影院(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"iptv_傲视影院"},
{"key":"csp_appys_iptv_尘梓TV", "name":"尘梓TV(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"iptv_尘梓TV"},
{"key":"csp_appys_iptv_稻草人TV", "name":"稻草人TV(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"iptv_稻草人TV"},
{"key":"csp_appys_iptv_嘀哩嘀哩", "name":"嘀哩嘀哩(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"iptv_嘀哩嘀哩"},
{"key":"csp_appys_iptv_动力影视", "name":"动力影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"iptv_动力影视"},
{"key":"csp_appys_iptv_大师兄", "name":"大师兄(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"iptv_大师兄"},
{"key":"csp_appys_iptv_疯狂看TV", "name":"疯狂看TV(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"iptv_疯狂看TV"},
{"key":"csp_appys_iptv_火箭影视", "name":"火箭影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"iptv_火箭影视"},
{"key":"csp_appys_iptv_黑龙影视", "name":"黑龙影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"iptv_黑龙影视"},
{"key":"csp_appys_iptv_红牛TV", "name":"红牛TV(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"iptv_红牛TV"},
{"key":"csp_appys_iptv_核桃影视", "name":"核桃影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"iptv_核桃影视"},
{"key":"csp_appys_iptv_聚多影视", "name":"聚多影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"iptv_聚多影视"},
{"key":"csp_appys_iptv_久久影院", "name":"久久影院(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"iptv_久久影院"},
{"key":"csp_appys_iptv_流星雨", "name":"流星雨(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"iptv_流星雨"},
{"key":"csp_appys_iptv_冷月TV", "name":"冷月TV(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"iptv_冷月TV"},
{"key":"csp_appys_iptv_双子星", "name":"双子星(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"iptv_双子星"},
{"key":"csp_appys_iptv_云播影视", "name":"云播影视(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"iptv_云播影视"},
{"key":"csp_appys_iptv_影酷TV", "name":"影酷TV(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"iptv_影酷TV"},
{"key":"csp_appys_iptv_乐酷TV", "name":"乐酷TV(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"iptv_乐酷TV"},
{"key":"csp_appys_iptv_小极TV", "name":"小极TV(M)", "type":3, "api":"csp_AppYs","searchable":1,"quickSearch":0,"filterable":1,"ext":"iptv_小极TV"}




],
// 直播配置，不懂也勿问。
  "lives":[
    {"group":"Astro 1","channels":[
	{"name":"AOD-HD","urls":["http://198.16.106.62:8278/streams/d/AodHD/playlist.m3u8"]},
	{"name":"AOD","urls":["http://50.7.161.82:8277/streams/d/aod_pye/playlist.m3u8"]},
	{"name":"AEC","urls":["http://50.7.161.82:8277/streams/d/aec_pye/playlist.m3u8"]},
	{"name":"IQIYI","urls":["http://50.7.161.82:8277/streams/d/iqiyi_pye/playlist.m3u8"]},
	{"name":"欢喜","urls":["http://198.16.106.62:8278/streams/d/Huahee/playlist.m3u8"]},
	{"name":"双星","urls":["http://50.7.161.82:8278/streams/d/Shuangxing/playlist.m3u8"]},
	{"name":"全佳","urls":["http://50.7.161.82:8278/streams/d/Quanjia/playlist.m3u8"]},
	{"name":"小太阳","urls":["http://50.7.161.82:8278/streams/d/Xiaotaiyang/playlist.m3u8"]},
	{"name":"天映經典","urls":["http://50.7.161.82:8278/streams/d/Celestial2/playlist.m3u8"]},
	{"name":"天映頻道","urls":["http://50.7.161.82:8278/streams/d/Celestial/playlist.m3u8"]},
	{"name":"八度空间","urls":["http://50.7.161.82:8278/streams/d/TV8/playlist.m3u8"]},
	{"name":"TVB星河","urls":["http://50.7.161.82:8278/streams/d/Xinhe/playlist.m3u8"]},
	{"name":"TVB星河频道","urls":["http://50.7.161.82:8278/streams/d/Xinhe/./playlist.m3u8"]},
	{"name":"翡翠华丽台","urls":["http://198.16.106.62:8278/streams/d/Wlt/playlist.m3u8"]},
	{"name":"HBO HD","urls":["http://50.7.161.82:8278/streams/d/Hbo/playlist.m3u8 "]},
	{"name":"HBO","urls":["http://198.16.106.62:8278//streams/d/sundance_twn/playlist.m3u8"]},
	{"name":"TV1","urls":["http://50.7.161.82:8278/streams/d/TV1/playlist.m3u8"]},
	{"name":"TV2","urls":["http://50.7.161.82:8278/streams/d/TV2/playlist.m3u8"]},
	{"name":"TV3","urls":["http://50.7.161.82:8278/streams/d/TV3/playlist.m3u8"]},
	{"name":"TV9","urls":["http://50.7.161.82:8278/streams/d/TV9/playlist.m3u8"]}
	]}],
	  
// 解析地址配置，不懂请参考官方Github。	  
  "parses": [
	{"name":"Json并发","type":2,"url":"Parallel"},
	{"name":"Json轮询","type":2,"url":"Sequence"},
	{"name":"1","url":"https://titan.mgtv.com.jumi.tv/player/?url="},
    	{"name":"2","url":"https://dmku.dijiaxia.com/?url="},
   	{"name":"3","url":"https://jx.ysgc.xyz/?url="},
   	{"name":"4","url":"http://egwang186.gitee.io/?url="},
    	{"name":"5","url":"https://jx.daidaitv.top:43810/?url="},
    	{"name":"6","url":"https://okjx.cc/?url="},
    	{"name":"7","url":"https://jx.ppflv.com/?url="},
    	{"name":"8","url":"http://an61.com/jx/vip?v="},
    	{"name":"9","url":"http://60jx.com/?url="},
    	{"name":"10","url":"http://cache.languang.icu:88/didi.php?url="},
    	{"name":"11","url":"https://play.tkys.tv/?url="},
    	{"name":"12","url":"https://buaon.xyz/?url="},
    	{"name":"13","url":"https://jx.zuixinyiqi.com/jiekou-3/?url="},
    	{"name":"14","url":"https://jiexi.moeamv.com/?url="},
	{"name":"Json.VodJX","url":"https://www.vodjx.top/api/?key=XSQzk8KFK1I7FfPK5X&url=","type":1}
  ],
	  
// 匹配解析地址名称，2.0.6版本已经开始应该不必添加什么了。	  
  "flags":["youku","qq","iqiyi","qiyi","letv","sohu","tudou","pptv","mgtv","wasu","bilibili"],

// 播放器，这个我也不知啥玩意，建议勿改勿问。。
  "ijk":[
{"group":"软解码","options":[{"category":4,"name":"opensles","value":"0"},{"category":4,"name":"overlay-format","value":"842225234"},{"category":4,"name":"framedrop","value":"1"},{"category":4,"name":"soundtouch","value":"1"},{"category":4,"name":"start-on-prepared","value":"1"},{"category":1,"name":"http-detect-range-support","value":"0"},{"category":1,"name":"fflags","value":"fastseek"},{"category": 2,"name":"skip_loop_filter","value":"48"},{"category":4,"name":"reconnect","value":"1"},{"category":4,"name":"max-buffer-size","value":"5242880"},{"category":4,"name":"enable-accurate-seek","value":"0"},{"category":4,"name":"mediacodec","value":"0"},{"category":4,"name":"mediacodec-auto-rotate","value":"0"},{"category":4,"name":"mediacodec-handle-resolution-change","value":"0"},{"category":4,"name":"mediacodec-hevc","value":"0"}]},
{"group":"硬解码","options":[{"category":4,"name":"opensles","value":"0"},{"category":4,"name":"overlay-format","value":"842225234"},{"category":4,"name":"framedrop","value":"1"},{"category":4,"name":"soundtouch","value":"1"},{"category":4,"name":"start-on-prepared","value":"1"},{"category":1,"name":"http-detect-range-support","value":"0"},{"category":1,"name":"fflags","value":"fastseek"},{"category": 2,"name":"skip_loop_filter","value":"48"},{"category":4,"name":"reconnect","value":"1"},{"category":4,"name":"max-buffer-size","value":"5242880"},{"category":4,"name":"enable-accurate-seek","value":"0"},{"category":4,"name":"mediacodec","value":"1"},{"category":4,"name":"mediacodec-auto-rotate","value":"1"},{"category":4,"name":"mediacodec-handle-resolution-change","value":"1"},{"category":4,"name":"mediacodec-hevc","value":"1"}]}
		],
	
// 屏蔽广告。
"ads":["mimg.0c1q0l.cn","www.googletagmanager.com","www.google-analytics.com","mc.usihnbcq.cn","mg.g1mm3d.cn","mscs.svaeuzh.cn","cnzz.hhttm.top","tp.vinuxhome.com","cnzz.mmstat.com","www.baihuillq.com","s23.cnzz.com","z3.cnzz.com","c.cnzz.com","stj.v1vo.top","z12.cnzz.com","img.mosflower.cn","tips.gamevvip.com","ehwe.yhdtns.com","xdn.cqqc3.com","www.jixunkyy.cn","sp.chemacid.cn","hm.baidu.com","s9.cnzz.com","z6.cnzz.com","um.cavuc.com","mav.mavuz.com","wofwk.aoidf3.com","z5.cnzz.com","xc.hubeijieshikj.cn","tj.tianwenhu.com","xg.gars57.cn","k.jinxiuzhilv.com","cdn.bootcss.com","ppl.xunzhuo123.com","xomk.jiangjunmh.top","img.xunzhuo123.com","z1.cnzz.com","s13.cnzz.com","xg.huataisangao.cn","z7.cnzz.com","xg.huataisangao.cn","z2.cnzz.com","s96.cnzz.com","q11.cnzz.com","thy.dacedsfa.cn","xg.whsbpw.cn","s19.cnzz.com","z8.cnzz.com","s4.cnzz.com","f5w.as12df.top","ae01.alicdn.com","www.92424.cn","k.wudejia.com","vivovip.mmszxc.top","qiu.xixiqiu.com","cdnjs.hnfenxun.com","cms.qdwght.com"]}
  
  
```
</details>


### 官方配置编辑器
```
https://catvod.github.io/CatVodTVJsonEditor/
```


### 上传配置接口
:warning:注意:warning:接口链接必须只有粘贴文本

:+1: `https://pastebin.com/raw/izVq5sXv` (有效) :+1:

:-1: `https://pastebin.com/izVq5sXv`  (无效) :-1:

:warning:看不懂英语不是问题，大多数浏览器是支持翻译中文的，或中文版的剪贴板，别装 "弱弱的" 问一句怎么用。:fu:

:warning:有时候配置没错但却加载不了，可以尝试换个配置链接【包括配置内容链接[jar包]】如以下，大陆网络大多数都需要翻墙才能使用pastebin.
1. https://pastebin.com/
2. https://ghostbin.com/
3. https://www.toptal.com/developers/hastebin/
4. https://netcut.cn/ （不建议使用并分享，被举报肯定封）
---

### 打开APP > 设置 > 当前配置接口 (填上配置接口链接) 如图下:

![.](/img/Tutoria2l.png)

![.](/img/Tutorial.png)

点击确定，然后返回即可。

---

# :warning:非官方网站，若有错误，自行解决。再见！！！:warning:
![.](/img/bye-cry.gif)
