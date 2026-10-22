代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258888.top/Article/details/gt2guvrgmgz.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gt2nylohrex.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gt2myniwbir.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gt2zypgtcdi.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gt2kdpohuor.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gt2dhymduoa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gt2lxakrhfo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gt2fthosvnk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gt2raifppjy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yvedp.cn/Article/details/gt2fkeqylnc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxuanxn.top/Article/details/gt2zycerbad.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2jlxsqihj.html

[H07] 断言
来源：http://dali.aizwys.cn/Article/details/gt2dlqourqu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nwbrower.top/Article/details/gt2yfhrqcfq.html

PHP:  assert($x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2xznhaefl.html

JS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2cldwgvyy.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2hufssort.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ivvv.top/Article/details/gt2mjiavgcp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dashuyun.cn/Article/details/gt2mrbfvpja.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jyoumei.cn/Article/details/gt2wrnaeruc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gt2zwvnyrcl.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gt2sjecdxgn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jlsjyb.cn/Article/details/gt2enlgxkhx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jlsjyb.cn/Article/details/gt2eaznedyk.html

JS:   e.message;  e.stack
来源：http://dali.daria6918.cn/Article/details/gt2ccqaoyhc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guannengcc.top/Article/details/gt2ljihqffx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fengsongda.top/Article/details/gt2ksqtszyc.html

Go:   err.Error()
来源：http://dali.zhiwuduotai.top/Article/details/gt2suecftbb.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gt2jgzwheqb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xziqi.cn/Article/details/gt2asfxznbs.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2orhmksae.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hywenlv.cn/Article/details/gt2attqfxkh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jiagoushi.top/Article/details/gt2auevgpkl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gzhubu.top/Article/details/gt2gmynutyk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gt2rhynminb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gt2qmituenl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guannengcc.top/Article/details/gt2xoetwcwl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnxiangtu.top/Article/details/gt2ixzpixfb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aibaodan.cn/Article/details/gt2sgquutxx.html

[H10] 资源自动释放
来源：http://dali.tanke756.top/Article/details/gt2klxrlilk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.316326.xyz/Article/details/gt2fbzrbttz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cashguo.top/Article/details/gt2kyihzkef.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gt2sewtsfyd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gt2gjscuxfs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xinyue.icu/Article/details/gt2nwhcbdlu.html

Go:   defer f.Close()
来源：http://dali.pycfn.com/Article/details/gt2dkbkbmtu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tanke756.top/Article/details/gt2lxmocgbv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2dgdhpefg.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2sasezvma.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2qoyfjvcm.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2qgcnymoc.html

[I01] 判断是否匹配
来源：http://dali.yj20258888.top/Article/details/gt2ceohbnpo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2etnzrsft.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2wfnytrry.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gt2dcrqrohz.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gt2pramzxvj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gt2juhbhenn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pycfn.com/Article/details/gt2lwegcdxu.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ixqprsci.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tianlin.xyz/Article/details/gt2ynjjxgqr.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2lnqdpvob.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gt2dgxzsrqs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.feifeiyinyue.top/Article/details/gt2zkonyvxi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gt2ooqlxfyb.html

TS:   s.match(/\d+/g)
来源：http://dali.svipenyu.cn/Article/details/gt2gaqqwunn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymlzvyzi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gt2hnwaaegk.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gt2owtusxtf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cheryme.top/Article/details/gt2sgbfowqu.html

[I03] 提取捕获分组
来源：http://dali.ydzc1.top/Article/details/gt2cphilufj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eaianmse.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gt2xzhyfsth.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2lppibwhm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2gszjcacc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gt2jkhdlqxe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hywenlv.cn/Article/details/gt2lvlvaidt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.bjfxy.top/Article/details/gt2xxvzydbn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fzhhl.top/Article/details/gt2uldazfop.html

[I04] 正则替换
来源：http://dali.iojbl.cn/Article/details/gt2onzdfbar.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.9152youxi.cn/Article/details/gt2wbteezhq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2vszknqlf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2bgdylczr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gt2vcgyauwy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2nwrvyaeg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cdnleiting.top/Article/details/gt2hqjdwkjo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tian-w.cn/Article/details/gt2aoxruzvv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gt2cbhwxuvz.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gt2hakhecup.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rgwkrrva.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cviknbgj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2ponmoskj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2grfpicll.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hysaishi.cn/Article/details/gt2kkhoaanz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shuidangran.top/Article/details/gt2sxhmhbdk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oitqfdes.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.haohaochexian.top/Article/details/gt2mgfyocoo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.birdmap.top/Article/details/gt2zauhkxkp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gt2jrolradd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuxming.cn/Article/details/gt2gfctpfhq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gt2arltlbpl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gt2opugimfp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gt2yzxoziqt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aizwys.cn/Article/details/gt2ayydnbak.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cdnleiting.top/Article/details/gt2rinsicsy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2xqbmovpn.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdbmbmhx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuxming.cn/Article/details/gt2izsqnuoo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gt2ivfmstpf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.iojbl.cn/Article/details/gt2fhgjkdwh.html

TS:   /error/gim
来源：http://dali.xuanzx.com/Article/details/gt2wpstinls.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gt2rpajckvm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fengsongda.top/Article/details/gt2aukyvctj.html

Ruby: s.scan(/error/i)
来源：http://dali.hfpthk.cn/Article/details/gt2czhdkmyg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxuanxn.top/Article/details/gt2piaphchs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vwvtmtvx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.smart0.xyz/Article/details/gt2zosldxwd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gt2pqdoofpo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2usthgwkz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sctbpyey.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gt2wyfeklug.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hongshengwenyu.top/Article/details/gt2jtfwgdmn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gt2hliisikj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gt2xplllpjp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2zayjwzfo.html

J. 日期与时间
来源：http://dali.meibo888.top/Article/details/gt2zaraaxdj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2thhkrkmi.html

[J01] 获取当前时间
来源：http://dali.jiagoushi.top/Article/details/gt2esxzrgwn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hywenlv.cn/Article/details/gt2bfqrvafn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gt2vbujqvik.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gt2bknnezdd.html

TS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gt2ioakhhrp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxuanxn.top/Article/details/gt2jywajoyh.html

Go:   time.Now()
来源：http://dali.yonumen.top/Article/details/gt2vfwnodqq.html

Ruby: Time.now
来源：http://dali.xylfe.cn/Article/details/gt2pbdpwpiv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hammf.cn/Article/details/gt2lumcswyr.html

[J02] 格式化输出
来源：http://dali.jinqigufen.top/Article/details/gt2fpzxgzfw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qubuqhtk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gt2xstbgxyx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hongshengwenyu.top/Article/details/gt2infxbkek.html

TS:   d.toISOString()
来源：http://dali.yj20258888.top/Article/details/gt2flembaaw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gt2wplplhhh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yrccsdok.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gt2twoyajpb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxuanxn.top/Article/details/gt2wegayfzj.html

[J03] 字符串解析为日期
来源：http://dali.xziqi.cn/Article/details/gt2axnhvxnq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gt2xdunvwpj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daxiang520.top/Article/details/gt2tocptetw.html

JS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2vxsjrlhg.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2jhzdsibk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2vwepchax.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2uiymlwju.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2hbckggww.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xziqi.cn/Article/details/gt2avaypilu.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gswdkksg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lvrjobtv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.redwolf501.top/Article/details/gt2apokjznu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gt2vouersll.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gt2dnqrqkzb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gt2croezlbe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2aloqzzkl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2gliejqhn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.c1oappe.top/Article/details/gt2dwugxkua.html

[J05] 时间加减（加 7 天）
来源：http://dali.kuanghao11.cn/Article/details/gt2rmxdhpgb.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gdegizox.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zycfv.cn/Article/details/gt2khsfbdvd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gt2hqyaacfp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gt2psufirsd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yongpay.top/Article/details/gt2xelzlemb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cdnleiting.top/Article/details/gt2bshzaems.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gt2ieascztq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuanzhike.top/Article/details/gt2edunngnb.html

[J06] 计算两时间之差
来源：http://dali.sxryk.cn/Article/details/gt2fgzwuwsk.html

Py:   (end - start).total_seconds()
来源：http://dali.zdqjudy.top/Article/details/gt2pcwacrxy.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gt2cgkodgdu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tanke756.top/Article/details/gt2sdknmekj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.kuanghao11.cn/Article/details/gt2pkwhdttm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenlongwang.top/Article/details/gt2cqprkfys.html

Go:   end.Sub(start).Hours()
来源：http://dali.shangyingyoupin.top/Article/details/gt2akeveigz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.0kj1m.cn/Article/details/gt2yhnsdbkh.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxuanxn.top/Article/details/gt2rphshhps.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gt2pmznacze.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2miobhubw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zdqjudy.top/Article/details/gt2nqlnvcea.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gt2lrsqlvnl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gt2ecwhfotu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yangfankeji.com/Article/details/gt2zgtdlhvv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rsfhremr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gt2ruhxpcak.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gt2mxfxduyf.html

[J08] 提取年月日与星期
来源：http://dali.yongpay.top/Article/details/gt2uzrwwxuo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.iojbl.cn/Article/details/gt2ihnsrnnz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dianchejie.cn/Article/details/gt2ukxiwwml.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shangyingyoupin.top/Article/details/gt2pdvnrnvd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eosvjlyo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xylfe.cn/Article/details/gt2nczagfzw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2plztoyrb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnqzz.top/Article/details/gt2ttrzeyys.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gaohongyu789.top/Article/details/gt2diamlyan.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gt2gyltlacq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenlongwang.top/Article/details/gt2hdkloidt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gzhubu.top/Article/details/gt2uffdzlzv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gt2codkbfgl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gt2amsykbfi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jyoumei.cn/Article/details/gt2edqwzsbx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ihvmhdrt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnqzz.top/Article/details/gt2sbrplawj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guannengcc.top/Article/details/gt2fmodhwof.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinghuilouyu.cn/Article/details/gt2musaydwe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.c1oappe.top/Article/details/gt2oqdjpqbd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shangyingyoupin.top/Article/details/gt2dyocpagk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zycfv.cn/Article/details/gt2yunaqahg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2rgtchvgv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gt2kwemstzn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guowangkeji.top/Article/details/gt2mbwnfmzg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gt2tbxidjch.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2whyjmzjz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ozcvhuvz.html

K. JSON 与序列化
来源：http://dali.xuanzx.com/Article/details/gt2dlsjojps.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2fgcuohol.html

[K01] 对象转 JSON 字符串
来源：http://dali.yangfankeji.com/Article/details/gt2ytimldti.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gt2jihcdojy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zkxzxevx.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gt2banhmsdi.html

TS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gt2itzdbxls.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sysykeji.top/Article/details/gt2bffnvivy.html

Go:   json.Marshal(obj)
来源：http://dali.yueranfly.top/Article/details/gt2fpsazbzs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ehwqpu.com/Article/details/gt2prgrhrbm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tian-w.cn/Article/details/gt2ojbnrquu.html

[K02] JSON 字符串转对象
来源：http://dali.xuanzx.com/Article/details/gt2tcptdjxi.html

Py:   json.loads(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2tehjgrvy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.c1oappe.top/Article/details/gt2tnfeiwcf.html

JS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gt2ztpgdlsn.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2rtfpdcyk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fhufzgwn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gt2ejrmmruy.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2nhjqqplz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zycfv.cn/Article/details/gt2hwfxppaf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cashguo.top/Article/details/gt2roigoxuh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gt2eqgilodw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gt2tlxadpfw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjilddls.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gt2evnditup.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gt2yfqftwkx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gt2zrxhdxlv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gzhubu.top/Article/details/gt2trzfktnl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gt2wzmkdtew.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zffdyxyn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2shjgnyez.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ppjwa.cn/Article/details/gt2jdlblbfu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gt2tjzawufh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gt2ftuqjand.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2negonoco.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gt2pyyglgoc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gt2fwdetpwo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wujbzpqg.html

[K05] 深拷贝对象
来源：http://dali.andypj.xyz/Article/details/gt2emjhpamk.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2dcrzfevc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhixingplan.top/Article/details/gt2ntqgbsky.html

JS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2jyeyjvnd.html

TS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gt2sybjrqds.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shzxlz.cn/Article/details/gt2ckihrvnq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yonumen.top/Article/details/gt2tkimbzzi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.0kj1m.cn/Article/details/gt2zpooehhu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.snrcjt.cn/Article/details/gt2rsygwbba.html

[K06] 解析 URL 查询串
来源：http://dali.tanke756.top/Article/details/gt2beptrdcz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gt2exeqhgbx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ppjwa.cn/Article/details/gt2dgtpvrgn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gt2dsmcpmdm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gt2ykzzinjh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xylfe.cn/Article/details/gt2wxjzgemk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gt2veopxpiy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gt2jrjvolqw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2ftgnvnbc.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gt2ybwikzwb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2wtmwsfgk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cashguo.top/Article/details/gt2hfiprzay.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2rvbohsoc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ghasoxyw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2oannncum.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yanxiufei.cn/Article/details/gt2qcgephvd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zusdkkqk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2qnqjheyd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sxryk.cn/Article/details/gt2cjfkgtxs.html

Py:   pickle.dumps(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2opyaxgae.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.0kj1m.cn/Article/details/gt2sohwbjuh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gt2kewabpmn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gt2oogvmbbw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhiwuduotai.top/Article/details/gt2vnlpspzn.html

Go:   encoding/gob
来源：http://dali.tanke756.top/Article/details/gt2cmdwqczd.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gt2mstfljxe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gt2suodmksn.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ldorvjku.html

L. 网络请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2neqqjsaq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2sxcsdnpk.html

[L01] 发送 GET 请求
来源：http://dali.daxiang520.top/Article/details/gt2zkbgalcg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.birdmap.top/Article/details/gt2iqglyais.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ydzc1.top/Article/details/gt2xxuywedv.html

JS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gt2vjldnssz.html

TS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gt2mmvlzntf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgfzy.top/Article/details/gt2zjanhsvu.html


<!-- 参考信息 -->