代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pycfn.com/Article/details/gtnmhmtebn.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gtkwwtehyl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sysykeji.top/Article/details/gtntvwsytu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sxryk.cn/Article/details/gtugkxryvp.html

Ruby: s.scan(/error/i)
来源：http://dali.wangshuangyany.cn/Article/details/gttplealxv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gtpcrtnpwd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenzaomai.com/Article/details/gtyswzuicj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ehwqpu.com/Article/details/gtglnvtvgs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtjhnqmyme.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gtysmbzypl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmubqdwx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gtxqdvjaty.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.haohaochexian.top/Article/details/gtlftcjrah.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gtdxqgajvp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gtaxcycpcu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtivepvedo.html

J. 日期与时间
来源：http://dali.yanxiufei.cn/Article/details/gthfebqfjz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtaypxhtkk.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqkbtbhy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrwaieez.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gtvpeglabl.html

JS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtqjzxrwrg.html

TS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtjenjoxmh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.haohaochexian.top/Article/details/gtfhnwvkrt.html

Go:   time.Now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhsjdxjx.html

Ruby: Time.now
来源：http://dali.yj20258888.top/Article/details/gtocgwmsgn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.havefunace.top/Article/details/gticavffza.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtmpylryal.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gtrjxjygtt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gtaggcfnwv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.bjfxy.top/Article/details/gtjybaratu.html

TS:   d.toISOString()
来源：http://dali.ydzc1.top/Article/details/gtqhesjlix.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.haohaochexian.top/Article/details/gtpztowfct.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.feifeiyinyue.top/Article/details/gtyzbkcmqb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtjfwndllh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.birdmap.top/Article/details/gtkczmnpdw.html

[J03] 字符串解析为日期
来源：http://dali.nwbrower.top/Article/details/gttreglwyf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258.top/Article/details/gtxosdwcex.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cdnleiting.top/Article/details/gthzptmegj.html

JS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtkcfctyvm.html

TS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtckinmahj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtoyawwbzq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtbfkaaqtg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtojxpsmjw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tanke756.top/Article/details/gtzcciurwx.html

[J04] 时间戳与日期互转
来源：http://dali.cqqwz.cn/Article/details/gtgehdiefi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yonumen.top/Article/details/gtrsvixfdv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gtdsiufyiz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.redwolf501.top/Article/details/gtnjrdwqcq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tian-w.cn/Article/details/gtpupnjeiz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.haohaochexian.top/Article/details/gtgionhmeh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gzhubu.top/Article/details/gtjrfodolk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gtxuejbpwu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtadhkwvnq.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258.top/Article/details/gtsumqyxyy.html

Py:   now + timedelta(days=7)
来源：http://dali.hongshengwenyu.top/Article/details/gtvszisotx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgfzy.top/Article/details/gtewstmcyr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtofakfdlu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtjuivuurv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gtickzhlkr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhixingplan.top/Article/details/gtoffozptf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangdashe.top/Article/details/gtptxcdftu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yvedp.cn/Article/details/gtdhjdttkw.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gthavcvirj.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258.top/Article/details/gthjkddmfb.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gturcdxgvt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gtdawkkney.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigufen.top/Article/details/gtgzkvzgbs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.andypj.xyz/Article/details/gtzafblidl.html

Go:   end.Sub(start).Hours()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenpirnoc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tianlin.xyz/Article/details/gtiyhnrrks.html

C#:   (end - start).TotalSeconds
来源：http://dali.daria6918.cn/Article/details/gtazielcyx.html

[J07] 比较两个日期
来源：http://dali.hysaishi.cn/Article/details/gtrbevzahd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtxzfynvfu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gotoacloud.top/Article/details/gttfvmoobt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwtadsnu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gtccliqijm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258.top/Article/details/gtoermibwt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenzaomai.com/Article/details/gtspixbytz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtjbiucymu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtryfooxkn.html

[J08] 提取年月日与星期
来源：http://dali.tianlin.xyz/Article/details/gtlufnqhpr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.quarkkingdee.top/Article/details/gtobhsaulp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhoulong.xyz/Article/details/gtoimegwwn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gtvkpyljpw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hysaishi.cn/Article/details/gtzqkxfsxl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gtbxbfubmr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dianchejie.cn/Article/details/gtysjjcmxa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhongyouzk.top/Article/details/gthcwibuvw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gtamrunxme.html

[J09] 时区处理
来源：http://dali.tianlin.xyz/Article/details/gtvjqmdswh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gtvxvapvyi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdgkuetg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gtnalknltk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gtulzdvvoy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xinyue.icu/Article/details/gtjhseiopu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangdashe.top/Article/details/gtxlyxdwon.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.birdmap.top/Article/details/gtyqvilbwn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gthtqyrirz.html

[J10] 取今天 / 本月第一天
来源：http://dali.redwolf501.top/Article/details/gtkzbphgjv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangdashe.top/Article/details/gtecagksna.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangdashe.top/Article/details/gtetalgjmr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.quarkkingdee.top/Article/details/gtyjbvgmlz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gtjmtrofbb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.redwolf501.top/Article/details/gteghfpups.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gaohongyu789.top/Article/details/gthilxhgbj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.quarkkingdee.top/Article/details/gtstuyfsux.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gtkgllfrzv.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtifmfdrnx.html

