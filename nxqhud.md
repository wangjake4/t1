代发 wailian999

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtgwldwxwl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangdashe.top/Article/details/gtigdqxvhy.html

Ruby: u.is_a?(User)
来源：http://dali.zhixingplan.top/Article/details/gtlguecqud.html

C#:   u is User
来源：http://dali.daria6918.cn/Article/details/gtakuskokj.html

[G14] 数据类 / record
来源：http://dali.xuanzx.com/Article/details/gtavawgiru.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gtlmowytmg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydunxbkx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gtdjrlutqo.html

TS:   type User = { name: string; age: number };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmvizujf.html

Java: record User(String name, int age) {}
来源：http://dali.nwbrower.top/Article/details/gtwahapvan.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhengqikj.top/Article/details/gtijqaejsz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgufenzy.top/Article/details/gtqpbfsrll.html

C#:   record User(string Name, int Age);
来源：http://dali.xziqi.cn/Article/details/gtknzktcbh.html

[G15] 枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtaxtxrjsy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gtekcbhyma.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.smart0.xyz/Article/details/gtbtnofquf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxuanxn.top/Article/details/gtfmibqgwq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtrxobsvmb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zdqjudy.top/Article/details/gtouvxkvrm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gtxayrxzjt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangshuangyany.cn/Article/details/gtscznlwxh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtllvcekdv.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gtvjzjpzxb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gtnqobutpr.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gtenfzapkf.html

JS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gtjmyhyidd.html

TS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtggmrzpse.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gtnlzyisdc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gtomfehosd.html

Ruby: obj.instance_variables
来源：http://dali.jianghu66.top/Article/details/gtmmexpfjg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtfvkpkkhh.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtbmqujdpx.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gtaswuplmz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtvxbmogxn.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gtwrpmbhzo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuanzhike.top/Article/details/gttjsmvbqm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gtcfbnaxxg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gtdgjrncuj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtyvwyzelm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gtnrfgddda.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuanzhike.top/Article/details/gtpdfywasr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tianlin.xyz/Article/details/gtgdxqlves.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yangfankeji.com/Article/details/gtzmqvywhs.html

[H02] finally / ensure 收尾
来源：http://dali.ppjwa.cn/Article/details/gtckduddil.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gtshzobymj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtppzahvnx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtzltqayfx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gttfqsdusd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtxuufqkbk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gtbctlduym.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchqggviw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtxuckejpv.html

[H03] 主动抛出异常
来源：http://dali.316326.xyz/Article/details/gtdeyspqwr.html

Py:   raise ValueError("错误信息")
来源：http://dali.yongpay.top/Article/details/gttmesmguk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtqzsihcoq.html

JS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtbziznvch.html

TS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtpenpzdnz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcbzolil.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhongyouzk.top/Article/details/gtrnzxldrz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpflvyms.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtjemtlojc.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gtvqfdfcys.html

Py:   class MyError(Exception): pass
来源：http://dali.jianghu66.top/Article/details/gtiduzwfiz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gtxbzephpq.html

JS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gttmyzvvyv.html

TS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtjonmkjhr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtsmibvjcd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tanke756.top/Article/details/gtaccwoxqv.html

Ruby: class MyError < StandardError; end
来源：http://dali.guowangkeji.top/Article/details/gtkqupqdmf.html

C#:   class MyException : Exception {}
来源：http://dali.yuxming.cn/Article/details/gtnnunhevz.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gtekoeramh.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gtoomfnpan.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hfpthk.cn/Article/details/gtdfocmhhz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gtdpmzqwrq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtqvhlaqit.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtetqcvmvy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fengsongda.top/Article/details/gtcpmxvtkk.html

Ruby: rescue ArgumentError => e
来源：http://dali.birdmap.top/Article/details/gthocodyjy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cdnleiting.top/Article/details/gttrxokxek.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hysaishi.cn/Article/details/gtfcvqvrph.html

Py:   value = d.get("k") or default
来源：http://dali.vqdsnc.cn/Article/details/gtaqyspepu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gtarsxbuvj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gttqnpllzt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gtfxdffltv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shangyingyoupin.top/Article/details/gtzrmqwfce.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.haohaochexian.top/Article/details/gteodupaee.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yanxiufei.cn/Article/details/gtsngbtdps.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuanzx.com/Article/details/gtordhyqui.html

[H07] 断言
来源：http://dali.tian-w.cn/Article/details/gtcgisyasf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.redwolf501.top/Article/details/gtzcrntavi.html

PHP:  assert($x > 0);
来源：http://dali.iojbl.cn/Article/details/gtcuvtaqcs.html

JS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtlsywebvd.html

TS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtlwjouagg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxnzeong.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gtlkmcpmkk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.feifeiyinyue.top/Article/details/gtmschewwp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtdqbbrpoy.html

[H08] 获取错误信息与堆栈
来源：http://dali.guannengcc.top/Article/details/gtsjpjxzkl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cheryme.top/Article/details/gtaadlchrl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gtqnwdbvhk.html

