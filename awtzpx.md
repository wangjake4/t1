代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.c1oappe.top/Article/details/gtnjbhlhev.html

Ruby: rescue ArgumentError => e
来源：http://dali.yvedp.cn/Article/details/gtiffvwtja.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenlongwang.top/Article/details/gtfayqrtlp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.meibo888.top/Article/details/gtwptuodqe.html

Py:   value = d.get("k") or default
来源：http://dali.yueranfly.top/Article/details/gtoizhkuyu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gtefhdwrzm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtnuyjxhla.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gtfrbyzpps.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gotoacloud.top/Article/details/gtyjsxgxuw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dashuyun.cn/Article/details/gthrqvwvrq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gtiyeguuvl.html

C#:   obj?.A?.B ?? default
来源：http://dali.ydzc1.top/Article/details/gtgskxuhdz.html

[H07] 断言
来源：http://dali.daxiang520.top/Article/details/gthrujzhvq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhongyouzk.top/Article/details/gtpitaslqr.html

PHP:  assert($x > 0);
来源：http://dali.fzhhl.top/Article/details/gtyteessyo.html

JS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtxfzztfci.html

TS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtzahzilrg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sweek.top/Article/details/gtrgybctty.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hywenlv.cn/Article/details/gtmakjsjsj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gtibrshrga.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gticabafco.html

[H08] 获取错误信息与堆栈
来源：http://dali.hfpthk.cn/Article/details/gtgwlaihry.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hywenlv.cn/Article/details/gtyrelkvtp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cqqwz.cn/Article/details/gtcwjtxwad.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjiismjka.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gttyktbedl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gthbkfwdvy.html

Go:   err.Error()
来源：http://dali.andypj.xyz/Article/details/gtidyjosun.html

Ruby: e.message;  e.backtrace
来源：http://dali.pengpengdd.cyou/Article/details/gtupkwyxdx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258888.top/Article/details/gtcdarcpie.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdlyaqnp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yvedp.cn/Article/details/gtykzgross.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjxbpckr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yongpay.top/Article/details/gtrtrjaqlv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hongshengwenyu.top/Article/details/gtrvvebdey.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yonumen.top/Article/details/gtujpobypn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnqzz.top/Article/details/gtarozkini.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.meibo888.top/Article/details/gtdlzoqljs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guannengcc.top/Article/details/gtfmthcjgp.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gtcsmnvkrb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yueranfly.top/Article/details/gtnsnrxedb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ppjwa.cn/Article/details/gtlqvgcjqy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gtktlbmhxe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gtmldxznxa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzdkxaul.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gtilcanfmb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gtcdnztqbj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtpwwiznnx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gthjnfnjhd.html

I. 正则表达式
来源：http://dali.haohaochexian.top/Article/details/gtehrqcbke.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtmexsbsat.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gtkgylcooh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gtabsvkcyt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gthbootpcm.html

JS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gtepqvstke.html

TS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gtgjhievym.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tian-w.cn/Article/details/gtjbbyhwvb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtowkdvssw.html

Ruby: s.match?(/\d+/)
来源：http://dali.meibo888.top/Article/details/gtrzqnugsr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtotziptdu.html

[I02] 提取所有匹配
来源：http://dali.kuanghao11.cn/Article/details/gtmrbnkokf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtuqmmipmf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gtsdnnurms.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dashuyun.cn/Article/details/gtnlkwvllh.html

TS:   s.match(/\d+/g)
来源：http://dali.shuidangran.top/Article/details/gtdmnqinbw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ybcxt.top/Article/details/gtoxykpnfx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtfkeuqbca.html

