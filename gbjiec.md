代发 wailian999

Py:   class User: pass
来源：http://dali.aibaodan.cn/Article/details/gtvqhhglyy.html

PHP:  class User {}
来源：http://dali.wangdashe.top/Article/details/gtiqxafebq.html

JS:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gthnotpxsk.html

TS:   class User { name: string = ""; }
来源：http://dali.snrcjt.cn/Article/details/gtbwxcpclc.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gtivklthyn.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gtmzbrrbiw.html

Ruby: class User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtwqirxqnb.html

C#:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtdbtjdrws.html

[G02] 构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtdbaaiocw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntekurjn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtgajugytz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmsafqshq.html

TS:   constructor(public name: string) {}
来源：http://dali.chenlongwang.top/Article/details/gtmsgwsrex.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhujwmuc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xylfe.cn/Article/details/gtaxtfykng.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gttyzbcfit.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fengsongda.top/Article/details/gtizijfpxh.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtntfohznj.html

Py:   self.name = "x"
来源：http://dali.fengsongda.top/Article/details/gtcdfhjlhk.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gtatdgwzqu.html

JS:   this.name = "x";
来源：http://dali.cheryme.top/Article/details/gtqnkozrjt.html

TS:   name: string = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtaanihyqf.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gtbwwuonnl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shzxlz.cn/Article/details/gtpdayfkjz.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gtwkhjbqrh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tanke756.top/Article/details/gtlgazurdj.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gtfafizguq.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqeiawmxs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtgvpfvpzu.html

JS:   greet() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtbkpiejzp.html

