代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2zinbkqgi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2kusidvwx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2zlvzmhjd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2zfhafprw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gt2zytgebfy.html

[J04] 时间戳与日期互转
来源：http://dali.tian-w.cn/Article/details/gt2xsrkoxfr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmmlpjtc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gt2ispjduov.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zycfv.cn/Article/details/gt2wwiytmmy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gt2ucnneniw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2dqdpuzhz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gt2fxjsdhef.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2atfveopu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2zfeqoeze.html

[J05] 时间加减（加 7 天）
来源：http://dali.sweek.top/Article/details/gt2ofdlqwvo.html

Py:   now + timedelta(days=7)
来源：http://dali.guowangkeji.top/Article/details/gt2qtbfimse.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhengqikj.top/Article/details/gt2nqkdsscu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gt2qvjrnpxz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gt2hibcectb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hysaishi.cn/Article/details/gt2pztzjtph.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gt2sbqmemln.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gt2jszcxmwp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gt2auyeinwe.html

[J06] 计算两时间之差
来源：http://dali.tian-w.cn/Article/details/gt2vqhuqaaf.html

Py:   (end - start).total_seconds()
来源：http://dali.yuanzhike.top/Article/details/gt2nqdjwxqg.html

PHP:  $end->diff($start)->days;
来源：http://dali.tianlin.xyz/Article/details/gt2feymiodk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sufxvd.cn/Article/details/gt2hknbvnxl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqslryuq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgufenzy.top/Article/details/gt2tvxkjgzg.html

Go:   end.Sub(start).Hours()
来源：http://dali.guowangkeji.top/Article/details/gt2qglienpv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shangyingyoupin.top/Article/details/gt2qztlmlwr.html

C#:   (end - start).TotalSeconds
来源：http://dali.ydzc1.top/Article/details/gt2ukrwtfoo.html

[J07] 比较两个日期
来源：http://dali.zhiwuduotai.top/Article/details/gt2jwngqfft.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gt2jsxtplyl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yangfankeji.com/Article/details/gt2xeociato.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gt2lugxwcra.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gt2jcxzjrlw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gt2ewuojdhu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ivvv.top/Article/details/gt2dprbbtff.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gt2bmudquws.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2irdrrmob.html

[J08] 提取年月日与星期
来源：http://dali.c1oappe.top/Article/details/gt2wktfagcx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuanzhike.top/Article/details/gt2coubsppn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daria6918.cn/Article/details/gt2yzkywgnz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shuidangran.top/Article/details/gt2fiwfnqyg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jiagoushi.top/Article/details/gt2sfjzlxew.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yongpay.top/Article/details/gt2cnhdjyox.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yueranfly.top/Article/details/gt2rbqidjdh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guowangkeji.top/Article/details/gt2rsukkoun.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tanke756.top/Article/details/gt2bkrnttpg.html

[J09] 时区处理
来源：http://dali.ehwqpu.com/Article/details/gt2ungcuotw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sxryk.cn/Article/details/gt2bzfqfomj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258888.top/Article/details/gt2cwhxkrxs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gt2gebzvxvj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gt2trltotoe.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gt2ojmwnjyb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuanzx.com/Article/details/gt2jjwztclg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gotoacloud.top/Article/details/gt2rmatgyya.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwblgml.html

[J10] 取今天 / 本月第一天
来源：http://dali.cucudq.cn/Article/details/gt2ppegaxfv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gt2yqzxnnbk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2iojilutm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gt2gurybqvz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2ssagwzvp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgfzy.top/Article/details/gt2irntsgnh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jyoumei.cn/Article/details/gt2eaafyvjx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fuldpjqj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gotoacloud.top/Article/details/gt2joxcrswc.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2jijekunb.html

K. JSON 与序列化
来源：http://dali.shuidangran.top/Article/details/gt2hnlyhkws.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2ylhrqqhs.html

[K01] 对象转 JSON 字符串
来源：http://dali.c1oappe.top/Article/details/gt2gfqtwdel.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gt2eufbyekm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gt2ycyteazl.html

