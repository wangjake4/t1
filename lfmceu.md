代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.xziqi.cn/Article/details/gtmgejxsyq.html

Java: record User(String name, int age) {}
来源：http://dali.cqqwz.cn/Article/details/gtgxbeodil.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gogol.net.cn/Article/details/gtktpinslr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xziqi.cn/Article/details/gtkzjfycdi.html

C#:   record User(string Name, int Age);
来源：http://dali.yueranfly.top/Article/details/gtqwckbing.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gtviwedezr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gtifykwmbx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.quarkkingdee.top/Article/details/gtuoyonyoj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigufen.top/Article/details/gtbnadolhr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtawrkhrrt.html

Java: enum Color { RED, GREEN }
来源：http://dali.tianlin.xyz/Article/details/gtyviaeaal.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ppjwa.cn/Article/details/gtacukpyob.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jianghu66.top/Article/details/gtnctimrqo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gttayuyiow.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gtqkdywerq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhixingplan.top/Article/details/gtyhmfvqwr.html

PHP:  get_object_vars($obj);
来源：http://dali.yangfankeji.com/Article/details/gtdbzejphj.html

JS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtsnjidowl.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtqdabcdhi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yvedp.cn/Article/details/gtwbkvntay.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tanke756.top/Article/details/gtzquvarjy.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gtymmkxuvq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtlkbprsym.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtowwjufve.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gtvtdgecse.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtoejrfhqj.html

[H01] try / catch 基础
来源：http://dali.cashguo.top/Article/details/gtjcclbghv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtvsnsqtxx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gtxcwiibye.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtwpquibsg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtawbsgtfr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sufxvd.cn/Article/details/gtzimddusg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daxiang520.top/Article/details/gtftzyajrg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xziqi.cn/Article/details/gtlfzvqiqq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gtypxnaofn.html

[H02] finally / ensure 收尾
来源：http://dali.shangyingyoupin.top/Article/details/gtaisrazrd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gtqtnyjhiy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtzensulgl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtqnpvvvia.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtqvpyqnai.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtfdmzkeam.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.mhx1999.top/Article/details/gtvbaxwtjc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuanzhike.top/Article/details/gtqvqhmvfg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtcvzyaowp.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gtrdtppuru.html

Py:   raise ValueError("错误信息")
来源：http://dali.fzhhl.top/Article/details/gtspvzcvju.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtaenpnycp.html

JS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtbgpuesdb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtznpibpyz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtsdplepcq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gtteezhomm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gtlrlhlamf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtdlhidohb.html

[H04] 自定义异常类型
来源：http://dali.shangyingyoupin.top/Article/details/gteifizknb.html

Py:   class MyError(Exception): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybsikoae.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtmygtjaqh.html

JS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gtzygxqfwa.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtewfjxymy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsvfedbv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zycfv.cn/Article/details/gtcytzxmwz.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gttrehazwv.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gtgokdbipz.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjceomkor.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gtotilmzgb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shzxlz.cn/Article/details/gtlvtkmcci.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtynynwamw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtozifkoux.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtxcvjlzwl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pycfn.com/Article/details/gtattfmkrt.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gtikrnwlhc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.quarkkingdee.top/Article/details/gtlpvuvvtl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gtkofjdgpw.html

Py:   value = d.get("k") or default
来源：http://dali.hammf.cn/Article/details/gtujltnkyk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gtzglefrei.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtmyjwxzxw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtiglgznan.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yanxiufei.cn/Article/details/gtquyyksqx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gtthvdttqx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jlsjyb.cn/Article/details/gtuzhootpg.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuanzx.com/Article/details/gtxkayiyhj.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gtxkqroowd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cdnleiting.top/Article/details/gtmobwfnzr.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gtadqbetic.html

JS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtrvjozwuj.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtkuodbluj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.c1oappe.top/Article/details/gtywbeiwzy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.0kj1m.cn/Article/details/gtrlpvuzvg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pycfn.com/Article/details/gtgdlzgysy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtesermged.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhengqikj.top/Article/details/gtddweuabt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenzaomai.com/Article/details/gtljuodyky.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gtciufqlef.html

JS:   e.message;  e.stack
来源：http://dali.zhongyouzk.top/Article/details/gtihqauijo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gotoacloud.top/Article/details/gtgpluzlwr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxfbalvw.html

Go:   err.Error()
来源：http://dali.daxiang520.top/Article/details/gtxhkjaawa.html

Ruby: e.message;  e.backtrace
来源：http://dali.fengsongda.top/Article/details/gtarhdefwe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ivvv.top/Article/details/gtkvesyjzj.html