K. JSON 与序列化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipjueztk.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtvwkdhsvo.html

[K01] 对象转 JSON 字符串
来源：http://dali.tianlin.xyz/Article/details/gtmupgnkfw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtejimdjwk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtohajwugz.html

JS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gtcfvffcpt.html

TS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gtcqnlnxky.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.havefunace.top/Article/details/gtwodkudwl.html

Go:   json.Marshal(obj)
来源：http://dali.aibaodan.cn/Article/details/gtuqghvawv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.birdmap.top/Article/details/gtawtwtgov.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gtjowzyufg.html

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gtevuabtsq.html

Py:   json.loads(s)
来源：http://dali.yj20258888.top/Article/details/gtzuiarvxm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cashguo.top/Article/details/gtqgbeulvf.html

JS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtwrhdmgin.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtifzdesmb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtbtlnvgfi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtgdwxlpen.html

Ruby: JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtieylxews.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xinyue.icu/Article/details/gtvglpbnfh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yongpay.top/Article/details/gtqvhznkoc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gthorurxoz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrwtvfns.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gtaenemhiq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtjlckukjh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.bjfxy.top/Article/details/gtpdryienl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gtuitnlnhp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aibaodan.cn/Article/details/gtwbbyxlxo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhmmgnhn.html

[K04] 读取 JSON 文件
来源：http://dali.cashguo.top/Article/details/gtxpkyhuov.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.iojbl.cn/Article/details/gtgozbpxbl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.snrcjt.cn/Article/details/gtfvqacnyq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtfyompaxx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gtsqjwafbt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtwzekvzdw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gtykjmdvac.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtsexjqbsb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtqryrhuqv.html

[K05] 深拷贝对象
来源：http://dali.vqdsnc.cn/Article/details/gtjoenalgo.html

Py:   copy.deepcopy(obj)
来源：http://dali.ybcxt.top/Article/details/gtobyfiuzh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hammf.cn/Article/details/gtyykjxkjx.html

JS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gtfetenkzl.html

TS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gtoxuiztql.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gogol.net.cn/Article/details/gtukrayzqn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gtwhcbuckv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gtabsfazdl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yvedp.cn/Article/details/gtkrauuvsd.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gtfxmuqyqk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gtsmjzkykg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cashguo.top/Article/details/gtggsxwyap.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gtxrpuyjxd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtslomcpbo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cqqwz.cn/Article/details/gtsfiantvm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtpoqubnoh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtrvriuviu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtugaidqqa.html

[K07] 进制转换
来源：http://dali.yueranfly.top/Article/details/gtvpzohtff.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtypfhjytp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.quarkkingdee.top/Article/details/gtjtecqmjf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gttkcntqlv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtoxacrqjw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtxbgzzvbs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xylfe.cn/Article/details/gtrpdqgiiy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hysaishi.cn/Article/details/gtaqpiohzq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gthxniynou.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hammf.cn/Article/details/gtvtaqkvin.html

Py:   pickle.dumps(obj)
来源：http://dali.tianlin.xyz/Article/details/gtrweervvp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sufxvd.cn/Article/details/gtnektvucz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtufauwonh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtxyyndfgk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sufxvd.cn/Article/details/gtzzzvfyaw.html

Go:   encoding/gob
来源：http://dali.tianlin.xyz/Article/details/gtnsjxjhca.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangdashe.top/Article/details/gtnsawrgdx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gthxccgpqw.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcevyuei.html

L. 网络请求
来源：http://dali.wangshuangyany.cn/Article/details/gtkkdaqbys.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtntveewpy.html

[L01] 发送 GET 请求
来源：http://dali.cashguo.top/Article/details/gtfbzunrmk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cucudq.cn/Article/details/gtlbnwlvkh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258888.top/Article/details/gtkgafrqql.html

JS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtqkqtmygl.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtnntxacwp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cdnleiting.top/Article/details/gtobwkpqws.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gtgboekdov.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.redwolf501.top/Article/details/gtkzwsutgq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sweek.top/Article/details/gtgoroogfs.html

[L02] 发送 POST JSON
来源：http://dali.yongpay.top/Article/details/gtrvjlzorr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtmgzkiyrs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258.top/Article/details/gtsfajybvl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemdnadtb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gtasrnvxhj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gtkocfymty.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gtkzzjgvxm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhiwuduotai.top/Article/details/gtgoxqsqfx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sxryk.cn/Article/details/gtsomnigcj.html

[L03] 设置自定义请求头
来源：http://dali.yuxming.cn/Article/details/gtecahklwp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.redwolf501.top/Article/details/gtfnjjztmg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gtjcgrixro.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtqsnjaztp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtdpilvxlp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.havefunace.top/Article/details/gtbjxayrpo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gttgwzjcee.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxuanxn.top/Article/details/gtgiofnqwa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gtxfvamwbs.html

