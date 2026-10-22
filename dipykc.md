代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.yuanzhike.top/Article/details/gtteiqgwfs.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gtawlawcjq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gtujhpviyy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxuanxn.top/Article/details/gtmcybyuoy.html

C#:   record User(string Name, int Age);
来源：http://dali.xinyue.icu/Article/details/gtqlcvplvh.html

[G15] 枚举
来源：http://dali.yanxiufei.cn/Article/details/gtvtluphqw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cqqwz.cn/Article/details/gtwpocusnv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daria6918.cn/Article/details/gtpwetkzmv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cdnleiting.top/Article/details/gtaosagvdh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gtxehcojjg.html

Java: enum Color { RED, GREEN }
来源：http://dali.sysykeji.top/Article/details/gtvbfouzbb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxinkj.top/Article/details/gtxhicsufm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gtliiqlypf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtaqnihjtt.html

[G16] 对象转数组 / 字典
来源：http://dali.cdnleiting.top/Article/details/gtxxuxlgab.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cucudq.cn/Article/details/gtvhmdgsfc.html

PHP:  get_object_vars($obj);
来源：http://dali.shuidangran.top/Article/details/gtcvzpaqxo.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstsgvzhf.html

TS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtlipdfhcd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gtlbvhvkcj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aizwys.cn/Article/details/gtkkuirgrw.html

Ruby: obj.instance_variables
来源：http://dali.dashuyun.cn/Article/details/gtebkpxxsi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gtgedewuhu.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtoqtvcjfe.html

H. 异常与错误处理
来源：http://dali.ydzc1.top/Article/details/gtiwaeursu.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtgjwqakpx.html

[H01] try / catch 基础
来源：http://dali.c1oappe.top/Article/details/gtycfzbuua.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuanzx.com/Article/details/gtvrotavim.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gtqjdkdqzc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtuhepvjqg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjvhgymk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guowangkeji.top/Article/details/gtwztocvag.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cqqwz.cn/Article/details/gtxwxiacnf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gtcfbsjdrn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tian-w.cn/Article/details/gtvgqdzdlc.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gtrnqqcasr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gttqqgmgok.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtlirytjyr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtoyseeera.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtkmqfefoc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtwnautuvb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuanzhike.top/Article/details/gtqwelhlon.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gtwqcwjqib.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtwcqmckez.html

[H03] 主动抛出异常
来源：http://dali.jinqigufen.top/Article/details/gtwzpiclzp.html

Py:   raise ValueError("错误信息")
来源：http://dali.pengpengdd.cyou/Article/details/gtbelzehst.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtfuiwmhsw.html

JS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtihpcwuri.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtkvvcwtrr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtahltmhwe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuanzhike.top/Article/details/gtlrgvgbnj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yanxiufei.cn/Article/details/gtauasoqjp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtmlavzglt.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gtpjqqifpf.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gthttutyxb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gthnejasmk.html

JS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gtckqoitoj.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtsiqfvval.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihufdlnh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gtiwiognuw.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdcqskrw.html

C#:   class MyException : Exception {}
来源：http://dali.ehwqpu.com/Article/details/gtmmsrglrm.html

[H05] 捕获特定类型
来源：http://dali.yongpay.top/Article/details/gtecunuzae.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gtuntegxum.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zdqjudy.top/Article/details/gtpkenujkb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gtmyzrdpkk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtecnnytdy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfwlvmjw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tian-w.cn/Article/details/gtbbzgeaeh.html

Ruby: rescue ArgumentError => e
来源：http://dali.shangyingyoupin.top/Article/details/gtwnebspkw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gtmxtkwwir.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xinyue.icu/Article/details/gtzxgjtzcm.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gtaechtaqw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gtsaxuyfum.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtjtvjylko.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gtndtlihfk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.quarkkingdee.top/Article/details/gtjxkjgqoa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangshuangyany.cn/Article/details/gtwctlzqwx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gtxwyqtxho.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gtspzkgkzg.html

[H07] 断言
来源：http://dali.wangdashe.top/Article/details/gttwcyvrqn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jlsjyb.cn/Article/details/gtxxysogzz.html