JS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2qhioktcn.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2jodykrgj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guowangkeji.top/Article/details/gt2ddlvqlkq.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lafzbhos.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gt2vdrbersx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2btgvmsit.html

[K02] JSON 字符串转对象
来源：http://dali.haohaochexian.top/Article/details/gt2ludnzbbh.html

Py:   json.loads(s)
来源：http://dali.yangfankeji.com/Article/details/gt2krtkhwjw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gt2mcmhxbgr.html

JS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gt2jncfebkn.html

TS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gt2fzsdyzwf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangdashe.top/Article/details/gt2bmtybjzy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gt2igcaohhy.html

Ruby: JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gt2ysdhcdjr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yongpay.top/Article/details/gt2ejwnnrha.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zzpngefq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gt2ziqogtyj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gt2bkmzquob.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2wjydgofo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2sqvgquhc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuxming.cn/Article/details/gt2rdffuoan.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258888.top/Article/details/gt2xiixvxyx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2pwmaahgm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258.top/Article/details/gt2leojcuzq.html

[K04] 读取 JSON 文件
来源：http://dali.tanke756.top/Article/details/gt2wonvcpzq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gogol.net.cn/Article/details/gt2smfwawpv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dashuyun.cn/Article/details/gt2rmvlvmjr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gt2skvtwymd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gt2kwfwdnfg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cucudq.cn/Article/details/gt2xuhlezya.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtyypttv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gt2ewozuuvc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daxiang520.top/Article/details/gt2jghukial.html

[K05] 深拷贝对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sadnrrjd.html

