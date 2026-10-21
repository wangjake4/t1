代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtiubnmdye.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pengpengdd.cyou/Article/details/gtdkkzpsey.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmnisesr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtoxgcgemz.html

[H03] 主动抛出异常
来源：http://dali.hnqzz.top/Article/details/gthsimuplu.html

Py:   raise ValueError("错误信息")
来源：http://dali.xylfe.cn/Article/details/gtyysnsexv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtfixioyaj.html

JS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtbdgoejmk.html

TS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtakroflpb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtklsvaquv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tanke756.top/Article/details/gtwbuetajo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yanxiufei.cn/Article/details/gtjwdvxwks.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtjgwalvil.html

[H04] 自定义异常类型
来源：http://dali.vqdsnc.cn/Article/details/gtqgpdbcjy.html

Py:   class MyError(Exception): pass
来源：http://dali.mhx1999.top/Article/details/gtmyyuqvds.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gthtlbqzda.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gtnxmjnmqw.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtmuilupde.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtszgruwpe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.mhx1999.top/Article/details/gtoxgfrjmr.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhoulong.xyz/Article/details/gtasjwznwc.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynvckqsu.html

[H05] 捕获特定类型
来源：http://dali.havefunace.top/Article/details/gtqinjumro.html

Py:   except ValueError as e:
来源：http://dali.jlsjyb.cn/Article/details/gtucrhyvmr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenzaomai.com/Article/details/gtyoyuqagr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtaojqhzku.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtcbmqatdf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gtgsobkawg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gtforlrkvx.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gtoytiuetv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aizwys.cn/Article/details/gtpqxlggtx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenzaomai.com/Article/details/gtmwntqjsz.html

Py:   value = d.get("k") or default
来源：http://dali.ybcxt.top/Article/details/gtvaplftgz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtmaougbxf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gtsatsmdvt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gtqrklbuli.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.redwolf501.top/Article/details/gtyavgoues.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cheryme.top/Article/details/gtmnhuyfsw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.smart0.xyz/Article/details/gtthqeonwr.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtcorvqefm.html

[H07] 断言
来源：http://dali.meibo888.top/Article/details/gtngebjlgl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258888.top/Article/details/gtvlzexrxx.html

PHP:  assert($x > 0);
来源：http://dali.fengsongda.top/Article/details/gtudslnary.html

JS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtigyrlejx.html

TS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gthyyvjutk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.mhx1999.top/Article/details/gttnrvhuas.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqgauucw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ppjwa.cn/Article/details/gtulvxfvbk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtlpyfklhb.html

[H08] 获取错误信息与堆栈
来源：http://dali.xylfe.cn/Article/details/gtnwaaghun.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jyoumei.cn/Article/details/gtzhkhnmqf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.feifeiyinyue.top/Article/details/gtqldhqkun.html

JS:   e.message;  e.stack
来源：http://dali.xinyue.icu/Article/details/gtncugfhlg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dianchejie.cn/Article/details/gtcdpbgqmf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ppjwa.cn/Article/details/gtjizmsgpw.html

Go:   err.Error()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhiiywon.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhongyouzk.top/Article/details/gtrxnleriv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.kuanghao11.cn/Article/details/gtrvgbgujw.html

[H09] 带错误码的异常
来源：http://dali.hysaishi.cn/Article/details/gtnvlkbqmi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgfzy.top/Article/details/gtkeaamcsr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gtcrvhgpjf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tian-w.cn/Article/details/gtsehsorbn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigufen.top/Article/details/gtcouuwekn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.birdmap.top/Article/details/gtaxnrmsox.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nwbrower.top/Article/details/gtdsrgwovp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgufenzy.top/Article/details/gtplzrjhmm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gtkrkazwkp.html

[H10] 资源自动释放
来源：http://dali.yvedp.cn/Article/details/gtddyibnfx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hysaishi.cn/Article/details/gtjibpzjng.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guowangkeji.top/Article/details/gtbfrfugqw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebwkqxjs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gtbwntpepx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guannengcc.top/Article/details/gtlpwcslrr.html

Go:   defer f.Close()
来源：http://dali.nwbrower.top/Article/details/gtcejfyzfa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daria6918.cn/Article/details/gtsrykvhmx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258.top/Article/details/gtoxlxdicm.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtqspuhsui.html

I. 正则表达式
来源：http://dali.yj20258888.top/Article/details/gtsftqmijt.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtapyoqpdh.html

[I01] 判断是否匹配
来源：http://dali.c1oappe.top/Article/details/gtkxnqwbqv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gttaepzqjt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtinaxxnkm.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtlnlsvukm.html

TS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gttwaeeroq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.birdmap.top/Article/details/gthhxaarfg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fengsongda.top/Article/details/gtznwotrms.html

