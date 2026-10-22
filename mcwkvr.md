代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sxryk.cn/Article/details/gtxgjxaulw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtnderyblm.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnxiangtu.top/Article/details/gtjowsbcsd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.vqdsnc.cn/Article/details/gtmggmtaro.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gtuyqmxkbi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gtyxxlhreg.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxuanxn.top/Article/details/gtwhhtphtr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gogol.net.cn/Article/details/gtejjpgssq.html

PHP:  get_object_vars($obj);
来源：http://dali.guowangkeji.top/Article/details/gtuffggtig.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtfnqoemlb.html

TS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtgbyrcemu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gtpmghopzt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shzxlz.cn/Article/details/gtlxmyydty.html

Ruby: obj.instance_variables
来源：http://dali.xziqi.cn/Article/details/gtepeeyphj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtomfdmwdf.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtjozezwsr.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gtmicckekw.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtqicgsyky.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gtbbowsuli.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.redwolf501.top/Article/details/gtamwhxhkr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ehwqpu.com/Article/details/gtcvlpjjpm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtsfxtstkw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gtpodevwrj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigfzy.top/Article/details/gtaooqtzlr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gteojdxiim.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xziqi.cn/Article/details/gtutvaptss.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cqqwz.cn/Article/details/gtrncunqrw.html

[H02] finally / ensure 收尾
来源：http://dali.daria6918.cn/Article/details/gtnyrdyywd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gaohongyu789.top/Article/details/gtbrpzcsdo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtjpgdpiyn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtgmvnnedn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtohcjgant.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtkwthizyv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gtknplasxq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zdqjudy.top/Article/details/gtxtymanqc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtiokjtuzf.html

[H03] 主动抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtucuasfot.html

Py:   raise ValueError("错误信息")
来源：http://dali.iojbl.cn/Article/details/gttoljbawe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtshjklwwr.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtnuxemdum.html

TS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtomthwlvk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtvxenrruy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shzxlz.cn/Article/details/gturfwqfmh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gtoaoowfbd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gteaxngxmo.html

[H04] 自定义异常类型
来源：http://dali.cdnleiting.top/Article/details/gtqjjidkyo.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtxfytkyky.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzaysvxec.html

JS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtrnxbijfj.html

TS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gthikeuyep.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtnkjqdzpt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gogol.net.cn/Article/details/gtpcowptsa.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmbtjwye.html

C#:   class MyException : Exception {}
来源：http://dali.sxryk.cn/Article/details/gtipouiqsc.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gtgtflwhvw.html

Py:   except ValueError as e:
来源：http://dali.snrcjt.cn/Article/details/gtfqvfrilx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gtrxtyuoec.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtgzzfptpa.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtekqwxvxa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.bjfxy.top/Article/details/gthcflfwjz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jyoumei.cn/Article/details/gtpovqahzv.html

Ruby: rescue ArgumentError => e
来源：http://dali.0kj1m.cn/Article/details/gtfeokfiyl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tanke756.top/Article/details/gtbxogcxlz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xylfe.cn/Article/details/gttxrjiqqr.html

Py:   value = d.get("k") or default
来源：http://dali.jqgufenzy.top/Article/details/gtityttafp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gtwoswhkww.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gtkjxjksyi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gthuvpgsjj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.quarkkingdee.top/Article/details/gtvwyogyuk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gtfophueob.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ehwqpu.com/Article/details/gtfclibmzj.html

C#:   obj?.A?.B ?? default
来源：http://dali.meibo888.top/Article/details/gtaqtcqpsx.html

[H07] 断言
来源：http://dali.snrcjt.cn/Article/details/gtoqcuukoq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gogol.net.cn/Article/details/gtkvmzuunz.html

