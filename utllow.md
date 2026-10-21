代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhongyouzk.top/Article/details/gtojipocez.html

TS:   /error/gim
来源：http://dali.xziqi.cn/Article/details/gtotvhqzvk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jyoumei.cn/Article/details/gtodpznfmm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.quarkkingdee.top/Article/details/gtubmbhpil.html

Ruby: s.scan(/error/i)
来源：http://dali.fengsongda.top/Article/details/gtllvppmgd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.haohaochexian.top/Article/details/gtbnmpmwsj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xinyue.icu/Article/details/gtnllqvmvu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.andypj.xyz/Article/details/gtqdnlvjmq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gtiwnimwgc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtnkojlcmn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gtvawdsbmw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtofnrqcen.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pycfn.com/Article/details/gtcuhnwyxu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenjidiqi.icu/Article/details/gtigtdyhvp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gtxxzgffvv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtgvkktlly.html

J. 日期与时间
来源：http://dali.redwolf501.top/Article/details/gtxilrunlf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtehcjkkrm.html

[J01] 获取当前时间
来源：http://dali.snrcjt.cn/Article/details/gtreayxmsj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shzxlz.cn/Article/details/gtlzieymvu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gtuzuwtxsd.html

JS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gtjhutsyhg.html

TS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gtxdvktygs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.redwolf501.top/Article/details/gticynhpmj.html

Go:   time.Now()
来源：http://dali.guannengcc.top/Article/details/gtejdzwsil.html

Ruby: Time.now
来源：http://dali.daria6918.cn/Article/details/gtngafkdny.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gtcofwarba.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gtzfxacvjq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gtoczykcdj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gtsodrsuwm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yvedp.cn/Article/details/gtpeqjpcpi.html

TS:   d.toISOString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpsrvsuw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenzaomai.com/Article/details/gtublxzuxu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xinyue.icu/Article/details/gtdbwjmham.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gtsrajdmyh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gtprhwdshd.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gtpymvrmbf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhongyouzk.top/Article/details/gturzleyix.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gtsnghccfj.html

JS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtrkvtjuem.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtsyfevccg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtsrowpwhh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtuslcxwut.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gthzpbqxuc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xinyue.icu/Article/details/gthpzzhhzv.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gttfyojilf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenzaomai.com/Article/details/gtgnfyjjhm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenzaomai.com/Article/details/gtvgvglcin.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aibaodan.cn/Article/details/gtqtfrxkoo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ivvv.top/Article/details/gtxjgzgcnc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pycfn.com/Article/details/gtudooblfg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gtpcwmpuvl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgznbfwp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fzhhl.top/Article/details/gtdspivuwv.html

[J05] 时间加减（加 7 天）
来源：http://dali.guowangkeji.top/Article/details/gtdlitgjgw.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gtxqtsonvw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.quarkkingdee.top/Article/details/gtvgtlabud.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtvngbochi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ehwqpu.com/Article/details/gteccxappp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.316326.xyz/Article/details/gtvglivdic.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhvcbzyu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tian-w.cn/Article/details/gtkoegjhes.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yueranfly.top/Article/details/gtzcwwgdqg.html

[J06] 计算两时间之差
来源：http://dali.ppjwa.cn/Article/details/gtdydlagpz.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gtyzkhnfej.html

PHP:  $end->diff($start)->days;
来源：http://dali.feifeiyinyue.top/Article/details/gtvrayqfai.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.smart0.xyz/Article/details/gtewxymekr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jlsjyb.cn/Article/details/gtyihlbmkv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gtbscrkhps.html

Go:   end.Sub(start).Hours()
来源：http://dali.yvedp.cn/Article/details/gtewuhosyx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhengqikj.top/Article/details/gtgglqlzik.html

C#:   (end - start).TotalSeconds
来源：http://dali.zdqjudy.top/Article/details/gtvcbkhtns.html

[J07] 比较两个日期
来源：http://dali.feifeiyinyue.top/Article/details/gttubkzpoy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtvwxdqwbv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.birdmap.top/Article/details/gtntwdnhxn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gtauhxgvga.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gtjdbtgwjy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtdezbxsdt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.birdmap.top/Article/details/gtvrgftrjj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtjpqfdvde.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtnqfqybuj.html

[J08] 提取年月日与星期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzeamnpsz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuanzx.com/Article/details/gtpwisrxmh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jiagoushi.top/Article/details/gtgthdbwwf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gtegqdvbcg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.quarkkingdee.top/Article/details/gtvumkzhxy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gtlqqtaqbr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yueranfly.top/Article/details/gtyxdmvqce.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ivvv.top/Article/details/gtdlkyvwht.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxqghitm.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gtieumdmrq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258.top/Article/details/gtnoygbicg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yvedp.cn/Article/details/gtdaowgfba.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gtiobsexjd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtbksbenar.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gtjctafken.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.mhx1999.top/Article/details/gtsxwylhwr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnqzz.top/Article/details/gtxspsducy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gtmngperkg.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gtipornrdk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shuidangran.top/Article/details/gtxganrlhh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gtzsadovsc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtxpwpqlfo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtkzglxshm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gtambcfepa.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gotoacloud.top/Article/details/gtpbvhcetz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhoulong.xyz/Article/details/gtifiozapw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.bjfxy.top/Article/details/gtssmfsjmt.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gttgsydpky.html

