代发 wailian999

Py:   class User: pass
来源：http://dali.cdnleiting.top/Article/details/gtxtowkxmi.html

PHP:  class User {}
来源：http://dali.sysykeji.top/Article/details/gtxhvbshfj.html

JS:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtvbrimpdm.html

TS:   class User { name: string = ""; }
来源：http://dali.tanke756.top/Article/details/gtanqtrvkm.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtofuplyoo.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gtjlcngzyn.html

Ruby: class User; end
来源：http://dali.hywenlv.cn/Article/details/gtmoraouwj.html

C#:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtpljfhwol.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gttmelxfcc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gtbxzvyrfe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gtfyfnsnom.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtywkpkugd.html

TS:   constructor(public name: string) {}
来源：http://dali.guowangkeji.top/Article/details/gtkqrpxuto.html

Java: User(String name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtxpajrzef.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigufen.top/Article/details/gtammoypul.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.kuanghao11.cn/Article/details/gtpeqawyuo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxbcozyl.html

[G03] 实例属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvugbwvq.html

Py:   self.name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhyalbrb.html

PHP:  public string $name = "x";
来源：http://dali.xinyue.icu/Article/details/gtolabejov.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gtgfdcvyxj.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gtebsnoduv.html

Java: private String name;
来源：http://dali.fengsongda.top/Article/details/gtiqplyeaz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftzuvszi.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtjpohsmih.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhengqikj.top/Article/details/gtclhqrxyg.html

[G04] 定义方法
来源：http://dali.shuidangran.top/Article/details/gtsnscwqlu.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtcrjltefr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtgwowfewm.html

JS:   greet() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtlqufvwpb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gthtramnqv.html

Java: String greet() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtelkeshsf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtvttgfoux.html

Ruby: def greet; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtuvjkvhoh.html

C#:   public string Greet() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtnjqbqnbz.html

[G05] 继承
来源：http://dali.zhengqikj.top/Article/details/gtcjbjxads.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtibsftqhc.html

PHP:  class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtmmrgssnu.html

JS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtcjvqlfhb.html

TS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtcciamjih.html

Java: class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtsqclqjnr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fzhhl.top/Article/details/gtzsqoqnkr.html

Ruby: class Admin < User; end
来源：http://dali.xylfe.cn/Article/details/gtkwpswyca.html

C#:   class Admin : User {}
来源：http://dali.cucudq.cn/Article/details/gtncxfyaqp.html

[G06] 重写方法
来源：http://dali.dashuyun.cn/Article/details/gtctccvqkz.html

Py:   def greet(self): return "admin"
来源：http://dali.wangshuangyany.cn/Article/details/gtmltllzhl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtxyeoicyx.html

JS:   greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtcuqnhxvf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtbfpujbuj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtmvcwdivq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gtkjaksxjr.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gtbzszjcmz.html

C#:   public override string Greet() => "admin";
来源：http://dali.jyoumei.cn/Article/details/gtnwmjnsoc.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gtfvwucmba.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gtjunejiru.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtsbkqsupp.html

JS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtkttpzbgz.html

TS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtbujkajck.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gtivoblocf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jyoumei.cn/Article/details/gtthaqzuzp.html

Ruby: super
来源：http://dali.jqgfzy.top/Article/details/gtzdtmfjlm.html

C#:   base.Greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtdqortkbq.html

[G08] 静态方法与属性
来源：http://dali.ybcxt.top/Article/details/gtedqpjkwh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gtfuynsmax.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtopxqqvjo.html

JS:   static f() {}
来源：http://dali.ivvv.top/Article/details/gtgeigstgf.html

TS:   static f(): void {}
来源：http://dali.fengsongda.top/Article/details/gthvutmeyi.html

Java: static void f() {}
来源：http://dali.haohaochexian.top/Article/details/gtnzcpyvfe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.mhx1999.top/Article/details/gttfekcrqy.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gtzijnmfvy.html

C#:   public static void F() {}
来源：http://dali.aizwys.cn/Article/details/gthabjmgov.html

[G09] 接口 / 抽象类
来源：http://dali.hysaishi.cn/Article/details/gtqfkpfqgx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gtkkwxbgos.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxinkj.top/Article/details/gtwmkkxcjg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.0kj1m.cn/Article/details/gtjsbnepwv.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtmnsxebvc.html

Java: interface Shape { double area(); }
来源：http://dali.zycfv.cn/Article/details/gthmitzegd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.feifeiyinyue.top/Article/details/gtctiljhor.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gthceymxrj.html

C#:   interface IShape { double Area(); }
来源：http://dali.bjfxy.top/Article/details/gtdtkesdrt.html

[G10] 访问控制
来源：http://dali.yj20258.top/Article/details/gtkmvehgwb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.snrcjt.cn/Article/details/gtsadqsria.html

PHP:  public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtwebjhfrr.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gttnxtjfif.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtkqoqnaqh.html

Java: public / protected / private / 默认包级
来源：http://dali.yonumen.top/Article/details/gtumwzgrwe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258.top/Article/details/gtcnoonkhp.html

Ruby: public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtzukbrrfc.html

C#:   public / protected / private / internal
来源：http://dali.jianghu66.top/Article/details/gtrxyitxut.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gtddlbwtvc.html

Py:   @property 与 @x.setter
来源：http://dali.aibaodan.cn/Article/details/gtcjaqljxc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvikdpwpl.html

JS:   get name() { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtrafddezq.html

TS:   get name(): string { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gtggydbteb.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtiuhmysvg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtdlzkrzpo.html

Ruby: attr_accessor :name
来源：http://dali.mhx1999.top/Article/details/gtqngzfgbo.html

C#:   public string Name { get; set; }
来源：http://dali.cashguo.top/Article/details/gtpqcuwizz.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gtqxrgicbk.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtmebsoiix.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtevaogxve.html

JS:   toString() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtxjvctuxo.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnggkkzh.html

Java: @Override public String toString() { return name; }
来源：http://dali.fzhhl.top/Article/details/gthsqmwrpc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesluitwt.html

Ruby: def to_s; @name; end
来源：http://dali.xziqi.cn/Article/details/gtlnsaefns.html

C#:   public override string ToString() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtbbafpvpm.html

[G13] 判断对象类型
来源：http://dali.smart0.xyz/Article/details/gtmxcplyve.html

Py:   isinstance(u, User)
来源：http://dali.hongshengwenyu.top/Article/details/gtblotrcas.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtvnzeohbm.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtajcfzbgw.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtimlpyjml.html

Java: u instanceof User
来源：http://dali.sweek.top/Article/details/gtgvxddoku.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.quarkkingdee.top/Article/details/gthmtnnavo.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gtvqolerpn.html

C#:   u is User
来源：http://dali.zdqjudy.top/Article/details/gtkgpmghei.html

[G14] 数据类 / record
来源：http://dali.meibo888.top/Article/details/gtrpedhobt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gtepxkqmjo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.meibo888.top/Article/details/gtsevxjnlw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gtozkpkcmh.html

TS:   type User = { name: string; age: number };
来源：http://dali.pycfn.com/Article/details/gtczvuwerh.html

Java: record User(String name, int age) {}
来源：http://dali.yongpay.top/Article/details/gtnjdgovhk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gtkxyxuuwx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.vqdsnc.cn/Article/details/gtavkmtrvy.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gtjqzpoqds.html

[G15] 枚举
来源：http://dali.yueranfly.top/Article/details/gtejmozuuw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gtxifwtsnn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.9152youxi.cn/Article/details/gtlbaawcxn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tanke756.top/Article/details/gtmnkeomld.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtyctdoopc.html

Java: enum Color { RED, GREEN }
来源：http://dali.yanxiufei.cn/Article/details/gtgxfqynmj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fzhhl.top/Article/details/gtmznxljzq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gtteabjweo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gtaywncgam.html

[G16] 对象转数组 / 字典
来源：http://dali.0kj1m.cn/Article/details/gtukqsnlhy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuetiantiany.cn/Article/details/gtlqrnrzik.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gtniawvpve.html

JS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtnqjqomna.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gttbnowbei.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258.top/Article/details/gtdkdyjjwo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenjidiqi.icu/Article/details/gtnbopmbjp.html

Ruby: obj.instance_variables
来源：http://dali.hysaishi.cn/Article/details/gtvnuocdkr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyfdekum.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtotgtpixw.html

H. 异常与错误处理
来源：http://dali.ybcxt.top/Article/details/gtvpolxbep.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtkzhrzdzs.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gthkyrrxqu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sweek.top/Article/details/gtbfhnhidj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hysaishi.cn/Article/details/gtgwlyivwu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtfujzekmw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtkghcnqwh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yonumen.top/Article/details/gtrgtzfzdi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daxiang520.top/Article/details/gtlnzzupgv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daria6918.cn/Article/details/gtfjhultms.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ivvv.top/Article/details/gtzhhcddsi.html

[H02] finally / ensure 收尾
来源：http://dali.hongshengwenyu.top/Article/details/gthekiquil.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccxrhoqo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtmkqtolli.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtlgtvkgle.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtuuhblorm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtkngoelxw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cheryme.top/Article/details/gttpwuipjr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hysaishi.cn/Article/details/gtjqekxkvr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtqitngufr.html

[H03] 主动抛出异常
来源：http://dali.birdmap.top/Article/details/gtklnnbqni.html

Py:   raise ValueError("错误信息")
来源：http://dali.aizwys.cn/Article/details/gtlrlmwvhm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtouhdtheg.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtlltenlyf.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtjuesfdzu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdbwjzgi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daxiang520.top/Article/details/gttzabmfwe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangshuangyany.cn/Article/details/gtpwoboscf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtswadccfc.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gtsuhntxae.html

Py:   class MyError(Exception): pass
来源：http://dali.iojbl.cn/Article/details/gtvnukexbb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gtdrftaids.html

JS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtxfkzkebl.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtjjazpzcf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtszebdndr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daria6918.cn/Article/details/gtlbfdlovj.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnqzz.top/Article/details/gtsfhxpsfr.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gtymvecnzx.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gtqvnpkdgw.html

Py:   except ValueError as e:
来源：http://dali.gzhubu.top/Article/details/gtkzofphro.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gtolwidnmr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtutuhquts.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gtwgkweoau.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfifexgy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sweek.top/Article/details/gtrwjjbstf.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gtdptqsoir.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gtwftyakko.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gtgpoheyor.html

Py:   value = d.get("k") or default
来源：http://dali.hywenlv.cn/Article/details/gtxlyozzia.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gtcefhjwpr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtbfxxuhsd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtzaftmwvf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shuidangran.top/Article/details/gtnrvminuw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuxming.cn/Article/details/gtmobkqbwf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.iojbl.cn/Article/details/gtpvzfbbbt.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuxming.cn/Article/details/gtfbmdcorw.html

[H07] 断言
来源：http://dali.guowangkeji.top/Article/details/gtguykcwtf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sufxvd.cn/Article/details/gtixgeupaa.html

PHP:  assert($x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtvhokscnt.html

JS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtlnccawud.html

TS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtlwubhrmi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gttjorrwol.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gtxdqyornk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.quarkkingdee.top/Article/details/gtdxmhxajf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtyrpciblb.html

[H08] 获取错误信息与堆栈
来源：http://dali.fzhhl.top/Article/details/gthkdsiwtx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zycfv.cn/Article/details/gtcdrhwxjy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zdqjudy.top/Article/details/gtidukdcvz.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gtwgmfbcrt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenlongwang.top/Article/details/gtotgqichf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gotoacloud.top/Article/details/gthddejxmd.html

Go:   err.Error()
来源：http://dali.jianghu66.top/Article/details/gtfaeglftv.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangdashe.top/Article/details/gtlbxcjffa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuxming.cn/Article/details/gtxgotkxeh.html

[H09] 带错误码的异常
来源：http://dali.gaohongyu789.top/Article/details/gtxvedycll.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.mhx1999.top/Article/details/gtecbjnbti.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gtmsfrglvg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tanke756.top/Article/details/gtnxgurnkx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guowangkeji.top/Article/details/gtrojxscxh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sxryk.cn/Article/details/gtawiknozh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gtgpczmwdw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jianghu66.top/Article/details/gtxpyaqmwy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sufxvd.cn/Article/details/gtsvogvfbs.html

[H10] 资源自动释放
来源：http://dali.shzxlz.cn/Article/details/gtpwoatewf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuxming.cn/Article/details/gtmifqcgdr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gtyltpnicw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gtxxxccfdl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gtlyrvldbu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aibaodan.cn/Article/details/gthqqtcbiz.html

Go:   defer f.Close()
来源：http://dali.shuidangran.top/Article/details/gtjnrpquij.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gtitqtwcrv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtbeqjrbts.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gthujtgpht.html

I. 正则表达式
来源：http://dali.cucudq.cn/Article/details/gtbggonhzv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gttunhawey.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gtvcmmvwzg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtwqznbsef.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtabussauu.html

JS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gtxqypegjt.html

TS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtnvgnlfbb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gttzdetqse.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ydzc1.top/Article/details/gttvdrtnhf.html

Ruby: s.match?(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtbtqhhgbk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenlongwang.top/Article/details/gtipnhdgpd.html

[I02] 提取所有匹配
来源：http://dali.shuidangran.top/Article/details/gtsjyujufg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtygrwtwvv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gtwsjakydc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gaohongyu789.top/Article/details/gtxgfvasvg.html

TS:   s.match(/\d+/g)
来源：http://dali.zhongyouzk.top/Article/details/gtvbblfhrx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sweek.top/Article/details/gtuclgcpeb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.mhx1999.top/Article/details/gtkeipehsj.html

Ruby: s.scan(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtuizgiuzd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtowiuqxit.html

[I03] 提取捕获分组
来源：http://dali.zhongyouzk.top/Article/details/gtvgywwtdz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhoulong.xyz/Article/details/gtdpukhifh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhongyouzk.top/Article/details/gtxkdwiqsd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtwixjtgvg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jianghu66.top/Article/details/gtykeawxzg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigufen.top/Article/details/gtyvhyohnk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.iojbl.cn/Article/details/gtxtkderyz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hywenlv.cn/Article/details/gtaiivpclq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sxryk.cn/Article/details/gtwzrrrhrm.html

[I04] 正则替换
来源：http://dali.yangfankeji.com/Article/details/gtroxijslx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.quarkkingdee.top/Article/details/gttloywtmv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gtwvpvuyfb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbadwbzpj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtnefxopgg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqerrhfj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtfaitsogl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.snrcjt.cn/Article/details/gtqqzuvtwi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gtlixggfrx.html

[I05] 按正则拆分
来源：http://dali.sweek.top/Article/details/gtcbjemuvr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtyiyxcetk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtphjgmnyc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtaecwcvxp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtmmvhduyf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jianghu66.top/Article/details/gtyfekzkow.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.meibo888.top/Article/details/gtgwbqsdsp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtdjptqhxa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenlongwang.top/Article/details/gtuctoexwh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gtmntnmerl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtovacpgfk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hfpthk.cn/Article/details/gtmpdnfcmm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gtcshrxeqz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtgbwrlhlq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxwschnq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shuidangran.top/Article/details/gtaxtfnfmm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cucudq.cn/Article/details/gtqhgulfis.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtqvukvrdq.html

[I07] 忽略大小写与多行模式
来源：http://dali.sufxvd.cn/Article/details/gtlptossns.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pycfn.com/Article/details/gtvviuixui.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttoevgbbu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dashuyun.cn/Article/details/gtqhembvsx.html

TS:   /error/gim
来源：http://dali.9152youxi.cn/Article/details/gtfhghnsdt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.andypj.xyz/Article/details/gtocolyewp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gogol.net.cn/Article/details/gtwzrtwdgw.html


<!-- 参考信息 -->