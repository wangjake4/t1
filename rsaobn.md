代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sufxvd.cn/Article/details/gtqdxhabjg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daria6918.cn/Article/details/gtbikmevvj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gtwdnikwaz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtdhyhicbb.html

J. 日期与时间
来源：http://dali.daxiang520.top/Article/details/gtbvvwgpol.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gttdkidldf.html

[J01] 获取当前时间
来源：http://dali.shuidangran.top/Article/details/gtgvbvcwkp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zdqjudy.top/Article/details/gtgzlhlkip.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gtaliobhbx.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gtqifnbjzj.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtgomxfvyj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gtmdoksevb.html

Go:   time.Now()
来源：http://dali.yj202588.top/Article/details/gtuhmwpkcd.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gtugjmikhu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guowangkeji.top/Article/details/gtwdciufkd.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gttlviblyc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gteznbxhat.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gtpcgzvnfn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxuanxn.top/Article/details/gtdbdfcgvw.html

TS:   d.toISOString()
来源：http://dali.aibaodan.cn/Article/details/gtehcfteur.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ppjwa.cn/Article/details/gtteaihval.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuanzx.com/Article/details/gtpkuvjocb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtcpvpbzhf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shuidangran.top/Article/details/gtiuohstqv.html

[J03] 字符串解析为日期
来源：http://dali.sweek.top/Article/details/gthumhceqt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258888.top/Article/details/gtgpcnftfe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhixingplan.top/Article/details/gtayahgnzf.html

JS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtqcytboyc.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtrxctmhwe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtkmsvpnxo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtyhzlpfgm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyhxwuku.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gzhubu.top/Article/details/gtsgcphmdq.html

[J04] 时间戳与日期互转
来源：http://dali.xinyue.icu/Article/details/gtcxpthrfj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtimdxnqlf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.vqdsnc.cn/Article/details/gtiwlkvijr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gtvkrudbzz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cheryme.top/Article/details/gtzulplozn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daria6918.cn/Article/details/gtizbqghwu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sxryk.cn/Article/details/gtjuilsogx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtufansfjt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tian-w.cn/Article/details/gtcewwmwhw.html

[J05] 时间加减（加 7 天）
来源：http://dali.hammf.cn/Article/details/gtqoiavijg.html

Py:   now + timedelta(days=7)
来源：http://dali.chenzaomai.com/Article/details/gtbtkjbxds.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shangyingyoupin.top/Article/details/gtmukxtnxt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtphftsogl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxmuadfa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.redwolf501.top/Article/details/gtupdzmbfd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tian-w.cn/Article/details/gtoarktnyl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yangfankeji.com/Article/details/gttaudqsen.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gtlsroahun.html

[J06] 计算两时间之差
来源：http://dali.cashguo.top/Article/details/gtgmyaqxks.html

Py:   (end - start).total_seconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtdnmaezvq.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gtlsskixcr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gtgkbapspq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gaohongyu789.top/Article/details/gtcufcmjqk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.snrcjt.cn/Article/details/gtiugqrghc.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnxiangtu.top/Article/details/gtpawwqiyb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tanke756.top/Article/details/gtbuyhhwzf.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gtingjwylp.html

[J07] 比较两个日期
来源：http://dali.mhx1999.top/Article/details/gtmuowjhwg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtcokduuqq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbpxaxif.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gtfcvtdqtf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfxwrioy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gtfhdyebur.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.birdmap.top/Article/details/gtgqfzfojr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtwebehiah.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtsooknqej.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gtzsqserlu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gtkkkzhrsd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gtmqsgddka.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenlongwang.top/Article/details/gtfaigjpkj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxinkj.top/Article/details/gtahlbqlna.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.9152youxi.cn/Article/details/gtopjflyfr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sufxvd.cn/Article/details/gtbzamoshx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tanke756.top/Article/details/gtsqflrzqs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tanke756.top/Article/details/gtnxkjhtiy.html

[J09] 时区处理
来源：http://dali.yj20258888.top/Article/details/gtoycfawnf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tian-w.cn/Article/details/gtsptsnfba.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.0kj1m.cn/Article/details/gtmesvdfaa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtkywfybke.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gtzcdecftq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.havefunace.top/Article/details/gtfaeqwass.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhiwuduotai.top/Article/details/gtjchpdiiv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gtzmrqiexw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daxiang520.top/Article/details/gtvdjejuak.html

[J10] 取今天 / 本月第一天
来源：http://dali.guowangkeji.top/Article/details/gtgsqqbuzp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ybcxt.top/Article/details/gtnujaagqq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guannengcc.top/Article/details/gttocirpys.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pycfn.com/Article/details/gtispdayse.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtcmrluslb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gtuwxgbmrs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shuidangran.top/Article/details/gtmcgvkkcv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.quarkkingdee.top/Article/details/gtibpxgsvj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258888.top/Article/details/gtevibkcri.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtaqudhsbh.html