Py:   copy.deepcopy(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2zgocqkvf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gotoacloud.top/Article/details/gt2gyrvtkds.html

JS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2ptdebxvs.html

TS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2cwzdibtj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fengsongda.top/Article/details/gt2mgczthoh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.vqdsnc.cn/Article/details/gt2apdhnpts.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hywenlv.cn/Article/details/gt2jbfwhuks.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gt2cnhoddfz.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gt2myusrykx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gt2tvvnfeaa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.iojbl.cn/Article/details/gt2wvoqwqul.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gt2ynqvfirk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gt2kuoswaub.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gt2oujvqlep.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gt2llmgzhgb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pftfbcel.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnkahii.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gt2itxeefmm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2lpyswghn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shuidangran.top/Article/details/gt2ypdetqvd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gt2almckknt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2vhlcgrjq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2amnruelw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dianchejie.cn/Article/details/gt2efsooigm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xinyue.icu/Article/details/gt2iqmxhngl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2aafhklac.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.kuanghao11.cn/Article/details/gt2flyhsgkp.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2mhjybybh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xylfe.cn/Article/details/gt2wfmsgico.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gt2vvggqakr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gt2ovnwuvcu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.havefunace.top/Article/details/gt2ehbygqmq.html

Go:   encoding/gob
来源：http://dali.jyoumei.cn/Article/details/gt2nekwgmsl.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gt2shgpptgk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zgorzvfv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2abxwdkaj.html

L. 网络请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ccerrkpz.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2mdpymvxt.html

[L01] 发送 GET 请求
来源：http://dali.ydzc1.top/Article/details/gt2vfotbufb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jiagoushi.top/Article/details/gt2lnrzotuq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ptooryuh.html

JS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gt2cmnaocik.html

TS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gt2wfznibkf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aizwys.cn/Article/details/gt2lgpqleqf.html

Go:   resp, err := http.Get(url)
来源：http://dali.316326.xyz/Article/details/gt2irkfbrvy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cashguo.top/Article/details/gt2hkajekpt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gt2abkanguq.html

[L02] 发送 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gt2bvhumzhy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daria6918.cn/Article/details/gt2rqsaaxfl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guannengcc.top/Article/details/gt2ziplfell.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gt2hqhboadv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gt2nrpwewtt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tian-w.cn/Article/details/gt2buvkllss.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.meibo888.top/Article/details/gt2wrvbhlmz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuanzhike.top/Article/details/gt2sejwfgjf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ydzc1.top/Article/details/gt2ijtrtypr.html

[L03] 设置自定义请求头
来源：http://dali.shangyingyoupin.top/Article/details/gt2tappxiga.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hywenlv.cn/Article/details/gt2ebugfkvp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jyoumei.cn/Article/details/gt2qdnmouvj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gt2rqurosts.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gt2wxskmoll.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.vqdsnc.cn/Article/details/gt2fzqcudak.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gt2mrqkbrpj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj202588.top/Article/details/gt2xkatelee.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gt2fffpuvrv.html

[L04] 设置超时
来源：http://dali.9152youxi.cn/Article/details/gt2potmlcni.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xziqi.cn/Article/details/gt2hphqrvyi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sysykeji.top/Article/details/gt2xnrabmff.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gt2rxeayiko.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gt2spxztfgg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cdektrvo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.mhx1999.top/Article/details/gt2wzlefhrf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gotoacloud.top/Article/details/gt2hrwiuvzj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gt2saxknvwq.html

[L05] 上传文件（multipart）
来源：http://dali.snrcjt.cn/Article/details/gt2fklnwfuc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gkbhjpel.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.redwolf501.top/Article/details/gt2ncxnyntz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gt2gjqcelrq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gt2yxqrblhj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cheryme.top/Article/details/gt2dxodokyy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2kzvkrfcd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shzxlz.cn/Article/details/gt2cghxskmm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2uowmtfmo.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dumtunxy.html

Py:   resp.json()
来源：http://dali.zhengqikj.top/Article/details/gt2reahvhtw.html

PHP:  json_decode($body, true);
来源：http://dali.zhixingplan.top/Article/details/gt2dctwtlne.html

JS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gt2vdivtmgf.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gt2vhynowel.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gt2sdsbzezq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cucudq.cn/Article/details/gt2rvpnnvry.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gzhubu.top/Article/details/gt2dbcylqwg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangdashe.top/Article/details/gt2sytpwiok.html

[L07] 处理 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dnjlksfn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sysykeji.top/Article/details/gt2lgkmjthu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.snrcjt.cn/Article/details/gt2aptxujxj.html

JS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gt2cczucmyl.html

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gt2ohcvjbqm.html

Java: resp.statusCode()
来源：http://dali.iojbl.cn/Article/details/gt2setftoxf.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gt2zdqeeuwm.html

Ruby: resp.code.to_i
来源：http://dali.vqdsnc.cn/Article/details/gt2rihbqyen.html

C#:   (int)resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gt2lytpaobx.html

[L08] 并发请求多个地址
来源：http://dali.zhengqikj.top/Article/details/gt2jyzcztvq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenjidiqi.icu/Article/details/gt2vfxteggm.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gt2rohkysfq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gt2xutqqnyb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gt2fgdsqckl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ehwqpu.com/Article/details/gt2rgxwhrox.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hywenlv.cn/Article/details/gt2mspjyaga.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.svipenyu.cn/Article/details/gt2lhvcdgtr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.redwolf501.top/Article/details/gt2qzohiqkh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ckwyymcg.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gt2tojwayby.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2gmzkpdhe.html

[M01] 读取命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntjcjiwp.html

Py:   sys.argv[1:]
来源：http://dali.bjfxy.top/Article/details/gt2gnfepcoy.html

PHP:  $argv;  $argc;
来源：http://dali.andypj.xyz/Article/details/gt2gazjjpaf.html

JS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gt2ufmnvgdk.html

TS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gt2lnzhcoyi.html

Java: args 数组（main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ayqauqrl.html

Go:   os.Args[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2drrfrbyw.html

Ruby: ARGV
来源：http://dali.dashuyun.cn/Article/details/gt2pooubzju.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gt2znhrtnyy.html

[M02] 读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gt2ntkldwgw.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2exjscvqi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gt2vrqltvrm.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2emkbcvdn.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gt2fsdlgxdz.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2gzopudvs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258888.top/Article/details/gt2jkqyihxz.html

Ruby: ENV["HOME"]
来源：http://dali.yueranfly.top/Article/details/gt2yxbtztzr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2orwhcely.html

[M03] 执行外部命令
来源：http://dali.aibaodan.cn/Article/details/gt2afxgpivp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhixingplan.top/Article/details/gt2iibuxrjr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gaohongyu789.top/Article/details/gt2mvbsbjtf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gt2veceuafa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gt2cqjlrmwu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gt2wlnttnxl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xziqi.cn/Article/details/gt2gciwaunw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guannengcc.top/Article/details/gt2yysaktvk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guowangkeji.top/Article/details/gt2hunwnhvp.html

[M04] 获取当前工作目录
来源：http://dali.zhongyouzk.top/Article/details/gt2fseahaph.html

Py:   os.getcwd()
来源：http://dali.yuanzhike.top/Article/details/gt2ntanmfcy.html

PHP:  getcwd();
来源：http://dali.dianchejie.cn/Article/details/gt2andxttot.html

JS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gt2swkyhvyd.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gt2smpxueji.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sweek.top/Article/details/gt2hiagafrk.html

Go:   os.Getwd()
来源：http://dali.ivvv.top/Article/details/gt2ikdckvla.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gt2rrwpjvke.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cucudq.cn/Article/details/gt2kufajttp.html

[M05] 设置退出码
来源：http://dali.316326.xyz/Article/details/gt2ksktdfdk.html

Py:   sys.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xwhetzsj.html

PHP:  exit(1);
来源：http://dali.haohaochexian.top/Article/details/gt2yjzdvaac.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ugwhpwhs.html

TS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2qdzxspib.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2ksbehffm.html

Go:   os.Exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2fczspmkx.html

Ruby: exit 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzlprvwj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dianchejie.cn/Article/details/gt2empydqbw.html

[M06] 向标准错误输出
来源：http://dali.xuetiantiany.cn/Article/details/gt2dacafaot.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gt2gqqiaqkh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.9152youxi.cn/Article/details/gt2gcfdpcjt.html

JS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gt2fczydovb.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2szrldtkg.html

Java: System.err.println("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2cmcvsbon.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuanzx.com/Article/details/gt2limvoheg.html

Ruby: warn "err"
来源：http://dali.fzhhl.top/Article/details/gt2nkgcqehz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2jydhnopt.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gt2sjvddrka.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gt2abqhawil.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xziqi.cn/Article/details/gt2ejnfkdrb.html

JS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gt2dcgvpoyl.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gt2rqbiqijd.html

Java: public static void main(String[] args)
来源：http://dali.andypj.xyz/Article/details/gt2wbpwlewe.html

Go:   func main()
来源：http://dali.yuanzhike.top/Article/details/gt2evdgeuly.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gogol.net.cn/Article/details/gt2rmqpqwno.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gt2lzifozio.html

[M08] 获取系统与运行时信息
来源：http://dali.xinyue.icu/Article/details/gt2uhaorxru.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gt2dbjgqzec.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhixingplan.top/Article/details/gt2dryqvrjm.html

JS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gt2eoczvsaj.html

TS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gt2etmvnuyt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tutmntoj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yanxiufei.cn/Article/details/gt2rsexwbsp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yvedp.cn/Article/details/gt2huxwrjss.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aizwys.cn/Article/details/gt2cmblmrfq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2jyyiwpfv.html

N. 数据结构与算法
来源：http://dali.aizwys.cn/Article/details/gt2epuphsvy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2idtfpmgh.html

[N01] 二分查找（有序数组）
来源：http://dali.cucudq.cn/Article/details/gt2ontlhoni.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2xqepqzlc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xinyue.icu/Article/details/gt2diyztums.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gt2onqstmtq.html


<!-- 参考信息 -->