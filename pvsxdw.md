代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gt2kcdraijz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2arveeszu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2ngbbwmkr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.iojbl.cn/Article/details/gt2japrihvh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aibaodan.cn/Article/details/gt2gbnpfpkd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2fydgapbp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tianlin.xyz/Article/details/gt2cdssyfoi.html

[F12] CSV 读写
来源：http://dali.tianlin.xyz/Article/details/gt2sxbbcbms.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gt2haslqxon.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gt2xbozofhg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gt2wzpyhcxp.html

TS:   // 同上
来源：http://dali.aibaodan.cn/Article/details/gt2aieohlxm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ppjwa.cn/Article/details/gt2nqrktboa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gt2vzdgsxfl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuanzx.com/Article/details/gt2mehihinh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hysaishi.cn/Article/details/gt2wvhovlgg.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jfpumiwq.html

G. 面向对象
来源：http://dali.zdqjudy.top/Article/details/gt2hrcbcuah.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2vqtsetyk.html

[G01] 定义类
来源：http://dali.sufxvd.cn/Article/details/gt2gnmkrldk.html

Py:   class User: pass
来源：http://dali.ydzc1.top/Article/details/gt2brgqlzbr.html

PHP:  class User {}
来源：http://dali.xuanzx.com/Article/details/gt2bsfjznyf.html

JS:   class User {}
来源：http://dali.guannengcc.top/Article/details/gt2pgfqfkwg.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gt2cbamtoxn.html

Java: class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2cufpvvhc.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gt2aepojsoc.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gt2epcchfya.html

C#:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2nrlgqtph.html

[G02] 构造函数
来源：http://dali.ehwqpu.com/Article/details/gt2mhxqiftn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gt2azbrhdlj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2hsjktesa.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gt2tpuojodd.html

TS:   constructor(public name: string) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2qqchnavv.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2vcrzptja.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dashuyun.cn/Article/details/gt2lhbjlaal.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.mhx1999.top/Article/details/gt2dnoothng.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hftgaiyv.html

[G03] 实例属性
来源：http://dali.hysaishi.cn/Article/details/gt2bsjkhmdy.html

Py:   self.name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gt2lopevmjx.html

PHP:  public string $name = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2chnpsmpd.html

JS:   this.name = "x";
来源：http://dali.yj202588.top/Article/details/gt2vucotvxb.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2nvldszvk.html

Java: private String name;
来源：http://dali.316326.xyz/Article/details/gt2jjxokhwo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.snrcjt.cn/Article/details/gt2ekseveam.html

Ruby: @name = "x"
来源：http://dali.daria6918.cn/Article/details/gt2gumesvxy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2lgcjhlqr.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gt2xhgwmiic.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gt2ptasfjzh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gt2tffqgaqo.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2rswjslkc.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2igyrydxw.html

Java: String greet() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ermdjrco.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2mrvyopmo.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gt2vcncrvgx.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gt2idlsfhdv.html

[G05] 继承
来源：http://dali.jyoumei.cn/Article/details/gt2gfojrgel.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gt2dwwmtnfe.html

PHP:  class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gt2jaxqtmvk.html

JS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2nyyhtxww.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2cnuhbadu.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2qixdomtt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgufenzy.top/Article/details/gt2kuztgvho.html

Ruby: class Admin < User; end
来源：http://dali.ppjwa.cn/Article/details/gt2ufvacypy.html

C#:   class Admin : User {}
来源：http://dali.jyoumei.cn/Article/details/gt2rfpegthv.html

[G06] 重写方法
来源：http://dali.quarkkingdee.top/Article/details/gt2hhtcbwcj.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gt2tfsiycxw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2kfufqjnd.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2xbvoftxg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2xtdqzcfs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2viprxmak.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gt2bwgaynub.html

Ruby: def greet; "admin"; end
来源：http://dali.ydzc1.top/Article/details/gt2itpsehdc.html

C#:   public override string Greet() => "admin";
来源：http://dali.9152youxi.cn/Article/details/gt2evkfdyml.html

[G07] 调用父类方法
来源：http://dali.jianghu66.top/Article/details/gt2rtdqhwtg.html

