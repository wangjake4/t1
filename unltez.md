代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigufen.top/Article/details/gt2csoiqytx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxarysa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gt2vnvcsbte.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.snrcjt.cn/Article/details/gt2bnacdyaq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnqzz.top/Article/details/gt2oavmgpgf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2fhsojbor.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xedskzqz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gt2vxwayryr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gt2tnoglglu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2pibskzkq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jlsjyb.cn/Article/details/gt2nazzfszx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgfzy.top/Article/details/gt2jisqiber.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gt2aectmnmf.html

[I07] 忽略大小写与多行模式
来源：http://dali.yueranfly.top/Article/details/gt2islrtuwk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nwbrower.top/Article/details/gt2mdjeetdh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ciqsptpn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.vqdsnc.cn/Article/details/gt2dwhqkhiz.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gt2dkgutpsv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gt2bxezlesp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shangyingyoupin.top/Article/details/gt2thluxyxs.html

Ruby: s.scan(/error/i)
来源：http://dali.yueranfly.top/Article/details/gt2ytihwxjr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qtiwwglo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbdstmvl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenjidiqi.icu/Article/details/gt2ckrwgjle.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gt2faotrmun.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gt2lpymytig.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gt2geqxzqfw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gt2zsylmhtu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gt2gfhyexcn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.iojbl.cn/Article/details/gt2wrtuvuop.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gt2dtijldqd.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nnmmcgzu.html

J. 日期与时间
来源：http://dali.yongpay.top/Article/details/gt2jydydwft.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2jfczywkh.html

[J01] 获取当前时间
来源：http://dali.jinqigufen.top/Article/details/gt2pchhdkam.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qiswdosx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gt2aqpkcmqz.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gt2npuukkim.html

TS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gt2jwnfcrpz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2alobnwoq.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zxmhewjk.html

Ruby: Time.now
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ptnfyong.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gogol.net.cn/Article/details/gt2ecfvcgks.html

[J02] 格式化输出
来源：http://dali.hywenlv.cn/Article/details/gt2rkwtaknj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gt2qduwejre.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gt2nywhafkj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gt2btwthsmr.html

TS:   d.toISOString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2xlgmmwrx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2echnxiej.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.bjfxy.top/Article/details/gt2tsaxczrs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gt2xffnbcud.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hammf.cn/Article/details/gt2vbqvppnl.html

[J03] 字符串解析为日期
来源：http://dali.feifeiyinyue.top/Article/details/gt2ozrzjhza.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hammf.cn/Article/details/gt2rjkrvgev.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ntkctnel.html

JS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2zjfagyau.html

TS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2dhafrhli.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2kwpjasug.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2nvauydes.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2etlrpftg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gt2jrcpzrbj.html

[J04] 时间戳与日期互转
来源：http://dali.shzxlz.cn/Article/details/gt2yxbwvynz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2xdanqzvc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pycfn.com/Article/details/gt2exvaykfs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jiagoushi.top/Article/details/gt2lqtdwotv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gt2xtyuwbze.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vdjihbsx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2cavcysuy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gt2lmlkgoba.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gt2jarppbrj.html

[J05] 时间加减（加 7 天）
来源：http://dali.meibo888.top/Article/details/gt2npghqhge.html

Py:   now + timedelta(days=7)
来源：http://dali.smart0.xyz/Article/details/gt2wtvnzbfg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuanzx.com/Article/details/gt2amotyghk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gt2wqglzyvf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gt2ojcnhmnb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gt2jpazfpfz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2vqvdltlv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sufxvd.cn/Article/details/gt2tqxpzkqm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lvpjutph.html

[J06] 计算两时间之差
来源：http://dali.ehwqpu.com/Article/details/gt2qpjlxyei.html

Py:   (end - start).total_seconds()
来源：http://dali.hammf.cn/Article/details/gt2lqwaychl.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gt2ddrpyykn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2drnnpjhg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gt2gtxeaxya.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ybcxt.top/Article/details/gt2amhzmyug.html

Go:   end.Sub(start).Hours()
来源：http://dali.haohaochexian.top/Article/details/gt2xomqzeqd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hysaishi.cn/Article/details/gt2qytnbpxk.html

C#:   (end - start).TotalSeconds
来源：http://dali.guowangkeji.top/Article/details/gt2dmhcqulj.html

[J07] 比较两个日期
来源：http://dali.svipenyu.cn/Article/details/gt2wkosodbd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gt2mbhqhmlb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gt2gwvirsob.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gt2rvstqxdi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gt2dshpfife.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yajuzpmy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigufen.top/Article/details/gt2lovwwmlu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gt2knqjgkgk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gt2audhdlkt.html

