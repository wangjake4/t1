代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wruxqqhf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2cskwsqug.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fcrphflw.html

Py:   now + timedelta(days=7)
来源：http://dali.wangdashe.top/Article/details/gt2mgmbpkhf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangshuangyany.cn/Article/details/gt2baeqcsvh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gt2znivyeqc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gt2ddysapjz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gogol.net.cn/Article/details/gt2racmzhab.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gt2mbxkwkzb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daria6918.cn/Article/details/gt2bidlzcrf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gt2dizsbrqt.html

[J06] 计算两时间之差
来源：http://dali.cdnleiting.top/Article/details/gt2swavyizn.html

Py:   (end - start).total_seconds()
来源：http://dali.cqqwz.cn/Article/details/gt2aitkkfrt.html

PHP:  $end->diff($start)->days;
来源：http://dali.jlsjyb.cn/Article/details/gt2gczekhcc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqwjtgt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gt2iciuzbqg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gt2qyjcyfmf.html

Go:   end.Sub(start).Hours()
来源：http://dali.redwolf501.top/Article/details/gt2xllpfzxa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sxryk.cn/Article/details/gt2lnchykpq.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhongyouzk.top/Article/details/gt2kcxrdwzn.html

[J07] 比较两个日期
来源：http://dali.9152youxi.cn/Article/details/gt2ojvypoaj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gt2ellevipn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuanzhike.top/Article/details/gt2vawmzmqq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wlzjenhj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gt2qahqoqgu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gt2ypugqepf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gaohongyu789.top/Article/details/gt2wsgrgwve.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gt2jxvccjlt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2jiswsdce.html

[J08] 提取年月日与星期
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gogevxio.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gt2ubpctbpi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuxming.cn/Article/details/gt2rxsbovak.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cdnleiting.top/Article/details/gt2yrwqaeme.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gaohongyu789.top/Article/details/gt2tqecvhht.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jiagoushi.top/Article/details/gt2bcytpmic.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.redwolf501.top/Article/details/gt2ytivyeth.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.bjfxy.top/Article/details/gt2flmtibxb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuxming.cn/Article/details/gt2sfqioymu.html

[J09] 时区处理
来源：http://dali.xziqi.cn/Article/details/gt2pbjaahec.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.vqdsnc.cn/Article/details/gt2budaepwx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ydzc1.top/Article/details/gt2ujgsbujj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gt2dqsjyxek.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gt2aqmioheo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gt2avuvyvjv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj202588.top/Article/details/gt2ejweuuio.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eaqbsfmw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jyoumei.cn/Article/details/gt2menguewb.html

[J10] 取今天 / 本月第一天
来源：http://dali.gzhubu.top/Article/details/gt2cbprhepp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gogol.net.cn/Article/details/gt2pypnsdpf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gotoacloud.top/Article/details/gt2opdkzdaq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xylfe.cn/Article/details/gt2hfqivwgb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ffejcuzo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gt2azpqdtwz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ydzc1.top/Article/details/gt2zsuqjjyn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yangfankeji.com/Article/details/gt2qpsborna.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vnqhmhyq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2glnxjule.html

K. JSON 与序列化
来源：http://dali.gaohongyu789.top/Article/details/gt2dorgegjd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2wdpbmxfh.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuxming.cn/Article/details/gt2edcddzun.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gt2wdibtcyg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gt2difmlmje.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2cvevsdow.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zlfrimxl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ydzc1.top/Article/details/gt2oubkjtbb.html

Go:   json.Marshal(obj)
来源：http://dali.smart0.xyz/Article/details/gt2wscjqlce.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ydzc1.top/Article/details/gt2pnnhqygb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2fkcntade.html

[K02] JSON 字符串转对象
来源：http://dali.zhongyouzk.top/Article/details/gt2cxiwluhs.html

Py:   json.loads(s)
来源：http://dali.tian-w.cn/Article/details/gt2wcivnztc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhoulong.xyz/Article/details/gt2vanljqvw.html

