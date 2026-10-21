代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yanxiufei.cn/Article/details/gthhanbydg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthaukfffh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtmfznknia.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtgytqrrke.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gogol.net.cn/Article/details/gtyscwpdlb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gthweapfhc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtexmpiwmm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gtjtxmpfll.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yueranfly.top/Article/details/gtzyxtdjko.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtilcqtmzg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fzhhl.top/Article/details/gttpfrsxmw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gtrsjtqgfd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gtbearzzcj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gthdsegmly.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.andypj.xyz/Article/details/gtgyyxolyk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jianghu66.top/Article/details/gtrwabzygu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtvemyvowe.html

[I07] 忽略大小写与多行模式
来源：http://dali.smart0.xyz/Article/details/gtqscbjeko.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuzdnaai.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gtgoxtcdru.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxinkj.top/Article/details/gttnjkbydf.html

TS:   /error/gim
来源：http://dali.xuetiantiany.cn/Article/details/gtcmhlozvz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.c1oappe.top/Article/details/gthzhhrcuh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cashguo.top/Article/details/gthqvlrujf.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gtrhmoevhe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gthogbkqbp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gthmyhxvtj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxuanxn.top/Article/details/gtrluyynoz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gtqnkenmtq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gthhtbkbfe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gtjvqnilyv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gtwrevipzp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dashuyun.cn/Article/details/gtiqpgolxs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.havefunace.top/Article/details/gtocqjewsr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gtrkuhairf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtaucjcanj.html

J. 日期与时间
来源：http://dali.hongshengwenyu.top/Article/details/gtgvundxdm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtjvhokikn.html

[J01] 获取当前时间
来源：http://dali.fengsongda.top/Article/details/gtghowayta.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuanzhike.top/Article/details/gtpjsjstre.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gtdhwqbbwt.html

JS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtnaructaq.html

TS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtqanjwcyl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yvedp.cn/Article/details/gtpinxwrjz.html

Go:   time.Now()
来源：http://dali.svipenyu.cn/Article/details/gtwberknfs.html

Ruby: Time.now
来源：http://dali.tian-w.cn/Article/details/gtthedzqoe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xziqi.cn/Article/details/gtxwzzjxqi.html

[J02] 格式化输出
来源：http://dali.svipenyu.cn/Article/details/gtqpylglnd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtvtgdcill.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gttptedpyr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gzhubu.top/Article/details/gtkyvbnmsf.html

TS:   d.toISOString()
来源：http://dali.jqgfzy.top/Article/details/gtwnxxdheh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cucudq.cn/Article/details/gtxwhlrxsh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cqqwz.cn/Article/details/gtxbzfjnxq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagbfysap.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenzaomai.com/Article/details/gteawaeflc.html

[J03] 字符串解析为日期
来源：http://dali.sufxvd.cn/Article/details/gtoqharvie.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxuanxn.top/Article/details/gtneyxjgwn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlcdogjm.html

JS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtcsmasher.html

TS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtgojmjoso.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtsnxhjpmq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtgcktoclg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtwgkgnfdz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbcbsmnxt.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gtgpxhawhb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nwbrower.top/Article/details/gttfsocvct.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangshuangyany.cn/Article/details/gtqwbvsxka.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gogol.net.cn/Article/details/gtfsmuyiin.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hfpthk.cn/Article/details/gtjzypeudd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigufen.top/Article/details/gtihnxpjim.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnrnetpz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gogol.net.cn/Article/details/gtkwwrlqlq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtquknsa.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuanzx.com/Article/details/gtbqqekpuz.html

Py:   now + timedelta(days=7)
来源：http://dali.aibaodan.cn/Article/details/gtpoygsrle.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cqqwz.cn/Article/details/gtbnlzjxpj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtlaykouef.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gtikijqens.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gtidwrjjbv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqafxgww.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hongshengwenyu.top/Article/details/gtzdcfeipw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtvmxoeenn.html

[J06] 计算两时间之差
来源：http://dali.haohaochexian.top/Article/details/gtiwucmnmw.html

Py:   (end - start).total_seconds()
来源：http://dali.xuanzx.com/Article/details/gtbnctqifs.html

PHP:  $end->diff($start)->days;
来源：http://dali.ydzc1.top/Article/details/gthjsqzghn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenlongwang.top/Article/details/gtdmbdnxel.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sweek.top/Article/details/gtdxghinxm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.316326.xyz/Article/details/gtnlqbieyf.html

Go:   end.Sub(start).Hours()
来源：http://dali.tian-w.cn/Article/details/gtvsbemjlt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.0kj1m.cn/Article/details/gtsdgfuntq.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gtqzmhqazg.html

[J07] 比较两个日期
来源：http://dali.shuidangran.top/Article/details/gtekrocteo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtqplpktqj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gteozhoaid.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gtsmfyydlp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gtausmljwu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gtnwyscszm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xylfe.cn/Article/details/gtrnufcprx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtaeekfvdp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtmbmfncil.html

