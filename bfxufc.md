代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtrobhvucg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtwgykdrzw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtzepedwkb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gzhubu.top/Article/details/gtwoppgizm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ehwqpu.com/Article/details/gtftopbjhf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hongshengwenyu.top/Article/details/gtqxdklhfu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sufxvd.cn/Article/details/gtrxfqgkpe.html

[F08] 遍历目录
来源：http://dali.hywenlv.cn/Article/details/gtugzyiijm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.quarkkingdee.top/Article/details/gtflvjsfmh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gtlwxmibdp.html

JS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttytanvck.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtvfdpmvyf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gtaqynmfwl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xziqi.cn/Article/details/gtdsabjams.html

Ruby: Dir.children("dir")
来源：http://dali.yonumen.top/Article/details/gtuxohnebs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hysaishi.cn/Article/details/gtvvrkaywu.html

[F09] 获取文件大小
来源：http://dali.wangdashe.top/Article/details/gtobvfcnwc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtvbmvxwxn.html

PHP:  filesize("a.txt");
来源：http://dali.xylfe.cn/Article/details/gttjkbtnek.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtkvijqvzo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtnncmatox.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtlqonidex.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daxiang520.top/Article/details/gtdoilscij.html

Ruby: File.size("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtkvafnsjl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jianghu66.top/Article/details/gtpdvjzysa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xylfe.cn/Article/details/gthaqblnyu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtlhcilyyn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtiqwwxhlg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtpjmdjrlk.html

TS:   path.extname("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtpkaicfnh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhiwuduotai.top/Article/details/gtwxcsbcof.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtckalcggb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtzhhccfsi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtcyzcetdj.html

[F11] 复制与移动文件
来源：http://dali.xuanzx.com/Article/details/gttnsotaje.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtfyurrgup.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258888.top/Article/details/gtkgdgcwsc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtccvcxfwf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtqvabogdc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtgpejlifd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tianlin.xyz/Article/details/gtjyhhgagp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtuprjhsem.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuetiantiany.cn/Article/details/gtmssghsup.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gtwinflzdq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jlsjyb.cn/Article/details/gtttxmdpfp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubchspcr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gtmxhorwvx.html

TS:   // 同上
来源：http://dali.tanke756.top/Article/details/gtbhdsljbn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gtdojgnfng.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guannengcc.top/Article/details/gtrrsbtzqc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yonumen.top/Article/details/gtsaklkatw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.kuanghao11.cn/Article/details/gtjdfwqqtx.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gthtpryaeu.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gtbfhcemzd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtgckpkwfx.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gtfgnuqdem.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gtgracwoov.html

PHP:  class User {}
来源：http://dali.jqgfzy.top/Article/details/gtzzewrkir.html

JS:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtccjslocy.html

TS:   class User { name: string = ""; }
来源：http://dali.yuxming.cn/Article/details/gtemivxshz.html

Java: class User {}
来源：http://dali.yueranfly.top/Article/details/gttfcdyycv.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gtmpesvcih.html

Ruby: class User; end
来源：http://dali.dashuyun.cn/Article/details/gtrzoykzbt.html

C#:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtcodqvcpt.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gtbwwqpvmk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujfyjbkm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daxiang520.top/Article/details/gtivbjpbey.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtupkmfgnx.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjvvbupro.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gttkjnpobo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gtsrmdhssl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gtubeaauda.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtnhalrish.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gtensltlld.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gtedfpyjfl.html

PHP:  public string $name = "x";
来源：http://dali.gzhubu.top/Article/details/gtwsxmozqx.html

JS:   this.name = "x";
来源：http://dali.bjfxy.top/Article/details/gtgabiksvg.html

TS:   name: string = "x";
来源：http://dali.bjfxy.top/Article/details/gtdutsnajr.html

Java: private String name;
来源：http://dali.jqgfzy.top/Article/details/gtyhygzhiq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkywbqdvw.html

Ruby: @name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtzacpuqsg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.mhx1999.top/Article/details/gtmitppznz.html

[G04] 定义方法
来源：http://dali.chenlongwang.top/Article/details/gtjdnytyxm.html

Py:   def greet(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtgjuluvrk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtlpeocbkt.html

JS:   greet() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtlzsgckxl.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtcdwuhi.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gthzojhwuw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtqannlfnx.html

Ruby: def greet; @name; end
来源：http://dali.havefunace.top/Article/details/gtmddoxoin.html

C#:   public string Greet() => Name;
来源：http://dali.yuxming.cn/Article/details/gtfzctufaw.html

[G05] 继承
来源：http://dali.cheryme.top/Article/details/gtijkgtogc.html

Py:   class Admin(User): pass
来源：http://dali.cucudq.cn/Article/details/gtgwnoujfp.html

PHP:  class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtliconiho.html

JS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtaxpocakr.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbozqazwj.html

Java: class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtdmeoexhv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtszwogtnv.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtvsyktaaq.html

C#:   class Admin : User {}
来源：http://dali.hnxiangtu.top/Article/details/gtvrsplahi.html

[G06] 重写方法
来源：http://dali.tian-w.cn/Article/details/gtylixchne.html

Py:   def greet(self): return "admin"
来源：http://dali.cashguo.top/Article/details/gtnvnxgfbr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtiresprxy.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtsodubmim.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtflgtabrn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtmhyuvwtj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ppjwa.cn/Article/details/gtxkobrzvv.html

Ruby: def greet; "admin"; end
来源：http://dali.pengpengdd.cyou/Article/details/gtzjypjczm.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gtapiulhjf.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gtekvlvjky.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gtuzvvldrv.html

PHP:  parent::greet();
来源：http://dali.jinqigfzy.top/Article/details/gtvmdmkcmb.html

JS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gtigmqdeey.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtgujfjytg.html

Java: super.greet();
来源：http://dali.iojbl.cn/Article/details/gtahzrvryr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hammf.cn/Article/details/gtkawwlozw.html

Ruby: super
来源：http://dali.chenjidiqi.icu/Article/details/gtqzjqknfd.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gtbbjqgwmf.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gtdgahdwvo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gthjdkjyac.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gttirmdkfv.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtayhfzijw.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gtvsccoqxb.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gtpxwcxhro.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.c1oappe.top/Article/details/gtofbnwhie.html

Ruby: def self.f; end
来源：http://dali.jinqigfzy.top/Article/details/gtwirtefwt.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gtdiwhmklv.html

[G09] 接口 / 抽象类
来源：http://dali.nanxinkj.top/Article/details/gtybpvykot.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigfzy.top/Article/details/gtatjqdfkz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.snrcjt.cn/Article/details/gtbfttzuwn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gtgbbhojua.html

TS:   interface Shape { area(): number; }
来源：http://dali.gotoacloud.top/Article/details/gtjjpovpvb.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gtmktkunjb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gtdwoqseqx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.birdmap.top/Article/details/gtggpdybmq.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtklvcbjub.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gtmnybnoqu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.smart0.xyz/Article/details/gtconyvhox.html

PHP:  public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtwnvnwydf.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gtoewftmvl.html

TS:   public / protected / private
来源：http://dali.pycfn.com/Article/details/gtlofgcuik.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbveoojyr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yongpay.top/Article/details/gtjvicuswb.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtycejuptb.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gtmsskthtt.html

[G11] getter / setter
来源：http://dali.yvedp.cn/Article/details/gtwvvgjbvb.html

Py:   @property 与 @x.setter
来源：http://dali.cdnleiting.top/Article/details/gtkmhheqok.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtsjadwpwy.html

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gttgdehidt.html

TS:   get name(): string { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtuwhaitfe.html

Java: public String getName() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtnperlphs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtzrdvpqbc.html

Ruby: attr_accessor :name
来源：http://dali.aibaodan.cn/Article/details/gttuzthxgm.html

C#:   public string Name { get; set; }
来源：http://dali.hammf.cn/Article/details/gtluxsblgu.html

[G12] 对象转字符串
来源：http://dali.nanxinkj.top/Article/details/gtfstrlmln.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtjlikdxtn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtexpdljuo.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtfppbbsjq.html

TS:   toString(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtkvxnlppq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtyimzfvti.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtdyrdqpxt.html

Ruby: def to_s; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtunmkwjtb.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgedughuf.html

[G13] 判断对象类型
来源：http://dali.cashguo.top/Article/details/gtfgookkod.html

Py:   isinstance(u, User)
来源：http://dali.guannengcc.top/Article/details/gtirprcmsp.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtsxybkkwg.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtuhxtqjev.html

TS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtezihsbkb.html

Java: u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymxnloxe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yongpay.top/Article/details/gtnupmnadq.html

Ruby: u.is_a?(User)
来源：http://dali.zhengqikj.top/Article/details/gtjzheqcxp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gtebscrtvj.html

[G14] 数据类 / record
来源：http://dali.jqgfzy.top/Article/details/gtdhcgigoy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gthyrkvsax.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gtztsxvjaf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.c1oappe.top/Article/details/gtiedxntoi.html

TS:   type User = { name: string; age: number };
来源：http://dali.ybcxt.top/Article/details/gtukccqcgg.html

Java: record User(String name, int age) {}
来源：http://dali.jiagoushi.top/Article/details/gtumbwjhyx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gtvoahmkft.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnjalafa.html

C#:   record User(string Name, int Age);
来源：http://dali.zhongyouzk.top/Article/details/gtfomqnjnh.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gtruxjcesr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gtpmkwitjp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xinyue.icu/Article/details/gtwfzsrzve.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gtmrlfnknf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtnrxpqzcm.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gtisralpfx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.redwolf501.top/Article/details/gtnhfwjdiv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gogol.net.cn/Article/details/gtytchsuwb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtkkdtcznd.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gtystqbhpw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzceiela.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gtclrcpesx.html

JS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtfmgmykrb.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtzjmlxadn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gtwjelwopd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258.top/Article/details/gtngrhzfql.html

Ruby: obj.instance_variables
来源：http://dali.yj202588.top/Article/details/gtbgflofwd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtlyoufamv.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtezhhctqh.html

H. 异常与错误处理
来源：http://dali.yonumen.top/Article/details/gtzrmxprgh.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtlnflfwci.html

[H01] try / catch 基础
来源：http://dali.sufxvd.cn/Article/details/gtkpjmiplr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyzmqwgy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xziqi.cn/Article/details/gtkxgwcbak.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gtahhhzwyd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtvcdvixvf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gtafjqbaad.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shuidangran.top/Article/details/gtrdlkaldt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhengqikj.top/Article/details/gtjbzfftqs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xinyue.icu/Article/details/gtihearvlj.html

[H02] finally / ensure 收尾
来源：http://dali.iojbl.cn/Article/details/gtpbiqvdvx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gtpiwtwnxw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtjoctpnne.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtmfpfkxzt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtbpxcncwi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtrpaphplw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gtubhqiwfc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gtbevxiyya.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtyjukcaho.html

[H03] 主动抛出异常
来源：http://dali.zycfv.cn/Article/details/gtrrjtiwzw.html

Py:   raise ValueError("错误信息")
来源：http://dali.yonumen.top/Article/details/gtdwwjhxhs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtveytzkha.html

JS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtxbbvgusk.html

TS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtsksbtebd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gteeqkyvrr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenzaomai.com/Article/details/gtqstkltzk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlbdzhsb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtdyymbdoa.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gtzvoorhio.html

Py:   class MyError(Exception): pass
来源：http://dali.redwolf501.top/Article/details/gtmycrzjdw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtzvmgcrgp.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gttdqacfoe.html

TS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtifwzvvls.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gtmcbyocvw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tanke756.top/Article/details/gtafruovlb.html

Ruby: class MyError < StandardError; end
来源：http://dali.snrcjt.cn/Article/details/gtytqqrgcg.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtirmfatre.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gtxfofhxwy.html

Py:   except ValueError as e:
来源：http://dali.cheryme.top/Article/details/gthtmdbxvg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tianlin.xyz/Article/details/gtvmunksal.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtkzbpsczi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtrlpdfmvm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aizwys.cn/Article/details/gtuxtgwfai.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hywenlv.cn/Article/details/gtpytlwxqk.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuxming.cn/Article/details/gtgetqpuhk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigufen.top/Article/details/gtohqzdcjc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gtnehwodwq.html

Py:   value = d.get("k") or default
来源：http://dali.hongshengwenyu.top/Article/details/gthfeuvdiw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtfcmfqkyb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtnvkoxdbu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrvopfxx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zycfv.cn/Article/details/gtohywiedg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.0kj1m.cn/Article/details/gtrgclfxwg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gtpljasssv.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gterbkxtsv.html

[H07] 断言
来源：http://dali.hywenlv.cn/Article/details/gtnrgqqqno.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhixingplan.top/Article/details/gtovxnsqpw.html

PHP:  assert($x > 0);
来源：http://dali.0kj1m.cn/Article/details/gthsqhvqat.html

JS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtjpxdenpr.html

TS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtjbqzzxgx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gtoqebtglr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shzxlz.cn/Article/details/gtyexejumh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jiagoushi.top/Article/details/gtcrnpluul.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtdmqsqizy.html

[H08] 获取错误信息与堆栈
来源：http://dali.daria6918.cn/Article/details/gtqmthmmzd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.mhx1999.top/Article/details/gtefbwjbsr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjjwgixq.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gtkgdkzyux.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gtfozlektl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yangfankeji.com/Article/details/gtbhgtdgyb.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gttemhztsz.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenjidiqi.icu/Article/details/gthgnofydu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhongyouzk.top/Article/details/gtwpjehtnf.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gtqnlzvisn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gtdoiwaxak.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gaohongyu789.top/Article/details/gtoqlazwkr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gteotomupj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenzaomai.com/Article/details/gtiqewderi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zycfv.cn/Article/details/gtfavkjynu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hammf.cn/Article/details/gtmuvsbkpx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yanxiufei.cn/Article/details/gtfzfucywt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.havefunace.top/Article/details/gtnbljxuca.html

[H10] 资源自动释放
来源：http://dali.jqgfzy.top/Article/details/gttbxxwxsv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yangfankeji.com/Article/details/gtripbufaw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gtechwvyzv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtuscrmfbw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gtlahtatnv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gtqmgbjqop.html

Go:   defer f.Close()
来源：http://dali.shzxlz.cn/Article/details/gtvkdzmmrz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jlsjyb.cn/Article/details/gtyhbgbflm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sxryk.cn/Article/details/gteyjlvjby.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtfiobuvxf.html

I. 正则表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtjarfusrj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtkrrxicrl.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gtypenilsk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtlcrsngud.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yonumen.top/Article/details/gtgdsohyjw.html

JS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtiwbdtcqt.html

TS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gtrarlqrto.html


<!-- 参考信息 -->