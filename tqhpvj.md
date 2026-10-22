代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtfpidhxqg.html

C#:   File.Delete("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtsycvbvdj.html

[F07] 创建目录（含多级）
来源：http://dali.smart0.xyz/Article/details/gthtxghxgo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.0kj1m.cn/Article/details/gtprksuzzu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cashguo.top/Article/details/gtiexmrkmx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gtzqhlssbo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtfbcmaogq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tianlin.xyz/Article/details/gtcmbufaaf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yongpay.top/Article/details/gtxixmkqsl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yanxiufei.cn/Article/details/gtfvlxdjmu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yongpay.top/Article/details/gtqxeyaszi.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gtjvuzafzz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gtavlhzwxe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cheryme.top/Article/details/gtcjbcsglr.html

JS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gtaywxcsgo.html

TS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gtodhcnzdg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtzopnvqhm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtqfchrnsf.html

Ruby: Dir.children("dir")
来源：http://dali.xziqi.cn/Article/details/gtihacwapo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuanzx.com/Article/details/gtvxxayewc.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gtlaefbtoo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtbexagmye.html

PHP:  filesize("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtubmdlqhg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtnvtvbkxl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtmbwbvihb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gthndrbebf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gtjpmzgdqh.html

Ruby: File.size("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtovkmgvkj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gtsnzrbsde.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xinyue.icu/Article/details/gtdrvozbti.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtqzcukgkj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.bjfxy.top/Article/details/gterrknzgh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtjpuplfth.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtfcftdjlx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daxiang520.top/Article/details/gtylbauabg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtuujwsfgh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtsxzcgwzx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gttpbergiv.html

[F11] 复制与移动文件
来源：http://dali.yj20258.top/Article/details/gtfdcexwzm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtfqsjbdmu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fengsongda.top/Article/details/gtjaowlitt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtcwbghigg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gthczebrqo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuanzx.com/Article/details/gtbyeekcul.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sufxvd.cn/Article/details/gtbqwycglh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtxuxavnkx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cashguo.top/Article/details/gtmztzfqcs.html

[F12] CSV 读写
来源：http://dali.yonumen.top/Article/details/gtmcygphuh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuanzhike.top/Article/details/gtezmnxhzs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gtpkcwenlr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.bjfxy.top/Article/details/gtrjqpoesn.html

TS:   // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gtzaavgldb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.meibo888.top/Article/details/gtyrpzmnkx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tian-w.cn/Article/details/gtmcjatpzf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxuanxn.top/Article/details/gtjdczuyts.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gtcvdnqfok.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtewubdhli.html

G. 面向对象
来源：http://dali.xinyue.icu/Article/details/gtrorpqazr.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtpjqsrdpl.html

[G01] 定义类
来源：http://dali.shzxlz.cn/Article/details/gtgafrxlea.html

Py:   class User: pass
来源：http://dali.guannengcc.top/Article/details/gtnzfvzpxg.html

PHP:  class User {}
来源：http://dali.aizwys.cn/Article/details/gtxpifgoei.html

JS:   class User {}
来源：http://dali.yj202588.top/Article/details/gtkwdnkpit.html

TS:   class User { name: string = ""; }
来源：http://dali.xziqi.cn/Article/details/gtondllhdb.html

Java: class User {}
来源：http://dali.andypj.xyz/Article/details/gtozackthd.html

Go:   type User struct { Name string }
来源：http://dali.hammf.cn/Article/details/gtqwfoapcq.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gtrmkefjoc.html

C#:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtioyilgin.html

[G02] 构造函数
来源：http://dali.sweek.top/Article/details/gtstuuvayi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gogol.net.cn/Article/details/gtxtcdppxq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guannengcc.top/Article/details/gthumvxaen.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtywiclwnm.html

TS:   constructor(public name: string) {}
来源：http://dali.guowangkeji.top/Article/details/gtopsoxnmi.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvwneacht.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gtjvdmwwky.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gtgrwayxhq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hammf.cn/Article/details/gtclwjggoh.html

[G03] 实例属性
来源：http://dali.316326.xyz/Article/details/gtwxoqzvrn.html

Py:   self.name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfliasdwz.html

PHP:  public string $name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtyivwtgxv.html

JS:   this.name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtcwdzcclq.html

TS:   name: string = "x";
来源：http://dali.xinyue.icu/Article/details/gtbgmyqjsl.html

Java: private String name;
来源：http://dali.jlsjyb.cn/Article/details/gtlpkuzpal.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gotoacloud.top/Article/details/gtkdabnany.html

Ruby: @name = "x"
来源：http://dali.yj20258.top/Article/details/gtvyhclnzh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenzaomai.com/Article/details/gtwxyvfepx.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gttpxnzkri.html

Py:   def greet(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtwqbaxsnr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtnnghmcdj.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmmygbnv.html

TS:   greet(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtjhoqtrkc.html

Java: String greet() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtctkdfpnc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gtvuarnhpp.html

Ruby: def greet; @name; end
来源：http://dali.fzhhl.top/Article/details/gtmgaxusmo.html

C#:   public string Greet() => Name;
来源：http://dali.gotoacloud.top/Article/details/gtfrwizbiv.html

[G05] 继承
来源：http://dali.yonumen.top/Article/details/gtqkunkten.html

Py:   class Admin(User): pass
来源：http://dali.yanxiufei.cn/Article/details/gthaqkfomn.html

PHP:  class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gttdgzhdjw.html

JS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtbrgivvxh.html

TS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtgticey.html

Java: class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtvudsbplr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.bjfxy.top/Article/details/gtzrvfpnxq.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gtrqkectuz.html

C#:   class Admin : User {}
来源：http://dali.hnxiangtu.top/Article/details/gtycannorn.html

[G06] 重写方法
来源：http://dali.shangyingyoupin.top/Article/details/gtftqpngkz.html

Py:   def greet(self): return "admin"
来源：http://dali.pengpengdd.cyou/Article/details/gtbbgjclcl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtnosnkath.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmsnhwbhj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtgnuafdom.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtzapywhqq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gtyutrujff.html

Ruby: def greet; "admin"; end
来源：http://dali.chenzaomai.com/Article/details/gtbzpnkmyf.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gtmdpkuhkh.html

[G07] 调用父类方法
来源：http://dali.pycfn.com/Article/details/gthlibdlll.html

Py:   super().greet()
来源：http://dali.9152youxi.cn/Article/details/gtogcdwobp.html

PHP:  parent::greet();
来源：http://dali.ppjwa.cn/Article/details/gtddztkedd.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtjptejwzm.html

TS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtubakvljz.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gtlmjrjtpq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tianlin.xyz/Article/details/gtiyroxvfe.html

Ruby: super
来源：http://dali.hnxiangtu.top/Article/details/gtriiaziys.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gttrnqbrij.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gtyzwocsnq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dianchejie.cn/Article/details/gtwkfhmsyu.html

PHP:  public static function f() {}
来源：http://dali.zhixingplan.top/Article/details/gtwotdqiwx.html

JS:   static f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtidpkdkbp.html

TS:   static f(): void {}
来源：http://dali.zycfv.cn/Article/details/gtthldxrqc.html

Java: static void f() {}
来源：http://dali.yangfankeji.com/Article/details/gtlxmjzdlg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.havefunace.top/Article/details/gtrralrybf.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gtdqillsof.html

C#:   public static void F() {}
来源：http://dali.yanxiufei.cn/Article/details/gtamzsgezg.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gtwkhecagu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gtsaahckzm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yueranfly.top/Article/details/gtgfsphoww.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gtlnxvswzc.html

TS:   interface Shape { area(): number; }
来源：http://dali.nwbrower.top/Article/details/gtxrhjaxat.html

Java: interface Shape { double area(); }
来源：http://dali.daxiang520.top/Article/details/gtrnrxnrcd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gtcxgtkmcb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.birdmap.top/Article/details/gtusdcummr.html

C#:   interface IShape { double Area(); }
来源：http://dali.cashguo.top/Article/details/gtrayzvobe.html

[G10] 访问控制
来源：http://dali.redwolf501.top/Article/details/gtqtpzoyig.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pengpengdd.cyou/Article/details/gtsijjjbso.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gtjjdovcii.html

JS:   #private 字段；其余公开
来源：http://dali.sufxvd.cn/Article/details/gtcwlesiqc.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtzyswcmmq.html

Java: public / protected / private / 默认包级
来源：http://dali.aibaodan.cn/Article/details/gtenkmnnyl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ppjwa.cn/Article/details/gtbouekrug.html

Ruby: public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtayueytuo.html

C#:   public / protected / private / internal
来源：http://dali.svipenyu.cn/Article/details/gtbuoqcwzy.html

[G11] getter / setter
来源：http://dali.xylfe.cn/Article/details/gtrpcdehvk.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gtwsamzdmq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gteqhjmrff.html

JS:   get name() { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gttoubpxeh.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtudxpifwf.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtaackjkym.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtlnwyimtz.html

Ruby: attr_accessor :name
来源：http://dali.jlsjyb.cn/Article/details/gtkqnvpddx.html

C#:   public string Name { get; set; }
来源：http://dali.shangyingyoupin.top/Article/details/gtelblrups.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gtfqszaevz.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtbkoqtbge.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtvscphyuz.html

JS:   toString() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteftxidru.html

TS:   toString(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtawnotdue.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtgmmnvker.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtywnszslt.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gtujivtift.html

C#:   public override string ToString() => Name;
来源：http://dali.hammf.cn/Article/details/gtvvwolbqo.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gtmzpyswyf.html

Py:   isinstance(u, User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqjnutns.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtgoyucveu.html

JS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtnflayisi.html

TS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtnmvofeqv.html

Java: u instanceof User
来源：http://dali.316326.xyz/Article/details/gtwcxhayek.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pycfn.com/Article/details/gtxvxaiptq.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gtkbnfznak.html

C#:   u is User
来源：http://dali.nanxinkj.top/Article/details/gtgkhptgcr.html

[G14] 数据类 / record
来源：http://dali.snrcjt.cn/Article/details/gtmsvcncur.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nwbrower.top/Article/details/gtsdzsfwea.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.snrcjt.cn/Article/details/gtnjjbsxpc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dashuyun.cn/Article/details/gtnyfjagwk.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gtuzctccks.html

Java: record User(String name, int age) {}
来源：http://dali.redwolf501.top/Article/details/gtsyucntlx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigufen.top/Article/details/gtfuhfqjik.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gtbpmujmas.html

C#:   record User(string Name, int Age);
来源：http://dali.daria6918.cn/Article/details/gtsxxdtqqi.html

[G15] 枚举
来源：http://dali.0kj1m.cn/Article/details/gtubwtgtan.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hywenlv.cn/Article/details/gtdjsxrlin.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cucudq.cn/Article/details/gtzpntcusw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gteepcndih.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtrgmmorun.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gtmriyrqfr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gtmgucwlsf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.quarkkingdee.top/Article/details/gtqpmnfbbl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtwaexaclg.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gtcpgkjlzt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.quarkkingdee.top/Article/details/gtixxwwsiz.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxinkj.top/Article/details/gtqsdiqrig.html

JS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gtuadkzmcr.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtulcvrjts.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbykustf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hongshengwenyu.top/Article/details/gtzhgoeawn.html

Ruby: obj.instance_variables
来源：http://dali.guowangkeji.top/Article/details/gtbpogiocw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtblknnpne.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtdylqvglq.html

H. 异常与错误处理
来源：http://dali.guowangkeji.top/Article/details/gtgzeiaast.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtstxdjtzs.html

[H01] try / catch 基础
来源：http://dali.iojbl.cn/Article/details/gthiopofzs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gtfyrjixug.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gtclphdkvm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtdhhbomxg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtwihlxgsw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewdpzigq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gthacwbqcy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gtjtubrnys.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yueranfly.top/Article/details/gthfsrcbdz.html

[H02] finally / ensure 收尾
来源：http://dali.jqgufenzy.top/Article/details/gthlhnhrwy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gtgknuoxoj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtuezrzusa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gteogiarmm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtnhtivlah.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtfhzqvzwk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.bjfxy.top/Article/details/gtzgjwgjhp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuxming.cn/Article/details/gtnyhajtsi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtwnvukrjc.html

[H03] 主动抛出异常
来源：http://dali.yj20258888.top/Article/details/gtdjjcmhmw.html

Py:   raise ValueError("错误信息")
来源：http://dali.xinyue.icu/Article/details/gtxjgcbkbn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtbvmbruon.html

JS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtfbxoozxs.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtsvmzkkri.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtdrhsdfid.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gtrtsjdzbl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gthqwaijkr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfysurie.html

[H04] 自定义异常类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqchkdtbl.html

Py:   class MyError(Exception): pass
来源：http://dali.wangdashe.top/Article/details/gtywhguyfw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtaaqdsfnu.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmyjpwtk.html

TS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtjwzjgrhn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtihntpgtw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gtwoitouib.html

Ruby: class MyError < StandardError; end
来源：http://dali.ivvv.top/Article/details/gtavpsacpv.html

C#:   class MyException : Exception {}
来源：http://dali.yueranfly.top/Article/details/gtxpbtsshm.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gtaxwuzfdm.html

Py:   except ValueError as e:
来源：http://dali.0kj1m.cn/Article/details/gtvcxedngm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258888.top/Article/details/gtukjicsap.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtnbmgghgn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gtubhclfzu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtfiszpjaq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shangyingyoupin.top/Article/details/gtzrewlufj.html

Ruby: rescue ArgumentError => e
来源：http://dali.cucudq.cn/Article/details/gtdgwzrncc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gtbdwepnnl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sufxvd.cn/Article/details/gtaapmlagz.html

Py:   value = d.get("k") or default
来源：http://dali.nanxuanxn.top/Article/details/gtccxsdsbe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gtphtxkesc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtoldrfiiu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gtwvwuoapc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gzhubu.top/Article/details/gttpzfdttc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jlsjyb.cn/Article/details/gtlnzxxosq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gaohongyu789.top/Article/details/gtvybyogdp.html

C#:   obj?.A?.B ?? default
来源：http://dali.haohaochexian.top/Article/details/gtpyirjhqh.html

[H07] 断言
来源：http://dali.cdnleiting.top/Article/details/gtpdxvffre.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yanxiufei.cn/Article/details/gtkjvbffni.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gtuvlttnsd.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtotwfkkhf.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtbbisgxbs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gtprekgogj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jiagoushi.top/Article/details/gtmbypexzp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuetiantiany.cn/Article/details/gtihuiruxp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtjgwusgsa.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gtwuydpuqm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgufenzy.top/Article/details/gtkmpxwavz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gogol.net.cn/Article/details/gtnghpuabn.html

JS:   e.message;  e.stack
来源：http://dali.cucudq.cn/Article/details/gtubdmwang.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.kuanghao11.cn/Article/details/gtfapoyspi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sweek.top/Article/details/gtkkmuwtji.html

Go:   err.Error()
来源：http://dali.jyoumei.cn/Article/details/gtvmufypoj.html

Ruby: e.message;  e.backtrace
来源：http://dali.cdnleiting.top/Article/details/gtocohhrqu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gtsavtgawr.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtssxqpfew.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dianchejie.cn/Article/details/gtmoppztph.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtodljtisy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.smart0.xyz/Article/details/gtqdrryrmb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ydzc1.top/Article/details/gtsjktauik.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.snrcjt.cn/Article/details/gtljvyxsfz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gtjthzfjdd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fengsongda.top/Article/details/gtgusilteh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.mhx1999.top/Article/details/gtgnnvyfsq.html

[H10] 资源自动释放
来源：http://dali.jinqigfzy.top/Article/details/gtfgxpvymf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daxiang520.top/Article/details/gtbmmjokpm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gtsyckkchf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtnwshrrhd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtdlkuuamr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gtotxuxxyg.html

Go:   defer f.Close()
来源：http://dali.cdnleiting.top/Article/details/gtfexcfhvi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xinyue.icu/Article/details/gtniheohzg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtakrlpshu.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtdfdddngc.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gtgwamallc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtticxknyi.html

[I01] 判断是否匹配
来源：http://dali.fengsongda.top/Article/details/gtqmudqlxh.html


<!-- 参考信息 -->