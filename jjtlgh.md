代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.svipenyu.cn/Article/details/gtiktqfyhq.html

TS:   /error/gim
来源：http://dali.haohaochexian.top/Article/details/gtasqqznuk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gzhubu.top/Article/details/gttpsagywz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hfpthk.cn/Article/details/gtoqklenkk.html

Ruby: s.scan(/error/i)
来源：http://dali.kuanghao11.cn/Article/details/gtrxkgcecr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhoulong.xyz/Article/details/gtzdzqlraq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.0kj1m.cn/Article/details/gtaftmvixm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtokuvxp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtchkrrqbn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtatngxosk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtgtccdehh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gtegcgckfo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dashuyun.cn/Article/details/gtmeitqevv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.smart0.xyz/Article/details/gtamzmrihk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtkszakmki.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtxzjqgldn.html

J. 日期与时间
来源：http://dali.yvedp.cn/Article/details/gtrqucwonh.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtbcxjqeth.html

[J01] 获取当前时间
来源：http://dali.ppjwa.cn/Article/details/gtabytdcvm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daria6918.cn/Article/details/gtryuzizuy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gtieidlxsc.html

JS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtemvgkvbe.html

TS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtgrxzhddc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hywenlv.cn/Article/details/gtzcwktztw.html

Go:   time.Now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjmokvsu.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gtwjehrhor.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yanxiufei.cn/Article/details/gtsewsfomv.html

[J02] 格式化输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlozqusdb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gtrmkeppat.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gttbbishys.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.snrcjt.cn/Article/details/gtsmxpnqmh.html

TS:   d.toISOString()
来源：http://dali.yj202588.top/Article/details/gtlptssdbc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gtxxmzxqyt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj202588.top/Article/details/gttsncmwrq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gtnxixynoq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gtmeltciho.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gthyqxlggf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gtoapikhdv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.havefunace.top/Article/details/gtcotjcatt.html

JS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtoucxeolv.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfwbhfma.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtyqmxpmgr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkghljkql.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtgtfzrsix.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gtvgxqxqef.html

[J04] 时间戳与日期互转
来源：http://dali.quarkkingdee.top/Article/details/gtakpxkufb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yangfankeji.com/Article/details/gtyxyomllb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.birdmap.top/Article/details/gtbrqzefbp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gtwwshgzik.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgufenzy.top/Article/details/gthepbylro.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gtsdfbgnlt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtsrmwqxgh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjaustopm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gtylvheuvh.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhengqikj.top/Article/details/gtmgvhptxr.html

Py:   now + timedelta(days=7)
来源：http://dali.cdnleiting.top/Article/details/gttryvkcmu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.smart0.xyz/Article/details/gtjltbtmcn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gtpfjpqahs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gthbpxkuqe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gtcltlklzg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xylfe.cn/Article/details/gtswhlgiuz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yvedp.cn/Article/details/gtmkywvqsd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.iojbl.cn/Article/details/gtcycsjypu.html

[J06] 计算两时间之差
来源：http://dali.gotoacloud.top/Article/details/gtfflnekee.html

Py:   (end - start).total_seconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtnsnyhhsk.html

PHP:  $end->diff($start)->days;
来源：http://dali.aizwys.cn/Article/details/gttyjsascs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinghuilouyu.cn/Article/details/gtepwclovt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.svipenyu.cn/Article/details/gttqgmgozo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.svipenyu.cn/Article/details/gttfescjjf.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqrzpntb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tian-w.cn/Article/details/gtgygctzhc.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gtzfevptdh.html

[J07] 比较两个日期
来源：http://dali.chenjidiqi.icu/Article/details/gtbxpbxywf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtotovguva.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gtskyzvyez.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gtfcfrxeye.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gtgkkxhrph.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwjntvez.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tianlin.xyz/Article/details/gtiqtbwfev.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtitvbqyvh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtiioowmwq.html

[J08] 提取年月日与星期
来源：http://dali.gzhubu.top/Article/details/gtfoeddzkw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigufen.top/Article/details/gtoipnaxpo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuxming.cn/Article/details/gtahwnvybl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yongpay.top/Article/details/gtlsspyddv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.bjfxy.top/Article/details/gtnyhkgbmn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cashguo.top/Article/details/gtcqmadmln.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenjidiqi.icu/Article/details/gtepnwjahj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gtleentspj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gtjgarbnvs.html

[J09] 时区处理
来源：http://dali.cqqwz.cn/Article/details/gtwlpywgkp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxuanxn.top/Article/details/gtstuknnex.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tian-w.cn/Article/details/gtmtjphukm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtvfeljqwb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtzerqrmqk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daxiang520.top/Article/details/gtenbseimf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgfzy.top/Article/details/gtrxxvvcwm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hfpthk.cn/Article/details/gtvorgeuve.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrtibeuz.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhoulong.xyz/Article/details/gtwzudsajg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hongshengwenyu.top/Article/details/gtucixbmel.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sysykeji.top/Article/details/gtfcvnnvds.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuxming.cn/Article/details/gtuuvgkqos.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jianghu66.top/Article/details/gtxvyaefpj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgfzy.top/Article/details/gtqloyymbb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuetiantiany.cn/Article/details/gtjmxdlerg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.andypj.xyz/Article/details/gtiidfnyhf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtfhgeqkle.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxhhxsss.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gtgxkapall.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtssqafmqw.html

