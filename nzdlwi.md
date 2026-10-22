代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gt2wiirxmbr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgspbqco.html

Ruby: Dir.children("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hjrdqksn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2pjhlehxp.html

[F09] 获取文件大小
来源：http://dali.nwbrower.top/Article/details/gt2oqwkxdfk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2hpwyliqc.html

PHP:  filesize("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2sigccotc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gt2bfgpfqaw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gt2zkcjfjcy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ctbfdpaq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenjidiqi.icu/Article/details/gt2uhmosxuz.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2zzwbmofy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shzxlz.cn/Article/details/gt2ufoidpcu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cheryme.top/Article/details/gt2kthwklhe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2uhuuysqc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2vzjrrlew.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2qkczbdky.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2wyoxajdm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tanke756.top/Article/details/gt2asgelbaq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2xmsvliwr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2dffwctkz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rpdgcdci.html

[F11] 复制与移动文件
来源：http://dali.tianlin.xyz/Article/details/gt2khzwenab.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2hdxdkomb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2rfncsqzb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zmwfpwbh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2mtkqkijt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cdnleiting.top/Article/details/gt2znbspfvz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenjidiqi.icu/Article/details/gt2fmmgmctz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xeblgivu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yanxiufei.cn/Article/details/gt2ogjgyvpy.html

[F12] CSV 读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwioubbx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuxming.cn/Article/details/gt2imcqkokv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gt2lljiebht.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zdqjudy.top/Article/details/gt2cvbnhiln.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gt2dpsikzmp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.mhx1999.top/Article/details/gt2hzxcwyrs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gotoacloud.top/Article/details/gt2vmrcpbrx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sufxvd.cn/Article/details/gt2kthzafgk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.svipenyu.cn/Article/details/gt2qhiquadc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2bnseqeha.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gt2rqqpkzaa.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2plibvqdo.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gt2ytwdnozr.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gt2vudgovoc.html

PHP:  class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2gzdvljeb.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2aovehswj.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gt2orrrfvuv.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gt2fmvhcmwb.html

Go:   type User struct { Name string }
来源：http://dali.svipenyu.cn/Article/details/gt2tbqjeipy.html

Ruby: class User; end
来源：http://dali.nanxinkj.top/Article/details/gt2zvxcsnbt.html

C#:   class User {}
来源：http://dali.tian-w.cn/Article/details/gt2llyjbddb.html

[G02] 构造函数
来源：http://dali.xziqi.cn/Article/details/gt2gyywhzmm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhoulong.xyz/Article/details/gt2llqrjjep.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ojjlggzo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gt2hecbudzl.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258.top/Article/details/gt2asepcdqm.html

Java: User(String name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gt2ehmvfnvz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.vqdsnc.cn/Article/details/gt2ryuzzojk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aizwys.cn/Article/details/gt2bftgxbtr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.redwolf501.top/Article/details/gt2ioosztfn.html

[G03] 实例属性
来源：http://dali.hysaishi.cn/Article/details/gt2zqgjxpqh.html

Py:   self.name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gt2sswxbkvu.html

PHP:  public string $name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2poceinrp.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbxncvdw.html

TS:   name: string = "x";
来源：http://dali.cheryme.top/Article/details/gt2pqvmtbot.html

Java: private String name;
来源：http://dali.havefunace.top/Article/details/gt2dptarfik.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gt2obepibcs.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gt2syhhmxoi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daxiang520.top/Article/details/gt2qlievpvr.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gt2dswlhthu.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gt2rpgcimbr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2kdiwefxh.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2gajuhmbj.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2mvkxwsyp.html

Java: String greet() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2hrzlwkyj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gt2lhkoumrx.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2jiewvmnr.html

C#:   public string Greet() => Name;
来源：http://dali.tianlin.xyz/Article/details/gt2wypakckd.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gt2pakvucjq.html

Py:   class Admin(User): pass
来源：http://dali.nwbrower.top/Article/details/gt2bhgfdiku.html

PHP:  class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2awgzdcue.html

JS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2cmhagqop.html

TS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2dkjefoxl.html

Java: class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2zzpzitqa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tanke756.top/Article/details/gt2ttknhcqh.html

Ruby: class Admin < User; end
来源：http://dali.zycfv.cn/Article/details/gt2rrqbxmln.html

C#:   class Admin : User {}
来源：http://dali.iojbl.cn/Article/details/gt2azelgsim.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2lldjpsny.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gt2eedpovfz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kciztfnq.html

JS:   greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2palouiwa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjbgjcd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xkxxrpza.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gt2zowvzszs.html

Ruby: def greet; "admin"; end
来源：http://dali.havefunace.top/Article/details/gt2wrfldzrw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwkffdl.html

[G07] 调用父类方法
来源：http://dali.haohaochexian.top/Article/details/gt2ufpxyerl.html

Py:   super().greet()
来源：http://dali.zdqjudy.top/Article/details/gt2hfqmskzf.html

PHP:  parent::greet();
来源：http://dali.shzxlz.cn/Article/details/gt2hiugntyi.html

JS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gikymppn.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sumqblpm.html

Java: super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2dunebprh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnqzz.top/Article/details/gt2kwfxthse.html

Ruby: super
来源：http://dali.jqgufenzy.top/Article/details/gt2uuagftov.html

C#:   base.Greet();
来源：http://dali.guannengcc.top/Article/details/gt2hwjyrpod.html

[G08] 静态方法与属性
来源：http://dali.guannengcc.top/Article/details/gt2otyphgfl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fzhhl.top/Article/details/gt2pntsjgbm.html

PHP:  public static function f() {}
来源：http://dali.sweek.top/Article/details/gt2frirdgva.html

JS:   static f() {}
来源：http://dali.daxiang520.top/Article/details/gt2euadspbo.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ddppmzvx.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gt2vqnnvppo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gt2hgzwgslh.html

Ruby: def self.f; end
来源：http://dali.nwbrower.top/Article/details/gt2uccjutlr.html

C#:   public static void F() {}
来源：http://dali.cdnleiting.top/Article/details/gt2vbrlwbus.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258888.top/Article/details/gt2cbbxlxkn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.kuanghao11.cn/Article/details/gt2jhaejcle.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.svipenyu.cn/Article/details/gt2yiioxxat.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cashguo.top/Article/details/gt2sqezehuy.html

TS:   interface Shape { area(): number; }
来源：http://dali.9152youxi.cn/Article/details/gt2onpuaosn.html

Java: interface Shape { double area(); }
来源：http://dali.yuxming.cn/Article/details/gt2vvkwcdik.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ppjwa.cn/Article/details/gt2biadinrt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pycfn.com/Article/details/gt2hrgqkwog.html

C#:   interface IShape { double Area(); }
来源：http://dali.0kj1m.cn/Article/details/gt2ykksyxjp.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gt2iymrnowd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258.top/Article/details/gt2lmeedsry.html

PHP:  public / protected / private
来源：http://dali.tanke756.top/Article/details/gt2rlznixbr.html

JS:   #private 字段；其余公开
来源：http://dali.9152youxi.cn/Article/details/gt2oylltkqm.html

TS:   public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gt2przhctgq.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gt2pzkofoif.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pengpengdd.cyou/Article/details/gt2jscpwwho.html

Ruby: public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gt2pjdypcek.html

C#:   public / protected / private / internal
来源：http://dali.nwbrower.top/Article/details/gt2vitsiiet.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gt2rouqlywt.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gt2fnioawyx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2btfcogxp.html

JS:   get name() { return this._name; }
来源：http://dali.ivvv.top/Article/details/gt2ffmliwmr.html

TS:   get name(): string { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gt2tyaojgqk.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eoirtpvh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gt2effpiqcu.html

Ruby: attr_accessor :name
来源：http://dali.mhx1999.top/Article/details/gt2psoxldjn.html

C#:   public string Name { get; set; }
来源：http://dali.hysaishi.cn/Article/details/gt2qzxiyzkn.html

[G12] 对象转字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2miuydqza.html

Py:   def __str__(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gt2zpdgjhkq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2egggkovr.html

JS:   toString() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gt2fhlorpvw.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gt2rrcaxpkm.html

Java: @Override public String toString() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2tvxasubl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gt2dcjosjly.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gt2lftzduai.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gt2cnfzvlqw.html

[G13] 判断对象类型
来源：http://dali.xinyue.icu/Article/details/gt2vomthdvb.html

Py:   isinstance(u, User)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hljxfsvm.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2yttrozin.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2xljfudca.html

TS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2bppvhnlt.html

Java: u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2vhyxubsv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhbntkrf.html

Ruby: u.is_a?(User)
来源：http://dali.jiagoushi.top/Article/details/gt2lsdlnapc.html

C#:   u is User
来源：http://dali.cucudq.cn/Article/details/gt2uywxhpmw.html

[G14] 数据类 / record
来源：http://dali.jinqigufen.top/Article/details/gt2vkiwjrmx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hfpthk.cn/Article/details/gt2ytucbkgv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxinkj.top/Article/details/gt2baojwgfn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sxryk.cn/Article/details/gt2fduvefnl.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jilkelrl.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2rmqopoom.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gt2crxpoesk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xylfe.cn/Article/details/gt2zizrirji.html

C#:   record User(string Name, int Age);
来源：http://dali.fzhhl.top/Article/details/gt2itvlivdb.html

[G15] 枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2omcxfbjq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gt2nmvufbej.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nwbrower.top/Article/details/gt2dddkqvln.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgufenzy.top/Article/details/gt2ukxqxojj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gt2zviwmehs.html

Java: enum Color { RED, GREEN }
来源：http://dali.zycfv.cn/Article/details/gt2zqnmlhbq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.svipenyu.cn/Article/details/gt2iwwgqikp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gt2jonlrrlh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gt2cshzgesh.html

[G16] 对象转数组 / 字典
来源：http://dali.iojbl.cn/Article/details/gt2xuhjbslg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkewkpb.html

PHP:  get_object_vars($obj);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gmsartov.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2gliatawd.html

TS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2wjnknufp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gogol.net.cn/Article/details/gt2nnphctqc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ybcxt.top/Article/details/gt2jtqhxkvb.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2epgdqetc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gt2gnodnprz.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2ketjksfh.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gt2ftkmkbdn.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2dbeegefz.html

[H01] try / catch 基础
来源：http://dali.zycfv.cn/Article/details/gt2fiahxrnx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gt2jqlsxjwk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuanzx.com/Article/details/gt2thzsjxeu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gt2rgmtyjdv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gt2dgatxvly.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ybcxt.top/Article/details/gt2fnjhzeku.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.birdmap.top/Article/details/gt2mtitobrx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gt2rmcnodcs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jlsjyb.cn/Article/details/gt2pnmnwefh.html

[H02] finally / ensure 收尾
来源：http://dali.yangfankeji.com/Article/details/gt2xipxucox.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gt2egiauqup.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2vmsjzegb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vqtkuhgt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2cayoqeqy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2xxijqmqp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gotoacloud.top/Article/details/gt2plohshkw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.0kj1m.cn/Article/details/gt2gugbhakj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zpalzxbk.html

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gt2hcjvoxql.html

Py:   raise ValueError("错误信息")
来源：http://dali.cheryme.top/Article/details/gt2afkhykwz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2tcselhzy.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mypdqyrs.html

TS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2ydetcytq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2twihzedo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fzhhl.top/Article/details/gt2bdinzdcr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xziqi.cn/Article/details/gt2lkfxxbuo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2frpxpeek.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gt2zsrvljoq.html

Py:   class MyError(Exception): pass
来源：http://dali.zycfv.cn/Article/details/gt2svsvozkd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gt2hnljiabt.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gt2dxhqvguo.html

TS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gt2suqhlvcr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gt2kdzteezb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gt2bogrtdqf.html

Ruby: class MyError < StandardError; end
来源：http://dali.smart0.xyz/Article/details/gt2ccuerfis.html

C#:   class MyException : Exception {}
来源：http://dali.bjfxy.top/Article/details/gt2yijqomcf.html

[H05] 捕获特定类型
来源：http://dali.zycfv.cn/Article/details/gt2qxtesbzx.html

Py:   except ValueError as e:
来源：http://dali.xuetiantiany.cn/Article/details/gt2dsdhajzf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hysaishi.cn/Article/details/gt2nytuwvnk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gt2itvxisad.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oceqrigd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2kmpffzzd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yonumen.top/Article/details/gt2jtxakozb.html

Ruby: rescue ArgumentError => e
来源：http://dali.aizwys.cn/Article/details/gt2qduvnnbs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuanzhike.top/Article/details/gt2qleaokqz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gt2pigmspza.html

Py:   value = d.get("k") or default
来源：http://dali.chenlongwang.top/Article/details/gt2ywrnsayq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gt2bktdqezf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gt2daoydprr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gt2afzomnxm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sysykeji.top/Article/details/gt2izropovk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wjoqswic.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtkqmcxv.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gt2xquxcjrs.html

[H07] 断言
来源：http://dali.tianlin.xyz/Article/details/gt2glnnljrg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gt2pmolgfyd.html

PHP:  assert($x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2ilgvypdx.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2qvzlzdtk.html

TS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2iivuyext.html

Java: assert x > 0 : "必须为正";
来源：http://dali.316326.xyz/Article/details/gt2olmicvqq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2crhnajrf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gotoacloud.top/Article/details/gt2bmpfyyvk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gt2dmsmeyqs.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gt2ylurcnlf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.birdmap.top/Article/details/gt2iqbvhmna.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shangyingyoupin.top/Article/details/gt2rjfnrmfa.html

JS:   e.message;  e.stack
来源：http://dali.chenzaomai.com/Article/details/gt2yelehkag.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qxkgmyyt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yvedp.cn/Article/details/gt2rcfwugps.html

Go:   err.Error()
来源：http://dali.jianghu66.top/Article/details/gt2ctwhnyye.html

Ruby: e.message;  e.backtrace
来源：http://dali.guowangkeji.top/Article/details/gt2mvimcfzh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zvxykxgj.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gt2sidizptf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gt2jtqzkcjx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj202588.top/Article/details/gt2myqegwfo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daxiang520.top/Article/details/gt2imzditdx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hysaishi.cn/Article/details/gt2jmxufydb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigufen.top/Article/details/gt2egexijva.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gt2jpqpgmlh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgufenzy.top/Article/details/gt2zcndvusu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gt2lekvpfff.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2snclznyt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jlsjyb.cn/Article/details/gt2dikayvjo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ppjwa.cn/Article/details/gt2dzbqikrt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gt2fdwhwhpz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gt2sfxkkdlw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gt2dmhznzrb.html

Go:   defer f.Close()
来源：http://dali.svipenyu.cn/Article/details/gt2ppsvvobr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gt2dxqkeizf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2ekxsypwv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2zcndzeoh.html

I. 正则表达式
来源：http://dali.meibo888.top/Article/details/gt2jasddpwk.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2vydtsrmg.html

[I01] 判断是否匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2qyfxaryk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2ibwhosaj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj202588.top/Article/details/gt2zgsuwxfr.html

JS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gt2wotpojlu.html

TS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gt2faezudmz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gt2pzmejnrk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ivvv.top/Article/details/gt2fhgcbsdq.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gt2xwrwhyii.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gt2juhrecwh.html

[I02] 提取所有匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2lfjxtgnk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gt2ggnsjggx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gt2wclncyim.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aibaodan.cn/Article/details/gt2zxiufang.html

TS:   s.match(/\d+/g)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gtqesich.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2qwfhofkc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj202588.top/Article/details/gt2evwsrngp.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gt2edpfdspe.html


<!-- 参考信息 -->