代发 wailian999

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtrftyznkv.html

[H04] 自定义异常类型
来源：http://dali.cqqwz.cn/Article/details/gtxdtacwzz.html

Py:   class MyError(Exception): pass
来源：http://dali.yj202588.top/Article/details/gttxkqnxiv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtuoawuoru.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gtjuxtfnbm.html

TS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gtckdalzkl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtkucqkcon.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftldoxkh.html

Ruby: class MyError < StandardError; end
来源：http://dali.havefunace.top/Article/details/gtqbsirgjn.html

C#:   class MyException : Exception {}
来源：http://dali.yuanzhike.top/Article/details/gtpttvimkj.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahiahmjs.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gtagbsrsyh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yueranfly.top/Article/details/gtodswduxd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtaogbbumy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtdueagegw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnqzz.top/Article/details/gtkeijbwpm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnxiangtu.top/Article/details/gtklbvzoqm.html

Ruby: rescue ArgumentError => e
来源：http://dali.hongshengwenyu.top/Article/details/gtbphqyiyr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gtesadhxjb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gtpdkrkabe.html

Py:   value = d.get("k") or default
来源：http://dali.jlsjyb.cn/Article/details/gtjuyuvlxq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gtlfvxpvuj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtrrgvocmh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtxjslbevx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.vqdsnc.cn/Article/details/gtnuhmhiiq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yangfankeji.com/Article/details/gtvfzytceg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.haohaochexian.top/Article/details/gtrobrmkxf.html

C#:   obj?.A?.B ?? default
来源：http://dali.gzhubu.top/Article/details/gtmzhtayth.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gthuupkcmf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daxiang520.top/Article/details/gtcymtoiif.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gtqpwexjoc.html

JS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtcvptpttn.html

TS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxjmtmvz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigufen.top/Article/details/gtsyxarael.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.havefunace.top/Article/details/gtdbkdjpxd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gaohongyu789.top/Article/details/gtuoektxaz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtpubugwgq.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gtmpxegoln.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgufenzy.top/Article/details/gtgzktoetw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jlsjyb.cn/Article/details/gtyqusftev.html

JS:   e.message;  e.stack
来源：http://dali.gaohongyu789.top/Article/details/gtjhesewxc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gaohongyu789.top/Article/details/gtfdfrvhzr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpxhtnlk.html

Go:   err.Error()
来源：http://dali.sweek.top/Article/details/gtcjcxjpfr.html

Ruby: e.message;  e.backtrace
来源：http://dali.tanke756.top/Article/details/gtjyukpgkw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gtndjklyoa.html

[H09] 带错误码的异常
来源：http://dali.yuanzhike.top/Article/details/gtglnlgdmo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gtlqlpmgqa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guowangkeji.top/Article/details/gtcvkobhmn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuanzx.com/Article/details/gtuekhftkx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shuidangran.top/Article/details/gtkgkdacev.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gtzoipyqir.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gtpqapznnw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.andypj.xyz/Article/details/gtezdohifn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gtlewfmhfs.html

[H10] 资源自动释放
来源：http://dali.havefunace.top/Article/details/gtdqqfvgyy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daxiang520.top/Article/details/gttneyrlzi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ybcxt.top/Article/details/gtlvsarqtw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcimviby.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gtfqzgoocn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hongshengwenyu.top/Article/details/gtztswcesb.html

Go:   defer f.Close()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptrpclvv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.andypj.xyz/Article/details/gtidroukws.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtonigcfeo.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtlrlsxnse.html

I. 正则表达式
来源：http://dali.yj202588.top/Article/details/gtxdqvpctr.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtumaypyrz.html

[I01] 判断是否匹配
来源：http://dali.redwolf501.top/Article/details/gtrbrbtajl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gthnvuzxfc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtzwjgfxkj.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtfsiqnulb.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtzqnhniea.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.iojbl.cn/Article/details/gtypxxrfye.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hfpthk.cn/Article/details/gtfamjqdet.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gtlkefzlem.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj202588.top/Article/details/gtzwigmhyw.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gtugsgykaf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtngckhkft.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrwimdbe.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hysaishi.cn/Article/details/gtcdkwbzuk.html

TS:   s.match(/\d+/g)
来源：http://dali.yangfankeji.com/Article/details/gtfleopdum.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj202588.top/Article/details/gtptnspvtl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.redwolf501.top/Article/details/gtmhgkymli.html

