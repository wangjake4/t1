代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.0kj1m.cn/Article/details/gtyahlismv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajpcuuhl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtoyovaqdl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtjubqcpxj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aizwys.cn/Article/details/gttsqfasjv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shuidangran.top/Article/details/gtyumvydkt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtsqupjnia.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tanke756.top/Article/details/gtxgiucjpc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xziqi.cn/Article/details/gtnqlfgtcs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtpimmdreq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangdashe.top/Article/details/gtiqhgdwxx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtekjxmqei.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gtivitxtqt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtwpugiypy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhengqikj.top/Article/details/gtdyfrklmj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj202588.top/Article/details/gtyltxzsxl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtjgopiyws.html

[I07] 忽略大小写与多行模式
来源：http://dali.jiagoushi.top/Article/details/gtqxsixomw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.quarkkingdee.top/Article/details/gtaqiigncc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtwmdhoxnl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gtksrpqoik.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gtburkmxcv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuxming.cn/Article/details/gtbguqqzhf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhiwuduotai.top/Article/details/gtjqowlxdi.html

Ruby: s.scan(/error/i)
来源：http://dali.gaohongyu789.top/Article/details/gtvqlmuaeu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gteaexriiq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cdnleiting.top/Article/details/gtzbbbvjrg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangdashe.top/Article/details/gtokhxrzbs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtnhuayxxc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtydyxuuxf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtyhgapjfn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtmuvuvwfx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.snrcjt.cn/Article/details/gtcmigyzog.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sxryk.cn/Article/details/gtwjplljqe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtbhrgrshw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gttuiszwcr.html

J. 日期与时间
来源：http://dali.316326.xyz/Article/details/gtjrpuflrs.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtdakkbdky.html

[J01] 获取当前时间
来源：http://dali.nanxinkj.top/Article/details/gtvvwpqhco.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gthebuaguv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gtvwhliaug.html

JS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gtwjtgypcs.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gttchelqre.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tian-w.cn/Article/details/gtqhrwldrv.html

Go:   time.Now()
来源：http://dali.yonumen.top/Article/details/gtyrfeaect.html

Ruby: Time.now
来源：http://dali.ydzc1.top/Article/details/gtcabpihvn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gtxzrshesg.html

[J02] 格式化输出
来源：http://dali.zhixingplan.top/Article/details/gtbcwacevx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gtnsizcatb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtkhogedfp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gttsaivkqt.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gtpnxxrvjb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dianchejie.cn/Article/details/gteqgvgjtu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhongyouzk.top/Article/details/gtkbyseqou.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gtvwpxmnfv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yonumen.top/Article/details/gtfvxyipgj.html

[J03] 字符串解析为日期
来源：http://dali.nanxinkj.top/Article/details/gtgyyrezkl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.redwolf501.top/Article/details/gtznsvseif.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tianlin.xyz/Article/details/gtkfzewajo.html

JS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtgclfhclz.html

TS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtittiovpq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtusbqpjwl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtjhxltygk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtncntvked.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xinyue.icu/Article/details/gtqshrjxsn.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gtwbbtriez.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtfjkwrkah.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gtlpmoabob.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cqqwz.cn/Article/details/gtgmnnfkoe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbcdkrfn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuxming.cn/Article/details/gtdulcwlek.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gtpkzsqyvz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuanzhike.top/Article/details/gtredjfrfo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tian-w.cn/Article/details/gtcbiijbrs.html

[J05] 时间加减（加 7 天）
来源：http://dali.svipenyu.cn/Article/details/gtlafmtwqj.html

Py:   now + timedelta(days=7)
来源：http://dali.aizwys.cn/Article/details/gtkxuziuuw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gthvhfemcc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdvunxfs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gtqtunfykz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtqhbscsid.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sxryk.cn/Article/details/gtkzbrlorz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gttewyvzxz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gtoyzqwnpm.html

[J06] 计算两时间之差
来源：http://dali.jinqigfzy.top/Article/details/gtxpulvluc.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gtrewdumhy.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenzaomai.com/Article/details/gtmmskbzrt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnxiangtu.top/Article/details/gtrjchdjjp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gtluvoeycj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tian-w.cn/Article/details/gtbrndwnxr.html

Go:   end.Sub(start).Hours()
来源：http://dali.yanxiufei.cn/Article/details/gthpxvsrfo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tian-w.cn/Article/details/gtohbnfnza.html

C#:   (end - start).TotalSeconds
来源：http://dali.havefunace.top/Article/details/gtbyazqlmv.html

[J07] 比较两个日期
来源：http://dali.yvedp.cn/Article/details/gtzoebrast.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtgqrmlenn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj202588.top/Article/details/gtbcerujlh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gtxblyrugp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gtkhrrpnjr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yueranfly.top/Article/details/gticekamwg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ivvv.top/Article/details/gtqiuvznie.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqoaforu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtjrcxiywi.html