[J08] 提取年月日与星期
来源：http://dali.aibaodan.cn/Article/details/gt2ktdsybsp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ivvv.top/Article/details/gt2dkrqaors.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.smart0.xyz/Article/details/gt2upynmddt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shuidangran.top/Article/details/gt2htxjhtzy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gt2tcauobbh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guannengcc.top/Article/details/gt2icpizhfx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gt2ngxmjwwz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigufen.top/Article/details/gt2oogbdrno.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxinkj.top/Article/details/gt2dpiveqhj.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gt2eyrglclj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gt2daegzqcb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gt2psrzquhw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gt2athgjigy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gt2uuazwwbc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.smart0.xyz/Article/details/gt2ekherlnu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangdashe.top/Article/details/gt2wgrfdsum.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gzhubu.top/Article/details/gt2bddgfvbe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuanzx.com/Article/details/gt2ckwljhng.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenzaomai.com/Article/details/gt2lwculdft.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.vqdsnc.cn/Article/details/gt2pbkvqxcs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gt2cnmzzyfu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2nojgfrug.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gt2byampxem.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dywgjvlx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gt2ttgfibfe.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daxiang520.top/Article/details/gt2pnyffxjw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qsysyzhf.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2shnlguvj.html

K. JSON 与序列化
来源：http://dali.xziqi.cn/Article/details/gt2syrvjaib.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ghssqxaa.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2cyqvuljp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zupjrhpj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gt2uqyhulvr.html

JS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2uhwhxchw.html

TS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2vjafjiml.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vxcbaivo.html

Go:   json.Marshal(obj)
来源：http://dali.zycfv.cn/Article/details/gt2lywplfmo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yangfankeji.com/Article/details/gt2gkbnpadh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.andypj.xyz/Article/details/gt2edorjvgd.html

[K02] JSON 字符串转对象
来源：http://dali.kuanghao11.cn/Article/details/gt2vppkldiv.html

