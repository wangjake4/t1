代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.snrcjt.cn/Article/details/gtmjffprqd.html

Java: record User(String name, int age) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtejdcsyib.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tanke756.top/Article/details/gtxuhrxyhu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tianlin.xyz/Article/details/gtmmxovenm.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gtllbtsdfp.html

[G15] 枚举
来源：http://dali.redwolf501.top/Article/details/gtxpgleiln.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gtnopccgey.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gtinqvkqdz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.birdmap.top/Article/details/gtanylspjf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gtredaofci.html

Java: enum Color { RED, GREEN }
来源：http://dali.cashguo.top/Article/details/gtxvqtryec.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tian-w.cn/Article/details/gtgfaeyxtq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gtohnkqpib.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmdzbcej.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gtvslegwxc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cashguo.top/Article/details/gtowynzfdw.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gtcrnhqrpf.html

JS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtzqegimxe.html

TS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gtbziiackj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gtugudoakp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zycfv.cn/Article/details/gtegguprsl.html

Ruby: obj.instance_variables
来源：http://dali.zhiwuduotai.top/Article/details/gtgiexqhpg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtvbmsgyfi.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtgkrbcskl.html

H. 异常与错误处理
来源：http://dali.nanxinkj.top/Article/details/gtcodyekgw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtsyiizbdd.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gtdlxkaqys.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gtcwlkzbcq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuxming.cn/Article/details/gtyabssqsg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gtwsimdnqh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtchzuyzdd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tianlin.xyz/Article/details/gtojxnhlwu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gtqylpsvoa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.havefunace.top/Article/details/gtcuuqrmvh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258888.top/Article/details/gtljwskypf.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigufen.top/Article/details/gtdieltsjm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxinkj.top/Article/details/gtjskshltk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtqjykjrhq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtrponoafz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtzkmruacl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtlbqnsuhl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sxryk.cn/Article/details/gtpevobqnj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gtjsdfolwf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gthjhptfnt.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gtnxuatxur.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gtzfakdquz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtdaprnayw.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsdxsqzb.html

TS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtzbknnfwr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtsnoxevfc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shzxlz.cn/Article/details/gtwexxsrwz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gtxvrbswyf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtfuiroygy.html

[H04] 自定义异常类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdetjusti.html

Py:   class MyError(Exception): pass
来源：http://dali.xylfe.cn/Article/details/gtxlihyuod.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtztkskbuj.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtwsymbhyk.html

TS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gtiogqfqcu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gtoexopguf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzygdobj.html

Ruby: class MyError < StandardError; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdmceodf.html

C#:   class MyException : Exception {}
来源：http://dali.cdnleiting.top/Article/details/gtckirmhdy.html

[H05] 捕获特定类型
来源：http://dali.xylfe.cn/Article/details/gtldxoztna.html

Py:   except ValueError as e:
来源：http://dali.yj20258888.top/Article/details/gtbrfqfvpe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hfpthk.cn/Article/details/gtshfekqdc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtotsubzio.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtwnzekiag.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jyoumei.cn/Article/details/gtjrdpupjj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tian-w.cn/Article/details/gtazyejmlt.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgfzy.top/Article/details/gtbyscjhlf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ydzc1.top/Article/details/gtncgosixv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gtudwwjgjk.html

Py:   value = d.get("k") or default
来源：http://dali.birdmap.top/Article/details/gtdscfvzbv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gtseyugbvi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gtnezgwtzd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gtqkqdlpal.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.c1oappe.top/Article/details/gtmtgacqkq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hongshengwenyu.top/Article/details/gtccdfxzsm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hongshengwenyu.top/Article/details/gtyuhebdjz.html

C#:   obj?.A?.B ?? default
来源：http://dali.aibaodan.cn/Article/details/gtjtlprixl.html

[H07] 断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwralkthy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlqgqjhn.html

PHP:  assert($x > 0);
来源：http://dali.yueranfly.top/Article/details/gtybapjndh.html

JS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtvipwumpc.html

TS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtdhzwwuzk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhixingplan.top/Article/details/gtpazboupu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pycfn.com/Article/details/gtkokmuzag.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gogol.net.cn/Article/details/gtzaftepsu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtvybcbxtd.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gtzdksuufp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daria6918.cn/Article/details/gtqhcpslsq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guowangkeji.top/Article/details/gttkcuhgpr.html

JS:   e.message;  e.stack
来源：http://dali.gogol.net.cn/Article/details/gtovccgyuk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gtestxynrl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjuovndl.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gtvfdimmeu.html

Ruby: e.message;  e.backtrace
来源：http://dali.jyoumei.cn/Article/details/gtcstpgmll.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yanxiufei.cn/Article/details/gtwtidlavo.html

