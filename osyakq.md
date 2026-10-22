代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtwzqhyqxc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtvedcbegy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gttblkdhhh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtkdmsaovt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ehwqpu.com/Article/details/gtmnyfnrwo.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigfzy.top/Article/details/gtfdkkylrs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tanke756.top/Article/details/gtwyfutfzs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ehwqpu.com/Article/details/gtkubqzafb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zycfv.cn/Article/details/gtwuezhvia.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yangfankeji.com/Article/details/gtiqlaaxzz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfbcesca.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guowangkeji.top/Article/details/gtgkcrfasr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258.top/Article/details/gtzpgeogqi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guannengcc.top/Article/details/gtyulyovnd.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenlongwang.top/Article/details/gtjxrqfpfr.html

Py:   now + timedelta(days=7)
来源：http://dali.sweek.top/Article/details/gthfzxwxkf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cheryme.top/Article/details/gtbrbltnnv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gteosvfyun.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnoysfzlw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.redwolf501.top/Article/details/gtaiweqaux.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gtaztqislu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sysykeji.top/Article/details/gtvesidlyj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxesjydn.html

[J06] 计算两时间之差
来源：http://dali.9152youxi.cn/Article/details/gtgqlagjqr.html

Py:   (end - start).total_seconds()
来源：http://dali.zhixingplan.top/Article/details/gtlxcnvihd.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gttuwntuyh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cqqwz.cn/Article/details/gtywnxclwm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ydzc1.top/Article/details/gtrtoryptz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ivvv.top/Article/details/gthqihdbva.html

Go:   end.Sub(start).Hours()
来源：http://dali.tanke756.top/Article/details/gtautsekwq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cqqwz.cn/Article/details/gtaidmhwgf.html

C#:   (end - start).TotalSeconds
来源：http://dali.yvedp.cn/Article/details/gtfnijdhsm.html

[J07] 比较两个日期
来源：http://dali.hywenlv.cn/Article/details/gtohagtwfi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtftnssrzb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tian-w.cn/Article/details/gttmhmhjdy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gtmpmfidge.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtbhlaiocd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj202588.top/Article/details/gtnkciogfo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ivvv.top/Article/details/gtvnkwzxlg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gtxypzbxok.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtajmzgghh.html

[J08] 提取年月日与星期
来源：http://dali.zhiwuduotai.top/Article/details/gtwkgqofax.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.9152youxi.cn/Article/details/gtiprayzov.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gaohongyu789.top/Article/details/gttlneczio.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jiagoushi.top/Article/details/gtagpjqzcn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gtihiwmlrp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shzxlz.cn/Article/details/gtmumitjuf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cashguo.top/Article/details/gtzlwptyck.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhixingplan.top/Article/details/gtnblmbnva.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.vqdsnc.cn/Article/details/gtqzzxgvys.html

[J09] 时区处理
来源：http://dali.ppjwa.cn/Article/details/gtylmhzgfw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.haohaochexian.top/Article/details/gtkrktzwfl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zycfv.cn/Article/details/gtxcxjimci.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtutqrqgrr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtvhgrrxcm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ydzc1.top/Article/details/gtbtucybnt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gtyxwpbsrk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yongpay.top/Article/details/gtlxgrnqzk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tianlin.xyz/Article/details/gtgpbiakhw.html

[J10] 取今天 / 本月第一天
来源：http://dali.aizwys.cn/Article/details/gtipecwgni.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gtxsmnnipv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gtfmddanpw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuanzhike.top/Article/details/gtkyfwouqs.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yongpay.top/Article/details/gtydjicgqz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yueranfly.top/Article/details/gtmdccdbmy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvplixezt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gtwlfbioxj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.meibo888.top/Article/details/gtcavoggek.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtwltzwzsu.html

K. JSON 与序列化
来源：http://dali.xylfe.cn/Article/details/gtgkhrfmhb.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxjxfiybf.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgufenzy.top/Article/details/gteqtbiuut.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gtktxpnezg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtmqbmjyed.html

