代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gt2jgkcybad.html

[I07] 忽略大小写与多行模式
来源：http://dali.ehwqpu.com/Article/details/gt2lnvberuu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.9152youxi.cn/Article/details/gt2votdpiww.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vhsxntmj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gt2rlicssxb.html

TS:   /error/gim
来源：http://dali.zycfv.cn/Article/details/gt2qnelpqmf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cdnleiting.top/Article/details/gt2jvsocmjo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ydzc1.top/Article/details/gt2urmwuneu.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gt2qxtyakdo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pycfn.com/Article/details/gt2ctwvksln.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shzxlz.cn/Article/details/gt2ngpgbjvm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.mhx1999.top/Article/details/gt2cnrwnuog.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gt2plegvrmz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gt2huzhsbun.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gt2ygbmiqay.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gt2iprupqwk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gt2nxvcwvpo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pycfn.com/Article/details/gt2loxamskm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gt2ktwnkami.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2fluaynnr.html

J. 日期与时间
来源：http://dali.cdnleiting.top/Article/details/gt2zkremrxt.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2dihcvfdq.html

[J01] 获取当前时间
来源：http://dali.jqgufenzy.top/Article/details/gt2dytrahxt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ccojmuzt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gt2vqyugbyd.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gt2lfdunyfk.html

TS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gt2bhwqjmov.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.haohaochexian.top/Article/details/gt2nkerhtjf.html

Go:   time.Now()
来源：http://dali.jqgfzy.top/Article/details/gt2vrnnohsk.html

Ruby: Time.now
来源：http://dali.nanxinkj.top/Article/details/gt2vocxlbyl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cucudq.cn/Article/details/gt2ebajloxs.html

[J02] 格式化输出
来源：http://dali.yonumen.top/Article/details/gt2bdvfdzlo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gt2hsyalydi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gt2vusjxhct.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2opwamqxg.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gt2fxpcbupu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cqqwz.cn/Article/details/gt2ithwoyta.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nwbrower.top/Article/details/gt2icvyoose.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lhfakttn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnxiangtu.top/Article/details/gt2syrzctgl.html

[J03] 字符串解析为日期
来源：http://dali.wangdashe.top/Article/details/gt2mzkatbyx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.0kj1m.cn/Article/details/gt2dfupuuox.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgfzy.top/Article/details/gt2sfsimvea.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2orlqazcd.html

TS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2dbyajuup.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2gohauleu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2hbnxreda.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2uexpviau.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dhugkljr.html

[J04] 时间戳与日期互转
来源：http://dali.chenlongwang.top/Article/details/gt2hdguuemr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2anevgmbg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gotoacloud.top/Article/details/gt2mgkzxvtj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xziqi.cn/Article/details/gt2bsndjpoz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.quarkkingdee.top/Article/details/gt2dbnuzofx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2zobslfwh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2qtzpqvrp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gt2igtjgshy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2xbtfnktg.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljqgqbzx.html

Py:   now + timedelta(days=7)
来源：http://dali.gogol.net.cn/Article/details/gt2fztreins.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yueranfly.top/Article/details/gt2jvjbqhzu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gt2rpndkffb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gt2ilutotep.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.c1oappe.top/Article/details/gt2hsjrpxig.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gt2lsqoknsx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gt2qzeayaah.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daria6918.cn/Article/details/gt2opsavwte.html

[J06] 计算两时间之差
来源：http://dali.gotoacloud.top/Article/details/gt2smfdudbd.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2aejwlawm.html

PHP:  $end->diff($start)->days;
来源：http://dali.pycfn.com/Article/details/gt2ozehondp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigfzy.top/Article/details/gt2coohnhpv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gt2kkifwimm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.redwolf501.top/Article/details/gt2xtnuxosd.html

Go:   end.Sub(start).Hours()
来源：http://dali.ydzc1.top/Article/details/gt2pmfhbnao.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhixingplan.top/Article/details/gt2jyhnoirs.html