[H09] 带错误码的异常
来源：http://dali.ppjwa.cn/Article/details/gtbyhccrbt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zdqjudy.top/Article/details/gtthrfvowp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenlongwang.top/Article/details/gtduomvele.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gotoacloud.top/Article/details/gtgswrajrz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gtagyaisln.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gtoamaewoe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pycfn.com/Article/details/gthztanoig.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hongshengwenyu.top/Article/details/gtrthxscta.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ydzc1.top/Article/details/gtfgxzovxn.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gtmkjbhojb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgfzy.top/Article/details/gttyiggpbl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gtgswbsyhz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtsvxtvcpc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gtxpwkqmsi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndxcxkzp.html

Go:   defer f.Close()
来源：http://dali.redwolf501.top/Article/details/gtbeewszci.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gtkurnprny.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtxrxtixnc.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtxjwflrnj.html

I. 正则表达式
来源：http://dali.hywenlv.cn/Article/details/gtiqbxqbqb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtmfmlkuys.html

[I01] 判断是否匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtwexnrzpq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gteylzuedg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hammf.cn/Article/details/gtotrxcgff.html

JS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtpfruevzh.html

TS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtgecychax.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gtzowhyyva.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jiagoushi.top/Article/details/gtqivxeesn.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258.top/Article/details/gtxlsszbzv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tianlin.xyz/Article/details/gttvrqdiyj.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gtwmcvvsrr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtcrllwbuj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.havefunace.top/Article/details/gthtzcggfw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daxiang520.top/Article/details/gtkfgrghxj.html

TS:   s.match(/\d+/g)
来源：http://dali.wangdashe.top/Article/details/gteczjjjkw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pycfn.com/Article/details/gtbafncnjz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cashguo.top/Article/details/gtzqlycfvu.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gttlsirmhh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daxiang520.top/Article/details/gtczqeuxqn.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gtmgywrrzt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fzhhl.top/Article/details/gtuckiraqy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gtelnbgzwd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.smart0.xyz/Article/details/gtzkwfzxwr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnxiangtu.top/Article/details/gtmptbnqww.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gzhubu.top/Article/details/gtqgyqnohc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tianlin.xyz/Article/details/gtcqhrpbmd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtldfkapph.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqxixcte.html

[I04] 正则替换
来源：http://dali.cqqwz.cn/Article/details/gtdqwlmocr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsbyqnrs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtswtlawcg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtfyetsbzr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gtuhmzmxbr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gteldnqauo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtdnwuwhti.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtgxxiehox.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gtzsczkfyg.html

[I05] 按正则拆分
来源：http://dali.zhengqikj.top/Article/details/gtpcmcaepa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuanzx.com/Article/details/gtoczggfki.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtfpgtghbq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtogcpqtdu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gtzalknyub.html

Java: s.split("\\s*,\\s*")
来源：http://dali.mhx1999.top/Article/details/gtdtgdfsml.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtrjozjqei.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtfvrwphpx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjekczob.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dianchejie.cn/Article/details/gttdmuigry.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtgsfgcgjz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cheryme.top/Article/details/gtwhpxjwzx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gthdhnoxzl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtmbmcwzud.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtvtgwzrjg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqdphbwo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinghuilouyu.cn/Article/details/gtogwyiefd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gttvrzwkcn.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gttfhwrhft.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.meibo888.top/Article/details/gtwoujuiji.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxlifggh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gogol.net.cn/Article/details/gtojgigvic.html

TS:   /error/gim
来源：http://dali.hongshengwenyu.top/Article/details/gtsdjggehe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gtbvzjqxno.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ydzc1.top/Article/details/gtsdogqift.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gtdcbwklxs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.iojbl.cn/Article/details/gtewwysgds.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gogol.net.cn/Article/details/gtkqqxspkj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gttueuoibf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gtwzhzdumt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gtlifbwcti.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gtvnzcwkay.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gtgjpdzpnu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gtrpxodpsd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.316326.xyz/Article/details/gtbokjlquv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvobyevi.html

================================================================================
来源：http://dali.sweek.top/Article/details/gthqdummom.html

J. 日期与时间
来源：http://dali.bjfxy.top/Article/details/gthzkvxtnr.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gthfdxqjwy.html

[J01] 获取当前时间
来源：http://dali.yj20258888.top/Article/details/gtqzncbrlc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.quarkkingdee.top/Article/details/gtbyiwjhlv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gteiaxvgup.html

JS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gttoclweij.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtkpxxyvgy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gzhubu.top/Article/details/gtqxfjjamx.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gtpvjsbdmq.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gtaygrsqlu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.mhx1999.top/Article/details/gtuotkdavn.html

[J02] 格式化输出
来源：http://dali.mhx1999.top/Article/details/gtzilglupa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtljojiesl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gtnilntbme.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.mhx1999.top/Article/details/gtbfcfqqzk.html

TS:   d.toISOString()
来源：http://dali.svipenyu.cn/Article/details/gtrzkixzwo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgfzy.top/Article/details/gttfqaowdr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenlongwang.top/Article/details/gtmutpehhl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtqngcsegu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yangfankeji.com/Article/details/gtnzkswgad.html

