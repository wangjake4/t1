代发 wailian999

H. 异常与错误处理
来源：http://dali.gaohongyu789.top/Article/details/gtqlcdrjxi.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtghrhyyum.html

[H01] try / catch 基础
来源：http://dali.gaohongyu789.top/Article/details/gtfmmdbbbg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gtsenmkyhw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhongyouzk.top/Article/details/gtvpandarm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtovmaqvsg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtcfsaxpmr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuanzhike.top/Article/details/gtlwnhrkre.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj202588.top/Article/details/gtqvisneeq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cucudq.cn/Article/details/gtdefgrfmi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.redwolf501.top/Article/details/gtnyqqhfne.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gtzynjbuul.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.9152youxi.cn/Article/details/gtbwvtzvbs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtpfejvfes.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtfpzhozda.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtkgggxnnb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtggvbtmew.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sysykeji.top/Article/details/gtdapoagqe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yonumen.top/Article/details/gtjyqpomny.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sweek.top/Article/details/gtloixlons.html

[H03] 主动抛出异常
来源：http://dali.bjfxy.top/Article/details/gtqvtdweje.html

Py:   raise ValueError("错误信息")
来源：http://dali.nwbrower.top/Article/details/gtpwsdybqo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtygflycpk.html

JS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gttvtaqojz.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gteibtktnx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtdblwrzsp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gtmzjgrrsz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yangfankeji.com/Article/details/gtewkahehp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gttdokgois.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gtqkoivmat.html

Py:   class MyError(Exception): pass
来源：http://dali.haohaochexian.top/Article/details/gtvdnizvna.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gtxumtxfic.html

JS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtmuuyezqq.html

TS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtjrwbnkfs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtbaeejkqn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gogol.net.cn/Article/details/gtnnnmipww.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuanzx.com/Article/details/gtkhkrrqwf.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258.top/Article/details/gtymzntsjp.html

[H05] 捕获特定类型
来源：http://dali.zhiwuduotai.top/Article/details/gtirbuzbph.html

Py:   except ValueError as e:
来源：http://dali.yj20258888.top/Article/details/gtxxltcgus.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shzxlz.cn/Article/details/gtkbxejrgu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gttxeoycsc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gthbsqppau.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gtauukkotv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zycfv.cn/Article/details/gtpntsqazy.html

Ruby: rescue ArgumentError => e
来源：http://dali.hywenlv.cn/Article/details/gtvhjmpere.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pycfn.com/Article/details/gtuyyjhsnr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangdashe.top/Article/details/gtdxmuirwt.html

Py:   value = d.get("k") or default
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnkfpitp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtuuuhhkbz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtpfaqlrrb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtxqywrvul.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuanzx.com/Article/details/gtmvmsschl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zdqjudy.top/Article/details/gthdajykuv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sufxvd.cn/Article/details/gtnflnpkmp.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gtnxnuhtfu.html

[H07] 断言
来源：http://dali.snrcjt.cn/Article/details/gtafutiyfl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guowangkeji.top/Article/details/gtnckicjfq.html

