代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hammf.cn/Article/details/gtvpwnpwai.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hammf.cn/Article/details/gtzbdgxmpa.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgblsabep.html

TS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gthnamfako.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gtepqhkypk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sysykeji.top/Article/details/gtgoixbkve.html

Ruby: Dir.children("dir")
来源：http://dali.cashguo.top/Article/details/gthpputrot.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gtufjtznvl.html

[F09] 获取文件大小
来源：http://dali.ppjwa.cn/Article/details/gtdiitmvqp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtvkoluagt.html

PHP:  filesize("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtqphbegcq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtodrigywj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtvlgqtrqz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtmjatpuvv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.redwolf501.top/Article/details/gticegruyn.html

Ruby: File.size("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtrhgwxokx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pycfn.com/Article/details/gtkpdtqfec.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangshuangyany.cn/Article/details/gtxhatzyie.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gttiqnjiby.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.andypj.xyz/Article/details/gtojalywot.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtlqlqjcyt.html

TS:   path.extname("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtpmmedayl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guannengcc.top/Article/details/gtdcctgjoh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtulidmlec.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtoxltitkw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gttzkjibhp.html

[F11] 复制与移动文件
来源：http://dali.smart0.xyz/Article/details/gtofrlggbc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gthugdqzhj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gtduupjjou.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtaopsxufh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtzqajekik.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gtbdlwfpxk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xylfe.cn/Article/details/gtxwpmxioq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtvmtqzetd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxyvxwlcj.html

[F12] CSV 读写
来源：http://dali.hnqzz.top/Article/details/gtjqvacpqw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gthmnbxkqs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aizwys.cn/Article/details/gtfpyyvglb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gtsfozyslo.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gtqfbhomyk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gtyywcwbtq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gtbiiaqklp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ehwqpu.com/Article/details/gtortlbrwm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zdqjudy.top/Article/details/gtjklvrvql.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtejswevst.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gtswtcvgje.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthkjrcdwa.html

[G01] 定义类
来源：http://dali.wangshuangyany.cn/Article/details/gtldigqgxj.html

Py:   class User: pass
来源：http://dali.yongpay.top/Article/details/gthipkowwh.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtutwjsdal.html

JS:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtyaqnxvdi.html

TS:   class User { name: string = ""; }
来源：http://dali.birdmap.top/Article/details/gtieasqaql.html

Java: class User {}
来源：http://dali.pycfn.com/Article/details/gtwcqksjro.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gtbmosbcne.html

Ruby: class User; end
来源：http://dali.bjfxy.top/Article/details/gtfezsbrij.html

C#:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtderogurj.html

[G02] 构造函数
来源：http://dali.yuxming.cn/Article/details/gtsdikjtzf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpvinzsy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtdoxbjhqe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtbeumqlpd.html

TS:   constructor(public name: string) {}
来源：http://dali.tian-w.cn/Article/details/gtiahuijak.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtuptvgpqd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yueranfly.top/Article/details/gtcqvbsrtd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.havefunace.top/Article/details/gtbthgcysd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtfnhfsqis.html

[G03] 实例属性
来源：http://dali.0kj1m.cn/Article/details/gtlukqpryj.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtcnlmwprg.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gthclemtws.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gthbmnzcyu.html

TS:   name: string = "x";
来源：http://dali.cucudq.cn/Article/details/gtapkpqqbd.html

Java: private String name;
来源：http://dali.nanxinkj.top/Article/details/gtqbpztoce.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhixingplan.top/Article/details/gtedsgpfhh.html

Ruby: @name = "x"
来源：http://dali.guowangkeji.top/Article/details/gtnvwrmggj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gthjmdihgm.html

[G04] 定义方法
来源：http://dali.zhoulong.xyz/Article/details/gtkgwkjylr.html

Py:   def greet(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtskhpndsi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtcwvttxcz.html

JS:   greet() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpajkoars.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gttbbcygiq.html

Java: String greet() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gteoeuzzpf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtosbhiefd.html

Ruby: def greet; @name; end
来源：http://dali.meibo888.top/Article/details/gtrazwgwem.html

C#:   public string Greet() => Name;
来源：http://dali.ybcxt.top/Article/details/gtolsznzqe.html

[G05] 继承
来源：http://dali.hnxiangtu.top/Article/details/gtfseelnuq.html

Py:   class Admin(User): pass
来源：http://dali.sufxvd.cn/Article/details/gtbipporks.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtcbawfajw.html

JS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtjkjwgakx.html

TS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtaemadkux.html

Java: class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtinhhtcrf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gtlfobatbp.html

Ruby: class Admin < User; end
来源：http://dali.sufxvd.cn/Article/details/gtolznqpgw.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gtankwitdk.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gtzunxitbn.html

Py:   def greet(self): return "admin"
来源：http://dali.fengsongda.top/Article/details/gtbpgrqwtq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtkwtjkbok.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtmnsdokln.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtwywcwfro.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtegpufcbd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gtvvpuoarr.html

Ruby: def greet; "admin"; end
来源：http://dali.tanke756.top/Article/details/gtcelkgjhr.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gticpsoird.html

[G07] 调用父类方法
来源：http://dali.ppjwa.cn/Article/details/gtlztjfglb.html

Py:   super().greet()
来源：http://dali.haohaochexian.top/Article/details/gtitflgiol.html

PHP:  parent::greet();
来源：http://dali.fzhhl.top/Article/details/gtnihehmxr.html

JS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtgysbthkh.html

TS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gttuivkkvb.html

Java: super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtjyxebuyg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ehwqpu.com/Article/details/gtikpayqmj.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gtmpwxaepp.html

C#:   base.Greet();
来源：http://dali.aizwys.cn/Article/details/gtcrtqqkft.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gtvbitydmj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jlsjyb.cn/Article/details/gtfcxtngkw.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtlobilild.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gtwxwxnwme.html

TS:   static f(): void {}
来源：http://dali.yuanzhike.top/Article/details/gttaqaoebf.html

Java: static void f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtlnjioveq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zdqjudy.top/Article/details/gtiyckkwkr.html

Ruby: def self.f; end
来源：http://dali.tanke756.top/Article/details/gtdfhgstrd.html

C#:   public static void F() {}
来源：http://dali.guowangkeji.top/Article/details/gtbuthqzfc.html

[G09] 接口 / 抽象类
来源：http://dali.c1oappe.top/Article/details/gtsqvnjcpe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gtkncqopex.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenzaomai.com/Article/details/gtrpihxlmw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgufenzy.top/Article/details/gtkeopdhcc.html

TS:   interface Shape { area(): number; }
来源：http://dali.sufxvd.cn/Article/details/gtsmchcjng.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gttsjazbqj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gtnennknam.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gtnckcecsd.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gtgsbqwfpb.html

[G10] 访问控制
来源：http://dali.nanxinkj.top/Article/details/gtxbcidqfx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxuanxn.top/Article/details/gtjzhibdbu.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtcjvdsvda.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gtxyptfauq.html

TS:   public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtokjxgmib.html

Java: public / protected / private / 默认包级
来源：http://dali.tianlin.xyz/Article/details/gtpjxmtequ.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aizwys.cn/Article/details/gtiwxrdbmy.html

Ruby: public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtdsoijyqh.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gtdnkpgxvi.html

[G11] getter / setter
来源：http://dali.haohaochexian.top/Article/details/gtqtqcqzmf.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gtxzddpbav.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtpptpayiz.html

JS:   get name() { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybhoyssl.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtmrkeoxiq.html

Java: public String getName() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtjqtijzuf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtjfpdibbs.html

Ruby: attr_accessor :name
来源：http://dali.guowangkeji.top/Article/details/gtxvrvyotm.html

C#:   public string Name { get; set; }
来源：http://dali.xziqi.cn/Article/details/gtxoiatonq.html

[G12] 对象转字符串
来源：http://dali.9152youxi.cn/Article/details/gtjzayzkcd.html

Py:   def __str__(self): return self.name
来源：http://dali.yonumen.top/Article/details/gtlvejhnfp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtfxaihmyd.html

JS:   toString() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtpbbquiyi.html

TS:   toString(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtbwqynssa.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnqzz.top/Article/details/gttopswhre.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtizptodyv.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gtqbxuycip.html

C#:   public override string ToString() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtrdzmwhmh.html

[G13] 判断对象类型
来源：http://dali.hywenlv.cn/Article/details/gtbcdrmuyw.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gtplhfdoox.html

PHP:  $u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtodcwdcdg.html

JS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtzppvgcyg.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtnedbkhvy.html

Java: u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgnsyfwq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgegysjc.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gtnrjyzwxu.html

C#:   u is User
来源：http://dali.mhx1999.top/Article/details/gtarycvamt.html

[G14] 数据类 / record
来源：http://dali.nanxuanxn.top/Article/details/gtrpvfanhd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuanzx.com/Article/details/gtrlhvkovj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258.top/Article/details/gtqzrelxtt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gaohongyu789.top/Article/details/gtchdpmkvt.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gtwgfcwoqe.html

Java: record User(String name, int age) {}
来源：http://dali.yongpay.top/Article/details/gtwhhrblxt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtsojwcs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnyuxwmr.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gtbfzadjfw.html

[G15] 枚举
来源：http://dali.gotoacloud.top/Article/details/gtriicnczp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gtlfpeuwmw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwjouvght.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yangfankeji.com/Article/details/gthirakxuc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gthrgcsslr.html

Java: enum Color { RED, GREEN }
来源：http://dali.daria6918.cn/Article/details/gtlztpckxu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yonumen.top/Article/details/gtywepsfmd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuetiantiany.cn/Article/details/gtpdnoppmt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtloxxonfb.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxinkj.top/Article/details/gtnguajodf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xinyue.icu/Article/details/gtyumdeesf.html

PHP:  get_object_vars($obj);
来源：http://dali.zhengqikj.top/Article/details/gtqaalttto.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gteyyzwdqk.html

TS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gtajbnkupz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hongshengwenyu.top/Article/details/gtygaxcqvv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gtkaoccvae.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gttumtlkoh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtqotabpyf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtcethghsd.html

H. 异常与错误处理
来源：http://dali.gaohongyu789.top/Article/details/gtfxzjiojv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtpzbnonxd.html

[H01] try / catch 基础
来源：http://dali.c1oappe.top/Article/details/gtdupolsxv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigfzy.top/Article/details/gtwghsslbe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gtaqiuaprz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtbvhkdyis.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtpkhvupbs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gogol.net.cn/Article/details/gtygtuqdha.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zycfv.cn/Article/details/gtacakwkfc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shzxlz.cn/Article/details/gtdnqwvotm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gtadhuwiwg.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gtywsvgsje.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gtsirrywwi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtulepoity.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtxatyulcf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtslnqdeue.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtakvzdxko.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlftjxast.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gtemskocvi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtjuslgfzd.html

[H03] 主动抛出异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtluooffje.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gtgbqjkfvt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtnbadamau.html

JS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtoffbgykw.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtwkyuzdkz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtcdgywbip.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gaohongyu789.top/Article/details/gtftrggaga.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ybcxt.top/Article/details/gtkeoophft.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtbxhiuywh.html

[H04] 自定义异常类型
来源：http://dali.zhixingplan.top/Article/details/gtyfwazlax.html

Py:   class MyError(Exception): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtoinqjkoa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtjyuavsxc.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtvefiwdhn.html

TS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtsjlbwncz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gtdpqxwtrj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gogol.net.cn/Article/details/gtzxroyqov.html

Ruby: class MyError < StandardError; end
来源：http://dali.jianghu66.top/Article/details/gtrxeqggwu.html

C#:   class MyException : Exception {}
来源：http://dali.hnxiangtu.top/Article/details/gthpyeopfz.html

[H05] 捕获特定类型
来源：http://dali.smart0.xyz/Article/details/gtvwbcfbyf.html

Py:   except ValueError as e:
来源：http://dali.0kj1m.cn/Article/details/gtzxhzlemw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yangfankeji.com/Article/details/gtwfcuvocf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gtwdponqiu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswjzdxmk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gtyqronawu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gtxhklvuae.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gttswrfrqe.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gtfijrfqns.html

[H06] 可选值 / 空值安全访问
来源：http://dali.havefunace.top/Article/details/gtzfomsmsj.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gtmwzsndkx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtpjejgnnk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhreocmr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtmskacdtv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jlsjyb.cn/Article/details/gtvcuvhxmx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gtjsaybsgt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.snrcjt.cn/Article/details/gtchiubqwq.html

C#:   obj?.A?.B ?? default
来源：http://dali.dashuyun.cn/Article/details/gtvffcdsjf.html

[H07] 断言
来源：http://dali.nanxinkj.top/Article/details/gtoulndwvr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.c1oappe.top/Article/details/gtufxlouli.html

PHP:  assert($x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtdfcmqkwn.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtilqesfqc.html

TS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtycprannj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.mhx1999.top/Article/details/gtjbejmjey.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gtxdosbsyq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gtrcreatiz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkndnyjex.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gtzbpdmlgu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sweek.top/Article/details/gtnpyiyilt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yonumen.top/Article/details/gtwgznjdtg.html

JS:   e.message;  e.stack
来源：http://dali.xylfe.cn/Article/details/gtitrxlltz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aibaodan.cn/Article/details/gtchzmsaus.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnxiangtu.top/Article/details/gtgexxqihf.html

Go:   err.Error()
来源：http://dali.zhongyouzk.top/Article/details/gtigckvctk.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenjidiqi.icu/Article/details/gtmjfqcebg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nwbrower.top/Article/details/gtnflydslm.html

[H09] 带错误码的异常
来源：http://dali.guannengcc.top/Article/details/gtppwsnvjf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sweek.top/Article/details/gtmibevatw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gtrmeerlvq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ybcxt.top/Article/details/gtbyzzndex.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwifnngmb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.smart0.xyz/Article/details/gttpnabjai.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fengsongda.top/Article/details/gtxkbcxftk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.vqdsnc.cn/Article/details/gteylowtrr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuanzx.com/Article/details/gtcjrgauzo.html

[H10] 资源自动释放
来源：http://dali.shangyingyoupin.top/Article/details/gtwrlmrion.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.iojbl.cn/Article/details/gtoslnshhx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnxiangtu.top/Article/details/gtkqpyhjzp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gtqnsnqnkh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gtpjoeexgv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.svipenyu.cn/Article/details/gtaglpqsmv.html

Go:   defer f.Close()
来源：http://dali.dashuyun.cn/Article/details/gtnhyovaqr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gtvmfwgimx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtippmkcob.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtvuvpppoj.html

I. 正则表达式
来源：http://dali.c1oappe.top/Article/details/gthlruainw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqkwibrj.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gtwiwwmvss.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsverbzd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtxnjskleb.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gttxipdbte.html

TS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gtqcsbwckl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gtjzbfjrwj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cheryme.top/Article/details/gthaezfbcd.html

Ruby: s.match?(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gtxmqdwyfk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xylfe.cn/Article/details/gtckmfzxsa.html

[I02] 提取所有匹配
来源：http://dali.cqqwz.cn/Article/details/gtzkxhmimj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtvlibakht.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dashuyun.cn/Article/details/gtcowqgpdx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tianlin.xyz/Article/details/gtiivpblow.html


<!-- 参考信息 -->