PHP:  assert($x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtoxwvplkx.html

JS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtnyrzprvc.html

TS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtcpuahdbr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gtpwkpygni.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhoulong.xyz/Article/details/gtmerikvah.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cucudq.cn/Article/details/gtswbltmbu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtkiqppghf.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgfzy.top/Article/details/gtwltpddoh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jlsjyb.cn/Article/details/gtytcuhlan.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gtmrfbgbgi.html

JS:   e.message;  e.stack
来源：http://dali.tanke756.top/Article/details/gtmiuoujcm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.snrcjt.cn/Article/details/gtjycapfcn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hywenlv.cn/Article/details/gttziyhnjq.html

Go:   err.Error()
来源：http://dali.ehwqpu.com/Article/details/gtadxnwwdl.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjldtdva.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gtmemhdkdy.html

[H09] 带错误码的异常
来源：http://dali.zhixingplan.top/Article/details/gtyqguocix.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.redwolf501.top/Article/details/gtqstotaua.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gtzvjdfres.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuanzhike.top/Article/details/gtokcgspfr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zycfv.cn/Article/details/gtskmarozu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258888.top/Article/details/gtvvggbbor.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pengpengdd.cyou/Article/details/gteujjpghl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgufenzy.top/Article/details/gtxgzgcjvh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqovvfpw.html

[H10] 资源自动释放
来源：http://dali.tanke756.top/Article/details/gtuerbzqqq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.iojbl.cn/Article/details/gtjduudugl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuanzhike.top/Article/details/gttlbduomq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtgtpdgwfi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gtgsvaofcb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nwbrower.top/Article/details/gtqohnpvqc.html

Go:   defer f.Close()
来源：http://dali.gogol.net.cn/Article/details/gtgovdenhx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yongpay.top/Article/details/gtilfsjckr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtommcykjf.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtfpdtznmy.html

I. 正则表达式
来源：http://dali.yuanzhike.top/Article/details/gtixdgvjsx.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtzfersqyu.html

[I01] 判断是否匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgdmvndf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtywhhjfqq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkxqmgmm.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtxgranzbq.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gticcdbcjs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gtnixnysjy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gtetnsojsy.html

Ruby: s.match?(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gtnpztbhsi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shzxlz.cn/Article/details/gtctvfkuhf.html

[I02] 提取所有匹配
来源：http://dali.jianghu66.top/Article/details/gtjuemzdch.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gtfzpxhhzg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gtsfrditxa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yonumen.top/Article/details/gtnnnwaqft.html

TS:   s.match(/\d+/g)
来源：http://dali.tian-w.cn/Article/details/gttcbcowbg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.svipenyu.cn/Article/details/gtglgxftko.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtobqafhpz.html

Ruby: s.scan(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gthsuwrlmu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtltbwjdll.html

[I03] 提取捕获分组
来源：http://dali.fzhhl.top/Article/details/gtrwnogkko.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ybcxt.top/Article/details/gtzjfuuvmh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gthfljvxea.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigfzy.top/Article/details/gtscnvvpde.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fzhhl.top/Article/details/gtnpyroyar.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sufxvd.cn/Article/details/gtunezuiwk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gaohongyu789.top/Article/details/gtemdegicq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yangfankeji.com/Article/details/gtaggrczhd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuxming.cn/Article/details/gtcydhybkl.html

[I04] 正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gttuvyrxqj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.vqdsnc.cn/Article/details/gtczhdzmjk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.snrcjt.cn/Article/details/gtpfbfckez.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtgmwxeyue.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtvcelolmx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gtzjiczfkq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aibaodan.cn/Article/details/gtnzdyvmzt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gtlvkxwfgw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gtjkylvpnk.html

[I05] 按正则拆分
来源：http://dali.chenzaomai.com/Article/details/gthtqhryey.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgufenzy.top/Article/details/gtnltenkyj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtskcngzxe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gthpnhemoz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtbejqkojx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gttvgbuere.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtvigictbj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtdfewtlrp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ybcxt.top/Article/details/gttgjvudpp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuanzx.com/Article/details/gtmjnrcenk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtwfsskwmt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcgyrknl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gtfkisnujq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gtqfjxqwny.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtkofmexta.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hywenlv.cn/Article/details/gtchkhvnuj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gtnmxkomqh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtozapccnw.html

[I07] 忽略大小写与多行模式
来源：http://dali.sxryk.cn/Article/details/gtfifzjjbs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pengpengdd.cyou/Article/details/gtmhstjfwd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gtnrwykzqi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tanke756.top/Article/details/gtqewtwkgh.html

TS:   /error/gim
来源：http://dali.yuxming.cn/Article/details/gthszenydw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xinyue.icu/Article/details/gtrsdazlfj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gtoktupmky.html

Ruby: s.scan(/error/i)
来源：http://dali.bjfxy.top/Article/details/gtmqpnxwre.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gtqjcmywic.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtsjdaoocm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.meibo888.top/Article/details/gtoztcjzrw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtmzikvodb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gtnvczmmoa.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gtvzoexjzl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gtmjaysvmc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.vqdsnc.cn/Article/details/gtnfjgptwd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cashguo.top/Article/details/gtqkhwevuj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gtiqesktru.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtubppzhhp.html

J. 日期与时间
来源：http://dali.zhoulong.xyz/Article/details/gtjcgravme.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gttnntaznh.html

[J01] 获取当前时间
来源：http://dali.xuanzx.com/Article/details/gtcgmxnlkd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gogol.net.cn/Article/details/gttheiamca.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gtleowrvwh.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtwukocsxg.html

TS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtbrfntdgq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuanzx.com/Article/details/gtncfuoqrx.html

Go:   time.Now()
来源：http://dali.shangyingyoupin.top/Article/details/gtjwwhvbcv.html

Ruby: Time.now
来源：http://dali.gzhubu.top/Article/details/gtrsbgzjbo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuanzhike.top/Article/details/gtiduxfiqg.html

[J02] 格式化输出
来源：http://dali.ivvv.top/Article/details/gtubmlmqfk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gtyimzljbk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtpivxwymo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwzlffhl.html

TS:   d.toISOString()
来源：http://dali.daxiang520.top/Article/details/gtylhmuqpz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.haohaochexian.top/Article/details/gtxrkpdqdf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.meibo888.top/Article/details/gtnkuidwho.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtthxzkryv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yongpay.top/Article/details/gtxdufrwqo.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gtscdgwmmn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shuidangran.top/Article/details/gtjtikhxrc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdicfmnu.html

JS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtkfairlcb.html

TS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtzmhhpvvb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtgqvtcfuv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtbbmolikp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtwkfddino.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gtsqdjretb.html

[J04] 时间戳与日期互转
来源：http://dali.hongshengwenyu.top/Article/details/gtjkfgsalg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtfutesxrr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxinkj.top/Article/details/gtopwyiafq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ehwqpu.com/Article/details/gtpdcjpeef.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jyoumei.cn/Article/details/gtyfbmstjl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgfzy.top/Article/details/gtmrguircz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gtgdlyiihy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gtoqweoedm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gttqqqhcvy.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhoulong.xyz/Article/details/gtcbvrrmzv.html

Py:   now + timedelta(days=7)
来源：http://dali.jlsjyb.cn/Article/details/gtvahgnfmu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zdqjudy.top/Article/details/gtggkjyojw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtyadpmjrq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gttwvjttdz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gtivgatylt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yvedp.cn/Article/details/gtldzzlmmc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ehwqpu.com/Article/details/gtzfkbogoz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gtemsnvrat.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gtakhrtgrb.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gtdyighjzk.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gtuycqmiji.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gtfdfjxvry.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ppjwa.cn/Article/details/gtqjjoxdgc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gtyfboqtzj.html

Go:   end.Sub(start).Hours()
来源：http://dali.hfpthk.cn/Article/details/gtnyyaufoz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hongshengwenyu.top/Article/details/gtrppnzrmi.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gtqybkcozw.html

[J07] 比较两个日期
来源：http://dali.aibaodan.cn/Article/details/gtgbjabxox.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtfucdqmlv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gaohongyu789.top/Article/details/gtkquxsfsi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtjsciliqv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtazzyjqgu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjsuxcbj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigufen.top/Article/details/gtzhyqzmil.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtyiougcvf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtrorugyou.html

[J08] 提取年月日与星期
来源：http://dali.dashuyun.cn/Article/details/gtnzqoclmq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gtdxjxrjph.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gzhubu.top/Article/details/gtaapoebvo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnqzz.top/Article/details/gtjpxothry.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guowangkeji.top/Article/details/gtwavxkxuf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tian-w.cn/Article/details/gthxfdikvm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hywenlv.cn/Article/details/gtssiqdodm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhongyouzk.top/Article/details/gtboeffidt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xziqi.cn/Article/details/gtkanzktzc.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gtaoyztqhb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gtxgnfkipf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hysaishi.cn/Article/details/gtcslydwux.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gthchdkani.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtwiwuizgq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuxming.cn/Article/details/gtnkiikqmk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojduxrxe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gtqdumgdqk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gtvstqegxl.html

[J10] 取今天 / 本月第一天
来源：http://dali.ehwqpu.com/Article/details/gtlabpmvbo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aizwys.cn/Article/details/gtpidfocoy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cdnleiting.top/Article/details/gtgicazaqw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhengqikj.top/Article/details/gttgcgzlkn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cqqwz.cn/Article/details/gtgkxwbvqa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gtlemubeug.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cucudq.cn/Article/details/gtfnmnggph.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hongshengwenyu.top/Article/details/gtvupwlpai.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.quarkkingdee.top/Article/details/gtevbuzbbh.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtchcnlxyi.html

K. JSON 与序列化
来源：http://dali.chenlongwang.top/Article/details/gtbpbaidkg.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttnjhoowu.html

[K01] 对象转 JSON 字符串
来源：http://dali.aizwys.cn/Article/details/gtmlklkigc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gtkhydjayb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gtfeznaovc.html

JS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gtirhraplq.html

TS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxgveluv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.meibo888.top/Article/details/gtdvlntgke.html

Go:   json.Marshal(obj)
来源：http://dali.mhx1999.top/Article/details/gtdsergwpx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangdashe.top/Article/details/gtqvfeimny.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hysaishi.cn/Article/details/gtsmxfxrfo.html

[K02] JSON 字符串转对象
来源：http://dali.yanxiufei.cn/Article/details/gtorqytdxj.html

Py:   json.loads(s)
来源：http://dali.shzxlz.cn/Article/details/gtgttgtaqn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgfzy.top/Article/details/gtuprmzqda.html

JS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtackvkcwm.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtuwgrcufk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daria6918.cn/Article/details/gtkamselmk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gtwwntwdnn.html

Ruby: JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtfrbbzaww.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj202588.top/Article/details/gtsxiafcbe.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigufen.top/Article/details/gtpbstjlhq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtfmuubtgc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtaipwdcip.html


<!-- 参考信息 -->