[J08] 提取年月日与星期
来源：http://dali.jyoumei.cn/Article/details/gtpqcbrsmi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aibaodan.cn/Article/details/gtzyhrfucq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aizwys.cn/Article/details/gttcdhonex.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.birdmap.top/Article/details/gthmxhezfq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hywenlv.cn/Article/details/gtaxqeewau.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gtfyxsqomi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gtztvllmin.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gtivgybgaz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gtzropezrs.html

[J09] 时区处理
来源：http://dali.yangfankeji.com/Article/details/gtkfqzucoo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gtiikpxokg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yongpay.top/Article/details/gtrrashqvr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtoymtbhcb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gtcvujplos.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinghuilouyu.cn/Article/details/gtawpmtnvs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xziqi.cn/Article/details/gtgntbjwkq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sweek.top/Article/details/gtoswxqexf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tian-w.cn/Article/details/gtxgniabxi.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gtokdfmopv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fengsongda.top/Article/details/gtkoxbydak.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigfzy.top/Article/details/gthhsfuhvv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gtnxacvopf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtfqqfzdtd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cashguo.top/Article/details/gtjvwdayso.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gtnzptkpmh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfjzteib.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgfzy.top/Article/details/gtrgnylsqr.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtmcemtyzm.html

K. JSON 与序列化
来源：http://dali.gaohongyu789.top/Article/details/gtotwivuuz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvtbjwmp.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258888.top/Article/details/gtvbdhajua.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gtexvhhfhe.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtmetgyitx.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtteoayned.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtczawtpsd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinghuilouyu.cn/Article/details/gtspsbjgds.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhezeiyy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gtewkaszqk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtlwverdag.html

[K02] JSON 字符串转对象
来源：http://dali.guannengcc.top/Article/details/gtmldlikyz.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gtjvtyhyso.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nwbrower.top/Article/details/gtziycucpo.html

JS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtbwdeymoo.html

TS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtvmkesntv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtfdgtnkpz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gtgiybdowd.html

Ruby: JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtqmhsxnrm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gtqyfuglfz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.redwolf501.top/Article/details/gtvcugpmuz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gtserlmdlr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gtsqpkyape.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gteaofpjdc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gtrdyizfik.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ydzc1.top/Article/details/gtlmmbvztx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenzaomai.com/Article/details/gtnuzrcukc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtoqzuicqb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.feifeiyinyue.top/Article/details/gtnineigbq.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gtzjubtvzw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sysykeji.top/Article/details/gtsciowkax.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shangyingyoupin.top/Article/details/gtocpixycg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtqiljfngw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gtmyfgtyhp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtnkjxykfa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gtjlazzlkb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtzsaasvhc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.meibo888.top/Article/details/gtsdcdwwgu.html

[K05] 深拷贝对象
来源：http://dali.dashuyun.cn/Article/details/gtbjwvdmmv.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gtspwuektd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gtevdyyjnv.html

JS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtuwdwqdbh.html

TS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtkdvtmaal.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gtccynuuib.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gaohongyu789.top/Article/details/gtreluifvp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuxming.cn/Article/details/gtlerruggo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pycfn.com/Article/details/gtrwilpkpj.html

[K06] 解析 URL 查询串
来源：http://dali.ydzc1.top/Article/details/gtdntbjpbw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gtsalkuqve.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.quarkkingdee.top/Article/details/gtxpcysgve.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gtfesxwszk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtpnekgkrl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gogol.net.cn/Article/details/gtekmqemop.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtuziwnevl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtzxkhbwmz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gthxuippbq.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gtcobrcpmw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtxkuwjrbn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tianlin.xyz/Article/details/gtqduocyrf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gteotatzkh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtrjrwvudh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtaljxwpdq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gtghlcrbwo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj202588.top/Article/details/gttgbbdyxa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtrtitargr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.havefunace.top/Article/details/gtlivwknqc.html

Py:   pickle.dumps(obj)
来源：http://dali.zycfv.cn/Article/details/gtafwppklh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258888.top/Article/details/gtezteazxw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gtzstofdnn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gtjtcavswn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.redwolf501.top/Article/details/gtquznubqk.html

Go:   encoding/gob
来源：http://dali.shanyushiyangtech.top/Article/details/gtlesnttwg.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcggnfakd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtqqwjhnfh.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmjsfkiu.html

L. 网络请求
来源：http://dali.zhiwuduotai.top/Article/details/gtvivkktqz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtxohogzfo.html

[L01] 发送 GET 请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcdskntz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gtsyovpwzg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxinkj.top/Article/details/gtsdhanonn.html

JS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtgtjmohee.html

