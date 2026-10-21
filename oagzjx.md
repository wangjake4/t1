代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gtggoerepk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ehwqpu.com/Article/details/gtcsyhxcqz.html

Ruby: Dir.children("dir")
来源：http://dali.fengsongda.top/Article/details/gtdjrjfjub.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gtuazgobda.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gtmucjrsfn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtqtmkohdn.html

PHP:  filesize("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtgbroqsyf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtygmtyhxr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzhmwmwk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtsfejaeij.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.quarkkingdee.top/Article/details/gtteddiubn.html

Ruby: File.size("a.txt")
来源：http://dali.birdmap.top/Article/details/gtnpmpdpro.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ppjwa.cn/Article/details/gtjnxzlrqt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigfzy.top/Article/details/gtbrpdeufg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gttvlodvoe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gttxuzedwb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtuobyjaxq.html

TS:   path.extname("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtuzelsgtu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yanxiufei.cn/Article/details/gtbypwinxy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtytaoqgcp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtyfnirjwi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtbgfpmplo.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gttmagkfnm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtgnshchdc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ybcxt.top/Article/details/gtqobwzjct.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtccfgxxid.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtknlbjtyh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtzexllrfr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuanzhike.top/Article/details/gtozdfevnw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtgiqngore.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xziqi.cn/Article/details/gtydrtejmk.html

[F12] CSV 读写
来源：http://dali.jyoumei.cn/Article/details/gtrfskjdro.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yueranfly.top/Article/details/gtvwdcrxai.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258.top/Article/details/gtazyenzss.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.haohaochexian.top/Article/details/gtnryikfln.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gtxltxcebo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbvuikzr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pengpengdd.cyou/Article/details/gtgkkycjjy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtkenjferd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gtzffzyyug.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtpezoovoj.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gtqtuxroky.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtfmffzkld.html

[G01] 定义类
来源：http://dali.fzhhl.top/Article/details/gtuaisqgnd.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gtybgnbxgn.html

PHP:  class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpawrhmag.html

JS:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtvwcygxkd.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxinkj.top/Article/details/gtwxhkkaud.html

Java: class User {}
来源：http://dali.daxiang520.top/Article/details/gtjpxsialv.html

Go:   type User struct { Name string }
来源：http://dali.yanxiufei.cn/Article/details/gtvqltzlrz.html

Ruby: class User; end
来源：http://dali.cqqwz.cn/Article/details/gtvmkiznvc.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtddfshowz.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gtdrrqierd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gtoldbqwta.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gtoqyldfro.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdvgzczm.html

TS:   constructor(public name: string) {}
来源：http://dali.hammf.cn/Article/details/gtjcipnbmx.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtljrnvbsz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gtjhbrslec.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gtofenhkrj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtggojvabz.html

[G03] 实例属性
来源：http://dali.guowangkeji.top/Article/details/gtvtbopavl.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gtndefmykc.html

PHP:  public string $name = "x";
来源：http://dali.xylfe.cn/Article/details/gtakedycon.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gtrjwzvlna.html

TS:   name: string = "x";
来源：http://dali.zhixingplan.top/Article/details/gtrpuonobh.html

Java: private String name;
来源：http://dali.nwbrower.top/Article/details/gtwwywzsaq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.vqdsnc.cn/Article/details/gthblnqulw.html

Ruby: @name = "x"
来源：http://dali.tanke756.top/Article/details/gthjhfquuu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gtsgamebjr.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gtpjaqoqkp.html

Py:   def greet(self): return self.name
来源：http://dali.tanke756.top/Article/details/gthpxwgekf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtlpulchqb.html

JS:   greet() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtcnkldnqw.html

TS:   greet(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtqpudptgm.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtrhbuutcu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtyukhchmd.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gtujfhlsez.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258888.top/Article/details/gtlplndaun.html

[G05] 继承
来源：http://dali.hammf.cn/Article/details/gtuzoqycff.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gtcgftwpdz.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtweqpxyjs.html

JS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gthmfffpzi.html

TS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtgjotycrw.html

Java: class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtjhczlsmm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gtbfintmzo.html

Ruby: class Admin < User; end
来源：http://dali.jlsjyb.cn/Article/details/gtskluduep.html

C#:   class Admin : User {}
来源：http://dali.gaohongyu789.top/Article/details/gtzivkhgmg.html

[G06] 重写方法
来源：http://dali.jinqigfzy.top/Article/details/gtnhvkteco.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gtnqyiquvd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtjxllfngn.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gteodzqdcx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtmfvlocfk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtminjyusx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gtsjboozrv.html

Ruby: def greet; "admin"; end
来源：http://dali.dianchejie.cn/Article/details/gtulkwawld.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gtpodouqna.html

[G07] 调用父类方法
来源：http://dali.yuanzhike.top/Article/details/gtzbvvhmgn.html

Py:   super().greet()
来源：http://dali.chenlongwang.top/Article/details/gtjymllyqy.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gtvtmasbql.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtmdbopdme.html

TS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gthweuvlrg.html

Java: super.greet();
来源：http://dali.pycfn.com/Article/details/gtmvcmdlpz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gogol.net.cn/Article/details/gtyncxfouh.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gtrmzjnqlf.html

C#:   base.Greet();
来源：http://dali.yj20258888.top/Article/details/gtvqklmudj.html

[G08] 静态方法与属性
来源：http://dali.jqgfzy.top/Article/details/gtgxpunvem.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxuanxn.top/Article/details/gtwddmfsql.html

PHP:  public static function f() {}
来源：http://dali.yuxming.cn/Article/details/gtruytpzsr.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gtdrsesmnr.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gtwdgsbvnv.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtkjhqtkmg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cqqwz.cn/Article/details/gtdrhzoseh.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gtenujrddx.html

C#:   public static void F() {}
来源：http://dali.gzhubu.top/Article/details/gtovuxyiws.html

[G09] 接口 / 抽象类
来源：http://dali.c1oappe.top/Article/details/gtxckcjnsr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gtdgvcivkz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cheryme.top/Article/details/gtyzlpcgwm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gtxzgsogas.html

TS:   interface Shape { area(): number; }
来源：http://dali.gaohongyu789.top/Article/details/gtcmnevrpj.html

Java: interface Shape { double area(); }
来源：http://dali.tanke756.top/Article/details/gtkchvecdb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guowangkeji.top/Article/details/gtxhuvussq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gtlyfwuiqt.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gtszzbxgqt.html

[G10] 访问控制
来源：http://dali.yj20258.top/Article/details/gtnvgsdhnc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sxryk.cn/Article/details/gtrdmcbqpi.html

PHP:  public / protected / private
来源：http://dali.birdmap.top/Article/details/gtkiccevsw.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gthnmcqhkw.html

TS:   public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtearweysz.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gtsmxxhwbn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yvedp.cn/Article/details/gttkrfxyod.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gtgjctdstb.html

C#:   public / protected / private / internal
来源：http://dali.jyoumei.cn/Article/details/gtcrxpoacp.html

[G11] getter / setter
来源：http://dali.wangdashe.top/Article/details/gtrbkzxipl.html

Py:   @property 与 @x.setter
来源：http://dali.quarkkingdee.top/Article/details/gtuowfcpzm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcbfrxuz.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258.top/Article/details/gtgzzyedys.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gtccadzlmt.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtncuqcbvg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtcepzbofa.html

Ruby: attr_accessor :name
来源：http://dali.feifeiyinyue.top/Article/details/gtshuxzedi.html

C#:   public string Name { get; set; }
来源：http://dali.0kj1m.cn/Article/details/gtfxzkvxpf.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gtkjjsqqog.html

Py:   def __str__(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtnqigfxga.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtueukgrhd.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtisesgjlc.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwehrcdqi.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtqhbfusmd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtyjonjiwt.html

Ruby: def to_s; @name; end
来源：http://dali.jianghu66.top/Article/details/gttfincguk.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gtziwhqwsj.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gtghdxildx.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gtddvcihdo.html

PHP:  $u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtlaulqsfp.html

JS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtdudzcggi.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtmuddffqb.html

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtvuimfsjl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtloqmhmsa.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gtubgczmsv.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gtzrvzzijz.html

[G14] 数据类 / record
来源：http://dali.jinqigufen.top/Article/details/gtjtmlqcms.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gtehuobvdx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cashguo.top/Article/details/gtubxyrzal.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pengpengdd.cyou/Article/details/gtckccuuwi.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxuanxn.top/Article/details/gtmxlvegvs.html

Java: record User(String name, int age) {}
来源：http://dali.daria6918.cn/Article/details/gtjsvrvlst.html

Go:   type User struct { Name string; Age int }
来源：http://dali.haohaochexian.top/Article/details/gthmrdqqng.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gthgwwmcfn.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangtech.top/Article/details/gtomrmurnv.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gtjojfmkiq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ehwqpu.com/Article/details/gtbwbrddje.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hfpthk.cn/Article/details/gtunxeusjb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gtmfhbsoze.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtjgzuvono.html

Java: enum Color { RED, GREEN }
来源：http://dali.hywenlv.cn/Article/details/gtdvqbltlv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.svipenyu.cn/Article/details/gtxedvkuzq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gtoxyworks.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gtkuuwpguk.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gtjdymymfz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gtrjlredma.html

PHP:  get_object_vars($obj);
来源：http://dali.chenlongwang.top/Article/details/gtbbtuofgo.html

JS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtdarerkbo.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvkspgvz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuanzhike.top/Article/details/gtnmtdvbwr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gtmwybokuj.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gtbytxacmm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcwsunse.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtpbrhmexz.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gtlltfrcrp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtvowcysgv.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gthlqnwkip.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangdashe.top/Article/details/gtloyytbya.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guowangkeji.top/Article/details/gtlpzcasre.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtpbtkyokw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtqqfszfya.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sufxvd.cn/Article/details/gtndikvtkn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jiagoushi.top/Article/details/gtnjvdpdtd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daria6918.cn/Article/details/gtslbkfwhi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenlongwang.top/Article/details/gtprvhvshj.html

[H02] finally / ensure 收尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcykohaco.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhixingplan.top/Article/details/gtqyojpbdh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqkmflrw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtwcxiispv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gthsnqcojb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtmtdrnyzx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yvedp.cn/Article/details/gteoklkwek.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gtboltxebc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtmjxielbk.html

[H03] 主动抛出异常
来源：http://dali.hnqzz.top/Article/details/gtuuiozqay.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gtehdxsjfd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtjkbnls.html

JS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtjkveztgf.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtdidgttpu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtkzvrrdto.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gtjrhusuzz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guowangkeji.top/Article/details/gtmxtssbtg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtstevwrrt.html

[H04] 自定义异常类型
来源：http://dali.svipenyu.cn/Article/details/gtfxbjqfnp.html

Py:   class MyError(Exception): pass
来源：http://dali.ppjwa.cn/Article/details/gtjbtkigdm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gtorqiqiqx.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtqupwbxdv.html

TS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtyayucvsq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gttqnlalwz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gtcbnzrjtr.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gtqsgfniqs.html

C#:   class MyException : Exception {}
来源：http://dali.tian-w.cn/Article/details/gtqnoolfqo.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gtdtxvtmdr.html

Py:   except ValueError as e:
来源：http://dali.shuidangran.top/Article/details/gtwvzidkcz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxuanxn.top/Article/details/gtcyjxwclr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gtonjmzzmu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtnpwvwanq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxuanxn.top/Article/details/gtqxgfdwzk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shzxlz.cn/Article/details/gtlssmleym.html

Ruby: rescue ArgumentError => e
来源：http://dali.cucudq.cn/Article/details/gtiifybmvg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daria6918.cn/Article/details/gtydxcbsrb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdjipukk.html

Py:   value = d.get("k") or default
来源：http://dali.aibaodan.cn/Article/details/gthvfattbw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gtisivxhwq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtaozbxqsx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtcnhnlcak.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gtqqbotjzv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.kuanghao11.cn/Article/details/gtzdpeziig.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gtrgnsphds.html

C#:   obj?.A?.B ?? default
来源：http://dali.daria6918.cn/Article/details/gtjjuoysso.html

[H07] 断言
来源：http://dali.vqdsnc.cn/Article/details/gtlenpsxbd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmwzftzz.html

PHP:  assert($x > 0);
来源：http://dali.hammf.cn/Article/details/gtweuwizwy.html

JS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtxxdmhubm.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtudsfxmdv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtumdyimvk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gogol.net.cn/Article/details/gttkemttrw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gtylmnwhjb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtpqekblxf.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenjidiqi.icu/Article/details/gtfhhmrhvm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daria6918.cn/Article/details/gtmxaluguh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dashuyun.cn/Article/details/gtckdthrbs.html

JS:   e.message;  e.stack
来源：http://dali.fengsongda.top/Article/details/gtglctngho.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnxiangtu.top/Article/details/gtyftidgvu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ppjwa.cn/Article/details/gtnfrhrxdx.html

Go:   err.Error()
来源：http://dali.sysykeji.top/Article/details/gtdxhbtmdq.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuetiantiany.cn/Article/details/gtczhleayg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuanzx.com/Article/details/gtumuwegoq.html

[H09] 带错误码的异常
来源：http://dali.xziqi.cn/Article/details/gtxnfgghnc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuetiantiany.cn/Article/details/gtheoirsxc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yongpay.top/Article/details/gtwihxbobj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gtinmlrfii.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gaohongyu789.top/Article/details/gtsdcmngce.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhengqikj.top/Article/details/gtjtirrdeu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.bjfxy.top/Article/details/gtuvfzpnjz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ivvv.top/Article/details/gtzurkncnu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pengpengdd.cyou/Article/details/gtsrodinbp.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gtuppprbrb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hammf.cn/Article/details/gtxechbjzg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xylfe.cn/Article/details/gtgvnmadmw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtgvrjvaki.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtrkqqpqsy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guowangkeji.top/Article/details/gtilcpmugy.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gtahkfgupm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gtkidetfzc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtzuoickhi.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtvnwunqyc.html

I. 正则表达式
来源：http://dali.ivvv.top/Article/details/gtfpbjiqzl.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwqabvng.html

[I01] 判断是否匹配
来源：http://dali.hnqzz.top/Article/details/gtfnojyzdr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtpuuezauh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuanzx.com/Article/details/gtygchputj.html

JS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvaloqjs.html

TS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjpqshlg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gtdwznaejp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.meibo888.top/Article/details/gtgvtwbcms.html

Ruby: s.match?(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gtqluytfpc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yonumen.top/Article/details/gtoyjgnsqr.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gthtwmctgc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtawbimtiv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pengpengdd.cyou/Article/details/gtldeeveuq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxraswctb.html

TS:   s.match(/\d+/g)
来源：http://dali.jiagoushi.top/Article/details/gtcnvyagwl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gttnydtdro.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtmygkjhbx.html

Ruby: s.scan(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtknxjddco.html


<!-- 参考信息 -->