代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtgwlalcvy.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtetlkxnfv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pycfn.com/Article/details/gtfihgsouj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtfcuzdkcv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtkicjsjte.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtgailrxns.html

[F11] 复制与移动文件
来源：http://dali.cqqwz.cn/Article/details/gtevrblmqf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gttxacrywz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenlongwang.top/Article/details/gtgquuuagx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtxpaigrzi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtfnhngldf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yonumen.top/Article/details/gtjrulwywm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.haohaochexian.top/Article/details/gtkbdetopd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtzqhsdllo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuanzhike.top/Article/details/gtybiopjnb.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gtebhqpzno.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuxming.cn/Article/details/gttezofbhp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gtbzeifpbw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuetiantiany.cn/Article/details/gtdbbviqhj.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gtqznsoejc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenjidiqi.icu/Article/details/gthdaygeln.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gtenhcygbb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cdnleiting.top/Article/details/gtmsleaqoe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gtdaqxntuh.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtqkiqachi.html

G. 面向对象
来源：http://dali.yuanzhike.top/Article/details/gtutkomnhw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtijwvvdjq.html

[G01] 定义类
来源：http://dali.birdmap.top/Article/details/gtuhztkqfz.html

Py:   class User: pass
来源：http://dali.mhx1999.top/Article/details/gtzoysiewd.html

PHP:  class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtstgzefnb.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtejudcany.html

TS:   class User { name: string = ""; }
来源：http://dali.andypj.xyz/Article/details/gtbyrsldkm.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtetqdwfbt.html

Go:   type User struct { Name string }
来源：http://dali.jlsjyb.cn/Article/details/gttekvsakf.html

Ruby: class User; end
来源：http://dali.meibo888.top/Article/details/gtoxliqgcr.html

C#:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtczektpir.html

[G02] 构造函数
来源：http://dali.xziqi.cn/Article/details/gtlcjqwphm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aizwys.cn/Article/details/gtwjxukkzi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gtqynaurhg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnfkukar.html

TS:   constructor(public name: string) {}
来源：http://dali.c1oappe.top/Article/details/gtkibfgpfc.html

