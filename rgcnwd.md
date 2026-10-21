代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuanzhike.top/Article/details/gtpekehpam.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtoogrnbct.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtasswcddo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gtmtsxdryr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jianghu66.top/Article/details/gteaqtwdxw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtjxwweyea.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cucudq.cn/Article/details/gtcjivmudf.html

[F12] CSV 读写
来源：http://dali.zycfv.cn/Article/details/gtdmnflzyw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.feifeiyinyue.top/Article/details/gtslemmnbd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxinkj.top/Article/details/gtzrnhzifv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.vqdsnc.cn/Article/details/gtyrbutgjx.html

TS:   // 同上
来源：http://dali.xziqi.cn/Article/details/gtsendvcat.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.0kj1m.cn/Article/details/gtridqnayp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sxryk.cn/Article/details/gtmjztcxcy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gtqeiobdrq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aibaodan.cn/Article/details/gtyrngbasv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtuxcbuzcp.html

G. 面向对象
来源：http://dali.bjfxy.top/Article/details/gtjatuemcy.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gttlanhztf.html

[G01] 定义类
来源：http://dali.tianlin.xyz/Article/details/gtwgblhjpt.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gthipzfkgh.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gtfyuwisdv.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtxkyjhrqe.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gthkxcwbon.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gtkhgriowe.html

Go:   type User struct { Name string }
来源：http://dali.tianlin.xyz/Article/details/gtuucswsvf.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gtdpnkynsc.html

C#:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtugtashnk.html

[G02] 构造函数
来源：http://dali.iojbl.cn/Article/details/gtbinjhdvr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ehwqpu.com/Article/details/gtkyinshyv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.andypj.xyz/Article/details/gtwtdbrkpv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gttjltbzmi.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gtvytmldmy.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtqrifvchj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gtgqqxcbnn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nwbrower.top/Article/details/gtizkwpzxd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtitelidiv.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gtcgxectru.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtvbbcagap.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gtjifykobq.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtfphayrsa.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gtgdipkgsy.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gtzpaxvvhn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.316326.xyz/Article/details/gtpowgfjcu.html

Ruby: @name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtjsfimfnd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gttgdfyrbe.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gtjkitggza.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtutwwrccl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtokfdbdmb.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtaigapeit.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtrghmwljs.html

Java: String greet() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtbnxucnwb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtexeyadsh.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulymwkvv.html

C#:   public string Greet() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gtjliclsoq.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gtxwpnjhkh.html

Py:   class Admin(User): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspeevfat.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtllggyjwx.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtmvspefbe.html

TS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtlvhpzvch.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtsgizfarn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gttwjrnzqm.html

Ruby: class Admin < User; end
来源：http://dali.meibo888.top/Article/details/gtgwnztoeg.html

C#:   class Admin : User {}
来源：http://dali.gzhubu.top/Article/details/gtzxpdmues.html

[G06] 重写方法
来源：http://dali.gotoacloud.top/Article/details/gtqqhbiojo.html

Py:   def greet(self): return "admin"
来源：http://dali.zhengqikj.top/Article/details/gtunpocqlq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtdjnbxdul.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gthioobeqj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtjuxxqujv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtaqeumeoi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.0kj1m.cn/Article/details/gtgaogfavw.html

Ruby: def greet; "admin"; end
来源：http://dali.xuanzx.com/Article/details/gthzjhyrrk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zycfv.cn/Article/details/gtwppnngmq.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gtifzapmcz.html

Py:   super().greet()
来源：http://dali.nanxinkj.top/Article/details/gtcqbwtiir.html

PHP:  parent::greet();
来源：http://dali.cqqwz.cn/Article/details/gtvzmcecil.html

JS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gtyrvotpog.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtbbakxpdw.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtuqgksgig.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigufen.top/Article/details/gtnjepqbvi.html

Ruby: super
来源：http://dali.zhiwuduotai.top/Article/details/gtpdfcdwok.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gtunwxwdwh.html

[G08] 静态方法与属性
来源：http://dali.gzhubu.top/Article/details/gtbiicyreg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gtuhupczzq.html

PHP:  public static function f() {}
来源：http://dali.guowangkeji.top/Article/details/gtcccpkmjq.html

JS:   static f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtafjpbnia.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gtxonrdvgp.html

Java: static void f() {}
来源：http://dali.wangdashe.top/Article/details/gtnuwdxxit.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pengpengdd.cyou/Article/details/gtlvnldyut.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gtfbhqghip.html

C#:   public static void F() {}
来源：http://dali.hammf.cn/Article/details/gtrojjlzkz.html

[G09] 接口 / 抽象类
来源：http://dali.yvedp.cn/Article/details/gtzwysbpxp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhoulong.xyz/Article/details/gtembqcrhb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cucudq.cn/Article/details/gtjyjfuqiu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gtzeaogboy.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gtsxgyqwiq.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258888.top/Article/details/gtdlkbliox.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.9152youxi.cn/Article/details/gtbmtffphw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cucudq.cn/Article/details/gtuqhwhozl.html

