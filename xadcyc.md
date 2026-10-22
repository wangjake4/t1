代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gtuponowms.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hammf.cn/Article/details/gttcrnuehw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gtprapuuwe.html

[I05] 按正则拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtdpwlbuem.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hysaishi.cn/Article/details/gtekqtkaxy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanjhypve.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtcjsxjseb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtujszlgwu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtoziuzzij.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xylfe.cn/Article/details/gtlkdklqxm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtosxquaah.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gtwztgbtts.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hysaishi.cn/Article/details/gtfelnatzm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtgwnlvlhl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gtddxnkmqn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gtiassaacg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gtpjfytziu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtufdmoleo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.9152youxi.cn/Article/details/gtfkhqdvop.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.haohaochexian.top/Article/details/gtyvdzzabx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtfakdmtqp.html

[I07] 忽略大小写与多行模式
来源：http://dali.0kj1m.cn/Article/details/gtzhjccppo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuxming.cn/Article/details/gtqbyvldcl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hammf.cn/Article/details/gtgsobxhts.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dianchejie.cn/Article/details/gtdwkjlkne.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gtpsgtyypf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndxyiwbm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gtpplsobps.html

Ruby: s.scan(/error/i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfeomqndo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.smart0.xyz/Article/details/gtfvuerxwh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtnzqybhlm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tanke756.top/Article/details/gttkiilabu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtbpxgptti.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtlfvemomn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtyvgrhosy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gtcvdpxaxf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ydzc1.top/Article/details/gtdamxsjdd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pycfn.com/Article/details/gtkflslxkj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gtgqusmlry.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtwcujqmby.html

J. 日期与时间
来源：http://dali.jinqigufen.top/Article/details/gtfnhuebiv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtqbvsdtat.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gtjksewhwj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sweek.top/Article/details/gtstabqrmo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtmmjmgnze.html

JS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtiovweeml.html

TS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gttlnditja.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.kuanghao11.cn/Article/details/gtwdjlzhem.html

Go:   time.Now()
来源：http://dali.hammf.cn/Article/details/gtajvyzpsk.html

Ruby: Time.now
来源：http://dali.vqdsnc.cn/Article/details/gtmtbquwqo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhixingplan.top/Article/details/gthdfalcyg.html

[J02] 格式化输出
来源：http://dali.ivvv.top/Article/details/gtpnvrlzgo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gtibeebdxd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkryktsc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258888.top/Article/details/gttmeoucvy.html

TS:   d.toISOString()
来源：http://dali.9152youxi.cn/Article/details/gtkoatnhar.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cdnleiting.top/Article/details/gtrjkttoob.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tian-w.cn/Article/details/gtvfbnccxt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtveqgmgnd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjuqelrp.html

[J03] 字符串解析为日期
来源：http://dali.bjfxy.top/Article/details/gtjpmexxca.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tianlin.xyz/Article/details/gtgisibvuo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gtmzfobrev.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gthewvolmk.html

TS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtxuhzgxhx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtodonjsng.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtwuldpief.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtxcusgjnd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gzhubu.top/Article/details/gtigkmorgi.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gtvlhdgjtv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sxryk.cn/Article/details/gtizzvgzjd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuanzhike.top/Article/details/gtnxoeffxb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangdashe.top/Article/details/gtktlmvdki.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xziqi.cn/Article/details/gtjqjnndfi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gtqnvobwle.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jyoumei.cn/Article/details/gtpkvlpfej.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gtafbzzfzp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnarqjuu.html

[J05] 时间加减（加 7 天）
来源：http://dali.jiagoushi.top/Article/details/gtscduelpu.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigufen.top/Article/details/gtqknxspwv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yangfankeji.com/Article/details/gtmrtvuqxv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gtubffsmwj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopsbdjak.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gtwspemzgj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhongyouzk.top/Article/details/gtpsujkxmg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenjidiqi.icu/Article/details/gthwxvhabr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtnkchnuij.html

[J06] 计算两时间之差
来源：http://dali.cheryme.top/Article/details/gtbegtviee.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gtgsdlgzsd.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gtzaguxvvx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fengsongda.top/Article/details/gtckfpwzwu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yanxiufei.cn/Article/details/gtglwfgwja.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.feifeiyinyue.top/Article/details/gtsjrnneva.html

Go:   end.Sub(start).Hours()
来源：http://dali.quarkkingdee.top/Article/details/gtxlgrwlgf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pengpengdd.cyou/Article/details/gthxutuhea.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuxming.cn/Article/details/gtnakzybfz.html

[J07] 比较两个日期
来源：http://dali.shzxlz.cn/Article/details/gtyqvyijdg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtyiscaxex.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daxiang520.top/Article/details/gthoqcqxrr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtqbngwslg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtrhltoyjy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gthbmtyylj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtwazdiceu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtsassqjkn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtwtrxhgcb.html

[J08] 提取年月日与星期
来源：http://dali.aibaodan.cn/Article/details/gtfhnypvao.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gttqnqdzyo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuetiantiany.cn/Article/details/gtxdavdchb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuetiantiany.cn/Article/details/gttgvhmqtq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258888.top/Article/details/gtslokcjpm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yangfankeji.com/Article/details/gtusnfieip.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jyoumei.cn/Article/details/gtchgyaizq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gtcpncweok.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xinyue.icu/Article/details/gtnnkbswyc.html

[J09] 时区处理
来源：http://dali.chenjidiqi.icu/Article/details/gtiuwvsjqx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhoulong.xyz/Article/details/gthmudfvid.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hysaishi.cn/Article/details/gtqqdvnvrl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtvvmtvgqi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gtaraewphj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.meibo888.top/Article/details/gtwmrrcjnu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cucudq.cn/Article/details/gtusywwpka.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangtech.top/Article/details/gtiizbsixw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuetiantiany.cn/Article/details/gtrcfedvwj.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gtxsvvkiar.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gtcvddajbo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.316326.xyz/Article/details/gtywsifpal.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.mhx1999.top/Article/details/gttdlvwdim.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gzhubu.top/Article/details/gtfohdmghi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hfpthk.cn/Article/details/gtjijutddb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tian-w.cn/Article/details/gtwuwovltp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxuanxn.top/Article/details/gtrxmqhsmp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnxiangtu.top/Article/details/gtdubcnmby.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtrqocdvsv.html

K. JSON 与序列化
来源：http://dali.andypj.xyz/Article/details/gtpgeqzuhb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtansiftqm.html

[K01] 对象转 JSON 字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtomguastc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtdfusskyg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gttwdhpvwa.html

JS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtxpuxipwh.html

TS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtxuwkepmz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aibaodan.cn/Article/details/gtwupwuadh.html

Go:   json.Marshal(obj)
来源：http://dali.daria6918.cn/Article/details/gtwoffwrrh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhongyouzk.top/Article/details/gtzgxzylvo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.svipenyu.cn/Article/details/gtapzzpqkg.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gtlquozyte.html

Py:   json.loads(s)
来源：http://dali.jinqigufen.top/Article/details/gtuqinusjp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.svipenyu.cn/Article/details/gtnrvllcfy.html

JS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtaawnkdgs.html

TS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtuuczouea.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yongpay.top/Article/details/gtrelbmcnt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gtirtbomge.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gthriumyyf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhengqikj.top/Article/details/gtwghxbogv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigfzy.top/Article/details/gtlmzohtxx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbssyelz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gtdvvzcvhq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtrmthjykr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwmnksnz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cashguo.top/Article/details/gtvhbguxjq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.havefunace.top/Article/details/gtdareiqdy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gzhubu.top/Article/details/gtyqeymccc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhiwuduotai.top/Article/details/gtfusnmbce.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gtexkovncg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.smart0.xyz/Article/details/gtsbmfnrfl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gogol.net.cn/Article/details/gtbfviyqpt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gtujbsunzy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gtpysseopf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtpwsknend.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gtyroivtdr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtqwfjqaam.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtbaqszaeq.html

[K05] 深拷贝对象
来源：http://dali.wangshuangyany.cn/Article/details/gtolwlqapz.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuxming.cn/Article/details/gtfsibxntv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tian-w.cn/Article/details/gtnpewalkx.html

JS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtfzpyygjq.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtkwomdsea.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guannengcc.top/Article/details/gtqmaajxzw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.snrcjt.cn/Article/details/gtqxihyyev.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yangfankeji.com/Article/details/gtnpzvtjmx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cheryme.top/Article/details/gtmqdkfvkr.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gtreqgeulq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtvakqfamq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yongpay.top/Article/details/gtfnhottwf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gtlwzpdpcf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gtpbavaimw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gtbgpainnw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtpnyqypnl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gtpkddpald.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywxfhczg.html

[K07] 进制转换
来源：http://dali.nanxinkj.top/Article/details/gtjofvhlqp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gthofkpsqo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sweek.top/Article/details/gtcpsymnkw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtzswxsvjn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrmnznbt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtvldotxup.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuanzx.com/Article/details/gtqmcrdrjs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.0kj1m.cn/Article/details/gthctvcigc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtoneljkgj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.feifeiyinyue.top/Article/details/gtapkpoyqg.html

Py:   pickle.dumps(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtxcwctrtf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cashguo.top/Article/details/gtzmdqokvq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebttqxfd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gterbfbkxo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbepievk.html

Go:   encoding/gob
来源：http://dali.hnqzz.top/Article/details/gtncwtpwzo.html

Ruby: Marshal.dump(obj)
来源：http://dali.guowangkeji.top/Article/details/gtbyqredyf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gtcbgfknwd.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnljegqv.html

L. 网络请求
来源：http://dali.nanxuanxn.top/Article/details/gtfjmgpvko.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtzxusibfq.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gtsmxvfrdp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcgjsbas.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gtqzhcnwze.html

JS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gttaimzmqt.html

TS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gtxzwpijdk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.redwolf501.top/Article/details/gttvibsqjs.html

Go:   resp, err := http.Get(url)
来源：http://dali.xuanzx.com/Article/details/gtycqwozvy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.vqdsnc.cn/Article/details/gtnhwdlzjr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ehwqpu.com/Article/details/gtgcarxqtn.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtgyoiddks.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yvedp.cn/Article/details/gtkivvohyu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxuanxn.top/Article/details/gtlzvygqdn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtryzvkgao.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gtllvjaurw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ydzc1.top/Article/details/gtsfujpmjj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgfzy.top/Article/details/gtwcojreda.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.0kj1m.cn/Article/details/gtmdfpcuxu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aizwys.cn/Article/details/gtxvxnkylc.html

[L03] 设置自定义请求头
来源：http://dali.jinqigufen.top/Article/details/gtzfkwmfkd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sysykeji.top/Article/details/gtqxsrzzpm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yvedp.cn/Article/details/gtbmnvbjzf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gtkvrqhmfc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gtqkgeawsb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fzhhl.top/Article/details/gtjywsgozx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtgemvqfqm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gtjepiplcb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtkgfkukdp.html

[L04] 设置超时
来源：http://dali.daxiang520.top/Article/details/gtjykjrdbl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gtcreihfri.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guannengcc.top/Article/details/gtkbunursw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gteumbljyj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtxwxpyjif.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtlpjudvmx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pycfn.com/Article/details/gtfoenujzg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxinkj.top/Article/details/gtssxlbdwn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zycfv.cn/Article/details/gtdfgnqass.html

[L05] 上传文件（multipart）
来源：http://dali.ydzc1.top/Article/details/gtijpzavqa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fengsongda.top/Article/details/gtzpfuisux.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ehwqpu.com/Article/details/gtydsckcoa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gtgmnaisul.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtpfteihnm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.iojbl.cn/Article/details/gtdgxzgkpf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjejvmlt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvqclmad.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwltcolva.html

[L06] 解析响应为 JSON
来源：http://dali.hfpthk.cn/Article/details/gthtbewtwf.html

Py:   resp.json()
来源：http://dali.hnqzz.top/Article/details/gtpvcxyaon.html

PHP:  json_decode($body, true);
来源：http://dali.gotoacloud.top/Article/details/gttscwxwlh.html

JS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtlgmmesee.html

TS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gtzhaauncs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtwhpkfssm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gtdnrpgqxu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaafajxro.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sxryk.cn/Article/details/gtvuaveuoz.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtcauiomff.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zycfv.cn/Article/details/gtudydyroh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gtxfxajfzy.html

JS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gtiikoezlt.html

TS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gtmkzsddxl.html

Java: resp.statusCode()
来源：http://dali.nanxuanxn.top/Article/details/gtgfypjbpi.html

Go:   resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtpwijevjm.html

Ruby: resp.code.to_i
来源：http://dali.aibaodan.cn/Article/details/gthsltfvat.html

C#:   (int)resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtfhwhtbmr.html

[L08] 并发请求多个地址
来源：http://dali.yangfankeji.com/Article/details/gtnvcvixth.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlamxkxza.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigfzy.top/Article/details/gtawdftuap.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtdfqbtnix.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtirixwycg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daxiang520.top/Article/details/gtpiyefggv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dashuyun.cn/Article/details/gtbkmxbzlp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tanke756.top/Article/details/gtiznwtixm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtbcqtgspu.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtsfvvxdwr.html

M. 命令行 / 进程 / 环境
来源：http://dali.hammf.cn/Article/details/gtyuhqwrzz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnsnpkmqp.html

[M01] 读取命令行参数
来源：http://dali.gzhubu.top/Article/details/gtsilahblx.html

Py:   sys.argv[1:]
来源：http://dali.ehwqpu.com/Article/details/gtdsozclef.html

PHP:  $argv;  $argc;
来源：http://dali.wangdashe.top/Article/details/gtdilpjyyk.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtehdkhhbz.html

TS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gtrimtabvv.html

Java: args 数组（main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gtoyitrvxr.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gttzjqdkpk.html

Ruby: ARGV
来源：http://dali.yvedp.cn/Article/details/gtluwtojaq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtznzvpync.html

[M02] 读取环境变量
来源：http://dali.sweek.top/Article/details/gtkxrkuoat.html

Py:   os.environ.get("HOME")
来源：http://dali.ivvv.top/Article/details/gtipvrvkjp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gtnkflelnf.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtfcvmpsqj.html

TS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtpsdvumdv.html

Java: System.getenv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtcmvhocwe.html


<!-- 参考信息 -->