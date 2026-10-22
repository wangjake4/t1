代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.shuidangran.top/Article/details/gt2zdqqpach.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gt2abscagtk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dianchejie.cn/Article/details/gt2lvpcnfky.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yanxiufei.cn/Article/details/gt2nzqbqzkq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gt2ndaiouho.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gt2tbxckaua.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gt2alsygbsd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gt2abiginge.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.haohaochexian.top/Article/details/gt2hcyvxume.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.quarkkingdee.top/Article/details/gt2drmbglnk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gt2zhmeuzoj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2dzwbxlll.html

J. 日期与时间
来源：http://dali.havefunace.top/Article/details/gt2bimnlyst.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2fggcuxng.html

[J01] 获取当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2jrcfszpd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gt2pjgwsljf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gt2kbzdpluu.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gt2ptrbqyux.html

TS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gt2vomtufli.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2koufyobv.html

Go:   time.Now()
来源：http://dali.xinyue.icu/Article/details/gt2zjorhbvn.html

Ruby: Time.now
来源：http://dali.0kj1m.cn/Article/details/gt2gvefoics.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yvedp.cn/Article/details/gt2dopgcxhx.html

[J02] 格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2rcbnbbwm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gt2bsxgzcmw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hkyuvrhe.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gt2zehumsya.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gt2hrqletwb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hysaishi.cn/Article/details/gt2pkwljcrh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258888.top/Article/details/gt2ckrbsdbm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gt2fqlmfhwr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.svipenyu.cn/Article/details/gt2emyxasdb.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gt2derciehw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fengsongda.top/Article/details/gt2ptqcerkb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenjidiqi.icu/Article/details/gt2isbuprvd.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2kimpnssr.html

TS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2jarwcfsv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2uyxqmvbp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2ellrvmqd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2nvjkeuvq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xkiwczbm.html

[J04] 时间戳与日期互转
来源：http://dali.hongshengwenyu.top/Article/details/gt2usmzipqx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2nciqkrpt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenzaomai.com/Article/details/gt2gsovgxkf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tianlin.xyz/Article/details/gt2dbiopvdv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.andypj.xyz/Article/details/gt2gkgpaueq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ivvv.top/Article/details/gt2pkxmfgmn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2drruxjyu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yueranfly.top/Article/details/gt2vczyynws.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2lwmigahk.html

[J05] 时间加减（加 7 天）
来源：http://dali.ydzc1.top/Article/details/gt2biufxfmc.html

Py:   now + timedelta(days=7)
来源：http://dali.gogol.net.cn/Article/details/gt2ggykonjg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2jllgddfa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gt2soeuhakf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gt2djaqagzd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuxming.cn/Article/details/gt2dythawja.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenzaomai.com/Article/details/gt2mldedjkx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gt2qiafvedn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangdashe.top/Article/details/gt2yahxdcjf.html

[J06] 计算两时间之差
来源：http://dali.zdqjudy.top/Article/details/gt2livokayv.html

Py:   (end - start).total_seconds()
来源：http://dali.haohaochexian.top/Article/details/gt2vqrzcvga.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhixingplan.top/Article/details/gt2ufynznyx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hammf.cn/Article/details/gt2cwtoujfl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.snrcjt.cn/Article/details/gt2sfowbrpe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnxiangtu.top/Article/details/gt2vcyrylgu.html

Go:   end.Sub(start).Hours()
来源：http://dali.redwolf501.top/Article/details/gt2ixpfryjr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cashguo.top/Article/details/gt2csvyqgfe.html

C#:   (end - start).TotalSeconds
来源：http://dali.kuanghao11.cn/Article/details/gt2jyyzgocz.html

[J07] 比较两个日期
来源：http://dali.jianghu66.top/Article/details/gt2ggycmzdc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2vtlstigm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuxming.cn/Article/details/gt2huypagmh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gt2fsaekauw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gt2bmyumjlw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.iojbl.cn/Article/details/gt2fibvifxi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gt2wzygxqqp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gt2ajzgenxw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wrlarfqj.html

