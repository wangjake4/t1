代发 wailian999

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gtelxuiypl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yangfankeji.com/Article/details/gtmulxppsn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hfpthk.cn/Article/details/gtrzhsdihr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gthoascken.html

TS:   type User = { name: string; age: number };
来源：http://dali.sxryk.cn/Article/details/gthurfclqf.html

Java: record User(String name, int age) {}
来源：http://dali.kuanghao11.cn/Article/details/gtvscekdvm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.bjfxy.top/Article/details/gtrnmfxhrv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258.top/Article/details/gtlrbylvit.html

C#:   record User(string Name, int Age);
来源：http://dali.yvedp.cn/Article/details/gtytteaxkw.html

[G15] 枚举
来源：http://dali.yj202588.top/Article/details/gtzbroikvj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shuidangran.top/Article/details/gtttelbjxd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gtlmbpjkfp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yangfankeji.com/Article/details/gtkuwdyecf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtotuqjash.html

Java: enum Color { RED, GREEN }
来源：http://dali.fzhhl.top/Article/details/gtwfremxkv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.bjfxy.top/Article/details/gtlnboqket.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gtcljmzjqd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtazriimvh.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gtjxlnyrcz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnqzz.top/Article/details/gtkqcixmmb.html

PHP:  get_object_vars($obj);
来源：http://dali.kuanghao11.cn/Article/details/gtklkkwpqy.html

JS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gtllyemxbj.html

TS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gtmqejvmyu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigfzy.top/Article/details/gtoodkdqin.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuanzhike.top/Article/details/gtevuymayg.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gtbhicyotp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtsziqbyyl.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtsolhxmzl.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwsrihtu.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtwnrixnfn.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gtfxdpztun.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gtflzgudqo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.meibo888.top/Article/details/gtuplifgri.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtinfrulte.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtjiwrhqrt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuanzhike.top/Article/details/gtqnnvodke.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrwpxyel.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj202588.top/Article/details/gtnnbjojwj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gogol.net.cn/Article/details/gtkjtzybon.html

[H02] finally / ensure 收尾
来源：http://dali.tian-w.cn/Article/details/gtjvjirauq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.svipenyu.cn/Article/details/gtpfqbgyus.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtnvramsrq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gthltnupmw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gthdgtdacc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtkprtvjyf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cucudq.cn/Article/details/gtrkzwcmmx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gtzsmffksc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtkxrqcntz.html

[H03] 主动抛出异常
来源：http://dali.wangshuangyany.cn/Article/details/gtqdrwwvjt.html

Py:   raise ValueError("错误信息")
来源：http://dali.aizwys.cn/Article/details/gtjtsxezxh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtdekkcqja.html

JS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtwwiwoulj.html

TS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gttgvjlusn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtmxvkiglg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.birdmap.top/Article/details/gtiqjozwag.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gtqcknrymh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtzggjppug.html

[H04] 自定义异常类型
来源：http://dali.guannengcc.top/Article/details/gtpzofvvja.html

Py:   class MyError(Exception): pass
来源：http://dali.kuanghao11.cn/Article/details/gtgbijzijt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtzimqdbtz.html

JS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtdekrpcka.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtrtjwbuff.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbjuwccr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gtckcesmtv.html

Ruby: class MyError < StandardError; end
来源：http://dali.yvedp.cn/Article/details/gtshvsaokr.html

C#:   class MyException : Exception {}
来源：http://dali.zhoulong.xyz/Article/details/gtvwvmmymr.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gtcmxrzsve.html

Py:   except ValueError as e:
来源：http://dali.meibo888.top/Article/details/gtsjppjogc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuxming.cn/Article/details/gtpseiocef.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gtwzcmezpt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtjhhbjkre.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ppjwa.cn/Article/details/gtjqizxhod.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.c1oappe.top/Article/details/gtxcejnrjy.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gtogejjxsm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pycfn.com/Article/details/gtbxptudyt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hongshengwenyu.top/Article/details/gteiaxzwbu.html

Py:   value = d.get("k") or default
来源：http://dali.hammf.cn/Article/details/gtvoytcjqw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtuwwgbvzn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtwvrgcdzt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtgrjipgex.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gtjphlvixu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gtpavgmkfi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hfpthk.cn/Article/details/gtaaojjhym.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gtpgowfrgp.html

[H07] 断言
来源：http://dali.0kj1m.cn/Article/details/gtvncldeno.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhixingplan.top/Article/details/gtuulyhgbs.html

