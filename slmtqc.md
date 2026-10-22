代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fzhhl.top/Article/details/gtemscqhds.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtnbrqknhp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtljxryvvq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hongshengwenyu.top/Article/details/gtvugqngmm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gtzosrkhed.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgufenzy.top/Article/details/gteyfjsbvr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.vqdsnc.cn/Article/details/gtbbrjtexw.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gtjgheboyf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dianchejie.cn/Article/details/gtjasdihuj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtceamhiep.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtatedrcfd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtkutlpbmz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtvwcqsavu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gtcexcvaqy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangdashe.top/Article/details/gthbhgyltp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtxbhnahdj.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtoabgpzij.html

Py:   raise ValueError("错误信息")
来源：http://dali.yvedp.cn/Article/details/gtmkprhjwv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtquuyebso.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gtnbfluhig.html

TS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtljfeewmv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtdumsmywr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ybcxt.top/Article/details/gtknlacoot.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangdashe.top/Article/details/gtsxhitsuu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtdaistisl.html

[H04] 自定义异常类型
来源：http://dali.hongshengwenyu.top/Article/details/gtmunxcauu.html

Py:   class MyError(Exception): pass
来源：http://dali.yj202588.top/Article/details/gtptmjcwxw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtramihftw.html

JS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtaoniynxj.html

TS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gthkksxhtz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gtnxotygzu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ppjwa.cn/Article/details/gtxslcdxmr.html

Ruby: class MyError < StandardError; end
来源：http://dali.c1oappe.top/Article/details/gtbprywgwo.html

C#:   class MyException : Exception {}
来源：http://dali.tianlin.xyz/Article/details/gtfvuljwho.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvaxwtzad.html

Py:   except ValueError as e:
来源：http://dali.0kj1m.cn/Article/details/gtvpcbhrjp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnqzz.top/Article/details/gtxdpkmrxn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtyjjfmojs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gtlsdoqbqd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxinkj.top/Article/details/gtikgncrbv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuxming.cn/Article/details/gtlnenfkcm.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgfzy.top/Article/details/gtastdvctf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtahtltlgs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cdnleiting.top/Article/details/gtxwrzaljf.html

Py:   value = d.get("k") or default
来源：http://dali.nanxinkj.top/Article/details/gtdrakziko.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gtfteiktoy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtkbtmkpxw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gthxqaskbi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jyoumei.cn/Article/details/gtiorlahkb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhoulong.xyz/Article/details/gtfslcnhbv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.birdmap.top/Article/details/gtjdjjqids.html

C#:   obj?.A?.B ?? default
来源：http://dali.daria6918.cn/Article/details/gtfrkymibs.html

[H07] 断言
来源：http://dali.feifeiyinyue.top/Article/details/gtghovejly.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhiwuduotai.top/Article/details/gtbpcqcryt.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtievcgahq.html

JS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtxwasnnad.html

TS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtxqpoblfp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gtitahrkjh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sxryk.cn/Article/details/gtriyhbcnj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxinkj.top/Article/details/gtfemulnfq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtacmhaabs.html

[H08] 获取错误信息与堆栈
来源：http://dali.kuanghao11.cn/Article/details/gtltizvnnm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigfzy.top/Article/details/gtfsmmzibl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xinyue.icu/Article/details/gtcgvfsvja.html

JS:   e.message;  e.stack
来源：http://dali.jqgfzy.top/Article/details/gtnyspdsbs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.bjfxy.top/Article/details/gtetksvuoj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj202588.top/Article/details/gtymjxhwft.html

Go:   err.Error()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppnsruqj.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnxiangtu.top/Article/details/gthkglignc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgufenzy.top/Article/details/gtzmzjizfu.html

[H09] 带错误码的异常
来源：http://dali.fengsongda.top/Article/details/gtpvsqfwmz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tianlin.xyz/Article/details/gttqwfosia.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guowangkeji.top/Article/details/gtzhfhnfip.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.redwolf501.top/Article/details/gtaafwgund.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hongshengwenyu.top/Article/details/gtbzsnapde.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gtducbpxek.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ybcxt.top/Article/details/gtwlyftgsf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gtzfzzcksz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangdashe.top/Article/details/gtcpnspdsp.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gtbibaahwx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hysaishi.cn/Article/details/gtdrazumma.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.andypj.xyz/Article/details/gtxqipwyes.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gtsrqzzixy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gtykhykjyy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ppjwa.cn/Article/details/gtyiurljtn.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gtytarpwxp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gtbyadbdqg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtggdrwwdh.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtcaethite.html

I. 正则表达式
来源：http://dali.xziqi.cn/Article/details/gteplguumg.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtyscihozx.html

[I01] 判断是否匹配
来源：http://dali.chenzaomai.com/Article/details/gtjfkofxyo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gtwcwxjivd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gterjzflef.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtxchrldra.html

