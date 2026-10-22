代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2bhsoiptg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2soyndcxy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ivvv.top/Article/details/gt2juglonsk.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2symrrpvl.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2duosqgib.html

[F06] 删除文件
来源：http://dali.hfpthk.cn/Article/details/gt2cierqcap.html

Py:   os.remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2ihmmprlj.html

PHP:  unlink("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2mvkjjcgi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2klwhpsus.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2kdwtayvr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2lyvqahli.html

Go:   os.Remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2zszlamgg.html

Ruby: File.delete("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2bfqqwtir.html

C#:   File.Delete("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2epyjhxys.html

[F07] 创建目录（含多级）
来源：http://dali.cheryme.top/Article/details/gt2nobdjveu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.vqdsnc.cn/Article/details/gt2jyllwkre.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258888.top/Article/details/gt2gkoiliyw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gt2baekmvek.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gt2kfxxuddf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jianghu66.top/Article/details/gt2gcntpfcx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.snrcjt.cn/Article/details/gt2okivfthi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhengqikj.top/Article/details/gt2nebmmbxv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gt2xskhcgtk.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gt2ftpwppow.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gt2yzihmbiv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gaohongyu789.top/Article/details/gt2edrnmwcc.html

JS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mnihgsml.html

TS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2eaeubyix.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gt2hdyaequa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2kcfnoxhk.html

Ruby: Dir.children("dir")
来源：http://dali.yongpay.top/Article/details/gt2owjltevc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zycfv.cn/Article/details/gt2aokxvydf.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gt2bxyepgvi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2hlxbmrfy.html

PHP:  filesize("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2cesnysis.html

JS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gt2vfzkwfzy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gt2tirpbeja.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2tyilbafq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pxxxgmyz.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2bzebdhmp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgfzy.top/Article/details/gt2buaywttq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.haohaochexian.top/Article/details/gt2wqszwmvi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2ealsfzei.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2ggjskmuj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2uboucdva.html

TS:   path.extname("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2zkfuhfys.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gt2crqtqyrj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2rfqwzugc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2yvxypxof.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2iudwelyy.html

[F11] 复制与移动文件
来源：http://dali.yuxming.cn/Article/details/gt2awwyifvs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2ovlydofw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.havefunace.top/Article/details/gt2blvpwdwi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gt2nwkqeviw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2wijkdduk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tanke756.top/Article/details/gt2kidyyzvu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nwbrower.top/Article/details/gt2nybsfazx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2ricobfxc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuxming.cn/Article/details/gt2qgzzoctr.html

[F12] CSV 读写
来源：http://dali.cqqwz.cn/Article/details/gt2jcnvyzly.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yueranfly.top/Article/details/gt2imbaliaa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgfzy.top/Article/details/gt2stefppcr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ufiumuna.html

TS:   // 同上
来源：http://dali.c1oappe.top/Article/details/gt2nsmoxmdx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ydzc1.top/Article/details/gt2rixjymdj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gt2zbmaxebr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gt2mtacphkw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pycfn.com/Article/details/gt2lacnlcsz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2hksdbxuj.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gt2vvsljgkl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2qdzqukqb.html

[G01] 定义类
来源：http://dali.yongpay.top/Article/details/gt2rryvtnif.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gt2lvljybmr.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gt2tsixxkcj.html

JS:   class User {}
来源：http://dali.wangdashe.top/Article/details/gt2skcbelzv.html

TS:   class User { name: string = ""; }
来源：http://dali.birdmap.top/Article/details/gt2wlaqxbrp.html

Java: class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2ofctjqhj.html

Go:   type User struct { Name string }
来源：http://dali.tian-w.cn/Article/details/gt2zpccnmok.html

Ruby: class User; end
来源：http://dali.pycfn.com/Article/details/gt2fxlgunzn.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2udqbyflo.html

[G02] 构造函数
来源：http://dali.yj20258888.top/Article/details/gt2bfvumdsg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhoulong.xyz/Article/details/gt2krhkbljf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gt2pakfdayt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gt2ezcxdimn.html

TS:   constructor(public name: string) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hbfvimdj.html

Java: User(String name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xwcywuik.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nfhlzfdi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gt2qiwzsmed.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dashuyun.cn/Article/details/gt2drqnusmf.html

[G03] 实例属性
来源：http://dali.yongpay.top/Article/details/gt2uzxeabwg.html

Py:   self.name = "x"
来源：http://dali.daria6918.cn/Article/details/gt2clsghlsa.html

PHP:  public string $name = "x";
来源：http://dali.sysykeji.top/Article/details/gt2pdlngceo.html

JS:   this.name = "x";
来源：http://dali.hnqzz.top/Article/details/gt2cpyvhbgy.html

TS:   name: string = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2gaqgqtjn.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gt2hxzodpxm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gt2wusrccny.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gt2cjearyvb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2icscvnnj.html

[G04] 定义方法
来源：http://dali.zycfv.cn/Article/details/gt2nixymsyp.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gt2vtpodjsd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2dspveqka.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2xxnkbpkj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhimnyw.html

Java: String greet() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2qedxxjtw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2kxjmwekb.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gt2jfslfinf.html

C#:   public string Greet() => Name;
来源：http://dali.sxryk.cn/Article/details/gt2gubhilht.html

[G05] 继承
来源：http://dali.9152youxi.cn/Article/details/gt2wermrwuv.html

Py:   class Admin(User): pass
来源：http://dali.zycfv.cn/Article/details/gt2yfglnafv.html

PHP:  class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2cfdjkmam.html

JS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2xvgiujxy.html

TS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2xcidnyme.html

Java: class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2bfwxtomm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hysaishi.cn/Article/details/gt2jnxpquyc.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gt2avvsqhhq.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2uxznajzv.html

[G06] 重写方法
来源：http://dali.zhixingplan.top/Article/details/gt2saoyxjaq.html

Py:   def greet(self): return "admin"
来源：http://dali.yueranfly.top/Article/details/gt2qhbyphcq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2ztqtdvut.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gt2ikmofgvq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2xrqbmnuy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2vmextaqg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gt2cqoaefio.html

Ruby: def greet; "admin"; end
来源：http://dali.jlsjyb.cn/Article/details/gt2gxxndnbp.html

C#:   public override string Greet() => "admin";
来源：http://dali.cucudq.cn/Article/details/gt2jqkysubp.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gt2yqbxxuxe.html

Py:   super().greet()
来源：http://dali.tanke756.top/Article/details/gt2wrkofuvs.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gt2vdacqhim.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2kgyeyuxm.html

TS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gt2lzhhzfgc.html

Java: super.greet();
来源：http://dali.yangfankeji.com/Article/details/gt2drhldbkf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cashguo.top/Article/details/gt2xucvnkho.html

Ruby: super
来源：http://dali.jianghu66.top/Article/details/gt2jqyzbumz.html

C#:   base.Greet();
来源：http://dali.cqqwz.cn/Article/details/gt2vsaloqja.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gt2kgklkwmb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gt2opnufrnz.html

PHP:  public static function f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2kuxwoegh.html

JS:   static f() {}
来源：http://dali.haohaochexian.top/Article/details/gt2tabutxus.html

TS:   static f(): void {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmpgjlgf.html

Java: static void f() {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ulmsvtoh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yanxiufei.cn/Article/details/gt2jviqycie.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gt2ktqxepqw.html

C#:   public static void F() {}
来源：http://dali.dianchejie.cn/Article/details/gt2tntbmkik.html

[G09] 接口 / 抽象类
来源：http://dali.gogol.net.cn/Article/details/gt2pcwzdhwp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fzhhl.top/Article/details/gt2xyzgirct.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gzhubu.top/Article/details/gt2xsqnynns.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gt2clmxogfv.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gt2fmmodtsh.html

Java: interface Shape { double area(); }
来源：http://dali.tianlin.xyz/Article/details/gt2iyweijlv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gt2aaaunlmx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yanxiufei.cn/Article/details/gt2mloyxmvi.html

C#:   interface IShape { double Area(); }
来源：http://dali.sufxvd.cn/Article/details/gt2jheaveym.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gt2vwallaop.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sweek.top/Article/details/gt2glwgrdwt.html

PHP:  public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gt2cynkrkoz.html

JS:   #private 字段；其余公开
来源：http://dali.yonumen.top/Article/details/gt2sgaovtly.html

TS:   public / protected / private
来源：http://dali.c1oappe.top/Article/details/gt2lfolodzr.html

Java: public / protected / private / 默认包级
来源：http://dali.xuetiantiany.cn/Article/details/gt2iiboseqe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxuanxn.top/Article/details/gt2dmxpeqme.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gt2abexdhby.html

C#:   public / protected / private / internal
来源：http://dali.shzxlz.cn/Article/details/gt2hbyiadnq.html

[G11] getter / setter
来源：http://dali.aibaodan.cn/Article/details/gt2kilizkes.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2micjwwyp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2eeimtjzs.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gt2vpjqvizk.html

TS:   get name(): string { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gt2wngjfkug.html

Java: public String getName() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2uulmlojd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gt2sivoutjq.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gt2mvypflpa.html

C#:   public string Name { get; set; }
来源：http://dali.wangdashe.top/Article/details/gt2jpwaqeol.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gt2qmrcxlbs.html

Py:   def __str__(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iajoaqvk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gt2tsinrllc.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2jbuqwotv.html

TS:   toString(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2uxeadqrb.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2vwzpdqfo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2otbxygsg.html

Ruby: def to_s; @name; end
来源：http://dali.ydzc1.top/Article/details/gt2amjcbrqw.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gt2tksixnzg.html

[G13] 判断对象类型
来源：http://dali.daria6918.cn/Article/details/gt2ukanxtir.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gt2tbcabvki.html

PHP:  $u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rpyxbtho.html

JS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2jhklgdej.html

TS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2utfjyjnx.html

Java: u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2vlcvemtf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ehwqpu.com/Article/details/gt2kqwjmjzz.html

Ruby: u.is_a?(User)
来源：http://dali.316326.xyz/Article/details/gt2ockeluxb.html

C#:   u is User
来源：http://dali.guannengcc.top/Article/details/gt2hyzxnoin.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhijexnr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ybcxt.top/Article/details/gt2xwjrbyaj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gt2kmlvwvso.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ybcxt.top/Article/details/gt2zepbzyxg.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gt2qlcjtdnb.html

Java: record User(String name, int age) {}
来源：http://dali.cdnleiting.top/Article/details/gt2fuhdwurs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sxryk.cn/Article/details/gt2fglfcten.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yonumen.top/Article/details/gt2nkxxcabm.html

C#:   record User(string Name, int Age);
来源：http://dali.kuanghao11.cn/Article/details/gt2jymiqftr.html

[G15] 枚举
来源：http://dali.shuidangran.top/Article/details/gt2zpzxalom.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnqzz.top/Article/details/gt2cmjqtuhv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.smart0.xyz/Article/details/gt2jciwrktg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jlsjyb.cn/Article/details/gt2zxnivjin.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2stimsewg.html

Java: enum Color { RED, GREEN }
来源：http://dali.ydzc1.top/Article/details/gt2ujqwtcpb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xinyue.icu/Article/details/gt2awnkugsh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gogol.net.cn/Article/details/gt2cgydmzzt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2mqutbder.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gt2uttalqya.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gt2zpsggrxb.html

PHP:  get_object_vars($obj);
来源：http://dali.feifeiyinyue.top/Article/details/gt2vbspmcbh.html

JS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2bwlilhzk.html

TS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gt2mwokucky.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhengqikj.top/Article/details/gt2iajeigvk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.havefunace.top/Article/details/gt2dmxmghsk.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gt2sjdjgxlt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gt2dbqulljo.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2tngxyctz.html

H. 异常与错误处理
来源：http://dali.9152youxi.cn/Article/details/gt2kwywolfe.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2ybbohclv.html

[H01] try / catch 基础
来源：http://dali.yueranfly.top/Article/details/gt2rhobplcc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenzaomai.com/Article/details/gt2krllduym.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zdqjudy.top/Article/details/gt2atmocgrk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gt2efwsmynm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gggywlvn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gt2awlnlpzd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gt2pawklmdj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhongyouzk.top/Article/details/gt2isecszgm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dianchejie.cn/Article/details/gt2fpuhoxci.html

[H02] finally / ensure 收尾
来源：http://dali.gzhubu.top/Article/details/gt2eqcjrmbk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigufen.top/Article/details/gt2lixbaetk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2tlphkxjh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2aarsdmav.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2ntgyobcs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2igztgwro.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gt2wgrypypx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gt2zgefxlip.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2fexwfadg.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmdhgswv.html

Py:   raise ValueError("错误信息")
来源：http://dali.c1oappe.top/Article/details/gt2eryahtvb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2djgmpnro.html

JS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2ncammckt.html

TS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2wqynqmru.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2nopqkvge.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pycfn.com/Article/details/gt2jnevxvra.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guannengcc.top/Article/details/gt2jplvnpbo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2mivezvcb.html

[H04] 自定义异常类型
来源：http://dali.haohaochexian.top/Article/details/gt2cadddook.html

Py:   class MyError(Exception): pass
来源：http://dali.dashuyun.cn/Article/details/gt2goexaemu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gt2hydproyk.html

JS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gt2oihlsbru.html

TS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2usmwqvvv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gt2qjskmdpa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hysaishi.cn/Article/details/gt2cxngnzqu.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gt2yhzxgcou.html

C#:   class MyException : Exception {}
来源：http://dali.sxryk.cn/Article/details/gt2svcxmyvu.html

[H05] 捕获特定类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2ycpvfgnf.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gt2huslexpq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.svipenyu.cn/Article/details/gt2uolhlyyz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gt2oorycxxu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2yuazdnam.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zycfv.cn/Article/details/gt2vldrhcgc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.haohaochexian.top/Article/details/gt2mkwqgvpv.html

Ruby: rescue ArgumentError => e
来源：http://dali.havefunace.top/Article/details/gt2auhijyhg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gt2ovyhpjwh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258888.top/Article/details/gt2zanhtwpp.html

Py:   value = d.get("k") or default
来源：http://dali.nwbrower.top/Article/details/gt2xlgruhpv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.havefunace.top/Article/details/gt2vptlclcm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gt2hrifyuor.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gt2yhibphie.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.smart0.xyz/Article/details/gt2zugzadbq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gt2iqawdjro.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuanzhike.top/Article/details/gt2loltdkqi.html

C#:   obj?.A?.B ?? default
来源：http://dali.daxiang520.top/Article/details/gt2hrbrzsjn.html

[H07] 断言
来源：http://dali.wangshuangyany.cn/Article/details/gt2fcfsrhcj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jlsjyb.cn/Article/details/gt2tauzprwn.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2opzhofal.html

JS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2kidoeluz.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2lzikoiai.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2soruccjz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gt2tynozbrs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nwbrower.top/Article/details/gt2sgnavsuk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2cyiamzpq.html

[H08] 获取错误信息与堆栈
来源：http://dali.xinyue.icu/Article/details/gt2jrkjimpr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cashguo.top/Article/details/gt2dbpzambu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gotoacloud.top/Article/details/gt2zayoqkrd.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gt2bavkasrd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gt2ooncoysh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hywenlv.cn/Article/details/gt2jsyuesgk.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gt2ytklmibn.html

Ruby: e.message;  e.backtrace
来源：http://dali.yanxiufei.cn/Article/details/gt2mfhlcuqh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tianlin.xyz/Article/details/gt2mhlfezea.html

[H09] 带错误码的异常
来源：http://dali.yueranfly.top/Article/details/gt2hvzfyjaq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shangyingyoupin.top/Article/details/gt2rciazuig.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.0kj1m.cn/Article/details/gt2xrcdfblw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daxiang520.top/Article/details/gt2uwxevzwl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuxming.cn/Article/details/gt2pcgjuqse.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gkkhucno.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.9152youxi.cn/Article/details/gt2tntoagme.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hammf.cn/Article/details/gt2vzhwnhgw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gt2rdjxbyos.html

[H10] 资源自动释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2huqlqizd.html


<!-- 参考信息 -->