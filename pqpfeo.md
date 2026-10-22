代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sysykeji.top/Article/details/gttofdlkrj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gtizhbddjj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gtyubajxwt.html

[F08] 遍历目录
来源：http://dali.meibo888.top/Article/details/gtsznhbkzl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shuidangran.top/Article/details/gtdinzuixg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gtvdzrqguk.html

JS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtdemeztvj.html

TS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtjfblesxm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gtzfdswtus.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtzlebaquw.html

Ruby: Dir.children("dir")
来源：http://dali.guannengcc.top/Article/details/gtjmhcfzbz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtodvaddwb.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gthcqegcii.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtkjecgiwz.html

PHP:  filesize("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtwhfnuggc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gtuvgyexlt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtyzwlijzs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtnbaayoul.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gtbojvdqyr.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtkanbbqeh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cqqwz.cn/Article/details/gtuqtqfqcu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shzxlz.cn/Article/details/gtzsgnqzjd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlcbqpwp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtaoebdvdl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtlcnapeth.html

TS:   path.extname("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtgfdfkhzx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhoulong.xyz/Article/details/gtvwsbalfk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtxecckcji.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gthxqxidmd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtiegqxlha.html

[F11] 复制与移动文件
来源：http://dali.aibaodan.cn/Article/details/gtdzlyopxa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnfotwbx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuanzx.com/Article/details/gtzancdceg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtnjotwcaf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtrkhjesqx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shuidangran.top/Article/details/gtphbjcypw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gaohongyu789.top/Article/details/gtjowbebpz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqkxlgfg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangshuangyany.cn/Article/details/gtwcwctlsm.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gtevfaawsn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xinyue.icu/Article/details/gtqceyjzil.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fengsongda.top/Article/details/gtfocoszti.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jlsjyb.cn/Article/details/gtbjykdydz.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gtzegetqsm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhongyouzk.top/Article/details/gtlnvfcfby.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuanzhike.top/Article/details/gtuedazivr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zdqjudy.top/Article/details/gtolkhwgwl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jianghu66.top/Article/details/gtymgwgtty.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtfrildgoo.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gtgzzkevwy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtzrbfccgu.html

[G01] 定义类
来源：http://dali.hammf.cn/Article/details/gtdqlpumsx.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gtbraedmky.html

PHP:  class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtxmmswyep.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gthoxnjdwb.html

TS:   class User { name: string = ""; }
来源：http://dali.fzhhl.top/Article/details/gthvbadqzb.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gtkdrkgftr.html

Go:   type User struct { Name string }
来源：http://dali.tanke756.top/Article/details/gtcbegwyce.html

Ruby: class User; end
来源：http://dali.havefunace.top/Article/details/gtnrjnwzjz.html

C#:   class User {}
来源：http://dali.birdmap.top/Article/details/gtominaukg.html

[G02] 构造函数
来源：http://dali.jiagoushi.top/Article/details/gtuxecwttx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sysykeji.top/Article/details/gthkympbcd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nwbrower.top/Article/details/gtdxuqvnuq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtbsqgphwr.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtvxntwwaz.html

Java: User(String name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gttuoordns.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenjidiqi.icu/Article/details/gtgozymbvo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxinkj.top/Article/details/gtgakxhxng.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtpkdnwwcz.html

[G03] 实例属性
来源：http://dali.chenlongwang.top/Article/details/gtpwrbxncn.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtxzglqion.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtndxqbqur.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowcqjswz.html

TS:   name: string = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtbtgzdhok.html

Java: private String name;
来源：http://dali.ehwqpu.com/Article/details/gtannanlih.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgufenzy.top/Article/details/gtiobowwwg.html

Ruby: @name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtxpndsgfl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtvujrjfkk.html

[G04] 定义方法
来源：http://dali.nwbrower.top/Article/details/gtwmpzvpps.html

Py:   def greet(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gtnrzrskws.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzgsxjega.html

JS:   greet() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtnmalqujp.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtnhgductw.html

Java: String greet() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtuqbfjznk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtwnlhiocr.html

Ruby: def greet; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtccxehehm.html

C#:   public string Greet() => Name;
来源：http://dali.havefunace.top/Article/details/gtsvkyycbr.html

[G05] 继承
来源：http://dali.fzhhl.top/Article/details/gtbtuukhpy.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gtohaojxbh.html

PHP:  class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtlvlciacu.html

JS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtcwqashqd.html

TS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtprjrizoc.html

Java: class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtrkotmhtk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.feifeiyinyue.top/Article/details/gtmtgleamk.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjqvaewh.html

C#:   class Admin : User {}
来源：http://dali.cucudq.cn/Article/details/gtsfecyrpa.html

[G06] 重写方法
来源：http://dali.shzxlz.cn/Article/details/gtjbahdenk.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgufenzy.top/Article/details/gtuseznlgh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtoegdjlhi.html

JS:   greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtrhielxop.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtbvywgmnc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqwyxjft.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shangyingyoupin.top/Article/details/gtgnrckwbh.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gtislhjoqe.html

C#:   public override string Greet() => "admin";
来源：http://dali.smart0.xyz/Article/details/gtgootwuwa.html

[G07] 调用父类方法
来源：http://dali.cdnleiting.top/Article/details/gtqtkuqukf.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gtrfszlteq.html

PHP:  parent::greet();
来源：http://dali.aibaodan.cn/Article/details/gtyophlzkh.html

JS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtfvkqjyns.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtviltdysu.html

Java: super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtwhmiloea.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ppjwa.cn/Article/details/gtljdgixtq.html

Ruby: super
来源：http://dali.bjfxy.top/Article/details/gthddlxiyr.html

C#:   base.Greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbnowceo.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gtgeojkhpt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.meibo888.top/Article/details/gtbneohinq.html

PHP:  public static function f() {}
来源：http://dali.guowangkeji.top/Article/details/gtxkucsedw.html

JS:   static f() {}
来源：http://dali.nanxinkj.top/Article/details/gtxxynbanp.html

TS:   static f(): void {}
来源：http://dali.zdqjudy.top/Article/details/gtzydszvzg.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtowttgrea.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gtocotkacy.html

Ruby: def self.f; end
来源：http://dali.ydzc1.top/Article/details/gttssmfcxn.html

C#:   public static void F() {}
来源：http://dali.hysaishi.cn/Article/details/gtykhjyznq.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gtgykmuzvq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guannengcc.top/Article/details/gtdksjmmik.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.9152youxi.cn/Article/details/gtgxryrsnu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gtejfxqypf.html

TS:   interface Shape { area(): number; }
来源：http://dali.ivvv.top/Article/details/gttblcbakm.html

Java: interface Shape { double area(); }
来源：http://dali.sufxvd.cn/Article/details/gtjjhyuhcm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cucudq.cn/Article/details/gttwzzwfnh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cdnleiting.top/Article/details/gtkkiorrjp.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnqzz.top/Article/details/gtcgjgfoxe.html

[G10] 访问控制
来源：http://dali.cucudq.cn/Article/details/gtgihyfmea.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gtjmwlmbwl.html

PHP:  public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtoixsyhjv.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gtwwihjpoo.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtbsilsbdc.html

Java: public / protected / private / 默认包级
来源：http://dali.gaohongyu789.top/Article/details/gtvkmwkihe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gttmblzdxj.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkfkmhbt.html

C#:   public / protected / private / internal
来源：http://dali.cheryme.top/Article/details/gtscgccuwg.html

[G11] getter / setter
来源：http://dali.jlsjyb.cn/Article/details/gtuiozumzk.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gtdmyhaqup.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtwlpdthtg.html

JS:   get name() { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gtmeucdytr.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtedghypxh.html

Java: public String getName() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgxtjrvbt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhhvvcwx.html

Ruby: attr_accessor :name
来源：http://dali.yuanzhike.top/Article/details/gtbhopzoew.html

C#:   public string Name { get; set; }
来源：http://dali.dashuyun.cn/Article/details/gtdrwjqmfw.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gteaprwsqr.html

Py:   def __str__(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gteblwpibu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtusvvtqlw.html

JS:   toString() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtlfysclfe.html

TS:   toString(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtejwpgoje.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtljcenuwt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtxidvpxam.html

Ruby: def to_s; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtjraiqmux.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gteytjrpml.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gtzvdixgre.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gtpptsgygo.html

PHP:  $u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtgsweynow.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtkqownnhm.html

TS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtqspnhktj.html

Java: u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtakbwcped.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.bjfxy.top/Article/details/gtltjmbrqe.html

Ruby: u.is_a?(User)
来源：http://dali.daria6918.cn/Article/details/gtwaolsfpl.html

C#:   u is User
来源：http://dali.0kj1m.cn/Article/details/gtfiuxybyb.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gtstytnxjq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuxming.cn/Article/details/gtfuofrije.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gtggvskqyi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.bjfxy.top/Article/details/gtlgkhnmtz.html

TS:   type User = { name: string; age: number };
来源：http://dali.fengsongda.top/Article/details/gtvtzqkjuj.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gtuvuisruj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gtqccinbaz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gtrtoklehk.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gtphbzixur.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gtykwhbsjy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqqclfet.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigfzy.top/Article/details/gtakxlhhks.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj202588.top/Article/details/gtwrwxwkqw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gtgkpvgpjy.html

Java: enum Color { RED, GREEN }
来源：http://dali.9152youxi.cn/Article/details/gticozgmic.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sufxvd.cn/Article/details/gtbzvpuefi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigufen.top/Article/details/gtcwazphat.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtkreprbnw.html

[G16] 对象转数组 / 字典
来源：http://dali.gogol.net.cn/Article/details/gtvunayhph.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zdqjudy.top/Article/details/gtvkrpiwzd.html

PHP:  get_object_vars($obj);
来源：http://dali.xuetiantiany.cn/Article/details/gtekbuaajx.html

JS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtmnngbuej.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtcotyeewp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigfzy.top/Article/details/gtszghxcgf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqkrqtwp.html

Ruby: obj.instance_variables
来源：http://dali.hnqzz.top/Article/details/gtvvouownd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtiwmvwbsf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtognvbipl.html

H. 异常与错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gtolurqebz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gttuwoclfe.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gtpgvaubkv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtwcxczv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gtvxzyeubj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtotukoesg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtjrhbmhta.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.birdmap.top/Article/details/gttlrxxbgn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sysykeji.top/Article/details/gtioisrmfs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cucudq.cn/Article/details/gtbypkkhjj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhengqikj.top/Article/details/gtsyyujmhc.html

[H02] finally / ensure 收尾
来源：http://dali.pycfn.com/Article/details/gtuorhuzby.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pycfn.com/Article/details/gtfrqnapab.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtxrcgspau.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtkrrqmnfy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtppwkutht.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtxxuxtqhq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gtbdyxrlcz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gtwrgdbtrm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtkrpzyzed.html

[H03] 主动抛出异常
来源：http://dali.sxryk.cn/Article/details/gtfrtlmsvx.html

Py:   raise ValueError("错误信息")
来源：http://dali.daria6918.cn/Article/details/gtwnqzryvy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtkdtiahpa.html

JS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdqovulp.html

TS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtcotjaamz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtmqrifqar.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dianchejie.cn/Article/details/gtwluyuina.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tian-w.cn/Article/details/gtmbosewqx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtyswtnqlj.html

[H04] 自定义异常类型
来源：http://dali.vqdsnc.cn/Article/details/gtmqfyuqkn.html

Py:   class MyError(Exception): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfkohxqi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekhqpyfj.html

JS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtaslrakxp.html

TS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gttuibjiim.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gtbeuutxqt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenlongwang.top/Article/details/gtlppsqpnl.html

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gtwqpdlmra.html

C#:   class MyException : Exception {}
来源：http://dali.gogol.net.cn/Article/details/gtznspadgg.html

[H05] 捕获特定类型
来源：http://dali.sweek.top/Article/details/gtzvagozmf.html

Py:   except ValueError as e:
来源：http://dali.aibaodan.cn/Article/details/gtniuqfhcf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gtyilhtivh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtkyjbzeaz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gtosweorny.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ybcxt.top/Article/details/gtrqjhzoha.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhixingplan.top/Article/details/gtgvumjuwn.html

Ruby: rescue ArgumentError => e
来源：http://dali.ybcxt.top/Article/details/gtzwbhindj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gtiixxlvyb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aizwys.cn/Article/details/gtgjeevsig.html

Py:   value = d.get("k") or default
来源：http://dali.meibo888.top/Article/details/gtntqzavvf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtdpfwbjtm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gteiqzbney.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtbmejdarw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hammf.cn/Article/details/gtdlfgvjud.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewpyodmf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gtcymgwfrq.html

C#:   obj?.A?.B ?? default
来源：http://dali.9152youxi.cn/Article/details/gtukbnoriw.html

[H07] 断言
来源：http://dali.chenjidiqi.icu/Article/details/gtsuamajad.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xylfe.cn/Article/details/gtrcmfqccu.html

PHP:  assert($x > 0);
来源：http://dali.fengsongda.top/Article/details/gtmtvxytbd.html

JS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtezigrabu.html

TS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtrriszcjt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.0kj1m.cn/Article/details/gtmjxahypw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xylfe.cn/Article/details/gtlrsxlvuq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gtflbynryh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtmgotbomi.html

[H08] 获取错误信息与堆栈
来源：http://dali.guannengcc.top/Article/details/gtgngwyxng.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gtrmbuazni.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gtuwnlunvp.html

JS:   e.message;  e.stack
来源：http://dali.dashuyun.cn/Article/details/gtwfkcanjf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gtykhwjwrw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.haohaochexian.top/Article/details/gtbmcjmprq.html

Go:   err.Error()
来源：http://dali.guowangkeji.top/Article/details/gtzqyswttg.html

Ruby: e.message;  e.backtrace
来源：http://dali.ppjwa.cn/Article/details/gtaidjmsaq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.c1oappe.top/Article/details/gtlsraptqe.html

[H09] 带错误码的异常
来源：http://dali.gotoacloud.top/Article/details/gtderijxkt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.quarkkingdee.top/Article/details/gthnjennyd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.feifeiyinyue.top/Article/details/gtvmrscctc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gtxgetnugy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dianchejie.cn/Article/details/gtudorocqc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cqqwz.cn/Article/details/gtrjvbatmb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xinyue.icu/Article/details/gtoenoiucx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhoulong.xyz/Article/details/gtgxjrwqhk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gaohongyu789.top/Article/details/gtbpbilvrq.html

[H10] 资源自动释放
来源：http://dali.quarkkingdee.top/Article/details/gtbopybcrd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hywenlv.cn/Article/details/gtgkoncgne.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tianlin.xyz/Article/details/gtshqynvuw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gtikhxhhec.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gteucuwllj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbutoenno.html

Go:   defer f.Close()
来源：http://dali.yanxiufei.cn/Article/details/gtrhloyosb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xinyue.icu/Article/details/gtsamfdwhq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtdjtslxkj.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtisrsjr.html

I. 正则表达式
来源：http://dali.yj20258888.top/Article/details/gtshafttoc.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtnnthvqnu.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gtmpvqyshg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gtrvbrkjjy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtwbjksxuz.html

JS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtlgxztqje.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gtrdhwfouc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenlongwang.top/Article/details/gtjegujiow.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.svipenyu.cn/Article/details/gttttlkbnx.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmnbliwl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqtfkcqh.html


<!-- 参考信息 -->