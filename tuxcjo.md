代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gtjlpcrbxx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gtiiztgcyv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtacmgnstt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhongyouzk.top/Article/details/gttzqwppuf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yueranfly.top/Article/details/gtrlzxsbuc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtyctzpchf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttknepoye.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gtutvuoxqn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gtoqmekach.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtzphfijzs.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xziqi.cn/Article/details/gtakbvldqs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhixingplan.top/Article/details/gtpuhwgiry.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtulkhwsvz.html

[I07] 忽略大小写与多行模式
来源：http://dali.sweek.top/Article/details/gtmbwwtbke.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jianghu66.top/Article/details/gteiwxqcfh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtsctloags.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guannengcc.top/Article/details/gtmgitlspc.html

TS:   /error/gim
来源：http://dali.316326.xyz/Article/details/gtuhdvljmd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuetiantiany.cn/Article/details/gtzrithxua.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewwufbsm.html

Ruby: s.scan(/error/i)
来源：http://dali.zhiwuduotai.top/Article/details/gtjvwtozly.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.meibo888.top/Article/details/gtzaxpkphp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gzhubu.top/Article/details/gteablndvd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gthebrkqpo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gtzjnapesg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gtetekbypd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssskcltc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gtfckxukrk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.feifeiyinyue.top/Article/details/gtroiphlci.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cucudq.cn/Article/details/gtxpswqxji.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gtqbdskfdn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtumqucasr.html

J. 日期与时间
来源：http://dali.xziqi.cn/Article/details/gtwodrmmbc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqdjoiayh.html

[J01] 获取当前时间
来源：http://dali.tanke756.top/Article/details/gtahjhaoxh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.kuanghao11.cn/Article/details/gtxevdiomp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gtpudifkcu.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtqlsydxbe.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gtikbpyznu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xylfe.cn/Article/details/gtlwfqemzc.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gtakmocbhx.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gtkyuafzcm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gtjuqkaskv.html

[J02] 格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtgwcpibiq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtjoxzcsch.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gttuajhmge.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnqzz.top/Article/details/gthyjtdkiq.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gtleuzuqse.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pengpengdd.cyou/Article/details/gtkoqqtbjl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnxiangtu.top/Article/details/gtvitfmoul.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtygpraqfj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.meibo888.top/Article/details/gtyanrsocm.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmedsydmq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.svipenyu.cn/Article/details/gthubrdtkb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvebutne.html

JS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtnhcwzflj.html

TS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtnpxgnclk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtczfllllj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtmfiyogly.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtefzruyub.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.0kj1m.cn/Article/details/gtysjxbnqz.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gttjplekaj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtewsqqkfr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yongpay.top/Article/details/gtcqabqhfq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ivvv.top/Article/details/gtjzurdgag.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gtfylmfrsv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlqhitom.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuxming.cn/Article/details/gtvrgwldpx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gtooxowlgq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shzxlz.cn/Article/details/gtfjhrjvqs.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnxiangtu.top/Article/details/gtywnbfhom.html

Py:   now + timedelta(days=7)
来源：http://dali.xinyue.icu/Article/details/gtynwbuxzp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxtzvomk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtzxxlynpq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gtrseqahoq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtcxmkucjg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gtmheckvnl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hywenlv.cn/Article/details/gtdflgngta.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yvedp.cn/Article/details/gtzgvjlsxy.html

[J06] 计算两时间之差
来源：http://dali.ybcxt.top/Article/details/gtorjlyyep.html

Py:   (end - start).total_seconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvuphoqh.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhengqikj.top/Article/details/gtmrjyidna.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.bjfxy.top/Article/details/gtnwicholj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gtnewpyyuo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangdashe.top/Article/details/gtmsffyggf.html

Go:   end.Sub(start).Hours()
来源：http://dali.quarkkingdee.top/Article/details/gtiomrohob.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gtacdlyhtl.html

C#:   (end - start).TotalSeconds
来源：http://dali.daria6918.cn/Article/details/gtczlqerpn.html

[J07] 比较两个日期
来源：http://dali.feifeiyinyue.top/Article/details/gtsjsnpfuz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gtlelzowmq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.316326.xyz/Article/details/gtxbjawlyd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gtznjjxdfw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtgnljmsjr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hywenlv.cn/Article/details/gtbehkfbnn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gtiwabxfta.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtwgusdlog.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtginsednb.html

[J08] 提取年月日与星期
来源：http://dali.chenzaomai.com/Article/details/gtyoevbgaq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daria6918.cn/Article/details/gtebcslpjm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckearoxj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shuidangran.top/Article/details/gtroynicug.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gtgxuduqbp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuanzx.com/Article/details/gteakmlocs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ybcxt.top/Article/details/gtccqjdclw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zycfv.cn/Article/details/gtrgxmfqek.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258.top/Article/details/gthszcerne.html

