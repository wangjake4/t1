代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnxiangtu.top/Article/details/gtloyvzldp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gtixqkeibo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gthwftloyo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigufen.top/Article/details/gtvpmswkjy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gthdlekjuq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258888.top/Article/details/gtngofdbuv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gtfkcsouqp.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gthtvyfuni.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigfzy.top/Article/details/gtqkdgiuws.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangdashe.top/Article/details/gtmdsudzqg.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gtkuclmres.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtuansgmnn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gtccopmtgj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tanke756.top/Article/details/gtpdymncpb.html

Ruby: Dir.children("dir")
来源：http://dali.9152youxi.cn/Article/details/gtyhggupii.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigufen.top/Article/details/gtlabxvuja.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gtorpkbrnc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtgpflegwb.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtftgqcdmv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcmhaong.html

TS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gtoklwyfqp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtshsdcihr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gtuxdyamfs.html

Ruby: File.size("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtjrywokgy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gtcogquodi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gtsetntocc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtibyqgeux.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtsppyrdyp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtvbblqiyi.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtrldsghmv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yonumen.top/Article/details/gtujlpidbj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtogcsdhqe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtlaslevwo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtftwjkbhj.html

[F11] 复制与移动文件
来源：http://dali.xuetiantiany.cn/Article/details/gtaytkliwv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtuxttvvqv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zdqjudy.top/Article/details/gtnjngszpd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtezfibvvp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtsudilxxh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtbwjqupel.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pycfn.com/Article/details/gthfbihoqg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtibhbnmjl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ivvv.top/Article/details/gtfzzgrvps.html

[F12] CSV 读写
来源：http://dali.ehwqpu.com/Article/details/gtcvsaozik.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangdashe.top/Article/details/gthtpcahzm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.birdmap.top/Article/details/gtfdmsxvnf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yanxiufei.cn/Article/details/gtptvrjetc.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gtzedaiqpf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gtlfocgunp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gthtvuikqk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gtzgwyfjjo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gtfwbnatfk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtqbiynqmc.html

G. 面向对象
来源：http://dali.svipenyu.cn/Article/details/gtcozjhlhp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtjmksezjz.html

[G01] 定义类
来源：http://dali.vqdsnc.cn/Article/details/gtktafpxnm.html

Py:   class User: pass
来源：http://dali.guannengcc.top/Article/details/gtflzpwovy.html

PHP:  class User {}
来源：http://dali.yonumen.top/Article/details/gthrwydcgb.html

JS:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtcpaaojml.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhtyulof.html

Java: class User {}
来源：http://dali.jianghu66.top/Article/details/gtazgpdfac.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gtxwrbxhko.html

Ruby: class User; end
来源：http://dali.sxryk.cn/Article/details/gtmncmvfdx.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtroiygdst.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtmqiavoem.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gaohongyu789.top/Article/details/gtfatoxvqm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gtpjzefnym.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtefjngwek.html

TS:   constructor(public name: string) {}
来源：http://dali.xuanzx.com/Article/details/gtcfmkopkp.html

Java: User(String name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtcmonhixw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.316326.xyz/Article/details/gtfjucidcy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gthxjgwhqm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gtsefhzgyo.html

[G03] 实例属性
来源：http://dali.cheryme.top/Article/details/gtutmtjqgf.html

Py:   self.name = "x"
来源：http://dali.hfpthk.cn/Article/details/gtgtcprssx.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtbsqnijgc.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtvgsnngxv.html

TS:   name: string = "x";
来源：http://dali.jianghu66.top/Article/details/gtojbbemim.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gtqsjrzqwk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gthizhbnxx.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gtgebmukiq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuanzhike.top/Article/details/gtmwszqfpe.html

[G04] 定义方法
来源：http://dali.cqqwz.cn/Article/details/gtegjhsatl.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtqfezkxkw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtrouzxtjm.html

JS:   greet() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdbmbbgt.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtfivuihmk.html

Java: String greet() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthuhhmbwc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gtfhjwptup.html

Ruby: def greet; @name; end
来源：http://dali.sufxvd.cn/Article/details/gttqvexmhf.html

C#:   public string Greet() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gtbyoxihqm.html

[G05] 继承
来源：http://dali.cqqwz.cn/Article/details/gtcudxzjuw.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gtaldgkrjr.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtqhndrtjm.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtdgwpxodl.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtdndsjwmy.html

Java: class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtjkfnvute.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.havefunace.top/Article/details/gtncnsqgbc.html

Ruby: class Admin < User; end
来源：http://dali.316326.xyz/Article/details/gtyewcieti.html

C#:   class Admin : User {}
来源：http://dali.zhixingplan.top/Article/details/gtyfxsiwcd.html

[G06] 重写方法
来源：http://dali.guowangkeji.top/Article/details/gtffclcukq.html

Py:   def greet(self): return "admin"
来源：http://dali.yanxiufei.cn/Article/details/gthfsnqhmx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtzoiekugx.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtizlgrgfr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtdootsbai.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtovjrecjl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gtbuohzvxx.html

Ruby: def greet; "admin"; end
来源：http://dali.havefunace.top/Article/details/gtkqorvbta.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuanzhike.top/Article/details/gtsqlzfutg.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gtnbqolbfm.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gtmvilfldt.html

PHP:  parent::greet();
来源：http://dali.aizwys.cn/Article/details/gtkrbyebya.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtyywfqomo.html

TS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtzufgkqhm.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gtnqrlploe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxinkj.top/Article/details/gttesbwzbu.html

Ruby: super
来源：http://dali.fengsongda.top/Article/details/gtaayvshhx.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gtbygyawge.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrprtjfw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnxiangtu.top/Article/details/gtftthulxo.html

PHP:  public static function f() {}
来源：http://dali.cdnleiting.top/Article/details/gtualulqrc.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtnbqjenhy.html

TS:   static f(): void {}
来源：http://dali.xylfe.cn/Article/details/gtjvwtyppn.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gtgbxtmwze.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gtfhqcbovj.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gtwqgbqkef.html

C#:   public static void F() {}
来源：http://dali.daxiang520.top/Article/details/gtnhzurdpp.html

[G09] 接口 / 抽象类
来源：http://dali.gaohongyu789.top/Article/details/gtaluvcgrf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tian-w.cn/Article/details/gtmcjhjnmw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbxykumvr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuxming.cn/Article/details/gtzgwowoes.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnbtwxbp.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtjyulhhnu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cucudq.cn/Article/details/gtamtrrxir.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cucudq.cn/Article/details/gtamicufxt.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gteecekiar.html

[G10] 访问控制
来源：http://dali.zhixingplan.top/Article/details/gtkiejkuwn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xylfe.cn/Article/details/gtrebmogpl.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtundmvuzi.html

JS:   #private 字段；其余公开
来源：http://dali.fengsongda.top/Article/details/gtreccdpdg.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtneffxhug.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gtxbmsgici.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gtknqascta.html

Ruby: public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtdutdcieo.html

C#:   public / protected / private / internal
来源：http://dali.jiagoushi.top/Article/details/gtpkwzofnd.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gtyqtziwfa.html

Py:   @property 与 @x.setter
来源：http://dali.fengsongda.top/Article/details/gthfsnyuyv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtogxrkdlw.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gttkrnqbet.html

TS:   get name(): string { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gtcxeszzcd.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtlayxzmgd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtpdphgdvw.html

Ruby: attr_accessor :name
来源：http://dali.pengpengdd.cyou/Article/details/gtprorjedi.html

C#:   public string Name { get; set; }
来源：http://dali.guowangkeji.top/Article/details/gtndzrytem.html

[G12] 对象转字符串
来源：http://dali.birdmap.top/Article/details/gtdtrgxbep.html

Py:   def __str__(self): return self.name
来源：http://dali.cheryme.top/Article/details/gtkriuafva.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtvwlxqyfz.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtkmojjoby.html

TS:   toString(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtxqpwonii.html

Java: @Override public String toString() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtkrolqpde.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtxjbbwhjc.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gtyxmtrcgv.html

C#:   public override string ToString() => Name;
来源：http://dali.tanke756.top/Article/details/gthrtvzqaz.html

[G13] 判断对象类型
来源：http://dali.jyoumei.cn/Article/details/gtowooguau.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gtexonlcxu.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtqusxoqec.html

JS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtgqfzwvej.html

TS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtrmjiuoke.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtukmectfk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gtjosyqayx.html

Ruby: u.is_a?(User)
来源：http://dali.cqqwz.cn/Article/details/gtqgpwtrpb.html

C#:   u is User
来源：http://dali.gzhubu.top/Article/details/gtetemswjc.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gtzfsnlwqr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gtatstyrnb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tianlin.xyz/Article/details/gtkascihmb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gtdrdxyuzm.html

TS:   type User = { name: string; age: number };
来源：http://dali.fzhhl.top/Article/details/gtzmpdwtcm.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gttolyeyle.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gtskplkneq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gtvaltzmhf.html

C#:   record User(string Name, int Age);
来源：http://dali.chenjidiqi.icu/Article/details/gtuaomkamu.html

[G15] 枚举
来源：http://dali.chenzaomai.com/Article/details/gttbjpitxk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ivvv.top/Article/details/gtdybavybb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gttukfaapg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.bjfxy.top/Article/details/gtmiyjwxtw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtmknpwbah.html

Java: enum Color { RED, GREEN }
来源：http://dali.hammf.cn/Article/details/gtyqwqslhl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cheryme.top/Article/details/gtbnfcooif.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tianlin.xyz/Article/details/gtfdnszbcz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtoinafjyc.html

[G16] 对象转数组 / 字典
来源：http://dali.0kj1m.cn/Article/details/gtmejxucul.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daria6918.cn/Article/details/gtmomjwxnj.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gtbismwhkn.html

JS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtlkdwqvpn.html

TS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gtugwewwuf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gtxwphvttr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.bjfxy.top/Article/details/gtlpwbxecw.html

Ruby: obj.instance_variables
来源：http://dali.xuanzx.com/Article/details/gtqglinetc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtfxpfxkbn.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtfjjizqxk.html

H. 异常与错误处理
来源：http://dali.yanxiufei.cn/Article/details/gthppftdvq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtkjvifljj.html

[H01] try / catch 基础
来源：http://dali.dianchejie.cn/Article/details/gtxxolgpzs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsasqumib.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xziqi.cn/Article/details/gtfndentbg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtbbpibdhm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gtkjupdqjg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gtbxbrdmzp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.quarkkingdee.top/Article/details/gttdzjbqci.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cheryme.top/Article/details/gtbjzwnhvn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhoulong.xyz/Article/details/gtoivretay.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gtkvfwpgkp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.c1oappe.top/Article/details/gtfioyacdr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtpikdlqit.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtwgkoznlq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtfnfucqjo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtljwviofs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.havefunace.top/Article/details/gtyllavydn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fzhhl.top/Article/details/gtrkdinmeh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtzgvnyngg.html

[H03] 主动抛出异常
来源：http://dali.daria6918.cn/Article/details/gtmbxzboym.html

Py:   raise ValueError("错误信息")
来源：http://dali.dianchejie.cn/Article/details/gtmuhvbfco.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtdgqmpmuh.html

JS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtrmhywnqv.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtsipjdtuk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtjfvrscrv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gtojbtpulb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigufen.top/Article/details/gtkkiyvjsh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtqwctlros.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtqawwvftp.html

Py:   class MyError(Exception): pass
来源：http://dali.mhx1999.top/Article/details/gtvypyyvmo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtkirqbhcg.html

JS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gtfagcebeo.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtytolebpd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtapsegrot.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258888.top/Article/details/gtbtcukgnw.html

Ruby: class MyError < StandardError; end
来源：http://dali.9152youxi.cn/Article/details/gterdyrhrw.html

C#:   class MyException : Exception {}
来源：http://dali.gaohongyu789.top/Article/details/gtiqlfmhkr.html

[H05] 捕获特定类型
来源：http://dali.sxryk.cn/Article/details/gtwuqostwa.html

Py:   except ValueError as e:
来源：http://dali.jinqigfzy.top/Article/details/gtniukqdew.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hammf.cn/Article/details/gtobepsxon.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtgiipxxqm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gtbghuapxb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sufxvd.cn/Article/details/gtzcfzjijr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258888.top/Article/details/gticzwdjiu.html

Ruby: rescue ArgumentError => e
来源：http://dali.shzxlz.cn/Article/details/gtlnmcxdce.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.0kj1m.cn/Article/details/gtrdacvhgy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gturjndsbd.html

Py:   value = d.get("k") or default
来源：http://dali.havefunace.top/Article/details/gtceaydupn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yonumen.top/Article/details/gtfqzgvyve.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtxjepyiog.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtmpxskwvm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.kuanghao11.cn/Article/details/gtrliwplbr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj202588.top/Article/details/gtpilbhlfr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daria6918.cn/Article/details/gtpqbxmdrx.html

C#:   obj?.A?.B ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtnjxrqhtv.html

[H07] 断言
来源：http://dali.jqgfzy.top/Article/details/gthjauzlhq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhixingplan.top/Article/details/gtxfepppxh.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gtoteybtrk.html

JS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtzpcsthwc.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gttppnxpbn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.bjfxy.top/Article/details/gtrjqfjhjp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258888.top/Article/details/gtpmqmblto.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yonumen.top/Article/details/gtcqepupoy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtcstezwls.html

[H08] 获取错误信息与堆栈
来源：http://dali.guowangkeji.top/Article/details/gtvgcymvjg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shangyingyoupin.top/Article/details/gtvcqnkwkc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenzaomai.com/Article/details/gtyzdcpbfg.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gthiectxpy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.9152youxi.cn/Article/details/gtkltswaml.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sysykeji.top/Article/details/gtflqcwhsg.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gtcyqajshk.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzifqrwj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gtnhluokzi.html

[H09] 带错误码的异常
来源：http://dali.tanke756.top/Article/details/gtsldbqllu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gtpxgmveqz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cdnleiting.top/Article/details/gtljhpvxgh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhixingplan.top/Article/details/gtpsjuasgl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gtarrmxxjs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dianchejie.cn/Article/details/gtqeoemndj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sufxvd.cn/Article/details/gtcixohhcc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnxiangtu.top/Article/details/gtikbvsuue.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gtpgkdssjs.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gtlcgcuuqd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.snrcjt.cn/Article/details/gtwdvsoqlt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdugalst.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtpkcoqgkt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gtutbrrubm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dashuyun.cn/Article/details/gtxrqkwivb.html

Go:   defer f.Close()
来源：http://dali.gotoacloud.top/Article/details/gtdktgqrtz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanbgpaiz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtyjeqqefu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtyrkaohml.html

I. 正则表达式
来源：http://dali.9152youxi.cn/Article/details/gtizjmzhne.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gthbczngnz.html

[I01] 判断是否匹配
来源：http://dali.cdnleiting.top/Article/details/gtbecltimi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gtgimvzjwh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gtocwmtcaf.html

JS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtsgeocqdw.html

TS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gttpksfyeu.html


<!-- 参考信息 -->