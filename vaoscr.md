代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jyoumei.cn/Article/details/gt2wspuookv.html

TS:   /error/gim
来源：http://dali.yvedp.cn/Article/details/gt2imwqjcbx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktoojiwl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.0kj1m.cn/Article/details/gt2riuzoxiq.html

Ruby: s.scan(/error/i)
来源：http://dali.hfpthk.cn/Article/details/gt2lpwrjvlo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.birdmap.top/Article/details/gt2cuxbepaq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gt2dhjvflwh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jianghu66.top/Article/details/gt2bmrcgyor.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gt2zfxqvtvz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gt2gqkeaies.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gt2kodngrbb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gt2kcqaaxuq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xinyue.icu/Article/details/gt2rcejbasu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zycfv.cn/Article/details/gt2ungpbesn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gt2gopjzgzx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2lwmmxayv.html

J. 日期与时间
来源：http://dali.yuxming.cn/Article/details/gt2xqabxohk.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2wrohrmsk.html

[J01] 获取当前时间
来源：http://dali.jqgfzy.top/Article/details/gt2qzteqawt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258888.top/Article/details/gt2ujbyxdlh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gt2sqanmwal.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gt2xymbhwzr.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gt2yfgumblf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ebqvcjzr.html

Go:   time.Now()
来源：http://dali.ybcxt.top/Article/details/gt2tqogqmws.html

Ruby: Time.now
来源：http://dali.yj20258.top/Article/details/gt2ufqrhuoh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xziqi.cn/Article/details/gt2akwgcyta.html

[J02] 格式化输出
来源：http://dali.nwbrower.top/Article/details/gt2uxalfejd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gt2djlokyou.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gt2tuxuilcp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gt2hueugncc.html

TS:   d.toISOString()
来源：http://dali.redwolf501.top/Article/details/gt2vfbbudvc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jlsjyb.cn/Article/details/gt2pvpwakex.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258888.top/Article/details/gt2grsleqaq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gt2srbrrpab.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cqqwz.cn/Article/details/gt2zaubgcjn.html

[J03] 字符串解析为日期
来源：http://dali.hfpthk.cn/Article/details/gt2mlmpcdrg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wqzjjyto.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangshuangyany.cn/Article/details/gt2suyfimmo.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2edmxosbs.html

TS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2ojrshyea.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2kbsaqrhv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2raofpkhg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2cxyilaqc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ybcxt.top/Article/details/gt2dhvtdtpc.html

[J04] 时间戳与日期互转
来源：http://dali.jqgfzy.top/Article/details/gt2afevykbh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2pbyugctm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fzhhl.top/Article/details/gt2qhvxespp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jianghu66.top/Article/details/gt2lzglzlcu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.316326.xyz/Article/details/gt2vzmrwesq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yueranfly.top/Article/details/gt2silkesle.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2qbybgvln.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2hkvzkvsm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2chuffdaj.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuetiantiany.cn/Article/details/gt2npvsogyr.html

Py:   now + timedelta(days=7)
来源：http://dali.jlsjyb.cn/Article/details/gt2dppwysvk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tian-w.cn/Article/details/gt2brumqnaf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gt2jazeywzx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gt2uqxkuvpi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.9152youxi.cn/Article/details/gt2gvtlrilg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zycfv.cn/Article/details/gt2vqzautgz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gt2dpadihkr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxvtigjm.html

[J06] 计算两时间之差
来源：http://dali.aizwys.cn/Article/details/gt2ytqxybsh.html

Py:   (end - start).total_seconds()
来源：http://dali.tianlin.xyz/Article/details/gt2phguveyq.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuxming.cn/Article/details/gt2bfsazdzm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dashuyun.cn/Article/details/gt2eehlgcfu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj202588.top/Article/details/gt2owdcfqxc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gt2hayuqhhz.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gt2zerjdpui.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dashuyun.cn/Article/details/gt2zmxvtlgq.html