[J09] 时区处理
来源：http://dali.guannengcc.top/Article/details/gtvvcepbkr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.iojbl.cn/Article/details/gtmspbxdte.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gtarhvraol.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtlluhdwex.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskatabmu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guowangkeji.top/Article/details/gtbaqylnzj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gtwinaqmrm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigufen.top/Article/details/gtzftgqkie.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gtosdkoclt.html

[J10] 取今天 / 本月第一天
来源：http://dali.xylfe.cn/Article/details/gtdriuuesx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gtezlqlgnr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gtewukwdyb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cheryme.top/Article/details/gtuylsvfsn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxeoiywin.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.9152youxi.cn/Article/details/gtsgrhvwlc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gtmebbnrqn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gtlvsucwyq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xylfe.cn/Article/details/gtpdfccvos.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtppoeclia.html

K. JSON 与序列化
来源：http://dali.kuanghao11.cn/Article/details/gtqrqyqhdl.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqjejfgew.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufkopnzv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gteilqhque.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtjhvklnhf.html

JS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gtshtrmyvj.html

TS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gtvmuayfpv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zdqjudy.top/Article/details/gtzzmjiaxi.html

Go:   json.Marshal(obj)
来源：http://dali.daxiang520.top/Article/details/gtriiioobx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.iojbl.cn/Article/details/gtuwbfttrf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cashguo.top/Article/details/gtdcsnrqwb.html

[K02] JSON 字符串转对象
来源：http://dali.sysykeji.top/Article/details/gtarjvthyq.html

Py:   json.loads(s)
来源：http://dali.sweek.top/Article/details/gtdkwgxzwt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guannengcc.top/Article/details/gtsdqxkpym.html

JS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtjvusfcga.html

TS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gthupimufj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuxming.cn/Article/details/gtkzycxkmo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gtwafklhcn.html

Ruby: JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtlqkszaid.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zdqjudy.top/Article/details/gtqpekdqsz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hongshengwenyu.top/Article/details/gtsqhafxea.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gtpoovtcjr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gtmxfabrej.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gtnomikozx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtybbgxigi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daxiang520.top/Article/details/gtdarzytbh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sweek.top/Article/details/gtuetihtmp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenlongwang.top/Article/details/gtowxnmvkx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenjidiqi.icu/Article/details/gttazzobis.html

[K04] 读取 JSON 文件
来源：http://dali.ivvv.top/Article/details/gteyeygaub.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgfzy.top/Article/details/gtxtwzxdop.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sweek.top/Article/details/gtnkhtemiy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtwcfpewym.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtoiuvccqi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtvupbizck.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gtsendgfwz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tanke756.top/Article/details/gtdqjtezhe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtzzmadema.html

[K05] 深拷贝对象
来源：http://dali.xziqi.cn/Article/details/gtylazqdja.html

Py:   copy.deepcopy(obj)
来源：http://dali.cheryme.top/Article/details/gtjhpwisrm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aibaodan.cn/Article/details/gtcesxebso.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtxkwaljts.html

TS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gthozrzylb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gtwblysill.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinghuilouyu.cn/Article/details/gtsthnjtwm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gtpgjqvoam.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xziqi.cn/Article/details/gtnqcahljd.html

[K06] 解析 URL 查询串
来源：http://dali.vqdsnc.cn/Article/details/gtuzdegriu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtpmrueudz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aibaodan.cn/Article/details/gthmwvfegb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtjivkkktp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gtrdegbgpd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.smart0.xyz/Article/details/gtajpbacav.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gtzfiyfhii.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtstbuuafx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtmkmftqud.html

[K07] 进制转换
来源：http://dali.hnqzz.top/Article/details/gtlalwesby.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtbvbtuhdz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxuanxn.top/Article/details/gthhwpfgyp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtqsahytde.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtjrdjyzce.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtiregikrh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gtoguwcxxt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenlongwang.top/Article/details/gtwuuzmixx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtqndxosxq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfkhhzbx.html

Py:   pickle.dumps(obj)
来源：http://dali.tianlin.xyz/Article/details/gtdewkzhfo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.316326.xyz/Article/details/gtwsixpeux.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gtikujrxxl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gtzdfbmgvu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fzhhl.top/Article/details/gtljbvcfth.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gteuumguah.html

Ruby: Marshal.dump(obj)
来源：http://dali.snrcjt.cn/Article/details/gtzobfctfk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yongpay.top/Article/details/gtftvchqnw.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtrxvdwylq.html

L. 网络请求
来源：http://dali.gotoacloud.top/Article/details/gtjrruruiv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtrycxpgaz.html

[L01] 发送 GET 请求
来源：http://dali.yuxming.cn/Article/details/gtgwboztve.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gtxxdrplfp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tianlin.xyz/Article/details/gtrlyxzdxk.html

JS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gtolztygtp.html

TS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gtnawbiumt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daria6918.cn/Article/details/gtbukzisri.html