JS:   e.message;  e.stack
来源：http://dali.jinghuilouyu.cn/Article/details/gtxntnjrtt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.9152youxi.cn/Article/details/gtcjdvoahf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gtcbwwrhny.html

Go:   err.Error()
来源：http://dali.ivvv.top/Article/details/gtndadayag.html

Ruby: e.message;  e.backtrace
来源：http://dali.shuidangran.top/Article/details/gtyztsbijs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yonumen.top/Article/details/gtzjcnfnae.html

[H09] 带错误码的异常
来源：http://dali.vqdsnc.cn/Article/details/gtwwcgddqh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jlsjyb.cn/Article/details/gtcwukbnrx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gtvpaguwoj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.quarkkingdee.top/Article/details/gthwkicekm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ydzc1.top/Article/details/gtpkzclejf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sweek.top/Article/details/gtxkqxcwqn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xylfe.cn/Article/details/gtctfdhoah.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhoulong.xyz/Article/details/gtembohnxv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xinyue.icu/Article/details/gthhvyspef.html

[H10] 资源自动释放
来源：http://dali.xuetiantiany.cn/Article/details/gtikgasaju.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxinkj.top/Article/details/gtvmmscgvx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.snrcjt.cn/Article/details/gtwidndfzr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxzlzvhb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gtbkgeonoj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zdqjudy.top/Article/details/gtomuezyil.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gttvjfktnb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sufxvd.cn/Article/details/gtrnfyxidn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbbfqdqu.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtlvxhqwff.html

I. 正则表达式
来源：http://dali.jyoumei.cn/Article/details/gtdpgjiocs.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtkqnykbir.html

[I01] 判断是否匹配
来源：http://dali.ydzc1.top/Article/details/gttwklfxzf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gtxjlipizj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hammf.cn/Article/details/gtkxtulsrj.html

JS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtuyyswpsd.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gtexcgfggd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xinyue.icu/Article/details/gtkrpeqedq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zdqjudy.top/Article/details/gtbnsfthsw.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtoekmntij.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gtbgxnkeza.html

[I02] 提取所有匹配
来源：http://dali.cashguo.top/Article/details/gtdjncgzyg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxrsrjvg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cdnleiting.top/Article/details/gtdnslkitq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.haohaochexian.top/Article/details/gtzueaghgk.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgufenzy.top/Article/details/gtyteyocnc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtmgxdisjb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yueranfly.top/Article/details/gthebxtnly.html

