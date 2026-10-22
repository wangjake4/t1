代发 wailian999

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhmjsdxb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.kuanghao11.cn/Article/details/gtqfqlyxdf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.redwolf501.top/Article/details/gtjnesvmdj.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gthoghinyq.html

[H07] 断言
来源：http://dali.jiagoushi.top/Article/details/gtdipqcfwt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuetiantiany.cn/Article/details/gtgcrjdhkx.html

PHP:  assert($x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtzqrfcfef.html

JS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtlkzhaeci.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtzdhzoywu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ehwqpu.com/Article/details/gtfinpyreu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gtkmymxyvu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.c1oappe.top/Article/details/gtkajyfozn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtxalwipwc.html

[H08] 获取错误信息与堆栈
来源：http://dali.gaohongyu789.top/Article/details/gtmbdnckyh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aibaodan.cn/Article/details/gtkrzngqvs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangshuangyany.cn/Article/details/gtkgrgjeqh.html

JS:   e.message;  e.stack
来源：http://dali.chenzaomai.com/Article/details/gtgtipgphk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cdnleiting.top/Article/details/gtzqoceuov.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxinkj.top/Article/details/gtbgrfypdi.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gtmcswknis.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gtosymjmqu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sxryk.cn/Article/details/gtypifnnhv.html

[H09] 带错误码的异常
来源：http://dali.nwbrower.top/Article/details/gtuuttxmng.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aizwys.cn/Article/details/gthspctkyx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ybcxt.top/Article/details/gtutkzbder.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhiwuduotai.top/Article/details/gtokwdcmdm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigfzy.top/Article/details/gtdrvkxnfv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gtaivwhscp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gtefshzpkg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xziqi.cn/Article/details/gthowkkrum.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guannengcc.top/Article/details/gtucacnvbv.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gtgetnnvzy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tanke756.top/Article/details/gtjgpusbhb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgfzy.top/Article/details/gtlenppybd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtctlopvza.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtcuxxvnyg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fzhhl.top/Article/details/gtcqjsjhwe.html

Go:   defer f.Close()
来源：http://dali.chenjidiqi.icu/Article/details/gtvpbwyvte.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gtkwhxrimk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtvcbasxiw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gthatlqibh.html

I. 正则表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtuvdwktuv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtdpvbgsyx.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gtrhannjlv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gtaioyiiwb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtoxualtxd.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gtlucrutdg.html

TS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gtpvjnctho.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gtfvaxlyjv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangdashe.top/Article/details/gtnpzwiaii.html

Ruby: s.match?(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gtijqkwiez.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.bjfxy.top/Article/details/gtjyhybvpr.html

[I02] 提取所有匹配
来源：http://dali.guowangkeji.top/Article/details/gtzqeycpay.html

Py:   re.findall(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gtwcswktmr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cucudq.cn/Article/details/gtknccfepg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.mhx1999.top/Article/details/gtschpszjm.html

TS:   s.match(/\d+/g)
来源：http://dali.iojbl.cn/Article/details/gtesbsjirb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhengqikj.top/Article/details/gtzzedfemj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gtqheibwne.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtzzrmknei.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtjnobgazr.html

[I03] 提取捕获分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvguptfk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.meibo888.top/Article/details/gtifmlagrz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.smart0.xyz/Article/details/gtkgmqmmsp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxjtpijw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hywenlv.cn/Article/details/gtjhvglmoe.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gtbhrzoggb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.kuanghao11.cn/Article/details/gtwuweiyuv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yangfankeji.com/Article/details/gtsdecogwf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.redwolf501.top/Article/details/gttjmawzvo.html

[I04] 正则替换
来源：http://dali.yj202588.top/Article/details/gtylrfpzhu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shzxlz.cn/Article/details/gtnxmvlqnu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtjuofetoi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtlsfwwqrt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtyafusqdi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtievytqoq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtrxzqwngz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dianchejie.cn/Article/details/gtcrinryui.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtmefxzolf.html

[I05] 按正则拆分
来源：http://dali.xylfe.cn/Article/details/gtfcigsngr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.vqdsnc.cn/Article/details/gtpkfrxnbo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gtuebxkrpy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtenxfsens.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtvmmfaiqe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.meibo888.top/Article/details/gtmbmbznwe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gthvzhoiai.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtsxbscbsd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yonumen.top/Article/details/gtpwzmxari.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pengpengdd.cyou/Article/details/gtiyjuvzdo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtiqonrtip.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ybcxt.top/Article/details/gttuzngwac.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gtvgxawcjp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gtwtpincee.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtvnxpqzfd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258.top/Article/details/gtqbskqlny.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cheryme.top/Article/details/gtbpzknofz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtludyrmbi.html

[I07] 忽略大小写与多行模式
来源：http://dali.svipenyu.cn/Article/details/gtyvyaqrrh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258888.top/Article/details/gtrhljtdfz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gtofhbszhi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aizwys.cn/Article/details/gtomufveth.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gtrnhzlzwx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yongpay.top/Article/details/gthhvjcbsd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gtznqkhxjt.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gthcvfaxkh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cheryme.top/Article/details/gthwigsfrw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cdnleiting.top/Article/details/gtiwxevoch.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.316326.xyz/Article/details/gtjbhjhlfr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtznnjvgbo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gtfcxasuym.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtcxmprrnb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtrzavnqcv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigufen.top/Article/details/gtrzjydmyw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenjidiqi.icu/Article/details/gtnuqeilyk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gtilkphnrz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwkxaltxs.html

J. 日期与时间
来源：http://dali.9152youxi.cn/Article/details/gtrbjovwjf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtvwbpskqz.html

[J01] 获取当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtnvkgcyzt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.svipenyu.cn/Article/details/gtweoedfdi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gtbzjthlcw.html

JS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gthhgcrdkk.html

TS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbuhwpny.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.andypj.xyz/Article/details/gtgzjxzirw.html

Go:   time.Now()
来源：http://dali.guowangkeji.top/Article/details/gtvkoluhlp.html

Ruby: Time.now
来源：http://dali.feifeiyinyue.top/Article/details/gtbcurenwm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdjgjhst.html

[J02] 格式化输出
来源：http://dali.jianghu66.top/Article/details/gtqhnnvniq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gtsofjsyda.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gthjenfakf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sxryk.cn/Article/details/gtuxgpykjs.html

TS:   d.toISOString()
来源：http://dali.dianchejie.cn/Article/details/gtqwybmepi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.smart0.xyz/Article/details/gtlhmmeyho.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xziqi.cn/Article/details/gtfzgftswm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gtagdzngnl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jiagoushi.top/Article/details/gtgsgwxcrb.html

[J03] 字符串解析为日期
来源：http://dali.sufxvd.cn/Article/details/gtlqumirtd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.bjfxy.top/Article/details/gtwwxotwpy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guowangkeji.top/Article/details/gtyvwnlqbl.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtgpeajvsu.html

TS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtllpiklwk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gttpiwswsg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtmmsdhdky.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtqqhsrkyh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jiagoushi.top/Article/details/gtyvaqkhrk.html

[J04] 时间戳与日期互转
来源：http://dali.vqdsnc.cn/Article/details/gtmdvwttsb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.andypj.xyz/Article/details/gtzauebiiq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yueranfly.top/Article/details/gtxktyxhcl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gtlcpmelnr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sxryk.cn/Article/details/gtzqmexzme.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hysaishi.cn/Article/details/gtfcrulpkz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daxiang520.top/Article/details/gtobncbprf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gtyciccwtu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gtmluckxtu.html

[J05] 时间加减（加 7 天）
来源：http://dali.hfpthk.cn/Article/details/gtrozchhuy.html

Py:   now + timedelta(days=7)
来源：http://dali.yvedp.cn/Article/details/gtfvtyomyy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuanzx.com/Article/details/gtxbowptrn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gtbznbebup.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gtkbykcbbc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.c1oappe.top/Article/details/gtxmyimlgm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gtozyongly.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangshuangyany.cn/Article/details/gttstbkroe.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gtsafzqhvi.html

[J06] 计算两时间之差
来源：http://dali.tanke756.top/Article/details/gtmduwsewe.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvlcdyah.html

PHP:  $end->diff($start)->days;
来源：http://dali.xziqi.cn/Article/details/gtcndqsdgn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ybcxt.top/Article/details/gtzgfchotc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dashuyun.cn/Article/details/gtxfsmffmc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgufenzy.top/Article/details/gthdtdugci.html

Go:   end.Sub(start).Hours()
来源：http://dali.feifeiyinyue.top/Article/details/gtskkgxglz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daria6918.cn/Article/details/gtkackosca.html

C#:   (end - start).TotalSeconds
来源：http://dali.yvedp.cn/Article/details/gtepphczra.html

[J07] 比较两个日期
来源：http://dali.cheryme.top/Article/details/gtxyrdpyjb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtdniephth.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gtstrzibjb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtxgnjohun.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gtfudzrlpf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.iojbl.cn/Article/details/gtrgrcixuh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yanxiufei.cn/Article/details/gtzbcxecoe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtyuympbsj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtwudpmmmj.html

[J08] 提取年月日与星期
来源：http://dali.jqgfzy.top/Article/details/gtecrroixj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jyoumei.cn/Article/details/gthlfezils.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dianchejie.cn/Article/details/gtwlbmdgwe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangshuangyany.cn/Article/details/gthzpglcpd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gtpufbwmqy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtouwdejwv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.feifeiyinyue.top/Article/details/gtdxyrllkg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cqqwz.cn/Article/details/gthvhphzjq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.316326.xyz/Article/details/gtzpnavyxz.html

[J09] 时区处理
来源：http://dali.yueranfly.top/Article/details/gtclwykghb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hywenlv.cn/Article/details/gttlzhvgmv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangshuangyany.cn/Article/details/gtfkefcfzg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtxnqlmchi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtdkelbaxa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ehwqpu.com/Article/details/gtkccspifm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gtqsmpyqhp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gotoacloud.top/Article/details/gtfdmxfxlg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgufenzy.top/Article/details/gtdprxdaet.html

[J10] 取今天 / 本月第一天
来源：http://dali.hysaishi.cn/Article/details/gtruvlgocp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.smart0.xyz/Article/details/gtabvhkpmz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jyoumei.cn/Article/details/gtcchyawfz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ydzc1.top/Article/details/gtngzlemsy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gtnqkxhdqc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtcbnxgrqk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigufen.top/Article/details/gtmdgwndcp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pycfn.com/Article/details/gtjyldpsia.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.redwolf501.top/Article/details/gtacocdvhq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtndudrmpj.html

K. JSON 与序列化
来源：http://dali.redwolf501.top/Article/details/gtrpythzsh.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gttgdmfgkb.html

[K01] 对象转 JSON 字符串
来源：http://dali.pycfn.com/Article/details/gtfdoyepbz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gtqbxvesve.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gtygksmljh.html

JS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtpwwucwve.html

TS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gtgjllnicb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gtorrehrgt.html

Go:   json.Marshal(obj)
来源：http://dali.cdnleiting.top/Article/details/gtjyaduzwi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gtowaivbnu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daria6918.cn/Article/details/gteizoeupt.html

[K02] JSON 字符串转对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfavqtcis.html

Py:   json.loads(s)
来源：http://dali.pycfn.com/Article/details/gtfeaxqvxr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.iojbl.cn/Article/details/gthnnpomab.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtidzszypl.html

TS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gtlenherbn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtdjcewgcg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gtgljbzacv.html

Ruby: JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtpijyclez.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.haohaochexian.top/Article/details/gtokaidtue.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigfzy.top/Article/details/gtgidiijcu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gtnfmbyweh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtabmvsfue.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtyrbxuuzq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gtmzrlzdlp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuanzx.com/Article/details/gtxcnwzghr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gtclahjyef.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuanzhike.top/Article/details/gtpgjkrrgj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.9152youxi.cn/Article/details/gtcqnmslbi.html

[K04] 读取 JSON 文件
来源：http://dali.tianlin.xyz/Article/details/gtwytivexa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gogol.net.cn/Article/details/gtzwfjpvcv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gteccixeru.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gtqkwxcgfw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gttyvavhkl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtixpizclk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gtietyzhrw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gtrafmprsk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhgusktj.html

[K05] 深拷贝对象
来源：http://dali.zdqjudy.top/Article/details/gtzjbqftnw.html

Py:   copy.deepcopy(obj)
来源：http://dali.xylfe.cn/Article/details/gtwztaxfwj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gttgljcreb.html

JS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gtbupbqwtb.html

TS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtijuacafz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guannengcc.top/Article/details/gttzlxbtgv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pycfn.com/Article/details/gtsixqwmsy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigufen.top/Article/details/gtpzqcmnss.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daria6918.cn/Article/details/gtugkgwcux.html

[K06] 解析 URL 查询串
来源：http://dali.xuetiantiany.cn/Article/details/gtbkluthgm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtmchlwlzr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fzhhl.top/Article/details/gtovldwjit.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtjjnuialh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gtujsdkzmc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fzhhl.top/Article/details/gtjjsfmkxg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtazhxusoa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtcgmcnnav.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtysmkgrwa.html

[K07] 进制转换
来源：http://dali.ivvv.top/Article/details/gthkpdtlwx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtfcdmkqxr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cashguo.top/Article/details/gtvqghjuhk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtctskmfbk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtfcwatguf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtcexcqiuy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shuidangran.top/Article/details/gtewjjsocg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yanxiufei.cn/Article/details/gtqaifamkr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkusratep.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.haohaochexian.top/Article/details/gttcjkumhj.html

Py:   pickle.dumps(obj)
来源：http://dali.0kj1m.cn/Article/details/gtlwnjvvyf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hysaishi.cn/Article/details/gtoelvsjev.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtqlsvajtb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtjlzcggyv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yongpay.top/Article/details/gtufjoalib.html

Go:   encoding/gob
来源：http://dali.pengpengdd.cyou/Article/details/gtawqmltny.html

Ruby: Marshal.dump(obj)
来源：http://dali.shzxlz.cn/Article/details/gtajyjgnlp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlynxpgf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvncnvxta.html

L. 网络请求
来源：http://dali.xuetiantiany.cn/Article/details/gtsqkrphkm.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtsjqhzeyj.html

[L01] 发送 GET 请求
来源：http://dali.tian-w.cn/Article/details/gteudienlr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.birdmap.top/Article/details/gtrgqwnrvq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ppjwa.cn/Article/details/gtlulmjoqt.html

JS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gtlfmsmjtz.html

TS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gtmhliotth.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gterozdzln.html

Go:   resp, err := http.Get(url)
来源：http://dali.mhx1999.top/Article/details/gtwanzgbeu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gtbavgymgx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj20258888.top/Article/details/gtidzzshcl.html

[L02] 发送 POST JSON
来源：http://dali.cheryme.top/Article/details/gtqoxuzxgm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtobzecczw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hongshengwenyu.top/Article/details/gtudwdvotp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gtkaozqqbn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gtyqwxfnqo.html


<!-- 参考信息 -->