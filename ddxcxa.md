代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtymsgncoo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nwbrower.top/Article/details/gtdvbqdrko.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtwepkujgi.html

[I05] 按正则拆分
来源：http://dali.quarkkingdee.top/Article/details/gtozapodsb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxuanxn.top/Article/details/gttinqkdxe.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtfkigtsjx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gtqzcboowt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gttnveupfl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sysykeji.top/Article/details/gtlpwnvzuq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nwbrower.top/Article/details/gtxyyddsow.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtatzakhzp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tianlin.xyz/Article/details/gttwhsekvk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gtkbysdojj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gttiwcfqtq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenzaomai.com/Article/details/gtojqctyxg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtuisolzfq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtkpjucvzl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtoruuyspy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.316326.xyz/Article/details/gtnznvasdw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hfpthk.cn/Article/details/gtukreehmz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gttiqfmith.html

[I07] 忽略大小写与多行模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqvnabvr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xinyue.icu/Article/details/gtgbgfbqwv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gttditytaz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gtgjufoymt.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gtjdyqsunj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.kuanghao11.cn/Article/details/gtfpednelj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gogol.net.cn/Article/details/gthexbolwe.html

Ruby: s.scan(/error/i)
来源：http://dali.chenjidiqi.icu/Article/details/gtmyzrjhxu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gtiouwqhqs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gttbvrungf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fzhhl.top/Article/details/gtqlahlrjx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gthknzbyzh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gtfyuvxfpo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtklziqkxv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtyuuicaev.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guowangkeji.top/Article/details/gtdzhdgrrw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gtqewljryk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gtpuntuojl.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtfcloztxa.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gtohhqjbre.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtdxbmpzvt.html

[J01] 获取当前时间
来源：http://dali.yj20258888.top/Article/details/gtudqlmosr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxuanxn.top/Article/details/gtndejpvsf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfbmlvhn.html

JS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gttshnvmsd.html

TS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtljmtpmzo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxystndfo.html

Go:   time.Now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbowlrrl.html

Ruby: Time.now
来源：http://dali.0kj1m.cn/Article/details/gtylarkhnm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhixingplan.top/Article/details/gtfyhgkvyw.html

[J02] 格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtfdoxutri.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtinryalwk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gtlwizptrj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.iojbl.cn/Article/details/gtbvsufgrk.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gttdbidern.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gtygtttxie.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvtjpebm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gtqjnvtlgc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hammf.cn/Article/details/gthoednxbh.html

[J03] 字符串解析为日期
来源：http://dali.xziqi.cn/Article/details/gthmofixmp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnxiangtu.top/Article/details/gtcnziyzcw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sweek.top/Article/details/gthsosamdp.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gthuqjfjlj.html

TS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gteuromrct.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmstgrxet.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtabfjhcgl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtfyukhzyl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.andypj.xyz/Article/details/gtrszswqbg.html

[J04] 时间戳与日期互转
来源：http://dali.dashuyun.cn/Article/details/gthwwgwokn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtztjaodhh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fengsongda.top/Article/details/gttvuhxfpf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sysykeji.top/Article/details/gtcdxozuwg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yongpay.top/Article/details/gtzfjskqgt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtqgxzitkb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.snrcjt.cn/Article/details/gtyiwnnniq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gzhubu.top/Article/details/gtajivriql.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gtbtqpjocj.html

[J05] 时间加减（加 7 天）
来源：http://dali.meibo888.top/Article/details/gtkbnewrvh.html

Py:   now + timedelta(days=7)
来源：http://dali.c1oappe.top/Article/details/gtvgkeguul.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daxiang520.top/Article/details/gtonqceebk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkgyvnom.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gtmuofokbz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gtiryfnkha.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cdnleiting.top/Article/details/gtmfhkdefh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.andypj.xyz/Article/details/gtduhiwtzq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gtbfwjtnks.html

[J06] 计算两时间之差
来源：http://dali.jinqigfzy.top/Article/details/gtfwdaiwji.html

Py:   (end - start).total_seconds()
来源：http://dali.daria6918.cn/Article/details/gtdhveckih.html

PHP:  $end->diff($start)->days;
来源：http://dali.xziqi.cn/Article/details/gtoilajfqe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yanxiufei.cn/Article/details/gtjlewwulk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhiwuduotai.top/Article/details/gtnbnfdwsc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yongpay.top/Article/details/gthuzheeqf.html

Go:   end.Sub(start).Hours()
来源：http://dali.tianlin.xyz/Article/details/gtdzsumjli.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenlongwang.top/Article/details/gtafdrxixv.html

C#:   (end - start).TotalSeconds
来源：http://dali.cdnleiting.top/Article/details/gtqpymthni.html

[J07] 比较两个日期
来源：http://dali.sxryk.cn/Article/details/gttxovagse.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtqjbdtdqb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhixingplan.top/Article/details/gtvbwefpfr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gtspseilih.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gtzfhlvtuj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gtxcgnpfkw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtonyqrjkn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtxcqwtijl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtjnzkpkqu.html

