代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gt2rxzkjreh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gt2ttfmoesb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zzsvuolr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aizwys.cn/Article/details/gt2zcbqcsbq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ppjwa.cn/Article/details/gt2xfxdqmea.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yangfankeji.com/Article/details/gt2fcuirqsd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ksdknjpc.html

[J06] 计算两时间之差
来源：http://dali.gotoacloud.top/Article/details/gt2uiondsqc.html

Py:   (end - start).total_seconds()
来源：http://dali.gaohongyu789.top/Article/details/gt2ygygzwgp.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kirnaukb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgufenzy.top/Article/details/gt2gykwktvm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgufenzy.top/Article/details/gt2awljqyqu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.haohaochexian.top/Article/details/gt2echltklz.html

Go:   end.Sub(start).Hours()
来源：http://dali.havefunace.top/Article/details/gt2prjprlvf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.316326.xyz/Article/details/gt2qxejswuk.html

C#:   (end - start).TotalSeconds
来源：http://dali.yvedp.cn/Article/details/gt2pygjnknx.html

[J07] 比较两个日期
来源：http://dali.aibaodan.cn/Article/details/gt2bpgcurmi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gt2ufahbxyp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gt2ezvdjloh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gt2dbyvtnec.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gt2dqwqirdu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sweek.top/Article/details/gt2jgpnnwuh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shuidangran.top/Article/details/gt2wixjuiud.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gt2qbihvjgu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nczyqiuu.html

[J08] 提取年月日与星期
来源：http://dali.ehwqpu.com/Article/details/gt2ubknjyze.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sysykeji.top/Article/details/gt2mvvdrvqo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jiagoushi.top/Article/details/gt2iuaocvtm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gt2oaoixepw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnltgdii.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigufen.top/Article/details/gt2yiuizbla.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gt2gymocovi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yanzbfuv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gt2nszczdiy.html

[J09] 时区处理
来源：http://dali.haohaochexian.top/Article/details/gt2rsmqgjrn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangdashe.top/Article/details/gt2psbxztxg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.bjfxy.top/Article/details/gt2ettblqbg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gt2gbsbhwpj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gt2gdunmqwn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.bjfxy.top/Article/details/gt2mamagweo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangshuangyany.cn/Article/details/gt2evwajvnm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.snrcjt.cn/Article/details/gt2lrdxwwdn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuanzhike.top/Article/details/gt2pdjzzins.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhoulong.xyz/Article/details/gt2gqggycim.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2abxcgwag.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuanzx.com/Article/details/gt2vhxyoqfp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nwbrower.top/Article/details/gt2adtnunid.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2tcoyktct.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jrjvhxqh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jianghu66.top/Article/details/gt2askdjnzo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gt2ttxhgtqo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2jtwulfse.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2jtqpdscf.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gt2gpehuxeh.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2keeddorm.html

[K01] 对象转 JSON 字符串
来源：http://dali.sufxvd.cn/Article/details/gt2peqkcela.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gt2ayoyjjiu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gt2zyjumktg.html

JS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gt2pgawydye.html

TS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gt2mpkprrje.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhixingplan.top/Article/details/gt2prmhrtfg.html