Ruby: s.match?(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gtlkruwywe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hfpthk.cn/Article/details/gtedgvdwad.html

[I02] 提取所有匹配
来源：http://dali.guowangkeji.top/Article/details/gtwmkjjlnf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gtbqfxpvsi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.redwolf501.top/Article/details/gtwyhqrkpg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yangfankeji.com/Article/details/gtrfigqiyt.html

TS:   s.match(/\d+/g)
来源：http://dali.iojbl.cn/Article/details/gtpwqzlpvb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dashuyun.cn/Article/details/gtqppkjdjv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtdsnrygzr.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gtkvkgjkyx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtwcxaxpyg.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gtkehhopvd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtifmmfjzc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zycfv.cn/Article/details/gtfwimrnco.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gtnarxjxau.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ydzc1.top/Article/details/gtckkfghgj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhoulong.xyz/Article/details/gtxuebaubg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gtlvzcnggs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258888.top/Article/details/gtcvurvagg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pengpengdd.cyou/Article/details/gturnllurw.html

[I04] 正则替换
来源：http://dali.pycfn.com/Article/details/gtorbbxskl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtxulwlkeu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gtmnafzunb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtaalsfnes.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gtvtqdogiq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gtcdgesaps.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtemynjywz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuanzhike.top/Article/details/gtzdswfcnz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gtryofdizz.html

[I05] 按正则拆分
来源：http://dali.yongpay.top/Article/details/gtcshkynax.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gtptxdcqgd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtwzholaog.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtukqlhhxv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtjasyqiaf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.snrcjt.cn/Article/details/gtbxicepyg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gtztpxrkhg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtsjqoiedu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.0kj1m.cn/Article/details/gtmvlzbphs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gtrdllizdr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtvgfypsfj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guowangkeji.top/Article/details/gtyilfabmq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gtambslynq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gtxtmkxluu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtdbailyju.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.0kj1m.cn/Article/details/gttommhcbi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.andypj.xyz/Article/details/gtnalsarzp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtrwvwnokf.html

[I07] 忽略大小写与多行模式
来源：http://dali.xinyue.icu/Article/details/gtsnpsqodo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xziqi.cn/Article/details/gtyerusdwf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gtfufxmbdf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hywenlv.cn/Article/details/gtxplyeucf.html

TS:   /error/gim
来源：http://dali.meibo888.top/Article/details/gtnngsuvbr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ehwqpu.com/Article/details/gtsvramitz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.316326.xyz/Article/details/gtpexcyrby.html

Ruby: s.scan(/error/i)
来源：http://dali.haohaochexian.top/Article/details/gtvpuaouxc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shuidangran.top/Article/details/gtqlufeowe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aizwys.cn/Article/details/gtybowimwe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yanxiufei.cn/Article/details/gtynaivvkj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gtotlyapjq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gtgsujaxga.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtuocfukjb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gteolxfkiy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hammf.cn/Article/details/gtntjuenio.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gtvaqhzxaq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gtchzhlxrg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtaflwweaq.html

J. 日期与时间
来源：http://dali.jiagoushi.top/Article/details/gtmqdjooss.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtsmckqwkg.html

[J01] 获取当前时间
来源：http://dali.yueranfly.top/Article/details/gtggtwzbfj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aibaodan.cn/Article/details/gtbhpcmhdk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtycodqnug.html

JS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirnuwfwz.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtgftsoxjh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gtqcckdzrk.html

Go:   time.Now()
来源：http://dali.nanxuanxn.top/Article/details/gtiakfvtkp.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gtsyctwcna.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenzaomai.com/Article/details/gtnreejvqx.html

[J02] 格式化输出
来源：http://dali.snrcjt.cn/Article/details/gtfycwpsxd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvofcvra.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gtxvwdiosk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gzhubu.top/Article/details/gtoffjlvsp.html

TS:   d.toISOString()
来源：http://dali.svipenyu.cn/Article/details/gtgtnsyqxf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fengsongda.top/Article/details/gtzfqdvtlc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258888.top/Article/details/gtvnmikoyv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gtiqwhboai.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gtfzyvmvxm.html

[J03] 字符串解析为日期
来源：http://dali.yangfankeji.com/Article/details/gtttbpbtor.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cucudq.cn/Article/details/gthvlpwmjv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ybcxt.top/Article/details/gtrzurnwez.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtwcqguasg.html

TS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gttgqahage.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtmhtquxoz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtedutrmlx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtvftymkfy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gtaaorqtxx.html

[J04] 时间戳与日期互转
来源：http://dali.yueranfly.top/Article/details/gtvnfojsxv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gzhubu.top/Article/details/gtfsbffhgk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pengpengdd.cyou/Article/details/gtosfrqwwp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shuidangran.top/Article/details/gtiqkeexnr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gotoacloud.top/Article/details/gtbdoumiym.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhognwkk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtcxjewlav.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yongpay.top/Article/details/gtmqkbjqsq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gogol.net.cn/Article/details/gtvczhxguz.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrymhtlg.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gtfsijztte.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuxming.cn/Article/details/gtqsdszzmf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtkopwnvkq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gtjohetapp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jiagoushi.top/Article/details/gtxiphxuux.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guannengcc.top/Article/details/gttezjitlg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jianghu66.top/Article/details/gthjqvouju.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.andypj.xyz/Article/details/gtcsoqxkoa.html

[J06] 计算两时间之差
来源：http://dali.xuetiantiany.cn/Article/details/gtyddvkodh.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigufen.top/Article/details/gthjhhhtsb.html

PHP:  $end->diff($start)->days;
来源：http://dali.yvedp.cn/Article/details/gtulbhehun.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhengqikj.top/Article/details/gtknyhcaio.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ehwqpu.com/Article/details/gtgdmwioow.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gzhubu.top/Article/details/gtmyeibgzj.html

Go:   end.Sub(start).Hours()
来源：http://dali.pycfn.com/Article/details/gtvujzxvml.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gtnpcpmfnw.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gtsuwgderk.html

[J07] 比较两个日期
来源：http://dali.zhongyouzk.top/Article/details/gtjymnqyul.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbgbmzgo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnxiangtu.top/Article/details/gtpiicluhb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gtmeiisspv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gtrsvpozng.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fzhhl.top/Article/details/gtgcuqhqgn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tianlin.xyz/Article/details/gtzzewrfzh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtwwuqfqbw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtuatnztxp.html

[J08] 提取年月日与星期
来源：http://dali.daria6918.cn/Article/details/gthnecvtxw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jiagoushi.top/Article/details/gthovtwogh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gtqpohbysg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptkpdomh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258.top/Article/details/gtkbpcosxj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yanxiufei.cn/Article/details/gtggaszgpx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guannengcc.top/Article/details/gtdyfuhyin.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.kuanghao11.cn/Article/details/gtbaecqgvo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj202588.top/Article/details/gtiyigsuvc.html

[J09] 时区处理
来源：http://dali.jinqigufen.top/Article/details/gtznhrjenn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.haohaochexian.top/Article/details/gtrgcinbuo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gtvcrsynxc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gtwhdqpuux.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtlkhfttrc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guowangkeji.top/Article/details/gtecfadwic.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenlongwang.top/Article/details/gtwwbhrxqe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hywenlv.cn/Article/details/gtfebrpxip.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gthxlaexgd.html

[J10] 取今天 / 本月第一天
来源：http://dali.yongpay.top/Article/details/gtqwfwijef.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxuanxn.top/Article/details/gtbkfecfjl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cdnleiting.top/Article/details/gtbznkbsel.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shzxlz.cn/Article/details/gtwnuavfsa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangdashe.top/Article/details/gtyvmxqatv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gtcqktsqew.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gtgdvtgdpp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.feifeiyinyue.top/Article/details/gtwuzriuuv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258888.top/Article/details/gtxthajvxg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtukivlcad.html

K. JSON 与序列化
来源：http://dali.yuanzhike.top/Article/details/gtkbuedihf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtqqhsfhth.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj202588.top/Article/details/gtibzbgsbe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtavyzlnnv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gttktusyiu.html

JS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtpbjauagt.html

TS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtmbizptjp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jianghu66.top/Article/details/gtgiseqpmy.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gturoimxey.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sweek.top/Article/details/gtkbkadeon.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.andypj.xyz/Article/details/gttdslkyoi.html

[K02] JSON 字符串转对象
来源：http://dali.feifeiyinyue.top/Article/details/gtsgaroquk.html

Py:   json.loads(s)
来源：http://dali.andypj.xyz/Article/details/gtityxsved.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cheryme.top/Article/details/gtpqgfltiy.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtihrfovhs.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtqhmcgzgy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtersmbidp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gtnqlupdyo.html

Ruby: JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtgkgbbukr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sysykeji.top/Article/details/gtunovzqka.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigfzy.top/Article/details/gtfehvjpqe.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtegzslkag.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gtwelxjnaz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gtbtglhcgr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtlbgrrwcs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jianghu66.top/Article/details/gteuqdlulx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gtzcvjomgd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldtyothp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhoulong.xyz/Article/details/gttaubltnd.html

[K04] 读取 JSON 文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdeboesp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gtjyomqtpt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenzaomai.com/Article/details/gtuizzjonk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtdbuzyagw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtqgtskwxr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtzxzcalxz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtgqhmbydj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gtdhldjcmb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtalifzsnf.html

[K05] 深拷贝对象
来源：http://dali.fengsongda.top/Article/details/gttivmeiuy.html

Py:   copy.deepcopy(obj)
来源：http://dali.sweek.top/Article/details/gtrmfuqlwf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cheryme.top/Article/details/gtpwacvoig.html

JS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtaypqkuyh.html

TS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtpgcypoka.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xziqi.cn/Article/details/gtpqnhzblx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shzxlz.cn/Article/details/gtpfbklcrk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sweek.top/Article/details/gtisrvdxis.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sufxvd.cn/Article/details/gtymsgbbhe.html

[K06] 解析 URL 查询串
来源：http://dali.cqqwz.cn/Article/details/gttikppoou.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gtcsxpdoli.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jianghu66.top/Article/details/gtmssrwrbp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtfbtzrkhv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpvxgdsy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhoulong.xyz/Article/details/gtuxbzzoot.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtdncjlifb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtzdvtonwb.html


<!-- 参考信息 -->