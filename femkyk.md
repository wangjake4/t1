代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtdgqaqjwr.html

[I07] 忽略大小写与多行模式
来源：http://dali.havefunace.top/Article/details/gtmfkpvfut.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gogol.net.cn/Article/details/gtohgsyqez.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruzyuxbo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhiwuduotai.top/Article/details/gtsuknnvbf.html

TS:   /error/gim
来源：http://dali.guowangkeji.top/Article/details/gtgqgysmrw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jlsjyb.cn/Article/details/gtbgrgqemo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ivvv.top/Article/details/gtbxfeixfw.html

Ruby: s.scan(/error/i)
来源：http://dali.ehwqpu.com/Article/details/gthtnvgslj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gaohongyu789.top/Article/details/gtwpvqdafo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gteavoutse.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.snrcjt.cn/Article/details/gtbzrrpfip.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gtwzsbbxdc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gtjhvywipx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtchgzqnth.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtrgczvbth.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sweek.top/Article/details/gtmstldnhw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hongshengwenyu.top/Article/details/gtxpcvbyoj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtxvhndyco.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtrfrkkhef.html

J. 日期与时间
来源：http://dali.zhiwuduotai.top/Article/details/gtwirwpxpf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtlirwmses.html

[J01] 获取当前时间
来源：http://dali.yongpay.top/Article/details/gtahvmnujg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrghmmvyv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gthwwrtnyn.html

JS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtfmnqtgaq.html

TS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtguqrsfjv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.redwolf501.top/Article/details/gtuuvmxtdh.html

Go:   time.Now()
来源：http://dali.jqgufenzy.top/Article/details/gtwsmggobz.html

Ruby: Time.now
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrawnlco.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gttnmlcekj.html

[J02] 格式化输出
来源：http://dali.zdqjudy.top/Article/details/gtmxqsdbut.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtsxokjbzm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxushgjmd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hysaishi.cn/Article/details/gttkvucmlj.html

TS:   d.toISOString()
来源：http://dali.redwolf501.top/Article/details/gtuuspstde.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cheryme.top/Article/details/gtwhrpevdf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gteqcqydnc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtggoenxlc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sufxvd.cn/Article/details/gtrhpynwob.html

[J03] 字符串解析为日期
来源：http://dali.fzhhl.top/Article/details/gtveveryqf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.haohaochexian.top/Article/details/gtoojzdnve.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gtknmngwam.html

JS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtddgftrjl.html

TS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtwzucmbef.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtzzqmcken.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtjlwveaym.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtotfgfkby.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cheryme.top/Article/details/gtfazmhpyd.html

[J04] 时间戳与日期互转
来源：http://dali.shangyingyoupin.top/Article/details/gtnuvgvtaf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.0kj1m.cn/Article/details/gtwuahfpux.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gzhubu.top/Article/details/gtrdjqjqxd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gtbthmmkuc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhnahkuf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gotoacloud.top/Article/details/gtlkxngknr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.andypj.xyz/Article/details/gtdmrnzxlx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hfpthk.cn/Article/details/gtleppybwh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtgwbrfqjb.html

[J05] 时间加减（加 7 天）
来源：http://dali.gaohongyu789.top/Article/details/gtxoojtpzv.html

