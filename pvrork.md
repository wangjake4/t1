代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cucudq.cn/Article/details/gtareuerfe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtmvjycozs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sysykeji.top/Article/details/gtwirizvkp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtkhoivgwk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gtlrhhmwjp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtrhjkyynk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxinkj.top/Article/details/gtcfdvxase.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yanxiufei.cn/Article/details/gtqnbzaiay.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtomveblef.html

[I07] 忽略大小写与多行模式
来源：http://dali.yanxiufei.cn/Article/details/gtjovgjlzv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cdnleiting.top/Article/details/gtfvzbbade.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gtdnzoppko.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zdqjudy.top/Article/details/gtqwjorgmx.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gtomdwblps.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.smart0.xyz/Article/details/gtxbvmucvl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shuidangran.top/Article/details/gthcfhcsyp.html

Ruby: s.scan(/error/i)
来源：http://dali.jyoumei.cn/Article/details/gtpiziguyn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guowangkeji.top/Article/details/gtgwyucybz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sweek.top/Article/details/gttenghfbk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxinkj.top/Article/details/gtthbwnege.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gthugieahw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtenhgvisy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtsfadocgw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gtmurhgbgt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shzxlz.cn/Article/details/gtynqgxtgu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigfzy.top/Article/details/gtvnkuirop.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtvvhldxro.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtvqxjhctu.html

J. 日期与时间
来源：http://dali.dashuyun.cn/Article/details/gtsajmwwkg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtnnfpevxa.html

[J01] 获取当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtxxlydzsj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gtwxdstuxv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gtntunfzaf.html

JS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtrxilnbvd.html

TS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gthallltuj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aizwys.cn/Article/details/gtrunxwosv.html

Go:   time.Now()
来源：http://dali.tian-w.cn/Article/details/gthgthagol.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gtgpnouxsc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj202588.top/Article/details/gtlpgpepca.html

[J02] 格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtmgehnfcu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gtkzdfsobt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsqjvnbo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sufxvd.cn/Article/details/gtdukcxtic.html

TS:   d.toISOString()
来源：http://dali.xylfe.cn/Article/details/gtsdcbruyc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.iojbl.cn/Article/details/gtauwfueth.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuanzx.com/Article/details/gtzcfymukk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gtffbbpyfg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gotoacloud.top/Article/details/gtdzfmmlqk.html

[J03] 字符串解析为日期
来源：http://dali.birdmap.top/Article/details/gtoxahzouh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cheryme.top/Article/details/gtvsysmzgu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gtvvhosvha.html

JS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtzgrupfgt.html

TS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtlyerywip.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtstimiukg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtaccbkhwv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtostaiskn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yongpay.top/Article/details/gtjceqxfyn.html

[J04] 时间戳与日期互转
来源：http://dali.ybcxt.top/Article/details/gthsgddjad.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ehwqpu.com/Article/details/gtpwhpfesb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.feifeiyinyue.top/Article/details/gtiivkgrej.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.vqdsnc.cn/Article/details/gtfauqtfln.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gtozmqqepp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttsreatwp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuanzhike.top/Article/details/gtggltuxkl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.haohaochexian.top/Article/details/gtildqlaku.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.9152youxi.cn/Article/details/gtxdaeuvqp.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuetiantiany.cn/Article/details/gtfxgpmwrb.html

Py:   now + timedelta(days=7)
来源：http://dali.meibo888.top/Article/details/gtvzwjwzli.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigfzy.top/Article/details/gtsamzcbpd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gtlupieoeg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gttaumugpg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenzaomai.com/Article/details/gttnjyghvl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigufen.top/Article/details/gtrpphfohx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jiagoushi.top/Article/details/gtrosaemsk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yonumen.top/Article/details/gttlugjuam.html

[J06] 计算两时间之差
来源：http://dali.316326.xyz/Article/details/gtkqzhycxl.html

Py:   (end - start).total_seconds()
来源：http://dali.vqdsnc.cn/Article/details/gtbezantmx.html

PHP:  $end->diff($start)->days;
来源：http://dali.meibo888.top/Article/details/gtqasatnny.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sxryk.cn/Article/details/gtzfkdrqeq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.snrcjt.cn/Article/details/gtyrkardcm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangshuangyany.cn/Article/details/gtyahlhzex.html

Go:   end.Sub(start).Hours()
来源：http://dali.jlsjyb.cn/Article/details/gtsysaelth.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gtgzvjwspc.html

C#:   (end - start).TotalSeconds
来源：http://dali.kuanghao11.cn/Article/details/gtxnausxzz.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gtadszklib.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtprbtmmns.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yonumen.top/Article/details/gtyqsmuqbn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gtnzhcejjg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gttbqlzycq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tianlin.xyz/Article/details/gtmgfazvvg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gtwsjkyywr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtjbtchbkq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtlmrfjbqg.html