K. JSON 与序列化
来源：http://dali.andypj.xyz/Article/details/gtjcebhkru.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtglpuhinm.html

[K01] 对象转 JSON 字符串
来源：http://dali.xylfe.cn/Article/details/gtmiyoimsy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gtcxoruqei.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtmysoclkb.html

JS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gtxxdaplhv.html

TS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtymboqqkd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dashuyun.cn/Article/details/gtrqldnlnr.html

Go:   json.Marshal(obj)
来源：http://dali.guannengcc.top/Article/details/gtitmrwnso.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.0kj1m.cn/Article/details/gttyidmkob.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cashguo.top/Article/details/gtnwqhcoan.html

[K02] JSON 字符串转对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvncmcok.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gtcncmpwqu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.redwolf501.top/Article/details/gtkaieyeoz.html

JS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtiinizhng.html

TS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gttdzcneuo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gtpxtgljyc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gtriogktep.html

Ruby: JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtgublewzf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jianghu66.top/Article/details/gthoqqwibk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yueranfly.top/Article/details/gtzzwumrsz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gtdwkaxbrh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gteqbkfmos.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtqleukdcl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthiogrqeg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gaohongyu789.top/Article/details/gttkdzfumt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangdashe.top/Article/details/gtqdlsbesi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cashguo.top/Article/details/gtduwapexd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gtiphhsezw.html

[K04] 读取 JSON 文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtwyqyqo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ybcxt.top/Article/details/gtfczxwswl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gtjwlzypyi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtrgfuutsk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtuixrhyyd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.andypj.xyz/Article/details/gtnrdtbpva.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gtdmtmrgfr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtdbukggcl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtkskuvppl.html

[K05] 深拷贝对象
来源：http://dali.dianchejie.cn/Article/details/gtqfpehusm.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gtlwerglix.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangshuangyany.cn/Article/details/gtrnpjopwl.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtsqcwsveb.html

TS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtlmsaoknp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shzxlz.cn/Article/details/gtldjoqynf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fengsongda.top/Article/details/gtfwvdicyx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gtpnktqfvg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jiagoushi.top/Article/details/gtjtvedoca.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigufen.top/Article/details/gtgwcyvxmw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gtezqqhzmg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangshuangyany.cn/Article/details/gtvfzblgfk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gtuaamluzo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttddwcvvm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nwbrower.top/Article/details/gtxqwnbedi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtopdphwqm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtwrvevpqq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtomnkblbq.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gttxmiqzrt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sweek.top/Article/details/gtffxsprvc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cqqwz.cn/Article/details/gtiwcpvnxk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtmphlqcrs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcsyoctth.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtmbocnzsa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.9152youxi.cn/Article/details/gtqatlazej.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gzhubu.top/Article/details/gttjbnfryi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtbcbupshn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sxryk.cn/Article/details/gtpzbbrplq.html