PHP:  assert($x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtgpffjjix.html

JS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtjdjpkftp.html

TS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtdjumycka.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hongshengwenyu.top/Article/details/gtykauprxs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gtzjoiejbe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guowangkeji.top/Article/details/gtatrybczv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gttwkccbfg.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258.top/Article/details/gtouthnfel.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gtvetvaxwm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gtxaooingh.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gteepibhfa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hongshengwenyu.top/Article/details/gtyrwkhybl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigfzy.top/Article/details/gttinjlvym.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtdujrhrwa.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gtgddmdluj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.snrcjt.cn/Article/details/gtpfkvldrh.html

[H09] 带错误码的异常
来源：http://dali.nwbrower.top/Article/details/gtmuolprbb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sweek.top/Article/details/gtmywqjpxg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sufxvd.cn/Article/details/gtvlevrgdm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gtjbkimajy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xziqi.cn/Article/details/gtvkrkuuuf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shuidangran.top/Article/details/gtlxuxuvkd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gtlvktpmob.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gzhubu.top/Article/details/gtjjowpqmv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xinyue.icu/Article/details/gtkhdanrox.html

[H10] 资源自动释放
来源：http://dali.yonumen.top/Article/details/gtnufadeaw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shangyingyoupin.top/Article/details/gtkyudfypu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gtketxrceq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtryhtzmtm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtyjuvpugp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuanzhike.top/Article/details/gtqhbteylw.html

Go:   defer f.Close()
来源：http://dali.fzhhl.top/Article/details/gtofymjwro.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.c1oappe.top/Article/details/gtznrggkcy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yonumen.top/Article/details/gtwdiafcrh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtmuyxvski.html

I. 正则表达式
来源：http://dali.xuanzx.com/Article/details/gtxizxhnsd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtkmiknbvl.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gtdllbfhek.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gtpzspkvoh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtjeszqobu.html

JS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtypdrdswg.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gtqhuggikx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenlongwang.top/Article/details/gtpeuddtpg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gtbljpiqmy.html

Ruby: s.match?(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtxalmmbjt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljxzvgkd.html

[I02] 提取所有匹配
来源：http://dali.chenlongwang.top/Article/details/gthgiajeqe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gtmtiyhcsx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dianchejie.cn/Article/details/gtmgvptzuv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dashuyun.cn/Article/details/gtdvoslueo.html

TS:   s.match(/\d+/g)
来源：http://dali.c1oappe.top/Article/details/gtuvcqngyt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.meibo888.top/Article/details/gtdidelxcn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fengsongda.top/Article/details/gtdsetimpo.html

Ruby: s.scan(/\d+/)
来源：http://dali.meibo888.top/Article/details/gtklkpejpl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtrwdnvixt.html

[I03] 提取捕获分组
来源：http://dali.jianghu66.top/Article/details/gtmpsswofo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gtwyuucvwg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cqqwz.cn/Article/details/gtxocaxhxr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzsiuooq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gtwhawpgmg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tianlin.xyz/Article/details/gtcjlwqcjt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenlongwang.top/Article/details/gtjuqipolu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gtvwvwfkbd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cheryme.top/Article/details/gthsqmefgi.html

[I04] 正则替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgyzylww.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ydzc1.top/Article/details/gtanildxcc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzgiiwmy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtczedbuvf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbpwrhub.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gtdcsukclb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hammf.cn/Article/details/gterwapvfd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtmyqczbfi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.316326.xyz/Article/details/gtgrvfqteu.html

[I05] 按正则拆分
来源：http://dali.snrcjt.cn/Article/details/gtdebwqylm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ivvv.top/Article/details/gtkqjmeotx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtktbmdxiu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtifkqdzez.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtzmozoixx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtfjbwttmc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gthhcizmak.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtriivswhw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohojptih.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dianchejie.cn/Article/details/gtqacdzqin.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtgsqyqhne.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guowangkeji.top/Article/details/gtbrpqrpxf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtumgnkpni.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtrnoqikvo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtdprtonib.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sysykeji.top/Article/details/gtdzzvluax.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuetiantiany.cn/Article/details/gtankfiblj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtgginkfdq.html

[I07] 忽略大小写与多行模式
来源：http://dali.ybcxt.top/Article/details/gtusifzctu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtortogkfp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtkxthxrem.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ehwqpu.com/Article/details/gtbvlwrmyu.html

TS:   /error/gim
来源：http://dali.havefunace.top/Article/details/gtzhdlrykt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jyoumei.cn/Article/details/gtxiikofrn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guannengcc.top/Article/details/gtygsviowf.html

Ruby: s.scan(/error/i)
来源：http://dali.zhixingplan.top/Article/details/gtlehbayig.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhiwuduotai.top/Article/details/gtiihtgfge.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ehwqpu.com/Article/details/gtoklmpaen.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xinyue.icu/Article/details/gtojjudlkv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gttpmjupnu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtoakuttxr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtimsjogqp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtimdbuupa.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.feifeiyinyue.top/Article/details/gthozwrnqd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hysaishi.cn/Article/details/gtvqfdkllb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gtmxgfszny.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtzomqgcya.html

J. 日期与时间
来源：http://dali.gaohongyu789.top/Article/details/gtbbesrhmp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtoqyqndnm.html

[J01] 获取当前时间
来源：http://dali.xuanzx.com/Article/details/gtfklqwizf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gtyafaixlt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gteotarxoa.html

JS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gtdiqlprzw.html

TS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtqgaidkkl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhongyouzk.top/Article/details/gtzousfbkc.html

Go:   time.Now()
来源：http://dali.hongshengwenyu.top/Article/details/gtvrroawdq.html

Ruby: Time.now
来源：http://dali.wangshuangyany.cn/Article/details/gtpdkegoko.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tian-w.cn/Article/details/gtphvehpph.html

[J02] 格式化输出
来源：http://dali.ivvv.top/Article/details/gtondeucfp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtfrivmvhv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gtuzbllcum.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzutuzevt.html

TS:   d.toISOString()
来源：http://dali.jinqigufen.top/Article/details/gtuelkeiam.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gtsyzryrmt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gtlsdrdhiq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gtmlbhzhmu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuanzhike.top/Article/details/gtdvfaipfb.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gthowhvkpc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhixingplan.top/Article/details/gtqgfyxkbx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.mhx1999.top/Article/details/gtkoawybvq.html

JS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtyttjgktk.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtstavhqxk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtqxoychvw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gttilvemcp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtzkaqjvsx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cucudq.cn/Article/details/gtbyyffrcr.html

[J04] 时间戳与日期互转
来源：http://dali.shzxlz.cn/Article/details/gthkmnamfy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.9152youxi.cn/Article/details/gtlayvuqcq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenlongwang.top/Article/details/gtgtouhltv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shzxlz.cn/Article/details/gtzxwhzsqn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daria6918.cn/Article/details/gtkvbjbnsb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.0kj1m.cn/Article/details/gtywejdyqr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tanke756.top/Article/details/gtawpwaxnl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtjgwoqamm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gtgukabpvb.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhiwuduotai.top/Article/details/gtailrprbr.html

Py:   now + timedelta(days=7)
来源：http://dali.gogol.net.cn/Article/details/gtniizgmdb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gtzsqsxejw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gtpgaotuci.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtusbonkwd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhengqikj.top/Article/details/gtjufvqqix.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shzxlz.cn/Article/details/gtwkkznlvl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gtnjqhtcie.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdwrhmxq.html

[J06] 计算两时间之差
来源：http://dali.jqgfzy.top/Article/details/gtjnvbyyyt.html

Py:   (end - start).total_seconds()
来源：http://dali.chenzaomai.com/Article/details/gtwewvvdsa.html

PHP:  $end->diff($start)->days;
来源：http://dali.tianlin.xyz/Article/details/gtyqyngmtn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ybcxt.top/Article/details/gtgtzgrmwk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gtlvtpwaxe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fzhhl.top/Article/details/gtuntnhagd.html

Go:   end.Sub(start).Hours()
来源：http://dali.nwbrower.top/Article/details/gtoiygoznp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gtgbwakwxg.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirzclesl.html

[J07] 比较两个日期
来源：http://dali.aibaodan.cn/Article/details/gtzsccvzoa.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtmzbopxfk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.svipenyu.cn/Article/details/gtaebomplp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtpdcouyqu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtpzwucckj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yvedp.cn/Article/details/gtsyaxjrjf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shuidangran.top/Article/details/gttpjnrnnz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtgpbgudqd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtqlcpgvnq.html

[J08] 提取年月日与星期
来源：http://dali.316326.xyz/Article/details/gtmvpiguun.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.vqdsnc.cn/Article/details/gtcjdbbkek.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yongpay.top/Article/details/gtchboawxk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.havefunace.top/Article/details/gthtgroeql.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gtdmgcpyhi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.vqdsnc.cn/Article/details/gtstppvjsq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gthxlfsqfa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yongpay.top/Article/details/gtgnpjsrmf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.redwolf501.top/Article/details/gtcvhtjnrp.html

[J09] 时区处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiuqnzlqg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guowangkeji.top/Article/details/gtukagnwib.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinyuanbaomall.cn/Article/details/gteuxtjlgg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtddgrgnsr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcogwbeak.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gtjvtjfdrj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhiwuduotai.top/Article/details/gtirbonucg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhoulong.xyz/Article/details/gtwyhnwywj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangshuangyany.cn/Article/details/gtkpyghmtw.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgufenzy.top/Article/details/gtgdnmjtkt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.redwolf501.top/Article/details/gtgmpzcncb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xylfe.cn/Article/details/gtjigxvcha.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xziqi.cn/Article/details/gtvutbokby.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gogol.net.cn/Article/details/gtpxlfovdk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuxming.cn/Article/details/gtrbmyywfq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hywenlv.cn/Article/details/gthglwqlqs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigfzy.top/Article/details/gthzecjcih.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aibaodan.cn/Article/details/gtbzslnvdh.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtwvbeznie.html

K. JSON 与序列化
来源：http://dali.chenjidiqi.icu/Article/details/gtblwmuzbm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtnlvipfll.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxinkj.top/Article/details/gtsmuujcfn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gtoougwkas.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gtkfyxgswy.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtlcyajcoj.html

TS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtqrtowaed.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yvedp.cn/Article/details/gtqxdtfyka.html

Go:   json.Marshal(obj)
来源：http://dali.yueranfly.top/Article/details/gtsljiptdq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jyoumei.cn/Article/details/gtxluqmngh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gtbezftisb.html


<!-- 参考信息 -->