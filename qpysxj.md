代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynweuerc.html

JS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtbhzhyklz.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtxwbggycl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cheryme.top/Article/details/gtygyyduku.html

Go:   time.Now()
来源：http://dali.sufxvd.cn/Article/details/gtjmvbmdbv.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gthmiupdav.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hywenlv.cn/Article/details/gtlrwbtkxr.html

[J02] 格式化输出
来源：http://dali.yueranfly.top/Article/details/gtpswnngdp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gtijfvvcni.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gtdwualhyl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shuidangran.top/Article/details/gtmhfpodhu.html

TS:   d.toISOString()
来源：http://dali.yonumen.top/Article/details/gtzswsbvwz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shuidangran.top/Article/details/gtkiiovgfn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnqzz.top/Article/details/gtnbtmeyoa.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gtypyycgne.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pengpengdd.cyou/Article/details/gtxjpylxvx.html

[J03] 字符串解析为日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsfwwgvz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenzaomai.com/Article/details/gttnocywpa.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ppjwa.cn/Article/details/gtluicmhru.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtpulmmazf.html

TS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gthzytfshm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtainvzdse.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtkhvoxtmd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtilwcnjmg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigfzy.top/Article/details/gtosotfdvu.html

[J04] 时间戳与日期互转
来源：http://dali.jlsjyb.cn/Article/details/gtsjnektwv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtqnyawglu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fzhhl.top/Article/details/gtxgrgwpvf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxinkj.top/Article/details/gtbjyfqjjp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cqqwz.cn/Article/details/gtoppkozon.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cashguo.top/Article/details/gtzlartuzj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtxrytqnfc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ehwqpu.com/Article/details/gtcnqisufn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangdashe.top/Article/details/gtdpcurbrk.html

[J05] 时间加减（加 7 天）
来源：http://dali.ehwqpu.com/Article/details/gtglgmzrdn.html

Py:   now + timedelta(days=7)
来源：http://dali.shuidangran.top/Article/details/gtkxssdusc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhengqikj.top/Article/details/gtqnbcjjpm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gthkhvnzrm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtapcvypmm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtzefgdnse.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.andypj.xyz/Article/details/gtrxlgczkg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jyoumei.cn/Article/details/gtokopeiti.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdactuwd.html

[J06] 计算两时间之差
来源：http://dali.tian-w.cn/Article/details/gtfveuqknb.html

Py:   (end - start).total_seconds()
来源：http://dali.316326.xyz/Article/details/gtixfycekr.html

PHP:  $end->diff($start)->days;
来源：http://dali.dianchejie.cn/Article/details/gtktueovpv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gtiuuldkkp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tianlin.xyz/Article/details/gtbhhbclgz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuanzhike.top/Article/details/gtjluxuhad.html

Go:   end.Sub(start).Hours()
来源：http://dali.c1oappe.top/Article/details/gtmptzfhbv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shangyingyoupin.top/Article/details/gtriaejzep.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gtyfhihurp.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gtisccrgdl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtimerwshh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yueranfly.top/Article/details/gtfafijdpc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gtilezhzsx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gtmdjuuhhi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gtuqbtcujs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cucudq.cn/Article/details/gtrwksmrim.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtotoklbyb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtffvfypmk.html

[J08] 提取年月日与星期
来源：http://dali.yanxiufei.cn/Article/details/gtvfgwehnf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgufenzy.top/Article/details/gtxnxcqdta.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gtmtmrerme.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gtudttpbjx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gtqppwjnbz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ybcxt.top/Article/details/gtvpzrqyyt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hfpthk.cn/Article/details/gtezazfsxb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gtfrwofmrv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pengpengdd.cyou/Article/details/gtntqqwfti.html

[J09] 时区处理
来源：http://dali.hnqzz.top/Article/details/gtkzsjaxws.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yonumen.top/Article/details/gtjwnsynez.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhongyouzk.top/Article/details/gtrhtmirwy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gtdixunani.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gtldnnjyxp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gtzupsmljn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gaohongyu789.top/Article/details/gtnrugigzu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yueranfly.top/Article/details/gtrtqrbuik.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.svipenyu.cn/Article/details/gtfdbvopet.html

[J10] 取今天 / 本月第一天
来源：http://dali.snrcjt.cn/Article/details/gtjtrgtioa.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gtwnssxhqx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hysaishi.cn/Article/details/gtchvhdglk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ppjwa.cn/Article/details/gtjbkrlczo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ivvv.top/Article/details/gtsvncbtqc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gtmftztect.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gtyfzjtwhf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhoulong.xyz/Article/details/gtscvqcgsa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtbstsnzky.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtnoluvaxq.html

K. JSON 与序列化
来源：http://dali.zycfv.cn/Article/details/gtwlmgaqkc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtzpumcowg.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gtcdmhilff.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdgaycbu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtyilbztpn.html

JS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtgkmhnnvc.html

TS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gthsoiamlv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.mhx1999.top/Article/details/gtucoqznfz.html