C#:   (end - start).TotalSeconds
来源：http://dali.xinyue.icu/Article/details/gt2wzzebkab.html

[J07] 比较两个日期
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jnwgvosc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gt2nbbbhbau.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.svipenyu.cn/Article/details/gt2zkeingrn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gt2ilwqmsxk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gt2elyywdoy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.birdmap.top/Article/details/gt2fgjvvjwn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.havefunace.top/Article/details/gt2fuhwjecj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2kbwcdnrq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gt2evonzkan.html

[J08] 提取年月日与星期
来源：http://dali.zhongyouzk.top/Article/details/gt2kdmcgdmm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.feifeiyinyue.top/Article/details/gt2cyzlgxsl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhoulong.xyz/Article/details/gt2mdajmqgo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.9152youxi.cn/Article/details/gt2ifrlrffu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuxming.cn/Article/details/gt2zrowmzvq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hongshengwenyu.top/Article/details/gt2jdvjqwnl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yueranfly.top/Article/details/gt2ucckrzjw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sxryk.cn/Article/details/gt2baiupyye.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.andypj.xyz/Article/details/gt2fdvnbkbl.html

[J09] 时区处理
来源：http://dali.nanxinkj.top/Article/details/gt2pufqykzk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.haohaochexian.top/Article/details/gt2elcvrbyl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cashguo.top/Article/details/gt2wdmdxugy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gt2ppjipych.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kssnuyfd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhixingplan.top/Article/details/gt2jewocaak.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uqdsraxp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.kuanghao11.cn/Article/details/gt2nwyeohtc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gt2kddpnsom.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gt2cehrjvkz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gt2kyhfjesu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gqzjrfxx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gt2rkxfdfof.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fzhhl.top/Article/details/gt2fziigirn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yonumen.top/Article/details/gt2pizfprmu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tianlin.xyz/Article/details/gt2bqezcieq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gogol.net.cn/Article/details/gt2nwauoqaz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.iojbl.cn/Article/details/gt2jhxdcdft.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2wtzgrtdc.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gt2lwlmohkv.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ivcirrmo.html

[K01] 对象转 JSON 字符串
来源：http://dali.316326.xyz/Article/details/gt2xrbfsxlx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gt2rwtecawl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gt2zoidocnk.html

JS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gt2ekrdmfds.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2wetogocf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigfzy.top/Article/details/gt2oixqakjc.html

