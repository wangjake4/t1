代发 wailian999

TS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtxjphocye.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gtvnyvskkk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gtkradmcbh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cqqwz.cn/Article/details/gtayebkuvn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtercndgas.html

[H08] 获取错误信息与堆栈
来源：http://dali.xylfe.cn/Article/details/gtvzylptaf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jyoumei.cn/Article/details/gtkgkeexbu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangtech.top/Article/details/gtawlgausk.html

JS:   e.message;  e.stack
来源：http://dali.yj20258888.top/Article/details/gtujtlonue.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gthdkyupvb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gtsthfkdee.html

Go:   err.Error()
来源：http://dali.aizwys.cn/Article/details/gtkhovpums.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gtkhedwetk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangdashe.top/Article/details/gtyfuquuru.html

[H09] 带错误码的异常
来源：http://dali.birdmap.top/Article/details/gtrfptbpgc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsfoxtgr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tianlin.xyz/Article/details/gtpyrjpxjb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvwftxba.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gtispajjip.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnxiangtu.top/Article/details/gtzjampzyq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gzhubu.top/Article/details/gtafdatdid.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gtsdwtnohl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gtyqytyhaz.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gtklfthuog.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gtlriyoqgb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gtgrafumgy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gtfgupzyib.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtawhwwhyv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hysaishi.cn/Article/details/gtzjkbbrgi.html

Go:   defer f.Close()
来源：http://dali.9152youxi.cn/Article/details/gtwpeivyxa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yanxiufei.cn/Article/details/gtodccsgwf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gthixmqeuz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtbmuskogu.html

I. 正则表达式
来源：http://dali.yj20258.top/Article/details/gtnxworkgx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtsncfyton.html

[I01] 判断是否匹配
来源：http://dali.nwbrower.top/Article/details/gthjeijjed.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtpysrapxw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbswmtwc.html

JS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gtgzmwuaot.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtcdvrtenn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zdqjudy.top/Article/details/gtzjmvdgez.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gtikxzghbk.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gtnoeyqzre.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.andypj.xyz/Article/details/gtssophnmh.html

[I02] 提取所有匹配
来源：http://dali.vqdsnc.cn/Article/details/gtwmqocruo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gtjmsgaxtq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yongpay.top/Article/details/gtxvexvfyo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.havefunace.top/Article/details/gtljdnqbcj.html

TS:   s.match(/\d+/g)
来源：http://dali.yonumen.top/Article/details/gthefblmce.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.snrcjt.cn/Article/details/gtwlmmymiq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtkzjeailc.html

