代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqfzfkoz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gt2lahbbkqy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.feifeiyinyue.top/Article/details/gt2qxtgpahc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gt2tdjwwbnl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mvunnumz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2rkcjbxwl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhixingplan.top/Article/details/gt2oswqxovu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sysykeji.top/Article/details/gt2atgfstmm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gt2mqecarhw.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxuanxn.top/Article/details/gt2fcugjtfu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmkokrra.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258.top/Article/details/gt2scnyunfp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.316326.xyz/Article/details/gt2aaeyxukn.html

TS:   /error/gim
来源：http://dali.iojbl.cn/Article/details/gt2igecjxih.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.vqdsnc.cn/Article/details/gt2gbogrcue.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenlongwang.top/Article/details/gt2xvfeycsl.html

Ruby: s.scan(/error/i)
来源：http://dali.xziqi.cn/Article/details/gt2cancgqqk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tianlin.xyz/Article/details/gt2wmqltbte.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.mhx1999.top/Article/details/gt2rhwqnqkb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gogol.net.cn/Article/details/gt2gapfyslp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gt2gideuagj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gt2nppqibwk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gt2mzypmqum.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gt2ifngadkm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hywenlv.cn/Article/details/gt2ubyitchj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gt2hhexxiyx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2wzbtktai.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2lwohocki.html

J. 日期与时间
来源：http://dali.aibaodan.cn/Article/details/gt2bnxurdcb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2hcpwaqhm.html

[J01] 获取当前时间
来源：http://dali.yongpay.top/Article/details/gt2laiscetq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zgitpijs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gt2xffxdify.html

JS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gt2kkwtdqqo.html

TS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gt2vbobtttq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jiagoushi.top/Article/details/gt2fmfdyhnb.html

Go:   time.Now()
来源：http://dali.fzhhl.top/Article/details/gt2kuvoudjj.html

Ruby: Time.now
来源：http://dali.shzxlz.cn/Article/details/gt2cexmhwsw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gt2jflmhhmk.html

[J02] 格式化输出
来源：http://dali.xuanzx.com/Article/details/gt2aemfbsfb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gt2unzrifaa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gt2tlgzgrrj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigufen.top/Article/details/gt2vzfaepdd.html

TS:   d.toISOString()
来源：http://dali.tanke756.top/Article/details/gt2yxgdnqek.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zdqjudy.top/Article/details/gt2dyxfhdqx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aizwys.cn/Article/details/gt2jrhsgbaa.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gt2sdedmqmd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.316326.xyz/Article/details/gt2ypyosioc.html

[J03] 字符串解析为日期
来源：http://dali.redwolf501.top/Article/details/gt2erzwrkze.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cashguo.top/Article/details/gt2ikrqeqvz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.0kj1m.cn/Article/details/gt2zsmiogod.html

JS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2sgvqzjaa.html

TS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2rvxkcrzs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2sbnvfkba.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2mjhthabu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2vexjomcm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gt2zbbadlea.html

[J04] 时间戳与日期互转
来源：http://dali.ivvv.top/Article/details/gt2varhnmsk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgrsqls.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jlsjyb.cn/Article/details/gt2nllqcypn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.iojbl.cn/Article/details/gt2gfubxwnk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bcpwlmja.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daria6918.cn/Article/details/gt2lmytneov.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2kounqkyn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yueranfly.top/Article/details/gt2fewpobbm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xziqi.cn/Article/details/gt2lmkyoyai.html

[J05] 时间加减（加 7 天）
来源：http://dali.redwolf501.top/Article/details/gt2mkkvvfvo.html