Py:   super().greet()
来源：http://dali.yj202588.top/Article/details/gt2prizxfsr.html

PHP:  parent::greet();
来源：http://dali.xziqi.cn/Article/details/gt2zxwikwpa.html

JS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gt2plojzocq.html

TS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2qpnvwwgi.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gt2vmqbjiex.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gogol.net.cn/Article/details/gt2wgfrjftu.html

Ruby: super
来源：http://dali.fzhhl.top/Article/details/gt2iqjjwtva.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gt2xqmevmcc.html

[G08] 静态方法与属性
来源：http://dali.svipenyu.cn/Article/details/gt2tcrzmojp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jianghu66.top/Article/details/gt2homawscd.html

PHP:  public static function f() {}
来源：http://dali.cdnleiting.top/Article/details/gt2ckbrovfz.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2ewqqtipr.html

TS:   static f(): void {}
来源：http://dali.cashguo.top/Article/details/gt2vqwrfsau.html

Java: static void f() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ownftumj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gotoacloud.top/Article/details/gt2xzngcpcc.html

Ruby: def self.f; end
来源：http://dali.hysaishi.cn/Article/details/gt2rjlsvrmk.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gt2mtuivnpi.html

[G09] 接口 / 抽象类
来源：http://dali.pycfn.com/Article/details/gt2wgnyjbbb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gotoacloud.top/Article/details/gt2jergcuoz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnxiangtu.top/Article/details/gt2kuivqrul.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gt2jbkwbnug.html

TS:   interface Shape { area(): number; }
来源：http://dali.smart0.xyz/Article/details/gt2bgclvgrz.html

Java: interface Shape { double area(); }
来源：http://dali.daxiang520.top/Article/details/gt2saktxxvn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xinyue.icu/Article/details/gt2klnisull.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgfzy.top/Article/details/gt2vigifytl.html

C#:   interface IShape { double Area(); }
来源：http://dali.nwbrower.top/Article/details/gt2jlbtlzlj.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gt2yumkdpxi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigfzy.top/Article/details/gt2jowcyejc.html

PHP:  public / protected / private
来源：http://dali.redwolf501.top/Article/details/gt2kuuuutpw.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gt2vfkshwdz.html

TS:   public / protected / private
来源：http://dali.tanke756.top/Article/details/gt2zfswvnjx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhixingplan.top/Article/details/gt2nznqvqll.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohfqkmcf.html

Ruby: public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gt2otmolszx.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gt2smidqvfj.html

[G11] getter / setter
来源：http://dali.0kj1m.cn/Article/details/gt2wovdguhw.html

Py:   @property 与 @x.setter
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ymdwfmsv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kqchtujf.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gt2icrufrjj.html