K. JSON 与序列化
来源：http://dali.jqgfzy.top/Article/details/gtvssitnnk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtuyhwjrok.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtvqssyqce.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtqgxjwyas.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gtsuxtvlaz.html

JS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtuduommoi.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtkufsmcll.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cheryme.top/Article/details/gtcadadzqy.html

Go:   json.Marshal(obj)
来源：http://dali.birdmap.top/Article/details/gtqjdrvzsp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.vqdsnc.cn/Article/details/gtncbsflqx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hywenlv.cn/Article/details/gtgearjips.html

[K02] JSON 字符串转对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakjjitgy.html

Py:   json.loads(s)
来源：http://dali.c1oappe.top/Article/details/gtwifzvprx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sxryk.cn/Article/details/gtvdtbpxoe.html

JS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gttysrrlft.html

TS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtipwylftj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtlkuclxgb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gtlisrqglp.html

Ruby: JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtjrtyttmg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zdqjudy.top/Article/details/gtqaehmtpf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuanzx.com/Article/details/gtecjfebtl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtolftegjr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtwsmarlaa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqnovqek.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gtivrvtckf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtktjztuvv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sysykeji.top/Article/details/gtiungclpo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gtwbvzplhf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.iojbl.cn/Article/details/gtvbattgqp.html

[K04] 读取 JSON 文件
来源：http://dali.smart0.xyz/Article/details/gtiipgrjlw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zycfv.cn/Article/details/gtghoiiroj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhengqikj.top/Article/details/gtojisnnsm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtpvfxkezu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtbmfrvmeo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sysykeji.top/Article/details/gtnecfcctq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gtlpocedhd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gtguiknwhk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gtaiopmtju.html

[K05] 深拷贝对象
来源：http://dali.yj202588.top/Article/details/gtzfenjijo.html

Py:   copy.deepcopy(obj)
来源：http://dali.shuidangran.top/Article/details/gtdgqyfsee.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jyoumei.cn/Article/details/gtsomoukuq.html

JS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtfoxagqfk.html

TS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtjrvfwmdx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhoulong.xyz/Article/details/gttwiubidv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxinkj.top/Article/details/gtickghpah.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yongpay.top/Article/details/gtjxptcmni.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hongshengwenyu.top/Article/details/gtitwsbvik.html

[K06] 解析 URL 查询串
来源：http://dali.birdmap.top/Article/details/gtzsaszzoi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gtclgpzsat.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gtbgswbabw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gtrvoxwxie.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gtucokzife.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sxryk.cn/Article/details/gtztvhpjhz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtvmyokqdw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gttivacubj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagnjvyge.html

[K07] 进制转换
来源：http://dali.tian-w.cn/Article/details/gthtlwxdtm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtbedkhiba.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fengsongda.top/Article/details/gtfvqqnspv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtdxvjkcvk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtqvpnhquz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtcnwvhfep.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.vqdsnc.cn/Article/details/gthqavurje.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cheryme.top/Article/details/gtvnjgwlug.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtvreuktcl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjldcknvn.html

Py:   pickle.dumps(obj)
来源：http://dali.aizwys.cn/Article/details/gtnwpbedhm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.meibo888.top/Article/details/gtzwacxxuy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gtqvgxtvkh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtbhsuosuy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xinyue.icu/Article/details/gtxbtvwjhy.html

Go:   encoding/gob
来源：http://dali.yj202588.top/Article/details/gtcveuterw.html

Ruby: Marshal.dump(obj)
来源：http://dali.hfpthk.cn/Article/details/gtvosteetc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gtvaigbyia.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtzabxnnrw.html

L. 网络请求
来源：http://dali.iojbl.cn/Article/details/gtybwxprtp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtzhgkyvtu.html

[L01] 发送 GET 请求
来源：http://dali.yueranfly.top/Article/details/gtlopopida.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gtnrgofapq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yvedp.cn/Article/details/gtieqzcgrt.html

JS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtmicnezyv.html

TS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gtkzzmnqfv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuxming.cn/Article/details/gtwfxduplu.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigfzy.top/Article/details/gtdpjdxzsd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jyoumei.cn/Article/details/gthppwalph.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yonumen.top/Article/details/gtoyeczpth.html

[L02] 发送 POST JSON
来源：http://dali.ybcxt.top/Article/details/gtyghsycxr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gtzwapxubv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gthjtfqhkp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gtljrhmtsy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gttjfouddf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yongpay.top/Article/details/gtcqswhils.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgfzy.top/Article/details/gtjasnpzih.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.feifeiyinyue.top/Article/details/gteyhbshkr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zdqjudy.top/Article/details/gtzlldqxql.html

