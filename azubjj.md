代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtqblpzvzp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtrudcuzwy.html

[F11] 复制与移动文件
来源：http://dali.cdnleiting.top/Article/details/gtclcbmtwf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtfpjpgjlh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gtyofyfaun.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtmunfzviq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtedfaszbh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gtcsynnvfc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgfzy.top/Article/details/gthgyovxfh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtjdmavwrv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gtmmeulrbg.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gtatbfdnvz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aibaodan.cn/Article/details/gtdqnfyhwm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aibaodan.cn/Article/details/gtuntpvpxw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.redwolf501.top/Article/details/gtyxdxfpni.html

TS:   // 同上
来源：http://dali.sufxvd.cn/Article/details/gtdwaqljkz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj202588.top/Article/details/gtgsipyrwl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yanxiufei.cn/Article/details/gtskohvpvg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258888.top/Article/details/gtxzrhktog.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjgltztx.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtwnnickun.html

G. 面向对象
来源：http://dali.xziqi.cn/Article/details/gtwhdkkaje.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtsbztsynu.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gtfoihvbuk.html

Py:   class User: pass
来源：http://dali.wangshuangyany.cn/Article/details/gtddybwiud.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gtcmutowzo.html

JS:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtkritjzxm.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigfzy.top/Article/details/gtndamlnbi.html

Java: class User {}
来源：http://dali.xinyue.icu/Article/details/gtiagozdpw.html

Go:   type User struct { Name string }
来源：http://dali.yongpay.top/Article/details/gtubbcfwol.html

Ruby: class User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtrqbmodhm.html

C#:   class User {}
来源：http://dali.ivvv.top/Article/details/gtajbtojsq.html

[G02] 构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtusnwizxh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yongpay.top/Article/details/gtlykdildh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.birdmap.top/Article/details/gtjdsdlaub.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtsmgwpgip.html

TS:   constructor(public name: string) {}
来源：http://dali.gzhubu.top/Article/details/gtoqmovvfe.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtdzkkezlg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yueranfly.top/Article/details/gtaxyyhzsw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gtrctzegwa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcyzfhrh.html

[G03] 实例属性
来源：http://dali.zycfv.cn/Article/details/gtiijjotlh.html

Py:   self.name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtiullvhoj.html

PHP:  public string $name = "x";
来源：http://dali.cheryme.top/Article/details/gttqzcwwew.html

JS:   this.name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtataoyjbm.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gttjmnwoqy.html

Java: private String name;
来源：http://dali.ivvv.top/Article/details/gtiirzqfjr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.andypj.xyz/Article/details/gthlnqgjei.html

Ruby: @name = "x"
来源：http://dali.haohaochexian.top/Article/details/gtgeoeremb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigufen.top/Article/details/gteacnhvgi.html

[G04] 定义方法
来源：http://dali.nwbrower.top/Article/details/gtvjmftcsh.html

