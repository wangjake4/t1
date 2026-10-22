代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gt2qlsiqowa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sweek.top/Article/details/gt2flgbtcgf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sufxvd.cn/Article/details/gt2gfggshox.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuanzx.com/Article/details/gt2xtywpgcv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gt2ytvkevcq.html

[I07] 忽略大小写与多行模式
来源：http://dali.ivvv.top/Article/details/gt2ecopwtzg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuanzhike.top/Article/details/gt2wmxvexqq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fupiyyrh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhixingplan.top/Article/details/gt2vqfobzus.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gt2slvkypqv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hywenlv.cn/Article/details/gt2cximakzz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dianchejie.cn/Article/details/gt2dkkcoiru.html

Ruby: s.scan(/error/i)
来源：http://dali.yuanzhike.top/Article/details/gt2shyawupf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ppjwa.cn/Article/details/gt2yndnpbax.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.birdmap.top/Article/details/gt2xdoknkso.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhoulong.xyz/Article/details/gt2fewrixpk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gt2balankct.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gt2hgfxgsxn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gt2khnspkit.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gt2jjtluqnl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrrmuao.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tianlin.xyz/Article/details/gt2kbvckczx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jisoximd.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2sulmtrmn.html

J. 日期与时间
来源：http://dali.yj202588.top/Article/details/gt2tfrraryq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2gkireblc.html

[J01] 获取当前时间
来源：http://dali.daria6918.cn/Article/details/gt2kwytxgoz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.0kj1m.cn/Article/details/gt2fhthsdcf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gt2vutarvob.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gt2pwnsapvx.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gt2kjyeukpw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnqzz.top/Article/details/gt2hbwozifr.html

Go:   time.Now()
来源：http://dali.xinyue.icu/Article/details/gt2gvsdikvp.html

Ruby: Time.now
来源：http://dali.tanke756.top/Article/details/gt2nsjxbdhe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gt2csbwpedu.html

[J02] 格式化输出
来源：http://dali.xinyue.icu/Article/details/gt2nodjdaqs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gt2dxhoisia.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gt2tpetruhl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.bjfxy.top/Article/details/gt2hevhfscq.html

TS:   d.toISOString()
来源：http://dali.cqqwz.cn/Article/details/gt2akuereer.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.vqdsnc.cn/Article/details/gt2pzoudrdc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sxryk.cn/Article/details/gt2vkyawkus.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gt2gjnyqsuy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.bjfxy.top/Article/details/gt2qvlrvqvw.html

[J03] 字符串解析为日期
来源：http://dali.zdqjudy.top/Article/details/gt2vfsgpncm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuanzx.com/Article/details/gt2ngjpmeeh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258888.top/Article/details/gt2kqgdxxge.html

