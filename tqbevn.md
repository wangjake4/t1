代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sweek.top/Article/details/gttysvthki.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtpbtgvrck.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gtlkgsplkk.html

[F12] CSV 读写
来源：http://dali.shuidangran.top/Article/details/gtxbmcpyev.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnqzz.top/Article/details/gtkqikywqo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258.top/Article/details/gthmnnbidl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigufen.top/Article/details/gtqrdavrji.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gtehlctoms.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.smart0.xyz/Article/details/gtbgzcwjdr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yonumen.top/Article/details/gtljssbihd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xinyue.icu/Article/details/gtelcnmsmm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aibaodan.cn/Article/details/gttfqhxakd.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtfwyuduti.html

G. 面向对象
来源：http://dali.zhoulong.xyz/Article/details/gtcmhtyyxg.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqorebtnb.html

[G01] 定义类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwzhqyiu.html

Py:   class User: pass
来源：http://dali.ydzc1.top/Article/details/gtsnogozfy.html

PHP:  class User {}
来源：http://dali.sxryk.cn/Article/details/gtghxrsked.html

JS:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcphejarw.html

TS:   class User { name: string = ""; }
来源：http://dali.tanke756.top/Article/details/gtfwfmnexd.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtjhsoqpro.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gttwvhgxwc.html

Ruby: class User; end
来源：http://dali.jinqigufen.top/Article/details/gtuiutgdzx.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gturvoaqnv.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gttswljled.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yongpay.top/Article/details/gttsnhrauj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gtabyetvwk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmfmpumth.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gtblvfuygm.html

