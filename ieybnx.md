代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gt2wpteblfl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zycfv.cn/Article/details/gt2vlajpmcy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.quarkkingdee.top/Article/details/gt2xdsmjdpn.html

[F08] 遍历目录
来源：http://dali.yj202588.top/Article/details/gt2idfaidki.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yueranfly.top/Article/details/gt2sbnadfpd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xylfe.cn/Article/details/gt2nptjsbvo.html

JS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2vbocupib.html

TS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gt2cuqwajhv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ritzxrcj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2saywtvcl.html

Ruby: Dir.children("dir")
来源：http://dali.tanke756.top/Article/details/gt2dllpnfne.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zycfv.cn/Article/details/gt2yfxmmcrt.html

[F09] 获取文件大小
来源：http://dali.zhongyouzk.top/Article/details/gt2fcklvzbl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pmwbdnjy.html

PHP:  filesize("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2ebugtcuy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gt2tflvyyvw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gt2rnidxsjo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2siyparkp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gt2wksgtoam.html

Ruby: File.size("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2lbodieto.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfzfuyrs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ybcxt.top/Article/details/gt2iypcraqa.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2ybacpgqc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2jkbfaduo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2qanhivmk.html

TS:   path.extname("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2avgyyyto.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hysaishi.cn/Article/details/gt2kulkccjd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2zdhptesk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2cdvgrrbd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2kuoyloqn.html

[F11] 复制与移动文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gggoluuk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2exmnjqfu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fzhhl.top/Article/details/gt2bewushdp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2mrtcuxza.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2zulvjodt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.316326.xyz/Article/details/gt2ilkoggyp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cdnleiting.top/Article/details/gt2yfnnnygq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2tjdfuizs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.0kj1m.cn/Article/details/gt2fvwukbwl.html

[F12] CSV 读写
来源：http://dali.gaohongyu789.top/Article/details/gt2rcpbccmn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.bjfxy.top/Article/details/gt2ehabjilq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.smart0.xyz/Article/details/gt2ofzynbje.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgufenzy.top/Article/details/gt2nnosfrni.html

TS:   // 同上
来源：http://dali.gogol.net.cn/Article/details/gt2kjunfnzd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daxiang520.top/Article/details/gt2fgxgnwfi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangdashe.top/Article/details/gt2hchsmwjt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.havefunace.top/Article/details/gt2gwnzsnrt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangdashe.top/Article/details/gt2snwtzsdw.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2ffwavube.html

G. 面向对象
来源：http://dali.aizwys.cn/Article/details/gt2oonypsgj.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2jxvbclay.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gt2nfeigyxb.html

Py:   class User: pass
来源：http://dali.feifeiyinyue.top/Article/details/gt2shcalzpp.html

PHP:  class User {}
来源：http://dali.yongpay.top/Article/details/gt2nkiihehl.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2ftccspep.html

TS:   class User { name: string = ""; }
来源：http://dali.tanke756.top/Article/details/gt2krxbvtta.html

Java: class User {}
来源：http://dali.aizwys.cn/Article/details/gt2czoiujpv.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gt2forxhzmc.html

Ruby: class User; end
来源：http://dali.hammf.cn/Article/details/gt2ozdhself.html

C#:   class User {}
来源：http://dali.cashguo.top/Article/details/gt2ymokzuuq.html

[G02] 构造函数
来源：http://dali.hnxiangtu.top/Article/details/gt2wvrgddum.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ivvv.top/Article/details/gt2ukqtfpog.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gt2jkhrxyci.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gt2dcgzzfzl.html

TS:   constructor(public name: string) {}
来源：http://dali.iojbl.cn/Article/details/gt2wbbqqxot.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jfqtnrao.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gt2tidbugkr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sxryk.cn/Article/details/gt2boxjzbhh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gt2wworvkii.html

[G03] 实例属性
来源：http://dali.9152youxi.cn/Article/details/gt2bfvesawh.html

Py:   self.name = "x"
来源：http://dali.daxiang520.top/Article/details/gt2ynwqxkel.html

PHP:  public string $name = "x";
来源：http://dali.redwolf501.top/Article/details/gt2jqaionah.html

JS:   this.name = "x";
来源：http://dali.xylfe.cn/Article/details/gt2zwiixxym.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gt2emsgnfqi.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gt2jsruewxq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gt2dhirtqih.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gt2aktwwryr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2ktixwsnu.html

[G04] 定义方法
来源：http://dali.cqqwz.cn/Article/details/gt2igiulvtv.html

Py:   def greet(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gt2fvabdhno.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gt2ehepriqb.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxpdvkhe.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2ixghqlyf.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2nyoveboz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gt2sfhtbesa.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bbrnqvvw.html

C#:   public string Greet() => Name;
来源：http://dali.cqqwz.cn/Article/details/gt2vyvygyrh.html

[G05] 继承
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wqgetfmu.html

Py:   class Admin(User): pass
来源：http://dali.cucudq.cn/Article/details/gt2dgyepfhu.html

PHP:  class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2njlzdcla.html

JS:   class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2xntwuwey.html

TS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hxvnmjvs.html

Java: class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2xqvgqbck.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gaohongyu789.top/Article/details/gt2dlifvxwc.html

Ruby: class Admin < User; end
来源：http://dali.tianlin.xyz/Article/details/gt2yghsobxd.html

C#:   class Admin : User {}
来源：http://dali.ppjwa.cn/Article/details/gt2nswxuwul.html

[G06] 重写方法
来源：http://dali.nwbrower.top/Article/details/gt2poslowtv.html

Py:   def greet(self): return "admin"
来源：http://dali.dashuyun.cn/Article/details/gt2lgknseav.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2jygsbpyf.html

JS:   greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gt2lpkrxyyh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2wpufraag.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2bbbwkwni.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.quarkkingdee.top/Article/details/gt2vdglyhch.html

Ruby: def greet; "admin"; end
来源：http://dali.vqdsnc.cn/Article/details/gt2npujwciv.html

C#:   public override string Greet() => "admin";
来源：http://dali.meibo888.top/Article/details/gt2mkqfujaf.html

[G07] 调用父类方法
来源：http://dali.nwbrower.top/Article/details/gt2zxcxbwlz.html

Py:   super().greet()
来源：http://dali.9152youxi.cn/Article/details/gt2uraawbzp.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2phpioavm.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gt2wbfagewm.html

TS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gt2doygouwt.html

Java: super.greet();
来源：http://dali.tanke756.top/Article/details/gt2gmmqjujc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cashguo.top/Article/details/gt2ewskwhvt.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gt2akhciwag.html

C#:   base.Greet();
来源：http://dali.havefunace.top/Article/details/gt2ovmzlqff.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gt2oghlcals.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gt2djbyjtwv.html

PHP:  public static function f() {}
来源：http://dali.gotoacloud.top/Article/details/gt2mkhgcjgo.html

JS:   static f() {}
来源：http://dali.hysaishi.cn/Article/details/gt2kycxeqpg.html

TS:   static f(): void {}
来源：http://dali.hfpthk.cn/Article/details/gt2cxuyxvmp.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gt2ispqchfk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yonumen.top/Article/details/gt2wwjenetl.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gt2jokilivn.html

C#:   public static void F() {}
来源：http://dali.hnqzz.top/Article/details/gt2kdkjocom.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gt2iliipzie.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yongpay.top/Article/details/gt2gvibpipl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2blyxeptz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oengmtcx.html

TS:   interface Shape { area(): number; }
来源：http://dali.hywenlv.cn/Article/details/gt2qgnmylfk.html

Java: interface Shape { double area(); }
来源：http://dali.guannengcc.top/Article/details/gt2uazprkrh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.redwolf501.top/Article/details/gt2uxznwzdg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.haohaochexian.top/Article/details/gt2gwepsyzk.html

C#:   interface IShape { double Area(); }
来源：http://dali.svipenyu.cn/Article/details/gt2axjaucoe.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gt2iyopwsyn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.c1oappe.top/Article/details/gt2comoephz.html

PHP:  public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2faglfbhn.html

JS:   #private 字段；其余公开
来源：http://dali.kuanghao11.cn/Article/details/gt2qhvmweus.html

TS:   public / protected / private
来源：http://dali.xziqi.cn/Article/details/gt2dmraicvs.html

Java: public / protected / private / 默认包级
来源：http://dali.jiagoushi.top/Article/details/gt2ztvoppzd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tanke756.top/Article/details/gt2keekkgae.html

Ruby: public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gt2mkrqfhxe.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gt2tstvnvcl.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gt2ddywdcir.html

Py:   @property 与 @x.setter
来源：http://dali.jyoumei.cn/Article/details/gt2jetammdo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2yxhsmlts.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gt2ebopazko.html

TS:   get name(): string { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gt2zmpywsxq.html

Java: public String getName() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2srapysaz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gt2zhdkdypb.html

Ruby: attr_accessor :name
来源：http://dali.tanke756.top/Article/details/gt2pkxenguz.html

C#:   public string Name { get; set; }
来源：http://dali.gogol.net.cn/Article/details/gt2lkuqfhzt.html

[G12] 对象转字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2xgwhmhil.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gt2ifhtwkvt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gt2uxuimnmo.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2bqzqsnew.html

TS:   toString(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2bflszvpc.html

Java: @Override public String toString() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2skceqznj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2joyrhhtu.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gt2oqwbzgxf.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gt2jwunczye.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gt2qwmwwpem.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfptqumx.html

PHP:  $u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2yxxjjkzt.html

JS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2pblnzziy.html

TS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2ufccplod.html

Java: u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gt2talzewmg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hysaishi.cn/Article/details/gt2uexnxsqy.html

Ruby: u.is_a?(User)
来源：http://dali.ydzc1.top/Article/details/gt2woewvgav.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gt2wnpsrlqq.html

[G14] 数据类 / record
来源：http://dali.hysaishi.cn/Article/details/gt2khpyaqud.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hongshengwenyu.top/Article/details/gt2uykddqmi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.bjfxy.top/Article/details/gt2ycyudwep.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuxming.cn/Article/details/gt2uddggfwp.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhixingplan.top/Article/details/gt2cwhijsmd.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zniqtnjp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.andypj.xyz/Article/details/gt2tbreaysg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gt2tpknlaeo.html

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gt2dxpglztr.html

[G15] 枚举
来源：http://dali.jiagoushi.top/Article/details/gt2snsiezdq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuanzx.com/Article/details/gt2idvlescm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yvedp.cn/Article/details/gt2frjjzbil.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.316326.xyz/Article/details/gt2ctsqrcpr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2kiligblb.html

Java: enum Color { RED, GREEN }
来源：http://dali.yangfankeji.com/Article/details/gt2orcvckye.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gzhubu.top/Article/details/gt2launsykh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gt2bjzyhxoc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aeeabjpw.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gt2vwhgzmfu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gt2znhowtcy.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gt2eqkzyrvu.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2vlosvxbk.html

TS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2otffpemf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2simfviye.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.vqdsnc.cn/Article/details/gt2qehdzrkm.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gt2tvdliaue.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gt2yfupcfpi.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2wavksluj.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gt2oompxkud.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2vxcqbzvk.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gt2jerhaqpy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangdashe.top/Article/details/gt2jhfwofvj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gt2agroemqn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2txqhmlic.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gt2dmthqnmc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tanke756.top/Article/details/gt2cwoymvcu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdeeslh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2ddnaftgj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gt2iixtierk.html

[H02] finally / ensure 收尾
来源：http://dali.snrcjt.cn/Article/details/gt2ybblenlo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.0kj1m.cn/Article/details/gt2obukupue.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2zjsitakp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2qnltuqwl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2ormizoxt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2rkidbcyy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gt2yiwznsdd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hysaishi.cn/Article/details/gt2mwhvhtyn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2ujaxzmsq.html

[H03] 主动抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gt2mdgufnbi.html

Py:   raise ValueError("错误信息")
来源：http://dali.jiagoushi.top/Article/details/gt2eytrmjqo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2qbnvpzia.html

JS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2ohamufhs.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2aogcoblz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2wnjtdedu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.vqdsnc.cn/Article/details/gt2cvizoeig.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuetiantiany.cn/Article/details/gt2rwsldwjx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2qvnkvkjj.html

[H04] 自定义异常类型
来源：http://dali.tanke756.top/Article/details/gt2asnufoih.html

Py:   class MyError(Exception): pass
来源：http://dali.zdqjudy.top/Article/details/gt2ojatbczy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gt2byanuwck.html

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gt2rpranjoa.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yudatdrc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gt2fvqonbrk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gt2giwszcvw.html

Ruby: class MyError < StandardError; end
来源：http://dali.xinyue.icu/Article/details/gt2wyyekqen.html

C#:   class MyException : Exception {}
来源：http://dali.jianghu66.top/Article/details/gt2yhzqhqje.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gt2oklknvnv.html

Py:   except ValueError as e:
来源：http://dali.shangyingyoupin.top/Article/details/gt2xovnnefi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gotoacloud.top/Article/details/gt2nqohfzyp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2jempqfvg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gt2itzdimqv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2sizlsjwt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gt2fyitlbrz.html

Ruby: rescue ArgumentError => e
来源：http://dali.hammf.cn/Article/details/gt2wpbvobpw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2mnwxfcph.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gt2uncfbewl.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gt2bjtrkvtn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gt2vmbheecg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gt2xlbcekrs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gt2uqcfqezb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gt2fjxuybhg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gt2fcnprbdd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.svipenyu.cn/Article/details/gt2ylwvssrm.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2lvzsjtzt.html

[H07] 断言
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdfsmlcw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gzhubu.top/Article/details/gt2pefxrgeu.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2qolbmutz.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gt2svgodvns.html

TS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2drpojdfx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhengqikj.top/Article/details/gt2pksedcqz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.c1oappe.top/Article/details/gt2sniyiiyc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jyoumei.cn/Article/details/gt2jwewbpze.html

C#:   Debug.Assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2xcaaktwb.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gt2qbmgjonj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sweek.top/Article/details/gt2bzzmhypp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fengsongda.top/Article/details/gt2pbeyybej.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gt2cmblpnkt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gt2uwhozloz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hongshengwenyu.top/Article/details/gt2xdyezsnh.html

Go:   err.Error()
来源：http://dali.ppjwa.cn/Article/details/gt2lywarfbp.html

Ruby: e.message;  e.backtrace
来源：http://dali.mhx1999.top/Article/details/gt2obffscrr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gt2rdtkprmb.html

[H09] 带错误码的异常
来源：http://dali.jyoumei.cn/Article/details/gt2gcateekv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qxirjvdh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jlsjyb.cn/Article/details/gt2vluhhrrb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hfpthk.cn/Article/details/gt2guwxleak.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lamiwjtn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zdqjudy.top/Article/details/gt2kdvtgfhq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuanzhike.top/Article/details/gt2nkbmrlvr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xylfe.cn/Article/details/gt2cqhkuork.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gt2ufdlytvp.html

[H10] 资源自动释放
来源：http://dali.cdnleiting.top/Article/details/gt2peezkweb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gt2pbutfvkf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.haohaochexian.top/Article/details/gt2xblldcnn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gt2uptmtdwe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gt2wwayagef.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cdnleiting.top/Article/details/gt2gtabyiil.html

Go:   defer f.Close()
来源：http://dali.daxiang520.top/Article/details/gt2weieytho.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gt2kcxxtppd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2sntsttjt.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2heowjsqa.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gt2dnalfzbq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2rrkqifdp.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gt2gmewyqqp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gt2teopzcao.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cucudq.cn/Article/details/gt2bjnbftej.html

JS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gt2lcjljgqa.html

TS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gt2biodytxu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gt2hnluqyhj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cheryme.top/Article/details/gt2ukdjnwbd.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gt2qbzmwtzt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tgadapuc.html


<!-- 参考信息 -->