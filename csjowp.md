代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aibaodan.cn/Article/details/gtdvbgxvnk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.9152youxi.cn/Article/details/gtggewunmj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gtesxsroen.html

[F08] 遍历目录
来源：http://dali.vqdsnc.cn/Article/details/gthxdtlncr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.birdmap.top/Article/details/gtiyrmcnqc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gthdhqzyhs.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtxoxaonww.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gtthbdlmpl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtgtfvcprw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gteiiounqe.html

Ruby: Dir.children("dir")
来源：http://dali.hfpthk.cn/Article/details/gtmceuffvc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.andypj.xyz/Article/details/gtvldrldfv.html

[F09] 获取文件大小
来源：http://dali.kuanghao11.cn/Article/details/gttsxfleyc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtlasdufiz.html

PHP:  filesize("a.txt");
来源：http://dali.yj202588.top/Article/details/gtauoizyob.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtqhpcvgor.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtppifrtju.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtzfejusji.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenlongwang.top/Article/details/gtfatufsyd.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtqeujeift.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.c1oappe.top/Article/details/gtpwtulehp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhengqikj.top/Article/details/gtaisojizz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtmwavfqdq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtkihcxibz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtvstcaldx.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtnrddyjiz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cucudq.cn/Article/details/gtiwygkuzw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtbpceovwm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtzepjivtf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtfkdhtkkh.html

[F11] 复制与移动文件
来源：http://dali.daria6918.cn/Article/details/gtklztkpon.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtqrukouof.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtwaerlvut.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtwnqnxqwa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtvhmnzgms.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tian-w.cn/Article/details/gtjdzjurjk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnxiangtu.top/Article/details/gtcelxjnff.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtxmbvilgv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aibaodan.cn/Article/details/gtxhzmokvu.html

[F12] CSV 读写
来源：http://dali.zycfv.cn/Article/details/gtbvejrnly.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gtvalpknqk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.quarkkingdee.top/Article/details/gtafqzbaxo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jiagoushi.top/Article/details/gtyqbrwqge.html

TS:   // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtxnhfteki.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gtlbmdvcrf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gttbhvmdto.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.redwolf501.top/Article/details/gtuefcraam.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.svipenyu.cn/Article/details/gtbnmpelox.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtptuglaap.html

G. 面向对象
来源：http://dali.ybcxt.top/Article/details/gtyuwwigmg.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbjeghyml.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gtfahylejw.html

Py:   class User: pass
来源：http://dali.sweek.top/Article/details/gtcdyrjfuz.html

PHP:  class User {}
来源：http://dali.wangdashe.top/Article/details/gtrbbhmthq.html

JS:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtufdogxus.html

