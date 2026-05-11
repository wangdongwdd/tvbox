# 爬虫校验报告

- 生成时间: 2026-05-11T17:10:23+08:00
- 爬虫目录: /home/harold/workspace/atv-spiders/py
- 输出目录: /home/harold/workspace/tvbox-resources
- 并发线程数: 16
- 总耗时(ms): 119638.799
- 总数: 80
- 成功: 49
- 失败: 31

## 阶段失败统计

| 阶段 | 数量 |
| --- | ---: |
| 模块加载 | 0 |
| 初始化 | 0 |
| 首页分类 | 1 |
| 分类列表 | 7 |
| 视频详情 | 2 |
| 播放地址 | 0 |
| 地址校验 | 13 |
| 未预期异常 | 8 |

## 明细结果

| 爬虫 | 状态 | 失败阶段 | 总耗时 | 模块加载 | 初始化 | 首页分类 | 分类列表 | 视频详情 | 播放地址 | 地址校验 | 返回地址 | 错误信息 |
| --- | --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- | --- |
| 4K指南 | 成功 |  | 5344.507 | 17.7 | 0.001 | 0.002 | 2660.484 | 2280.341 | 0.004 | 385.011 | https://pan.quark.cn/s/e0726c4989dc |  |
| AAZ音乐 | 失败 | 未预期异常 | 10074.438 | 17.423 | 0.001 | 10028.16 | 0.0 | 0.0 | 0.0 | 0.0 |  | HTTPSConnectionPool(host='www.aaz.cx', port=443): Read timed out. (read timeout=10) |
| Atvp | 失败 | 未预期异常 | 73.173 | 72.372 | 0.004 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 |  | Atvp source is empty |
| PPnix | 成功 |  | 7106.631 | 65.187 | 0.001 | 0.001 | 2262.119 | 3083.889 | 0.008 | 1694.224 | https://www.ppnix.com/info/m3u8/8138/1080P.m3u8 |  |
| QQ音乐 | 成功 |  | 1539.353 | 20.256 | 0.012 | 0.006 | 570.962 | 438.974 | 338.857 | 131.873 | https://isure.stream.qqmusic.qq.com/F0000040rOp00lZYHC.flac?guid=d1d14732c38bd66eeadacc2d8ff5fcb4&vkey=BB5B6CF95B250327CC9E477ACC50C9C5687E94B828385BC82371DE3FBD850EF465BA488BBDBE33F67CEBA29C29E744888AAE672E1F5E0F7D__v2b9abc83&uin=1152921504846230218&fromtag=119114&redirect=1 |  |
| UVod | 失败 | 地址校验 | 12378.98 | 69.565 | 1987.885 | 1975.607 | 2343.672 | 2091.091 | 2169.561 | 1740.646 | https://file-endpoint33.oledsa.com/content/dy-ljwl-shd-20260509-01.mp4/index.m3u8?st=qH_X1RSF4qZyeNYIpj7ZtA&e=1778505033 | HTTPSConnectionPool(host='file-endpoint33.oledsa.com', port=443): Max retries exceeded with url: /content/dy-ljwl-shd-20260509-01.mp4/index.m3u8?st=qH_X1RSF4qZyeNYIpj7ZtA&e=1778505033 (Caused by SSLError(SSLCertVerificationError(1, '[SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed: unable to get local issuer certificate (_ssl.c:1081)'))) |
| libvio | 失败 | 分类列表 | 1967.408 | 16.488 | 0.001 | 0.001 | 1908.987 | 0.0 | 0.0 | 0.0 |  | 分类视频列表为空 |
| youknow | 成功 |  | 13688.334 | 16.395 | 0.001 | 0.001 | 3338.09 | 2753.518 | 3187.774 | 4391.155 | https://vip.dytt-tvs.com/20260504/18941_6de7c6c7/index.m3u8 |  |
| youtube | 失败 | 分类列表 | 2361.287 | 18.493 | 0.004 | 0.038 | 2304.756 | 0.0 | 0.0 | 0.0 |  | 分类视频列表为空 |
| 七味 | 成功 |  | 119632.475 | 14.132 | 0.001 | 0.001 | 2346.679 | 2386.864 | 112577.81 | 2277.683 | https://www.pcmp4.com/py/94740-3-1.html |  |
| 不太灵 | 失败 | 未预期异常 | 19328.681 | 17.384 | 0.0 | 3384.368 | 4081.81 | 11817.689 | 0.0 | 0.0 |  | HTTPSConnectionPool(host='web5.mukaku.com', port=443): Read timed out. (read timeout=10) |
| 世纪音乐 | 失败 | 地址校验 | 816.452 | 17.806 | 0.001 | 227.761 | 170.164 | 149.176 | 0.004 | 227.388 | https://www.4c44.com/data/down.php?ac=music&id=ydektetnwt | HTTP 403 |
| 两个BT | 成功 |  | 10128.089 | 22.541 | 0.001 | 0.001 | 2191.119 | 1889.955 | 3860.313 | 2129.916 | https://zijieapi.douyinbyte.com/m3u8/dd0ca2ca11fcbf34e0a0d769ad4f7180.m3u8 |  |
| 乌云影视 | 成功 |  | 16802.496 | 17.832 | 0.001 | 1998.449 | 1865.778 | 6420.111 | 0.019 | 6475.186 | https://d1jdnmkc1n5cn4.cloudfront.net/gen_overseas/https://s2.bfllvip.com/video/yanxiaxing/a6ef854c0c1f/index.m3u8 |  |
| 乐兔 | 失败 | 未预期异常 | 10112.521 | 18.663 | 0.001 | 0.001 | 10055.307 | 0.0 | 0.0 | 0.0 |  | HTTPSConnectionPool(host='www.letu.me', port=443): Read timed out. (read timeout=10) |
| 二小 | 成功 |  | 7347.559 | 16.995 | 0.001 | 0.002 | 4279.469 | 1821.681 | 0.003 | 1191.757 | https://pan.baidu.com/s/1aWSIgHVAv9PM6LOEZh6V6A?pwd=byd2 |  |
| 人人电影 | 失败 | 分类列表 | 2533.483 | 0.311 | 0.0 | 0.0 | 2533.035 | 0.0 | 0.0 | 0.0 |  | 分类视频列表为空 |
| 人人视频 | 失败 | 地址校验 | 1304.824 | 0.464 | 0.001 | 170.11 | 282.136 | 266.305 | 400.622 | 184.437 | https://a3fkpcuk2gkkpmr.302.fledgecloud.com:56782/zj-302-cdn.bwcgee.cn/60b815c142c671f1ac975017e1f90402/30ffc804ae454cdaa23c4518d492908d-0e6b5348788a46aeb1399e154ae316e5-ld.mp4?auth_key=1778505024-9f17513aa51246e1aeadbb6cc366a44b-0-43911a33a7f86f318b20e637b4037277&clientType=web_pc&clientVersion=1.0.0&parseUsage=PLAY&uid=0&rk=f89bf47c27dd4c368672508de12e4fba&hevc=false&seasonId=57181 | HTTP 403 |
| 优酷 | 成功 |  | 1217.888 | 0.664 | 0.001 | 0.005 | 317.963 | 606.218 | 0.004 | 292.336 | https://v.youku.com/v_show/id_XNjUxODQ1MzE1Ng==.html |  |
| 低端影视 | 成功 |  | 5574.101 | 0.285 | 0.001 | 0.001 | 2564.216 | 2851.391 | 0.008 | 157.743 | https://hn.bfvvs.com/play/eXDLzQVe/index.m3u8 |  |
| 修罗 | 失败 | 地址校验 | 11690.627 | 0.381 | 0.0 | 0.001 | 2640.12 | 1754.044 | 4849.278 | 2445.878 | https://v.xlys.ltd.ua/obj/0D064C8B0DB542E409CC060C12EE6D2B1B98DF19BF0AD5DC7172E25F4B598C9F | HTTP 403 |
| 凡客TV | 成功 |  | 21636.188 | 0.32 | 0.001 | 0.001 | 9894.193 | 2649.695 | 4864.94 | 4226.681 | https://fktv.me/ysapi/m3u8/p/59a97924eaa4a4151f13a9dd67ce4eb5.m3u8 |  |
| 剧圈圈 | 成功 |  | 21260.891 | 0.383 | 0.0 | 0.0 | 3478.571 | 3425.806 | 10492.766 | 3862.906 | https://www.jqqzx.cc/play/62945-3-1.html |  |
| 剧迷 | 失败 | 地址校验 | 9947.721 | 0.288 | 0.0 | 0.001 | 2100.19 | 2347.027 | 2691.178 | 2808.546 | https://vip.dytt-see.com/20260505/36518_39a596c5/index.m3u8 | HTTP 403 |
| 博看听书 | 成功 |  | 4411.36 | 0.254 | 0.0 | 3232.842 | 291.111 | 812.366 | 0.002 | 74.467 | http://audio.bookan.com.cn/video1/audio/20200706001/aache64_133068a2.m4a |  |
| 厂长资源 | 失败 | 分类列表 | 7747.136 | 0.638 | 0.104 | 0.001 | 7746.067 | 0.0 | 0.0 | 0.0 |  | 分类视频列表为空 |
| 双星 | 成功 |  | 1007.144 | 0.506 | 396.22 | 0.005 | 204.168 | 181.953 | 0.004 | 223.476 | https://pan.quark.cn/s/aefc43744bd3 |  |
| 听书 | 成功 |  | 1283.022 | 0.916 | 80.295 | 0.001 | 195.69 | 496.89 | 406.995 | 101.476 | http://audiopay.cos.tx.xmcdn.com/download/1.0.0/storages/b817-audiopay/16/AA/GKwRIaIGGaRGADgE-gEx_hMS-aacv2-48K.m4a?sign=602865530bda687fcb9dde202e1f0eee&buy_key=FM&token=3113&timestamp=1778490631&duration=453 |  |
| 听友FM | 成功 |  | 13990.886 | 0.888 | 0.001 | 2656.299 | 2968.287 | 3792.749 | 4392.468 | 179.198 | https://file.hgeuz.cn/stream/eJwANwDI_wJVZgVKIIrU0ECux-GJ1PSt38ahythCqsH-r9TAQ4rj5F94rOjbQKjk063xyIX2z3hfeGcIHF4BAAD__5DtISY.?ts=1778488205&sign=625c3a14e1a6c8df8d4d35663d542452 |  |
| 四万影视 | 失败 | 未预期异常 | 1764.933 | 0.283 | 0.0 | 0.0 | 1762.742 | 0.0 | 0.0 | 0.0 |  | HTTPSConnectionPool(host='40000.me', port=443): Max retries exceeded with url: /api/maccms?ac=detail&t=20&pg=1&by=time (Caused by SSLError(SSLCertVerificationError(1, '[SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed: self-signed certificate (_ssl.c:1081)'))) |
| 在线之家 | 成功 |  | 9433.115 | 0.332 | 0.0 | 0.0 | 2317.623 | 4245.068 | 2609.814 | 259.753 | https://media-sxty-fy-corp.sx3oss.ctyunxs.cn/CORPCLOUD/f076ccf5-a095-45a2-b086-cbf66f4aa40d.mp4?response-content-disposition=attachment%3Bfilename%3D%22%E9%93%81%E8%A1%80%E6%88%98%E5%A3%AB%E6%9D%80%E6%88%AE%E4%B9%8B%E5%9C%B02025HD1080P.mp4%22%3Bfilename*%3DUTF-8%27%27%25E9%2593%2581%25E8%25A1%2580%25E6%2588%2598%25E5%25A3%25AB%25E6%259D%2580%25E6%2588%25AE%25E4%25B9%258B%25E5%259C%25B02025HD1080P.mp4&x-amz-CLIENTNETWORK=UNKNOWN&x-amz-CLOUDTYPEIN=CORP&x-amz-CLIENTTYPEIN=UNKNOWN&Signature=/nJLhyEJivvBkuxOJdnCRWWa4yE%3D&AWSAccessKeyId=0Lg7dAq3ZfHvePP8DKEU&Expires=1778499884&x-amz-limitrate=102400&response-content-type=video/mp4&x-amz-FSIZE=2183471772&x-amz-UID=10000004591358&x-amz-UFID=31374317010337932 |  |
| 多多 | 成功 |  | 1953.537 | 0.285 | 0.0 | 0.0 | 574.088 | 421.346 | 0.003 | 957.271 | https://pan.baidu.com/s/1tCpt9UMVoL9OxQyvpKUYZA?pwd=yyds |  |
| 奕搜 | 成功 |  | 5198.321 | 0.265 | 0.0 | 0.0 | 2685.5 | 2263.231 | 0.016 | 248.626 | https://pan.quark.cn/s/e5345bdd71f6 |  |
| 如意资源 | 成功 |  | 10842.419 | 0.322 | 0.0 | 0.006 | 5974.547 | 2326.115 | 0.004 | 2540.887 | https://svip.ryiplay18.com/20260508/6294_cfc8934f/index.m3u8 |  |
| 布布影视 | 成功 |  | 7247.213 | 0.298 | 0.0 | 0.0 | 2130.924 | 2141.733 | 2629.582 | 344.051 | https://c167-obsdaz-ykj-01.obs.dualstack.cidc-rp-2006.joint.cmecloud.cn/1810c8ff2a78456b9348fadfe7ab0fd0086?response-content-disposition=attachment%3B%20filename%2A%3DUTF-8%27%274K.mp4&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20260511T091040Z&X-Amz-SignedHeaders=host&X-Amz-Expires=86400&X-Amz-Credential=AH4RWOMWLEL7ROYSF2S5%2F20260511%2Fcidc-rp-2006%2Fs3%2Faws4_request&t=2&u=1261698636582652615&ot=family&oi=1263000283947275586&f=FibTFWRt8ncqZsYDWQP5LF5BI3oB5_LXK&ext=eyJ1dCI6MX0%3D&X-Amz-Signature=e6411f7091b621576bb8d7d909861b24af7ccc31534058ba5f922f9b3e3970f0 |  |
| 微观短剧 | 成功 |  | 1007.016 | 0.413 | 0.029 | 219.097 | 275.267 | 318.424 | 0.002 | 193.166 | https://tv-video.cdn.drama.9ddm.com/22/A0/22A0BFFF46651CC23355B115F6307653.mp4?timestamp=1778490635&sign=8ed8a07d229ab909d1ec0acbb4c90122 |  |
| 新韩剧网 | 成功 |  | 8481.589 | 0.231 | 0.0 | 0.0 | 2376.709 | 1735.055 | 1704.59 | 2664.439 | https://cdn.yzzyvip-29.com/20260201/16425_49d7d186/index.m3u8 |  |
| 星星短剧 | 成功 |  | 1243.749 | 0.203 | 0.0 | 0.0 | 462.744 | 634.136 | 0.003 | 146.182 | https://img.novel.wsljf.xyz/shortPlay-mp4/420424102051841/EvnIm1746774634078/abc6208e-390b-4533-a1a4-b9e5741cc384/540x960/output.m3u8 |  |
| 木偶 | 成功 |  | 4616.466 | 0.307 | 0.0 | 0.0 | 2160.795 | 2204.33 | 0.008 | 250.7 | https://115cdn.com/s/swf0zna36dh?password=p696 |  |
| 樱花动漫 | 失败 | 地址校验 | 17328.695 | 0.327 | 0.001 | 0.001 | 4225.688 | 4583.181 | 6593.55 | 1925.021 | https://v.lzcdn27.com/20260215/5293_35f4e89c/index.m3u8 | HTTP 404 |
| 橘子TV | 成功 |  | 17576.686 | 0.644 | 2486.652 | 2272.318 | 2446.613 | 2698.253 | 7589.623 | 81.897 | https://ad.kpyy258.com/m3u87/share/7256561/7452333/20260503/185008/1080/index.m3u8?sign=8b8f3035f3fd40c60c2ce7926d39c9da&t=1778490653 |  |
| 欧歌 | 成功 |  | 6075.092 | 0.428 | 0.0 | 0.0 | 2734.26 | 1767.662 | 0.006 | 1572.261 | https://pan.baidu.com/s/1plecwmM4KBFNk_hU52nJIQ?pwd=8888 |  |
| 毒舌影视 | 失败 | 地址校验 | 12758.022 | 0.341 | 0.001 | 2581.573 | 2393.275 | 2462.777 | 2647.886 | 2671.682 | https://cdn.yddsha2.com/m3u87/share/7398015/7593829/20260511/121559/1080/master.m3u8 | HTTPSConnectionPool(host='cdn.yddsha2.com', port=443): Max retries exceeded with url: /m3u87/share/7398015/7593829/20260511/121559/1080/master.m3u8 (Caused by SSLError(SSLEOFError(8, '[SSL: UNEXPECTED_EOF_WHILE_READING] EOF occurred in violation of protocol (_ssl.c:1081)'))) |
| 河马短剧 | 成功 |  | 2747.38 | 0.311 | 0.001 | 669.804 | 654.787 | 1356.928 | 0.026 | 64.573 | https://dzzt-video.cbread.cn/620fddcdecb4360a618e381ed2e5f87d/6a02ec10/58/5x3/53x4/534x6/53468100014/612428785_1/612428785.720p.narrowv3.mp4 |  |
| 滴答影视 | 成功 |  | 3988.853 | 0.354 | 0.001 | 0.001 | 1746.813 | 2031.323 | 0.005 | 209.789 | https://pan.quark.cn/s/98a640e2e3ee |  |
| 潮流APP | 成功 |  | 803.345 | 0.292 | 0.002 | 129.602 | 116.83 | 155.257 | 309.107 | 91.26 | http://210.16.164.53:9090/nby/m3u8/getM3u8?name=jx.91by.top&time=1778490641533&url=NBY-e84585334a25c5b49078dfac81549a0b.m3u8 |  |
| 爱奇艺 | 成功 |  | 4763.589 | 0.606 | 0.017 | 3197.428 | 1045.681 | 256.895 | 0.002 | 261.116 | http://www.iqiyi.com/v_vd55wo89uk.html |  |
| 爱看 | 失败 | 地址校验 | 6390.726 | 0.248 | 0.0 | 0.001 | 717.647 | 3736.443 | 0.004 | 1935.964 | https://vv.jisuzyv.com/play/epY8RMra/index.m3u8 | HTTPSConnectionPool(host='vv.jisuzyv.com', port=443): Max retries exceeded with url: /play/epY8RMra/index.m3u8 (Caused by SSLError(SSLCertVerificationError(1, '[SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed: unable to get local issuer certificate (_ssl.c:1081)'))) |
| 独播库 | 成功 |  | 7445.059 | 0.248 | 0.0 | 0.001 | 1818.492 | 1853.28 | 1929.912 | 1842.443 | https://vid.dbokutv.com/20260416/ppotb62-S71lT2yliZApDBSvkYzBsrmD3fpCJ4nBsHgTcyo5xOy6ejP7DiStHqR2qmCIqmCp8nE44oGZakRN0q/chunklist.m3u8 |  |
| 玩偶哥哥 | 成功 |  | 5062.408 | 0.257 | 0.0 | 0.0 | 1965.963 | 1934.822 | 0.004 | 1160.996 | https://pan.baidu.com/s/1hbYaibe8p-HfdhIUP7vvFA?pwd=f8x5 |  |
| 玩偶聚合 | 成功 |  | 5953.172 | 0.35 | 0.0 | 0.064 | 2046.197 | 2721.339 | 0.002 | 1184.763 | https://pan.baidu.com/s/1wlGptZsrXaSU5zwTNON1MA?pwd=wogg |  |
| 瓜子 | 成功 |  | 8250.615 | 0.311 | 0.001 | 0.02 | 2023.645 | 3864.409 | 1895.99 | 465.064 | https://vd.hxcztech.com/1b506f5009a9b786d0fbe876b0cb3b0c/20260511171050/decry/vd/20260311/MjYwZjE1YTRkO/172631/1998_1080/aac/h264/hls/decrypt/index.m3u8 |  |
| 百度短剧 | 成功 |  | 2118.693 | 0.259 | 0.0 | 496.268 | 246.073 | 1063.803 | 222.068 | 89.367 | http://vd3.bdstatic.com/mda-rh54j6is12ydd0q3/1080p/mv_cae264_backtrack_1080p_normal/1754453773225130912/mda-rh54j6is12ydd0q3.mp4?v_from_s=haokan-ui-video-hna |  |
| 盘Ta | 成功 |  | 1015.098 | 0.384 | 0.001 | 320.767 | 251.591 | 273.186 | 0.024 | 168.526 | https://yun.139.com/shareweb/#/w/i/2sUfBKpu5QBqz |  |
| 盘尊社区 | 失败 | 视频详情 | 4763.575 | 0.502 | 0.001 | 0.001 | 2412.858 | 2348.675 | 0.0 | 0.0 |  | 详情缺少播放源或播放列表 |
| 盘聚 | 成功 |  | 7343.014 | 0.474 | 0.001 | 0.001 | 1807.077 | 1986.986 | 1967.209 | 1580.798 | https://pan.baidu.com/s/1NiQJW0DJBw8FR_Y1_k8Yig?pwd=ojmk |  |
| 短剧优选 | 成功 |  | 6105.836 | 0.962 | 597.563 | 4016.486 | 930.795 | 490.373 | 0.003 | 68.883 | https://cdn-vod-playlet.wtzw.com/asset/b936eac78f199fd865afbe3c5b707e7f/play_multi_video/6f7310c287644b7c813ab8e2eb7a4a0c/f1223068052dd7f1bc88718af4b2c0e4.m3u8 |  |
| 短剧网 | 成功 |  | 3942.963 | 1.561 | 0.002 | 0.001 | 2732.715 | 961.585 | 0.01 | 245.586 | https://pan.quark.cn/s/5be7fea2409f |  |
| 糯米 | 成功 |  | 2430.785 | 0.492 | 0.001 | 311.322 | 671.536 | 273.101 | 407.593 | 764.978 | https://vip.123pan.cn/1853039965/dy/东北往事极恶不赦.m3u8 |  |
| 红果短剧 | 失败 | 分类列表 | 281.227 | 0.324 | 0.0 | 0.0 | 280.752 | 0.0 | 0.0 | 0.0 |  | 分类视频列表为空 |
| 网易云音乐 | 失败 | 未预期异常 | 1645.789 | 0.396 | 0.0 | 641.674 | 792.805 | 0.015 | 206.878 | 0.0 |  | Expecting value: line 1 column 1 (char 0) |
| 耐视点播 | 失败 | 分类列表 | 5323.242 | 0.256 | 0.0 | 0.0 | 5322.424 | 0.0 | 0.0 | 0.0 |  | 分类视频列表为空 |
| 腾讯视频 | 成功 |  | 2507.379 | 0.811 | 0.0 | 1089.638 | 311.391 | 822.089 | 0.003 | 282.163 | https://v.qq.com/x/cover/mzc002009g0nh88/w4102d4f4ur.html |  |
| 至臻 | 成功 |  | 5276.972 | 0.366 | 0.001 | 0.001 | 3266.223 | 1745.511 | 0.007 | 264.156 | https://pan.quark.cn/s/b3e194803b59 |  |
| 芒果 | 成功 |  | 1327.128 | 0.441 | 0.0 | 0.001 | 396.091 | 517.341 | 0.001 | 412.595 | https://www.mgtv.com/b/731684/24256393.html |  |
| 茶杯狐 | 失败 | 地址校验 | 12374.187 | 1.045 | 0.001 | 3913.676 | 1375.842 | 1140.997 | 2160.33 | 3781.487 | https://vip.ffzy-plays.com/20260511/53449_d36f905d/index.m3u8 | HTTP 403 |
| 虎斑 | 成功 |  | 5720.616 | 0.506 | 0.001 | 0.001 | 2083.173 | 2725.291 | 0.021 | 910.29 | https://pan.baidu.com/s/1aTT5yy3QuYPxWz-s4vz4aA?pwd=b5b5 |  |
| 蜡笔 | 成功 |  | 5146.577 | 0.38 | 0.0 | 0.001 | 3326.634 | 799.045 | 0.013 | 1019.965 | https://pan.baidu.com/s/1NiPgbk9_FIhSYfmGm-Cqxg?pwd=q5m6 |  |
| 袋鼠影视 | 失败 | 地址校验 | 4453.057 | 0.529 | 0.0 | 0.001 | 1286.589 | 832.225 | 856.295 | 1475.63 | https://v10.baofeng10.com/video/xiangxinwojiaxianzhizhenmianmu/5d222521d913/index.m3u8 | HTTP 404 |
| 路漫漫 | 失败 | 未预期异常 | 19841.955 | 0.41 | 0.001 | 0.001 | 1424.392 | 1228.133 | 17185.342 | 0.0 |  | HTTPSConnectionPool(host='yun.92cj.com', port=443): Max retries exceeded with url: /yunbox/?type=vxdev&vid=1071_0bc354askaabemajexgxvfus53yeexxqcjka&referer=https://www.lmm85.com/play/8030_1_1.html (Caused by ConnectTimeoutError(<HTTPSConnection(host='yun.92cj.com', port=443) at 0x7ed5b76b9e50>, 'Connection to yun.92cj.com timed out. (connect timeout=15)')) |
| 酷我听书 | 失败 | 地址校验 | 4508.909 | 0.336 | 0.0 | 409.861 | 117.996 | 3681.574 | 140.531 | 157.23 | http://lv.sycdn.kuwo.cn/5612796c8193285bc329505fefb096e2/6a019d1e/resource/30106/trackmedia/long/M500002ZiI9a1sctnS.mp3?bitrate$128&format$mp3&source$kwplayerhd_ar_4.3.0.8_tianbao_T1A_qirui.apk&type$convert_url_with_sign&user$&loginUid$ | HTTP 403 |
| 酷狗音乐 | 成功 |  | 2210.431 | 2.274 | 595.138 | 333.298 | 424.618 | 386.1 | 413.489 | 54.21 | http://fsdg360.tx.kugou.com/202605111710/22d256027c87066e295611461503e1ad/v3/fe31adeed5e32b5c8716be52c9be5109/yp/p_0_960115/ap1013_us0_mic85f71c379c462618de1399950957c33_pi6101_mx330023250_qu128_s2916735058.mp3?ft=car_203559_10049&fts=b05bb02d44717442054bac7624ed9a29&ext=.mp3 |  |
| 金牌 | 成功 |  | 2849.851 | 0.294 | 0.0 | 1484.044 | 250.542 | 266.013 | 269.784 | 577.796 | https://ppvod011.blbtgg.com/splitOut/20260318/1267932/V20260318194542050871267932/index.m3u8?auth_key=1778490653-3b9338fdda634eebb6f902134635edfd-0-de8083f485cb88dbd34c4cb2d1019597 |  |
| 闪电 | 成功 |  | 4407.361 | 0.313 | 0.0 | 0.0 | 1152.498 | 2436.956 | 0.009 | 816.983 | https://drive.uc.cn/s/e145774bc14b4?public=1 |  |
| 雷鲸 | 失败 | 视频详情 | 4174.826 | 0.688 | 0.001 | 0.002 | 3194.571 | 979.23 | 0.0 | 0.0 |  | 详情缺少播放源或播放列表 |
| 飞快TV | 失败 | 地址校验 | 12103.471 | 0.292 | 0.0 | 0.001 | 3900.037 | 4108.74 | 3015.682 | 1078.246 | https://v10.baofeng10.com/video/mafukazhenshishenhua/2c2d27d77672/index.m3u8 | HTTP 404 |
| 高清猫 | 失败 | 分类列表 | 1060.648 | 0.467 | 0.0 | 0.005 | 1059.542 | 0.0 | 0.0 | 0.0 |  | 分类视频列表为空 |
| 魔方APP | 失败 | 首页分类 | 1568.404 | 1.44 | 0.005 | 1566.434 | 0.0 | 0.0 | 0.0 | 0.0 |  | 分类列表为空 |
| 麦田影院 | 失败 | 未预期异常 | 2386.088 | 0.534 | 0.001 | 0.002 | 2383.976 | 0.0 | 0.0 | 0.0 |  | ('Connection aborted.', RemoteDisconnected('Remote end closed connection without response')) |
| 黑猫APP | 失败 | 地址校验 | 6233.171 | 1.97 | 0.008 | 976.208 | 1054.528 | 909.409 | 0.016 | 3288.957 | https://vip.ffzy-plays.com/20260511/53448_da254751/index.m3u8 | HTTP 403 |
