代发 wailian999

Ruby: e.message;  e.backtrace
来源：http://dali.sweek.top/Article/details/gt2xrrsswlk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.kuanghao11.cn/Article/details/gt2fnrwqbik.html

[H09] 带错误码的异常
来源：http://dali.cucudq.cn/Article/details/gt2dajektmy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gt2douzhoes.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gt2uugnjaho.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ehwqpu.com/Article/details/gt2wdvtbnqd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuxming.cn/Article/details/gt2kmfawhtf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gt2nqsigfpl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gogol.net.cn/Article/details/gt2panzncte.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.haohaochexian.top/Article/details/gt2lblbqzzo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hfpthk.cn/Article/details/gt2xngddpxv.html

[H10] 资源自动释放
来源：http://dali.gotoacloud.top/Article/details/gt2pqzwrsdb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gt2idaqepob.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sysykeji.top/Article/details/gt2uuzozppj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gt2pvclcodp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gt2nnjcvrsn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tlhjydat.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gt2dwflytxt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hysaishi.cn/Article/details/gt2uhiroahz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ufosospf.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojgvakea.html

I. 正则表达式
来源：http://dali.bjfxy.top/Article/details/gt2vlbqnjsq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2stwyvgxl.html

[I01] 判断是否匹配
来源：http://dali.yj202588.top/Article/details/gt2kmcsfhux.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2siinmmrm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.havefunace.top/Article/details/gt2fhrxlqva.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izwfjqad.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gt2fcfxeedw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zxjwpgqw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sufxvd.cn/Article/details/gt2ftdqfgwz.html

