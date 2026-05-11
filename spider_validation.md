# 爬虫校验报告

- 生成时间: 2026-05-11T17:50:04+08:00
- 并发线程数: 16
- 总耗时(ms): 116.543秒
- 总数: 79
- 成功: 57
- 失败: 22

## 阶段失败统计

| 阶段 | 数量 |
| --- | ---: |
| 模块加载 | 0 |
| 初始化 | 0 |
| 首页分类 | 1 |
| 分类列表 | 6 |
| 视频详情 | 3 |
| 播放地址 | 0 |
| 地址校验 | 6 |
| 未预期异常 | 6 |

## 明细结果

| 爬虫 | 状态 | 失败阶段 | 总耗时 | 模块加载 | 初始化 | 首页分类 | 分类列表 | 视频详情 | 播放地址 | 地址校验 | 返回地址 | 错误信息 |
| --- | --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- | --- |
| 4K指南 | 成功 |  | 3.497秒 | 16.542ms | 0.001ms | 0.003ms | 1.833秒 | 1.375秒 | 0.004ms | 248.526ms | https://pan.quark.cn/s/e0726c4989dc |  |
| AAZ音乐 | 失败 | 未预期异常 | 10.034秒 | 15.551ms | 0.001ms | 10.015秒 | 0.0ms | 0.0ms | 0.0ms | 0.0ms |  | HTTPSConnectionPool(host='www.aaz.cx', port=443): Read timed out. (read timeout=10) |
| PPnix | 成功 |  | 4.256秒 | 61.282ms | 0.001ms | 0.001ms | 1.299秒 | 1.157秒 | 0.016ms | 1.739秒 | https://www.ppnix.com/info/m3u8/8138/1080P.m3u8 |  |
| QQ音乐 | 成功 |  | 1.458秒 | 12.712ms | 0.006ms | 0.002ms | 600.185ms | 340.229ms | 350.849ms | 151.663ms | https://isure.stream.qqmusic.qq.com/F0000040rOp00lZYHC.flac?guid=f2b6dc6522b73e1ae298c114574d9e75&vkey=CEB2B902D2DF63A86316A2D81A0C5B72885D1EBA7076B352B942A40B78F393587E9478D74FE2D970BFEC4ECFDF56F946A41281BDA583AAEB__v2b9aadcd&uin=1152921504846230218&fromtag=119114&redirect=1 |  |
| UVod | 失败 | 地址校验 | 12.851秒 | 64.26ms | 2.081秒 | 903.88ms | 1.928秒 | 994.506ms | 927.856ms | 761.323ms | https://file-endpoint33.oledsa.com/content/dsj-zj-20260510-shd-01.mp4/index.m3u8?st=zc6_sPG6_m7Ogt3nNjrnnA&e=1778507416 | HTTPSConnectionPool(host='file-endpoint33.oledsa.com', port=443): Max retries exceeded with url: /content/dsj-zj-20260510-shd-01.mp4/index.m3u8?st=zc6_sPG6_m7Ogt3nNjrnnA&e=1778507416 (Caused by SSLError(SSLCertVerificationError(1, '[SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed: unable to get local issuer certificate (_ssl.c:1081)'))) |
| libvio | 失败 | 分类列表 | 2.152秒 | 15.79ms | 0.001ms | 0.002ms | 790.878ms | 0.0ms | 0.0ms | 0.0ms |  | 分类视频列表为空 |
| youknow | 成功 |  | 10.665秒 | 11.423ms | 0.0ms | 0.001ms | 2.313秒 | 1.947秒 | 5.274秒 | 1.117秒 | https://tyyszywvod2.com/videos/202605/04/69f890a13d69b2ec911c96ca/4bf1g9/index.m3u8 |  |
| youtube | 成功 |  | 7.41秒 | 12.388ms | 0.004ms | 0.038ms | 2.321秒 | 2.182秒 | 0.004ms | 1.734秒 | https://www.youtube.com/watch?v=S_THoT67n-0 |  |
| 七味 | 成功 |  | 116.538秒 | 13.382ms | 0.001ms | 0.001ms | 1.397秒 | 1.331秒 | 110.419秒 | 3.369秒 | https://www.pcmp4.com/py/94740-3-1.html |  |
| 不太灵 | 失败 | 视频详情 | 6.676秒 | 12.534ms | 0.001ms | 1.338秒 | 1.185秒 | 1.289秒 | 0.004ms | 0.0ms |  | 详情缺少播放源或播放列表 |
| 世纪音乐 | 失败 | 地址校验 | 1.136秒 | 11.599ms | 0.001ms | 277.939ms | 0.005ms | 141.474ms | 0.006ms | 168.631ms | https://www.4c44.com/data/down.php?ac=music&id=hwehhhdnkt | HTTP 403 |
| 两个BT | 成功 |  | 5.968秒 | 18.53ms | 0.001ms | 0.001ms | 1.004秒 | 878.659ms | 2.73秒 | 1.335秒 | https://zijieapi.douyinbyte.com/m3u8/dd0ca2ca11fcbf34e0a0d769ad4f7180.m3u8 |  |
| 乌云影视 | 成功 |  | 7.846秒 | 11.706ms | 0.001ms | 951.407ms | 958.107ms | 2.642秒 | 0.022ms | 3.273秒 | https://d1jdnmkc1n5cn4.cloudfront.net/gen_overseas/https://s2.bfllvip.com/video/yanxiaxing/a6ef854c0c1f/index.m3u8 |  |
| 乐兔 | 失败 | 未预期异常 | 10.116秒 | 11.82ms | 0.001ms | 0.002ms | 10.063秒 | 0.0ms | 0.0ms | 0.0ms |  | HTTPSConnectionPool(host='www.letu.me', port=443): Read timed out. (read timeout=10) |
| 二小 | 成功 |  | 4.406秒 | 11.488ms | 0.001ms | 0.004ms | 3.143秒 | 963.845ms | 0.006ms | 248.387ms | https://pan.quark.cn/s/b3e194803b59 |  |
| 人人电影 | 失败 | 分类列表 | 2.906秒 | 11.667ms | 0.001ms | 0.001ms | 1.365秒 | 0.0ms | 0.0ms | 0.0ms |  | 分类视频列表为空 |
| 人人视频 | 失败 | 地址校验 | 2.692秒 | 0.303ms | 0.0ms | 337.64ms | 274.894ms | 263.582ms | 383.698ms | 286.051ms | https://tfvs3grhdgmt1gc41hcjz8yzdk.ourdvsssvip.com:20443/ws-302.bwcgee.cn/1042fe66438071f1b7975420848d0402/6eacc12bf7a6411c8174b99723f415bc-494b769a1432c115ec157a0c96eb87ed-ld.mp4?key=6bba023594e4c7cabe38b2db5aec0201&time=1778507408100&clientType=web_pc&clientVersion=1.0.0&parseUsage=PLAY&uid=0&rk=a6e5f63aef6a4b45b8a40b9edd99e501&hevc=false&seasonId=56136&wsiphost=ipdbme&wsrid_tag=6a01a650_PS-000-015Zk108_2786-39890-s1t1778493008186&x-mamba-business-label=13679&redirect_cnt=0&ip_type=0&wshc=C&requery=0 | HTTP 403 |
| 优酷 | 成功 |  | 1.149秒 | 0.405ms | 0.001ms | 0.001ms | 285.781ms | 593.695ms | 0.002ms | 268.744ms | https://v.youku.com/v_show/id_XNjUxODQ1MzE1Ng==.html |  |
| 低端影视 | 成功 |  | 3.282秒 | 0.289ms | 0.001ms | 0.001ms | 1.399秒 | 1.78秒 | 0.008ms | 102.745ms | https://hn.bfvvs.com/play/eXDLzQVe/index.m3u8 |  |
| 修罗 | 成功 |  | 14.627秒 | 0.394ms | 0.0ms | 0.001ms | 1.167秒 | 1.425秒 | 2.418秒 | 822.181ms | https://v16m-default.akamaized.net/9cdf18b2dd4ad589579d6c41467602aa/862bc9d9/video/tos/alisg/tos-alisg-v-26190a-sg/osERzcA0Kf5u6i4Y2dHBowAgqWAPYjAAkEAmim/ |  |
| 凡客TV | 成功 |  | 9.499秒 | 0.277ms | 0.0ms | 0.0ms | 1.649秒 | 1.691秒 | 3.081秒 | 3.077秒 | https://fktv.me/ysapi/m3u8/p/59a97924eaa4a4151f13a9dd67ce4eb5.m3u8 |  |
| 剧圈圈 | 成功 |  | 9.347秒 | 0.313ms | 0.001ms | 0.0ms | 1.916秒 | 1.515秒 | 4.395秒 | 1.521秒 | https://www.jqqzx.cc/play/62945-3-1.html |  |
| 剧迷 | 成功 |  | 12.448秒 | 0.929ms | 0.002ms | 0.003ms | 1.17秒 | 1.502秒 | 3.085秒 | 1.101秒 | https://img.ruyijx.com/m3u8/4rgQ5Bq9tqo4Kv.m3u8?w9hvDJmL3kK3AvFn6u |  |
| 博看听书 | 成功 |  | 4.6秒 | 0.288ms | 0.0ms | 3.287秒 | 282.655ms | 802.29ms | 0.002ms | 227.349ms | http://audio.bookan.com.cn/video1/audio/20200706001/aache64_133068a2.m4a |  |
| 厂长资源 | 失败 | 分类列表 | 7.178秒 | 0.385ms | 0.062ms | 0.001ms | 2.9秒 | 0.0ms | 0.0ms | 0.0ms |  | 分类视频列表为空 |
| 双星 | 成功 |  | 1.037秒 | 0.246ms | 403.395ms | 0.004ms | 211.55ms | 186.325ms | 0.004ms | 234.571ms | https://pan.quark.cn/s/aefc43744bd3 |  |
| 听书 | 成功 |  | 3.407秒 | 0.247ms | 80.219ms | 0.001ms | 207.203ms | 2.62秒 | 344.646ms | 153.635ms | http://audiopay.cos.tx.xmcdn.com/download/1.0.0/storages/b817-audiopay/16/AA/GKwRIaIGGaRGADgE-gEx_hMS-aacv2-48K.m4a?sign=af95a5a189230f78ae15624e966eae94&buy_key=FM&token=6151&timestamp=1778493013&duration=453 |  |
| 听友FM | 成功 |  | 8.506秒 | 1.501ms | 0.0ms | 1.386秒 | 1.315秒 | 2.638秒 | 3.003秒 | 160.368ms | https://file.hgeuz.cn/stream/eJwANwDI_wJVZgVKIIrU0ECux-GJ1PSt38ahythCqsH-r9TAQ4rj5F94rOjbQKjk063xyIX2z3hfeGcIHF4BAAD__5DtISY.?ts=1778491890&sign=8bc9963675bda91a2769a9d05d4b8c55 |  |
| 四万影视 | 失败 | 未预期异常 | 1.136秒 | 0.424ms | 0.001ms | 0.001ms | 1.133秒 | 0.0ms | 0.0ms | 0.0ms |  | HTTPSConnectionPool(host='40000.me', port=443): Max retries exceeded with url: /api/maccms?ac=detail&t=20&pg=1&by=time (Caused by SSLError(SSLCertVerificationError(1, '[SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed: self-signed certificate (_ssl.c:1081)'))) |
| 在线之家 | 成功 |  | 4.687秒 | 0.315ms | 0.001ms | 0.001ms | 1.006秒 | 2.051秒 | 1.345秒 | 284.072ms | https://media-sxty-fy-corp.sx3oss.ctyunxs.cn/CORPCLOUD/f076ccf5-a095-45a2-b086-cbf66f4aa40d.mp4?response-content-disposition=attachment%3Bfilename%3D%22%E9%93%81%E8%A1%80%E6%88%98%E5%A3%AB%E6%9D%80%E6%88%AE%E4%B9%8B%E5%9C%B02025HD1080P.mp4%22%3Bfilename*%3DUTF-8%27%27%25E9%2593%2581%25E8%25A1%2580%25E6%2588%2598%25E5%25A3%25AB%25E6%259D%2580%25E6%2588%25AE%25E4%25B9%258B%25E5%259C%25B02025HD1080P.mp4&x-amz-CLIENTNETWORK=UNKNOWN&x-amz-CLOUDTYPEIN=CORP&x-amz-CLIENTTYPEIN=UNKNOWN&Signature=/nJLhyEJivvBkuxOJdnCRWWa4yE%3D&AWSAccessKeyId=0Lg7dAq3ZfHvePP8DKEU&Expires=1778499884&x-amz-limitrate=102400&response-content-type=video/mp4&x-amz-FSIZE=2183471772&x-amz-UID=10000004591358&x-amz-UFID=31374317010337932 |  |
| 多多 | 成功 |  | 2.006秒 | 0.446ms | 0.0ms | 0.001ms | 516.447ms | 405.851ms | 0.003ms | 1.083秒 | https://pan.baidu.com/s/1tCpt9UMVoL9OxQyvpKUYZA?pwd=yyds |  |
| 奕搜 | 成功 |  | 3.478秒 | 0.471ms | 0.0ms | 0.001ms | 1.882秒 | 1.369秒 | 0.001ms | 225.904ms | https://pan.quark.cn/s/e5345bdd71f6 |  |
| 如意资源 | 成功 |  | 5.23秒 | 0.255ms | 0.0ms | 0.005ms | 2.44秒 | 1.3秒 | 0.003ms | 1.489秒 | https://svip.ryiplay18.com/20260508/6294_cfc8934f/index.m3u8 |  |
| 布布影视 | 成功 |  | 4.171秒 | 0.332ms | 0.0ms | 0.001ms | 1.354秒 | 1.089秒 | 1.419秒 | 308.255ms | https://c167-obsdaz-ykj-01.obs.dualstack.cidc-rp-2006.joint.cmecloud.cn/1810c8ff2a78456b9348fadfe7ab0fd0086?response-content-disposition=attachment%3B%20filename%2A%3DUTF-8%27%274K.mp4&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20260511T094218Z&X-Amz-SignedHeaders=host&X-Amz-Expires=86400&X-Amz-Credential=AH4RWOMWLEL7ROYSF2S5%2F20260511%2Fcidc-rp-2006%2Fs3%2Faws4_request&t=2&u=1261698636582652615&ot=family&oi=1263000283947275586&f=FibTFWRt8ncqZsYDWQP5LF5BI3oB5_LXK&ext=eyJ1dCI6MX0%3D&X-Amz-Signature=4f726def9e3aa7dbdd8b0ba39d0d5b3599ea107d3e43c0c1f188bfd85a0d472b |  |
| 微观短剧 | 成功 |  | 1.037秒 | 0.493ms | 0.026ms | 221.777ms | 316.155ms | 325.755ms | 0.002ms | 172.604ms | https://tv-video.cdn.drama.9ddm.com/22/A0/22A0BFFF46651CC23355B115F6307653.mp4?timestamp=1778493015&sign=90d01cc0f2bd3fe9c6adc65b6b6a3616 |  |
| 新韩剧网 | 成功 |  | 4.7秒 | 0.289ms | 0.0ms | 0.001ms | 778.516ms | 781.399ms | 694.702ms | 2.445秒 | https://cdn.yzzyvip-29.com/20260201/16425_49d7d186/index.m3u8 |  |
| 星星短剧 | 成功 |  | 1.298秒 | 0.35ms | 0.001ms | 0.001ms | 482.304ms | 667.336ms | 0.002ms | 147.404ms | https://img.novel.wsljf.xyz/shortPlay-mp4/420424102051841/EvnIm1746774634078/abc6208e-390b-4533-a1a4-b9e5741cc384/540x960/output.m3u8 |  |
| 木偶 | 成功 |  | 2.466秒 | 0.272ms | 0.0ms | 0.0ms | 1.237秒 | 944.602ms | 0.006ms | 283.449ms | https://115cdn.com/s/swf0zna36dh?password=p696 |  |
| 樱花动漫 | 成功 |  | 17.921秒 | 0.315ms | 0.001ms | 0.001ms | 2.049秒 | 2.233秒 | 2.086秒 | 2.028秒 | https://cdn.yzzyvip-32.com/20260510/38628_9b9d9c0a/index.m3u8 |  |
| 橘子TV | 成功 |  | 13.892秒 | 0.783ms | 3.815秒 | 1.83秒 | 1.848秒 | 1.796秒 | 4.533秒 | 68.389ms | https://ad.kpyy258.com/m3u87/share/7256561/7452333/20260503/185008/1080/index.m3u8?sign=30ec1861953f71d6a57e2702c5a62db1&t=1778493027 |  |
| 欧歌 | 成功 |  | 3.95秒 | 0.248ms | 0.0ms | 0.0ms | 1.905秒 | 739.56ms | 0.009ms | 1.304秒 | https://pan.baidu.com/s/1plecwmM4KBFNk_hU52nJIQ?pwd=8888 |  |
| 毒舌影视 | 失败 | 地址校验 | 9.472秒 | 0.386ms | 0.001ms | 1.638秒 | 1.089秒 | 1.046秒 | 1.433秒 | 499.379ms | https://cdn.yddsha2.com/m3u87/share/7273975/7469253/20260504/180336/1080/master.m3u8 | HTTPSConnectionPool(host='cdn.yddsha2.com', port=443): Max retries exceeded with url: /m3u87/share/7273975/7469253/20260504/180336/1080/master.m3u8 (Caused by SSLError(SSLEOFError(8, '[SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1081)'))) |
| 河马短剧 | 成功 |  | 2.413秒 | 0.329ms | 0.0ms | 645.039ms | 730.348ms | 944.584ms | 0.037ms | 91.226ms | https://dzzt-video.cbread.cn/a47e0c4b6634c6ba52175dc0da481b91/6a02de00/58/5x3/53x4/534x6/53468100014/612428785_1/612428785.720p.narrowv3.mp4 |  |
| 滴答影视 | 成功 |  | 2.169秒 | 0.314ms | 0.0ms | 0.001ms | 1.051秒 | 827.879ms | 0.003ms | 290.124ms | https://pan.quark.cn/s/98a640e2e3ee |  |
| 潮流APP | 成功 |  | 842.298ms | 0.301ms | 0.002ms | 144.908ms | 132.082ms | 172.92ms | 298.181ms | 93.462ms | http://43.248.100.143:9090/nby/m3u8/getM3u8?name=jx.91by.top&time=1778493018253&url=NBY-e84585334a25c5b49078dfac81549a0b.m3u8 |  |
| 爱奇艺 | 成功 |  | 5.367秒 | 0.528ms | 0.017ms | 3.858秒 | 769.81ms | 501.063ms | 0.001ms | 236.952ms | http://www.iqiyi.com/v_vd55wo89uk.html |  |
| 爱看 | 成功 |  | 7.3秒 | 0.372ms | 0.001ms | 0.001ms | 971.978ms | 1.807秒 | 0.002ms | 1.1秒 | https://v.gsuus.com/play/erk8nPBa/index.m3u8 |  |
| 独播库 | 成功 |  | 3.678秒 | 0.337ms | 0.001ms | 0.001ms | 870.815ms | 828.781ms | 959.982ms | 1.017秒 | https://vid.dbokutv.com/20260416/ppotb62-S71lT2yliZApDBSvkYzBsrmD3fpCJ4nBsHgTcyo5xOy6ejP7DiStHqR2qmCIqmCp8nE44oGZakRN0q/chunklist.m3u8 |  |
| 玩偶哥哥 | 成功 |  | 2.449秒 | 0.288ms | 0.0ms | 0.001ms | 792.219ms | 668.408ms | 0.003ms | 987.546ms | https://pan.baidu.com/s/1hbYaibe8p-HfdhIUP7vvFA?pwd=f8x5 |  |
| 玩偶聚合 | 成功 |  | 2.983秒 | 0.379ms | 0.0ms | 0.063ms | 863.581ms | 1.121秒 | 0.003ms | 998.077ms | https://pan.baidu.com/s/1wlGptZsrXaSU5zwTNON1MA?pwd=wogg |  |
| 瓜子 | 成功 |  | 13.816秒 | 0.549ms | 0.002ms | 0.038ms | 965.074ms | 1.752秒 | 886.073ms | 197.803ms | https://vd.hxcztech.com/130d5175952a4427ae5afc7911715a74/20260511175032/decry/vd/20260511/NTRmNzllODNj/131917/2580_1080/aac/h264/hls/decrypt/index.m3u8 |  |
| 百度短剧 | 成功 |  | 1.633秒 | 0.244ms | 0.0ms | 402.227ms | 264.388ms | 631.648ms | 252.256ms | 82.063ms | http://vd3.bdstatic.com/mda-rh54j6is12ydd0q3/1080p/mv_cae264_backtrack_1080p_normal/1754453773225130912/mda-rh54j6is12ydd0q3.mp4?v_from_s=haokan-ui-video-hna |  |
| 盘Ta | 成功 |  | 1.093秒 | 0.292ms | 0.0ms | 334.54ms | 313.033ms | 270.612ms | 0.031ms | 173.457ms | https://yun.139.com/shareweb/#/w/i/2sUfBKpu5QBqz |  |
| 盘尊社区 | 失败 | 视频详情 | 6.883秒 | 0.468ms | 0.001ms | 0.001ms | 2.394秒 | 1.309秒 | 0.0ms | 0.0ms |  | 详情缺少播放源或播放列表 |
| 盘聚 | 成功 |  | 5.091秒 | 1.018ms | 0.003ms | 0.003ms | 1.853秒 | 1.124秒 | 723.186ms | 1.388秒 | https://pan.baidu.com/s/1NiQJW0DJBw8FR_Y1_k8Yig?pwd=ojmk |  |
| 短剧优选 | 成功 |  | 5.842秒 | 0.798ms | 666.538ms | 3.946秒 | 780.495ms | 370.35ms | 0.002ms | 77.309ms | https://cdn-vod-playlet.wtzw.com/asset/b936eac78f199fd865afbe3c5b707e7f/play_multi_video/6f7310c287644b7c813ab8e2eb7a4a0c/f1223068052dd7f1bc88718af4b2c0e4.m3u8 |  |
| 短剧网 | 成功 |  | 3.154秒 | 0.251ms | 0.0ms | 0.0ms | 1.387秒 | 1.534秒 | 0.005ms | 231.858ms | https://pan.quark.cn/s/5be7fea2409f |  |
| 糯米 | 成功 |  | 2.625秒 | 0.317ms | 0.0ms | 543.729ms | 754.184ms | 528.406ms | 389.551ms | 406.607ms | https://vip.123pan.cn/1853039965/dy/东北往事极恶不赦.m3u8 |  |
| 红果短剧 | 失败 | 分类列表 | 2.451秒 | 0.32ms | 0.001ms | 0.001ms | 208.724ms | 0.0ms | 0.0ms | 0.0ms |  | 分类视频列表为空 |
| 网易云音乐 | 失败 | 未预期异常 | 1.444秒 | 0.277ms | 0.001ms | 587.482ms | 663.965ms | 0.006ms | 190.03ms | 0.0ms |  | Expecting value: line 1 column 1 (char 0) |
| 耐视点播 | 失败 | 分类列表 | 3.858秒 | 0.298ms | 0.0ms | 0.001ms | 1.804秒 | 0.0ms | 0.0ms | 0.0ms |  | 分类视频列表为空 |
| 腾讯视频 | 成功 |  | 2.728秒 | 1.042ms | 0.001ms | 1.478秒 | 294.274ms | 718.309ms | 0.002ms | 235.159ms | https://v.qq.com/x/cover/mzc002009g0nh88/w4102d4f4ur.html |  |
| 至臻 | 失败 | 未预期异常 | 10.014秒 | 0.396ms | 0.0ms | 0.001ms | 10.012秒 | 0.0ms | 0.0ms | 0.0ms |  | HTTPConnectionPool(host='www.miqk.cc', port=80): Max retries exceeded with url: /index.php/vod/show/id/1/page/1.html (Caused by ConnectTimeoutError(<HTTPConnection(host='www.miqk.cc', port=80) at 0x7526343706b0>, 'Connection to www.miqk.cc timed out. (connect timeout=10)')) |
| 芒果 | 成功 |  | 1.598秒 | 0.295ms | 0.0ms | 0.001ms | 352.631ms | 903.862ms | 0.001ms | 340.29ms | https://www.mgtv.com/b/731684/24256393.html |  |
| 茶杯狐 | 失败 | 地址校验 | 17.42秒 | 0.515ms | 0.001ms | 1.438秒 | 1.317秒 | 1.113秒 | 2.24秒 | 3.296秒 | https://vip.ffzy-video.com/20260305/38855_8aecd51d/index.m3u8 | HTTP 403 |
| 虎斑 | 成功 |  | 1.97秒 | 0.342ms | 0.0ms | 0.001ms | 350.112ms | 646.591ms | 0.01ms | 972.051ms | https://pan.baidu.com/s/1aTT5yy3QuYPxWz-s4vz4aA?pwd=b5b5 |  |
| 蜡笔 | 成功 |  | 3.774秒 | 0.465ms | 0.0ms | 0.001ms | 1.362秒 | 795.119ms | 0.003ms | 1.615秒 | https://pan.baidu.com/s/1NiPgbk9_FIhSYfmGm-Cqxg?pwd=q5m6 |  |
| 袋鼠影视 | 失败 | 地址校验 | 10.721秒 | 0.45ms | 0.001ms | 0.001ms | 1.167秒 | 940.968ms | 1.78秒 | 1.924秒 | https://vip.dytt-kan.com/20260330/12924_fae034d2/index.m3u8 | HTTP 403 |
| 路漫漫 | 成功 |  | 6.293秒 | 0.752ms | 0.001ms | 0.0ms | 1.661秒 | 1.211秒 | 3.215秒 | 204.499ms | https://groupvideo.photo.qq.com/1071_0bc354askaabemajexgxvfus53yeexxqcjka.f0.mp4?dis_k=e640e628c0d8b4f7222fbe4ce1aaf919&dis_t=1778493030 |  |
| 酷我听书 | 成功 |  | 5.157秒 | 0.561ms | 0.001ms | 393.299ms | 104.411ms | 202.733ms | 155.662ms | 206.127ms | http://cz.sycdn.kuwo.cn/8cf5267fe2915fbbff127e125df4618e/6a01a666/resource/m1/34/31/3390639861.wma?bitrate$128&format$wma&source$kwplayerhd_ar_4.3.0.8_tianbao_T1A_qirui.apk&type$convert_url_with_sign&user$&loginUid$ |  |
| 酷狗音乐 | 成功 |  | 1.974秒 | 0.546ms | 515.942ms | 349.872ms | 302.88ms | 348.329ms | 375.345ms | 79.937ms | http://fsdg360.hw.kugou.com/202605111750/b8354090d0d9785f5fcc004ab5e1b32b/v3/c23347e375a1e1791a0204a70e9ee204/yp/p_0_960123/ap1013_us0_mic85f71c379c462618de1399950957c33_pi6101_mx745188085_qu128_s1023251.mp3?ft=car_203559_10049&fts=b05bb02d44717442054bac7624ed9a29&ext=.mp3 |  |
| 金牌 | 成功 |  | 3.248秒 | 0.276ms | 0.0ms | 1.818秒 | 294.238ms | 286.574ms | 325.753ms | 521.724ms | https://ppvod011.blbtgg.com/splitOut/20260318/1267932/V20260318194542050871267932/index.m3u8?auth_key=1778493028-01775c72dcd54d6ab8b1853d3b2346cc-0-6b93b389c2a44661855ddee1f7555967 |  |
| 闪电 | 成功 |  | 3.603秒 | 0.289ms | 0.0ms | 0.0ms | 1.95秒 | 1.266秒 | 0.01ms | 385.352ms | https://drive.uc.cn/s/e145774bc14b4?public=1 |  |
| 雷鲸 | 失败 | 视频详情 | 6.744秒 | 0.588ms | 0.001ms | 0.002ms | 1.703秒 | 2.331秒 | 0.0ms | 0.0ms |  | 详情缺少播放源或播放列表 |
| 飞快TV | 成功 |  | 11.436秒 | 0.37ms | 0.001ms | 0.0ms | 3.487秒 | 3.365秒 | 3.302秒 | 1.281秒 | https://cdn.yzzyvip-29.com/20260511/23657_6c73721a/index.m3u8 |  |
| 高清猫 | 失败 | 分类列表 | 1.889秒 | 0.366ms | 0.0ms | 0.003ms | 959.422ms | 0.0ms | 0.0ms | 0.0ms |  | 分类视频列表为空 |
| 魔方APP | 失败 | 首页分类 | 1.176秒 | 0.461ms | 0.002ms | 1.175秒 | 0.0ms | 0.0ms | 0.0ms | 0.0ms |  | 分类列表为空 |
| 麦田影院 | 失败 | 未预期异常 | 1.672秒 | 0.428ms | 0.001ms | 0.001ms | 1.669秒 | 0.0ms | 0.0ms | 0.0ms |  | ('Connection aborted.', RemoteDisconnected('Remote end closed connection without response')) |
| 黑猫APP | 成功 |  | 12.805秒 | 0.46ms | 0.002ms | 3.658秒 | 963.146ms | 945.697ms | 781.35ms | 86.979ms | https://v26-show.douyinvod.com/8960cf7c51aea1cf8360e0b58495c1b3/6a0204b9/video/tos/cn/tos-cn-v-5f73e7/o0lr0UpopnA09eDtBlFEg9DFa7H11VrEEyf6Na/ |  |