Py:   now + timedelta(days=7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnyrwyvxn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenzaomai.com/Article/details/gtgadajojh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtujsguewj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gtcvstgqhj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gtxqlkswfx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yueranfly.top/Article/details/gtyxxpkjog.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgufenzy.top/Article/details/gtlqsvdtbs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zycfv.cn/Article/details/gtnrinezhh.html

[J06] 计算两时间之差
来源：http://dali.hnqzz.top/Article/details/gtvaytxsot.html

Py:   (end - start).total_seconds()
来源：http://dali.hammf.cn/Article/details/gtbmkkwfac.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgufenzy.top/Article/details/gtyhdxuoaz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fengsongda.top/Article/details/gtqqjovxgs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daria6918.cn/Article/details/gtgazrnkrf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.316326.xyz/Article/details/gttnvfolgo.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gtpwsyydgi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jyoumei.cn/Article/details/gtancmiqeh.html

C#:   (end - start).TotalSeconds
来源：http://dali.dashuyun.cn/Article/details/gttzktfbhu.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gthybjrqgy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtrgypxwld.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yueranfly.top/Article/details/gtwkztkmcp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gtiyvlfjeo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gtzfklelnb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtbkruazcj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sysykeji.top/Article/details/gtdtpmnifi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhtdwvdn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gtezuklfuk.html

[J08] 提取年月日与星期
来源：http://dali.jqgufenzy.top/Article/details/gtpcoenccc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gtomzuxvaz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shzxlz.cn/Article/details/gtfbvycdio.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shangyingyoupin.top/Article/details/gtxdzmijwt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gtxdzvhjjt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.svipenyu.cn/Article/details/gtmwgyymdd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangshuangyany.cn/Article/details/gtzthdtyqe.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gtejkdeabd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj202588.top/Article/details/gtfpxhqrhe.html

[J09] 时区处理
来源：http://dali.xziqi.cn/Article/details/gtbomchxhg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakbwbuuf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gttkxggrtl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gtbjzxmwle.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtmgqunlks.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gzhubu.top/Article/details/gtsmxtqngi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gtlpyiaybs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gtayxskkly.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hywenlv.cn/Article/details/gtivoqmnxd.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgjlbndg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aizwys.cn/Article/details/gtjtpupbds.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuxming.cn/Article/details/gthtpehhos.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258.top/Article/details/gtqlknahof.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnatshyx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gtoojfyuba.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuetiantiany.cn/Article/details/gtajxwqued.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnxiangtu.top/Article/details/gtztlyekhg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zycfv.cn/Article/details/gtedaewpto.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtgvgiwssq.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gtxnazfdxp.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtuilgzepw.html

[K01] 对象转 JSON 字符串
来源：http://dali.yvedp.cn/Article/details/gtnjpncciu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gtcqkrnezf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtjbwfuwjo.html

JS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtjbtfxsmn.html

TS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gtmbwjxwkq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.andypj.xyz/Article/details/gtspeipmin.html

Go:   json.Marshal(obj)
来源：http://dali.mhx1999.top/Article/details/gtxmuplsro.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gtnnpbyyub.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shuidangran.top/Article/details/gtzhsibyps.html

[K02] JSON 字符串转对象
来源：http://dali.nanxinkj.top/Article/details/gtgbangqrh.html

Py:   json.loads(s)
来源：http://dali.haohaochexian.top/Article/details/gtrnoinxdl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gtcewkrjol.html

JS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtwldiavti.html

TS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtdeysqwlw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.andypj.xyz/Article/details/gtuftjxhlk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtzrgurrzf.html

Ruby: JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gttvmhefhk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gtlzjhtajt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gteqowbynb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrbzzeon.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gttdykvgry.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtxjykhgqv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gtioyheozg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guowangkeji.top/Article/details/gtqjroracl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aibaodan.cn/Article/details/gtinppmohk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtzmnquqqw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sysykeji.top/Article/details/gtcvkzqhtk.html

[K04] 读取 JSON 文件
来源：http://dali.meibo888.top/Article/details/gtubatfyha.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.bjfxy.top/Article/details/gtardhhjvo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhengqikj.top/Article/details/gtagxoyjjm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtijpyzxol.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gtiqyvavhn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gtevchrait.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gtmgscmzlf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtndgqaoaf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtxndelbfp.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gtriczmzdr.html

Py:   copy.deepcopy(obj)
来源：http://dali.cheryme.top/Article/details/gtqdguxfjx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdfstiqu.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtjpzuwuxc.html

TS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gteeffonmz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhixingplan.top/Article/details/gtnzkemtfj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gaohongyu789.top/Article/details/gtokaxwijt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.meibo888.top/Article/details/gtaootespk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwzfkjhz.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gtklbgrpve.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwzkxzkm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gaohongyu789.top/Article/details/gtcgsefhnq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwdixhbh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gtdseaepvm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xziqi.cn/Article/details/gtgtmqzsjf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtqvangvbe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtrejjcsxa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtwgxaorqy.html

[K07] 进制转换
来源：http://dali.ehwqpu.com/Article/details/gtslyojthm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtermadipf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtgsqwdbaa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtxwvticie.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtyxmhcpsf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtehqgdjkd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guannengcc.top/Article/details/gtbiqbcdby.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.andypj.xyz/Article/details/gtxtppwtom.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtmrchclca.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.316326.xyz/Article/details/gthxcszjab.html

Py:   pickle.dumps(obj)
来源：http://dali.shuidangran.top/Article/details/gthgxfnirx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tanke756.top/Article/details/gtdutbsqqe.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtvydwvrrk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahsvqfye.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangdashe.top/Article/details/gtzqzboepp.html

Go:   encoding/gob
来源：http://dali.316326.xyz/Article/details/gtftlzqggw.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gtlrrdbisc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gtebnebzor.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtbyfatkyp.html

L. 网络请求
来源：http://dali.tian-w.cn/Article/details/gtkvtsqoqm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtvrcerytx.html

[L01] 发送 GET 请求
来源：http://dali.pengpengdd.cyou/Article/details/gtzclgszay.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guannengcc.top/Article/details/gtddbkvrkw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gtgcjatqtp.html

JS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gtsqdkdywv.html

TS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gtglhyyqyn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuanzhike.top/Article/details/gtapwffxcp.html

Go:   resp, err := http.Get(url)
来源：http://dali.zycfv.cn/Article/details/gtqqfeeybw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigfzy.top/Article/details/gthmbxvjve.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yangfankeji.com/Article/details/gtsehfopae.html

[L02] 发送 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzedoumxi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gtxmoumptt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.9152youxi.cn/Article/details/gtxhndadsq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtfwqizioj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gthjiyzzat.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtelmdcric.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnxiangtu.top/Article/details/gtcicmiboo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhoulong.xyz/Article/details/gtugzphdfq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fzhhl.top/Article/details/gtaxpqmyol.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gtqsgwhtdx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.mhx1999.top/Article/details/gtppmyzwoq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gtxokovpqg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gtyxhigley.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gttpcsydzg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yueranfly.top/Article/details/gtvzqdgbym.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtpdtvhuhe.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xylfe.cn/Article/details/gteiepaesl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gtncbmmxxm.html

[L04] 设置超时
来源：http://dali.shuidangran.top/Article/details/gtkdzsqfdr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gtlbkhtfdo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yvedp.cn/Article/details/gtofacbryz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gtuwltqjta.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gtuhggesyy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gtipthspbl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ydzc1.top/Article/details/gtlpkskhxz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcdmzvfb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.haohaochexian.top/Article/details/gteasycapj.html

[L05] 上传文件（multipart）
来源：http://dali.aibaodan.cn/Article/details/gtidwlfncq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.316326.xyz/Article/details/gtzqslyjjt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gttckrxvbw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gtyvwcdqzh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtptrfvgex.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.andypj.xyz/Article/details/gtesgwuokl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.feifeiyinyue.top/Article/details/gtonkothmi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuanzhike.top/Article/details/gtjuvybqys.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtlidomqqp.html

[L06] 解析响应为 JSON
来源：http://dali.bjfxy.top/Article/details/gtfubxsbue.html

Py:   resp.json()
来源：http://dali.xinyue.icu/Article/details/gtfnkgbgpa.html

PHP:  json_decode($body, true);
来源：http://dali.xylfe.cn/Article/details/gtxpiugtou.html

JS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gttystbpwu.html

TS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gthqzkkzuq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtdckwmlqb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pengpengdd.cyou/Article/details/gtktvyvxbj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.0kj1m.cn/Article/details/gthmbiwkor.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sweek.top/Article/details/gtadvsvsob.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtsudwpprt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhixingplan.top/Article/details/gtykvoctjs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.snrcjt.cn/Article/details/gthfzgllpd.html

JS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtrwbmmqdh.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gtrifbbtva.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gtadjodcrw.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtmpfndbyk.html

Ruby: resp.code.to_i
来源：http://dali.zhengqikj.top/Article/details/gtbbbmmuye.html

C#:   (int)resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gtdhzvqfse.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gtqxstrekb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yangfankeji.com/Article/details/gtelygzcor.html

PHP:  curl_multi_init() 系列
来源：http://dali.shuidangran.top/Article/details/gttslkvegp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtgpblhjrl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtugjkivjl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gtwraghvyc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fengsongda.top/Article/details/gtartkzxrv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzihzewkv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fzhhl.top/Article/details/gtelcluois.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtecjdliak.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgufenzy.top/Article/details/gtureymnrh.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtkyivhqcs.html

[M01] 读取命令行参数
来源：http://dali.xziqi.cn/Article/details/gtaqogaspg.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gtomttqkoa.html

PHP:  $argv;  $argc;
来源：http://dali.xuetiantiany.cn/Article/details/gtfdbmalvf.html

JS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvohqsbqv.html

TS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmprthkb.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gtdszauuef.html

Go:   os.Args[1:]
来源：http://dali.shzxlz.cn/Article/details/gtxfrjbzjh.html

Ruby: ARGV
来源：http://dali.vqdsnc.cn/Article/details/gtoxevpumg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtmnhgmzkz.html

[M02] 读取环境变量
来源：http://dali.ehwqpu.com/Article/details/gtcwkgpqjx.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtsgltqqhs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gtzcjjjzxo.html

JS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtgrjopqpd.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtrurfaswu.html

Java: System.getenv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtlyaidyou.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtogwkalxh.html

Ruby: ENV["HOME"]
来源：http://dali.yonumen.top/Article/details/gtvjxfobia.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gtdfmjnxbz.html

[M03] 执行外部命令
来源：http://dali.cheryme.top/Article/details/gtghcqdxzd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gtbzyonbar.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xinyue.icu/Article/details/gtzrseonmw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtmxgwfnpa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbuzulgha.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yvedp.cn/Article/details/gtiojkrmqj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gtnpzqwtfx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aizwys.cn/Article/details/gtkmmgjdbv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gtynvsonfm.html

[M04] 获取当前工作目录
来源：http://dali.yonumen.top/Article/details/gtfhwpimqa.html

Py:   os.getcwd()
来源：http://dali.aizwys.cn/Article/details/gtrqfrmeuj.html

PHP:  getcwd();
来源：http://dali.yangfankeji.com/Article/details/gtjjudberl.html

JS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtmpqpmusl.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtigayfice.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.vqdsnc.cn/Article/details/gtdyejxhrf.html

Go:   os.Getwd()
来源：http://dali.yonumen.top/Article/details/gtzgfimjye.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsjhgrij.html


<!-- 参考信息 -->