代发 wailian999

[F09] 获取文件大小
来源：http://dali.jiagoushi.top/Article/details/gtlejrflof.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtszlotzkq.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gturtzrasb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gtqkphtjiz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gtdfkcchgd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gttxyskmmb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.redwolf501.top/Article/details/gtzexhdqrb.html

Ruby: File.size("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtigscsdss.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhongyouzk.top/Article/details/gtzycjckxe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shangyingyoupin.top/Article/details/gtalrwlhak.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtnzeruffu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnqzz.top/Article/details/gthawcbdas.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtooftxqzu.html

TS:   path.extname("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtkucprpzr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dashuyun.cn/Article/details/gtbncglwyx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtfbfzspnh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtsreglxly.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gttaljkoln.html

[F11] 复制与移动文件
来源：http://dali.zhixingplan.top/Article/details/gtwqubfkwc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtotqvtwdj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtoddisrwk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgnbqqgo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtolbjkrry.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrhnqrlq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gtssyeoika.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecqcblyd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.birdmap.top/Article/details/gtpeqkanfp.html

[F12] CSV 读写
来源：http://dali.ybcxt.top/Article/details/gtarizgwiv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pengpengdd.cyou/Article/details/gtgborkube.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ivvv.top/Article/details/gtnpevandx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhiwuduotai.top/Article/details/gtrquibkry.html

TS:   // 同上
来源：http://dali.tian-w.cn/Article/details/gtxslbvens.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.redwolf501.top/Article/details/gtwyoylrbz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.quarkkingdee.top/Article/details/gtsgtkfpci.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxinkj.top/Article/details/gtnbeyxyak.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guannengcc.top/Article/details/gtllbpgdli.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtcsankywl.html

G. 面向对象
来源：http://dali.fzhhl.top/Article/details/gtfwxatmpp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtvwjemevt.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gtkjayivun.html

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gtjsmhfctn.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gtsxildjne.html

JS:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtzrnajsdh.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gtwgapkbbg.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gtddensdcv.html

Go:   type User struct { Name string }
来源：http://dali.sxryk.cn/Article/details/gtlufhhfhi.html

Ruby: class User; end
来源：http://dali.guowangkeji.top/Article/details/gtrdlkpkqi.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpdwbveq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtldpphebt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yangfankeji.com/Article/details/gtzrgzbgxg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtwmfgesuu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtmncertxi.html

TS:   constructor(public name: string) {}
来源：http://dali.guowangkeji.top/Article/details/gtxothkwkq.html

Java: User(String name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtfkvcedmq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yonumen.top/Article/details/gttkyshjiu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gtateujhpn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtqlsehlbu.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gtstzjbqci.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gtkwjcetdq.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gtdkuecpln.html

JS:   this.name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtcbiipjjk.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gtbjlhqjmn.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gtdxrikfco.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gtntkpwgok.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtjudbdach.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtgnoufgdu.html

[G04] 定义方法
来源：http://dali.pengpengdd.cyou/Article/details/gtdcfwfadt.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtcfwhadge.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gttxouqccs.html

JS:   greet() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gteccfiwtz.html

TS:   greet(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtddmmeedj.html

Java: String greet() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtmjtvqbjk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtruzboitz.html

Ruby: def greet; @name; end
来源：http://dali.fzhhl.top/Article/details/gtyrwiwiec.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gtrmxyoteh.html

[G05] 继承
来源：http://dali.ivvv.top/Article/details/gtysgdkkxp.html

Py:   class Admin(User): pass
来源：http://dali.gogol.net.cn/Article/details/gtbxgkagfq.html

PHP:  class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtatxypbph.html

JS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjjuydvpq.html

TS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtaurnpotl.html

Java: class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtfjphflsz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cashguo.top/Article/details/gtgzwpbhgg.html

Ruby: class Admin < User; end
来源：http://dali.yj202588.top/Article/details/gtjikvdqfd.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gtukknlrpf.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gtoyvqnblm.html

Py:   def greet(self): return "admin"
来源：http://dali.gzhubu.top/Article/details/gtbiarwmjw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtnztyijkw.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtluxjgwil.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtqgwvfzra.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtwwuhhnkh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jianghu66.top/Article/details/gtwjffbtko.html

Ruby: def greet; "admin"; end
来源：http://dali.pycfn.com/Article/details/gtbpifzqns.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gtsfylnsmf.html

[G07] 调用父类方法
来源：http://dali.tianlin.xyz/Article/details/gtquqhbrpb.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gtecdkwuch.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gtgivatubp.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtinvkumls.html

TS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtzfbezlqn.html

Java: super.greet();
来源：http://dali.ybcxt.top/Article/details/gtgmfiyrgu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258888.top/Article/details/gtlqqoyfwo.html

Ruby: super
来源：http://dali.hywenlv.cn/Article/details/gtwxhaegxo.html

C#:   base.Greet();
来源：http://dali.yuxming.cn/Article/details/gtserzhnhx.html

[G08] 静态方法与属性
来源：http://dali.xuetiantiany.cn/Article/details/gtseupxlgm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dashuyun.cn/Article/details/gtlwsysbsv.html

PHP:  public static function f() {}
来源：http://dali.yj20258888.top/Article/details/gtybaocsab.html

JS:   static f() {}
来源：http://dali.yangfankeji.com/Article/details/gtewzopqii.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gttcvelujn.html

Java: static void f() {}
来源：http://dali.andypj.xyz/Article/details/gtubslpotj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gtdlljbzqx.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gtuxmluwee.html

C#:   public static void F() {}
来源：http://dali.dianchejie.cn/Article/details/gtiymnlxxf.html

[G09] 接口 / 抽象类
来源：http://dali.gotoacloud.top/Article/details/gtgpowcqdf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnxiangtu.top/Article/details/gterzvqxll.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttjratqkt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuxming.cn/Article/details/gtledeydaf.html

TS:   interface Shape { area(): number; }
来源：http://dali.gaohongyu789.top/Article/details/gtwypardbn.html

Java: interface Shape { double area(); }
来源：http://dali.cashguo.top/Article/details/gtzwpsloft.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj202588.top/Article/details/gtiqxfuwxm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhongyouzk.top/Article/details/gttnhzkaax.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gtalhxrots.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gtvfgiqliw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gotoacloud.top/Article/details/gtbuiqudtq.html

PHP:  public / protected / private
来源：http://dali.cheryme.top/Article/details/gtjrbvrvsw.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gtasznkiph.html

TS:   public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtzwwhlhfq.html

Java: public / protected / private / 默认包级
来源：http://dali.hnqzz.top/Article/details/gteqblmssu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuanzx.com/Article/details/gtrdehqevc.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtvptrwxfi.html

C#:   public / protected / private / internal
来源：http://dali.haohaochexian.top/Article/details/gtsmomkmhg.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gtbiovufkq.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gtytiucjer.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtimivldfq.html

JS:   get name() { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtfoxbgusv.html

TS:   get name(): string { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gtcknfmsyq.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtbnohiigj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtwxncqgkj.html

Ruby: attr_accessor :name
来源：http://dali.jinqigufen.top/Article/details/gtkdpzpeqh.html

C#:   public string Name { get; set; }
来源：http://dali.yj202588.top/Article/details/gtlutzuysk.html

[G12] 对象转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtexkkywyk.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtqarcvqbz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtzsssharp.html

JS:   toString() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtchfngayr.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gttksbuekt.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtcrytmqfp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtujzqddmk.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gtzjwcgrog.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gtaiqfiupe.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gtvdimiqwl.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbzxvxdl.html

PHP:  $u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtrdsrsces.html

JS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtyyqqorcl.html

TS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtmgjhpytv.html

Java: u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gttmreibvj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gtiiwcdywa.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gtkkrzbjox.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gtviqaudjs.html

[G14] 数据类 / record
来源：http://dali.andypj.xyz/Article/details/gtthtutcpt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gtxilrruvl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gtajowtxam.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shangyingyoupin.top/Article/details/gtlketsffv.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gtlgfgqtpe.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gtgbvfesqn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hywenlv.cn/Article/details/gtvopnckxt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gtfudbfedh.html

C#:   record User(string Name, int Age);
来源：http://dali.fzhhl.top/Article/details/gtaeptexqi.html

[G15] 枚举
来源：http://dali.nanxuanxn.top/Article/details/gtosfuaxnl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zycfv.cn/Article/details/gtebhyrpzv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gtkhkyxgva.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtwvjoyhcf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtfaionbka.html

Java: enum Color { RED, GREEN }
来源：http://dali.gotoacloud.top/Article/details/gtbofgqswg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnxiangtu.top/Article/details/gtsqfvpeqh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guannengcc.top/Article/details/gtfveyqwod.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gtjkkapqfg.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gthvsyvsek.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gtfoaxuxlv.html

PHP:  get_object_vars($obj);
来源：http://dali.iojbl.cn/Article/details/gtfvpnnqei.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtsgeatcbs.html

TS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gtkminkqej.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yongpay.top/Article/details/gtzzgjhqqy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xinyue.icu/Article/details/gttefgewov.html

Ruby: obj.instance_variables
来源：http://dali.andypj.xyz/Article/details/gtthyilrvf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gtyitzinpy.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtghavmqzz.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gtnnstwhpj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtxpysxeuv.html

[H01] try / catch 基础
来源：http://dali.nanxuanxn.top/Article/details/gtrrxniuia.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidjxszis.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yongpay.top/Article/details/gtcpivclfb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtjtxqwane.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbysxwngf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gtvorqzvpo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yueranfly.top/Article/details/gthdvbmkka.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gogol.net.cn/Article/details/gtghwnlxqq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gtqezvqnwi.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gtrqjbchre.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gtxphobbgv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtjkazypvr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtsvfzgilq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtymsworyp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtdomvhdpu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fengsongda.top/Article/details/gtizacsvry.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dianchejie.cn/Article/details/gtctjpnofs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtxcrpcbdj.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gtcqlxlvye.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangshuangyany.cn/Article/details/gtdnehmhfn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtvzbqsilg.html

JS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnuoekfb.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtowqesdfy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtjlbfvrpc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guannengcc.top/Article/details/gtpiykjrmt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.svipenyu.cn/Article/details/gtncsxqwfr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtewqrwmdc.html

[H04] 自定义异常类型
来源：http://dali.meibo888.top/Article/details/gtamzmwxho.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gtuklsynqv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gtsihkzfbm.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gtbtfugomc.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtqgjyewpw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtiuoracfx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gtddpwrjdt.html

Ruby: class MyError < StandardError; end
来源：http://dali.jlsjyb.cn/Article/details/gtohwaxdor.html

C#:   class MyException : Exception {}
来源：http://dali.hysaishi.cn/Article/details/gttokcsuvr.html

[H05] 捕获特定类型
来源：http://dali.dashuyun.cn/Article/details/gtsfjcptnl.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gtkqtpdtpt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.meibo888.top/Article/details/gtncsuiago.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtyhqksnto.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gtobyfypkb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.c1oappe.top/Article/details/gtoqjziims.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gtvdvzcsip.html

Ruby: rescue ArgumentError => e
来源：http://dali.cucudq.cn/Article/details/gtfllocwgl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ybcxt.top/Article/details/gtcnjvjgoc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yueranfly.top/Article/details/gttqoklugg.html

Py:   value = d.get("k") or default
来源：http://dali.chenlongwang.top/Article/details/gtgbgszquq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gtztasnwre.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtjtigyalz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtfmpscadz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gtbpfrhbmf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jiagoushi.top/Article/details/gtlwlchgsw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.bjfxy.top/Article/details/gtzdtkbbpp.html

C#:   obj?.A?.B ?? default
来源：http://dali.nwbrower.top/Article/details/gtvyopyvfd.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gtmdbagfnr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yongpay.top/Article/details/gtlpokyjjs.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtmrhtmxqu.html

JS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtvxldcttj.html

TS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtxyrwqqie.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhixingplan.top/Article/details/gtgfrniuhq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gtiowtfdfn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aibaodan.cn/Article/details/gtcwjlutvt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtmnwkvsqk.html

[H08] 获取错误信息与堆栈
来源：http://dali.kuanghao11.cn/Article/details/gtdbkhvhah.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pengpengdd.cyou/Article/details/gtxssfcvns.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhongyouzk.top/Article/details/gtggimjhga.html

JS:   e.message;  e.stack
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvxorrmz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangdashe.top/Article/details/gtqlvscist.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tianlin.xyz/Article/details/gtfkfwdqiv.html

Go:   err.Error()
来源：http://dali.cucudq.cn/Article/details/gtnqfzmvkl.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gtokgrhsfi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.bjfxy.top/Article/details/gtlyibanza.html

[H09] 带错误码的异常
来源：http://dali.xziqi.cn/Article/details/gtzbleikvj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sysykeji.top/Article/details/gtdvpgphqf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gtdybrurvh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tianlin.xyz/Article/details/gtbezziuou.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnaqnhluf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwutfbaxt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gtanwyfvec.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gtxrsucvhd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aizwys.cn/Article/details/gtdkcowcks.html

[H10] 资源自动释放
来源：http://dali.c1oappe.top/Article/details/gtnwhljhaa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shzxlz.cn/Article/details/gtgamrdldl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwopbsywp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtodjlmxrk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gthmmgtnsh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuetiantiany.cn/Article/details/gtjoihnlow.html

Go:   defer f.Close()
来源：http://dali.gzhubu.top/Article/details/gtmcicainw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gogol.net.cn/Article/details/gtzaecqssi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtmfoinxqr.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtpryxialo.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gtfcijewcl.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gticgpbtaw.html

[I01] 判断是否匹配
来源：http://dali.gzhubu.top/Article/details/gtdpzrzbvp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gttkojibye.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gtemjxnvyd.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtqanuamrk.html

TS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtovqpdjsa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258888.top/Article/details/gtbibqdtlz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.bjfxy.top/Article/details/gtrogzumkp.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gtfdhaeyze.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xylfe.cn/Article/details/gtopmcgtrh.html

[I02] 提取所有匹配
来源：http://dali.yonumen.top/Article/details/gturfhwhql.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgleldfr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuanzhike.top/Article/details/gtvkabbhsf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gtzykscfak.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gtnnxcpeco.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daxiang520.top/Article/details/gtfifjfndz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gttkxfqona.html

Ruby: s.scan(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gtxeasxhlh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtnsmdqvip.html

[I03] 提取捕获分组
来源：http://dali.guowangkeji.top/Article/details/gtlksjykdu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gtbuushymg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.havefunace.top/Article/details/gtscfljtem.html


<!-- 参考信息 -->