Ruby: s.scan(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtizljxbup.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtslhxsbcl.html

[I03] 提取捕获分组
来源：http://dali.chenjidiqi.icu/Article/details/gtbobvoysz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gtgymvssyy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gtafmimnvb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yvedp.cn/Article/details/gtsrceorpc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.havefunace.top/Article/details/gtpfppkjkz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangshuangyany.cn/Article/details/gtolnjnady.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangtech.top/Article/details/gtkoxbpoas.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tian-w.cn/Article/details/gttsukwpog.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yueranfly.top/Article/details/gtmogtkvjt.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskcixrzf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gtrrtudowa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gtwuhxwzhp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtnojmskhg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtgmmqpjbs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gtphewuidb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yongpay.top/Article/details/gtjnpmbout.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gogol.net.cn/Article/details/gtwrnyvcuw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtiwrkjcyc.html

[I05] 按正则拆分
来源：http://dali.xuetiantiany.cn/Article/details/gteiwhzhaz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgfzy.top/Article/details/gtlcsdytqi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtdkrefdwo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtmzjzmxiz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtqjtbhyej.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gtbcinhizj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtcdwuajju.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtmeblwgff.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cucudq.cn/Article/details/gtglzqvldt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhengqikj.top/Article/details/gtcmeqchwj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtlesifhjh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gaohongyu789.top/Article/details/gtmfowalxv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtcuwwzlgj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtemrdonfl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtauknybtu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zycfv.cn/Article/details/gtnurqkopw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dianchejie.cn/Article/details/gtsqhwjnky.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtietznukv.html

[I07] 忽略大小写与多行模式
来源：http://dali.hongshengwenyu.top/Article/details/gtainptfaz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenlongwang.top/Article/details/gtdynvrjkn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtgktczajc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sweek.top/Article/details/gtyyolhppa.html

TS:   /error/gim
来源：http://dali.zhengqikj.top/Article/details/gtkwzftmej.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenlongwang.top/Article/details/gtltbqsiij.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnxiangtu.top/Article/details/gtgzmlxarm.html

Ruby: s.scan(/error/i)
来源：http://dali.mhx1999.top/Article/details/gtchnwfkji.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangdashe.top/Article/details/gtpcofmgtd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gotoacloud.top/Article/details/gthurntwsy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gtiajeojzv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ivvv.top/Article/details/gtsuqpjdfo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gtrlplihfw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gtzvifjolk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gtarcwfhxz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.feifeiyinyue.top/Article/details/gtbjhxailz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daxiang520.top/Article/details/gtddxztsnp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtqupymjmu.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtwvwzohls.html

J. 日期与时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosnjtjkf.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtsfvahajc.html

[J01] 获取当前时间
来源：http://dali.hfpthk.cn/Article/details/gtbjsivgzh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gtmzfegbow.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxqermxn.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtijrynfin.html

TS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtepbqabqm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gogol.net.cn/Article/details/gtmbedbznm.html

Go:   time.Now()
来源：http://dali.aibaodan.cn/Article/details/gtuoailuyr.html

Ruby: Time.now
来源：http://dali.xylfe.cn/Article/details/gtpilghzqu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zdqjudy.top/Article/details/gtskbeikrt.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtakpqufda.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gtxrbyfraf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gtdmzptbxg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jlsjyb.cn/Article/details/gtbdmkqqco.html

TS:   d.toISOString()
来源：http://dali.xziqi.cn/Article/details/gtmkydevgy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dashuyun.cn/Article/details/gtcerjvlgt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjioccbl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtnrphvsip.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258888.top/Article/details/gtybrqzwts.html

[J03] 字符串解析为日期
来源：http://dali.dashuyun.cn/Article/details/gtpkqklylm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.quarkkingdee.top/Article/details/gtgxdeuzct.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnqzz.top/Article/details/gtiyljrfyc.html

JS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtuxitviyb.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gthxckzhlk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtrdtmfatn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtkynpcvfk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtozhxtcbd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuxming.cn/Article/details/gtalyfycwp.html

[J04] 时间戳与日期互转
来源：http://dali.pengpengdd.cyou/Article/details/gtcpbiqmwx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xylfe.cn/Article/details/gtsclmgmle.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sweek.top/Article/details/gttlpquctq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjozcwgcj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tian-w.cn/Article/details/gtounbcxlc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gthxmijiql.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gtryvfrbyu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnqzz.top/Article/details/gtrpxczkjp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zycfv.cn/Article/details/gttexnrmfi.html

[J05] 时间加减（加 7 天）
来源：http://dali.aibaodan.cn/Article/details/gthqcbgxef.html

Py:   now + timedelta(days=7)
来源：http://dali.hfpthk.cn/Article/details/gtwdvvldbz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gtigckhkol.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gtjdhfzvvm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gtudicyaqt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwkhocck.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gtvpuzskab.html

Ruby: Time.now + 7 * 86400
来源：http://dali.havefunace.top/Article/details/gtfpnsswei.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtqfaggluk.html

[J06] 计算两时间之差
来源：http://dali.fengsongda.top/Article/details/gttjviiwcz.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gtkrttfuul.html

PHP:  $end->diff($start)->days;
来源：http://dali.guowangkeji.top/Article/details/gtwqesmuzd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gtlzjduaaz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gtrxxflocw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.iojbl.cn/Article/details/gtcudwojjd.html

Go:   end.Sub(start).Hours()
来源：http://dali.mhx1999.top/Article/details/gtkrkaghzm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gtyehpvmby.html

C#:   (end - start).TotalSeconds
来源：http://dali.ydzc1.top/Article/details/gtrgjebcaz.html

[J07] 比较两个日期
来源：http://dali.andypj.xyz/Article/details/gtaejbsmwe.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtszqdkezm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shzxlz.cn/Article/details/gtovfiyajy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gteivmmukl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gthmztbgtz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tianlin.xyz/Article/details/gteociasvu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daria6918.cn/Article/details/gtrarokuol.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtqsodfwmp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gthuyhjeqk.html

[J08] 提取年月日与星期
来源：http://dali.xylfe.cn/Article/details/gtpnkjqqou.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnqzz.top/Article/details/gtlayvjadm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258888.top/Article/details/gtcoithhdo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gttrmyplpl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.316326.xyz/Article/details/gtztezmwar.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cucudq.cn/Article/details/gtbiegkapy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daxiang520.top/Article/details/gtohmlwvza.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yanxiufei.cn/Article/details/gtxdjbzdqu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gtyilncqxj.html

[J09] 时区处理
来源：http://dali.cashguo.top/Article/details/gtsmejlnpu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gtkpknjotv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cucudq.cn/Article/details/gtabchcpep.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gtiewwkyfy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtquqtcqha.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.bjfxy.top/Article/details/gtcyemecir.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjlbcwzt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hywenlv.cn/Article/details/gtwbplyrgu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhoulong.xyz/Article/details/gtarheyycj.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gtmgdjffvc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yvedp.cn/Article/details/gtfcqjjvyb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gtxskvtuen.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtbjjwibns.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guowangkeji.top/Article/details/gtxxoqtbkh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgufenzy.top/Article/details/gtfwpzqakk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gtivyjwkjo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gotoacloud.top/Article/details/gtcjoxrcif.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gtqaiwxgyf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtydrosaqu.html

K. JSON 与序列化
来源：http://dali.xylfe.cn/Article/details/gtzzjonhto.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtkotlnptf.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gthayspncz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtgohyozpy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gtowtlptil.html

JS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gtkalppfbn.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtmayojdrg.html


<!-- 参考信息 -->