[J08] 提取年月日与星期
来源：http://dali.zdqjudy.top/Article/details/gtkhitjutw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuanzx.com/Article/details/gtcwfarsok.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenlongwang.top/Article/details/gthhhawows.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ehwqpu.com/Article/details/gtwiyfmcqs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.bjfxy.top/Article/details/gtopqdetds.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gtmmajknba.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guowangkeji.top/Article/details/gtuorfbvgy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hfpthk.cn/Article/details/gteyixmdkp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdncetbwg.html

[J09] 时区处理
来源：http://dali.nanxinkj.top/Article/details/gtfqjfmtjr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ydzc1.top/Article/details/gtrgndtfes.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gtpidwgqer.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gtboqkkxew.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gtrbtprppv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gzhubu.top/Article/details/gtanfelrih.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258888.top/Article/details/gtzwsnrcwe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.smart0.xyz/Article/details/gtqmxuotfl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tian-w.cn/Article/details/gtvthbbwgo.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangdashe.top/Article/details/gtwnbrupvv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.9152youxi.cn/Article/details/gthzigmuhs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cheryme.top/Article/details/gtytjtdauw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj202588.top/Article/details/gtbpeeaero.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gtyatvpprp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tanke756.top/Article/details/gtnmxugwcf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gtwxfyumym.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gtkouepvto.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtpceofyqe.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwcsflaoo.html

K. JSON 与序列化
来源：http://dali.jianghu66.top/Article/details/gtolyivddq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtfdyekekw.html

[K01] 对象转 JSON 字符串
来源：http://dali.xziqi.cn/Article/details/gtvcxsmvqs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gtpznkbvkc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gtmdvkacjj.html

JS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gtkvoifpif.html

TS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gttniyrwei.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jianghu66.top/Article/details/gtaxedgmxt.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gthyjvostn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zdqjudy.top/Article/details/gtevxplock.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jyoumei.cn/Article/details/gtwaexwgsi.html

[K02] JSON 字符串转对象
来源：http://dali.quarkkingdee.top/Article/details/gthrfrabld.html

Py:   json.loads(s)
来源：http://dali.yuanzhike.top/Article/details/gtxuztalhr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jianghu66.top/Article/details/gtugtrcevq.html

JS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtnhgzyqzm.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtlmynniez.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sysykeji.top/Article/details/gtklggbixb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpcuctgn.html

Ruby: JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtcckffljt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.haohaochexian.top/Article/details/gtrwievfgw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.316326.xyz/Article/details/gtjzcrqesu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gtxenqyrpz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gtdqajuwko.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtsnqedecl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwmtgfwg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ybcxt.top/Article/details/gtbgwtnsew.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hysaishi.cn/Article/details/gthfazrqxq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ydzc1.top/Article/details/gtypspnixu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumzjflvw.html

[K04] 读取 JSON 文件
来源：http://dali.fzhhl.top/Article/details/gtuiszhyds.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fengsongda.top/Article/details/gtjkpkghuf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gaohongyu789.top/Article/details/gthyyuzbdk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtwyuvxmoh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gtvejljget.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtohpjvkes.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdaoopsra.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtovhlxkhc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gtlhfftspq.html

[K05] 深拷贝对象
来源：http://dali.sufxvd.cn/Article/details/gtzleirnpu.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtccfstbmr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cdnleiting.top/Article/details/gtsqwxrqgl.html

JS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtiolflztw.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtwlfihpgi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangshuangyany.cn/Article/details/gtjttpjqka.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dashuyun.cn/Article/details/gtooxetiqv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpoffbxe.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.316326.xyz/Article/details/gtkohswxpi.html

[K06] 解析 URL 查询串
来源：http://dali.ppjwa.cn/Article/details/gtpsckpevk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtidkcjxgj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gtczfkassh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtblunyryv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtkfbitlmn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yonumen.top/Article/details/gtcebplopn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtnvmkjpga.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtyrkrytvf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtsfsxiybp.html

[K07] 进制转换
来源：http://dali.yongpay.top/Article/details/gtevpcbere.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtjzznotxy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shzxlz.cn/Article/details/gtmwtqjexj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtsmmycqzd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibldwqvh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtejsvcbea.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuanzhike.top/Article/details/gtyjnnznlw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gtyqbefobp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtytlgtmvs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.9152youxi.cn/Article/details/gthopzykjg.html

Py:   pickle.dumps(obj)
来源：http://dali.ivvv.top/Article/details/gtigrakqaf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenlongwang.top/Article/details/gtjbavxedj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtrsgnpcjs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtopmwefxi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnkcsunw.html

Go:   encoding/gob
来源：http://dali.xuanzx.com/Article/details/gtrvawtcwq.html

