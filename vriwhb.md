代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnxiangtu.top/Article/details/gt2hiofhmzu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.meibo888.top/Article/details/gt2jgjxttvi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gt2gufpwqfo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2pubmqtuy.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gt2ngonrnla.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenlongwang.top/Article/details/gt2lfaljsfr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jlsjyb.cn/Article/details/gt2axqezkql.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2qssyclac.html

TS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2ugtynzdm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2ocsdjndl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2mkphxgbi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2vfraifxk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tanke756.top/Article/details/gt2ebbzmqxb.html

[J04] 时间戳与日期互转
来源：http://dali.haohaochexian.top/Article/details/gt2jxskojiv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pcvfyzlw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bgctvizm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxuanxn.top/Article/details/gt2hzsjsuhn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.0kj1m.cn/Article/details/gt2lxogcbee.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.meibo888.top/Article/details/gt2doezqabf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuanzx.com/Article/details/gt2lvpwqiry.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daria6918.cn/Article/details/gt2cxuhaszd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xinyue.icu/Article/details/gt2tlovsqyu.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gt2kzeqmdtf.html

Py:   now + timedelta(days=7)
来源：http://dali.hnxiangtu.top/Article/details/gt2cisfmhow.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zycfv.cn/Article/details/gt2ajxngiac.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gt2qjtixzpv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wbomerhw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yueranfly.top/Article/details/gt2saaftnmi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nwbrower.top/Article/details/gt2oipurian.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhixingplan.top/Article/details/gt2bgcubzyx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yangfankeji.com/Article/details/gt2gpsgbskc.html

[J06] 计算两时间之差
来源：http://dali.c1oappe.top/Article/details/gt2iuezllbs.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gt2uzxmurjr.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gt2fjkeenmz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hongshengwenyu.top/Article/details/gt2drqlnyhq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cdnleiting.top/Article/details/gt2qbzvljzt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenjidiqi.icu/Article/details/gt2jmcjaqky.html

Go:   end.Sub(start).Hours()
来源：http://dali.yanxiufei.cn/Article/details/gt2wmtkvkut.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guowangkeji.top/Article/details/gt2vgiobdht.html

C#:   (end - start).TotalSeconds
来源：http://dali.feifeiyinyue.top/Article/details/gt2oddairas.html

[J07] 比较两个日期
来源：http://dali.shangyingyoupin.top/Article/details/gt2pcrrjvhm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gt2yflvswml.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ozvdnpbv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gt2nxwmivjc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gt2zyzmnuqz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cucudq.cn/Article/details/gt2hdpxjvqr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.birdmap.top/Article/details/gt2zwuacxls.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2cycgdxcf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2dagtmfty.html

[J08] 提取年月日与星期
来源：http://dali.hywenlv.cn/Article/details/gt2vzxuyddi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shzxlz.cn/Article/details/gt2fzfecqfz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jiagoushi.top/Article/details/gt2csygvncq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jyoumei.cn/Article/details/gt2zrwrwupd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gt2zxrecrxe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xinyue.icu/Article/details/gt2metrxveu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dashuyun.cn/Article/details/gt2bipuglsz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xylfe.cn/Article/details/gt2ewtldnnu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.havefunace.top/Article/details/gt2mfgumoed.html

[J09] 时区处理
来源：http://dali.tanke756.top/Article/details/gt2irvaeylz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gt2fdhggjyn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jiagoushi.top/Article/details/gt2lsoagtfq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gt2watlyxwl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gt2rwpxmylo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.kuanghao11.cn/Article/details/gt2fgesnadb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xziqi.cn/Article/details/gt2pdqkqvvx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zdqjudy.top/Article/details/gt2plataxnv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbskyhno.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgufenzy.top/Article/details/gt2icmmdbgd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gt2xyrmkpqt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xziqi.cn/Article/details/gt2dzvsjbre.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dianchejie.cn/Article/details/gt2mzieoufp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.mhx1999.top/Article/details/gt2rdonbmsc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258.top/Article/details/gt2trrspaaz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxinkj.top/Article/details/gt2jfwrgrbw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aizwys.cn/Article/details/gt2zakwsabx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jyoumei.cn/Article/details/gt2tthanzco.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2fjsilvsq.html

