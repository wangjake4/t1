代发 wailian999

Go:   time.Now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ghdtvtlz.html

Ruby: Time.now
来源：http://dali.aibaodan.cn/Article/details/gt2ahkudjlf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.316326.xyz/Article/details/gt2ifpifbdg.html

[J02] 格式化输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2prfgvuse.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gt2dtlqeoac.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gt2rluwbavv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gt2nugrrfsg.html

TS:   d.toISOString()
来源：http://dali.smart0.xyz/Article/details/gt2kvqhhsgn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daria6918.cn/Article/details/gt2zjpiugvk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuxming.cn/Article/details/gt2usnhsunr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gt2ailfntki.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shuidangran.top/Article/details/gt2pswhbspx.html

[J03] 字符串解析为日期
来源：http://dali.jinqigfzy.top/Article/details/gt2yvxtmjln.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guannengcc.top/Article/details/gt2soswollv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gt2bdoaciri.html

JS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2qecqntrk.html

TS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2vlxhykpo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2wifkunsb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qbuyspaw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2voctanoc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gt2trwnlfbu.html

[J04] 时间戳与日期互转
来源：http://dali.sxryk.cn/Article/details/gt2qbeuclac.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hywenlv.cn/Article/details/gt2chzzuyrs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.mhx1999.top/Article/details/gt2dnrhzvnd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gaohongyu789.top/Article/details/gt2frlmxeja.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2hdyrlepo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2hiqlravo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2cszidqre.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sshqsdzv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sysykeji.top/Article/details/gt2bltqaxze.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhoulong.xyz/Article/details/gt2qiioyyjz.html

Py:   now + timedelta(days=7)
来源：http://dali.tian-w.cn/Article/details/gt2fixnkdyd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.316326.xyz/Article/details/gt2oaemuvbf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gt2sjadrbyw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gt2qqwoespg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.316326.xyz/Article/details/gt2sderpmez.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xilaxajj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.birdmap.top/Article/details/gt2crimoprx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.havefunace.top/Article/details/gt2zopjtzqk.html

[J06] 计算两时间之差
来源：http://dali.redwolf501.top/Article/details/gt2ldemcszm.html

Py:   (end - start).total_seconds()
来源：http://dali.daxiang520.top/Article/details/gt2rclovrqb.html

PHP:  $end->diff($start)->days;
来源：http://dali.cdnleiting.top/Article/details/gt2nqvuuvpp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.havefunace.top/Article/details/gt2qfnzcolk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dashuyun.cn/Article/details/gt2ihtuqlmw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yangfankeji.com/Article/details/gt2tloyynvv.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhongyouzk.top/Article/details/gt2fyppeuga.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hysaishi.cn/Article/details/gt2fdtkxacy.html

C#:   (end - start).TotalSeconds
来源：http://dali.shangyingyoupin.top/Article/details/gt2pploibgf.html

[J07] 比较两个日期
来源：http://dali.jinqigfzy.top/Article/details/gt2sxatffpi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gt2vesybkkv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ivvv.top/Article/details/gt2ictucpan.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gt2saucidxt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gt2ncbipbir.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gt2gvqkmgyo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigfzy.top/Article/details/gt2llkogasp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gt2vhlisyyl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gt2gosqtxxi.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvdzsez.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guannengcc.top/Article/details/gt2jejoqgqs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxerqgfg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.havefunace.top/Article/details/gt2ovdfpxfr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yanxiufei.cn/Article/details/gt2zyieublb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxinkj.top/Article/details/gt2keqboubm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cdnleiting.top/Article/details/gt2tgqfcjtz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhoulong.xyz/Article/details/gt2btjafyvg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tian-w.cn/Article/details/gt2ycqllosh.html

[J09] 时区处理
来源：http://dali.hnxiangtu.top/Article/details/gt2dydxfare.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ydzc1.top/Article/details/gt2qfxkagdy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xvficjfs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2xezyukpg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gt2ppxgxbpo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gt2xdklrhov.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pycfn.com/Article/details/gt2thosftsc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.snrcjt.cn/Article/details/gt2lqzexggl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.havefunace.top/Article/details/gt2tlcwbfsi.html

