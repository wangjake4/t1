代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtrriglpuo.html

Ruby: def greet; @name; end
来源：http://dali.cdnleiting.top/Article/details/gtxekzkpiq.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gtftxdjcli.html

[G05] 继承
来源：http://dali.meibo888.top/Article/details/gtbwbysjtq.html

Py:   class Admin(User): pass
来源：http://dali.xziqi.cn/Article/details/gtpernqucs.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthallwuad.html

JS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtpfxfooxg.html

TS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtwjlszdve.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gttvppcafg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gtbiaimjuv.html

Ruby: class Admin < User; end
来源：http://dali.yanxiufei.cn/Article/details/gtvososjnl.html

C#:   class Admin : User {}
来源：http://dali.redwolf501.top/Article/details/gtnixlqsoj.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gtvuqhpuqz.html

Py:   def greet(self): return "admin"
来源：http://dali.hywenlv.cn/Article/details/gtborfmder.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtfpcoszik.html

JS:   greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtsmnhcspq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmwbnusxo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gthvichzbw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gtyfdvtssi.html

Ruby: def greet; "admin"; end
来源：http://dali.fengsongda.top/Article/details/gtxpggsupm.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gtztfhofcn.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gtbyjqlqyp.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gtvgkgvcwx.html

PHP:  parent::greet();
来源：http://dali.quarkkingdee.top/Article/details/gttmeopmmk.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtzqhvqnqf.html

TS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtsqbelotk.html

Java: super.greet();
来源：http://dali.yvedp.cn/Article/details/gtzylztqid.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hysaishi.cn/Article/details/gtnptwjgxt.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gtyydcitjj.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gtxcixfwln.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gtzttuyvgc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gtvplyrjwh.html

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtajtgcrgq.html

JS:   static f() {}
来源：http://dali.shuidangran.top/Article/details/gtcixsmhea.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gtxvfexfmc.html

Java: static void f() {}
来源：http://dali.dianchejie.cn/Article/details/gtltvhbzjf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nwbrower.top/Article/details/gtjihjftvh.html

Ruby: def self.f; end
来源：http://dali.0kj1m.cn/Article/details/gtcahqvyjx.html

C#:   public static void F() {}
来源：http://dali.guowangkeji.top/Article/details/gtuzihhyah.html

[G09] 接口 / 抽象类
来源：http://dali.ehwqpu.com/Article/details/gtdiqxmskr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhengqikj.top/Article/details/gtdpzqrlyx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dashuyun.cn/Article/details/gtofpjhbrk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ivvv.top/Article/details/gtzhvzssuv.html

TS:   interface Shape { area(): number; }
来源：http://dali.jianghu66.top/Article/details/gtoltatzpe.html

Java: interface Shape { double area(); }
来源：http://dali.hywenlv.cn/Article/details/gtccntglxb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gtnndnelyp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gthtlffier.html

C#:   interface IShape { double Area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokljzstp.html

[G10] 访问控制
来源：http://dali.iojbl.cn/Article/details/gtyxobfhey.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sxryk.cn/Article/details/gtsostpscw.html

PHP:  public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtrrdaekzy.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gthurnsnve.html

TS:   public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtaxeadpkm.html

Java: public / protected / private / 默认包级
来源：http://dali.pengpengdd.cyou/Article/details/gteuhyzmgc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.meibo888.top/Article/details/gtjlvcfosd.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtvckpcbqe.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gtxxbcnybu.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gtxtzgromx.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gtgscfokrf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtfwadjtbs.html