Go:   json.Marshal(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2luynucdv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gt2tgjyiqje.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cheryme.top/Article/details/gt2uurpyyxr.html

[K02] JSON 字符串转对象
来源：http://dali.zhoulong.xyz/Article/details/gt2sbxwqmxe.html

Py:   json.loads(s)
来源：http://dali.hnqzz.top/Article/details/gt2jcbrdrnk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cheryme.top/Article/details/gt2urdorxmm.html

JS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gt2vznynhcc.html

TS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gt2gtmyvpor.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2ltgyxida.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gt2terbedkm.html

Ruby: JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gt2mtkchjkk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gt2odellhrz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenlongwang.top/Article/details/gt2uldfwctl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gt2hopmvwyd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gt2eiluqvya.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2evfblyqm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gt2qmtfiyxj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aiufiuhz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hfpthk.cn/Article/details/gt2ivudxnwh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangdashe.top/Article/details/gt2agcilbwt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnqzz.top/Article/details/gt2fvnhzgxl.html

[K04] 读取 JSON 文件
来源：http://dali.yj202588.top/Article/details/gt2nlqwugaq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xziqi.cn/Article/details/gt2ptclzqsl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj202588.top/Article/details/gt2tulcharc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gt2mwrjkgeb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gt2kedoynbe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gt2xabpusqq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gt2wmdbuakk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gt2cycctesi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gt2qvzkassj.html

[K05] 深拷贝对象
来源：http://dali.tian-w.cn/Article/details/gt2ocufkafv.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ifvxdkov.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258888.top/Article/details/gt2proyeejb.html

JS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gt2bhockbuv.html

TS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2rwnqciuu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daxiang520.top/Article/details/gt2wybinwsv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cheryme.top/Article/details/gt2wpsioajw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ivvv.top/Article/details/gt2mnxdxven.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yangfankeji.com/Article/details/gt2qrweknwa.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gt2okhktzbw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gt2epgprbjs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yangfankeji.com/Article/details/gt2uckxwwhk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gt2xsyomvnp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gt2tvufcamf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gt2jolgnriw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gt2zpdgymmo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svjhhvqb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gt2qbabqtts.html

[K07] 进制转换
来源：http://dali.9152youxi.cn/Article/details/gt2yvrjjukc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2wyczoqbe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hywenlv.cn/Article/details/gt2brwttpcy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2jnezrwpk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2fufocabq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2roqbkbkc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuxming.cn/Article/details/gt2vhfpgxlc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sxryk.cn/Article/details/gt2dynveerp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhvzummq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cdnleiting.top/Article/details/gt2hcawphky.html

Py:   pickle.dumps(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2xavlbghb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pycfn.com/Article/details/gt2raefrryx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gt2qwapnzdx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gt2yydqdbid.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ivvv.top/Article/details/gt2xlhgrsbs.html

Go:   encoding/gob
来源：http://dali.sxryk.cn/Article/details/gt2viwcwuyt.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gt2opurssrm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gt2ojnvywgu.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2phqtgxwk.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmtbbjjd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2dvfdlpzl.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gt2mtwkeysx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yonumen.top/Article/details/gt2uzukfouk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.c1oappe.top/Article/details/gt2zuskucls.html

JS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gt2yojizaln.html

TS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2oempngun.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tgrdznza.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2jnxkygen.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.mhx1999.top/Article/details/gt2ueyqvwae.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.9152youxi.cn/Article/details/gt2bqcjwhib.html

[L02] 发送 POST JSON
来源：http://dali.yj202588.top/Article/details/gt2pfnminib.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gt2ewoquhzp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gaohongyu789.top/Article/details/gt2jejjclcf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gt2ujabbfxm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gt2pnrzhlnv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sysykeji.top/Article/details/gt2eraxymyh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gt2oxspaboi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sweek.top/Article/details/gt2cnnltkgh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.haohaochexian.top/Article/details/gt2jxtzokwz.html

[L03] 设置自定义请求头
来源：http://dali.fzhhl.top/Article/details/gt2evadgyfe.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gaohongyu789.top/Article/details/gt2lngeksxz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xylfe.cn/Article/details/gt2uojlsspd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gt2qbqjqiky.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gt2elnnvaix.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgfzy.top/Article/details/gt2alkzdslb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gt2mmcajtch.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hywenlv.cn/Article/details/gt2hqfuwntu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gt2sdfqhxqk.html

[L04] 设置超时
来源：http://dali.guowangkeji.top/Article/details/gt2lolyysez.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ehwqpu.com/Article/details/gt2cxgsjfsb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jlsjyb.cn/Article/details/gt2inafcbnb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2xhjqayab.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gt2viimnnmc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fengsongda.top/Article/details/gt2oxcwwbkx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sweek.top/Article/details/gt2ywsvdueo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yvedp.cn/Article/details/gt2gxibpodb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zycfv.cn/Article/details/gt2mchmqoqr.html

[L05] 上传文件（multipart）
来源：http://dali.jiagoushi.top/Article/details/gt2dzooxjyc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.snrcjt.cn/Article/details/gt2aqnorsxq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gt2kyoiogab.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gt2itwcvtyf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gt2dlppgszg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xziqi.cn/Article/details/gt2whauasav.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sufxvd.cn/Article/details/gt2rpfqhwmh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guowangkeji.top/Article/details/gt2lmzprxcw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gt2zbwgjdwv.html

[L06] 解析响应为 JSON
来源：http://dali.mhx1999.top/Article/details/gt2yfkaaymw.html

Py:   resp.json()
来源：http://dali.yj20258888.top/Article/details/gt2zmujucnk.html

PHP:  json_decode($body, true);
来源：http://dali.yvedp.cn/Article/details/gt2uwclexlk.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gt2bkxuazfn.html

TS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gt2yptudypo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2ckdlhpja.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ydzc1.top/Article/details/gt2bivqdrft.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sxryk.cn/Article/details/gt2lbytkxzk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guowangkeji.top/Article/details/gt2xbjpnysd.html

[L07] 处理 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gt2hdtczepq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.bjfxy.top/Article/details/gt2noxhtsju.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj202588.top/Article/details/gt2lwbkmyhb.html

JS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gt2wwdbezyi.html

TS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gt2wncoifpt.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gt2owbhxobj.html

Go:   resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gt2xrzexkgv.html

Ruby: resp.code.to_i
来源：http://dali.fengsongda.top/Article/details/gt2dvefmbnz.html

C#:   (int)resp.StatusCode
来源：http://dali.gogol.net.cn/Article/details/gt2vysakhoo.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gt2mghfyepj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xylfe.cn/Article/details/gt2gddcjxsa.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhiwuduotai.top/Article/details/gt2nltposoo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gt2jqwrvjgm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gt2lanbzdga.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jiagoushi.top/Article/details/gt2dmbkreae.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.bjfxy.top/Article/details/gt2ylegsbor.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cdnleiting.top/Article/details/gt2xcopxtis.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cheryme.top/Article/details/gt2zqtzxhin.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2evfoweyq.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gt2uwbpoyxp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2hsfmkjwx.html

[M01] 读取命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gt2rcambcog.html

Py:   sys.argv[1:]
来源：http://dali.fzhhl.top/Article/details/gt2bnhummbi.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gt2abfgkfoh.html

JS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gt2rrpshyqo.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gt2kwgdfdas.html

Java: args 数组（main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gt2dsquirof.html

Go:   os.Args[1:]
来源：http://dali.cqqwz.cn/Article/details/gt2zcnxbwjs.html

Ruby: ARGV
来源：http://dali.hongshengwenyu.top/Article/details/gt2onmaokfm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gt2rnlghkwf.html

[M02] 读取环境变量
来源：http://dali.nanxinkj.top/Article/details/gt2jrhryfvl.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gt2cxnqvtcq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gt2byuuvwbw.html

JS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gt2hckakano.html

TS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gt2uyfqrujw.html

Java: System.getenv("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2vpbunugt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dctxmkyu.html

Ruby: ENV["HOME"]
来源：http://dali.fzhhl.top/Article/details/gt2ashtzjjf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2vjvcbyol.html

[M03] 执行外部命令
来源：http://dali.hongshengwenyu.top/Article/details/gt2ttjoyjfj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ivvv.top/Article/details/gt2wfldtkxs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fengsongda.top/Article/details/gt2fykpijog.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gt2yszqifzk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gt2nnvzozts.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jlsjyb.cn/Article/details/gt2nvicxzfs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgufenzy.top/Article/details/gt2dlrkkyvu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.snrcjt.cn/Article/details/gt2oecedunt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jyoumei.cn/Article/details/gt2nhmsfqve.html

[M04] 获取当前工作目录
来源：http://dali.tanke756.top/Article/details/gt2bntfhmmd.html

Py:   os.getcwd()
来源：http://dali.hysaishi.cn/Article/details/gt2ibfvekkv.html

PHP:  getcwd();
来源：http://dali.zhixingplan.top/Article/details/gt2yanlyysb.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ollrensf.html

TS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gt2nlpqdkqo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.andypj.xyz/Article/details/gt2vfcdqaxf.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nkcgqygj.html

Ruby: Dir.pwd
来源：http://dali.wangdashe.top/Article/details/gt2ouxtpbwg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daria6918.cn/Article/details/gt2uulklsfl.html

[M05] 设置退出码
来源：http://dali.zhongyouzk.top/Article/details/gt2iojwgxje.html

Py:   sys.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2oayvwlqh.html

PHP:  exit(1);
来源：http://dali.guowangkeji.top/Article/details/gt2xtrsygpo.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2lnaezcmm.html

TS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gt2syxzzbbr.html

Java: System.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2umretnmr.html

Go:   os.Exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2rtmzgwuc.html

Ruby: exit 1
来源：http://dali.birdmap.top/Article/details/gt2tmbqjqzo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daxiang520.top/Article/details/gt2gpjqzrsx.html

[M06] 向标准错误输出
来源：http://dali.yj202588.top/Article/details/gt2tyruiewq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hammf.cn/Article/details/gt2xkvpppno.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfknyik.html

JS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gt2ketetsvd.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gt2gugqwpox.html

Java: System.err.println("err")
来源：http://dali.yueranfly.top/Article/details/gt2rangatcu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mxnjmwsf.html

Ruby: warn "err"
来源：http://dali.ivvv.top/Article/details/gt2tsgszwee.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shuidangran.top/Article/details/gt2dptzmygc.html

[M07] 判断是否为主入口
来源：http://dali.nanxuanxn.top/Article/details/gt2qbcsjfgt.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gt2powitmzt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yongpay.top/Article/details/gt2wpwabuev.html

JS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gt2wqjzgvsi.html

TS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gt2djdgyzep.html

Java: public static void main(String[] args)
来源：http://dali.yuanzhike.top/Article/details/gt2gapzynqe.html

Go:   func main()
来源：http://dali.chenzaomai.com/Article/details/gt2ihkbxnkm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pycfn.com/Article/details/gt2dvkrmqqc.html

C#:   static void Main(string[] args)
来源：http://dali.wangdashe.top/Article/details/gt2jcjrjefy.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gt2lcjxyzzf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yvedp.cn/Article/details/gt2brnxxtkc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gt2toxvqdrn.html

JS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gt2jozmiujb.html

TS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gt2udgmwwve.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guannengcc.top/Article/details/gt2jqoagdwb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.c1oappe.top/Article/details/gt2ikdcuimp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gt2iwfujnfj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yongpay.top/Article/details/gt2xdiepggg.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2emalwrcm.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vegyuzbr.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2yfgwcxgf.html

[N01] 二分查找（有序数组）
来源：http://dali.shuidangran.top/Article/details/gt2nxjvlvtw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2efjqfjfp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.meibo888.top/Article/details/gt2pqlddqun.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gt2rfivdfuc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2tclhdhad.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2zvlcsahb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2txwztuuy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jyoumei.cn/Article/details/gt2znbhksmv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2rhthhpvz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zycfv.cn/Article/details/gt2yrynlweb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gt2uixsjzwc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tianlin.xyz/Article/details/gt2nvtawjnn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gt2qvavzlgt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gt2rfncbhuq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xziqi.cn/Article/details/gt2zkmclcbg.html

Go:   slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2rfrttacj.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gt2eujmdwej.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xylfe.cn/Article/details/gt2meyaepah.html

[N03] 快速排序（分治示例）
来源：http://dali.zhoulong.xyz/Article/details/gt2zmsfsdkj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.vqdsnc.cn/Article/details/gt2bxkrtzsq.html


<!-- 参考信息 -->