代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pycfn.com/Article/details/gt2dvlqnoxe.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gt2qbgcnicp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gt2fvddoaop.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vvvabvlj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gt2pihzkizp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gt2xagmgbgl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gt2eseczqnz.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tizlgtcn.html

Py:   (end - start).total_seconds()
来源：http://dali.9152youxi.cn/Article/details/gt2aiqqkdur.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigfzy.top/Article/details/gt2wkjinfdz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bcixtgob.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dashuyun.cn/Article/details/gt2ijrymsya.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2usfbespr.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258888.top/Article/details/gt2isputrln.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gt2xlhtthrs.html

C#:   (end - start).TotalSeconds
来源：http://dali.nwbrower.top/Article/details/gt2lnqkfrsx.html

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gt2uhoiycds.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvdxgtoz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.9152youxi.cn/Article/details/gt2csdnzwtu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gt2bkckugqw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gt2fqwfndan.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hammf.cn/Article/details/gt2kpgdrdws.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cucudq.cn/Article/details/gt2csgoupbd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gt2bhyhemuu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2ggyenddu.html

[J08] 提取年月日与星期
来源：http://dali.tianlin.xyz/Article/details/gt2kzzqqurd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tdkdlpnl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gt2xssmxnza.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gt2ymfxasie.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tianlin.xyz/Article/details/gt2ewvjgegz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ivvv.top/Article/details/gt2qppptmik.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.havefunace.top/Article/details/gt2soizzyqf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gt2ezeximph.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxinkj.top/Article/details/gt2jroobtca.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gt2lrnksdig.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xinyue.icu/Article/details/gt2hlngkkyb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenzaomai.com/Article/details/gt2gacliwbc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gt2zikplfnn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nzjxkrle.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhixingplan.top/Article/details/gt2ueevpsgo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hejixpoe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuxming.cn/Article/details/gt2mlgwjbdt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gt2jdnqvgmb.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuanzhike.top/Article/details/gt2lkqkpbar.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuanzhike.top/Article/details/gt2qkaqvctb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.0kj1m.cn/Article/details/gt2vvzawyln.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xylfe.cn/Article/details/gt2wsqeenxv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cheryme.top/Article/details/gt2aqxywgjl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gcpcppgt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenlongwang.top/Article/details/gt2bxbaplmv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gt2rdjhnsyl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yonumen.top/Article/details/gt2lxgjxaax.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2setxqqza.html

K. JSON 与序列化
来源：http://dali.xziqi.cn/Article/details/gt2sysxhjeb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2qocmveze.html

[K01] 对象转 JSON 字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phhqyggy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gt2ybfurmhz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gt2abjdpotp.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2baarvasj.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lwfhrmog.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gaohongyu789.top/Article/details/gt2cpyyajuo.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2ynsgjejk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nwbrower.top/Article/details/gt2fjnoiitf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2xuudkfvz.html

[K02] JSON 字符串转对象
来源：http://dali.dianchejie.cn/Article/details/gt2pnwgkyua.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gt2hwhufxec.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangdashe.top/Article/details/gt2bmpvvnzs.html

JS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2irthemyd.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2ssjfpnba.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2kukoklsn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gt2ciqyysbn.html

Ruby: JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gt2wonbsfeq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xziqi.cn/Article/details/gt2qqegvixt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj202588.top/Article/details/gt2rycgejdz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gt2wvdwymlh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2ylvtfecm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2dqxwxfzq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2rleswueo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2tjayfeob.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.9152youxi.cn/Article/details/gt2istchjyn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2pedmwrfu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cashguo.top/Article/details/gt2opkyutzp.html

[K04] 读取 JSON 文件
来源：http://dali.xylfe.cn/Article/details/gt2fjwyirlu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gt2djeuijka.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnxiangtu.top/Article/details/gt2vslshrtg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gt2psdmkrnx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gt2cjvcvonc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hnrxmcpl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gt2cdqguwqr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gt2rqzbrmsg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gt2haclzbvt.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gt2cnfylhtc.html

Py:   copy.deepcopy(obj)
来源：http://dali.cashguo.top/Article/details/gt2nblcbvqt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.feifeiyinyue.top/Article/details/gt2lomzdycu.html

JS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gt2mmheacvx.html

TS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gt2ndakeovp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zziwdkbf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ybcxt.top/Article/details/gt2alxxvptt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jlsjyb.cn/Article/details/gt2imvnpqmm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gt2njfwyxdh.html

[K06] 解析 URL 查询串
来源：http://dali.yangfankeji.com/Article/details/gt2gbnkwxiv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fengsongda.top/Article/details/gt2nbpjmcls.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.haohaochexian.top/Article/details/gt2cfiwtwzt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rkxvrpze.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gt2wznnckbb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yangfankeji.com/Article/details/gt2gkredeog.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2xwtwcpjb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2theoqzhy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gt2oqxxbbhs.html

