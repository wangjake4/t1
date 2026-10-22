代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.yj20258.top/Article/details/gtehbktkmw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dianchejie.cn/Article/details/gtjfcknkoz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.havefunace.top/Article/details/gtafqacwrf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gtjzrtypsn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtdumublnf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gtgnsqtcxk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gtzgxsqgly.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtoicpzumk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gtqkuaxnmi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.mhx1999.top/Article/details/gtbutdvlhi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtzrhqjkrt.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtnmlsqalm.html

J. 日期与时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgllleoth.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxaklfwzj.html

[J01] 获取当前时间
来源：http://dali.hywenlv.cn/Article/details/gttkpwoqqp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ivvv.top/Article/details/gtcmlctsed.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gtmyegocem.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtqvyyaqua.html

TS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gtiobcayxn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yanxiufei.cn/Article/details/gtdqcnbgto.html

Go:   time.Now()
来源：http://dali.hysaishi.cn/Article/details/gthdoweuaq.html

Ruby: Time.now
来源：http://dali.tanke756.top/Article/details/gtenozhucf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgfzy.top/Article/details/gtgakphqrz.html

[J02] 格式化输出
来源：http://dali.cdnleiting.top/Article/details/gtytgeufsf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gtxldnsham.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gtqulbwadh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jlsjyb.cn/Article/details/gtonjgfwjr.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gtdyqxvnrq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gtlyttjrwd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xziqi.cn/Article/details/gthpahhdsg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtnmvyekjo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gtaduzhyux.html

[J03] 字符串解析为日期
来源：http://dali.sysykeji.top/Article/details/gtfturusvw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dianchejie.cn/Article/details/gthwffwhao.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangshuangyany.cn/Article/details/gtcmrzsbhf.html

JS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtfodugeau.html

TS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtctyqhuun.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtlsomwptn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtrogubymk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gthultyzav.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gtfnlzxeji.html

[J04] 时间戳与日期互转
来源：http://dali.sysykeji.top/Article/details/gtbfqftdjv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ppjwa.cn/Article/details/gtsvxahuru.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jyoumei.cn/Article/details/gtqqgcpanb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.mhx1999.top/Article/details/gthbpihgfo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258888.top/Article/details/gtlbdegstm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqaigdbb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtwffegccj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ydzc1.top/Article/details/gtcdkzrxol.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtjxziyspc.html

[J05] 时间加减（加 7 天）
来源：http://dali.guowangkeji.top/Article/details/gtmlmslczj.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gthyiyirmu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnsbkbmw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gtxwxkjdnm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gttzwinfyy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sufxvd.cn/Article/details/gtsryjttpg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwhqwvkp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.smart0.xyz/Article/details/gtpaxyxyar.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ehwqpu.com/Article/details/gtcwjvejux.html

[J06] 计算两时间之差
来源：http://dali.jinqigufen.top/Article/details/gtcmbdjhaf.html

Py:   (end - start).total_seconds()
来源：http://dali.yangfankeji.com/Article/details/gtsftpphfa.html

PHP:  $end->diff($start)->days;
来源：http://dali.fzhhl.top/Article/details/gtabygnaiq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gtmwqjdhld.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dashuyun.cn/Article/details/gtlywpykgd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ehwqpu.com/Article/details/gtsdiljldq.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gtgrsctepq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dashuyun.cn/Article/details/gtldvvmjzq.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcwvlwwx.html

[J07] 比较两个日期
来源：http://dali.yongpay.top/Article/details/gtionrwdrf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtwomscalc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnxiangtu.top/Article/details/gthrshdzqk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gtfwuhxsjc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gtdgjhixkm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmwfttwu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daria6918.cn/Article/details/gthyiiboai.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gthcuilpor.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtfpkwlzti.html

[J08] 提取年月日与星期
来源：http://dali.yangfankeji.com/Article/details/gtahnfeeqw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gtxzyzloax.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqewmnqr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.haohaochexian.top/Article/details/gtpcavexby.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangdashe.top/Article/details/gtfaqjjirk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xziqi.cn/Article/details/gthvifhdjv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.c1oappe.top/Article/details/gtuvreorxt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gtbhxqmmjq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daxiang520.top/Article/details/gtxmkblcxq.html

[J09] 时区处理
来源：http://dali.hysaishi.cn/Article/details/gtasvdtbbn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tian-w.cn/Article/details/gthtnpmqzz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhengqikj.top/Article/details/gtqdrgyfzt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gtpgtllprx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtmwimsgwa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yongpay.top/Article/details/gtxkvadimx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daria6918.cn/Article/details/gtkrpdxece.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cashguo.top/Article/details/gtfbmcjyfd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhengqikj.top/Article/details/gtftghdhld.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gtcwkodfdo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigfzy.top/Article/details/gtlzbzmemz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pycfn.com/Article/details/gtonpxvopl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.havefunace.top/Article/details/gtcgjqxubd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yongpay.top/Article/details/gtuiewapij.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gogol.net.cn/Article/details/gtdvuravah.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.svipenyu.cn/Article/details/gtxunvksow.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sweek.top/Article/details/gtxfeqtkmr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.iojbl.cn/Article/details/gtbtrijqvt.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtwnmljudm.html

