代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gtqffxfjac.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gtctugneio.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhixingplan.top/Article/details/gtxuhnvfdr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuetiantiany.cn/Article/details/gtzeslilyh.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxnoqpam.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zycfv.cn/Article/details/gttqehsewb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gtezvtqdld.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cucudq.cn/Article/details/gtazepvjaz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gtkmzfolem.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gtqlqoprrw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gtcptgkmkj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gtgtvlqmud.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.snrcjt.cn/Article/details/gtwssjbgbr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.kuanghao11.cn/Article/details/gtidkdksot.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gthlqalzsi.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtfotyebvk.html

J. 日期与时间
来源：http://dali.zhoulong.xyz/Article/details/gtlkvojhyb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtsvwtaxye.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcvecfxv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrqbionn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtctgdiszt.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtssihzsch.html

TS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgzpgmiz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnqzz.top/Article/details/gthklnglhq.html

Go:   time.Now()
来源：http://dali.zhixingplan.top/Article/details/gtajzjtfeg.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gtsxfmcwtw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dianchejie.cn/Article/details/gtxnnbcjuk.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gthmcaptfm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtyiowdnzv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtqzzqqalc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzpryukv.html

TS:   d.toISOString()
来源：http://dali.andypj.xyz/Article/details/gtjztdrjwb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hongshengwenyu.top/Article/details/gtzpzncejr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gotoacloud.top/Article/details/gtlwjtlucl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gtdhtennmu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gtkmlfvsic.html

[J03] 字符串解析为日期
来源：http://dali.shzxlz.cn/Article/details/gtkrwvqlgq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ydzc1.top/Article/details/gtfmiuojkq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuanzhike.top/Article/details/gtzqglolme.html

JS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtywleruqo.html

TS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtxxwkzmzd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtximvxeho.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtlwjmzsiw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtmbpjgtrt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosdagvpk.html

[J04] 时间戳与日期互转
来源：http://dali.hammf.cn/Article/details/gtxvgzzpgw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangdashe.top/Article/details/gtxlbgmzqw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.iojbl.cn/Article/details/gtzevybhjq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdumnelov.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkhlxsbx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.smart0.xyz/Article/details/gtziosxnsl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jianghu66.top/Article/details/gtbgrlzjmp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gtflhitkzn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xinyue.icu/Article/details/gtttblodtw.html

[J05] 时间加减（加 7 天）
来源：http://dali.pycfn.com/Article/details/gtledztrhe.html

Py:   now + timedelta(days=7)
来源：http://dali.tanke756.top/Article/details/gtzqlpxjsd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cqqwz.cn/Article/details/gtuiyuohsv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gtvbfvgnpa.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtxvyvtxck.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtgozgduak.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnxiangtu.top/Article/details/gthwsnpqsv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yongpay.top/Article/details/gtbygflgul.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtauhhebca.html

[J06] 计算两时间之差
来源：http://dali.tian-w.cn/Article/details/gtspelmeic.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgufenzy.top/Article/details/gtcgsmxpmy.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj202588.top/Article/details/gttuyqjgvh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hammf.cn/Article/details/gtdcnkjyfe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shuidangran.top/Article/details/gtdksqxepz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.svipenyu.cn/Article/details/gtbuxsepac.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gtenxgzqdg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sufxvd.cn/Article/details/gtpxkrfhol.html

C#:   (end - start).TotalSeconds
来源：http://dali.zdqjudy.top/Article/details/gtnsozfili.html

[J07] 比较两个日期
来源：http://dali.hfpthk.cn/Article/details/gtaajwcoii.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtxkkjdcmc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.iojbl.cn/Article/details/gtqwruxiyx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gtexfilmqs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gtozzusnkx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.316326.xyz/Article/details/gthquexsez.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hfpthk.cn/Article/details/gtveupzncj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtnlffievi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtnkljuunz.html

[J08] 提取年月日与星期
来源：http://dali.zhiwuduotai.top/Article/details/gtzxyrskvh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gtgbxymwoa.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhengqikj.top/Article/details/gtjfbnztvp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shangyingyoupin.top/Article/details/gtkjzgulst.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gtlgadyjsj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aibaodan.cn/Article/details/gtmzojfbdh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sxryk.cn/Article/details/gtliwunaxr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplloixzq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daxiang520.top/Article/details/gteousxrfh.html

[J09] 时区处理
来源：http://dali.shangyingyoupin.top/Article/details/gtuvaaycuv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gtaykavnmo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgfzy.top/Article/details/gtxdeipaoh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gtnszlygyn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtazuvmoyd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gtqbbcykqk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xinyue.icu/Article/details/gtimwygxjm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yanxiufei.cn/Article/details/gtvxhxbsdv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigfzy.top/Article/details/gtfehdleag.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gtscordcrb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigfzy.top/Article/details/gttvksgatx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yanxiufei.cn/Article/details/gtfbiclqdc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtuhxytgku.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gtgzhboujt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.svipenyu.cn/Article/details/gttxwefxcw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cashguo.top/Article/details/gtdamherqb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ppjwa.cn/Article/details/gtaiwgypth.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gotoacloud.top/Article/details/gtpjblrpej.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtjkscxemu.html