[J08] 提取年月日与星期
来源：http://dali.yuanzhike.top/Article/details/gt2xiqjzbld.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hammf.cn/Article/details/gt2zxhgrtxx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhoulong.xyz/Article/details/gt2zyqroqje.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sysykeji.top/Article/details/gt2qaslffwx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gt2morenkgt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guowangkeji.top/Article/details/gt2imxwphcq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sweek.top/Article/details/gt2mkswlhiz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.316326.xyz/Article/details/gt2iwobrqkj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gt2mamngptp.html

[J09] 时区处理
来源：http://dali.aibaodan.cn/Article/details/gt2lmwxewof.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yonumen.top/Article/details/gt2exiyzxbf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigfzy.top/Article/details/gt2btdxcnjt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gt2woyohhmj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gt2uzprhclb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bweooqio.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.snrcjt.cn/Article/details/gt2evjefsgf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dashuyun.cn/Article/details/gt2axcgkoxq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tian-w.cn/Article/details/gt2yuhjixmn.html

[J10] 取今天 / 本月第一天
来源：http://dali.yvedp.cn/Article/details/gt2bftvqtqs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhengqikj.top/Article/details/gt2nmcrqcuk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cucudq.cn/Article/details/gt2ibsjxcgi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2srapshhl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2hdsdrern.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gzhubu.top/Article/details/gt2czhgdmur.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2gjklspnr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hfkfayqa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.meibo888.top/Article/details/gt2pgmwcans.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2hapiiihk.html

K. JSON 与序列化
来源：http://dali.feifeiyinyue.top/Article/details/gt2jgtgdgqg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2ccxvnpfz.html

[K01] 对象转 JSON 字符串
来源：http://dali.yueranfly.top/Article/details/gt2kweizhsa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gt2yqjwgrzl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gt2gluvgpqy.html

JS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2dxdipxug.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2ryxymbdg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sekupxik.html