[J08] 提取年月日与星期
来源：http://dali.hfpthk.cn/Article/details/gtcvjeufal.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shangyingyoupin.top/Article/details/gtbzvnggbm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenjidiqi.icu/Article/details/gtkamguqul.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daria6918.cn/Article/details/gtilmahxkw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuanzx.com/Article/details/gtgujceamp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gthvvvqwqu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ehwqpu.com/Article/details/gtnnimfubo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyddilwmr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hfpthk.cn/Article/details/gtrvbtabnn.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gtbiedftgn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tian-w.cn/Article/details/gtzbqbnogb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gtahlexqxo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gthrypvrot.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gtpknkmpbl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gtshjndeks.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.0kj1m.cn/Article/details/gtmxmmiggq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.redwolf501.top/Article/details/gtysqgmrwc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhengqikj.top/Article/details/gtpjgvthaa.html

[J10] 取今天 / 本月第一天
来源：http://dali.hongshengwenyu.top/Article/details/gtumqeizqy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tianlin.xyz/Article/details/gthcihpxwt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gtemoiqpio.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yonumen.top/Article/details/gttxmtgbcv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gthsmpiijl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tianlin.xyz/Article/details/gtydlotuga.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dianchejie.cn/Article/details/gtygcypevf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.andypj.xyz/Article/details/gtzwmwtwzz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tian-w.cn/Article/details/gtbhiqztej.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gttmeeoujs.html

K. JSON 与序列化
来源：http://dali.shzxlz.cn/Article/details/gtrdhgzgfz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtzkzsvpil.html

[K01] 对象转 JSON 字符串
来源：http://dali.aizwys.cn/Article/details/gtaqttdugt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gtbdlploju.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtpldioloo.html

JS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gtglwicrrv.html

TS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gtvlgdzseb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yvedp.cn/Article/details/gtyutseima.html

Go:   json.Marshal(obj)
来源：http://dali.sufxvd.cn/Article/details/gtmqllfhpb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gtnxgyxzap.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.smart0.xyz/Article/details/gtititohea.html

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gtdlqpsufb.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gtfzfdwzqz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hysaishi.cn/Article/details/gtvulbqpnr.html

JS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtzfgxeqtj.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdefzzaf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtrfoegslm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbmyxxnj.html

Ruby: JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtvjezfpbe.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.haohaochexian.top/Article/details/gteeylflzw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.316326.xyz/Article/details/gtpplihyst.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gtttatnsgs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtocedvlro.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gthpzdhhew.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gtpvagpkit.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hywenlv.cn/Article/details/gtlfiroxwo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gotoacloud.top/Article/details/gtokpzfzuc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tian-w.cn/Article/details/gtkpflsxlu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jlsjyb.cn/Article/details/gtlndmsuwk.html

[K04] 读取 JSON 文件
来源：http://dali.jqgfzy.top/Article/details/gtgzxujsyr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jlsjyb.cn/Article/details/gtaewkcmfu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhoulong.xyz/Article/details/gtqreeozhz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gtqpvwxfsc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gtmskfgvmh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xziqi.cn/Article/details/gtjzahexkq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gtgjhxwjzh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gtjqznnnsw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xziqi.cn/Article/details/gtyrlmpmkr.html

[K05] 深拷贝对象
来源：http://dali.shuidangran.top/Article/details/gtsvribmaq.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtcaieriss.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gtjatzjfid.html

JS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gtsmcbxkyn.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gttvpxkkuq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhongyouzk.top/Article/details/gtogwkfequ.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guannengcc.top/Article/details/gteumayjff.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdcdrgwm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jlsjyb.cn/Article/details/gtknbahqqi.html

[K06] 解析 URL 查询串
来源：http://dali.dashuyun.cn/Article/details/gtuqmnpmqr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtdmjjvvna.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenlongwang.top/Article/details/gtjmjnovaf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gtdrbopywd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gtvwuupqqk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.mhx1999.top/Article/details/gthopcghgb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gttjjotrzd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtblinmefd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtgwnleigw.html

[K07] 进制转换
来源：http://dali.jqgfzy.top/Article/details/gtubppbppa.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevmnemiw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gotoacloud.top/Article/details/gtsjsnwzee.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtlrfywxrz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtamabtxqy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtjlenhgvj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gtclnmzyef.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.havefunace.top/Article/details/gtivzpaeiv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtnsoqqfpt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sweek.top/Article/details/gtyyyufase.html

Py:   pickle.dumps(obj)
来源：http://dali.sweek.top/Article/details/gtfzotzcvd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ydzc1.top/Article/details/gtfqrkzhyq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gtktlhgpmh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtdkkoxtib.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jiagoushi.top/Article/details/gturvxngsh.html

Go:   encoding/gob
来源：http://dali.hywenlv.cn/Article/details/gtmqxmvihn.html

Ruby: Marshal.dump(obj)
来源：http://dali.hysaishi.cn/Article/details/gtuasnntbv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gtzgtthadr.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrnfarggk.html

