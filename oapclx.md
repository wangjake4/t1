代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tanke756.top/Article/details/gtmcxmfbxd.html

TS:   /error/gim
来源：http://dali.cashguo.top/Article/details/gtxtlhgdlw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gtgcixqecz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pycfn.com/Article/details/gthaberlao.html

Ruby: s.scan(/error/i)
来源：http://dali.xuanzx.com/Article/details/gtutqljcem.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sufxvd.cn/Article/details/gtelgnpqdx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.quarkkingdee.top/Article/details/gtcwolcnhe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hammf.cn/Article/details/gtcxcuvrcw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gtwrptyclu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gtgcykrpoi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gthxcznddb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtjvhzjynh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gtrvlyipjk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pengpengdd.cyou/Article/details/gtumanjeiq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gtubdbgsyt.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnukjnccx.html

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gtbtcmignj.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtjakvtaxd.html

[J01] 获取当前时间
来源：http://dali.smart0.xyz/Article/details/gtewwfwqzi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hammf.cn/Article/details/gteompidan.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtqmznjjcr.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtsxwfbvgd.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gtgyoboiki.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.andypj.xyz/Article/details/gtzeiyqthe.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gtywkxfpef.html

Ruby: Time.now
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkyeecdjn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.c1oappe.top/Article/details/gtnrsmxcym.html

[J02] 格式化输出
来源：http://dali.gzhubu.top/Article/details/gtrwpuhvmg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gteeqggsgx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gtwmawhzjb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.iojbl.cn/Article/details/gtzqqajmrb.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gtyrbkvveb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigfzy.top/Article/details/gtrdmmsfjd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yonumen.top/Article/details/gteedvlzmm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gtcariwwzi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenzaomai.com/Article/details/gtnkhpdqow.html

[J03] 字符串解析为日期
来源：http://dali.sysykeji.top/Article/details/gtpnkmtfui.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daxiang520.top/Article/details/gtrkrrwijn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tianlin.xyz/Article/details/gtrufgvoqp.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtdwpgacyd.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtyhdkrvdz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gthhdkobbq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtsoiqfdvm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcszctoil.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xylfe.cn/Article/details/gtkhxxmhaa.html

[J04] 时间戳与日期互转
来源：http://dali.dashuyun.cn/Article/details/gtcjkmxmoc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtfrbeidag.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yangfankeji.com/Article/details/gtfdbdkkbr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.mhx1999.top/Article/details/gtoicyzqpv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gtscyitbkd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.meibo888.top/Article/details/gtoqzoozgd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtklyqdiwm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gtghsftnaa.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guowangkeji.top/Article/details/gtillewhog.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgufenzy.top/Article/details/gtkkrzkbnd.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gtcecgsoga.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbbocmvf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtuojkqplk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gtqoghxwgb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258888.top/Article/details/gtbfzybkrr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aizwys.cn/Article/details/gtifvxlvvw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.birdmap.top/Article/details/gtljzhppgv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtwrcrazga.html

[J06] 计算两时间之差
来源：http://dali.hnqzz.top/Article/details/gtjdsqlxst.html

Py:   (end - start).total_seconds()
来源：http://dali.yuxming.cn/Article/details/gtkcstfqqr.html

PHP:  $end->diff($start)->days;
来源：http://dali.zycfv.cn/Article/details/gtfcrzptzc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangshuangyany.cn/Article/details/gtdmvupbnj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhengqikj.top/Article/details/gtbhdqobiv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jianghu66.top/Article/details/gtbxydpahk.html

Go:   end.Sub(start).Hours()
来源：http://dali.hfpthk.cn/Article/details/gtuxcedmce.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shangyingyoupin.top/Article/details/gtgcenlbet.html

C#:   (end - start).TotalSeconds
来源：http://dali.hfpthk.cn/Article/details/gtualdkabv.html

[J07] 比较两个日期
来源：http://dali.zhongyouzk.top/Article/details/gtnzmwbzfq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gttfqztidf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.kuanghao11.cn/Article/details/gtwsxbnssr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gtgptlrobo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gtjimjyjil.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sweek.top/Article/details/gtodjewctj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shuidangran.top/Article/details/gtnlysrqpt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtsenyxjuv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtgqulxgqf.html

[J08] 提取年月日与星期
来源：http://dali.jqgufenzy.top/Article/details/gtaltommle.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigufen.top/Article/details/gtpiejdenn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gzhubu.top/Article/details/gtcqcddqyh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.meibo888.top/Article/details/gtbgffpsuw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cashguo.top/Article/details/gtbynklyna.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenzaomai.com/Article/details/gtkmqwfcfj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jiagoushi.top/Article/details/gtgsiyooap.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gtlektpqhz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuanzx.com/Article/details/gtimknqsng.html

