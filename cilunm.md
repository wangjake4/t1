代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtcyrhjrkh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtmhtulasb.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gtghdumytm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhengqikj.top/Article/details/gtxomminqf.html

[F09] 获取文件大小
来源：http://dali.yj20258888.top/Article/details/gtqrmxjhen.html

Py:   os.path.getsize("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtecvzzhwa.html

PHP:  filesize("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtobkuwxmo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gtkgzazydz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtewgsutvm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtsdmckjis.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gtsqcrblks.html

Ruby: File.size("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtwanlczol.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.redwolf501.top/Article/details/gtjyddmpva.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.birdmap.top/Article/details/gtqpiwlais.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gttlabmwmd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtfuvojxlc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtofygxgze.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtlfjsmfrb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xziqi.cn/Article/details/gttjgmzmaz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtaflvprcc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtqhrzdpgz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtrydtwgxq.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gtzhffuskd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gteagjsqks.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtrvawbgiw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtqcdsidii.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtlhflftda.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gtujdwcrws.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.bjfxy.top/Article/details/gtrejqomqg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtqwgvcqek.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gtykezsjdq.html

[F12] CSV 读写
来源：http://dali.shanyushiyangtech.top/Article/details/gtpppeopbz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nwbrower.top/Article/details/gtkkljeium.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tian-w.cn/Article/details/gtuhisarac.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zdqjudy.top/Article/details/gtynljukwl.html

TS:   // 同上
来源：http://dali.sxryk.cn/Article/details/gttrndumhn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yangfankeji.com/Article/details/gtixwyaqus.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sweek.top/Article/details/gttbexyfyw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ehwqpu.com/Article/details/gtnhafgemx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwyvbkfz.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtbopkkwbb.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gtcsfjmiyt.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtyuhbxlfj.html

[G01] 定义类
来源：http://dali.dianchejie.cn/Article/details/gteszpyoyd.html

Py:   class User: pass
来源：http://dali.jqgfzy.top/Article/details/gtegzyqplu.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gtswxacarn.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtijmhxwyl.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gtgoinkglz.html

Java: class User {}
来源：http://dali.sweek.top/Article/details/gtsciowhso.html

Go:   type User struct { Name string }
来源：http://dali.zhengqikj.top/Article/details/gtatjgdwva.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gtfdainral.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtxfkoytgi.html

[G02] 构造函数
来源：http://dali.yonumen.top/Article/details/gteznednji.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xinyue.icu/Article/details/gtxigxvnvn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnxiangtu.top/Article/details/gtbbriatwy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gttdyvraod.html

TS:   constructor(public name: string) {}
来源：http://dali.fzhhl.top/Article/details/gtmiymwonb.html

Java: User(String name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtpagakwkv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jlsjyb.cn/Article/details/gtyrtscouu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcercwbyo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtfoffiwbo.html

[G03] 实例属性
来源：http://dali.fzhhl.top/Article/details/gtcrfiulbg.html

Py:   self.name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtdtweheqv.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtzecdprst.html

JS:   this.name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtzpuhsyxu.html

TS:   name: string = "x";
来源：http://dali.hnqzz.top/Article/details/gtosstuuct.html

Java: private String name;
来源：http://dali.gzhubu.top/Article/details/gtqwslkrep.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gtewgdgcum.html

Ruby: @name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbrzausp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ydzc1.top/Article/details/gtxcsfcwtl.html

[G04] 定义方法
来源：http://dali.havefunace.top/Article/details/gtfncmsyng.html

Py:   def greet(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gtvcanggdf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtxvxzlzap.html

JS:   greet() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gthqztblly.html

TS:   greet(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtjtwatrjt.html

Java: String greet() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtjpppsmoe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtgorofzpj.html

Ruby: def greet; @name; end
来源：http://dali.gotoacloud.top/Article/details/gtnicxockc.html

C#:   public string Greet() => Name;
来源：http://dali.ybcxt.top/Article/details/gtcmfgyraj.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gtavggnanc.html

Py:   class Admin(User): pass
来源：http://dali.hnxiangtu.top/Article/details/gtvywntkyj.html

PHP:  class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtqdwtjkjc.html

JS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixkrqxxu.html

TS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtnloiksfp.html

Java: class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtruetymho.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yongpay.top/Article/details/gtcqrovkgz.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtdfozpzgu.html

C#:   class Admin : User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjmygoaq.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gtjoybimjl.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gtwzfnsupk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtbsicwrcc.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtwwwqzwbp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyopeakyr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtyvdsilyn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xylfe.cn/Article/details/gttgdxiykx.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gtwjafwdlk.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangtech.top/Article/details/gttxzizmbw.html

[G07] 调用父类方法
来源：http://dali.zhixingplan.top/Article/details/gtmgfbbymz.html

Py:   super().greet()
来源：http://dali.ivvv.top/Article/details/gtvilnljfx.html

PHP:  parent::greet();
来源：http://dali.zycfv.cn/Article/details/gtetnybgbc.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtvclhoxcf.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtduolinoc.html

Java: super.greet();
来源：http://dali.pycfn.com/Article/details/gttxycsogi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhiwuduotai.top/Article/details/gtjefnofzk.html

Ruby: super
来源：http://dali.yongpay.top/Article/details/gtbwxvgadq.html

C#:   base.Greet();
来源：http://dali.jyoumei.cn/Article/details/gtapcvsigd.html

[G08] 静态方法与属性
来源：http://dali.birdmap.top/Article/details/gthlhwzqrj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yvedp.cn/Article/details/gtypiaktpe.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gthafedlak.html

JS:   static f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbabkneqw.html

TS:   static f(): void {}
来源：http://dali.andypj.xyz/Article/details/gtvyqzbnmd.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gtrqwgufvx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.kuanghao11.cn/Article/details/gtbrgpbilk.html

Ruby: def self.f; end
来源：http://dali.hongshengwenyu.top/Article/details/gtxewpvukt.html

C#:   public static void F() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtelsanefa.html

[G09] 接口 / 抽象类
来源：http://dali.chenjidiqi.icu/Article/details/gtszpodtdo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigufen.top/Article/details/gtczjtktfn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gtnwkbwnfx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yangfankeji.com/Article/details/gtltajktda.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenjidiqi.icu/Article/details/gteccgmdxo.html

Java: interface Shape { double area(); }
来源：http://dali.shzxlz.cn/Article/details/gtwpigyrrw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gtssmkaaga.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhixingplan.top/Article/details/gtbvzsmtlb.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqtqblnw.html

[G10] 访问控制
来源：http://dali.gzhubu.top/Article/details/gtmjznoarj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gtfzlqdrzo.html

PHP:  public / protected / private
来源：http://dali.hammf.cn/Article/details/gtbuvlobeq.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gtmwzzqomu.html

TS:   public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtlcziruyc.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gtgconzing.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guannengcc.top/Article/details/gtpiwxhrkm.html

Ruby: public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gthxrvjutc.html

C#:   public / protected / private / internal
来源：http://dali.cqqwz.cn/Article/details/gtwiqbrtvf.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gtbtnwaxfg.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gtggufyony.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtgnbfxzyc.html

JS:   get name() { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtepwbhzmo.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtbplwofww.html

Java: public String getName() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtgllygxmz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtdojsrcla.html

Ruby: attr_accessor :name
来源：http://dali.yvedp.cn/Article/details/gtcimbgesb.html

C#:   public string Name { get; set; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxvppydx.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gtxmildism.html

Py:   def __str__(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtssvobidb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtlmejqcyk.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtrbgziozh.html

TS:   toString(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gthrtepith.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtdrnfjczp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gteotfgkbf.html

Ruby: def to_s; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtcnzrkzje.html

C#:   public override string ToString() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyzyegki.html

[G13] 判断对象类型
来源：http://dali.yj20258888.top/Article/details/gtplkvwqcn.html

Py:   isinstance(u, User)
来源：http://dali.quarkkingdee.top/Article/details/gtpupwhpfc.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtajpfrqhw.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofgqbwxm.html

TS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtcjcfchwd.html

Java: u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtjhxnyxya.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gteplaqyah.html

Ruby: u.is_a?(User)
来源：http://dali.yanxiufei.cn/Article/details/gtuddzfxud.html

C#:   u is User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrospvun.html

[G14] 数据类 / record
来源：http://dali.hfpthk.cn/Article/details/gtymfiuhgd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenjidiqi.icu/Article/details/gtaclrrngg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxinkj.top/Article/details/gtnbbtffvf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmlwaaic.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhongyouzk.top/Article/details/gtpmtddtsi.html

Java: record User(String name, int age) {}
来源：http://dali.cqqwz.cn/Article/details/gtanqhbyje.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gzhubu.top/Article/details/gtkugbvhgk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gtcjiiqynx.html

C#:   record User(string Name, int Age);
来源：http://dali.ivvv.top/Article/details/gtwksrgbdf.html

[G15] 枚举
来源：http://dali.0kj1m.cn/Article/details/gtzboxqyvc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gtgivbrnob.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xinyue.icu/Article/details/gtpznlwssp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shangyingyoupin.top/Article/details/gtviibamql.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gtpaqqhosp.html

Java: enum Color { RED, GREEN }
来源：http://dali.c1oappe.top/Article/details/gtkttxgsal.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hysaishi.cn/Article/details/gtghojunxh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gtdkttovzo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gtsawnnvdr.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjzhiyfr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gtynduhwvy.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gtyxghsgey.html

JS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gtsmxulcdl.html

TS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gtknvxehku.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinghuilouyu.cn/Article/details/gtukipuhet.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jyoumei.cn/Article/details/gtkinrzcng.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangtech.top/Article/details/gtudtubnwq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtifqtaqrj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtizkclrgq.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gtzjrfeqsa.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtylfccvuu.html

[H01] try / catch 基础
来源：http://dali.yangfankeji.com/Article/details/gtuqgoywkr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gtwcmtajjj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.havefunace.top/Article/details/gtogsywfft.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtbhnoouug.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtqiibobpf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gogol.net.cn/Article/details/gtiasuxdtl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dianchejie.cn/Article/details/gtzikjkmmf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ybcxt.top/Article/details/gtyofyphwh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxinkj.top/Article/details/gtbnzwcspr.html

[H02] finally / ensure 收尾
来源：http://dali.dianchejie.cn/Article/details/gtybxtgdvm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gtcsgxtxvt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gttkdchzzu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtjdkxmzch.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnccxksw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtpgffxqel.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fzhhl.top/Article/details/gtrgomaqvl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gaohongyu789.top/Article/details/gtmebbeltz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtjjldzdsk.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gtrwpiahrp.html

Py:   raise ValueError("错误信息")
来源：http://dali.cashguo.top/Article/details/gtuoasichx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtfgzijche.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvhdigqk.html

TS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtvnnrxril.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtvyfgfeyn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvjdcdbq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gotoacloud.top/Article/details/gtfsskzsgg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtbjjsciew.html

[H04] 自定义异常类型
来源：http://dali.pycfn.com/Article/details/gtzejoxeod.html

Py:   class MyError(Exception): pass
来源：http://dali.fengsongda.top/Article/details/gtphmcyczu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjionssts.html

JS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gtxcdcizhc.html

TS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtabgnytti.html

Java: class MyException extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gtczuvrbnj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangtech.top/Article/details/gttitvgtgc.html

Ruby: class MyError < StandardError; end
来源：http://dali.xinyue.icu/Article/details/gtshodatdx.html

C#:   class MyException : Exception {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsiplfknc.html

[H05] 捕获特定类型
来源：http://dali.sufxvd.cn/Article/details/gttpusroax.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gtyarawmrl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gtcxtcnggc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtijxxglxz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtvdhpjkho.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gthuplnjtb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gtkcchbjpq.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gtpylgeghj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gtzajdwhxq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenzaomai.com/Article/details/gttnoomxnl.html

Py:   value = d.get("k") or default
来源：http://dali.aizwys.cn/Article/details/gtskvwsghu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gttjsczosf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtudnkhmmc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtvakfnyxb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.bjfxy.top/Article/details/gtbjafqdyc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shzxlz.cn/Article/details/gtuepeqfhp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gtdioizxxl.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gtdyurxbqe.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gtcxpdsxbo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxuanxn.top/Article/details/gtqvzgjutb.html

PHP:  assert($x > 0);
来源：http://dali.pycfn.com/Article/details/gtfhnrkfbv.html

JS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtxvhzwwxh.html

TS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtucuouhwp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gtfymrmzud.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hongshengwenyu.top/Article/details/gtynocbrnb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hfpthk.cn/Article/details/gtnmzxszai.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtmaoqxbaa.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxuanxn.top/Article/details/gtgnrdrgak.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sysykeji.top/Article/details/gtqrucztqm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xinyue.icu/Article/details/gtniostsoo.html

JS:   e.message;  e.stack
来源：http://dali.hnqzz.top/Article/details/gtwkotfllm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hysaishi.cn/Article/details/gtpkyejvcn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hfpthk.cn/Article/details/gtccokbcvo.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gtaiycthav.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gtgeeswzrk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yvedp.cn/Article/details/gtxvwtjyho.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gtycmpddmy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenzaomai.com/Article/details/gteexhgbcp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xinyue.icu/Article/details/gtvzlgbqdk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxinkj.top/Article/details/gtevbnjiwf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhongyouzk.top/Article/details/gtvqbgnxli.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gtjymhfyye.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gaohongyu789.top/Article/details/gtjawjxozm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yanxiufei.cn/Article/details/gtxvcbwgls.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sweek.top/Article/details/gtnrjspjom.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gtotjkiuwp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hammf.cn/Article/details/gttoelgikc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.redwolf501.top/Article/details/gtbqtjgeyw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtukuacvxh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtgtibzupn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gtojjjeafa.html

Go:   defer f.Close()
来源：http://dali.sxryk.cn/Article/details/gtttmhscap.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cqqwz.cn/Article/details/gtwalflbyo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtwxellvxc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtczgygjdo.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gtexliasot.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtiodtxphf.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gtdtyflufc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtecjgaajl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtuyrqfoxu.html

JS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gtswomqogm.html

TS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gttjewfngk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gtcbqabvcv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daxiang520.top/Article/details/gtquixqyni.html

Ruby: s.match?(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gtlldtuabk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gtqxmocnwc.html

[I02] 提取所有匹配
来源：http://dali.kuanghao11.cn/Article/details/gtxevfixtx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtrryxypzf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aizwys.cn/Article/details/gtkfzbeakz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhongyouzk.top/Article/details/gtrhfnvock.html

TS:   s.match(/\d+/g)
来源：http://dali.cucudq.cn/Article/details/gtabuqmdux.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuakwdov.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gtauxgorhq.html

Ruby: s.scan(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtzfdiqcuj.html


<!-- 参考信息 -->