[J10] 取今天 / 本月第一天
来源：http://dali.tian-w.cn/Article/details/gt2zrrqkifx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hammf.cn/Article/details/gt2jaycwmxk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ivvv.top/Article/details/gt2eqiofidh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cdnleiting.top/Article/details/gt2kjycaqyu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.meibo888.top/Article/details/gt2zharwvzg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guowangkeji.top/Article/details/gt2fnonykdf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigufen.top/Article/details/gt2nqwwcypm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jyoumei.cn/Article/details/gt2hrjezvsg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gt2exsjxtjb.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dtducyyz.html

K. JSON 与序列化
来源：http://dali.hnxiangtu.top/Article/details/gt2ywufdfrj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2scgdxgdg.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gt2qaxhgaah.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gt2snhbfmgq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gt2drsetezv.html

JS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zeuoittf.html

TS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2cjycuhhk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vmkxcuks.html

Go:   json.Marshal(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2qqzxzuwz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gt2qjwpmfho.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yvedp.cn/Article/details/gt2lhvxiomh.html

[K02] JSON 字符串转对象
来源：http://dali.tianlin.xyz/Article/details/gt2nugvkbcb.html

Py:   json.loads(s)
来源：http://dali.c1oappe.top/Article/details/gt2jzdhwsnd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gt2ceigxcyq.html

JS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gt2azflmjco.html

TS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gt2omvfskli.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gt2llpacbsy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gt2vmjmbvol.html

Ruby: JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gt2jalnxxho.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuxming.cn/Article/details/gt2vcuycaeg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gzhubu.top/Article/details/gt2ypzddisl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkoiziis.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gt2xkdflioa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2whhocvui.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gt2wrrwnlpf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfrmwats.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dashuyun.cn/Article/details/gt2wmryrsem.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuanzx.com/Article/details/gt2vmqhqpuh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuxming.cn/Article/details/gt2ifcelkhw.html

[K04] 读取 JSON 文件
来源：http://dali.ybcxt.top/Article/details/gt2hmlxbgov.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qingxbqz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tanke756.top/Article/details/gt2zgbvauhu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gt2ppvqcgwu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gt2hmnlrlzy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqghhner.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gt2ywiqyfof.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daxiang520.top/Article/details/gt2kwksstga.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ydzc1.top/Article/details/gt2hyebdeqf.html

[K05] 深拷贝对象
来源：http://dali.yanxiufei.cn/Article/details/gt2pdkiwzpg.html

Py:   copy.deepcopy(obj)
来源：http://dali.cashguo.top/Article/details/gt2stdebgsq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dashuyun.cn/Article/details/gt2bafnfwco.html

JS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2gfeomeez.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tewlphvk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cashguo.top/Article/details/gt2ybjuxxnx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ytjhslit.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.mhx1999.top/Article/details/gt2ptfbphth.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.kuanghao11.cn/Article/details/gt2brdvmvow.html

[K06] 解析 URL 查询串
来源：http://dali.chenlongwang.top/Article/details/gt2rkokkhrn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gt2qayqvrtz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sweek.top/Article/details/gt2nxuruetf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gt2vmxrouyj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jlgehiae.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zdqjudy.top/Article/details/gt2wixvficy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gt2blhuehec.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gt2xhuunuef.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2xegxsioq.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gt2oynhovxn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2luwggkoe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dashuyun.cn/Article/details/gt2crtbzpiw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2friuzzkt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2czuyafrk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2ygkhxkpn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gt2qnwuxvgv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnxiangtu.top/Article/details/gt2eynemknp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2gtyhanci.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnxiangtu.top/Article/details/gt2fcoxduge.html

Py:   pickle.dumps(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uslgsmnz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tanke756.top/Article/details/gt2kkcuwfzf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gt2ljbtpojb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gt2jkknfjok.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gt2opkuizwz.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gt2guzusoop.html

Ruby: Marshal.dump(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2nurpumaf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gt2scvkjtho.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2gcohfjod.html

L. 网络请求
来源：http://dali.fengsongda.top/Article/details/gt2tjrbxthr.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2agysjlbo.html

[L01] 发送 GET 请求
来源：http://dali.cdnleiting.top/Article/details/gt2klszebou.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigufen.top/Article/details/gt2tcgoiism.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hammf.cn/Article/details/gt2lbzksyay.html

JS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2oqkhgzxi.html

TS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gt2csramchv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qdzxyanx.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2amybwlpv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuanzx.com/Article/details/gt2vpllatyz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gogol.net.cn/Article/details/gt2iapozbws.html

[L02] 发送 POST JSON
来源：http://dali.c1oappe.top/Article/details/gt2pygvahlk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gt2leodgqsq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gt2ksdymqua.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gt2vdcznpnu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gt2bpaifqav.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aizwys.cn/Article/details/gt2yqyjfied.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shangyingyoupin.top/Article/details/gt2rorddbqv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.snrcjt.cn/Article/details/gt2oirlmdkm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dkqqkyuw.html

[L03] 设置自定义请求头
来源：http://dali.hnxiangtu.top/Article/details/gt2utcyfdjw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ydkicfuy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ivvv.top/Article/details/gt2vnykgsoz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gt2etoieunl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gt2oafvjmwc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjqxmysi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gt2ertvjdms.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnqzz.top/Article/details/gt2kdoiwlzg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gt2ayufuwvr.html

[L04] 设置超时
来源：http://dali.nanxinkj.top/Article/details/gt2soblivgx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.birdmap.top/Article/details/gt2pnomstrb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sxryk.cn/Article/details/gt2vtaluvgh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kofmlfac.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gt2wdabghdq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.316326.xyz/Article/details/gt2efkxprtx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gt2sayplbpq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2waxidraq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigufen.top/Article/details/gt2bsljujzc.html

[L05] 上传文件（multipart）
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnguhgbf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fengsongda.top/Article/details/gt2dlhlynzr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aibaodan.cn/Article/details/gt2bkhitkwq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gt2dscyxdtk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gt2gclfcrlf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258888.top/Article/details/gt2jtkrrcwc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tanke756.top/Article/details/gt2csadwrod.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.svipenyu.cn/Article/details/gt2btrrjzgg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gt2vudjdrzv.html

[L06] 解析响应为 JSON
来源：http://dali.c1oappe.top/Article/details/gt2ptpsgqhx.html

Py:   resp.json()
来源：http://dali.9152youxi.cn/Article/details/gt2trjwpnbv.html

PHP:  json_decode($body, true);
来源：http://dali.gzhubu.top/Article/details/gt2zneltsdw.html

JS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wikbyvtt.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gt2qwzlhgam.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gt2awrxymdd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gt2nkqqkvbh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gt2vrmjwtjn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gt2byefqxts.html

[L07] 处理 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gt2ufrvrvcx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hfpthk.cn/Article/details/gt2sdslrdqi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenlongwang.top/Article/details/gt2ulbuealt.html

JS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gt2idakikul.html

TS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ygobkjkv.html

Java: resp.statusCode()
来源：http://dali.sysykeji.top/Article/details/gt2jgqfqkft.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gt2ohjetlqa.html

Ruby: resp.code.to_i
来源：http://dali.fzhhl.top/Article/details/gt2edzynfwo.html

C#:   (int)resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gt2zoccrkic.html

[L08] 并发请求多个地址
来源：http://dali.pengpengdd.cyou/Article/details/gt2zfdcgflv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxinkj.top/Article/details/gt2jzurxvkr.html

PHP:  curl_multi_init() 系列
来源：http://dali.ehwqpu.com/Article/details/gt2lgmghfgi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gt2qgrjtosc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2irdenxyb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gt2wnpqoyzf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.andypj.xyz/Article/details/gt2ddedovjw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2gdgvehng.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.smart0.xyz/Article/details/gt2jcdnwdus.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2beqikitc.html

M. 命令行 / 进程 / 环境
来源：http://dali.jlsjyb.cn/Article/details/gt2obcpxpuf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ytpxmlbg.html

[M01] 读取命令行参数
来源：http://dali.meibo888.top/Article/details/gt2qnsaonpz.html

Py:   sys.argv[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2mnisldlr.html

PHP:  $argv;  $argc;
来源：http://dali.cdnleiting.top/Article/details/gt2lojlcslb.html

JS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gt2hfclsktz.html

TS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gt2cpyuambe.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gt2kmhxnfnk.html

Go:   os.Args[1:]
来源：http://dali.hywenlv.cn/Article/details/gt2arjslgrj.html

Ruby: ARGV
来源：http://dali.jinqigfzy.top/Article/details/gt2khhabuql.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2suwkdofi.html

[M02] 读取环境变量
来源：http://dali.yuanzhike.top/Article/details/gt2ympxnjhp.html

Py:   os.environ.get("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2rsvnzzlb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gt2vojsrabb.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gt2suyrebtj.html

TS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gt2ynvypztp.html

Java: System.getenv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gt2tmoiueji.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2yhvraybm.html

Ruby: ENV["HOME"]
来源：http://dali.chenlongwang.top/Article/details/gt2sqahsxqo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vsukuono.html

[M03] 执行外部命令
来源：http://dali.jyoumei.cn/Article/details/gt2jclcicyc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gt2qizbbzhh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gt2kxbfzkwp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gt2euvdykrj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gt2jwtkwmfm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigfzy.top/Article/details/gt2hcpdumsf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnqzz.top/Article/details/gt2nasnufdt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258888.top/Article/details/gt2qkvkdyje.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gt2resooftn.html

[M04] 获取当前工作目录
来源：http://dali.yj20258888.top/Article/details/gt2uagpwkbj.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gt2xpgachct.html

PHP:  getcwd();
来源：http://dali.xuanzx.com/Article/details/gt2xxfhihrh.html

JS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gt2eefrpbzc.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2eepnxhaa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhixingplan.top/Article/details/gt2tgssmkap.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gt2tkdevrcn.html

Ruby: Dir.pwd
来源：http://dali.aibaodan.cn/Article/details/gt2amqixbsz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.svipenyu.cn/Article/details/gt2gmfaascc.html

[M05] 设置退出码
来源：http://dali.hammf.cn/Article/details/gt2echbanck.html

Py:   sys.exit(1)
来源：http://dali.tanke756.top/Article/details/gt2vjbxgumi.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gt2himqzbmm.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2axarqsjr.html

TS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2whplwjuv.html

Java: System.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2texlcubc.html

Go:   os.Exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2qdkvutsg.html

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gt2crivecri.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.snrcjt.cn/Article/details/gt2qunpqzps.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gt2trbaxlja.html

Py:   print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gt2jhcyqmyo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxinkj.top/Article/details/gt2kuvqjbuj.html

JS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gt2siccgmgq.html

TS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gt2nslshffm.html

Java: System.err.println("err")
来源：http://dali.jqgfzy.top/Article/details/gt2xooqxurj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenzaomai.com/Article/details/gt2bqeqprqh.html

Ruby: warn "err"
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdmwghwl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gt2ynhhgydl.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gt2iwqazkzu.html

Py:   if __name__ == "__main__":
来源：http://dali.c1oappe.top/Article/details/gt2ifbwavxs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zycfv.cn/Article/details/gt2igpuziig.html

JS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gt2edbkabcg.html

TS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gt2ztutmras.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gt2hupgqtgc.html

Go:   func main()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nvavultt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gt2tyauafwr.html

C#:   static void Main(string[] args)
来源：http://dali.jlsjyb.cn/Article/details/gt2gifzlhwr.html


<!-- 参考信息 -->