代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gtybmxfpls.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gtferktafc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zdqjudy.top/Article/details/gtimmcykwo.html

[F08] 遍历目录
来源：http://dali.yonumen.top/Article/details/gtkdiizhmn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.iojbl.cn/Article/details/gtdzibcsme.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tanke756.top/Article/details/gtwjffqzxm.html

JS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtizmngcnl.html

TS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gtbifrvjnm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gtxwfrjlgv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtajdbxsyw.html

Ruby: Dir.children("dir")
来源：http://dali.jqgufenzy.top/Article/details/gthztjiflk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtbwssieuc.html

[F09] 获取文件大小
来源：http://dali.pycfn.com/Article/details/gtwnydfyxg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtniodmbqu.html

PHP:  filesize("a.txt");
来源：http://dali.cashguo.top/Article/details/gtpbtlkrih.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gttymebzoy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtdkhnunrs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtkqayirkf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gthjwkgptp.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtxuhozxpv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jlsjyb.cn/Article/details/gtjrrhfztp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gtygxojnmz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtzwpampjl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258.top/Article/details/gthttacrdl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtfhwcpofk.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtgrakarjl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daria6918.cn/Article/details/gtnsriaudz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtvbsibbeh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtkubmaidh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtfpgdnxvq.html

[F11] 复制与移动文件
来源：http://dali.nwbrower.top/Article/details/gthylwfyfz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtmcvktfsq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gtqqeczodg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtnoyqobia.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtxccrslfa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpuztzinz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pycfn.com/Article/details/gtwvnbmvxl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtifcvgwpm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258888.top/Article/details/gtpnnlxzjd.html

[F12] CSV 读写
来源：http://dali.ehwqpu.com/Article/details/gttphjdgfo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pengpengdd.cyou/Article/details/gttwrmcfsq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yueranfly.top/Article/details/gtpubffvsp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.iojbl.cn/Article/details/gthntkuons.html

TS:   // 同上
来源：http://dali.kuanghao11.cn/Article/details/gtfnmbpezl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gtbpyjcgvf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gtmlkprkxf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gtkibmquig.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gzhubu.top/Article/details/gtmuqnrjxo.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtyddunotn.html

G. 面向对象
来源：http://dali.0kj1m.cn/Article/details/gtqrnsjzwj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtfispdeph.html

[G01] 定义类
来源：http://dali.wangshuangyany.cn/Article/details/gtqdzcikfq.html

Py:   class User: pass
来源：http://dali.smart0.xyz/Article/details/gtxthybbmv.html

PHP:  class User {}
来源：http://dali.pycfn.com/Article/details/gttoehxrvq.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gtyxvckxtq.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gthsuwiaiu.html

Java: class User {}
来源：http://dali.yuxming.cn/Article/details/gtpdswfqgb.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gtvmniouav.html

Ruby: class User; end
来源：http://dali.shuidangran.top/Article/details/gtruvidfld.html

C#:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtquundclg.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gtcsyqhuzt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xziqi.cn/Article/details/gtoeglmjtr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ydzc1.top/Article/details/gtdrwnlcen.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gtxrvqnlgz.html

TS:   constructor(public name: string) {}
来源：http://dali.sweek.top/Article/details/gtluiuhtwy.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgrvohuzy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sysykeji.top/Article/details/gtghadnwjs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gtjvcizicl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gtuqqjfkgj.html

[G03] 实例属性
来源：http://dali.cashguo.top/Article/details/gtphxrikjb.html

Py:   self.name = "x"
来源：http://dali.smart0.xyz/Article/details/gtjlmlwfic.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtohtrgckz.html

JS:   this.name = "x";
来源：http://dali.ppjwa.cn/Article/details/gtdzcfaqaj.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtzywmmqgl.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gtjxabennk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gtzebabtzm.html

Ruby: @name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtlkrhacsy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yongpay.top/Article/details/gtbzumpkhk.html