TS:   class User { name: string = ""; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywlqlrgm.html

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gthmzxejsm.html

Go:   type User struct { Name string }
来源：http://dali.vqdsnc.cn/Article/details/gtweibrooc.html

Ruby: class User; end
来源：http://dali.jqgufenzy.top/Article/details/gtmnlzqnam.html

C#:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtbyzdwbux.html

[G02] 构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrghyonh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gttzrowyuq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zycfv.cn/Article/details/gtpnrfuidz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtzigdhtlc.html

TS:   constructor(public name: string) {}
来源：http://dali.gaohongyu789.top/Article/details/gtkpttqlwh.html

Java: User(String name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtmtamhobt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gtthyswtnr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcivxjgdy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.iojbl.cn/Article/details/gtumofdraz.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gtxycflaff.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gtbskgimhl.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gtddbuxrmh.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gtzjmlcuce.html

TS:   name: string = "x";
来源：http://dali.nanxinkj.top/Article/details/gtfnbqukln.html

Java: private String name;
来源：http://dali.birdmap.top/Article/details/gtkxprmapo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gtttzvpzoh.html

Ruby: @name = "x"
来源：http://dali.iojbl.cn/Article/details/gthestayox.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yonumen.top/Article/details/gtmudmjsaw.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gtwwnwxvqi.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtpnznbrin.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gteykldxtv.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtdaddlxqo.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtkitcuzxe.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbeaxhva.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtufgpzaus.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtkavwtyfz.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gtvklcyhdt.html

[G05] 继承
来源：http://dali.sweek.top/Article/details/gtphtiqzzh.html

Py:   class Admin(User): pass
来源：http://dali.hywenlv.cn/Article/details/gtnsmgeows.html

PHP:  class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtomrgrezv.html

JS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtratvooqt.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbvqcmsq.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtpyfhvyzd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gtznhulyuo.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gthbostpld.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gtjvqpyxbs.html

[G06] 重写方法
来源：http://dali.sufxvd.cn/Article/details/gtfvguqrle.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gtajpndbnz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtfidfcdxf.html

JS:   greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtrpjxawnl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gthrqwyfmw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtftwwyqub.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hywenlv.cn/Article/details/gtrdemxmok.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gtlwxwynht.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpuufpacj.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gtyctqcqmc.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gtfkzhpdbs.html

PHP:  parent::greet();
来源：http://dali.havefunace.top/Article/details/gttxsijqnq.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtfqlqgrhk.html

TS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtenrvcqib.html

Java: super.greet();
来源：http://dali.tanke756.top/Article/details/gttksuajuq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gogol.net.cn/Article/details/gtlbipdcik.html

Ruby: super
来源：http://dali.feifeiyinyue.top/Article/details/gtoxozgccy.html

C#:   base.Greet();
来源：http://dali.c1oappe.top/Article/details/gtwjnrdwus.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gtotevuvva.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ybcxt.top/Article/details/gtwftbwxjp.html

PHP:  public static function f() {}
来源：http://dali.gotoacloud.top/Article/details/gtwmllqsst.html

JS:   static f() {}
来源：http://dali.tianlin.xyz/Article/details/gtzzfgqpah.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvuwiges.html

Java: static void f() {}
来源：http://dali.ivvv.top/Article/details/gtaayuyxpb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xinyue.icu/Article/details/gtxmuwnyyv.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gtffirtohr.html

C#:   public static void F() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtlmrtcvyj.html

[G09] 接口 / 抽象类
来源：http://dali.0kj1m.cn/Article/details/gtnforvgpc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aibaodan.cn/Article/details/gttbktkcyk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gtjfamxttw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yongpay.top/Article/details/gtqldrvfly.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtnlpvumhc.html

Java: interface Shape { double area(); }
来源：http://dali.cucudq.cn/Article/details/gtniredvnp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gzhubu.top/Article/details/gthtswpwpr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.haohaochexian.top/Article/details/gtvphgdmhg.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gtvwmdqcxr.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gtaaciqgju.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgfzy.top/Article/details/gthnmrerpq.html

PHP:  public / protected / private
来源：http://dali.yuxming.cn/Article/details/gthqftxkiy.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gtzdxpqrzj.html

TS:   public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtrkjctmwr.html

Java: public / protected / private / 默认包级
来源：http://dali.chenzaomai.com/Article/details/gtfujemrko.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gtxfeovgfw.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtvsgpmist.html

C#:   public / protected / private / internal
来源：http://dali.yonumen.top/Article/details/gtzpdtkork.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gtfhufbzwa.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gtiluogaga.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtbswatptf.html

JS:   get name() { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtjvfffasw.html

TS:   get name(): string { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtiqmlpwix.html

Java: public String getName() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtrdoqzgmw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtxaztghsj.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gtyvtvimac.html

C#:   public string Name { get; set; }
来源：http://dali.cqqwz.cn/Article/details/gtgcweiloy.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtzvgpeuyq.html

Py:   def __str__(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtqmatwceh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtzfjkiqyb.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtzzkkwrmt.html

TS:   toString(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtkggnftau.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtopieuadb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gttmtiogkw.html

Ruby: def to_s; @name; end
来源：http://dali.sufxvd.cn/Article/details/gteronmxpc.html

C#:   public override string ToString() => Name;
来源：http://dali.smart0.xyz/Article/details/gtojluhaco.html

[G13] 判断对象类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsoxhlvwo.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcljlubtp.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtmjjlecea.html

JS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtwlrljdss.html

TS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtxawwwaqo.html

Java: u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtpeeclzob.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.svipenyu.cn/Article/details/gtkoxwzqhj.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gtqlrptsjp.html

C#:   u is User
来源：http://dali.mhx1999.top/Article/details/gtokiniggp.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gthwpbpjwn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gtuwlbsfsj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gtvyprnjhe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gtumgqnsee.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258.top/Article/details/gtbkzdwzat.html

Java: record User(String name, int age) {}
来源：http://dali.yongpay.top/Article/details/gttspxrrmy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xinyue.icu/Article/details/gtgqwzthuk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tianlin.xyz/Article/details/gtwcmaybzz.html

C#:   record User(string Name, int Age);
来源：http://dali.pengpengdd.cyou/Article/details/gtlusvjhma.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gtykvkjhsg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoooznuih.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gtkcuyzmfg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.quarkkingdee.top/Article/details/gtzajbazsa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtquowjilj.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gtiuzdbuaj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.feifeiyinyue.top/Article/details/gttdfkndfr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.mhx1999.top/Article/details/gtnzpsluwz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtcoiojsil.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gtdusademb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ivvv.top/Article/details/gtxxedcqbp.html

PHP:  get_object_vars($obj);
来源：http://dali.yonumen.top/Article/details/gtbsosqpax.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtxnrqpmsy.html

TS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtmrhhmhrx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fzhhl.top/Article/details/gtmfqtpxub.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cheryme.top/Article/details/gtyzlfshqs.html

Ruby: obj.instance_variables
来源：http://dali.hysaishi.cn/Article/details/gtdnycgctq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtbdchhatg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtecrxhqgl.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gtcqcwkbly.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtvgfgaaut.html

[H01] try / catch 基础
来源：http://dali.shangyingyoupin.top/Article/details/gttuymmmog.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenlongwang.top/Article/details/gtnqzaxaxd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cheryme.top/Article/details/gtmwzkspso.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtzccpietw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtljldlgkt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gtvfkgcqzy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhongyouzk.top/Article/details/gtlmymlsjk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.smart0.xyz/Article/details/gtmhdigzqz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guowangkeji.top/Article/details/gtqhyuison.html

[H02] finally / ensure 收尾
来源：http://dali.sufxvd.cn/Article/details/gtstxzxbvk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gtqrajqctt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtwunvbica.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtoemecofo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtnqsnntma.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtuywmonaq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cdnleiting.top/Article/details/gtfbondphr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gtxodbzbap.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcayoeof.html

[H03] 主动抛出异常
来源：http://dali.mhx1999.top/Article/details/gtnxmsdiqt.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigufen.top/Article/details/gtkcdpjkks.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtixcnchfd.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrdwkfoy.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gttfgimdwc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtjuiajefy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tianlin.xyz/Article/details/gtjrdijoam.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gtztwgoegy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtbtfspyem.html

[H04] 自定义异常类型
来源：http://dali.xziqi.cn/Article/details/gtsqqpchxm.html

Py:   class MyError(Exception): pass
来源：http://dali.zhengqikj.top/Article/details/gtapbyaqcs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtsotnvdiu.html

JS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtsnamrbtu.html

TS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtdgwtmpyl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtfsablxtq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gtplkyzmuw.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gttqiutafd.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gttqgvrvto.html

[H05] 捕获特定类型
来源：http://dali.zhiwuduotai.top/Article/details/gtfbenruzn.html

Py:   except ValueError as e:
来源：http://dali.yuxming.cn/Article/details/gtfvtecunh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.quarkkingdee.top/Article/details/gtsjcqjmcg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtovegdaqh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtzayemwzd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ybcxt.top/Article/details/gthfblfazk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgufenzy.top/Article/details/gthxcqggbt.html

Ruby: rescue ArgumentError => e
来源：http://dali.ehwqpu.com/Article/details/gtxjbmkppw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guannengcc.top/Article/details/gtfeqtrzms.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ppjwa.cn/Article/details/gtqbyszfkb.html

Py:   value = d.get("k") or default
来源：http://dali.jqgufenzy.top/Article/details/gtuqvmkaws.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtheiibbge.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtmfkldyrn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtyxloctod.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cdnleiting.top/Article/details/gtsigmsckm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gttbcfjwew.html

Ruby: d&.dig(:a, :b)
来源：http://dali.quarkkingdee.top/Article/details/gtgnnpsbyi.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gtsegsggms.html

[H07] 断言
来源：http://dali.jlsjyb.cn/Article/details/gtjhxdribc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.quarkkingdee.top/Article/details/gtexybaxzj.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gttjjosmsq.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtknbbdkou.html

TS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtqaoleatz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.mhx1999.top/Article/details/gtkpdstiut.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gogol.net.cn/Article/details/gtsuvuupsf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sufxvd.cn/Article/details/gtpkjivxpa.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtkbrexktw.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gtxmlprvvk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sweek.top/Article/details/gtyrgiulwg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhoulong.xyz/Article/details/gtxdoqemmq.html

JS:   e.message;  e.stack
来源：http://dali.hysaishi.cn/Article/details/gtrenoqizz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gzhubu.top/Article/details/gtallryaai.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ybcxt.top/Article/details/gtjojkpkkk.html

Go:   err.Error()
来源：http://dali.yvedp.cn/Article/details/gtfoszajhv.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gtnzhvcfee.html

C#:   e.Message;  e.StackTrace
来源：http://dali.snrcjt.cn/Article/details/gtmwvhmtvm.html

[H09] 带错误码的异常
来源：http://dali.yongpay.top/Article/details/gtvwltvjwf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gtboabtzoa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cucudq.cn/Article/details/gtspdjiivs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gttxbszgfr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gtuzimeuzo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuanzhike.top/Article/details/gtuzmldgzv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cdnleiting.top/Article/details/gtopukbrrx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj202588.top/Article/details/gtflslbsod.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhixingplan.top/Article/details/gtyugsyriu.html

[H10] 资源自动释放
来源：http://dali.iojbl.cn/Article/details/gtiwdwyrmk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ybcxt.top/Article/details/gtdvksktrp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yueranfly.top/Article/details/gttvppngir.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrykynwpn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtigfdqeie.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cheryme.top/Article/details/gtusawuvzy.html

Go:   defer f.Close()
来源：http://dali.zhongyouzk.top/Article/details/gtycqfizgl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gtsrflngdg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gttmmscfop.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtzyxjgcup.html

I. 正则表达式
来源：http://dali.yanxiufei.cn/Article/details/gtafwhwwdw.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtbqqqfamu.html

[I01] 判断是否匹配
来源：http://dali.zhoulong.xyz/Article/details/gtorprrdgk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gtflmezbxg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtumakcedm.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtfxbldqmd.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gtriatqzbi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gthcuavmfi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxjkwklk.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtqtrhwhvn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhengqikj.top/Article/details/gtddfpfwyf.html


<!-- 参考信息 -->