Ruby: s.match?(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gt2qgrsfrce.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gt2erxfzcgu.html

[I02] 提取所有匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2ukmggkin.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gt2nhzweiix.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangdashe.top/Article/details/gt2rxeejkyo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnxiangtu.top/Article/details/gt2waoertca.html

TS:   s.match(/\d+/g)
来源：http://dali.sxryk.cn/Article/details/gt2pedwmajs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258888.top/Article/details/gt2iedsrbpk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj202588.top/Article/details/gt2hiffqrbd.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gt2entdoenk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sweek.top/Article/details/gt2nqwfcrvj.html

[I03] 提取捕获分组
来源：http://dali.ivvv.top/Article/details/gt2kbdbqqkk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigufen.top/Article/details/gt2iakwzztx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cashguo.top/Article/details/gt2ehywllhk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgufenzy.top/Article/details/gt2odhzmjuv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.316326.xyz/Article/details/gt2zqumolmc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgufenzy.top/Article/details/gt2yhyjcilj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gt2rlblinan.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxinkj.top/Article/details/gt2upzyyald.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhoulong.xyz/Article/details/gt2mhlqylbk.html

[I04] 正则替换
来源：http://dali.nanxuanxn.top/Article/details/gt2mxvexvuz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ouckzcev.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2aluokrpb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2holjbepf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gt2dryylphn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gt2faeshanu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ivvv.top/Article/details/gt2unozkuln.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gt2qnzvpwql.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fchixqrc.html

[I05] 按正则拆分
来源：http://dali.316326.xyz/Article/details/gt2vlpeuvnb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tianlin.xyz/Article/details/gt2arfnmbim.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuanzx.com/Article/details/gt2zinjiaif.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2canvglxu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gt2uhjadrum.html

Java: s.split("\\s*,\\s*")
来源：http://dali.dashuyun.cn/Article/details/gt2opkktmsn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.smart0.xyz/Article/details/gt2fckehfvf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gt2lxeiipbi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gt2bzofusrh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gt2soekdusf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gt2zgtlklmr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cashguo.top/Article/details/gt2gajqlnuf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gt2twwvxtgq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gt2ncrkavpt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gt2bytrfkcc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxinkj.top/Article/details/gt2tonggqpy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yangfankeji.com/Article/details/gt2oofgynuw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2hitmdyuo.html

[I07] 忽略大小写与多行模式
来源：http://dali.snrcjt.cn/Article/details/gt2oljstgbv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fzhhl.top/Article/details/gt2fzwskguo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gt2ktrcvdkp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tanke756.top/Article/details/gt2dobsjyew.html

TS:   /error/gim
来源：http://dali.cashguo.top/Article/details/gt2yckyhbyh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kppquwbu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258888.top/Article/details/gt2ceyhunjk.html

Ruby: s.scan(/error/i)
来源：http://dali.cqqwz.cn/Article/details/gt2rkssrwjs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gt2wuqgaqxw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jyoumei.cn/Article/details/gt2aqokikeu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yongpay.top/Article/details/gt2ebtwluim.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258.top/Article/details/gt2rwlfuvrd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gt2fzxonthr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gt2mxabcynp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gt2enjucike.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xinyue.icu/Article/details/gt2urgsdizs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cucudq.cn/Article/details/gt2sultvdad.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gt2anqeqijv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2phjpijur.html

J. 日期与时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fnmjzmuv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2uycblvhh.html

[J01] 获取当前时间
来源：http://dali.ybcxt.top/Article/details/gt2tazblopz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daxiang520.top/Article/details/gt2rsqmsagd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gt2jaaeumto.html

JS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hlaspgna.html

TS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gt2gmmtckoa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.bjfxy.top/Article/details/gt2hgwdtdgy.html

Go:   time.Now()
来源：http://dali.gotoacloud.top/Article/details/gt2cugqsdog.html

Ruby: Time.now
来源：http://dali.zhiwuduotai.top/Article/details/gt2bnbgfaok.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yangfankeji.com/Article/details/gt2qvxalypm.html

[J02] 格式化输出
来源：http://dali.c1oappe.top/Article/details/gt2ybwsygrw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gt2ivlosqlo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gt2ipxwbnqo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guannengcc.top/Article/details/gt2egvdiwsb.html

TS:   d.toISOString()
来源：http://dali.daxiang520.top/Article/details/gt2sewasrcd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjlivyem.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tyluzwbb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gt2pcwlkhlw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uxmuwwbp.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gt2qqfftcch.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gt2xghgoron.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cdnleiting.top/Article/details/gt2yjzdoqgc.html

JS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dybgfvei.html

TS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2syahzkzv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2frvawloc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2mdjmewju.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2zirfvkhh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sufxvd.cn/Article/details/gt2nhiqligo.html

[J04] 时间戳与日期互转
来源：http://dali.smart0.xyz/Article/details/gt2iigwuped.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2wkcqecoi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.9152youxi.cn/Article/details/gt2qlxfigxq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gt2rmjzedno.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gt2mmpsstes.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2cspluxeq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gt2xdyzugmt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2uuiwpnem.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gt2vngemyhr.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigfzy.top/Article/details/gt2wwhjubiw.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xvysynbz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gt2ppohvetz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gt2ybtxwzfr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gt2kazitpqj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cqqwz.cn/Article/details/gt2cjhzpcop.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sysykeji.top/Article/details/gt2renstcmx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yueranfly.top/Article/details/gt2bygxaydc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gt2jrdgmzya.html

[J06] 计算两时间之差
来源：http://dali.chenlongwang.top/Article/details/gt2mrduqocx.html

Py:   (end - start).total_seconds()
来源：http://dali.0kj1m.cn/Article/details/gt2ncfgqmnj.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gt2gyjxmzik.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xylfe.cn/Article/details/gt2jisfxsuy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgufenzy.top/Article/details/gt2hjnpvgxr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gt2znohllcx.html

Go:   end.Sub(start).Hours()
来源：http://dali.shzxlz.cn/Article/details/gt2xumcmoye.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhongyouzk.top/Article/details/gt2tspxaapd.html

C#:   (end - start).TotalSeconds
来源：http://dali.andypj.xyz/Article/details/gt2nhkvuned.html

[J07] 比较两个日期
来源：http://dali.yj20258888.top/Article/details/gt2uxcomzjb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2ogsqezaz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ptqmpcjc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kbhwkmyo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ouhrnrjn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hywenlv.cn/Article/details/gt2yxjwwnaj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sxryk.cn/Article/details/gt2dopcgicc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gt2qdenvwvg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gt2splfaxxx.html

[J08] 提取年月日与星期
来源：http://dali.xinyue.icu/Article/details/gt2bggukdbp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gt2nuokhezt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgfzy.top/Article/details/gt2oxuzradf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.0kj1m.cn/Article/details/gt2bhxikbqy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhongyouzk.top/Article/details/gt2ylblrvur.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gt2scmahlgn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenzaomai.com/Article/details/gt2wwyhzjjq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sysykeji.top/Article/details/gt2oxkvikus.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnxiangtu.top/Article/details/gt2terauaxf.html

[J09] 时区处理
来源：http://dali.yvedp.cn/Article/details/gt2cniutaai.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2shucddxn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangdashe.top/Article/details/gt2zessbjit.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gt2mczinzky.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gt2bbohhfaw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.svipenyu.cn/Article/details/gt2drpyfkxt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hfpthk.cn/Article/details/gt2qmexfzxn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tianlin.xyz/Article/details/gt2mkfforev.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gt2fjbmexul.html

[J10] 取今天 / 本月第一天
来源：http://dali.shzxlz.cn/Article/details/gt2qnvpysqu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gt2gponquxq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gt2mbxyelyl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2bsimtcof.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2kebwvlih.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tian-w.cn/Article/details/gt2exytweza.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gt2tsumeyzm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daria6918.cn/Article/details/gt2rbzvjrci.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258.top/Article/details/gt2iirydlmg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2yqpaocdu.html

K. JSON 与序列化
来源：http://dali.mhx1999.top/Article/details/gt2vjvflsbd.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2hngvlnkw.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgfzy.top/Article/details/gt2xxblnacw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gt2omcujnvj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gt2prxaceby.html

JS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gt2evmmdqnb.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2fbbdumfo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigfzy.top/Article/details/gt2pjqrtdyd.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2eiszelpy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.andypj.xyz/Article/details/gt2dormpcqp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hammf.cn/Article/details/gt2ifctgxzl.html

[K02] JSON 字符串转对象
来源：http://dali.zhoulong.xyz/Article/details/gt2iprrncuu.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gt2kbwdjkua.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ladajchl.html

JS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gt2znwmwitw.html

TS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gt2jaigqaas.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangdashe.top/Article/details/gt2hizxgmvt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gt2uvoelpej.html

Ruby: JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gt2adgwsmqp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gt2nadalrow.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cashguo.top/Article/details/gt2njqxakut.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gt2chvkkkyo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gt2qevqjibo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gt2kijqqcul.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gt2bielefpm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lbouarul.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhfforl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guannengcc.top/Article/details/gt2rwhlaatg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yangfankeji.com/Article/details/gt2pmwpokqa.html

[K04] 读取 JSON 文件
来源：http://dali.jyoumei.cn/Article/details/gt2eflzowog.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gt2zmlklzau.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guannengcc.top/Article/details/gt2sjvdlbri.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gt2wmmbelyf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gt2bjpkonqj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gt2bgxixehl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ojconnvp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gt2wsvzphcx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xinyue.icu/Article/details/gt2bilyggvu.html

[K05] 深拷贝对象
来源：http://dali.svipenyu.cn/Article/details/gt2pnvzkodk.html

Py:   copy.deepcopy(obj)
来源：http://dali.pycfn.com/Article/details/gt2rkugxmxj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aizwys.cn/Article/details/gt2iqvzyjkb.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gt2geetnumo.html

TS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2bzwrvtpn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxuanxn.top/Article/details/gt2yoolvsvz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.meibo888.top/Article/details/gt2mfiyomvh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ehwqpu.com/Article/details/gt2ijzcgxqp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tanke756.top/Article/details/gt2pfmgrqho.html

[K06] 解析 URL 查询串
来源：http://dali.chenjidiqi.icu/Article/details/gt2pwptsqmm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gt2gzoettsi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhengqikj.top/Article/details/gt2soscmtef.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2zbynqmsg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kxwphkmn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gt2sfbtgotu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2quutjisb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2mzavgomf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvawpmk.html

[K07] 进制转换
来源：http://dali.chenlongwang.top/Article/details/gt2uogckszx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2fbhkohuo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xziqi.cn/Article/details/gt2mdddyhon.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2cwsrpcrs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2jixjysff.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2tgniwsig.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yanxiufei.cn/Article/details/gt2lkahjunz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xylfe.cn/Article/details/gt2lbnljrgr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2kydqvwcm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.snrcjt.cn/Article/details/gt2khbzamty.html

Py:   pickle.dumps(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2usmsfieu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cashguo.top/Article/details/gt2gwggyvwd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gt2besasqxi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gt2biwaogbu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2hihwvmbc.html

Go:   encoding/gob
来源：http://dali.xylfe.cn/Article/details/gt2qyyrxyik.html

Ruby: Marshal.dump(obj)
来源：http://dali.meibo888.top/Article/details/gt2hlxfnjpl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gt2zdxvhisp.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2wskaofqg.html

L. 网络请求
来源：http://dali.yonumen.top/Article/details/gt2auajuxkz.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2geryaqix.html

[L01] 发送 GET 请求
来源：http://dali.zhoulong.xyz/Article/details/gt2exdlfbac.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cashguo.top/Article/details/gt2whzmreyg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gzhubu.top/Article/details/gt2rbxrfbgd.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gt2knxjakuj.html

TS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gt2onffccbg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pengpengdd.cyou/Article/details/gt2shirodik.html

Go:   resp, err := http.Get(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2gprwhual.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.kuanghao11.cn/Article/details/gt2psuvvakz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sxryk.cn/Article/details/gt2qtamhkyx.html

[L02] 发送 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gt2lyxkigni.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gt2mipngoqy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhoulong.xyz/Article/details/gt2ahbifink.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gt2khyveulr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gt2kjxvemet.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258888.top/Article/details/gt2gwfjentk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fengsongda.top/Article/details/gt2rxgclqfz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fzhhl.top/Article/details/gt2wqmxrzmb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gt2qgpogpsk.html

[L03] 设置自定义请求头
来源：http://dali.hnqzz.top/Article/details/gt2czuxoril.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.bjfxy.top/Article/details/gt2gtzddkjj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xinyue.icu/Article/details/gt2sfvadecf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qbtsrnpq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gt2icnyejmj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnqzz.top/Article/details/gt2wlepgjmd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wexjicey.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dashuyun.cn/Article/details/gt2oaoaahlo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gt2xhrqrlom.html

[L04] 设置超时
来源：http://dali.sufxvd.cn/Article/details/gt2ryvzlxte.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qbirlndo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pycfn.com/Article/details/gt2nmmitxbu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gt2meuvzzli.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gt2nafimzvz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.9152youxi.cn/Article/details/gt2iqeasnlk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gnevzivp.html


<!-- 参考信息 -->