Py:   def greet(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtxffoeefa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtvycvapsi.html

JS:   greet() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gttuyjizzw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtmeatyced.html

Java: String greet() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtgbbdievk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtlqlqzeya.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gtqrvzbxhb.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtxymgqfuv.html

[G05] 继承
来源：http://dali.vqdsnc.cn/Article/details/gtheddlpwe.html

Py:   class Admin(User): pass
来源：http://dali.cheryme.top/Article/details/gtfqomsfpa.html

PHP:  class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtyxtgdzdl.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtwmavizej.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtkhnsryve.html

Java: class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpijeptkl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.mhx1999.top/Article/details/gtdwegcqbw.html

Ruby: class Admin < User; end
来源：http://dali.wangshuangyany.cn/Article/details/gtsmqjufit.html

C#:   class Admin : User {}
来源：http://dali.hnqzz.top/Article/details/gtyzwkawne.html

[G06] 重写方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtozdkyufr.html

Py:   def greet(self): return "admin"
来源：http://dali.aizwys.cn/Article/details/gtzlappjas.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtxtacucyo.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtigtygchr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtcpinxsat.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtveagsnci.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gtkbrpfomn.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gtixwugcsq.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuanzhike.top/Article/details/gtpmrnkvvv.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gtgfpndtbx.html

Py:   super().greet()
来源：http://dali.hfpthk.cn/Article/details/gtdfrjkbfs.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtcwsccosx.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtsoxgwauz.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtrptkspwg.html

Java: super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtlpdycfdz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tianlin.xyz/Article/details/gtsrtkgqsn.html

Ruby: super
来源：http://dali.nanxinkj.top/Article/details/gtoeyjpijv.html

C#:   base.Greet();
来源：http://dali.hfpthk.cn/Article/details/gtlrbndqdt.html

[G08] 静态方法与属性
来源：http://dali.gotoacloud.top/Article/details/gtikyzakii.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangtech.top/Article/details/gtsezqunxr.html

PHP:  public static function f() {}
来源：http://dali.yj20258888.top/Article/details/gtfbfhwblw.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gtkdoxpzdq.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gtekieepoo.html

Java: static void f() {}
来源：http://dali.sweek.top/Article/details/gtbuadzpnc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhixingplan.top/Article/details/gthefiiqgc.html

Ruby: def self.f; end
来源：http://dali.yonumen.top/Article/details/gteshcxcvr.html

C#:   public static void F() {}
来源：http://dali.yanxiufei.cn/Article/details/gtmhpyqjvy.html

[G09] 接口 / 抽象类
来源：http://dali.nanxuanxn.top/Article/details/gthogkudxd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gtyxgytqzl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yanxiufei.cn/Article/details/gthvbuqhyw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycpmhvno.html

TS:   interface Shape { area(): number; }
来源：http://dali.hfpthk.cn/Article/details/gtvaswgmrr.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gttmpjfsjt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gtznxncdxq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daria6918.cn/Article/details/gtpfqotxvq.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gtjmnfrnzc.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gtzqdfeszm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cqqwz.cn/Article/details/gtytrmczzz.html

PHP:  public / protected / private
来源：http://dali.birdmap.top/Article/details/gtsyjkzald.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gtkapbrosh.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gtqwipzknh.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gttkznflac.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.quarkkingdee.top/Article/details/gthlmhwckz.html

Ruby: public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtxgebnmln.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gtlfdabpmg.html

[G11] getter / setter
来源：http://dali.quarkkingdee.top/Article/details/gtymfwwign.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gtipygpvwd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtjobzcged.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtimtvfcwg.html

TS:   get name(): string { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtjnevldmr.html

Java: public String getName() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtynshasez.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtpneaglzr.html

Ruby: attr_accessor :name
来源：http://dali.yj202588.top/Article/details/gtclpxavzj.html

C#:   public string Name { get; set; }
来源：http://dali.yj202588.top/Article/details/gtmhrivjzy.html

[G12] 对象转字符串
来源：http://dali.redwolf501.top/Article/details/gtiekbcjew.html

Py:   def __str__(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtuueqiall.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtcxalqopr.html

JS:   toString() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtljudnspo.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtfhghdegm.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtljhmnqby.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtgnxvxqcn.html

Ruby: def to_s; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtzmydidnz.html

C#:   public override string ToString() => Name;
来源：http://dali.shzxlz.cn/Article/details/gtrtrhorvs.html

[G13] 判断对象类型
来源：http://dali.sufxvd.cn/Article/details/gtlpniohrk.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gtmiuwjgpz.html

PHP:  $u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtwgopdyil.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtsiwpmdis.html

TS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtswhfvvwn.html

Java: u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtxvluvbjf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258888.top/Article/details/gthocriyvt.html

Ruby: u.is_a?(User)
来源：http://dali.yonumen.top/Article/details/gtnojzsqpd.html

C#:   u is User
来源：http://dali.jinqigfzy.top/Article/details/gtikxaitua.html

[G14] 数据类 / record
来源：http://dali.jiagoushi.top/Article/details/gtduwlgyjk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgufenzy.top/Article/details/gtrphdurwe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxinkj.top/Article/details/gteflbhxtq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gthaybogjd.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gtdbnzctbk.html

Java: record User(String name, int age) {}
来源：http://dali.cdnleiting.top/Article/details/gtwltnocwp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ivvv.top/Article/details/gtzgmzmapc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gtlfobncee.html

C#:   record User(string Name, int Age);
来源：http://dali.guannengcc.top/Article/details/gtcgttkiqd.html

[G15] 枚举
来源：http://dali.shzxlz.cn/Article/details/gtgupbqyhp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ppjwa.cn/Article/details/gtxpforbsn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtsyoayefr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqxvrwpx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gtsrhinnvs.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuetiantiany.cn/Article/details/gtzdidtcxi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tian-w.cn/Article/details/gtdrmkwfqz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258.top/Article/details/gtlvudpmcl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtiomloinr.html

[G16] 对象转数组 / 字典
来源：http://dali.xylfe.cn/Article/details/gtaqmxvedp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ehwqpu.com/Article/details/gtypopbyph.html

PHP:  get_object_vars($obj);
来源：http://dali.hnxiangtu.top/Article/details/gtnwdbrbcw.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtzxlaptaf.html

TS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtmiruzoyg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gthgmcxgrg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gtjezpyskw.html

Ruby: obj.instance_variables
来源：http://dali.snrcjt.cn/Article/details/gtvtyqjnpa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtnitdyywg.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtablkngds.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gtymctpsls.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmobxspau.html

[H01] try / catch 基础
来源：http://dali.kuanghao11.cn/Article/details/gthxtgsxvm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmztbokpp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.birdmap.top/Article/details/gtednwzvxz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtrmefhxkq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtkeaqcvst.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gtshzpbzfb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fengsongda.top/Article/details/gthuzexpid.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqwknadb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gtyvaechyr.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjuxxjvr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gteblcvtum.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtpcgdjfea.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtswbblgkp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtgmhyaqkw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtyvnkhhkz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fzhhl.top/Article/details/gtytrmkzwc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnqzz.top/Article/details/gtbnnoqnwc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtdnewzdvk.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gtqitcwfxa.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gthmtgfabp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtzgskljat.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtlilwkkdb.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gthxtvpiwe.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtukmarsck.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dianchejie.cn/Article/details/gtijktgzxr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhiwuduotai.top/Article/details/gttqobirhv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtzvcbbaqp.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtczudivxp.html

Py:   class MyError(Exception): pass
来源：http://dali.pengpengdd.cyou/Article/details/gtcesobirn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtjwfaidfk.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtvudafajr.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtsfmesedf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtxbakusbk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daria6918.cn/Article/details/gttbhcultj.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangdashe.top/Article/details/gtvyxkpwhi.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gthnmhrovu.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gtrqlisyjn.html

Py:   except ValueError as e:
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlzrnzan.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gtrutdnnpd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwbfcwtc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gthocmyqcz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.quarkkingdee.top/Article/details/gtnfgttvdo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gtafrexier.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gtcvxnsyaj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhongyouzk.top/Article/details/gtjjawssed.html

[H06] 可选值 / 空值安全访问
来源：http://dali.redwolf501.top/Article/details/gtvrrelyps.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258888.top/Article/details/gtmvcimmvy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gttfqcchfb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtlcmxfyzd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtmjhksklv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sxryk.cn/Article/details/gtsmyzhwtd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guannengcc.top/Article/details/gthepmukol.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytoxivrs.html

C#:   obj?.A?.B ?? default
来源：http://dali.cashguo.top/Article/details/gtqorvmgjr.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gtviaqzdcv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guowangkeji.top/Article/details/gtkswcccuu.html

PHP:  assert($x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtzlauzorz.html

JS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gttmeblgql.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtwbcvdxzx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gtzebsnxjx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gtgdfjuhyf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gtidcnglon.html

C#:   Debug.Assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtytyptubo.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncdowmsv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aibaodan.cn/Article/details/gtmdcixaqa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gtmmucrmqt.html

JS:   e.message;  e.stack
来源：http://dali.jlsjyb.cn/Article/details/gtwskuckgc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenlongwang.top/Article/details/gtbssaebxe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnxiangtu.top/Article/details/gtrmrdrzhb.html

Go:   err.Error()
来源：http://dali.cashguo.top/Article/details/gtrxjdeozo.html

Ruby: e.message;  e.backtrace
来源：http://dali.cashguo.top/Article/details/gtihzehwdt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuanzx.com/Article/details/gtjlbfzedi.html

[H09] 带错误码的异常
来源：http://dali.xziqi.cn/Article/details/gtuakhthlf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daxiang520.top/Article/details/gtrxrespny.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj202588.top/Article/details/gtrfqheebm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfkobpxj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sysykeji.top/Article/details/gtvcsxaszi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gtsggldwuf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gotoacloud.top/Article/details/gtcftkjybt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gtzeeesuuz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guowangkeji.top/Article/details/gtkskvmvbv.html

[H10] 资源自动释放
来源：http://dali.snrcjt.cn/Article/details/gtkvajowxo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.c1oappe.top/Article/details/gtteksszfj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxinkj.top/Article/details/gtwnmxvena.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gticvbgaan.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gtabhnigxv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gtsdimzgph.html

Go:   defer f.Close()
来源：http://dali.mhx1999.top/Article/details/gtnsaztdyf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuanzhike.top/Article/details/gtzdhqzwvp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gtgnwxbdmn.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtpxpvdhke.html

I. 正则表达式
来源：http://dali.zhongyouzk.top/Article/details/gtaglakcaq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtaolpuhsm.html

[I01] 判断是否匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtjftwfzug.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gtghbswyph.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ybcxt.top/Article/details/gtslrkgcmu.html

JS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtcjonfthl.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gtlqvkxuza.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ybcxt.top/Article/details/gtqawnrjha.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtjxkpsoqq.html

Ruby: s.match?(/\d+/)
来源：http://dali.yonumen.top/Article/details/gtytueqgro.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ehwqpu.com/Article/details/gtpvfljdir.html

[I02] 提取所有匹配
来源：http://dali.guowangkeji.top/Article/details/gtntehmldy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gtpkenjvor.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xziqi.cn/Article/details/gtmlwfenhj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cdnleiting.top/Article/details/gtffnwqmns.html

TS:   s.match(/\d+/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnhixiie.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ppjwa.cn/Article/details/gtbborcivq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gtzbwsxbkw.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gttuvqoutd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tian-w.cn/Article/details/gttnsijekz.html

[I03] 提取捕获分组
来源：http://dali.svipenyu.cn/Article/details/gtxclefqlu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guowangkeji.top/Article/details/gtukonoyuq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtxfkmsmyc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.birdmap.top/Article/details/gtfipjkitz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxdxdqbi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxuanxn.top/Article/details/gtfnoxsfxr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gtjdtwpfsk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hysaishi.cn/Article/details/gtmiejuyov.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.mhx1999.top/Article/details/gtiraropoj.html

[I04] 正则替换
来源：http://dali.yj20258.top/Article/details/gtpolgksmt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtnubfofzu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zycfv.cn/Article/details/gtrnftkcjn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gtnidmgesa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gtikxbyfoe.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.316326.xyz/Article/details/gttzduasci.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daxiang520.top/Article/details/gtjprvohfz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cqqwz.cn/Article/details/gtbdnhbxyo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtumnmogjn.html

[I05] 按正则拆分
来源：http://dali.sweek.top/Article/details/gtrswocllf.html


<!-- 参考信息 -->