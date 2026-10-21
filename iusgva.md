代发 wailian999

Java: class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtklbklylx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenlongwang.top/Article/details/gtlkkfecap.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtncloeoda.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gtrjjlumtr.html

[G06] 重写方法
来源：http://dali.zdqjudy.top/Article/details/gtbaddmqui.html

Py:   def greet(self): return "admin"
来源：http://dali.zhongyouzk.top/Article/details/gtsuhqjfpl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtgvtdpqio.html

JS:   greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtqshkmzsm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtaklmnvyn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtmbxapbyy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.bjfxy.top/Article/details/gtkjdstoti.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gthjxdrxct.html

C#:   public override string Greet() => "admin";
来源：http://dali.sweek.top/Article/details/gtrypvdejt.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gturktlgju.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgmonkfb.html

PHP:  parent::greet();
来源：http://dali.svipenyu.cn/Article/details/gtlbervloi.html

JS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtktnswytp.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtzkqbwgmp.html

Java: super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtodfbdgwg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yongpay.top/Article/details/gtbkxffegy.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gtppjqvssh.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gtgfzwrkbu.html

[G08] 静态方法与属性
来源：http://dali.guowangkeji.top/Article/details/gtyrdhlhoz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aizwys.cn/Article/details/gtnmzmlxaw.html

PHP:  public static function f() {}
来源：http://dali.hysaishi.cn/Article/details/gtiwctnism.html

JS:   static f() {}
来源：http://dali.guannengcc.top/Article/details/gtiniswtun.html

TS:   static f(): void {}
来源：http://dali.guowangkeji.top/Article/details/gtuuzrttve.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gtzgnjsbnd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.svipenyu.cn/Article/details/gtsudgowqd.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gtwrvafpkr.html

C#:   public static void F() {}
来源：http://dali.zhoulong.xyz/Article/details/gtkstykeqv.html

[G09] 接口 / 抽象类
来源：http://dali.tanke756.top/Article/details/gtgorgnekf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhongyouzk.top/Article/details/gtjczxvloc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnxiangtu.top/Article/details/gtaaqdzqtn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fzhhl.top/Article/details/gtevosuhek.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpxrewehs.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtnzpfkeok.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ydzc1.top/Article/details/gtmzhnrrnr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwyfuuob.html

C#:   interface IShape { double Area(); }
来源：http://dali.iojbl.cn/Article/details/gtcttswywj.html

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gtglnvevln.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gtpxaysrlg.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtjlytblbi.html

JS:   #private 字段；其余公开
来源：http://dali.hongshengwenyu.top/Article/details/gtzjsoweco.html

TS:   public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtaqmiaddh.html

Java: public / protected / private / 默认包级
来源：http://dali.wangdashe.top/Article/details/gtlnaietzs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigfzy.top/Article/details/gtbibfxood.html

Ruby: public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtitdsebgl.html

C#:   public / protected / private / internal
来源：http://dali.birdmap.top/Article/details/gtyptznwpb.html

[G11] getter / setter
来源：http://dali.zhiwuduotai.top/Article/details/gthdrqqahh.html

Py:   @property 与 @x.setter
来源：http://dali.xuetiantiany.cn/Article/details/gtakdltelz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gttimgvbhw.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtgqthiljd.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtpslrdjtf.html

Java: public String getName() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtflsuqjir.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtjngiqnzs.html

Ruby: attr_accessor :name
来源：http://dali.iojbl.cn/Article/details/gtjwtemder.html

C#:   public string Name { get; set; }
来源：http://dali.andypj.xyz/Article/details/gtldtboswk.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtszkiqccs.html