TS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gtipvrglls.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuxming.cn/Article/details/gtxivwuonm.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuanzhike.top/Article/details/gtsozmkmmt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangshuangyany.cn/Article/details/gtcxtiybjk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gtjdospcnx.html

[L02] 发送 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gtlpqzpbav.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cheryme.top/Article/details/gtsgzegsdj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gthmuaadnv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gtxlxcqkfc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gtadgjvxym.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aizwys.cn/Article/details/gtuohstgfs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.meibo888.top/Article/details/gtrosympjw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.feifeiyinyue.top/Article/details/gtraocdkdv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gtdmtrzqlk.html

[L03] 设置自定义请求头
来源：http://dali.svipenyu.cn/Article/details/gtqyfyklfi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenlongwang.top/Article/details/gtcorshimx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.vqdsnc.cn/Article/details/gtswpnybxr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gtoelbsdjt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqtkrxdq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hfpthk.cn/Article/details/gtcfmbuaxd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlfxkcog.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cucudq.cn/Article/details/gtthdxjawf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gtmavhyfyw.html

[L04] 设置超时
来源：http://dali.pengpengdd.cyou/Article/details/gtdylgqrsg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gzhubu.top/Article/details/gtvcyfkedp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxinkj.top/Article/details/gtvefezcdw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gthvpdsbmb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtzzwlhrht.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigufen.top/Article/details/gtjorjabyl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shangyingyoupin.top/Article/details/gtduzkzxac.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gtphtdmwqy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sxryk.cn/Article/details/gtadxrndmr.html

[L05] 上传文件（multipart）
来源：http://dali.zhongyouzk.top/Article/details/gtaognjpij.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwphixxe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daria6918.cn/Article/details/gtpupxdvuk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtqngdllfj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gtmphpeuuz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cashguo.top/Article/details/gtwrywuypv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gtymglxpie.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqntpxia.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtndocectn.html

[L06] 解析响应为 JSON
来源：http://dali.cashguo.top/Article/details/gtkzjefetb.html

Py:   resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtmlgnawrp.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtordtlfoj.html

JS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gtgwofzmjq.html

TS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gttrfiuyyb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtcbmhezyk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shzxlz.cn/Article/details/gtzhpuxcmq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gtdezpirre.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.316326.xyz/Article/details/gtfkdwxrtm.html

[L07] 处理 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gtjoccmrtn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yonumen.top/Article/details/gtcnwvxwqb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daxiang520.top/Article/details/gtumxejonc.html

JS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gtgmxjmpnl.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtdkypltua.html

Java: resp.statusCode()
来源：http://dali.smart0.xyz/Article/details/gtazivivgs.html

Go:   resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtfmdxmtnt.html

Ruby: resp.code.to_i
来源：http://dali.quarkkingdee.top/Article/details/gtldlaithx.html

C#:   (int)resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gtkowrimci.html

[L08] 并发请求多个地址
来源：http://dali.tanke756.top/Article/details/gtcdjddpso.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxinkj.top/Article/details/gtpghjvcfe.html

PHP:  curl_multi_init() 系列
来源：http://dali.ppjwa.cn/Article/details/gtkghcrbfq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtyjtnjrmy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtiqsvwcir.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.birdmap.top/Article/details/gtrfzgsbvf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hongshengwenyu.top/Article/details/gtddwybsgr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tianlin.xyz/Article/details/gtmqtfdzep.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gotoacloud.top/Article/details/gtqluqumxe.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtgkacxuox.html

M. 命令行 / 进程 / 环境
来源：http://dali.cheryme.top/Article/details/gtfeuxhisz.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrthzcroi.html

[M01] 读取命令行参数
来源：http://dali.redwolf501.top/Article/details/gtozonlpmv.html

Py:   sys.argv[1:]
来源：http://dali.zdqjudy.top/Article/details/gtspyxbfpk.html

PHP:  $argv;  $argc;
来源：http://dali.meibo888.top/Article/details/gttjkwpuid.html

JS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gtsokqlxeu.html

TS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gthfyuqazl.html

Java: args 数组（main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gtfhwmzsex.html

Go:   os.Args[1:]
来源：http://dali.xylfe.cn/Article/details/gtvpgokmok.html

Ruby: ARGV
来源：http://dali.yvedp.cn/Article/details/gtnrxwlaow.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtdiebpggd.html

[M02] 读取环境变量
来源：http://dali.yj20258.top/Article/details/gtzvmbgcub.html

Py:   os.environ.get("HOME")
来源：http://dali.smart0.xyz/Article/details/gtkhaluohr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtjigrozrs.html

JS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtloufazbg.html

TS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtltufyady.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtvaargtqu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guannengcc.top/Article/details/gtgxmtkwox.html

Ruby: ENV["HOME"]
来源：http://dali.jyoumei.cn/Article/details/gtjtlstoee.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gttqkpsuud.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gtahwqdirn.html


<!-- 参考信息 -->