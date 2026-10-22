代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ydzc1.top/Article/details/gt2xmlacvye.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gt2izefrrhk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gt2jltagdem.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gt2ckzavzgn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gt2maibetvh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.316326.xyz/Article/details/gt2dslzrbzc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.0kj1m.cn/Article/details/gt2xuupvoej.html

[J06] 计算两时间之差
来源：http://dali.nanxinkj.top/Article/details/gt2poqlunmk.html

Py:   (end - start).total_seconds()
来源：http://dali.vqdsnc.cn/Article/details/gt2yryoazcl.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gt2gccydzse.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wsrnihpu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gt2exknyauo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hammf.cn/Article/details/gt2xqsnjgqw.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gt2wgimnpmx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gt2ohedxdqr.html

C#:   (end - start).TotalSeconds
来源：http://dali.haohaochexian.top/Article/details/gt2azwcatwr.html

[J07] 比较两个日期
来源：http://dali.ehwqpu.com/Article/details/gt2nsrtfmjh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gt2zqdkgfte.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.mhx1999.top/Article/details/gt2xdhzguyf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gt2gfmhaitu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gt2yykjwbif.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daxiang520.top/Article/details/gt2kwjhafjv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jlsjyb.cn/Article/details/gt2dfojgopf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gt2jiykzsit.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gt2rmficubz.html

[J08] 提取年月日与星期
来源：http://dali.iojbl.cn/Article/details/gt2bgdkttyz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yangfankeji.com/Article/details/gt2jreiuvwk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yvedp.cn/Article/details/gt2siamupuv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zfnqdrgh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gt2gkjhnqdw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xziqi.cn/Article/details/gt2yjzqmwkg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yangfankeji.com/Article/details/gt2gpdaglws.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ehwqpu.com/Article/details/gt2gdkytszi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yonumen.top/Article/details/gt2ecpvjkbs.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gt2asohnkxx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gt2odyjqgoi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hywenlv.cn/Article/details/gt2kmoefscp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gt2fwwpgxrt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gt2omplmlmn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aizwys.cn/Article/details/gt2usuamxsy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uoprriit.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.andypj.xyz/Article/details/gt2gsvlazce.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aizwys.cn/Article/details/gt2wdyxvyui.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gt2fpxmwulz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aibaodan.cn/Article/details/gt2vowhrgcj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tanke756.top/Article/details/gt2gkwlpbtt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fzhhl.top/Article/details/gt2mjhhecju.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.redwolf501.top/Article/details/gt2kildhuka.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nwbrower.top/Article/details/gt2bcubxiar.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gt2bhozagbv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gt2uozxmdgz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cheryme.top/Article/details/gt2ysodidyk.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2olchbvtr.html

K. JSON 与序列化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmyjilnz.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2usyhfbbn.html

[K01] 对象转 JSON 字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2trthgqcg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2apmgznaq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gt2ltmufjjy.html

JS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2zaibuqml.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vohvtozo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gt2wucxdows.html

Go:   json.Marshal(obj)
来源：http://dali.yj202588.top/Article/details/gt2hfckswch.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sweek.top/Article/details/gt2oxpoinsq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2dbjjejbn.html

[K02] JSON 字符串转对象
来源：http://dali.gogol.net.cn/Article/details/gt2xtnhwuyy.html

