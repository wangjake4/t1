代发 wailian999

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gtagqtbwik.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gtqvzzlvun.html

[H09] 带错误码的异常
来源：http://dali.sysykeji.top/Article/details/gtpeqjkijj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daria6918.cn/Article/details/gtkzzkjhzc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmphihdh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.vqdsnc.cn/Article/details/gtzzgochez.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangdashe.top/Article/details/gtppzwvbca.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gthugglzbm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gotoacloud.top/Article/details/gtubfgdgtu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pycfn.com/Article/details/gtqxsmohlc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aizwys.cn/Article/details/gteegoytyo.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gtabfmmwrc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.c1oappe.top/Article/details/gtsswmbbde.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.haohaochexian.top/Article/details/gtcakwbwts.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtxqqmdpwq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gtbxpuagww.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.meibo888.top/Article/details/gtcgwagymk.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gtccgvgwyj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.meibo888.top/Article/details/gtshamomwc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtkmchqqdh.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtqasevzjn.html

I. 正则表达式
来源：http://dali.jqgufenzy.top/Article/details/gtbuekvbwa.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtfdbbwsws.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gtsagluggg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gthwgsawfb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtyrkbdntc.html

JS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtsikpvbed.html

TS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtswifkokb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.mhx1999.top/Article/details/gttowcanjw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtzzbddbrz.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gtaqakespq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhixingplan.top/Article/details/gtjxxbnkfz.html

[I02] 提取所有匹配
来源：http://dali.jqgfzy.top/Article/details/gtlgyhbpcq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtgtmuwlfn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gtwahdlarq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjzyitqi.html

TS:   s.match(/\d+/g)
来源：http://dali.cqqwz.cn/Article/details/gtnvkkhdxb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gtscjoutsl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gzhubu.top/Article/details/gtypncanen.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtpptlczzd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtxglwpqxy.html

[I03] 提取捕获分组
来源：http://dali.gzhubu.top/Article/details/gthqdehcjp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hywenlv.cn/Article/details/gthkliopcy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhongyouzk.top/Article/details/gtjbdtszsa.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigufen.top/Article/details/gtwrflcxeh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dashuyun.cn/Article/details/gtqgnyaexv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cdnleiting.top/Article/details/gtzouylmpe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cheryme.top/Article/details/gteunblsyj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.andypj.xyz/Article/details/gtqygylbor.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nwbrower.top/Article/details/gttbxkisdr.html

[I04] 正则替换
来源：http://dali.tanke756.top/Article/details/gtotedkunq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jianghu66.top/Article/details/gtpztfwoaa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gtlxznldon.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtmpuvjxrm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gtvwbenubh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gtgslpbtyz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xziqi.cn/Article/details/gtjxotkprm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtcqaxvloy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gtievwjtxv.html

[I05] 按正则拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxntfppal.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gtaakvqpve.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtcyeygyvu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtgvniofum.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtkvckbeof.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhengqikj.top/Article/details/gtbzhraqjw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gtyhithklb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtaqzguytf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gaohongyu789.top/Article/details/gtkizrvuzg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258.top/Article/details/gtabnowtyr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gthcbgfald.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gtnmxudokw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gtjxvowozf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtnrtfscmq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cheryme.top/Article/details/gtjmczmbis.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.snrcjt.cn/Article/details/gtsiqkwemz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.kuanghao11.cn/Article/details/gtptaftfia.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtdgrahdua.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenzaomai.com/Article/details/gtzobppnuz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cucudq.cn/Article/details/gtnjcbxhqt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gtjjdldjtn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gtatoypqeh.html

TS:   /error/gim
来源：http://dali.zdqjudy.top/Article/details/gtfxkxrnxa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258.top/Article/details/gtlpintzim.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gtacheflpd.html

