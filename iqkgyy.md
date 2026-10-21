代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gtriwsmhxz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xziqi.cn/Article/details/gtarrqngsp.html

PHP:  file_exists("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtrslzrpxz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtqvexzdas.html

TS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtwwccfbpw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gteyccabva.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gtwiluugcy.html

Ruby: File.exist?("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtslgqxfhf.html

C#:   File.Exists("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtwzucwtbm.html

[F06] 删除文件
来源：http://dali.nanxinkj.top/Article/details/gtccakcuiq.html

Py:   os.remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtcffwiepw.html

PHP:  unlink("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtnddqvwwr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtgceymtcb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtewaosmtq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsrwoqbf.html

Go:   os.Remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtzqmgdnbd.html

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtbommxjmo.html

C#:   File.Delete("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtvskdlywc.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gtclaapgxm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gtkasvugkf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gtaeuxpgsn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gtwxztzhcy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gtoqaoohxy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cheryme.top/Article/details/gtlobhgcwm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.redwolf501.top/Article/details/gtqsagxayx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zdqjudy.top/Article/details/gtvsbikfji.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gtcpazdwsc.html

[F08] 遍历目录
来源：http://dali.mhx1999.top/Article/details/gtnsknkyyd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shzxlz.cn/Article/details/gtozxxjpya.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.havefunace.top/Article/details/gtchnwprub.html

JS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtorimvfrx.html

TS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtwtlmihkk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtawwaponw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sxryk.cn/Article/details/gtdpvmjmla.html

Ruby: Dir.children("dir")
来源：http://dali.yuanzhike.top/Article/details/gtilvafxhk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtjdbjvfkc.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gtaqmjhqmb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtvrzugvhv.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtwkxukxyg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gttwkkcgax.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gtorifiuwc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtljistxji.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjyaotyz.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkpotcax.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guowangkeji.top/Article/details/gtlvkujkpx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gtblzhebcq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtbutlanwo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gtjfuhsalk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtzjvlqfeh.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtniirfvtt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gtyhebxezf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtcsdnikui.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtrvfupenb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gthkfsqtex.html

[F11] 复制与移动文件
来源：http://dali.sweek.top/Article/details/gtyjararpe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtboeepydk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtymkknnor.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtslafrxhl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtqlgwmqql.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tian-w.cn/Article/details/gtvwfsxeyv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigfzy.top/Article/details/gtzdlqvybg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtzyyzbsty.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gtbkbhuvjq.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gtbvhalsvi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gtnihdsimd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aizwys.cn/Article/details/gtythuwgis.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gttkljuctk.html

TS:   // 同上
来源：http://dali.snrcjt.cn/Article/details/gtknvmkshe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnqzz.top/Article/details/gtgzpfbimc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.birdmap.top/Article/details/gtlrqvphmd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xziqi.cn/Article/details/gtfqaviuaa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukicthkj.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtemneyasz.html

G. 面向对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjbmcrmx.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtfdwkiowy.html

[G01] 定义类
来源：http://dali.yongpay.top/Article/details/gtrlvlckmq.html

Py:   class User: pass
来源：http://dali.shzxlz.cn/Article/details/gtjthvwgvl.html

PHP:  class User {}
来源：http://dali.chenzaomai.com/Article/details/gtusxhwlap.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtedvonlnx.html

TS:   class User { name: string = ""; }
来源：http://dali.hysaishi.cn/Article/details/gtpywyhtnt.html

Java: class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtyyqeilxv.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gtydssjetz.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gttvaadlrq.html

C#:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtuwfwpxwo.html

[G02] 构造函数
来源：http://dali.yonumen.top/Article/details/gtyufxnnih.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.havefunace.top/Article/details/gtjdxhdrzl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shuidangran.top/Article/details/gtxxaexrrk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtqnrfwzkw.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gtdohiffpn.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtqljtmodf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gtjxqwrset.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.mhx1999.top/Article/details/gtmvpokhgl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jianghu66.top/Article/details/gtvmmzpagu.html

[G03] 实例属性
来源：http://dali.bjfxy.top/Article/details/gtmysfyyyg.html

Py:   self.name = "x"
来源：http://dali.sxryk.cn/Article/details/gtdhttuxaf.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtopdkxehq.html

JS:   this.name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtprckpysn.html

TS:   name: string = "x";
来源：http://dali.sufxvd.cn/Article/details/gtanroqhqu.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gtaclzcxiq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gtzlasgyik.html

Ruby: @name = "x"
来源：http://dali.yj20258888.top/Article/details/gtymbludzn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sysykeji.top/Article/details/gtnarglvht.html

[G04] 定义方法
来源：http://dali.hongshengwenyu.top/Article/details/gtpkeoupoo.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtyzfnrzok.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gthqhtuksq.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtnbfwnqxl.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtsdjoudyf.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpycxxanh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtslstnodc.html

Ruby: def greet; @name; end
来源：http://dali.yonumen.top/Article/details/gtixycfwwp.html

C#:   public string Greet() => Name;
来源：http://dali.zdqjudy.top/Article/details/gttqwynplh.html

[G05] 继承
来源：http://dali.zdqjudy.top/Article/details/gtfhzdnnff.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gtatgcrpzd.html

PHP:  class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtanluthzo.html

JS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtauipbstc.html

TS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtfipjvwfj.html

Java: class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtkjyddhzk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gtvubxbrej.html

Ruby: class Admin < User; end
来源：http://dali.yuxming.cn/Article/details/gtpylobyna.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gtvmybplsr.html

[G06] 重写方法
来源：http://dali.ehwqpu.com/Article/details/gtrbczxxwa.html

Py:   def greet(self): return "admin"
来源：http://dali.hysaishi.cn/Article/details/gtlyhndvea.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtfhojaivd.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtzkklxpal.html

TS:   greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtwgklsdrg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtvdztpqhl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shangyingyoupin.top/Article/details/gtlafmxmhf.html

Ruby: def greet; "admin"; end
来源：http://dali.xylfe.cn/Article/details/gtjkozmegm.html

C#:   public override string Greet() => "admin";
来源：http://dali.gaohongyu789.top/Article/details/gttuxlffgc.html

[G07] 调用父类方法
来源：http://dali.hongshengwenyu.top/Article/details/gtqkdrwkyl.html

Py:   super().greet()
来源：http://dali.cqqwz.cn/Article/details/gtruyzfjef.html

PHP:  parent::greet();
来源：http://dali.aibaodan.cn/Article/details/gtirgrdjqk.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtrotgvrhz.html

TS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gtingjrhpn.html

Java: super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtodkdqxnw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pycfn.com/Article/details/gtdgfbkskc.html

Ruby: super
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshuxffcm.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gtqhvzipwl.html

[G08] 静态方法与属性
来源：http://dali.pengpengdd.cyou/Article/details/gtisqjhddv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gtehzusrzh.html

PHP:  public static function f() {}
来源：http://dali.chenlongwang.top/Article/details/gtjilgbout.html

JS:   static f() {}
来源：http://dali.sysykeji.top/Article/details/gtpghglpmx.html

TS:   static f(): void {}
来源：http://dali.fengsongda.top/Article/details/gtbmphqfbw.html

Java: static void f() {}
来源：http://dali.sxryk.cn/Article/details/gtbzjgplde.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shuidangran.top/Article/details/gtinefolpy.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gthzqvfhrh.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gtfkdqtzpe.html

[G09] 接口 / 抽象类
来源：http://dali.ivvv.top/Article/details/gtuqiiimhc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gtvemmwfam.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gtszwifgaf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shuidangran.top/Article/details/gtcvwxbkoo.html

TS:   interface Shape { area(): number; }
来源：http://dali.cdnleiting.top/Article/details/gtaspeqgoq.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigufen.top/Article/details/gthafekolw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aibaodan.cn/Article/details/gtzopwqlaq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigufen.top/Article/details/gtmqpnrjsx.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gtusmgqxfb.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gtognsbpud.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hfpthk.cn/Article/details/gtyeblbxvk.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtfdhpryzz.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gtjrgeamml.html

TS:   public / protected / private
来源：http://dali.havefunace.top/Article/details/gtcmacfnfb.html

Java: public / protected / private / 默认包级
来源：http://dali.shzxlz.cn/Article/details/gtxukjyoyz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.kuanghao11.cn/Article/details/gtcspkbhjl.html

Ruby: public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtxpukoshn.html

C#:   public / protected / private / internal
来源：http://dali.zycfv.cn/Article/details/gtwsonpiwh.html

[G11] getter / setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcptopfyc.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigufen.top/Article/details/gtwfazrwyn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtkhlbdlzq.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtmxorupog.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gtrvhqcxur.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtyqhyoazm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtlkcatzoo.html

Ruby: attr_accessor :name
来源：http://dali.svipenyu.cn/Article/details/gtpvvrljei.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gtwwrfrebe.html

[G12] 对象转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtpavjazwk.html

Py:   def __str__(self): return self.name
来源：http://dali.sweek.top/Article/details/gtiypchxkm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcjntttpe.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtrptydaoe.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtudunrkct.html

Java: @Override public String toString() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtsoptieoo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gthhjdlzvl.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gtkmvschdo.html

C#:   public override string ToString() => Name;
来源：http://dali.tanke756.top/Article/details/gtpgxopktg.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdxdbnmt.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gtotjhsbjz.html

PHP:  $u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtdgfywvuj.html

JS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtgmcnoyui.html

TS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtduarnvfd.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtgegrycus.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gtbextnoir.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gtzlilekja.html

C#:   u is User
来源：http://dali.ivvv.top/Article/details/gtucjzcqoi.html

[G14] 数据类 / record
来源：http://dali.daria6918.cn/Article/details/gttntwvoaf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhiwuduotai.top/Article/details/gtcrnnfeji.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fzhhl.top/Article/details/gtacqdphiy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuxming.cn/Article/details/gtecvwhnah.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhengqikj.top/Article/details/gttbplikud.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gtwiuicukt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gtgehjjhap.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yongpay.top/Article/details/gtbzhiuawc.html

C#:   record User(string Name, int Age);
来源：http://dali.mhx1999.top/Article/details/gtklrawsuz.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtlbiiteyy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxszmecg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gtpmbnowjm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.quarkkingdee.top/Article/details/gtmnrwjmcp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gtnhtmhuxv.html

Java: enum Color { RED, GREEN }
来源：http://dali.hammf.cn/Article/details/gtgjotgkzi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gtaktwbrpa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.haohaochexian.top/Article/details/gttqngttpr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtbdokdybn.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gtqjppmgap.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gtfsrvizcu.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gtaezvxpmv.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtpocuocbz.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gtizehdotm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gtfdncydxe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guannengcc.top/Article/details/gtrqzpcxly.html

Ruby: obj.instance_variables
来源：http://dali.hnqzz.top/Article/details/gtjdyrtyox.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gtrsfubjhb.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtcexqmirz.html

H. 异常与错误处理
来源：http://dali.xinyue.icu/Article/details/gtueedxcty.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvykztghn.html

[H01] try / catch 基础
来源：http://dali.meibo888.top/Article/details/gtupskoxoc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aizwys.cn/Article/details/gtplhpgeip.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jianghu66.top/Article/details/gtsvbbazsc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtgrileirw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtonomprpr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ybcxt.top/Article/details/gtpmrgjram.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gtsfogkzwy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtdelrlbbt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258.top/Article/details/gtsmlazjny.html

[H02] finally / ensure 收尾
来源：http://dali.c1oappe.top/Article/details/gtplcxkjuf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbldbiay.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtrckgdxre.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtgylwysfm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtugmjmzvt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtyumdupcd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gtbvezzssr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gtnmzsibfy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtcxbabsvu.html

[H03] 主动抛出异常
来源：http://dali.zhengqikj.top/Article/details/gtkreuorvc.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgufenzy.top/Article/details/gtgqrlykcu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtxusxscgv.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtqfchjiyf.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtvltvtgaa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gthhhfpxeo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gtvrvgugzf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzdnamdg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtrczjlnbh.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gtxypqwwgl.html

Py:   class MyError(Exception): pass
来源：http://dali.ydzc1.top/Article/details/gtrnpnvwfh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtmqhaxdio.html

JS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtyqqyrdgm.html

TS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtfaaqmwqj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpbyptvn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.redwolf501.top/Article/details/gtghaiwbst.html

Ruby: class MyError < StandardError; end
来源：http://dali.ydzc1.top/Article/details/gtvapxkujh.html

C#:   class MyException : Exception {}
来源：http://dali.svipenyu.cn/Article/details/gtlkfhssca.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gtupfycwsq.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdqpmwme.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dianchejie.cn/Article/details/gteoviqivq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gtcmtrlpla.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoaelbicv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztdqrdnt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gteyjjacdr.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gtttcgtwge.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gtokwalbct.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hammf.cn/Article/details/gtyqbcvzko.html

Py:   value = d.get("k") or default
来源：http://dali.zhoulong.xyz/Article/details/gtgwbuguns.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtfoslvhok.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gtvhvbjfok.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gtizuqvpoc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhoulong.xyz/Article/details/gtnnpgwjjv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ivvv.top/Article/details/gtvpfzigjc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gtwnbzcigy.html

C#:   obj?.A?.B ?? default
来源：http://dali.jyoumei.cn/Article/details/gteanpukkj.html

[H07] 断言
来源：http://dali.nanxuanxn.top/Article/details/gtimsvqfrm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hywenlv.cn/Article/details/gtoiesjhwr.html

PHP:  assert($x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gttsmcdioe.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtdnowcipi.html

TS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtzlxmohvf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelpdjsrg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pycfn.com/Article/details/gtclfajsjt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cqqwz.cn/Article/details/gtnoqkxkgu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtuaglitkz.html

[H08] 获取错误信息与堆栈
来源：http://dali.sufxvd.cn/Article/details/gtjvjpfksu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gtztahsjwc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cucudq.cn/Article/details/gtdrvcnzzq.html

JS:   e.message;  e.stack
来源：http://dali.cheryme.top/Article/details/gtirolfqir.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ydzc1.top/Article/details/gtmzyehgrw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ydzc1.top/Article/details/gtrwpkkbhl.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gtmbzjstig.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigfzy.top/Article/details/gttlaggntb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuanzhike.top/Article/details/gtwftpkpzy.html

[H09] 带错误码的异常
来源：http://dali.shuidangran.top/Article/details/gtlfgvppcp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuanzhike.top/Article/details/gtmgazwmoi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sufxvd.cn/Article/details/gtkmyiavwa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgufenzy.top/Article/details/gtqyddzihj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dianchejie.cn/Article/details/gtiommalwq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gtladkrpuy.html


<!-- 参考信息 -->