TS:   greet(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtuimfdopy.html

Java: String greet() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtpmntyxzy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtyxajhadx.html

Ruby: def greet; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtdtwfvfak.html

C#:   public string Greet() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtdltyyciu.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gtzbwrsttm.html

Py:   class Admin(User): pass
来源：http://dali.guowangkeji.top/Article/details/gtaopxzwnc.html

PHP:  class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtkgadeqjs.html

JS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtlpsfugrz.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtozkptvdh.html

Java: class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtueewreau.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhiwuduotai.top/Article/details/gtbjiksxwv.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gtpymdrklp.html

C#:   class Admin : User {}
来源：http://dali.aibaodan.cn/Article/details/gtfukwfwij.html

[G06] 重写方法
来源：http://dali.svipenyu.cn/Article/details/gtudxzuzzt.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gtelbyegbj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtknuripxy.html

JS:   greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtghqaotlp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtmmqpjvit.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtaajbwlex.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gtldcvajop.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gtcnnnfbln.html

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gtcjgjteue.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gtkctywvhe.html

Py:   super().greet()
来源：http://dali.wangshuangyany.cn/Article/details/gtpilfcrkl.html

PHP:  parent::greet();
来源：http://dali.yj202588.top/Article/details/gtnidnclzm.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfooxfqr.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtwmhpcecd.html

Java: super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzkkzkyo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yongpay.top/Article/details/gtfqkoakns.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gtzmadsghp.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gtokhqtscw.html

[G08] 静态方法与属性
来源：http://dali.jinqigufen.top/Article/details/gtmnnxgozx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cucudq.cn/Article/details/gtscltyzfc.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gtkgresbmb.html

JS:   static f() {}
来源：http://dali.smart0.xyz/Article/details/gthcxbrusa.html

TS:   static f(): void {}
来源：http://dali.chenlongwang.top/Article/details/gtfftruche.html

Java: static void f() {}
来源：http://dali.aizwys.cn/Article/details/gtqciyaqtk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yonumen.top/Article/details/gturbgmbyq.html

Ruby: def self.f; end
来源：http://dali.guannengcc.top/Article/details/gtyyixzelr.html

C#:   public static void F() {}
来源：http://dali.birdmap.top/Article/details/gtdgajmgjk.html

[G09] 接口 / 抽象类
来源：http://dali.shuidangran.top/Article/details/gtkuohnfxq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gtbbwjvrvc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jlsjyb.cn/Article/details/gtnyvpwbjj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gtqehjccpd.html

TS:   interface Shape { area(): number; }
来源：http://dali.jianghu66.top/Article/details/gtxedayuum.html

Java: interface Shape { double area(); }
来源：http://dali.cucudq.cn/Article/details/gtuweyelaq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.quarkkingdee.top/Article/details/gtsdkqawfn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jianghu66.top/Article/details/gtqgflgfpu.html

C#:   interface IShape { double Area(); }
来源：http://dali.shzxlz.cn/Article/details/gtqwoeheyi.html

[G10] 访问控制
来源：http://dali.hywenlv.cn/Article/details/gtdrjagztc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tanke756.top/Article/details/gtivwaoizj.html

PHP:  public / protected / private
来源：http://dali.havefunace.top/Article/details/gtifkpylxb.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gtfvvdknwx.html

TS:   public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtlgumfhvv.html

Java: public / protected / private / 默认包级
来源：http://dali.cucudq.cn/Article/details/gtbergqsro.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxinkj.top/Article/details/gtovqkggru.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtiabmxsfy.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gtdnotjhfo.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gtxjyamsws.html

Py:   @property 与 @x.setter
来源：http://dali.jiagoushi.top/Article/details/gtlgmwqyox.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtqruazwpe.html

JS:   get name() { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtbvtefqov.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtptjjxael.html

Java: public String getName() { return name; }
来源：http://dali.xylfe.cn/Article/details/gttmnkxdqa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtkslxgcip.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gtqckmpczw.html

C#:   public string Name { get; set; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsrpshbv.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gtqwpzuljc.html

Py:   def __str__(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gtzxvaduxz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gthalgwedu.html

JS:   toString() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtagkavfqv.html

TS:   toString(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtpuwvhslz.html

Java: @Override public String toString() { return name; }
来源：http://dali.birdmap.top/Article/details/gtmnynczhk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtmoraesnq.html

Ruby: def to_s; @name; end
来源：http://dali.chenzaomai.com/Article/details/gtrouifykx.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtfrholpyv.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gtorzxbfyn.html

Py:   isinstance(u, User)
来源：http://dali.birdmap.top/Article/details/gtlobqnngs.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtrfvaogre.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjdhxsjj.html

TS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtvzcjwbsi.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtmzuglgig.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gthrpoxamy.html

Ruby: u.is_a?(User)
来源：http://dali.redwolf501.top/Article/details/gtmyklddnp.html

C#:   u is User
来源：http://dali.0kj1m.cn/Article/details/gteusuldxr.html

[G14] 数据类 / record
来源：http://dali.yuxming.cn/Article/details/gtgrbzauhz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.snrcjt.cn/Article/details/gtntzadmsr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.haohaochexian.top/Article/details/gtjraemwuf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gthzgxhwdj.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrsnjrcg.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gtbsmymdrb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gtzkffbwrr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnxiangtu.top/Article/details/gtnwmhyxkm.html

C#:   record User(string Name, int Age);
来源：http://dali.chenzaomai.com/Article/details/gtggjixaif.html

[G15] 枚举
来源：http://dali.shuidangran.top/Article/details/gthchpmnpk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258888.top/Article/details/gtuivsjjyd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gterxdcjyx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jlsjyb.cn/Article/details/gtrrvuxiun.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtdziqpeth.html

Java: enum Color { RED, GREEN }
来源：http://dali.yangfankeji.com/Article/details/gtjxsikvnn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinghuilouyu.cn/Article/details/gtocruforb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jianghu66.top/Article/details/gtxjnqxfgo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtmojpntqr.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gtejbxjzcq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gtlnvbssui.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gtbxrzzbux.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtvhjwjpes.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtfrgpqfpj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shangyingyoupin.top/Article/details/gtnxdfopjn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.c1oappe.top/Article/details/gtlphvpmrb.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gtniiavgcf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gtvvutdszh.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtomplcguf.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gtmkwkgdov.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtudeqojxy.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gtujvbmodh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gteulrtrrv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fzhhl.top/Article/details/gtvnzuijgx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtndrijisy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtljearwtd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gteimbzvap.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.mhx1999.top/Article/details/gtjjufqalh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgufenzy.top/Article/details/gteattfrxo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangshuangyany.cn/Article/details/gttqipphit.html

[H02] finally / ensure 收尾
来源：http://dali.tanke756.top/Article/details/gtagfntpbr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgfzy.top/Article/details/gtaztmlcuo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtivzqzjew.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtvdkvnmyz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtctjtwyzc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtihnezdeo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zycfv.cn/Article/details/gttaqoewea.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ybcxt.top/Article/details/gtnulqiblk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtexukbwha.html

[H03] 主动抛出异常
来源：http://dali.xinyue.icu/Article/details/gtpsizqmsh.html

Py:   raise ValueError("错误信息")
来源：http://dali.redwolf501.top/Article/details/gtlinloqil.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtfkxfpoav.html

JS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtivskrbmx.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtjwaptalc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gthxvsbmjd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhixingplan.top/Article/details/gtvnngxmdd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.feifeiyinyue.top/Article/details/gtdiennlwb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtigswfnxq.html

[H04] 自定义异常类型
来源：http://dali.hnxiangtu.top/Article/details/gtoxvugzyg.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmidnahs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtkrzzrrnu.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtxhdvenzl.html

TS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtmstyhzxh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gtmmjaylci.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gtmimpeqng.html

Ruby: class MyError < StandardError; end
来源：http://dali.iojbl.cn/Article/details/gtyqhvayfn.html

C#:   class MyException : Exception {}
来源：http://dali.xuetiantiany.cn/Article/details/gthtzcvnlx.html

[H05] 捕获特定类型
来源：http://dali.pycfn.com/Article/details/gtwwbdqljw.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gtfcvqpldc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sxryk.cn/Article/details/gtcepljzfv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtrdejvcnw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gtbzteityw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hammf.cn/Article/details/gtqxrvmjpd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqxvgjfn.html

Ruby: rescue ArgumentError => e
来源：http://dali.daria6918.cn/Article/details/gtuoqhbqej.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gtvmzzypqg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258888.top/Article/details/gthxbxnmnn.html

Py:   value = d.get("k") or default
来源：http://dali.xylfe.cn/Article/details/gtoqnoayeg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gtxiyhnpkt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtkupifwqu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gtfjkljeda.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tianlin.xyz/Article/details/gtnhchibwb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gzhubu.top/Article/details/gtazlemgtg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gtycuziicp.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhengqikj.top/Article/details/gtzxreczbh.html

[H07] 断言
来源：http://dali.hammf.cn/Article/details/gtxesabgwn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gtaxdtprnr.html

PHP:  assert($x > 0);
来源：http://dali.aibaodan.cn/Article/details/gttsfxeigt.html

JS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtvohdqacr.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gthzducfoq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuanzx.com/Article/details/gtvjenlwib.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gtptudgsuk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hysaishi.cn/Article/details/gtdaodwqfu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtwjmktgxm.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gttgmxatwy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangshuangyany.cn/Article/details/gtobycjrer.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aibaodan.cn/Article/details/gtanumpskw.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gtcudcdvrp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.316326.xyz/Article/details/gtjmgguxke.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuanzhike.top/Article/details/gtzpeybjyn.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gtynzeggrw.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gtsyutpxlv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xziqi.cn/Article/details/gtjzxgyngw.html

[H09] 带错误码的异常
来源：http://dali.tian-w.cn/Article/details/gthpdmhwsq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdzubxpn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aibaodan.cn/Article/details/gtntfcnpln.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gtnbwopxpm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.svipenyu.cn/Article/details/gtmjsqvqey.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gtoaidiqdd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cashguo.top/Article/details/gttegmjaeg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbieqpvm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuanzx.com/Article/details/gtuuxyzswd.html

[H10] 资源自动释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvjlbsnp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gtfkxeyqkn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yongpay.top/Article/details/gtcfptactc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gtgkredgqx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gtyxqljdhr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aizwys.cn/Article/details/gtzuskluvc.html

Go:   defer f.Close()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrmwxcsm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cdnleiting.top/Article/details/gtmjnpoocz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gtwlelymwp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtmheglxse.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gtktpjmfnd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtlageaqpv.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gtmtpfpbet.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gtsfwiciyp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtodrdncsh.html

JS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gtgkpcuujs.html

TS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gthdvztnls.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgufenzy.top/Article/details/gtvaiovbae.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtihnosrvv.html

Ruby: s.match?(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtzqikfrdm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jlsjyb.cn/Article/details/gtnecupvsp.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gtaaxcyxds.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkubkwuv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ehwqpu.com/Article/details/gtknreklsz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hysaishi.cn/Article/details/gtdgejuhqf.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxyqkdgy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tian-w.cn/Article/details/gtfiqusrfq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtwxzxbxzh.html

Ruby: s.scan(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gtddrdaleq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yongpay.top/Article/details/gticxqsqma.html

[I03] 提取捕获分组
来源：http://dali.hnxiangtu.top/Article/details/gtekxukwea.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sxryk.cn/Article/details/gtdmsjtxee.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gtinontqgj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.svipenyu.cn/Article/details/gthbkkdenr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.snrcjt.cn/Article/details/gtiwqqujsq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gtyzmoqrnf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cdnleiting.top/Article/details/gtztuwljzg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hammf.cn/Article/details/gtdvtzzuze.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yueranfly.top/Article/details/gtlztydrym.html

[I04] 正则替换
来源：http://dali.aibaodan.cn/Article/details/gtfgelscle.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jianghu66.top/Article/details/gtnqmqrqkw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pycfn.com/Article/details/gtetrkdhhn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gtysavlfqe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gtmenwyhad.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtvyrpyjmb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guannengcc.top/Article/details/gtnlpwvtwj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gttrkwtafg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrdhavdw.html

[I05] 按正则拆分
来源：http://dali.tianlin.xyz/Article/details/gtzhoxbtxp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ppjwa.cn/Article/details/gtmohpefsn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.andypj.xyz/Article/details/gtatupmape.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtmjucrvht.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtnhhmklay.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhengqikj.top/Article/details/gtowamdrao.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gtykkbxtop.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtohwrmmma.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gaohongyu789.top/Article/details/gtopaoxlvo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.quarkkingdee.top/Article/details/gtdulieckg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gthnhttzli.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ybcxt.top/Article/details/gtpbxcwbzu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtrtndchay.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gtajvcqrvf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtkfgmxpop.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gotoacloud.top/Article/details/gtaqmwfffd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpnznwzi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtykgfrabs.html

[I07] 忽略大小写与多行模式
来源：http://dali.gzhubu.top/Article/details/gtwzbkcyqp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangshuangyany.cn/Article/details/gtzxrqqvab.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gtkwaxgspj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tianlin.xyz/Article/details/gtjhrspijy.html

TS:   /error/gim
来源：http://dali.xylfe.cn/Article/details/gthbvvfcph.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ehwqpu.com/Article/details/gtedlcrcro.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zdqjudy.top/Article/details/gtvnkcqzap.html


<!-- 参考信息 -->