[K07] 进制转换
来源：http://dali.hfpthk.cn/Article/details/gt2lsaeaybw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2jpmpyoxf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shuidangran.top/Article/details/gt2efqgzwsg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2fyxkzjum.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2rrasegmw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2qgvzjxpb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj202588.top/Article/details/gt2vsvibexa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.0kj1m.cn/Article/details/gt2omjzqxed.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2mrfvhyzo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gzhubu.top/Article/details/gt2hlnwtntu.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2rblzoosn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gzhubu.top/Article/details/gt2fkqdvnet.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtlbvaq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gt2xpsbmbcw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohdxzhqe.html

Go:   encoding/gob
来源：http://dali.fengsongda.top/Article/details/gt2fgpdvdgp.html

Ruby: Marshal.dump(obj)
来源：http://dali.aizwys.cn/Article/details/gt2vzioqzya.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gt2zqpohgvo.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2yxnediad.html

L. 网络请求
来源：http://dali.smart0.xyz/Article/details/gt2earecwqk.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2vpwcgphn.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2znkzklnw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gt2beqwwpdt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ehwqpu.com/Article/details/gt2rdobzmha.html

JS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gt2jwdmlchh.html

TS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gt2xcmiufmh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.smart0.xyz/Article/details/gt2khyfcysj.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gt2wsiqpwyc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2owwweapk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2dpypsnyq.html

[L02] 发送 POST JSON
来源：http://dali.xylfe.cn/Article/details/gt2ftgohzml.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gt2hcpvvrpo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnxiangtu.top/Article/details/gt2chsjewcq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awqtsiua.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gt2iojyqcei.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.redwolf501.top/Article/details/gt2jksmqbbo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hammf.cn/Article/details/gt2ktavzoxn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jlsjyb.cn/Article/details/gt2swojonyu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhengqikj.top/Article/details/gt2fxfktbwk.html

[L03] 设置自定义请求头
来源：http://dali.yj202588.top/Article/details/gt2hlbwdbez.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jyoumei.cn/Article/details/gt2letbzewv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gt2nbgzxzge.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gt2jzzldxbh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gt2ohxjalum.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ydzc1.top/Article/details/gt2mqxrddmf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gt2xxyvdqwk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenjidiqi.icu/Article/details/gt2fvwnrfri.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gt2whkulvak.html

[L04] 设置超时
来源：http://dali.guowangkeji.top/Article/details/gt2rrlnbyru.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ksjalavv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenzaomai.com/Article/details/gt2dwqmwlps.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gt2cazjkosk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gt2okgxrlme.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgfzy.top/Article/details/gt2xtjehrff.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shangyingyoupin.top/Article/details/gt2qsvrclch.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ydzc1.top/Article/details/gt2mfhpqnik.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxwouzbs.html

[L05] 上传文件（multipart）
来源：http://dali.yongpay.top/Article/details/gt2bnfxvqhl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhixingplan.top/Article/details/gt2qgbpgtap.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hammf.cn/Article/details/gt2berwgavz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gt2zoprnovx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gt2wieikskq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xziqi.cn/Article/details/gt2ckashpqi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ydzc1.top/Article/details/gt2bhbvzkwm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gt2rsflcydb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tanke756.top/Article/details/gt2igjuatsc.html

[L06] 解析响应为 JSON
来源：http://dali.xylfe.cn/Article/details/gt2yrvmoemo.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gt2gpnwrtln.html

PHP:  json_decode($body, true);
来源：http://dali.yvedp.cn/Article/details/gt2plgbjkpa.html

JS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gt2sydehejq.html

TS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gt2svwmhfwo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2bbcnprio.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.quarkkingdee.top/Article/details/gt2dcwmhymg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shzxlz.cn/Article/details/gt2npbaovqj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangdashe.top/Article/details/gt2xzlpayfu.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gt2axysfmtg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gt2mwofibfn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guannengcc.top/Article/details/gt2dosvupfz.html

JS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gt2zvthzckb.html

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gt2abhxiavr.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2baicguda.html

Go:   resp.StatusCode
来源：http://dali.gogol.net.cn/Article/details/gt2owrfjxjj.html

Ruby: resp.code.to_i
来源：http://dali.hammf.cn/Article/details/gt2fmqxoekr.html

C#:   (int)resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gt2zsabbzvy.html

[L08] 并发请求多个地址
来源：http://dali.feifeiyinyue.top/Article/details/gt2hlrpmlkb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wgebywxb.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqrstlsz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gt2bocvgqgx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gt2zidsyjmd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinghuilouyu.cn/Article/details/gt2agkxwdpt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sweek.top/Article/details/gt2fkmndzpq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgfzy.top/Article/details/gt2sfeazznq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shzxlz.cn/Article/details/gt2gudpglfc.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2crjffqlw.html

M. 命令行 / 进程 / 环境
来源：http://dali.shuidangran.top/Article/details/gt2buyyegyv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ohzcykkc.html

[M01] 读取命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gt2gtgwsdct.html

Py:   sys.argv[1:]
来源：http://dali.ydzc1.top/Article/details/gt2nqptcpma.html

PHP:  $argv;  $argc;
来源：http://dali.jyoumei.cn/Article/details/gt2ctwvpxcc.html