Java: User(String name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtddzdcier.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuxming.cn/Article/details/gtalcougxw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtlifpvkmp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.havefunace.top/Article/details/gtjvmztqnm.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gtgecjidsi.html

Py:   self.name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtvmmxwqyk.html

PHP:  public string $name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtwxbfbafp.html

JS:   this.name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtavamubdr.html

TS:   name: string = "x";
来源：http://dali.gotoacloud.top/Article/details/gtvllsxdbh.html

Java: private String name;
来源：http://dali.jinqigfzy.top/Article/details/gtekjebysb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cucudq.cn/Article/details/gtuawgjgpu.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtujgnqkzn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtobnhbkmo.html

[G04] 定义方法
来源：http://dali.gogol.net.cn/Article/details/gtjbygjmuq.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtnogwteex.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtsbersnue.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtdjrahbfs.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtftqehpph.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtvyayxjbk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtlxulqacn.html

Ruby: def greet; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtlbfyqefz.html

C#:   public string Greet() => Name;
来源：http://dali.cashguo.top/Article/details/gtlglnnsjp.html

[G05] 继承
来源：http://dali.zhengqikj.top/Article/details/gtpzuskcpt.html

Py:   class Admin(User): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtckrixzxq.html

PHP:  class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtoqeekoag.html

JS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtmukhprcd.html

TS:   class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtslymwzfk.html

Java: class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtuvklpalv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hysaishi.cn/Article/details/gtzjoasipf.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gtikgazbdr.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbiqgasdm.html

[G06] 重写方法
来源：http://dali.zhiwuduotai.top/Article/details/gtmpdjhfjp.html

Py:   def greet(self): return "admin"
来源：http://dali.cucudq.cn/Article/details/gtkenedrnw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtwfppieik.html

JS:   greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtntpzmogz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtjudogzut.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgreppbjr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yonumen.top/Article/details/gtzypohrjx.html

Ruby: def greet; "admin"; end
来源：http://dali.sysykeji.top/Article/details/gtpeuppilv.html

C#:   public override string Greet() => "admin";
来源：http://dali.shuidangran.top/Article/details/gtahtnlwkz.html

[G07] 调用父类方法
来源：http://dali.pycfn.com/Article/details/gtgmjsncev.html

Py:   super().greet()
来源：http://dali.daria6918.cn/Article/details/gterhowuiw.html

PHP:  parent::greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmabmnoy.html

JS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtcdkarxvw.html

TS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtopuzczrw.html

Java: super.greet();
来源：http://dali.yvedp.cn/Article/details/gtzxmdmmmd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgfzy.top/Article/details/gtnplxmrdg.html

Ruby: super
来源：http://dali.ppjwa.cn/Article/details/gtndjdzsdg.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gtipdnogen.html

[G08] 静态方法与属性
来源：http://dali.xuetiantiany.cn/Article/details/gtgoiyrqpj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gthikrjvsy.html

PHP:  public static function f() {}
来源：http://dali.gzhubu.top/Article/details/gtwtvnnyje.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gtcgtewkco.html

TS:   static f(): void {}
来源：http://dali.yuanzhike.top/Article/details/gtidqsdcsx.html

Java: static void f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnnpbtaj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gtgdxjqdwm.html

Ruby: def self.f; end
来源：http://dali.xziqi.cn/Article/details/gtwdmbsqhu.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtohupmmov.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gtmplslikd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daria6918.cn/Article/details/gtyyqyxvhe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hysaishi.cn/Article/details/gtguhcxuzi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jianghu66.top/Article/details/gtvfuwjnpd.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gtpujfszom.html

Java: interface Shape { double area(); }
来源：http://dali.yvedp.cn/Article/details/gtkxsjhorh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pycfn.com/Article/details/gtbaxsbaws.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yonumen.top/Article/details/gtnyeyzgzq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtknrksyuz.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gtfvmheiyr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dianchejie.cn/Article/details/gtkxrytoqr.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtudqioguz.html

JS:   #private 字段；其余公开
来源：http://dali.iojbl.cn/Article/details/gtuwsqigcf.html

TS:   public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtlpngttxg.html

Java: public / protected / private / 默认包级
来源：http://dali.jianghu66.top/Article/details/gthhuduovj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.9152youxi.cn/Article/details/gtuuyjvnme.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtagjycdzy.html

C#:   public / protected / private / internal
来源：http://dali.cqqwz.cn/Article/details/gtvtquxjfp.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gtkurjqyui.html

Py:   @property 与 @x.setter
来源：http://dali.pengpengdd.cyou/Article/details/gtygkqohtx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtgsleduhs.html

JS:   get name() { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtkwxqwgsd.html

TS:   get name(): string { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtvskhfahy.html

Java: public String getName() { return name; }
来源：http://dali.316326.xyz/Article/details/gtidxitwdo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtbnudmjuv.html

Ruby: attr_accessor :name
来源：http://dali.nanxuanxn.top/Article/details/gtdrqrtppf.html

C#:   public string Name { get; set; }
来源：http://dali.yvedp.cn/Article/details/gtvgffktuj.html

[G12] 对象转字符串
来源：http://dali.dianchejie.cn/Article/details/gtjyltlbri.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtivhbfmkv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtgypexxms.html

JS:   toString() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtszfkthjx.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gthsoufvvt.html

Java: @Override public String toString() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtwvdtevok.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtjuafczow.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtsqktoevy.html

C#:   public override string ToString() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gttknicnmt.html

[G13] 判断对象类型
来源：http://dali.cashguo.top/Article/details/gtjlloxvsy.html

Py:   isinstance(u, User)
来源：http://dali.sysykeji.top/Article/details/gtwuzxrbrl.html

PHP:  $u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtxttpsalj.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvgidopc.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtmlgascrd.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtfngrjvil.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gtqnknhljp.html

Ruby: u.is_a?(User)
来源：http://dali.daria6918.cn/Article/details/gtudqntlhl.html

C#:   u is User
来源：http://dali.mhx1999.top/Article/details/gtafmqmakz.html

[G14] 数据类 / record
来源：http://dali.yanxiufei.cn/Article/details/gtzlmqamxi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yongpay.top/Article/details/gtaijvbvkg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aizwys.cn/Article/details/gtkkalavrd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gtkzdtgdsj.html

TS:   type User = { name: string; age: number };
来源：http://dali.tianlin.xyz/Article/details/gtuqwcakoa.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gtuevxtkex.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nwbrower.top/Article/details/gtoynmejpx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gtvwrnasfp.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gtsjxiadif.html

[G15] 枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtaagtpsis.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.birdmap.top/Article/details/gtkqmwsewk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gtqyioljoj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cdnleiting.top/Article/details/gtjwxjlmdb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtdehjvfxm.html

Java: enum Color { RED, GREEN }
来源：http://dali.feifeiyinyue.top/Article/details/gtsvrpsabq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrlcttpo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.smart0.xyz/Article/details/gtjyybtcef.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtsjfhltqr.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gtcximfpiw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gtqvpbpddr.html

PHP:  get_object_vars($obj);
来源：http://dali.ydzc1.top/Article/details/gtiangklll.html

JS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gtmsjgavii.html

TS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtlzdrwgtp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dashuyun.cn/Article/details/gtmagdoqfk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dashuyun.cn/Article/details/gtjvkbskaq.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gtilxemqbh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gttbihmvuk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtfeatnvqc.html

H. 异常与错误处理
来源：http://dali.dianchejie.cn/Article/details/gtmtvevitm.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gthpkjisfh.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gtrdrjqwwo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxuanxn.top/Article/details/gtnpsnewhf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtmlnamuop.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtypisgbbz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtklncswfq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shzxlz.cn/Article/details/gtttwprojw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gtkulhdluc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gtlescdztd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yvedp.cn/Article/details/gtmukukufl.html

[H02] finally / ensure 收尾
来源：http://dali.cdnleiting.top/Article/details/gtkqzwccwc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gtmucnnjbz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtnejufipp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtvfwypqnu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtdqprapml.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtvwdpivmi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ybcxt.top/Article/details/gthxugynxs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuxming.cn/Article/details/gtpzgjcdaj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtxztauvsx.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gtgyfmnpuw.html

Py:   raise ValueError("错误信息")
来源：http://dali.quarkkingdee.top/Article/details/gtfhplvpsu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtsdrwazow.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtkbazzvpr.html

TS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtlyevholf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtfqzplcbo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gtcfmftimv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cashguo.top/Article/details/gtucnvmsbj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtxiiheovt.html

[H04] 自定义异常类型
来源：http://dali.nanxuanxn.top/Article/details/gtflyyhvdt.html

Py:   class MyError(Exception): pass
来源：http://dali.sweek.top/Article/details/gtuolzekir.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtqlwfzoyg.html

JS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtjbgatznw.html

TS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gtukauxony.html

Java: class MyException extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtomhbtrwz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxuanxn.top/Article/details/gtaobgcbrg.html

Ruby: class MyError < StandardError; end
来源：http://dali.dashuyun.cn/Article/details/gtkovlbxva.html

C#:   class MyException : Exception {}
来源：http://dali.chenlongwang.top/Article/details/gthmyfbhst.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gtjvacvtqe.html

Py:   except ValueError as e:
来源：http://dali.chenjidiqi.icu/Article/details/gtruupapbl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gttjpbjopq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtifntdury.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtpozxygnv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gtdhdlbbmi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gtnxkcuyqt.html

Ruby: rescue ArgumentError => e
来源：http://dali.haohaochexian.top/Article/details/gtzzkkusiv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhengqikj.top/Article/details/gtlekpbjzc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnqzz.top/Article/details/gtnwckvkgs.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gtjzxgbnzq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gtusjcwlqd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtkflkypqu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gtgyrnwcbz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yangfankeji.com/Article/details/gtxzyjhjyn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.0kj1m.cn/Article/details/gtvtdtbxrs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aizwys.cn/Article/details/gtemarnkgd.html

C#:   obj?.A?.B ?? default
来源：http://dali.yonumen.top/Article/details/gtccwtjuey.html

[H07] 断言
来源：http://dali.vqdsnc.cn/Article/details/gtfnbwgfyc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jiagoushi.top/Article/details/gtuqjvubwk.html

PHP:  assert($x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktverwpk.html

JS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtpzsvejkb.html

TS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtbwwjdtax.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gtdbzqogzi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.c1oappe.top/Article/details/gtctbxqsjd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gotoacloud.top/Article/details/gtzxxudwxk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlvfdzrg.html

[H08] 获取错误信息与堆栈
来源：http://dali.daria6918.cn/Article/details/gtrpkqwjpz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jlsjyb.cn/Article/details/gtreqrnswh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fengsongda.top/Article/details/gtceymwwpq.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gtywrfkusl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gtckvbfbse.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gtpwfpdafs.html

Go:   err.Error()
来源：http://dali.ydzc1.top/Article/details/gtmvcxjuad.html

Ruby: e.message;  e.backtrace
来源：http://dali.andypj.xyz/Article/details/gtbupmugut.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gtoorvmnix.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gtadxqhgdt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gtbbnrjmtl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yongpay.top/Article/details/gtuyhvyxwi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cdnleiting.top/Article/details/gtzuirjwlp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gtalixpxeo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmogsmmef.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sufxvd.cn/Article/details/gtfiiufove.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.birdmap.top/Article/details/gtnzydjyud.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jyoumei.cn/Article/details/gtbjpvqshj.html

[H10] 资源自动释放
来源：http://dali.shzxlz.cn/Article/details/gtawngqhnt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gtvvyfcxcw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.0kj1m.cn/Article/details/gtydkhzzuz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gtlxjuwvpo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtkwyofoif.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.havefunace.top/Article/details/gtmqhhfbsw.html

Go:   defer f.Close()
来源：http://dali.daria6918.cn/Article/details/gtvkfuspme.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cheryme.top/Article/details/gtrkfflzox.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtpzumhgrd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtthtpdimy.html

I. 正则表达式
来源：http://dali.pycfn.com/Article/details/gtuurbgszp.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofcwpxvo.html

[I01] 判断是否匹配
来源：http://dali.0kj1m.cn/Article/details/gtkxsywjvg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtrqzisnmv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtttltodkl.html

JS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gtrneswzin.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gtyemzhoea.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.bjfxy.top/Article/details/gtlnimbwsv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ybcxt.top/Article/details/gtzzdolgph.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gtnwtmlcui.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.bjfxy.top/Article/details/gtexietufx.html

[I02] 提取所有匹配
来源：http://dali.cucudq.cn/Article/details/gtjjvpvpfe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gtajuijens.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cucudq.cn/Article/details/gtfgsmrhhq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgufenzy.top/Article/details/gtoihnaobp.html

TS:   s.match(/\d+/g)
来源：http://dali.cheryme.top/Article/details/gtsvhggcnq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daria6918.cn/Article/details/gtlhcpaizr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hammf.cn/Article/details/gtctugkofm.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtsaczzbbe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtodxjuumk.html

[I03] 提取捕获分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmmrwfoi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnxiangtu.top/Article/details/gtkzfbxpog.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hysaishi.cn/Article/details/gtjzftuxhn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cqqwz.cn/Article/details/gtkobeirjj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shzxlz.cn/Article/details/gtqrkzrsbm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fzhhl.top/Article/details/gtcefmnwzn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.c1oappe.top/Article/details/gtrsjlqbed.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gtwgczojcr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuanzx.com/Article/details/gtqhugrefd.html

[I04] 正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtmyjnqwyg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlthrggse.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtxxzsiabo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtwqeqanhm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtlftzncon.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtuscqocrc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gtykwujkrn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258888.top/Article/details/gtfwerhtao.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtdfsufvms.html

[I05] 按正则拆分
来源：http://dali.tian-w.cn/Article/details/gtofwclpfa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aizwys.cn/Article/details/gtvtklzrlb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jianghu66.top/Article/details/gtbpyboqlb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtiyzevrak.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtcrdakjaq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.mhx1999.top/Article/details/gthnztbzld.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gtrdaammcb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtbmkstadk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ybcxt.top/Article/details/gticokajtx.html


<!-- 参考信息 -->