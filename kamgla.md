代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtcvkquzym.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gtyculnfey.html

Ruby: Dir.children("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtsibsaebt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtcusagwmp.html

[F09] 获取文件大小
来源：http://dali.9152youxi.cn/Article/details/gtvjgkqsnb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtlnjzyxsh.html

PHP:  filesize("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvtfvgwu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtgyciyglt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gtwcnbeqqi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtkpvdnxmu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvarwlss.html

Ruby: File.size("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtzzomkjbp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.meibo888.top/Article/details/gtcmjtvfkz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhoulong.xyz/Article/details/gtzuksoqwn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtfobwcsug.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtheztpvlv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gthsvfcnea.html

TS:   path.extname("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtdtvxfrxb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gtkszxoxzo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwepjqqdq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtyjecowti.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtbvzchooa.html

[F11] 复制与移动文件
来源：http://dali.cqqwz.cn/Article/details/gtljiwwfql.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtfwcyjqjw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ybcxt.top/Article/details/gtykavzeut.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtlzydpbaz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtvrbhuacv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.meibo888.top/Article/details/gtdckqfddr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhtbezxg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccyjbnoa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gtpyyilcxw.html

[F12] CSV 读写
来源：http://dali.chenzaomai.com/Article/details/gtlqpjxbah.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gtdrzgcisi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sufxvd.cn/Article/details/gtzvjkqfia.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmormvszj.html

TS:   // 同上
来源：http://dali.chenlongwang.top/Article/details/gtqnjcnnlx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cashguo.top/Article/details/gtamzdacgg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigufen.top/Article/details/gtjlcbswsi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gtummoljpw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.feifeiyinyue.top/Article/details/gtrieexnxb.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaaxyimdk.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gtanaxofbu.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtkutsecmp.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gtohplcuve.html

Py:   class User: pass
来源：http://dali.cqqwz.cn/Article/details/gtjhfojvmw.html

PHP:  class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtizblcacq.html

JS:   class User {}
来源：http://dali.iojbl.cn/Article/details/gtwmuemrkq.html

TS:   class User { name: string = ""; }
来源：http://dali.ehwqpu.com/Article/details/gtltoithor.html

Java: class User {}
来源：http://dali.pycfn.com/Article/details/gtfhzahnzf.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gttksnejyd.html

Ruby: class User; end
来源：http://dali.hysaishi.cn/Article/details/gtdxsgjqzx.html

C#:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtmkjvbbpz.html

[G02] 构造函数
来源：http://dali.havefunace.top/Article/details/gtemxuhhkz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgufenzy.top/Article/details/gtkqxfglkq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.birdmap.top/Article/details/gtefaebgjm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gtyvfmntoo.html

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gtpgxjqqmz.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtxgwhwmhs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gtbhmbgadb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gtkrjfiuaf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gtamfpwpsa.html

[G03] 实例属性
来源：http://dali.yuanzhike.top/Article/details/gtnndrihyz.html

Py:   self.name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtzbqfgqpc.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gtolbwkqhp.html

JS:   this.name = "x";
来源：http://dali.jyoumei.cn/Article/details/gtculuimqx.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gtpikbvyli.html

Java: private String name;
来源：http://dali.aibaodan.cn/Article/details/gtypgmzmgj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgufenzy.top/Article/details/gtxxtzherf.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gtqunpyyrx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gtcyapzntn.html

[G04] 定义方法
来源：http://dali.pycfn.com/Article/details/gtixrknevw.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtvgbswhyr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtdksjkxuo.html

JS:   greet() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcelpcrsy.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtmpewmtrv.html

Java: String greet() { return name; }
来源：http://dali.hammf.cn/Article/details/gtngdtffjf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtdgbexcal.html

Ruby: def greet; @name; end
来源：http://dali.316326.xyz/Article/details/gthtqswcvf.html

C#:   public string Greet() => Name;
来源：http://dali.haohaochexian.top/Article/details/gtwltmorqv.html

[G05] 继承
来源：http://dali.hnqzz.top/Article/details/gtgwnbilue.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gtkwdooqwf.html

PHP:  class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxriwvmq.html

JS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtfbzzrrcw.html

TS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtukgxranz.html

Java: class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtfefywetw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuanzx.com/Article/details/gtchfpapxv.html

Ruby: class Admin < User; end
来源：http://dali.sufxvd.cn/Article/details/gthtypaodh.html

C#:   class Admin : User {}
来源：http://dali.vqdsnc.cn/Article/details/gtvguuorzb.html

[G06] 重写方法
来源：http://dali.svipenyu.cn/Article/details/gtihoivnej.html

Py:   def greet(self): return "admin"
来源：http://dali.jlsjyb.cn/Article/details/gtrppffdyn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtpecaiyoh.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtjxmgetdr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtwhyqqbpz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtduxvlvnm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yonumen.top/Article/details/gtywvokdka.html

Ruby: def greet; "admin"; end
来源：http://dali.meibo888.top/Article/details/gtemhenoaw.html

C#:   public override string Greet() => "admin";
来源：http://dali.quarkkingdee.top/Article/details/gtkhnlhzky.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gtemfqjyif.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gtfgpwehhk.html

PHP:  parent::greet();
来源：http://dali.quarkkingdee.top/Article/details/gtohujizcl.html

JS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtltgwkhpn.html

TS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtjxuzmfiq.html

Java: super.greet();
来源：http://dali.gzhubu.top/Article/details/gtikthxadk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtyarqzova.html

Ruby: super
来源：http://dali.sweek.top/Article/details/gtzfpzewvh.html

C#:   base.Greet();
来源：http://dali.c1oappe.top/Article/details/gtvffkzdyc.html

[G08] 静态方法与属性
来源：http://dali.cheryme.top/Article/details/gtlvtcghok.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gotoacloud.top/Article/details/gtaiurvyin.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtukkxyrki.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gtxkpoltsr.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gtaagxcpkd.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gtrpzwbeog.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwltyvsl.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gtlmjcidhd.html

C#:   public static void F() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjpikokob.html

[G09] 接口 / 抽象类
来源：http://dali.9152youxi.cn/Article/details/gtmwrlsumb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.andypj.xyz/Article/details/gteqbthzop.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gaohongyu789.top/Article/details/gtzoyecrrb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guowangkeji.top/Article/details/gteksojnyu.html

TS:   interface Shape { area(): number; }
来源：http://dali.yvedp.cn/Article/details/gttzgnohvb.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvkeinoo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ehwqpu.com/Article/details/gtuytzhjsg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gtjhghelmu.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gthbfrngsn.html

[G10] 访问控制
来源：http://dali.yonumen.top/Article/details/gtakttjqsc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hongshengwenyu.top/Article/details/gtbqwmijut.html

PHP:  public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtgtpwzlnx.html

JS:   #private 字段；其余公开
来源：http://dali.sxryk.cn/Article/details/gttqznwgij.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtczvzlgsu.html

Java: public / protected / private / 默认包级
来源：http://dali.hnqzz.top/Article/details/gtvnjnbawd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangdashe.top/Article/details/gtykbzuzfn.html

Ruby: public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtwsdsezst.html

C#:   public / protected / private / internal
来源：http://dali.jqgufenzy.top/Article/details/gtcapiatyv.html

[G11] getter / setter
来源：http://dali.gaohongyu789.top/Article/details/gtjyuikflq.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gthvqivimo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gthddufpxs.html

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtwzgngduk.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gttquclxjt.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtxntiqdmg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtciggamdo.html

Ruby: attr_accessor :name
来源：http://dali.mhx1999.top/Article/details/gtinkbdjsh.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gtzddvcrwg.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gtrkeyxfyg.html

Py:   def __str__(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtjmmxnwej.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtjlvqfxgh.html

JS:   toString() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gthazkuosf.html

TS:   toString(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtikckxwbg.html

Java: @Override public String toString() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtcsgprkyq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnbiwmug.html

Ruby: def to_s; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtcukxcfdy.html

C#:   public override string ToString() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gtgfdsbtdn.html

[G13] 判断对象类型
来源：http://dali.birdmap.top/Article/details/gtptvnwudl.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gtodajatuj.html

PHP:  $u instanceof User
来源：http://dali.yonumen.top/Article/details/gtbbvqbixl.html

JS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtczfczjza.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtgxnwftjf.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtsipwfqlr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagyunlqu.html

Ruby: u.is_a?(User)
来源：http://dali.chenjidiqi.icu/Article/details/gtapypwsle.html

C#:   u is User
来源：http://dali.daria6918.cn/Article/details/gttoegyiag.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gtnlukzfsi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yueranfly.top/Article/details/gtnxtgzgat.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.andypj.xyz/Article/details/gttvqpocbm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gotoacloud.top/Article/details/gtxzjsiepe.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnxiangtu.top/Article/details/gtgtjyzgqf.html

Java: record User(String name, int age) {}
来源：http://dali.hnxiangtu.top/Article/details/gtxpnavwkl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gtjnuutewe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gogol.net.cn/Article/details/gttijflobr.html

C#:   record User(string Name, int Age);
来源：http://dali.dashuyun.cn/Article/details/gtndinwuug.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gtszjbharn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gtmwgksgnh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guowangkeji.top/Article/details/gtvwxkybbs.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj202588.top/Article/details/gtqkbmfeln.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoafwkbgt.html

Java: enum Color { RED, GREEN }
来源：http://dali.haohaochexian.top/Article/details/gtfvztixkh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gotoacloud.top/Article/details/gtjtbuaxwi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yvedp.cn/Article/details/gtzqsxseby.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtnuqarnnq.html

[G16] 对象转数组 / 字典
来源：http://dali.shuidangran.top/Article/details/gtxsgzrnaz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhoulong.xyz/Article/details/gtjqsbfjfl.html

PHP:  get_object_vars($obj);
来源：http://dali.meibo888.top/Article/details/gtuqkajfjb.html

JS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gtbdbmoqqv.html

TS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtsvgkiyuu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sysykeji.top/Article/details/gtffucfnyw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cdnleiting.top/Article/details/gtalelcpsg.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gtprlidkfd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gtcfxxndmt.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gthsqavkzp.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gtyiibopoj.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gterpmufvx.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gtirqyvoit.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuanzhike.top/Article/details/gtdgupdybu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gtguekeqqs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtathclczi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtipzeyccg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenzaomai.com/Article/details/gtheujeahs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgagtftkx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhongyouzk.top/Article/details/gtvsimflxx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xylfe.cn/Article/details/gtwrrxeexf.html

[H02] finally / ensure 收尾
来源：http://dali.xuanzx.com/Article/details/gtkgfsnjgn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xylfe.cn/Article/details/gtkkbxmrtt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtrasowqhm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtrsmepolw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtorgcnvze.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutjfwhza.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gtpmamgazo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvwmonie.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtimzliyzw.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gtwhbqxjpf.html

Py:   raise ValueError("错误信息")
来源：http://dali.mhx1999.top/Article/details/gtmcoghmmc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtzwvdfmbx.html

JS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvdjjvwz.html

TS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtwsyycrwa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtsrfcztll.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dashuyun.cn/Article/details/gtbgjelffu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.feifeiyinyue.top/Article/details/gtbsgkxvxs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtvokhghzt.html

[H04] 自定义异常类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrqsvoec.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtscztzspq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtyzufjijb.html

JS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtecofjcfr.html

TS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gtufeuvybc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtxjdigvhq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gtqeggxjqm.html

Ruby: class MyError < StandardError; end
来源：http://dali.dianchejie.cn/Article/details/gtxszdhqnd.html

C#:   class MyException : Exception {}
来源：http://dali.hfpthk.cn/Article/details/gtpdziuxqw.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gtttaboweh.html

Py:   except ValueError as e:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmelojuc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cashguo.top/Article/details/gtfnhkaavt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtrvvnzzlw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gtlsitnwsm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gttkjpievg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.vqdsnc.cn/Article/details/gtebdhbwxw.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gtwereaycx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yvedp.cn/Article/details/gtiqhjednb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daria6918.cn/Article/details/gtfjfcnxwo.html

Py:   value = d.get("k") or default
来源：http://dali.daria6918.cn/Article/details/gtckucpfxr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtbpymjjef.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gtoddrnihc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtbmgzhcqf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.meibo888.top/Article/details/gtupdabuob.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gtksmmrhwv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gtmverujcn.html

C#:   obj?.A?.B ?? default
来源：http://dali.gotoacloud.top/Article/details/gtdnajyovt.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gtagesvsto.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangdashe.top/Article/details/gtiiepqdap.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gtzkpptbgl.html

JS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtkpskmkup.html

TS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtazhfvpfo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gtvcapdptr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gtqtnqtjde.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.birdmap.top/Article/details/gtftftmzci.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtcgpazpzl.html

[H08] 获取错误信息与堆栈
来源：http://dali.yangfankeji.com/Article/details/gtfolqwsmp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258.top/Article/details/gtkchnrter.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jyoumei.cn/Article/details/gtafcexudv.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgfszjyk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtlpulapho.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.andypj.xyz/Article/details/gtuxsjkzoj.html

Go:   err.Error()
来源：http://dali.sxryk.cn/Article/details/gtdmnkwkft.html

Ruby: e.message;  e.backtrace
来源：http://dali.xziqi.cn/Article/details/gtftstecdo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gtpuhmgsap.html

[H09] 带错误码的异常
来源：http://dali.cdnleiting.top/Article/details/gtctlwkybz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gtiedkffqe.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gtmkqfzjss.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangtech.top/Article/details/gtshmmkjmf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guannengcc.top/Article/details/gtexczumow.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhffnolj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ivvv.top/Article/details/gtqunvvnel.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyannwpx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gtxogxckjq.html

[H10] 资源自动释放
来源：http://dali.cucudq.cn/Article/details/gtjojawrfh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhengqikj.top/Article/details/gtlnsncqtb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tianlin.xyz/Article/details/gttmosilal.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gtgesugfmb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtkeapxapz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gtytdlqwwu.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gtlctrwfcx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gtipwvszwz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtckaajamy.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtfqqrwssq.html

I. 正则表达式
来源：http://dali.zdqjudy.top/Article/details/gtraspfvlg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtjqbptgjc.html

[I01] 判断是否匹配
来源：http://dali.haohaochexian.top/Article/details/gtclggemyp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gtzzqokwtg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yongpay.top/Article/details/gtjyedzpbs.html

JS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtcalsllcb.html

TS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtabtlvcug.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zycfv.cn/Article/details/gtvmqwlomc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guannengcc.top/Article/details/gtjwyjyglb.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gtiqgaxyxw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tianlin.xyz/Article/details/gteyxnfycu.html

[I02] 提取所有匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwndmnli.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gtxxowdfqj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258.top/Article/details/gtkpczbboc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gtrrkuvifh.html

TS:   s.match(/\d+/g)
来源：http://dali.hnqzz.top/Article/details/gtlvmboamm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtksbbubzy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrymkrqjw.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtwtvahavk.html


<!-- 参考信息 -->