[J03] 字符串解析为日期
来源：http://dali.gotoacloud.top/Article/details/gtanulxlvo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.svipenyu.cn/Article/details/gtrnmjptgu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gtultlvplr.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtwqzvbstb.html

TS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtirvuvyeq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtonajceob.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtwmfhstlj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtaktvjkio.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gzhubu.top/Article/details/gtpwqwquaa.html

[J04] 时间戳与日期互转
来源：http://dali.xuanzx.com/Article/details/gttamdfxga.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenzaomai.com/Article/details/gtjtqxitkv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gtiqcsobdm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hysaishi.cn/Article/details/gtrgdgrkyv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.birdmap.top/Article/details/gtjyslhyvm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sysykeji.top/Article/details/gttvvvisyo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj202588.top/Article/details/gtotlawzlo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.havefunace.top/Article/details/gtytcvvtky.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gtlfthtggy.html

[J05] 时间加减（加 7 天）
来源：http://dali.yanxiufei.cn/Article/details/gtufeyyuxj.html

Py:   now + timedelta(days=7)
来源：http://dali.meibo888.top/Article/details/gttgreyoda.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gtmtdbpjvs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gtxnpdbbzy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gtvglttiqk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcquvpjxq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgfzy.top/Article/details/gtiwhmjiuj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmykfpmt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aibaodan.cn/Article/details/gtwnspbsic.html

[J06] 计算两时间之差
来源：http://dali.wangshuangyany.cn/Article/details/gteiffwrkp.html

Py:   (end - start).total_seconds()
来源：http://dali.daria6918.cn/Article/details/gtqktjimyv.html

PHP:  $end->diff($start)->days;
来源：http://dali.yongpay.top/Article/details/gtkeocrcee.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yvedp.cn/Article/details/gtqzllgkhv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.havefunace.top/Article/details/gtqpdlpcth.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sxryk.cn/Article/details/gtbzalpzgt.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gtozqbzhlk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuxming.cn/Article/details/gtsbghfidv.html

C#:   (end - start).TotalSeconds
来源：http://dali.daria6918.cn/Article/details/gtdqknzepd.html

[J07] 比较两个日期
来源：http://dali.hnqzz.top/Article/details/gtbutsfyno.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpodugws.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cucudq.cn/Article/details/gtzdqcdqky.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gtagmllwlw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtpfzizadw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.redwolf501.top/Article/details/gthtfbsezf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gtffcuowft.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtxzizzflg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtuagrumyg.html

[J08] 提取年月日与星期
来源：http://dali.dianchejie.cn/Article/details/gtmteugwhg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hysaishi.cn/Article/details/gtttrkyzus.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cheryme.top/Article/details/gtilhjqeex.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangshuangyany.cn/Article/details/gtxxeqbbyr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fzhhl.top/Article/details/gtdgmjegcp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tian-w.cn/Article/details/gtezlzarly.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yonumen.top/Article/details/gtxstouqbb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pengpengdd.cyou/Article/details/gtqidfvafr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.svipenyu.cn/Article/details/gteqqnrpgd.html

[J09] 时区处理
来源：http://dali.9152youxi.cn/Article/details/gtzeqpjfis.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jiagoushi.top/Article/details/gtdayvpapi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fzhhl.top/Article/details/gteooneuhp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gtjxpugsxf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gtaddgergy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gtnyjobjqf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gtetwbiiol.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yanxiufei.cn/Article/details/gtjzjloscz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cashguo.top/Article/details/gtzwetatzy.html

[J10] 取今天 / 本月第一天
来源：http://dali.yangfankeji.com/Article/details/gtzeqcpwlq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.316326.xyz/Article/details/gtdtpioccu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gtczfmeuhf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xinyue.icu/Article/details/gtcrxhwhgc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pycfn.com/Article/details/gtnjyxxhzc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daria6918.cn/Article/details/gtfdowtvhf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gtaoxtodqz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxinkj.top/Article/details/gttcqmucwj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.redwolf501.top/Article/details/gtfezrgzex.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtfoogiupn.html

K. JSON 与序列化
来源：http://dali.shanyushiyangtech.top/Article/details/gtomaetndk.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtawyozxpl.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gtmssyqfss.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtgwyqqele.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtczlrhpwl.html

JS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gtspjlpoju.html

TS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gtswpuurjm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.smart0.xyz/Article/details/gtzckyioul.html

Go:   json.Marshal(obj)
来源：http://dali.sweek.top/Article/details/gtdgeveioa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gtknevefqn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yvedp.cn/Article/details/gthvwhierv.html

[K02] JSON 字符串转对象
来源：http://dali.guowangkeji.top/Article/details/gtllvamreb.html

Py:   json.loads(s)
来源：http://dali.shuidangran.top/Article/details/gtjakbsdub.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuparuxun.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzpofrlh.html


<!-- 参考信息 -->