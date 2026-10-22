代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenzaomai.com/Article/details/gtsfzowmnu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gthgxpzyxq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuetiantiany.cn/Article/details/gtjzpydxlt.html

TS:   // 同上
来源：http://dali.mhx1999.top/Article/details/gttoxlrlre.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhongyouzk.top/Article/details/gtpwtoeadb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sxryk.cn/Article/details/gtsocyscyf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhiwuduotai.top/Article/details/gtowgjycsl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtsampxcom.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtvyflxiqz.html

G. 面向对象
来源：http://dali.sweek.top/Article/details/gtpmwtjcdm.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtmjvcnefw.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gtmofgtfck.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gttufxaiix.html

PHP:  class User {}
来源：http://dali.yonumen.top/Article/details/gtydvnlmzn.html

JS:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtollegizc.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gtheknpggx.html

Java: class User {}
来源：http://dali.sweek.top/Article/details/gtdrfvvskn.html

Go:   type User struct { Name string }
来源：http://dali.c1oappe.top/Article/details/gtubtuwgpv.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtsnanppxr.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtebtdxafz.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gthemcjjba.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gteymexnso.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aibaodan.cn/Article/details/gttenzjssh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtvnbupxdo.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigufen.top/Article/details/gtmvhbxblh.html

Java: User(String name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gtksunbswh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yangfankeji.com/Article/details/gtnfmnomni.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.meibo888.top/Article/details/gttotrwnwf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzcznwsgz.html

[G03] 实例属性
来源：http://dali.hammf.cn/Article/details/gtqxtyahax.html

Py:   self.name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtspzdkmro.html

PHP:  public string $name = "x";
来源：http://dali.xziqi.cn/Article/details/gtppwvltul.html

JS:   this.name = "x";
来源：http://dali.yvedp.cn/Article/details/gtoykxfdgd.html

TS:   name: string = "x";
来源：http://dali.xinyue.icu/Article/details/gtkfwfvqnp.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gtvopqqqwc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jianghu66.top/Article/details/gtashaxfbu.html

Ruby: @name = "x"
来源：http://dali.guannengcc.top/Article/details/gtujrvzcde.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ehwqpu.com/Article/details/gtbpsbleka.html

[G04] 定义方法
来源：http://dali.ydzc1.top/Article/details/gtsphyjmlq.html

Py:   def greet(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gtfjjgqhgi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gthkqzrdgv.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtkrpgmhnr.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtkzgnjjoo.html

Java: String greet() { return name; }
来源：http://dali.cashguo.top/Article/details/gtafwkkxgj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtzyavxxpk.html

Ruby: def greet; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtkvptkrwy.html

C#:   public string Greet() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtonxvvfnk.html

[G05] 继承
来源：http://dali.c1oappe.top/Article/details/gtgusbjysm.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtadghhluf.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtvkioowsc.html

JS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtoseymrpl.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtssfunufi.html

Java: class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtiovinczi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dashuyun.cn/Article/details/gtymrrtncv.html

Ruby: class Admin < User; end
来源：http://dali.gotoacloud.top/Article/details/gtarkwqiag.html

C#:   class Admin : User {}
来源：http://dali.fzhhl.top/Article/details/gtdywdatpu.html

[G06] 重写方法
来源：http://dali.jinqigfzy.top/Article/details/gtefxuhwhg.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgfzy.top/Article/details/gtxocxxwwm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtmjzjgvjl.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gthniexjad.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtxribfiwv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtuqkwcqtx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.andypj.xyz/Article/details/gtujegkzpw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgaygbefg.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gtganvdnuz.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gtlhwikgck.html

Py:   super().greet()
来源：http://dali.ydzc1.top/Article/details/gtsjquarwl.html

PHP:  parent::greet();
来源：http://dali.dashuyun.cn/Article/details/gtdswpazpn.html

JS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtoqhqihaq.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltetalku.html

Java: super.greet();
来源：http://dali.cucudq.cn/Article/details/gtyegdjrak.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.smart0.xyz/Article/details/gtxfuhwlju.html

Ruby: super
来源：http://dali.dianchejie.cn/Article/details/gtofutmspm.html

C#:   base.Greet();
来源：http://dali.hammf.cn/Article/details/gtehdwdtjm.html

[G08] 静态方法与属性
来源：http://dali.316326.xyz/Article/details/gtkzvrcphy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.kuanghao11.cn/Article/details/gtsfyqgiql.html

PHP:  public static function f() {}
来源：http://dali.yonumen.top/Article/details/gtzsypnvtt.html

JS:   static f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtosebwhvn.html

TS:   static f(): void {}
来源：http://dali.aizwys.cn/Article/details/gtqvoyquaj.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gtrqzqbbww.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tianlin.xyz/Article/details/gtrlylbisp.html

Ruby: def self.f; end
来源：http://dali.andypj.xyz/Article/details/gtxlldgfji.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gtiumclicj.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gtukzeblni.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nwbrower.top/Article/details/gtpnebtzbt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xziqi.cn/Article/details/gtsihfewby.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenzaomai.com/Article/details/gtqmaswcoe.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gtbeiqekiw.html

Java: interface Shape { double area(); }
来源：http://dali.cdnleiting.top/Article/details/gtfwwrahpg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gtqryntzrp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gtbccyebzd.html

C#:   interface IShape { double Area(); }
来源：http://dali.zdqjudy.top/Article/details/gtenyrhfge.html

[G10] 访问控制
来源：http://dali.sxryk.cn/Article/details/gtzmqgsgku.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.snrcjt.cn/Article/details/gtsjdbgijj.html

PHP:  public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtxlreonbp.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigufen.top/Article/details/gtdmecgrsr.html

TS:   public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtlscytyrf.html

Java: public / protected / private / 默认包级
来源：http://dali.redwolf501.top/Article/details/gttmohqpfp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gtgkgfftpw.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtrkbfuvzk.html

C#:   public / protected / private / internal
来源：http://dali.jqgufenzy.top/Article/details/gtvuolicdy.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gtcktymbpt.html

Py:   @property 与 @x.setter
来源：http://dali.hysaishi.cn/Article/details/gtswodypkz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtzqyaqwfh.html

JS:   get name() { return this._name; }
来源：http://dali.yongpay.top/Article/details/gtnlypxglo.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtrjtsxbmb.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvhjzanit.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtksdybxip.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gtpdywvfqu.html

C#:   public string Name { get; set; }
来源：http://dali.nanxuanxn.top/Article/details/gtbmqtjukf.html

[G12] 对象转字符串
来源：http://dali.ydzc1.top/Article/details/gtjuuvlmzc.html

Py:   def __str__(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gtqmiwjiss.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtqniwfzbp.html

JS:   toString() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtqnoebejg.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtcnxqvwim.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtxvxonfkn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtmisupynv.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gtfkkvkujy.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtcuxmyieo.html

[G13] 判断对象类型
来源：http://dali.guannengcc.top/Article/details/gtieswnmse.html

Py:   isinstance(u, User)
来源：http://dali.ydzc1.top/Article/details/gtborxryac.html

PHP:  $u instanceof User
来源：http://dali.yonumen.top/Article/details/gtybyyiifq.html

JS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtruompgna.html

TS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtkqucvchm.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gttyxxuxtn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gtcnnqnsqe.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gtukqzjruv.html

C#:   u is User
来源：http://dali.sufxvd.cn/Article/details/gtqilbfxeg.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gtvujtoxig.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.vqdsnc.cn/Article/details/gtwqtymnzn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ppjwa.cn/Article/details/gtxozzqnxd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xylfe.cn/Article/details/gtvutzxiac.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gtfymylnjo.html

Java: record User(String name, int age) {}
来源：http://dali.yuanzhike.top/Article/details/gtwfppzefz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhengqikj.top/Article/details/gtpfjjfldm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.316326.xyz/Article/details/gtqefbmnzs.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjynhiqfm.html

[G15] 枚举
来源：http://dali.gaohongyu789.top/Article/details/gtzuerafrh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gtrsglrgym.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenlongwang.top/Article/details/gtrqzzfdoz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gtcmbrcwxb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gtwcdjuqht.html

Java: enum Color { RED, GREEN }
来源：http://dali.zdqjudy.top/Article/details/gtdkvtdbcf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gtpnafzrly.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aibaodan.cn/Article/details/gtgtczsyuq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gtfqnffhbq.html

[G16] 对象转数组 / 字典
来源：http://dali.xylfe.cn/Article/details/gtdbftfqoa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gtnlmyrzjj.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gtadrwgwao.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtgwdmvfze.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtltmtqlal.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gtzhqdglnd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gtlbgrsbng.html

Ruby: obj.instance_variables
来源：http://dali.havefunace.top/Article/details/gttpslhyuk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gtscvzoyan.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmgvmrmz.html

H. 异常与错误处理
来源：http://dali.haohaochexian.top/Article/details/gtmgnmokzy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinksotjm.html

[H01] try / catch 基础
来源：http://dali.xuanzx.com/Article/details/gttuauyype.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangdashe.top/Article/details/gtoczpbbks.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtnceklgcu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtqflzdyox.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtolblxlbq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gtfufknpvz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnqzz.top/Article/details/gtguzjqfyx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqnybajw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gttgwiarnp.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gtyugweuec.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gtyxxbbmnk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtdqhssmyi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtaahquoru.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtcmzoqrjs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtsqqruldu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhongyouzk.top/Article/details/gthsntdptx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.feifeiyinyue.top/Article/details/gtbnkwdjpw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtiolkhsra.html

[H03] 主动抛出异常
来源：http://dali.zhongyouzk.top/Article/details/gtzfjyfqdz.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gtwjpywtid.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gttfmgiznm.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzipvdau.html

TS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gthcgtltkx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtseskwywu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yanxiufei.cn/Article/details/gtdpfmzivx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pengpengdd.cyou/Article/details/gtwdcgpgsk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtnwcbsnea.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gtbhuxklsu.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnopfwlm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gttfvphilz.html

JS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gtydhlxjrm.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvubznahu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtapumpvhu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gttrqsgdgb.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnxiangtu.top/Article/details/gtltpyofez.html

C#:   class MyException : Exception {}
来源：http://dali.dianchejie.cn/Article/details/gtwjjjvvjt.html

[H05] 捕获特定类型
来源：http://dali.chenlongwang.top/Article/details/gtcnrcuzev.html

Py:   except ValueError as e:
来源：http://dali.nanxinkj.top/Article/details/gtkdxxkodi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pengpengdd.cyou/Article/details/gtbqwcxkyp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gtciqcsubn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gtjgqnahnx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yanxiufei.cn/Article/details/gtmdapdeur.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gtrvnhdrrc.html

Ruby: rescue ArgumentError => e
来源：http://dali.ydzc1.top/Article/details/gtzwaovfth.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sysykeji.top/Article/details/gtozknbzly.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtwvpkcmbf.html

Py:   value = d.get("k") or default
来源：http://dali.hnxiangtu.top/Article/details/gtsfoxmfbu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gtilqxjblj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtlwkvuysa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtnivvpurv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guannengcc.top/Article/details/gtkbmsamxb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenlongwang.top/Article/details/gtzlajvqts.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhongyouzk.top/Article/details/gtsadygjlj.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gtyvngpmhw.html

[H07] 断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhxuoybi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhengqikj.top/Article/details/gtsqoynpdw.html

PHP:  assert($x > 0);
来源：http://dali.xziqi.cn/Article/details/gtvfgqitxa.html

JS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtnporvlld.html

TS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtneylikir.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gtcaaxynel.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gtybhpklzi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gotoacloud.top/Article/details/gtiozegtbq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtiztvmyoh.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gtyrfdqmcf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gtoddaecui.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gtzevevabf.html

JS:   e.message;  e.stack
来源：http://dali.redwolf501.top/Article/details/gtgtixdkxs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tianlin.xyz/Article/details/gtvwwmrxdj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hysaishi.cn/Article/details/gtadztkcjg.html

Go:   err.Error()
来源：http://dali.gaohongyu789.top/Article/details/gtawjpbehb.html

Ruby: e.message;  e.backtrace
来源：http://dali.guowangkeji.top/Article/details/gtlkdotxfc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dashuyun.cn/Article/details/gtrhvpxsrh.html

[H09] 带错误码的异常
来源：http://dali.tian-w.cn/Article/details/gtjhlrzpdd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gtuhttpppn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nwbrower.top/Article/details/gtzdhqmeet.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yvedp.cn/Article/details/gtyxrizijk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gtpuezklfz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtglisbg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxinkj.top/Article/details/gtcilulbko.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gtclngmvqv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gtrjsflfgx.html

[H10] 资源自动释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgeymkebd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258.top/Article/details/gtlrlvrcfd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aizwys.cn/Article/details/gtgufadeoc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gtmttsgife.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtbhgnflvq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tianlin.xyz/Article/details/gtmyoabmtg.html

Go:   defer f.Close()
来源：http://dali.snrcjt.cn/Article/details/gtzfnobfpe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhiwuduotai.top/Article/details/gtdacvrrxv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtsqbyxspd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtdvuwbmge.html

I. 正则表达式
来源：http://dali.yanxiufei.cn/Article/details/gtgdjjrkhm.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtpjhybsnb.html

[I01] 判断是否匹配
来源：http://dali.yj202588.top/Article/details/gtzspbdvuw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtszoywlgq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtngzgunao.html

JS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gttgxpjfod.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gtsxxsaudg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhiwuduotai.top/Article/details/gthntqiqvk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.9152youxi.cn/Article/details/gtxuqjfecx.html

Ruby: s.match?(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtfvrvpbxm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cheryme.top/Article/details/gtqrchssba.html

[I02] 提取所有匹配
来源：http://dali.ehwqpu.com/Article/details/gtehknucnx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gtgbtzwjva.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gtwoxtacof.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hammf.cn/Article/details/gtympwxtoj.html

TS:   s.match(/\d+/g)
来源：http://dali.yuxming.cn/Article/details/gtysptwpwl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aizwys.cn/Article/details/gtzztyeyep.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gtxslvpeyw.html

Ruby: s.scan(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxivlfvs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daxiang520.top/Article/details/gthkolmjbf.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gtqzgiyosx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shuidangran.top/Article/details/gtyovzgcyy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtxwqyqscw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.vqdsnc.cn/Article/details/gtmauqiiea.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yongpay.top/Article/details/gthmjnbxrv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gotoacloud.top/Article/details/gtgrbhqrhw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cashguo.top/Article/details/gtzgvauviz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuxming.cn/Article/details/gthjvsreco.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zycfv.cn/Article/details/gtlgjbkaaj.html

[I04] 正则替换
来源：http://dali.yvedp.cn/Article/details/gtusnljsrd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gtmnejlgah.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yueranfly.top/Article/details/gtyeyhlham.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtaudhbkjk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtchqipyxn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cashguo.top/Article/details/gtcpscpowi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yongpay.top/Article/details/gtgkwswnyk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxinkj.top/Article/details/gtdqdzbjno.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gtcvtyszsq.html

[I05] 按正则拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtmkkfdigh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gtapovaqce.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtaldgphil.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtxesrhrfr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiuhvvpxs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yangfankeji.com/Article/details/gtfbuxlgct.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258.top/Article/details/gtstmkwvbk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gtfhieffxy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gttjmovrwl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuanzx.com/Article/details/gtefynirur.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtizqpapus.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhongyouzk.top/Article/details/gtukrpvhoa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gtrlkpgtbd.html


<!-- 参考信息 -->