K. JSON 与序列化
来源：http://dali.smart0.xyz/Article/details/gtptwnkztu.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtifnsrnpa.html

[K01] 对象转 JSON 字符串
来源：http://dali.cheryme.top/Article/details/gtmvqjjhey.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gtcfuhnfdy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xylfe.cn/Article/details/gtlwljgkyf.html

JS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtuewoxpve.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtsdoxsyyx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hongshengwenyu.top/Article/details/gtfbenfrqy.html

Go:   json.Marshal(obj)
来源：http://dali.wangdashe.top/Article/details/gtzvroeoxx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hfpthk.cn/Article/details/gtebfzgsbk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jianghu66.top/Article/details/gtzbpudwgb.html

[K02] JSON 字符串转对象
来源：http://dali.chenlongwang.top/Article/details/gtowabiafi.html

Py:   json.loads(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtwiqozhhu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuanzhike.top/Article/details/gtajbxfebz.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtsmemxsqo.html

TS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtcoqklfoc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gtiqbthvif.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gtimotpnqa.html

Ruby: JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtrxtrknqm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yongpay.top/Article/details/gtyvismypm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shuidangran.top/Article/details/gtgfdlndtf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gttwtahsau.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulfpcyli.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gtawonqdyq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gtkrmpfiur.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gtqautumwz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gtenvsggcw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gtqjmbolva.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sxryk.cn/Article/details/gtizyucppn.html

[K04] 读取 JSON 文件
来源：http://dali.shuidangran.top/Article/details/gtjzohekdp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gtqjuqbcur.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gtfqnsiwht.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gtbszagczy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtuhbqmepk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtheavlwxb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtkdwmghke.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gtkkpeljqf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258.top/Article/details/gtbxhvmyrv.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gtjonspxpa.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhengqikj.top/Article/details/gtmmzsmneg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cheryme.top/Article/details/gtxeotxytw.html

JS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbydzezl.html

TS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtxbjceqgh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tanke756.top/Article/details/gtbvykudpu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cucudq.cn/Article/details/gtehlqcknz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.vqdsnc.cn/Article/details/gtsexbboyh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aizwys.cn/Article/details/gteqykafqd.html

[K06] 解析 URL 查询串
来源：http://dali.ehwqpu.com/Article/details/gtzkyaolrf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gttnjaxikj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sufxvd.cn/Article/details/gttjooymgf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtxxpnjoxx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gthuoqrmyn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nwbrower.top/Article/details/gtseljbkxz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtaabtgmun.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtxkgvgvbk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gtefpjgkfh.html

[K07] 进制转换
来源：http://dali.ybcxt.top/Article/details/gtukptnttm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtljixltmc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258888.top/Article/details/gtqdslyogm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtownlnnlm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtewpqnhht.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtvpksuynd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ppjwa.cn/Article/details/gtkpfspqzw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jyoumei.cn/Article/details/gtldtodrba.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkyskftb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fengsongda.top/Article/details/gttshvrqeb.html

Py:   pickle.dumps(obj)
来源：http://dali.shuidangran.top/Article/details/gtlvvzvsmz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.9152youxi.cn/Article/details/gtwaitdoeo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gtrrwwwoud.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gtwpgnrzgs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yvedp.cn/Article/details/gtfdyaampw.html

Go:   encoding/gob
来源：http://dali.ivvv.top/Article/details/gtopaqrqkt.html

Ruby: Marshal.dump(obj)
来源：http://dali.tianlin.xyz/Article/details/gtkdmhnjzm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtdoosuqkr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtycnyxwqq.html

L. 网络请求
来源：http://dali.yuxming.cn/Article/details/gtjpxuwttl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtvnhejlcy.html

[L01] 发送 GET 请求
来源：http://dali.shangyingyoupin.top/Article/details/gtwoiukzmd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gaohongyu789.top/Article/details/gtkvzfaxub.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ehwqpu.com/Article/details/gtkefudzay.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtiwirheod.html

TS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gtouzltubl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gtnsitwneu.html

Go:   resp, err := http.Get(url)
来源：http://dali.gzhubu.top/Article/details/gtqhoflhqp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hammf.cn/Article/details/gtfeggwlku.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenzaomai.com/Article/details/gterhfqjfv.html

[L02] 发送 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtddpndbxn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gtzdyznexe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztwcaumn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gtxzlxtcot.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjsupmmz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtvcqhiasd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xylfe.cn/Article/details/gtumffusnm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gtdvqaxfho.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zdqjudy.top/Article/details/gtewkgsqsu.html

[L03] 设置自定义请求头
来源：http://dali.tian-w.cn/Article/details/gtzuwjlusz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gtsnpfmydc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gtpmbwzrpb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gtnfnqoglc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtmwhwfefu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxuanxn.top/Article/details/gtfkljdbox.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gtefrkujlq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhoulong.xyz/Article/details/gtsjkexwij.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gtqgrzcnap.html

[L04] 设置超时
来源：http://dali.ybcxt.top/Article/details/gtcjpdkmju.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhixingplan.top/Article/details/gthqwtkclv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daria6918.cn/Article/details/gteuvzlcnx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gtowlkepeh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtuelyiews.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenlongwang.top/Article/details/gttngajzgq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hfpthk.cn/Article/details/gtyurprmtq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsspwldf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gtfsxofuqw.html

[L05] 上传文件（multipart）
来源：http://dali.yongpay.top/Article/details/gtnadttmdc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guannengcc.top/Article/details/gtsxdixxtg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xylfe.cn/Article/details/gtcrkupluf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gtbytxuikk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gtcsbyemlc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gttlqxnqdy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgufenzy.top/Article/details/gtottlldls.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.vqdsnc.cn/Article/details/gtrwlygcah.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnlblmbx.html

[L06] 解析响应为 JSON
来源：http://dali.nwbrower.top/Article/details/gtneiwzqyk.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtrlzpnkha.html

PHP:  json_decode($body, true);
来源：http://dali.gzhubu.top/Article/details/gtkbckuqhq.html

JS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gtbeiybwev.html

TS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gtsbfqzlra.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtoxqxkeik.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yongpay.top/Article/details/gtiwqcjeou.html

Ruby: JSON.parse(resp.body)
来源：http://dali.meibo888.top/Article/details/gtfpbuesoj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hammf.cn/Article/details/gtawcwzxgp.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtmjfgloyx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dashuyun.cn/Article/details/gteafykigb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xziqi.cn/Article/details/gtbqjwbkzh.html

JS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtuwvbontg.html

TS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrndbbxxa.html

Java: resp.statusCode()
来源：http://dali.ydzc1.top/Article/details/gtoogxatgk.html

Go:   resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtqzrjchdw.html

Ruby: resp.code.to_i
来源：http://dali.chenlongwang.top/Article/details/gtwcnqcaxs.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gthyylvplc.html

[L08] 并发请求多个地址
来源：http://dali.jqgfzy.top/Article/details/gtlcyutphp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj202588.top/Article/details/gtvnlhhvzq.html

PHP:  curl_multi_init() 系列
来源：http://dali.feifeiyinyue.top/Article/details/gtvumjcvyr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtfvsbrleh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtdujopgqf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.smart0.xyz/Article/details/gtfrbvhwdt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gtjipxptts.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sxryk.cn/Article/details/gtcqeweojc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daria6918.cn/Article/details/gtgenukopb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtcufooefa.html

M. 命令行 / 进程 / 环境
来源：http://dali.jlsjyb.cn/Article/details/gtzboorfga.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtvqumaqky.html

[M01] 读取命令行参数
来源：http://dali.fengsongda.top/Article/details/gtgkwqufhi.html

Py:   sys.argv[1:]
来源：http://dali.tianlin.xyz/Article/details/gtjtghayfb.html

PHP:  $argv;  $argc;
来源：http://dali.chenzaomai.com/Article/details/gthooajusl.html

JS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtjoyorvwc.html

TS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gtpyfzoupr.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtekykjwyr.html

Go:   os.Args[1:]
来源：http://dali.aizwys.cn/Article/details/gtqnmmtfqa.html

Ruby: ARGV
来源：http://dali.snrcjt.cn/Article/details/gtyukviydu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqvlqgat.html

[M02] 读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdaobdpxb.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtazfjxvrm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gttfrhldcv.html

JS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gtvfwzxubz.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gttwpoxich.html

Java: System.getenv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsayydpol.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtdvtyqqtq.html

Ruby: ENV["HOME"]
来源：http://dali.hnqzz.top/Article/details/gtwhtaqjjp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aizwys.cn/Article/details/gtfazbxhuj.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gtcyitrhdz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hfpthk.cn/Article/details/gtgleofanp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jlsjyb.cn/Article/details/gtvjmhlpxr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gtzyabtewg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtvugicjsd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnouoqko.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cheryme.top/Article/details/gtlfswwyms.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cqqwz.cn/Article/details/gtrynrhofb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuxming.cn/Article/details/gtvwqmnfhh.html

[M04] 获取当前工作目录
来源：http://dali.xziqi.cn/Article/details/gtehbxngkm.html

Py:   os.getcwd()
来源：http://dali.birdmap.top/Article/details/gthkgnwdzg.html

PHP:  getcwd();
来源：http://dali.yj20258888.top/Article/details/gtcvzdwenz.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtwbnqmnkj.html

TS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtvqmdqkjf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shuidangran.top/Article/details/gtnlmuueuq.html

Go:   os.Getwd()
来源：http://dali.nwbrower.top/Article/details/gtzwrjayqa.html

Ruby: Dir.pwd
来源：http://dali.sxryk.cn/Article/details/gtvqmfimbu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yangfankeji.com/Article/details/gtyvvlacvr.html

[M05] 设置退出码
来源：http://dali.nwbrower.top/Article/details/gtbdhfcmky.html

Py:   sys.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtqgxwsabi.html

PHP:  exit(1);
来源：http://dali.shuidangran.top/Article/details/gtytfcvibo.html


<!-- 参考信息 -->