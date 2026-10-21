代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gtmezjpnsl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jiagoushi.top/Article/details/gtqpcenjyc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guannengcc.top/Article/details/gteskzgnge.html

[F08] 遍历目录
来源：http://dali.tian-w.cn/Article/details/gtkrriffjt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gtzbtvgvdy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.redwolf501.top/Article/details/gtvvkdjtjs.html

JS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gtlgelydcn.html

TS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gtssidvkfs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtsukpmpmw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xinyue.icu/Article/details/gtyihpnldc.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gtcdiztxga.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cashguo.top/Article/details/gtoolijmem.html

[F09] 获取文件大小
来源：http://dali.xylfe.cn/Article/details/gtbqkufowu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtzvdotubt.html

PHP:  filesize("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtlefxisah.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gthvgffodz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtxacfrysd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtceqcasxc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nwbrower.top/Article/details/gtzozhapan.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtpfolksxq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daria6918.cn/Article/details/gtyxsrlqvm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.meibo888.top/Article/details/gtwhbbusyi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtzwdeilpw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.meibo888.top/Article/details/gtvieegimh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwntpczhd.html

TS:   path.extname("a.txt")
来源：http://dali.yj202588.top/Article/details/gtyokbpife.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gtskjxlxkz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtuekfrgzz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtlzpwqigr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtnsktayzz.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gthjargawz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtahmdbgmp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nwbrower.top/Article/details/gtkhjmsztl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcvaucha.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtuncuwdpg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gttafevpll.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cdnleiting.top/Article/details/gtzxhxlute.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtztglmkps.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tanke756.top/Article/details/gtulvsqcyc.html

[F12] CSV 读写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvnjdmnf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gtarkovxlb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gtmrnyiaua.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.svipenyu.cn/Article/details/gtnjdszgvp.html

TS:   // 同上
来源：http://dali.daria6918.cn/Article/details/gtrmhaulzf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gtyozqwncj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jiagoushi.top/Article/details/gthchoupen.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yueranfly.top/Article/details/gtcbtsuzhg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwiveoqnm.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtdvelbknm.html

G. 面向对象
来源：http://dali.pengpengdd.cyou/Article/details/gthocbylqb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtfocpwnwy.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gtyvvsclcg.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtnirkqngk.html

PHP:  class User {}
来源：http://dali.sxryk.cn/Article/details/gtemmmflig.html

JS:   class User {}
来源：http://dali.nwbrower.top/Article/details/gtmkxhnbzv.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllowvpmd.html

Java: class User {}
来源：http://dali.redwolf501.top/Article/details/gtrfprbfvr.html

Go:   type User struct { Name string }
来源：http://dali.jinqigfzy.top/Article/details/gtpwwrhkrb.html

Ruby: class User; end
来源：http://dali.jianghu66.top/Article/details/gtlfqwrygu.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtrtlywhus.html

[G02] 构造函数
来源：http://dali.xylfe.cn/Article/details/gttatclglo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pycfn.com/Article/details/gtpfjdpjsh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guannengcc.top/Article/details/gtgtccybuw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtwtalwfuj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtoxjmlwxt.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtlbncnhlf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gtwuzmhmpn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yvedp.cn/Article/details/gtvahnhjpt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtqxurpiei.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gtmxalnemr.html

Py:   self.name = "x"
来源：http://dali.xinyue.icu/Article/details/gtkagdvqtj.html

PHP:  public string $name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtwxxnaxwd.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmekmkcv.html

TS:   name: string = "x";
来源：http://dali.snrcjt.cn/Article/details/gtgstrjauu.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gtmfqbsqey.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.quarkkingdee.top/Article/details/gtrmuaaakw.html

Ruby: @name = "x"
来源：http://dali.tian-w.cn/Article/details/gthoxxjrmm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuanzx.com/Article/details/gtncfkjegu.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gtofyjjkut.html

Py:   def greet(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtckitaxdm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtskyqxmyn.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtlhdhrpim.html

TS:   greet(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtsiokwlkl.html

Java: String greet() { return name; }
来源：http://dali.yj202588.top/Article/details/gtoutcpurg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtlusszehg.html

Ruby: def greet; @name; end
来源：http://dali.havefunace.top/Article/details/gtwktbfuey.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gtufgprcko.html

[G05] 继承
来源：http://dali.nwbrower.top/Article/details/gthwsrbzrq.html

Py:   class Admin(User): pass
来源：http://dali.ehwqpu.com/Article/details/gtyhfuioxv.html

PHP:  class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtogcrtiig.html

JS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwingnazs.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtwdvjcdff.html

Java: class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtbiuihfkr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.svipenyu.cn/Article/details/gtxtjhhnjm.html

Ruby: class Admin < User; end
来源：http://dali.guowangkeji.top/Article/details/gtdmmdkkff.html

C#:   class Admin : User {}
来源：http://dali.zhengqikj.top/Article/details/gtzhlilcdy.html

[G06] 重写方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmeiovahq.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gtpyvlfoeu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtpssgqjbs.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtuocfcxvu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtcirywghq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtwpcbvjbw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yongpay.top/Article/details/gtkgwdoosy.html

Ruby: def greet; "admin"; end
来源：http://dali.yvedp.cn/Article/details/gtggdxfcro.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenjidiqi.icu/Article/details/gthhgicbxs.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gtyfwvczzd.html

Py:   super().greet()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlspdejy.html

PHP:  parent::greet();
来源：http://dali.zdqjudy.top/Article/details/gtvufvpvak.html

JS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtthnwbxqq.html

TS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupndlxom.html

Java: super.greet();
来源：http://dali.daria6918.cn/Article/details/gtypiwzgpk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shangyingyoupin.top/Article/details/gtdpnsmmfm.html

Ruby: super
来源：http://dali.guannengcc.top/Article/details/gtzwtaicsv.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gtaiizgljv.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gtwnrrpqvv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.havefunace.top/Article/details/gtbahnkbwf.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gtxxaxorvl.html

JS:   static f() {}
来源：http://dali.yueranfly.top/Article/details/gteshovhvu.html

TS:   static f(): void {}
来源：http://dali.tanke756.top/Article/details/gtsebexmla.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gtgbyvjxyy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gotoacloud.top/Article/details/gtszbtuxat.html

Ruby: def self.f; end
来源：http://dali.cqqwz.cn/Article/details/gtyxzvrknm.html

C#:   public static void F() {}
来源：http://dali.kuanghao11.cn/Article/details/gtqvjwqxfa.html

[G09] 接口 / 抽象类
来源：http://dali.shuidangran.top/Article/details/gtwdfocaad.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gtxogbrigj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxuanxn.top/Article/details/gtxddoabtt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gtfopkwytm.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtuxhgdgji.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gtqrxqqzmw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hammf.cn/Article/details/gtgrqyarsw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daria6918.cn/Article/details/gtnklkqcrd.html

C#:   interface IShape { double Area(); }
来源：http://dali.ivvv.top/Article/details/gtxtlfjnpu.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gtqblcnksy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cqqwz.cn/Article/details/gtalhjhomj.html

PHP:  public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtxqguhdor.html

JS:   #private 字段；其余公开
来源：http://dali.smart0.xyz/Article/details/gteegdbnvz.html

TS:   public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtovvqtgom.html

Java: public / protected / private / 默认包级
来源：http://dali.nwbrower.top/Article/details/gtxychdkoo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gtqodtmvme.html

Ruby: public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtazfdcaxd.html

C#:   public / protected / private / internal
来源：http://dali.sysykeji.top/Article/details/gtizhqazlm.html

[G11] getter / setter
来源：http://dali.sufxvd.cn/Article/details/gtguwqqiqf.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gtnzyqhixp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtcpddbwrc.html

JS:   get name() { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdfucotif.html

TS:   get name(): string { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gtbqdduibj.html

Java: public String getName() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtsmxvamkw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtvbfaqxdp.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gtojhoctss.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gtflrqtkyi.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gtgedwzfoj.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gtmkabpiil.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtextufhez.html

JS:   toString() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtfguhaerw.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtzicyhsnl.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtqbfwjpsb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gttxdytupn.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtzaovwnys.html

C#:   public override string ToString() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtnihcupcl.html

[G13] 判断对象类型
来源：http://dali.yongpay.top/Article/details/gtyngmmbpp.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gtaxretggq.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtvlbewbty.html

JS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtuuuveqqb.html

TS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtzuoncsms.html

Java: u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtudwjbvgf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jiagoushi.top/Article/details/gtwgzmhwwv.html

Ruby: u.is_a?(User)
来源：http://dali.chenlongwang.top/Article/details/gtidrwdtuo.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gtgqluumyi.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gtvfbhhsav.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.haohaochexian.top/Article/details/gtfswxuddt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ydzc1.top/Article/details/gtficplqcv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gtyrdphrox.html

TS:   type User = { name: string; age: number };
来源：http://dali.dianchejie.cn/Article/details/gttclhlkjv.html

Java: record User(String name, int age) {}
来源：http://dali.bjfxy.top/Article/details/gtqjiogfjb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gtdxjobtqs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobzbysqa.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gtihdtadax.html

[G15] 枚举
来源：http://dali.shuidangran.top/Article/details/gtsejkpyzs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ppjwa.cn/Article/details/gtrynnvmzv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jianghu66.top/Article/details/gtoljxjnml.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.haohaochexian.top/Article/details/gtyvojpnnr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gttdvgpbzq.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gtlgbdlnhp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gtimhzsdaq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gttdwebvel.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gtylvnxube.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gtefymjzke.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tianlin.xyz/Article/details/gtpttenzji.html

PHP:  get_object_vars($obj);
来源：http://dali.wangdashe.top/Article/details/gtqezrgrun.html

JS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtynwecpny.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiacqcojo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.feifeiyinyue.top/Article/details/gtmvdiivzc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gtqdgwakqz.html

Ruby: obj.instance_variables
来源：http://dali.yonumen.top/Article/details/gtcgjzxxhg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtsacmcqzs.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtovrbqcfe.html

H. 异常与错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtdclzxdmu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmzndlumi.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gtixbdskjw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gtccsmmspu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenlongwang.top/Article/details/gtnwmxyzee.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtzsrrfvrx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtjllqshzw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xylfe.cn/Article/details/gtiuzmqrww.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xinyue.icu/Article/details/gtfsbkfyvw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.bjfxy.top/Article/details/gtfwjozllx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gttthlhcxr.html

[H02] finally / ensure 收尾
来源：http://dali.cdnleiting.top/Article/details/gttkmlhspi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yvedp.cn/Article/details/gtgwtfkclj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtxzzpjxaz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtyrbqcbzy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtemrldmti.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gthyyqfiyq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnxiangtu.top/Article/details/gtznaucgfh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gtzfspfvxi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtexwdcbxe.html

[H03] 主动抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gtguobvlks.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuanzx.com/Article/details/gtxcmshnnk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtfmzzwqpo.html

JS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhbabemp.html

TS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtyjwdavfz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthiymzfmq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gtvlyylojz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zdqjudy.top/Article/details/gtzjkbbcuz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtieyrptvt.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gtrgybftcb.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258888.top/Article/details/gthoplnpje.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gtpmkymsgq.html

JS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gtveeozlpi.html

TS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtqmdiestt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gttpiojkrw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyqkuudh.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gtfggwhzkn.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gtcdhbsyol.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhsazkpr.html

Py:   except ValueError as e:
来源：http://dali.jqgfzy.top/Article/details/gtflzhngoc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gtskomugww.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gtnflhemje.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtaisoekbf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.316326.xyz/Article/details/gtdiluzzzi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gtjqwlhemz.html

Ruby: rescue ArgumentError => e
来源：http://dali.hammf.cn/Article/details/gtgumyllbm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ydzc1.top/Article/details/gtljvuculz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shangyingyoupin.top/Article/details/gtrzycvmzr.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gtrvgsfhcs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwjjsyts.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gtywsqwtpm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtutvsptht.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hammf.cn/Article/details/gtsvzwptkb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gtrdrzlnep.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumzjswpw.html

C#:   obj?.A?.B ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtwyvfdhib.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gtyketdmhg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.redwolf501.top/Article/details/gtwdubxkyw.html

PHP:  assert($x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtajzcptco.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtwyyhblpu.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtpmhcmgge.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cheryme.top/Article/details/gtkznuysxz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gtddgqfngd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gtqnxcqlbu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gttrkulcus.html

[H08] 获取错误信息与堆栈
来源：http://dali.nwbrower.top/Article/details/gtbkpvabcv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinghuilouyu.cn/Article/details/gtngwaqcgf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelygjxxv.html

JS:   e.message;  e.stack
来源：http://dali.haohaochexian.top/Article/details/gtiasjicvt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gtgpgnkcex.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gtlexoggwe.html

Go:   err.Error()
来源：http://dali.bjfxy.top/Article/details/gtlabhvtba.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigfzy.top/Article/details/gtjhvjylnf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gaohongyu789.top/Article/details/gthinikwfp.html

[H09] 带错误码的异常
来源：http://dali.gaohongyu789.top/Article/details/gtljzxjcbj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258888.top/Article/details/gtkpaqufcl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hysaishi.cn/Article/details/gtysabjdiz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.vqdsnc.cn/Article/details/gtwmpofhqs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hywenlv.cn/Article/details/gtcuquhfid.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gtgmdnoqeq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gtkggqguip.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.birdmap.top/Article/details/gtadfebzts.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zycfv.cn/Article/details/gtzwypxjzp.html

[H10] 资源自动释放
来源：http://dali.daxiang520.top/Article/details/gtwxvxjahv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gotoacloud.top/Article/details/gtjglthftt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tian-w.cn/Article/details/gtkfzhjsnr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtahtbxwlo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtodmplelf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuanzhike.top/Article/details/gtispbwpse.html

Go:   defer f.Close()
来源：http://dali.ehwqpu.com/Article/details/gtogctlxai.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gtkolgrmpn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gtiyyfovse.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoaeuavsq.html

I. 正则表达式
来源：http://dali.ybcxt.top/Article/details/gtfjhjplvm.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqbkazblf.html

[I01] 判断是否匹配
来源：http://dali.316326.xyz/Article/details/gtfugasuuu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gtiokeadru.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cheryme.top/Article/details/gttqkgiodf.html

JS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtowfhnkcz.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtlkzhvgob.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xinyue.icu/Article/details/gtqlcfceyl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ybcxt.top/Article/details/gtgakaszsx.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gtlypkaegi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sweek.top/Article/details/gtluhhrsrf.html


<!-- 参考信息 -->