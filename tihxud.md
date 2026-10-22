代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yangfankeji.com/Article/details/gt2utkppfva.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gt2rcpaueco.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gt2qzkxtajt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnxiangtu.top/Article/details/gt2ltlomyfa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gotoacloud.top/Article/details/gt2dcxyuhfp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gt2nrcfofry.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2kfyptxen.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hammf.cn/Article/details/gt2cvqxydgu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangdashe.top/Article/details/gt2eecehmvl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2zfwnnpeo.html

[J05] 时间加减（加 7 天）
来源：http://dali.jlsjyb.cn/Article/details/gt2iuvxnrxu.html

Py:   now + timedelta(days=7)
来源：http://dali.zycfv.cn/Article/details/gt2czfavqvl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qllvefix.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxmwzqnl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gt2jemetett.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zjbcjmqm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhixingplan.top/Article/details/gt2epwnltvo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangshuangyany.cn/Article/details/gt2hfvkrskx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zqpcgihf.html

[J06] 计算两时间之差
来源：http://dali.gaohongyu789.top/Article/details/gt2gtkjsasc.html

Py:   (end - start).total_seconds()
来源：http://dali.jlsjyb.cn/Article/details/gt2rfoirdsk.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gt2hktepjyg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigufen.top/Article/details/gt2kdeirwua.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gt2shmjpcws.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cucudq.cn/Article/details/gt2fotiwnwd.html

Go:   end.Sub(start).Hours()
来源：http://dali.zdqjudy.top/Article/details/gt2dgeegiwi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hfpthk.cn/Article/details/gt2sqbnsgql.html

C#:   (end - start).TotalSeconds
来源：http://dali.xylfe.cn/Article/details/gt2dylvadlt.html

[J07] 比较两个日期
来源：http://dali.sxryk.cn/Article/details/gt2rqtvjqpr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gt2idtuzpyn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ohkqutnm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gt2zlpjzefn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gt2lsuvtnzy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cashguo.top/Article/details/gt2cuohfhzz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbrczdmf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2yolunyhh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gt2dfrlrlxt.html

[J08] 提取年月日与星期
来源：http://dali.yonumen.top/Article/details/gt2zvlksjcc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cashguo.top/Article/details/gt2qisgtzcr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.iojbl.cn/Article/details/gt2vjyykhbr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cqqwz.cn/Article/details/gt2mpbpelcn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ehwqpu.com/Article/details/gt2iqznombe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigfzy.top/Article/details/gt2dseggkpg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenlongwang.top/Article/details/gt2ylabkeay.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ozzotsit.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tian-w.cn/Article/details/gt2zshprvnp.html

[J09] 时区处理
来源：http://dali.smart0.xyz/Article/details/gt2anijaigp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aizwys.cn/Article/details/gt2cmgbuiln.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rojferhb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gt2yjhvgdks.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gt2fahdqwtq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.vqdsnc.cn/Article/details/gt2hlgstwnu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sufxvd.cn/Article/details/gt2anfwvyms.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258888.top/Article/details/gt2jvohmufe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.kuanghao11.cn/Article/details/gt2djsieuyz.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gt2uapoaejr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ehwqpu.com/Article/details/gt2csbszfoo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.kuanghao11.cn/Article/details/gt2xfjwugfr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daria6918.cn/Article/details/gt2qsqyuycl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.redwolf501.top/Article/details/gt2smrrmppz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aibaodan.cn/Article/details/gt2uadqppxt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zycfv.cn/Article/details/gt2muflaxdx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gotoacloud.top/Article/details/gt2xyccikdk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2lnobtfjz.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2mrbvdbve.html

K. JSON 与序列化
来源：http://dali.tian-w.cn/Article/details/gt2rgqhtqsb.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2jhnlmvgg.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2tanimlnv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gt2stsukqvs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gt2pbywjzpp.html

JS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2iozbfnrk.html

TS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gt2jodfpcxr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gt2gehumfpd.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gt2ednrbuhy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.mhx1999.top/Article/details/gt2twxmwdch.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daxiang520.top/Article/details/gt2ugqwqoyr.html

[K02] JSON 字符串转对象
来源：http://dali.jianghu66.top/Article/details/gt2zasqnlxo.html

Py:   json.loads(s)
来源：http://dali.gotoacloud.top/Article/details/gt2ccjnitme.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gt2bvmzfzcf.html

JS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gt2kahzoldx.html

TS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jlwxpsmd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gufqaaft.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gt2ugkurzhj.html

Ruby: JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ehrcsvzz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sweek.top/Article/details/gt2ncywatsr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sysykeji.top/Article/details/gt2ivnrsdtl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gt2eqounalh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gt2fuehxbfo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gt2zzdehwux.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2gtizmafu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2nftftfrk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.meibo888.top/Article/details/gt2aahmwwdb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sxryk.cn/Article/details/gt2mhmmehqr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dobzuybq.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gt2zhuprbwf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hammf.cn/Article/details/gt2ruwavjdy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xziqi.cn/Article/details/gt2wgkkswxi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iufsgoas.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gt2rlimomph.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gt2egtyugcd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gt2cyrrqjsf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gt2oeiennri.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gt2xswtonvp.html