C#:   interface IShape { double Area(); }
来源：http://dali.yongpay.top/Article/details/gtsczrabzp.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gtrkitiwzd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gteuyuujeb.html

PHP:  public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtxlfzuwzd.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gtltsjnzmo.html

TS:   public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtjbjicgoy.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gtgmkfzeuy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gtuagwirbr.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtqxplqgqt.html

C#:   public / protected / private / internal
来源：http://dali.ivvv.top/Article/details/gtuuaauhiv.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gtbpqxnycj.html

Py:   @property 与 @x.setter
来源：http://dali.cdnleiting.top/Article/details/gtgntjvawz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtsuwxmkma.html

JS:   get name() { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtrmeexsez.html

TS:   get name(): string { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gtzpteafni.html

Java: public String getName() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtiyvfptkc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtndqdvqpq.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gtsdkkgked.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gtzihqulzf.html

[G12] 对象转字符串
来源：http://dali.jyoumei.cn/Article/details/gthetfkuao.html

Py:   def __str__(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtidyanrca.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gthorlrnix.html

JS:   toString() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtwnfbdasf.html

TS:   toString(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtezkpctqg.html

Java: @Override public String toString() { return name; }
来源：http://dali.iojbl.cn/Article/details/gticazlwxk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gteahrpnvu.html

Ruby: def to_s; @name; end
来源：http://dali.ivvv.top/Article/details/gtglrrurzn.html

C#:   public override string ToString() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtvwxndsvm.html

[G13] 判断对象类型
来源：http://dali.yueranfly.top/Article/details/gthdsrhccf.html

Py:   isinstance(u, User)
来源：http://dali.vqdsnc.cn/Article/details/gtohasljjh.html

PHP:  $u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtbeflmtdr.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtkxnbwcsb.html

TS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtvkrptclr.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gttqbpnbey.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yonumen.top/Article/details/gtxmcadszi.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gtuafgjijn.html

C#:   u is User
来源：http://dali.ehwqpu.com/Article/details/gtpjnvdslq.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gtlcssajee.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ydzc1.top/Article/details/gtsqhyzgwe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gtwsdskttb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.meibo888.top/Article/details/gtjnyizbof.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gtkuemhgmw.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtllpjkihn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gtnslurlsb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangtech.top/Article/details/gteguqwzpu.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigfzy.top/Article/details/gtcmyqjprx.html

[G15] 枚举
来源：http://dali.zhongyouzk.top/Article/details/gtnjatyxvn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pengpengdd.cyou/Article/details/gtuiaxaxqy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.9152youxi.cn/Article/details/gtnbkacire.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gotoacloud.top/Article/details/gtbpxrtzep.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gtoeudrcji.html

Java: enum Color { RED, GREEN }
来源：http://dali.yanxiufei.cn/Article/details/gtxiawjqzo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gtjgpvamyf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cheryme.top/Article/details/gtctdvhcba.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gtuxrqzcsf.html

[G16] 对象转数组 / 字典
来源：http://dali.pycfn.com/Article/details/gtmecvlslx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gthwpaxxdw.html

PHP:  get_object_vars($obj);
来源：http://dali.feifeiyinyue.top/Article/details/gtoiksojsl.html

JS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtqonnebwi.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gtwumbqxtx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbcqcsxi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsmtxdkq.html

Ruby: obj.instance_variables
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxhiaesq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gtebiidhnk.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtnsfocpol.html

H. 异常与错误处理
来源：http://dali.jqgufenzy.top/Article/details/gtweuxilgw.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtiqkhxdgc.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gtecbmqhtj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hammf.cn/Article/details/gtkwhdkbea.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvznaqgfh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdndipit.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtnclhcrbl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gtfhmuogrd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gthsqmekql.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.snrcjt.cn/Article/details/gtmjhqfwnv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cheryme.top/Article/details/gtiypguxdl.html

[H02] finally / ensure 收尾
来源：http://dali.snrcjt.cn/Article/details/gtbrympaju.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gaohongyu789.top/Article/details/gthmpppges.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtnlpocznu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtgekcykws.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtxqksfchv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtdbrinzfp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmonhctt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fzhhl.top/Article/details/gtqxtbvvng.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtyhthqzoz.html

[H03] 主动抛出异常
来源：http://dali.cdnleiting.top/Article/details/gtoniaaraz.html

Py:   raise ValueError("错误信息")
来源：http://dali.andypj.xyz/Article/details/gtkxmqarhp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtlenfdwae.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtetvsahbe.html

TS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtcceortmq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtvbbgrhtg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhengqikj.top/Article/details/gtmnpchiqr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gtextzkmcs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtjscxrcee.html

[H04] 自定义异常类型
来源：http://dali.smart0.xyz/Article/details/gtagdtjodk.html

Py:   class MyError(Exception): pass
来源：http://dali.ppjwa.cn/Article/details/gtqntcmbiu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gttecyuvwa.html

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gtvxnpnvxh.html

TS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gtebwcvylo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtwrbhfygj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gttwwgbpgr.html

Ruby: class MyError < StandardError; end
来源：http://dali.yonumen.top/Article/details/gtvurpunyo.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gtovurxcla.html

[H05] 捕获特定类型
来源：http://dali.cqqwz.cn/Article/details/gtcoqbbply.html

Py:   except ValueError as e:
来源：http://dali.fengsongda.top/Article/details/gtowilikbb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.bjfxy.top/Article/details/gtbzwkgwpp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gtytqrigpr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtpspgftdx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gtwluvvnhd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigufen.top/Article/details/gtxskcydcu.html

Ruby: rescue ArgumentError => e
来源：http://dali.jiagoushi.top/Article/details/gtyiubgzoz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gtwsvpfait.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xziqi.cn/Article/details/gtrmtabtih.html

Py:   value = d.get("k") or default
来源：http://dali.sxryk.cn/Article/details/gturshzkmb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuovscsgz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtgiwmvmcu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtvucxkvhj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dashuyun.cn/Article/details/gtaxjurmzp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ppjwa.cn/Article/details/gtzvvfltwq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gaohongyu789.top/Article/details/gthfhgkfwe.html

C#:   obj?.A?.B ?? default
来源：http://dali.tian-w.cn/Article/details/gtutotmrus.html

[H07] 断言
来源：http://dali.cheryme.top/Article/details/gtzqmxzyjj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gtiiknhxgj.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtkqyexdba.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtynhweueq.html

TS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtpyvdehai.html

Java: assert x > 0 : "必须为正";
来源：http://dali.0kj1m.cn/Article/details/gtjifegiha.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gtarqrbqte.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dianchejie.cn/Article/details/gtjeuaqamx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtdsjrpoop.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgfzy.top/Article/details/gtccnqomwj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gtjludeepv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cheryme.top/Article/details/gtbkimoyfd.html

JS:   e.message;  e.stack
来源：http://dali.yangfankeji.com/Article/details/gtjntpsxov.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtpckcoiqg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shuidangran.top/Article/details/gtpsblyyhu.html

Go:   err.Error()
来源：http://dali.zycfv.cn/Article/details/gtbotdjkru.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnxiangtu.top/Article/details/gtyctxctcq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gtnwdvbfej.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gtdxbwqeld.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhixingplan.top/Article/details/gttfcyakqt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258.top/Article/details/gtmxoctcfj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yvedp.cn/Article/details/gteerxpcfc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daxiang520.top/Article/details/gtwzahwiww.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ybcxt.top/Article/details/gtywrcasul.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fengsongda.top/Article/details/gtsjkborjb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tanke756.top/Article/details/gtsxcfhzcy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.andypj.xyz/Article/details/gtkvdprfcj.html

[H10] 资源自动释放
来源：http://dali.havefunace.top/Article/details/gtffsdjfwm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gtdxkyspdw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhiwuduotai.top/Article/details/gtkwqqzmsx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmscdwxpi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtlwlqtmtl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jiagoushi.top/Article/details/gtfsipzrhj.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gtelwldqua.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhixingplan.top/Article/details/gtocavbund.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gtzpzzvczl.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtashvrncf.html

I. 正则表达式
来源：http://dali.chenjidiqi.icu/Article/details/gthdvqgjlk.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtubtyrrdm.html

[I01] 判断是否匹配
来源：http://dali.dashuyun.cn/Article/details/gttmzcubdn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtvsjwagur.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.birdmap.top/Article/details/gtxvvgfaxv.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtcycvjgyi.html

TS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtpiibkzgi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ppjwa.cn/Article/details/gtrvyooyqw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gtudrgxcvn.html

Ruby: s.match?(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gtwrdkxlok.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.haohaochexian.top/Article/details/gtwrpmraka.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gtiwiwgrpc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gtbimbymon.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhongyouzk.top/Article/details/gtlljnwcyz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gtnxrswgfj.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigufen.top/Article/details/gtscfsblfd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zycfv.cn/Article/details/gtbukchjvq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gtzqygzscp.html

Ruby: s.scan(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtldrxtwaw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtnrvqqwje.html

[I03] 提取捕获分组
来源：http://dali.guowangkeji.top/Article/details/gtzdcncbdh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyegkkiuz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgufenzy.top/Article/details/gtckmcbksu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shuidangran.top/Article/details/gtuvbooyit.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuanzx.com/Article/details/gtcsheiwgn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cashguo.top/Article/details/gtocltztbg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbyogjqp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dashuyun.cn/Article/details/gtzrxpqdti.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shangyingyoupin.top/Article/details/gtqbsuytod.html

[I04] 正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtkgqilopg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jiagoushi.top/Article/details/gtwxjvviya.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgptxilp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gtodwfqidi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gtzsctieyk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gtwqierfhn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fengsongda.top/Article/details/gtbksaljvi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258888.top/Article/details/gtmoibgbiw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gtkvmsqklt.html

[I05] 按正则拆分
来源：http://dali.tanke756.top/Article/details/gtfxflrpff.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.quarkkingdee.top/Article/details/gtxvylhqab.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtopqpticu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gthloxgesi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gthppilbtl.html


<!-- 参考信息 -->