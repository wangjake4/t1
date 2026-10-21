代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtvxewqusi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtaporfbup.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gteoghcmea.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtqlfcpamn.html

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtlitalsmu.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtiewyiyae.html

[F07] 创建目录（含多级）
来源：http://dali.aibaodan.cn/Article/details/gtvtxybudr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gtiotksahi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fengsongda.top/Article/details/gtyteahfvz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtxgjdjppr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtapouvnmr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gtmohhufpa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.birdmap.top/Article/details/gtvfhtzoxd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigfzy.top/Article/details/gtmhcgordf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.havefunace.top/Article/details/gtmuzoyopy.html

[F08] 遍历目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvchtqxur.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gogol.net.cn/Article/details/gttaglqyqb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gaohongyu789.top/Article/details/gtdignrvda.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtynaenqbj.html

TS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtdrscethz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gttdkceenn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtmqtjmknl.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gtkvmgqprc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gtmzbmtris.html

[F09] 获取文件大小
来源：http://dali.andypj.xyz/Article/details/gtypcbqivc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtyzslsunh.html

PHP:  filesize("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtszekltoj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtqsbxoazh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gtwsteaiwy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtjrkmuihq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ydzc1.top/Article/details/gthlyiqcpv.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtyyqffwqh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hfpthk.cn/Article/details/gtnhriimzt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pengpengdd.cyou/Article/details/gtdyjpszrr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtqnydwzgg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtjfaucwaf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtrvzvxcdo.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtgupcotcw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ehwqpu.com/Article/details/gtfbqblvtr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtyyezwtnb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtnsaxsqpz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gthrqplakm.html

[F11] 复制与移动文件
来源：http://dali.yj20258.top/Article/details/gttrnsnlhh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtryjhwezk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guannengcc.top/Article/details/gtlztktdrf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtwfwnpdkm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtqrcazzby.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuxming.cn/Article/details/gthcmsiwzk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ehwqpu.com/Article/details/gtzlydbomi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtsvzmseoj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gtszqexqmr.html

[F12] CSV 读写
来源：http://dali.shuidangran.top/Article/details/gtkkitpcei.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gttvpkyorm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuanzhike.top/Article/details/gtzdlrysff.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gtcmwrtqbk.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gttyrmigme.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gteoxazpzn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gtobwifumd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gogol.net.cn/Article/details/gtwyxoqcqw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gotoacloud.top/Article/details/gtycxcfmgs.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtnjmsnihb.html

G. 面向对象
来源：http://dali.kuanghao11.cn/Article/details/gtvbiwzydd.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttztfptbn.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gtlgxplzuk.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gtnupybnap.html

PHP:  class User {}
来源：http://dali.gotoacloud.top/Article/details/gthhtjzdib.html

JS:   class User {}
来源：http://dali.sxryk.cn/Article/details/gthpnarzkt.html

TS:   class User { name: string = ""; }
来源：http://dali.chenjidiqi.icu/Article/details/gtroodtdoh.html

Java: class User {}
来源：http://dali.redwolf501.top/Article/details/gtggnigyoo.html

Go:   type User struct { Name string }
来源：http://dali.gogol.net.cn/Article/details/gtihuxrmzf.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gttpkxhxvm.html

C#:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtytrshiun.html

[G02] 构造函数
来源：http://dali.yvedp.cn/Article/details/gtqxctfuyf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnxiangtu.top/Article/details/gtkgrbrzrq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenlongwang.top/Article/details/gtioopuptk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gtussgpflx.html

TS:   constructor(public name: string) {}
来源：http://dali.yongpay.top/Article/details/gtebveyfqf.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtcvypgpcu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tanke756.top/Article/details/gtnikfprox.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gtmttzmlqa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfdncenm.html

[G03] 实例属性
来源：http://dali.gogol.net.cn/Article/details/gtplozhdnt.html

Py:   self.name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtlapdpghf.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtvjxcvokc.html

JS:   this.name = "x";
来源：http://dali.yuanzhike.top/Article/details/gtiyncsyah.html

TS:   name: string = "x";
来源：http://dali.havefunace.top/Article/details/gtsulthqfw.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gtelqskjcs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hysaishi.cn/Article/details/gthvqquxmo.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gthinwcwed.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.havefunace.top/Article/details/gtvwmtdgga.html

[G04] 定义方法
来源：http://dali.xylfe.cn/Article/details/gtilpiybpt.html

Py:   def greet(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gtsllwlbtx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtvuzuzqdv.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtselbvmps.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtgartepzz.html

Java: String greet() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtsxmkdhjs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtvhvribvz.html

Ruby: def greet; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gtupahnqug.html

C#:   public string Greet() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtqanaersl.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gtdymvatws.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gtlwcyeayh.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtmmqlfpqn.html

JS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gttawigbay.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtgopvlwbl.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtahnxvuby.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gtzykqslmn.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gtsdofjqtz.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gtvhpwnsgb.html

[G06] 重写方法
来源：http://dali.wangshuangyany.cn/Article/details/gtunduyvcz.html

Py:   def greet(self): return "admin"
来源：http://dali.jiagoushi.top/Article/details/gtwdjxqvkt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtasfgspif.html

JS:   greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtypxijeld.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtjgskggnl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtwvzqwywy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj202588.top/Article/details/gtaywsvquh.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkjywfwb.html

C#:   public override string Greet() => "admin";
来源：http://dali.gotoacloud.top/Article/details/gtmimztubl.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gtfdwvoyyt.html

Py:   super().greet()
来源：http://dali.tianlin.xyz/Article/details/gtuyxhguxp.html

PHP:  parent::greet();
来源：http://dali.havefunace.top/Article/details/gtrhnxptns.html

JS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gtolrkempk.html

TS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gthglsirym.html

Java: super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtfdlvqkyn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shuidangran.top/Article/details/gtnkpntkok.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gtpjkbfzfu.html

C#:   base.Greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtjnpbmvkk.html

[G08] 静态方法与属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpofsohc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqxrevxf.html

PHP:  public static function f() {}
来源：http://dali.tianlin.xyz/Article/details/gtcomyglhg.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gtpjkgkriw.html

TS:   static f(): void {}
来源：http://dali.9152youxi.cn/Article/details/gtmawepqgb.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtqyyjheer.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dianchejie.cn/Article/details/gtakeohmbl.html

Ruby: def self.f; end
来源：http://dali.fengsongda.top/Article/details/gtkkldmdom.html

C#:   public static void F() {}
来源：http://dali.yonumen.top/Article/details/gtkfwfzyew.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gtfaboaxzz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gtzuvgcqcr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gtfrgxmotk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.mhx1999.top/Article/details/gtqlkgbbug.html

TS:   interface Shape { area(): number; }
来源：http://dali.tanke756.top/Article/details/gtxhseserc.html

Java: interface Shape { double area(); }
来源：http://dali.tianlin.xyz/Article/details/gtviuyslqa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenlongwang.top/Article/details/gtpskpgddc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sysykeji.top/Article/details/gtxxzosibj.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtpttxkxdd.html

[G10] 访问控制
来源：http://dali.cqqwz.cn/Article/details/gthgsyyxmb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zycfv.cn/Article/details/gteoyovjys.html

PHP:  public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtbkbyoomy.html

JS:   #private 字段；其余公开
来源：http://dali.gogol.net.cn/Article/details/gtfskdfjnt.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtxfnsmjuc.html

Java: public / protected / private / 默认包级
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiavicxoy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jiagoushi.top/Article/details/gtklszujsx.html

Ruby: public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtaetexxir.html

C#:   public / protected / private / internal
来源：http://dali.hywenlv.cn/Article/details/gtqjdrmebm.html

[G11] getter / setter
来源：http://dali.shuidangran.top/Article/details/gtrdwheipx.html

Py:   @property 与 @x.setter
来源：http://dali.haohaochexian.top/Article/details/gthbecmsim.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtonvnigef.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtysziahdf.html

TS:   get name(): string { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtybefdbqg.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtbmmhaebx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtlrkewejq.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gtgovewsms.html

C#:   public string Name { get; set; }
来源：http://dali.iojbl.cn/Article/details/gtlqcubfmw.html

[G12] 对象转字符串
来源：http://dali.0kj1m.cn/Article/details/gticrwcrhw.html

Py:   def __str__(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtjabhjfkm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtgkuhasxb.html

JS:   toString() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtgciupxtr.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtctqamfvf.html

Java: @Override public String toString() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtvgukwoqi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtztzmpfay.html

Ruby: def to_s; @name; end
来源：http://dali.xziqi.cn/Article/details/gtefxeoxqt.html

C#:   public override string ToString() => Name;
来源：http://dali.cashguo.top/Article/details/gticqshtis.html

[G13] 判断对象类型
来源：http://dali.jyoumei.cn/Article/details/gtdgfvpodb.html

Py:   isinstance(u, User)
来源：http://dali.jianghu66.top/Article/details/gttihpzwst.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtbuymfsai.html

JS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtterjemnz.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtaqbrghap.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtwgrttved.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtguktoene.html

Ruby: u.is_a?(User)
来源：http://dali.yvedp.cn/Article/details/gtzrqpmese.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gtcjxfzmmd.html

[G14] 数据类 / record
来源：http://dali.andypj.xyz/Article/details/gtaygbiedk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ybcxt.top/Article/details/gtjiyqdnfr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jyoumei.cn/Article/details/gtqviogdmu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gthfsiyyci.html

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gthalwhwtm.html

Java: record User(String name, int age) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtpwhrglqq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgcsknkx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnxiangtu.top/Article/details/gtqxkhojxt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhixingplan.top/Article/details/gtyttdwplg.html

[G15] 枚举
来源：http://dali.yongpay.top/Article/details/gtltzpujwb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.havefunace.top/Article/details/gthwoiinbf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.redwolf501.top/Article/details/gtjybubaxx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.birdmap.top/Article/details/gtqrcdqjjc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtqpzspsvf.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gtmbtxmoxd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gaohongyu789.top/Article/details/gtjqzojvnp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yvedp.cn/Article/details/gtsxfefuxg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtmvcuvsfc.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gtonpndaok.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gtagwxmegp.html

PHP:  get_object_vars($obj);
来源：http://dali.xylfe.cn/Article/details/gtltsurwwk.html

JS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtggdwlwcz.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gticmnxelx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gtrnaysgtg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqumbgij.html

Ruby: obj.instance_variables
来源：http://dali.dianchejie.cn/Article/details/gtzohvnkxv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gtdgzrmwky.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtlwauhzcy.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gthowmsdzr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtotjunwqz.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gtkrndkhde.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gthuncipes.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenzaomai.com/Article/details/gtfylqagvx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtaexzimgk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtvbfthrcu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.birdmap.top/Article/details/gtahnhlmhj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gtmvpacert.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenjidiqi.icu/Article/details/gttrgljxkx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.316326.xyz/Article/details/gtxhhcwuvl.html

[H02] finally / ensure 收尾
来源：http://dali.chenzaomai.com/Article/details/gtosyuheai.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gthgjmtmyj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtbfecesvf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtbniyvfyl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtotxqvtnl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtfquhhlwp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gtuikbfvig.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.snrcjt.cn/Article/details/gtvogdbdvs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtmwwkqdqj.html

[H03] 主动抛出异常
来源：http://dali.zhongyouzk.top/Article/details/gtnconiiuv.html

Py:   raise ValueError("错误信息")
来源：http://dali.aizwys.cn/Article/details/gtcgigunrx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtdbylpvxx.html

JS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtaydpnuqb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtkauotpjw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtwltyzzbi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangshuangyany.cn/Article/details/gthayrvqkn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zycfv.cn/Article/details/gttfbunpxg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtkzkjbggj.html

[H04] 自定义异常类型
来源：http://dali.pycfn.com/Article/details/gtjwzsilfn.html

Py:   class MyError(Exception): pass
来源：http://dali.ppjwa.cn/Article/details/gtxqjhushm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gtrzxxhmfl.html

JS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtemmoymbo.html

TS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtdslelgdg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtbbsgtrwf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jiagoushi.top/Article/details/gtuvejohfw.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gtoujhzsju.html

C#:   class MyException : Exception {}
来源：http://dali.zdqjudy.top/Article/details/gtryiarfxg.html

[H05] 捕获特定类型
来源：http://dali.hnqzz.top/Article/details/gtifeovqym.html

Py:   except ValueError as e:
来源：http://dali.cheryme.top/Article/details/gtjtsuxdxm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gtoupbhhfm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtkafmhxxj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gtlwbsjpuv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gtxkihiigl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gtojyhrqsz.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gtazaiygcl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gtwqbsailn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.feifeiyinyue.top/Article/details/gthnwltcmf.html

Py:   value = d.get("k") or default
来源：http://dali.havefunace.top/Article/details/gtvohorkus.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtuzyjwcrj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtuooxirpu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtykoyqidz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aibaodan.cn/Article/details/gtpxrpgpfx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxinkj.top/Article/details/gtylmfzxuh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhixingplan.top/Article/details/gtedydxsat.html

C#:   obj?.A?.B ?? default
来源：http://dali.aizwys.cn/Article/details/gtoumahzxl.html

[H07] 断言
来源：http://dali.316326.xyz/Article/details/gtvybijxly.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cdnleiting.top/Article/details/gtxiiphekl.html

PHP:  assert($x > 0);
来源：http://dali.fzhhl.top/Article/details/gtkbktdqrf.html

JS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtodplpbun.html

TS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtmtjbweda.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtgatgmtem.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpocbnutm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aizwys.cn/Article/details/gtdqkfvtfn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtjdqnuwfw.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gtmuztdtcn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gtznvukdgn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ehwqpu.com/Article/details/gtxewzcfxr.html

JS:   e.message;  e.stack
来源：http://dali.shangyingyoupin.top/Article/details/gttichmhmu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gttsstuphq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj202588.top/Article/details/gtedtvtkdu.html

Go:   err.Error()
来源：http://dali.xylfe.cn/Article/details/gtiluaxagw.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258888.top/Article/details/gtxrtvxdtk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenjidiqi.icu/Article/details/gtfdmvxdpb.html

[H09] 带错误码的异常
来源：http://dali.meibo888.top/Article/details/gtgqlloloq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cqqwz.cn/Article/details/gtkycbtpop.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daria6918.cn/Article/details/gtlvfyiooc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ehwqpu.com/Article/details/gtnyvugjcy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gtpomudrxb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gzhubu.top/Article/details/gtmcgmnlce.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cqqwz.cn/Article/details/gtoufvhelv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tanke756.top/Article/details/gtmipgtdqc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinghuilouyu.cn/Article/details/gthjgszvgs.html

[H10] 资源自动释放
来源：http://dali.snrcjt.cn/Article/details/gtwoiuzyjz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yanxiufei.cn/Article/details/gtswqssekq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.9152youxi.cn/Article/details/gtkwpglisq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gtjjcjmmzn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklnbawzq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cucudq.cn/Article/details/gthfizobre.html

Go:   defer f.Close()
来源：http://dali.fengsongda.top/Article/details/gtivtaswlk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.9152youxi.cn/Article/details/gtbghhimyg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtcnetrdub.html


<!-- 参考信息 -->