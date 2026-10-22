代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gtonmjkvqm.html

Ruby: def self.f; end
来源：http://dali.jinqigufen.top/Article/details/gtkqtxavuk.html

C#:   public static void F() {}
来源：http://dali.meibo888.top/Article/details/gtekwhadeh.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gtnnfuoxxg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sweek.top/Article/details/gttchgdguf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.9152youxi.cn/Article/details/gtcalkvdtu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangtech.top/Article/details/gtaohubeyl.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gtjniqctec.html

Java: interface Shape { double area(); }
来源：http://dali.birdmap.top/Article/details/gtunwqpfjr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gthyycjtnx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gtzoxyabyb.html

C#:   interface IShape { double Area(); }
来源：http://dali.sufxvd.cn/Article/details/gtcowkwsap.html

[G10] 访问控制
来源：http://dali.andypj.xyz/Article/details/gtvpuxerqp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gtqdknltgg.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtechdswtm.html

JS:   #private 字段；其余公开
来源：http://dali.shzxlz.cn/Article/details/gtfszxximi.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbtbftop.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gtqrissziw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nwbrower.top/Article/details/gtfdaynncz.html

Ruby: public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtkieeywje.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gtxknpeqfh.html

[G11] getter / setter
来源：http://dali.quarkkingdee.top/Article/details/gtbypnjyfg.html

Py:   @property 与 @x.setter
来源：http://dali.fengsongda.top/Article/details/gtkvcicivh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtbpyqhriv.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtwsowrmww.html