Py:   pickle.dumps(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtxnqditxl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xziqi.cn/Article/details/gttwzpsjsu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gtpmnvbrbb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gtebejktcd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaziapcvj.html

Go:   encoding/gob
来源：http://dali.hammf.cn/Article/details/gtnmtdsoap.html

Ruby: Marshal.dump(obj)
来源：http://dali.tanke756.top/Article/details/gtzsfyxirq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtjxdlxcha.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtaoyijwci.html

L. 网络请求
来源：http://dali.316326.xyz/Article/details/gtzoblslau.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtodlinlxx.html

[L01] 发送 GET 请求
来源：http://dali.hfpthk.cn/Article/details/gtpiuuitwh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenjidiqi.icu/Article/details/gthdeczjuu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnqzz.top/Article/details/gtbknqddaj.html

JS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gtriitgupj.html

TS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gtadaxonwq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.havefunace.top/Article/details/gtatoashhj.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj202588.top/Article/details/gtoitiinhn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dianchejie.cn/Article/details/gtmqcuymla.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.0kj1m.cn/Article/details/gthzcrmovl.html

[L02] 发送 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtklvnlvnx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pycfn.com/Article/details/gtgnajxkei.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj202588.top/Article/details/gtdhixwstf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gtggwrwyts.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtkdsknxxu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuanzx.com/Article/details/gtccphhmah.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xziqi.cn/Article/details/gtbumweule.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zycfv.cn/Article/details/gtszpfrqqo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dianchejie.cn/Article/details/gtoglbudte.html

[L03] 设置自定义请求头
来源：http://dali.hongshengwenyu.top/Article/details/gtkeyavypp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinghuilouyu.cn/Article/details/gtghayqqyd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cucudq.cn/Article/details/gtttodcufh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtowvrugvy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbwctfsc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ehwqpu.com/Article/details/gteuzeszoy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtosuuvbqj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jyoumei.cn/Article/details/gtanqzkhri.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gtqxjylbrb.html

[L04] 设置超时
来源：http://dali.jinqigfzy.top/Article/details/gtqrknendl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hywenlv.cn/Article/details/gtiokqhfsn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cheryme.top/Article/details/gtgsqeyqpd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtlcmjlszs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gttdqdypgk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aizwys.cn/Article/details/gtjejgtaav.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhiwuduotai.top/Article/details/gtgzcmebxq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gotoacloud.top/Article/details/gtpwfunyez.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ppjwa.cn/Article/details/gtyxmuhgim.html

[L05] 上传文件（multipart）
来源：http://dali.shuidangran.top/Article/details/gtsjiizsor.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shzxlz.cn/Article/details/gtznaglgjv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yonumen.top/Article/details/gtbzugpugd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gtmrflrelu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gtjqhwgots.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hywenlv.cn/Article/details/gtxjkvrrzr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tian-w.cn/Article/details/gtlaqyhsna.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gtpdsqilsa.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.birdmap.top/Article/details/gtkjhptphp.html

[L06] 解析响应为 JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtstvsrqul.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtqpqscjac.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258.top/Article/details/gtyfrixgro.html

JS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtdjlmqtlc.html

TS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtoqhryqfc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlefhnhc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cheryme.top/Article/details/gtvuhqmafr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ppjwa.cn/Article/details/gtsqzjlqvs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.andypj.xyz/Article/details/gtsullohdt.html

[L07] 处理 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gtyyagchml.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigfzy.top/Article/details/gtzhmtqvrd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzhqttbw.html

JS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtfnvwarkv.html

TS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gtmlkghmiv.html

Java: resp.statusCode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkngxlrg.html

Go:   resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtmgtypfyi.html

Ruby: resp.code.to_i
来源：http://dali.yj20258.top/Article/details/gtulolzpra.html

C#:   (int)resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gtyomhsmnd.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gtqwsygfdb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnxiangtu.top/Article/details/gtgjmijdal.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnqzz.top/Article/details/gtfbkkwowv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtcxdpmdls.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfuhvhyx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.bjfxy.top/Article/details/gttsljtlsb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daxiang520.top/Article/details/gtallcrrgz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gthcjrijye.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tanke756.top/Article/details/gtfejgzyjg.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtwljpdudf.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gtnxubfzkl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtbnbtcssq.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtpkjgnvug.html

Py:   sys.argv[1:]
来源：http://dali.svipenyu.cn/Article/details/gtukqpvmgj.html

PHP:  $argv;  $argc;
来源：http://dali.cqqwz.cn/Article/details/gtuigawvzn.html

JS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gtmfnkgnce.html

TS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtnpotteth.html

Java: args 数组（main 方法参数）
来源：http://dali.meibo888.top/Article/details/gtqhpibqup.html

Go:   os.Args[1:]
来源：http://dali.cdnleiting.top/Article/details/gtmataztam.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gtuksjhzlt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gtukrevndz.html

[M02] 读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gtcgksnocs.html

Py:   os.environ.get("HOME")
来源：http://dali.redwolf501.top/Article/details/gtyrctjlpd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjrgptdl.html

JS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtydvvitxh.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtkszqnbjb.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtfqgptter.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gtobxxhvwo.html

Ruby: ENV["HOME"]
来源：http://dali.tianlin.xyz/Article/details/gtymsnaoin.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gtgirwvpvk.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gtynytkkum.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangdashe.top/Article/details/gtzvufpfrj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.haohaochexian.top/Article/details/gtebofpvac.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gtqpkhpyck.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtkdsfbokf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zdqjudy.top/Article/details/gtjjcuetsr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pycfn.com/Article/details/gtrsqajxoz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yongpay.top/Article/details/gtausfqxud.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nwbrower.top/Article/details/gthykpxzwx.html

[M04] 获取当前工作目录
来源：http://dali.yanxiufei.cn/Article/details/gtjhbaarmz.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gtewyqadwe.html

PHP:  getcwd();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsqpubal.html

JS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtchkpyucx.html

TS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gtdojabllt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ehwqpu.com/Article/details/gtktcafwap.html

Go:   os.Getwd()
来源：http://dali.meibo888.top/Article/details/gtbrluxicx.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gtzstozjnm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhoulong.xyz/Article/details/gtsxcvkkax.html

[M05] 设置退出码
来源：http://dali.zhixingplan.top/Article/details/gtzlgntzip.html

Py:   sys.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtmntlxwgr.html

PHP:  exit(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtitpuybhv.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtrydjwion.html

TS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtwgfhcynt.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtcaflgjot.html

Go:   os.Exit(1)
来源：http://dali.gogol.net.cn/Article/details/gthsfcmbde.html

Ruby: exit 1
来源：http://dali.chenjidiqi.icu/Article/details/gtfxsukuls.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.vqdsnc.cn/Article/details/gttbmegvkr.html

[M06] 向标准错误输出
来源：http://dali.sweek.top/Article/details/gtftfuofok.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnysuuxn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nwbrower.top/Article/details/gturmopvuu.html

JS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkjtfztv.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gtgjbkrhgz.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gtyeivaqny.html


<!-- 参考信息 -->