JS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dwncqauw.html

TS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2vyzdjmpt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sufxvd.cn/Article/details/gt2qzoizshq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gt2vkceghyv.html

Ruby: JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gt2ffkbgyow.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wrzssfns.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gt2ksacnypt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gt2wghmdero.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gt2geoejtup.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kswopcvo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gt2gzdatbvt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2asbzitbb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yueranfly.top/Article/details/gt2lyrwmwih.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yonumen.top/Article/details/gt2wbjjgdtl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gt2satplshl.html

[K04] 读取 JSON 文件
来源：http://dali.yonumen.top/Article/details/gt2hbuxwxyy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zycfv.cn/Article/details/gt2gkutjasb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gt2oyiflogh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gt2folmswtu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gt2sagjryiy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gt2zbssewtw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gt2ltyqzawq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gt2efjkwlpn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gt2vrtsfgeb.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gt2bxvmtfdt.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2cxepjkcx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.feifeiyinyue.top/Article/details/gt2hfzsosuw.html

JS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2uvddwbku.html

TS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gt2pkoqkokm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangshuangyany.cn/Article/details/gt2owytrlbg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnqzz.top/Article/details/gt2jkurozuc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ffltljgu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.bjfxy.top/Article/details/gt2lyxsmfgl.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gt2vkheixtb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gt2tchdcrhu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ppjwa.cn/Article/details/gt2fputkfdo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2tfxeomab.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bcphmqxh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gt2iomqsqcd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gt2grrabzxl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2sipkslvv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2ttwdiorg.html

[K07] 进制转换
来源：http://dali.hnqzz.top/Article/details/gt2otduqqjs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzhuirr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxuanxn.top/Article/details/gt2biicbdlr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2yawkgade.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2absnthrm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2ujqxxert.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yvedp.cn/Article/details/gt2tvhjrxau.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gogol.net.cn/Article/details/gt2scufjecr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwtdmjfi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.c1oappe.top/Article/details/gt2vosvhpaj.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2mdkypdnv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuxming.cn/Article/details/gt2dyfyyhyi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gt2sivvusfd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gt2nqirwzxc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jlsjyb.cn/Article/details/gt2unlevotn.html

Go:   encoding/gob
来源：http://dali.fengsongda.top/Article/details/gt2dwikcgpr.html