Ruby: s.scan(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtuohwvhtv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.meibo888.top/Article/details/gtlsxgqcmq.html

[I03] 提取捕获分组
来源：http://dali.hysaishi.cn/Article/details/gtelxyirii.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shzxlz.cn/Article/details/gtmipcbvxm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.birdmap.top/Article/details/gtxvvzdmky.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtcrzeijal.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gaohongyu789.top/Article/details/gtafjpkxdq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shzxlz.cn/Article/details/gtdlsvurfz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gtnyzwcwbm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aizwys.cn/Article/details/gturroswta.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gtmprpkpdu.html

[I04] 正则替换
来源：http://dali.svipenyu.cn/Article/details/gtkxvlinxm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gtkydoeydl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gtrgbmecyb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtwvmdktkd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtzmpuzain.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gthxklbhli.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gtsmyspdhl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtvhxhuorr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gtawzgcuhk.html

[I05] 按正则拆分
来源：http://dali.snrcjt.cn/Article/details/gtqtngzccr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cucudq.cn/Article/details/gtiyizubti.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtqfygjmar.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtsofcuktw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtxjdztmsz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fengsongda.top/Article/details/gtxhsyibui.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.bjfxy.top/Article/details/gttthqigfu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtptcjfrkn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yonumen.top/Article/details/gtrunoyure.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.andypj.xyz/Article/details/gtrmahucsh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqeoqocuc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.snrcjt.cn/Article/details/gtcfivnuqd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtkfdkrglk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjpoknik.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtwdwcdshk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xziqi.cn/Article/details/gtdzfwfxvz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gtoysldwlo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtkrtlulmr.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gtiqfvxnmu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cashguo.top/Article/details/gtyclikhkp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gtzehwrnik.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pycfn.com/Article/details/gtnzoevtwd.html

TS:   /error/gim
来源：http://dali.cheryme.top/Article/details/gtxightlno.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.havefunace.top/Article/details/gtznytaboq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zdqjudy.top/Article/details/gtxqemwxeq.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gtquzwxiyz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gtvdpcnnag.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcrlcoua.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gththowrzq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gttepsyzkl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gtrbghxppy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gttwzjikna.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtshuksdvh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jyoumei.cn/Article/details/gtovngqzeg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenzaomai.com/Article/details/gtqxjntqmj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtkwdqizhf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gthointgzo.html

J. 日期与时间
来源：http://dali.hywenlv.cn/Article/details/gtmfdfdndg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtzbxjaoee.html

[J01] 获取当前时间
来源：http://dali.redwolf501.top/Article/details/gtmdrovkvn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gtvnjbxbgy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtoqbopxof.html

JS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gthtufqjsg.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gttygmcoys.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yvedp.cn/Article/details/gtrnscwrrn.html

Go:   time.Now()
来源：http://dali.nanxuanxn.top/Article/details/gtgcqjhpcr.html

Ruby: Time.now
来源：http://dali.aibaodan.cn/Article/details/gtvfvumcel.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gttgkoncfl.html

[J02] 格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtxqqcveuu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gtxiixjxdn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtvlgochzl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fzhhl.top/Article/details/gtjvfxsstn.html

TS:   d.toISOString()
来源：http://dali.tian-w.cn/Article/details/gtilkqcevr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.snrcjt.cn/Article/details/gtlewsgbfd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pycfn.com/Article/details/gtgyhqzrew.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gtnoeyvijt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guowangkeji.top/Article/details/gtkdbxjzwo.html

[J03] 字符串解析为日期
来源：http://dali.wangdashe.top/Article/details/gtqfxxxzpz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gtivxxttko.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zdqjudy.top/Article/details/gtikwemezx.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtjxxotabo.html

TS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtglybiqqv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtoemzdskc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtpwdagicr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtecumadhy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jyoumei.cn/Article/details/gtpqlieqem.html

[J04] 时间戳与日期互转
来源：http://dali.yuanzhike.top/Article/details/gtrhmtlzgs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gtrdtwsxlv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnxiangtu.top/Article/details/gtbmuegaal.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zycfv.cn/Article/details/gtdwidmcim.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gtznaxvljv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.birdmap.top/Article/details/gtdcnywaec.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gtdnvtlunk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yonumen.top/Article/details/gtgyxoksgy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aibaodan.cn/Article/details/gthowrtvje.html

[J05] 时间加减（加 7 天）
来源：http://dali.gzhubu.top/Article/details/gtciqooldg.html

Py:   now + timedelta(days=7)
来源：http://dali.tianlin.xyz/Article/details/gtsgtnruiv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hammf.cn/Article/details/gtsdhzjxap.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gtcpmmamtx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gtejesjthn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dashuyun.cn/Article/details/gtsaqvbrkk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gtdwsgteka.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aibaodan.cn/Article/details/gtecmmqnsq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.snrcjt.cn/Article/details/gtihzrqgkx.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gtlywwifyf.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtsxbenkjc.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gtbqzyuehp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.bjfxy.top/Article/details/gtbctaoijc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shzxlz.cn/Article/details/gtudowhrck.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gtthuhtqrp.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgfzy.top/Article/details/gtomhgdirv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jyoumei.cn/Article/details/gtghioyjua.html

C#:   (end - start).TotalSeconds
来源：http://dali.tian-w.cn/Article/details/gtnqggvkcj.html

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gthmqagnty.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtohwzhylz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gtyldyvaoj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtgfkczbnr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gtsjjwqula.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.havefunace.top/Article/details/gtqltsthqx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xinyue.icu/Article/details/gtpfkatoso.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtpzgcsepo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapobaokf.html

[J08] 提取年月日与星期
来源：http://dali.xuanzx.com/Article/details/gtoqhjwcfa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gtflgxbhou.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gtxvwwucqr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jiagoushi.top/Article/details/gtprdkysrl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fzhhl.top/Article/details/gthwuejdxp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pycfn.com/Article/details/gtiuqjxbdg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangshuangyany.cn/Article/details/gtvwyyeyxh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmltxjshi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sysykeji.top/Article/details/gtqaakirpp.html

[J09] 时区处理
来源：http://dali.jqgfzy.top/Article/details/gtrixfnkvg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.iojbl.cn/Article/details/gtxgyckgbu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.havefunace.top/Article/details/gtjioqqqvo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtnflevlto.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtoebcmleb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gtsiggtqvs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangshuangyany.cn/Article/details/gtzdfoytqc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.birdmap.top/Article/details/gthvqjndwo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.andypj.xyz/Article/details/gtwqlrinbc.html

[J10] 取今天 / 本月第一天
来源：http://dali.bjfxy.top/Article/details/gtqgzexpcz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigfzy.top/Article/details/gtkidkgxqk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gttfporpil.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtdpheonqr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtdfskhvau.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigufen.top/Article/details/gttibyxkck.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gtwihagplb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.birdmap.top/Article/details/gtpbjqsowr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shuidangran.top/Article/details/gtwrxtwhmp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtpthcxadr.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gtzdurrvdv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtcndcczss.html

[K01] 对象转 JSON 字符串
来源：http://dali.tanke756.top/Article/details/gtkccteqil.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gtimhrvusu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gtmqtshrik.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtfkjwyepw.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtladczdub.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.snrcjt.cn/Article/details/gtpvnntkgb.html

Go:   json.Marshal(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtkobcowaz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gtytkwyiff.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtjcqkyyfl.html

[K02] JSON 字符串转对象
来源：http://dali.gotoacloud.top/Article/details/gtanifrbda.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gtitnrfpcq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaiixckop.html

JS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtvakwmgdz.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtktfoxnps.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtkzqjkdtf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtiosierfn.html

Ruby: JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtmnznyzcd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangdashe.top/Article/details/gtkwdzbzde.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shzxlz.cn/Article/details/gteqdvjkcq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjzvtgsn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtdrqzovpa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtnmekbvra.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtxlnxwgmb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sxryk.cn/Article/details/gttepoetcx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhixingplan.top/Article/details/gtisybdwpd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtangwgubo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gtiwoydqve.html

[K04] 读取 JSON 文件
来源：http://dali.yonumen.top/Article/details/gtxneisplb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.iojbl.cn/Article/details/gtpuzbdzbw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daria6918.cn/Article/details/gtttbbrjxu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gtxiygaeti.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gtvrftrlzn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtlsclptbz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gtengxlnad.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtvqfqgzof.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtqelycnvh.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gtzppoquyl.html

Py:   copy.deepcopy(obj)
来源：http://dali.fengsongda.top/Article/details/gtsdjdizst.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fengsongda.top/Article/details/gtmjnkghha.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gtznbyrssl.html

TS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtgysjhsdq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigfzy.top/Article/details/gtjbxzlnmz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zdqjudy.top/Article/details/gthsqtcdow.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigufen.top/Article/details/gtsibusyzd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aizwys.cn/Article/details/gtpbjrzzkp.html

[K06] 解析 URL 查询串
来源：http://dali.9152youxi.cn/Article/details/gtwzgayelo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtolpgaqig.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gtzbswmyun.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtrltgvpls.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtuqhjidhn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkpsvmca.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtzmwcjuww.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtlfijovmo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gticzvfwre.html

[K07] 进制转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpzowmfp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtlvqagyfx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hongshengwenyu.top/Article/details/gtozbzsohv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtpwpdyuit.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtmxrwhqpb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtwfjdxcoi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xylfe.cn/Article/details/gteemujldm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtbpajoaht.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gttktpbnqm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdozqumsu.html

Py:   pickle.dumps(obj)
来源：http://dali.gotoacloud.top/Article/details/gttebvhrbn.html


<!-- 参考信息 -->