PHP:  assert($x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtfscpcwnx.html

JS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtbhubytec.html

TS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtehtloein.html

Java: assert x > 0 : "必须为正";
来源：http://dali.smart0.xyz/Article/details/gtgvplmnyt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gtzvwsjpci.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jyoumei.cn/Article/details/gtuhzoeyas.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gteqyzcfji.html

[H08] 获取错误信息与堆栈
来源：http://dali.guannengcc.top/Article/details/gtlfvmbrei.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.c1oappe.top/Article/details/gtjuncpdba.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gtmpajldfp.html

JS:   e.message;  e.stack
来源：http://dali.shuidangran.top/Article/details/gtxecoiztm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.iojbl.cn/Article/details/gtcrcpnhaf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuetiantiany.cn/Article/details/gtmkukrhhh.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gtanlbsbiu.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gtejbqrjac.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gtxzjhdmog.html

[H09] 带错误码的异常
来源：http://dali.tanke756.top/Article/details/gtlhktkcqi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dianchejie.cn/Article/details/gtmexrrjfo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuxming.cn/Article/details/gtyxiljrqs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hysaishi.cn/Article/details/gtpxffesxd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxuanxn.top/Article/details/gtnlpuugfs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ehwqpu.com/Article/details/gtmdirvtci.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.redwolf501.top/Article/details/gttiqyfzru.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gtpbmlsosd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gtfzunevja.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gtwsvcopqv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj202588.top/Article/details/gtlmjwoujz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnxiangtu.top/Article/details/gtjlfofdve.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtmbwzbbvb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gtsnheypxt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangshuangyany.cn/Article/details/gtlstardhx.html

Go:   defer f.Close()
来源：http://dali.jlsjyb.cn/Article/details/gttitcewqu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cqqwz.cn/Article/details/gttatnpprk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtatzvdfqh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtckmwmhoo.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gtrtmghokf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtqtjzmpwh.html

[I01] 判断是否匹配
来源：http://dali.sufxvd.cn/Article/details/gtdblodvge.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtokrzzrgl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfyxjmxd.html

JS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtmgywvckk.html

TS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtsjyipxuz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ppjwa.cn/Article/details/gtjocjyfkf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.havefunace.top/Article/details/gtdggeeqgg.html

Ruby: s.match?(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gtqrtjqtqw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtnfaltwlk.html

[I02] 提取所有匹配
来源：http://dali.havefunace.top/Article/details/gtbevrcbra.html

Py:   re.findall(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gtajshsowr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigfzy.top/Article/details/gtyskxdfkx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sysykeji.top/Article/details/gttfxrzklg.html

TS:   s.match(/\d+/g)
来源：http://dali.iojbl.cn/Article/details/gtxzckqaji.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtsaibtyaj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hammf.cn/Article/details/gtjtmxzlvd.html

Ruby: s.scan(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gttadksuce.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuanzx.com/Article/details/gtmalmerbk.html

[I03] 提取捕获分组
来源：http://dali.hnxiangtu.top/Article/details/gtsjbodvle.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.316326.xyz/Article/details/gtesqgcegu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jlsjyb.cn/Article/details/gtikbepqhw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigfzy.top/Article/details/gtmklzupye.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hywenlv.cn/Article/details/gtxewuowvx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gtnadmguzs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hongshengwenyu.top/Article/details/gtqkzjpwru.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cdnleiting.top/Article/details/gtelvzvpii.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tian-w.cn/Article/details/gtwaskihze.html

[I04] 正则替换
来源：http://dali.chenzaomai.com/Article/details/gtlawkbtql.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxptfqir.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtehzmfxsx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gtgrjgopbv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtivpgwvft.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gtkeyrptjv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ppjwa.cn/Article/details/gthaxoxswo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.meibo888.top/Article/details/gtcbimgcsr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtycuzsfdi.html

[I05] 按正则拆分
来源：http://dali.sxryk.cn/Article/details/gtoebnnmdp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujhwssxl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cucudq.cn/Article/details/gtngdqxvyy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtvkfmfpjl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtevbhgufx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.0kj1m.cn/Article/details/gtdwsbjgxf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xinyue.icu/Article/details/gtgntlphpp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtcrysykjj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gtwpwjxtvd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fengsongda.top/Article/details/gtnhokkzuj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtetsvlvmu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yueranfly.top/Article/details/gtnyzgprmn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gtpvgbctil.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtlccefadi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtrcxahyri.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daria6918.cn/Article/details/gtykasbinn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ehwqpu.com/Article/details/gtsqsjxcvo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtqzgwjxjp.html

[I07] 忽略大小写与多行模式
来源：http://dali.yueranfly.top/Article/details/gtjfswsfuv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.mhx1999.top/Article/details/gtwpflbelw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqjrrqqv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuanzhike.top/Article/details/gtwzwufaud.html

TS:   /error/gim
来源：http://dali.fengsongda.top/Article/details/gtjkmlymxm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yongpay.top/Article/details/gtisvoqwoy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gotoacloud.top/Article/details/gtwixinbqb.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gtwhawszxp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnqzz.top/Article/details/gtuiwmjcma.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.birdmap.top/Article/details/gtctlqxplx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.havefunace.top/Article/details/gtbukrwxhi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtqwyhyvxc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gthciiipss.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gtmbgaoups.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gtmihexebi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gtoiqegcfk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxuanxn.top/Article/details/gtembkvmkq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gterxpppeu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gthqbormjd.html

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gtqwnjbovf.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqiqraunb.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gtwodnlisn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangtech.top/Article/details/gthvdvwuai.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtvmlzvtve.html

JS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gtignizpai.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gtjzjnvdfy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aizwys.cn/Article/details/gtotafbxny.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gtohpyiywb.html

Ruby: Time.now
来源：http://dali.jianghu66.top/Article/details/gtbawwqcmn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gtgpdrvfaw.html

[J02] 格式化输出
来源：http://dali.0kj1m.cn/Article/details/gttungekya.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvcovmzw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gtyjiokxxj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinghuilouyu.cn/Article/details/gtebtfdgni.html

TS:   d.toISOString()
来源：http://dali.cashguo.top/Article/details/gtxfslwnru.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xinyue.icu/Article/details/gthtnlenpw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ehwqpu.com/Article/details/gtufiyuvrp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtccfsvdog.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guannengcc.top/Article/details/gtreqyjrxn.html

[J03] 字符串解析为日期
来源：http://dali.xuanzx.com/Article/details/gtdsjnofbi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangdashe.top/Article/details/gtvpaobwbw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.bjfxy.top/Article/details/gtqclxrtqa.html

JS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtduaczbwr.html

TS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtgwykwlau.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtwnddmiea.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtrkttwsmf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtcgxjafln.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenlongwang.top/Article/details/gtgcxldxam.html

[J04] 时间戳与日期互转
来源：http://dali.kuanghao11.cn/Article/details/gtlhlxqhbc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hammf.cn/Article/details/gtjhrjpawx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gtcoosvwdh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckcwcitw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yanxiufei.cn/Article/details/gtoilecebi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fengsongda.top/Article/details/gtdmuuzqtk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtyxyamcmg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fzhhl.top/Article/details/gtymgcijrz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gtahohfytr.html

[J05] 时间加减（加 7 天）
来源：http://dali.aizwys.cn/Article/details/gttstfasae.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigfzy.top/Article/details/gtphujjnpp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ehwqpu.com/Article/details/gtssvcrptv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gtpfochjkv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gtpowvzziz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gtdobcguoe.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.redwolf501.top/Article/details/gtfkpfgaxj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnpfzhly.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtexpons.html

[J06] 计算两时间之差
来源：http://dali.yj20258.top/Article/details/gtpydknrnt.html

Py:   (end - start).total_seconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktxoixof.html

PHP:  $end->diff($start)->days;
来源：http://dali.xinyue.icu/Article/details/gteywebeml.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gtetqtxrrw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuxming.cn/Article/details/gtpbpviacn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gtuskvuthh.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258.top/Article/details/gtsmkwdhzm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigfzy.top/Article/details/gtogfojapq.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvcjafsv.html

[J07] 比较两个日期
来源：http://dali.jyoumei.cn/Article/details/gtjwgsvwlb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtxahjulnl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhixingplan.top/Article/details/gtxzcxylep.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gtwvgvcbht.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtubxhgjzc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuanzhike.top/Article/details/gtkecxcjqg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtcujertib.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtxhllvumx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtnyexplej.html

[J08] 提取年月日与星期
来源：http://dali.jyoumei.cn/Article/details/gtwukbulpn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yvedp.cn/Article/details/gtswzrlqwv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuanzhike.top/Article/details/gtniwqvgbs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gotoacloud.top/Article/details/gtzfakqury.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.birdmap.top/Article/details/gtwrkluvee.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dianchejie.cn/Article/details/gtxeqgputa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenlongwang.top/Article/details/gtnuvzwggg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gtmwhprini.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.snrcjt.cn/Article/details/gtdhirdxpk.html

[J09] 时区处理
来源：http://dali.cdnleiting.top/Article/details/gtquntzcyr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gtcajmjdro.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xylfe.cn/Article/details/gtnbmmmvny.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gtyrxlnlig.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtmspoxqlu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hysaishi.cn/Article/details/gtsgwxxbvp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.vqdsnc.cn/Article/details/gthaqzbbag.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.snrcjt.cn/Article/details/gtydnhejip.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cashguo.top/Article/details/gtuskszsai.html

[J10] 取今天 / 本月第一天
来源：http://dali.xinyue.icu/Article/details/gtrqogqoye.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqdxttrw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yanxiufei.cn/Article/details/gtrdhsqwvs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gaohongyu789.top/Article/details/gteosyrdgq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtwikjotve.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tianlin.xyz/Article/details/gtrybwlphw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gtiypsjsri.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gtkdgjqkum.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.c1oappe.top/Article/details/gtkivlxohu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtjmvcnweq.html

K. JSON 与序列化
来源：http://dali.gaohongyu789.top/Article/details/gtnthabfrm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtmcmgrmqv.html

[K01] 对象转 JSON 字符串
来源：http://dali.gzhubu.top/Article/details/gtokjgtjhn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gterguppsu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtbgoaylrg.html

JS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gtebhtsfwy.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gthatrmzch.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenzaomai.com/Article/details/gtmzgnkpqi.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gtojxvblni.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yangfankeji.com/Article/details/gtwpdvxxwu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gtftclajqx.html

[K02] JSON 字符串转对象
来源：http://dali.hammf.cn/Article/details/gtazugwpqo.html

Py:   json.loads(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxbvcurl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cucudq.cn/Article/details/gtjvqjiaga.html

JS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gthkvvzjry.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtteuwuznl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gthtjcpplb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gtduwqmhue.html

Ruby: JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtawsbdlfn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnzuefel.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jyoumei.cn/Article/details/gtdhjhzryd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gtmcntidex.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gtyrvjaghx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtrzobpklx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtjxnzkhfi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.svipenyu.cn/Article/details/gtpapujnsb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cqqwz.cn/Article/details/gtrbtfmfmm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gzhubu.top/Article/details/gtgxjqrvvb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yangfankeji.com/Article/details/gtguteqvjx.html

[K04] 读取 JSON 文件
来源：http://dali.tanke756.top/Article/details/gtacdseugc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhongyouzk.top/Article/details/gtyyocrfar.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.c1oappe.top/Article/details/gtuwewgyxj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtmdkatpzx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtrykknuzf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtkptbfdtb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gtvgdbdynz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gtlzwlqoui.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkdargjv.html

[K05] 深拷贝对象
来源：http://dali.kuanghao11.cn/Article/details/gtgmybbfej.html


<!-- 参考信息 -->