[H09] 带错误码的异常
来源：http://dali.sxryk.cn/Article/details/gtzqsgnabv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhixingplan.top/Article/details/gtoxjglhxp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.meibo888.top/Article/details/gtfnemlldf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gtjvarncvk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cashguo.top/Article/details/gtkmbjcwws.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hfpthk.cn/Article/details/gtnvpgtcsr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gtworsrctj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenzaomai.com/Article/details/gtgdoyqyoh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nwbrower.top/Article/details/gtxgmsxpxs.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gtihnzgetb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gtubwngfed.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pengpengdd.cyou/Article/details/gtzntsqibo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gtqgjtviwn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gtmyoefqyq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgfzy.top/Article/details/gtmwfyjorx.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gturzqosmj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhixingplan.top/Article/details/gtykuxeova.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.meibo888.top/Article/details/gtllcxtdxd.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtarlsjhom.html

I. 正则表达式
来源：http://dali.yj20258.top/Article/details/gtbshohnro.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtaldmclfh.html

[I01] 判断是否匹配
来源：http://dali.sufxvd.cn/Article/details/gtghfvcysn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gthtszwyhb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xziqi.cn/Article/details/gtxpqddxxe.html

JS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxupnlcw.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvbjpemn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.mhx1999.top/Article/details/gtwtccpqcg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yongpay.top/Article/details/gtilxjkjzv.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtchlrijxn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aizwys.cn/Article/details/gtotfjjqqo.html

[I02] 提取所有匹配
来源：http://dali.wangdashe.top/Article/details/gtuwnwddcw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gtfvdahjnu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ehwqpu.com/Article/details/gtyedceyks.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sxryk.cn/Article/details/gtsgrwkfub.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258.top/Article/details/gtnocjkfjh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gtapbfaejx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gtwcbxaitt.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtjobntqki.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.meibo888.top/Article/details/gtkiwaogkd.html

[I03] 提取捕获分组
来源：http://dali.yueranfly.top/Article/details/gtlfvdkuyn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtpkicdcru.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ydzc1.top/Article/details/gtrvgrlmec.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gtetmjrjyy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgufenzy.top/Article/details/gtzplnrmra.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hysaishi.cn/Article/details/gtnmyzsrjk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.quarkkingdee.top/Article/details/gtytbsfoxt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigfzy.top/Article/details/gtnrscfosg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aizwys.cn/Article/details/gtrjbckugm.html

[I04] 正则替换
来源：http://dali.jqgufenzy.top/Article/details/gtnprijfbj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gtnnnpgtah.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gtoisbyzwx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtoxnvgsnb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtmlobdwye.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtjuwsogdx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuanzx.com/Article/details/gtakyfbmar.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hfpthk.cn/Article/details/gthyxdfkxm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gtyczsrujb.html

[I05] 按正则拆分
来源：http://dali.sweek.top/Article/details/gtafwmgdtz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpazytiu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gthtfdrjmf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gttmhdbnfm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtchefwvnx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gzhubu.top/Article/details/gthcahyfuo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtwtxakzkx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtnsbrrhky.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtloqsonhh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guowangkeji.top/Article/details/gtilskzfal.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtxtszteth.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ehwqpu.com/Article/details/gtzknlognt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gtuzlnrotb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtkjsorzod.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtcgefuubb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.vqdsnc.cn/Article/details/gtpyezykle.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hywenlv.cn/Article/details/gtdcjrspyj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtosdzsvop.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gtxznfhoju.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ydzc1.top/Article/details/gtavmttlgb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gtbeaeoaqn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.bjfxy.top/Article/details/gtquaerckz.html

TS:   /error/gim
来源：http://dali.birdmap.top/Article/details/gtsdpqrohr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjhxpnin.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hywenlv.cn/Article/details/gtttcmprzz.html

Ruby: s.scan(/error/i)
来源：http://dali.yj202588.top/Article/details/gtgdjmgpxt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfygsqzkc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pycfn.com/Article/details/gtsegwoefm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ivvv.top/Article/details/gthkhzhorc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gtpezsdcvj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gtoqjrmtlo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gttgzzidms.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gtwzokletj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258888.top/Article/details/gtgspnrdut.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gtceysqqhe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gtkxzgkpsa.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtsfswdkec.html

J. 日期与时间
来源：http://dali.ybcxt.top/Article/details/gtwfamehkr.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofyiesys.html

[J01] 获取当前时间
来源：http://dali.yangfankeji.com/Article/details/gtrbtpbjjk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xziqi.cn/Article/details/gtcqhhrumd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gtdosoymiu.html

JS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtvfdrtuqf.html

TS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gtrygwhmfd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ydzc1.top/Article/details/gtziiepjnp.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gtpxtcpurf.html

Ruby: Time.now
来源：http://dali.zycfv.cn/Article/details/gtqniugzpo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.redwolf501.top/Article/details/gtclhiflrp.html