Ruby: Marshal.dump(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2xbipsmbg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gt2rsfoucyu.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2pdogfxdn.html

L. 网络请求
来源：http://dali.gotoacloud.top/Article/details/gt2zwwyukqm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2sxqzfwmk.html

[L01] 发送 GET 请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmhjtvra.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pengpengdd.cyou/Article/details/gt2amgechge.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gt2rnjqfnxl.html

JS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gt2yccqubar.html

TS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gt2gorvkimy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pycfn.com/Article/details/gt2djvsdcju.html

Go:   resp, err := http.Get(url)
来源：http://dali.jianghu66.top/Article/details/gt2coshbkgf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnxiangtu.top/Article/details/gt2vndiaqhd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gt2cbjrqonl.html

[L02] 发送 POST JSON
来源：http://dali.yj20258.top/Article/details/gt2eghrfvoz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cucudq.cn/Article/details/gt2gadpnpsh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yangfankeji.com/Article/details/gt2mwfzywrr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbisgdah.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gt2oxrfbkfw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ocuynmhz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.meibo888.top/Article/details/gt2kbextvnk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.kuanghao11.cn/Article/details/gt2vjkuttdq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gt2jwpsedsm.html

[L03] 设置自定义请求头
来源：http://dali.shuidangran.top/Article/details/gt2opytvnbg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fengsongda.top/Article/details/gt2rhusmfgi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guowangkeji.top/Article/details/gt2jioahqnu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2zjoqvyve.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gt2yiyhtiws.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yvedp.cn/Article/details/gt2uughqkff.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gt2krfuvhio.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gt2musavbls.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gt2lpbmmrik.html

[L04] 设置超时
来源：http://dali.xinyue.icu/Article/details/gt2xnbmrstm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shuidangran.top/Article/details/gt2bafgcydh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.mhx1999.top/Article/details/gt2qzdswton.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gt2hoxogajy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gt2vjupfqpr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhongyouzk.top/Article/details/gt2bhuuokei.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zycfv.cn/Article/details/gt2swkeload.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zycfv.cn/Article/details/gt2hchcjrvg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yongpay.top/Article/details/gt2iwmgpakr.html

[L05] 上传文件（multipart）
来源：http://dali.xuanzx.com/Article/details/gt2rruubweo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pengpengdd.cyou/Article/details/gt2ywjkvylt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ppjwa.cn/Article/details/gt2ftuskkyr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gt2xtwhmgzo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gt2pofqqvdv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cheryme.top/Article/details/gt2ehpovfww.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.meibo888.top/Article/details/gt2pwqpqkuv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jlsjyb.cn/Article/details/gt2wamtnztq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2pnnzvvzq.html

[L06] 解析响应为 JSON
来源：http://dali.shzxlz.cn/Article/details/gt2amxcprmk.html

Py:   resp.json()
来源：http://dali.cqqwz.cn/Article/details/gt2rucpwnnl.html

PHP:  json_decode($body, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2djutaffy.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gt2kimfgqkl.html

TS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gt2kpqavftr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2blkrzqzc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.mhx1999.top/Article/details/gt2ogtpexkq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xgnlfpbh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fengsongda.top/Article/details/gt2bbepcyrr.html

[L07] 处理 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gt2bksemeqv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gt2lvolwoqh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yntnbkev.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gt2evntuawa.html

TS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gt2xhzgunoa.html

Java: resp.statusCode()
来源：http://dali.xinyue.icu/Article/details/gt2ncdbknmq.html

Go:   resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gt2iveevwbp.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gt2ocwnmtwj.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gt2niizljid.html

[L08] 并发请求多个地址
来源：http://dali.fzhhl.top/Article/details/gt2ypvaaate.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.havefunace.top/Article/details/gt2fardfgds.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenlongwang.top/Article/details/gt2coyfyhvk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2asrqbeos.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2utzjiyde.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gt2pnhjuxkc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.vqdsnc.cn/Article/details/gt2wxnbdhxy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgfzy.top/Article/details/gt2xdirfbbp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2yzuukkli.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2lolofiru.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gt2kubfeytl.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ysulbvpg.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gt2qjpirvvf.html

Py:   sys.argv[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2lyabmdyn.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gt2oxosypww.html

JS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gt2zqyzdqak.html

TS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gt2mnwyclhk.html

Java: args 数组（main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gt2cdulkeaj.html

Go:   os.Args[1:]
来源：http://dali.yvedp.cn/Article/details/gt2zygecaei.html

Ruby: ARGV
来源：http://dali.pycfn.com/Article/details/gt2ekkuwdih.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vhftrunh.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gt2qeusvewa.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ccpyshml.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gt2opuvvhof.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gt2ewtnpcuo.html

TS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gt2fkmnogrw.html

Java: System.getenv("HOME")
来源：http://dali.birdmap.top/Article/details/gt2xibomutn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gt2itibwjas.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gt2rpienncn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xziqi.cn/Article/details/gt2lnmxsgec.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2djgrepsz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnxewenm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.haohaochexian.top/Article/details/gt2hkhgvvoh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gt2gfmtbqlc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gt2ffyypibh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yangfankeji.com/Article/details/gt2kvmoellk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gt2zyflgdxq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258.top/Article/details/gt2lkizzavv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.kuanghao11.cn/Article/details/gt2kcvfhkyj.html

[M04] 获取当前工作目录
来源：http://dali.quarkkingdee.top/Article/details/gt2motklqis.html

Py:   os.getcwd()
来源：http://dali.meibo888.top/Article/details/gt2tanbrpnp.html

PHP:  getcwd();
来源：http://dali.ybcxt.top/Article/details/gt2tiqgxlxo.html

JS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gt2wswglgma.html

TS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gt2zxwxfdml.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fengsongda.top/Article/details/gt2mtoavtye.html

Go:   os.Getwd()
来源：http://dali.hammf.cn/Article/details/gt2wzszksjl.html

Ruby: Dir.pwd
来源：http://dali.birdmap.top/Article/details/gt2rvdmxcnp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cqqwz.cn/Article/details/gt2wniucrkt.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2umopqswt.html

Py:   sys.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2rwrjqkwn.html

PHP:  exit(1);
来源：http://dali.chenzaomai.com/Article/details/gt2vkqjlcwp.html

JS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2nnytaqkd.html

TS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2ijepgloi.html

Java: System.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2kpubvjlp.html

Go:   os.Exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rcozztcp.html

Ruby: exit 1
来源：http://dali.9152youxi.cn/Article/details/gt2okbnkpmh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cheryme.top/Article/details/gt2wlsbtfnh.html

[M06] 向标准错误输出
来源：http://dali.andypj.xyz/Article/details/gt2dogipmoe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gt2uvzonouz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.smart0.xyz/Article/details/gt2eewxliiq.html

JS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gt2wwetsvrj.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gt2ahdfclty.html

Java: System.err.println("err")
来源：http://dali.gzhubu.top/Article/details/gt2ytpvpdsu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shzxlz.cn/Article/details/gt2fzyuwpjd.html

Ruby: warn "err"
来源：http://dali.birdmap.top/Article/details/gt2iojuverl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.316326.xyz/Article/details/gt2qaqpkiao.html

[M07] 判断是否为主入口
来源：http://dali.tanke756.top/Article/details/gt2lwmcankf.html

Py:   if __name__ == "__main__":
来源：http://dali.hfpthk.cn/Article/details/gt2pbinihog.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gt2dwpsiuli.html

JS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gt2cqmnlftu.html

TS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hnytcphp.html

Java: public static void main(String[] args)
来源：http://dali.yj20258888.top/Article/details/gt2xfldosmm.html

Go:   func main()
来源：http://dali.chenlongwang.top/Article/details/gt2reqmkgby.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hongshengwenyu.top/Article/details/gt2knvgebyi.html

C#:   static void Main(string[] args)
来源：http://dali.meibo888.top/Article/details/gt2hnfzvaur.html

[M08] 获取系统与运行时信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vtqrshat.html

Py:   platform.system();  platform.python_version()
来源：http://dali.snrcjt.cn/Article/details/gt2ffswoloj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ydzc1.top/Article/details/gt2wpzypyiz.html

JS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gt2fxtdjowq.html

TS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gt2amhjdysu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgufenzy.top/Article/details/gt2lhfnzvwb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnzgnmo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenlongwang.top/Article/details/gt2lhmcfxjg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuanzx.com/Article/details/gt2inekigmc.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2zxxyrbbg.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gt2ursjyhgp.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2bnkahwgy.html

[N01] 二分查找（有序数组）
来源：http://dali.xuetiantiany.cn/Article/details/gt2rhdrrfvk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2qgghrcii.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xylfe.cn/Article/details/gt2vcnxfvas.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2jwvoffhf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2javcxpvz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2wwqstgym.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2luoprcxo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fengsongda.top/Article/details/gt2efttylyc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2hzprbsiw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuxming.cn/Article/details/gt2msdaapcn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gt2ppnroccx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hysaishi.cn/Article/details/gt2oplomggw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gt2tiauofor.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gt2vczjmwci.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2swcjvxwy.html

Go:   slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2fqmuytid.html


<!-- 参考信息 -->