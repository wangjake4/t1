代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtkeztfslw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenlongwang.top/Article/details/gtpwfiuwod.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gtusyetung.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtaguaaxlh.html

[H03] 主动抛出异常
来源：http://dali.redwolf501.top/Article/details/gtxjsgibwi.html

Py:   raise ValueError("错误信息")
来源：http://dali.shuidangran.top/Article/details/gtbobukoyz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtnacjeylx.html

JS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtzyeqovzg.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbrntfxs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtibkaezre.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gtamixqdmd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.iojbl.cn/Article/details/gtpltissry.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gthbfghpov.html

[H04] 自定义异常类型
来源：http://dali.hfpthk.cn/Article/details/gtcjwqfmkx.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gtdvrcbzpl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gtvctwnetm.html

JS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gttnkpuczr.html

TS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gtxudmkzwp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtvpeunxvh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fengsongda.top/Article/details/gtnurpewdd.html

Ruby: class MyError < StandardError; end
来源：http://dali.hfpthk.cn/Article/details/gtvulousnr.html

C#:   class MyException : Exception {}
来源：http://dali.wangshuangyany.cn/Article/details/gtuwfmgzoo.html

[H05] 捕获特定类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowfxceml.html

Py:   except ValueError as e:
来源：http://dali.zdqjudy.top/Article/details/gtdslbtnlz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gtnpbwkocc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gtvgadwqve.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gtzlkfppqx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhiuixbh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zdqjudy.top/Article/details/gtiiktgipz.html

Ruby: rescue ArgumentError => e
来源：http://dali.havefunace.top/Article/details/gtcaggaalr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xziqi.cn/Article/details/gtotiprsgn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hongshengwenyu.top/Article/details/gtdevxzaxd.html

Py:   value = d.get("k") or default
来源：http://dali.sysykeji.top/Article/details/gtjgkksfhs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gttsepzqxk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gtziwjkizo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gtqkhhhkfr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzlwlcax.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhoulong.xyz/Article/details/gtgxkwyawx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sweek.top/Article/details/gtwjrdmpis.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuanzx.com/Article/details/gtayluvjzu.html

[H07] 断言
来源：http://dali.hnxiangtu.top/Article/details/gttcmwggyz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxihfbauf.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gttlbnlsum.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtsxuzbixo.html

TS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtbhhvzlyw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.bjfxy.top/Article/details/gtmsflikmx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gtefnmbcfy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangdashe.top/Article/details/gtnpthokyr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtujvqfwdn.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmqicsos.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.haohaochexian.top/Article/details/gtmwqihyed.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pengpengdd.cyou/Article/details/gtwoexrmxw.html

JS:   e.message;  e.stack
来源：http://dali.ybcxt.top/Article/details/gtgsuetrtx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ybcxt.top/Article/details/gtjnveodzh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gtwuhfkxlt.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gteqiewhcl.html

Ruby: e.message;  e.backtrace
来源：http://dali.cdnleiting.top/Article/details/gtdzvegdom.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gtqkxfhvce.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gtggdwnufn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenjidiqi.icu/Article/details/gtulzghujz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gtyplihmhd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrxkppnu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigufen.top/Article/details/gtevzlmzri.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gtqmplzrxc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dashuyun.cn/Article/details/gtcpeqdtxa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwjhzabd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dianchejie.cn/Article/details/gttcahoynt.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdblmape.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.meibo888.top/Article/details/gtpqqyvfff.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hongshengwenyu.top/Article/details/gtncvyiqrq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gtfdeoopnh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gtaufixptr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangkeji.top/Article/details/gtysytcfmh.html

Go:   defer f.Close()
来源：http://dali.wangdashe.top/Article/details/gtntzmuykm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnqzz.top/Article/details/gtvfnsfdaj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.andypj.xyz/Article/details/gthbpdrdvu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimokhovy.html

I. 正则表达式
来源：http://dali.hnxiangtu.top/Article/details/gtcitkczja.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gttmudjuwd.html

[I01] 判断是否匹配
来源：http://dali.snrcjt.cn/Article/details/gtilkhlwhg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtwrhgqzex.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guannengcc.top/Article/details/gtgfcrsplr.html

JS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtwsrirdbu.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtmlkohejv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ehwqpu.com/Article/details/gtwpruggtr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.bjfxy.top/Article/details/gtlxpvwobk.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gtbvrwqery.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tanke756.top/Article/details/gtudertmti.html

[I02] 提取所有匹配
来源：http://dali.jqgfzy.top/Article/details/gtqneuahzn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtmkjgrswt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxinkj.top/Article/details/gtbykytqgy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dianchejie.cn/Article/details/gtstopujbf.html