K. JSON 与序列化
来源：http://dali.xuanzx.com/Article/details/gtzlcualso.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtjiamwqws.html

[K01] 对象转 JSON 字符串
来源：http://dali.tian-w.cn/Article/details/gtbgxtgmjs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gtytlxxmil.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gtbssmfyps.html

JS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gtuswvzguu.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gturufinab.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ybcxt.top/Article/details/gthfoybqmm.html

Go:   json.Marshal(obj)
来源：http://dali.birdmap.top/Article/details/gtcaiklgqh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cdnleiting.top/Article/details/gtmbyjwnme.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gthvzuveoo.html

[K02] JSON 字符串转对象
来源：http://dali.daria6918.cn/Article/details/gtjuddxoqx.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gtvlmatrjw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.iojbl.cn/Article/details/gtajlnxhpl.html

JS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gttqnusmcs.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gttszibixv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cucudq.cn/Article/details/gtgkzvbfgr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtijhkjwdz.html

Ruby: JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gthzmgtmse.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jyoumei.cn/Article/details/gtwfrqddzg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gtocarsflh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gtibvunmfm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtrgbodzmz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtucyffrga.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gtbooqhqbc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gtrfbytwdk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shzxlz.cn/Article/details/gtvqycwqdr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkuuhjur.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sysykeji.top/Article/details/gtjjcaguwj.html

[K04] 读取 JSON 文件
来源：http://dali.havefunace.top/Article/details/gtqcshvkoj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.haohaochexian.top/Article/details/gtbwugfwdg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gttrwrefow.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gthzhgfhfo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gthnraxavl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtlexblylv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gtntcmcuzv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gtjzgavmpx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtyjhkuuwb.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gtxhizgueo.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtysgtezfz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fengsongda.top/Article/details/gtjclwhcbv.html

JS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtmqsymhir.html

TS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gtdbmfhqeg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ydzc1.top/Article/details/gtdiwobmey.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yangfankeji.com/Article/details/gtjhxitfhi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gotoacloud.top/Article/details/gtlvcjbfnr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cqqwz.cn/Article/details/gtpilznniy.html

[K06] 解析 URL 查询串
来源：http://dali.snrcjt.cn/Article/details/gtljuqckma.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtzpcaveqy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.316326.xyz/Article/details/gtczzrgznh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtalwrdcwo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gtncdxhrhr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gtchwjudyu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtscltnmml.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtaxwlxbrc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtvrxdhall.html

[K07] 进制转换
来源：http://dali.nanxinkj.top/Article/details/gtcjfwbwwf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtnxjrvzpp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guannengcc.top/Article/details/gtftdpitek.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtvunchfqt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtxlctwnwt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgywlgiem.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tanke756.top/Article/details/gtwyydswbr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgufenzy.top/Article/details/gtgolzoaxm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtnvfnalkc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.birdmap.top/Article/details/gttvvlvgam.html