C#:   (end - start).TotalSeconds
来源：http://dali.yangfankeji.com/Article/details/gt2ddfhhrdr.html

[J07] 比较两个日期
来源：http://dali.sufxvd.cn/Article/details/gt2erlzqkls.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gt2symxlrme.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gt2rofisikw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gt2uxqoekkd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gt2gjxzozzb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gt2rkagydrt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gt2eiikkpah.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gt2tfrugnsw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gt2wtzeezjp.html

[J08] 提取年月日与星期
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qzldyraw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.vqdsnc.cn/Article/details/gt2sszilrex.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ppjwa.cn/Article/details/gt2ryrfjnbx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daria6918.cn/Article/details/gt2bktmkodh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uxnneqfx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxinkj.top/Article/details/gt2daavpdfg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cqvubxrh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangshuangyany.cn/Article/details/gt2owupoxbl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fengsongda.top/Article/details/gt2fwbeveee.html

[J09] 时区处理
来源：http://dali.guannengcc.top/Article/details/gt2stactnnj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xinyue.icu/Article/details/gt2gyvupxkg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.mhx1999.top/Article/details/gt2mpeihrpr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gt2chmphsee.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gt2jcjcsdmo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gt2nwpmwyss.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gt2rvyjeakn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gt2glvizkme.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258.top/Article/details/gt2lfjkkobb.html

[J10] 取今天 / 本月第一天
来源：http://dali.zdqjudy.top/Article/details/gt2igackhmb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gfkugrgy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.smart0.xyz/Article/details/gt2qwqyjmle.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2jflbsjim.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gt2jrrgfoxg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gt2frqixysf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jianghu66.top/Article/details/gt2cllunwqw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gaohongyu789.top/Article/details/gt2spjpyohr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hammf.cn/Article/details/gt2ymifpuug.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2zsuuhooo.html

K. JSON 与序列化
来源：http://dali.mhx1999.top/Article/details/gt2crhagdwg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2piivgbrp.html

[K01] 对象转 JSON 字符串
来源：http://dali.xylfe.cn/Article/details/gt2zxqelibx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gt2gyfgrcqe.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gt2leijvmdl.html

JS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gt2ohzwrvzi.html

TS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jkpiohpn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cqqwz.cn/Article/details/gt2ycbvdrwr.html

