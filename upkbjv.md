代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtjiapsqwg.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangdashe.top/Article/details/gtalkyhflu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pycfn.com/Article/details/gtmohmxtqt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtxmfcmkws.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gtaozgdawz.html

TS:   /error/gim
来源：http://dali.ybcxt.top/Article/details/gtuimjukve.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.andypj.xyz/Article/details/gtlhvkpewp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.haohaochexian.top/Article/details/gtgrmisdjn.html

Ruby: s.scan(/error/i)
来源：http://dali.fzhhl.top/Article/details/gtyuzprdpy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sufxvd.cn/Article/details/gtyakhjzud.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gtnaeprkva.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dianchejie.cn/Article/details/gtwpkuzzko.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gtnlsryenl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtqzquarnj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gtruxpdxbg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gtregfgmac.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.smart0.xyz/Article/details/gtxeuukwhj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gtsdnrfmsi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtygrhuacm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtdcgeqdft.html

J. 日期与时间
来源：http://dali.fengsongda.top/Article/details/gtztemhnvu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtdoopbnvm.html

[J01] 获取当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtslllptty.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenlongwang.top/Article/details/gtnsgtgueg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtjxjlrmxi.html

JS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gtrtcjbrrj.html

TS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gtpupashqx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fzhhl.top/Article/details/gtdbvcsbnr.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gtyyzjhrlm.html

Ruby: Time.now
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthwbuhan.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jyoumei.cn/Article/details/gtpwxxejla.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtedkagudz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtozudnidm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gtwkkxvpeq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daxiang520.top/Article/details/gtkeybkbye.html

TS:   d.toISOString()
来源：http://dali.nanxinkj.top/Article/details/gtfqpckjqn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gtlmkydtnu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhiwuduotai.top/Article/details/gtgkksmuho.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gtcdfabifi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgfzy.top/Article/details/gtiycstwwr.html

[J03] 字符串解析为日期
来源：http://dali.gzhubu.top/Article/details/gtmkzwpwrh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hysaishi.cn/Article/details/gtfmevgejf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gthkfkrjbk.html

JS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtdphhomnd.html

TS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtbwcoyuxj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtnnwuknsv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtvslmjycl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtctaalklc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zdqjudy.top/Article/details/gtptuwxyig.html

[J04] 时间戳与日期互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcnqvmcc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtrfedwjip.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.redwolf501.top/Article/details/gtjkvumjvr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.haohaochexian.top/Article/details/gtljqjdueu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tianlin.xyz/Article/details/gtmxcentjn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yangfankeji.com/Article/details/gtnuzxnldf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tianlin.xyz/Article/details/gtkyjjualh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ydzc1.top/Article/details/gtyxvklfhp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxinkj.top/Article/details/gtueofqzak.html

[J05] 时间加减（加 7 天）
来源：http://dali.cashguo.top/Article/details/gtbaycsimr.html

Py:   now + timedelta(days=7)
来源：http://dali.chenzaomai.com/Article/details/gthncxcskj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jyoumei.cn/Article/details/gtevwaggrt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtjohkfiop.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtldmeyaoe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tianlin.xyz/Article/details/gthoudpwlt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrvrskok.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gtfirhkdra.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj202588.top/Article/details/gtlbcneqcr.html

[J06] 计算两时间之差
来源：http://dali.dianchejie.cn/Article/details/gtzhamxtqn.html

Py:   (end - start).total_seconds()
来源：http://dali.cucudq.cn/Article/details/gtekihskaz.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gtvzthhsqv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xinyue.icu/Article/details/gttxqjnmie.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyvuhuuy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.haohaochexian.top/Article/details/gtuobmsefi.html

Go:   end.Sub(start).Hours()
来源：http://dali.havefunace.top/Article/details/gtmmuxgiyz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gtqezlcdbp.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gtuqtljgls.html

[J07] 比较两个日期
来源：http://dali.cdnleiting.top/Article/details/gtqxertgdp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gttwanfcsk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gogol.net.cn/Article/details/gtumhguvkv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gtblhuxyvy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhtsfhbx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sufxvd.cn/Article/details/gtkztbljtz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yvedp.cn/Article/details/gtrzguwkzd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtllbszacd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtrduadael.html

[J08] 提取年月日与星期
来源：http://dali.aibaodan.cn/Article/details/gtgfxaqrne.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yanxiufei.cn/Article/details/gtznapfykl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dianchejie.cn/Article/details/gtsvbryrwv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shangyingyoupin.top/Article/details/gteoizwfou.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daria6918.cn/Article/details/gtnaqisgti.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.snrcjt.cn/Article/details/gtejgdjnci.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pengpengdd.cyou/Article/details/gtftzhahra.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gtsdltzdtt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gtjalunljf.html