Go:   json.Marshal(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtkumkiutm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cqqwz.cn/Article/details/gteqfbvbna.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gttjhqztyx.html

[K02] JSON 字符串转对象
来源：http://dali.gogol.net.cn/Article/details/gtjftkgltz.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gtaacfxlbf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guannengcc.top/Article/details/gtmfiowwej.html

JS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtiicvqvfi.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtufcdrraf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtufcreohq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gtngipqusp.html

Ruby: JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtdumyyjjt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.mhx1999.top/Article/details/gtepsprkey.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.iojbl.cn/Article/details/gtqruvwbiy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gtngfgrdba.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtehebuhmd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtryhbjfwp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtxoxtcjoh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtunomeewc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.kuanghao11.cn/Article/details/gtcifefpao.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gtjlkbvzwy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sufxvd.cn/Article/details/gtsdkyftzi.html

[K04] 读取 JSON 文件
来源：http://dali.sufxvd.cn/Article/details/gtzvgoejsz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zycfv.cn/Article/details/gtkdsgzaio.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.smart0.xyz/Article/details/gtszijgmcs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gtxalhllvh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtusaewksw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tanke756.top/Article/details/gtctsimolb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtoaxvdauw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daxiang520.top/Article/details/gtykqlkflm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shuidangran.top/Article/details/gtqvvsnnjw.html

[K05] 深拷贝对象
来源：http://dali.jinqigfzy.top/Article/details/gtruhmvajs.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gtbcccrctp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xinyue.icu/Article/details/gtfiqnxvap.html

JS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtvqrxupjd.html

TS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtzsjqmaem.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgfzy.top/Article/details/gtbyjmhmdh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daria6918.cn/Article/details/gtnrlbdiir.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shangyingyoupin.top/Article/details/gtvurwfknj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nwbrower.top/Article/details/gtpjstgezy.html

[K06] 解析 URL 查询串
来源：http://dali.havefunace.top/Article/details/gtsfrnwkyy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtklgnnbsu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sweek.top/Article/details/gtqniyulgj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gtfcpbaczm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gtsgguklev.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangdashe.top/Article/details/gteqhszmfy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtmtvmpeyn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtgdhcanje.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtihushvau.html

[K07] 进制转换
来源：http://dali.zhixingplan.top/Article/details/gtggemljln.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gttcixmfvd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenjidiqi.icu/Article/details/gtoioxbhts.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtikutjhop.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtaoeslppa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtmeosguyy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jiagoushi.top/Article/details/gtkbsjkcaa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jiagoushi.top/Article/details/gtifmuddnp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtqtxobkpx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.redwolf501.top/Article/details/gtdbdiwpju.html

Py:   pickle.dumps(obj)
来源：http://dali.andypj.xyz/Article/details/gtnxcnwavi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gtvjpyzdum.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfhngkbx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gtrwubznlp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.kuanghao11.cn/Article/details/gtknucofnj.html

Go:   encoding/gob
来源：http://dali.0kj1m.cn/Article/details/gtjqotolqk.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gtuhokrmoe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtjozldali.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtmbpfddrm.html

L. 网络请求
来源：http://dali.yangfankeji.com/Article/details/gtdbhlzjiy.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtlcjbjfxy.html

[L01] 发送 GET 请求
来源：http://dali.dashuyun.cn/Article/details/gtyvhbbapm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gtzesziwgc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gtvrvbystf.html

JS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gttwszlzls.html

TS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtreizvyns.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgfzy.top/Article/details/gtatavhhtq.html

Go:   resp, err := http.Get(url)
来源：http://dali.daxiang520.top/Article/details/gtquprrxmf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.quarkkingdee.top/Article/details/gtzxcizifc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.mhx1999.top/Article/details/gtsedbfwdr.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtbzktubcu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ivvv.top/Article/details/gtitvdjlcz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgufenzy.top/Article/details/gtlmuewght.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gtfrczvlgy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gteqkbwzln.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shzxlz.cn/Article/details/gttqxageyt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jlsjyb.cn/Article/details/gtjspanrwg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.snrcjt.cn/Article/details/gtrgytrlbz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.redwolf501.top/Article/details/gtuympzzpd.html

[L03] 设置自定义请求头
来源：http://dali.hnxiangtu.top/Article/details/gtijrkmoql.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.feifeiyinyue.top/Article/details/gtpacbiwfn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jyoumei.cn/Article/details/gtdmuwetpe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gtafqckozf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gtsdnqszrp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gtsyvyeszq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtvxjnienb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnqzz.top/Article/details/gtrtxbnaqo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmkgpwic.html

[L04] 设置超时
来源：http://dali.iojbl.cn/Article/details/gttvdficxt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xylfe.cn/Article/details/gtmrwtqmox.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.9152youxi.cn/Article/details/gtozlkmgiu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtavonttmw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gttwkefnva.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtpsjnntug.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gogol.net.cn/Article/details/gtafdymuop.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guannengcc.top/Article/details/gtissojigj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoklmxsfm.html

[L05] 上传文件（multipart）
来源：http://dali.quarkkingdee.top/Article/details/gtmjicnyeu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jyoumei.cn/Article/details/gtrwuorxtt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jyoumei.cn/Article/details/gtztbsbfcr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutzltvyc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtiliqlfjh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gtmxzurahy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xylfe.cn/Article/details/gtutqhesfm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.0kj1m.cn/Article/details/gtvsbvcfga.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gtyiieozve.html

[L06] 解析响应为 JSON
来源：http://dali.xuanzx.com/Article/details/gtqlopnqiq.html

Py:   resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtmbuqwfxb.html

PHP:  json_decode($body, true);
来源：http://dali.daria6918.cn/Article/details/gtssnfcmal.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtlzyetfbq.html

TS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtmdcjihyh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtfetkojkm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pycfn.com/Article/details/gtovdcggja.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangtech.top/Article/details/gtodpzjyst.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cucudq.cn/Article/details/gttpmtkjwx.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtfgmmsplg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuanzhike.top/Article/details/gtdtlqohqk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.birdmap.top/Article/details/gtbfywdyor.html

JS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gtidxwwsiw.html

TS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtzusbymqn.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gtvlhhrulw.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtsoajpzfz.html

Ruby: resp.code.to_i
来源：http://dali.yj202588.top/Article/details/gtrmtjexie.html

C#:   (int)resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gtlpkylxbq.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gtwiaqvwyu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhiwuduotai.top/Article/details/gtdovsxyqj.html

PHP:  curl_multi_init() 系列
来源：http://dali.bjfxy.top/Article/details/gtcgehagjq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtxvwqkwni.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtmtbmapts.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dianchejie.cn/Article/details/gtuyfydcum.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.vqdsnc.cn/Article/details/gtloyhqzlp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gotoacloud.top/Article/details/gtwvqvyrbb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gtjdapsniw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtnjiposwp.html

M. 命令行 / 进程 / 环境
来源：http://dali.hfpthk.cn/Article/details/gtyibqtkrj.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtvpeoafwg.html

[M01] 读取命令行参数
来源：http://dali.zdqjudy.top/Article/details/gtwqqjjztf.html

Py:   sys.argv[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtrpoewicf.html

PHP:  $argv;  $argc;
来源：http://dali.yvedp.cn/Article/details/gtqzqirzng.html

JS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gtivpctkal.html

TS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gtmfnsqalr.html

Java: args 数组（main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gtsqsnqlwj.html

Go:   os.Args[1:]
来源：http://dali.aibaodan.cn/Article/details/gtdakforct.html

Ruby: ARGV
来源：http://dali.jinqigufen.top/Article/details/gtxtwafwxn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtdydlzypo.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gtvrdxulrz.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtujjspttq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtmagogaqc.html

JS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gtkeoolsgi.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtovcvvuvq.html

Java: System.getenv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtsmcrhqyy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtlshhvtzb.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gtmrjgavns.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtuuvxnzdw.html

[M03] 执行外部命令
来源：http://dali.nanxinkj.top/Article/details/gtveewegmk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebwcwhxj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pycfn.com/Article/details/gtjivedqld.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gtfssewpkf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gtwisygkjh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gtsnlapzqh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gtbzqzozhz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gtwlkjpdut.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tian-w.cn/Article/details/gthyregntb.html

[M04] 获取当前工作目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdorhasz.html

Py:   os.getcwd()
来源：http://dali.sweek.top/Article/details/gtfgrrmvyt.html

PHP:  getcwd();
来源：http://dali.xylfe.cn/Article/details/gtaovmcdow.html

JS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpbcpokp.html

TS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtfnbqkajx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yangfankeji.com/Article/details/gtdarpmimg.html

Go:   os.Getwd()
来源：http://dali.yonumen.top/Article/details/gtyxktkoax.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gtuvypomzm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhiwuduotai.top/Article/details/gtrgmfuyjh.html

[M05] 设置退出码
来源：http://dali.yj202588.top/Article/details/gtbbghcign.html

Py:   sys.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtbcbjevkz.html

PHP:  exit(1);
来源：http://dali.hammf.cn/Article/details/gteachmbfb.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtvmkxzkqt.html

TS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtscdijxcb.html

Java: System.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtolqfdula.html

Go:   os.Exit(1)
来源：http://dali.yueranfly.top/Article/details/gtevqjkuxw.html

Ruby: exit 1
来源：http://dali.hammf.cn/Article/details/gtrkniqlva.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gtdydouibg.html

[M06] 向标准错误输出
来源：http://dali.zhongyouzk.top/Article/details/gtijuyegpm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gtqmbvzveq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtpgmfuezl.html

JS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gtlybefecp.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtfanstlfk.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gtnrwwycvc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhoulong.xyz/Article/details/gtnsprmbno.html

Ruby: warn "err"
来源：http://dali.zhengqikj.top/Article/details/gtrfhouaif.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxinkj.top/Article/details/gtkvbovxzi.html

[M07] 判断是否为主入口
来源：http://dali.chenjidiqi.icu/Article/details/gtjgrnakiy.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gtbydhwrpl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shzxlz.cn/Article/details/gtsdosfbuq.html

JS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtebmdbvzf.html

TS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gtdtesnhdj.html


<!-- 参考信息 -->