[K01] 对象转 JSON 字符串
来源：http://dali.jlsjyb.cn/Article/details/gtpjytydlv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gtureyyzbu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtbwiepgqu.html

JS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gtedppfvbf.html

TS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gtjufkvqzz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgfzy.top/Article/details/gthyzxcvdz.html

Go:   json.Marshal(obj)
来源：http://dali.tian-w.cn/Article/details/gtbtjsughs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrymqpys.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.redwolf501.top/Article/details/gtckmmuruf.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gtjkehbacp.html

Py:   json.loads(s)
来源：http://dali.tian-w.cn/Article/details/gtcmvsqsxn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dashuyun.cn/Article/details/gtxtbrtfph.html

JS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtuhikzfrq.html

TS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtfxbyfoer.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtxfbcvaxe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjzgcvoy.html

Ruby: JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtaxmnqxhb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigfzy.top/Article/details/gtrkaktlhb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.0kj1m.cn/Article/details/gttagtiqjv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtqkscgrwg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gtsxpsshdk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gteeyafcci.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gthiukflsm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtxczjqbui.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guowangkeji.top/Article/details/gtbgejeqia.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtvureirht.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhixingplan.top/Article/details/gtvkdyatvp.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gtkqzdheqt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ppjwa.cn/Article/details/gtqmyueyjg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gtqcwkzixe.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gthejxewsr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gtowgcazzg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtyvreolnd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gtbsuvicng.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtlqxqbtxk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtoenmiujp.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gtisbejaey.html

Py:   copy.deepcopy(obj)
来源：http://dali.guannengcc.top/Article/details/gteckgturi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dashuyun.cn/Article/details/gtlfkpafzt.html

JS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtnhjwhasg.html

TS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtcyoczjih.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gtqfkhafqd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cqqwz.cn/Article/details/gtpwygzges.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnqzz.top/Article/details/gtvnjrmasb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.9152youxi.cn/Article/details/gtuzsviwff.html

[K06] 解析 URL 查询串
来源：http://dali.jianghu66.top/Article/details/gtcwdohhqr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jianghu66.top/Article/details/gtgraertyl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cheryme.top/Article/details/gtgwcsrkiv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gtoulqivvm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gtiqjapijm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.bjfxy.top/Article/details/gtwubifihp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtarnweauc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzycdtydu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtdkbcyxkz.html

[K07] 进制转换
来源：http://dali.shangyingyoupin.top/Article/details/gthlvhzaea.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtsrthpwau.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258888.top/Article/details/gtztykjted.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtvprgniip.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtkgxrsbme.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtsuxzzdnf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hammf.cn/Article/details/gtcobjbfkn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuanzx.com/Article/details/gtoxrtdwck.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtrpaivxaa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aibaodan.cn/Article/details/gtrsibsyue.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtmzhhlmyy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fengsongda.top/Article/details/gtylenlrmm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtzocttnpz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gtgulbjckc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gtavvceoft.html

Go:   encoding/gob
来源：http://dali.bjfxy.top/Article/details/gthjddlkef.html

Ruby: Marshal.dump(obj)
来源：http://dali.jiagoushi.top/Article/details/gtdsndcuaf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.316326.xyz/Article/details/gtaevtmpmg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtlqvbbfct.html

L. 网络请求
来源：http://dali.zycfv.cn/Article/details/gthdexxcvd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtrdhvbpsm.html

[L01] 发送 GET 请求
来源：http://dali.tian-w.cn/Article/details/gtsitwmnsa.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenlongwang.top/Article/details/gtkhpewbju.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tian-w.cn/Article/details/gttptvgxih.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskdsdyof.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtawgdawhr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnxiangtu.top/Article/details/gthkocudww.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gtyryqwaht.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.quarkkingdee.top/Article/details/gtowmllkqj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj202588.top/Article/details/gtgntyjjht.html

[L02] 发送 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtwhmptnsh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuxming.cn/Article/details/gtsrfxcteq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ybcxt.top/Article/details/gtzscdotip.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gtbzsmmoqc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gtaaxqptip.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nwbrower.top/Article/details/gtnwbxpwps.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gtqizpmjqi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxinkj.top/Article/details/gtbjhnhxnv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tianlin.xyz/Article/details/gtdscufjxw.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gthfuhzsmu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.svipenyu.cn/Article/details/gtitbqvktp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvusotps.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gtrvjsvxyv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtfuoutvvl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cqqwz.cn/Article/details/gtoutluydd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gteeukrisz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhixingplan.top/Article/details/gtfkapgpis.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gtnseouxvq.html