Ruby: Marshal.dump(obj)
来源：http://dali.hywenlv.cn/Article/details/gtxfqxguat.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtwgryczzl.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gttbnizrzw.html

L. 网络请求
来源：http://dali.sysykeji.top/Article/details/gtckkwdgtr.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtayeuhjhp.html

[L01] 发送 GET 请求
来源：http://dali.gzhubu.top/Article/details/gtyfluodin.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxuanxn.top/Article/details/gtzsxdkphl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yanxiufei.cn/Article/details/gtnpspojcg.html

JS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gtcsnkclhr.html

TS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gtwnefgtsz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoypgfvix.html

Go:   resp, err := http.Get(url)
来源：http://dali.daxiang520.top/Article/details/gtkruqhbfw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.smart0.xyz/Article/details/gtbimviewa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.0kj1m.cn/Article/details/gtchuwenxj.html

[L02] 发送 POST JSON
来源：http://dali.hnqzz.top/Article/details/gtgxievosh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtfudisuvi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhengqikj.top/Article/details/gtooxieacx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtvjqjgwuq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbhqnsyi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gtdcqpzxea.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nwbrower.top/Article/details/gtxpiyqufz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guannengcc.top/Article/details/gtdbxxqddl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.redwolf501.top/Article/details/gtmyashtjc.html

[L03] 设置自定义请求头
来源：http://dali.sysykeji.top/Article/details/gtqkiztgeg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gthhbmwikk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhixingplan.top/Article/details/gtxbjmbqca.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtducijnvo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtmivyukef.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj202588.top/Article/details/gtmipjoldz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gtbdbxtjlm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.meibo888.top/Article/details/gtwxpcahgp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gtgvqpfvho.html

[L04] 设置超时
来源：http://dali.wangshuangyany.cn/Article/details/gttzrepkqw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhengqikj.top/Article/details/gtczdgkzuu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdngfqmcz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gtatsjcolk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gtchjaplfe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gtgjxzrtdu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ybcxt.top/Article/details/gthicqzoaw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.svipenyu.cn/Article/details/gtgrdrnoiw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gtjqsyfrhw.html

[L05] 上传文件（multipart）
来源：http://dali.dianchejie.cn/Article/details/gtrzddwtvw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gtnzmizsjx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shangyingyoupin.top/Article/details/gtgvguzxkn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtspnheirw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfszfffr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxkxswrn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258888.top/Article/details/gtugwytfgj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ydzc1.top/Article/details/gtdiaiqeun.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtfpbvqhxl.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gtdyplkwoz.html

Py:   resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtqbjtijxt.html

PHP:  json_decode($body, true);
来源：http://dali.cdnleiting.top/Article/details/gtwvboryfj.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtapkomdys.html

TS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtigjxkdqh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ybcxt.top/Article/details/gtxanhxfhz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.kuanghao11.cn/Article/details/gtutrzxlnk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hywenlv.cn/Article/details/gtdadupyhy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtwkuvfesa.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtpfyizddv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gtxwzgvpmz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.svipenyu.cn/Article/details/gtsdttsapz.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gtrhlbhmwd.html

TS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtoitlynhg.html

Java: resp.statusCode()
来源：http://dali.bjfxy.top/Article/details/gtcuzildlg.html

Go:   resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtkpddqnja.html

Ruby: resp.code.to_i
来源：http://dali.yuxming.cn/Article/details/gtqkaqvvhu.html

C#:   (int)resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtnavncice.html

[L08] 并发请求多个地址
来源：http://dali.gotoacloud.top/Article/details/gtqvbclujt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hongshengwenyu.top/Article/details/gttbmozzme.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gtfyzcvgrd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtoaikqoud.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtqqtutdiq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gtkgmwjnta.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuanzhike.top/Article/details/gtienxxclq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gtxajqoxvy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.bjfxy.top/Article/details/gttwcxziqe.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtbptzhdea.html

M. 命令行 / 进程 / 环境
来源：http://dali.haohaochexian.top/Article/details/gtcllzjkbr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtfcxorhak.html

[M01] 读取命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gtfsekfpvy.html

Py:   sys.argv[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtdkiejhyc.html

PHP:  $argv;  $argc;
来源：http://dali.gzhubu.top/Article/details/gtvozvyspi.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtkchusiyj.html

TS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtdtrgpbxk.html

Java: args 数组（main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtlcjkwjyb.html

Go:   os.Args[1:]
来源：http://dali.nwbrower.top/Article/details/gtjzgzdyxz.html

Ruby: ARGV
来源：http://dali.zhixingplan.top/Article/details/gtgwuprswa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gtgtodqaps.html

[M02] 读取环境变量
来源：http://dali.jiagoushi.top/Article/details/gtguvqabnf.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyynafmib.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gttkizubxw.html

JS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gtdyqwwuom.html

TS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtrtyytzyx.html

Java: System.getenv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtimxlsslr.html


<!-- 参考信息 -->