JS:   get name() { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gtfaeukcih.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtzbgcwwba.html

Java: public String getName() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtwfncwmut.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtqtrpwohr.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gtwmygfhpv.html

C#:   public string Name { get; set; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezcinfnl.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gtsvrplbkq.html

Py:   def __str__(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtciwjhsql.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtugnfncvc.html

JS:   toString() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtbbjjdkav.html

TS:   toString(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtuqvjahsu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtjkvwhzft.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtfwwoyelq.html

Ruby: def to_s; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtkezcqxdb.html

C#:   public override string ToString() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwudpmwid.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gtbqwxavtj.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gtbyrfhtsp.html

PHP:  $u instanceof User
来源：http://dali.sweek.top/Article/details/gtlqwnkuuy.html

JS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtvpepamhb.html

TS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqydzdez.html

Java: u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtzelujagk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guowangkeji.top/Article/details/gtjzbxczry.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gtrztoqsxb.html

C#:   u is User
来源：http://dali.dianchejie.cn/Article/details/gtrvupktet.html

[G14] 数据类 / record
来源：http://dali.haohaochexian.top/Article/details/gtlgeeegpq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgufenzy.top/Article/details/gtxebikvtb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jianghu66.top/Article/details/gtnjkavnzn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.havefunace.top/Article/details/gtrqxcyxym.html

TS:   type User = { name: string; age: number };
来源：http://dali.hfpthk.cn/Article/details/gtxwyqjalh.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gttoieliul.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gzhubu.top/Article/details/gtqqxibcoc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gtbsslubrb.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gtufwaojqd.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gtjbcknria.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gtalfbhvnz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.svipenyu.cn/Article/details/gtxuhwbjfl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gtjevygnvs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtjykbfzkx.html

Java: enum Color { RED, GREEN }
来源：http://dali.yongpay.top/Article/details/gtmgigdeyk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhengqikj.top/Article/details/gtggpxpwsv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.mhx1999.top/Article/details/gtywqxmblb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gtpepezqst.html

[G16] 对象转数组 / 字典
来源：http://dali.shuidangran.top/Article/details/gtxgkfdqzc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shzxlz.cn/Article/details/gtkkfkolba.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gtdsyyabez.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtzpjvxbun.html

TS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gthwzykckd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuanzhike.top/Article/details/gtzuhgiesi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gtbzfaaxku.html

Ruby: obj.instance_variables
来源：http://dali.jianghu66.top/Article/details/gtdrrjjpiw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtlywblqom.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gteiybuyro.html

H. 异常与错误处理
来源：http://dali.gaohongyu789.top/Article/details/gtxtzsqdhm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtyihwmodt.html

[H01] try / catch 基础
来源：http://dali.jinqigfzy.top/Article/details/gtbrrdrlpa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gtwkdyicsg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangdashe.top/Article/details/gtwdgnkjsh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtstijcype.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztcesreh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.andypj.xyz/Article/details/gtqfqqjemj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnqrpmjb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuanzx.com/Article/details/gtudnwxukl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxbjzozd.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gttaosjxhq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.quarkkingdee.top/Article/details/gtgyurfrxp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtontwmibb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtlxifmtyx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtzcdiilul.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtsspvldqn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sysykeji.top/Article/details/gtstvvvefq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.9152youxi.cn/Article/details/gtgxjqapwh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gthmalwgkj.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrqklzgp.html

Py:   raise ValueError("错误信息")
来源：http://dali.yueranfly.top/Article/details/gtkxejwuvg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtjolgzjoo.html

JS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtoreznmjg.html

TS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gtdugtzahp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtfannzagi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.quarkkingdee.top/Article/details/gtfbfuqyrq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tian-w.cn/Article/details/gtovtrznlg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtpgphhhtm.html

[H04] 自定义异常类型
来源：http://dali.sxryk.cn/Article/details/gtqfcefmgs.html

Py:   class MyError(Exception): pass
来源：http://dali.meibo888.top/Article/details/gtxwlffizn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtlfrqagbg.html

JS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtvfrgdomj.html

TS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunugysqv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtfyfmadye.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shangyingyoupin.top/Article/details/gtjlqybntm.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gtgmbsnoxb.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gtjzxaywqd.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gtcbmbegyx.html

Py:   except ValueError as e:
来源：http://dali.chenlongwang.top/Article/details/gtnrszifnz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cdnleiting.top/Article/details/gtbtfdaicb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gtgbniqosh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtjxalykqj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gtmgthfauo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gtkhzuqsub.html

Ruby: rescue ArgumentError => e
来源：http://dali.sxryk.cn/Article/details/gtovbrhokp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tanke756.top/Article/details/gthphsxhxh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aibaodan.cn/Article/details/gtjdqkodby.html

Py:   value = d.get("k") or default
来源：http://dali.smart0.xyz/Article/details/gtgovwbhdo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtoaxohjep.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gtyzrwbutx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtpofwiezr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gtvnsuzybo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gtyrpebbij.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jyoumei.cn/Article/details/gtvwnfxgon.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gtdejmkmvw.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gtxjfttrgh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yvedp.cn/Article/details/gtqkyxeiic.html

PHP:  assert($x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtkpzyedsc.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtejndyvzv.html

TS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtyzclaqvf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dianchejie.cn/Article/details/gtvypveyrg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gtdeujhqvj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.redwolf501.top/Article/details/gtrovoeykx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtirvidfvg.html

[H08] 获取错误信息与堆栈
来源：http://dali.sysykeji.top/Article/details/gtilidntla.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj202588.top/Article/details/gtbbwkxvgm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxoskwuay.html

JS:   e.message;  e.stack
来源：http://dali.hnxiangtu.top/Article/details/gtcgofqbky.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gtsnvmcebo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.bjfxy.top/Article/details/gttswabkig.html

Go:   err.Error()
来源：http://dali.chenjidiqi.icu/Article/details/gtqqozprdj.html

Ruby: e.message;  e.backtrace
来源：http://dali.yangfankeji.com/Article/details/gtlrpbydod.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrggjqvrs.html

[H09] 带错误码的异常
来源：http://dali.pengpengdd.cyou/Article/details/gtklkhzbsh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gtmpzgiiku.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gtycqwisbj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtseppgdvs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmoyvhhd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ehwqpu.com/Article/details/gtgiaocyqr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xylfe.cn/Article/details/gtmusqapoq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gtsunehgbf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gtdqqqapyb.html

[H10] 资源自动释放
来源：http://dali.cashguo.top/Article/details/gtuwbiqavu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xinyue.icu/Article/details/gtpizkojbg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shuidangran.top/Article/details/gtmmlkjgub.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gtjijvzqpw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gtcfhzrijn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenjidiqi.icu/Article/details/gtijjoylpq.html

Go:   defer f.Close()
来源：http://dali.zhiwuduotai.top/Article/details/gtpvizhhli.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gtlkclirbt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtxkgvywao.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtmrocatvs.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gtpqqdcstf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtyetbeakv.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gttupxahad.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtgjyjngyh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtslymfniy.html

JS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtdpqjeeyj.html

TS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtrhlxaers.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gtflgxqvqw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.andypj.xyz/Article/details/gtffdyeguw.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gtvnlvvjmc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.9152youxi.cn/Article/details/gtxwqcypdg.html

[I02] 提取所有匹配
来源：http://dali.yanxiufei.cn/Article/details/gtqfuvncym.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtzabadwlm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgufenzy.top/Article/details/gtjfooftyu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhengqikj.top/Article/details/gtsnuikiiv.html

TS:   s.match(/\d+/g)
来源：http://dali.wangdashe.top/Article/details/gtqtmtmwze.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.c1oappe.top/Article/details/gtrrgvvenp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nwbrower.top/Article/details/gtmkirdunq.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj202588.top/Article/details/gtoavokddv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtfaihrrvs.html

[I03] 提取捕获分组
来源：http://dali.xinyue.icu/Article/details/gtfgenhbqf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgufenzy.top/Article/details/gtzfbrpqsb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hfpthk.cn/Article/details/gtdrpohbfc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj202588.top/Article/details/gtxxjmcvos.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xziqi.cn/Article/details/gtkxlznnjj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hysaishi.cn/Article/details/gtflkwmtwu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.c1oappe.top/Article/details/gtbapgpjre.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuanzx.com/Article/details/gtnbluybyw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shuidangran.top/Article/details/gtpspqrcus.html

[I04] 正则替换
来源：http://dali.yuanzhike.top/Article/details/gtyjfbbsyw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgfzy.top/Article/details/gtfacuunnv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwuibops.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gtjnyobjzs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gtqenjvgbi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtdbxihwna.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtctykyiyn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnpalmwn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gtyspvjacj.html

[I05] 按正则拆分
来源：http://dali.tian-w.cn/Article/details/gtgkzbszle.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shzxlz.cn/Article/details/gtnkucdtza.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtejhmskss.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtjojqsyws.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtkevoviak.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258.top/Article/details/gtkatzupvi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gtnmtzmmwg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtqwgyblvt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgfzy.top/Article/details/gtfzvdhvyt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.9152youxi.cn/Article/details/gtzulzevxx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtotetdtwr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ehwqpu.com/Article/details/gteuavpscq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkfzcnya.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtowmdmiyq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnoeubxdv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hysaishi.cn/Article/details/gtrstmykta.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenzaomai.com/Article/details/gtrudjokbu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtpcijklik.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigfzy.top/Article/details/gtyasqrmmr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zycfv.cn/Article/details/gtvmzxydng.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pycfn.com/Article/details/gttnfhgcud.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gtljcwnzrd.html

TS:   /error/gim
来源：http://dali.9152youxi.cn/Article/details/gtaiigxcfe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xylfe.cn/Article/details/gthjursabe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnxiangtu.top/Article/details/gtniuxcnde.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gtlbsbrrbj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.9152youxi.cn/Article/details/gtkwobgxlm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dashuyun.cn/Article/details/gtslkpzzln.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hysaishi.cn/Article/details/gtoqpnnemt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtecwntzxh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtkwcfaxtw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gtpiseexzk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtjvhhismv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqvzupyz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hongshengwenyu.top/Article/details/gtxbmsnjod.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gttliowtkx.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtiqdpkcjk.html

J. 日期与时间
来源：http://dali.sysykeji.top/Article/details/gthmshnexl.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtnshghgks.html

[J01] 获取当前时间
来源：http://dali.jqgufenzy.top/Article/details/gtrxgiyiwm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aizwys.cn/Article/details/gtstnjwphp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtidfanwgn.html

JS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gtzzypldtn.html

TS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtibwzwjkm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtncnwiysu.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gtomnartfb.html

Ruby: Time.now
来源：http://dali.ydzc1.top/Article/details/gtbwufnetl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhongyouzk.top/Article/details/gtcnycgqxq.html

[J02] 格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzlhlxzv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvkrywvt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtxbkdkcdv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258.top/Article/details/gtevjcnftz.html

TS:   d.toISOString()
来源：http://dali.yuanzhike.top/Article/details/gtuxlihcxl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.kuanghao11.cn/Article/details/gtvtgeypfq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchbvxefg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtxhrkqlwd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258888.top/Article/details/gtmtllzqiw.html


<!-- 参考信息 -->