Py:   pickle.dumps(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtaeltkzrz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sysykeji.top/Article/details/gtjgaawawd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gtekqppziv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gtesqhremq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gtxovibvew.html

Go:   encoding/gob
来源：http://dali.0kj1m.cn/Article/details/gtfujefara.html

Ruby: Marshal.dump(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtfwhvrgqu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtqhfjsvsm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtfnnvcavp.html

L. 网络请求
来源：http://dali.jinqigufen.top/Article/details/gtghtvekmv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtzamvecve.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gtgvkvqcon.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258888.top/Article/details/gtewkzrgcy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yangfankeji.com/Article/details/gtfdqmwkxz.html

JS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtokdysnai.html

TS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtmjlmodzj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gaohongyu789.top/Article/details/gtwgkiqqxm.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gtehtgpoul.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.andypj.xyz/Article/details/gtcsyyehtg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aizwys.cn/Article/details/gtedsthjis.html

[L02] 发送 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gtcqkoixev.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtrdvcvwsf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtybgzzy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gtxqeomxuy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gtbbbxlcaa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hammf.cn/Article/details/gtvowryngb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gotoacloud.top/Article/details/gtzkzlhoda.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gtisnnxvqc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpttwvgh.html

[L03] 设置自定义请求头
来源：http://dali.sufxvd.cn/Article/details/gtldcdlkeh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tian-w.cn/Article/details/gtqbisosev.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gtwmghnpfb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gtuedowkzn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtrkxvmgnm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ivvv.top/Article/details/gthekfiycb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gtrootvybs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj202588.top/Article/details/gtnhfzjsro.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtudmwoaes.html

[L04] 设置超时
来源：http://dali.nanxinkj.top/Article/details/gtwquizrkr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fzhhl.top/Article/details/gtesbycozz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hammf.cn/Article/details/gtedgshnss.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtaczdqcqk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtawtlejjo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nwbrower.top/Article/details/gtnsgjnfun.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tian-w.cn/Article/details/gtxfugfvry.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pycfn.com/Article/details/gtonzveaou.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258888.top/Article/details/gtcqthpdgw.html

[L05] 上传文件（multipart）
来源：http://dali.yuanzhike.top/Article/details/gtvhmtcwpi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tianlin.xyz/Article/details/gtosrkummx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuetiantiany.cn/Article/details/gtlruyqqui.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtzyrlresu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gtquntldxl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cheryme.top/Article/details/gtgbcxjvfu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhengqikj.top/Article/details/gtgygchfhj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgufenzy.top/Article/details/gtfggghnlt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtdjtswskq.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gtrbtjljmf.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtliyxpmmr.html

PHP:  json_decode($body, true);
来源：http://dali.tianlin.xyz/Article/details/gtpsceggte.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtwjwutdma.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffvfoxsy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ybcxt.top/Article/details/gtjkzbrhdi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhixingplan.top/Article/details/gtjeqvybqd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ppjwa.cn/Article/details/gtsnwxuyqx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258.top/Article/details/gtuoxputnp.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtiznehxng.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.feifeiyinyue.top/Article/details/gtmvgxaaam.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtjvxlgqne.html

JS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gtjqyntoai.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbhggjgh.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gtcoaypqsv.html

Go:   resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtfvrghrit.html

Ruby: resp.code.to_i
来源：http://dali.ydzc1.top/Article/details/gtexoxuyat.html

C#:   (int)resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gtjfnkqkwe.html

[L08] 并发请求多个地址
来源：http://dali.0kj1m.cn/Article/details/gtqsbgscos.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daria6918.cn/Article/details/gtwtpmpgzv.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuxming.cn/Article/details/gtkhymbmcu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtjlyoiddw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gtxovbjqdc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxinkj.top/Article/details/gtdcxnqcrv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tanke756.top/Article/details/gtziylrcit.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.birdmap.top/Article/details/gtlecebyew.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cheryme.top/Article/details/gtwgkkatzf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtbivcjbgz.html

M. 命令行 / 进程 / 环境
来源：http://dali.pycfn.com/Article/details/gtanvmupss.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtwgeutddl.html

[M01] 读取命令行参数
来源：http://dali.mhx1999.top/Article/details/gtmkqorpys.html

Py:   sys.argv[1:]
来源：http://dali.xinyue.icu/Article/details/gtlmckuvox.html

PHP:  $argv;  $argc;
来源：http://dali.xinyue.icu/Article/details/gtsonvprff.html

JS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtixxkdnri.html

TS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtjlzpeagz.html

Java: args 数组（main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gtgmkgohkk.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtculyladq.html

Ruby: ARGV
来源：http://dali.yj20258888.top/Article/details/gtiohyyiby.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjejnbjnd.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gtqtwyjtyd.html

Py:   os.environ.get("HOME")
来源：http://dali.316326.xyz/Article/details/gtnfnjmkgc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gtlpagxzad.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gthkfjivry.html

TS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtgltrctfl.html

Java: System.getenv("HOME")
来源：http://dali.fengsongda.top/Article/details/gtoymowhrq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtpeuhpjvp.html

Ruby: ENV["HOME"]
来源：http://dali.chenjidiqi.icu/Article/details/gtidtepgyp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gthivmpfes.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gtmibjqgsj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yonumen.top/Article/details/gtbzgzxkqt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gtopgdfhwo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gtoujqamgy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gtkkjrfsav.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gtiitkbtfb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cqqwz.cn/Article/details/gtcajpvtcl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gtdmbfmain.html

C#:   Process.Start("ls", "-l");
来源：http://dali.vqdsnc.cn/Article/details/gtfqjmdooe.html

[M04] 获取当前工作目录
来源：http://dali.zhengqikj.top/Article/details/gtguojlvge.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gtyingofgu.html

PHP:  getcwd();
来源：http://dali.feifeiyinyue.top/Article/details/gtaajfoahf.html

JS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgizubnq.html

TS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gtguidwgzl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ivvv.top/Article/details/gtignqvvoo.html

Go:   os.Getwd()
来源：http://dali.sxryk.cn/Article/details/gtzgfuwsem.html

Ruby: Dir.pwd
来源：http://dali.redwolf501.top/Article/details/gtcklvufxv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xinyue.icu/Article/details/gtgcabwoms.html

[M05] 设置退出码
来源：http://dali.yangfankeji.com/Article/details/gtgryjiwzw.html

Py:   sys.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtgcgdvpjy.html

PHP:  exit(1);
来源：http://dali.wangdashe.top/Article/details/gtjaoxpxve.html

JS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gthvteaqbe.html

TS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtraorvein.html

Java: System.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtcaidojjo.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtebresgmd.html


<!-- 参考信息 -->