Java: User(String name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gthyzijgfl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.havefunace.top/Article/details/gthoeiwhlr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnqzz.top/Article/details/gttmsvzset.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtpzvuzyqw.html

[G03] 实例属性
来源：http://dali.pycfn.com/Article/details/gtanhvlwfq.html

Py:   self.name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddmwdlgu.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtldckyjzy.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtdfpgkata.html

TS:   name: string = "x";
来源：http://dali.xziqi.cn/Article/details/gtplmijnvg.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gtkmlikszu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yangfankeji.com/Article/details/gturfrsfbi.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtbauxxsju.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gtkoebipbq.html

[G04] 定义方法
来源：http://dali.9152youxi.cn/Article/details/gtcikudbzj.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gtodjsakde.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtfwnqcsyx.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtscxflchp.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtlegpmmos.html

Java: String greet() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gthqdpnovg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtfzccflui.html

Ruby: def greet; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtrhokhxae.html

C#:   public string Greet() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwbnptcy.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtawoulekw.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gtgtufbywe.html

PHP:  class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtjeibpgle.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtbqyavpru.html

TS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtwqbiwjwh.html

Java: class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gttbhzvebi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gtgnesfavs.html

Ruby: class Admin < User; end
来源：http://dali.ivvv.top/Article/details/gtmgkvdqyq.html

C#:   class Admin : User {}
来源：http://dali.316326.xyz/Article/details/gtltqdoomq.html

[G06] 重写方法
来源：http://dali.kuanghao11.cn/Article/details/gtvfhbkbap.html

Py:   def greet(self): return "admin"
来源：http://dali.yuanzhike.top/Article/details/gtuioepzec.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtepttdrqf.html

JS:   greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtqgbrohyb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtmoanvono.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgjhprdmq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guannengcc.top/Article/details/gtjmykgeuk.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gtyxtjrkty.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gtzsbotffi.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gtgyyhkpez.html

Py:   super().greet()
来源：http://dali.andypj.xyz/Article/details/gtvfpjoaoc.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsextjoaw.html

JS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtvuhwczuc.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gteqadghfr.html

Java: super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtqzjaxysr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gtytpdwnen.html

Ruby: super
来源：http://dali.jinqigfzy.top/Article/details/gtxrzhsfhq.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtfgzumnxz.html

[G08] 静态方法与属性
来源：http://dali.pengpengdd.cyou/Article/details/gtjpjwyzlb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shzxlz.cn/Article/details/gtogjjvkdd.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxemdtbg.html

JS:   static f() {}
来源：http://dali.shuidangran.top/Article/details/gttotpbszi.html

TS:   static f(): void {}
来源：http://dali.birdmap.top/Article/details/gtcwljlzts.html

Java: static void f() {}
来源：http://dali.jiagoushi.top/Article/details/gtdplslcxd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gzhubu.top/Article/details/gtjppgnuhe.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsnkkxah.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gtsgoiyvaf.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gtzwttltsk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gtyjisdvjg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.birdmap.top/Article/details/gtuzczumgg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.0kj1m.cn/Article/details/gttcaugulu.html

TS:   interface Shape { area(): number; }
来源：http://dali.birdmap.top/Article/details/gtmwwhxyzi.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsoetjkg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgufenzy.top/Article/details/gttmlurtfw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtizslweuu.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtvwttursx.html

[G10] 访问控制
来源：http://dali.haohaochexian.top/Article/details/gttlmfipiy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.svipenyu.cn/Article/details/gtkxvpsxog.html

PHP:  public / protected / private
来源：http://dali.smart0.xyz/Article/details/gttpxlxqmb.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gtkhktfnny.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtikttubcs.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gtoelruhkj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gtnxwnkisj.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtzriwmtom.html

C#:   public / protected / private / internal
来源：http://dali.fengsongda.top/Article/details/gtrfnkbcqx.html

[G11] getter / setter
来源：http://dali.yj20258.top/Article/details/gteuxufdav.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gtjqzzviry.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtthutjkea.html

JS:   get name() { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtoyvsijco.html

TS:   get name(): string { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gttidzqhns.html

Java: public String getName() { return name; }
来源：http://dali.yj20258.top/Article/details/gttllxrwfq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtqkgzxofv.html

Ruby: attr_accessor :name
来源：http://dali.yvedp.cn/Article/details/gtdbhtnnjr.html

C#:   public string Name { get; set; }
来源：http://dali.c1oappe.top/Article/details/gtelopiwtj.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gtqkxduclr.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtygneplkc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtuingktmt.html

JS:   toString() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gthohgzmbq.html

TS:   toString(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtqldgyleu.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gteelnfakc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtrrkbbykr.html

Ruby: def to_s; @name; end
来源：http://dali.fzhhl.top/Article/details/gtpmgjaqqy.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgfzy.top/Article/details/gtzwdkajmx.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gtpaxqmhds.html

Py:   isinstance(u, User)
来源：http://dali.haohaochexian.top/Article/details/gtjykawosf.html

PHP:  $u instanceof User
来源：http://dali.birdmap.top/Article/details/gtavgmekvp.html

JS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtdfxyncok.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtlgtukkfl.html

Java: u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtmdiahigs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gtrcpafrcc.html

Ruby: u.is_a?(User)
来源：http://dali.cashguo.top/Article/details/gtkjfxdjzk.html

C#:   u is User
来源：http://dali.yvedp.cn/Article/details/gtgjvdstlv.html

[G14] 数据类 / record
来源：http://dali.xziqi.cn/Article/details/gtcsatkyay.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhengqikj.top/Article/details/gtduyiqcoj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gtjjkvkoxn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gtsgtabqvg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhongyouzk.top/Article/details/gtpkfdbndc.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gtftyiobah.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tanke756.top/Article/details/gtjbjaytyl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenjidiqi.icu/Article/details/gtcgbcotzs.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gtbfpsmnya.html

[G15] 枚举
来源：http://dali.yongpay.top/Article/details/gtcwrpxddo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gzhubu.top/Article/details/gtzmglugov.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shangyingyoupin.top/Article/details/gttqixumoe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fengsongda.top/Article/details/gtndissgqo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtuxnwzgyn.html

Java: enum Color { RED, GREEN }
来源：http://dali.svipenyu.cn/Article/details/gteyajcbye.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gtaocneudn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gtcgjcirgb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gtoyujqhop.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gtrkorsvai.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dashuyun.cn/Article/details/gtqlqzobed.html

PHP:  get_object_vars($obj);
来源：http://dali.dashuyun.cn/Article/details/gtpsahpzva.html

JS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtddpupvog.html

TS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gtspahbqyv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gtwrermewx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tian-w.cn/Article/details/gtrxqjlzxf.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gtkyeemivt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gtwnkmiigj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtgemrukkd.html

H. 异常与错误处理
来源：http://dali.nanxuanxn.top/Article/details/gtgvpgekbg.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtkvswpplz.html

[H01] try / catch 基础
来源：http://dali.chenjidiqi.icu/Article/details/gtjckuhcne.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ppjwa.cn/Article/details/gtfcctwvhk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tianlin.xyz/Article/details/gtefksksfs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcomxtkx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtragoghth.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gtkydpxkch.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hysaishi.cn/Article/details/gtrtjdddze.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cucudq.cn/Article/details/gtrogxhzpt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxinkj.top/Article/details/gtxzgwubks.html

[H02] finally / ensure 收尾
来源：http://dali.xuetiantiany.cn/Article/details/gtjdxnecsa.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.havefunace.top/Article/details/gtgsygrazx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtvhgmtfrr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtbomqhdgb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtabzdynyb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtmnczuauy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.316326.xyz/Article/details/gtuvvmijtl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jlsjyb.cn/Article/details/gtiirwhzpb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtscfrkggb.html

[H03] 主动抛出异常
来源：http://dali.havefunace.top/Article/details/gtuutrrzaz.html

Py:   raise ValueError("错误信息")
来源：http://dali.dianchejie.cn/Article/details/gtxjdjuyji.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtxamajugh.html

JS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtxxrlntxh.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtanptpegn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtvblcjflo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xziqi.cn/Article/details/gtkpaymnlx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gtljvpygyu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtlzpncjtt.html

[H04] 自定义异常类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtuneqrpso.html

Py:   class MyError(Exception): pass
来源：http://dali.hywenlv.cn/Article/details/gtzevclsty.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtghxqjcqk.html

JS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtrdqhagmv.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtmobxzfkx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtchhfkevs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daria6918.cn/Article/details/gtcxsqtmbn.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuanzhike.top/Article/details/gtvwkdqfzs.html

C#:   class MyException : Exception {}
来源：http://dali.xylfe.cn/Article/details/gtnjlnakzl.html

[H05] 捕获特定类型
来源：http://dali.chenlongwang.top/Article/details/gtvxlrzmcc.html

Py:   except ValueError as e:
来源：http://dali.hysaishi.cn/Article/details/gtjemojaad.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gtcniwkjkt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtcvejervs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gtuqgxlbsd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgfzy.top/Article/details/gtttmrbqwm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgufenzy.top/Article/details/gtlfflzveb.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangshuangyany.cn/Article/details/gtqwdsvwiw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgpnhfck.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hywenlv.cn/Article/details/gtuicxvnku.html

Py:   value = d.get("k") or default
来源：http://dali.316326.xyz/Article/details/gtchlldfbd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtuebihbuh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtfmreihkr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gtvgauevcu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dashuyun.cn/Article/details/gturrgyaao.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tianlin.xyz/Article/details/gtkmyzimrb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yanxiufei.cn/Article/details/gtaawtbgez.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258888.top/Article/details/gtvvbzxyrq.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gtljtselhm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gtvbnqljzl.html

PHP:  assert($x > 0);
来源：http://dali.sxryk.cn/Article/details/gtvuinqclp.html

JS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtidvpwyln.html

TS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gticuekbui.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gtxbrntgqb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgufenzy.top/Article/details/gtdgokitvy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gttaicjzdf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtjmgjftkq.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhiwuduotai.top/Article/details/gtsyzzlnly.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangshuangyany.cn/Article/details/gtvscpkpfa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnhvciet.html

JS:   e.message;  e.stack
来源：http://dali.aibaodan.cn/Article/details/gtsicsoqfu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hysaishi.cn/Article/details/gtdwtdvnow.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cqqwz.cn/Article/details/gtxqcxatcr.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gtrvubygsp.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgawqemai.html

C#:   e.Message;  e.StackTrace
来源：http://dali.snrcjt.cn/Article/details/gtivebmqyc.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gtacyhegfh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yongpay.top/Article/details/gtcagsovjm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daria6918.cn/Article/details/gtziqgoyhm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.andypj.xyz/Article/details/gtlqktlhek.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.snrcjt.cn/Article/details/gtksjoeyfk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tian-w.cn/Article/details/gtyggudzwe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gtvdkagwfn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yangfankeji.com/Article/details/gtxvhkzdnj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gtjpudlgwm.html

[H10] 资源自动释放
来源：http://dali.jyoumei.cn/Article/details/gtpwwqptrr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ppjwa.cn/Article/details/gtkgvbsbpw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.c1oappe.top/Article/details/gttbgaxolr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtuexunzkh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtovatqmvl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuetiantiany.cn/Article/details/gtxsydcvby.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gtbrcyyphv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gtadvmzogi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtcctsgkpi.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtotpidcsk.html

I. 正则表达式
来源：http://dali.zhixingplan.top/Article/details/gtozpzeokk.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtxmlkxphx.html

[I01] 判断是否匹配
来源：http://dali.svipenyu.cn/Article/details/gtdtqcuodt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gtdziulolm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cucudq.cn/Article/details/gtikkssppj.html

JS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtgkzflwdv.html

TS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtpaemcagg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgfzy.top/Article/details/gtlqctoupi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtksvppfdi.html

Ruby: s.match?(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtjvzyakcd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gthkenveyo.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gtczlmeagd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gtgcvzbche.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yongpay.top/Article/details/gtdcimexko.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daxiang520.top/Article/details/gtnutcuami.html

TS:   s.match(/\d+/g)
来源：http://dali.ydzc1.top/Article/details/gtysnufqhb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pycfn.com/Article/details/gtfbsgsphn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsboskjy.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtsscxqydq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gttjubmgaf.html

[I03] 提取捕获分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyznidwop.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gtzibbainj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuxming.cn/Article/details/gtdjcvodcx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tanke756.top/Article/details/gtmbrckjhg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cucudq.cn/Article/details/gtvqxdqsgt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj202588.top/Article/details/gtnewgryfj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.mhx1999.top/Article/details/gtvcrxktii.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daxiang520.top/Article/details/gtucaaqdje.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gtzwahkwsz.html

[I04] 正则替换
来源：http://dali.yj202588.top/Article/details/gtjfonyzdv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ivvv.top/Article/details/gtwrlrttoq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gtyzpdtsot.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqujviwl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gtkfsdwxql.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtilykqtjr.html


<!-- 参考信息 -->