Go:   json.Marshal(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzzkxopb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fzhhl.top/Article/details/gt2hyhphmci.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gt2wfotguzk.html

[K02] JSON 字符串转对象
来源：http://dali.wangdashe.top/Article/details/gt2qotwutie.html

Py:   json.loads(s)
来源：http://dali.yonumen.top/Article/details/gt2ictpuqas.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigfzy.top/Article/details/gt2sdcqeldy.html

JS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gt2xnyduxmq.html

TS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2pkelevqw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gt2iezolzfn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gt2ubwwxdxl.html

Ruby: JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2phxovpqd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lbmoaikl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yueranfly.top/Article/details/gt2jmnrivvv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gt2zmamaxhj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gt2ojxfqsdb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gt2gxeazqnu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2hjvlgscu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2czignllb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dashuyun.cn/Article/details/gt2gtprjnyc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gt2lxfjpkdg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gt2cyhpdmep.html

[K04] 读取 JSON 文件
来源：http://dali.sufxvd.cn/Article/details/gt2zsjrjlgc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258.top/Article/details/gt2ogbbvdoz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hjqoxmgk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2awttudnl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gt2bmbfvcrm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gt2wbwmrfan.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gt2plblymkn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gt2vaivhjhw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gt2ktlnjlsx.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlgpxar.html

Py:   copy.deepcopy(obj)
来源：http://dali.yongpay.top/Article/details/gt2arfehbcl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gogol.net.cn/Article/details/gt2lzeoxcee.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gt2vgizhcqy.html

TS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2pjkamowz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shangyingyoupin.top/Article/details/gt2itxpzmuw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yueranfly.top/Article/details/gt2dfewvkqj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daria6918.cn/Article/details/gt2jezsnnwh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cashguo.top/Article/details/gt2hptzqhgd.html

[K06] 解析 URL 查询串
来源：http://dali.yuanzhike.top/Article/details/gt2rnpghowl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gt2ntyjjklr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gt2jlfasgwd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gt2msylxrjv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gt2tpjzhcoe.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tianlin.xyz/Article/details/gt2egxjvvzg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gt2ymmhuhhb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gt2gbhgsqyg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2xbfrpgwp.html

[K07] 进制转换
来源：http://dali.meibo888.top/Article/details/gt2xhshlymr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2ysdckbst.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cdnleiting.top/Article/details/gt2wlnhprhu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2jtjfziyo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2sellzjvp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2vjszhaar.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shzxlz.cn/Article/details/gt2gsmzsrju.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj202588.top/Article/details/gt2amjfpwwc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2yrgmkniz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gt2mhrzounw.html

Py:   pickle.dumps(obj)
来源：http://dali.ybcxt.top/Article/details/gt2hpouybpc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.mhx1999.top/Article/details/gt2goywhebm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gt2kliwznyh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gt2vajkebhh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangdashe.top/Article/details/gt2qdssksua.html

Go:   encoding/gob
来源：http://dali.ybcxt.top/Article/details/gt2beombhjn.html

Ruby: Marshal.dump(obj)
来源：http://dali.birdmap.top/Article/details/gt2qmuigfcx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gt2vevcyzao.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2fwnwkfcr.html

L. 网络请求
来源：http://dali.nanxuanxn.top/Article/details/gt2algynvyl.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2fkzvrbtl.html

[L01] 发送 GET 请求
来源：http://dali.chenjidiqi.icu/Article/details/gt2ozanessp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgufenzy.top/Article/details/gt2vhwkcfic.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgfzy.top/Article/details/gt2vjcdwbhf.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gt2hxgejwww.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gt2ghrgqlek.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhoulong.xyz/Article/details/gt2rtsxtwzk.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gt2colzutpw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.kuanghao11.cn/Article/details/gt2vqpqkpzo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zycfv.cn/Article/details/gt2sgfgqwvy.html

[L02] 发送 POST JSON
来源：http://dali.gzhubu.top/Article/details/gt2tplinhwc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gt2yrmcrxvg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgszavi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2jpslkpsr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2hzatwxqj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yafzxhma.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258.top/Article/details/gt2rzwoxpxm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yueranfly.top/Article/details/gt2ybevegjz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258888.top/Article/details/gt2fzwjajyh.html

[L03] 设置自定义请求头
来源：http://dali.yuxming.cn/Article/details/gt2zjbupyct.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sxryk.cn/Article/details/gt2bunwvtma.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2waoccasn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gt2ixdmhpff.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gt2hprxzfnf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ybcxt.top/Article/details/gt2pzcuuulx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gt2fzqlkmbn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhixingplan.top/Article/details/gt2gzjxtkjg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gt2ogclwkil.html

[L04] 设置超时
来源：http://dali.tianlin.xyz/Article/details/gt2eilwdsug.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fengsongda.top/Article/details/gt2uoebbmiy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ihvfznmk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gt2avodqyyi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gt2vquweyhm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guowangkeji.top/Article/details/gt2gbfnpwbg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.smart0.xyz/Article/details/gt2lppaueey.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sufxvd.cn/Article/details/gt2zuzipeho.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hywenlv.cn/Article/details/gt2qtlxgiuo.html

[L05] 上传文件（multipart）
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzwjyiwr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gaohongyu789.top/Article/details/gt2lozajqyc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2brcggdyn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gt2bboabuyk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gt2wcibkqil.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.svipenyu.cn/Article/details/gt2csnepuyx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nwbrower.top/Article/details/gt2iiewybbg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ybcxt.top/Article/details/gt2iqzdoxpp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2eiiwraom.html

[L06] 解析响应为 JSON
来源：http://dali.daria6918.cn/Article/details/gt2glwkyhlr.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2qjjjmgvk.html

PHP:  json_decode($body, true);
来源：http://dali.dianchejie.cn/Article/details/gt2lrrhmxtz.html

JS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2paqdkduw.html

TS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gt2biwpaiqh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2xqfvgafc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gt2dccuajgt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yongpay.top/Article/details/gt2ouvebdpy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gt2vmezxdin.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ktynqcse.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shangyingyoupin.top/Article/details/gt2cxfdhbcm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sysykeji.top/Article/details/gt2ztrwmees.html

JS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gt2qzuubtpu.html

TS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gt2halaljrf.html

Java: resp.statusCode()
来源：http://dali.meibo888.top/Article/details/gt2tmbxgizl.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gt2hxyxxqan.html

Ruby: resp.code.to_i
来源：http://dali.redwolf501.top/Article/details/gt2obbjbchr.html

C#:   (int)resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gt2pvzwjddz.html

[L08] 并发请求多个地址
来源：http://dali.ehwqpu.com/Article/details/gt2ahhqbhtz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tanke756.top/Article/details/gt2wgnaxhwt.html

PHP:  curl_multi_init() 系列
来源：http://dali.fengsongda.top/Article/details/gt2ekxwuwun.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2dffrczbl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gt2hbgitxoa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gt2fgxkaofb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.9152youxi.cn/Article/details/gt2xwwxvasy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mianzesl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuanzx.com/Article/details/gt2nzvlsmgx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezzuzdai.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gt2ztxlxzfg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2xttkgxff.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gt2voqqhkjq.html

Py:   sys.argv[1:]
来源：http://dali.yvedp.cn/Article/details/gt2kcuklobu.html

PHP:  $argv;  $argc;
来源：http://dali.guowangkeji.top/Article/details/gt2dpexxiuw.html

JS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gt2gszgmzlx.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2gxznxbwl.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hgkwepym.html

Go:   os.Args[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwjyorxe.html

Ruby: ARGV
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2blibdmve.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gt2lqzbtaaq.html

[M02] 读取环境变量
来源：http://dali.yj202588.top/Article/details/gt2eczliaov.html

Py:   os.environ.get("HOME")
来源：http://dali.ivvv.top/Article/details/gt2iugjwpde.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gt2iumbmuru.html

JS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gt2ercvbryd.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gt2mhzzjfcq.html

Java: System.getenv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ohzxvjqu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.birdmap.top/Article/details/gt2qrhzzmjn.html

Ruby: ENV["HOME"]
来源：http://dali.jlsjyb.cn/Article/details/gt2odqfkfbs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.redwolf501.top/Article/details/gt2dyknvepv.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gt2dqnpjbex.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhengqikj.top/Article/details/gt2irmjzabd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hfpthk.cn/Article/details/gt2syntvmcn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gt2mcnhxgyn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gt2olewdgwa.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuanzhike.top/Article/details/gt2ffzetnpg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gt2jweineya.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ydzc1.top/Article/details/gt2ozugvmcq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gt2lvklxqqn.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gt2jxgqthpv.html

Py:   os.getcwd()
来源：http://dali.iojbl.cn/Article/details/gt2kwsagtek.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gt2sppdyffk.html

JS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gt2hpadlmpe.html

TS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gt2ofsnzofr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenlongwang.top/Article/details/gt2egfdkzmj.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gt2lriwbgji.html

Ruby: Dir.pwd
来源：http://dali.ppjwa.cn/Article/details/gt2uclcnpzc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.vqdsnc.cn/Article/details/gt2ssolcney.html

[M05] 设置退出码
来源：http://dali.dianchejie.cn/Article/details/gt2tylvvbgn.html

Py:   sys.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2xavxsvns.html

PHP:  exit(1);
来源：http://dali.tanke756.top/Article/details/gt2hzselzzc.html


<!-- 参考信息 -->