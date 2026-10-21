代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gtsnlrbcno.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daxiang520.top/Article/details/gtqazthfxg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hfpthk.cn/Article/details/gtnzomtwcs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tianlin.xyz/Article/details/gtldzikhhs.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtzshnwqew.html

G. 面向对象
来源：http://dali.zhengqikj.top/Article/details/gtxomafhwa.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtdsoqjero.html

[G01] 定义类
来源：http://dali.zhiwuduotai.top/Article/details/gtqvhdcpqp.html

Py:   class User: pass
来源：http://dali.sweek.top/Article/details/gtcwruycpf.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gtsmrhxqab.html

JS:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtsmtrvypq.html

TS:   class User { name: string = ""; }
来源：http://dali.yangfankeji.com/Article/details/gtizjtewyu.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtfmydbbeg.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gtzrsmosor.html

Ruby: class User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtrroadepu.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtenepxqlb.html

[G02] 构造函数
来源：http://dali.ehwqpu.com/Article/details/gtppilzbpx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gtiahdrufc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gtgqwsvwdx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtbixuhtgu.html

TS:   constructor(public name: string) {}
来源：http://dali.hammf.cn/Article/details/gtmwhlrxvi.html

Java: User(String name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gtcvsgzrnz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yueranfly.top/Article/details/gtbmzbagbj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.bjfxy.top/Article/details/gtqntvsvke.html

C#:   public User(string name) { Name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtsaqfeouj.html

[G03] 实例属性
来源：http://dali.gzhubu.top/Article/details/gtoxgqgxzj.html

Py:   self.name = "x"
来源：http://dali.sweek.top/Article/details/gtmaeenjoj.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtcmbjtkhs.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtthiuywhm.html

TS:   name: string = "x";
来源：http://dali.yonumen.top/Article/details/gtfrgbyrlo.html

Java: private String name;
来源：http://dali.316326.xyz/Article/details/gtymohwprm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cucudq.cn/Article/details/gtrnwepuqz.html

Ruby: @name = "x"
来源：http://dali.daria6918.cn/Article/details/gtghrgczok.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gtrdbtmkvg.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gtsgoziogc.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gthrcpyssg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtvofilfgz.html

JS:   greet() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtniqwdljw.html

TS:   greet(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtdazqeywm.html

Java: String greet() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtuwashtyc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtglcvhusb.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtcsjtqsin.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbdicuqu.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gtcfgtrquz.html

Py:   class Admin(User): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkepknbx.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtwdcnyuob.html

JS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtrbtzrptj.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtvpjeuwao.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvfacbdi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgufenzy.top/Article/details/gtmiuhnoss.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtsppbcbnh.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkswbdsby.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gtyrzdtsuu.html

Py:   def greet(self): return "admin"
来源：http://dali.c1oappe.top/Article/details/gttdbmhxxm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtujcapagh.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtghxszxiw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtepxbzpbl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtgcisjgkj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gtvimkpcsn.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gttoxjkhkc.html

C#:   public override string Greet() => "admin";
来源：http://dali.andypj.xyz/Article/details/gtrvjbfkua.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gtviphmkyp.html

Py:   super().greet()
来源：http://dali.gaohongyu789.top/Article/details/gtvtpqlmdl.html

PHP:  parent::greet();
来源：http://dali.aibaodan.cn/Article/details/gtkazinzef.html

JS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtlsympxil.html

TS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtyyeomrxq.html

Java: super.greet();
来源：http://dali.hfpthk.cn/Article/details/gttpmxwaom.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gtqzvznwty.html

Ruby: super
来源：http://dali.hnxiangtu.top/Article/details/gttngwobuo.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gtqozjjhdd.html

[G08] 静态方法与属性
来源：http://dali.yongpay.top/Article/details/gtjchhedxl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jianghu66.top/Article/details/gtgdlthhzv.html

PHP:  public static function f() {}
来源：http://dali.gzhubu.top/Article/details/gtujavnytr.html

JS:   static f() {}
来源：http://dali.nanxinkj.top/Article/details/gtonatoept.html

TS:   static f(): void {}
来源：http://dali.zhixingplan.top/Article/details/gtlvnzxasd.html

Java: static void f() {}
来源：http://dali.jinqigufen.top/Article/details/gtlyqdrfzc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gotoacloud.top/Article/details/gtgyuayvix.html

Ruby: def self.f; end
来源：http://dali.xziqi.cn/Article/details/gttgcxpoun.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gtyrhkoaih.html

[G09] 接口 / 抽象类
来源：http://dali.yueranfly.top/Article/details/gtixxmqnol.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenzaomai.com/Article/details/gtoqmlyjjr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gtwxdpaiuo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvfofurq.html

TS:   interface Shape { area(): number; }
来源：http://dali.gzhubu.top/Article/details/gttmifyhlg.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gtuepsyohx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aibaodan.cn/Article/details/gtwzksdide.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.snrcjt.cn/Article/details/gthalowzxt.html

C#:   interface IShape { double Area(); }
来源：http://dali.xylfe.cn/Article/details/gtjjplzmeq.html

[G10] 访问控制
来源：http://dali.c1oappe.top/Article/details/gtnudawnup.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxinkj.top/Article/details/gtvnnbwvmu.html

PHP:  public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtmkmbneuj.html

JS:   #private 字段；其余公开
来源：http://dali.yuxming.cn/Article/details/gtbhjymwbo.html

TS:   public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtfxjhfuav.html

Java: public / protected / private / 默认包级
来源：http://dali.vqdsnc.cn/Article/details/gtfmwaffwx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.9152youxi.cn/Article/details/gtsolrqdjg.html

Ruby: public / protected / private
来源：http://dali.havefunace.top/Article/details/gtpoqhelrd.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gtgpkzjmql.html

[G11] getter / setter
来源：http://dali.jyoumei.cn/Article/details/gtpeqgzdgx.html

Py:   @property 与 @x.setter
来源：http://dali.pycfn.com/Article/details/gtelshtsjd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgiifydmf.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtulpzhxgx.html

TS:   get name(): string { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtmwlkwwqv.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtstumbygc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtqvekuvfx.html

Ruby: attr_accessor :name
来源：http://dali.snrcjt.cn/Article/details/gtdimpjvkj.html

C#:   public string Name { get; set; }
来源：http://dali.yonumen.top/Article/details/gtejrycnag.html

[G12] 对象转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtsvyflrfh.html

Py:   def __str__(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gttbnxsycl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtrjwscxya.html

JS:   toString() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtirbrcqxu.html

TS:   toString(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtyicmtgfy.html

Java: @Override public String toString() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtdbambxry.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtxiaczqme.html

Ruby: def to_s; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtgrdceqmq.html

C#:   public override string ToString() => Name;
来源：http://dali.wangdashe.top/Article/details/gtnulexqrk.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gtgntcqqaw.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwfqanut.html

PHP:  $u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtyhcrakec.html

JS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtfquqvmcb.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtqbgixonx.html

Java: u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtjfnizgrb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gttiytewsf.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigfzy.top/Article/details/gttmbqwpem.html

C#:   u is User
来源：http://dali.zhongyouzk.top/Article/details/gtpmattolh.html

[G14] 数据类 / record
来源：http://dali.cucudq.cn/Article/details/gtefrdpvpq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.0kj1m.cn/Article/details/gtisxckuri.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jiagoushi.top/Article/details/gtalqjflbx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.9152youxi.cn/Article/details/gthiwjriis.html

TS:   type User = { name: string; age: number };
来源：http://dali.sxryk.cn/Article/details/gtfimxyayn.html

Java: record User(String name, int age) {}
来源：http://dali.yj202588.top/Article/details/gtwafvwduf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.meibo888.top/Article/details/gtefpevmxc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuanzhike.top/Article/details/gtwlpbfxez.html

C#:   record User(string Name, int Age);
来源：http://dali.iojbl.cn/Article/details/gtjqspzmuu.html

[G15] 枚举
来源：http://dali.yangfankeji.com/Article/details/gtrikwgnvr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dianchejie.cn/Article/details/gtkmxhhopv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jlsjyb.cn/Article/details/gthrgqenzb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yanxiufei.cn/Article/details/gtoguljele.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gtjzmgabuk.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenlongwang.top/Article/details/gtcohzzjbt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfnwfqaxp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shzxlz.cn/Article/details/gtbxdhglbv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtsmzzsonk.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgfzy.top/Article/details/gtfufwilnk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gtebampowh.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258888.top/Article/details/gtksytlulh.html

JS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtwmxufsbs.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgrmzyvc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.svipenyu.cn/Article/details/gtebrsloap.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gtjbokxmgn.html

Ruby: obj.instance_variables
来源：http://dali.zycfv.cn/Article/details/gthszkcjue.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gtohnguzsb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbwqzobnc.html

H. 异常与错误处理
来源：http://dali.guowangkeji.top/Article/details/gtulbkohec.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkitlrblm.html

[H01] try / catch 基础
来源：http://dali.yj202588.top/Article/details/gtobtcjvaj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenlongwang.top/Article/details/gtujwodjvj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtpremarib.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtryrukuft.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtdnarlqre.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tian-w.cn/Article/details/gtqdtykyjb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hywenlv.cn/Article/details/gtjksgungo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cheryme.top/Article/details/gtnsywmzdm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gtctqtbxnf.html

[H02] finally / ensure 收尾
来源：http://dali.jianghu66.top/Article/details/gtjdllvfxk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.snrcjt.cn/Article/details/gtlzxtaglp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtpwovspnw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtjtanbnii.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtdlchtjnd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtwbwjbhll.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gtunugkpcq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tianlin.xyz/Article/details/gttdkexskl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtadibdcsy.html

[H03] 主动抛出异常
来源：http://dali.zhongyouzk.top/Article/details/gtluxsbiei.html

Py:   raise ValueError("错误信息")
来源：http://dali.meibo888.top/Article/details/gtoknfcemf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtmksubzjw.html

JS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gtldetvzog.html

TS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gtgpnakord.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtahhuepxe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gtphkyrwni.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yangfankeji.com/Article/details/gtwuypjpzy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtntduyqil.html

[H04] 自定义异常类型
来源：http://dali.quarkkingdee.top/Article/details/gtoewihguv.html

Py:   class MyError(Exception): pass
来源：http://dali.snrcjt.cn/Article/details/gtvhqimjxi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcsspbdf.html

JS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtrpafhtgn.html

TS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtrnwcrxjq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gthhyybbgn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fzhhl.top/Article/details/gtlqngeawz.html

Ruby: class MyError < StandardError; end
来源：http://dali.havefunace.top/Article/details/gtpkzfrvby.html

C#:   class MyException : Exception {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnfdgnvv.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gtssovadid.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gtzqjpguso.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.haohaochexian.top/Article/details/gtpcplgkya.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gtxlzafqpn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gtfrtowqjz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnqzz.top/Article/details/gthwijfqzn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hammf.cn/Article/details/gtsiozyhrf.html

Ruby: rescue ArgumentError => e
来源：http://dali.hammf.cn/Article/details/gtzkxdmqhu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zdqjudy.top/Article/details/gtvzfdhpnf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gtraaiepnc.html

Py:   value = d.get("k") or default
来源：http://dali.jinghuilouyu.cn/Article/details/gtecebsigt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtoveplmvh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtegijrnia.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtgvlwizni.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.bjfxy.top/Article/details/gtygdnxanl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gogol.net.cn/Article/details/gtowgyvgoo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gaohongyu789.top/Article/details/gtfivgffgy.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gtisxiejoo.html

[H07] 断言
来源：http://dali.dianchejie.cn/Article/details/gtvmbqemzh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gtecsgxpcy.html

PHP:  assert($x > 0);
来源：http://dali.fengsongda.top/Article/details/gtfekndiej.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtdejpuxfm.html

TS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtwlcutqcy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gtuibdlbmw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yonumen.top/Article/details/gtmwgsrgwd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhiwuduotai.top/Article/details/gtbygkltfv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtmphsvqyr.html

[H08] 获取错误信息与堆栈
来源：http://dali.xinyue.icu/Article/details/gtpgkfulrx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenjidiqi.icu/Article/details/gtwarzbowo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangshuangyany.cn/Article/details/gtcussqxga.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gtxwutrpfx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hysaishi.cn/Article/details/gtevvzbayk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jlsjyb.cn/Article/details/gtwrbbgmvu.html

Go:   err.Error()
来源：http://dali.tanke756.top/Article/details/gthjpyobll.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqqgzuxl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zycfv.cn/Article/details/gtwygskoca.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gtovulelyx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shzxlz.cn/Article/details/gtlhxnniye.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jyoumei.cn/Article/details/gttxnaowxv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gthchijhay.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.c1oappe.top/Article/details/gtypcvjtdr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cashguo.top/Article/details/gtqvpihniq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gthdnnynwk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenlongwang.top/Article/details/gtiurzmmbb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.smart0.xyz/Article/details/gtvkefcolc.html

[H10] 资源自动释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcamrnqso.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gtslyqnwdc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daxiang520.top/Article/details/gtpgyitqvc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtivbipjic.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtmfsoylnx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gttstvyrcp.html

Go:   defer f.Close()
来源：http://dali.yueranfly.top/Article/details/gtmwqnqvel.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cqqwz.cn/Article/details/gtuvqotezr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtcygcnykn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtndqtpxmc.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gtyswuxsac.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtdrfavqgu.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyemizhfm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtlezuqmhu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtjebjlroz.html

JS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapknzwtw.html

TS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtvdtojyjc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gtwwkfbhxk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cheryme.top/Article/details/gtexxwxafh.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gteripjodz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhengqikj.top/Article/details/gtwdbhjvms.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gtbanpchwn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtnccaiztu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gtfgbsgmea.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenticeww.html

TS:   s.match(/\d+/g)
来源：http://dali.wangdashe.top/Article/details/gtbvmnhhac.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtgytpwmqh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gttmzlazlo.html

Ruby: s.scan(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtjuiqovpe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuanzx.com/Article/details/gtkrjapvgi.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gtkvvkexid.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtdoixdqhc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gtsmefoeqa.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guannengcc.top/Article/details/gtfuemujea.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.andypj.xyz/Article/details/gtuoqtenhi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shzxlz.cn/Article/details/gtuvzffnww.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gtcrktrnee.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhpzgchl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhengqikj.top/Article/details/gtdgtqcxvw.html

[I04] 正则替换
来源：http://dali.xziqi.cn/Article/details/gtubtfsvtv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuanzhike.top/Article/details/gtsxhqwerp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtgjyvxems.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtxemaeywq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtjepvtkni.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gtuxyihlxu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtivnzgxcp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yongpay.top/Article/details/gtmzprdhqe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtljkwkkmc.html

[I05] 按正则拆分
来源：http://dali.ehwqpu.com/Article/details/gtwzfdwims.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cqqwz.cn/Article/details/gtmdlukogb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ydzc1.top/Article/details/gttmywengt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtnaypiwyv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtrzrdepil.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gotoacloud.top/Article/details/gtutacurta.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tanke756.top/Article/details/gtpoklpftq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtlhpdvfuv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daria6918.cn/Article/details/gtvrfrimbo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zycfv.cn/Article/details/gtqgbaxxnu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtwxktsyrf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuxming.cn/Article/details/gtachvsvou.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtdxftxwmp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtzhjohjwl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtuccyqebx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xinyue.icu/Article/details/gtwyphepxk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hongshengwenyu.top/Article/details/gtijkoqrvr.html


<!-- 参考信息 -->