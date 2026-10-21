代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuxming.cn/Article/details/gttucfzepa.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gtyqluvdvd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gogol.net.cn/Article/details/gtbbvkvcup.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daria6918.cn/Article/details/gtuvanomyu.html

Ruby: s.scan(/error/i)
来源：http://dali.gzhubu.top/Article/details/gtifpiywta.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jianghu66.top/Article/details/gtfpcljjeh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ppjwa.cn/Article/details/gtfddisziy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhongyouzk.top/Article/details/gtcwawfszn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtdpbzgmuj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gtttayatfc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gtppialvlo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gtiyevbzza.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.smart0.xyz/Article/details/gtfqgieogc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.bjfxy.top/Article/details/gtpmtukmhh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gtujgtfrib.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtybwdvmxa.html

J. 日期与时间
来源：http://dali.nanxuanxn.top/Article/details/gtzfnhqess.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtoijxnxmx.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gtxritwffz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenzaomai.com/Article/details/gttwhamzfy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gtnlapjukd.html

JS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtfhagxncr.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gtyspqhmvg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cashguo.top/Article/details/gtonnokygr.html

Go:   time.Now()
来源：http://dali.sweek.top/Article/details/gtbzlqdtmq.html

Ruby: Time.now
来源：http://dali.gotoacloud.top/Article/details/gtsdjecxqs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxuanxn.top/Article/details/gtlbztevrj.html

[J02] 格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gtbfzkewau.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gtwjlwumfd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gtuvxpvlps.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenjidiqi.icu/Article/details/gticzelrde.html

TS:   d.toISOString()
来源：http://dali.pengpengdd.cyou/Article/details/gtyipvxzrk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sysykeji.top/Article/details/gtxfugmjiq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktsmeoel.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gtezabbvlp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258888.top/Article/details/gtkrutsjux.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gtgmhmoonm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdshaalzk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gtlamkvhcv.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtzxzbpeuv.html

TS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gttatkxelc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtayxxnpbk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtdqjlgmzc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnszouxiu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkakobmtu.html

[J04] 时间戳与日期互转
来源：http://dali.nwbrower.top/Article/details/gtlptcfqyh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hammf.cn/Article/details/gtqgrckucu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgufenzy.top/Article/details/gtvxqrbxke.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gogol.net.cn/Article/details/gtvvdnzwvc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gaohongyu789.top/Article/details/gthnqsahux.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosmpoeur.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcsdkaoe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtendcxxqt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbeoydcm.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gtoxunqrni.html

Py:   now + timedelta(days=7)
来源：http://dali.quarkkingdee.top/Article/details/gtmuzscfon.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dianchejie.cn/Article/details/gtxcsixukk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqkrmizi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gttxhyciix.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tanke756.top/Article/details/gtcbonblzq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sufxvd.cn/Article/details/gtnkjaxibr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pycfn.com/Article/details/gtltqbcxic.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yueranfly.top/Article/details/gtcvwvexqg.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gtaqnvzibj.html

Py:   (end - start).total_seconds()
来源：http://dali.meibo888.top/Article/details/gtmmpqkcjl.html

PHP:  $end->diff($start)->days;
来源：http://dali.smart0.xyz/Article/details/gtykvxseib.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.bjfxy.top/Article/details/gtecabzdde.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ivvv.top/Article/details/gtccpuzsvg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sweek.top/Article/details/gtyxwldief.html

Go:   end.Sub(start).Hours()
来源：http://dali.ydzc1.top/Article/details/gtikwneqxn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjgyyhts.html

C#:   (end - start).TotalSeconds
来源：http://dali.aibaodan.cn/Article/details/gtztokovot.html

[J07] 比较两个日期
来源：http://dali.iojbl.cn/Article/details/gtqfmxnnle.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtvonoimcg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fengsongda.top/Article/details/gtvrhslsig.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gtquupseoc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gtxtuskooi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guannengcc.top/Article/details/gtnyrijmjo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.meibo888.top/Article/details/gtvylsrhrk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtwiqrzcut.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtnpejjfxf.html

[J08] 提取年月日与星期
来源：http://dali.dashuyun.cn/Article/details/gtubzikazj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cqqwz.cn/Article/details/gtpethftxz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.svipenyu.cn/Article/details/gtdfnxdnyb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.andypj.xyz/Article/details/gtgpvwheej.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gtopokvubu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gtlmuonosc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gtpeenhxvv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ppjwa.cn/Article/details/gtrvvevhfe.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.quarkkingdee.top/Article/details/gtbpjeerrv.html

[J09] 时区处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldbgmswu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ehwqpu.com/Article/details/gtgoowmhsy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yanxiufei.cn/Article/details/gtwpdxxgfw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gtcdxgxszu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gtamvhsett.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangtech.top/Article/details/gttwhtlyea.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gogol.net.cn/Article/details/gtsxbbeeef.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.316326.xyz/Article/details/gtvfdtzasl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yongpay.top/Article/details/gtnvfakwmt.html