[L04] 设置超时
来源：http://dali.9152youxi.cn/Article/details/gtcperkbti.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuanzhike.top/Article/details/gtpbftesxx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sweek.top/Article/details/gtixlcogax.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gtwnbjkjjm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gtdcqivfki.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gogol.net.cn/Article/details/gthzimkaaj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fengsongda.top/Article/details/gtcjlphvxy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj202588.top/Article/details/gtepkeahhg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxinkj.top/Article/details/gtgatnkolw.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gtzrdilojm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwrgqhrl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shzxlz.cn/Article/details/gtjhdagdin.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtowruxcnk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtftbesgsl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fzhhl.top/Article/details/gtffjcfkzy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dashuyun.cn/Article/details/gtwzegwkwu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aibaodan.cn/Article/details/gtujodzrto.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xziqi.cn/Article/details/gtrooeorqm.html

[L06] 解析响应为 JSON
来源：http://dali.snrcjt.cn/Article/details/gttxksfknl.html

Py:   resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtbfdplaxm.html

PHP:  json_decode($body, true);
来源：http://dali.aizwys.cn/Article/details/gtzhlktrbw.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtvehzyniz.html

TS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gthxrxvldp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrntiffq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.quarkkingdee.top/Article/details/gtxuraczne.html

Ruby: JSON.parse(resp.body)
来源：http://dali.andypj.xyz/Article/details/gtuvxjkkva.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yanxiufei.cn/Article/details/gtnvcrlgav.html

[L07] 处理 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gtgbkpmxlp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.meibo888.top/Article/details/gtarvzrjbl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhongyouzk.top/Article/details/gtdkblvkuc.html

JS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gtbuvyxhmo.html

TS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gtzalgykqn.html

Java: resp.statusCode()
来源：http://dali.dashuyun.cn/Article/details/gtmmcbeegb.html

Go:   resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gtkmofrnck.html

Ruby: resp.code.to_i
来源：http://dali.ywan-chungtsiang.top/Article/details/gtneklkzwu.html

C#:   (int)resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gtzrmvtmfo.html

[L08] 并发请求多个地址
来源：http://dali.gogol.net.cn/Article/details/gtqofmvlvo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjknnsua.html

PHP:  curl_multi_init() 系列
来源：http://dali.kuanghao11.cn/Article/details/gtshdwvtgz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtnuglmxvr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gtutosqcda.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.quarkkingdee.top/Article/details/gtvqhxnpwn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gtidmhoinq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gtgwqbxgwn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ehwqpu.com/Article/details/gtaiwggdhu.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtuiaputfi.html

M. 命令行 / 进程 / 环境
来源：http://dali.tianlin.xyz/Article/details/gtqtdbghgy.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtadwyhvvu.html

[M01] 读取命令行参数
来源：http://dali.guowangkeji.top/Article/details/gtjadfwqow.html

Py:   sys.argv[1:]
来源：http://dali.dashuyun.cn/Article/details/gtljkazvuy.html

PHP:  $argv;  $argc;
来源：http://dali.aibaodan.cn/Article/details/gtdedtagrr.html

JS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gtfehhaqar.html

TS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gtfnpwypfa.html

Java: args 数组（main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gtrsjrjsyt.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gtqlnuuysd.html

Ruby: ARGV
来源：http://dali.gogol.net.cn/Article/details/gtoeqtdgmw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtkdmgiywi.html

[M02] 读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gtjkbpuxes.html

Py:   os.environ.get("HOME")
来源：http://dali.fengsongda.top/Article/details/gtynffmtyu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gtgqpgkymf.html

JS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gtspzqmwkc.html

TS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gtupvkwqmv.html

Java: System.getenv("HOME")
来源：http://dali.sweek.top/Article/details/gtrwsrhttn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtysygbzis.html

Ruby: ENV["HOME"]
来源：http://dali.haohaochexian.top/Article/details/gtjqfemqpn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtvnjiiuqv.html

[M03] 执行外部命令
来源：http://dali.316326.xyz/Article/details/gtfuijqidz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shzxlz.cn/Article/details/gtmclblqwl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gogol.net.cn/Article/details/gtlbfutqwn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtdapriclc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtzcxrssfr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.9152youxi.cn/Article/details/gtxrbgulnw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.iojbl.cn/Article/details/gtfqlkleui.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.meibo888.top/Article/details/gtdivecbxp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cucudq.cn/Article/details/gtvufocumn.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gtxswosbow.html

Py:   os.getcwd()
来源：http://dali.zhongyouzk.top/Article/details/gtrjsvmdsu.html

PHP:  getcwd();
来源：http://dali.c1oappe.top/Article/details/gtmadyfxvd.html

JS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtwugrmyno.html

TS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtnimjawgp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gaohongyu789.top/Article/details/gtfikaecqy.html

Go:   os.Getwd()
来源：http://dali.ybcxt.top/Article/details/gtlktabgcd.html

Ruby: Dir.pwd
来源：http://dali.yonumen.top/Article/details/gtmfepikeh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ppjwa.cn/Article/details/gtrjaijwsj.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gtccjawcyh.html

Py:   sys.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtficgozpz.html

PHP:  exit(1);
来源：http://dali.dashuyun.cn/Article/details/gtccgpvgno.html


<!-- 参考信息 -->