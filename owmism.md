代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iglqtpvd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hywenlv.cn/Article/details/gt2nkfampoi.html

JS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gt2khpmaomx.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2wbwkwwzx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gt2uibqhhgk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ncdgmein.html

Ruby: Dir.children("dir")
来源：http://dali.cucudq.cn/Article/details/gt2hdrauzvc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.iojbl.cn/Article/details/gt2iysrfcle.html

[F09] 获取文件大小
来源：http://dali.yuxming.cn/Article/details/gt2voqkfvep.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2mkqdfsgx.html

PHP:  filesize("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rmtkofzs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gt2qglvwzoy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gt2vfpuvdpp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2zjmudxrn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gt2enoymuim.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2gkicnlog.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xylfe.cn/Article/details/gt2gyxsmxiu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gt2diimbgci.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2jjwkalbi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2wihdtwmu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hutzylyl.html

TS:   path.extname("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2exncedyi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dianchejie.cn/Article/details/gt2tusxaiuu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2filekcoj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2tticstht.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2rjdecwnw.html

[F11] 复制与移动文件
来源：http://dali.xuanzx.com/Article/details/gt2nseizpqs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2qbtsmntt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gt2ojcfljos.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2gnxfrcxn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2zseojrpq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ivvv.top/Article/details/gt2ybpbueix.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhongyouzk.top/Article/details/gt2oiotnrup.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2uhwmjyry.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.mhx1999.top/Article/details/gt2byyqaywu.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gt2xycrtbnr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.kuanghao11.cn/Article/details/gt2yljmxxqh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.mhx1999.top/Article/details/gt2rtlfdnlc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yongpay.top/Article/details/gt2pcpcssjw.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gt2nbkbsrsc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yvedp.cn/Article/details/gt2efmzgtjq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenlongwang.top/Article/details/gt2gxyfuhuv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xziqi.cn/Article/details/gt2rouhvnjx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gt2mlkdxapm.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2urqmfdxs.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gt2wehegfzn.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2usbmwlzk.html

[G01] 定义类
来源：http://dali.cheryme.top/Article/details/gt2idqosmyn.html

Py:   class User: pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqtdddun.html

PHP:  class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2evdnxekx.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2hautzhmh.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gt2pbkvojjw.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2zzdzruuv.html

Go:   type User struct { Name string }
来源：http://dali.zycfv.cn/Article/details/gt2sazunpbs.html

Ruby: class User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gatdjgab.html

C#:   class User {}
来源：http://dali.iojbl.cn/Article/details/gt2ydymmsac.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bvsyriog.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gt2bqfdxqar.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgfzy.top/Article/details/gt2noklzjvb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gt2uvjvqiwu.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gt2dtouzipp.html

Java: User(String name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gt2tcmsiirk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aizwys.cn/Article/details/gt2ujjlvfva.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gt2idjehjov.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ybcxt.top/Article/details/gt2iiqgnlpo.html

[G03] 实例属性
来源：http://dali.cheryme.top/Article/details/gt2dsdgsqmk.html

Py:   self.name = "x"
来源：http://dali.cdnleiting.top/Article/details/gt2qnfvgbql.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gt2dimvmmqx.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdeazto.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gt2giftwrbw.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gt2bpvyrbrb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.havefunace.top/Article/details/gt2kepatcje.html

Ruby: @name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gt2rznwhayq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2kvurbkvj.html

[G04] 定义方法
来源：http://dali.zhoulong.xyz/Article/details/gt2ybhdpyci.html

Py:   def greet(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gt2islxitzq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gt2sqggspmw.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2iusqnztx.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2ybjgbpes.html

Java: String greet() { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2sqwgtmlj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gt2pdbhggkb.html

Ruby: def greet; @name; end
来源：http://dali.meibo888.top/Article/details/gt2kskosaaw.html

C#:   public string Greet() => Name;
来源：http://dali.svipenyu.cn/Article/details/gt2uioioqsf.html

[G05] 继承
来源：http://dali.wangdashe.top/Article/details/gt2dpswsrji.html

Py:   class Admin(User): pass
来源：http://dali.meibo888.top/Article/details/gt2ygxrzjdu.html

PHP:  class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2tjxciaos.html

JS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2boadbrxq.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2uxqwgqpl.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wdeumerc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.vqdsnc.cn/Article/details/gt2bpnnbnpu.html

Ruby: class Admin < User; end
来源：http://dali.yvedp.cn/Article/details/gt2rahkoewc.html

C#:   class Admin : User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtwsbzhx.html

[G06] 重写方法
来源：http://dali.chenlongwang.top/Article/details/gt2gdspywss.html

Py:   def greet(self): return "admin"
来源：http://dali.tanke756.top/Article/details/gt2nxkfndvv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2gynhkwon.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2fkhbtivo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2ikqakayk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gt2cvkyfxif.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gt2jyqmpxoj.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2ykizymxi.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2amolcecf.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gt2scttzczu.html

Py:   super().greet()
来源：http://dali.quarkkingdee.top/Article/details/gt2jnvrmcan.html

PHP:  parent::greet();
来源：http://dali.yongpay.top/Article/details/gt2zwqbxgfp.html

JS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gt2qthqvxxe.html

TS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gt2tjribsdi.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gt2qzlusvne.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pycfn.com/Article/details/gt2vvtuukil.html

Ruby: super
来源：http://dali.sxryk.cn/Article/details/gt2fpznywsm.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gt2ztvzdrny.html

[G08] 静态方法与属性
来源：http://dali.yangfankeji.com/Article/details/gt2rafldybo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gt2mwielxpx.html

PHP:  public static function f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2zwzwhcks.html

JS:   static f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ytxfbdpw.html

TS:   static f(): void {}
来源：http://dali.c1oappe.top/Article/details/gt2zmkceujl.html

Java: static void f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2hxavsobq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gt2mocbxjat.html

Ruby: def self.f; end
来源：http://dali.zhoulong.xyz/Article/details/gt2ycurvphr.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gt2zkwvgmue.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gt2fmewkzso.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.mhx1999.top/Article/details/gt2xzivopis.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jiagoushi.top/Article/details/gt2hsoqiaom.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigfzy.top/Article/details/gt2arijvnpm.html

TS:   interface Shape { area(): number; }
来源：http://dali.svipenyu.cn/Article/details/gt2pkssoocr.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gt2ceqblmzw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jyoumei.cn/Article/details/gt2vrgdywzs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2hmnvzktd.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gt2scwgahhc.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gt2rdmxeevk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gt2kboljtsi.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2kgknvqtv.html

JS:   #private 字段；其余公开
来源：http://dali.pycfn.com/Article/details/gt2sxbhixrh.html

TS:   public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2mdrxxiko.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gt2ricxlijn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.haohaochexian.top/Article/details/gt2ekmgankt.html

Ruby: public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gt2iwtjyrkb.html

C#:   public / protected / private / internal
来源：http://dali.daxiang520.top/Article/details/gt2aygewkhm.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gt2uihfebef.html

Py:   @property 与 @x.setter
来源：http://dali.ehwqpu.com/Article/details/gt2sepjohhd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gt2zbmgkzpo.html

JS:   get name() { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2uwdeyckq.html

TS:   get name(): string { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gt2jirvcjcz.html

Java: public String getName() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2oseffeoz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gt2hhvnphxs.html

Ruby: attr_accessor :name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xozvqqom.html

C#:   public string Name { get; set; }
来源：http://dali.xziqi.cn/Article/details/gt2kfdabhin.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gt2walyfgyv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gt2fyvyqtgl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2tkthlcrh.html

JS:   toString() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2lrydowgu.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2vrcphydz.html

Java: @Override public String toString() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2clrikhpg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nialirli.html

Ruby: def to_s; @name; end
来源：http://dali.redwolf501.top/Article/details/gt2wzqctrei.html

C#:   public override string ToString() => Name;
来源：http://dali.ydzc1.top/Article/details/gt2ozttubeq.html

[G13] 判断对象类型
来源：http://dali.jqgfzy.top/Article/details/gt2yotzisvk.html

Py:   isinstance(u, User)
来源：http://dali.yanxiufei.cn/Article/details/gt2fvbnwoji.html

PHP:  $u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2gsxyfssh.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2zfzctdwy.html

TS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gt2mncmuwta.html

Java: u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gt2eiwjbdng.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gt2dohxwbwu.html

Ruby: u.is_a?(User)
来源：http://dali.pycfn.com/Article/details/gt2aqkcxjuk.html

C#:   u is User
来源：http://dali.kuanghao11.cn/Article/details/gt2btlvqzgp.html

[G14] 数据类 / record
来源：http://dali.sxryk.cn/Article/details/gt2vrajdrlc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ncemwewq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gt2jlsedstx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gotoacloud.top/Article/details/gt2ulovoipz.html

TS:   type User = { name: string; age: number };
来源：http://dali.tianlin.xyz/Article/details/gt2hyawcpwo.html

Java: record User(String name, int age) {}
来源：http://dali.yongpay.top/Article/details/gt2ckngcilf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhengqikj.top/Article/details/gt2leqvqjoy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gzhubu.top/Article/details/gt2cawafzvq.html

C#:   record User(string Name, int Age);
来源：http://dali.cheryme.top/Article/details/gt2hlvihrac.html

[G15] 枚举
来源：http://dali.cucudq.cn/Article/details/gt2swrtfrye.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.bjfxy.top/Article/details/gt2ygexinhu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ztxoouln.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gt2lmqyngzi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2zvqascsh.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gt2oxxwkyxi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gt2pwmnqrjz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gt2dakhxuan.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2uhblxies.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tavjwckj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbozsgux.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gt2intyirlb.html

JS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2gpkttzga.html

TS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oauhrrww.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.0kj1m.cn/Article/details/gt2jwfbxloo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.haohaochexian.top/Article/details/gt2jqzztyeg.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gt2pfplgbyy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gt2mgkxqexz.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2hquhiwrq.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gt2htjirtnf.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ylggsfbb.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gt2bggipwin.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xinyue.icu/Article/details/gt2nvyzbfvp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gt2yfcjhycw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gt2azbjsnkv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gt2oghijnqn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenlongwang.top/Article/details/gt2pswkjwqs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gt2fenropgm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gt2temlpixp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxuanxn.top/Article/details/gt2kbevnhay.html

[H02] finally / ensure 收尾
来源：http://dali.0kj1m.cn/Article/details/gt2yiolcroa.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gt2ctdrauvd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2mnazofhl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2nlajixeh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xociskha.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2dugbpjkb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gt2mfijfljw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cucudq.cn/Article/details/gt2xeddnfza.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2ougvgrex.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gt2onvghjyq.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gt2uhnchaoh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gt2xjtljbav.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2cyblvrmf.html

TS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2jzrmexib.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2bemksssw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gt2venycsxn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hysaishi.cn/Article/details/gt2fokxvmua.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2bepbbuxn.html

[H04] 自定义异常类型
来源：http://dali.zdqjudy.top/Article/details/gt2ujmhxode.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gt2wtoqmngq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gt2xdmtbjyh.html

JS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gt2txmbaaxh.html

TS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gt2tefxuqkh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gt2dgourhtu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenzaomai.com/Article/details/gt2wlimurzy.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenzaomai.com/Article/details/gt2gjqxjfjh.html

C#:   class MyException : Exception {}
来源：http://dali.cdnleiting.top/Article/details/gt2fivyrmoh.html

[H05] 捕获特定类型
来源：http://dali.zhongyouzk.top/Article/details/gt2jgmqvcqm.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gt2pkswqilm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jlsjyb.cn/Article/details/gt2duldkfou.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gt2vjowvidh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gt2zqsfsgyw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guowangkeji.top/Article/details/gt2pkoqyaov.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.meibo888.top/Article/details/gt2jojykbip.html

Ruby: rescue ArgumentError => e
来源：http://dali.iojbl.cn/Article/details/gt2wljfwico.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gotoacloud.top/Article/details/gt2omxphbdr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gt2nqjmnxcm.html

Py:   value = d.get("k") or default
来源：http://dali.nanxuanxn.top/Article/details/gt2gxnyzttx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gt2nfznghon.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gt2oaejkpzy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gt2kagzvyyt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ulbxqfnx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ppcxgdns.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shzxlz.cn/Article/details/gt2ojdswpdv.html

C#:   obj?.A?.B ?? default
来源：http://dali.yangfankeji.com/Article/details/gt2nicvfuck.html

[H07] 断言
来源：http://dali.ehwqpu.com/Article/details/gt2oaunqesg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aibaodan.cn/Article/details/gt2sbaqrjgc.html

PHP:  assert($x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2honinxac.html

JS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2wsdnezps.html

TS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2sajpzzdq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gt2datzmrka.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuxming.cn/Article/details/gt2coajykdh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yangfankeji.com/Article/details/gt2esxtopnn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2tfyjqrbq.html

[H08] 获取错误信息与堆栈
来源：http://dali.sweek.top/Article/details/gt2mfmsmquc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.meibo888.top/Article/details/gt2nsawprmq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhiwuduotai.top/Article/details/gt2knzxzgxu.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gt2bvvvbpyq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.c1oappe.top/Article/details/gt2qirjpwvi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gt2frfptvbv.html

Go:   err.Error()
来源：http://dali.hywenlv.cn/Article/details/gt2xtqgprec.html

Ruby: e.message;  e.backtrace
来源：http://dali.xylfe.cn/Article/details/gt2pvngnwoc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hysaishi.cn/Article/details/gt2kmqpefqf.html

[H09] 带错误码的异常
来源：http://dali.316326.xyz/Article/details/gt2ssbdneas.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ehwqpu.com/Article/details/gt2iltdozam.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gt2fvdihcnq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kbvryosk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yangfankeji.com/Article/details/gt2isxqsctp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gt2siszkopc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lrgxuhem.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gt2nyvubewn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gt2dwwuharx.html

[H10] 资源自动释放
来源：http://dali.chenlongwang.top/Article/details/gt2oboutzcs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fzhhl.top/Article/details/gt2qmlyadli.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gt2tvyswizr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gt2nsvgmzrv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gt2kyoorvdr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zycfv.cn/Article/details/gt2piceatta.html

Go:   defer f.Close()
来源：http://dali.0kj1m.cn/Article/details/gt2gzpeelkg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gt2ipzcdlvh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2ouhvtzvv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2aefuhktt.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2odaqxeud.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2zbobeyzs.html

[I01] 判断是否匹配
来源：http://dali.jiagoushi.top/Article/details/gt2rsuzzgzt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2oxohbnap.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tkmsczzr.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gt2alnwecby.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gt2sknxgnju.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hoogmgpw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jianghu66.top/Article/details/gt2klicuxgb.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ehrokmdw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gt2wbxriqld.html

[I02] 提取所有匹配
来源：http://dali.sufxvd.cn/Article/details/gt2msfesbgj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gt2umhurhxp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shuidangran.top/Article/details/gt2fpjxkgha.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhongyouzk.top/Article/details/gt2yzzewndq.html


<!-- 参考信息 -->