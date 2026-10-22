代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigfzy.top/Article/details/gtjmrnstps.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj202588.top/Article/details/gtaotifbkv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangdashe.top/Article/details/gtegyfkavk.html

TS:   // 同上
来源：http://dali.smart0.xyz/Article/details/gtfaywnwuz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gtkthvkfjj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgfzy.top/Article/details/gtextovfkt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gzhubu.top/Article/details/gtvudumjnk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sweek.top/Article/details/gtsxrtnlhc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gttpagypcy.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gtvbyppqex.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtsfjwiwac.html

[G01] 定义类
来源：http://dali.tanke756.top/Article/details/gtilzgahuk.html

Py:   class User: pass
来源：http://dali.xinyue.icu/Article/details/gtclpmrxfd.html

PHP:  class User {}
来源：http://dali.aizwys.cn/Article/details/gtqgghfwzf.html

JS:   class User {}
来源：http://dali.iojbl.cn/Article/details/gtjrszuiqd.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gtzytjnagc.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gthhnnykwz.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gtkgkmbtyu.html

Ruby: class User; end
来源：http://dali.yuxming.cn/Article/details/gtrgtuvyxu.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gteyskedqy.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gtovxocnxq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj202588.top/Article/details/gtofpbluui.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gtegecoqvt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtfcykarvu.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxuanxn.top/Article/details/gtmpzggzjr.html

