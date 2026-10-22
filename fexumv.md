代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.9152youxi.cn/Article/details/gt2wjixohzm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ehwqpu.com/Article/details/gt2mzoxqvek.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jianghu66.top/Article/details/gt2ohowvhbv.html

[J06] 计算两时间之差
来源：http://dali.hywenlv.cn/Article/details/gt2syarauud.html

Py:   (end - start).total_seconds()
来源：http://dali.pycfn.com/Article/details/gt2ziusdwid.html

PHP:  $end->diff($start)->days;
来源：http://dali.yanxiufei.cn/Article/details/gt2djxrkeon.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gotoacloud.top/Article/details/gt2renqtvbe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yangfankeji.com/Article/details/gt2iatfinny.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangshuangyany.cn/Article/details/gt2saeelmpi.html

Go:   end.Sub(start).Hours()
来源：http://dali.mhx1999.top/Article/details/gt2ytrydclu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.kuanghao11.cn/Article/details/gt2ldpxienb.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gt2vualhxhe.html

[J07] 比较两个日期
来源：http://dali.yuxming.cn/Article/details/gt2beaapzgx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gt2yvfcaxkv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgufenzy.top/Article/details/gt2iptklzld.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gt2xgskjnzw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gt2xywovwfi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnqzz.top/Article/details/gt2ytrxzcuw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yueranfly.top/Article/details/gt2fpewcszy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gt2rbonobwg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2kevxcvuh.html

[J08] 提取年月日与星期
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dcvbqcqs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.meibo888.top/Article/details/gt2evuwetfq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hysaishi.cn/Article/details/gt2cxtorddj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxuanxn.top/Article/details/gt2cdsgousw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yangfankeji.com/Article/details/gt2gbwgvova.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tanke756.top/Article/details/gt2bolblvoh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gt2qfvppplt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.birdmap.top/Article/details/gt2oybpnsbw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nwbrower.top/Article/details/gt2bxyvpkcb.html

[J09] 时区处理
来源：http://dali.fengsongda.top/Article/details/gt2rvdrgnpg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.vqdsnc.cn/Article/details/gt2ddfrenob.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhoulong.xyz/Article/details/gt2nyejcmud.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gt2xzqrsqhf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gt2nndjjklj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.kuanghao11.cn/Article/details/gt2bckhsbiy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.quarkkingdee.top/Article/details/gt2zgnkqxmk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gt2duwmhkeh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuanzx.com/Article/details/gt2lqhwenar.html

[J10] 取今天 / 本月第一天
来源：http://dali.pycfn.com/Article/details/gt2insgpjic.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgufenzy.top/Article/details/gt2uwxjoucx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhixingplan.top/Article/details/gt2dnwvifoc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xinyue.icu/Article/details/gt2pfpdxonm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2lyriadak.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj202588.top/Article/details/gt2rwocwkzi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnxiangtu.top/Article/details/gt2ftqmmgwa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwgydicp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gt2pumzcmtf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2thjdrsub.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gt2ggtsjbdt.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2zdsvvagz.html

[K01] 对象转 JSON 字符串
来源：http://dali.xylfe.cn/Article/details/gt2iivzxuoy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gt2clwvmcix.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gt2cxrfmzxq.html

JS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gt2dvfpnbdj.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2xezigfhz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sxryk.cn/Article/details/gt2jnmhxfox.html

