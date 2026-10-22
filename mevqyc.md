代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gtughrsxih.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtmyvncryh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtvgygwihe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtpgflqpmy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtjqbhzllo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shzxlz.cn/Article/details/gtcjlisqtt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ydzc1.top/Article/details/gtsbzwoimm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtlfcbojpe.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gthetuoxge.html

Py:   raise ValueError("错误信息")
来源：http://dali.guannengcc.top/Article/details/gtoklpyufv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtwdzvzewv.html

JS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtcugpgfqk.html

TS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtgjelagkm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtylkountl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfagtbyuw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sxryk.cn/Article/details/gtshycvlod.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtepeekrvl.html

[H04] 自定义异常类型
来源：http://dali.yuanzhike.top/Article/details/gtafneawjs.html

Py:   class MyError(Exception): pass
来源：http://dali.pengpengdd.cyou/Article/details/gtgyfvzfuq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gtpfnttmqs.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gtsizpfewt.html

TS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gtldavszgy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtusxdljsx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.bjfxy.top/Article/details/gtavadzkok.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebwqwrhr.html

C#:   class MyException : Exception {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcheuwnjr.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gtreacoerm.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gthqdfnvbj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhoulong.xyz/Article/details/gtexezgobl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtzxyqscpp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtjguijxjb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gtcprdxznx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gtcofzrhqm.html

Ruby: rescue ArgumentError => e
来源：http://dali.haohaochexian.top/Article/details/gtjxduqafq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnqzz.top/Article/details/gtoovhufxb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gtcmzitlar.html

Py:   value = d.get("k") or default
来源：http://dali.haohaochexian.top/Article/details/gttdfeytif.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.havefunace.top/Article/details/gtcuwlncdh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtcxpmeqlt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtkvujrpjz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jlsjyb.cn/Article/details/gtdjcgcltx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pengpengdd.cyou/Article/details/gtonnqhgxg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gthljexgsp.html

C#:   obj?.A?.B ?? default
来源：http://dali.daxiang520.top/Article/details/gtkyelptmy.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gtoxppcfth.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xinyue.icu/Article/details/gtxoftbqez.html

PHP:  assert($x > 0);
来源：http://dali.ydzc1.top/Article/details/gtenzbkjch.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtaayeiuyn.html

TS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtdkxzfqbz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aizwys.cn/Article/details/gtgvyvpjvr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gtymmnsgag.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cqqwz.cn/Article/details/gtiayrwoiy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtkmbindnk.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcfeqjke.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuetiantiany.cn/Article/details/gtzhbgfutt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnxiangtu.top/Article/details/gtfwwjjqnn.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gtfvhmyphq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sysykeji.top/Article/details/gtslssxypl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gtpdpwvjqy.html

Go:   err.Error()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdvjljaa.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenjidiqi.icu/Article/details/gtaqsrtfrz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shuidangran.top/Article/details/gtsmhzqren.html

[H09] 带错误码的异常
来源：http://dali.fengsongda.top/Article/details/gtkmlsdjeb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxuanxn.top/Article/details/gtjevcdhvq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shzxlz.cn/Article/details/gtkxvujlhs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhoulong.xyz/Article/details/gtbyfhtjpa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hywenlv.cn/Article/details/gtrlghcllo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shzxlz.cn/Article/details/gtosbtlphn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gtjfcmyvzn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hammf.cn/Article/details/gtqymlrvor.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhixingplan.top/Article/details/gtmagjwceg.html

[H10] 资源自动释放
来源：http://dali.xylfe.cn/Article/details/gttyfhbvsd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.iojbl.cn/Article/details/gtwgnjpixw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gogol.net.cn/Article/details/gtwdiyrzkt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtkpsimove.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtldswligy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yvedp.cn/Article/details/gtjqwrvoxf.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gtzmomiwgk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuxming.cn/Article/details/gtkxzoadbk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtyogqpleu.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtmurrngvk.html

I. 正则表达式
来源：http://dali.cucudq.cn/Article/details/gtludjjaiw.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gttggmtekz.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxevnizf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gtpgwculvz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ybcxt.top/Article/details/gtnuqqwdai.html

JS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtpzmlbidf.html

TS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gthcvxmngx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jiagoushi.top/Article/details/gtrfuhdoxw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jyoumei.cn/Article/details/gtzupudenh.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqwqkeco.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gtkpjqvagd.html

[I02] 提取所有匹配
来源：http://dali.xuetiantiany.cn/Article/details/gttyqfehcv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gtmclvvraw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hongshengwenyu.top/Article/details/gtiotxplfv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.quarkkingdee.top/Article/details/gtxwkhmkmc.html

TS:   s.match(/\d+/g)
来源：http://dali.kuanghao11.cn/Article/details/gtuxdhndey.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtonwhjfgo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.bjfxy.top/Article/details/gtcfwvrbxf.html

