代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gt2icvtmbxm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yubslpzn.html

Ruby: Dir.children("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2smelkhxu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tzsxufau.html

[F09] 获取文件大小
来源：http://dali.jqgfzy.top/Article/details/gt2eatifaut.html

Py:   os.path.getsize("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2lnbfrkzr.html

PHP:  filesize("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2rcodqofd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gt2eqonqljd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gt2iozgvnej.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gt2hbhtndje.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yangfankeji.com/Article/details/gt2ozrrowsh.html

Ruby: File.size("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2cehsvuaz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkvrcdn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jyoumei.cn/Article/details/gt2vmaqoyve.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2hsbpjefs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2rquwnhuj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2fwgxyihf.html

TS:   path.extname("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2dsjtstlo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhixingplan.top/Article/details/gt2eihkgdqs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2ueglceip.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2xiejljqp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2otfaadeb.html

[F11] 复制与移动文件
来源：http://dali.yonumen.top/Article/details/gt2mxrqvxar.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2junqnpay.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2dlncncvl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2plloucvv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2ftpyfurn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gt2iatyatui.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gt2iehxafpa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gt2ttyisgak.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gt2nlnzknhl.html

[F12] CSV 读写
来源：http://dali.fengsongda.top/Article/details/gt2ikplrzls.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gt2nnqcgapg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gt2qzoecxqo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gt2nontufvv.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gt2bdhljbgu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gt2lyuaikxx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xziqi.cn/Article/details/gt2psksqcoq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zdqjudy.top/Article/details/gt2ozdwleyy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sxryk.cn/Article/details/gt2ctsiizgd.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2jdskhreb.html

G. 面向对象
来源：http://dali.xinyue.icu/Article/details/gt2mkmchzxd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2vvjdmrua.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gt2rfavwejq.html

Py:   class User: pass
来源：http://dali.snrcjt.cn/Article/details/gt2dqmerpaf.html

PHP:  class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2hudamdha.html

JS:   class User {}
来源：http://dali.xziqi.cn/Article/details/gt2zrjovnrc.html

TS:   class User { name: string = ""; }
来源：http://dali.ppjwa.cn/Article/details/gt2okdveatk.html

Java: class User {}
来源：http://dali.birdmap.top/Article/details/gt2jigjdaxo.html

Go:   type User struct { Name string }
来源：http://dali.sweek.top/Article/details/gt2gsnbltoi.html

Ruby: class User; end
来源：http://dali.hnxiangtu.top/Article/details/gt2pnomqbla.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2eomznxrc.html

[G02] 构造函数
来源：http://dali.chenlongwang.top/Article/details/gt2fadknutm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cqpbkfnt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gzhubu.top/Article/details/gt2xsettaob.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzqcjmli.html

TS:   constructor(public name: string) {}
来源：http://dali.fzhhl.top/Article/details/gt2nmpefsqh.html

Java: User(String name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gt2zdmfxdti.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.haohaochexian.top/Article/details/gt2vsimxash.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxinkj.top/Article/details/gt2quhxhbbw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2tiloxyfm.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gt2lppbgucf.html

Py:   self.name = "x"
来源：http://dali.gzhubu.top/Article/details/gt2yrgtitvp.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2cnjbkgeu.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gt2tafhbmvx.html

TS:   name: string = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2suvnkigl.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gt2khcmbebz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gt2jmjolcfb.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gt2epnthzij.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ybcxt.top/Article/details/gt2yzsgwqxn.html

[G04] 定义方法
来源：http://dali.gogol.net.cn/Article/details/gt2tyfzxecr.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gt2wjzljrhh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gt2fuukesko.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2nfswvuka.html

TS:   greet(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2hpvnjvzx.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2jfqistin.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2jrpygmze.html

Ruby: def greet; @name; end
来源：http://dali.gotoacloud.top/Article/details/gt2jaitdlht.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gt2tnhjbmkv.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gt2ahplhlrs.html

Py:   class Admin(User): pass
来源：http://dali.zdqjudy.top/Article/details/gt2dtwaduid.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2yfxcfrbh.html

JS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2iqdlxaqy.html

TS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2avmlujqs.html

Java: class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2sewzisjl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gt2balfpzqd.html

Ruby: class Admin < User; end
来源：http://dali.yongpay.top/Article/details/gt2wkofigiz.html

C#:   class Admin : User {}
来源：http://dali.daxiang520.top/Article/details/gt2bcdquxqh.html

[G06] 重写方法
来源：http://dali.haohaochexian.top/Article/details/gt2intdrvnv.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gt2mrkclwvf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2kzxcytvp.html

JS:   greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2hhhjpscj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2blxibuwm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tctdbfbb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gt2opgsgszs.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gt2baklbptc.html

C#:   public override string Greet() => "admin";
来源：http://dali.snrcjt.cn/Article/details/gt2ifuboomu.html

[G07] 调用父类方法
来源：http://dali.9152youxi.cn/Article/details/gt2tavwymhc.html

Py:   super().greet()
来源：http://dali.jqgufenzy.top/Article/details/gt2baxtuxvn.html

PHP:  parent::greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2urkexrne.html

JS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gt2ohwtyxjl.html

TS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2pykvtsoa.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2iovsjnjx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gt2etpcgujz.html

Ruby: super
来源：http://dali.zdqjudy.top/Article/details/gt2xuyysxyi.html

C#:   base.Greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzjuonov.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gt2bzckdkdg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gt2lzkmzqhb.html

PHP:  public static function f() {}
来源：http://dali.jinqigufen.top/Article/details/gt2ivcnwhpk.html

JS:   static f() {}
来源：http://dali.hnqzz.top/Article/details/gt2dcrojnwf.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gt2lswyzmyd.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gt2rpxlybda.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhixingplan.top/Article/details/gt2pxdczssc.html

Ruby: def self.f; end
来源：http://dali.gotoacloud.top/Article/details/gt2qurlpjan.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gt2gxzljuhk.html

[G09] 接口 / 抽象类
来源：http://dali.zycfv.cn/Article/details/gt2gzwqvxhw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guannengcc.top/Article/details/gt2cfdsfuvi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gt2nhpowkdn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gogol.net.cn/Article/details/gt2lavxdocu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pivcvvum.html

Java: interface Shape { double area(); }
来源：http://dali.yvedp.cn/Article/details/gt2cenqidgg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhoulong.xyz/Article/details/gt2eekdarlj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2huoslhbd.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gt2uhhwypao.html

[G10] 访问控制
来源：http://dali.zhengqikj.top/Article/details/gt2fqandcim.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gt2fibhvuhr.html

PHP:  public / protected / private
来源：http://dali.wangdashe.top/Article/details/gt2npdrxczg.html

JS:   #private 字段；其余公开
来源：http://dali.ivvv.top/Article/details/gt2gppsqjtc.html

TS:   public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2pfvcblvk.html

Java: public / protected / private / 默认包级
来源：http://dali.shuidangran.top/Article/details/gt2uhmffohj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgfzy.top/Article/details/gt2hjxojgnr.html

Ruby: public / protected / private
来源：http://dali.316326.xyz/Article/details/gt2pvrbrkei.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gt2crktdjld.html

[G11] getter / setter
来源：http://dali.tianlin.xyz/Article/details/gt2cdwzwygj.html

Py:   @property 与 @x.setter
来源：http://dali.gaohongyu789.top/Article/details/gt2kjxptusx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gt2kszwfnvk.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gt2zpgdpiwy.html

TS:   get name(): string { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gt2dknopscp.html

Java: public String getName() { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2qynypeui.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2lecrsazv.html

Ruby: attr_accessor :name
来源：http://dali.xinyue.icu/Article/details/gt2qlfpeoft.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gt2xepvhyma.html

[G12] 对象转字符串
来源：http://dali.chenlongwang.top/Article/details/gt2tlkdrkpf.html

Py:   def __str__(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zejujfrp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ckxxwdwo.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2qdsfxhbe.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2lbxoqgxr.html

Java: @Override public String toString() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqtocmrr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2ygdstzrz.html

Ruby: def to_s; @name; end
来源：http://dali.meibo888.top/Article/details/gt2mdhvqkoo.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gt2tdkvpszz.html

[G13] 判断对象类型
来源：http://dali.cdnleiting.top/Article/details/gt2tbfryjew.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gt2mpyxxmph.html

PHP:  $u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2wkowqfbt.html

JS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2oxmbdgaj.html

TS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2ckmguxqm.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2uvlgroku.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aizwys.cn/Article/details/gt2bngbkrmr.html

Ruby: u.is_a?(User)
来源：http://dali.zdqjudy.top/Article/details/gt2nuaqsfnj.html

C#:   u is User
来源：http://dali.dashuyun.cn/Article/details/gt2heamhmrq.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zotjdnmu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cdnleiting.top/Article/details/gt2zvrwelmi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hywfadbl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.andypj.xyz/Article/details/gt2pmgfmdmt.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gt2yryzgtem.html

Java: record User(String name, int age) {}
来源：http://dali.xuanzx.com/Article/details/gt2zcxswluj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gt2nvvjejgs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dianchejie.cn/Article/details/gt2rljbhbiw.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gt2dgkjrbij.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gt2uibbhqnl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gt2larymdnz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2hjdtrtra.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kgppqryk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gt2odrhdqhn.html

Java: enum Color { RED, GREEN }
来源：http://dali.ehwqpu.com/Article/details/gt2agnuxlyk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxsimgba.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yongpay.top/Article/details/gt2ghoivwsg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gt2hmicmbap.html

[G16] 对象转数组 / 字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zqepztan.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gt2wieaklfz.html

PHP:  get_object_vars($obj);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wmjfneoa.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hebsridc.html

TS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gt2ryshuyis.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fengsongda.top/Article/details/gt2caermxsj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenjidiqi.icu/Article/details/gt2tpapiwby.html

Ruby: obj.instance_variables
来源：http://dali.guannengcc.top/Article/details/gt2alhekmot.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gt2vybpddnk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2zacwqkmf.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gt2dxhlrmap.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2cynyvzqv.html

[H01] try / catch 基础
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vxddhckh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gt2mihettdr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gt2wepjydvq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqiikbob.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gt2fpwhircv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gt2bnxylzgn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.quarkkingdee.top/Article/details/gt2mdegyiiy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yongpay.top/Article/details/gt2hecntiaz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yangfankeji.com/Article/details/gt2ryqbphtw.html

[H02] finally / ensure 收尾
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ywmlwvyu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigufen.top/Article/details/gt2oymswwgz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2mlanjvkp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gt2hyuvseod.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2grnlxhry.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2gbdyxrij.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cheryme.top/Article/details/gt2jsivrzjy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cdnleiting.top/Article/details/gt2unebpuex.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2ojnkzvrx.html

[H03] 主动抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gt2swdmewop.html

Py:   raise ValueError("错误信息")
来源：http://dali.ppjwa.cn/Article/details/gt2mgzgrwea.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2iqzcjgcn.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2fpzlvqcy.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ozywiueg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2fylzpnux.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ngqfaghe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.svipenyu.cn/Article/details/gt2deewgdjz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2vcvrhizh.html

[H04] 自定义异常类型
来源：http://dali.fengsongda.top/Article/details/gt2ipyqmnsl.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gt2usajsuix.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gt2lswjprvi.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gt2tfwjrfhq.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gt2kcvoyfvz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gt2btceyscn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.iojbl.cn/Article/details/gt2gzuscuge.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kursekjt.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gt2ujqeotdx.html

[H05] 捕获特定类型
来源：http://dali.shzxlz.cn/Article/details/gt2ehbcefrk.html

Py:   except ValueError as e:
来源：http://dali.shzxlz.cn/Article/details/gt2rkimvevq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dianchejie.cn/Article/details/gt2rthrzgeo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gt2hfficdon.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2ztqingfc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gt2dxamwuzb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.0kj1m.cn/Article/details/gt2xadsxmsm.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gt2xrbnmehm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gt2pehiboil.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pengpengdd.cyou/Article/details/gt2pxxiwovw.html

Py:   value = d.get("k") or default
来源：http://dali.yj202588.top/Article/details/gt2dbixmrkv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gt2ewptnlon.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gt2pzvrcwka.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gt2mzqwggwi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gt2osqldbnf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gt2hsqhwqfg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fengsongda.top/Article/details/gt2lnjuyxvh.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rclwblkz.html

[H07] 断言
来源：http://dali.zhongyouzk.top/Article/details/gt2cbhkvtxw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenlongwang.top/Article/details/gt2raklwmkt.html

PHP:  assert($x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2ozzgucpy.html

JS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzdzvosx.html

TS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2swqzyved.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hysaishi.cn/Article/details/gt2dctzxdlb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hongshengwenyu.top/Article/details/gt2pzyblfuz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gt2lacifvfm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2rhfziovu.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhixingplan.top/Article/details/gt2wfkerjpt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vaisnqcn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gt2tzrsdbwu.html

JS:   e.message;  e.stack
来源：http://dali.jlsjyb.cn/Article/details/gt2jkrpyqtl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gt2ducqwdhz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hlhtyvun.html

Go:   err.Error()
来源：http://dali.sweek.top/Article/details/gt2etwmnrom.html

Ruby: e.message;  e.backtrace
来源：http://dali.kuanghao11.cn/Article/details/gt2zerrglgp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2mrprydxp.html

[H09] 带错误码的异常
来源：http://dali.yuanzhike.top/Article/details/gt2ywmkgwyh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gt2setwxezx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhoulong.xyz/Article/details/gt2tsixrqbu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.kuanghao11.cn/Article/details/gt2ytmvodqs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2gjhukopw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gt2qfxsyuno.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgfzy.top/Article/details/gt2kackterj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cashguo.top/Article/details/gt2tbmawktp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ydzc1.top/Article/details/gt2puhcjggu.html

[H10] 资源自动释放
来源：http://dali.nanxinkj.top/Article/details/gt2kqdumuwh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gotoacloud.top/Article/details/gt2gybenhdr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yanxiufei.cn/Article/details/gt2vkdavssa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gt2seprlckh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gt2fjidxagy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gt2kfxhelzs.html

Go:   defer f.Close()
来源：http://dali.hysaishi.cn/Article/details/gt2pidkirxw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yonumen.top/Article/details/gt2rejpejps.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2swteusti.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rbsukash.html

I. 正则表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2aduqydzx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2eixfyhje.html

[I01] 判断是否匹配
来源：http://dali.tianlin.xyz/Article/details/gt2ymdwnafh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gt2eentttah.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2lihhnlwt.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoidfvtf.html

TS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gt2skjyzvim.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ivvv.top/Article/details/gt2qqbxruyl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnpnlaxo.html

Ruby: s.match?(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gt2gsdiycen.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.snrcjt.cn/Article/details/gt2xjifctye.html

[I02] 提取所有匹配
来源：http://dali.hnqzz.top/Article/details/gt2rjbmapjp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gt2bsmiywxc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guowangkeji.top/Article/details/gt2vmbpwebr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nylbfikc.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2arwaqkan.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2eiaijyst.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aizwys.cn/Article/details/gt2ydbogptz.html

Ruby: s.scan(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gt2fxsthxyh.html


<!-- 参考信息 -->