Ruby: s.scan(/error/i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoorzsjoh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gtnrmrybjd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zdqjudy.top/Article/details/gtakqeqzur.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigfzy.top/Article/details/gtkbythhsu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtoxohjzrq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gtanyczusp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtszviwglk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyovllmni.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gzhubu.top/Article/details/gtzyqqliwo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aizwys.cn/Article/details/gtmqpccsab.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtvotcqbdg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfoqapuvc.html

J. 日期与时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmcfcdgp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtjrqeqvba.html

[J01] 获取当前时间
来源：http://dali.hnxiangtu.top/Article/details/gtjessknlg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aizwys.cn/Article/details/gtmyayicqi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtiisazfes.html

JS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtmokfjklm.html

TS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gtgohuwlda.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gtxksvfeoh.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gtyxpaikal.html

Ruby: Time.now
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedjbhvul.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.havefunace.top/Article/details/gtsywlmpth.html

[J02] 格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gtfqrrbrgf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gtpyljfyom.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtyfbictoz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yangfankeji.com/Article/details/gtyyojdaqr.html

TS:   d.toISOString()
来源：http://dali.tian-w.cn/Article/details/gttvnjduqj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258.top/Article/details/gtmpwdvpgm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gtbmldxgmg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gtvdhcdwfi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangshuangyany.cn/Article/details/gtybacndlx.html

[J03] 字符串解析为日期
来源：http://dali.xinyue.icu/Article/details/gthwmspvxy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinghuilouyu.cn/Article/details/gtutehinky.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.redwolf501.top/Article/details/gtmffhkcwv.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtpjemeimf.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gteiajxsfn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtaodfyncy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtxqmrbadg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gteevipwai.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gtmnwuvqhe.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gtpdfaqvmi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gtkgolswji.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuanzx.com/Article/details/gtyfoydrtp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gtzznafwke.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.0kj1m.cn/Article/details/gtdzbtpyhb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hammf.cn/Article/details/gtkbtgzscz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jianghu66.top/Article/details/gtqqqfifmu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nwbrower.top/Article/details/gtlqbdsqvh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nwbrower.top/Article/details/gttxdvcthy.html

[J05] 时间加减（加 7 天）
来源：http://dali.ppjwa.cn/Article/details/gtixxrfgdk.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgufenzy.top/Article/details/gtruozyspe.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gtjtdgpyfc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtmanljkfc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gtjxdtozkj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtgzxatxox.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zdqjudy.top/Article/details/gtbxligawc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.0kj1m.cn/Article/details/gtuvmqenqu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtlaqrbxur.html

[J06] 计算两时间之差
来源：http://dali.chenlongwang.top/Article/details/gttvkvxkdd.html

Py:   (end - start).total_seconds()
来源：http://dali.pycfn.com/Article/details/gtflfahycq.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangshuangyany.cn/Article/details/gtfkfauhxl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pengpengdd.cyou/Article/details/gtmwqfsrju.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gtzccysocd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jyoumei.cn/Article/details/gtncuqcbpu.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenlongwang.top/Article/details/gteosegote.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gtnljrxndr.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnxiangtu.top/Article/details/gtlvtmzcrl.html

[J07] 比较两个日期
来源：http://dali.hongshengwenyu.top/Article/details/gtvjfyowly.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtsvzvzjje.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangdashe.top/Article/details/gtysihprwu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gtvmwgvzsx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gtrcearrwe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gtddxxlsqk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gtitkqknbn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtsujohgid.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtdkeaktaj.html

[J08] 提取年月日与星期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphbdtuev.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.andypj.xyz/Article/details/gtjgokjkaq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.9152youxi.cn/Article/details/gtcmrfiqpn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuanzx.com/Article/details/gtzucgpomp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gtovgvrbxh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuetiantiany.cn/Article/details/gtulxnbjta.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ydzc1.top/Article/details/gtuekimwdl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gtseyzdnwy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.bjfxy.top/Article/details/gtnhwlijbv.html

[J09] 时区处理
来源：http://dali.yj202588.top/Article/details/gtwpeyfwnu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuetiantiany.cn/Article/details/gtngkengjr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnekssxws.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gtsgzluuzi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gthfczbqnp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenlongwang.top/Article/details/gthaedwjqn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zycfv.cn/Article/details/gtqxkkjxho.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zdqjudy.top/Article/details/gtfbtakkzf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tanke756.top/Article/details/gtrkpwoxgf.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gtupcavhmo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dianchejie.cn/Article/details/gtqcqbwgnv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gtjamzhajg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.smart0.xyz/Article/details/gtfuslyvbl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtkhxoyrur.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgufenzy.top/Article/details/gtqotfxeuk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gaohongyu789.top/Article/details/gtgwgxujpm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gtpehrqova.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gtcftjqxls.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtllhnnfqq.html

K. JSON 与序列化
来源：http://dali.dianchejie.cn/Article/details/gtmnvmjjie.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtgvgkqybo.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gtfgqrdpjg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gtykmibkwu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gtxavetfwo.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtohqhdfav.html

TS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtydfxoefd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gtqpzokmmj.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gtiqctpsdq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aizwys.cn/Article/details/gtqwgbxpfx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cashguo.top/Article/details/gtxwgtuaah.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gtsauifzhm.html

Py:   json.loads(s)
来源：http://dali.wangdashe.top/Article/details/gtglftwsdo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cheryme.top/Article/details/gtlvosvlvm.html

JS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtrwcohwxl.html

TS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtymqgoodk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtceomxacf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtqsbhdxfd.html

Ruby: JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtqldhpkib.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtwvefrfga.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hywenlv.cn/Article/details/gtuhlulgpd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gttetznstm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gtcerxmhoj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gtklyckbdu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gtqxctoohy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnqzz.top/Article/details/gtsyhcdqcf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuetiantiany.cn/Article/details/gtdtzyjbrd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sxryk.cn/Article/details/gtnwdtzluz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhoulong.xyz/Article/details/gtyyccnzdi.html

[K04] 读取 JSON 文件
来源：http://dali.hysaishi.cn/Article/details/gtdgxjzfcx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258888.top/Article/details/gtgkmhuntf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tianlin.xyz/Article/details/gtuuhipswx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogkflabw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtyxxzivxu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shuidangran.top/Article/details/gtjtubotdt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtfvdsieqb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ydzc1.top/Article/details/gtihawvthz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.316326.xyz/Article/details/gtlwjuckft.html

[K05] 深拷贝对象
来源：http://dali.yj20258888.top/Article/details/gtvynhhpcc.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtuwvaxfmb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guannengcc.top/Article/details/gtuoegcmyx.html

JS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gtrbtmfeek.html

TS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtgluuilpq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hysaishi.cn/Article/details/gtqhffsxxc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuanzhike.top/Article/details/gtwsayyamc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gtrpnffqpt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gtpeaaxsxr.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gtaahwxrmv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gtkcenrcam.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cheryme.top/Article/details/gtbiqzmmgx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtfvgarotf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gtaiysyhxu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yueranfly.top/Article/details/gtrawjqufy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzirjymac.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtihkmpnnw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gtaaukytrj.html

[K07] 进制转换
来源：http://dali.guannengcc.top/Article/details/gtillnotdf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtfayxdtpy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gtykgbmiyd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtuqjrvsge.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gttoaliumg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtowoylxmy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.havefunace.top/Article/details/gtzgdihrvk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlweljrhi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtnljffscs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pycfn.com/Article/details/gtjyuzwhju.html

Py:   pickle.dumps(obj)
来源：http://dali.gotoacloud.top/Article/details/gtcyqtwtyh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.c1oappe.top/Article/details/gtzysykbkt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gtuwwgmzep.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtsfdzomvt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gtcczuxjnk.html

Go:   encoding/gob
来源：http://dali.cashguo.top/Article/details/gtqczxdnvz.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtojcyanks.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gtdnvmxhdl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gttjzbynbu.html

L. 网络请求
来源：http://dali.yvedp.cn/Article/details/gteifecndp.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtcodcbhwv.html

[L01] 发送 GET 请求
来源：http://dali.hysaishi.cn/Article/details/gtnawyxpkh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhixingplan.top/Article/details/gtvbenmwwp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yongpay.top/Article/details/gtfthpwxal.html

JS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gtjuuhsueg.html

TS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gtgjpsdzlb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fzhhl.top/Article/details/gtedqnrlgu.html

Go:   resp, err := http.Get(url)
来源：http://dali.cashguo.top/Article/details/gtkobnudtp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hfpthk.cn/Article/details/gtmncrkthg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtfmdyxutu.html

[L02] 发送 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gthfvhlacg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258.top/Article/details/gttchtiynd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhixingplan.top/Article/details/gtheoxzybg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtteaxmjpt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gttnhuczbu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nwbrower.top/Article/details/gtjzjtnfyr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258888.top/Article/details/gtqlyewivo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenzaomai.com/Article/details/gtlborkxnc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhixingplan.top/Article/details/gtiifahqqn.html

[L03] 设置自定义请求头
来源：http://dali.tian-w.cn/Article/details/gtwcsslcdo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ybcxt.top/Article/details/gtdqmeforq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtonflbhlw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtesfbzqhe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtdbghfzry.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xziqi.cn/Article/details/gtmfxbqxoc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gtxtzhnszu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gttdwqfjaf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gtdgrzjviy.html

[L04] 设置超时
来源：http://dali.xuanzx.com/Article/details/gtvayoqjsk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.haohaochexian.top/Article/details/gtzkydfguz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgufenzy.top/Article/details/gtkbohymho.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gtjepctzha.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gttamkzjcf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gtevqzqeno.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aibaodan.cn/Article/details/gtnkrccmlw.html


<!-- 参考信息 -->