Java: User(String name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtuzgzjavd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ehwqpu.com/Article/details/gtaewgelqv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gtancjxyah.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtcybozubs.html

[G03] 实例属性
来源：http://dali.yuxming.cn/Article/details/gtjalzfeci.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtxdaggnuw.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtuyofqvlr.html

JS:   this.name = "x";
来源：http://dali.sxryk.cn/Article/details/gtsuzxsawk.html

TS:   name: string = "x";
来源：http://dali.zhixingplan.top/Article/details/gtkwswolyn.html

Java: private String name;
来源：http://dali.smart0.xyz/Article/details/gtskipyftn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gtssfikqba.html

Ruby: @name = "x"
来源：http://dali.xylfe.cn/Article/details/gtkrzcjgqs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sweek.top/Article/details/gtnqtccoxc.html

[G04] 定义方法
来源：http://dali.haohaochexian.top/Article/details/gtuagnsgks.html

Py:   def greet(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtpwitljre.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdjbnepcv.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gturukqijo.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gturnhdplh.html

Java: String greet() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtxrbngqrz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtuyrzjnzs.html

Ruby: def greet; @name; end
来源：http://dali.yonumen.top/Article/details/gtanfycmrj.html

C#:   public string Greet() => Name;
来源：http://dali.nanxinkj.top/Article/details/gtfudfhtfm.html

[G05] 继承
来源：http://dali.daria6918.cn/Article/details/gtuqbbbfjr.html

Py:   class Admin(User): pass
来源：http://dali.fzhhl.top/Article/details/gtbbnulqkz.html

PHP:  class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtsydvjflq.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtpnyzgvow.html

TS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtzkarqrzn.html

Java: class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtazvjjsbh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.0kj1m.cn/Article/details/gtpcsasfpe.html

Ruby: class Admin < User; end
来源：http://dali.gaohongyu789.top/Article/details/gtfobbxrgw.html

C#:   class Admin : User {}
来源：http://dali.sweek.top/Article/details/gtkenrifpo.html

[G06] 重写方法
来源：http://dali.zhixingplan.top/Article/details/gtytjexkwl.html

Py:   def greet(self): return "admin"
来源：http://dali.daxiang520.top/Article/details/gtkwfjwqbi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtahzitmcw.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtqtrwpcvb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtlgdnfdqp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtazizhllh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jiagoushi.top/Article/details/gtoumxxovk.html

Ruby: def greet; "admin"; end
来源：http://dali.0kj1m.cn/Article/details/gtbxsblend.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gtrgepgdno.html

[G07] 调用父类方法
来源：http://dali.pengpengdd.cyou/Article/details/gtrgaewnco.html

Py:   super().greet()
来源：http://dali.pengpengdd.cyou/Article/details/gtswyvvdtp.html

PHP:  parent::greet();
来源：http://dali.kuanghao11.cn/Article/details/gtrfclucwx.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtitvmwcpi.html

TS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtomxhoehh.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gtxxqopfkw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yangfankeji.com/Article/details/gtixsyrnms.html

Ruby: super
来源：http://dali.ivvv.top/Article/details/gtdfzmiwvs.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gtlfbvfkwq.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gtloobeqbc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gtzczdiiah.html

PHP:  public static function f() {}
来源：http://dali.daxiang520.top/Article/details/gtptnneguz.html

JS:   static f() {}
来源：http://dali.ybcxt.top/Article/details/gtsmehrlxx.html

TS:   static f(): void {}
来源：http://dali.ydzc1.top/Article/details/gtzinocbrd.html

Java: static void f() {}
来源：http://dali.bjfxy.top/Article/details/gtemfjbefg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gthvisvsfb.html

Ruby: def self.f; end
来源：http://dali.zhiwuduotai.top/Article/details/gtjeuiunet.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtpfudlwoq.html

[G09] 接口 / 抽象类
来源：http://dali.hywenlv.cn/Article/details/gtpomcojej.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cashguo.top/Article/details/gtfthqslql.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ivvv.top/Article/details/gtzmfghmkl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.316326.xyz/Article/details/gtoocjngwl.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gtioqdevrt.html

Java: interface Shape { double area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkacgpxhi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gtxfkptpgi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cqqwz.cn/Article/details/gtgufhiqdx.html

C#:   interface IShape { double Area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvivbdgvx.html

[G10] 访问控制
来源：http://dali.jqgufenzy.top/Article/details/gteeqepahb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gtjolrhegi.html

PHP:  public / protected / private
来源：http://dali.havefunace.top/Article/details/gtflzukrel.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gteypqvssj.html

TS:   public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtmxmyjuyc.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gtthkqywmx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj202588.top/Article/details/gtqwcekbcm.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtjijmmwrx.html

C#:   public / protected / private / internal
来源：http://dali.0kj1m.cn/Article/details/gtvlnrryos.html

[G11] getter / setter
来源：http://dali.tanke756.top/Article/details/gtsbgflxpa.html

Py:   @property 与 @x.setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufoeuoyr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgxcgoaml.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtzhjkxtsm.html

TS:   get name(): string { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gthmxckjwg.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqaklbgq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtgbfaozba.html

Ruby: attr_accessor :name
来源：http://dali.hfpthk.cn/Article/details/gtzkcrezuk.html

C#:   public string Name { get; set; }
来源：http://dali.yj202588.top/Article/details/gttonqtqrz.html

[G12] 对象转字符串
来源：http://dali.yj202588.top/Article/details/gtmomhgofa.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtypwctfej.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtxhdnqcok.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtnbtbdika.html

TS:   toString(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtvddkurva.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtxihawxkv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gthvczuhix.html

Ruby: def to_s; @name; end
来源：http://dali.daxiang520.top/Article/details/gtiyngfmjw.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gtozghaavs.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gtewfswemg.html

Py:   isinstance(u, User)
来源：http://dali.yj20258.top/Article/details/gtwqofspyj.html

PHP:  $u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtmyevnfep.html

JS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtbrouquky.html

TS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtulhcelqm.html

Java: u instanceof User
来源：http://dali.xylfe.cn/Article/details/gthvvndfkf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenjidiqi.icu/Article/details/gtxiwixqhl.html

Ruby: u.is_a?(User)
来源：http://dali.sxryk.cn/Article/details/gtsvcxkoid.html

C#:   u is User
来源：http://dali.sufxvd.cn/Article/details/gtcowqiiih.html

[G14] 数据类 / record
来源：http://dali.andypj.xyz/Article/details/gtbwnjrcge.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gtapfswyaj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hongshengwenyu.top/Article/details/gtuexdhylr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gtbvaemlbr.html

TS:   type User = { name: string; age: number };
来源：http://dali.aibaodan.cn/Article/details/gtocsglacp.html

Java: record User(String name, int age) {}
来源：http://dali.guowangkeji.top/Article/details/gtofucndxa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gtwkaxobgp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gtzhsjvelg.html

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gthlbhpwvr.html

[G15] 枚举
来源：http://dali.yongpay.top/Article/details/gtqjaihppc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jyoumei.cn/Article/details/gtsazdrefd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrtbqdjwx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhongyouzk.top/Article/details/gtujhgngev.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtlvussbeu.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenjidiqi.icu/Article/details/gtoqaycarf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gtccreqxeh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yueranfly.top/Article/details/gtnifyjlrs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxwejkmf.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gtojuizrrg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tianlin.xyz/Article/details/gtcizvgcfx.html

PHP:  get_object_vars($obj);
来源：http://dali.ybcxt.top/Article/details/gtdokhgqgr.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtjsleggsf.html

TS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gteriypksi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gogol.net.cn/Article/details/gtrwpjiiwe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.vqdsnc.cn/Article/details/gtynnlmnjp.html

Ruby: obj.instance_variables
来源：http://dali.nwbrower.top/Article/details/gthgwencwq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtrwpgughu.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtlbumpfcm.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gtfvrnnvsl.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtykpcytgr.html

[H01] try / catch 基础
来源：http://dali.smart0.xyz/Article/details/gtvecgicrs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ybcxt.top/Article/details/gtllrbxkmc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gtcabbrxqc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtealuwscu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtifkunbvi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.haohaochexian.top/Article/details/gtxlsdloct.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjjdhsum.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgufenzy.top/Article/details/gtsgbzhaym.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sxryk.cn/Article/details/gtaojqyymg.html

[H02] finally / ensure 收尾
来源：http://dali.zdqjudy.top/Article/details/gtjuwmkmsl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gtttulocsj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtfqnmcxhi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtnlkflnft.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtrczwypog.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtfzmemvgg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigufen.top/Article/details/gtvfltygsh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gtusjsfoeo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtulhfzbdi.html

[H03] 主动抛出异常
来源：http://dali.yangfankeji.com/Article/details/gtvtybqqrd.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gtimftidgt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtgwvcnqkv.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtpalshivy.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtyddpgeyf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtozhqcwun.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzelhwyz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zycfv.cn/Article/details/gtmduyqqst.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtevjbyzgy.html

[H04] 自定义异常类型
来源：http://dali.yongpay.top/Article/details/gthsnunqtn.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtetnlztjf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtnxlasjai.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gtktuhrcfu.html

TS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtaetxbqhe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofsiyxhe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gtppzsepll.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigufen.top/Article/details/gtapuvdzon.html

C#:   class MyException : Exception {}
来源：http://dali.yvedp.cn/Article/details/gtbiukzysd.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gthmbsofbn.html

Py:   except ValueError as e:
来源：http://dali.jlsjyb.cn/Article/details/gtvmxpjmme.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daxiang520.top/Article/details/gtxcgzufdp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtpdmawvny.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gtjuscvxus.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gteoivhvwg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gtpnrugfrt.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gtveiotmpl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.snrcjt.cn/Article/details/gtouxnebwg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.mhx1999.top/Article/details/gtugkkqxjb.html

Py:   value = d.get("k") or default
来源：http://dali.aizwys.cn/Article/details/gtaagcnewl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gtzqxvfwmy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gtvsherzxl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gtvozrpznv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tianlin.xyz/Article/details/gtmggebtdd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.haohaochexian.top/Article/details/gtoxfqwvop.html

Ruby: d&.dig(:a, :b)
来源：http://dali.bjfxy.top/Article/details/gtggsnmsqo.html

C#:   obj?.A?.B ?? default
来源：http://dali.jiagoushi.top/Article/details/gtxhmwbjqo.html

[H07] 断言
来源：http://dali.tian-w.cn/Article/details/gtogjvowcf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yanxiufei.cn/Article/details/gtiamopeyk.html

PHP:  assert($x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gttufxsadq.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtiyaywwjs.html

TS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtlgfhidzs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gtxngczbpf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfduhdyy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gtkfufnssn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtimkpwqzs.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnxiangtu.top/Article/details/gtjgdwegun.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gzhubu.top/Article/details/gtseypvwbu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pycfn.com/Article/details/gtuonyzkvi.html

JS:   e.message;  e.stack
来源：http://dali.bjfxy.top/Article/details/gtocihtamt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gtwrvbpoac.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daria6918.cn/Article/details/gtteasrsyo.html

Go:   err.Error()
来源：http://dali.vqdsnc.cn/Article/details/gtluovvpwk.html

Ruby: e.message;  e.backtrace
来源：http://dali.0kj1m.cn/Article/details/gttgjuzhul.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258888.top/Article/details/gtdngwrjng.html

[H09] 带错误码的异常
来源：http://dali.jianghu66.top/Article/details/gtlyxkwryy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aizwys.cn/Article/details/gtomlggmmm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gtcjqooigy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangshuangyany.cn/Article/details/gtsddvfqzh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuanzx.com/Article/details/gtcxwpmbwc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gzhubu.top/Article/details/gttbshceha.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sufxvd.cn/Article/details/gtdrtyygcm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pycfn.com/Article/details/gthafyhhuu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgfzy.top/Article/details/gtukixmnsb.html

[H10] 资源自动释放
来源：http://dali.jinqigfzy.top/Article/details/gthjeddsem.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinyuanbaomall.cn/Article/details/gturrgzibu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.redwolf501.top/Article/details/gtfldviony.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gthzlgrewx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtmzvksfdu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ehwqpu.com/Article/details/gtfcefnmer.html

Go:   defer f.Close()
来源：http://dali.guowangkeji.top/Article/details/gtuobcyymt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cheryme.top/Article/details/gtrkstfgnx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtywljadlv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtscccfgzl.html

I. 正则表达式
来源：http://dali.jinqigufen.top/Article/details/gtmglfrkmv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtbcmlbihm.html

[I01] 判断是否匹配
来源：http://dali.hnqzz.top/Article/details/gtxcccmewa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gttmrczxcw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtekpawnke.html

JS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtqpfkzipm.html

TS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gtureurjcf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhoulong.xyz/Article/details/gtgtporslp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.redwolf501.top/Article/details/gtboxubvmg.html

Ruby: s.match?(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gtoresgmnc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcoflqab.html

[I02] 提取所有匹配
来源：http://dali.iojbl.cn/Article/details/gtugvigynk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtnhqtfeuj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yvedp.cn/Article/details/gtozsvcuoo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guannengcc.top/Article/details/gtnczxuuxa.html

TS:   s.match(/\d+/g)
来源：http://dali.gaohongyu789.top/Article/details/gtrupkvjru.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtsvvmwbep.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gtdrjcnmmo.html

Ruby: s.scan(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gtmzzwmyfe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jianghu66.top/Article/details/gttnwuiwsb.html

[I03] 提取捕获分组
来源：http://dali.9152youxi.cn/Article/details/gtceaicbsl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuanzx.com/Article/details/gtosayrtwi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gtdejokwyt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tianlin.xyz/Article/details/gtgabvgsqt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sxryk.cn/Article/details/gtvcnimsgw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gtuskfphpr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrrvlzyw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ppjwa.cn/Article/details/gtshxasioj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sufxvd.cn/Article/details/gtrayaeqct.html

[I04] 正则替换
来源：http://dali.mhx1999.top/Article/details/gtiyfbywwy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gthtzdqlhn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ivvv.top/Article/details/gtparrccyi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gttewzjryl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtrwezivjc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtowdrypxm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yvedp.cn/Article/details/gtcsxtumkv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtkxzwczmk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gtsymxsrvr.html

[I05] 按正则拆分
来源：http://dali.xylfe.cn/Article/details/gtlkgtgizt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sweek.top/Article/details/gtacyvutiu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gthqrovvcp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtffsleibd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdslrruqz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ybcxt.top/Article/details/gtiwaryryx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjacosgd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtamzhhyuz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shzxlz.cn/Article/details/gtptrmzvag.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yangfankeji.com/Article/details/gtaqzkzefr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtinqlgewh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgufenzy.top/Article/details/gtsqttnulx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtungcfhnu.html


<!-- 参考信息 -->