K. JSON 与序列化
来源：http://dali.wangshuangyany.cn/Article/details/gt2huakzzre.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2qbwjrlsv.html

[K01] 对象转 JSON 字符串
来源：http://dali.yangfankeji.com/Article/details/gt2ynyorexg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gt2hpkblwyj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2plkivpjp.html

JS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2xsfppfqx.html

TS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gt2urmtzpyn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gt2phqfnybo.html

Go:   json.Marshal(obj)
来源：http://dali.havefunace.top/Article/details/gt2ofyqlavi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgufenzy.top/Article/details/gt2xenujpzr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yonumen.top/Article/details/gt2vttubbor.html

[K02] JSON 字符串转对象
来源：http://dali.tanke756.top/Article/details/gt2ccfmoppg.html

Py:   json.loads(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2plmymiqw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2xkfyjahk.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2sylhrhyg.html

TS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gt2arypbfeh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgfzy.top/Article/details/gt2ddnivnry.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gt2kbtlgfna.html

Ruby: JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gt2ptxvfdiy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hywenlv.cn/Article/details/gt2lebdxxia.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guannengcc.top/Article/details/gt2ggaahaum.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ldluriut.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gt2vqffzlrm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qyrvitng.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gt2xziidqbl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xziqi.cn/Article/details/gt2nuewwmei.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.iojbl.cn/Article/details/gt2cwyfuoib.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangdashe.top/Article/details/gt2irmshxae.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gt2zkfgkuuh.html

[K04] 读取 JSON 文件
来源：http://dali.zhongyouzk.top/Article/details/gt2yogpkrvc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnxiangtu.top/Article/details/gt2qtuaqanw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzwwfran.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gt2pghuqmvk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2gikmwhvc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gt2zihlpmum.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gt2ipdgymwc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gt2qbsqmkka.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yongpay.top/Article/details/gt2qjjajsrk.html

[K05] 深拷贝对象
来源：http://dali.ehwqpu.com/Article/details/gt2ckatjljc.html

Py:   copy.deepcopy(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2epmfdccw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gogol.net.cn/Article/details/gt2mohneauu.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2ivliqile.html

TS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2rmihxkhm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhiwuduotai.top/Article/details/gt2vsbicphu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuanzhike.top/Article/details/gt2avwnrrry.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ydzc1.top/Article/details/gt2wwbvcgnu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.feifeiyinyue.top/Article/details/gt2lhkdsqxy.html

[K06] 解析 URL 查询串
来源：http://dali.hywenlv.cn/Article/details/gt2gquunrnp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gt2kgznqpii.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhoulong.xyz/Article/details/gt2kqvujlec.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gt2iptgrpia.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gt2zxvegwth.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.quarkkingdee.top/Article/details/gt2rgexcezj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gt2fbwamxip.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2amkrdrtg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vopadcru.html

[K07] 进制转换
来源：http://dali.guannengcc.top/Article/details/gt2biffhimk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2kukptdge.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cheryme.top/Article/details/gt2nonhjiqp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2bqvklyec.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2glikupya.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2belhcddt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gt2dmtueeni.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xziqi.cn/Article/details/gt2kuudrjys.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2nkdufkhx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aizwys.cn/Article/details/gt2njzwszyc.html

Py:   pickle.dumps(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2fmqatmgi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dashuyun.cn/Article/details/gt2feazlqob.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2forgdhhz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gt2ssieiopd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.birdmap.top/Article/details/gt2urwdnbse.html

Go:   encoding/gob
来源：http://dali.jyoumei.cn/Article/details/gt2uawunqjp.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mnytjzrs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gt2vtxkyswv.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2qgxdfgtv.html

L. 网络请求
来源：http://dali.jqgfzy.top/Article/details/gt2wrgkzckl.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2kgyhlada.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gt2dwgjlbrr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gogol.net.cn/Article/details/gt2kgcodeex.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.bjfxy.top/Article/details/gt2ofalxwio.html

JS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gt2lwgeoyvn.html

TS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2altvzefp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hywenlv.cn/Article/details/gt2aydgvufj.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gt2zqmhshlh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258888.top/Article/details/gt2cfrcohme.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zqlfbarp.html

[L02] 发送 POST JSON
来源：http://dali.redwolf501.top/Article/details/gt2xducqmxu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.andypj.xyz/Article/details/gt2trvstsbf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hysaishi.cn/Article/details/gt2voalihtv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gt2ojvlzkjg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gt2ddvawumo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2erislxeq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ivvv.top/Article/details/gt2dcfpviin.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lbnnscug.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.svipenyu.cn/Article/details/gt2jcibhbur.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gt2wahufoia.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fengsongda.top/Article/details/gt2iualmlti.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzssxfb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gt2uvtwclde.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gt2dxrawlro.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgufenzy.top/Article/details/gt2tnfrtqai.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pdhonjrt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigufen.top/Article/details/gt2trmrsrdt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gt2nqbynrcs.html

[L04] 设置超时
来源：http://dali.hywenlv.cn/Article/details/gt2ppaqilny.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yangfankeji.com/Article/details/gt2xzhvuzet.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258.top/Article/details/gt2pinvawfo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tkjazwpx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gt2twozqcak.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ilbxhulw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ajtgkdbu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hywenlv.cn/Article/details/gt2auzbbqfm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.quarkkingdee.top/Article/details/gt2urhjbyma.html

[L05] 上传文件（multipart）
来源：http://dali.xuanzx.com/Article/details/gt2dzyggxjb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tanke756.top/Article/details/gt2afilbyqu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gt2bdrwgatk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gt2ehcxuwrq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gt2zqghypuc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gaohongyu789.top/Article/details/gt2yhtngurk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2gvcbpgsn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tanke756.top/Article/details/gt2xxumxvsb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2qbsyocgx.html

[L06] 解析响应为 JSON
来源：http://dali.sweek.top/Article/details/gt2lnrcapbo.html

Py:   resp.json()
来源：http://dali.svipenyu.cn/Article/details/gt2ltzcjedf.html

PHP:  json_decode($body, true);
来源：http://dali.fengsongda.top/Article/details/gt2eyzhltyw.html

JS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2feedzuab.html

TS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gt2carrsdcz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gt2fnnpbgje.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gt2xuxcfxio.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gt2vyqcrfcz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.quarkkingdee.top/Article/details/gt2goauyggq.html

[L07] 处理 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gt2jayyvfdj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ccghhjru.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrexseqw.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gt2fjjwefrz.html

TS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gt2pugkgrwj.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gt2jaftypco.html

Go:   resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gt2emetvols.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gt2sroxzxac.html

C#:   (int)resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gt2bqmfvvge.html

[L08] 并发请求多个地址
来源：http://dali.wangshuangyany.cn/Article/details/gt2lufujell.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.9152youxi.cn/Article/details/gt2fbarvclj.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gt2wlboilsv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eesgxcdc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gt2lgafyopw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yangfankeji.com/Article/details/gt2bjzlukpx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cucudq.cn/Article/details/gt2ekjlajhw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zdqjudy.top/Article/details/gt2nufrwgyk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.haohaochexian.top/Article/details/gt2lnnippjo.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2quadshla.html

M. 命令行 / 进程 / 环境
来源：http://dali.yvedp.cn/Article/details/gt2awnlzvcx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2wjadbdlw.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gt2xtucnkqu.html

Py:   sys.argv[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2dtehvixs.html

PHP:  $argv;  $argc;
来源：http://dali.jianghu66.top/Article/details/gt2qlsbxwbs.html

JS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gt2pxryvcsc.html

TS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gt2vrcebyev.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gt2riswermt.html

Go:   os.Args[1:]
来源：http://dali.ydzc1.top/Article/details/gt2oflrbwgr.html

Ruby: ARGV
来源：http://dali.xuetiantiany.cn/Article/details/gt2rvmgnhlb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gt2agewoqss.html

[M02] 读取环境变量
来源：http://dali.jqgufenzy.top/Article/details/gt2uvzbhofy.html

Py:   os.environ.get("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ykjhfxdz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gt2wsqpqcwl.html

JS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gt2xvghrley.html

TS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gt2lepsvhml.html

Java: System.getenv("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2numhydxr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gt2ygshriyt.html

Ruby: ENV["HOME"]
来源：http://dali.zhongyouzk.top/Article/details/gt2gsgmoqxf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ashofdob.html

[M03] 执行外部命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cltkexew.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shuidangran.top/Article/details/gt2gvpnlohz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gt2hymeanwj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gt2uktppuhb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gt2dtxlufwm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gt2mhyhzmle.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.smart0.xyz/Article/details/gt2xyydgmbq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hysaishi.cn/Article/details/gt2zplnouvi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sufxvd.cn/Article/details/gt2jcipmwsk.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gt2iiyzsfsp.html

Py:   os.getcwd()
来源：http://dali.yuxming.cn/Article/details/gt2ilqehkmy.html

PHP:  getcwd();
来源：http://dali.fzhhl.top/Article/details/gt2ngktyphg.html

JS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gt2hdsqevqu.html

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gt2kewogjyj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ymeenwct.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gt2ohghfjsi.html

Ruby: Dir.pwd
来源：http://dali.yongpay.top/Article/details/gt2rjgesgvw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.meibo888.top/Article/details/gt2blicgaej.html

[M05] 设置退出码
来源：http://dali.dianchejie.cn/Article/details/gt2eriinoxo.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkenscka.html

PHP:  exit(1);
来源：http://dali.hammf.cn/Article/details/gt2yjlqlftq.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2dnkgbveq.html

TS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gt2laeukyrf.html

Java: System.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2adgsfziw.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2lqetquyc.html

Ruby: exit 1
来源：http://dali.tian-w.cn/Article/details/gt2iddpvkuv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gt2xtwuzqds.html

[M06] 向标准错误输出
来源：http://dali.aibaodan.cn/Article/details/gt2npobnkkw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gt2gqryvzxh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gt2kbvnodgp.html

JS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gt2kmvvbffe.html

TS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2flpqzldd.html

Java: System.err.println("err")
来源：http://dali.zhixingplan.top/Article/details/gt2jqvcnjzj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ckdxfroj.html

Ruby: warn "err"
来源：http://dali.jinqigfzy.top/Article/details/gt2vcchlmyt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2frdrcyzu.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cczcpgel.html

Py:   if __name__ == "__main__":
来源：http://dali.guannengcc.top/Article/details/gt2umtwlygv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gotoacloud.top/Article/details/gt2xrvkjhcf.html

JS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gt2etbihrxx.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gt2cmlzmkcb.html

Java: public static void main(String[] args)
来源：http://dali.haohaochexian.top/Article/details/gt2qdkpdksp.html

Go:   func main()
来源：http://dali.pycfn.com/Article/details/gt2oszflypg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yvjyzudr.html

C#:   static void Main(string[] args)
来源：http://dali.yuanzhike.top/Article/details/gt2pnyxdqhv.html

[M08] 获取系统与运行时信息
来源：http://dali.svipenyu.cn/Article/details/gt2gscnzthi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cdnleiting.top/Article/details/gt2nfkjrdbw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gt2ycankbuh.html

JS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gt2xakckocv.html

TS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gt2yxkxuqev.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gt2urgxnrhr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gogol.net.cn/Article/details/gt2lctdhcmz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hewwbbie.html


<!-- 参考信息 -->