[G04] 定义方法
来源：http://dali.tianlin.xyz/Article/details/gttqklskzp.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtafvjztgt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gttgnzlenw.html

JS:   greet() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtlwzutnaw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtaehfvpdo.html

Java: String greet() { return name; }
来源：http://dali.yj20258.top/Article/details/gtkebccipr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtoljosggm.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsgyiahto.html

C#:   public string Greet() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtqvucurkh.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gtycovapkp.html

Py:   class Admin(User): pass
来源：http://dali.zhixingplan.top/Article/details/gtatfxnyim.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtjubzfflp.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtgvbmyvwm.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtxhbfuwvx.html

Java: class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtbygdrkne.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gtquyabqoi.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gtavdtqoav.html

C#:   class Admin : User {}
来源：http://dali.smart0.xyz/Article/details/gtokhmjnqr.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gtlvxtorxf.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gtqewmiqay.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gttqwyszrk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtgzkiwxos.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtyvcymtvy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtpoohfgiv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gtgzmptszi.html

Ruby: def greet; "admin"; end
来源：http://dali.xziqi.cn/Article/details/gtloilippm.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gtanyfwqeh.html

[G07] 调用父类方法
来源：http://dali.gogol.net.cn/Article/details/gtjfpcgjum.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcxuhlne.html

PHP:  parent::greet();
来源：http://dali.aibaodan.cn/Article/details/gtbkdryoti.html

JS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtwlpdcnec.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtdafwldkc.html

Java: super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtpwmsbfqr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gtldtasbyg.html

Ruby: super
来源：http://dali.jianghu66.top/Article/details/gtitcrmuii.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxviqdvf.html

[G08] 静态方法与属性
来源：http://dali.feifeiyinyue.top/Article/details/gtawsadqck.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sweek.top/Article/details/gtievbybrs.html

PHP:  public static function f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiuelczqo.html

JS:   static f() {}
来源：http://dali.nanxuanxn.top/Article/details/gttcyaponq.html

TS:   static f(): void {}
来源：http://dali.hnqzz.top/Article/details/gtieokgpgk.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gtwvnlyuvz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cqqwz.cn/Article/details/gtefhoesci.html

Ruby: def self.f; end
来源：http://dali.316326.xyz/Article/details/gtqzxmrsdn.html

C#:   public static void F() {}
来源：http://dali.haohaochexian.top/Article/details/gtfjmhobio.html

[G09] 接口 / 抽象类
来源：http://dali.tianlin.xyz/Article/details/gtsyfzthhf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlfzpkht.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gttvmepfnt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gtswcwohjc.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgufenzy.top/Article/details/gtrsrvnhey.html

Java: interface Shape { double area(); }
来源：http://dali.ydzc1.top/Article/details/gtiawmtxud.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gtarkogmkb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ybcxt.top/Article/details/gtalrjprzf.html

C#:   interface IShape { double Area(); }
来源：http://dali.sysykeji.top/Article/details/gtjxnjpxuv.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gtlpoddwdj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.snrcjt.cn/Article/details/gtdskpknyl.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtxputwwsl.html

JS:   #private 字段；其余公开
来源：http://dali.iojbl.cn/Article/details/gtuntpeysi.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gttxtaicny.html

Java: public / protected / private / 默认包级
来源：http://dali.dianchejie.cn/Article/details/gtonvsnfcr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tian-w.cn/Article/details/gtnstxebno.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gttdilhgmo.html

C#:   public / protected / private / internal
来源：http://dali.cheryme.top/Article/details/gtqvvzexyx.html

[G11] getter / setter
来源：http://dali.dashuyun.cn/Article/details/gtbjdzmlmh.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gtnnevudev.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtgrktxrut.html

