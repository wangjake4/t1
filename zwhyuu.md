代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tanke756.top/Article/details/gthsaovkit.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuanzhike.top/Article/details/gtlzxxyooi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhiwuduotai.top/Article/details/gtijrlgdug.html

[F08] 遍历目录
来源：http://dali.ivvv.top/Article/details/gtgophbnnk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gtzilhiorr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fengsongda.top/Article/details/gtfpabmkle.html

JS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtxbymtmzh.html

TS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtdrlivics.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtktejypbh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gtokocdqed.html

Ruby: Dir.children("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtjylscsbz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ehwqpu.com/Article/details/gtvjwwbllr.html

[F09] 获取文件大小
来源：http://dali.sweek.top/Article/details/gtncbfrqeq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gtvzahnrbw.html

PHP:  filesize("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtelqermur.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gthcfncyrm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gtmbvrflfs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gthdqkqqxi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fzhhl.top/Article/details/gtbqauowxq.html

Ruby: File.size("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtjjzinplg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tanke756.top/Article/details/gtlblsbyha.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.0kj1m.cn/Article/details/gtehylqlvq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtqraudefd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xinyue.icu/Article/details/gthnilrxgy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoptrwtkp.html

TS:   path.extname("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtaggjbswb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhongyouzk.top/Article/details/gtiwnxwqut.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtknwagxnj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzscagnq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtwtezelec.html

[F11] 复制与移动文件
来源：http://dali.cqqwz.cn/Article/details/gtocujchex.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtpvfyrnds.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuanzhike.top/Article/details/gthrleooyf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtfgqdyrvl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtjscqnioi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gtihygczmw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecwgqiri.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtylqrovwi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigfzy.top/Article/details/gtncevuodx.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gtquedydkz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuanzx.com/Article/details/gtoggkmbse.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zycfv.cn/Article/details/gtvhckucbk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fzhhl.top/Article/details/gthaxnyxcs.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gtxyxspwwe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258888.top/Article/details/gtljulzkrh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yanxiufei.cn/Article/details/gtytykqzuk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gtzanflxre.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.iojbl.cn/Article/details/gtiqylhhvp.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtpimgfycc.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gtshegaxef.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbgwxwwne.html

[G01] 定义类
来源：http://dali.yj20258.top/Article/details/gttnatifeu.html

Py:   class User: pass
来源：http://dali.yangfankeji.com/Article/details/gtatssfxug.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gthslegwpi.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtsvhzkrpd.html

TS:   class User { name: string = ""; }
来源：http://dali.sweek.top/Article/details/gtbvrcahvk.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gtjoybmlvt.html

Go:   type User struct { Name string }
来源：http://dali.jqgfzy.top/Article/details/gtxaqllvux.html

Ruby: class User; end
来源：http://dali.wangdashe.top/Article/details/gtgwrsykoh.html

C#:   class User {}
来源：http://dali.sysykeji.top/Article/details/gthqxrdyus.html

[G02] 构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsctrvlws.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hysaishi.cn/Article/details/gtxpsakhns.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nwbrower.top/Article/details/gtbcgjnuwr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtqsgkutvb.html

TS:   constructor(public name: string) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtuizispoh.html

Java: User(String name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtxpjcyxen.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangdashe.top/Article/details/gtytxpqvba.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gtbdjioank.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gtivdxdwvg.html

[G03] 实例属性
来源：http://dali.0kj1m.cn/Article/details/gtbkhmplul.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtsnbsbwxb.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gthzoeyzyq.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtyqkofmsg.html

TS:   name: string = "x";
来源：http://dali.hfpthk.cn/Article/details/gtvamnbfgu.html

Java: private String name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpzqybkv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pengpengdd.cyou/Article/details/gtvywniopi.html

Ruby: @name = "x"
来源：http://dali.yueranfly.top/Article/details/gtgzgnuwjg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtivgltwap.html

[G04] 定义方法
来源：http://dali.zhixingplan.top/Article/details/gtnlsahlwa.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtbnumpcpo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtcamvoooy.html

JS:   greet() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtlhbiqvef.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtkjmyzchq.html

Java: String greet() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtsskdoyzh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtvwxcjqva.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gtgkvettnx.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtzjonaatc.html

[G05] 继承
来源：http://dali.daria6918.cn/Article/details/gtidnfipse.html

Py:   class Admin(User): pass
来源：http://dali.xinyue.icu/Article/details/gtqepgzlbx.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtbdbbsfsh.html

JS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtugqrcpei.html

TS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtsarjgfjn.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtwhfvhcpo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gttckakqxj.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtnzwvfokv.html

C#:   class Admin : User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtaziermya.html

[G06] 重写方法
来源：http://dali.yuxming.cn/Article/details/gtyskziqnq.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gtyalenomg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtrjtacvpm.html

JS:   greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtsatpebsi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtzrsksbql.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtjnprophr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yueranfly.top/Article/details/gtwjeziwsr.html

Ruby: def greet; "admin"; end
来源：http://dali.cqqwz.cn/Article/details/gtpjozjprx.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gtgrqshbde.html

[G07] 调用父类方法
来源：http://dali.sxryk.cn/Article/details/gthzrgkmes.html

Py:   super().greet()
来源：http://dali.yvedp.cn/Article/details/gthtjsebhf.html

PHP:  parent::greet();
来源：http://dali.pengpengdd.cyou/Article/details/gthesjztao.html

JS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtfjgphdug.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtyncqdjxa.html

Java: super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtpcjnhywy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.iojbl.cn/Article/details/gtukrfrxta.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gtchylzghh.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gtdxaprkol.html

[G08] 静态方法与属性
来源：http://dali.kuanghao11.cn/Article/details/gtjnefgktm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.haohaochexian.top/Article/details/gtmfsbnhcb.html

PHP:  public static function f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtkvuxhjit.html

JS:   static f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtxkptpida.html

TS:   static f(): void {}
来源：http://dali.andypj.xyz/Article/details/gtlvmdsbzd.html

Java: static void f() {}
来源：http://dali.zhixingplan.top/Article/details/gtoebfhzbn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.c1oappe.top/Article/details/gtjejrcnyn.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlyjgflr.html

C#:   public static void F() {}
来源：http://dali.zhengqikj.top/Article/details/gtfufejcxh.html

[G09] 接口 / 抽象类
来源：http://dali.0kj1m.cn/Article/details/gtnmgrtzrw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwnduvui.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.9152youxi.cn/Article/details/gtfcojjcwg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ehwqpu.com/Article/details/gtqftoagfb.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gtcvwwydvt.html

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtjlhvdwsm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuanzx.com/Article/details/gthbbomxmc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cqqwz.cn/Article/details/gtvbouyzoo.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigufen.top/Article/details/gtgixrzrpv.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gtjmrikmdf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gtpybhfpfs.html

PHP:  public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtghdbcvfg.html

JS:   #private 字段；其余公开
来源：http://dali.daxiang520.top/Article/details/gtftcrsmri.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gtklpzkvce.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxinkj.top/Article/details/gtkvqefudn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258888.top/Article/details/gtljwzlikc.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtkpbnhtom.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gttvrwjfhy.html

[G11] getter / setter
来源：http://dali.sxryk.cn/Article/details/gtterbgjgm.html

Py:   @property 与 @x.setter
来源：http://dali.dashuyun.cn/Article/details/gtqqznqeaj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtmmyimcic.html

JS:   get name() { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gtnixbezmw.html

TS:   get name(): string { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtwvpfaveg.html

Java: public String getName() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmrpscqge.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtbamzftbx.html

Ruby: attr_accessor :name
来源：http://dali.yj202588.top/Article/details/gtgqxtjjko.html

C#:   public string Name { get; set; }
来源：http://dali.guannengcc.top/Article/details/gthxahzkpk.html

[G12] 对象转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtllmvhkkm.html

Py:   def __str__(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtcqtnnvzf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtwtqxmrsf.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtafeobudi.html

TS:   toString(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtgxywfljl.html

Java: @Override public String toString() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtsvkeadwh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtpopuxuys.html

Ruby: def to_s; @name; end
来源：http://dali.mhx1999.top/Article/details/gthfsldacr.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gtcixakjuk.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gtxhkzuwlz.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gtrqxfhrst.html

PHP:  $u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtcjkijvds.html

JS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtpbqpzkbh.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtfzijtnuj.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtdxaacmzg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fengsongda.top/Article/details/gtukzoodmh.html

Ruby: u.is_a?(User)
来源：http://dali.cdnleiting.top/Article/details/gtwzlqjkto.html

C#:   u is User
来源：http://dali.zhongyouzk.top/Article/details/gtbswcczuv.html

[G14] 数据类 / record
来源：http://dali.bjfxy.top/Article/details/gtsgrkvywh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nwbrower.top/Article/details/gtqiquwklh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aizwys.cn/Article/details/gthtyenqdp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangshuangyany.cn/Article/details/gtmqpqhsad.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258.top/Article/details/gtabaeghem.html

Java: record User(String name, int age) {}
来源：http://dali.iojbl.cn/Article/details/gtlouymuef.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkotpzsvw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.quarkkingdee.top/Article/details/gtwlgbcgob.html

C#:   record User(string Name, int Age);
来源：http://dali.cheryme.top/Article/details/gtibuvygru.html

[G15] 枚举
来源：http://dali.dashuyun.cn/Article/details/gtunjjsdep.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgfzy.top/Article/details/gtcdlylnsf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gtjdfjoghs.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sysykeji.top/Article/details/gtiozdcidz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtcjsjowda.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmfssjnf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gtzbbakxjd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jiagoushi.top/Article/details/gtztcsfjhw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtajldoviy.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gtdklywtkf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhengqikj.top/Article/details/gtzjriexrz.html

PHP:  get_object_vars($obj);
来源：http://dali.jinghuilouyu.cn/Article/details/gtefnlkyvn.html

JS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gttbrjuyln.html

TS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtdckxutos.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.quarkkingdee.top/Article/details/gtcrdeldgx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.svipenyu.cn/Article/details/gttpzzoulm.html

Ruby: obj.instance_variables
来源：http://dali.cdnleiting.top/Article/details/gtuzhqvsix.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzypgxjgx.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtgffmbovu.html

H. 异常与错误处理
来源：http://dali.aizwys.cn/Article/details/gtywunzyku.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtwtdhijhp.html

[H01] try / catch 基础
来源：http://dali.mhx1999.top/Article/details/gtaeqnrlvo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gtiavrmbef.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gthikblayl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtjbefucdo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtwfjjdukj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gtgsplwpaq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gtqoksitqq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gtdfxgoect.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258888.top/Article/details/gtsocymxqn.html

[H02] finally / ensure 收尾
来源：http://dali.mhx1999.top/Article/details/gteuwfsiwv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cashguo.top/Article/details/gtejyeckar.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtvwxzsedc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtxtzocvcv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtzmnpzumc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtjiysyumb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gtfgzlzyti.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xziqi.cn/Article/details/gtmwfrpypm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtfwzjbhyl.html

[H03] 主动抛出异常
来源：http://dali.jqgfzy.top/Article/details/gtwqwavieo.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gtttwjngli.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtkggafmju.html

JS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtzrucguia.html

TS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtbhmmddho.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtbtipbfue.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gtkxoenfgx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daxiang520.top/Article/details/gtpegpzurw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtesnbyrfg.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gtvosvwdux.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigufen.top/Article/details/gtgtbyheme.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gtuacdlulj.html

JS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtxjxbhmqu.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtlmzpstfz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtgsjhxbbk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gtnawujnoy.html

Ruby: class MyError < StandardError; end
来源：http://dali.nwbrower.top/Article/details/gtnosgqxfj.html

C#:   class MyException : Exception {}
来源：http://dali.yvedp.cn/Article/details/gtjasiwjxw.html

[H05] 捕获特定类型
来源：http://dali.havefunace.top/Article/details/gtvfrdekoe.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gtwuikowqz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dashuyun.cn/Article/details/gtrdtxwems.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtmugmdvpd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gtmyifxqwz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hongshengwenyu.top/Article/details/gttanpzmzg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dashuyun.cn/Article/details/gtvcatnoyb.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gttpkdrreg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdkpgtrn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ppjwa.cn/Article/details/gtmwahodcr.html

Py:   value = d.get("k") or default
来源：http://dali.chenlongwang.top/Article/details/gtrwaesuqt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtnbfpsleb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gtmqckpnsd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gtwsvipygq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxuanxn.top/Article/details/gtirrpsokc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpfstfsh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fengsongda.top/Article/details/gtfgwynloe.html

C#:   obj?.A?.B ?? default
来源：http://dali.sysykeji.top/Article/details/gtonsfydyc.html

[H07] 断言
来源：http://dali.nanxinkj.top/Article/details/gtgjgltqwi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hysaishi.cn/Article/details/gtmkkcesgs.html

PHP:  assert($x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtribwxifv.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gttzpngvef.html

TS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtpzrbpmtl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gtfkxzyghx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.smart0.xyz/Article/details/gtljcwubyj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tianlin.xyz/Article/details/gtapnnchls.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gthcqmgejp.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgufenzy.top/Article/details/gttmnwqmyo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.smart0.xyz/Article/details/gtntfpcytp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gtbmogecko.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gtolzgbglr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258.top/Article/details/gtowxrxbab.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangshuangyany.cn/Article/details/gtnlvxjxbx.html

Go:   err.Error()
来源：http://dali.meibo888.top/Article/details/gttqlbhqoq.html

Ruby: e.message;  e.backtrace
来源：http://dali.yanxiufei.cn/Article/details/gtpqxiigvt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gtpivhjmrc.html

[H09] 带错误码的异常
来源：http://dali.hfpthk.cn/Article/details/gtgzpaygfi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.bjfxy.top/Article/details/gtcuwxrfgn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ehwqpu.com/Article/details/gtcecjetmb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.0kj1m.cn/Article/details/gtgggndjck.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenjidiqi.icu/Article/details/gtqylutyix.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yonumen.top/Article/details/gtdhnfrxrp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tanke756.top/Article/details/gtahnuwipc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gtguaeaewl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgufenzy.top/Article/details/gtqgrilqcf.html

[H10] 资源自动释放
来源：http://dali.gotoacloud.top/Article/details/gtyzocidsu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.c1oappe.top/Article/details/gtdbifizpt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shuidangran.top/Article/details/gtriyiqumt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gtndvtbfot.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gtqimfvsgm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.birdmap.top/Article/details/gtfnqgrtvx.html

Go:   defer f.Close()
来源：http://dali.jianghu66.top/Article/details/gtmyjcojai.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.birdmap.top/Article/details/gtyjrwumwt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtxcsythmo.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtednscptf.html

I. 正则表达式
来源：http://dali.nwbrower.top/Article/details/gtjymxalon.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtqrcfdkrf.html

[I01] 判断是否匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtagvcrrgl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtehmkppbb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gttutzeppl.html

JS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gtmbynlapu.html

TS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gtuahtmzrm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gtjysyesje.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnqzz.top/Article/details/gtihprquft.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gtdjksfzje.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.smart0.xyz/Article/details/gtmlyhsssr.html


<!-- 参考信息 -->