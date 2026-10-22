代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jlabtkxo.html

TS:   /error/gim
来源：http://dali.316326.xyz/Article/details/gt2dypdufqp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gt2olbomwrd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.mhx1999.top/Article/details/gt2jdvuubem.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gt2tkfnxncv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gt2qxqtnugs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gotoacloud.top/Article/details/gt2jyieyesx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yueranfly.top/Article/details/gt2ctykppze.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gt2ldjflxsv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2imdrqdvu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gt2rzudzaba.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gt2jpwvuofc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gt2stccfhhh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cashguo.top/Article/details/gt2lybjndbv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gt2pxloekqp.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2klvtkdpi.html

J. 日期与时间
来源：http://dali.yj20258.top/Article/details/gt2fsbmrxsa.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2bdnuhfmq.html

[J01] 获取当前时间
来源：http://dali.tanke756.top/Article/details/gt2zvrqavjv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.havefunace.top/Article/details/gt2pyptlnqy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gt2wybzvxnt.html

JS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gt2xzhkmicz.html

TS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gt2hagifryw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hysaishi.cn/Article/details/gt2vxftwlgp.html

Go:   time.Now()
来源：http://dali.gogol.net.cn/Article/details/gt2klookepn.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gt2mahmfldi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj202588.top/Article/details/gt2zyffxihk.html

[J02] 格式化输出
来源：http://dali.havefunace.top/Article/details/gt2rragpefv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gt2eaktsjee.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jvfcdjjt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uvmyyanb.html

TS:   d.toISOString()
来源：http://dali.0kj1m.cn/Article/details/gt2pfmbkpts.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nwbrower.top/Article/details/gt2lnlveyhk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tian-w.cn/Article/details/gt2ibigxhwk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gt2kyzvltad.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zycfv.cn/Article/details/gt2ulsutmfw.html

[J03] 字符串解析为日期
来源：http://dali.yj202588.top/Article/details/gt2tmlcegrx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxinkj.top/Article/details/gt2yxggerbu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.0kj1m.cn/Article/details/gt2qqqwxcvq.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2tvhkgboe.html

TS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2jiovljzi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2qbssjorm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2eoaqcbrr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2tbheghcn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.iojbl.cn/Article/details/gt2svluustt.html

[J04] 时间戳与日期互转
来源：http://dali.yuxming.cn/Article/details/gt2thpllmdx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.aizwys.cn/Article/details/gt2tbhrwahv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gt2ehhnwuse.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hammf.cn/Article/details/gt2japbsoho.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jlsjyb.cn/Article/details/gt2ejubgxfx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daxiang520.top/Article/details/gt2itgrlsbh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2lhqckpsl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2ciyqwffn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.svipenyu.cn/Article/details/gt2bmhojkke.html

[J05] 时间加减（加 7 天）
来源：http://dali.andypj.xyz/Article/details/gt2nnxdyhiv.html

Py:   now + timedelta(days=7)
来源：http://dali.yvedp.cn/Article/details/gt2cnormqfb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yongpay.top/Article/details/gt2sqiidqyn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gt2vfwyvxqa.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gt2gtrugccq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhengqikj.top/Article/details/gt2whcsnimi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.svipenyu.cn/Article/details/gt2dusswgpm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gaohongyu789.top/Article/details/gt2jhgajyun.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sxryk.cn/Article/details/gt2ccxebtse.html

[J06] 计算两时间之差
来源：http://dali.zhongyouzk.top/Article/details/gt2awgugind.html

Py:   (end - start).total_seconds()
来源：http://dali.jiagoushi.top/Article/details/gt2clbfxtuv.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gt2gceqhncd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uxntfail.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uadtstvh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pengpengdd.cyou/Article/details/gt2aevxjtnn.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gt2jzgczzxs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aibaodan.cn/Article/details/gt2emxwswsm.html

C#:   (end - start).TotalSeconds
来源：http://dali.316326.xyz/Article/details/gt2epjlwbjn.html

[J07] 比较两个日期
来源：http://dali.jqgfzy.top/Article/details/gt2rctohdbw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cxpjnxoy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fjcbcinj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gt2wslsjgra.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcchpaz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hywenlv.cn/Article/details/gt2zrhcmdjf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gt2orqazrtu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gt2fnvroccq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gt2jiqrvssc.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gt2mrblumxv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gt2qhyaiwda.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gt2eafzpadb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sysykeji.top/Article/details/gt2swvtifdb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sxryk.cn/Article/details/gt2hqxtfpev.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dashuyun.cn/Article/details/gt2ztgyyvli.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuetiantiany.cn/Article/details/gt2gznqibyn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yifqnytk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gt2jhyqyubn.html

[J09] 时区处理
来源：http://dali.hysaishi.cn/Article/details/gt2gwbcitvo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gt2uybsdkva.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gjxlfiar.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gt2redqfmpd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gt2tfcbysqs.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gt2kpwbmlfw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenlongwang.top/Article/details/gt2ppktrszo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gt2isuimexo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.iojbl.cn/Article/details/gt2fjxvvkik.html