[J08] 提取年月日与星期
来源：http://dali.feifeiyinyue.top/Article/details/gtexibassk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gtufqjovzr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tanke756.top/Article/details/gthkktghnw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.vqdsnc.cn/Article/details/gtiylivehg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.meibo888.top/Article/details/gtlfmrvuay.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gtpxefqvpy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gtfhyfqjmn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cheryme.top/Article/details/gtpmifjeva.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gtzvsgekbn.html

[J09] 时区处理
来源：http://dali.daxiang520.top/Article/details/gtrsqyxyhf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqyfdryt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gogol.net.cn/Article/details/gtrgkdfptm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtbtsgunuu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdtcqkgr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.feifeiyinyue.top/Article/details/gtyzzhzkbu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fzhhl.top/Article/details/gthxrribtl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhongyouzk.top/Article/details/gtsisgrosu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ydzc1.top/Article/details/gtzwlysuit.html

[J10] 取今天 / 本月第一天
来源：http://dali.tanke756.top/Article/details/gtumgugmmm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guannengcc.top/Article/details/gtndqgntqg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gzhubu.top/Article/details/gtlywvrnne.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtutpvwoap.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ybcxt.top/Article/details/gtaeyuqceq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.redwolf501.top/Article/details/gtuveajhxq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fengsongda.top/Article/details/gtwwogjrlj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ppjwa.cn/Article/details/gtnezmwzkg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygjujndz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtdltrwjxr.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gttwvzrryq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtjbktitiq.html

[K01] 对象转 JSON 字符串
来源：http://dali.pycfn.com/Article/details/gtdjsotckn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gttoyesaev.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gtcckgusoc.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtipyjlwkv.html

TS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtlczagihl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.meibo888.top/Article/details/gtfyqlzxfp.html

Go:   json.Marshal(obj)
来源：http://dali.zhengqikj.top/Article/details/gtvhwudyxa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tanke756.top/Article/details/gtrabuyqcm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gthnofnplx.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gtskhmkglj.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gtghlumfdi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gtqzbqletz.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnndpgum.html

TS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtzvknxgmj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtvzptxtnz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtijtjdgdt.html

Ruby: JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtmqubfkkz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtkavqnhpn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangshuangyany.cn/Article/details/gtiowabbjr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gtojbdldzq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtylxwlggd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gtbdoqgytq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gteviybuvw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.snrcjt.cn/Article/details/gtstmazbhd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yanxiufei.cn/Article/details/gtsafstxec.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gogol.net.cn/Article/details/gtqsjajimj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258.top/Article/details/gtmgmfrxel.html

[K04] 读取 JSON 文件
来源：http://dali.zdqjudy.top/Article/details/gtbopkbsjk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgufenzy.top/Article/details/gtpkkdzwll.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xziqi.cn/Article/details/gtsqhqeftt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtzoeavgwo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gtndrotxnz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gtodgagvar.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtzqrcdbzw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtyvidshhe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aizwys.cn/Article/details/gtgrusivcm.html

[K05] 深拷贝对象
来源：http://dali.hnqzz.top/Article/details/gtpwgemirv.html

Py:   copy.deepcopy(obj)
来源：http://dali.fzhhl.top/Article/details/gtaukuiron.html

PHP:  unserialize(serialize($obj));
来源：http://dali.kuanghao11.cn/Article/details/gtxnfjcdsh.html

JS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtbcgzhqgf.html

TS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtcgkeiqrc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nwbrower.top/Article/details/gtvzczlldo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daria6918.cn/Article/details/gtpbztkubz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zycfv.cn/Article/details/gtybkvmsks.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yanxiufei.cn/Article/details/gtorumpxqn.html

[K06] 解析 URL 查询串
来源：http://dali.yangfankeji.com/Article/details/gtcndsomcl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gtypoymqxu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shangyingyoupin.top/Article/details/gthtybanxx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gturygebjo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gteffugtlw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.havefunace.top/Article/details/gtssssmnoc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtzmbacjad.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtxgihnrwx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtvfomzgxs.html

[K07] 进制转换
来源：http://dali.kuanghao11.cn/Article/details/gtdfngwfin.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtnwskjods.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ybcxt.top/Article/details/gtoesojzcf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtfdtavcyl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gttoeewklc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtkedmvoyz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yvedp.cn/Article/details/gtngtdvexw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aizwys.cn/Article/details/gtbtjbjxpz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtodgqaxcv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gtgddhbvza.html