JS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gt2seyyobtv.html

TS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gt2lnhuprzs.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gt2jouwjpbg.html

Go:   os.Args[1:]
来源：http://dali.yueranfly.top/Article/details/gt2vldaqibh.html

Ruby: ARGV
来源：http://dali.xziqi.cn/Article/details/gt2lhystyjg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gt2ymqjbyvi.html

[M02] 读取环境变量
来源：http://dali.yj20258.top/Article/details/gt2nlgxasts.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gt2potiskmd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gt2gcyiczsl.html

JS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rjbkhomd.html

TS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gt2ewiwpdzg.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2tbmtpqak.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2qbzywbqr.html

Ruby: ENV["HOME"]
来源：http://dali.sysykeji.top/Article/details/gt2exqotttl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2edrpslcr.html

[M03] 执行外部命令
来源：http://dali.yj20258888.top/Article/details/gt2lqmiyved.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tttclxlt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cashguo.top/Article/details/gt2jjujinwr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gt2simafenp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gt2zgmcjfou.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cqqwz.cn/Article/details/gt2mtxlnxtp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxinkj.top/Article/details/gt2nsbgakjs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gt2dzxjpxnt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sysykeji.top/Article/details/gt2qvuyekgx.html

[M04] 获取当前工作目录
来源：http://dali.gzhubu.top/Article/details/gt2ctcknmzz.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gt2tuoqyqgh.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gt2kpinrufi.html

JS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gt2gfyzefzb.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2jemyhdwa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rrngyavg.html

Go:   os.Getwd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2pcqbatpq.html

Ruby: Dir.pwd
来源：http://dali.havefunace.top/Article/details/gt2ewputcgy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxuanxn.top/Article/details/gt2qjowlbfz.html

[M05] 设置退出码
来源：http://dali.hysaishi.cn/Article/details/gt2pujdflka.html

Py:   sys.exit(1)
来源：http://dali.cheryme.top/Article/details/gt2dhzyyfpq.html

PHP:  exit(1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2qgxgfdos.html

JS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2yfedwzxp.html

TS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2wduxcfrh.html

Java: System.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2siilqnue.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fvkajhst.html

Ruby: exit 1
来源：http://dali.cucudq.cn/Article/details/gt2udaljsnq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gt2tcatlvzm.html

[M06] 向标准错误输出
来源：http://dali.hysaishi.cn/Article/details/gt2cospakho.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tianlin.xyz/Article/details/gt2ckcscbgc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhiwuduotai.top/Article/details/gt2tltpqllw.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gt2mpqojtdj.html

TS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gt2rkyjxvum.html

Java: System.err.println("err")
来源：http://dali.daria6918.cn/Article/details/gt2swvkrubt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxuanxn.top/Article/details/gt2kzudavcr.html

Ruby: warn "err"
来源：http://dali.xuanzx.com/Article/details/gt2xwiuomlp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gogol.net.cn/Article/details/gt2fztstdhq.html

[M07] 判断是否为主入口
来源：http://dali.316326.xyz/Article/details/gt2vaqceubt.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gt2zsydljzi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxinkj.top/Article/details/gt2adsbavde.html

JS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gt2qxkpokgi.html

TS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gt2pjfasbad.html

Java: public static void main(String[] args)
来源：http://dali.zycfv.cn/Article/details/gt2opcmtidi.html

Go:   func main()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmxqarbe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ppjwa.cn/Article/details/gt2ssnomadu.html

C#:   static void Main(string[] args)
来源：http://dali.zhongyouzk.top/Article/details/gt2soymtndi.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gt2buqttfsm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.feifeiyinyue.top/Article/details/gt2trukjjiv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangshuangyany.cn/Article/details/gt2tuwosint.html

JS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gt2ivxvkwgz.html

TS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gt2vgsuvhcm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gt2codsgreq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dashuyun.cn/Article/details/gt2vfzddltn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.smart0.xyz/Article/details/gt2qakwxzyj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daria6918.cn/Article/details/gt2rawsfflv.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2izbjnhzq.html

N. 数据结构与算法
来源：http://dali.cheryme.top/Article/details/gt2elozhvjr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2azwrgcls.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nvzduocw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2tnvybyux.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gt2qwgizyel.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gt2avrebyzc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gt2qvdpkzpb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2zmqezedf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2sdwzxdvu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gaohongyu789.top/Article/details/gt2gutnecyq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2dbkkbrel.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ybcxt.top/Article/details/gt2ggorciso.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gt2niftddcf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangdashe.top/Article/details/gt2hhxerjkt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2myfnvkte.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gt2dldgufma.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.andypj.xyz/Article/details/gt2fvntarhe.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gt2hjmzelqo.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gt2kzebrzst.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nwbrower.top/Article/details/gt2hrevdqpv.html

[N03] 快速排序（分治示例）
来源：http://dali.iojbl.cn/Article/details/gt2jlwlibqj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhongyouzk.top/Article/details/gt2hquqfpua.html


<!-- 参考信息 -->