[K05] 深拷贝对象
来源：http://dali.yuanzhike.top/Article/details/gt2zfdvwlbd.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258.top/Article/details/gt2aqtukxqv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigufen.top/Article/details/gt2jsjtcpjk.html

JS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2djtkgoct.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbltfyh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gt2wwwywnzk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangdashe.top/Article/details/gt2hevdyujy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzlgrjsl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.andypj.xyz/Article/details/gt2lcbsbpkx.html

[K06] 解析 URL 查询串
来源：http://dali.zycfv.cn/Article/details/gt2opgnevpw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gt2wntugmkh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hywenlv.cn/Article/details/gt2dnfauinj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gt2yqipfvxr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gt2oaseqytc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gt2patluobk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2zdttxhvn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gt2ceenlkcy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gt2gkbmzzfu.html

[K07] 进制转换
来源：http://dali.ivvv.top/Article/details/gt2yaxmmtzf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaimnbew.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cucudq.cn/Article/details/gt2ivverozk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mqlbzqxm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2dtoblkkp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2xsjhliej.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pycfn.com/Article/details/gt2xnpikezq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenzaomai.com/Article/details/gt2hbdaytwk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykthjmqi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yueranfly.top/Article/details/gt2pemzmwma.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2jkvnnabm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jianghu66.top/Article/details/gt2qlrgtcnt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gt2enfuqoey.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gt2svuouacx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gt2tjqwlxvz.html

Go:   encoding/gob
来源：http://dali.sufxvd.cn/Article/details/gt2tvyvmdlb.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2czywkkjr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gt2wupgwkjg.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2wgbukjxg.html

L. 网络请求
来源：http://dali.yuxming.cn/Article/details/gt2pbxzlcoh.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2seukrpre.html

[L01] 发送 GET 请求
来源：http://dali.pengpengdd.cyou/Article/details/gt2oarqlkam.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fengsongda.top/Article/details/gt2cvuftxcs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cdnleiting.top/Article/details/gt2svzlfnmt.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gt2rklfxxyt.html

TS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gt2sxenketb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.feifeiyinyue.top/Article/details/gt2nechokct.html

Go:   resp, err := http.Get(url)
来源：http://dali.zycfv.cn/Article/details/gt2wgdqkdxh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shuidangran.top/Article/details/gt2jbnclknw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wcdyvsgl.html

[L02] 发送 POST JSON
来源：http://dali.mhx1999.top/Article/details/gt2qgfgsxvo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xnaeztmt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sweek.top/Article/details/gt2oaaafndi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gt2vwmnrpbz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gt2ianzxixp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkfipkhn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenlongwang.top/Article/details/gt2tiwfuqeh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gotoacloud.top/Article/details/gt2fhsxykyv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xinyue.icu/Article/details/gt2nmupgcps.html

[L03] 设置自定义请求头
来源：http://dali.gotoacloud.top/Article/details/gt2wnuccbaq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zycfv.cn/Article/details/gt2yukecmpu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jianghu66.top/Article/details/gt2uwrhxufj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njrnivam.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gt2kcxzpewl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sweek.top/Article/details/gt2otjptqpa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gt2qttrpqlw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ydzc1.top/Article/details/gt2emiugbht.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gt2akbysmql.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gt2amufwtch.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gaohongyu789.top/Article/details/gt2riemsiro.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yueranfly.top/Article/details/gt2sspwabrq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gt2qjtdxxpa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gt2yxppdnap.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daria6918.cn/Article/details/gt2wootakpt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gt2pfemjezu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gogol.net.cn/Article/details/gt2supcenys.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hfpthk.cn/Article/details/gt2asskvnts.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gt2mqpxofnl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sufxvd.cn/Article/details/gt2grmxxzan.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gt2isocyono.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gt2rgideupn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gt2olgpkiut.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.vqdsnc.cn/Article/details/gt2siettcvq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovhdbqmx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gt2tdybgswc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cashguo.top/Article/details/gt2dazwqhmw.html

[L06] 解析响应为 JSON
来源：http://dali.jiagoushi.top/Article/details/gt2qeymadta.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gt2rxwpjzfc.html

PHP:  json_decode($body, true);
来源：http://dali.fengsongda.top/Article/details/gt2cbtthnmu.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2xupifgjo.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2inoywwxb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dosapsca.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.0kj1m.cn/Article/details/gt2mqhiezgb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkqnwnib.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.smart0.xyz/Article/details/gt2rxfvvhvo.html

[L07] 处理 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gt2vstewnum.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gt2rmvwauki.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hywenlv.cn/Article/details/gt2ctbkfupz.html

JS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gt2qqvqymmb.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gt2yjxbhaow.html

Java: resp.statusCode()
来源：http://dali.gogol.net.cn/Article/details/gt2djelohij.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gt2hgedwdzv.html

Ruby: resp.code.to_i
来源：http://dali.vqdsnc.cn/Article/details/gt2qrntbloy.html

C#:   (int)resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gt2qufuznxs.html