TS:   get name(): string { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gt2mioigdzs.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2gwlfvwob.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gt2xptvlnui.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gt2bmzbfxdr.html

C#:   public string Name { get; set; }
来源：http://dali.ivvv.top/Article/details/gt2bbdclney.html

[G12] 对象转字符串
来源：http://dali.yongpay.top/Article/details/gt2njjnpviq.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gt2egoqycow.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2swajnubt.html

JS:   toString() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2hdejmfoj.html

TS:   toString(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2nlzdtzdz.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2fifqaafg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gt2pqiyqypa.html

Ruby: def to_s; @name; end
来源：http://dali.hnqzz.top/Article/details/gt2ioothpvs.html

C#:   public override string ToString() => Name;
来源：http://dali.redwolf501.top/Article/details/gt2lrhtxyuq.html

[G13] 判断对象类型
来源：http://dali.jqgfzy.top/Article/details/gt2biwnosoy.html

Py:   isinstance(u, User)
来源：http://dali.ppjwa.cn/Article/details/gt2aomefavc.html

PHP:  $u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2paoxvoic.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gt2aqnqjozh.html

TS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2efhtxceb.html

Java: u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2ehbroiig.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cqqwz.cn/Article/details/gt2rdoowcmp.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gt2tyasxawl.html

C#:   u is User
来源：http://dali.xylfe.cn/Article/details/gt2edryfpuo.html

[G14] 数据类 / record
来源：http://dali.cdnleiting.top/Article/details/gt2hnrqjqji.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uisxfeoh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nwbrower.top/Article/details/gt2jwtyodhh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aibaodan.cn/Article/details/gt2qlmqomsj.html

TS:   type User = { name: string; age: number };
来源：http://dali.ybcxt.top/Article/details/gt2apxrwmxv.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigufen.top/Article/details/gt2yzmaeyes.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigufen.top/Article/details/gt2etqmrnax.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gt2zansqqef.html

C#:   record User(string Name, int Age);
来源：http://dali.birdmap.top/Article/details/gt2bfiejruh.html

[G15] 枚举
来源：http://dali.gotoacloud.top/Article/details/gt2tbpacdaa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xylfe.cn/Article/details/gt2easyuorh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gotoacloud.top/Article/details/gt2oqtkkgap.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sysykeji.top/Article/details/gt2sngdrpfs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gt2vadegsxz.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gt2eksvcwpj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pengpengdd.cyou/Article/details/gt2evempxed.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhixingplan.top/Article/details/gt2vopblowt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gt2hyifqads.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258888.top/Article/details/gt2dwbovrov.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gt2zprzwmyf.html

PHP:  get_object_vars($obj);
来源：http://dali.bjfxy.top/Article/details/gt2fsogwhtb.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2ltrhnzdo.html

TS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gt2xhebahgn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gt2fiivxkzg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gt2frqequca.html

Ruby: obj.instance_variables
来源：http://dali.mhx1999.top/Article/details/gt2joxcamci.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gt2ujykakki.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2vsjjkcct.html

H. 异常与错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khgcleic.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2tzwczsuk.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xehcjhbn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yueranfly.top/Article/details/gt2tzyojfjn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sailurot.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gt2hpptaghc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gt2nyvljyxc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gt2kupgzvpq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hptgnjco.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shzxlz.cn/Article/details/gt2glhzrvrt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yangfankeji.com/Article/details/gt2infnnfsc.html

[H02] finally / ensure 收尾
来源：http://dali.ybcxt.top/Article/details/gt2iyuobwyy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gt2jibxwdpf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2bdwsrphw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2aanahuny.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eulqveeu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2cdwiaeli.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aizwys.cn/Article/details/gt2nqyrjmnm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2kmcsmjou.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2sfzvxxzo.html

[H03] 主动抛出异常
来源：http://dali.svipenyu.cn/Article/details/gt2fjglqysa.html

Py:   raise ValueError("错误信息")
来源：http://dali.quarkkingdee.top/Article/details/gt2shkdinmp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2zotmzgqa.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2csyschfq.html

TS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2tbfnikjx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2rjcelaqa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tian-w.cn/Article/details/gt2wmwlrntp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuanzx.com/Article/details/gt2trwwuxhe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2qocradlt.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gt2zorspdwu.html

Py:   class MyError(Exception): pass
来源：http://dali.zhoulong.xyz/Article/details/gt2wnphiqod.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gt2ovhbbyon.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2akuobqqv.html

TS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gt2pykviguo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gt2pmwzfwyw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ppjwa.cn/Article/details/gt2ylrdwntt.html

Ruby: class MyError < StandardError; end
来源：http://dali.ppjwa.cn/Article/details/gt2vlxzwrcy.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258.top/Article/details/gt2jfwctftb.html

[H05] 捕获特定类型
来源：http://dali.tianlin.xyz/Article/details/gt2jgqngekp.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gt2spfptxkz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sxryk.cn/Article/details/gt2yyqmvvuv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gt2blvervym.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gt2pmoofehv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pycfn.com/Article/details/gt2tflirhxk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnxiangtu.top/Article/details/gt2apschrxc.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jrhvqsuz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2zcjjmals.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ivvv.top/Article/details/gt2uteesswb.html

Py:   value = d.get("k") or default
来源：http://dali.xinyue.icu/Article/details/gt2frxlemxs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmwvanwg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gt2lzawinyh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gt2yrmbyrlo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hammf.cn/Article/details/gt2efewyqai.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gzhubu.top/Article/details/gt2onmoooqp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gt2pagudtuc.html

C#:   obj?.A?.B ?? default
来源：http://dali.fzhhl.top/Article/details/gt2ffmamukd.html

[H07] 断言
来源：http://dali.shangyingyoupin.top/Article/details/gt2gbqhsmof.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yonumen.top/Article/details/gt2xwrndcdz.html

PHP:  assert($x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zbfcsadw.html

JS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gt2ahlegrkw.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2isqwxvki.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gt2rxkbxvyq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yonumen.top/Article/details/gt2dwnffjlb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gt2ouxlcijf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2yolljedo.html

[H08] 获取错误信息与堆栈
来源：http://dali.daxiang520.top/Article/details/gt2zrmflqau.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.iojbl.cn/Article/details/gt2tvebcyhn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gt2wiqvqevb.html

JS:   e.message;  e.stack
来源：http://dali.dashuyun.cn/Article/details/gt2hdptgdut.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cdnleiting.top/Article/details/gt2jhtaftan.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigufen.top/Article/details/gt2hzbeyira.html

Go:   err.Error()
来源：http://dali.tianlin.xyz/Article/details/gt2uegpvlmb.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gt2ydmqanrx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tanke756.top/Article/details/gt2ghnrwcke.html

[H09] 带错误码的异常
来源：http://dali.redwolf501.top/Article/details/gt2qcxklemd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuetiantiany.cn/Article/details/gt2lpazilfc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gt2omzsqitx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ppjwa.cn/Article/details/gt2lkncvgtw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.0kj1m.cn/Article/details/gt2ebeasmwg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gt2cybqiabn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yanxiufei.cn/Article/details/gt2bxpstffj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnxiangtu.top/Article/details/gt2ghaoikmg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxuanxn.top/Article/details/gt2vunjyidb.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gt2tnktgqnr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.bjfxy.top/Article/details/gt2nlhavzff.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.snrcjt.cn/Article/details/gt2rclsrmbs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gt2rtipmhqq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gt2avejamsm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbvupdhw.html

Go:   defer f.Close()
来源：http://dali.pycfn.com/Article/details/gt2uadxnqpv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ppjwa.cn/Article/details/gt2ctjblkbt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2sglastoa.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2nhwamqah.html

I. 正则表达式
来源：http://dali.nanxinkj.top/Article/details/gt2cmnluxgz.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ssrapwmo.html

[I01] 判断是否匹配
来源：http://dali.meibo888.top/Article/details/gt2nlslmadu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gt2jilnmnie.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.316326.xyz/Article/details/gt2pprmmdug.html

JS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gt2ihhbzttf.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gt2gzurdxcw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shuidangran.top/Article/details/gt2ecskwsji.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ivvv.top/Article/details/gt2sswdcgyy.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2ordwgtza.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gt2swyrgoep.html

[I02] 提取所有匹配
来源：http://dali.guannengcc.top/Article/details/gt2daxvwyhp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ragwoedj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guannengcc.top/Article/details/gt2quszvmbi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zfpayqjp.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pwecfhsi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2zxtrtifb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gt2ncpysafy.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gt2yklrjreb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2dthvwjoj.html

[I03] 提取捕获分组
来源：http://dali.sweek.top/Article/details/gt2ozkabxye.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.9152youxi.cn/Article/details/gt2xwhiagxd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pycfn.com/Article/details/gt2gdpqaevy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ivvv.top/Article/details/gt2nnilwisd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iqlnwers.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gt2ahfjomww.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pengpengdd.cyou/Article/details/gt2xjkeesqv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258.top/Article/details/gt2snhcyodg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cashguo.top/Article/details/gt2rjijupqg.html

[I04] 正则替换
来源：http://dali.yonumen.top/Article/details/gt2shpbzpnj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gt2xkfnkdzl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gt2zdzivjvs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2omwcdvyt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gt2rhpggyhi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gt2ewfxxnoo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smfzwshw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lcdvcrco.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ivvv.top/Article/details/gt2ohasmjqj.html

[I05] 按正则拆分
来源：http://dali.dashuyun.cn/Article/details/gt2nouwozxd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuxming.cn/Article/details/gt2mndrpfuh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cheryme.top/Article/details/gt2druhpnii.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gt2egxuqvtq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gt2hsyryanw.html


<!-- 参考信息 -->