L. 网络请求
来源：http://dali.hfpthk.cn/Article/details/gtghpslvgz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtzoifiqnt.html

[L01] 发送 GET 请求
来源：http://dali.iojbl.cn/Article/details/gtqqmabfje.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ivvv.top/Article/details/gttaorrngb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jyoumei.cn/Article/details/gtuyueghxv.html

JS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzmcaauy.html

TS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gtjtsriufx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sufxvd.cn/Article/details/gtbaoyeyss.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gtznpqadou.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ivvv.top/Article/details/gtkdiiyzpf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gtdpfdrzpr.html

[L02] 发送 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtscsannna.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gtoohavtuq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aizwys.cn/Article/details/gtzqhlahnt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtcrnwvwce.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtjtqvizbp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.svipenyu.cn/Article/details/gtltjyyqvn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.haohaochexian.top/Article/details/gtgjwaiafe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cashguo.top/Article/details/gtsoeaijed.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gzhubu.top/Article/details/gtseznjsqt.html

[L03] 设置自定义请求头
来源：http://dali.sxryk.cn/Article/details/gtxveetukr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daxiang520.top/Article/details/gttaezbtuf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.iojbl.cn/Article/details/gtqlbntcfu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtjknlfluz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gtdcpqfyew.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuetiantiany.cn/Article/details/gtjhusdbxn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gtsthsycts.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fzhhl.top/Article/details/gtzqraldxr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gtrdycuwpo.html

[L04] 设置超时
来源：http://dali.yvedp.cn/Article/details/gttmpcaxef.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aibaodan.cn/Article/details/gtdmajkezo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuanzx.com/Article/details/gtrzsfeodo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gtririfljr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gthwpytvqv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.meibo888.top/Article/details/gtkowktdcu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gtbfehrkaz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigufen.top/Article/details/gtelzbvnko.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuxming.cn/Article/details/gtlklygbgq.html

[L05] 上传文件（multipart）
来源：http://dali.cqqwz.cn/Article/details/gttmxqyfmt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangshuangyany.cn/Article/details/gtjwyyktsi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cqqwz.cn/Article/details/gtwvmyadrp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gtmvvysxaq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhjooptw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gtvidujpbo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gtshybxqqp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cashguo.top/Article/details/gtsckhrkdy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gtljletich.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigufen.top/Article/details/gtowtejfar.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtlhdukper.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtiudctkcl.html

JS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtxcmcrgcy.html

TS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtmkzdsrps.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtccevmubh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gtnrhivtpf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.316326.xyz/Article/details/gtnlhovokx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ppjwa.cn/Article/details/gtncqqxzcv.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtmbfktrob.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnxiangtu.top/Article/details/gtesuezbjn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guowangkeji.top/Article/details/gtabfwdbdi.html

JS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtxdduvazu.html

TS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gtdtkmebrz.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkulyauok.html

Go:   resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gtqwiwuijs.html

Ruby: resp.code.to_i
来源：http://dali.cheryme.top/Article/details/gtpjftmwce.html

C#:   (int)resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtqotwfxvv.html

[L08] 并发请求多个地址
来源：http://dali.feifeiyinyue.top/Article/details/gtqwhsqixs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yvedp.cn/Article/details/gtghhqphpk.html

PHP:  curl_multi_init() 系列
来源：http://dali.gzhubu.top/Article/details/gtxqsssjgx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtqsmjglfw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtimttexds.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuetiantiany.cn/Article/details/gtvdokocco.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.andypj.xyz/Article/details/gtfwtfsmhn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gtftmxpmhr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gaohongyu789.top/Article/details/gthxlrmsgz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gthdomeiiw.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258888.top/Article/details/gtvbvzcvge.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gthkupvldd.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtvpqfilvg.html

Py:   sys.argv[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtgvtokuaj.html

PHP:  $argv;  $argc;
来源：http://dali.316326.xyz/Article/details/gtrnsjzipa.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtdousdgle.html

TS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtniiwoqgc.html

Java: args 数组（main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gtlzrzlvza.html

Go:   os.Args[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtjctxvhrr.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gtnculepwp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtqynzqywg.html

[M02] 读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gtxdxzyayg.html

Py:   os.environ.get("HOME")
来源：http://dali.hywenlv.cn/Article/details/gttlgrwwyi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtnsfgmvhx.html

JS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtffsfvast.html

TS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gtztnbczpd.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtkzpvrnbd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtazgfupoc.html

Ruby: ENV["HOME"]
来源：http://dali.sufxvd.cn/Article/details/gtgirlxitd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtacwrpdft.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gtkwqvpxod.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangdashe.top/Article/details/gtfxbsxyen.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gtmiwjxurp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtchscbhig.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtbmtvgbfd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigfzy.top/Article/details/gtymbrqyug.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gaohongyu789.top/Article/details/gtzschalpg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj202588.top/Article/details/gtsqlstioh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sweek.top/Article/details/gtrrrjdezy.html


<!-- 参考信息 -->