[L08] 并发请求多个地址
来源：http://dali.xziqi.cn/Article/details/gt2xmhcwqqi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hammf.cn/Article/details/gt2baawmjvm.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gt2iowrvrmg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2engytuvg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gt2zpqejppo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.iojbl.cn/Article/details/gt2hnekuuwn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tanke756.top/Article/details/gt2snjusgam.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shuidangran.top/Article/details/gt2wqsvrpnp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gt2lqbolawe.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2xwjhzedl.html

M. 命令行 / 进程 / 环境
来源：http://dali.316326.xyz/Article/details/gt2wchudvsz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2zpnpphsl.html

[M01] 读取命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gt2tywuqxhm.html

Py:   sys.argv[1:]
来源：http://dali.gogol.net.cn/Article/details/gt2npwofwiz.html

PHP:  $argv;  $argc;
来源：http://dali.vqdsnc.cn/Article/details/gt2caakrvuw.html

JS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gt2pirifqus.html

TS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gt2yoijczib.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gt2fzfwstfb.html

Go:   os.Args[1:]
来源：http://dali.fengsongda.top/Article/details/gt2yrhshegs.html

Ruby: ARGV
来源：http://dali.shangyingyoupin.top/Article/details/gt2wxzesket.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gt2yiksmjjm.html

[M02] 读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gt2uwgqmnek.html

Py:   os.environ.get("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2senddzhb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gt2trtbsees.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gt2sqlyqflv.html

TS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gt2jufonxfi.html

Java: System.getenv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2euojuuxb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shuidangran.top/Article/details/gt2ufmjzqgh.html

Ruby: ENV["HOME"]
来源：http://dali.vqdsnc.cn/Article/details/gt2fbkjmmem.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gt2yabtawaq.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gt2gdgpeueu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangdashe.top/Article/details/gt2oeesndzn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aizwys.cn/Article/details/gt2mwmwhnke.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2efiwrdxa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2runveppg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nwbrower.top/Article/details/gt2rqymxtwi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gaohongyu789.top/Article/details/gt2ziltwpzx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2azjffjwm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aibaodan.cn/Article/details/gt2kdlvrkmj.html

[M04] 获取当前工作目录
来源：http://dali.sxryk.cn/Article/details/gt2wtrwnibt.html

Py:   os.getcwd()
来源：http://dali.jyoumei.cn/Article/details/gt2bwbotbmw.html

PHP:  getcwd();
来源：http://dali.dashuyun.cn/Article/details/gt2jnqmidqk.html

JS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gt2ksvklfpg.html

TS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gt2fkwtjczu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2stdhmhie.html

Go:   os.Getwd()
来源：http://dali.yj202588.top/Article/details/gt2eadocnde.html

Ruby: Dir.pwd
来源：http://dali.ydzc1.top/Article/details/gt2xhrczaol.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jianghu66.top/Article/details/gt2scjcuuyq.html

[M05] 设置退出码
来源：http://dali.aibaodan.cn/Article/details/gt2uzyyuzmm.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tabglppy.html

PHP:  exit(1);
来源：http://dali.daxiang520.top/Article/details/gt2bnscftrb.html

JS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gt2exodjvsr.html

TS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2lcmbuqey.html

Java: System.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2ffocggoi.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jspubzca.html

Ruby: exit 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2prfqswbl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.mhx1999.top/Article/details/gt2kvqmhzya.html

[M06] 向标准错误输出
来源：http://dali.redwolf501.top/Article/details/gt2ixjajsvf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gt2qzkekvdb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gt2vpzrjaei.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrzzirs.html

TS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gt2bdtqihzc.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjqklrle.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgufenzy.top/Article/details/gt2oyncjgiw.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gt2lkzyvdkj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gt2tibhnpke.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gt2mhwkswux.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2fsffnykt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tian-w.cn/Article/details/gt2dapbrndz.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvswswzv.html

TS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gt2esyizqym.html

Java: public static void main(String[] args)
来源：http://dali.ybcxt.top/Article/details/gt2uqxmnpjf.html

Go:   func main()
来源：http://dali.cqqwz.cn/Article/details/gt2bppcdons.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cashguo.top/Article/details/gt2kiuwwnkx.html

C#:   static void Main(string[] args)
来源：http://dali.zdqjudy.top/Article/details/gt2pjvtrckd.html

[M08] 获取系统与运行时信息
来源：http://dali.sxryk.cn/Article/details/gt2kithouhn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sxryk.cn/Article/details/gt2zqttbziy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daxiang520.top/Article/details/gt2xqgcpujw.html

JS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gt2evmsbjdm.html

TS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gt2ywgppjhl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.andypj.xyz/Article/details/gt2psxkrans.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jiagoushi.top/Article/details/gt2vpufbbev.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gt2bgbslzpy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gt2xwhcvrkg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2yuucerlk.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gt2stppjdlv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2sbzntcoj.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gt2biidgvwg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2diclarok.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gt2pbgvupfc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gt2idvkkjuh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gt2oepdkbzv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2slsqoaot.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2gckeuhsa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tianlin.xyz/Article/details/gt2rhoyytoy.html


<!-- 参考信息 -->