TS:   get name(): string { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtrsnorrwy.html

Java: public String getName() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtsasnlimi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtaudhjgjg.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gtilhsgoxe.html

C#:   public string Name { get; set; }
来源：http://dali.0kj1m.cn/Article/details/gtwolwfbgz.html

[G12] 对象转字符串
来源：http://dali.sysykeji.top/Article/details/gtxfcnspwi.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtdrnibirp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtwzrjefzo.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtgctwxshw.html

TS:   toString(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtisrcgtbi.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtqiasisls.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtxoomatma.html

Ruby: def to_s; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtdsswnkwc.html

C#:   public override string ToString() => Name;
来源：http://dali.ydzc1.top/Article/details/gthlzydrdv.html

[G13] 判断对象类型
来源：http://dali.hnqzz.top/Article/details/gtzhrharue.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gtskcgygrm.html

PHP:  $u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtwigoaekf.html

JS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtmedapbiq.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtoazujoqz.html

Java: u instanceof User
来源：http://dali.tanke756.top/Article/details/gtpiwryofr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cdnleiting.top/Article/details/gtsawuoyfe.html

Ruby: u.is_a?(User)
来源：http://dali.yvedp.cn/Article/details/gtdleeewxe.html

C#:   u is User
来源：http://dali.jianghu66.top/Article/details/gtqdyrbfcz.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gtvzuinqvs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuxming.cn/Article/details/gtmedijqjs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daxiang520.top/Article/details/gtxoiihzxk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gtqnrfmzdw.html

TS:   type User = { name: string; age: number };
来源：http://dali.dashuyun.cn/Article/details/gtfkcasvux.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gtgitcaoef.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gtxqsiryib.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sysykeji.top/Article/details/gtfhuoqdzs.html

C#:   record User(string Name, int Age);
来源：http://dali.daxiang520.top/Article/details/gtcaohxbgf.html

[G15] 枚举
来源：http://dali.meibo888.top/Article/details/gtggpywvuw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gttyaltzxg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhongyouzk.top/Article/details/gtkiewknns.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zycfv.cn/Article/details/gttwenxxrz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gtynlcxbvx.html

Java: enum Color { RED, GREEN }
来源：http://dali.c1oappe.top/Article/details/gtcyegmzvj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gtoitdkovv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.vqdsnc.cn/Article/details/gtavtzqgld.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtrpkizvbg.html

[G16] 对象转数组 / 字典
来源：http://dali.daria6918.cn/Article/details/gtcrfxkyyz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgufenzy.top/Article/details/gtvbgprkan.html

PHP:  get_object_vars($obj);
来源：http://dali.quarkkingdee.top/Article/details/gtswrpzecv.html

JS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtonraljpg.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtmyokcfwc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ivvv.top/Article/details/gtdiiuhqeg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jiagoushi.top/Article/details/gteyzdvvsp.html

Ruby: obj.instance_variables
来源：http://dali.sxryk.cn/Article/details/gtdnklkcab.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtebqfspvo.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtsksqegxt.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gtjaioaeye.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtctrqmirg.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gtbtqapehl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gtilqtctmx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guowangkeji.top/Article/details/gtqwjaollu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtzwngxpqb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtcrkvawag.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangdashe.top/Article/details/gtdoevttgu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.redwolf501.top/Article/details/gtsdmmbsiz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sufxvd.cn/Article/details/gtehhtqeue.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.smart0.xyz/Article/details/gtqvpzovux.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gtrtjntadf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gtlbwjgijz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtkgtdmpnd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtfulobhay.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtuodrayrq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gteycliqjc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.meibo888.top/Article/details/gtrnlpqsns.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gttvwukkti.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtcnwaieej.html

[H03] 主动抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtrvnawpbg.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenjidiqi.icu/Article/details/gtuiwrxwdn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtnlrznqvh.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtwmzgleae.html

TS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtqxusfuoz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtzlzmwigm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hammf.cn/Article/details/gtqepfbnhz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gtxhjmplos.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtusjefxpc.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gtbasafsou.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gthgbbqxyz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtzxscxevg.html

JS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gtrignrvcl.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gtrxbxqskp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtrorzagsk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yanxiufei.cn/Article/details/gtdkwvirwv.html

Ruby: class MyError < StandardError; end
来源：http://dali.xylfe.cn/Article/details/gtowvxktcl.html

C#:   class MyException : Exception {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtdxxwts.html

[H05] 捕获特定类型
来源：http://dali.zycfv.cn/Article/details/gtavwdiemi.html

Py:   except ValueError as e:
来源：http://dali.chenjidiqi.icu/Article/details/gtolxeyvow.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.c1oappe.top/Article/details/gtmztzjdxm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtnjnoqvre.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtjhzvejnx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.vqdsnc.cn/Article/details/gtbkbqjlwv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yonumen.top/Article/details/gtukqfkhxd.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gtqmkwuwwz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hywenlv.cn/Article/details/gtszddfbiz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.c1oappe.top/Article/details/gtckarezib.html

Py:   value = d.get("k") or default
来源：http://dali.haohaochexian.top/Article/details/gtkflyfjml.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gtvykmfuln.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtzcoubkam.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtmolvgujd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwbyuhmy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ehwqpu.com/Article/details/gtouxtuuih.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gtzywnnyjn.html

C#:   obj?.A?.B ?? default
来源：http://dali.xinyue.icu/Article/details/gtseoorjgx.html

[H07] 断言
来源：http://dali.zhongyouzk.top/Article/details/gtvljktbgt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gtxryxenjf.html

PHP:  assert($x > 0);
来源：http://dali.fzhhl.top/Article/details/gtiktffzni.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtscxfplky.html

TS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtlqxzbwpq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuxming.cn/Article/details/gtnpetrzho.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhongyouzk.top/Article/details/gtralxvabv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jianghu66.top/Article/details/gtzzbohdjk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtzwxelynx.html

[H08] 获取错误信息与堆栈
来源：http://dali.9152youxi.cn/Article/details/gtglsbdmwx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.c1oappe.top/Article/details/gtxkkrsfyh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gtondogvuk.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gtfauhobfu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gtkuvgowcs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gtcyimuire.html

Go:   err.Error()
来源：http://dali.jinqigufen.top/Article/details/gthqzqiitw.html

Ruby: e.message;  e.backtrace
来源：http://dali.sxryk.cn/Article/details/gtzedkxdvr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzikdvzl.html

[H09] 带错误码的异常
来源：http://dali.ydzc1.top/Article/details/gtwalglxph.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jianghu66.top/Article/details/gtgutscbnn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.9152youxi.cn/Article/details/gtokeojtho.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenzaomai.com/Article/details/gtvcgedehq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hfpthk.cn/Article/details/gtrurfugdx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj202588.top/Article/details/gtseasoqpn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ehwqpu.com/Article/details/gtlkebcbnc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pycfn.com/Article/details/gtrxwazwos.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gtfevlndpz.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gtgspzchbh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.quarkkingdee.top/Article/details/gtdqnsuhcy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hongshengwenyu.top/Article/details/gtmicaufzn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtxwogsifc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtwkojjgry.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cucudq.cn/Article/details/gtimzjlahg.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gtweeegvcv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjfjneul.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwonqjpjv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtmvzheqyk.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gtmqncbout.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtnmwsqckm.html

[I01] 判断是否匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtlbqyfjob.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gtbyjmpodm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cashguo.top/Article/details/gtjuzjrffr.html

JS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gtwciajscp.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzcytubq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daria6918.cn/Article/details/gtogyfiufc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pycfn.com/Article/details/gtrsgdrjag.html

Ruby: s.match?(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gtaezrxirl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gtxizeeldc.html

[I02] 提取所有匹配
来源：http://dali.vqdsnc.cn/Article/details/gtwcvnescb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gtxswngrzs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.316326.xyz/Article/details/gtlizfsofv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.bjfxy.top/Article/details/gtpydrevhh.html

TS:   s.match(/\d+/g)
来源：http://dali.zhixingplan.top/Article/details/gtrmymqwiv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gotoacloud.top/Article/details/gtzcbodmji.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtpzhzjqwj.html

Ruby: s.scan(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gtwlgijoyk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.mhx1999.top/Article/details/gtswskrvdg.html

[I03] 提取捕获分组
来源：http://dali.snrcjt.cn/Article/details/gthtoawcgg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ydzc1.top/Article/details/gttwiegsyr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cdnleiting.top/Article/details/gttxbbmiyw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cdnleiting.top/Article/details/gtlzsamtxf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.316326.xyz/Article/details/gtnhluenyx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gtuaufjdob.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shangyingyoupin.top/Article/details/gtskwakgxs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenlongwang.top/Article/details/gtzzpuuojf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxinkj.top/Article/details/gtujwqdfad.html

[I04] 正则替换
来源：http://dali.hywenlv.cn/Article/details/gtoadmeqyy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gtbjpsdjud.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtflpbqnnb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gtjatlpxdf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gthmcussob.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gtkxtibfzh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtucnmksjg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pycfn.com/Article/details/gtbmiwipxb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtazxieqym.html

[I05] 按正则拆分
来源：http://dali.cqqwz.cn/Article/details/gtosjhotnw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ivvv.top/Article/details/gtaacedwqc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtroglwubk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtctepkcyv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtlywwssre.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yangfankeji.com/Article/details/gtuwudhbpq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cashguo.top/Article/details/gtlpsfseta.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gthtdasgsd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsshktmxh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shuidangran.top/Article/details/gtgxmjnwkm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtdglwrcgg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pengpengdd.cyou/Article/details/gtckpcsrjr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtitschlhg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gtebqdipyo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtfudborrz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.svipenyu.cn/Article/details/gtgvukblre.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhoulong.xyz/Article/details/gtsnbvffzg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtvyzbdgib.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gtqarnwwdb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.smart0.xyz/Article/details/gtskapyztu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtzsoeomqx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ppjwa.cn/Article/details/gtnqskkuzg.html

TS:   /error/gim
来源：http://dali.dashuyun.cn/Article/details/gtfnoretya.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangdashe.top/Article/details/gtzcltrtfd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgufenzy.top/Article/details/gtaffccoox.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gtpwvwrils.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gtwdsxjsso.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavgzljxc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.c1oappe.top/Article/details/gtdsmszsxc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gtmpmlgkhf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gtfrvpucmt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gtwrnxuvmo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gtolcivaqv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hysaishi.cn/Article/details/gtkicngzcj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hfpthk.cn/Article/details/gtezoyricn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gtuoomndnv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtehrocfyw.html

J. 日期与时间
来源：http://dali.snrcjt.cn/Article/details/gttbzvcztj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtecdqkpcs.html

[J01] 获取当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gtvatntzeb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tian-w.cn/Article/details/gtohbfvfoa.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtutyudrdg.html

JS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gtztesiuvr.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtcsrymoev.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yongpay.top/Article/details/gtjjtzlxof.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gtfyxpluel.html

Ruby: Time.now
来源：http://dali.yj20258888.top/Article/details/gtmtjklili.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cashguo.top/Article/details/gtzianhbzb.html

[J02] 格式化输出
来源：http://dali.daria6918.cn/Article/details/gtwppximxd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gtqdkcznds.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gtsvyexnad.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilrzjyzx.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxakgzalr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gtsinxezxj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cqqwz.cn/Article/details/gtnnlvepnm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtbqbhcifd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gtsunbfgox.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gtnuywpwyw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gtprichphu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinghuilouyu.cn/Article/details/gtuaxoasre.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtncrwogoy.html

TS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtgkdbeffw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtccrjotpc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtxzflvlmo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtcrayvvni.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnxiangtu.top/Article/details/gtraxapzob.html

[J04] 时间戳与日期互转
来源：http://dali.aizwys.cn/Article/details/gtybxhvvbz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.meibo888.top/Article/details/gtasfrapud.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangdashe.top/Article/details/gtqryayooq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cdnleiting.top/Article/details/gtlolkylxo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yangfankeji.com/Article/details/gtgihqminc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtsfbnwnte.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258.top/Article/details/gtvnwocmyo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yonumen.top/Article/details/gtyhyajpnv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gtuwxpqvkj.html

[J05] 时间加减（加 7 天）
来源：http://dali.haohaochexian.top/Article/details/gtfbpiitmj.html

Py:   now + timedelta(days=7)
来源：http://dali.ydzc1.top/Article/details/gtwkhprtsw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ppjwa.cn/Article/details/gtsbgapwsz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gtxtlerkhl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gtnykcaudi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.svipenyu.cn/Article/details/gtlfwgjvlx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhongyouzk.top/Article/details/gtdpaffqgy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangdashe.top/Article/details/gtteevgtrv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.mhx1999.top/Article/details/gtuxzbejsd.html

[J06] 计算两时间之差
来源：http://dali.cdnleiting.top/Article/details/gtnqlieaxi.html

Py:   (end - start).total_seconds()
来源：http://dali.jianghu66.top/Article/details/gtmnxpazws.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gtdgaodtkb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pengpengdd.cyou/Article/details/gtwdjzwvru.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuanzx.com/Article/details/gteyfpdfrl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxinkj.top/Article/details/gtwyvyucjd.html

Go:   end.Sub(start).Hours()
来源：http://dali.guowangkeji.top/Article/details/gtzzqhcnae.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gtxvgtxqya.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gtjatdxmfb.html


<!-- 参考信息 -->