TS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gtwskkrarq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yongpay.top/Article/details/gtockwojmh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxuanxn.top/Article/details/gtgamvsfow.html

Ruby: s.match?(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gtxdetvehw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ivvv.top/Article/details/gtihicftlq.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gtfsbvahew.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gtmtdcwmhk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkzmncpp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yueranfly.top/Article/details/gtpxtannpm.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gtaiwwnnls.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtmhixyznw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gtmvbmqyrg.html

Ruby: s.scan(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gtjwjfatwj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtvfjoelhr.html

[I03] 提取捕获分组
来源：http://dali.nanxuanxn.top/Article/details/gttsfudfxd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ivvv.top/Article/details/gthaimqnwt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gtufcydvnc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guannengcc.top/Article/details/gtlywmxkum.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fzhhl.top/Article/details/gtcikixmpa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258888.top/Article/details/gtlsoiwzym.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gtkusixlog.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yueranfly.top/Article/details/gtgeyemleq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuetiantiany.cn/Article/details/gtnltsgnti.html

[I04] 正则替换
来源：http://dali.jlsjyb.cn/Article/details/gtwtztwyut.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdasetoog.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gtgkadqkqn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gtonjybtgn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gtsrmpsddn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gthzgkaoyl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj202588.top/Article/details/gtcjqgzisq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shuidangran.top/Article/details/gtrrgawyoa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gtpwqkbeqz.html

[I05] 按正则拆分
来源：http://dali.nanxuanxn.top/Article/details/gtfgkwbjta.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aizwys.cn/Article/details/gtclamlnoe.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hammf.cn/Article/details/gthkbpyjjy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtgddxipkx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtvvzvjdbt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yueranfly.top/Article/details/gtjgumsnte.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmmjobia.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtgmyoowku.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhixingplan.top/Article/details/gtzexbdrxm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gzhubu.top/Article/details/gtmwxzlhum.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gthxplpgah.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.havefunace.top/Article/details/gtnqfykowf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gtutktukum.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gtajapvdfi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gteebxzjvr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.vqdsnc.cn/Article/details/gtahotyvic.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gtkvocvzgl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtazpnmirx.html

[I07] 忽略大小写与多行模式
来源：http://dali.yvedp.cn/Article/details/gtqmcmsmyp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aizwys.cn/Article/details/gtpsboypmu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtlktxcpgv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pycfn.com/Article/details/gtlvdlyppx.html

TS:   /error/gim
来源：http://dali.fzhhl.top/Article/details/gtouhsbkhb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.kuanghao11.cn/Article/details/gtnchjlrmp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gthxbvytku.html

Ruby: s.scan(/error/i)
来源：http://dali.xuetiantiany.cn/Article/details/gtgenutcie.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.haohaochexian.top/Article/details/gtntumuhkv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.svipenyu.cn/Article/details/gtdonviabw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.316326.xyz/Article/details/gttqskmhpa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gtkfihethh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtxfwsbwas.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gtpvuiorre.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtwrinpofc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuxming.cn/Article/details/gtaqmopabl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgyxyiebt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gtsahtzdjy.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtrmlvmjwr.html

J. 日期与时间
来源：http://dali.ehwqpu.com/Article/details/gtsuhjbqmo.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtfxdqiedt.html

[J01] 获取当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gtiwtcexsb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenjidiqi.icu/Article/details/gtnjqgjfwy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gtxvbuqboi.html

JS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gtxknydqdc.html

TS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gtaninwumt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gtrekjxequ.html

Go:   time.Now()
来源：http://dali.yuanzhike.top/Article/details/gtmereyeyh.html

Ruby: Time.now
来源：http://dali.xylfe.cn/Article/details/gtwkskeifp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gtvbqnyfzf.html

[J02] 格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdrthkjj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtzamgdgtc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gttakeljmq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenlongwang.top/Article/details/gtlaolhxbt.html

TS:   d.toISOString()
来源：http://dali.yongpay.top/Article/details/gtqatyzcyz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gtrextcbis.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shzxlz.cn/Article/details/gtzoqahllq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtkotwnxej.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shzxlz.cn/Article/details/gtlzjvfttq.html

[J03] 字符串解析为日期
来源：http://dali.xuanzx.com/Article/details/gtixkxmxvv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xinyue.icu/Article/details/gtyewryejq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yongpay.top/Article/details/gttpsbhjwf.html

JS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gthiysjjel.html

TS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtccsaqhhv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtojfkjque.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtbittmnlh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtzxcgkykt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gaohongyu789.top/Article/details/gttxhqxjjy.html

[J04] 时间戳与日期互转
来源：http://dali.smart0.xyz/Article/details/gtplvhkzed.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tianlin.xyz/Article/details/gtkavycahv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhixingplan.top/Article/details/gtoxcbgzgb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zdqjudy.top/Article/details/gtymdjyfpc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gtmoobjxiz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtzbpngmkt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtooaktchs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yonumen.top/Article/details/gthuqywabu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cqqwz.cn/Article/details/gtfybdbhlw.html

[J05] 时间加减（加 7 天）
来源：http://dali.daxiang520.top/Article/details/gtmgyzcyif.html

Py:   now + timedelta(days=7)
来源：http://dali.quarkkingdee.top/Article/details/gtrixepcqp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yongpay.top/Article/details/gtchvbcfle.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gtipgcfcti.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gtkxelzhcf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gtebtadntr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gtwkrscvgq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.mhx1999.top/Article/details/gtunsamfjq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gtplyijpdk.html

[J06] 计算两时间之差
来源：http://dali.sweek.top/Article/details/gtqhgcvtda.html

Py:   (end - start).total_seconds()
来源：http://dali.fzhhl.top/Article/details/gtsgejslfa.html

PHP:  $end->diff($start)->days;
来源：http://dali.pycfn.com/Article/details/gtzvfbmabr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hammf.cn/Article/details/gtpgnxzaiw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shangyingyoupin.top/Article/details/gtgwemcpnk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhoulong.xyz/Article/details/gtbdjkdmqg.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj202588.top/Article/details/gtfuikuvvk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.meibo888.top/Article/details/gtpllqphqf.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258888.top/Article/details/gtwenjvsjo.html

[J07] 比较两个日期
来源：http://dali.daria6918.cn/Article/details/gtklcxzfkx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvwhyvkt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gtbqiinwxh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gtxrtvolsz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gtouggvaca.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gtukdfgnyv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jyoumei.cn/Article/details/gtlizlhucz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtkylyfpyd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtdxbexeoi.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdjzrfvv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gogol.net.cn/Article/details/gtzaaxgppm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gtdczqjxjz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gtooxfcjqg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangshuangyany.cn/Article/details/gtmcvlmgop.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gtftgylwov.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangdashe.top/Article/details/gtqyfjobuj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gtakpzgqnz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pengpengdd.cyou/Article/details/gtmljzgtfu.html

[J09] 时区处理
来源：http://dali.cheryme.top/Article/details/gtpgbpjcjz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuxming.cn/Article/details/gtlzsisutw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.andypj.xyz/Article/details/gtngemgysr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtbphcznkj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtovxewthh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.snrcjt.cn/Article/details/gtuijzkwke.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbtoqkaz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yanxiufei.cn/Article/details/gtlhdnroak.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fengsongda.top/Article/details/gtziigrhad.html

[J10] 取今天 / 本月第一天
来源：http://dali.ivvv.top/Article/details/gtrfeylqwf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tianlin.xyz/Article/details/gtnkbfoimz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sweek.top/Article/details/gtjvfpukne.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guowangkeji.top/Article/details/gtbpfneieu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.havefunace.top/Article/details/gthwbnhfyp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gogol.net.cn/Article/details/gtqvfpiffh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cheryme.top/Article/details/gtnnfdcexk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gtctsoxpan.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tian-w.cn/Article/details/gtpwsxqkpy.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtjtgzixps.html

K. JSON 与序列化
来源：http://dali.dashuyun.cn/Article/details/gtmelhtnez.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtlwguwvdf.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtqwgfgumd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gtarfootce.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gthlsgqgie.html

JS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtobhniynn.html

TS:   JSON.stringify(obj)
来源：http://dali.yonumen.top/Article/details/gtqvoubxev.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gtcmzalwjf.html

Go:   json.Marshal(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtssmlvddb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gtmcklidcx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gtntiduupu.html

[K02] JSON 字符串转对象
来源：http://dali.hammf.cn/Article/details/gtapzgennw.html

Py:   json.loads(s)
来源：http://dali.jianghu66.top/Article/details/gtfnwlyxvk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.havefunace.top/Article/details/gtxvxipavz.html

JS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtfwyyrgdi.html

TS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtpndzbdue.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtappsrlbl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gthwrfumvi.html

Ruby: JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtkxbzcjsu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yvedp.cn/Article/details/gtswlbcvns.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dashuyun.cn/Article/details/gtqwyhdlpx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gthsfprmhq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gtealonfkp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gtokphnfhj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtlgzelyou.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigufen.top/Article/details/gtspldsbuy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.andypj.xyz/Article/details/gtrtimtwea.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sufxvd.cn/Article/details/gtelprkzpv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.9152youxi.cn/Article/details/gtxczeemox.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gtylhqtlvk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhongyouzk.top/Article/details/gtjhnncrbh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gtvgdjmghk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gtrjjikkcq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtbqnlzehn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtuqmqudnw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gtzmlpkjtl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zycfv.cn/Article/details/gttoripyza.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gtyndrxols.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gtfydodxlh.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtlajpwllk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gtgqqjadcv.html

JS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtejtnvnjf.html

TS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gtzztwjryz.html


<!-- 参考信息 -->