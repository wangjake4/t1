代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nwbrower.top/Article/details/gttylsucta.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtapyhsekw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gtwgutcvhc.html

[F12] CSV 读写
来源：http://dali.yj20258888.top/Article/details/gtqlultobn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuanzhike.top/Article/details/gtyabyifqi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yanxiufei.cn/Article/details/gtxjwhqlwm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gaohongyu789.top/Article/details/gtgdgdypfx.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gtlriypsot.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gtchaysocd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtukxzuziu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ehwqpu.com/Article/details/gtfngjcinz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gtlzisnwmh.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtgrphggep.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gthxnrinkk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtnszrrkdb.html

[G01] 定义类
来源：http://dali.hammf.cn/Article/details/gtfhkbbwhu.html

Py:   class User: pass
来源：http://dali.daxiang520.top/Article/details/gtaouvjwnd.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gtwmsvhkyh.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtgmqyxmnq.html

TS:   class User { name: string = ""; }
来源：http://dali.yvedp.cn/Article/details/gttcvnnxza.html

Java: class User {}
来源：http://dali.ivvv.top/Article/details/gttlmlzgno.html

Go:   type User struct { Name string }
来源：http://dali.xziqi.cn/Article/details/gtswmqcclp.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gttbxhvvch.html

C#:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtvijtwkaz.html

[G02] 构造函数
来源：http://dali.iojbl.cn/Article/details/gtivwhtkpp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.quarkkingdee.top/Article/details/gtipuguemf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.c1oappe.top/Article/details/gticniyper.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtiyfymijw.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gtmhmahokq.html