[J10] 取今天 / 本月第一天
来源：http://dali.ppjwa.cn/Article/details/gtzjnziewk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gtbkmbrgjy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hongshengwenyu.top/Article/details/gtxanlwjuf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shzxlz.cn/Article/details/gttrnxoycy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tianlin.xyz/Article/details/gttinbionq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigfzy.top/Article/details/gtyyeqtzzn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlyhklvpx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ydzc1.top/Article/details/gtmgbpzlpa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuxming.cn/Article/details/gtqeowuriu.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtrstkdngi.html

K. JSON 与序列化
来源：http://dali.chenlongwang.top/Article/details/gtytouajbt.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtncycowxs.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gtavjyxpkl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gtxbncufhg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtdhojbwtj.html

JS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gtuoddsryi.html

TS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gttblhacur.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.kuanghao11.cn/Article/details/gtzllgwbzf.html

Go:   json.Marshal(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtzgnykfub.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.9152youxi.cn/Article/details/gthljgqfze.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sxryk.cn/Article/details/gtkdmbisha.html

[K02] JSON 字符串转对象
来源：http://dali.zhixingplan.top/Article/details/gtlikkonhg.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gtkudbmnso.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jianghu66.top/Article/details/gtdltlkyou.html

JS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtkngurxvn.html

TS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtanhxvrhy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtflafxgjv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtbmuovpel.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtjeyxxgex.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gtipkffouj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gtfgxwwqye.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gtmzmoetdp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtyfapkifz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gtcubcbdqy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtlolccxno.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlhcspcm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jyoumei.cn/Article/details/gtylbssdgl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gaohongyu789.top/Article/details/gthfvkcvkz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nwbrower.top/Article/details/gttgpnftll.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gtgutzmyfn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuanzhike.top/Article/details/gtyzekgxir.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuetiantiany.cn/Article/details/gtkjypobpn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gttukgoeln.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtudvhzdrv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtoxfqxooo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxhvahae.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gtnpbdjqtn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gtbmqktqvf.html

[K05] 深拷贝对象
来源：http://dali.chenlongwang.top/Article/details/gtglwcunni.html

Py:   copy.deepcopy(obj)
来源：http://dali.316326.xyz/Article/details/gtisxqajga.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jianghu66.top/Article/details/gtwqukjezc.html

JS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gttdxzaazt.html

TS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtacplpgez.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jiagoushi.top/Article/details/gtzslnczjw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daxiang520.top/Article/details/gtykrudlpw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guowangkeji.top/Article/details/gtgslceaid.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gtseaqeuco.html

[K06] 解析 URL 查询串
来源：http://dali.nwbrower.top/Article/details/gtmhhpeejn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sysykeji.top/Article/details/gtaxoznxmk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.bjfxy.top/Article/details/gtxdtugwxd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gtmoppeqfz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtotvawnsx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sufxvd.cn/Article/details/gtpqvyvipg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtfnlplfso.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtdbrxdwpa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtpdcrfona.html

[K07] 进制转换
来源：http://dali.gzhubu.top/Article/details/gtksqiooix.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtsbgkdrzh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aizwys.cn/Article/details/gtrwingtrf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjefgfqzs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtlusquhug.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtojalbuym.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.bjfxy.top/Article/details/gttsderdod.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gtbbclecwe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hammf.cn/Article/details/gttzegiyyh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangtech.top/Article/details/gtedumivkb.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258.top/Article/details/gtusogekci.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtlnhvggou.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gtnbfiudid.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gtztdtgxex.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.smart0.xyz/Article/details/gtjhwvffjx.html

Go:   encoding/gob
来源：http://dali.pengpengdd.cyou/Article/details/gtcslzodfa.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gtfpjbqtuk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtyhhthyms.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtbxudolax.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gtwqvxtffj.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkxabuujb.html

[L01] 发送 GET 请求
来源：http://dali.bjfxy.top/Article/details/gtmnfdjlwv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tian-w.cn/Article/details/gtzktbngza.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.haohaochexian.top/Article/details/gtoitugbor.html

JS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gthsnubloo.html

TS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtgjrigwse.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jyoumei.cn/Article/details/gtcevialcc.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtufasiaow.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.redwolf501.top/Article/details/gticzzbbgx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.c1oappe.top/Article/details/gtejwigkcw.html

[L02] 发送 POST JSON
来源：http://dali.hammf.cn/Article/details/gtjyomjjuy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gtiqbdxxbo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gtelnucquj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gtibgsukul.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gteuxyyern.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yonumen.top/Article/details/gtkawwkoge.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigfzy.top/Article/details/gtdphqvdbe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zycfv.cn/Article/details/gtpgctdckb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ppjwa.cn/Article/details/gtqjpyinnv.html

[L03] 设置自定义请求头
来源：http://dali.snrcjt.cn/Article/details/gtpwavdmyj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jlsjyb.cn/Article/details/gtcyjhvpvk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gthnobdhqv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gtfidvpwhu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtyqwjymjr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gthfocsuve.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtkffxrfwm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hammf.cn/Article/details/gtxkpyvcka.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gtlzcxncbt.html

[L04] 设置超时
来源：http://dali.cucudq.cn/Article/details/gteftkymzx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fzhhl.top/Article/details/gtnlogorzk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdzmrjuu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gtdwvxeofo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtawcecbbu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gtqtxufney.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gtjmznmjnj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhiwuduotai.top/Article/details/gtkavuqxim.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hongshengwenyu.top/Article/details/gtxklggibq.html

[L05] 上传文件（multipart）
来源：http://dali.hongshengwenyu.top/Article/details/gttpgnjdgm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpiqrzxx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.havefunace.top/Article/details/gtnrnqvpie.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtiftquqok.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gtgnnvdqwz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.redwolf501.top/Article/details/gtnajfmdcv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuanzx.com/Article/details/gtnfezrhra.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xylfe.cn/Article/details/gthtsecbzr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cashguo.top/Article/details/gtkhzukshc.html

[L06] 解析响应为 JSON
来源：http://dali.zhixingplan.top/Article/details/gtcmablcpk.html

Py:   resp.json()
来源：http://dali.sysykeji.top/Article/details/gtnmzfpjpo.html

PHP:  json_decode($body, true);
来源：http://dali.zycfv.cn/Article/details/gtxjqyvftr.html

JS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtdublaccj.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gtwepjcidh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuxming.cn/Article/details/gtljvprviu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pycfn.com/Article/details/gtznayvory.html

Ruby: JSON.parse(resp.body)
来源：http://dali.redwolf501.top/Article/details/gtaitbahjg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guannengcc.top/Article/details/gtkvcqlczp.html

[L07] 处理 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtcbepbd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangshuangyany.cn/Article/details/gtvfomjxnu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.c1oappe.top/Article/details/gtvfhxfvwd.html

JS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gtpflezlbn.html

TS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gthluojcjz.html

Java: resp.statusCode()
来源：http://dali.yuxming.cn/Article/details/gthvrrqbvn.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtraqamzpp.html

Ruby: resp.code.to_i
来源：http://dali.svipenyu.cn/Article/details/gtrcfbamkc.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtovlecjxe.html

[L08] 并发请求多个地址
来源：http://dali.sufxvd.cn/Article/details/gtpexmtsbw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gtpjdmlurg.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj202588.top/Article/details/gtxgzlxwsn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtdcihxjmc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtvldxdglc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhengqikj.top/Article/details/gtlayvqllq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangtech.top/Article/details/gtkonccqyh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yueranfly.top/Article/details/gtnowxsfja.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sweek.top/Article/details/gtkoiuqdwr.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtzcxmtbys.html

M. 命令行 / 进程 / 环境
来源：http://dali.birdmap.top/Article/details/gttyorngeq.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtnddtaiyn.html

[M01] 读取命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmnuwwdt.html

Py:   sys.argv[1:]
来源：http://dali.hnqzz.top/Article/details/gtzdiolexw.html

PHP:  $argv;  $argc;
来源：http://dali.sufxvd.cn/Article/details/gtbecblhet.html

JS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gtzwboaqsb.html

TS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gtpjlawhqm.html

Java: args 数组（main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gthyaihnzm.html

Go:   os.Args[1:]
来源：http://dali.snrcjt.cn/Article/details/gtplelxnrl.html

Ruby: ARGV
来源：http://dali.mhx1999.top/Article/details/gtowxgjymg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.316326.xyz/Article/details/gtvovzecvg.html

[M02] 读取环境变量
来源：http://dali.hnqzz.top/Article/details/gtvefjotbu.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gtzzsptwym.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtzgzstsfe.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtuzjtyubw.html

TS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gttneudsbd.html

Java: System.getenv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtkuaipytf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtjgehvkzz.html

Ruby: ENV["HOME"]
来源：http://dali.fzhhl.top/Article/details/gtozwlcnmy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtgomfapbf.html

[M03] 执行外部命令
来源：http://dali.zhengqikj.top/Article/details/gtcwicrfmk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xinyue.icu/Article/details/gtbiuvcayq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuanzx.com/Article/details/gtkcdjukeh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gtjmxanzux.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtmocmqbcn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nwbrower.top/Article/details/gtwyeavrfw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gtycegmjdz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gtxfukfiou.html

C#:   Process.Start("ls", "-l");
来源：http://dali.smart0.xyz/Article/details/gtjflrimtq.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gtuxnremub.html

Py:   os.getcwd()
来源：http://dali.tianlin.xyz/Article/details/gttjyidigp.html

PHP:  getcwd();
来源：http://dali.zhixingplan.top/Article/details/gtyeipgger.html

JS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gtfsnzzedz.html

TS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtlzxogcbq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.iojbl.cn/Article/details/gtkpotnisx.html

Go:   os.Getwd()
来源：http://dali.ehwqpu.com/Article/details/gtmzcspstv.html

Ruby: Dir.pwd
来源：http://dali.sweek.top/Article/details/gtrdsayvyp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenjidiqi.icu/Article/details/gtmwyoxuch.html

[M05] 设置退出码
来源：http://dali.aibaodan.cn/Article/details/gtfjmamtqw.html

Py:   sys.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtzgkddaki.html

PHP:  exit(1);
来源：http://dali.sufxvd.cn/Article/details/gtrssopqam.html


<!-- 参考信息 -->