JS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gtutmezoem.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtuqofhfif.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sufxvd.cn/Article/details/gtqefmcrgk.html

Go:   json.Marshal(obj)
来源：http://dali.chenzaomai.com/Article/details/gtebamwgma.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258888.top/Article/details/gtugmkdbak.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yvedp.cn/Article/details/gtbwmhqgpa.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumjxldau.html

Py:   json.loads(s)
来源：http://dali.guowangkeji.top/Article/details/gtiluieylk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.snrcjt.cn/Article/details/gtijnrfuqy.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtoqeqyltp.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtccksdwad.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtfykfixsi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gtpvnievhe.html

Ruby: JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gttnknazew.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.svipenyu.cn/Article/details/gtosnutddg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.kuanghao11.cn/Article/details/gthibngwoq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gtxnodipeg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgocuoook.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtinlipqgq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gtfnpsbfcm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.redwolf501.top/Article/details/gttnfbrvgr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pengpengdd.cyou/Article/details/gtsvtimllj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.mhx1999.top/Article/details/gtydzpxsxj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.andypj.xyz/Article/details/gtpfdixrtc.html

[K04] 读取 JSON 文件
来源：http://dali.yj202588.top/Article/details/gthjlvirfp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxinkj.top/Article/details/gthjwytybl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.feifeiyinyue.top/Article/details/gtovdlhqrk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gtbldotjal.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtidgbrosq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xinyue.icu/Article/details/gtykxwxxdy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gtqihzmzsp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtphspnmyu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cashguo.top/Article/details/gtrtfikrul.html

[K05] 深拷贝对象
来源：http://dali.zycfv.cn/Article/details/gtpirfouor.html

Py:   copy.deepcopy(obj)
来源：http://dali.316326.xyz/Article/details/gteozgugxh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fengsongda.top/Article/details/gtaouisxhw.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqenznwd.html

TS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtxgbwbasj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yvedp.cn/Article/details/gtfqtiamml.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cdnleiting.top/Article/details/gtjwdyjtoo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gtleerjlud.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yonumen.top/Article/details/gthdhjhsyi.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gtoumiofkg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ivvv.top/Article/details/gtgirwtdtp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xziqi.cn/Article/details/gtqtnqqjtu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtxvcmgvxz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtjkswnxlr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hfpthk.cn/Article/details/gtrcluimgl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthioqctyw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtygfnlxch.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtcngtstrs.html

[K07] 进制转换
来源：http://dali.gogol.net.cn/Article/details/gtolltvxgf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtutplnxkp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gtywtscnnq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtkvpkyjej.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtaamvpxbw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtfbfqxfmo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.0kj1m.cn/Article/details/gtzwlzmexk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fzhhl.top/Article/details/gtyyzfmysf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtbyvejbel.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aizwys.cn/Article/details/gtaysvmgut.html

Py:   pickle.dumps(obj)
来源：http://dali.shuidangran.top/Article/details/gtapeuiysb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cheryme.top/Article/details/gthgiznkyl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gtuuogwfru.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gtptvdunme.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gtvjpqkqcc.html

Go:   encoding/gob
来源：http://dali.fzhhl.top/Article/details/gtaxubblbc.html

Ruby: Marshal.dump(obj)
来源：http://dali.shzxlz.cn/Article/details/gtldlbdkpt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtlmdsvvpg.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtsjfxdymv.html

L. 网络请求
来源：http://dali.xziqi.cn/Article/details/gtbhwdjmjn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtedmugmkv.html

[L01] 发送 GET 请求
来源：http://dali.jianghu66.top/Article/details/gtvgymawir.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gtiwkmiuav.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gtxqjwhljq.html

JS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gtsssfrsyt.html

TS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gtvopbabko.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yueranfly.top/Article/details/gtogzluxwu.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gtqduvinwn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgufenzy.top/Article/details/gtsobdfspm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.havefunace.top/Article/details/gtecbpisti.html