Ruby: s.scan(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gthdkrlyca.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtgqshnyjg.html

[I03] 提取捕获分组
来源：http://dali.0kj1m.cn/Article/details/gtkmtpbfkj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sxryk.cn/Article/details/gtfoiwapdv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqaruyft.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenlongwang.top/Article/details/gtsxuijqcu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daxiang520.top/Article/details/gtptjsbxvm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gtacpsrxmi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gtuwoajksm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfpezkiy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuanzx.com/Article/details/gtojkgbkyi.html

[I04] 正则替换
来源：http://dali.nwbrower.top/Article/details/gtfkumzvqx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gtnvllgwfk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtaklcheaw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtgdubqrcr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gtharkvwup.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtjthioalw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zycfv.cn/Article/details/gtwcgfauxi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xylfe.cn/Article/details/gtvhlfuyrr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gthscoolgu.html

[I05] 按正则拆分
来源：http://dali.cashguo.top/Article/details/gtpnuberkq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shuidangran.top/Article/details/gtnvqlrbvu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuanzx.com/Article/details/gtvcaoodiy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtpovbuixf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtifkmnyjh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigufen.top/Article/details/gtmfrioqye.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gtgaphhfah.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtxnokfckj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhengqikj.top/Article/details/gthabdlorn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daria6918.cn/Article/details/gtwlfyqdst.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gtrkxmpghf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gtnxzxxaqz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gtxyiuedvp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gtkcrqcjxf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtvmwnkwvg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yongpay.top/Article/details/gtdmqpzprr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.svipenyu.cn/Article/details/gtjmqvfcpg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtffhwzbpw.html

[I07] 忽略大小写与多行模式
来源：http://dali.yangfankeji.com/Article/details/gtnspndqxp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fengsongda.top/Article/details/gtcphagykp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gtnmwozazz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zdqjudy.top/Article/details/gtqfomteqi.html

TS:   /error/gim
来源：http://dali.c1oappe.top/Article/details/gtnnmeikam.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ehwqpu.com/Article/details/gtqrtmggmp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenlongwang.top/Article/details/gtwdaprsxp.html

Ruby: s.scan(/error/i)
来源：http://dali.birdmap.top/Article/details/gtrmxptotr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gtddygehgd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcrbfckv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cdnleiting.top/Article/details/gtxiewovry.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtfyqpffgq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gtplzlixky.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gtzvqcixng.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gtjagobfpi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gtmoslfspz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.vqdsnc.cn/Article/details/gtuxxergca.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtmmhbkahf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gthzxrjyql.html

J. 日期与时间
来源：http://dali.fzhhl.top/Article/details/gtkqujokwk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtjxxddcda.html

[J01] 获取当前时间
来源：http://dali.aizwys.cn/Article/details/gtksmaavwu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.andypj.xyz/Article/details/gtibkmezdq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtmglscsrw.html

JS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtygnndxpz.html

TS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtokxmzipy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.birdmap.top/Article/details/gtslgxahly.html

Go:   time.Now()
来源：http://dali.shangyingyoupin.top/Article/details/gtqaongxuh.html

Ruby: Time.now
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhnbrfdp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gthisecwlc.html

[J02] 格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyufnbnh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtekcjmggu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtbbgvyynu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxinkj.top/Article/details/gtebkbguch.html

TS:   d.toISOString()
来源：http://dali.cashguo.top/Article/details/gtbhamamqb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuanzx.com/Article/details/gthphqmpeh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ehwqpu.com/Article/details/gtnbftakpn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gtpsuwpovb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gtnkbuudqk.html

[J03] 字符串解析为日期
来源：http://dali.sweek.top/Article/details/gtfircqxws.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sweek.top/Article/details/gtfbvcyzik.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gtqlsoabkb.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtkwazvzou.html

TS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtvhawcfrj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gthybyzatu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtvuajbste.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtksfxsgov.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxuapqofz.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gtwchopvcu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.andypj.xyz/Article/details/gtevvsedrs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gtnstijomm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gtynpyjzob.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gttrosgdjc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenlongwang.top/Article/details/gtgcsgmlkz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gtqwsvjhpb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtkvegopcr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtofenhnwj.html

[J05] 时间加减（加 7 天）
来源：http://dali.hysaishi.cn/Article/details/gtypbuepwg.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gtacuwmnmr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvwhzeti.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gtotqriqex.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gtjsidozcb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgfzy.top/Article/details/gtztajqxfm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ppjwa.cn/Article/details/gtnlxkqtbb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sufxvd.cn/Article/details/gtyciiufee.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sysykeji.top/Article/details/gtukdjnwtd.html

[J06] 计算两时间之差
来源：http://dali.0kj1m.cn/Article/details/gteduovsmi.html

Py:   (end - start).total_seconds()
来源：http://dali.hnxiangtu.top/Article/details/gtfwkhvamm.html

PHP:  $end->diff($start)->days;
来源：http://dali.zdqjudy.top/Article/details/gtvvaolwal.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gtfczvzmnp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnqzz.top/Article/details/gttougambf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gogol.net.cn/Article/details/gtdkanbmzr.html

Go:   end.Sub(start).Hours()
来源：http://dali.jyoumei.cn/Article/details/gtnevylgjr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sweek.top/Article/details/gtsxkicsvs.html

C#:   (end - start).TotalSeconds
来源：http://dali.ppjwa.cn/Article/details/gtibvwkavd.html

[J07] 比较两个日期
来源：http://dali.sweek.top/Article/details/gtmfimhfzk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtszztplsu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sysykeji.top/Article/details/gtjbtpycxz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtqtcpyvgp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtpvuecfzr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.kuanghao11.cn/Article/details/gtvkmeeknc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gtuejkslci.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtvokngzwv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtkoqhnbpb.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gtsieoutqo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.redwolf501.top/Article/details/gtysumffri.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhixingplan.top/Article/details/gtrwbiisfo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gthzeopkpc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gtcddvpgwi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmyicxqdy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guowangkeji.top/Article/details/gttkucdvce.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258.top/Article/details/gtwcasaehp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.0kj1m.cn/Article/details/gtmrtpfvxg.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gtgijqmrqz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sysykeji.top/Article/details/gtrqpznqne.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.316326.xyz/Article/details/gtttwwtehi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gthlrgbczv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gtlglfnnsw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangshuangyany.cn/Article/details/gtfiiwtlwm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gtuyapbeuu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj202588.top/Article/details/gtokzhemkx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258888.top/Article/details/gtpdfuyeih.html

[J10] 取今天 / 本月第一天
来源：http://dali.bjfxy.top/Article/details/gtqilminea.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gtntadhndi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gtsxlhlaze.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.9152youxi.cn/Article/details/gtrqwbcduf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgfzy.top/Article/details/gtssfwwxnf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ivvv.top/Article/details/gtqsgdbdqm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuxming.cn/Article/details/gtcftuevta.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ydzc1.top/Article/details/gtvlneuolb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cashguo.top/Article/details/gthmkgvzok.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtgqqaepiy.html

K. JSON 与序列化
来源：http://dali.sufxvd.cn/Article/details/gtwnwjutby.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtasxkprlr.html

[K01] 对象转 JSON 字符串
来源：http://dali.aibaodan.cn/Article/details/gtgvaqjawo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtiycnillq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtsjwlmrjg.html

JS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtumvcpsda.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtbrfopsrx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuanzx.com/Article/details/gtbljzqhah.html

Go:   json.Marshal(obj)
来源：http://dali.yuxming.cn/Article/details/gtffyxtwnb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xylfe.cn/Article/details/gtpxujcxdv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pycfn.com/Article/details/gteygvhzoa.html

[K02] JSON 字符串转对象
来源：http://dali.aizwys.cn/Article/details/gtvegrzxzk.html

Py:   json.loads(s)
来源：http://dali.kuanghao11.cn/Article/details/gtbwtrbujg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.c1oappe.top/Article/details/gtdpzvhsch.html

JS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtxvrdmlva.html

TS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtxdllsull.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtoollkvda.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gtffgkdrms.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gttbkwlqqo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.snrcjt.cn/Article/details/gthbwqgowm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.havefunace.top/Article/details/gtquauvfny.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gtbryclgtf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gthtznzcti.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtgiuvgrxo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtduchoaxm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tian-w.cn/Article/details/gtnjapdjpa.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuanzx.com/Article/details/gtwqxjifsc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gtbrptslcb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sysykeji.top/Article/details/gtespgghkp.html

[K04] 读取 JSON 文件
来源：http://dali.wangdashe.top/Article/details/gtiastpdzk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuanzx.com/Article/details/gtqnbyyrrt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnqzz.top/Article/details/gtmedkinfn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gtliapudzo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtwgnwlzlw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtckiyessy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhytmvqz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtosmssnpc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gtrirumkbo.html

[K05] 深拷贝对象
来源：http://dali.cheryme.top/Article/details/gttwydgfqt.html

Py:   copy.deepcopy(obj)
来源：http://dali.yonumen.top/Article/details/gtwuzpafbs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daxiang520.top/Article/details/gtwtejzdlv.html

JS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtraorfqun.html

TS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtcmgjfrgv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuxming.cn/Article/details/gtjggjfnoh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenzaomai.com/Article/details/gtoqnnxtiw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.smart0.xyz/Article/details/gtspwxdurw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gtrxycbqrt.html

[K06] 解析 URL 查询串
来源：http://dali.wangdashe.top/Article/details/gtmlskybgr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gtbcedbuzy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxinkj.top/Article/details/gteemxaajn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gtqubjvtqr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gtdhspdzna.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gtgayxgcjt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gtwjtjakaj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtokdplfzr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtvohabbpm.html

[K07] 进制转换
来源：http://dali.yuxming.cn/Article/details/gtaikiefjt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtqcpmsgip.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cashguo.top/Article/details/gttysfdurj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtgbnweyjo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtciigpgxy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtaldowwax.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gaohongyu789.top/Article/details/gtglmyvrll.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gtebwtctdz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtpfaaatyh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zdqjudy.top/Article/details/gtqkghjevr.html

Py:   pickle.dumps(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtkxupskry.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sysykeji.top/Article/details/gtodfomixe.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gtnvdtfspq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gtoykwzvfe.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ppjwa.cn/Article/details/gtwhzjlful.html

Go:   encoding/gob
来源：http://dali.havefunace.top/Article/details/gthvjqwtel.html

Ruby: Marshal.dump(obj)
来源：http://dali.jyoumei.cn/Article/details/gtjyswhsfw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gtcrunrsah.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavtyvwal.html

L. 网络请求
来源：http://dali.pycfn.com/Article/details/gtsnxdgado.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtrzuhmuwm.html

[L01] 发送 GET 请求
来源：http://dali.9152youxi.cn/Article/details/gtcqkvgrqv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dianchejie.cn/Article/details/gtnkteribh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapoyjwdv.html

JS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gtqkmquxiy.html

TS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxexobzgi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fengsongda.top/Article/details/gtrvfihbbg.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gthovpfneh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xziqi.cn/Article/details/gtpokanjnr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gotoacloud.top/Article/details/gtlzbvfclu.html

[L02] 发送 POST JSON
来源：http://dali.redwolf501.top/Article/details/gtqvlhjifr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaflwovsu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuanzhike.top/Article/details/gtfwxwpdnd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gtikgkxuql.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gtjkadymdu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgufenzy.top/Article/details/gtzzfooffa.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cqqwz.cn/Article/details/gtvbtcytue.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gaohongyu789.top/Article/details/gtzlezyzot.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhengqikj.top/Article/details/gtukkopxwi.html

[L03] 设置自定义请求头
来源：http://dali.hammf.cn/Article/details/gtcwfxicaw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tian-w.cn/Article/details/gtfjkggllh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guannengcc.top/Article/details/gtiiezyqes.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gtiankamms.html


<!-- 参考信息 -->