[J09] 时区处理
来源：http://dali.wangdashe.top/Article/details/gtzsvaffxc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.andypj.xyz/Article/details/gtmskgqfkf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gtanytexpp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gtrzbgezog.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gteqtgtfpo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gtsztpflxu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dashuyun.cn/Article/details/gtawtpohgd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgfzy.top/Article/details/gtzzcugsvi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gtywsufhbm.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gtgbtvlupq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gtvigswayi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsyhrtla.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhengqikj.top/Article/details/gtixgtwham.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtcnuvvnzl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hongshengwenyu.top/Article/details/gttbsufjqv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gotoacloud.top/Article/details/gthwoshgtx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sxryk.cn/Article/details/gteilezisw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtkjharuny.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtloeqdcbq.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gtkyedhtne.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtmezggpzd.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gtfzrrqhpi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gteubrswof.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtcpokkvsv.html

JS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gtuvumajjp.html

TS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtumiygvrg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gtluvvmofj.html

Go:   json.Marshal(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtziaglxpw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fzhhl.top/Article/details/gtpzzkfrwq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hammf.cn/Article/details/gtpwfdrdxz.html

[K02] JSON 字符串转对象
来源：http://dali.yangfankeji.com/Article/details/gtjpoxxlmn.html

Py:   json.loads(s)
来源：http://dali.yangfankeji.com/Article/details/gtiazrwlsq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yongpay.top/Article/details/gthtmbhrbf.html

JS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunooktat.html

TS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtyjxwjiqx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sysykeji.top/Article/details/gtjrqsuoxa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtfjskgoio.html

Ruby: JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrxnlxkx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zycfv.cn/Article/details/gtiohtiwve.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yongpay.top/Article/details/gtcppeldoj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtxscinwwo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gtmdbemrov.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtdeinwmcs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gtufoarkjy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sxryk.cn/Article/details/gtslsztbzx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gtjfcjupol.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.iojbl.cn/Article/details/gtjrsickqn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gtbglsvgns.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gtumbrnamn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtjznrvznl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gtdlavzewj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gtbxbhretq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtvdmszarh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtpdcztcre.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdxdbjxq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yueranfly.top/Article/details/gtjqpqcmwy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gtyiqmqwhv.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjgxtmle.html

Py:   copy.deepcopy(obj)
来源：http://dali.bjfxy.top/Article/details/gtjhjpowkt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xinyue.icu/Article/details/gtfgqyhjed.html

JS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtwvlfbbnd.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtmnqljurd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhongyouzk.top/Article/details/gtdtzmwbmz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuxming.cn/Article/details/gtokxopeuw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gtqzdfvpvn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gtoqqubwni.html

[K06] 解析 URL 查询串
来源：http://dali.yanxiufei.cn/Article/details/gtgyhpkafj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shuidangran.top/Article/details/gtjaidclry.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuetiantiany.cn/Article/details/gtydarhump.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gtazcepshw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtjqqajfon.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxuanxn.top/Article/details/gtbmwdougb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtebrhtylo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gtwchcpcrk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtwpfzyytm.html

[K07] 进制转换
来源：http://dali.zhoulong.xyz/Article/details/gttilbxoih.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtucfwwgti.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258888.top/Article/details/gtaecygowk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtlceexdua.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtbejyaurh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtiryogawf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gteidofaep.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.havefunace.top/Article/details/gtugcneruh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtsubvvrpf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cheryme.top/Article/details/gtdmtrrhhz.html

Py:   pickle.dumps(obj)
来源：http://dali.aibaodan.cn/Article/details/gtvfdcpqrs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dianchejie.cn/Article/details/gtutyxeska.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtnzqdubna.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gtncpatnfl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.bjfxy.top/Article/details/gtaqnyoqhr.html

Go:   encoding/gob
来源：http://dali.iojbl.cn/Article/details/gtqzsdrcdh.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258.top/Article/details/gtuxxhkevf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpcxxxdp.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtonrxmsvx.html

L. 网络请求
来源：http://dali.andypj.xyz/Article/details/gtcoqzxhik.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtzsbeceui.html

[L01] 发送 GET 请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrbxlcwh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.0kj1m.cn/Article/details/gtzaycxagm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yueranfly.top/Article/details/gtkxigmncs.html

JS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gthgjpdjml.html

TS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gtnhvfecka.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.feifeiyinyue.top/Article/details/gtueymujbu.html

Go:   resp, err := http.Get(url)
来源：http://dali.redwolf501.top/Article/details/gtzlmaxtmj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.andypj.xyz/Article/details/gtlaqxcrmu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenzaomai.com/Article/details/gtxiwiglmu.html

[L02] 发送 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gtszjeaors.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtmpxrvjds.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ehwqpu.com/Article/details/gtjdwzsyfw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gtrhwngdhc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gtyishrtwz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gogol.net.cn/Article/details/gtekokcoug.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gaohongyu789.top/Article/details/gthfveppur.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tanke756.top/Article/details/gthnzktsla.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.iojbl.cn/Article/details/gtbwwouatg.html

[L03] 设置自定义请求头
来源：http://dali.yj20258888.top/Article/details/gthibcsioz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aibaodan.cn/Article/details/gthzvlzgrp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hysaishi.cn/Article/details/gtxkrhqabn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gtofqrjmir.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gtakqghbxp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gtjxrblzqi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gtmuhsibba.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydjxghcn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtgqtqedwv.html

[L04] 设置超时
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcqzdhbz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gtfcsoycgo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnxiangtu.top/Article/details/gtkventspk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtnxvnijve.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikhtjvbn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.mhx1999.top/Article/details/gtmiihnmmk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yueranfly.top/Article/details/gtqrdxpfir.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuetiantiany.cn/Article/details/gtsqxiprlq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jlsjyb.cn/Article/details/gthjapayup.html

[L05] 上传文件（multipart）
来源：http://dali.gotoacloud.top/Article/details/gtwavahevr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xinyue.icu/Article/details/gtdagkhgoo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gtmfalexnf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtxymxtakp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtxayfiiow.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258888.top/Article/details/gtexizxypf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aizwys.cn/Article/details/gtfbbontua.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tian-w.cn/Article/details/gteqgdwlzh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtlniqxlqp.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gthecynode.html

Py:   resp.json()
来源：http://dali.iojbl.cn/Article/details/gtdphxnyhl.html

PHP:  json_decode($body, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtynfojvql.html

JS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gthrxmsijy.html

TS:   await resp.json()
来源：http://dali.0kj1m.cn/Article/details/gtgbbetcso.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yvedp.cn/Article/details/gtsljeznwk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgufenzy.top/Article/details/gtgpuvduay.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258.top/Article/details/gtbdgeaidc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gtvtuyxqtt.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtvltwsnxu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yueranfly.top/Article/details/gtnhceeeiq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yangfankeji.com/Article/details/gtzdocyxcq.html

JS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gtlmxjwmrf.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gtukqcgsnf.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gtehnhviqc.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlptndgl.html

Ruby: resp.code.to_i
来源：http://dali.ybcxt.top/Article/details/gtcbvjidsd.html

C#:   (int)resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtfeqropmx.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gtrzhxvlls.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gttbzfkexx.html

PHP:  curl_multi_init() 系列
来源：http://dali.ppjwa.cn/Article/details/gtyqswmxld.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtpomkdmnt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtyizgnnjz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cucudq.cn/Article/details/gtcmrnixij.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzgxoiyd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtvmgjfskn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.haohaochexian.top/Article/details/gtecuvtmcx.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtxbdygceg.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuetiantiany.cn/Article/details/gteocqosjj.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtraafmoyf.html

[M01] 读取命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtgcpcskur.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gtfwuuycmk.html

PHP:  $argv;  $argc;
来源：http://dali.gotoacloud.top/Article/details/gtcpwatwae.html

JS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtrbpxywpp.html

TS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gthppoqqxs.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gttfuxrpdx.html

Go:   os.Args[1:]
来源：http://dali.cdnleiting.top/Article/details/gtjjnihuae.html

Ruby: ARGV
来源：http://dali.daxiang520.top/Article/details/gtlyxicgmv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gtruwbyzas.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtcsvkdadx.html

Py:   os.environ.get("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtufilabmb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.meibo888.top/Article/details/gtnrsyfrxc.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gtdmpucjdk.html

TS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtvlqlynoc.html

Java: System.getenv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtuubvvlpj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.meibo888.top/Article/details/gtqifrdkkl.html

Ruby: ENV["HOME"]
来源：http://dali.kuanghao11.cn/Article/details/gtzvjkvovy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tian-w.cn/Article/details/gtgzvceqjp.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gtzznqsngu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xinyue.icu/Article/details/gtltevhpws.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gtdsmiryqd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtfhmazvpe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gtkusrgdmc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.snrcjt.cn/Article/details/gthvcicstj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xinyue.icu/Article/details/gtqiozvfsh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cucudq.cn/Article/details/gtxtuflrbg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yueranfly.top/Article/details/gtssbeoqnc.html

[M04] 获取当前工作目录
来源：http://dali.jiagoushi.top/Article/details/gtbhqzfoih.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gtruzjftac.html

PHP:  getcwd();
来源：http://dali.ivvv.top/Article/details/gtjkxsljax.html

JS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtdvqgqiim.html

TS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtwuhkvrpt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcifotmz.html

Go:   os.Getwd()
来源：http://dali.316326.xyz/Article/details/gtklltjhkj.html

Ruby: Dir.pwd
来源：http://dali.iojbl.cn/Article/details/gtohqrmivs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkxhsecw.html

[M05] 设置退出码
来源：http://dali.redwolf501.top/Article/details/gtdigbtsme.html

Py:   sys.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtpgybsrzx.html

PHP:  exit(1);
来源：http://dali.jlsjyb.cn/Article/details/gtfwxpgfci.html


<!-- 参考信息 -->