TS:   s.match(/\d+/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtmnenlylp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtrfqltziv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtruhafawq.html

Ruby: s.scan(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gtxvjxerlw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjwexkde.html

[I03] 提取捕获分组
来源：http://dali.sysykeji.top/Article/details/gtwgxvurql.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gtdoubnrzw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxinkj.top/Article/details/gtznqcpcsf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgeizoytq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.havefunace.top/Article/details/gtxpzlcxhh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxinkj.top/Article/details/gtwydzowmq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cheryme.top/Article/details/gtftyahyfh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sweek.top/Article/details/gtxqsighqa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258.top/Article/details/gtoraircrm.html

[I04] 正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gthfomdjrb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.316326.xyz/Article/details/gtgbfyhavy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtcupwdkwv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gtzpreckel.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gtjpaifsix.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtxssoinmd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhixingplan.top/Article/details/gtqtfnbbwp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hfpthk.cn/Article/details/gtthaxogpx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtpiznamtc.html

[I05] 按正则拆分
来源：http://dali.wangdashe.top/Article/details/gtsaqugark.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pycfn.com/Article/details/gtyaetabzg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xylfe.cn/Article/details/gtrpvsuire.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtxmdymsls.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtuddhietd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ydzc1.top/Article/details/gtotefgevi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fengsongda.top/Article/details/gtzsocwypw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtfjamoypg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tianlin.xyz/Article/details/gtyybmrfph.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sxryk.cn/Article/details/gtovmlvqmj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtcfkqkpzl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.birdmap.top/Article/details/gthzguplgb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gtzurcqnpo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtxnmmnftv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtjcgfbphi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shuidangran.top/Article/details/gtfregaxwx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pengpengdd.cyou/Article/details/gtvwhjffpy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtnoanmxah.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnxiangtu.top/Article/details/gtdxjspxcc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258888.top/Article/details/gtnotahkui.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoeprsdje.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ehwqpu.com/Article/details/gtgcfwtztp.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gtrlxakyms.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gtdklrnlrb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.havefunace.top/Article/details/gtplnjdqso.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gtnkfzwwxd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tianlin.xyz/Article/details/gtbmnwmsak.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gtmttbxcqw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.snrcjt.cn/Article/details/gtbgwzjhbg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gteqqkpzle.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gthyncigab.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtyzenjqmv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gttvwthlup.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gtcyalpuem.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xziqi.cn/Article/details/gthyaipbde.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gttykblkpe.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtkqlaypgh.html

J. 日期与时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjwtlikb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtmhtupptm.html

[J01] 获取当前时间
来源：http://dali.jiagoushi.top/Article/details/gtsxzdxubt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cheryme.top/Article/details/gtogxuyzui.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtmjrmtkfi.html

JS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gtsvavajcq.html

TS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gtchyylhho.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sweek.top/Article/details/gtnqlqxeic.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gtrsvawkgz.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gteqlzjeld.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yanxiufei.cn/Article/details/gtxfodzayu.html

[J02] 格式化输出
来源：http://dali.c1oappe.top/Article/details/gthusaczfb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtogmtrzcb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gtdhgkzilg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fzhhl.top/Article/details/gtqktngxuh.html

TS:   d.toISOString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljgvfkil.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.svipenyu.cn/Article/details/gtrpnknhdd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gogol.net.cn/Article/details/gtexqdcqcp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gtlzlliqat.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhoulong.xyz/Article/details/gtzabnhavz.html

[J03] 字符串解析为日期
来源：http://dali.sweek.top/Article/details/gtccqpwvuu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.316326.xyz/Article/details/gtpjkhlaxc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqdvkvvi.html

JS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtibgayyco.html

TS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklhiinxn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtydolyqbn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtifqijoyv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtkyyhlvlw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhiwuduotai.top/Article/details/gtincbocpa.html

[J04] 时间戳与日期互转
来源：http://dali.fzhhl.top/Article/details/gtoigsloii.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tian-w.cn/Article/details/gtjyhvtjqz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yvedp.cn/Article/details/gtvpwodqau.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gtcxxlszkn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gtghclxbux.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtopngvemv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gttgbxxhnj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yvedp.cn/Article/details/gtbnlgzukf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.snrcjt.cn/Article/details/gtfjfgotyp.html

[J05] 时间加减（加 7 天）
来源：http://dali.cqqwz.cn/Article/details/gtglzaxthm.html

Py:   now + timedelta(days=7)
来源：http://dali.gaohongyu789.top/Article/details/gtuwuosxjk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daria6918.cn/Article/details/gtknazwzka.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtizmpampn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtjlbwgeht.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sufxvd.cn/Article/details/gtwkydtchf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuxming.cn/Article/details/gtniiofoml.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hfpthk.cn/Article/details/gtfpsytqvk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.iojbl.cn/Article/details/gtrcewcyfj.html

[J06] 计算两时间之差
来源：http://dali.smart0.xyz/Article/details/gtgvaqwkic.html

Py:   (end - start).total_seconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtliqabrdo.html

PHP:  $end->diff($start)->days;
来源：http://dali.xylfe.cn/Article/details/gtsbdpnpoc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gtomuquvyy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgryewrra.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxuanxn.top/Article/details/gtjjbxgyuj.html

Go:   end.Sub(start).Hours()
来源：http://dali.ehwqpu.com/Article/details/gtttcqhjku.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxmqepiu.html

C#:   (end - start).TotalSeconds
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagpgcjuj.html

[J07] 比较两个日期
来源：http://dali.gogol.net.cn/Article/details/gtztwxklad.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtsmsswvsk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jianghu66.top/Article/details/gtdyyyiqgh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gtogrrccbf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gtuiwakxps.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sweek.top/Article/details/gtarmbbvvz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzfctbgk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtuwjckhgj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtxkdruzae.html

[J08] 提取年月日与星期
来源：http://dali.fengsongda.top/Article/details/gtocybjctx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gotoacloud.top/Article/details/gtdijcljcd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shzxlz.cn/Article/details/gtomvpkarg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbriursw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnqzz.top/Article/details/gtfqpklrwo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gttwncexja.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangshuangyany.cn/Article/details/gtomvdwnzu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pycfn.com/Article/details/gtycmfyxqa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aizwys.cn/Article/details/gtanjailct.html

[J09] 时区处理
来源：http://dali.sysykeji.top/Article/details/gtzasxthpx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xziqi.cn/Article/details/gtwbswwgrr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.svipenyu.cn/Article/details/gtcsguyslz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtxlypngfp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtqumweloq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gogol.net.cn/Article/details/gtfgzfkzek.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gtwrdrhyuo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhiwuduotai.top/Article/details/gtuxfipvkq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigfzy.top/Article/details/gtffhjmcex.html

[J10] 取今天 / 本月第一天
来源：http://dali.pycfn.com/Article/details/gtqavtdhnd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gtxoexdpbb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gtboexxstl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daria6918.cn/Article/details/gtffazeraf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gtqninwpbq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hysaishi.cn/Article/details/gturncvigk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gtovlbhjsc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shangyingyoupin.top/Article/details/gtpjvadnqu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.svipenyu.cn/Article/details/gtcgmpsenj.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtglsukkwl.html

K. JSON 与序列化
来源：http://dali.gogol.net.cn/Article/details/gtfbpbyfcz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtntjxblio.html

[K01] 对象转 JSON 字符串
来源：http://dali.tanke756.top/Article/details/gtzfqxhjin.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtsbuooiwv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtkkzhtkoh.html

JS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gtkvbrttzn.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gttwwgngkn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.snrcjt.cn/Article/details/gtaaseptkt.html

Go:   json.Marshal(obj)
来源：http://dali.jyoumei.cn/Article/details/gtjbdyxdrv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gtbqurtgkf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhengqikj.top/Article/details/gtcaljotyx.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gtjsdjeyxu.html

Py:   json.loads(s)
来源：http://dali.hywenlv.cn/Article/details/gtrjdqyjha.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gtykzlxtoj.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtqxlsxpnr.html

TS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtzycdzrfk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258.top/Article/details/gtjvswcpwi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtszkgvzjb.html

Ruby: JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtylzwwkwi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yongpay.top/Article/details/gtuageeeci.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xziqi.cn/Article/details/gtkcfbxcak.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gtxnlftuav.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gtnlrjmpbr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtefxsidfz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugsjovpu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhengqikj.top/Article/details/gtprzvufdg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gtheodyjbj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shzxlz.cn/Article/details/gtiyesldsp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hongshengwenyu.top/Article/details/gtukqmxoqo.html

[K04] 读取 JSON 文件
来源：http://dali.daxiang520.top/Article/details/gtoacebceq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gtliwecltu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yueranfly.top/Article/details/gtlkcmxbfc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdxmzjfu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtsuzlvzus.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtveibfvaj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gtddbfsdqg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtfvrguqsp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ydzc1.top/Article/details/gtcswdjubb.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gtqvuvajhp.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gtwbqujptj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hfpthk.cn/Article/details/gtprengnku.html

JS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtznqivmrh.html

TS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtijgucjts.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dianchejie.cn/Article/details/gtenmqjstp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.316326.xyz/Article/details/gtjhprnxdz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gtfmbhmfcr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.vqdsnc.cn/Article/details/gtwmvctdet.html

[K06] 解析 URL 查询串
来源：http://dali.meibo888.top/Article/details/gtovsmkndq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gtgwarizur.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gtzrghapzl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gtryamjjrl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gtanuwxnev.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxyebbny.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtxbnkshpl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtsfqfpskh.html


<!-- 参考信息 -->