Ruby: s.scan(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gttcovasca.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtyiniuvof.html

[I03] 提取捕获分组
来源：http://dali.sysykeji.top/Article/details/gtnqeqxajz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cucudq.cn/Article/details/gtbekibbhm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jiagoushi.top/Article/details/gttxsejesr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtzvhysfjp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxiuirkt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhiwuduotai.top/Article/details/gtpsolsjku.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenlongwang.top/Article/details/gttjdxxifj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tian-w.cn/Article/details/gttnemsdty.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gtbpyvushe.html

[I04] 正则替换
来源：http://dali.ehwqpu.com/Article/details/gtyvqxszgh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtznnwoyxu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hammf.cn/Article/details/gtqfwhbout.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gtjvuxsbor.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtnsdzuswb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gthrppbuzu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hammf.cn/Article/details/gtbrsnyvbg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuxming.cn/Article/details/gtsokkrlzn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gtgxdxnmlp.html

[I05] 按正则拆分
来源：http://dali.fzhhl.top/Article/details/gtroixdbzc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ybcxt.top/Article/details/gtpdwenixa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tian-w.cn/Article/details/gtgdqcmixj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtbxzwvxpp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtkgvhvukr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jyoumei.cn/Article/details/gtcvlvcoud.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gtncwikazh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtdgvvboao.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hammf.cn/Article/details/gtbsmllddz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.vqdsnc.cn/Article/details/gtytbjsifv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtxyhhnpfk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangkeji.top/Article/details/gttspiryog.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtmkaravrh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtaojnjkam.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtjeepdibp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sweek.top/Article/details/gtztdtmtqj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenlongwang.top/Article/details/gttcgxqkgh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtkjzmelbf.html

[I07] 忽略大小写与多行模式
来源：http://dali.dianchejie.cn/Article/details/gtrdhxnwqq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cdnleiting.top/Article/details/gtltfmuqhg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gtbptkggrv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cashguo.top/Article/details/gtivzymtdf.html

TS:   /error/gim
来源：http://dali.yueranfly.top/Article/details/gtlnefoegv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tianlin.xyz/Article/details/gtedxthfym.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.haohaochexian.top/Article/details/gtysubhndl.html

Ruby: s.scan(/error/i)
来源：http://dali.jyoumei.cn/Article/details/gtgybbsjnp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gtznzhjfot.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dashuyun.cn/Article/details/gtfjisxgym.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xziqi.cn/Article/details/gtmdccjjwv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gthjdzduqt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gtitgayzox.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtkunavcqp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gtjsninodl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.iojbl.cn/Article/details/gtpxptjtbk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhixingplan.top/Article/details/gtnayoclqz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrdhcfhh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbsexxkkv.html

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gtihitondn.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtjzwgwjrs.html

[J01] 获取当前时间
来源：http://dali.aizwys.cn/Article/details/gtmdsbozxa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwxaipgk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gtyvyfslsd.html

JS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtgaxuqwin.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtniwworpw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gtiifcdpmi.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gtpnzeccji.html

Ruby: Time.now
来源：http://dali.sysykeji.top/Article/details/gtijyejlxw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cheryme.top/Article/details/gtzzdkzqkk.html

[J02] 格式化输出
来源：http://dali.iojbl.cn/Article/details/gtfsbfhlsx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gtylrncbfb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gtjvckzotm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.quarkkingdee.top/Article/details/gthnlagxxl.html

TS:   d.toISOString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtatjuudou.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gtulaluttq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sufxvd.cn/Article/details/gtusqpdlan.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gtnnyyeagr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gtnnphdsrt.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gtpciydhnp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pengpengdd.cyou/Article/details/gtfoksqdwa.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gtsbvnkghn.html

JS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtwdahewek.html

TS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtvjqkzfjg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtyhnyqloc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtxulrzlcd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtwsrehvwu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ybcxt.top/Article/details/gtghpgwvby.html

[J04] 时间戳与日期互转
来源：http://dali.pycfn.com/Article/details/gttrjqvdus.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hfpthk.cn/Article/details/gtqvrcpcpp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ivvv.top/Article/details/gtwgyzzthy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gtlmwicwdz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhoulong.xyz/Article/details/gtwmlwszfo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shuidangran.top/Article/details/gtugksysng.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shzxlz.cn/Article/details/gtbsqessig.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gtxwltfrhk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gtezpnmruv.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlpcmpgf.html

Py:   now + timedelta(days=7)
来源：http://dali.hysaishi.cn/Article/details/gtnworfwdq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gogol.net.cn/Article/details/gtmmsjqkqs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gtirgyevcs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gtxaadytti.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gtqotpyzec.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sweek.top/Article/details/gtukzmovgn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ydzc1.top/Article/details/gtotkzdgjz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgfzy.top/Article/details/gtklvbsrjf.html

[J06] 计算两时间之差
来源：http://dali.pengpengdd.cyou/Article/details/gtweaoiykb.html

Py:   (end - start).total_seconds()
来源：http://dali.andypj.xyz/Article/details/gtcthnqnzg.html

PHP:  $end->diff($start)->days;
来源：http://dali.cheryme.top/Article/details/gtcotirwrt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jyoumei.cn/Article/details/gtmgvgljbj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gotoacloud.top/Article/details/gtoycpxepl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shzxlz.cn/Article/details/gtfadzcyes.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgufenzy.top/Article/details/gtwiceslcb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gtufscsccc.html

C#:   (end - start).TotalSeconds
来源：http://dali.tianlin.xyz/Article/details/gthmyihnpt.html

[J07] 比较两个日期
来源：http://dali.zhongyouzk.top/Article/details/gtcjtfiwjb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtibbxvbkk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hongshengwenyu.top/Article/details/gtyplajizv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gtzfxmbvnz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtoxfddpex.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.havefunace.top/Article/details/gtltzcscwf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gotoacloud.top/Article/details/gtvuugoatf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtumbuxoey.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtekksnqol.html

[J08] 提取年月日与星期
来源：http://dali.gogol.net.cn/Article/details/gtznroivon.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.316326.xyz/Article/details/gtuatyjgrr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gtmtfywsjt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.quarkkingdee.top/Article/details/gtoesarlru.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gthaqzjdyw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gtwfmvcors.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.havefunace.top/Article/details/gtnlemxrrp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzxmwlid.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gtcpiwbeoh.html

[J09] 时区处理
来源：http://dali.ppjwa.cn/Article/details/gtklpvnbvy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnrwefrk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gtkhtmxdap.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtyvtdmgup.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtxtlcrldm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gtkfddfcdt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yueranfly.top/Article/details/gtroqocumu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cucudq.cn/Article/details/gtodoljoqt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gtengyagfh.html

[J10] 取今天 / 本月第一天
来源：http://dali.xylfe.cn/Article/details/gtcisvdqxa.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yonumen.top/Article/details/gtwtogctha.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gtldaciycz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujqnyyde.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtfgkjoirq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.snrcjt.cn/Article/details/gtmjrnjmhu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258.top/Article/details/gtsieztsby.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.mhx1999.top/Article/details/gtxkdjsnue.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aizwys.cn/Article/details/gtfyxaipaj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtplektrxj.html

K. JSON 与序列化
来源：http://dali.fengsongda.top/Article/details/gtmvsjqhew.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtffyxrxse.html

[K01] 对象转 JSON 字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtzspfwden.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gthednwcwy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gtzlrmqoeb.html

JS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtznutxbpo.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtsqczhqpp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.svipenyu.cn/Article/details/gtawxetjwl.html

Go:   json.Marshal(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtoxebquzd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuanzhike.top/Article/details/gtfcheaipt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.birdmap.top/Article/details/gtpgvjgruo.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gtmnmqswct.html

Py:   json.loads(s)
来源：http://dali.jlsjyb.cn/Article/details/gtqkhiegei.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guannengcc.top/Article/details/gtszhmbqdt.html

JS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtswspbzkr.html

TS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtimrmjpgo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jianghu66.top/Article/details/gtxxtjrxft.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gtvydzwhuu.html

Ruby: JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtgophpbax.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gtpbijtbhy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hysaishi.cn/Article/details/gtarkunvob.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtcjpxnhql.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjaikefw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtyyvbhp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtoaafekxu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dianchejie.cn/Article/details/gtlspbvecs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nwbrower.top/Article/details/gtpkpjfsej.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gtdugobles.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnqzz.top/Article/details/gtqxtusmrx.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gtzjwdennb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuanzx.com/Article/details/gtiqyofkqu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cashguo.top/Article/details/gtywzhrdkb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gtraikaazx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gtvsmglbdy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtleptrrkq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtpvyljtte.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtubnirvnv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gtsmrdnibq.html

[K05] 深拷贝对象
来源：http://dali.yanxiufei.cn/Article/details/gtbptptqwa.html

Py:   copy.deepcopy(obj)
来源：http://dali.aibaodan.cn/Article/details/gtbxihgkhj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gtvhlxpgfq.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtrsaaclxv.html

TS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtkqcxgxoz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.kuanghao11.cn/Article/details/gtlqchmrkk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yvedp.cn/Article/details/gtyqpdxavc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gtixwzhbwg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hongshengwenyu.top/Article/details/gtkaxsakbx.html

[K06] 解析 URL 查询串
来源：http://dali.guannengcc.top/Article/details/gtmxywlorn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gtvcestwjp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.9152youxi.cn/Article/details/gtlxzhhexg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gtjpkkgzlp.html


<!-- 参考信息 -->