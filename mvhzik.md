代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gt2vrfmocos.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2xqfceuqy.html

Ruby: Dir.children("dir")
来源：http://dali.redwolf501.top/Article/details/gt2gjvnugqc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2igfjtecs.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gt2seqhapfn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2flrcyfky.html

PHP:  filesize("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2ocqvwszr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gt2jlrphoxx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gt2idwvsdra.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2wryawoad.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gt2tqxkccud.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2bzgmxkpq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.bjfxy.top/Article/details/gt2kdckpuex.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gt2ujudusls.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2snrubehi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2bxfzvxzx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2palxhbng.html

TS:   path.extname("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2peehpymh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenlongwang.top/Article/details/gt2orhiodqf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2xzjjpqvh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2dqpmjnlo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2smuqhhlw.html

[F11] 复制与移动文件
来源：http://dali.snrcjt.cn/Article/details/gt2fuyohzka.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2yklzlxvl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sweek.top/Article/details/gt2ufyuqllh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2cqfdtald.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2xqovenza.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shzxlz.cn/Article/details/gt2dazptqyx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.snrcjt.cn/Article/details/gt2zaculjdi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gt2wfdtxipv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.haohaochexian.top/Article/details/gt2nyklzhay.html

[F12] CSV 读写
来源：http://dali.c1oappe.top/Article/details/gt2cccairfb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuxming.cn/Article/details/gt2wwwzrqhp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gt2zwwwcghl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guannengcc.top/Article/details/gt2dkyksbre.html

TS:   // 同上
来源：http://dali.yuanzhike.top/Article/details/gt2lcmeuvnf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gt2lkzpngog.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnqzz.top/Article/details/gt2skdvkmic.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnqzz.top/Article/details/gt2papjwutz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.c1oappe.top/Article/details/gt2pogznwfn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ntinlirw.html

G. 面向对象
来源：http://dali.zhengqikj.top/Article/details/gt2uggolleg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2cexbgpxk.html

[G01] 定义类
来源：http://dali.wangdashe.top/Article/details/gt2texhrdce.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gt2dszdixqu.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2ohsjqdeg.html

JS:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ppticjig.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gt2zzovglyv.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2ymktzosc.html

Go:   type User struct { Name string }
来源：http://dali.yongpay.top/Article/details/gt2uiikauoi.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gt2ctuviqiv.html

C#:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2vqjsxbzl.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2vlneryvo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wycbglic.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gt2nunnkrfc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2qscoxmrv.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258888.top/Article/details/gt2pctnzipx.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gt2anfpichq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xinyue.icu/Article/details/gt2ucszvunp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gt2rgszfedg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2uabckncg.html

[G03] 实例属性
来源：http://dali.hnqzz.top/Article/details/gt2grfsntwn.html

Py:   self.name = "x"
来源：http://dali.snrcjt.cn/Article/details/gt2phofppcz.html

PHP:  public string $name = "x";
来源：http://dali.sxryk.cn/Article/details/gt2xdvmnwew.html

JS:   this.name = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2xfgtxhtn.html

TS:   name: string = "x";
来源：http://dali.hammf.cn/Article/details/gt2ihefxkum.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gt2gdcldsua.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dashuyun.cn/Article/details/gt2ifaldsbg.html

Ruby: @name = "x"
来源：http://dali.haohaochexian.top/Article/details/gt2pseerfkg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gt2fqxgjpkq.html

[G04] 定义方法
来源：http://dali.birdmap.top/Article/details/gt2sjqrcqzy.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gt2jircvzlh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gt2awhvfoxa.html

JS:   greet() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2saavnkxa.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gygujecv.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2cquxildl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2abhyquvk.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lmrynmqx.html

C#:   public string Greet() => Name;
来源：http://dali.yuxming.cn/Article/details/gt2dbgnvxam.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gt2uvtgjvjh.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gt2meyvbbqu.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2bmwlkxgu.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gt2fxnenwcr.html

TS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2bwklafms.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2oerhubjp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuanzx.com/Article/details/gt2rgjygoqe.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2vchxmbnh.html

C#:   class Admin : User {}
来源：http://dali.ivvv.top/Article/details/gt2hegkijvt.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gt2rmbxauss.html

Py:   def greet(self): return "admin"
来源：http://dali.yongpay.top/Article/details/gt2rtknfnob.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gt2lfsutoll.html

JS:   greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2enyraedj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2lvpzdhdl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2gilrzjfk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gt2xidnqopo.html

Ruby: def greet; "admin"; end
来源：http://dali.zycfv.cn/Article/details/gt2sirkwwpf.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj202588.top/Article/details/gt2uuuqfblo.html

[G07] 调用父类方法
来源：http://dali.9152youxi.cn/Article/details/gt2bfrbfhbz.html

Py:   super().greet()
来源：http://dali.ehwqpu.com/Article/details/gt2vlbhnuvi.html

PHP:  parent::greet();
来源：http://dali.ehwqpu.com/Article/details/gt2osvwweei.html

JS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gt2xjvurdjd.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gt2mhxlpbaf.html

Java: super.greet();
来源：http://dali.andypj.xyz/Article/details/gt2fsukifoy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuanzx.com/Article/details/gt2nyudkgua.html

Ruby: super
来源：http://dali.shuidangran.top/Article/details/gt2itoyehea.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gt2kllrbieo.html

[G08] 静态方法与属性
来源：http://dali.svipenyu.cn/Article/details/gt2ycgmtjvb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.andypj.xyz/Article/details/gt2yriecakj.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2afqfpcjj.html

JS:   static f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwxnebkp.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gt2ghzarjrd.html

Java: static void f() {}
来源：http://dali.sweek.top/Article/details/gt2jvohbldm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuxming.cn/Article/details/gt2zzoezwgo.html

Ruby: def self.f; end
来源：http://dali.iojbl.cn/Article/details/gt2etqembkt.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2atlzmlmr.html

[G09] 接口 / 抽象类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fwmugqzc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenzaomai.com/Article/details/gt2jfcwehjl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jiagoushi.top/Article/details/gt2odvxjdzq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2zimdsqmt.html

TS:   interface Shape { area(): number; }
来源：http://dali.ydzc1.top/Article/details/gt2yvhenbxj.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2xxocpfbo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangdashe.top/Article/details/gt2hghxkhhv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.smart0.xyz/Article/details/gt2wbmejzrp.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gt2adwsohbv.html

[G10] 访问控制
来源：http://dali.mhx1999.top/Article/details/gt2irlptyno.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zycfv.cn/Article/details/gt2affwoacf.html

PHP:  public / protected / private
来源：http://dali.gzhubu.top/Article/details/gt2zcvcvygy.html

JS:   #private 字段；其余公开
来源：http://dali.hfpthk.cn/Article/details/gt2altkugiz.html

TS:   public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gt2zvlxzqbn.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gt2hrkybaos.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.mhx1999.top/Article/details/gt2ahwpwlch.html

Ruby: public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gt2bobnrbcl.html

C#:   public / protected / private / internal
来源：http://dali.andypj.xyz/Article/details/gt2rnnykscr.html

[G11] getter / setter
来源：http://dali.0kj1m.cn/Article/details/gt2kajredkd.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gt2irocipkh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2yywjzuzj.html

JS:   get name() { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gt2rmlkmpeu.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gt2yhllqlzy.html

Java: public String getName() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2srjkimmn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gt2xfyubguq.html

Ruby: attr_accessor :name
来源：http://dali.sysykeji.top/Article/details/gt2trdfkurp.html

C#:   public string Name { get; set; }
来源：http://dali.xylfe.cn/Article/details/gt2xtagjfaa.html

[G12] 对象转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2hbwfkyyj.html

Py:   def __str__(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gt2okyptxys.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jrjyjcic.html

JS:   toString() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2snbksnbo.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khjgovlg.html

Java: @Override public String toString() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2eaneswcl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2dbgxbgbg.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gt2noebvpmr.html

C#:   public override string ToString() => Name;
来源：http://dali.smart0.xyz/Article/details/gt2agyhvjij.html

[G13] 判断对象类型
来源：http://dali.yonumen.top/Article/details/gt2tnxyhdth.html

Py:   isinstance(u, User)
来源：http://dali.mhx1999.top/Article/details/gt2yeqgoebh.html

PHP:  $u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gt2hvtudphl.html

JS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2bmmbxqvd.html

TS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gt2fzfzekqw.html

Java: u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2vqjtqmgb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258.top/Article/details/gt2fitflbki.html

Ruby: u.is_a?(User)
来源：http://dali.hysaishi.cn/Article/details/gt2zfozmedc.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gt2jgrrspjg.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gt2lbjufbfu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xinyue.icu/Article/details/gt2klojnspf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cheryme.top/Article/details/gt2sdatfggk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gt2npybujoi.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258888.top/Article/details/gt2adkhjpol.html

Java: record User(String name, int age) {}
来源：http://dali.aizwys.cn/Article/details/gt2zfbjulhl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydknnlpr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gt2cmtmpoyn.html

C#:   record User(string Name, int Age);
来源：http://dali.zhengqikj.top/Article/details/gt2yakzsxzb.html

[G15] 枚举
来源：http://dali.hammf.cn/Article/details/gt2wtcbxpcs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2sxwmexwb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yvedp.cn/Article/details/gt2nmdhyqzj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.svipenyu.cn/Article/details/gt2zlbpuvxs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jishcqld.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258888.top/Article/details/gt2skhaclsq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhixingplan.top/Article/details/gt2tnlkosvf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ficrxetk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gt2okmfgefw.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gt2alkzsveu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gt2gfcshfxi.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gt2ymrvcemq.html

JS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yrgeipet.html

TS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rkyvpxlw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yvedp.cn/Article/details/gt2xinunubs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gt2lymlaqpa.html

Ruby: obj.instance_variables
来源：http://dali.xinyue.icu/Article/details/gt2pqgonqrs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.havefunace.top/Article/details/gt2ouqlmfzu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2obwndtzp.html

H. 异常与错误处理
来源：http://dali.daxiang520.top/Article/details/gt2naxmfbct.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2ouizvxbq.html

[H01] try / catch 基础
来源：http://dali.yj20258.top/Article/details/gt2peuzswwl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gt2bzpeewpu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhixingplan.top/Article/details/gt2fmkfxpkh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gt2edvhveec.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ejlgevqj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gslhumgg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daxiang520.top/Article/details/gt2vacfczss.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gt2iwinctus.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gt2yuyldydb.html

[H02] finally / ensure 收尾
来源：http://dali.jqgfzy.top/Article/details/gt2jaokzmqh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhixingplan.top/Article/details/gt2mplpnhyp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2nvqhzrdt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2scpqlbjg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2flklyzbw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2axalyzjq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenlongwang.top/Article/details/gt2gndugmjy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gt2phiohxhs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2waigmzyc.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2swdlpjyc.html

Py:   raise ValueError("错误信息")
来源：http://dali.hysaishi.cn/Article/details/gt2escdvqwx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2vwfkujcc.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2jphodfyk.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2xkeubido.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2rcrxrldy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cdnleiting.top/Article/details/gt2kexclsjy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.bjfxy.top/Article/details/gt2mtlcyizm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2kumikcik.html

[H04] 自定义异常类型
来源：http://dali.0kj1m.cn/Article/details/gt2mbuurkgo.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gt2atcvnrht.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gt2hbxitkdt.html

JS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gt2wkoljdax.html

TS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gt2ydxcmwnm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gt2bzszzdxt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zycfv.cn/Article/details/gt2fufibxnq.html

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gt2ybbmujph.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gt2rvcghuow.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gt2vmdsmnoc.html

Py:   except ValueError as e:
来源：http://dali.jqgufenzy.top/Article/details/gt2dtikincp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hywenlv.cn/Article/details/gt2vixtxzqr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2fdyvzjmm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gt2rmgiufxs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nakkizyi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yonumen.top/Article/details/gt2lkrcztxa.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gt2rspensea.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gt2jnhkpnar.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aizwys.cn/Article/details/gt2taziqljq.html

Py:   value = d.get("k") or default
来源：http://dali.hammf.cn/Article/details/gt2kxoznnze.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gt2bkemfbra.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gt2pejytylo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gt2poqgmric.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shzxlz.cn/Article/details/gt2oucvcsro.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xziqi.cn/Article/details/gt2oynodqbo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zbkudher.html

C#:   obj?.A?.B ?? default
来源：http://dali.tianlin.xyz/Article/details/gt2zmxmyjdh.html

[H07] 断言
来源：http://dali.tanke756.top/Article/details/gt2vyngjvrc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jiagoushi.top/Article/details/gt2tufcwofo.html

PHP:  assert($x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2nuhfilzg.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gt2kyqnugmc.html

TS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2qpfpeufh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gt2mzapqkuy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gt2kznmdpvi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gt2ejqueuia.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2fslwzxub.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2spuqhhdd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yueranfly.top/Article/details/gt2hsduuxgy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gzhubu.top/Article/details/gt2gpuijimw.html

JS:   e.message;  e.stack
来源：http://dali.hammf.cn/Article/details/gt2cthsosbk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shuidangran.top/Article/details/gt2uyowzeoe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gt2pcczvalh.html

Go:   err.Error()
来源：http://dali.quarkkingdee.top/Article/details/gt2pemykixe.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigfzy.top/Article/details/gt2wnpfxidw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hammf.cn/Article/details/gt2nbdztawg.html

[H09] 带错误码的异常
来源：http://dali.ybcxt.top/Article/details/gt2qjoaeqrx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjvhiwqn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ivvv.top/Article/details/gt2gnojmeae.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sweek.top/Article/details/gt2hgljvmqi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tian-w.cn/Article/details/gt2uqieuhua.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ivvv.top/Article/details/gt2sclykzhd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhongyouzk.top/Article/details/gt2wqkkikua.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpiuhdcc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tianlin.xyz/Article/details/gt2bxqwhjvw.html

[H10] 资源自动释放
来源：http://dali.sysykeji.top/Article/details/gt2pekmtgha.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gt2ulwsvvdx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gt2xlglwoef.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gt2sgusayry.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gt2vmfjmgvz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wryrhwvv.html

Go:   defer f.Close()
来源：http://dali.hnxiangtu.top/Article/details/gt2qmxguvcj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guannengcc.top/Article/details/gt2qdhjhkaw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2isdnhqqe.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2bhiotmle.html

I. 正则表达式
来源：http://dali.jianghu66.top/Article/details/gt2dgeyakdr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2tpidupms.html

[I01] 判断是否匹配
来源：http://dali.jinqigufen.top/Article/details/gt2vpdggrfq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujqdfhuw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2erntfjzz.html

JS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gt2ykldibsb.html

TS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gt2txqkhvzz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fscwkief.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.havefunace.top/Article/details/gt2rcfbojtf.html

Ruby: s.match?(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nackjhtw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gt2ehccffyp.html

[I02] 提取所有匹配
来源：http://dali.zdqjudy.top/Article/details/gt2phfjsfxj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gt2nxascuxj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cdnleiting.top/Article/details/gt2ofnujphf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.havefunace.top/Article/details/gt2lmeqriyi.html

TS:   s.match(/\d+/g)
来源：http://dali.mhx1999.top/Article/details/gt2zzigwxxf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gt2qvfvxina.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gt2pruclnuw.html

Ruby: s.scan(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gt2ebczdhxv.html


<!-- 参考信息 -->