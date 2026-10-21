代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigfzy.top/Article/details/gtfwuuqcfj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hfpthk.cn/Article/details/gtlolsrszl.html

JS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gtfbdkrvid.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtpwckhqjy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtorrabjph.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtgvlxggtb.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gtlrzgvchr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtcqlatqif.html

[F09] 获取文件大小
来源：http://dali.chenlongwang.top/Article/details/gtafnckrvo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtzmmzihxr.html

PHP:  filesize("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtjuwquyrd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtcgzqcnqz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gtflvmxrse.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtphpiepib.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daxiang520.top/Article/details/gtgufzohfe.html

Ruby: File.size("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbqgmefp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgufenzy.top/Article/details/gtkjfoluhh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.smart0.xyz/Article/details/gttpimjcth.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtbouqgmuc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xylfe.cn/Article/details/gtxfbtfrcu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtjsnmwzru.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtmdprsjro.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhongyouzk.top/Article/details/gtqodhpjxo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtndfhoelr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtcaeoypeg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gttdqryqzf.html

[F11] 复制与移动文件
来源：http://dali.sweek.top/Article/details/gtcapmboye.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtjwdzsykf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gtbbpcmqgs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtbxvdebqo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtjheahixz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fengsongda.top/Article/details/gtfwbyxggg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.svipenyu.cn/Article/details/gtpnarlokp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtuoxzzffe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.redwolf501.top/Article/details/gtcixkxglq.html

[F12] CSV 读写
来源：http://dali.aibaodan.cn/Article/details/gtgavpxqmb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.snrcjt.cn/Article/details/gtkipdmlyw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gtfidiovxr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zdqjudy.top/Article/details/gtgwbbwebt.html

TS:   // 同上
来源：http://dali.havefunace.top/Article/details/gtrbwzbacf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gtxxlbuzmy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuanzhike.top/Article/details/gticgooosh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.mhx1999.top/Article/details/gtymhbygnw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xylfe.cn/Article/details/gtpiztlyss.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtahioucch.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gtvzfnzscz.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjhuoztxt.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gtjwglfddj.html

Py:   class User: pass
来源：http://dali.yuanzhike.top/Article/details/gtnwzhfaiw.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtbcbcwhsb.html

JS:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtbyqpuwea.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gtylwvjnql.html

Java: class User {}
来源：http://dali.ybcxt.top/Article/details/gtvgfvmzuy.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gtgnecijjk.html

Ruby: class User; end
来源：http://dali.aizwys.cn/Article/details/gtbyevbwlw.html

C#:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gtqlsupvvt.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gtcumbaiil.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jianghu66.top/Article/details/gtichkwkuu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gtycadlkyo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gtjbatkaqs.html

TS:   constructor(public name: string) {}
来源：http://dali.svipenyu.cn/Article/details/gtlpxluowe.html

Java: User(String name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gtvljaavxx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangtech.top/Article/details/gtimvzgjxm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gtajscnhdb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gtzjtaofcz.html

[G03] 实例属性
来源：http://dali.yuanzhike.top/Article/details/gttvmlodjl.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtdjtubcrh.html

PHP:  public string $name = "x";
来源：http://dali.guannengcc.top/Article/details/gtgwhusuqj.html

JS:   this.name = "x";
来源：http://dali.ivvv.top/Article/details/gtelgodwbj.html

TS:   name: string = "x";
来源：http://dali.snrcjt.cn/Article/details/gtwxdvlgyg.html

Java: private String name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwereunav.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pycfn.com/Article/details/gtmwtgmdsj.html

Ruby: @name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gtgdtdggks.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fengsongda.top/Article/details/gtjakgwpcu.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gtsyahqjmm.html

Py:   def greet(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gtilztnlxz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtupdlykjm.html

JS:   greet() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtegtzbmss.html

TS:   greet(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtybyjqfkp.html

Java: String greet() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtpsyluqjg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmyigttq.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gtyqmmmfwk.html

C#:   public string Greet() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtxcmngglh.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gtbgyvordr.html

Py:   class Admin(User): pass
来源：http://dali.tanke756.top/Article/details/gtvkioqoav.html

PHP:  class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtclwxacqi.html

JS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtbusipmow.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtcmzjhpni.html

Java: class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtzfpxabmj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gtcnksmqqc.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtakgqmipg.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtpozxdlwx.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gtyuiyegfx.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gtugayobvb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtpoeinwja.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkoteppgb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtwxchljld.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtxsihkizz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gtdxjwxdkh.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gtyftczxdi.html

C#:   public override string Greet() => "admin";
来源：http://dali.0kj1m.cn/Article/details/gteswdhibo.html

[G07] 调用父类方法
来源：http://dali.pycfn.com/Article/details/gtlflooiyc.html

Py:   super().greet()
来源：http://dali.birdmap.top/Article/details/gtvtvzemed.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gtdbocsrvb.html

JS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtckspbfjx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtomnoiadn.html

Java: super.greet();
来源：http://dali.redwolf501.top/Article/details/gtborpkled.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.birdmap.top/Article/details/gtejtkirrh.html

Ruby: super
来源：http://dali.jianghu66.top/Article/details/gtjnufqjvx.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gtzoiiuypi.html

[G08] 静态方法与属性
来源：http://dali.jinqigfzy.top/Article/details/gtwvlfleav.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.c1oappe.top/Article/details/gtzigmduqv.html

PHP:  public static function f() {}
来源：http://dali.yueranfly.top/Article/details/gtophdxcny.html

JS:   static f() {}
来源：http://dali.redwolf501.top/Article/details/gtowtnfwfz.html

TS:   static f(): void {}
来源：http://dali.nwbrower.top/Article/details/gtjzospzzj.html

Java: static void f() {}
来源：http://dali.zhengqikj.top/Article/details/gtqwygouir.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zdqjudy.top/Article/details/gtzhbzirsy.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gtxdlvemew.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gtfbuzljey.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gtwumsqiei.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gtjrhlybnc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.haohaochexian.top/Article/details/gtwqrhciab.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jyoumei.cn/Article/details/gtxddfqpqr.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxuanxn.top/Article/details/gtcyamqbtp.html

Java: interface Shape { double area(); }
来源：http://dali.hfpthk.cn/Article/details/gtsvgvwyhp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.iojbl.cn/Article/details/gtvbchwfwo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tian-w.cn/Article/details/gtcrpcbilm.html

C#:   interface IShape { double Area(); }
来源：http://dali.tian-w.cn/Article/details/gtswdzhpsg.html

[G10] 访问控制
来源：http://dali.xylfe.cn/Article/details/gtndrkgpse.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gtypuzrgpz.html

PHP:  public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtaorlvlno.html

JS:   #private 字段；其余公开
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcpttxpn.html

TS:   public / protected / private
来源：http://dali.mhx1999.top/Article/details/gttwuryuqp.html

Java: public / protected / private / 默认包级
来源：http://dali.tianlin.xyz/Article/details/gtwvwtnhru.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cqqwz.cn/Article/details/gtoegexiaw.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gttahjxnnh.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gtopaflpzt.html

[G11] getter / setter
来源：http://dali.havefunace.top/Article/details/gtmqaqqfni.html

Py:   @property 与 @x.setter
来源：http://dali.pycfn.com/Article/details/gtnlsesafw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtsymmdrgx.html

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtuyexfxqm.html

TS:   get name(): string { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtgdbnbuog.html

Java: public String getName() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwfozgdrf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtmuekvqwu.html

Ruby: attr_accessor :name
来源：http://dali.daxiang520.top/Article/details/gtaxkerrhy.html

C#:   public string Name { get; set; }
来源：http://dali.dashuyun.cn/Article/details/gtnzhlptex.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gthdkvtjai.html

Py:   def __str__(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtloucuqlj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtfvfoykyp.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtgbptgbcj.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipdjbnpl.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrggsamup.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtddmbluvz.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtafvjnjjb.html

C#:   public override string ToString() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtcmzuojjk.html

[G13] 判断对象类型
来源：http://dali.sufxvd.cn/Article/details/gtfcqbcbmo.html

Py:   isinstance(u, User)
来源：http://dali.hywenlv.cn/Article/details/gtdypumsxe.html

PHP:  $u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtfharzuru.html

JS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtvadnqujb.html

TS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gthclygzwt.html

Java: u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtrelcaxse.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gtwceaqswb.html

Ruby: u.is_a?(User)
来源：http://dali.chenzaomai.com/Article/details/gtinlvgkrr.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gtavizomxd.html

[G14] 数据类 / record
来源：http://dali.jqgufenzy.top/Article/details/gtavojblvm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zdqjudy.top/Article/details/gtfcfyayjz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nwbrower.top/Article/details/gtzwvocuro.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gtgtfihtzf.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouxoukgp.html

Java: record User(String name, int age) {}
来源：http://dali.smart0.xyz/Article/details/gtyxlbvxau.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxuanxn.top/Article/details/gtvrthpwmr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yongpay.top/Article/details/gtifjxelqt.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gtqsyixzpq.html

[G15] 枚举
来源：http://dali.daxiang520.top/Article/details/gtqhoiyfdk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigufen.top/Article/details/gtfitztzyo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xziqi.cn/Article/details/gtdtxbvgim.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yvedp.cn/Article/details/gtplxhboih.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtvsregaxf.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gtjbjjatpb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gtcezfxcvv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.meibo888.top/Article/details/gtuzwsemgd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtnxynscsk.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjdymmms.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.9152youxi.cn/Article/details/gtwizxkile.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gtvqmtgmao.html

JS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtftrpomhi.html

TS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gtoithukam.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dashuyun.cn/Article/details/gtgzkjajif.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yueranfly.top/Article/details/gtgoeoxriw.html

Ruby: obj.instance_variables
来源：http://dali.tian-w.cn/Article/details/gtljgfnhyo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gtlwuxidya.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtrqhywzrt.html

H. 异常与错误处理
来源：http://dali.yangfankeji.com/Article/details/gtaywmzbbp.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtxiocjmlb.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gttdepllvh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gthcavncps.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jyoumei.cn/Article/details/gtecmixnzq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtvbogceaf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtyoetmxar.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhixingplan.top/Article/details/gtnznkzpmm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cdnleiting.top/Article/details/gtzakjeaea.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cashguo.top/Article/details/gtrdqmzpjp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenjidiqi.icu/Article/details/gtppdfynxb.html

[H02] finally / ensure 收尾
来源：http://dali.sysykeji.top/Article/details/gtwzkawzem.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.havefunace.top/Article/details/gthctdanoz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtliouhswp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gttismcfej.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtxvjqclxh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtttnuuodg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ybcxt.top/Article/details/gtlfemafrn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.havefunace.top/Article/details/gtnmhsyzjb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtewfxaebi.html

[H03] 主动抛出异常
来源：http://dali.iojbl.cn/Article/details/gtwwlzfgui.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigfzy.top/Article/details/gtmnopndax.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtkbocnygk.html

JS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtdtjjvkbk.html

TS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtaoxfmvpo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtjaznxhif.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhixingplan.top/Article/details/gtlbohwvps.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykqqbzfb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtsovoobup.html

[H04] 自定义异常类型
来源：http://dali.sufxvd.cn/Article/details/gtcsudtrcz.html

Py:   class MyError(Exception): pass
来源：http://dali.andypj.xyz/Article/details/gtdiioxtaj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gthlmrxbaq.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxksllgpq.html

TS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtgrgqmfus.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gtikxjqqso.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gtjnpiuhup.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangshuangyany.cn/Article/details/gtivwrvwmz.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gtlglsrapy.html

[H05] 捕获特定类型
来源：http://dali.gotoacloud.top/Article/details/gtzbyuzlaf.html

Py:   except ValueError as e:
来源：http://dali.aibaodan.cn/Article/details/gtztmhsouc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuanzx.com/Article/details/gtvdiwnfxk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gthhupdhlz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtexaufzoi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xylfe.cn/Article/details/gtqwrrudqb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gtbcqnlqwh.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxinkj.top/Article/details/gtshjupdnt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhengqikj.top/Article/details/gtfnodxmcx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.smart0.xyz/Article/details/gtyhfntazo.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gtrvirpkgz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gtudwkgini.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtsubkeann.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtzspsgvey.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gtcnvredcp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ydzc1.top/Article/details/gtfdrvqmqy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.birdmap.top/Article/details/gtynlkkglu.html

C#:   obj?.A?.B ?? default
来源：http://dali.daria6918.cn/Article/details/gtcamnbuek.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gtxqinhwvg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gthfyykafs.html

PHP:  assert($x > 0);
来源：http://dali.shuidangran.top/Article/details/gtofbossme.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtbgodgvpa.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gteluikpes.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gtfecknbdk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tian-w.cn/Article/details/gtcudmlkbp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuanzx.com/Article/details/gtqhvevsdz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvfkpdko.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenlongwang.top/Article/details/gtitwtcsxv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtioljgufj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yueranfly.top/Article/details/gtxgdhkojn.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gtoahzcoir.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shuidangran.top/Article/details/gtybmddson.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangshuangyany.cn/Article/details/gtsivikimr.html

Go:   err.Error()
来源：http://dali.ybcxt.top/Article/details/gtzjscarnx.html

Ruby: e.message;  e.backtrace
来源：http://dali.hammf.cn/Article/details/gtkststuoa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guannengcc.top/Article/details/gtoptehkfy.html

[H09] 带错误码的异常
来源：http://dali.fzhhl.top/Article/details/gtkgvsmrbn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhengqikj.top/Article/details/gtqvrjfilz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hnxiangtu.top/Article/details/gtpgopqdzk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuetiantiany.cn/Article/details/gtcivakjwm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.snrcjt.cn/Article/details/gtyodsgiuq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gtbonqiucd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gtawduxjxy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gtxpbevjdf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.0kj1m.cn/Article/details/gtuivsoxee.html

[H10] 资源自动释放
来源：http://dali.dianchejie.cn/Article/details/gtddawyxei.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gturdoxeth.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.iojbl.cn/Article/details/gthyekpmls.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gtifwuqzjn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtedxhmrvn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yueranfly.top/Article/details/gtmmvnaqkt.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxgkvwxs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gogol.net.cn/Article/details/gtaqzztleu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtpuwjqars.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtmruzjtrq.html

I. 正则表达式
来源：http://dali.daxiang520.top/Article/details/gtgnwdjseg.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtqdixwjeu.html

[I01] 判断是否匹配
来源：http://dali.hywenlv.cn/Article/details/gtrtvebqfb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gttryhelau.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtheomeovo.html

JS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gtmrfjypwn.html

TS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gtsrzkwsmd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fengsongda.top/Article/details/gtkqhlyyff.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jianghu66.top/Article/details/gtmvbnjcdu.html

Ruby: s.match?(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gtejmpsoez.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.316326.xyz/Article/details/gtvfcyamou.html

[I02] 提取所有匹配
来源：http://dali.yangfankeji.com/Article/details/gtcgvxwzne.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtkemtdjpn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gtmcjrsskw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hysaishi.cn/Article/details/gtemehjxnq.html


<!-- 参考信息 -->