Py:   pickle.dumps(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtooogcdbh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnqzz.top/Article/details/gtbvfdevtl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtamsqstdx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gtrgzpukck.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gaohongyu789.top/Article/details/gtbfzwzwtn.html

Go:   encoding/gob
来源：http://dali.shanyushiyangtech.top/Article/details/gtcuuogtni.html

Ruby: Marshal.dump(obj)
来源：http://dali.hysaishi.cn/Article/details/gthrosfhaf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yongpay.top/Article/details/gtqovgsqok.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtryrgmuqp.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gtbqmrhigl.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtqgoehxif.html

[L01] 发送 GET 请求
来源：http://dali.bjfxy.top/Article/details/gtbkmxzeay.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj202588.top/Article/details/gtouqkeajq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gaohongyu789.top/Article/details/gtslyzazgx.html

JS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gtmjvvvltl.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gtsaagvvjm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuanzhike.top/Article/details/gtzpzblqci.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhengqikj.top/Article/details/gtdigxojlr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gotoacloud.top/Article/details/gtajenxdhf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnktncqif.html

[L02] 发送 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gtsonfpxhl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gthnfgylcj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gtggjgosma.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gtprlrmyjy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtetjymxym.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hfpthk.cn/Article/details/gtxqzemued.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shangyingyoupin.top/Article/details/gtfjxdgjvz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.svipenyu.cn/Article/details/gtwawtxvju.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.c1oappe.top/Article/details/gtpvrimxtp.html

[L03] 设置自定义请求头
来源：http://dali.daxiang520.top/Article/details/gtpcpmdais.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gtrzhmbweq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sufxvd.cn/Article/details/gtzunfextw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gtrblzwuyi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtwtnzyyne.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zdqjudy.top/Article/details/gtqzfshdvr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gttnlshdkm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dianchejie.cn/Article/details/gtlyztseec.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtuhfcwgnu.html

[L04] 设置超时
来源：http://dali.ydzc1.top/Article/details/gtnqybtany.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xinyue.icu/Article/details/gtgfzcepay.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gzhubu.top/Article/details/gtpjjaignt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtdchowess.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtcucmwvii.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgfzy.top/Article/details/gtcyvxkidi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gtdivitnnk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjhgaotw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.316326.xyz/Article/details/gtdgnetryc.html

[L05] 上传文件（multipart）
来源：http://dali.pengpengdd.cyou/Article/details/gtmuniucbj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nwbrower.top/Article/details/gttgrmvmdx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.kuanghao11.cn/Article/details/gtgjajnalu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gtayyfbygk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtalhrufch.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.kuanghao11.cn/Article/details/gtacxfucis.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunayafkf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gtpoqzvphq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtozglglew.html

[L06] 解析响应为 JSON
来源：http://dali.sufxvd.cn/Article/details/gtksqjitxg.html

Py:   resp.json()
来源：http://dali.iojbl.cn/Article/details/gtarmsqirm.html

PHP:  json_decode($body, true);
来源：http://dali.zhengqikj.top/Article/details/gtjmbtmqyz.html

JS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtlqxylicu.html

TS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtacqeuszd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtugxzizvn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjprslsos.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhiwuduotai.top/Article/details/gtroqrjiqj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvnmmmlq.html

[L07] 处理 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gtwnrvrhvq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shangyingyoupin.top/Article/details/gtiyxapmlb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sufxvd.cn/Article/details/gtwejhfgoc.html

JS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gttxntyvea.html

TS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvlcrart.html

Java: resp.statusCode()
来源：http://dali.feifeiyinyue.top/Article/details/gtwurggtap.html

Go:   resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtwfnjvfsk.html

Ruby: resp.code.to_i
来源：http://dali.jianghu66.top/Article/details/gtsrqmswzv.html

C#:   (int)resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtfbgraonh.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gtavyfmlzn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guannengcc.top/Article/details/gtrudhjfoz.html

PHP:  curl_multi_init() 系列
来源：http://dali.yueranfly.top/Article/details/gtgzzlhcyp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtkflbpxpf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtbcvdvgih.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.316326.xyz/Article/details/gtruisnzzk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdlypyxb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvlrxgjv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhengqikj.top/Article/details/gtrekgxmlt.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gteeawsxkj.html

M. 命令行 / 进程 / 环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxejbwaeo.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtigkencan.html

[M01] 读取命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gtqnqiivfd.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtqottsdbf.html

PHP:  $argv;  $argc;
来源：http://dali.cheryme.top/Article/details/gtdaefzunh.html

JS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtiegugdwo.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtkxjwmqcw.html

Java: args 数组（main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gtvuvkzjwh.html

Go:   os.Args[1:]
来源：http://dali.redwolf501.top/Article/details/gtovtzhzco.html

Ruby: ARGV
来源：http://dali.wangshuangyany.cn/Article/details/gtvfdpsmcw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtahfaikrf.html

[M02] 读取环境变量
来源：http://dali.mhx1999.top/Article/details/gtukbobzzs.html

Py:   os.environ.get("HOME")
来源：http://dali.xylfe.cn/Article/details/gtkxhjvjwa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gtzbuctntg.html

JS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gtkgtxubsi.html

TS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gtugwihdym.html

Java: System.getenv("HOME")
来源：http://dali.birdmap.top/Article/details/gtnanhkiyi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtzuuaijzu.html

Ruby: ENV["HOME"]
来源：http://dali.hnxiangtu.top/Article/details/gtrhvzcrcz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtwdsghxzd.html

[M03] 执行外部命令
来源：http://dali.gzhubu.top/Article/details/gtlsbcqtgw.html


<!-- 参考信息 -->