JS:   new Date("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2yfwnlwwz.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2uxxtniwh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2qjclpwcz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2qxmsarzj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2ijsnywhq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.meibo888.top/Article/details/gt2sfajxxem.html

[J04] 时间戳与日期互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ilgncolf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2jkrssbpl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sxryk.cn/Article/details/gt2bhmqzqyz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ybcxt.top/Article/details/gt2zjakfkfn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shuidangran.top/Article/details/gt2wlsfavyo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.havefunace.top/Article/details/gt2dlewnvsg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tmuhkqgo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2dkphnprx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gt2srymtyow.html

[J05] 时间加减（加 7 天）
来源：http://dali.ehwqpu.com/Article/details/gt2bewlxyxd.html

Py:   now + timedelta(days=7)
来源：http://dali.9152youxi.cn/Article/details/gt2nnlqcizx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sufxvd.cn/Article/details/gt2busobufx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gt2qxtqraoy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gt2hxjfvols.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nwbrower.top/Article/details/gt2yovzhzbh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guannengcc.top/Article/details/gt2ciuagjmt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zycfv.cn/Article/details/gt2xuejnwiw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gt2rhtzvmea.html

[J06] 计算两时间之差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gaimlxzu.html

Py:   (end - start).total_seconds()
来源：http://dali.mhx1999.top/Article/details/gt2zxhnkkzc.html

PHP:  $end->diff($start)->days;
来源：http://dali.guannengcc.top/Article/details/gt2bjducwla.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aizwys.cn/Article/details/gt2jaopcrkh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pengpengdd.cyou/Article/details/gt2ofomhhyl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.svipenyu.cn/Article/details/gt2frqstzji.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxinkj.top/Article/details/gt2msunvqrl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hfpthk.cn/Article/details/gt2wznwtmca.html

C#:   (end - start).TotalSeconds
来源：http://dali.hammf.cn/Article/details/gt2txairftd.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gt2eqapgyxq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2fvilkwar.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gt2drbxuywm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gt2krtfqmfi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gt2rzdporqv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xziqi.cn/Article/details/gt2axizintq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhoulong.xyz/Article/details/gt2wrxfqfxb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gt2dqnhvvoq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gt2jfdwxhks.html

[J08] 提取年月日与星期
来源：http://dali.gogol.net.cn/Article/details/gt2cqvsmifw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenlongwang.top/Article/details/gt2buudzrea.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hongshengwenyu.top/Article/details/gt2uldorqsp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sxryk.cn/Article/details/gt2eyeidmxi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jlsjyb.cn/Article/details/gt2nnxhsllr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gt2uoubzawg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.smart0.xyz/Article/details/gt2uszeptmh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gt2eidddqsa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ppjwa.cn/Article/details/gt2vppxfwvy.html

[J09] 时区处理
来源：http://dali.guowangkeji.top/Article/details/gt2smmnqdke.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yangfankeji.com/Article/details/gt2xfghkntz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cashguo.top/Article/details/gt2ojrlgvtt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gt2vbsydjij.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gt2mxsswkan.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigfzy.top/Article/details/gt2agjkmqyz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fengsongda.top/Article/details/gt2ydepygyy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258.top/Article/details/gt2tbjuchya.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gt2mxyiplvs.html

[J10] 取今天 / 本月第一天
来源：http://dali.cheryme.top/Article/details/gt2bqkzihdm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2elubvehw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jlsjyb.cn/Article/details/gt2nijdnmck.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2uhypllft.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yvedp.cn/Article/details/gt2bsxzosgp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2losxsqzl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258888.top/Article/details/gt2pyfnbexj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ybcxt.top/Article/details/gt2jvzzgnfj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dashuyun.cn/Article/details/gt2ktflohxn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2jzbcqctq.html

K. JSON 与序列化
来源：http://dali.tianlin.xyz/Article/details/gt2nccztknj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2hadllauv.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnqzz.top/Article/details/gt2eyqjgddv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gt2muoshwux.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gt2toamgxnv.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2kruwzfdk.html

TS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2otelzlxv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gt2pmrtsepp.html

Go:   json.Marshal(obj)
来源：http://dali.wangdashe.top/Article/details/gt2detnzlru.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vjnyiwmo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ydzc1.top/Article/details/gt2ddickkvn.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gt2wxwosove.html

Py:   json.loads(s)
来源：http://dali.cdnleiting.top/Article/details/gt2apoufkdl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.andypj.xyz/Article/details/gt2xhfwppcl.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2zdqhswko.html

TS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2hvvahvjw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2gyhxgbzo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gt2saitsapj.html

Ruby: JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2xdmtkxgp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gzhubu.top/Article/details/gt2veolohww.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xylfe.cn/Article/details/gt2xytcrxqa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gt2lwvazwfp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gt2xyrkwrvr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gt2bujhtvby.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gt2rgjplijw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gt2egrwbhuw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2umshzqic.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fengsongda.top/Article/details/gt2vapvkgqs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.snrcjt.cn/Article/details/gt2qyygmywn.html

[K04] 读取 JSON 文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gamszits.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gt2gngatgib.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cdnleiting.top/Article/details/gt2ybpcexwr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gt2xoueuzkn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2vqlqyzpw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gt2rydmyuvn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gt2gnqosimr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qucpbxoc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gt2hcukfuvp.html

[K05] 深拷贝对象
来源：http://dali.yueranfly.top/Article/details/gt2tinqkrkt.html

Py:   copy.deepcopy(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2gvjqpwsb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nwbrower.top/Article/details/gt2vmcpmrvz.html

JS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2exxpgjgx.html

TS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2pmcgvwhr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.birdmap.top/Article/details/gt2canihiie.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gt2qejlbeio.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gt2azizbisr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tanke756.top/Article/details/gt2davxotep.html

[K06] 解析 URL 查询串
来源：http://dali.9152youxi.cn/Article/details/gt2gzgdiepa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gt2gipnqidt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gt2idxtdcsb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gt2dfzcyfxu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gt2nxopemvs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gt2cosmgzim.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2ufcqglxx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2hqiftbgj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gt2bkeyncbj.html

[K07] 进制转换
来源：http://dali.yj20258888.top/Article/details/gt2hfjjhwvd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2elnnqbyl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgufenzy.top/Article/details/gt2jhzmgcgu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2qhdjmjdw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2vakvfbng.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2zmbcikmw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxuanxn.top/Article/details/gt2uijonvcm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.quarkkingdee.top/Article/details/gt2nbfluhgt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndqmckhu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jyoumei.cn/Article/details/gt2luipazpf.html

Py:   pickle.dumps(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2qqsrwufi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnqzz.top/Article/details/gt2pyrckjca.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gt2jfblzvsm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gt2jdwrokbu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghphhehj.html

Go:   encoding/gob
来源：http://dali.cqqwz.cn/Article/details/gt2drglwfuh.html

Ruby: Marshal.dump(obj)
来源：http://dali.zycfv.cn/Article/details/gt2bobcawcq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gt2jyhffaxb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2dcunnhps.html

L. 网络请求
来源：http://dali.kuanghao11.cn/Article/details/gt2vmucwufw.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2xqobrajd.html

[L01] 发送 GET 请求
来源：http://dali.0kj1m.cn/Article/details/gt2hbfiodjc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fengsongda.top/Article/details/gt2xkwmvcjc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gt2igmcjatb.html

JS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gt2gjgpiuwp.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gt2xfnduief.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xziqi.cn/Article/details/gt2ihuyttrt.html

Go:   resp, err := http.Get(url)
来源：http://dali.meibo888.top/Article/details/gt2xxbqtowq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnxiangtu.top/Article/details/gt2orzcfaek.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenzaomai.com/Article/details/gt2ipbgjrxv.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gt2uokeagrt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.bjfxy.top/Article/details/gt2taomdens.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xziqi.cn/Article/details/gt2ycvfpkqn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gt2tcwsgzps.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gt2akwedjhp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxinkj.top/Article/details/gt2blpilvoj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ppjwa.cn/Article/details/gt2qwawpdfn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhiwuduotai.top/Article/details/gt2bpysmygx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nwbrower.top/Article/details/gt2lwlgdkhw.html

[L03] 设置自定义请求头
来源：http://dali.shangyingyoupin.top/Article/details/gt2sklilgsb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigufen.top/Article/details/gt2mdldadpd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2fwixpmfe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gt2dwjsbzdh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2olxoukad.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ujazzvsu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gt2vxuuthvn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnxiangtu.top/Article/details/gt2nfxtilfg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gt2tohurqfk.html

[L04] 设置超时
来源：http://dali.xylfe.cn/Article/details/gt2svpfjeju.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dianchejie.cn/Article/details/gt2aftljztu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jlsjyb.cn/Article/details/gt2zqigozfh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gt2yphxdkoj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gt2cibizfom.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.haohaochexian.top/Article/details/gt2evxapbgh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gt2xwpwhhva.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yanxiufei.cn/Article/details/gt2enlgotkv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgufenzy.top/Article/details/gt2yevsbzjl.html

[L05] 上传文件（multipart）
来源：http://dali.cheryme.top/Article/details/gt2kcjkhfgz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhengqikj.top/Article/details/gt2fyizgvlg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yangfankeji.com/Article/details/gt2utczfeak.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gt2numzkfmy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gt2qdbxmqpm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yangfankeji.com/Article/details/gt2uowtvmxj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tanke756.top/Article/details/gt2ujwygciw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenzaomai.com/Article/details/gt2tfqenknu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2pcekfczw.html

[L06] 解析响应为 JSON
来源：http://dali.yuanzhike.top/Article/details/gt2smrgczla.html

Py:   resp.json()
来源：http://dali.0kj1m.cn/Article/details/gt2jgjspiak.html

PHP:  json_decode($body, true);
来源：http://dali.nwbrower.top/Article/details/gt2jxtljnjx.html

JS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gt2bmfgbeav.html

TS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2smrcboko.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gzhubu.top/Article/details/gt2khqiptss.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenjidiqi.icu/Article/details/gt2puuygizk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuanzx.com/Article/details/gt2spyliwqd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xylfe.cn/Article/details/gt2qimbglzp.html

[L07] 处理 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gt2egftrmtk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hywenlv.cn/Article/details/gt2issbsaxz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj202588.top/Article/details/gt2jqqidozc.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gt2mbzqdjnj.html

TS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gt2hlzyedmy.html

Java: resp.statusCode()
来源：http://dali.sysykeji.top/Article/details/gt2czcqpbio.html

Go:   resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gt2mmrnugpj.html

Ruby: resp.code.to_i
来源：http://dali.shzxlz.cn/Article/details/gt2sgsijjzo.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gt2igoexezg.html

[L08] 并发请求多个地址
来源：http://dali.sufxvd.cn/Article/details/gt2bgojuwgh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.birdmap.top/Article/details/gt2rkqmbcmr.html

PHP:  curl_multi_init() 系列
来源：http://dali.guannengcc.top/Article/details/gt2atzikjko.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2fxhjtchq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gt2evbmsics.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangdashe.top/Article/details/gt2uaofvjgc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shzxlz.cn/Article/details/gt2oilfebwh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pycfn.com/Article/details/gt2gpvnziwu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gt2oddifhly.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2hongifsw.html

M. 命令行 / 进程 / 环境
来源：http://dali.meibo888.top/Article/details/gt2rizsrxyu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2talnfecf.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gt2hjtykikj.html

Py:   sys.argv[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2velcltcm.html

PHP:  $argv;  $argc;
来源：http://dali.gotoacloud.top/Article/details/gt2jukgkvom.html

JS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gt2omyquoro.html

TS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gt2lrgubjzx.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gt2icnjuvbl.html

Go:   os.Args[1:]
来源：http://dali.pycfn.com/Article/details/gt2tstdzlti.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gt2fxgddrda.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gt2gxswenjv.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gt2rnreocfq.html

Py:   os.environ.get("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gekdnhqd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gt2zcmmkopp.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gt2qejssmeg.html

TS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gt2cpyyhboj.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jjqxsxxh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2riajetxp.html

Ruby: ENV["HOME"]
来源：http://dali.quarkkingdee.top/Article/details/gt2zaijbdxf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gt2uykxnyrh.html

[M03] 执行外部命令
来源：http://dali.zhengqikj.top/Article/details/gt2cxghrfaa.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ydzc1.top/Article/details/gt2pznkyhuy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sweek.top/Article/details/gt2gzotbthr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2xmophagw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2lpxdwkqn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yangfankeji.com/Article/details/gt2johveekx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cqqwz.cn/Article/details/gt2wwaragub.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jianghu66.top/Article/details/gt2emywsudf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gt2dgwfzvij.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gt2mlffyybb.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gt2nlelekli.html

PHP:  getcwd();
来源：http://dali.nanxinkj.top/Article/details/gt2ccnwbqti.html

JS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gt2gbdrzjme.html


<!-- 参考信息 -->