Ruby: s.scan(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtvqxrcerg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtppprtvdb.html

[I03] 提取捕获分组
来源：http://dali.tanke756.top/Article/details/gtemhxculg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zdqjudy.top/Article/details/gteeswlwtl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhcrzjim.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gtpjedcjtz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgfzy.top/Article/details/gtmnazgbgb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigfzy.top/Article/details/gtikyoelek.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jianghu66.top/Article/details/gtaceywajp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guowangkeji.top/Article/details/gtocjpqqng.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cqqwz.cn/Article/details/gtrpsdtytv.html

[I04] 正则替换
来源：http://dali.sysykeji.top/Article/details/gtpdepahye.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnxiangtu.top/Article/details/gtzletpulf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gtuiofahyt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gtfbclwksi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtvspuakxt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gtvcjaixpo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.316326.xyz/Article/details/gtroxpmszq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gtyskrbrcd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtgedigwna.html

[I05] 按正则拆分
来源：http://dali.shzxlz.cn/Article/details/gtnsnzhces.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.svipenyu.cn/Article/details/gtbjsqbeny.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtfuvbtdbe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtuyvvgdwp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtxraibkog.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guowangkeji.top/Article/details/gtcgivputi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtotgdobym.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtqpvpchgs.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigufen.top/Article/details/gtjwjyqkdg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gtlaegknbp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtiasiqugj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.andypj.xyz/Article/details/gtunyaoggm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtixrtnwur.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gtszycdvfc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtkxjfvbgd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuxming.cn/Article/details/gtnstuujww.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.bjfxy.top/Article/details/gtfyciffew.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtgphuxmvb.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldbgufyh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258888.top/Article/details/gtxloqaeas.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gtmexaenjp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nwbrower.top/Article/details/gtpgnbfjxz.html

TS:   /error/gim
来源：http://dali.yueranfly.top/Article/details/gtxnbuwxmx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guowangkeji.top/Article/details/gttxhnnend.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yueranfly.top/Article/details/gtebozhexr.html

Ruby: s.scan(/error/i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgarxiwyw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.snrcjt.cn/Article/details/gtdxtrzvyb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.birdmap.top/Article/details/gtrpvtinbc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gteltegyig.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtjwobjrwk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gtxyxnrcjf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbmsknyo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbdhwptr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xinyue.icu/Article/details/gtdcjnaufn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigufen.top/Article/details/gtqmlqwzoy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtdwowjlbv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtedqaitqh.html

J. 日期与时间
来源：http://dali.ehwqpu.com/Article/details/gthmxwheit.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtgkjvwvbv.html

[J01] 获取当前时间
来源：http://dali.gzhubu.top/Article/details/gtxkywkyap.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yangfankeji.com/Article/details/gtxatxvmnu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqdxroip.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtdmqbglug.html

TS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gtqugwrfuv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tian-w.cn/Article/details/gtuafflejd.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gtsjkskvbh.html

Ruby: Time.now
来源：http://dali.wangdashe.top/Article/details/gtuqcrnpvu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfqcaarv.html

[J02] 格式化输出
来源：http://dali.hfpthk.cn/Article/details/gtnibdpaou.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtqchbhdqm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtrzaomwew.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenzaomai.com/Article/details/gtyaiqztix.html

TS:   d.toISOString()
来源：http://dali.pycfn.com/Article/details/gtfgkuyszl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nwbrower.top/Article/details/gtgummshyg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgdrsbfp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gtoabrqdmk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gtqxndario.html

[J03] 字符串解析为日期
来源：http://dali.tianlin.xyz/Article/details/gtwbteuknm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ybcxt.top/Article/details/gtgkrjwzgz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yongpay.top/Article/details/gtkfnbuhaj.html

JS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtfuwmkobo.html

TS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtnwrwmumj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtlrfjxgle.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtqkutwmfu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtbfcsgigf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdovlivbw.html

[J04] 时间戳与日期互转
来源：http://dali.pycfn.com/Article/details/gtuktenzuk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.9152youxi.cn/Article/details/gtdviqortx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gtiebvipmb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guannengcc.top/Article/details/gtqofunwkr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxuanxn.top/Article/details/gtcnuacgmk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258.top/Article/details/gtcziptrfa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gtsyuekrig.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtgvflpbsf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gtuizptcfu.html

[J05] 时间加减（加 7 天）
来源：http://dali.mhx1999.top/Article/details/gtzbzffehx.html

Py:   now + timedelta(days=7)
来源：http://dali.cqqwz.cn/Article/details/gtjuiivjjs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daxiang520.top/Article/details/gtayhncgzc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gtqrbmtnyb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gtacxgfjis.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xinyue.icu/Article/details/gtdbsiwmlt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhiwuduotai.top/Article/details/gttzghsmxx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sufxvd.cn/Article/details/gtteeovkwp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gtsayzvcxo.html

[J06] 计算两时间之差
来源：http://dali.yanxiufei.cn/Article/details/gtlmzwinqo.html

Py:   (end - start).total_seconds()
来源：http://dali.tianlin.xyz/Article/details/gtzabraipn.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhixingplan.top/Article/details/gtlotfsdkm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yueranfly.top/Article/details/gtdbpagsrm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.smart0.xyz/Article/details/gtqhbzzcvm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guannengcc.top/Article/details/gtomipszbj.html

Go:   end.Sub(start).Hours()
来源：http://dali.c1oappe.top/Article/details/gtegxagmwc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dianchejie.cn/Article/details/gtnafstyls.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangtech.top/Article/details/gtezqbfahy.html

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gteugjhbgm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtclqzeklv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.quarkkingdee.top/Article/details/gtvnnqddzg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtipxcyqnq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtwwtseuqv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuxming.cn/Article/details/gtrbpsnncj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxinkj.top/Article/details/gtyyrjyccd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gttvroccca.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtfdgygyid.html

[J08] 提取年月日与星期
来源：http://dali.redwolf501.top/Article/details/gtpryjdgey.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yvedp.cn/Article/details/gtdedeybks.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gtirzoxdbc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidggrmrx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.vqdsnc.cn/Article/details/gtxchfnkzx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tianlin.xyz/Article/details/gtyuvxqzlz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fzhhl.top/Article/details/gtcxzwxgxi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zdqjudy.top/Article/details/gtninwyzut.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guowangkeji.top/Article/details/gtjixkwpqx.html

[J09] 时区处理
来源：http://dali.yangfankeji.com/Article/details/gtpzosotlb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.snrcjt.cn/Article/details/gtadfapcqf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fzhhl.top/Article/details/gtwtzvxuct.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gttrmmpxnq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtkbjtxexf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gtfktvtlzd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuanzx.com/Article/details/gtzbpaykfw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gtmqppkvyb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gogol.net.cn/Article/details/gtoztbzxmr.html

[J10] 取今天 / 本月第一天
来源：http://dali.sysykeji.top/Article/details/gtinocrbqo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gtlfqyvpvs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258.top/Article/details/gtcxqomtve.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgfzy.top/Article/details/gtfrtsdogb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj202588.top/Article/details/gtbizuvftn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.kuanghao11.cn/Article/details/gtfcuitvaq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhiwuduotai.top/Article/details/gtdixuckzh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gtgmipydvv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjivovxeb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtpfozciih.html

K. JSON 与序列化
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwavqwpr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtrpwidnvv.html

[K01] 对象转 JSON 字符串
来源：http://dali.vqdsnc.cn/Article/details/gtcgwisgev.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gtdqpoaenz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtcnjkvpye.html

JS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtxktdyrwx.html

TS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gtfrvpecdk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.havefunace.top/Article/details/gtwjbuxisu.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gtbhzwgmmd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shuidangran.top/Article/details/gtqppbqlft.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yvedp.cn/Article/details/gtlwxsrgmi.html

[K02] JSON 字符串转对象
来源：http://dali.zdqjudy.top/Article/details/gtvnjadtbu.html

Py:   json.loads(s)
来源：http://dali.yuxming.cn/Article/details/gtswowretm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhpiupnw.html

JS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtvaksxwbo.html

TS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtivpokjts.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daxiang520.top/Article/details/gtmfphrplv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gtonizrsmy.html

Ruby: JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtobmpgydf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gtlhyakvit.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangtech.top/Article/details/gtousgqswn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gtuoqwbqsv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtnmziugpz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtcpuimmog.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gtamtgxzfc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.316326.xyz/Article/details/gtoxwvqyfz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.haohaochexian.top/Article/details/gtrrnybxkx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuanzhike.top/Article/details/gtxgajortm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pycfn.com/Article/details/gtholgcjem.html

[K04] 读取 JSON 文件
来源：http://dali.chenjidiqi.icu/Article/details/gtmcvredub.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.quarkkingdee.top/Article/details/gtxymlceox.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenzaomai.com/Article/details/gtuylspujl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtkbkjcqqk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gtppifhixw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xinyue.icu/Article/details/gtoluikgqr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gtctlcpyol.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqaygeqks.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gtqbesbdfk.html

[K05] 深拷贝对象
来源：http://dali.hysaishi.cn/Article/details/gtulamaqqr.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangdashe.top/Article/details/gtjuotjwvm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gotoacloud.top/Article/details/gtozsdrqbu.html

JS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtegfuptrp.html

TS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtvbaaivbg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zycfv.cn/Article/details/gtzwddfmbl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cashguo.top/Article/details/gtuqsoqnzo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hammf.cn/Article/details/gttgzgyixp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvabtlulw.html

[K06] 解析 URL 查询串
来源：http://dali.vqdsnc.cn/Article/details/gtawqrucqy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtrnpsvlwr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.havefunace.top/Article/details/gtzaezmgbh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gtonheomqb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gtgauaafjc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gtbrbuujom.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtdyzhshqn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtmifjzryo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtapwugimt.html

[K07] 进制转换
来源：http://dali.nanxuanxn.top/Article/details/gtzbwivdzh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtkgptcvys.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gtsvdohukq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtyvtwrjas.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtblolrvre.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtbemoaqld.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ybcxt.top/Article/details/gtryzsoljd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.smart0.xyz/Article/details/gtucjfqqss.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtoenymxpg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gtmncfywok.html

Py:   pickle.dumps(obj)
来源：http://dali.hfpthk.cn/Article/details/gtxuqobcwx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtdujunqbg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gtmbtyeszc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtwkigmtvb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jiagoushi.top/Article/details/gtkxpgdhmo.html

Go:   encoding/gob
来源：http://dali.xuanzx.com/Article/details/gtmkubmsdd.html

Ruby: Marshal.dump(obj)
来源：http://dali.dianchejie.cn/Article/details/gtybzshfhc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtryflmiwb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtylqqrgww.html

L. 网络请求
来源：http://dali.birdmap.top/Article/details/gtjogdtcly.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtiuqtfmek.html

[L01] 发送 GET 请求
来源：http://dali.redwolf501.top/Article/details/gtvlwelcoq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.havefunace.top/Article/details/gtdyfxwqhd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yongpay.top/Article/details/gtwosmchdv.html

JS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gtjsunxndo.html

TS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gtvqssouqo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.9152youxi.cn/Article/details/gtrriqrpce.html


<!-- 参考信息 -->