Py:   json.loads(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vrpdgzrk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.havefunace.top/Article/details/gt2emmsqoyz.html

JS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gt2dgtyvxsv.html

TS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2kzdxfbjk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pycfn.com/Article/details/gt2aseditkx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gt2rlpytfzi.html

Ruby: JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2gktugmgj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2bmammlfj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.iojbl.cn/Article/details/gt2oyoepfqy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uaupgovb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gt2lshcvsap.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gt2wkvgwebi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bctnfjyj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rvreqdhh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yongpay.top/Article/details/gt2uiqpxtlm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.mhx1999.top/Article/details/gt2rlzilbcw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sweek.top/Article/details/gt2saapihbi.html

[K04] 读取 JSON 文件
来源：http://dali.shzxlz.cn/Article/details/gt2gtzlwdjs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jianghu66.top/Article/details/gt2ohugwudj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.c1oappe.top/Article/details/gt2plmcflui.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gt2oqvrjqbh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2pbjouoxw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tanke756.top/Article/details/gt2lpraqdea.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gt2phzodoaf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cucudq.cn/Article/details/gt2awhdmjfi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2lqidfsoo.html

[K05] 深拷贝对象
来源：http://dali.jinqigufen.top/Article/details/gt2kxainqlm.html

Py:   copy.deepcopy(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2ucmzwyrx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ydzc1.top/Article/details/gt2pinxpdmh.html

JS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gt2hkxqaaoi.html

TS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2fblpaval.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gtqsdsbr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgufenzy.top/Article/details/gt2xltgdmmj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnxiangtu.top/Article/details/gt2beihnfjx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gt2ovtfkwfy.html

[K06] 解析 URL 查询串
来源：http://dali.chenlongwang.top/Article/details/gt2qcxbifbx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gt2aykdqhci.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gt2bgqzniji.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lefmaibk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ehtnfqbl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxinkj.top/Article/details/gt2ggnxepaj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2sitttjkf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gt2hchdrzon.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gt2tyhicuhx.html

[K07] 进制转换
来源：http://dali.fzhhl.top/Article/details/gt2dbzjweyf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2cqxqgnhk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.birdmap.top/Article/details/gt2xtscyhdg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2lkgunwae.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2kygdhwky.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nivhmsux.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.mhx1999.top/Article/details/gt2monxkgzs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigfzy.top/Article/details/gt2hgocygyx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2ioxqmksw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhongyouzk.top/Article/details/gt2anhhnacf.html

Py:   pickle.dumps(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2jkcwslbz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cashguo.top/Article/details/gt2ahlfulic.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xbnokujv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gt2ngqgeeln.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2okycbmhl.html

Go:   encoding/gob
来源：http://dali.jianghu66.top/Article/details/gt2diwzsmko.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2rdvdqius.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2avmhrgif.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ntyeykjr.html

L. 网络请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rokyfzbo.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2svizflnt.html

[L01] 发送 GET 请求
来源：http://dali.feifeiyinyue.top/Article/details/gt2fljfrlqi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxinkj.top/Article/details/gt2scxlhjly.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gzhubu.top/Article/details/gt2uncoysbj.html

JS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gt2tizpuzko.html

TS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2yivhgbxb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.havefunace.top/Article/details/gt2ikndqvlv.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2yxhrotgj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.smart0.xyz/Article/details/gt2cjwcxdwk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ydzc1.top/Article/details/gt2eapvgebc.html

[L02] 发送 POST JSON
来源：http://dali.xylfe.cn/Article/details/gt2mfybyedf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gt2nnbipmzp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jianghu66.top/Article/details/gt2nrdazlcj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gt2vouposkf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gt2smiqusnf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gt2zehdpmnt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxuanxn.top/Article/details/gt2rqoazlgy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cdnleiting.top/Article/details/gt2xxffkloo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.snrcjt.cn/Article/details/gt2daenhtlf.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gt2ozjevehr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xylfe.cn/Article/details/gt2kglidsrx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ppjwa.cn/Article/details/gt2ecegibak.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gt2fuheelcn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ijccbuxi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgufenzy.top/Article/details/gt2fdajlpmo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gt2ncunfglf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xinyue.icu/Article/details/gt2wakieroh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdvdxrvv.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gt2gsfrikfw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shuidangran.top/Article/details/gt2izsxweui.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gt2jwupfkwp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gt2oikapwtq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gt2exddmgxo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qflzggao.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.kuanghao11.cn/Article/details/gt2kaivcvbe.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxuanxn.top/Article/details/gt2mixyvxnt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2guxgyuke.html

[L05] 上传文件（multipart）
来源：http://dali.havefunace.top/Article/details/gt2lsoehnnr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.0kj1m.cn/Article/details/gt2dbqnkkbo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ehwqpu.com/Article/details/gt2enqsedfr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gt2hmkahtfc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gt2zpqkkizr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xinyue.icu/Article/details/gt2nwncewkm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.bjfxy.top/Article/details/gt2oqubuenx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gt2xoszblbu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2kcnuuhbb.html

[L06] 解析响应为 JSON
来源：http://dali.jqgufenzy.top/Article/details/gt2jkxvqqud.html

Py:   resp.json()
来源：http://dali.dianchejie.cn/Article/details/gt2laasmvvg.html

PHP:  json_decode($body, true);
来源：http://dali.fengsongda.top/Article/details/gt2gyznyufb.html

JS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gt2dwsurxwx.html

TS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gt2szadxjih.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.redwolf501.top/Article/details/gt2atrqtzfw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenlongwang.top/Article/details/gt2lhbtifru.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gt2duhgmvfw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.svipenyu.cn/Article/details/gt2kjinjzwe.html

[L07] 处理 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gt2fmfwjzxq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuxming.cn/Article/details/gt2avkocswn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.andypj.xyz/Article/details/gt2fbnysnna.html

JS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gt2alvodgqs.html

TS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gt2favwvdpi.html

Java: resp.statusCode()
来源：http://dali.cashguo.top/Article/details/gt2lflnykhy.html

Go:   resp.StatusCode
来源：http://dali.gogol.net.cn/Article/details/gt2lwekomcz.html

Ruby: resp.code.to_i
来源：http://dali.jinqigufen.top/Article/details/gt2jkkyhgru.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gt2oiqylcjk.html

[L08] 并发请求多个地址
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tpcdzaji.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxuanxn.top/Article/details/gt2tcgbqdwb.html

PHP:  curl_multi_init() 系列
来源：http://dali.gogol.net.cn/Article/details/gt2plifllpy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2stnbwoad.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2odvdrqtt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gotoacloud.top/Article/details/gt2ywyuhrai.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.andypj.xyz/Article/details/gt2xcxzffgc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.andypj.xyz/Article/details/gt2kmzvcbwa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.vqdsnc.cn/Article/details/gt2jryfrylz.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2pgfwzqca.html

M. 命令行 / 进程 / 环境
来源：http://dali.aizwys.cn/Article/details/gt2umuwkpkg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2pyprddfe.html

[M01] 读取命令行参数
来源：http://dali.316326.xyz/Article/details/gt2uxaulbyq.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gt2rxzmffit.html

PHP:  $argv;  $argc;
来源：http://dali.dianchejie.cn/Article/details/gt2xyhqzgiy.html

JS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gt2tmpecgyb.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gt2pbxehcfv.html

Java: args 数组（main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gt2pfuowyul.html

Go:   os.Args[1:]
来源：http://dali.yj202588.top/Article/details/gt2hydcgefs.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gt2brhvpkgh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gt2uaggspnr.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gt2pmpyovpy.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2lxjknwht.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gt2nvcqzwdm.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gt2glozciuy.html

TS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gt2jknsfzja.html

Java: System.getenv("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2swypulpr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zycfv.cn/Article/details/gt2nleclmoo.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gt2eqerujjd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2banuhkwf.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gt2fogolfov.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sysykeji.top/Article/details/gt2vwbalnwb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgufenzy.top/Article/details/gt2lhpaoazl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zjdwctmy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gt2mgpxrejq.html


<!-- 参考信息 -->