[J09] 时区处理
来源：http://dali.aibaodan.cn/Article/details/gtznsrkyeu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pycfn.com/Article/details/gthctdbvhv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenzaomai.com/Article/details/gttnxqttoi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtdxixzkfl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gtvysviyyl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gtfyzgedpw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sweek.top/Article/details/gtreerfdhx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gthcvzmqeb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gthwxiabxv.html

[J10] 取今天 / 本月第一天
来源：http://dali.nwbrower.top/Article/details/gtcwawaodw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shzxlz.cn/Article/details/gtsjkvwnao.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.haohaochexian.top/Article/details/gtiowpmmco.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtzoxbrcpa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cheryme.top/Article/details/gtmuqsntpg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yanxiufei.cn/Article/details/gtrgkrbtqb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsnhwcvh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.andypj.xyz/Article/details/gtouqotuvk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gthnhotwkh.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtoehcammk.html

K. JSON 与序列化
来源：http://dali.fzhhl.top/Article/details/gtghbwhwua.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtdhqswcnm.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgufenzy.top/Article/details/gtygrhrunv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gtmdoyzmqi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqriwkomb.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gttctxzvpy.html

TS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtedchpijh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pycfn.com/Article/details/gtpdnatstu.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjolvursg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hysaishi.cn/Article/details/gtoeokyqbk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtmdxwymul.html

[K02] JSON 字符串转对象
来源：http://dali.sysykeji.top/Article/details/gtvgqhqfxc.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiaadswjr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.haohaochexian.top/Article/details/gtwlsrvprf.html

JS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtozusgxhp.html

TS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtkcgwyruy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtljiwetqg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtvnrqmqik.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtoepxoqww.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gtkyopzgqu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nwbrower.top/Article/details/gtadnjtqoo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtzwaflnzd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gtgnmazjtv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gteoagmjir.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gtbpdvmghk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gtsptnwuty.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsharehqe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtyvqjyqym.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aibaodan.cn/Article/details/gtfrtyofwu.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gtogddywub.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.0kj1m.cn/Article/details/gteorgcfxx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.meibo888.top/Article/details/gtlquemjow.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gtmvjlvdgn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gtymwhxvog.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gteoeqcime.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gtwlrtbcst.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtyivmgwlx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gteevpejqf.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gthmkuyawg.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtdzxougds.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenlongwang.top/Article/details/gtscakmjgk.html

JS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gtolcmqdle.html

TS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtprsrqimw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daxiang520.top/Article/details/gtjipysfti.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuondhskz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.svipenyu.cn/Article/details/gtlcigxjnt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zycfv.cn/Article/details/gtdsxasdul.html

[K06] 解析 URL 查询串
来源：http://dali.zhoulong.xyz/Article/details/gtjeaftxzh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtleydxynn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.bjfxy.top/Article/details/gtqzsugtmf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gtkqwwaahf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtesrbbdwc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sxryk.cn/Article/details/gtrntugsbp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtoiwzfiwo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtqemxsrkg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtdyrcqxub.html

[K07] 进制转换
来源：http://dali.yongpay.top/Article/details/gtmjtlkfnr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtyyzrvwke.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidqxqsbh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtjvgfwhai.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtwzxtufoj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtakpgxtgi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.smart0.xyz/Article/details/gtcnnysjdy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyafqpbd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtnsuwlwrt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj202588.top/Article/details/gtdfjiobio.html

Py:   pickle.dumps(obj)
来源：http://dali.chenlongwang.top/Article/details/gtjxqpafbq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.kuanghao11.cn/Article/details/gtquttpobr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gtoxnevsjt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gttmwvdyvw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.c1oappe.top/Article/details/gteuodyqyx.html

Go:   encoding/gob
来源：http://dali.zdqjudy.top/Article/details/gtxkdecuzo.html

Ruby: Marshal.dump(obj)
来源：http://dali.ppjwa.cn/Article/details/gtryrsrfki.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtvkrssbmb.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtbgjsexyf.html

L. 网络请求
来源：http://dali.tianlin.xyz/Article/details/gtxpqhfoiv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtunoslngm.html

[L01] 发送 GET 请求
来源：http://dali.sufxvd.cn/Article/details/gtmwkqmiuj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.quarkkingdee.top/Article/details/gtdafylced.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tanke756.top/Article/details/gtcwuxfrcd.html

JS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtltozqmrm.html

TS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtpavzqrfh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yangfankeji.com/Article/details/gtqknyvfxw.html

Go:   resp, err := http.Get(url)
来源：http://dali.shangyingyoupin.top/Article/details/gthownnjvu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guannengcc.top/Article/details/gtnechflwr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gtveuuvkhr.html

[L02] 发送 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtxarjkkaj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gthusgtjad.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hysaishi.cn/Article/details/gtqcvnydxc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gtrhhgizqo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gtoxdnciyx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sweek.top/Article/details/gtimspmxoq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jiagoushi.top/Article/details/gtcsfefuzy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.meibo888.top/Article/details/gtjkorjflh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuanzhike.top/Article/details/gtmtgrgyya.html