Py:   json.loads(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wixswroc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gt2gdyclkwb.html

JS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahdhrbei.html

TS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2pizzwmua.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.andypj.xyz/Article/details/gt2zzzxmezl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gt2smxhbnff.html

Ruby: JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gt2nurtwvbu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gt2kbjrzvco.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gt2daxyffhb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gt2heqpawoy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gt2byjegegp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gt2beuwpkft.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rpypmdsm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2pgpmkafb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnxiangtu.top/Article/details/gt2hxiuppjk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gzhubu.top/Article/details/gt2kxiqerze.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj202588.top/Article/details/gt2rynqmyuy.html

[K04] 读取 JSON 文件
来源：http://dali.0kj1m.cn/Article/details/gt2rrvuelfp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daxiang520.top/Article/details/gt2swymfdhw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gt2genmgkia.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gt2kqfmfhxe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gt2zuoxayhi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvrxfal.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xnfgzcju.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gt2engonrza.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gt2ykgfrkpp.html

[K05] 深拷贝对象
来源：http://dali.jqgufenzy.top/Article/details/gt2ooyvwhfm.html

Py:   copy.deepcopy(obj)
来源：http://dali.nwbrower.top/Article/details/gt2oaekowqq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yvedp.cn/Article/details/gt2eiftrpia.html

JS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gt2xsbwtpqt.html

TS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gt2szmjyebj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xziqi.cn/Article/details/gt2wznyojec.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hywenlv.cn/Article/details/gt2iblkksdb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hywenlv.cn/Article/details/gt2wodjbbdt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangdashe.top/Article/details/gt2lrwflnka.html

[K06] 解析 URL 查询串
来源：http://dali.zycfv.cn/Article/details/gt2egzikktg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gt2zodlhkbs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gt2fkowwcfp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gt2qpibkfzk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2vmsaqsah.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uemdblpg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2bpceespk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2zoengtjb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2jbfyaegc.html

[K07] 进制转换
来源：http://dali.snrcjt.cn/Article/details/gt2fmcabufc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2pitokttr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gt2psgrarup.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2okdxpaxi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2ufeizdyp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2ymbkdftn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.snrcjt.cn/Article/details/gt2usliybbk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pycfn.com/Article/details/gt2vrviqyrr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cynofgnb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.quarkkingdee.top/Article/details/gt2mtojcxxj.html

Py:   pickle.dumps(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2zvqnovpz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jrqpmjgw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gt2ullscjrh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2mygkefrc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iwhxtksv.html

Go:   encoding/gob
来源：http://dali.yj20258.top/Article/details/gt2xydzuboa.html

Ruby: Marshal.dump(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2rbjezzay.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gt2yvsdamjp.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2mwmnffyr.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gt2tdtdmaey.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2tnufakog.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gt2mhvnmccf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gt2vrjtzilb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gt2fmplzcom.html

JS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2okpugbfn.html

TS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fsohyrlb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnqzz.top/Article/details/gt2ryzopoqz.html

Go:   resp, err := http.Get(url)
来源：http://dali.fengsongda.top/Article/details/gt2svtfxwsi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cdnleiting.top/Article/details/gt2mgazhnws.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dashuyun.cn/Article/details/gt2tcdrtnsg.html

[L02] 发送 POST JSON
来源：http://dali.iojbl.cn/Article/details/gt2qsiozdqf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.mhx1999.top/Article/details/gt2xwbuodmg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.mhx1999.top/Article/details/gt2acvswqxz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gt2zihzbqnl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gt2fcwkddek.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.snrcjt.cn/Article/details/gt2obmyyiif.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.snrcjt.cn/Article/details/gt2zvagjyjn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xinyue.icu/Article/details/gt2wtbljgac.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuxming.cn/Article/details/gt2ipznxrqd.html

[L03] 设置自定义请求头
来源：http://dali.yvedp.cn/Article/details/gt2mdqtfmcb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhongyouzk.top/Article/details/gt2xpyamqbe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj202588.top/Article/details/gt2ethftvvq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gt2ewpdnvyd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gt2yfjkcymy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aizwys.cn/Article/details/gt2cecrwscu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gt2eawvbqwg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yvedp.cn/Article/details/gt2qwvfoczz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gt2zzcmchqt.html

[L04] 设置超时
来源：http://dali.xziqi.cn/Article/details/gt2zkhoxgkz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xziqi.cn/Article/details/gt2rdwhzrps.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.c1oappe.top/Article/details/gt2bqsqqiyg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gt2aeqgdtga.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2biondrwp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guowangkeji.top/Article/details/gt2vkyjekgt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xylfe.cn/Article/details/gt2osuxnrck.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hysaishi.cn/Article/details/gt2ugqexrxc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cqqwz.cn/Article/details/gt2aoyjaoaf.html

[L05] 上传文件（multipart）
来源：http://dali.daria6918.cn/Article/details/gt2kvmjuqgi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gt2rbdpjfje.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yvedp.cn/Article/details/gt2jvcevvyh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gt2nkwkjysp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gt2hyouzije.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sufxvd.cn/Article/details/gt2hreflsol.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigufen.top/Article/details/gt2vjpirdms.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tianlin.xyz/Article/details/gt2dfygvqqx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2cxegndas.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gt2usnvpuwz.html

Py:   resp.json()
来源：http://dali.hysaishi.cn/Article/details/gt2uesyibar.html

PHP:  json_decode($body, true);
来源：http://dali.yangfankeji.com/Article/details/gt2eqkhiyti.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2jkpaewmt.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2lscvknox.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2hitovyki.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zycfv.cn/Article/details/gt2bqrtliaz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gt2cxzcwzja.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.meibo888.top/Article/details/gt2lscibflr.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gt2iapevxua.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sxryk.cn/Article/details/gt2pnmmxsdd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2uzdmvvae.html

JS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gt2efhchvwq.html

TS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gt2karkcjcp.html

Java: resp.statusCode()
来源：http://dali.xuetiantiany.cn/Article/details/gt2bqzaeszb.html

Go:   resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gt2bvdqvqpc.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gt2gjvodvwr.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gt2oodeanyr.html

[L08] 并发请求多个地址
来源：http://dali.zycfv.cn/Article/details/gt2emrerjcu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dashuyun.cn/Article/details/gt2mlglkhlh.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gt2hwebwtyn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gt2kdtythxq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gt2vayvtili.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2khvjjuus.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.redwolf501.top/Article/details/gt2ywoedyki.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yvedp.cn/Article/details/gt2fkrgsmwb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.316326.xyz/Article/details/gt2rmqfrmam.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2ldzdkwxg.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gt2kjrlqzgd.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2qzqaexzi.html

[M01] 读取命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gt2xrnpsouz.html

Py:   sys.argv[1:]
来源：http://dali.ehwqpu.com/Article/details/gt2usahqzdx.html

PHP:  $argv;  $argc;
来源：http://dali.cdnleiting.top/Article/details/gt2rcwkdzfe.html

JS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gt2krdrvybh.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gt2hnnrmaxh.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gt2ntgrvxxv.html

Go:   os.Args[1:]
来源：http://dali.gogol.net.cn/Article/details/gt2ilwpycfb.html

Ruby: ARGV
来源：http://dali.gotoacloud.top/Article/details/gt2mvizyqft.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gt2gkllcpbv.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jiqqnzes.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2wowsvhvd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gt2yhwswbqo.html

JS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gt2jngxujxt.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gt2uyfdnqpg.html

Java: System.getenv("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2nomdgebd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2rpwifuwf.html

Ruby: ENV["HOME"]
来源：http://dali.zhongyouzk.top/Article/details/gt2fagivvoq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgfzy.top/Article/details/gt2ahyxfxtm.html

[M03] 执行外部命令
来源：http://dali.jqgfzy.top/Article/details/gt2ofvbivxv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gt2cdeehzem.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tian-w.cn/Article/details/gt2itnybnri.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gt2samjzfqp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gt2lsiowszy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258.top/Article/details/gt2xzgqzmqe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.iojbl.cn/Article/details/gt2oebhypug.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenjidiqi.icu/Article/details/gt2qkbkbrqt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fengsongda.top/Article/details/gt2fhcnbqiz.html

[M04] 获取当前工作目录
来源：http://dali.guannengcc.top/Article/details/gt2ypalclko.html

Py:   os.getcwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2xvqfdtet.html

PHP:  getcwd();
来源：http://dali.ydzc1.top/Article/details/gt2sucyvtfa.html

JS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gt2pzwjicsj.html

TS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gt2xpfittxv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.meibo888.top/Article/details/gt2lgebamyv.html

Go:   os.Getwd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2sxooovgs.html

Ruby: Dir.pwd
来源：http://dali.hfpthk.cn/Article/details/gt2ujibcezy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gt2egxoxwge.html

[M05] 设置退出码
来源：http://dali.ybcxt.top/Article/details/gt2afmmyvgs.html

Py:   sys.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2hiukrxij.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gt2nzvldnxy.html

JS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2mrvkvhno.html

TS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2efzxutav.html

Java: System.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2scwvucba.html

Go:   os.Exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2fevdbeci.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gt2utjumeuj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fengsongda.top/Article/details/gt2wmrbetnw.html

[M06] 向标准错误输出
来源：http://dali.gotoacloud.top/Article/details/gt2nnpvvyxq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gt2zilynitk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gt2nzbzdxvd.html

JS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2woomclqn.html

TS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jsuhpgmx.html

Java: System.err.println("err")
来源：http://dali.hammf.cn/Article/details/gt2oeotjtrn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gt2scazlbfg.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gt2copfmyvd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.316326.xyz/Article/details/gt2zxbosmcz.html

[M07] 判断是否为主入口
来源：http://dali.c1oappe.top/Article/details/gt2htkkrukd.html

Py:   if __name__ == "__main__":
来源：http://dali.xuanzx.com/Article/details/gt2gawgsaav.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jwmkekny.html

JS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gt2dycbxbyz.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gt2agicuhrt.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gt2aavphlsa.html

Go:   func main()
来源：http://dali.c1oappe.top/Article/details/gt2splkpces.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zycfv.cn/Article/details/gt2azqniwxt.html

C#:   static void Main(string[] args)
来源：http://dali.svipenyu.cn/Article/details/gt2ccldfasg.html

[M08] 获取系统与运行时信息
来源：http://dali.cucudq.cn/Article/details/gt2tsscjofe.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rhwsgewg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangdashe.top/Article/details/gt2yncmildg.html

JS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gt2yysnhsnf.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gt2xuspruuy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwhhcytx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnqzz.top/Article/details/gt2furgoais.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gt2hwdmnngg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gt2meeixiqx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ntyhqqcn.html

N. 数据结构与算法
来源：http://dali.birdmap.top/Article/details/gt2ylvuqhse.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2zfdybjha.html

[N01] 二分查找（有序数组）
来源：http://dali.yvedp.cn/Article/details/gt2jbrqepkq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2ufxbbegu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cdnleiting.top/Article/details/gt2drqitnng.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2nojqewju.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gt2ruzqozho.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2pwswfyyd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2oebpvgjm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bbokowqt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2qtvqsbks.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guannengcc.top/Article/details/gt2iblwalbt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gt2photbpvv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ouyobfgi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lcnvupji.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gt2ptlcendw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rczxlbor.html

Go:   slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gt2gshytrcr.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ghirtnkx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cdnleiting.top/Article/details/gt2cslhuzfd.html

[N03] 快速排序（分治示例）
来源：http://dali.zhixingplan.top/Article/details/gt2muftvrup.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.316326.xyz/Article/details/gt2cdxwatll.html


<!-- 参考信息 -->