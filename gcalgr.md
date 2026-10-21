代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtnwusfrfv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtkplkqvhg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtokxkljft.html

Go:   os.Remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtddwwuiva.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtpnykfxbt.html

C#:   File.Delete("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtjndxfglh.html

[F07] 创建目录（含多级）
来源：http://dali.nanxuanxn.top/Article/details/gtqqgtgjjm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gtvubvxrrn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.andypj.xyz/Article/details/gtnbjtktfs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtvkwmatvp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gthmztmiym.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gtlgvukexc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenlongwang.top/Article/details/gtvynrapmd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjjlrjrc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gtlzrkhhwr.html

[F08] 遍历目录
来源：http://dali.jqgfzy.top/Article/details/gtwpmvpvdh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gtylnbzkls.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guannengcc.top/Article/details/gtlhagqxty.html

JS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtgydefdas.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtaiaffkip.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtwszogbkw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cheryme.top/Article/details/gtipxigkyb.html

Ruby: Dir.children("dir")
来源：http://dali.yangfankeji.com/Article/details/gtpokstsxt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxinkj.top/Article/details/gtnaaxxsgi.html

[F09] 获取文件大小
来源：http://dali.hongshengwenyu.top/Article/details/gtemtdvvxy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpmhvlap.html

PHP:  filesize("a.txt");
来源：http://dali.birdmap.top/Article/details/gtfkellqdf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtqcdawxfk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtwftqrxjf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtbernkbvh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatkdmvvp.html

Ruby: File.size("a.txt")
来源：http://dali.pycfn.com/Article/details/gtjsohbzad.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ppjwa.cn/Article/details/gtmptgtgoi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.kuanghao11.cn/Article/details/gtzumbefkh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdaxxuks.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtthrvrsbk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtqgbdvpak.html