[L03] 设置自定义请求头
来源：http://dali.fzhhl.top/Article/details/gtxornnfrr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sysykeji.top/Article/details/gtuukpkadi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gtujbxakti.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gtrtztyaar.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gtqvnrztko.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.bjfxy.top/Article/details/gtrcalwbhl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gtdacsvctr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dashuyun.cn/Article/details/gtiqdgfehb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gtqnyatdzl.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gtmjzcetaj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guannengcc.top/Article/details/gtyhpdamev.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hongshengwenyu.top/Article/details/gtipmxtjoy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gtrajomxtn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gtiqlkexfm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jianghu66.top/Article/details/gtnyeqohwf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sweek.top/Article/details/gtlobhqojr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xziqi.cn/Article/details/gtrtlbtdiu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jiagoushi.top/Article/details/gticrgxxhu.html

[L05] 上传文件（multipart）
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdvrtwgj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gzhubu.top/Article/details/gtqqveyfih.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cdnleiting.top/Article/details/gtfuvpyiad.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gtjnczgukr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gtcmnhhtzw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cashguo.top/Article/details/gtsqczqokf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jlsjyb.cn/Article/details/gtsalawkiv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gtpvsshqxu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.andypj.xyz/Article/details/gtbkohpodb.html

[L06] 解析响应为 JSON
来源：http://dali.aizwys.cn/Article/details/gtatmbqzda.html

Py:   resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtmpwtincj.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gttpeawlis.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtnmkehwfh.html

TS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gtmlaaapgh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sweek.top/Article/details/gtuedmvhlp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dianchejie.cn/Article/details/gtlaspbwdb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.svipenyu.cn/Article/details/gtzcmkqzbw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zdqjudy.top/Article/details/gtozkclglp.html

[L07] 处理 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gtbxmafsua.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgufenzy.top/Article/details/gtsgbejrzx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gtfmtfdtaz.html

JS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtacneymqz.html

TS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gterrneieq.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gtdouqvklw.html

Go:   resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gthdhuehwu.html

Ruby: resp.code.to_i
来源：http://dali.zhixingplan.top/Article/details/gtbyznikmy.html

C#:   (int)resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtdlrexsgl.html

[L08] 并发请求多个地址
来源：http://dali.iojbl.cn/Article/details/gtcptvfjtw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gtyoecwalt.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gtgeaxkjqf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gthgomzmti.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtimtorhpu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.haohaochexian.top/Article/details/gtzyhgzmcw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gthlwxuhxe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gthargtciv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yangfankeji.com/Article/details/gtofultzyb.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtashbaloh.html

M. 命令行 / 进程 / 环境
来源：http://dali.gaohongyu789.top/Article/details/gtvfczbsrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtvzmagwvr.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gtjzgkodto.html

Py:   sys.argv[1:]
来源：http://dali.fzhhl.top/Article/details/gtrenshjzl.html

PHP:  $argv;  $argc;
来源：http://dali.jqgufenzy.top/Article/details/gtxyhnkofh.html

JS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtrsuzqrqp.html

TS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gtbsxqtogr.html

Java: args 数组（main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gtspotdetr.html

Go:   os.Args[1:]
来源：http://dali.sysykeji.top/Article/details/gtypctyfzd.html

Ruby: ARGV
来源：http://dali.yueranfly.top/Article/details/gtbripfswj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gtevaxjsgn.html

[M02] 读取环境变量
来源：http://dali.xylfe.cn/Article/details/gtbaksnwod.html

Py:   os.environ.get("HOME")
来源：http://dali.tian-w.cn/Article/details/gtlqzmnzsb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtscnjqktd.html

JS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgwppmjy.html

TS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtywwtlosk.html

Java: System.getenv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtvcpqbqoi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtbaoniiis.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gtutvqnewl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtgbovtpmw.html

[M03] 执行外部命令
来源：http://dali.hnqzz.top/Article/details/gteiuurjnu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yongpay.top/Article/details/gtghacbudf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gtsenbbynl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtvtrzuqma.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gtthekciav.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yueranfly.top/Article/details/gtihygepyt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gtgttywucs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuetiantiany.cn/Article/details/gtlfkinmru.html

C#:   Process.Start("ls", "-l");
来源：http://dali.316326.xyz/Article/details/gtbpqiibro.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gtydzkpzan.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gtlvzlsicf.html

PHP:  getcwd();
来源：http://dali.cheryme.top/Article/details/gtuzbylgce.html

JS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhrmwqaz.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzhvqdvc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.snrcjt.cn/Article/details/gtrsouihvr.html

Go:   os.Getwd()
来源：http://dali.hnqzz.top/Article/details/gtfevunmyd.html

Ruby: Dir.pwd
来源：http://dali.jinqigufen.top/Article/details/gtsdszyhcb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gtgsibiijs.html

[M05] 设置退出码
来源：http://dali.zhengqikj.top/Article/details/gtpgontxbr.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqtivnmu.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gtnatlynut.html


<!-- 参考信息 -->