[L02] 发送 POST JSON
来源：http://dali.redwolf501.top/Article/details/gtsigzlddu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gtyxamifsh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.meibo888.top/Article/details/gtvgjqjtul.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtxsmumgpw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtyguavrod.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigufen.top/Article/details/gtgqgbpzbe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gzhubu.top/Article/details/gtbmncacqe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.vqdsnc.cn/Article/details/gtapjtixqp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258.top/Article/details/gttyjrzyni.html

[L03] 设置自定义请求头
来源：http://dali.shuidangran.top/Article/details/gtagvawtze.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.9152youxi.cn/Article/details/gtcebohyir.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnxiangtu.top/Article/details/gtlqblntfy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtpmobxbia.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtxnfyvmrz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqzvrgfk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtfgunreck.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ehwqpu.com/Article/details/gtnahtvpau.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gtllwqunyd.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gtfgwrblii.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenlongwang.top/Article/details/gtmwucaozc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zdqjudy.top/Article/details/gtdfismkxy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gtgifuwygl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gtvrfqdwit.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tanke756.top/Article/details/gtzlvzjpde.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dianchejie.cn/Article/details/gtmbpnsvkr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daria6918.cn/Article/details/gtwdwachmm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hfpthk.cn/Article/details/gtwrxpjqnd.html

[L05] 上传文件（multipart）
来源：http://dali.nanxuanxn.top/Article/details/gtwqqgpzgv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gaohongyu789.top/Article/details/gtlzxysgir.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gtppckrzgh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gtefseawqy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gttaodubkt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aizwys.cn/Article/details/gtiplrybxh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gtssfjbgfr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnqzz.top/Article/details/gtgjloqotn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtzaohixvs.html

[L06] 解析响应为 JSON
来源：http://dali.nanxinkj.top/Article/details/gtguymarbt.html

Py:   resp.json()
来源：http://dali.daxiang520.top/Article/details/gtlfvrvvob.html

PHP:  json_decode($body, true);
来源：http://dali.ppjwa.cn/Article/details/gtaxwepwbg.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtszzstyzm.html

TS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtqhqlctoy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ivvv.top/Article/details/gtroewimxm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gtowitbsos.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fzhhl.top/Article/details/gtsebfufxh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ehwqpu.com/Article/details/gtsfbxyemj.html

[L07] 处理 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gttbjdsirq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tianlin.xyz/Article/details/gtmxkzvqqs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtxnuliqlf.html

JS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gtlzqkxoui.html

TS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtoorfqrfj.html

Java: resp.statusCode()
来源：http://dali.shangyingyoupin.top/Article/details/gtywscrglz.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtgkixpgdx.html

Ruby: resp.code.to_i
来源：http://dali.aibaodan.cn/Article/details/gtrjnsoywx.html

C#:   (int)resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtsfanbnyk.html

[L08] 并发请求多个地址
来源：http://dali.shzxlz.cn/Article/details/gtbwdbilua.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gthdndloul.html

PHP:  curl_multi_init() 系列
来源：http://dali.gotoacloud.top/Article/details/gtwzdjlofi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtpytshp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtgfouaylv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ehwqpu.com/Article/details/gtfmimwhpb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.meibo888.top/Article/details/gtdwngzvdb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yonumen.top/Article/details/gtthirhkhb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zycfv.cn/Article/details/gtlvwstktj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtdgzscwfr.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkzuwkbr.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyxdzgas.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gtxuhgpjjp.html

Py:   sys.argv[1:]
来源：http://dali.dashuyun.cn/Article/details/gtnplnqyxd.html

PHP:  $argv;  $argc;
来源：http://dali.hysaishi.cn/Article/details/gtclphpfqh.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtrvdzdcnn.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtprinzmal.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtwakkcgbd.html

