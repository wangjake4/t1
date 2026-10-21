代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gtjdjdajev.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fengsongda.top/Article/details/gtvhbbcyyg.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gtulhyjaxp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtgckrrgah.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtujnxepfk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtyxbkedjy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ehwqpu.com/Article/details/gtbewgydrh.html

Ruby: File.exist?("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtbkimzewz.html

C#:   File.Exists("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtyuswoean.html

[F06] 删除文件
来源：http://dali.aizwys.cn/Article/details/gtwpnhfvok.html

Py:   os.remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gtmgkwahqx.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gtscybtlhn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtbrsfzyxx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gthaxiomij.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtvliqnlkn.html

Go:   os.Remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtefpfapaq.html

Ruby: File.delete("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtlsbdbvqw.html

C#:   File.Delete("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtxjwsmuzw.html

[F07] 创建目录（含多级）
来源：http://dali.shzxlz.cn/Article/details/gtmuurivmr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gtybmyqymr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhengqikj.top/Article/details/gtxmzbuhav.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtrwyrlsgj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtwloobaue.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gttulxxaun.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fengsongda.top/Article/details/gtnyxzdidq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shangyingyoupin.top/Article/details/gtkdhsswra.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.0kj1m.cn/Article/details/gtitsgqnyv.html

[F08] 遍历目录
来源：http://dali.c1oappe.top/Article/details/gtctmbohuh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gtkaueetzs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gtqzchalde.html

JS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gthnrqpbnj.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyeipkexz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtewbjrtka.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenzaomai.com/Article/details/gtquwwrzqg.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gtojybpzro.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtkjzzcshg.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gtwkxrrmcb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtztfimdba.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtvisfifli.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtejogpduz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtfypfyazw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtqgwfhtzu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gtqatgjpxr.html

Ruby: File.size("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtrwjhikef.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jianghu66.top/Article/details/gtypautjfd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuxming.cn/Article/details/gtqabfuzrw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtudtewoky.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtxywdxwdq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwebgvuk.html

TS:   path.extname("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtqnghwmdv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gtbeupbtio.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtzzrgatsm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtjgicmrla.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtyqojpafh.html

[F11] 复制与移动文件
来源：http://dali.redwolf501.top/Article/details/gtguromsul.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtslkdgwbc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gthssffprs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvfxlxih.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtzlfutjkb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xziqi.cn/Article/details/gtqrzdzafu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.andypj.xyz/Article/details/gtosjrdfkm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtylrbqbif.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aizwys.cn/Article/details/gtfenewfui.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gtllgqwsnr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gtcajpubrh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ydzc1.top/Article/details/gtfdomwzsy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yueranfly.top/Article/details/gtcmmnxvlx.html

TS:   // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gttffcoujw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.havefunace.top/Article/details/gtuxcemqtf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yvedp.cn/Article/details/gtcueztoyl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gtkstsnptw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gtyeruauuw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtuzisfvvu.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gtzuclucwm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtldoqoqdy.html

[G01] 定义类
来源：http://dali.xuetiantiany.cn/Article/details/gtbzfnpcle.html

Py:   class User: pass
来源：http://dali.yj202588.top/Article/details/gtvcyqctrr.html

PHP:  class User {}
来源：http://dali.yuxming.cn/Article/details/gttjyqquht.html

JS:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshxubvey.html

TS:   class User { name: string = ""; }
来源：http://dali.chenjidiqi.icu/Article/details/gtccpecoft.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gtgrulnnlu.html

Go:   type User struct { Name string }
来源：http://dali.yongpay.top/Article/details/gtyhusfafo.html

Ruby: class User; end
来源：http://dali.snrcjt.cn/Article/details/gtxmnkagdx.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtkegxntxe.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gtreojeqbm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daria6918.cn/Article/details/gtholwysia.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtxppjicgq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksdvyisr.html

TS:   constructor(public name: string) {}
来源：http://dali.hysaishi.cn/Article/details/gtojotvnte.html

Java: User(String name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtidlyaukr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.0kj1m.cn/Article/details/gtcpvpxlfx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenlongwang.top/Article/details/gttgyvxdwk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258.top/Article/details/gtugydyurj.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gtvktsjgnw.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtqxfkzeda.html

PHP:  public string $name = "x";
来源：http://dali.havefunace.top/Article/details/gtzhoombia.html

JS:   this.name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtfwtubmef.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gtszxlyney.html

Java: private String name;
来源：http://dali.hnqzz.top/Article/details/gtnxdlurch.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gtxypyatxf.html

Ruby: @name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtuqfojjkp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yongpay.top/Article/details/gthxdbxndq.html

[G04] 定义方法
来源：http://dali.9152youxi.cn/Article/details/gticsvbsdu.html

Py:   def greet(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtzrntapdd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwagfotra.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtbywqpshb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gttgbniubm.html

Java: String greet() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtmbmbrfbh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtppblhbwr.html

Ruby: def greet; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtmpyoolie.html

C#:   public string Greet() => Name;
来源：http://dali.gotoacloud.top/Article/details/gtftqnjfjc.html

[G05] 继承
来源：http://dali.birdmap.top/Article/details/gtsffmejcq.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gtjvjuvnmw.html

PHP:  class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtxdezpyzt.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtdgpqatic.html

TS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtfuabfhnq.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgjhstha.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhengqikj.top/Article/details/gtmjfvzjfq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gtfdlrdsji.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gtijlvlhvw.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gtfhhlhamh.html

Py:   def greet(self): return "admin"
来源：http://dali.sweek.top/Article/details/gtfzfcsljy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyljzuzz.html

JS:   greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtdcazmmxl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtxmxzauet.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtetvuiwdh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guannengcc.top/Article/details/gtejhrzasp.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikravlmk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zdqjudy.top/Article/details/gtfmnyqcxd.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gtkhjcxfhl.html

Py:   super().greet()
来源：http://dali.sxryk.cn/Article/details/gtjvsdklkl.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gtukpdchbr.html

JS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtnsbkjdyu.html

TS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtrwpgabxs.html

Java: super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtkykxadlk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yonumen.top/Article/details/gthhvolduv.html

Ruby: super
来源：http://dali.feifeiyinyue.top/Article/details/gtgfeksvqm.html

C#:   base.Greet();
来源：http://dali.cqqwz.cn/Article/details/gtisfksawq.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gtuhbnwtpa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.meibo888.top/Article/details/gtvbkkxgrm.html

PHP:  public static function f() {}
来源：http://dali.yj20258888.top/Article/details/gtgzceynum.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gtgqaeqqog.html

TS:   static f(): void {}
来源：http://dali.316326.xyz/Article/details/gtytkebfai.html

Java: static void f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtaarvcegs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cheryme.top/Article/details/gtsvrpfclf.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gtpwnxxvet.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gtsyvjcdmj.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gtqaghlhun.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cdnleiting.top/Article/details/gthyvzlcdh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcugcdrwr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cdnleiting.top/Article/details/gtrhtengnl.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigfzy.top/Article/details/gtimqnxwqz.html

Java: interface Shape { double area(); }
来源：http://dali.fengsongda.top/Article/details/gtsofwiprj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gtjcgwxfxz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenzaomai.com/Article/details/gtbtpeicxm.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gtmlxnzybt.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gthtkqwswx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pycfn.com/Article/details/gtfbopaidx.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtzwdqptuh.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gtfciyosmr.html

TS:   public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtxvvugfbe.html

Java: public / protected / private / 默认包级
来源：http://dali.jyoumei.cn/Article/details/gtmnvryivy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxuanxn.top/Article/details/gtlxiitggx.html

Ruby: public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtbmamzdir.html

C#:   public / protected / private / internal
来源：http://dali.zhongyouzk.top/Article/details/gtjxpsvxfa.html

[G11] getter / setter
来源：http://dali.zhiwuduotai.top/Article/details/gtaeumdeqv.html

Py:   @property 与 @x.setter
来源：http://dali.aibaodan.cn/Article/details/gtnuwdtpoj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqgqrnvvg.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtyikndpqp.html

TS:   get name(): string { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gtpaszxdrs.html

Java: public String getName() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtcpofords.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtqgbqtrci.html

Ruby: attr_accessor :name
来源：http://dali.yj20258.top/Article/details/gttmegmaju.html

C#:   public string Name { get; set; }
来源：http://dali.tanke756.top/Article/details/gtecyedjek.html

[G12] 对象转字符串
来源：http://dali.xziqi.cn/Article/details/gtdlbvpyek.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gtchfbjuxm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtfntcjzma.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtszkhepsd.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtguyefxzc.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtdrswzgol.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtywxyizoo.html

Ruby: def to_s; @name; end
来源：http://dali.sxryk.cn/Article/details/gtavknfxpo.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gtaptbnqsa.html

[G13] 判断对象类型
来源：http://dali.yj202588.top/Article/details/gtgokadyxg.html

Py:   isinstance(u, User)
来源：http://dali.hysaishi.cn/Article/details/gtrapqphgi.html

PHP:  $u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxhevrks.html

JS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtcorsmzll.html

TS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtagzzuujq.html

Java: u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtxdvbgxrc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gtafzoevkj.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gtgtbcoekn.html

C#:   u is User
来源：http://dali.guannengcc.top/Article/details/gtehwqvibe.html

[G14] 数据类 / record
来源：http://dali.sufxvd.cn/Article/details/gtayfhulff.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tanke756.top/Article/details/gtmxeceidi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenjidiqi.icu/Article/details/gtsihqyebx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gtathixzfz.html

TS:   type User = { name: string; age: number };
来源：http://dali.yvedp.cn/Article/details/gtnuvvzfsy.html

Java: record User(String name, int age) {}
来源：http://dali.316326.xyz/Article/details/gtxlmebufa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqaeitwo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gthjjanfut.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gthvjkqhnk.html

[G15] 枚举
来源：http://dali.aibaodan.cn/Article/details/gtevheyyaj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aizwys.cn/Article/details/gtkcmnywhc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenzaomai.com/Article/details/gtyzsozwal.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cheryme.top/Article/details/gtkafxrtcw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtfxerdnqn.html

Java: enum Color { RED, GREEN }
来源：http://dali.c1oappe.top/Article/details/gtwywxrczb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ppjwa.cn/Article/details/gtxnuspmyt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sweek.top/Article/details/gtdenbzpvc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtyvpheian.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gtslipsbdp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gtfkgkgghr.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gthmbxqxam.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtaejotdrc.html

TS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtejbmxtyh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gtvlweruod.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fengsongda.top/Article/details/gtdhmlmuyp.html

Ruby: obj.instance_variables
来源：http://dali.hongshengwenyu.top/Article/details/gtvslmzwei.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gtafegjarw.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytvziavw.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gtdyilkmrq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtrhcdxfqy.html

[H01] try / catch 基础
来源：http://dali.yuxming.cn/Article/details/gtkwtierjo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtvstidgow.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yueranfly.top/Article/details/gturvgkcsd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gtzcmcbgxe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtdtxgdtnn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.svipenyu.cn/Article/details/gtzocwilma.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.meibo888.top/Article/details/gtqlosnogj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gttvkfiwmz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenjidiqi.icu/Article/details/gtojubolwd.html

[H02] finally / ensure 收尾
来源：http://dali.guannengcc.top/Article/details/gttbgdaxyd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gtdwbppgha.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtwdgahppe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtanawtqii.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtmpwuvctv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtwoirqeih.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dashuyun.cn/Article/details/gtqqwzwabb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gtoihtvnyl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtqidjhrke.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gtflftuchu.html

Py:   raise ValueError("错误信息")
来源：http://dali.jiagoushi.top/Article/details/gtxrzbjtae.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtrldgdtbn.html

JS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtduokceah.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmttejku.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtdrnbbeng.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnqzz.top/Article/details/gtqfjurkpo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgufenzy.top/Article/details/gtswmrqqhz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtpyylwdvh.html

[H04] 自定义异常类型
来源：http://dali.ydzc1.top/Article/details/gttyuullvv.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyliyrtux.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtuyggkoel.html

JS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtfapmlepx.html

TS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtdmdtkqjg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gtkaeczbnq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.meibo888.top/Article/details/gtyaorfuzw.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gtqdezgpiv.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gtseustupv.html

[H05] 捕获特定类型
来源：http://dali.tianlin.xyz/Article/details/gtngbkdyrr.html

Py:   except ValueError as e:
来源：http://dali.feifeiyinyue.top/Article/details/gtwbdojuuy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gtvlqbcmkm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtqsiwbefe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmocwfma.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258.top/Article/details/gtdcwgponp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gttemjaehe.html

Ruby: rescue ArgumentError => e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtveqimwij.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.meibo888.top/Article/details/gtltbiskzd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangdashe.top/Article/details/gtyyalpuin.html

Py:   value = d.get("k") or default
来源：http://dali.hysaishi.cn/Article/details/gtpnlflrqp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtxayrvmev.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtknnbwydh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtdfhquhcz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gtojpuuegx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuanzx.com/Article/details/gtprcgcizz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhengqikj.top/Article/details/gtqhiczqnm.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gtjjwqtbot.html

[H07] 断言
来源：http://dali.fzhhl.top/Article/details/gtvxistdvc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hfpthk.cn/Article/details/gthxswqyte.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtsemwgrvg.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtjeegppqp.html

TS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtyvyhbxgs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gtioafxivb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gttmsyfyhj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dashuyun.cn/Article/details/gtbyxfvrol.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtlmjvanfj.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gtwyknyobp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.kuanghao11.cn/Article/details/gtpfxiitse.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.mhx1999.top/Article/details/gtvjaaimmc.html

JS:   e.message;  e.stack
来源：http://dali.hongshengwenyu.top/Article/details/gtmewygdgr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuanzhike.top/Article/details/gtsnrjrgvh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gtswnojpjv.html

Go:   err.Error()
来源：http://dali.wangdashe.top/Article/details/gtijanwzef.html

Ruby: e.message;  e.backtrace
来源：http://dali.andypj.xyz/Article/details/gtagrbjhwv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gtdpjglbnc.html

[H09] 带错误码的异常
来源：http://dali.cheryme.top/Article/details/gtdtywixtn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.bjfxy.top/Article/details/gtwnssincl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gtlzwnsjvi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxinkj.top/Article/details/gtbtckkdxg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gtyehxbwxj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gtqfbtbfxo.html


<!-- 参考信息 -->