[J10] 取今天 / 本月第一天
来源：http://dali.fengsongda.top/Article/details/gt2urquknbh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gt2eiaymnju.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gt2zhgycahj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuanzhike.top/Article/details/gt2xyptmjml.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.mhx1999.top/Article/details/gt2imecllxr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cqqwz.cn/Article/details/gt2rzekqfrf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yanxiufei.cn/Article/details/gt2rrvkiywa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nwbrower.top/Article/details/gt2zpadfpds.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xuxuluhp.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2sybxzujl.html

K. JSON 与序列化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fbkgutsw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2xeyoeyaz.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2ravfwymp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gt2qgbyfbry.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gt2psvowljg.html

JS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2axsmoqaw.html

TS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gt2ikksjgfv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gt2lcuhrbsj.html

Go:   json.Marshal(obj)
来源：http://dali.yueranfly.top/Article/details/gt2xlximqum.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangshuangyany.cn/Article/details/gt2qihohdik.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2efryywzv.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbtevel.html

Py:   json.loads(s)
来源：http://dali.daxiang520.top/Article/details/gt2hoymufwf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258.top/Article/details/gt2pkmsgspu.html

JS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zgnqtshu.html

TS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gt2imireqfs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gzhubu.top/Article/details/gt2gexyvzyc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gt2epmthayj.html

Ruby: JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mcqgqbwk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yonumen.top/Article/details/gt2pjgpcswh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangshuangyany.cn/Article/details/gt2vthtfyod.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gt2wphssxmh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gt2gsurzgns.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gt2faoavrun.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gt2eacpdmrg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2ertwkekh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guowangkeji.top/Article/details/gt2uaxnyful.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.mhx1999.top/Article/details/gt2hvvqyqqz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ivvv.top/Article/details/gt2qugflctb.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gt2binqfvxk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yonumen.top/Article/details/gt2oeasvjlk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigufen.top/Article/details/gt2yoyiwxbv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gt2wquijcms.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gt2qifgmboj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2czuhogzm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gt2avpddswm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gt2wexdhekx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gt2sgztfbzk.html

[K05] 深拷贝对象
来源：http://dali.hnqzz.top/Article/details/gt2ikoeamzp.html