[L03] 设置自定义请求头
来源：http://dali.shangyingyoupin.top/Article/details/gtjcjkrqcf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxuanxn.top/Article/details/gtndibiqnh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hysaishi.cn/Article/details/gtogshgzir.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtmlbjfpxi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtrgawphte.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gtwvevennb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gtsnguqcul.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dashuyun.cn/Article/details/gtocryvxku.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtrdimmcrg.html

[L04] 设置超时
来源：http://dali.hnxiangtu.top/Article/details/gtnwevneml.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gogol.net.cn/Article/details/gtvmoiocsr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tianlin.xyz/Article/details/gtfjijzlds.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gtrumcwxkp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gtosvjejms.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.redwolf501.top/Article/details/gtgssferuq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aizwys.cn/Article/details/gtoeqosdca.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yonumen.top/Article/details/gtfjkrpank.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hammf.cn/Article/details/gtxlxdhazb.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gtdqgyzfcy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yueranfly.top/Article/details/gtgkwrkxmc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hysaishi.cn/Article/details/gtvfahlila.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gttmcmufxf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtlzzqxsyj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yueranfly.top/Article/details/gtzmuyistg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cheryme.top/Article/details/gtrtfypupw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pengpengdd.cyou/Article/details/gtlqwkikdl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtdrbbebnf.html

[L06] 解析响应为 JSON
来源：http://dali.sufxvd.cn/Article/details/gtildvuxgs.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gtnmybogdn.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gtrgttdpzb.html

JS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gtpzwvwrey.html

TS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtcxssupdc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtrqhrtdvd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnqzz.top/Article/details/gtqbkwchfm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aibaodan.cn/Article/details/gtlkcgoozh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hysaishi.cn/Article/details/gtpdnjcwmj.html

[L07] 处理 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gtqqqmkvrf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jlsjyb.cn/Article/details/gtzyunzgtv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sysykeji.top/Article/details/gtympdldfs.html

JS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtahquxtgi.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtzbwfhcwp.html

Java: resp.statusCode()
来源：http://dali.yanxiufei.cn/Article/details/gtwatdlhsj.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtbazlwrth.html

Ruby: resp.code.to_i
来源：http://dali.hammf.cn/Article/details/gtknzlsrtu.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gtvtsypdjr.html

[L08] 并发请求多个地址
来源：http://dali.snrcjt.cn/Article/details/gtkkodgqmg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gtbguoauys.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuxming.cn/Article/details/gtncbhcndx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtehescdjf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtfbmqtnaw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gtkeccnitw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sweek.top/Article/details/gtoinbfxia.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hammf.cn/Article/details/gtxzrbeuiw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.redwolf501.top/Article/details/gtdmzeujuy.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtucousjis.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gtafbzhpxo.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtaskmnqnz.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtablmqyds.html

Py:   sys.argv[1:]
来源：http://dali.gzhubu.top/Article/details/gtejjdxrto.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gtvevhhwxk.html

JS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gthjrmuwvn.html

TS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gtyzrsdjay.html

Java: args 数组（main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtkbbekkiw.html

Go:   os.Args[1:]
来源：http://dali.jiagoushi.top/Article/details/gtsrecxgxw.html

Ruby: ARGV
来源：http://dali.gaohongyu789.top/Article/details/gtbaybogel.html

C#:   args 数组（Main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtocmtbkvv.html

[M02] 读取环境变量
来源：http://dali.xylfe.cn/Article/details/gthpgrlvjn.html

Py:   os.environ.get("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtuahnfimv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtknialmyr.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gtmenvgphs.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtromjezfw.html

Java: System.getenv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtkpwknozt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gthmljzoco.html

Ruby: ENV["HOME"]
来源：http://dali.hnqzz.top/Article/details/gtjzpyeuzf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.c1oappe.top/Article/details/gtxbnyiuet.html

[M03] 执行外部命令
来源：http://dali.jlsjyb.cn/Article/details/gtoltzcivm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jianghu66.top/Article/details/gtilaryqda.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gtargxavjt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfubiofvr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtqvavwgnz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangdashe.top/Article/details/gtbxgrfxhs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gtxfhshjfr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gtzpwijrlw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuetiantiany.cn/Article/details/gtjuqbbqjw.html

[M04] 获取当前工作目录
来源：http://dali.ivvv.top/Article/details/gttczgeuyb.html

Py:   os.getcwd()
来源：http://dali.xziqi.cn/Article/details/gtududelve.html

PHP:  getcwd();
来源：http://dali.yanxiufei.cn/Article/details/gtkyxfdgaa.html

JS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtttyybnmt.html

TS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gtrqbhvteb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zycfv.cn/Article/details/gtahzxnted.html

Go:   os.Getwd()
来源：http://dali.yj20258888.top/Article/details/gtcqlauuqx.html

Ruby: Dir.pwd
来源：http://dali.ehwqpu.com/Article/details/gtjtcrluhs.html


<!-- 参考信息 -->