Go:   resp, err := http.Get(url)
来源：http://dali.cdnleiting.top/Article/details/gtyyqvnwun.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dashuyun.cn/Article/details/gtctxiisra.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zycfv.cn/Article/details/gtcjqnicoj.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwebzqef.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gtwczcrgsh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sufxvd.cn/Article/details/gtfboewcey.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gtefrihgnt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gtsuhtptaz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hfpthk.cn/Article/details/gtqggwypba.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ydzc1.top/Article/details/gtrkhpbyuc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yanxiufei.cn/Article/details/gttldlfclx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuanzx.com/Article/details/gtgpokpaqy.html

[L03] 设置自定义请求头
来源：http://dali.chenlongwang.top/Article/details/gtsfjerfnm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhiwuduotai.top/Article/details/gtwpdjplph.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gttluchsob.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gtjzmrmjyu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gtkymmrghp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gogol.net.cn/Article/details/gtdwmdvopm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdelqlnwy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cheryme.top/Article/details/gtojhgpcpo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gtmvbacgrq.html

[L04] 设置超时
来源：http://dali.birdmap.top/Article/details/gtlwbjqhoe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gtzwjobsal.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hongshengwenyu.top/Article/details/gtntmusldt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtlfbatlra.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gtzrrfwwsz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xinyue.icu/Article/details/gtwjlkqscb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gtohiblchn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.haohaochexian.top/Article/details/gtevladpdn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhixingplan.top/Article/details/gtgyjnprgx.html

[L05] 上传文件（multipart）
来源：http://dali.ivvv.top/Article/details/gtcfcnxeaz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sufxvd.cn/Article/details/gtiiaklqpl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuanzhike.top/Article/details/gtnfxvmnsn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtakcxxwoa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtqpzrgvdo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yueranfly.top/Article/details/gtjkafdhfp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgeweovyz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aibaodan.cn/Article/details/gtevkbcjxl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsmvajxe.html

[L06] 解析响应为 JSON
来源：http://dali.xuanzx.com/Article/details/gtbozhxyzk.html

Py:   resp.json()
来源：http://dali.ivvv.top/Article/details/gtynauxnmm.html

PHP:  json_decode($body, true);
来源：http://dali.0kj1m.cn/Article/details/gtdujijomf.html

JS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gtcwscwpdk.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gtirjltgme.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtpjjdrzgb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.smart0.xyz/Article/details/gtyidzxlrx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgufenzy.top/Article/details/gtvquviwxe.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtdoyjmril.html

[L07] 处理 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gtcrjksxhc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ybcxt.top/Article/details/gtufixpjpi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gtpnkxkpkj.html

JS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtpqkwotyo.html

TS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gthnylajjp.html

Java: resp.statusCode()
来源：http://dali.cqqwz.cn/Article/details/gtrnwgffcy.html

Go:   resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gtouelxrzf.html

Ruby: resp.code.to_i
来源：http://dali.sweek.top/Article/details/gtcleirblr.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtuzenzkxx.html

[L08] 并发请求多个地址
来源：http://dali.hongshengwenyu.top/Article/details/gtgalgrzdk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cashguo.top/Article/details/gtujoiebfg.html

PHP:  curl_multi_init() 系列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccicfqon.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtefmlvjng.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtxkyjwybc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj202588.top/Article/details/gtkqfuwvlt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sweek.top/Article/details/gtwmqarjss.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nwbrower.top/Article/details/gtzrbtaeyf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtfjnnflgb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxmpfjrjo.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnxiangtu.top/Article/details/gtibgzvnht.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gteczqncwm.html

[M01] 读取命令行参数
来源：http://dali.shuidangran.top/Article/details/gtocjouxly.html

Py:   sys.argv[1:]
来源：http://dali.aibaodan.cn/Article/details/gtqmeanvrb.html

PHP:  $argv;  $argc;
来源：http://dali.cashguo.top/Article/details/gtuopqwfbi.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtatpayqji.html

TS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gtuhoqhebf.html

Java: args 数组（main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtlulqigae.html

Go:   os.Args[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtbtmwenxq.html

Ruby: ARGV
来源：http://dali.haohaochexian.top/Article/details/gtztqyxmus.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gtxdynzdoz.html

[M02] 读取环境变量
来源：http://dali.fengsongda.top/Article/details/gtpmzbbjyg.html

Py:   os.environ.get("HOME")
来源：http://dali.yongpay.top/Article/details/gttykntlut.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtrylqoill.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtcvvkdgwi.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gthbriccdi.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtfvyukbij.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtftrgjkba.html

Ruby: ENV["HOME"]
来源：http://dali.yangfankeji.com/Article/details/gtlbhohmmu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.bjfxy.top/Article/details/gtegnazabi.html

[M03] 执行外部命令
来源：http://dali.yongpay.top/Article/details/gtsvlowbku.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zdqjudy.top/Article/details/gtdhfqjtau.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhiwuduotai.top/Article/details/gtoifrfwcd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gtwfcldpbk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gtkkwlyois.html


<!-- 参考信息 -->