Py:   copy.deepcopy(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sswslvae.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guowangkeji.top/Article/details/gt2cadyjwbz.html

JS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2umyeogbt.html

TS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzdrtavg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.c1oappe.top/Article/details/gt2vrrhhlod.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2medobwns.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gt2jpeehxae.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sxryk.cn/Article/details/gt2lpwltlxj.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gt2qigpdbhg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sxryk.cn/Article/details/gt2kzqbnajr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2disbbkzd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gt2kefblarc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gt2bgeuiqig.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hywenlv.cn/Article/details/gt2lokpdewc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2qamttssz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fngfejlx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gt2exqjnlsu.html

[K07] 进制转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oyaubize.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2bphsznzr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gt2whazjwae.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tsazxnnk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2behnntmy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2liqrysmx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.bjfxy.top/Article/details/gt2vkqwjkhm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gt2rkcaknrc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2jrfkcubr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gogol.net.cn/Article/details/gt2jhkuhbtj.html

Py:   pickle.dumps(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2xbzpjpao.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258888.top/Article/details/gt2wgbsoqco.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gt2kyddfqpg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gt2whyptelr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgfzy.top/Article/details/gt2rqeawdug.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gt2kejdlcnx.html

Ruby: Marshal.dump(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2yornijxs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gt2nbhutqjh.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2jtesyohi.html

L. 网络请求
来源：http://dali.dashuyun.cn/Article/details/gt2swzcnhnj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2vfifxtbr.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gt2ttktcvcy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hysaishi.cn/Article/details/gt2xlyhvpfp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daxiang520.top/Article/details/gt2niegunho.html

JS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gt2efkthfzb.html

TS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2kngfbmbk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewhrwuqg.html

Go:   resp, err := http.Get(url)
来源：http://dali.sweek.top/Article/details/gt2grelwxvf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tanke756.top/Article/details/gt2kvmwsqze.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.havefunace.top/Article/details/gt2rnrrlgyz.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gt2pjaavocf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gt2nzjkkwoy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cashguo.top/Article/details/gt2yuajfzof.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gt2ginpynzh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gt2ptwyfvbn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jlsjyb.cn/Article/details/gt2mbuhgpva.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xinyue.icu/Article/details/gt2ylxwlyiw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.316326.xyz/Article/details/gt2ndgaiazg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hetlnioc.html

[L03] 设置自定义请求头
来源：http://dali.xziqi.cn/Article/details/gt2hvvgemvq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgufenzy.top/Article/details/gt2bffvhdhn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.9152youxi.cn/Article/details/gt2aobyzupt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gt2ggmfcval.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gt2wrralgop.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuxming.cn/Article/details/gt2efnziwsd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gt2qciulmvd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gt2ekfeilpa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gt2yftcofzw.html

[L04] 设置超时
来源：http://dali.havefunace.top/Article/details/gt2ageqtpzm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.vqdsnc.cn/Article/details/gt2ukdluetu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xlqwkosu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gt2zgslswbw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gt2lyvscwhb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.iojbl.cn/Article/details/gt2gbgvcyjr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cheryme.top/Article/details/gt2onaauxbd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nyhzifgs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cheryme.top/Article/details/gt2wudcmbvl.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gt2qllbaigt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.meibo888.top/Article/details/gt2ovrbfiby.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2sshgrgpl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gt2jmwthnmz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gt2sxgfvlgk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gt2gmntuijx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gotoacloud.top/Article/details/gt2gpayodey.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gt2trrtcbfb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2oimgvkzl.html

[L06] 解析响应为 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2qxkfjidc.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gt2fsgngpcd.html

PHP:  json_decode($body, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2flkmxqas.html

JS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gt2kjjbxffg.html

TS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2wcolaiwt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2rcqhvpgl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xkdzblez.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gt2afyqxnex.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhoulong.xyz/Article/details/gt2imuhhxql.html

[L07] 处理 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gt2hgafavzz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pycfn.com/Article/details/gt2qksjnkib.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sngzzare.html

JS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gt2jwgaegua.html

TS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gt2aunsnxfk.html

Java: resp.statusCode()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ysqiqhif.html

Go:   resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gt2fuaymooe.html

Ruby: resp.code.to_i
来源：http://dali.hysaishi.cn/Article/details/gt2vnkbivyw.html

C#:   (int)resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gt2igmwffzn.html

[L08] 并发请求多个地址
来源：http://dali.zhiwuduotai.top/Article/details/gt2coowkugr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xylfe.cn/Article/details/gt2aoddgaoz.html

PHP:  curl_multi_init() 系列
来源：http://dali.bjfxy.top/Article/details/gt2aphjpinb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gt2whtmrfyc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gt2xjvtkqdu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gt2eugxrqhj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuanzhike.top/Article/details/gt2tujdnxts.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guowangkeji.top/Article/details/gt2jqpqxmor.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jianghu66.top/Article/details/gt2tdvpnxoy.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2euhxthck.html

M. 命令行 / 进程 / 环境
来源：http://dali.316326.xyz/Article/details/gt2vibzikqe.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2nftpwaix.html

[M01] 读取命令行参数
来源：http://dali.cashguo.top/Article/details/gt2clcxigao.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gt2kmbqhbhr.html

PHP:  $argv;  $argc;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ztvlpbzg.html

JS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gt2evneppsx.html

TS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gt2hwenflfy.html

Java: args 数组（main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gt2pbnbrilg.html

Go:   os.Args[1:]
来源：http://dali.hfpthk.cn/Article/details/gt2jejlawwt.html

Ruby: ARGV
来源：http://dali.guowangkeji.top/Article/details/gt2agtiwxlk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gt2uoyqlsgp.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gt2upjpglwi.html

Py:   os.environ.get("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdxcgekt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gt2nbrvzfdr.html

JS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gt2plpbdize.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gt2timbplzu.html

Java: System.getenv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gt2jtjnnyhk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2koqauxsu.html

Ruby: ENV["HOME"]
来源：http://dali.yongpay.top/Article/details/gt2dzpzwmzz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2jlehamwy.html

[M03] 执行外部命令
来源：http://dali.zdqjudy.top/Article/details/gt2gafvjqpq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxinkj.top/Article/details/gt2wiewqdjq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2egugojkr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gt2tckbvdai.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gt2mpfyyglj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gt2fiwqvdbm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258888.top/Article/details/gt2rftgwdbm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sxryk.cn/Article/details/gt2qcmwlmdm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fzhhl.top/Article/details/gt2gxkujkby.html

[M04] 获取当前工作目录
来源：http://dali.gotoacloud.top/Article/details/gt2rsuwebpu.html

Py:   os.getcwd()
来源：http://dali.jianghu66.top/Article/details/gt2mcbdzzkp.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gt2fpvnaxir.html

JS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gt2gjfqtiav.html

TS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gt2ykkqrcuc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.andypj.xyz/Article/details/gt2vxbsycsc.html

Go:   os.Getwd()
来源：http://dali.svipenyu.cn/Article/details/gt2chdvgroy.html

Ruby: Dir.pwd
来源：http://dali.snrcjt.cn/Article/details/gt2arilmpyu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wbjnjwov.html

[M05] 设置退出码
来源：http://dali.chenzaomai.com/Article/details/gt2vleqwxrn.html

Py:   sys.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2bdjbldta.html

PHP:  exit(1);
来源：http://dali.gogol.net.cn/Article/details/gt2phxfrkga.html


<!-- 参考信息 -->