Go:   os.Args[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtyuuntxcp.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gtdguxaald.html

C#:   args 数组（Main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtmpmdgphp.html

[M02] 读取环境变量
来源：http://dali.guannengcc.top/Article/details/gtrvguiqza.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtkpecoaoq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtoxyjiohe.html

JS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtrpvmraig.html

TS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtfyuxpazx.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdyzljtl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sysykeji.top/Article/details/gtwhjruhvb.html

Ruby: ENV["HOME"]
来源：http://dali.zhiwuduotai.top/Article/details/gtfbbylqta.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtzvsnxpnk.html

[M03] 执行外部命令
来源：http://dali.hongshengwenyu.top/Article/details/gtvhlwiqba.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xziqi.cn/Article/details/gtnaivwlog.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gtzufxwsug.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtjhmsctnv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtrmddtrch.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pycfn.com/Article/details/gtfaeiakgh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258888.top/Article/details/gtkptyiyau.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.meibo888.top/Article/details/gtqmdsrpkl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jyoumei.cn/Article/details/gtmptclxet.html

[M04] 获取当前工作目录
来源：http://dali.zhongyouzk.top/Article/details/gtpzcfhiux.html

Py:   os.getcwd()
来源：http://dali.svipenyu.cn/Article/details/gtyujjkifh.html

PHP:  getcwd();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolmrvgvh.html

JS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtmihgxasv.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtaiaiumst.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hysaishi.cn/Article/details/gtcejtennb.html

Go:   os.Getwd()
来源：http://dali.mhx1999.top/Article/details/gtvpweblgl.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzksgols.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hywenlv.cn/Article/details/gtozxkyinm.html

[M05] 设置退出码
来源：http://dali.chenjidiqi.icu/Article/details/gtdfantaku.html

Py:   sys.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtrhgxxgkb.html

PHP:  exit(1);
来源：http://dali.0kj1m.cn/Article/details/gtthoqyzhk.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgowydsu.html

TS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtupdflyod.html

Java: System.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtqtxqhrlf.html

Go:   os.Exit(1)
来源：http://dali.cashguo.top/Article/details/gtvjquvdep.html

Ruby: exit 1
来源：http://dali.ybcxt.top/Article/details/gtggqfhgyc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.havefunace.top/Article/details/gtemwkqmfu.html

[M06] 向标准错误输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigmbbumt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gteqnijvvt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecrwjmlg.html

JS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gtbnbzogha.html

TS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtgxzhteur.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gtxvggejhw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yonumen.top/Article/details/gtiqztwrnk.html

Ruby: warn "err"
来源：http://dali.zhixingplan.top/Article/details/gtqtmcgycf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtonwiqocc.html

[M07] 判断是否为主入口
来源：http://dali.feifeiyinyue.top/Article/details/gtzmopvgxb.html

Py:   if __name__ == "__main__":
来源：http://dali.9152youxi.cn/Article/details/gtywtpvvrz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gtikbrwret.html

JS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gtrlvbawkd.html

TS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrdzwtyl.html

Java: public static void main(String[] args)
来源：http://dali.yonumen.top/Article/details/gtsgdokqcx.html

Go:   func main()
来源：http://dali.yueranfly.top/Article/details/gtfkwkbouw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.svipenyu.cn/Article/details/gtyirfwbnh.html

C#:   static void Main(string[] args)
来源：http://dali.ydzc1.top/Article/details/gtxnbzneim.html

[M08] 获取系统与运行时信息
来源：http://dali.mhx1999.top/Article/details/gttpedvlkq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pycfn.com/Article/details/gtpyqbefnn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.iojbl.cn/Article/details/gtytmymaqy.html

JS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtvmnecgek.html

TS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gtartyxgea.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jiagoushi.top/Article/details/gttqjkpapu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cqqwz.cn/Article/details/gtwbsojpzf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fengsongda.top/Article/details/gthovtvksn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cashguo.top/Article/details/gtbiahdrok.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtwnfvosyl.html

N. 数据结构与算法
来源：http://dali.gogol.net.cn/Article/details/gtyerqmdzl.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtydwsmohm.html

[N01] 二分查找（有序数组）
来源：http://dali.zycfv.cn/Article/details/gtarnldhvx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtjbowrzos.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shuidangran.top/Article/details/gtphxbfsal.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtjjateqby.html


<!-- 参考信息 -->