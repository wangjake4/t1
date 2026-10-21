代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtxmkxnyth.html

[F06] 删除文件
来源：http://dali.zhengqikj.top/Article/details/gtvyydhbcf.html

Py:   os.remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gthztffeyw.html

PHP:  unlink("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtgtzgznos.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtdsxfefgc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtcpvpdsnl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtkkhplhkp.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtvmqnrr.html

Ruby: File.delete("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtwtqscucd.html

C#:   File.Delete("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtkiuqrjxb.html

[F07] 创建目录（含多级）
来源：http://dali.quarkkingdee.top/Article/details/gtndcbcdft.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gtcpvskrqk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guowangkeji.top/Article/details/gtlmytekgv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtvwscxcsm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtbuhrzuki.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.birdmap.top/Article/details/gtsivmqihl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gzhubu.top/Article/details/gtjqxxqjer.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuanzhike.top/Article/details/gtkyynjyfp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gtdiqbahvr.html

[F08] 遍历目录
来源：http://dali.kuanghao11.cn/Article/details/gtffngayoc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangshuangyany.cn/Article/details/gtvkycbqim.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yvedp.cn/Article/details/gtjobofldq.html

JS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtsgjnpkjl.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtfudojapu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtklvypogp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtboqiimbz.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gtmbwmtyfr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.birdmap.top/Article/details/gtqwizuxnb.html

[F09] 获取文件大小
来源：http://dali.zhixingplan.top/Article/details/gtiwatfflk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebbbhgax.html

PHP:  filesize("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtoqeqouqj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtdiakhgnp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtvyssuqaq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtbniaysvy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.meibo888.top/Article/details/gtqlpfmbgy.html

Ruby: File.size("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtnulfjacm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.316326.xyz/Article/details/gtllpheirp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gtgxvllgpv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtwjrccqgi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtzzojwrts.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtxdymbvmk.html

TS:   path.extname("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtggxvjqqx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ehwqpu.com/Article/details/gtmdarwsqu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtvqmhfnjp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtwhtrgqzn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtjwdmjsgu.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gtfktovril.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtfgdmuqmu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jiagoushi.top/Article/details/gthpskxzuv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtktrdfvah.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtaielgzhc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtmppbpiej.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gtsegujmmv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtqygfmvrd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hysaishi.cn/Article/details/gtssaybtss.html

[F12] CSV 读写
来源：http://dali.yj20258.top/Article/details/gtincrwqsh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.haohaochexian.top/Article/details/gtkvxvudwi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zycfv.cn/Article/details/gtknqjwtgz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gtlwubdtna.html

TS:   // 同上
来源：http://dali.yueranfly.top/Article/details/gtdfubrkrl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenlongwang.top/Article/details/gtsocmgeho.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuetiantiany.cn/Article/details/gteyoimkge.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shuidangran.top/Article/details/gtzyxnwmzq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aizwys.cn/Article/details/gtbnpctcsr.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtuknmfmuy.html

G. 面向对象
来源：http://dali.ehwqpu.com/Article/details/gtaolzvdod.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtgagjxqym.html

[G01] 定义类
来源：http://dali.chenlongwang.top/Article/details/gtuvifoqki.html

Py:   class User: pass
来源：http://dali.jinqigfzy.top/Article/details/gtkrgedyus.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gtmijlcfyc.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtqkgtdchw.html

TS:   class User { name: string = ""; }
来源：http://dali.yueranfly.top/Article/details/gtwlowydxo.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtlkfgjexv.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gtygqzyclr.html

Ruby: class User; end
来源：http://dali.hysaishi.cn/Article/details/gtoeuplpgu.html

C#:   class User {}
来源：http://dali.yongpay.top/Article/details/gtjhmhbvww.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gtrndvcaub.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pycfn.com/Article/details/gtwusyijqe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfonjmrq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtzfnekarp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gtuycmpluo.html

Java: User(String name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gtjpecxxdz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jiagoushi.top/Article/details/gtdgzqrokz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gttbzquypi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yvedp.cn/Article/details/gtzpplsqri.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gtziycoxsx.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gtqyqfovvx.html

PHP:  public string $name = "x";
来源：http://dali.yueranfly.top/Article/details/gtgfodioyo.html

JS:   this.name = "x";
来源：http://dali.ybcxt.top/Article/details/gtyroxzfzq.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfnudlwq.html

Java: private String name;
来源：http://dali.vqdsnc.cn/Article/details/gtexboqtdc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yangfankeji.com/Article/details/gtijefutms.html

Ruby: @name = "x"
来源：http://dali.jyoumei.cn/Article/details/gtckedgjsn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gtzgvqjsyz.html

[G04] 定义方法
来源：http://dali.tanke756.top/Article/details/gtfjctvjjc.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymjujnyz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtxudnxkja.html

JS:   greet() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtvfmxeyca.html

TS:   greet(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtnjoceydk.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtxlaqlsls.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtmgftojvn.html

Ruby: def greet; @name; end
来源：http://dali.xziqi.cn/Article/details/gtoaecwqen.html

C#:   public string Greet() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtkzwkfqzz.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gtgpvcghjz.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gtfjjcrqxm.html

PHP:  class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtuetjrjpv.html

JS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtknlqwlxk.html

TS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtvuxenkse.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtdytgadzw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gtteslidyn.html

Ruby: class Admin < User; end
来源：http://dali.cheryme.top/Article/details/gthtdvkxvr.html

C#:   class Admin : User {}
来源：http://dali.sufxvd.cn/Article/details/gtihhmxdhx.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gtxrtdvlto.html

Py:   def greet(self): return "admin"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdiczfjft.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtwnkxdxau.html

JS:   greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtgrfanbcm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtrunrprph.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtddjfezow.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gtcrgsfrkn.html

Ruby: def greet; "admin"; end
来源：http://dali.jlsjyb.cn/Article/details/gtagczvaet.html

C#:   public override string Greet() => "admin";
来源：http://dali.jianghu66.top/Article/details/gtmdxlzrfe.html

[G07] 调用父类方法
来源：http://dali.yj20258888.top/Article/details/gtpwmsmnjx.html

Py:   super().greet()
来源：http://dali.svipenyu.cn/Article/details/gtqunkxyhn.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gtuwiymddi.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtyeaddany.html

TS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtivriaejy.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtivdbslbd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yanxiufei.cn/Article/details/gtjilmukco.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gtnxmqidnx.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gtlwvordwy.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gtidlgnzwg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sweek.top/Article/details/gtjqixorkp.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtynexnxbn.html

JS:   static f() {}
来源：http://dali.bjfxy.top/Article/details/gtvbnsrzad.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gtevibjxwd.html

Java: static void f() {}
来源：http://dali.ybcxt.top/Article/details/gtjejuiwou.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuetiantiany.cn/Article/details/gtarqrcvnf.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gtjvqmgvix.html

C#:   public static void F() {}
来源：http://dali.meibo888.top/Article/details/gtjrrnbnkb.html

[G09] 接口 / 抽象类
来源：http://dali.meibo888.top/Article/details/gtejvztcyz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cqqwz.cn/Article/details/gtfcsszogk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtornpxrlb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hammf.cn/Article/details/gtrxjpamlk.html

TS:   interface Shape { area(): number; }
来源：http://dali.ppjwa.cn/Article/details/gtnhnvcdty.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gtrhjtiimh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hfpthk.cn/Article/details/gtgrzgzuti.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuetiantiany.cn/Article/details/gtvnxvgdaq.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpuwdbfv.html

[G10] 访问控制
来源：http://dali.cqqwz.cn/Article/details/gtrtxqayrn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.meibo888.top/Article/details/gtmgtcqojc.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtynbvxjnq.html

JS:   #private 字段；其余公开
来源：http://dali.cdnleiting.top/Article/details/gtjgdkymwo.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtotzrftdw.html

Java: public / protected / private / 默认包级
来源：http://dali.yonumen.top/Article/details/gtgnbexsji.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gtlcthfdau.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtrnmdtcim.html

C#:   public / protected / private / internal
来源：http://dali.xylfe.cn/Article/details/gtklitmvhp.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gtzndpmujl.html

Py:   @property 与 @x.setter
来源：http://dali.0kj1m.cn/Article/details/gtaxqorgwm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtctqcmkdu.html

JS:   get name() { return this._name; }
来源：http://dali.sweek.top/Article/details/gtolzppsbv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtkzdodpbg.html

Java: public String getName() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtdcmrjlkq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtaexzwtbj.html

Ruby: attr_accessor :name
来源：http://dali.feifeiyinyue.top/Article/details/gtjlqsrkvi.html

C#:   public string Name { get; set; }
来源：http://dali.shzxlz.cn/Article/details/gtfxeghual.html

[G12] 对象转字符串
来源：http://dali.svipenyu.cn/Article/details/gtbxxwhjzm.html

Py:   def __str__(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtefblprmr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtvfnbdbdv.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtdlucqn.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtpcdsyxib.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtgpyblvjc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtsifnxidv.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gtmexyozca.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gtgvsrqfvg.html

[G13] 判断对象类型
来源：http://dali.hnqzz.top/Article/details/gtrfyjxbmb.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gtubuunsbk.html

PHP:  $u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtyeqysbbe.html

JS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtzfhmsqhg.html

TS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtyhfsqoun.html

Java: u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtthhkascr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.havefunace.top/Article/details/gtqbjkbjld.html

Ruby: u.is_a?(User)
来源：http://dali.dashuyun.cn/Article/details/gtlswyhakw.html

C#:   u is User
来源：http://dali.wangdashe.top/Article/details/gtrwufqogg.html

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gtnyyfzizj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258888.top/Article/details/gtortoiqfo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ydzc1.top/Article/details/gtvkxerztx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gtmignmxxf.html

TS:   type User = { name: string; age: number };
来源：http://dali.meibo888.top/Article/details/gtgdpayuxw.html

Java: record User(String name, int age) {}
来源：http://dali.wangdashe.top/Article/details/gtmfhzemef.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gtoprslowy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.kuanghao11.cn/Article/details/gthabhyisq.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gtopfzzpvf.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gtbmoftrnp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhixingplan.top/Article/details/gthkjactrx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aizwys.cn/Article/details/gtjeuamgop.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jlsjyb.cn/Article/details/gtlwpntryc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gtatodlyyd.html

Java: enum Color { RED, GREEN }
来源：http://dali.fzhhl.top/Article/details/gtjzplneus.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cashguo.top/Article/details/gtsxhlowdc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pengpengdd.cyou/Article/details/gtsgttabms.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtxnghxffl.html

[G16] 对象转数组 / 字典
来源：http://dali.pengpengdd.cyou/Article/details/gtjdjayvgm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gtbdpdqxxs.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gtuzmcfgkf.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gthauutdda.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzksoqgdy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gogol.net.cn/Article/details/gtdxhjnjcy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jlsjyb.cn/Article/details/gtoovmisqk.html

Ruby: obj.instance_variables
来源：http://dali.jianghu66.top/Article/details/gtymaagneb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtcjzrotwz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqdyoexdu.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gtoqvhulam.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtqovuokvt.html

[H01] try / catch 基础
来源：http://dali.guannengcc.top/Article/details/gtaonjqhlc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuanzx.com/Article/details/gtvafsayif.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhixingplan.top/Article/details/gtrjufjhyz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gteiqjedms.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtryvftepu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.vqdsnc.cn/Article/details/gtpykdpzor.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gtpobuhzmx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jianghu66.top/Article/details/gtlwdqdscd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlysopco.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gtixtlgtna.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tianlin.xyz/Article/details/gtspalidnv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtzjgsxwde.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtamhiuhou.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtyscpczuc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtdzgosqgs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhoulong.xyz/Article/details/gtjdxgieve.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuanzhike.top/Article/details/gtihucalhl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtnexgyjsg.html

[H03] 主动抛出异常
来源：http://dali.zdqjudy.top/Article/details/gtapdgjtcf.html

Py:   raise ValueError("错误信息")
来源：http://dali.hysaishi.cn/Article/details/gtkfcsfoxm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtkicapwnl.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtadmvojas.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtgbehgjas.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtggkgxylx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shuidangran.top/Article/details/gtjkjdwpon.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhengqikj.top/Article/details/gtcqudzhjs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtlzuljpzw.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gtmqeottrk.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigufen.top/Article/details/gtphgtivea.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtgoregatp.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gteqcprbuz.html

TS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtqidgqszs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtulgfwtkp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xinyue.icu/Article/details/gtpadjqggi.html

Ruby: class MyError < StandardError; end
来源：http://dali.cashguo.top/Article/details/gtujxiaqqg.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258888.top/Article/details/gtuwhzwwzf.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gtfgkqvsni.html

Py:   except ValueError as e:
来源：http://dali.vqdsnc.cn/Article/details/gtzwnbojrd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hywenlv.cn/Article/details/gtksgrfihb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtwwhiytuc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtfjilxhga.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ehwqpu.com/Article/details/gtwdzawfwb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ppjwa.cn/Article/details/gteygrdemu.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gtfdoybgrf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gtjknpjtze.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdueekduy.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gtxhuoqovf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtlbbcxpln.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gtgqgttjjv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gthqicrssn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhpoxjnh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xylfe.cn/Article/details/gttrafnyzk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gtdqpkmdah.html

C#:   obj?.A?.B ?? default
来源：http://dali.ivvv.top/Article/details/gtxovlycnd.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gtgsthvfkh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.haohaochexian.top/Article/details/gtbkjerdch.html

PHP:  assert($x > 0);
来源：http://dali.aizwys.cn/Article/details/gtfcdhayaq.html

JS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtelzbuhiq.html

TS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtgfyhevsi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yvedp.cn/Article/details/gtqfpfivkt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gtmienmjyf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gtcpxvroik.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gttswwbwwa.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenlongwang.top/Article/details/gtdbbqeazy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzowltfji.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daria6918.cn/Article/details/gtzrbqpkqn.html

JS:   e.message;  e.stack
来源：http://dali.hongshengwenyu.top/Article/details/gtqivuaelq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.kuanghao11.cn/Article/details/gtkfcyvjpo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gtvcpacdjt.html

Go:   err.Error()
来源：http://dali.xziqi.cn/Article/details/gtpmpckzls.html

Ruby: e.message;  e.backtrace
来源：http://dali.redwolf501.top/Article/details/gteyanofle.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ivvv.top/Article/details/gtlshhpalp.html

[H09] 带错误码的异常
来源：http://dali.dianchejie.cn/Article/details/gtqxfkarhx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zdqjudy.top/Article/details/gtyhishlwb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gtchadicav.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhiwuduotai.top/Article/details/gthuaacwvm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fzhhl.top/Article/details/gtdpsettwr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cucudq.cn/Article/details/gtoqrdxheg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gtcghgtipz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.quarkkingdee.top/Article/details/gtxgtehkdc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258888.top/Article/details/gtxjckfrju.html

[H10] 资源自动释放
来源：http://dali.shzxlz.cn/Article/details/gtekiubhlh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.iojbl.cn/Article/details/gtempvqlnb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.andypj.xyz/Article/details/gttgcbdugj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtmvdojhjy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtmowytmfy.html


<!-- 参考信息 -->