Py:   def __str__(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtkvxhkjau.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtczisjcli.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtbaopbsva.html

TS:   toString(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtyxrtwfdn.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtlgpsjhdp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtbgvpfjtz.html

Ruby: def to_s; @name; end
来源：http://dali.sufxvd.cn/Article/details/gtlmxbgbfu.html

C#:   public override string ToString() => Name;
来源：http://dali.mhx1999.top/Article/details/gtvzqufggq.html

[G13] 判断对象类型
来源：http://dali.chenjidiqi.icu/Article/details/gtwqohhjzy.html

Py:   isinstance(u, User)
来源：http://dali.yj20258.top/Article/details/gtailwursb.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsvyrqam.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfscfuxft.html

TS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gttbgviain.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtgymlhuwo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.iojbl.cn/Article/details/gtdcmqzvlx.html

Ruby: u.is_a?(User)
来源：http://dali.xziqi.cn/Article/details/gtkpdgcyys.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gtwoghhlgy.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gtdquapryd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gtkvxkwegi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gtqzlptrrw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tianlin.xyz/Article/details/gtflngazys.html

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gthvqzzlia.html

Java: record User(String name, int age) {}
来源：http://dali.tanke756.top/Article/details/gtxtzmmnyb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj202588.top/Article/details/gtidclamct.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenlongwang.top/Article/details/gtpfgcaxyz.html

C#:   record User(string Name, int Age);
来源：http://dali.pengpengdd.cyou/Article/details/gtclrcqtnx.html

[G15] 枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtlvwieblr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gzhubu.top/Article/details/gtuslglpkq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgufenzy.top/Article/details/gtcaqxzesj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhixingplan.top/Article/details/gtzhxsvfip.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtflgtxamb.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gtfuoocmet.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.meibo888.top/Article/details/gtgzumncip.html

Ruby: Color = %i[red green].freeze
来源：http://dali.mhx1999.top/Article/details/gtadbuihqn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gtbsmkgnbt.html

[G16] 对象转数组 / 字典
来源：http://dali.zhengqikj.top/Article/details/gtcchbbjbw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgufenzy.top/Article/details/gtvjxygmok.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gtulgsktss.html

JS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtzwbvxvmm.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtffhkdbnb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyurymhns.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gtchbhmgvn.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gtvhzhdafe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtbqovcckw.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtqzbtwkiu.html

H. 异常与错误处理
来源：http://dali.tianlin.xyz/Article/details/gtxxsetcwf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtzdhpcilw.html

[H01] try / catch 基础
来源：http://dali.zhoulong.xyz/Article/details/gtqfgmhnoe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gtbzvrxixr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fengsongda.top/Article/details/gttzabojtu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtbyojqsvl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtawaqyxlj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigufen.top/Article/details/gtimkixwaq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gtgfisseqq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hywenlv.cn/Article/details/gtwafzvhqk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gtqwrxtbac.html

[H02] finally / ensure 收尾
来源：http://dali.hfpthk.cn/Article/details/gtogltqfhq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gtwegntqzd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtcvhniiaw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtsuiegpqr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtpcoetjpi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtzegrfcii.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gtziucnudz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gtnevxhhjt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtycdmfcwl.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsiqdjrh.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnqzz.top/Article/details/gtfgwulxbs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gticnvrakl.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtlddghdam.html

TS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtzwssetrh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtqbpdzyjj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yongpay.top/Article/details/gtcfndxvel.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gtidknlrfv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtjtbttnww.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gtjdsybdoo.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gtxkfaetuq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtjatpbpta.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gtksolhtph.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtyrdwegng.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gticotcitp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangdashe.top/Article/details/gtdcdcoyjb.html

Ruby: class MyError < StandardError; end
来源：http://dali.guannengcc.top/Article/details/gtiwipoijo.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258.top/Article/details/gtljbkjfvz.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjqdilys.html

Py:   except ValueError as e:
来源：http://dali.svipenyu.cn/Article/details/gthfxhzwev.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gtqshdktpj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gtxozjyxyd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtnkmvhzkt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.0kj1m.cn/Article/details/gtdudderml.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj202588.top/Article/details/gthdxsszup.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gtlbtynpjz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dianchejie.cn/Article/details/gtdpzzuwuz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenlongwang.top/Article/details/gttftqivjg.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gtacyjrorc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gtdjqwxkpu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtozkhubpc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtaqjshlhb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gttxacfewj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yueranfly.top/Article/details/gtmsnauezf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dianchejie.cn/Article/details/gtnshxbuaj.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuanzhike.top/Article/details/gtzxxexbfp.html

[H07] 断言
来源：http://dali.guowangkeji.top/Article/details/gttsffovwf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgfzy.top/Article/details/gtvgzuavqf.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtdjzorqfv.html

JS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtrvzqxegn.html

TS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gthhvrmrfa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gthjvipjhu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.smart0.xyz/Article/details/gtrcnxmsff.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258888.top/Article/details/gtbolbcoui.html

C#:   Debug.Assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtnywqrkqi.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtenfmwp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gtyivwrgwl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tianlin.xyz/Article/details/gtonkyuxqe.html

JS:   e.message;  e.stack
来源：http://dali.wangdashe.top/Article/details/gtvsczsjgs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.c1oappe.top/Article/details/gtzrvymfpk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cqqwz.cn/Article/details/gtzcnwifcd.html

Go:   err.Error()
来源：http://dali.zycfv.cn/Article/details/gteoogngzq.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gttkrdbdny.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangdashe.top/Article/details/gtqyiymjqy.html

[H09] 带错误码的异常
来源：http://dali.ydzc1.top/Article/details/gtrqbbuorv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pengpengdd.cyou/Article/details/gtvvmsgtsy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jlsjyb.cn/Article/details/gtuvlqmpas.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gtghvqdxkh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvjltdij.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenlongwang.top/Article/details/gtmunshlja.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tianlin.xyz/Article/details/gtokrwxonf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tanke756.top/Article/details/gtqarpweea.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtauasctmu.html

[H10] 资源自动释放
来源：http://dali.guannengcc.top/Article/details/gtxmyrgclv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sysykeji.top/Article/details/gtnfsmlwtn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nwbrower.top/Article/details/gtrokyojwb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtviekukgt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtrglwlere.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gteitxdofd.html

Go:   defer f.Close()
来源：http://dali.tian-w.cn/Article/details/gtocfnqwdg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlokwrofz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtirshkcej.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtvygsgmwy.html

I. 正则表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvtywhob.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtbukompxt.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gtqaytljfv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gtadlnhipv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cheryme.top/Article/details/gtcpidurjg.html

JS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtvzoqslog.html

TS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmalfhagn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhoulong.xyz/Article/details/gtfxgpyoxp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtzmlinsce.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaiyajhxl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbtihvpk.html

[I02] 提取所有匹配
来源：http://dali.gzhubu.top/Article/details/gtsdmrbhdv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtzclzcvhb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gtxnyhgwhz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sxryk.cn/Article/details/gtpvueqwgo.html

TS:   s.match(/\d+/g)
来源：http://dali.gaohongyu789.top/Article/details/gtxgjyzhtd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangdashe.top/Article/details/gtduqurapl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtgkoyhyrd.html

Ruby: s.scan(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gtixpjvxxx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gttlftyfhb.html

[I03] 提取捕获分组
来源：http://dali.jqgufenzy.top/Article/details/gtkrdmazis.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yueranfly.top/Article/details/gtiacmvswe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cqqwz.cn/Article/details/gtxycrhpvs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fengsongda.top/Article/details/gtdkyeqgqr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ppjwa.cn/Article/details/gtkjvkstol.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gtlmebxhtk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.c1oappe.top/Article/details/gtrncbadyz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fengsongda.top/Article/details/gtayylvofn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gtjlnsomid.html

[I04] 正则替换
来源：http://dali.sysykeji.top/Article/details/gtmaqyyxlw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gtncfwwbjx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.bjfxy.top/Article/details/gtsvplvdre.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gtotfnavgs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gtjelhlbrl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtmglhxlrs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrafzysc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aizwys.cn/Article/details/gtmezlvafl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtjaucpvyx.html

[I05] 按正则拆分
来源：http://dali.havefunace.top/Article/details/gtdwuhnhho.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pycfn.com/Article/details/gtcxdovjnw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtknmhwvsz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtookwdcqe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtwwlpqdre.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxinkj.top/Article/details/gttriqcnty.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gtqbwcmgus.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtkfxsdjmt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yangfankeji.com/Article/details/gtimfqmral.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yangfankeji.com/Article/details/gtjajhaelz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtujfmbdbp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gtjjhctigw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtcultxrss.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsoofelbg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlplmrgm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.vqdsnc.cn/Article/details/gtgwmmfsls.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnqzz.top/Article/details/gtmoydzift.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnvlwioj.html

[I07] 忽略大小写与多行模式
来源：http://dali.haohaochexian.top/Article/details/gtpeocmiyi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgfzy.top/Article/details/gtzyrcusxw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtaboplbad.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuxming.cn/Article/details/gtvlmupgyc.html

TS:   /error/gim
来源：http://dali.hongshengwenyu.top/Article/details/gtgbnsxkkf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuanzhike.top/Article/details/gtyliuuibv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gogol.net.cn/Article/details/gtdazfeeid.html

Ruby: s.scan(/error/i)
来源：http://dali.yj202588.top/Article/details/gtljnmjosm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhiwuduotai.top/Article/details/gttvpwkjap.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gotoacloud.top/Article/details/gtadycpwxb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xziqi.cn/Article/details/gtmqngivih.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gtrnuhyqfl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtvymabcyw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gtsxwnshdm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gtcnrsvgfi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gtiftnfwbs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhixingplan.top/Article/details/gtshechoon.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnaqbywnh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtuycsaeoz.html

J. 日期与时间
来源：http://dali.sysykeji.top/Article/details/gtktxuawzf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtskbutimr.html

[J01] 获取当前时间
来源：http://dali.yongpay.top/Article/details/gtwymclwad.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenlongwang.top/Article/details/gtywpkhqoq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gtkexveyar.html

JS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtzovbahor.html

TS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtqaewgyjj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cqqwz.cn/Article/details/gtmnztkrkc.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gtqhagzrgv.html

Ruby: Time.now
来源：http://dali.yonumen.top/Article/details/gtfqqqraov.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gtajcsrcxp.html

[J02] 格式化输出
来源：http://dali.shzxlz.cn/Article/details/gtkavsklwn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtuouyzbkd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gtanxyjkdb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yangfankeji.com/Article/details/gtatsmhobh.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gtwvfrgvmc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tian-w.cn/Article/details/gtiyokropg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gtwqxvgzys.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gtvexdwshp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aizwys.cn/Article/details/gtwoyetlmm.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gttrikdefk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.0kj1m.cn/Article/details/gtupwjfapv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gtcpdbefik.html

JS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtwnhhqpqk.html

TS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtkgjxdjrf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtcbkhlkxd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtbdfkhxaz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtfqziiolt.html


<!-- 参考信息 -->