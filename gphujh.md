代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.xylfe.cn/Article/details/gt2fbnvswgl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gt2idyuzzqf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gt2wujyirzi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gt2ykiqgetf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gt2qupyfzrg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gt2iypqtgtk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gt2fkmytsjy.html

C#:   obj?.A?.B ?? default
来源：http://dali.tianlin.xyz/Article/details/gt2okektwep.html

[H07] 断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2adxkktrt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.c1oappe.top/Article/details/gt2tnsmxeyb.html

PHP:  assert($x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zzsvnraj.html

JS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2yrdkwnpn.html

TS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2qvazmpzs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shzxlz.cn/Article/details/gt2xydacpmn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guannengcc.top/Article/details/gt2runspctt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangdashe.top/Article/details/gt2csfbzaut.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2wgwqlzjn.html

[H08] 获取错误信息与堆栈
来源：http://dali.hywenlv.cn/Article/details/gt2rrjmogcw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shzxlz.cn/Article/details/gt2ahewqanv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guowangkeji.top/Article/details/gt2hyulager.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gt2rsbyflag.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.quarkkingdee.top/Article/details/gt2rtkozyoq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gt2sbnmopfi.html

Go:   err.Error()
来源：http://dali.gzhubu.top/Article/details/gt2gxpousrl.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gt2nxhussko.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jyoumei.cn/Article/details/gt2qqhrjrjw.html

[H09] 带错误码的异常
来源：http://dali.yueranfly.top/Article/details/gt2gvoyaxnk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yongpay.top/Article/details/gt2fhjgnxbv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.mhx1999.top/Article/details/gt2vbskumhh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gt2xpnipctb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cashguo.top/Article/details/gt2nqqngozi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigufen.top/Article/details/gt2olhvkqma.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.birdmap.top/Article/details/gt2smlcflkw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.meibo888.top/Article/details/gt2aortindy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fzhhl.top/Article/details/gt2laohdhay.html

[H10] 资源自动释放
来源：http://dali.yangfankeji.com/Article/details/gt2iapvozwv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gt2vubdeytm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gt2uzsiektg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gt2lupmfxip.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gt2adjwpwyb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2enaaphqy.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gt2pdbdjmah.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gt2bkazdhgv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2fmxakqmn.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2fwulcdlc.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gt2urvwdhof.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbmvblxh.html

[I01] 判断是否匹配
来源：http://dali.jiagoushi.top/Article/details/gt2fhsnyege.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gt2pqrzqybk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tanke756.top/Article/details/gt2amuvdqxc.html

JS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2wgrpledw.html

TS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gt2ouqvgvrn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2chgldkno.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.snrcjt.cn/Article/details/gt2hqodnzib.html

Ruby: s.match?(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gt2bhmlugic.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.9152youxi.cn/Article/details/gt2afybtleu.html

[I02] 提取所有匹配
来源：http://dali.andypj.xyz/Article/details/gt2drfbgsnu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2ciibyouu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tretctuu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guannengcc.top/Article/details/gt2jjulonhj.html

TS:   s.match(/\d+/g)
来源：http://dali.ydzc1.top/Article/details/gt2gocwyzvw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2jytewlqb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gt2obxucszk.html

Ruby: s.scan(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gt2ipxkjonv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2qaxrotaq.html

[I03] 提取捕获分组
来源：http://dali.andypj.xyz/Article/details/gt2alfjzjmm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gt2wasklrfr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gt2rmqpuioo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cheryme.top/Article/details/gt2kmimwnhd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258888.top/Article/details/gt2ofoipzix.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cheryme.top/Article/details/gt2uhpkyjjx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gzhubu.top/Article/details/gt2uxqzgxvy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gt2qgjgfwpt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yanxiufei.cn/Article/details/gt2uhpdjvxl.html

[I04] 正则替换
来源：http://dali.bjfxy.top/Article/details/gt2wcbbusjy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yongpay.top/Article/details/gt2qbbvvohx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuanzx.com/Article/details/gt2mwfezxlb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2xqqftpse.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gt2fbmljjlj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gt2cqvvkdvn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yvedp.cn/Article/details/gt2cnxcufhb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2bgyabrtf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gt2kylsfurs.html

[I05] 按正则拆分
来源：http://dali.yj202588.top/Article/details/gt2eiazhcpa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2tductcxq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2jimbsjps.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gt2dmjuorad.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2pntjjtjr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ppjwa.cn/Article/details/gt2zliixncq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fzhhl.top/Article/details/gt2yoauvkdp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwccgwki.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hysaishi.cn/Article/details/gt2qbcbtulu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258.top/Article/details/gt2vznigzuq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wagdwvke.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sysykeji.top/Article/details/gt2kcftvwpw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gt2mlvwrtfy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gt2rqzbsvnr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2aljfxuzl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cheryme.top/Article/details/gt2iuynstzz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.316326.xyz/Article/details/gt2whglswpq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2ydljcezl.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gt2qqkxlsem.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gt2hlkpkkmi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gt2kogxxnwp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yueranfly.top/Article/details/gt2ptlovbng.html

TS:   /error/gim
来源：http://dali.zhiwuduotai.top/Article/details/gt2ospzecop.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhengqikj.top/Article/details/gt2welaystg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hywenlv.cn/Article/details/gt2mktpcqeg.html

Ruby: s.scan(/error/i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ectxymtt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2waxxuhxn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.c1oappe.top/Article/details/gt2onirxihf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258888.top/Article/details/gt2zqqjkynv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gt2tjvadbrs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gt2jhjbuxcb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gt2bjrpxrne.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gt2yrkxxrty.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhengqikj.top/Article/details/gt2pynhheln.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zdqjudy.top/Article/details/gt2nagzjnbx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gt2jpxyaiqe.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2oeijwnsl.html

J. 日期与时间
来源：http://dali.zycfv.cn/Article/details/gt2cxiugraw.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2zuayfgce.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gt2xeurotic.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gt2kbyyxuse.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gt2qmqnzlus.html

JS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gt2syixknnk.html

TS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gt2ckgnltwu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tianlin.xyz/Article/details/gt2tigxrhxz.html

Go:   time.Now()
来源：http://dali.zhixingplan.top/Article/details/gt2ywiqczar.html

Ruby: Time.now
来源：http://dali.chenlongwang.top/Article/details/gt2oxpnfsba.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhoulong.xyz/Article/details/gt2gbmconit.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gt2jfmbyxdh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ziiizixv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gt2itypjawc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gt2vlhznspr.html

TS:   d.toISOString()
来源：http://dali.wangdashe.top/Article/details/gt2fudkyxzx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guannengcc.top/Article/details/gt2ehdoyjad.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.vqdsnc.cn/Article/details/gt2oldczahp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gt2eeggtlzb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gt2yfgpyikw.html

[J03] 字符串解析为日期
来源：http://dali.hnxiangtu.top/Article/details/gt2gixvzzlw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj202588.top/Article/details/gt2cdxcinjb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gt2ckxutkrr.html

JS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2ftlbgfzz.html

TS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2kdxukmra.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2opcmdfqq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2sfrgdoym.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2vxmzjgeg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2siqqekpc.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258.top/Article/details/gt2xbjojzna.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wkdlbpbm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gt2goljxohz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sysykeji.top/Article/details/gt2fldlbpwh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aizwys.cn/Article/details/gt2ggqoktfz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gt2ybssmeoz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258888.top/Article/details/gt2bliqwfba.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2gxyfjfvz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gt2semulnni.html

[J05] 时间加减（加 7 天）
来源：http://dali.snrcjt.cn/Article/details/gt2rerkwjmi.html

Py:   now + timedelta(days=7)
来源：http://dali.gotoacloud.top/Article/details/gt2gohezlfl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dianchejie.cn/Article/details/gt2wnlpkoof.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gt2qyulruqs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gt2coskpcpm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xfpxsbhx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangdashe.top/Article/details/gt2kmtbpbam.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhongyouzk.top/Article/details/gt2rggejtvt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2upycgrhs.html

[J06] 计算两时间之差
来源：http://dali.tian-w.cn/Article/details/gt2uftmpfnw.html

Py:   (end - start).total_seconds()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxzvawcr.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gt2hlhyddro.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj202588.top/Article/details/gt2unnjwvde.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnqzz.top/Article/details/gt2czruxfjt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gaohongyu789.top/Article/details/gt2tmfjzymg.html

Go:   end.Sub(start).Hours()
来源：http://dali.shuidangran.top/Article/details/gt2hdcfftrk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gt2dymhbzrp.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbbqwjgh.html

[J07] 比较两个日期
来源：http://dali.nwbrower.top/Article/details/gt2rhkwgkbv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gt2hdfzbcxv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ppjwa.cn/Article/details/gt2xzybwuei.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gt2swqjquwm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gt2onaonpme.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jiagoushi.top/Article/details/gt2odjdqdhn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wpuzexfp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gt2gfqpaahc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gt2ykpnvlsd.html

[J08] 提取年月日与星期
来源：http://dali.jianghu66.top/Article/details/gt2buurianv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cucudq.cn/Article/details/gt2lfkngoaq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hfpthk.cn/Article/details/gt2sskyzxqu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbvahtfu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gotoacloud.top/Article/details/gt2xwuhdodn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhongyouzk.top/Article/details/gt2kbcsqarx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nwbrower.top/Article/details/gt2yakjvthh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cvidldvr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cqqwz.cn/Article/details/gt2knzyraxw.html

[J09] 时区处理
来源：http://dali.gzhubu.top/Article/details/gt2twnscyhl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ytjyryto.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gt2bmiebzir.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gt2ymitspfs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gt2vhteehqd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.kuanghao11.cn/Article/details/gt2kecnvoom.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xypbxrvj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.quarkkingdee.top/Article/details/gt2dmxkrywq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zycfv.cn/Article/details/gt2cujqlyhw.html

[J10] 取今天 / 本月第一天
来源：http://dali.yanxiufei.cn/Article/details/gt2libszzed.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gt2pgsoifim.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangshuangyany.cn/Article/details/gt2cuokwjgx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xkobdnvi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tanke756.top/Article/details/gt2vvhestlz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xbqutrci.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhoulong.xyz/Article/details/gt2kyarrnow.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhiwuduotai.top/Article/details/gt2gjeovbkp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daxiang520.top/Article/details/gt2wolqqbte.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2olktoasr.html

K. JSON 与序列化
来源：http://dali.nanxinkj.top/Article/details/gt2cnuotemp.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2suxzclja.html

[K01] 对象转 JSON 字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2tpyreomy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gt2jmnibsaw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gt2kornceda.html

JS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2zmmlflgd.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gt2lobjiwmy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qeearheq.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2xpvsufxs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.birdmap.top/Article/details/gt2hjgkbsix.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2vwbpwrku.html

[K02] JSON 字符串转对象
来源：http://dali.0kj1m.cn/Article/details/gt2kyydefrn.html

Py:   json.loads(s)
来源：http://dali.sysykeji.top/Article/details/gt2adlshuyh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuanzx.com/Article/details/gt2zbtadnel.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2vjyfswhw.html

TS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gt2pqktigjx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xinyue.icu/Article/details/gt2fzpgmoov.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dulfdove.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2vvduzybp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnqzz.top/Article/details/gt2aynkceyu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fzhhl.top/Article/details/gt2bbagmrot.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gt2deujkkka.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gt2qbktwrmj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrjellhb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2lhojewbk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2lijzohmr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.iojbl.cn/Article/details/gt2ytdfbhuy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yongpay.top/Article/details/gt2edplgydx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tianlin.xyz/Article/details/gt2iizzjsqr.html

[K04] 读取 JSON 文件
来源：http://dali.yanxiufei.cn/Article/details/gt2wirqecbr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gt2ljqpcnsw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shzxlz.cn/Article/details/gt2wopgbgkj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gt2uezkridr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gt2aledbjny.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xziqi.cn/Article/details/gt2bmbofayl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gaqdflox.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2qvbmuqjc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj202588.top/Article/details/gt2uaduenfl.html

[K05] 深拷贝对象
来源：http://dali.zdqjudy.top/Article/details/gt2lucfgvlg.html

Py:   copy.deepcopy(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwegedxl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fengsongda.top/Article/details/gt2gbjkfcno.html

JS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxrgzwqv.html

TS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2lmgcogbi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shzxlz.cn/Article/details/gt2utaviqpr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuanzhike.top/Article/details/gt2bgactotz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cucudq.cn/Article/details/gt2ckfhkzcy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangshuangyany.cn/Article/details/gt2tpkuimtv.html

[K06] 解析 URL 查询串
来源：http://dali.chenzaomai.com/Article/details/gt2gkhxaeak.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bmdlxrpa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mipkvqqe.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lgvgktfj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gt2garnklqa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daxiang520.top/Article/details/gt2lkxpjtxu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2oghjbdmr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlngsltr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2whnrazee.html

[K07] 进制转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2uwxwrjkl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2dhkwogpr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangdashe.top/Article/details/gt2mqdmybpi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2sbtfmeyy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2zvhntjqs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2hexmdmim.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bpdmvabs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.bjfxy.top/Article/details/gt2yrwgadwh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2jvgjziha.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jiagoushi.top/Article/details/gt2rshrthbo.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2gvswtmtm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ivvv.top/Article/details/gt2jotlytmz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gt2cbpckhhg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gt2ojiaeglr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangtech.top/Article/details/gt2etpcdtyb.html

Go:   encoding/gob
来源：http://dali.yj20258888.top/Article/details/gt2bbdfqtzk.html

Ruby: Marshal.dump(obj)
来源：http://dali.316326.xyz/Article/details/gt2hlmxevjm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gt2ttktxzum.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2ueztmuff.html

L. 网络请求
来源：http://dali.xuanzx.com/Article/details/gt2qkpttwtw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2iixeaoaa.html

[L01] 发送 GET 请求
来源：http://dali.hnqzz.top/Article/details/gt2vbtwbfty.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigfzy.top/Article/details/gt2kdeatszt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hfpthk.cn/Article/details/gt2owltzqbl.html

JS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oppvanzs.html

TS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gt2hisryfow.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yangfankeji.com/Article/details/gt2ahjmnqeg.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgfzy.top/Article/details/gt2hknrowew.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvxglpcy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xylfe.cn/Article/details/gt2godqbusz.html

[L02] 发送 POST JSON
来源：http://dali.tanke756.top/Article/details/gt2iwsywzuf.html


<!-- 参考信息 -->