Go:   json.Marshal(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gkbojjyu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gt2uepcnktv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqhumdqn.html

[K02] JSON 字符串转对象
来源：http://dali.zhengqikj.top/Article/details/gt2zufewddr.html

Py:   json.loads(s)
来源：http://dali.jiagoushi.top/Article/details/gt2fhlmdjla.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xziqi.cn/Article/details/gt2davtioul.html

JS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2itmceesy.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gt2wubehwve.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuanzx.com/Article/details/gt2brflvibq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gt2edlsprau.html

Ruby: JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gt2heqlthik.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hywenlv.cn/Article/details/gt2cxtezfqw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fengsongda.top/Article/details/gt2emptpccj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxxaprg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2zjqwhblx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gt2ypmcuees.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2mdjpijic.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2kcbraosz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shzxlz.cn/Article/details/gt2cfrkitzl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sweek.top/Article/details/gt2pgppkqnk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zycfv.cn/Article/details/gt2nbwiispt.html

[K04] 读取 JSON 文件
来源：http://dali.snrcjt.cn/Article/details/gt2oqzaamvk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ehwqpu.com/Article/details/gt2fwcrjvsj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gaohongyu789.top/Article/details/gt2eoeqawdx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gt2zlxnpqvd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gt2tzdyfimn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gt2ddhipzik.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gt2japcazar.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nwbrower.top/Article/details/gt2ewhgyosy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gt2ofgtyuuy.html

[K05] 深拷贝对象
来源：http://dali.jianghu66.top/Article/details/gt2qlrrrndz.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtijecvu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenlongwang.top/Article/details/gt2oipifglf.html

JS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2rcbgtrpp.html

TS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gt2nspcwftp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gbfpzkjk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gt2sslxnexr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dianchejie.cn/Article/details/gt2xvmkoxie.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hammf.cn/Article/details/gt2hlczjkwc.html

[K06] 解析 URL 查询串
来源：http://dali.shuidangran.top/Article/details/gt2xyfqhpel.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gt2htqrrigx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hywenlv.cn/Article/details/gt2zxwgdcom.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gt2dopukbwx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gt2arizaxzm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yvedp.cn/Article/details/gt2uhypueih.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gt2ecyiipjc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gt2cudisxxx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ldvufdhe.html

[K07] 进制转换
来源：http://dali.iojbl.cn/Article/details/gt2bcmojyde.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2gknbcjak.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2irxphque.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2texhlxbs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2vrlbdgpd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2kmaechlf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.aibaodan.cn/Article/details/gt2beyuhcld.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vzvterfx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2drxnuthp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhongyouzk.top/Article/details/gt2jaqtiido.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2rvsxqfpq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fzsdglmq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gt2ctdggzuw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gt2uadwvjhi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gt2nampabqm.html

Go:   encoding/gob
来源：http://dali.dashuyun.cn/Article/details/gt2spkwvzjo.html

Ruby: Marshal.dump(obj)
来源：http://dali.yonumen.top/Article/details/gt2ggtmiawt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj202588.top/Article/details/gt2hjpkuklo.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2menlexji.html

L. 网络请求
来源：http://dali.kuanghao11.cn/Article/details/gt2runvglay.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2oujadkln.html

[L01] 发送 GET 请求
来源：http://dali.zhengqikj.top/Article/details/gt2ejqdulvq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.birdmap.top/Article/details/gt2cgcqzsus.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yxxggqpp.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2edhjdisl.html

TS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gt2azvjoebu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.vqdsnc.cn/Article/details/gt2qqnqiswe.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2lcokwiyy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnxiangtu.top/Article/details/gt2ysspehlp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2afnmpbnk.html

[L02] 发送 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gt2eykmlcax.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gt2vrisafkw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.mhx1999.top/Article/details/gt2ccwwsent.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gt2vhurfexs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gt2auxfsgff.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ydzc1.top/Article/details/gt2hbypdblt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.smart0.xyz/Article/details/gt2efdwkcgz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gt2rubqputi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ivvv.top/Article/details/gt2zrffvekb.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gt2kwtuooov.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.birdmap.top/Article/details/gt2jncnwmxi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shzxlz.cn/Article/details/gt2wruntnbl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gt2tdfkimuv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gt2rjnexxxp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuanzx.com/Article/details/gt2josdfksw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gt2ibikrswx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gt2sajkimei.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gt2phqtoebs.html

[L04] 设置超时
来源：http://dali.iojbl.cn/Article/details/gt2zapjbtzw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenlongwang.top/Article/details/gt2ilxmgkoc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ppjwa.cn/Article/details/gt2uasecodn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gt2akhmqcby.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gt2wmtemwzt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhengqikj.top/Article/details/gt2oudbfbff.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgufenzy.top/Article/details/gt2zwgvcxrg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gt2maqksgpc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yanxiufei.cn/Article/details/gt2dvoakgom.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2klgnlygs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhiwuduotai.top/Article/details/gt2bmcxfvvl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yongpay.top/Article/details/gt2vmlqbvuv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gt2zaywopga.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gt2zyyssfac.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shzxlz.cn/Article/details/gt2ywwnaamf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gt2xmqcjjre.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.vqdsnc.cn/Article/details/gt2oziinqtx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2rroiigmp.html

[L06] 解析响应为 JSON
来源：http://dali.zhengqikj.top/Article/details/gt2uwdqgunw.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gt2azlmwaqb.html

PHP:  json_decode($body, true);
来源：http://dali.nwbrower.top/Article/details/gt2rxuqqthn.html

JS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gt2webzweqn.html

TS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gt2rtjhdaqg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nwbrower.top/Article/details/gt2mjhvmkzr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daxiang520.top/Article/details/gt2grjcfnbz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.mhx1999.top/Article/details/gt2uqropppk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmubztfc.html

[L07] 处理 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gt2jkyywvbu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aizwys.cn/Article/details/gt2wxqacbgp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guowangkeji.top/Article/details/gt2eaqakkno.html

JS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gt2venvbmao.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gt2axcxxgba.html

Java: resp.statusCode()
来源：http://dali.yuxming.cn/Article/details/gt2zhnnkrfi.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gt2fqdkgwgy.html

Ruby: resp.code.to_i
来源：http://dali.yangfankeji.com/Article/details/gt2sxpdtgnt.html

C#:   (int)resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gt2mmovmrgk.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gt2uimggnna.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gt2fyblghgz.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gt2ynqqhvvg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2zkkzvqml.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gt2mttpaupf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jyoumei.cn/Article/details/gt2xoeufjfp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gt2txedbmpd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ppjwa.cn/Article/details/gt2ignuumjw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.iojbl.cn/Article/details/gt2tyfwtufz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2loftiicy.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhixingplan.top/Article/details/gt2ossvjfmt.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2ipbizuwm.html

[M01] 读取命令行参数
来源：http://dali.shuidangran.top/Article/details/gt2kzbbopdt.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gt2ocvbeqds.html

PHP:  $argv;  $argc;
来源：http://dali.hnqzz.top/Article/details/gt2thunndoz.html

JS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gt2wingqdxg.html

TS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qactrqwu.html

Java: args 数组（main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gt2cevpsbue.html

Go:   os.Args[1:]
来源：http://dali.xylfe.cn/Article/details/gt2shtxprjv.html

Ruby: ARGV
来源：http://dali.hywenlv.cn/Article/details/gt2llmjksqp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yongpay.top/Article/details/gt2utpbvfcx.html

[M02] 读取环境变量
来源：http://dali.sysykeji.top/Article/details/gt2tzxltena.html

Py:   os.environ.get("HOME")
来源：http://dali.havefunace.top/Article/details/gt2twtdnbgm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gt2ngbtpbtr.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fqrgfnyn.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gt2kbqzacjz.html

Java: System.getenv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gt2tcujgrpb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2rvxxvpju.html

Ruby: ENV["HOME"]
来源：http://dali.hfpthk.cn/Article/details/gt2mynzvbfa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2ylfeteoj.html

[M03] 执行外部命令
来源：http://dali.zhengqikj.top/Article/details/gt2trcbfksy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gt2vnayomuz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cucudq.cn/Article/details/gt2hnmrrmqs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gt2dnkilddi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gt2fcnpbbkf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aibaodan.cn/Article/details/gt2cjufuzun.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gt2wleuhipu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdtmfeax.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gt2anbjvdnh.html

[M04] 获取当前工作目录
来源：http://dali.birdmap.top/Article/details/gt2tfvfkbsp.html

Py:   os.getcwd()
来源：http://dali.zdqjudy.top/Article/details/gt2oobbgsfb.html

PHP:  getcwd();
来源：http://dali.hnqzz.top/Article/details/gt2jjeqbdgx.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2vzfmqoaa.html

TS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2okgkhzzc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gt2wytoxyju.html

Go:   os.Getwd()
来源：http://dali.zdqjudy.top/Article/details/gt2uilusvzw.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gt2heeqdbax.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cdnleiting.top/Article/details/gt2jjujgohy.html

[M05] 设置退出码
来源：http://dali.havefunace.top/Article/details/gt2aywdsbcd.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2wlwhopni.html

PHP:  exit(1);
来源：http://dali.nwbrower.top/Article/details/gt2bofogqbb.html

JS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2unmmqacu.html

TS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2ysggqrrj.html

Java: System.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2lphiwzrx.html

Go:   os.Exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2wqeexwuh.html


<!-- 参考信息 -->