Java: User(String name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtidshobmu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xziqi.cn/Article/details/gteyypsfqh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gtsekiympz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtsfnqbdqm.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gtgadhyrid.html

Py:   self.name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpihdaau.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtbugtmriz.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gtjwzloxca.html

TS:   name: string = "x";
来源：http://dali.0kj1m.cn/Article/details/gtvxnlttdo.html

Java: private String name;
来源：http://dali.tanke756.top/Article/details/gtmfuvwxag.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ehwqpu.com/Article/details/gtbudpkpzj.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtytjniyya.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuanzx.com/Article/details/gtfodibgfh.html

[G04] 定义方法
来源：http://dali.zhengqikj.top/Article/details/gtimhuzasp.html

Py:   def greet(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gtfsjggclo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtvmrqmkco.html

JS:   greet() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxgvhawb.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtwomdbzkh.html

Java: String greet() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqrshqst.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtyhnuulhc.html

Ruby: def greet; @name; end
来源：http://dali.sysykeji.top/Article/details/gtfyohltst.html

C#:   public string Greet() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtszwlucli.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gtmautsrdo.html

Py:   class Admin(User): pass
来源：http://dali.tianlin.xyz/Article/details/gtzwjzcjra.html

PHP:  class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtqtgxktqk.html

JS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtycnriadd.html

TS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtjalojlzp.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtsxnlhumm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.316326.xyz/Article/details/gtxxfaulcm.html

Ruby: class Admin < User; end
来源：http://dali.vqdsnc.cn/Article/details/gtqcifwznd.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtoznexoao.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gtuccrcfbf.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gtdwlhgycs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtcdepomeh.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzguttdzz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyogaumub.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtrmjqttjr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jianghu66.top/Article/details/gtgrdludct.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gtvhdcxnng.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuanzhike.top/Article/details/gtoxjzhkse.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gtrhdxmeth.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gtmiqtehrk.html

PHP:  parent::greet();
来源：http://dali.c1oappe.top/Article/details/gthbwlxjnf.html

JS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtwnnmrovz.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gtmiuazfqr.html

Java: super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtnpjuodhw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pycfn.com/Article/details/gtvxatewws.html

Ruby: super
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxmzqawr.html

C#:   base.Greet();
来源：http://dali.yj202588.top/Article/details/gtlnjknrim.html

[G08] 静态方法与属性
来源：http://dali.cucudq.cn/Article/details/gtgpbgajgq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.kuanghao11.cn/Article/details/gtenxwyibo.html

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gtxcghdmmt.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtvracvvoi.html

TS:   static f(): void {}
来源：http://dali.aizwys.cn/Article/details/gtghrksdbb.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtmzvjsdct.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shuidangran.top/Article/details/gthyjyodsr.html

Ruby: def self.f; end
来源：http://dali.guowangkeji.top/Article/details/gtojnnufef.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gtekrnxzgh.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskgmpdlu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daria6918.cn/Article/details/gthasdyewp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwdwysox.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gtkqssyfoi.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhengqikj.top/Article/details/gtpegehpal.html

Java: interface Shape { double area(); }
来源：http://dali.tianlin.xyz/Article/details/gtylhsnpkm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cqqwz.cn/Article/details/gtreyklqyp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigfzy.top/Article/details/gtlxvxkfib.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtxbotappl.html

[G10] 访问控制
来源：http://dali.jqgufenzy.top/Article/details/gtekrnjjra.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gotoacloud.top/Article/details/gtrhdohoai.html

PHP:  public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtqvdhsobg.html

JS:   #private 字段；其余公开
来源：http://dali.hywenlv.cn/Article/details/gtxmdodybb.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtilwtwnwa.html

Java: public / protected / private / 默认包级
来源：http://dali.havefunace.top/Article/details/gtqchprlfd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gzhubu.top/Article/details/gtfiuwdjmd.html

Ruby: public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtssublbqt.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gttvlnxyiq.html

[G11] getter / setter
来源：http://dali.ivvv.top/Article/details/gtynzuqrom.html

Py:   @property 与 @x.setter
来源：http://dali.hnqzz.top/Article/details/gtpumsknlu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtxdvgijvi.html

JS:   get name() { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtbatmqyvn.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtpjjecwpz.html

Java: public String getName() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtiykpkeen.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtrfuiwlor.html

Ruby: attr_accessor :name
来源：http://dali.yj20258.top/Article/details/gtaytvotzf.html

C#:   public string Name { get; set; }
来源：http://dali.ivvv.top/Article/details/gtebmfkhac.html

[G12] 对象转字符串
来源：http://dali.ehwqpu.com/Article/details/gtjlgrflgd.html

Py:   def __str__(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtyqiyflun.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtdfupwmal.html

JS:   toString() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtkcwsuirs.html

TS:   toString(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtgmpanyvb.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtaymwbpph.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtiytecssq.html

Ruby: def to_s; @name; end
来源：http://dali.smart0.xyz/Article/details/gtcraprhai.html

C#:   public override string ToString() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtqdjctmbu.html

[G13] 判断对象类型
来源：http://dali.zdqjudy.top/Article/details/gtudwtsuqn.html

Py:   isinstance(u, User)
来源：http://dali.shuidangran.top/Article/details/gtpjodmbba.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtaylyyvfp.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtulidkkyq.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtcyzkzesh.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtncmcdzci.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gtpwrfrqbg.html

Ruby: u.is_a?(User)
来源：http://dali.hnxiangtu.top/Article/details/gtcnkythum.html

C#:   u is User
来源：http://dali.nanxinkj.top/Article/details/gticdqexwo.html

[G14] 数据类 / record
来源：http://dali.dianchejie.cn/Article/details/gtiicovpxy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gtetjhkkwy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.vqdsnc.cn/Article/details/gtsqvthdnm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zdqjudy.top/Article/details/gtgxgutmiu.html

TS:   type User = { name: string; age: number };
来源：http://dali.gogol.net.cn/Article/details/gtcyocaisu.html

Java: record User(String name, int age) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtdjjgojys.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sysykeji.top/Article/details/gtpmmuabif.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gtbldtfbth.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gtspcfxddg.html

[G15] 枚举
来源：http://dali.mhx1999.top/Article/details/gtpwxhwoeh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuanzx.com/Article/details/gtbiwqvqkr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jyoumei.cn/Article/details/gtwviiphwv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuxming.cn/Article/details/gtxcucpwpg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtbrpvibwd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhengqikj.top/Article/details/gtxwhndfmb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangkeji.top/Article/details/gterjozipp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gtucbfioje.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtbnikmyun.html

[G16] 对象转数组 / 字典
来源：http://dali.yongpay.top/Article/details/gtxqhlhdym.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.mhx1999.top/Article/details/gtwqqbdgbf.html

PHP:  get_object_vars($obj);
来源：http://dali.ehwqpu.com/Article/details/gtdglojbxi.html

JS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtoeatvtez.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtmoaecfkk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hfpthk.cn/Article/details/gtnszsgvvm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gtvfpbyper.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gtibkfppxm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtspozxdzb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtiqtlcuww.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gtovjqblsl.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtngnulcef.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gtaeytiuee.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gtfdlpdjsk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmwkqask.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtzlhsacpl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtkmvjzlgt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhengqikj.top/Article/details/gthdhiltyc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shuidangran.top/Article/details/gtnjdnqstt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnkcvbfq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gtyzyghxue.html

[H02] finally / ensure 收尾
来源：http://dali.jyoumei.cn/Article/details/gtwkjpwrqr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nwbrower.top/Article/details/gtyzttfbic.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtaukwkjel.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtvyxogooh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtauuqxfvc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxseeigwc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gtzygimxbv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.snrcjt.cn/Article/details/gtpzdomlth.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtdxuhduoa.html

[H03] 主动抛出异常
来源：http://dali.meibo888.top/Article/details/gtbyvnemva.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenzaomai.com/Article/details/gtzlgjhzqt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtxhydeipw.html

JS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtbwgtljiy.html

TS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtzmccrqna.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtmazglufz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsxjvads.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gtmlbvgsut.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gthjoeneqe.html

[H04] 自定义异常类型
来源：http://dali.sufxvd.cn/Article/details/gtitkhseen.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gthzkguxwz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtczplslud.html

JS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gtreogqwnx.html

TS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gtpjkkbrff.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpzdmnvtd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shangyingyoupin.top/Article/details/gtdtcgcaii.html

Ruby: class MyError < StandardError; end
来源：http://dali.pycfn.com/Article/details/gtrhbodtci.html

C#:   class MyException : Exception {}
来源：http://dali.nwbrower.top/Article/details/gtoovoueer.html

[H05] 捕获特定类型
来源：http://dali.yvedp.cn/Article/details/gttytojvnr.html

Py:   except ValueError as e:
来源：http://dali.cheryme.top/Article/details/gtyqfaejhk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pengpengdd.cyou/Article/details/gtyfttaimf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtmspaszes.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtytfwvkrj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqxqbvnpj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgufenzy.top/Article/details/gtytvhlsgw.html

Ruby: rescue ArgumentError => e
来源：http://dali.sweek.top/Article/details/gthmlbrbwa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gtyhggpvjg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yangfankeji.com/Article/details/gtfhadbevy.html

Py:   value = d.get("k") or default
来源：http://dali.xuanzx.com/Article/details/gtvowvilcf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gthuclwpei.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtpgiecfxw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtmaiakbvq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gtsoqvncug.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ppjwa.cn/Article/details/gtizwzqsfq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.meibo888.top/Article/details/gttpainpip.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gtfzvjmdbg.html

[H07] 断言
来源：http://dali.nanxuanxn.top/Article/details/gtokbownbq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hywenlv.cn/Article/details/gtertdzakq.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvbcdetw.html

JS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtqopevasv.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtlolpxfij.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gtmwmwljvf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tian-w.cn/Article/details/gtdnnlobaz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.iojbl.cn/Article/details/gtlfjqickf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtfbpsegic.html

[H08] 获取错误信息与堆栈
来源：http://dali.sufxvd.cn/Article/details/gtvxqguzvh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ehwqpu.com/Article/details/gttoouxkhf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gtzkiskcew.html

JS:   e.message;  e.stack
来源：http://dali.yangfankeji.com/Article/details/gttmwaasrx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shzxlz.cn/Article/details/gtjlvpznah.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gtkowuggic.html

Go:   err.Error()
来源：http://dali.ehwqpu.com/Article/details/gtjyvkvkeh.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhongyouzk.top/Article/details/gtsbhynwxl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gtcwvstkje.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gtzhdicivz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tian-w.cn/Article/details/gtxteiuybz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gaohongyu789.top/Article/details/gtekrssnpw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shzxlz.cn/Article/details/gtgcmroqys.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gzhubu.top/Article/details/gtqphppwaf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteupekzdj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yanxiufei.cn/Article/details/gtjscccajr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.vqdsnc.cn/Article/details/gtsrkzlorp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gtxrcagmsl.html

[H10] 资源自动释放
来源：http://dali.xziqi.cn/Article/details/gtiorxyycm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxuanxn.top/Article/details/gtmcxnnnbt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.snrcjt.cn/Article/details/gtdcviuqcv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtxplqydyy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gteglksvrn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj202588.top/Article/details/gtqvvlwnsz.html

Go:   defer f.Close()
来源：http://dali.chenlongwang.top/Article/details/gtejtpxbun.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.snrcjt.cn/Article/details/gtxvabtcku.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtaljvopbo.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtnvuytfxq.html

I. 正则表达式
来源：http://dali.yvedp.cn/Article/details/gtrzgxuvnk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtldnimooi.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gtvlfhnxwm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtkrrpesvu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtzendrpoe.html

JS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gtdlksgjqr.html

TS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gtckdzbakp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aizwys.cn/Article/details/gtqqmgqtai.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.havefunace.top/Article/details/gthuohbikk.html

Ruby: s.match?(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gtkrzktpot.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtmwankooy.html

[I02] 提取所有匹配
来源：http://dali.dashuyun.cn/Article/details/gtmkldecol.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtfesbghpn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj202588.top/Article/details/gttojpqfew.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hongshengwenyu.top/Article/details/gtjrjfjdsd.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtcgebzgfn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtlldylguy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtdhiwqaep.html

Ruby: s.scan(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtbdzuxlwn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtqmwlxrts.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gtlyiufbcp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yongpay.top/Article/details/gtslvtwshy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guowangkeji.top/Article/details/gtfqrsmrsi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.smart0.xyz/Article/details/gtguimokgn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtpmxhasaf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgufenzy.top/Article/details/gtyjkokemp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gtqulfklos.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtdbzdgvvb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yanxiufei.cn/Article/details/gtmcfcrlbi.html

[I04] 正则替换
来源：http://dali.nwbrower.top/Article/details/gtqcuvjfmv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtabzrxeod.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gtntlywgne.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaowdyadw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtleelkika.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtjbrezhsh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.c1oappe.top/Article/details/gtnftmmezv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yueranfly.top/Article/details/gtnmfgxwbg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gtclnzwppn.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gtatajieez.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sufxvd.cn/Article/details/gtyzlybxnl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.c1oappe.top/Article/details/gtivyafvnk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtwklmfxuy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtdcxuguyx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj202588.top/Article/details/gtgzkokdjm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtslzoecmd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtufoqvdft.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxinkj.top/Article/details/gtbmtqhtsp.html


<!-- 参考信息 -->