[J02] 格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gtjmwnnxyl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtlqlfmwgy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gtogwxecoe.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gtdgwmmxfz.html

TS:   d.toISOString()
来源：http://dali.pengpengdd.cyou/Article/details/gtssxlxsfq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gttwluxjxz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhongyouzk.top/Article/details/gtlyibqhdk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gtxgfmaeec.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gtczkjbjfk.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gtzuhskyvc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gtulmaiwsw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sweek.top/Article/details/gtszqkgmpt.html

JS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtqzbcwrfk.html

TS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtagmrrjem.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtelzlxsss.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtllufeutx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtcdenglyp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tanke756.top/Article/details/gtfbqecgai.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gtrohvayec.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sxryk.cn/Article/details/gtnftgumyg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gtapetshku.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.quarkkingdee.top/Article/details/gtbgguhfsl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yongpay.top/Article/details/gtgikgpinb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtevrapcfu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gtljqgywus.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gzhubu.top/Article/details/gtufnorrrg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtxxxoqmvm.html

[J05] 时间加减（加 7 天）
来源：http://dali.cqqwz.cn/Article/details/gtiuliicne.html

Py:   now + timedelta(days=7)
来源：http://dali.jianghu66.top/Article/details/gtuigahgaz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhengqikj.top/Article/details/gtlchxemma.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gtoxsgugua.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gtbzhlhkwi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yueranfly.top/Article/details/gtqoziztzb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtxwtcrqly.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xylfe.cn/Article/details/gtwylwcvgo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cucudq.cn/Article/details/gttzaglnct.html

[J06] 计算两时间之差
来源：http://dali.yj20258.top/Article/details/gtstgqxboo.html

Py:   (end - start).total_seconds()
来源：http://dali.guowangkeji.top/Article/details/gtwopzimqw.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gtbtyiqpto.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanatmahw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ivvv.top/Article/details/gtiyqfzmpu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxinkj.top/Article/details/gtsikieyqg.html

Go:   end.Sub(start).Hours()
来源：http://dali.yongpay.top/Article/details/gtgxbqvgxj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yanxiufei.cn/Article/details/gtzccciute.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhiwuduotai.top/Article/details/gtkdngkzme.html

[J07] 比较两个日期
来源：http://dali.hysaishi.cn/Article/details/gteugqxqkv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtbxctqwnw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.vqdsnc.cn/Article/details/gtpmxzuggb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtkumnmwwi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtnvaxlmop.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.quarkkingdee.top/Article/details/gtmfrgyzlr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsklybmyf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gttvntxziw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtjehtmxlu.html

[J08] 提取年月日与星期
来源：http://dali.tian-w.cn/Article/details/gtugodcacc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hammf.cn/Article/details/gtwmlhlnup.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.haohaochexian.top/Article/details/gtlxjiruvk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shangyingyoupin.top/Article/details/gtxijyuafz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuanzx.com/Article/details/gthmxgmzrh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yangfankeji.com/Article/details/gtacdqbtge.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guowangkeji.top/Article/details/gtfsdilrll.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cdnleiting.top/Article/details/gtqavcpxnl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cashguo.top/Article/details/gtmrnbljux.html

[J09] 时区处理
来源：http://dali.yj20258.top/Article/details/gtvdivawpg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ybcxt.top/Article/details/gthxuurjws.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.smart0.xyz/Article/details/gtdyymjeyg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gtacykqldi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtypctgpdv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yvedp.cn/Article/details/gtmojyryqy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.redwolf501.top/Article/details/gtahiesawa.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gtnexwsaiy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aizwys.cn/Article/details/gthzazrard.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gtyueqscpm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdeqbdrw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.birdmap.top/Article/details/gtogcwfnzk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nwbrower.top/Article/details/gtfoumjwpe.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtarwfruwn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gtfwsgtjer.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cheryme.top/Article/details/gtvtvmcnlj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gtpkadyken.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gtskswgpzq.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtjlekribh.html

K. JSON 与序列化
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxjpdgjq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtuqrgkwlj.html

[K01] 对象转 JSON 字符串
来源：http://dali.nwbrower.top/Article/details/gtcyfykknd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gtrcdabrwv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gtzaahgdik.html

JS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtxvhlrxwh.html

TS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtsuuczrdj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenlongwang.top/Article/details/gteheilsbd.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gtitnsjgvs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jlsjyb.cn/Article/details/gtibkkgvxp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gtjpwqylwi.html

[K02] JSON 字符串转对象
来源：http://dali.aizwys.cn/Article/details/gtwvdgvtbj.html

Py:   json.loads(s)
来源：http://dali.pycfn.com/Article/details/gtrorgoicl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gtsxwmrqpj.html

JS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtsaefgokd.html


<!-- 参考信息 -->