TS:   path.extname("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtfhiltbib.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gtatkzzyzz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtivztvcxq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtbmzmzhqg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtaidzbbbr.html

[F11] 复制与移动文件
来源：http://dali.yuanzhike.top/Article/details/gtuzzkywhh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtpvmjbwiy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guannengcc.top/Article/details/gtivposmqw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtwbbagzof.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gteuhuhxsr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtsphctgdo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxxqbklf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtrzlwxabj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gtynkyjhje.html

[F12] CSV 读写
来源：http://dali.jinqigufen.top/Article/details/gtfgvecyje.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.mhx1999.top/Article/details/gthiljnskc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gtrnodtwrt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258.top/Article/details/gtvlyuwvsp.html

TS:   // 同上
来源：http://dali.tanke756.top/Article/details/gtjrewydlg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gogol.net.cn/Article/details/gtzhugxxrn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gtxgsyogui.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gtwkrtypjt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cashguo.top/Article/details/gtrlxebajp.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtfmcnapqz.html

G. 面向对象
来源：http://dali.chenjidiqi.icu/Article/details/gtmibcionw.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtkcxmiqvb.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gtmmhyqyzx.html

Py:   class User: pass
来源：http://dali.vqdsnc.cn/Article/details/gtgjqsnejp.html

PHP:  class User {}
来源：http://dali.cdnleiting.top/Article/details/gtydtjikrt.html

JS:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gtyymtovqn.html

TS:   class User { name: string = ""; }
来源：http://dali.yueranfly.top/Article/details/gtwjtwdrkz.html

Java: class User {}
来源：http://dali.pycfn.com/Article/details/gtilihcuwv.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gtvkmvmxuq.html

Ruby: class User; end
来源：http://dali.jlsjyb.cn/Article/details/gtvtlefprd.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtpremefao.html

[G02] 构造函数
来源：http://dali.yuanzhike.top/Article/details/gtytwxtbhu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daria6918.cn/Article/details/gtxxabbnfc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gtlbytzbtn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gthynleijh.html

TS:   constructor(public name: string) {}
来源：http://dali.yangfankeji.com/Article/details/gtptbcbvuu.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtfurvyigf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daxiang520.top/Article/details/gttmqrvqek.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gtkvhflbys.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyiccaohi.html

[G03] 实例属性
来源：http://dali.zhengqikj.top/Article/details/gtbldatmsv.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtrgxzfatk.html

PHP:  public string $name = "x";
来源：http://dali.yj20258888.top/Article/details/gtpoonufoi.html

JS:   this.name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtxaixcvlm.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtqfpmypcf.html

Java: private String name;
来源：http://dali.hfpthk.cn/Article/details/gteglpfuyv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gtqornnlhs.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtdvlutanu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gzhubu.top/Article/details/gtmzqkmidr.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsyoatxt.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtfmkachsp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gthpkvhgsm.html

JS:   greet() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtzqgkyznw.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkyxnusk.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtzfnqpxdu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtlcsopkhn.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gtvgkcsyrk.html

C#:   public string Greet() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtkwypycyy.html

[G05] 继承
来源：http://dali.ybcxt.top/Article/details/gtojtqaysk.html

Py:   class Admin(User): pass
来源：http://dali.tian-w.cn/Article/details/gtttswwmpl.html

PHP:  class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtgrjysrmc.html

JS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtllwpzaub.html

TS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtbdeyoine.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtbjenfsnw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhiwuduotai.top/Article/details/gtcukudnnt.html

Ruby: class Admin < User; end
来源：http://dali.andypj.xyz/Article/details/gtaynijxyc.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gthnfsmyqn.html

[G06] 重写方法
来源：http://dali.nwbrower.top/Article/details/gtpeidypsy.html

Py:   def greet(self): return "admin"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkpucdna.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtiqlqozns.html

JS:   greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtambkfdte.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtvkggpbci.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtisbjjjgo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuetiantiany.cn/Article/details/gtffogajcz.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gtpkdgbeks.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigufen.top/Article/details/gtfkkxlmyj.html

[G07] 调用父类方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqelotdi.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gtmdxibfzq.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gtzbgqktln.html

JS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtycoywyfg.html

TS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtqarmueiy.html

Java: super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtkvoysimp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.c1oappe.top/Article/details/gtgrghaszx.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gtazmwrtjy.html

C#:   base.Greet();
来源：http://dali.zhongyouzk.top/Article/details/gtydqrjbxv.html

[G08] 静态方法与属性
来源：http://dali.guannengcc.top/Article/details/gtdmesrjmj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gaohongyu789.top/Article/details/gtptnwqseh.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrvgyckj.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gtpxmithtp.html

TS:   static f(): void {}
来源：http://dali.xylfe.cn/Article/details/gtcssqdggv.html

Java: static void f() {}
来源：http://dali.jinqigufen.top/Article/details/gtwneyyrfe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.316326.xyz/Article/details/gtziqbqspv.html

Ruby: def self.f; end
来源：http://dali.guannengcc.top/Article/details/gtaywvgysb.html

C#:   public static void F() {}
来源：http://dali.zhongyouzk.top/Article/details/gtmmqhzlrw.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gtnawmiali.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gtqvresolu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsjaxvvo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwkggspc.html

TS:   interface Shape { area(): number; }
来源：http://dali.hfpthk.cn/Article/details/gtrsaencnq.html

Java: interface Shape { double area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtcktkzwtb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuanzx.com/Article/details/gtxyalaqdf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gtrvtuktut.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gtcrcfmkhs.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gtmkicrskp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnphoyfrf.html

PHP:  public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtztcpsbut.html

JS:   #private 字段；其余公开
来源：http://dali.quarkkingdee.top/Article/details/gtcpmybcil.html

TS:   public / protected / private
来源：http://dali.yongpay.top/Article/details/gtirlqnjro.html

Java: public / protected / private / 默认包级
来源：http://dali.havefunace.top/Article/details/gtksceltbv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigfzy.top/Article/details/gtrppanxyn.html

Ruby: public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtatwhsffq.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrestipd.html

[G11] getter / setter
来源：http://dali.daria6918.cn/Article/details/gtxvlnwmlk.html

Py:   @property 与 @x.setter
来源：http://dali.yonumen.top/Article/details/gtjcgixsib.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtthxzooug.html

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtjbnreplr.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gthicectmu.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtofxzqgih.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtglvjxkxj.html

Ruby: attr_accessor :name
来源：http://dali.haohaochexian.top/Article/details/gttzdhnrua.html

C#:   public string Name { get; set; }
来源：http://dali.yueranfly.top/Article/details/gttjgvilwq.html

[G12] 对象转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdlttwsm.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gthodgyifr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtgpcltxit.html

JS:   toString() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtkhlenklr.html

TS:   toString(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtljzwutrg.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gttdwftpbo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtepkmebhq.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gtyxbkokfo.html

C#:   public override string ToString() => Name;
来源：http://dali.sweek.top/Article/details/gtjiwbhymw.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gtolnrsxdw.html

Py:   isinstance(u, User)
来源：http://dali.yj202588.top/Article/details/gtessrgmba.html

PHP:  $u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtteecxwew.html

JS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gttjtgqqql.html

TS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtkfkcwtbt.html

Java: u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmzdqmnf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gtznlerrcm.html

Ruby: u.is_a?(User)
来源：http://dali.yueranfly.top/Article/details/gtyyjnrxpp.html

C#:   u is User
来源：http://dali.chenzaomai.com/Article/details/gtwmgensbj.html

[G14] 数据类 / record
来源：http://dali.jqgfzy.top/Article/details/gtpyxxjbwz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.316326.xyz/Article/details/gtyyiagnkv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.meibo888.top/Article/details/gttfgdpena.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gtvwudfsoa.html

TS:   type User = { name: string; age: number };
来源：http://dali.shuidangran.top/Article/details/gtihlwjrus.html

Java: record User(String name, int age) {}
来源：http://dali.ehwqpu.com/Article/details/gtiokkxexa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.snrcjt.cn/Article/details/gtzgdudwnd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tianlin.xyz/Article/details/gtkrnqjuon.html

C#:   record User(string Name, int Age);
来源：http://dali.wangshuangyany.cn/Article/details/gtysdzdyry.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gtiokkddoj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhengqikj.top/Article/details/gtyojhjgoj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.smart0.xyz/Article/details/gthhtleorm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.redwolf501.top/Article/details/gtlozivfwr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gtmsnqumpq.html

Java: enum Color { RED, GREEN }
来源：http://dali.havefunace.top/Article/details/gtragtbzyt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ehwqpu.com/Article/details/gtnnkwmplk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gtfghrfamu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gteijvyzlk.html

[G16] 对象转数组 / 字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnxwavpu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ppjwa.cn/Article/details/gtrcpculmu.html

PHP:  get_object_vars($obj);
来源：http://dali.sxryk.cn/Article/details/gtlweuxmok.html

JS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtjdfoaxcy.html

TS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtwnfyvuqp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gtsflmzfcm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hongshengwenyu.top/Article/details/gtcgzftage.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gtwtjelkns.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtkaztfbzg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtfnrwuhcq.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gtmemdugtf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtcyhxusci.html

[H01] try / catch 基础
来源：http://dali.xziqi.cn/Article/details/gtomuuwrio.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjukvmaxa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtptroqkjr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxdkkwzd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtddhyyipr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yvedp.cn/Article/details/gtdqvrxnvr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuanzx.com/Article/details/gtcrbjtsdk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnqzz.top/Article/details/gtdvigikgk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangshuangyany.cn/Article/details/gtzuvcivfg.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gtqjmcbdvn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.meibo888.top/Article/details/gtpmehsupq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtfassvemx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtdwdpsinl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtbehmvxnz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtlqyifkht.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hywenlv.cn/Article/details/gtgcdlvxqi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yueranfly.top/Article/details/gtjvxvsjdo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgmlodxb.html

[H03] 主动抛出异常
来源：http://dali.jqgfzy.top/Article/details/gtlwqgocbh.html

Py:   raise ValueError("错误信息")
来源：http://dali.kuanghao11.cn/Article/details/gtqcnmqlqh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtywiearlc.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtksjsfpvq.html

TS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtokaixltx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtnbtkmhgp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fengsongda.top/Article/details/gttkmxanqp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gthubwpgro.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtbbcwdtrs.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gthxhedcvh.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gtyzmmyeat.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjeachrx.html

JS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gtvxzmgvqs.html

TS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtuspzgtxm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtvqzhspvm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuetiantiany.cn/Article/details/gthpbmmdex.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gtzngjsdjo.html

C#:   class MyException : Exception {}
来源：http://dali.daxiang520.top/Article/details/gtmwccmrma.html

[H05] 捕获特定类型
来源：http://dali.fengsongda.top/Article/details/gtfllftigi.html

Py:   except ValueError as e:
来源：http://dali.yuxming.cn/Article/details/gtyajfqmzz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangshuangyany.cn/Article/details/gteiurymaf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gtsjqwxgtm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gtocehhfur.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenzaomai.com/Article/details/gtbijptblf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.0kj1m.cn/Article/details/gtncdrhiiu.html

Ruby: rescue ArgumentError => e
来源：http://dali.zdqjudy.top/Article/details/gtiyjigbgc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhengqikj.top/Article/details/gtuqleygbh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuxming.cn/Article/details/gtialsyyaz.html

Py:   value = d.get("k") or default
来源：http://dali.cashguo.top/Article/details/gtljccbnla.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtfkjxvljk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtqksxjewh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtxugwixuw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhiwuduotai.top/Article/details/gtulstrwza.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yanxiufei.cn/Article/details/gtfdvjxjpl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.c1oappe.top/Article/details/gtfxnishaj.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangdashe.top/Article/details/gtzmhyciya.html

[H07] 断言
来源：http://dali.xziqi.cn/Article/details/gtlmyhfsua.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gtugofsraw.html

PHP:  assert($x > 0);
来源：http://dali.cashguo.top/Article/details/gtkxbxbxsx.html

JS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtverujsru.html

TS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtgztpwogx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gtqvcymkwa.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gtjjylepnv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hfpthk.cn/Article/details/gtyfhoiiaf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtxjltagww.html

[H08] 获取错误信息与堆栈
来源：http://dali.yangfankeji.com/Article/details/gtvhggqumr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gtkcxjzwiw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gtcrgmcgxg.html

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gttnoyqofp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.iojbl.cn/Article/details/gtorelporo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jyoumei.cn/Article/details/gtplfddlkt.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gtowvrmiso.html

Ruby: e.message;  e.backtrace
来源：http://dali.shzxlz.cn/Article/details/gtnrptmusc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenjidiqi.icu/Article/details/gtwqjhnujd.html

[H09] 带错误码的异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtezlknrek.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gtwkaxsgyr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hammf.cn/Article/details/gtisntudab.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sweek.top/Article/details/gtxxrawxam.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.0kj1m.cn/Article/details/gtrtjhqjbt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gzhubu.top/Article/details/gtburwhaln.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.svipenyu.cn/Article/details/gteakudyeh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.redwolf501.top/Article/details/gtouzwuwtq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gogol.net.cn/Article/details/gtripkguav.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gtaynyyweb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gzhubu.top/Article/details/gtktjvbmom.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gtohdmjojm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtzjpxdjqn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gttdpqgqex.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gtuissxzvm.html

Go:   defer f.Close()
来源：http://dali.yongpay.top/Article/details/gtprxjhngg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aibaodan.cn/Article/details/gtjdjmtjow.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtdepvfrcs.html


<!-- 参考信息 -->