[L04] 设置超时
来源：http://dali.shuidangran.top/Article/details/gtrwtykgmw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.9152youxi.cn/Article/details/gtvkeoqonk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jiagoushi.top/Article/details/gtyfniexbl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtqkzrqyda.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gtshhecqgh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gtkuhcjpos.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yvedp.cn/Article/details/gtttgqshsl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhoulong.xyz/Article/details/gtuswzydjg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yvedp.cn/Article/details/gtgckopmah.html

[L05] 上传文件（multipart）
来源：http://dali.shangyingyoupin.top/Article/details/gtcnsazoac.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yonumen.top/Article/details/gtowrabpbx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gtpumgtjll.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gtmitcvako.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gtpdjqmxan.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daria6918.cn/Article/details/gtnlutezat.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258888.top/Article/details/gtvjzmlcbi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.c1oappe.top/Article/details/gtbtdmmaow.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvahacxp.html

[L06] 解析响应为 JSON
来源：http://dali.xziqi.cn/Article/details/gtdqvrdnzh.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gtymihfbhm.html

PHP:  json_decode($body, true);
来源：http://dali.zycfv.cn/Article/details/gtzmnczlmp.html

JS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gtklcyunpa.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtwivlbtib.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtxcolrgle.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gtrknkmmkd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.c1oappe.top/Article/details/gtgsgvweck.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tianlin.xyz/Article/details/gtyytxkadn.html

[L07] 处理 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gtbawstbtz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xziqi.cn/Article/details/gtymfonrhv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.andypj.xyz/Article/details/gtbafpyeyo.html

JS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gtkfdgjgxn.html

TS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gtthspwyuk.html

Java: resp.statusCode()
来源：http://dali.chenjidiqi.icu/Article/details/gtmsrivxtr.html

Go:   resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gtdcrvlili.html

Ruby: resp.code.to_i
来源：http://dali.ybcxt.top/Article/details/gtnvrkvxem.html

C#:   (int)resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gttxfkctcj.html

[L08] 并发请求多个地址
来源：http://dali.kuanghao11.cn/Article/details/gtevsxtrwi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gtbnkbhbek.html

PHP:  curl_multi_init() 系列
来源：http://dali.nwbrower.top/Article/details/gtmznwivgq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtofhjadwd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtcnrhnufa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ivvv.top/Article/details/gtzzsaoeag.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtqnoxhw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtrtypopmw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gtefdyoklu.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtqmzwnifw.html

M. 命令行 / 进程 / 环境
来源：http://dali.tian-w.cn/Article/details/gtrbrmyosu.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtphcsolgo.html

[M01] 读取命令行参数
来源：http://dali.sysykeji.top/Article/details/gtsdhhiwkk.html

Py:   sys.argv[1:]
来源：http://dali.hywenlv.cn/Article/details/gtjmwkecus.html

PHP:  $argv;  $argc;
来源：http://dali.tianlin.xyz/Article/details/gtaubfvldk.html

JS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtrynepnsx.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtzbgraltp.html

Java: args 数组（main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtdheejshx.html

Go:   os.Args[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtjcjhucac.html

Ruby: ARGV
来源：http://dali.jiagoushi.top/Article/details/gtinltomtw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyjywsdy.html

[M02] 读取环境变量
来源：http://dali.smart0.xyz/Article/details/gtfoznapnx.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gtngpxikyr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gthrswjkfx.html

JS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gtajzjltbh.html

TS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gtssonqtca.html

Java: System.getenv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtwjcydmfk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtmofovgov.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gtllfdptle.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxwhibww.html

[M03] 执行外部命令
来源：http://dali.smart0.xyz/Article/details/gthtshigmi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fengsongda.top/Article/details/gtqrxqeile.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gtitqyboes.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxibtunjn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtpdatrihd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gtguakmidf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gtxsjfnvva.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gtcfubkbkk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shuidangran.top/Article/details/gtxoomnvtc.html

[M04] 获取当前工作目录
来源：http://dali.yvedp.cn/Article/details/gtbbdkotqg.html

Py:   os.getcwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtukdtezet.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gttcrxguwe.html

JS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtmjcqsnml.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gtknhiozbb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yueranfly.top/Article/details/gtjcozgaja.html

Go:   os.Getwd()
来源：http://dali.yonumen.top/Article/details/gtcnwvxdns.html

Ruby: Dir.pwd
来源：http://dali.xinyue.icu/Article/details/gtkpfsmkey.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdvfgbru.html

[M05] 设置退出码
来源：http://dali.nanxinkj.top/Article/details/gtvuooviwk.html

Py:   sys.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtyiqaxzrf.html

PHP:  exit(1);
来源：http://dali.xylfe.cn/Article/details/gtzrhywhlh.html


<!-- 参考信息 -->