JS:   get name() { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtfytgxpbq.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogghdcck.html

Java: public String getName() { return name; }
来源：http://dali.ivvv.top/Article/details/gtwmvkrikx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtfeplvklv.html

Ruby: attr_accessor :name
来源：http://dali.hywenlv.cn/Article/details/gtjfbflbfm.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpzcxmvfv.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtvflwwghk.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtuhfixuzd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtjdfluiiv.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gthydmtxsz.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtlnfydkyr.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtlehkhbrl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtmfzbxije.html

Ruby: def to_s; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtpnezhprj.html

C#:   public override string ToString() => Name;
来源：http://dali.yonumen.top/Article/details/gtdgdodsdk.html

[G13] 判断对象类型
来源：http://dali.iojbl.cn/Article/details/gtzazoifuh.html

Py:   isinstance(u, User)
来源：http://dali.mhx1999.top/Article/details/gtmgperadi.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtsphnaqzx.html

JS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gthrdwqznq.html

TS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtfkawtexp.html

Java: u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtxtqgogal.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangtech.top/Article/details/gthnjtgkys.html

Ruby: u.is_a?(User)
来源：http://dali.fzhhl.top/Article/details/gtmeqourlg.html

C#:   u is User
来源：http://dali.hnxiangtu.top/Article/details/gttapixqqp.html

[G14] 数据类 / record
来源：http://dali.ybcxt.top/Article/details/gtooptfawq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gtybafshwc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkralbwna.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhoulong.xyz/Article/details/gtclxmizen.html

TS:   type User = { name: string; age: number };
来源：http://dali.yvedp.cn/Article/details/gtxqtfdslx.html

Java: record User(String name, int age) {}
来源：http://dali.cqqwz.cn/Article/details/gticmxipid.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gtggqpyuso.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigufen.top/Article/details/gtverijeds.html

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfkcigcl.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gtjdksvjjp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aizwys.cn/Article/details/gtlaxepeil.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jyoumei.cn/Article/details/gthpydrzup.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gtyiytlczs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtjcoxgfpv.html

Java: enum Color { RED, GREEN }
来源：http://dali.zdqjudy.top/Article/details/gtghwlagqd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jianghu66.top/Article/details/gtzmoydygk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xziqi.cn/Article/details/gttuqxpsto.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtxowuhtjo.html

[G16] 对象转数组 / 字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpjlirut.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.9152youxi.cn/Article/details/gtchkwejen.html

PHP:  get_object_vars($obj);
来源：http://dali.jyoumei.cn/Article/details/gtcsjgalyw.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtllmapavw.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtjirnfpzu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuxming.cn/Article/details/gttopwnwvd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhixingplan.top/Article/details/gtjqqqoyvq.html

Ruby: obj.instance_variables
来源：http://dali.nanxuanxn.top/Article/details/gtkvdzatjl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtvcrrqcil.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtsxlkpqhu.html

H. 异常与错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctqhkucc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtwvbnwcma.html

[H01] try / catch 基础
来源：http://dali.gotoacloud.top/Article/details/gtqtphfwqf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gtatyjcmny.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gteghhzlvc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtslyxdlmb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtwxbkqkfv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangshuangyany.cn/Article/details/gtfzkdnrku.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gttkdnptnb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnxiangtu.top/Article/details/gtujxxvmop.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yueranfly.top/Article/details/gtnmasywoc.html

[H02] finally / ensure 收尾
来源：http://dali.snrcjt.cn/Article/details/gtcpkuuajh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfzzllji.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnndgynhb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtvnbbwuka.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtkkbqrpbc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtmbtjgzly.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shuidangran.top/Article/details/gtpufytzgn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.snrcjt.cn/Article/details/gtrouuoova.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtcgcqrlji.html

[H03] 主动抛出异常
来源：http://dali.dashuyun.cn/Article/details/gtftnfahvk.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhongyouzk.top/Article/details/gtiemgaqme.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gttpegeeqd.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtktzwboms.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtnvpedyma.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtgdpzmiqf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gtagmnomrc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zdqjudy.top/Article/details/gtmocwwsyp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtnbiqsayt.html

[H04] 自定义异常类型
来源：http://dali.jinqigfzy.top/Article/details/gthuzzkknf.html

Py:   class MyError(Exception): pass
来源：http://dali.pengpengdd.cyou/Article/details/gtacbconyw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtnzcjmvav.html

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gtahcdnmku.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtfvwmskzt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtuxkvnfvk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gttyxkgojm.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenjidiqi.icu/Article/details/gtubtilakb.html

C#:   class MyException : Exception {}
来源：http://dali.daxiang520.top/Article/details/gtzkllpgcb.html

[H05] 捕获特定类型
来源：http://dali.gotoacloud.top/Article/details/gttvetaiva.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gtsobqnrqs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gtmkvqmvvs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gtvyiqfidt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtuxuoktib.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gtifbfvksr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gtmghltwda.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gteeyngipn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gtgkvqygoy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbejmiqe.html

Py:   value = d.get("k") or default
来源：http://dali.c1oappe.top/Article/details/gtktirkqtx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gtpfrrxdgi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtpyizdnrg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtyojkyoch.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenlongwang.top/Article/details/gtdzqxwqzt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdhsxgen.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jianghu66.top/Article/details/gtdjmnagxz.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhengqikj.top/Article/details/gtcplvzbpb.html

[H07] 断言
来源：http://dali.yangfankeji.com/Article/details/gtklemibgw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aizwys.cn/Article/details/gthnnewrfl.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gtaftfdzny.html

JS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfskfofqs.html

TS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gthblpfylu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gtsxtyiwbw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gtkbkfbges.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pycfn.com/Article/details/gtxvvyibtg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtkssfsatl.html

[H08] 获取错误信息与堆栈
来源：http://dali.vqdsnc.cn/Article/details/gtupceaewd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pycfn.com/Article/details/gtjtjjgdbs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aizwys.cn/Article/details/gtdzyooctl.html

JS:   e.message;  e.stack
来源：http://dali.xuetiantiany.cn/Article/details/gtffwryszk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sxryk.cn/Article/details/gtsnggsvnr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dashuyun.cn/Article/details/gtvpyxomia.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gtwgymrsok.html

Ruby: e.message;  e.backtrace
来源：http://dali.9152youxi.cn/Article/details/gtbgmzvjai.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daria6918.cn/Article/details/gtduwtbrvz.html

[H09] 带错误码的异常
来源：http://dali.zhiwuduotai.top/Article/details/gtjungqbef.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ivvv.top/Article/details/gtsvxzfxuq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.iojbl.cn/Article/details/gtvdmwybdt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cheryme.top/Article/details/gtwwljhsbf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guannengcc.top/Article/details/gtcqnbuexe.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sufxvd.cn/Article/details/gtdaoakybi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuanzhike.top/Article/details/gtfigaryog.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gtcnkrctam.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yanxiufei.cn/Article/details/gtxoklxhnp.html

[H10] 资源自动释放
来源：http://dali.jinqigufen.top/Article/details/gtisligjbc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.redwolf501.top/Article/details/gtaerotsaz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.iojbl.cn/Article/details/gtorandcmq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gtxrdixljs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtxyoehvgl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daxiang520.top/Article/details/gtprtmixcc.html

Go:   defer f.Close()
来源：http://dali.dianchejie.cn/Article/details/gtcaezvttj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjibatifh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtenngsnhy.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtpgcrbmga.html

I. 正则表达式
来源：http://dali.meibo888.top/Article/details/gtknrxnvtq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtypbtfmed.html

[I01] 判断是否匹配
来源：http://dali.snrcjt.cn/Article/details/gtbzdbrrpa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtzepdzzfp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtanxzstpj.html

JS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gtbsgjzurq.html

TS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtxwsgzykc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tian-w.cn/Article/details/gttqyojrtf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tian-w.cn/Article/details/gtsqzsdmtx.html

Ruby: s.match?(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtaptnckvy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gtxdfiwzlu.html


<!-- 参考信息 -->