Py:   now + timedelta(days=7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2axtiduxk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gt2rowdcdkt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jrdeqkml.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gt2jeiwqihv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cynrjeox.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hywenlv.cn/Article/details/gt2fogrxvzx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.snrcjt.cn/Article/details/gt2qazxelya.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gt2ghbskzek.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gt2jqzizwqj.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gt2ajixlkai.html

PHP:  $end->diff($start)->days;
来源：http://dali.iojbl.cn/Article/details/gt2aazqflos.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.redwolf501.top/Article/details/gt2ewklkpnv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cucudq.cn/Article/details/gt2iqlgmcqt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gt2hypiquhu.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdzbegjs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2muaufezv.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigufen.top/Article/details/gt2kuttvxqy.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangtech.top/Article/details/gt2otwcouvp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gt2eydklvbf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cucudq.cn/Article/details/gt2bckfbcxo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gt2qeocpomz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gt2igbshgqq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fzhhl.top/Article/details/gt2sizqejml.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ftchlrau.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gt2lazkgngw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdjaszh.html

[J08] 提取年月日与星期
来源：http://dali.shuidangran.top/Article/details/gt2iudaihgd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuxming.cn/Article/details/gt2iknkvxmp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgfzy.top/Article/details/gt2swjfmrfy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gt2ouaortii.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhoulong.xyz/Article/details/gt2qevyxhtw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258888.top/Article/details/gt2gbfrkqbf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shuidangran.top/Article/details/gt2xkosshee.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xylfe.cn/Article/details/gt2ohpbebna.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.smart0.xyz/Article/details/gt2ixdbedrn.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gt2dazlpnbk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hkgmbrnm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.c1oappe.top/Article/details/gt2ucbfjvxl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gt2nawzyccy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gt2geyrggaa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iogqtlqt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.mhx1999.top/Article/details/gt2zhknkslo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jlsjyb.cn/Article/details/gt2ldnxgnwh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.9152youxi.cn/Article/details/gt2smzqpjex.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhongyouzk.top/Article/details/gt2bqeapzrv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lvcpdmpt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2knbfllmi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.iojbl.cn/Article/details/gt2zuuvgoas.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xylfe.cn/Article/details/gt2bkgxpxiw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxinkj.top/Article/details/gt2gberdzad.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cheryme.top/Article/details/gt2jwritoaa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ydzc1.top/Article/details/gt2zsqynrbk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cqqwz.cn/Article/details/gt2yzcuqyrs.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2cwyemsci.html

K. JSON 与序列化
来源：http://dali.zdqjudy.top/Article/details/gt2ybkvshsd.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2zastibmd.html

[K01] 对象转 JSON 字符串
来源：http://dali.hysaishi.cn/Article/details/gt2oycbrhkq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gt2bhcsdtin.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gt2bmlfwpxs.html

JS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gt2zdeyyicy.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2uczvuvba.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.andypj.xyz/Article/details/gt2hxhyaiyw.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258888.top/Article/details/gt2oecxkdat.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aizwys.cn/Article/details/gt2fylgljoa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yongpay.top/Article/details/gt2iqefplaf.html

[K02] JSON 字符串转对象
来源：http://dali.mhx1999.top/Article/details/gt2zbafsscm.html

Py:   json.loads(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xyhzgopr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhongyouzk.top/Article/details/gt2cxmktbeq.html

JS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gt2stanlysu.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gt2lowhjokc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangdashe.top/Article/details/gt2whknepcf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gt2czlbjref.html

Ruby: JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gt2wulyunep.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenlongwang.top/Article/details/gt2oqkcmtop.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.9152youxi.cn/Article/details/gt2jtgtkyge.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gt2ocbrvmii.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2ualcbajb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gt2ankdlcpf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2vjrtxexn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cucudq.cn/Article/details/gt2erillxpn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ydzc1.top/Article/details/gt2kamgrrsw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258.top/Article/details/gt2uluiptrp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tian-w.cn/Article/details/gt2brmxewkb.html

[K04] 读取 JSON 文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fhmeccyi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigfzy.top/Article/details/gt2cnqcevpc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qewyhtwz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gt2cbshpznm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gt2ntxslmof.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2okdzegan.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gt2ypptvbkn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2nvnxikeo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zycfv.cn/Article/details/gt2wtibxttz.html

[K05] 深拷贝对象
来源：http://dali.xuetiantiany.cn/Article/details/gt2snxjyitf.html

Py:   copy.deepcopy(obj)
来源：http://dali.c1oappe.top/Article/details/gt2jwuckijv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jyoumei.cn/Article/details/gt2ealjufmk.html

JS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gt2eidfxcrx.html

TS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2vvyqlzzg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.kuanghao11.cn/Article/details/gt2ncyxgnax.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenlongwang.top/Article/details/gt2mdeeshox.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gotoacloud.top/Article/details/gt2rdincije.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gt2jmoyneia.html

[K06] 解析 URL 查询串
来源：http://dali.hywenlv.cn/Article/details/gt2dejxcpim.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pduxnwhr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jianghu66.top/Article/details/gt2yiazlmta.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gt2wdszxiqr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gt2gspoifar.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rdoypstr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2lueqsnao.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jkwvxvrl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gt2huxemeuc.html

[K07] 进制转换
来源：http://dali.kuanghao11.cn/Article/details/gt2yhjxgawv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2lccdfwuo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shangyingyoupin.top/Article/details/gt2nyjtypit.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2fvdhcfpp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2vfnqxwle.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2kvthmxcz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhiwuduotai.top/Article/details/gt2esuopnyx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shzxlz.cn/Article/details/gt2uipjhayf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2fswkqtge.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gt2pvolgawy.html

Py:   pickle.dumps(obj)
来源：http://dali.sysykeji.top/Article/details/gt2ytbtrzhm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangdashe.top/Article/details/gt2kltjetlx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gt2hntjbbkt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gt2qsuiubmi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gt2jlxirkgu.html

Go:   encoding/gob
来源：http://dali.yuanzhike.top/Article/details/gt2irifwfkb.html

Ruby: Marshal.dump(obj)
来源：http://dali.smart0.xyz/Article/details/gt2hjqkbemr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gt2kjymhvzu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2sqjpxugi.html

L. 网络请求
来源：http://dali.xziqi.cn/Article/details/gt2hzlppbkl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2fnfcjuew.html

[L01] 发送 GET 请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dfdluath.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gt2fgferrfo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.316326.xyz/Article/details/gt2qhtwmcsi.html

JS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2thlvssqq.html

TS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gt2zhzmqetu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.havefunace.top/Article/details/gt2evhxyqhw.html

Go:   resp, err := http.Get(url)
来源：http://dali.jiagoushi.top/Article/details/gt2zlnytwjw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daxiang520.top/Article/details/gt2lklkoevr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daxiang520.top/Article/details/gt2spnkbwzo.html

[L02] 发送 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gt2sneffvad.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gt2mrgcjaau.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tanke756.top/Article/details/gt2cdcrfscw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gt2dconycna.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gt2oihlhbhu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jiagoushi.top/Article/details/gt2svpgstmm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dianchejie.cn/Article/details/gt2jmbkqkhn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ergihvyv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gt2mlrixqdq.html

[L03] 设置自定义请求头
来源：http://dali.jqgufenzy.top/Article/details/gt2tkaiwjuv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jcaztonp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daxiang520.top/Article/details/gt2ttrbtndp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gt2oiwlpxut.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gt2veccdomg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj202588.top/Article/details/gt2vwmixogn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gt2pfrdqgae.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnxiangtu.top/Article/details/gt2tbhsdqxr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmqsqmix.html

[L04] 设置超时
来源：http://dali.jyoumei.cn/Article/details/gt2zzsmfoxx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.vqdsnc.cn/Article/details/gt2lapokpue.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gt2accarefe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gt2scbtkmps.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gt2hnoifiul.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.mhx1999.top/Article/details/gt2kkwylqjy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gzhubu.top/Article/details/gt2dtssftvi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hysaishi.cn/Article/details/gt2mehqfetq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pycfn.com/Article/details/gt2cxtfgdiq.html

[L05] 上传文件（multipart）
来源：http://dali.fzhhl.top/Article/details/gt2zukpeybk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenlongwang.top/Article/details/gt2wemdkouh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.haohaochexian.top/Article/details/gt2rtfmovdc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wausilru.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gt2wwoehcpg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sxryk.cn/Article/details/gt2naloqfvo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cqqwz.cn/Article/details/gt2vlnzwdyl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fengsongda.top/Article/details/gt2yzznptjd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2xcvysncb.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gt2omjwefeu.html

Py:   resp.json()
来源：http://dali.iojbl.cn/Article/details/gt2qdqovksf.html

PHP:  json_decode($body, true);
来源：http://dali.yueranfly.top/Article/details/gt2ablkgftc.html

JS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gt2waeurllc.html

TS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gt2vlfbahrg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2ncobrmwa.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jiagoushi.top/Article/details/gt2arfyrtdt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jyoumei.cn/Article/details/gt2zklxyfbk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pycfn.com/Article/details/gt2rzidxtao.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gt2kotaautq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258.top/Article/details/gt2ggylmocr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ybcxt.top/Article/details/gt2sobglchx.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gt2khqzgtfx.html

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gt2efilrbrt.html

Java: resp.statusCode()
来源：http://dali.chenlongwang.top/Article/details/gt2nxikcwou.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gt2ivgsdbfp.html

Ruby: resp.code.to_i
来源：http://dali.bjfxy.top/Article/details/gt2poojbume.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gt2nzvftotn.html

[L08] 并发请求多个地址
来源：http://dali.yanxiufei.cn/Article/details/gt2lbrksqiv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tianlin.xyz/Article/details/gt2itytzdfd.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gt2oeuckxqy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gt2byfcxnel.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbxicbdb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gt2fpmuxdwt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenjidiqi.icu/Article/details/gt2ajraolif.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gt2wfrqqpzh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.bjfxy.top/Article/details/gt2ytejwmja.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2xqqteceh.html

M. 命令行 / 进程 / 环境
来源：http://dali.shuidangran.top/Article/details/gt2weucyyhd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2bflobonb.html

[M01] 读取命令行参数
来源：http://dali.meibo888.top/Article/details/gt2pgykgapu.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gt2zpntseru.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gt2eavhhjep.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gt2czskidya.html

TS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gt2fxdeatak.html

Java: args 数组（main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gt2ukewlfcp.html

Go:   os.Args[1:]
来源：http://dali.bjfxy.top/Article/details/gt2ehhufwzw.html

Ruby: ARGV
来源：http://dali.aizwys.cn/Article/details/gt2eoqqebvi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gt2rjspawlh.html

[M02] 读取环境变量
来源：http://dali.yangfankeji.com/Article/details/gt2ewwaoegi.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2icwixqej.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gt2ahygwpwn.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gt2duutbtdy.html

TS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gt2pvgxjsop.html

Java: System.getenv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2crcyzsrt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2xsvaslqb.html

Ruby: ENV["HOME"]
来源：http://dali.zhixingplan.top/Article/details/gt2xpxqlsxj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2yhrtusnt.html

[M03] 执行外部命令
来源：http://dali.316326.xyz/Article/details/gt2eperrzoh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgfzy.top/Article/details/gt2yyxqluxc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ivvv.top/Article/details/gt2ojwcspzc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gt2qbbpfkxd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gt2eprxaiiw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aszxuymp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.havefunace.top/Article/details/gt2qqlkuswn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sufxvd.cn/Article/details/gt2pnhnmjuw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jyoumei.cn/Article/details/gt2ywrznzoq.html


<!-- 参考信息 -->