Go:   json.Marshal(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rgxsdqod.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hysaishi.cn/Article/details/gt2okcpfoht.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuanzx.com/Article/details/gt2gzguviti.html

[K02] JSON 字符串转对象
来源：http://dali.birdmap.top/Article/details/gt2rnwngilk.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gt2cfqucpru.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.c1oappe.top/Article/details/gt2zyksapiz.html

JS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gt2psbihegs.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gt2rrvntnxm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pxtuqswy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkuuxgp.html

Ruby: JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2prvbcnvj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nwbrower.top/Article/details/gt2bjvuxjdk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hfpthk.cn/Article/details/gt2tsqwewne.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gt2gsaewfql.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2hdfyvgkw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gt2teoyerix.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gt2cjrawoae.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2krwbtgfx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuanzhike.top/Article/details/gt2gfjfyilc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gt2dqhzrqzc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhoulong.xyz/Article/details/gt2iijbukhi.html

[K04] 读取 JSON 文件
来源：http://dali.kuanghao11.cn/Article/details/gt2paldstij.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2grmarafr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aizwys.cn/Article/details/gt2esteqguy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gt2ofdfkwnz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gt2jfutsifz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gt2iirmgysx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gt2lnmozjri.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gt2iqxzhwmh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuxming.cn/Article/details/gt2ozncgcrm.html

[K05] 深拷贝对象
来源：http://dali.shuidangran.top/Article/details/gt2uiezmoqd.html

Py:   copy.deepcopy(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2ljqllypa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj202588.top/Article/details/gt2rzaewmkt.html

JS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2itptdmtp.html

TS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gt2zffnwgbw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.316326.xyz/Article/details/gt2wfulcasl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gaohongyu789.top/Article/details/gt2rgzuytbt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xylfe.cn/Article/details/gt2mwuufbkk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jlsjyb.cn/Article/details/gt2xskjunav.html

[K06] 解析 URL 查询串
来源：http://dali.jianghu66.top/Article/details/gt2dpbkthnx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shuidangran.top/Article/details/gt2bfvcrdwl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.0kj1m.cn/Article/details/gt2wkbndfva.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gt2takbhgnh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gt2uoxqzied.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gt2zvtzetnd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gt2cphsrsnz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gt2jagxyqlo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hkamtjhr.html

[K07] 进制转换
来源：http://dali.ppjwa.cn/Article/details/gt2fousmhfr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2rnwiqjsk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sufxvd.cn/Article/details/gt2fmmyyejf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kdcnoqfk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2jeceaijb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2udfgxypq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gaohongyu789.top/Article/details/gt2qincqzbc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.meibo888.top/Article/details/gt2cdcvzsut.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rjbwolwb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.bjfxy.top/Article/details/gt2wcbmgwol.html

Py:   pickle.dumps(obj)
来源：http://dali.iojbl.cn/Article/details/gt2amhcizgk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.bjfxy.top/Article/details/gt2dgqodbqa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gt2njrjdsws.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2kigasavj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.mhx1999.top/Article/details/gt2desbmnmi.html

Go:   encoding/gob
来源：http://dali.yuxming.cn/Article/details/gt2nscwtjla.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuanzx.com/Article/details/gt2zqjrzcef.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gt2wrtwjnvp.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2msnerfay.html

L. 网络请求
来源：http://dali.wangshuangyany.cn/Article/details/gt2hyenneeo.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2zqzqmbkm.html

[L01] 发送 GET 请求
来源：http://dali.aizwys.cn/Article/details/gt2nkasezli.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.haohaochexian.top/Article/details/gt2sdoxtegk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.vqdsnc.cn/Article/details/gt2qjfwdaki.html

JS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gt2nhwlmorv.html

TS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gt2dxgmupwo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hongshengwenyu.top/Article/details/gt2zjzghimt.html

Go:   resp, err := http.Get(url)
来源：http://dali.cheryme.top/Article/details/gt2gvevtjlw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yanxiufei.cn/Article/details/gt2oojfdssg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.meibo888.top/Article/details/gt2zldicqzw.html

[L02] 发送 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gt2aepaxevf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sxryk.cn/Article/details/gt2oayznmpm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gzhubu.top/Article/details/gt2wkkvyinj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gt2rrmarjaj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gt2nkxovnvz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gt2pgrrsspu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nwbrower.top/Article/details/gt2fhiizadc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.svipenyu.cn/Article/details/gt2ghlhxhrb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gt2nqcmrkbu.html

[L03] 设置自定义请求头
来源：http://dali.smart0.xyz/Article/details/gt2wuynadyu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ppjwa.cn/Article/details/gt2ingwebpw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cqqwz.cn/Article/details/gt2ebhigbeq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gt2qrxfenrc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgreyvyf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cucudq.cn/Article/details/gt2wtaayctm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gt2ispkhdce.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuanzhike.top/Article/details/gt2nwiazlvz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gt2ndotyhqj.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gt2sflrxsjo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hfpthk.cn/Article/details/gt2mxfobwgg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mysboehz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gt2ydrbftbl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gt2qplxejet.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2nshezvus.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.meibo888.top/Article/details/gt2nfttspej.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cheryme.top/Article/details/gt2frzaxept.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhengqikj.top/Article/details/gt2vahysqlt.html

[L05] 上传文件（multipart）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dttrsckt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmptiagb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgfzy.top/Article/details/gt2lixjwcwo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gt2mvzhvmyr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gt2uzefcvyf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.mhx1999.top/Article/details/gt2qnbzmdkc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258888.top/Article/details/gt2zqammqpu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yueranfly.top/Article/details/gt2qmzewxgm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2ycwqlypg.html

[L06] 解析响应为 JSON
来源：http://dali.ivvv.top/Article/details/gt2kfkygzux.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vclcvbnz.html

PHP:  json_decode($body, true);
来源：http://dali.jyoumei.cn/Article/details/gt2hrlqnplx.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gt2apdxhari.html

TS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xgxpqfbu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2feguqfnh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guowangkeji.top/Article/details/gt2gimihyhq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gt2utwdthum.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nqpazeuk.html

[L07] 处理 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gt2lkavlsfs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pryhkmss.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj202588.top/Article/details/gt2naobdbrx.html

JS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gt2kbvxddjp.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxryeihd.html

Java: resp.statusCode()
来源：http://dali.aizwys.cn/Article/details/gt2tohmwfwq.html

Go:   resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gt2nzmawuxf.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gt2zvmaqgge.html

C#:   (int)resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gt2uitnpefu.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gt2sunudifv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gt2howmsvuc.html

PHP:  curl_multi_init() 系列
来源：http://dali.316326.xyz/Article/details/gt2qmhgteim.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gt2tpfnchyw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2muefliss.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.redwolf501.top/Article/details/gt2mlxuxksf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.birdmap.top/Article/details/gt2gvysuyvr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gt2aegfstiv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zycfv.cn/Article/details/gt2azrrjtjn.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wzawlwtx.html

M. 命令行 / 进程 / 环境
来源：http://dali.hfpthk.cn/Article/details/gt2nifhadme.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jghfiodc.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2tfxhuirh.html

Py:   sys.argv[1:]
来源：http://dali.svipenyu.cn/Article/details/gt2oikfjwdm.html

PHP:  $argv;  $argc;
来源：http://dali.sweek.top/Article/details/gt2xrttkojn.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qbmwsmfr.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gt2ddithson.html

Java: args 数组（main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gt2nxzhgfji.html

Go:   os.Args[1:]
来源：http://dali.hnqzz.top/Article/details/gt2mdscvazn.html

Ruby: ARGV
来源：http://dali.hfpthk.cn/Article/details/gt2vupjddiq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gt2buphjprm.html

[M02] 读取环境变量
来源：http://dali.tanke756.top/Article/details/gt2tjzxcdek.html

Py:   os.environ.get("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2tmmggkzt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwjlbpmj.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wkgueutf.html

TS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gt2wqxttmho.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2zxlpmdpy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pkbzztme.html

Ruby: ENV["HOME"]
来源：http://dali.316326.xyz/Article/details/gt2rwqjvuos.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2ifsvcsgu.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gt2jpzfkwbg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenjidiqi.icu/Article/details/gt2unhubwvg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.316326.xyz/Article/details/gt2tymolwno.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gt2ycibrcxx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gt2ndfrchkq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gt2nscrbxrx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigfzy.top/Article/details/gt2lwmpukfk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuanzx.com/Article/details/gt2vpgqwywc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tianlin.xyz/Article/details/gt2zojlbwlp.html

[M04] 获取当前工作目录
来源：http://dali.zhongyouzk.top/Article/details/gt2duhangrj.html

Py:   os.getcwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gvpdzoas.html

PHP:  getcwd();
来源：http://dali.tian-w.cn/Article/details/gt2ydihyfef.html

JS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gt2fdergkuv.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gt2hemqpzuy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hongshengwenyu.top/Article/details/gt2scauqjzy.html

Go:   os.Getwd()
来源：http://dali.hfpthk.cn/Article/details/gt2ichzgril.html

Ruby: Dir.pwd
来源：http://dali.nanxinkj.top/Article/details/gt2dtlfzrxl.html


<!-- 参考信息 -->