PHP:  assert($x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcosrpjvv.html

JS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtkqjwuyic.html

TS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtuahxkgxq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shzxlz.cn/Article/details/gtduclnvrd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj202588.top/Article/details/gtmwzxwsav.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aizwys.cn/Article/details/gtuhftedsi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtemlekhkc.html

[H08] 获取错误信息与堆栈
来源：http://dali.pengpengdd.cyou/Article/details/gtvfxvpkml.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gtipfpvuod.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenzaomai.com/Article/details/gtraoezwny.html

JS:   e.message;  e.stack
来源：http://dali.haohaochexian.top/Article/details/gtopgmprnj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tianlin.xyz/Article/details/gtayfbldiv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gogol.net.cn/Article/details/gtrrhecqho.html

Go:   err.Error()
来源：http://dali.smart0.xyz/Article/details/gtxpnrphwu.html

Ruby: e.message;  e.backtrace
来源：http://dali.ivvv.top/Article/details/gtyucloiec.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gtlpvfdghz.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gtmhoyjnev.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tanke756.top/Article/details/gturxoqmng.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cdnleiting.top/Article/details/gttmpzmdpk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.kuanghao11.cn/Article/details/gtznssmlsy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zdqjudy.top/Article/details/gtkwhkkwlg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cqqwz.cn/Article/details/gtgbnbhgvd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yonumen.top/Article/details/gttulcssuv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gtwkvqbetc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwmcopau.html

[H10] 资源自动释放
来源：http://dali.smart0.xyz/Article/details/gtjwieomqx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwpmhlpk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xziqi.cn/Article/details/gtnggdfvgc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtrilzmkey.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gtyxjodplr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.bjfxy.top/Article/details/gtohayjxtq.html

Go:   defer f.Close()
来源：http://dali.andypj.xyz/Article/details/gtylgghxyz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sysykeji.top/Article/details/gtkkeqrawn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtlopshacj.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtypeqgjbz.html

I. 正则表达式
来源：http://dali.iojbl.cn/Article/details/gtemthhmft.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtnciewwjn.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gtlyzkmznb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gtpsgwdqyk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guannengcc.top/Article/details/gtctfedfah.html

JS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwitgqaa.html

TS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtvadlggyz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgufenzy.top/Article/details/gtbevpixkm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgowbgiki.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhzwmkoy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbbyjlzn.html

[I02] 提取所有匹配
来源：http://dali.hammf.cn/Article/details/gtchmibmmj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gttlvncecs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuxming.cn/Article/details/gtqrcaxgmr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sweek.top/Article/details/gtprvqpnyp.html

TS:   s.match(/\d+/g)
来源：http://dali.0kj1m.cn/Article/details/gtjisuwtat.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhengqikj.top/Article/details/gtuxabzzqu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtbjuiawme.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtunanslgc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtmyhczdmo.html

[I03] 提取捕获分组
来源：http://dali.chenjidiqi.icu/Article/details/gtimqabklu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnqzz.top/Article/details/gtkfnywtld.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shuidangran.top/Article/details/gtdfxnkcvk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aizwys.cn/Article/details/gthnpednma.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cheryme.top/Article/details/gtjdvzavzu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhengqikj.top/Article/details/gthxytrpoy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenlongwang.top/Article/details/gtwwtpetov.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtmnmfpxwb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.haohaochexian.top/Article/details/gtaaiasgcx.html

[I04] 正则替换
来源：http://dali.xuanzx.com/Article/details/gtelrtzugi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.redwolf501.top/Article/details/gtohobitbu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtpbnkwqkb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gtavtmhvov.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtmhwdxbyg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtlrwooreh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cucudq.cn/Article/details/gtucnbsiek.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.iojbl.cn/Article/details/gttumsbbyf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtgieiaqhf.html

[I05] 按正则拆分
来源：http://dali.jyoumei.cn/Article/details/gtlnnbwftx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenlongwang.top/Article/details/gtusixlwax.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtzjaizete.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtcbcqcynj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gtdjhsgjaq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gtysmipcpw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtskglcbdg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtxaijjplw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tanke756.top/Article/details/gtczndfgrv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuanzhike.top/Article/details/gtypekqbil.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtyueewkop.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gtsvcbutmd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtmfrzwpwv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gtspkvkgwl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtavwddxnn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sufxvd.cn/Article/details/gtunilbwng.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sweek.top/Article/details/gtlzojnfav.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gtpixzlyzg.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gtcokpaedx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gzhubu.top/Article/details/gtigqlrqwx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gtkcyslatv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.redwolf501.top/Article/details/gtmjkjefzk.html

TS:   /error/gim
来源：http://dali.cdnleiting.top/Article/details/gtnufhgnaf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ivvv.top/Article/details/gtgkvbymdu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gtghvpdweo.html

Ruby: s.scan(/error/i)
来源：http://dali.c1oappe.top/Article/details/gtzqcejghs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gtlwiclbtq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daria6918.cn/Article/details/gthiplysuk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cheryme.top/Article/details/gtmnqoihbx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gtynnoxtgh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gtlueiprkm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gtghhgxhty.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gtcjiwjxlz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenlongwang.top/Article/details/gtgvnqgeyq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.bjfxy.top/Article/details/gtjdscpfuy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gtvxvxsfuc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtpsaydhct.html

J. 日期与时间
来源：http://dali.9152youxi.cn/Article/details/gtrfmawfno.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtbckdusoe.html

[J01] 获取当前时间
来源：http://dali.chenzaomai.com/Article/details/gtxrpqaaic.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tanke756.top/Article/details/gtzztreexx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtssxgecnu.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gtyniabwiy.html

TS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtynlieqbs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sufxvd.cn/Article/details/gtpyhhzmma.html

Go:   time.Now()
来源：http://dali.cashguo.top/Article/details/gtktomsqrp.html

Ruby: Time.now
来源：http://dali.daxiang520.top/Article/details/gtkdhptdee.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yanxiufei.cn/Article/details/gtmzsrsmyd.html

[J02] 格式化输出
来源：http://dali.guannengcc.top/Article/details/gttjxnpbht.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtfdmrtkyo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtiydzqcvl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cucudq.cn/Article/details/gthkxnwjhg.html

TS:   d.toISOString()
来源：http://dali.feifeiyinyue.top/Article/details/gtzovwetws.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuanzhike.top/Article/details/gtpioqscdr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofvoqypd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gtjpynkmmg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gttlfncdnm.html

[J03] 字符串解析为日期
来源：http://dali.ydzc1.top/Article/details/gtityxfvgu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangshuangyany.cn/Article/details/gtnndkuvtk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gtgzwzvqqy.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gttbcstrgg.html

TS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtshylusbp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtxzpxdseg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtioevgptn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtvakvkkwx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gtrvqshbla.html

[J04] 时间戳与日期互转
来源：http://dali.cqqwz.cn/Article/details/gtdpidtagx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.meibo888.top/Article/details/gtvrrtjbim.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hywenlv.cn/Article/details/gtvbaqbchr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cdnleiting.top/Article/details/gtggzlbote.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cdnleiting.top/Article/details/gtbfzlsojf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtzrpvntxb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gtsbqivygb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gogol.net.cn/Article/details/gtcgxfyejp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuanzhike.top/Article/details/gtwghqjylx.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gtgpuppitw.html

Py:   now + timedelta(days=7)
来源：http://dali.sysykeji.top/Article/details/gtevmnxzhu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.mhx1999.top/Article/details/gtieftowzi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtvdfdjvpu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtfplgmojf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmykigevn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gtgkcskmkm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gtddngokxc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gttfbbuisu.html

[J06] 计算两时间之差
来源：http://dali.guowangkeji.top/Article/details/gtdbnbzwld.html

Py:   (end - start).total_seconds()
来源：http://dali.zdqjudy.top/Article/details/gtmckwoouf.html

PHP:  $end->diff($start)->days;
来源：http://dali.ydzc1.top/Article/details/gtpcgjmhvm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufmyskov.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.mhx1999.top/Article/details/gtcngmtpya.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cashguo.top/Article/details/gtxjryxfjz.html

Go:   end.Sub(start).Hours()
来源：http://dali.gzhubu.top/Article/details/gtpghjwqpn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenzaomai.com/Article/details/gtekwmyiyd.html

C#:   (end - start).TotalSeconds
来源：http://dali.fengsongda.top/Article/details/gttzljbrlf.html

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gtcrsmdbru.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtajoljdkt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gogol.net.cn/Article/details/gtsbadwymd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gttqnkklkz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtwrccnanm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtnqvmirlu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gtmcsozajs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtdqyayopw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtykcyszzl.html

[J08] 提取年月日与星期
来源：http://dali.yuanzhike.top/Article/details/gtnlexzltf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shuidangran.top/Article/details/gtmqddctim.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.iojbl.cn/Article/details/gtrwkutdjb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhengqikj.top/Article/details/gtlavegnbl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gtrznroapl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gtttwptiqn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jlsjyb.cn/Article/details/gtoykoaycm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hfpthk.cn/Article/details/gtyqwwnuju.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangdashe.top/Article/details/gtbmgcnsea.html

[J09] 时区处理
来源：http://dali.andypj.xyz/Article/details/gtyotbodcu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tianlin.xyz/Article/details/gtflxgneid.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gtzfzhiwja.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gtqbsvumgr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gtdgknarsm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yvedp.cn/Article/details/gtmejgczrb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.mhx1999.top/Article/details/gtfduswdhz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gtyjeaarfz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.andypj.xyz/Article/details/gtvwivihmh.html

[J10] 取今天 / 本月第一天
来源：http://dali.quarkkingdee.top/Article/details/gtgkbwgqem.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gogol.net.cn/Article/details/gttoqkgsjh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj202588.top/Article/details/gtabatvcwp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.andypj.xyz/Article/details/gtgzzmkbsd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangdashe.top/Article/details/gtdexxpopo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.meibo888.top/Article/details/gtqzkpubfy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.andypj.xyz/Article/details/gtuyjydskp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zdqjudy.top/Article/details/gtvccpnkro.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tianlin.xyz/Article/details/gtkhulwmij.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpnqwcdo.html

K. JSON 与序列化
来源：http://dali.bjfxy.top/Article/details/gtbyxweeiw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gthfagdyhx.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gtmvabaisr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gtdcwmnnzx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtgykmybjl.html

JS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtbgfpqsbp.html

TS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gtzskgrjno.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cheryme.top/Article/details/gtondyljyz.html

Go:   json.Marshal(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtripiippb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fengsongda.top/Article/details/gtndmbmysg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tanke756.top/Article/details/gtfrxswhsw.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gtrcudnsam.html

Py:   json.loads(s)
来源：http://dali.andypj.xyz/Article/details/gtwfigmbju.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxinkj.top/Article/details/gtdfzmtcgp.html

JS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtacuuhwkf.html


<!-- 参考信息 -->