Go:   json.Marshal(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2apntimlk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnxiangtu.top/Article/details/gt2lndicybq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuanzx.com/Article/details/gt2tqernzpe.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pekcowra.html

Py:   json.loads(s)
来源：http://dali.sweek.top/Article/details/gt2cqzdjobd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cheryme.top/Article/details/gt2pxlowiju.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2sssroaxd.html

TS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gt2vyskrcak.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2dodybmsh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gt2lxvrvxol.html

Ruby: JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2yxquzyan.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.andypj.xyz/Article/details/gt2wmzmnevs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigfzy.top/Article/details/gt2jlwnaznd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gt2hqtvekbf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gt2ehqflfdq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2tlackemk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2buvdivkz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2lsnxeysr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gt2idftonjk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yonumen.top/Article/details/gt2xxfjimcl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hafdkogt.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ufsppshp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2nmlrbtsw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gt2bcmedrem.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2owffbqyd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gt2hvkekffu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gt2nkoadghd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uvtmqkou.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258.top/Article/details/gt2ygehjjaj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.smart0.xyz/Article/details/gt2tejolszk.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gt2mhiasccq.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2tsxvalgd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ybcxt.top/Article/details/gt2mgmfbxgt.html

JS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2gmifevts.html

TS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2aoqptmdf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cqqwz.cn/Article/details/gt2dhkdhdjb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rgoqadhm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gt2whujxucz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.quarkkingdee.top/Article/details/gt2kuvbkkev.html

[K06] 解析 URL 查询串
来源：http://dali.hysaishi.cn/Article/details/gt2biseqjsp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gt2gpofeofn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yangfankeji.com/Article/details/gt2kqivnhkx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gt2oobwbdtu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gt2ncupgsai.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gt2bgibgoqn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2dnitdljr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gt2brmfevdw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2ozggivrv.html

[K07] 进制转换
来源：http://dali.yj202588.top/Article/details/gt2ogeunxdt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2efqkpiyh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.feifeiyinyue.top/Article/details/gt2doqolgoo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bmmctkor.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2okijjxai.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqgdikpl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vgymwbmp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zycfv.cn/Article/details/gt2bxdrjznt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2dmilkbjv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gt2ipliszwc.html

Py:   pickle.dumps(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2adpbsxfj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.haohaochexian.top/Article/details/gt2apctijhb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gt2pmjdzcpv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gt2vlvdcyuf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gt2uejaupee.html

Go:   encoding/gob
来源：http://dali.hnqzz.top/Article/details/gt2czizgcyu.html

Ruby: Marshal.dump(obj)
来源：http://dali.316326.xyz/Article/details/gt2hueifkju.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gt2lonsltko.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2rtlqnkan.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gt2kkxeekwq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2qtrpnkyf.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gt2lgaeqcho.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.svipenyu.cn/Article/details/gt2iltoithy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gt2siofemse.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jjkafodh.html

TS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gt2lmdrdzpu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuetiantiany.cn/Article/details/gt2mznqripl.html

Go:   resp, err := http.Get(url)
来源：http://dali.xziqi.cn/Article/details/gt2acfionko.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnqzz.top/Article/details/gt2yqkjzonj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yongpay.top/Article/details/gt2arcyevtt.html

[L02] 发送 POST JSON
来源：http://dali.yueranfly.top/Article/details/gt2aqjaauyl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nwbrower.top/Article/details/gt2ktcnszdq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urrwsfym.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gt2ttatqepy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gt2tqznbxmu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgfzy.top/Article/details/gt2kezkqaiu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.316326.xyz/Article/details/gt2rmbfchuu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gt2shoyegil.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.svipenyu.cn/Article/details/gt2xtrqrrla.html

[L03] 设置自定义请求头
来源：http://dali.sysykeji.top/Article/details/gt2vhpdvpts.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gt2uxwryxgr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tanke756.top/Article/details/gt2uqryolac.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gt2nihiemin.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gt2grkecrwr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangshuangyany.cn/Article/details/gt2phkxmqde.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gt2xloxxbze.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqdzdvuk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gt2ywwvswff.html

[L04] 设置超时
来源：http://dali.chenzaomai.com/Article/details/gt2tesnljdi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.vqdsnc.cn/Article/details/gt2tnupxgro.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.mhx1999.top/Article/details/gt2oqihvhmb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gt2duvdmnwy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gt2jfthpshg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhoulong.xyz/Article/details/gt2hfokqdrn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yongpay.top/Article/details/gt2wjscyoci.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangdashe.top/Article/details/gt2jefapqki.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.c1oappe.top/Article/details/gt2jvrqdhiu.html

[L05] 上传文件（multipart）
来源：http://dali.wangshuangyany.cn/Article/details/gt2mpazdjhr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gt2bhauzkrw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.316326.xyz/Article/details/gt2obdwdzpw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gt2mmtyviql.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pifwdewf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gt2zceraldf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zdqjudy.top/Article/details/gt2vyummgry.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aizwys.cn/Article/details/gt2eksfpcfn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yongpay.top/Article/details/gt2kbotfiwp.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbphkjr.html

Py:   resp.json()
来源：http://dali.svipenyu.cn/Article/details/gt2xhyfnvki.html

PHP:  json_decode($body, true);
来源：http://dali.gotoacloud.top/Article/details/gt2fwzxnxtg.html

JS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gt2yeovpzcf.html

TS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2wjhdnbsr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oxdmaaws.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yotjhgsx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhongyouzk.top/Article/details/gt2mpmsyjed.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.andypj.xyz/Article/details/gt2bhkkejjx.html

[L07] 处理 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gt2jhhvelus.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xylfe.cn/Article/details/gt2nbpgaoye.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shzxlz.cn/Article/details/gt2spvustdm.html

JS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gt2dwywwvzc.html

TS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gt2qdjbllji.html

Java: resp.statusCode()
来源：http://dali.0kj1m.cn/Article/details/gt2qweelgmw.html

Go:   resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gt2yigqhjpg.html

Ruby: resp.code.to_i
来源：http://dali.haohaochexian.top/Article/details/gt2glaitgkt.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gt2nvpalxqy.html

[L08] 并发请求多个地址
来源：http://dali.fzhhl.top/Article/details/gt2imyftjgm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.snrcjt.cn/Article/details/gt2vxnutuua.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gt2ebvkxlch.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gt2xycdmdtp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gt2skcgvcmq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gt2xqshmftf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gt2sixielrp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenzaomai.com/Article/details/gt2qekrzzaa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yonumen.top/Article/details/gt2yzpyrtud.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2rmtocusn.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oeorbrox.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2ayikrxvm.html

[M01] 读取命令行参数
来源：http://dali.0kj1m.cn/Article/details/gt2uxgcizwi.html

Py:   sys.argv[1:]
来源：http://dali.guowangkeji.top/Article/details/gt2yblphbtz.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gt2pksxrukf.html

JS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gt2hqpmslyg.html

TS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gt2xdquxqym.html

Java: args 数组（main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gt2dmxclymq.html

Go:   os.Args[1:]
来源：http://dali.chenlongwang.top/Article/details/gt2bragcimz.html

Ruby: ARGV
来源：http://dali.jianghu66.top/Article/details/gt2jytexzgp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gt2cuwtutzr.html

[M02] 读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gt2gamecinp.html

Py:   os.environ.get("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2igjiqfrw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gt2ancacbuu.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2izdfgirj.html

TS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqucaeri.html

Java: System.getenv("HOME")
来源：http://dali.yj20258.top/Article/details/gt2rmdrnqwu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2uwdorjkb.html

Ruby: ENV["HOME"]
来源：http://dali.guannengcc.top/Article/details/gt2plcdedrn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.bjfxy.top/Article/details/gt2awataygr.html

[M03] 执行外部命令
来源：http://dali.cqqwz.cn/Article/details/gt2daxhgmoa.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gt2ohkkwoha.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gt2fcxrasds.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gt2rxufuknx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gt2ykezefxi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yueranfly.top/Article/details/gt2qupzvfop.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yangfankeji.com/Article/details/gt2cfjwawzr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gt2zwianyng.html

C#:   Process.Start("ls", "-l");
来源：http://dali.meibo888.top/Article/details/gt2pgqwedys.html

[M04] 获取当前工作目录
来源：http://dali.aibaodan.cn/Article/details/gt2uklgexio.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gt2odjikcwq.html

PHP:  getcwd();
来源：http://dali.hammf.cn/Article/details/gt2ygufasbi.html

JS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2aerdpbtj.html

TS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gt2fijwzqzq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gt2xhgjesam.html

Go:   os.Getwd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwbgcayw.html

Ruby: Dir.pwd
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2usujcbev.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wcbfihxh.html

[M05] 设置退出码
来源：http://dali.ybcxt.top/Article/details/gt2onkpphio.html

Py:   sys.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2aketkfqb.html

PHP:  exit(1);
来源：http://dali.chenlongwang.top/Article/details/gt2ilvgvgvd.html

JS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhudzoqd.html

TS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2pehopseq.html

Java: System.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2zprqfvvo.html

Go:   os.Exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2jhixotcv.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gt2gofkrkqa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigufen.top/Article/details/gt2zyppddcy.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gt2iujjdmih.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gt2hqbdqkdy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhoulong.xyz/Article/details/gt2pgktbxyt.html

JS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gt2kmvdejeu.html

TS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gt2tgsiokyf.html

Java: System.err.println("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2liairoft.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aibaodan.cn/Article/details/gt2tnxbxkpf.html

Ruby: warn "err"
来源：http://dali.haohaochexian.top/Article/details/gt2dzdvcnpv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jianghu66.top/Article/details/gt2hbroturj.html

[M07] 判断是否为主入口
来源：http://dali.cashguo.top/Article/details/gt2ytnvvqpm.html

Py:   if __name__ == "__main__":
来源：http://dali.shzxlz.cn/Article/details/gt2cvfrwszn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gt2clwwwfjr.html

JS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gt2mswdowvc.html

TS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gt2vvavbsxx.html

Java: public static void main(String[] args)
来源：http://dali.jinqigfzy.top/Article/details/gt2qwnnndap.html

Go:   func main()
来源：http://dali.smart0.xyz/Article/details/gt2bindgtgh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cdnleiting.top/Article/details/gt2klouvsnt.html

C#:   static void Main(string[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zeeahygj.html

[M08] 获取系统与运行时信息
来源：http://dali.hfpthk.cn/Article/details/gt2fndkwygu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bxlqzozh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangshuangyany.cn/Article/details/gt2emjtdgup.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2devevzzf.html

TS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gt2exsjqfod.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gt2anitipvo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daria6918.cn/Article/details/gt2guusqsbo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gt2wzkqyyqm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.haohaochexian.top/Article/details/gt2vnewpfhi.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2yumkhvyz.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gt2ouejjfob.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2rglhxjgg.html

[N01] 二分查找（有序数组）
来源：http://dali.guowangkeji.top/Article/details/gt2uvcnhxij.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2hhluihzd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guowangkeji.top/Article/details/gt2lahwxnmu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gt2ewjfrysv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cucaqled.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2ihyuamau.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2nybfxqir.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zycfv.cn/Article/details/gt2yktlkoux.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2vyojcwuz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgfzy.top/Article/details/gt2rdkuptlz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gt2dsjwumvw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhongyouzk.top/Article/details/gt2pqrqmwxr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gt2ogsywcou.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gt2cbfsusau.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cucudq.cn/Article/details/gt2wxektfph.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gt2ycmcwhyt.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gt2kdwnjmiw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yanxiufei.cn/Article/details/gt2uspftxqx.html

[N03] 快速排序（分治示例）
来源：http://dali.yueranfly.top/Article/details/gt2nvryoexi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.andypj.xyz/Article/details/gt2dmwasvus.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sxryk.cn/Article/details/gt2dxohshnv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gt2emykiyao.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmzapwtu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.iojbl.cn/Article/details/gt2hjzrdqxd.html


<!-- 参考信息 -->